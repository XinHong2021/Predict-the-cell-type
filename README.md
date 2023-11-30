# Predict-the-cell-type
Predicting the celltype from gene motifs in mouse development

## Project on kaggle
This is a KaggleInClass challenge, you can find at https://www.kaggle.com/c/antechinus/.

## Implementation
### Data description and visualization
Using 1003 types of genes to predict 10 types of cells. 
*Insights*
Genes are described in numeric variables and most of values are 0. 

### Data engineering

#### lasso regression 
The purpose of lasso regession is to select only the highly relevant features, to improve the algorithm effieciency. 

#### Multidimensional Scaling (MDS)
The model calculates the distance between all data points and remove outliers, which may influence further machine learning algorithms. 

### Supervised machine learning 
Compared possible ML models such as SVM, NN, and tuned parameters in gradient boosted tree to predict cell types1. 
