# NLP-Classification_Sentiment_Analysis-Sagemaker

## Project Overview. 
In this project, I build a classification model to analyze the sentiment of movie reviews. This model takes the data from 10,000+ IMDb movie reviews, to make predictions on new reviews that are handed to it. This model can also be used for other industry applications such as restaurant reviews, or auto repair shop reviews, etc. The processing for the NLP algorithm can be specifically tuned to analyze the sentiment of any type of review. I also built a lambda function within AWS environment, and an API gateway inside of AWS to allow this model to be fully production ready. I was able to send my friends and family a website link, where they could type in a review, and instantly be delivered the prediction of whether their review was mostly positive, or mostly negative from this model.

This was a very fun project, I enjoyed it very much! And I hope you do too :-)

Link to IMDB Dataset:
http://ai.stanford.edu/~amaas/data/sentiment/

### Files in this repository and their purpose
Main Notebook.ipynb - JupyterNotebook containing all code used in project

   Project Notebook.ipybn - A presentation of all steps taken in Main Notebook, in detail.

   predict.py - File holding the deployment setup for pytorch model
   
   model.py - File holding the pytorch model parameters

   train.py - File holding the pytorch model training parameters

   index.html - HTML file with simple GUI and web address connecting to AWS REST API key

   LICENSE - MIT license for this project

   README - this file


### Main Notebook uses Python 3.6, and the following libraries
   Pandas

   Matplotlib

   SKlearn

   Numpy
