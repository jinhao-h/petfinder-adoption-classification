Based on the Kaggle Competition https://www.kaggle.com/c/petfinder-adoption-prediction/
NOTE: This project was also used as part of a term-long group assignment for COMP9417 - Machine Learning.

# Kaggle Competition - PetFinder Adoption Classification/Prediction

Group members: Kurt Wang, Min Jung Son, Jinhao Huang, Victor Tsang

[PetFinder.my Adoption Prediction](https://www.kaggle.com/c/petfinder-adoption-prediction/)

## PetFinder.my Adoption Prediction

PetFinder.my has been Malaysia’s leading animal welfare platform since 2008, with a database of more than 150,000 animals. PetFinder collaborates closely with animal lovers, media, corporations, and global organizations to improve animal welfare.

Animal adoption rates are strongly correlated to the metadata associated with their online profiles, such as descriptive text and photo characteristics. As one example, PetFinder is currently experimenting with a simple AI tool called the Cuteness Meter, which ranks how cute a pet is based on qualities present in their photos.

**In this competition you will be developing algorithms to predict the adoptability of pets - specifically, how quickly is a pet adopted?**

More details found here: [https://www.kaggle.com/c/petfinder-adoption-prediction/overview](https://www.kaggle.com/c/petfinder-adoption-prediction/overview)

## Repository Structure

`data` stores all our datasets, we have 3 subfolders: `source`, `interm`, `final`. `source` data should just contain all the data taken directly from kaggle, and nothing should change in here. This is our source of truth. `interm` then contains any intermediate tables that we made/cleaned/filtered for analysis or exploration, and `final` folder contains the final data used for our candidate/champion models.

`models` contains our python code, working out and final models.

## Data

1. Get kaggle API installed with `pip install --user kaggle` (docs [here](https://github.com/Kaggle/kaggle-api))
    * Remember to set up your API credentials, also described in the link above
2. Unzip data into `data/source/`.