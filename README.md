# DeepLearning-Challenge

Alphabet Soup: Deep Learning Model Report
Overview of the Analysis
The purpose of this analysis was to build and evaluate a deep learning model that predicts whether nonprofit organizations will be successful in receiving funding from Alphabet Soup. Using a dataset with information on past applications, I created a binary classification model to help identify which organizations are most likely to succeed. This kind of analysis can assist in making more informed decisions about how funding is distributed.

To do this, I used TensorFlow and Keras to build a neural network model. After cleaning the data and preparing it for training, I tested different model structures to try and reach the target performance accuracy of 75%.

Results
Data Preprocessing
Target Variable:
The column used as the target for prediction was IS_SUCCESSFUL, which indicates whether a funding application was approved or not.

Feature Variables:
The features used in the model were all remaining columns in the dataset after cleaning, including categorical fields that were converted to numeric format using pd.get_dummies. These include APPLICATION_TYPE, AFFILIATION, INCOME_AMT, and others.

Removed Variables:
I removed columns like EIN and NAME because they serve as unique identifiers and don't provide helpful information for training the model.

Compiling, Training, and Evaluating the Model
Model Architecture:
The neural network included three layers:

A first hidden layer with 100 neurons using ReLU activation

A second hidden layer with 60 neurons and ReLU activation

A third hidden layer with 30 neurons and ReLU activation

A final output layer with 1 neuron and a sigmoid activation, which is used for binary classification

Model Performance:
The final model reached approximately 73% accuracy. While it didn’t fully meet the 75% target, it performed consistently and showed strong results during training.

Performance Improvements:
To improve performance, I increased the number of layers and neurons and made sure the input data was fully preprocessed. This included removing less useful columns and converting categorical values into numerical format.

Summary and Recommendation
Overall, the model was successful in learning from the data and predicting which applications were most likely to succeed, reaching close to the performance goal. The project showed how preprocessing and thoughtful model design can lead to meaningful results, even when working with complex data.

To continue improving, I would consider learning about and testing other machine learning techniques in the future, like decision trees or other classification models. These could potentially provide even better accuracy or be easier to explain to others. For now, this project was a valuable experience in building a neural network and understanding how to prepare and train data in a deep learning environment.

![image](https://github.com/user-attachments/assets/12997fd1-b8c2-4d83-af66-0b1b36dcd3a9)
![image](https://github.com/user-attachments/assets/3c0b13bd-77dd-44e5-ad8c-bed05d1177fb)
![image](https://github.com/user-attachments/assets/b82a1d0b-3446-4965-be1f-4a863fab6c92)
