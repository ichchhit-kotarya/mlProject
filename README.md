End to End machine learning project


import dagshub
dagshub.init(repo_owner='ichchhit-kotarya', repo_name='mlProject', mlflow=True)

import mlflow
with mlflow.start_run():
  mlflow.log_param('parameter name', 'value')
  mlflow.log_metric('metric name', 1)