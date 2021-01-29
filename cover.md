# Cancer

## What is the notebook about?
Classification of Cancer, an Uncontrollable growth of cells, a disease of mitosis which creates a clump of cancerous cells (tumor), interfering with the healthy functioning of vital organs essential to sustain our life. 
Cancer is determined with a Biopsy, we have biospecimen records with metrics useful to identify the type of cancer. A prediction attempt is made, by utilizing biospecimen reports, and combining it with some generic clinical information to determine the type of ancer.

## What algorithms are used?
* XGBoost Classifier is used to predict the `primary diagnosis` using the features extracted.

## What is the content of the notebook?
This notebook reads several split biospecimen and clinical reports, storing them in an datastructure. The data is preprocessed and the model is trained with it.
The confusion matrix displays results of the XGBoost Classifier, with an observed accuracy of 86% on the population set.
