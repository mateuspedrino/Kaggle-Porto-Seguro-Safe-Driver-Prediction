# Kaggle - Porto Seguro Safe Driver Prediction

The aim of this notebook is to provide a preliminary and exploratory analysis of Kaggle Porto Seguro prediction problem (available at : https://www.kaggle.com/c/porto-seguro-safe-driver-prediction), giving some tips on how to deal with missing and unbalanced data. After doing that, random forest will be tested and some discussions around it will be conducted considering accuracy and auc score results. The prediction feature is "target", we will try to predict it from the other features (except id and removed features during the preprocessing).


I'd like to thank Rafael Alencar and Bert Carremans for theirs kernels, they were essential to perform the discussions in this notebook.

It's also important to highlight that it's not the goal of this notebook to go deep in the solution, however it has achieved a successful auc score in the end.

obs : Datasets (training and test) must be downloaded from the link above.
