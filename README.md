# Rap_Lyric_Generation_LSTM
Character and word level natural language generation models that generate lyrics in the style of different rappers using RNNs with LSTM layers.

## Motivation
This group project was completed for a Natural Language Processing class at The George Washington University.  Our group chose to use the concepts we learned in class to generate new rap lyrics by training RNNs on a rapper's corpus of lyrics.  

## Data Source
Our data we used to train our models came from Kaggle but the dataset has since been removed from the site.  We used lyrics by Drake to train the character and word models.  Our group also scraped additional lyrics from MetroLyrics.com but have yet to train any models with the scraped data.

##  Using the Files
- drake-songs.csv contains the training data for the character and word models.
- Generators folder contains a notebook for the character and word models.  These notebooks load the saved models and generate new lyrics for evaluation.  Inspect the predict_Character_Model.ipynb for model evaluation as well.
- Lyric_Scrape.ipynb contains a web scraper that can pull lyrics for any artist on MetroLyrics.com.
- Models folder contains the saved models that were trained on the drake-songs.csv data.
- Report.pdf is the write-up for the project.  Refer to this for context.
- Training folder contains the notebooks used for training the character and word models. 
