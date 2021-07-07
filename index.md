# DeepLearning en la Practica 2021
Notas, Codigo y Ejemplos del curso de DL dictado por Marvik como materia electiva de la Maestria de Ciencia de Datos por UTEC.

Esta pagina es un ejemplo de como crear un proyecto utilizando herramientas open source para la gestion de proyectos de ML/DL/AI/DS el mismo sera implementado a traves de un pipeline de deploy automatico.

# GitHub Project
En [projecto principal](https://github.com/orgs/ml-as-a-service/projects/3) se pude visualizar un tablero kanban donde se gestionan los modulos o subproyectos. El mismo permite tener una vision global del estado del proyecto, asi como los diferentes repositorios relacionados.


# Repositories
## Main 
 - Repositorio [principal](https://github.com/ml-as-a-service/dlpm)

## SubProjects
 - Repositorio [DL](https://github.com/ml-as-a-service/dlpm-dl)
 - Repositorio [CNN](https://github.com/ml-as-a-service/dlpm-cnn)
 - Repositorio [opencv](https://github.com/ml-as-a-service/dlpm-opencv)
 - Repositorio [GAN](https://github.com/ml-as-a-service/dlpm-gan)
 - Repositorio [NLP](https://github.com/ml-as-a-service/dlpm-nlp)
 - Repositorio [RNN](https://github.com/ml-as-a-service/dlpm-rnn)
 - Repositorio [MLOps](https://github.com/ml-as-a-service/dlpm-mlops)
 - Repositorio [EC](https://github.com/ml-as-a-service/dlpm-ec)

# 7 steps of ML
El (proceso general de ML)[https://www.kdnuggets.com/2018/05/general-approaches-machine-learning-process.html] consiste en 7 pasos 

## 1 - Data Collection (Gathering data)

 - The quantity & quality of your data dictate how accurate our model is
 - The outcome of this step is generally a representation of data (Guo simplifies to specifying a table) which we will use for training
 - Using pre-collected data, by way of datasets from Kaggle, UCI, etc., still fits into this step
 
## 2 - Data Preparation (Preparing that data)

 - Wrangle data and prepare it for training
 - Clean that which may require it (remove duplicates, correct errors, deal with missing values, normalization, data type conversions, etc.)
 - Randomize data, which erases the effects of the particular order in which we collected and/or otherwise prepared our data
 - Visualize data to help detect relevant relationships between variables or class imbalances (bias alert!), or perform other exploratory analysis
 - Split into training and evaluation sets
 
## 3 - Choose a Model (Choosing a model)

 - Different algorithms are for different tasks; choose the right one
 
## 4 - Train the Model (Training)

 - The goal of training is to answer a question or make a prediction correctly as often as possible
 - Linear regression example: algorithm would need to learn values for m (or W) and b (x is input, y is output)
 - Each iteration of process is a training step
 
## 5 - Evaluate the Model (Evaluation)

 - Uses some metric or combination of metrics to "measure" objective performance of model
 - Test the model against previously unseen data
 - This unseen data is meant to be somewhat representative of model performance in the real world, but still helps tune the model (as opposed to test data, which does not)
 - Good train/eval split? 80/20, 70/30, or similar, depending on domain, data availability, dataset particulars, etc.
 
## 6 - Parameter Tuning (Hyperparameter tuning)

 - This step refers to hyperparameter tuning, which is an "artform" as opposed to a science
 - Tune model parameters for improved performance
 - Simple model hyperparameters may include: number of training steps, learning rate, initialization values and distribution, etc.
 
## 7 - Make Predictions (Prediction)

 - Using further (test set) data which have, until this point, been withheld from the model (and for which class labels are known), are used to test the model; a better approximation of how the model will perform in the real world
