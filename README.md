# TED-Talks-Views-Prediction

# Objective: 
The main objective is to build a predictive model, which could help in predicting the views of the videos uploaded on the TEDx website.

# Dataset Information:

Number of records: 4005

Number of attributes: 19

# Feature Information:

talk_id: A unique identifier for each TED Talk video.

title: The title of the talk.

speaker_1: The primary speaker for the talk.

all_speakers: A list of all the speakers for the talk.

occupations: The occupations of the speakers.

about_speakers: Information about the speakers, such as their backgrounds and expertise.

views: The number of views the video has received.

recorded_date: The date the talk was recorded.

published_date: The date the talk was published on the TED Talks YouTube channel.

event: The name of the TED event where the talk was given.

native_lang: The language the talk was given in.

available_lang: The languages the talk is available in.

duration: The length of the video.(in sec.)

topics: The topics covered in the talk.

related talks: Other TED Talks that are related to this talk.

url: The URL of the video.

description: A brief description of the talk.

transcript: A transcript of the talk.

Target Variable: Views(The number of views the video has received.)

# Project Work Flow

Importing Libraries

Loading the Dataset

Data Cleaning

EDA & Feature Engineering

Feature selection

Fitting the regression models and HyperParameter Tuning

Final selection of the model

# Technical Details

Worked on various regression models like Linear regression, Ridge regression, Lasso regression, Decision Tree, Random Forest, Gradient Boosting and XGBoost.

# Conclusion

Random Forest regression model works exceptionally well in achieving the target.
