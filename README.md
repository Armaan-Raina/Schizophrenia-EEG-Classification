# Schizophrenia-EEG-Classification
This was a personal project I completed to help immerse myself in the world of EEG processing and where that intersects machine learning. 
I found a dataset online (https://repod.icm.edu.pl/dataset.xhtml?persistentId=doi:10.18150/repod.0107441) that contained EEG samples from 
14 schizophrenic patients and 14 control (healthy) subjects. I preprocessed the data using the MNE library in Python, visualized it, performed an ICA to remove artifacts from eye movement, extracted features by computing band power, and trained a Scikit-learn Random Forest Classifier to 97% accuracy to classify healthy and schizophrenic features. 
