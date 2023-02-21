# Hyperparameters-Tuning
Hyperparameters Tuning

Here i have two projects

- param_tuning1:

  I compare models between each other(Ensemble Methods, Gaussian Processes, Linear Models, Navies Bayes, Nearest Neighbor, SVM, Trees and XGBoost)
  After this, i chose model with the best perfomence (test score) and do params tuning with GridSearchCV
  
- param_tuning2:

  I compare less amount of models but with all of them do params tuning with RandomizedSearchCV in loop.
  
  Make several pretty visualization graphs:
  
      -Compare perfomance of each model and their scores(f1-score, AUC, Precision, Recall)
      ![newplot (1)](https://user-images.githubusercontent.com/78692457/220389017-fd1fa560-3a1d-4784-8eff-ae29dbbd997e.png)

      -Fit Time of each model.
      ![newplot (2)](https://user-images.githubusercontent.com/78692457/220389105-e32d309b-267a-44f9-9cce-f796efa0e900.png)
      
      -AUC ROC
      ![newplot (3)](https://user-images.githubusercontent.com/78692457/220389233-0e3ce838-3a6b-410e-900e-a285c30e0f54.png)

      -Confusion matrixes
      ![newplot (4)](https://user-images.githubusercontent.com/78692457/220389273-09b83e01-f20c-4ba5-9bb5-3ed1668dc232.png)

