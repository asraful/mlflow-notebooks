# mlflow-notebooks
Learning  MLflow: A Machine Learning Lifecycle Platform

Output : 

![ElasticNet-paths](https://user-images.githubusercontent.com/284564/135728173-9fe5f6f0-acd0-4de8-914b-d410e6c48cd4.png)


Model Invocations : 

curl --request POST http://127.0.0.1:<port>/invocations \
       --header "Content-Type:application/json; format=pandas-split" \
       --data '{
    "columns":["age", "sex", "bmi", "bp", "s1", "s2", "s3", "s4", "s5", "s6"],
   "data":[[0.01608, -0.010064, 0.00100, 0.00000, 0.00642, 0.01189, 0.13023, -0.23949, -0.14542, 0.63205]]
  }'



Reference : 
https://github.com/mlflow/mlflow/tree/master/examples/sklearn_elasticnet_diabetes
