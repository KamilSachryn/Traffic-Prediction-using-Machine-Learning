# LookBeforeYouLeap

Leveraging predictive ML models to improve Automotive Safety and Travel Time through Twitter Sentiment Analysis and Traffic Record feature selection
Authors:  Hannah Do,  Kamil Sachryn           


- Retrieval of tweets through Snscape, Tweepy, and geocoding through ArcGIS
- Text processing through various NLP processing and Vader methods (sentiment analysis)
- Collection of accident record and feature selection

- Integration of twitter features into traffic accident records - merging the two datasets based on the distance between instances
- SMOTE and random instance generation for balancing the class

- ML predictions and evaluation (processed files are in 'merged' folder)

### Installation

The model requires the following libraries and programs

 - `python3`
 - `Jupyter Notebook`
 - `numpy`
 - `pandas` 
 - `matplotlib`
 - `seaborn` 
 - `sklearn`
 - `xgboost`


### Usage

The model is designed to be used within Jupyter Notebook, and requires it to run. 

Once started the checkpoint can be used to view a set of possible results, or can be re-run to generate and test a new model with the same or altered parameters. 

### Dataset

The dataset can be changed within the `data_traffic` and `data_twitter` folders with the users own data. 
