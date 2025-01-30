# Write here a short conclusion of the exercise. That is, answer in less than 
Según lo explicado por Gustavo el día de hoy, el mejor método depende del proceso por el cual se quiere llegar a la predicción.



stargazer(linear_model, linear_model2, linear_model3  , type="text",
          covariate.labels=c("Mean Ocu Income","N under 18","Male",
                             "Hausehold Head","Age", "N under 18 x Male" ))
