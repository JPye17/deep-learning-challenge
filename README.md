# Enhanced Deep Learning Model Performance: Adjusted to Match Notebook

The nonprofit foundation Alphabet Soup wants a tool that can help it select the applicants for funding with the best chance of success in their ventures. With your knowledge of machine learning and neural networks, you’ll use the features in the provided dataset to create a binary classifier that can predict whether applicants will be successful if funded by Alphabet Soup.

Preprocess the data:
* The target variable for the model is IS_SUCCESSFUL.
* The feature variables for the model include APPLICATION_TYPE, AFFILIATION, CLASSIFICATION, USE_CASE, ORGANIZATION, STATUS, INCOME_AMT, SPECIAL_CONSIDERATIONS, and ASK_AMT.
* The EIN and NAME columns were removed from the input data as they are identification columns and not useful as features or targets.

Compile, Train, and Evaluate the Model
The model consists of three hidden layers with 80, 30, and 1 neurons, respectively, and ReLU activation functions. The output layer uses a sigmoid activation function for binary classification. The structure was chosen to provide a balance between complexity and the potential for overfitting, while maintaining the ability to learn complex patterns in the data.

Optimize the Model

The iniatial test show an accuracy of 73-74% which is below desired. 

Summary:

The deep learning model did not initially achieve the desired output of above 75%. Although, there can be further analysis to achieve better results. Such as dropping irrelevant columns, adjusting values for each bin, adding/removing hidden layers, adding more neurons to a hidden layver, and increasing/decreasing the number of epochs in the training. 
