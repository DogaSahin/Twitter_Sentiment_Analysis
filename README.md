# Tweet Sentiment Polarization

## Table of Contents

1. [General Info](#general-info)
2. [Requirements](#requirements)
3. [Dataset](#dataset)
4. [Author](#author)

### General Info

The purpose of this project is to classify tweets about the covid-19 pandemic as emotionally positive or negative. All codes are written in python notebook format. 
- Get_Tweets: In this notebook, there are codes that convert the desired amount of tweets into pandas dataframe format, using the desired keywords from Twitter, and cleaning them with NLP techniques and performing the classification process.
- main: This notebook contains codes for LSTM model training and making predictions on the dataset we got from the Get_Tweets notebook.

### Requirements

Ensure you have met the following requirements:
- Python == 3
- numpy == 1.18
- pandas == 1.1
- tensorflow == 1.x
- keras == 2.4
- nltk == 3.5

To install the python library:
```bash
pip install name_of_library
```

**note** : This project works in the tensorflow 1.x versions. You must check the version if you dont want to face errors.

### Dataset
To evaluate the model you must download a speicic dataset mentioned in the link below.
- [Sentiment140 dataset with 1.6 million tweets](https://www.kaggle.com/kazanova/sentiment140)

### Author

- [DogaSahin](https://github.com/DogaSahin) on GitHub
- [Doğa Şahin](https://www.linkedin.com/in/do%C4%9Fa-%C5%9Fahin/) on LinkedIn
