# MNIST-Handwritten Digit-Classification using ANN 

## For this assignment, I have worked on the MNIST database. The MNIST data is a database of handwritten digits from 0 to 9. The database contains 60,000 28x28 grayscale images of the 10 digits, along with a test set of 10,000 images. I have created an ANN model for identifying the digit from the handwritten images.

## Steps :
1. Loading the database to variable named digit_mnist using the Keras inbuilt datasets

2. Import data to create X_train_full, y_train_full, X_test and y_test variables

3. Normalize the data

4. Create a validation set of 6000 images

5. Create an ANN model with two dense layers of 200 and 100 neurons

6. Compile and train the model for 60 epochs

7. Plot the loss and accuracy against epoch

8. Evaluate the model accuracy on the test dataset

9. Predict the digit for the first 5 records of the test dataset

10. Comparison of Test data and classified output.

![image](https://user-images.githubusercontent.com/85127724/146087043-e1856b87-ace7-4b3a-b980-d35ac12051d4.png)

![image](https://user-images.githubusercontent.com/85127724/145874599-4da6e47e-b96b-4361-9b85-7394a7203377.png)

Digits classified for the same data points :  [7 2 1 0 4]
