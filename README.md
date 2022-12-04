# README

This is a repository for Rosanna Luo's capstone project for Brainstation.

The work here is for creating a way for landlords to set a good rental price for their rental property in NYC as well as learn more about the NYC rental market.

## Files

See these files for information on the project

### Data

Data is too large to be hosted in github, so it is hosted in google drive

The original data set is here:
data/renthopNYC.csv: https://drive.google.com/file/d/1Chq6XkMH-6Xua8pUeyzDCu5tu8W6OmC-/view?usp=sharing

We have data at intermediate stages throughout development

Prior to any training but after some data cleaning, we have:
data/clean_rent_data_pre_description.csv: https://drive.google.com/file/d/1B8OM0oz_0wARnqNTk05jvLK7cFSEKhTO/view?usp=sharing

After some basic cleaning that involves using a validation set, we have split up the training and test data into the files:
- data/clean_rent_data_post_desc_train.csv: https://drive.google.com/file/d/17SKOItV8GOd5zRA5C4VIAaJ9ipY0oyV0/view?usp=sharing
- data/clean_rent_data_post_desc_test.csv: https://drive.google.com/file/d/1jOysAYOBN13mOs0ky4ENHhPLM2_tCMlv/view?usp=sharing

### Jupyter Notebooks

There are two Jupyter notebooks. Both have information on the logic behind the steps and analysis of the results.

NYCRentalPriceCalculatorData.ipynb is primarily for loading, cleaning, augmenting and exploring the data.

NYCRentalPriceCalculatorModel.ipynb is for creating the models. There is also some data cleaning here due to the nature of the exploration of models resulting in needing to clean the data further.

### Models

The most performative model is stored via a pickle file at nyc_rental_price.pkl

### Executive Summary

An executive summary of the capstone project is available at NYCRentPriceExecSummary.pdf