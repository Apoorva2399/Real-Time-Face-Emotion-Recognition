# Real-Time-Face-Emotion-Recognition Using Transfer Learning
 Here we have created the models which recognises the real time emotion of person in frame. So basically its a team project done by me and my friend Md Sarfaraz Iqbal.Here is model trained by me using Transfer Learning. 

Transfer learning is a  research problem in machine learning model that focuses on storing knowledge gained while solving a problem and applies it to another problem of similar kind. It offers better starting point and improves the model performance when applied on second task.

![transfer_learning](https://user-images.githubusercontent.com/81186352/117619020-613f2c80-b18c-11eb-845a-7396b80aa5ff.jpg)
 
 In this Model 'MobileNet' Transfer-Learning is used, along with computer vision for Real time face emotion recognition through webcam, so based on these a streamlit app is created which is deployed on Heroku cloud platform.
The model is trained on the dataset 'FER-13 cleaned dataset', which had five emotion categories namely 'Happy', 'Sad', 'Neutral','Angry' and 'Disgust' in which all the images were 48x48 pixel grayscale images of face.

 Since there was an soft limit size of 300MB on heroku colud platform to perfectly deploy and run the model through app. My model size was around 438MB because of which i can only deploy the app but couldn't run perfectly. So this can be solved by providing some more extra space or by further reducing the slug size of model if possible.
 
 Since my model gave application error after deployment because of slug size, my team-mate have trained a model using CNN which gave an accuracy of 66.47% for train data, and 58.19% on test data at 42nd epoc.and we deployed this model on heroku cloud platform where slug size was around 413MB, which successfully deployed and app is facing issue in boot time.

Here is link of CNN model -- https://github.com/sarfaraziqbal/face-emotion-recognition-cnn

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



