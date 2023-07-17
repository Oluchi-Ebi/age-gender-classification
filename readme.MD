# Prediction of Gender, Ethnicity and Age

The dataset used for this research was gotten from UTKFace: https://susanqq.github.io/UTKFace/?ssp=1&darkschemeovr=0&setlang=en-GB&safesearch=moderate
The dataset has two variations with two colour channels: RGB and greyscale.

UTKFace dataset is a large-scale face dataset with a long age span (ranging from 0 to 116 years old). The dataset consists of 20K+ face images with annotations of age, gender, and ethnicity.


The age_gender.csv is already preprocessed and is labelled by age, gender and ethnicity.

The main Jupyter notebook, 'Final_notebook' contains a combination of multiple notebooks. Due to computational limitations, they cannot be run together. 

## The labels:
- The age is an integer from 0 to 116
- The gender is either 0 (male) or 1 (female)
- The ethnicity is an integer from 0 to 4, denoting White, Black, Asian, Indian, and Others (like Hispanic, Latino, Middle Eastern).

## Summaries
- The data exploration shows that the ethnicity contains more White, suggesting that the data is an imbalanced dataset. 
- There are more age groups within the 20s to 40s
- Separate models were developed for the age, gender and ethnicity

