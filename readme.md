# TERMINATE BASH SCRIPT USAGE GUID

## Description
-This script is designed to stop process just like the "kill -9" unix command, in fact this uses it under the hood, but this tool give the user more power by just providing the name of the process andnot be obliged to go and search for each p-id related to it and kill then one after the other


## Benefits of terminate
1- Easy to use.
2- More user power.
3- Modular.
4- Time gain  compared to the unix kill command.


## Usage:
	terminate <name_of_the_process>.
	
	:stdout: killed
	:sterr : it depends on whatever the problem cause is.	

Exemples:
	
	terminate firefox

explaination: this will get all the processes related to firefox in your machine, and kill them.
	      so all you firefox windows will be shutdown.



## License: MIT.




