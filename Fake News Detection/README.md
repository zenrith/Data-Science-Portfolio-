# Fishing the Reals from the Fakes
 
Note: Before jumping into the code, do read the poster and report to gain a better understanding of what we are trying to do. Simply reading the code straight might be a bit mind boggling. 

## Contents

1. Datasets: Data that we used for the project
2. Notebooks: Notebooks containing all our code 
3. Results: Record of all results from our experiments
4. Report: In here you can find my team's formally documented insights  
5. Poster: My team's poster containing insights from our preliminary results 


## Datasets
These are the data that we have used in our project, obtained from the ISOT Fake News dataset. 

Fake.csv and True.csv - Original unprocessed data from ISOT.
news_final.csv - Combined data, with some preprocessing such as removal of stop words and lowercasing all characters.
SR_combined.csv - Combined data, with the additional removal of source "Reuters".
truncated_combined.csv - Combined data, in which 'text' field has been limited to only 150 words.


## Notebooks

We have split our code into 4 main sections:
1. Pre-processing
2. Word2Vec Models
3. TF-IDF Models
4. Results Visualisation

**Pre-processing**
In this notebook, we carried out basic pre-processing, which includes: removal of empty fields, removal of stop words, source removal and others.

**Word2Vec Models**
In this notebook, we ran the models using the text-vectorisation technique of Word2Vec on the various datasets as mentioned above.

**TF-IDF Models**
In this notebook, we ran the models using the text-vectorisation technique of TF-IDF on the various datasets as mentioned above.

**Results Visualisation**
In this notebook, we took the results that we have obtained, namely f1-scores and generated the results in a graphical form for easier visualisation.


## Results

Under results, we have the following files:
1. Confusion Matrices Plot
2. w2v_results.npy
3. results_tfidf.npy
4. results_tfidf_text_comparison_fbeta.npy

**Confusion Matrices Plot**
In this folder, we have images of all the confusion matrices obtained from running the models.

**w2v_results.npy**
These are the f1-scores we have obtained, running the models on Word2Vec text-vectorisation.

**results_tfidf.npy**
These are the f1-scores we have obtained, running the models on TF-IDF text-vectorisation.

**results_tfidf_text_comparison_fbeta.npy**
These are the f-beta scores we have obtained, running the models on TF-IDF text-vectorisation and only the 'text' field. 



## Report

The report is a detailed summary of our project aims, our experiments and findings


## Poster 

The poster is a brief overview of our project's preliminary findings
