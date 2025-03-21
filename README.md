Importing Libraries:-
Loaded essential libraries for image processing (Pillow), data handling (NumPy) and machine learning (scikit-learn)

Dataset Loading and Preprocessing:-
•	Defined paths for the cats and dogs image folders
•	Resized images to 64x64 pixels, converted them to grayscale and flattened them into vectors

Combining the Dataset:-
Merged the cat and dog images into a single feature matrix X and combined the labels into y

Train-Test Split:- 
Split the dataset into 80% training and 20% testing sets

Model Training:- 
Trained an SVM classifier with a linear kernel on the training set

Model Evaluation:-
•	Made predictions on the test set
•	Calculated accuracy and displayed a classification report

Visualization:- 
Displayed 10 test images along with the model's predictions
