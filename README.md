# BarthDoe team

Description of the files :

data : repository with the material provided for the competition
data_npy : repository that contains the bumpy arrays used for the best submission
predictions : cdv files of the two best predictions we made
creation_features.py : file which creates and saves the features and label in numpy arrays
prediction.py : file which makes the prediction from the numpy arrays saved by creation_features.py

If you want to test our codes you can either :

1 - First run "creation_features.py" to create the training and testing features from the original data in "data". Then, run "prediction.py" which makes a prediction with the features saved by creation_features.npy in data_npy. "prediction.py" writes the file predictions.csv)

2 - You can run directly "prediction.py" with the numpy arrays we provided in data_npy