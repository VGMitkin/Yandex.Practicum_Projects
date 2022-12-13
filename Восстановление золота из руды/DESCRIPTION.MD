## Project. Prediction of the gold recovery ratio from gold ore.
### Description of the project
It is necessary to prepare a prototype of a machine learning model for Zifra. The company develops solutions for the efficient operation of industrial enterprises.

The model should predict the recovery rate of gold from gold ore. You have data with extraction and cleaning parameters at your disposal.

The model will help optimize production so as not to launch an enterprise with unprofitable characteristics.

### Content of the project

1. Data preparation
    1.1 Data exploration
    1.2 Verification of the correctness of the calculation of enrichment efficiency. Calculate it on the training set. Find the MAE between calculations and feature value.
    1.3 Analysis of features not available in the test sample.
    1.4 Data preprocessing.
    
2. Data analysis and answering questions
   2.1. How does the concentration of metals (Au, Ag, Pb) change at different purification stages?
   2.2. Compare the size distributions of raw material granules on the training and test samples.
   2.3. Study of the total concentration of all substances at different stages: in raw materials, in rough and final concentrates. Search for anomalous values in the total distribution.
3. Model training
   3.1. Write a function to calculate the final sMAPE.
   3.2. Train different models and evaluate their quality by cross-validation. Choose the best model and test it on a test set.

#### It is necessary to predict two quantities at once:
1. Efficiency of crude concentrate enrichment
2. final concentrate enrichment efficiency

### Libraries used in the project:
- pandas
- Numpy
- matplotlib
- Seaborn
- SKlearn
