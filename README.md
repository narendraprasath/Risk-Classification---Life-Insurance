

### Life Insurance - Risk Classification

It contains the following folder structure
	
	-> data - It contains training data
	-> model - It contains persistent model as pkl file format
	-> RestAPI - It contains the flask project. It sereves endpoint for testing
	-> Risk classification - LIC.ipynb - This is jupyter notebook. Also contains .html format for the same file.

### Risk classification - LIC.ipynb

1) Open the notebook in jupyter. It contains the entire ML pipeline available

Prerequisite:
	- Anaconda 3.5
	- Neccessary packages availabe in requirement.txt 

### RestAPI

It contains flask project.It runs on port 6020. 

The dataset for training and testing has been split using stratified fashion. The below endpoint takes the test data and predict the result.
Return the accuracy of test data

Endpoint:
	GET /training

Http Response:
	It return the Accuracy of test data. 

How to Run:
	python server.py
	


