# MLflowEndToEndDL

# dagshub 

import dagshub
dagshub.init(repo_owner='sohjpeg', repo_name='MLflowEndToEndDL', mlflow=True)

import mlflow
with mlflow.start_run():
  mlflow.log_param('parameter name', 'value')
  mlflow.log_metric('metric name', 1)