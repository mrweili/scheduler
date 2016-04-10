#Interview Scheduler

### HOW TO USE: 

#### 1. Running the code with given sample data:

	- Go to the location of the source files in cmd/terminal
	- Run the command
	``````````````````````````````````````````````````````
		python3 test_sample_data.py
	``````````````````````````````````````````````````````
	- Follow the message in the console.


#### 2. Running the code in interaction mode:
	In this mode you have a change to choose which data files you want to read.


	** IMPORTANT **
		Whenver run the program in interaction mode, please read data files in set. 
	That is, if you generated a set of data files called random_data_xx_4.csv (a set will includes locations,
	profs and students files), you have to read the files that is in the same set, ending with same number. 
	Or the program will crash.

		If you mix data together, the program will not find the preferred profs in the profs list, hence terminates.

	** IMPORTANT **
		Please read Distance-Sample.csv while running the set of data generated by generator.

	- Go to the location of the source files in cmd/terminal
	- Run the command
	``````````````````````````````````````````````````````
		python3 scheduler.py
	``````````````````````````````````````````````````````
	- Follow the message in the console.

	Note: 
		There are already sets of data in the repo /data. 
	There are locations, students, profs, and distance .csv files located in the repo that named accordingly. 


#### 3. If you want to generate some random data:

	- Change to the location of the source files in cmd/terminal
	- Run the command
	``````````````````````````````````````````````````````
		python3 sample_generator.py
	``````````````````````````````````````````````````````
	- Follow the message in the console.

	Note: 
		sample_generator.py only generates a set of solvable but random data. 
		The purpose of sample_generator.py is to give a large amount of data for testing. 

	Note’: 
		the sets of data generated by sample_generator.py is based on the data in the repo /data/generate/source, 
	so if you want to run the set of data generated by the program, 
	please load Distance-Sample.csv( it contains the distance between pair of loactions).



NOTE: The version of Python we are using for the project is 3.4.3


