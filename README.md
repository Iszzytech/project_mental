# About the Project
Depression detection using audio files in Python using Convolutional Neural Networks (CNN) and the DAIC-WOZ dataset is a project that aims to detect depression in individuals based on their speech patterns. The DAIC-WOZ dataset is a collection of audio and video recordings of interviews between patients and mental health professionals.

The project begins by pre-processing the audio files to extract relevant features, such as pitch, energy, and formants. The pre-processed features are then used to train a CNN model using Keras and TensorFlow. The model includes several layers of convolutional, pooling, and dense layers, with activation functions and regularization techniques applied to prevent overfitting.

Once the model is trained, it is used to predict the depression levels of individuals based on their speech patterns. The project includes a user interface where users can record an audio, and the model will predict their depression level.

Overall, this project demonstrates the effectiveness of CNNs in accurately detecting depression in individuals based on their speech patterns. The use of the DAIC-WOZ dataset provides a large and diverse set of audio recordings that can be used to train and test the model, and the user interface makes it easy for individuals to receive an initial assessment of their depression level.

# How to Setup the Project
1. First you need python installed use version 3.8.5 or 3.9.13 to avoid compatibility issues
2. CD into 'working-directory'
3. Create a virtual env and activate
4. Run the code "pip install -r requirements.txt"
5. If all went smoothly execute the code "flask run"
6. If you have multiple python version simply use this code to create a virtual env on windows OS  

    "python -m virtualenv -p 'installed-python-version-path'\python.exe myenv"
7. Majorly the default path is located in "c:\users\pc-name\AppData\Local\Programs\Python" the you'll add \python.exe 
8. Incase you can't find AppData on your windows topbar click views -> show/hide -> allow hidden files.  
    
Thanks.
