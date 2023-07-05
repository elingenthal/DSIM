'50_speakers_audio_data' folder-> contains original dataset downloaded at: https://www.kaggle.com/datasets/vjcalling/speaker-recognition-audio-dataset


For both tasks (Identification and Verification) there's a folder following this workflow:

preprocessing.ipynb -> builds dataset that will be used for our ML models in a 'data' folder

feature_selection.ipynb -> selects features that will be used for ML

ML.ipynb -> creates train and test sets in the 'train_test_data_folder', applies validation on the choice of ML model and on the hyparameter tuning of the best models. Shows performances of final models and saves them

DL.ipynb -> trains a GRU neural network, shows its performances and saves the model