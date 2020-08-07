# Facial Expression Identification using Deep Learning

<p align="center">
  <a href="https://github.com/121yaseen/FacialExpressionIdentifier">
  </a>
![](banner-1.png)
## 📌 Introduction

This Machine Learning Web Application utilizes a  Convolutional Neural Network to process the  Images, detect and predict the facial Expression. The [Dataset](https://www.kaggle.com/msambare/fer2013) to process the Deep Learning Algorithm is taken from FER 2013 dataset from Kaggle. This trained model has 63% accuracy in Facial Expression Recognition. This application uses Haar Cascade Classifier for detecting the faces. 



## 🏁 Technology Stack

* [Keras](http://keras.io/)
* [Flask](https://github.com/pallets/flask)
* [HTML](https://www.w3.org/TR/html52/)

## 🏃‍♂️ Local Installation

1. Drop a ⭐ on the Github Repository. 
2. Clone the Repo by going to your local Git Client and pushing in the command: 

```sh
https://github.com/121yaseen/FacialExpressionIdentifier.git
```

3. Install the Packages: 
```sh
pip install -r requirements.txt
```

4. At last, push in the command:
```sh
python main.py
```

5. Go to ` http://127.0.0.1:5000/` and enjoy the application.

## 📋 Notes

- [ ] It uses webcam for video input default. You can predict on custom videos by changing the video source in camera.py
- [ ] Samples videos for prediction are available [Here](https://drive.google.com/drive/folders/17I1RoxStQrYCxwKHWEMbv2kOos6yQJBF?usp=sharing)
- [ ] Model has 63% accuracy which is not a state-of-the-art performance

## 📋 Further Changes to be Done

- [ ] Set up an HTML form to upload custom videos for prediction 
- [ ] Deploying the Web Application on Cloud.
- [ ] Development of an architecture using Pre-Trained Model like VGG16.
- [ ] Implementing the Model in PyTorch.
- [ ] Enhance the User-Interface using HTML/CSS.
- [ ] Set the Application on Docker.

## 📜 LICENSE

[MIT](https://github.com/121yaseen/FacialExpressionIdentifier/blob/master/LICENSE)
