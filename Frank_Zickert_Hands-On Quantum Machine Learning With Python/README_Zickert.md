This folder contains my `Jupyter` notebooks for exercises related to chapters of
```
    Hands-On Quantum Machine Learning With Python
    Volume 1: Get Started by Dr. Frank Zickert
    Copyright © 2021 Dr. Frank Zickert, pyqml.com
```

Chapter 1.8 explains how to set up `Jupyter` notebooks on your computer.

I used anaconda since I am using a Windows computer on which I could not
activate Linux.

I used conda to install `jupyter`, `notebook`, `jupyterlabs` .

I used pip to install `qiskit`, `scikit-learn`, `scikit-learn-intelex`,
`pylatexenc` .

I start the notebook server in an `Anaconda Prompt` terminal with the command
```
>jupyter notebook

```

## intro_qiskit.ipynb
This is a modified exercise from
```
Chapter 2 Binary Classification
```
I added Accuracy and Matthews Correlation Coefficient metrics.
Also added scatter_matrix plot and consistency checks on the metrics.
Omitted random and predict_death classifiers.

## titanic_ml.ipynb

This is a modified exercise from
```
Chapter 3 Qubit and Quantum States
```
I added Accuracy and Matthews Correlation Coefficient metrics.
I corrected bugs in the use of rankings as probabilities
and in the use of probabilities to set quantum states.
