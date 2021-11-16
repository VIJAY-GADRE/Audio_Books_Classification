# Audio_Books_Classification

## Action Plan
- Prepare the data and preprocess it. (Create training, validation, and testing dataset)
- Outline the Model and choose the activation function.
- Set the appropriate advanced optimizers and the loss functions.
- Make the model learn. (Backpropagation)
- Test the accuracy of the model.

## Algorithm
### 1) Import the relevant libraries.

### 2) Preprocess the Data.
- i. Load the dataset
- ii. Balance the dataset according to priority
- iii. Standardize the Inputs
- iv. Shuffle the inputs
- v. Split the dataset into training, validation, and testing
- vi. Save the dataset in .npz file

### 3) Model Oulining (Feed-Forward NN)
- i. Load the .npz files and extract the inputs and targets 
- ii. Declare the size for input, output and hidden layers
- iii.. Create a Sequential Model with 3 hidden layers
- iv. Optimize the algorithm
- v. Fit the model on the training data (make the model learn)
- vi. Test the model.


##### NOTE:- The Model has been tested on Mac M1 (Metal)
