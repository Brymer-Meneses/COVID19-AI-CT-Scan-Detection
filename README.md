# COVID19-AI-CT-Scan-Detection

The model used by this application is a fine-tuned EfficientNet-Lite4 Model provided by TensorFlow Hub making it fast to run on mobile devices. 
I have trained this model for a total of 12789 images from the following datasets below achieving a testing accuracy of 97.32%. For more information you can look at the
raw code from '/Machine Learning Files/'.

Here is the confusion matrix that came from the evaluation of the model on the testing dataset.
![Confusion_Matrix](/images/confusion_matrix.png)

0 - covid-19 detected
    The model detects covid-19 infection
1 - covid-19 undetected 
    The model detects no signs of covid-19 infection
2 - non-informative
    The model detects an image that cannot be used to detect covid-19 infection


# Datasets used

Dataset1 -> https://github.com/mr7495/COVID-CTset

Dataset2 -> https://www.kaggle.com/azaemon/preprocessed-ct-scans-for-covid19

# Disclaimer:

The A.I. model used to run this application hasn't been tested on 'real world data' but only on open anonymized datasets online. Please bear this in mind when using this application.


# Screenshots
![covid_detection](/images/covid_infected.png)
![non_covid_detection](/images/covid_not_infected.png)
![non_informative](/images/not_informative.png)


