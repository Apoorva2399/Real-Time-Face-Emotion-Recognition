# Real-Time-Face-Emotion-Recogniton Using Transfer Learning

Transfer learning is a  research problem in machine learning model that focuses on storing knowledge gained while solving a problem and applies it to another problem of similar kind. It offers better starting point and improves the model performance when applied on second task.
 
 In this Model 'MobileNet' Transfer-Learning is used, along with computer vision for Real time face emotion recognition through webcam, so based on these a streamlit app is created which is deployed on Heroku cloud platform.
The model is trained on the dataset 'FER-13 cleaned dataset', which had five emotion categories namely 'Happy', 'Sad', 'Neutral','Angry' and 'Disgust' in which all the images were 48x48 pixel grayscale images of face.

 Since, there was an soft limit size of 300MB on heroku colud platform to perfectly deploy and run the model through app. My model size was around 438MB because of which i can only deploy the app but couldn't run perfectly. So this can be solved by providing some more extra space or by further reducing the slug size of model if possible.

# Dependencies
* Tensorlow
* Keras
* MobileNet
* Opencv
* Streamlit


# Setup
## You need  the Following:
Python and the following packages:
* OpenCV 
* Keras (with Tensorflow backend)
* Tensorflow
* Numpy
* pandas
* Matplotlib
* sklearn

# Try it out:
* prepare data
* train model
* test it
     * dataset -- https://www.kaggle.com/gauravsharma99/fer13-cleaned-dataset
     * Transfer-Learning Model -- https://github.com/Apoorva2399/Real-Time-Face-Emotion-Recogniton/blob/main/facial-emotion.ipynb
     * Real time face emotion recognition through webcam -- https://github.com/Apoorva2399/Real-Time-Face-Emotion-Recogniton/blob/main/Real%20Time%20Face%20Emotion%20Detection.ipynb
     * Run on streamlit app -- https://github.com/Apoorva2399/Real-Time-Face-Emotion-Recogniton/blob/main/app.py
* deploy Your app    

# Here is my deployed app link :
  * https://real-time-emotion-recognition.herokuapp.com/



