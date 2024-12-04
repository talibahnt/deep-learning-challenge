# deep-learning-challenge


<img width="565" alt="Screenshot 2024-12-03 at 7 23 33 PM" src="https://github.com/user-attachments/assets/2b08730d-06a0-4aa8-82ff-c7706922a85e">

Table of Contents
Background	2
Setting up the environment and repo: GitHub	3
Preprocess the Data	3
Compile, Train and Evaluate the Model	4
Optimize the Model	5
Write a Report on the Neural Network Model	6
	Copy Files Into Your Repository/Results                                                                                7-15

![image](https://github.com/user-attachments/assets/a1b4ea77-60ca-4212-9f31-36db233e98c5)

Overview of the analysis: Explain the purpose of this analysis.
The nonprofit foundation Alphabet Soup wants a tool that can help it select the applicants for funding with the best chance of success in their ventures. With your knowledge of machine learning and neural networks, you’ll use the features in the provided dataset to create a binary classifier that can predict whether applicants will be successful if funded by Alphabet Soup.
From Alphabet Soup’s business team, you have received a CSV containing more than 34,000 organizations that have received funding from Alphabet Soup over the years. Within this dataset are a number of columns that capture metadata about each organization, such as:
•	EIN and NAME—Identification columns
•	APPLICATION_TYPE—Alphabet Soup application type
•	AFFILIATION—Affiliated sector of industry
•	CLASSIFICATION—Government organization classification
•	USE_CASE—Use case for funding
•	ORGANIZATION—Organization type
•	STATUS—Active status
•	INCOME_AMT—Income classification
•	SPECIAL_CONSIDERATIONS—Special considerations for application
•	ASK_AMT—Funding amount requested
•	IS_SUCCESSFUL—Was the money used effectively

![image](https://github.com/user-attachments/assets/35d24f5d-9edd-45c6-b522-d8f5b6224ba6)

Alphabet Soup Charity Optimization Case 1:

 <img width="493" alt="Screenshot 2024-12-03 at 7 33 16 PM" src="https://github.com/user-attachments/assets/3817a908-c41b-46dc-a81f-11ccb6d6176e">

Hidden Layers	2
Random State	30
Number of Neurons in First Layer	80
Number of Neurons in Second Layer	30
Activation Function for Hidden Layers	Relu
Activation Function for Output Layer	Sigmoid
Number of Epochs	100

<img width="446" alt="Screenshot 2024-12-03 at 7 34 38 PM" src="https://github.com/user-attachments/assets/7840598d-6470-497a-a014-99438d8ca6a7">

<img width="495" alt="Screenshot 2024-12-03 at 7 35 36 PM" src="https://github.com/user-attachments/assets/37d475ec-2724-4dde-8944-b94bda1e2cb0">


Summary:
 <img width="469" alt="Screenshot 2024-12-03 at 7 36 20 PM" src="https://github.com/user-attachments/assets/acfc21f4-cf78-4721-b9f9-81f8f7328831">


•	There are neurons between 30-80.
•	There are two hidden layers.
•	There are two activation layers: Relu and Sigmoid.
•	There are 100 Epochs.
•	There are graphs that demonstrate the loss and accuracy.
•	My models kept averaging between 72% to 73% for accuracy. My recommendation is to keep adding hidden layers and to use different activation functions other than Relu and Sigmoid. 

Alphabet Soup Charity Optimization Case 2:

 <img width="526" alt="Screenshot 2024-12-03 at 7 36 49 PM" src="https://github.com/user-attachments/assets/4937773b-9f71-49cb-9391-cf72d1830766">

Hidden Layers	4
Random State	42
Number of Neurons in First Layer	100
Number of Neurons in Second Layer	80
Number of Neurons in Second Layer	30
Number of Neurons in Second Layer	10
Activation Function for Hidden Layers	Relu
Activation Function for Output Layer	Sigmoid
Number of Epochs	100

 <img width="349" alt="Screenshot 2024-12-03 at 7 37 28 PM" src="https://github.com/user-attachments/assets/8178794e-6e57-4a01-a0e0-04eacbbe741c">

 <img width="511" alt="Screenshot 2024-12-03 at 7 37 59 PM" src="https://github.com/user-attachments/assets/b668ba6b-d06c-48e3-b4ed-3508c67df29c">

Summary:
 
<img width="468" alt="Screenshot 2024-12-03 at 7 38 51 PM" src="https://github.com/user-attachments/assets/fdb67d67-08b3-4e46-9f9a-6bd6aef43232">

•	There are neurons (hidden nodes) between 10-100.
•	There are four hidden layers.
•	There are two activation layers: Relu and Sigmoid.
•	There are 100 Epochs.
•	There are graphs that demonstrate the loss and accuracy.
•	My models kept averaging between 72% to 73% for accuracy. I added hidden layers and changed the random state. My recommendation is to keep adding hidden layers and to use different activation functions other than Relu and Sigmoid. Also, looking at another variable other than is successful.

Alphabet Soup Charity Optimization Case 3:
 <img width="466" alt="Screenshot 2024-12-03 at 7 39 35 PM" src="https://github.com/user-attachments/assets/19f5b695-fd72-4694-b561-31d37cf8b2a5">


Hidden Layers	3
Random State	42
Number of Neurons in First Layer	100
Number of Neurons in Second Layer	80
Number of Neurons in Third Layer	10
Activation Function for Hidden Layers	Relu
Activation Function for Output Layer	Sigmoid
Number of Epochs	100

 <img width="473" alt="Screenshot 2024-12-03 at 7 40 04 PM" src="https://github.com/user-attachments/assets/8e7747fc-9e23-491c-9178-81f209fd8799">

 <img width="489" alt="Screenshot 2024-12-03 at 7 40 33 PM" src="https://github.com/user-attachments/assets/9aef39c6-580f-4da5-b722-f143ac1da5b7">


Summary:

 <img width="465" alt="Screenshot 2024-12-03 at 7 40 52 PM" src="https://github.com/user-attachments/assets/4837af4e-7784-4e80-917e-f8156ad6349b">


•	There are neurons (hidden nodes) between 10-100.
•	There are three hidden layers.
•	There are two activation layers: Relu and Sigmoid.
•	There are 100 Epochs.
•	There are graphs that demonstrate the loss and accuracy.
•	Overall, my models kept averaging between 72% to 73% for accuracy. Alternated, the activation functions for the hidden and outer layers. I had only three hidden layers and changed the random state. My recommendation is to keep adding hidden layers and to use different activation functions other than Relu and Sigmoid. Also, looking at another variable other than is successful. Or dropping columns.
