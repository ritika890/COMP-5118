# COMP5118
Generating Fun Facts from Wikipedia tables
This repository consists of the files for superlative phrase prediction in table titles as well as templates.

For running both the prediction files, basic python libraries are required. Additionally,
Wikitables [URL : https://wikitables.readthedocs.io/en/latest/] is required for importing the table contents.
And 
Syntaxnet Parser [URL: https://github.com/brianlow/syntaxnet-docker] is required which requires pre-installation of docker.

The structure of files is divided into different sections: Data Collection, Feature engineering, data preprocessing and data modeling.

The data file ‘Wikipedia_Tables_one.csv’ is required for the prediction of table titles. 

The motivation of this work is done based on this paper: Automatically Generating Interesting Facts fromWikipedia Tables
https://dl.acm.org/doi/pdf/10.1145/3299869.3314043
