# Pneumonia Detector

Project Submitted By,

Jeenath S,
CSE - Final Year
Bharathiyar Institute of Engineering for Women.

Live website on,
https://jeenath.herokuapp.com/pneumonia

## About

This webapp was developed using Flask Web Framework and was deployed on Heroku server. The models used to predict the diseases were trained on large Datasets. All the links for datasets and the python notebooks used for model creation are mentioned below in this readme. The webapp can predict following Diseases:


- Pneumonia

## Models with their Accuracy of Prediction

| Disease        | Type of Model            | Accuracy |
| -------------- | ------------------------ | -------- |
| Pneumonia      | Deep Learning Model(CNN) | 95%      |

## HOMEPAGE

![Screenshot (622)](https://user-images.githubusercontent.com/88899234/160613163-ffd5a6ae-d3fe-4ffc-8563-e4b4089662c3.png)

## TESTPAGE

![Screenshot (623)](https://user-images.githubusercontent.com/88899234/160613520-11c03201-84cb-4986-9a73-be072f78fa4e.png)

## PROJECT DEMO VIDEO


https://user-images.githubusercontent.com/88899234/161116804-21b48930-bd44-4f72-a5d2-24445a56beac.mp4


## NOTE

==> You can access the website live at:https://jeenath.herokuapp.com/pneumonia  <br>
==> Python version 3.6.15 was used for the whole project.<br>

## Steps to run this application in your system

1. Clone or download the repo.
2. Open command prompt in the downloaded folder.
3. Create a virtual environment

```
mkvirtualenv environment_name
```

4. Install all the dependencies:

```
pip install -r requirements.txt
```

5. Run the application

```
python app.py
```

## Dataset Links

All the datasets were used from kaggle.


- [Pneumonia Dataset](https://www.kaggle.com/paultimothymooney/chest-xray-pneumonia)
