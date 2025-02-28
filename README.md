# NER_image_classification
First of all, you should install the requirements

   $ pip install -r requirements.txt

## Task 1 - Image classification + OOP
In the first task I used MNIST dataset and built 3 classification models around it.

Here is some Exploratory Data Analysis:

![image](https://github.com/user-attachments/assets/7b3b17ba-2a70-47de-8b9e-5fd0d4ccff2f)
![image](https://github.com/user-attachments/assets/c0d114c0-01a2-47e5-bb45-c089f80f3052)
![image](https://github.com/user-attachments/assets/6d9a6cc0-0e0f-42b9-8e08-c155bcd654ad)
![image](https://github.com/user-attachments/assets/f79f71af-dc74-43ff-803a-b1ed4e9ca250)

### Model Performance Summary

1. Random Forest
   
- Used Grid Search to find the optimal hyperparameters.
- Achieved 96.26% accuracy on the test data.

2. Feed-Forward Neural Network (FFNN)

- Applied a train/validation loss approach to fine-tune hyperparameters.
- Achieved 97.95% accuracy on the test data.

3. Convolutional Neural Network (CNN)

- Applied a train/validation loss approach to fine-tune hyperparameters.
- Achieved 98.91% accuracy on the test data.

## Task 2 - Named entity recognition + image classification 
   
   
