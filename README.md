# MPI Parallel QuickSort


The project has 4 jobscript files:

	jobscript1  is for running the project in sequential mode
	jobscript2  is for running in parralel on 2 processors
	jobscript4  is for running in parralel on 4 processors
	jobscript8  is for running in parralel on 8 processors
	jobscript16 is for running in parralel on 16 processors

Project has two model for pivot selection:

	model 1 is for random pivot selection
	model 2 is for median pivot selection
	
The default mode for pivot selection is model 1

in order to change the model you can go to line 44 of Quick.c and change the variable model to 2.
	
number of elements is set to 1024 (you can change it to 1,048,576). Max value for the numbers is 100 (it can change to any value but the running time will go higher)

The output files show the result of final array and also running time of each individual processors.

