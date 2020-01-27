*****************************README*******************************

STEP 1:
Install all these python modules before running the code:
numpy, pandas, pickle

***************************TRAINING*******************************
STEP 2:
Define the path of the corpuses. 

STEP 3:
Enter the number of sentences to train the model on, by default it is set as 50000 but you can change it.

STEP 4:
Run the blocks of code sequentially

STEP 5:
While training the models you can train using convergence criteria as well as with fixed number of iterations(10)
Uncomment "while redo" before calling the "train_IBM1" and "train_IBM2" functions to use the convergence criteria instead of fixed number of iterations
10 iterations was observed to generally converge and hereafter changes were not prominent

STEP 6:
Trained Models of both IBM Model 1 and IBM Model 2 are saved in the path given by "result_path".
Prompt will be generated to enter the name with which you want to save the mapping of the trained results which will be used while testing.

***********************TESTING*************************************

STEP 7:
Load the translations which you have saved earlier.

STEP 8:
Now, enter the name of the doc which you want to get translated.

STEP 9:
Jaccard Coefficient and Cosine Similarity are stored in the file named 'resultdoc.txt'
Translated sentences are saved to the file named 'output.txt'