# Neural Network Assessment: SurGen SR386 by Ratanapara Choorat

## Introduction

This project showcase the process of building an Artificial Neural Network(ANN) to predict the mortality within colorectal cancer (CRC) patients using the SurGen SR386 cohort. Within this project,
includes the program as jupyter notebook called "NeuralNetwork_Finale.ipynb", The code will include some comments that I discover during the work and some general steps to how to program works and reacts, datset used for the program called SR386_labels.csv, 
and the output of the best baseline and final model run within the program.

## Installing the Program

Since this is native program and not within the Google Colab, I have included the pip install command to ensure the program works and the libraries I use is as follows:

- **TensorFlow/Keras** -> ANN model framework
- **Pandas** -> Data Import and Manipulation
- **Numpy** -> Numeric Features
- **Scikit-Learn** -> For Data preprocessing, metrics for model evaluation (Precision, Recall, F1-Score), and Selecting Best Feature (KBest)
- **Imbalance-Learn** -> For SMOTE technique during model tuning process
- **Matplotlib/Seaborn** -> Plotting and Better Visualizations

When click run the program, the program should start working as expected and will see the cleaning, preprocessing, training and evaluation steps to produce report.

## File Description:

- **NeuralNetwork_Finale.ipynb** -> Main file for all python code of this project as mentioned before
- **SR386_labels.csv** -> Dataset used for this project
- **base.png** -> Best Baseline model image results
- **output.png** -> Best Tuned Model image results
- **readme.md** -> Current file