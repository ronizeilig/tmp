readme.md

This short readme file explains how to run the CLI application that prints the numbers from 1 to 10 in a random order to the terminal.

Files included with this project:
	RandomPrint.sh
(The CLI application is written inside the included file named- "RandomPrint.sh")

In order to execute this file in a Linux or MacOS system:
	1. open the Linux/MacOS terminal 
	2. download the RandomPrint.sh file to your place of choice, 
		for example- /home/tmp
	3. navigate to the RandomPrint.sh file location using the cd command, 
		for example- cd /home/tmp
	4. make the file executable by executing the following command- chmod +x RandomPrint.sh
	4. execute the application by running the following command- . [SH_FILE_LOCATION]/RandomPrint.sh
		in the example above, in which the RandomPrint.sh was downloaded to path home/tmp the command to execute should be:
		. /home/tmp/RandomPrint.sh
	the outcome of this command will be displayed in the terminal horizontally, for example- 5 2 10 6 9 3 4 8 1 7
