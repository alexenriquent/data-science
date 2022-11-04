# Data Science Projects
This repository provides a high-level overview of data science projects I have worked on for both academic and self-learning purposes. Links are included for projects whose source code can be made public.
## Publications
### [Identifying Risk Factors for Heart Disease in Electronic Medical Records: A Deep Learning Approach](https://aclanthology.org/W18-2303/)
This research investigates the applications of deep learning for identifying risk factors for heart disease in electronic medical records  and develop a clinical information extraction model based on the investigation result. The main task is to determine clinical evidence contained in each patients medical record, which indicates the presence of diseases (coronary artery disease and diabetes) and relevant risk factors (hyperlipidaemia, hypertension, obesity status, smoking status, family history, etc).
## Text
### [Document Type Classification](https://github.com/alexenriquent/document-classification)
This proof-of-concept is an attempt to demonstrate an end-to-end pipeline for document type classification using a deep feedforward neural network. The labels to predict include "agenda", "medical record", "paper" and "resume". Apart from training and saving the model locally, this project also includes an implementation for an alternative scenario where Azure Machine Learning is used to manage the machine learning life cycle.
### [Service Request Classification](https://github.com/alexenriquent/sr-classification)
In a ticketing system where users can send emails to initiate service requests, there may be multiple junk tickets or tickets with no actions required coming in that need to be manually filtered out and closed. This project is an attempt to automate this filtering process using a deep neural network as the classification model and Flask for local deployment. Essentially, it is a binary classification problem to evaluate the validity of each service request.
## Audio
### [Music Generation](https://github.com/alexenriquent/music-generation)
This project is an attempt to tackle the task of music generation using a Recurrent Neural Network with Long Short-Term Memory (LSTM) trained on the MAESTRO data with the help of TensorFlow and Keras deep learning frameworks for model development.
### [Music Genre Classification](https://github.com/alexenriquent/music-genre-classification)
This project focuses on techniques for extracting features from audio data using the the Librosa library. The extracted features will then be used to train a music genre classifier implemented in Tensorflow. The GTZAN dataset used in this project contains 10 classes, each class with a 100 of different 30 seconds audio files. The classes include blues, classical, country, disco, hip-hop, jazz, metal, pop, reggae and rock.
## Structured Data
### [Movie Recommender](https://github.com/alexenriquent/movie-recommender)
This project uses [TensorFlow Datasets (TFDS)](https://www.tensorflow.org/datasets) and the [TensorFlow Recommenders library (TFRS)](https://www.tensorflow.org/recommenders) with an addition of deep nueral network layers to create a movie recommender system that can better capture more of the complex patterns of information that are present and increase the ease of how new information in the form of further data feature columns are added.
## Data Mining
### [Speed Dating Experiment](https://github.com/alexenriquent/speed-dating-experiment)
What influences love at first sight? (Or, at least, love in the first four minutes?) This project applies a series of data mining techniques to the Speed Dating Experiment dataset compiled by Columbia Business School professors Ray Fisman and Sheena Iyengar for their paper [Gender Differences in Mate Selection: Evidence From a Speed Dating Experiment](https://doi.org/10.7916/D8FB585Z). The objective is to analyse dating behaviour and decision making factors based on participants' personal attributes and their interactions with potential partners.
## Data Exploration and Analysis
* [Analysing CIA Factbook Data Using SQLite](https://github.com/alexenriquent/dataquest/tree/master/facebook) - Analysing a compendium of statistics about all of the countries on Earth, which contains demographic information such as the population as of 2015, the annual population growth rate, the total land and water area, etc.
* [Analysing NYC High School Data](https://github.com/alexenriquent/dataquest/tree/master/schools) - Analysing the data on New York City high school SAT scores as well as the demographics for each high school combined with other related information, such as graduation outcomes, Advanced Placement (AP) test results, etc.
* [Analysing Thanksgiving Dinner](https://github.com/alexenriquent/dataquest/tree/master/thanksgiving) - Analysing the dataset containing 1,058 responses to an online survey about what Americans eat for Thanksgiving dinner. Each survey respondent was asked questions about what they typically eat for Thanksgiving, along with some demographic questions, such as their gender, income, and location. 
* [Answering Business Questions using SQL](https://github.com/alexenriquent/dataquest/tree/master/chinook) - Analysing the Chinook database (available for SQL Server, Oracle, MySQL, etc.) containing information about a fictional digital music shop, including the artists, songs, and albums from the music shop, as well as information on the shop's employees, customers, and the customers' purchases.
* [Finding the Best Markets to Advertise in an E-learning Product](https://github.com/alexenriquent/dataquest/tree/master/new-coders) - Analysing the New Coders survey by FreeCodeCamp, which contains information on how thousands of people all around the world are learning to code, and why they are choosing to do so. The objective is to determine best markets to advertise an e-learning product.
* [Investigating Fandango's Movie Rating System](https://github.com/alexenriquent/dataquest/tree/master/fandango) - In October 2015, a data journalist named Walt Hickey analysed movie ratings data and found strong evidence to suggest that Fandango's rating system was biased and dishonest. This project analyses more recent movie ratings data to determine whether there has been any change in Fandango's rating system after Hickey's analysis.
* [Kaggle Workflow](https://github.com/alexenriquent/dataquest/tree/master/kaggle) - Exploring the data science workflow from ingesting and preprocessing data, exploring data, engineering new features, selecting models through to making a submission to Kaggle.
* [Predicting Bike Rentals](https://github.com/alexenriquent/dataquest/tree/master/bike-rentals) - Analysing detailed data on the number of bicycles people rent by the hour and day in Washington, D.C. and predicting the total number of bike rentals (casual + registered) using the linear regressing, decision tree and random forest algorithms.
* [Predicting Car Prices](https://github.com/alexenriquent/dataquest/tree/master/car-prices) - Predicting car prices with k-nearest neighbour regression trained on the dataset containing information about the technical aspects of the vehicle such as the motor's displacement, the weight of the car, the miles per gallon, how fast the car accelerates, and more.
* [Predicting House Sale Prices](https://github.com/alexenriquent/dataquest/tree/master/housing) - Predicting house sale prices using the linear regression algorithm trained on the Ames Housing dataset, which describes the sale of individual residential property in Ames, Iowa from 2006 to 2010. It contains 2930 observations and a large number of explanatory variables involved in assessing home values.
* [Predicting the Stock Market](https://github.com/alexenriquent/dataquest/tree/master/stock-market) - Predicting future stock prices using the linear regression algorithm trained on historical data on the price of the S&P500 Index.
* [Star Wars Survey](https://github.com/alexenriquent/dataquest/tree/master/star-wars) - Exploring and analysing the Star Wars survey dataset containing demographic information as well as answers to the Star Wars film franchise-related questions.
* [Visualising Earnings Based On College Majors](https://github.com/alexenriquent/dataquest/tree/master/college-majors) - Visualising the recent grad student data from the College Majors dataset (originally from the American Community Survey 2010-2012 Public Use Microdata Series).
* [Visualising Gender Gap Across All College Degrees](https://github.com/alexenriquent/dataquest/tree/master/gender-gap) - Visualising the dataset containing the percentage of bachelor's degrees granted to women from 1970 to 2012 compiled and released by the Department of Education Statistics. The dataset is broken up into 17 categories of degrees, with each column as a separate category.
* [Winning Jeopardy](https://github.com/alexenriquent/dataquest/tree/master/jeopardy) -Exploring and analysing a dataset of 20,000 Jeopardy questions to figure out some patterns in the questions that could help a participant win.
