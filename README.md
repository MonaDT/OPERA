# <p align = center> The Flemish Operation  </center>
##  <p align = center> Language choices in the repertoire of the Antwerp Opera  (1893 – 1934) </center>


<div id="header" align="center">
  <img src="https://github.com/MonaDT/OPERA/assets/94553096/0d5563b8-e28b-4c0e-b5b7-dea88f64fe25" width="800"/>
</div>

This repository contains the data and code accompanying the abovementioned master thesis in order to obtain a degree in  *Digital Text Analysis* at the *University of Antwerp* (2022-2023).

The repository contains the following **data** and **code**:

**Materials**
- `Binomial_prep.csv` -> the preprocessed dataset as it was used in the Generalized Linear Model.
- `META.txt` -> txt-file containing addition metadata which as added to the dataframe such as the composer, original language and original title.
- `KVO_META.CSV` -> The preprocessed dataset.
- `Metadata_OBV_gesplitsts_test.csv` -> The dataset before preprocessing.

**Notebooks**
- `bar_chart_race.ipynb` -> Code for creating bar char races of the composers and original languages. ***This notebook was not used for the thesis.***
- `Crop_test.ipynb` - > Code used to automatically crop the images of the programme leaflets to size.
- `DF_cleaner.ipynb` -> Code used to preprocess the data and includes the steps of data normalisation as well as the additional metadata (this notebook requires META.txt)
- `DF_prep_GLM.ipynb` -> Code used to preprocess the dataset in order to create the GLMs.
- `Data_exploration.ipynb` -> notebook used for data exploration.
- `GLM.ipynb` -> R notebook where the Generalised Linear Models are conducted.
- `Gala_Popular.ipynb` -> Analysis of gala performances and popular performances.
- `Lang_distributions.ipynb` -> Code for analysing the diochronic language distribution per season.
- `Turnover.ipynb` -> exploration of turnover of top 10 productions, genres and languages across directorial changes in the opera. ***This notebook was not used for the thesis.***
- `Reperformance` -> Analysis of chance of reruns in the Antwerp Opera. ***This notebook was not used for the thesis.***



