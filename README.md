## Keep tracking of the steps taken for ML deployment here
1) Download the aws cli 
2) Go to IAM -> User -> Create New User -> Give name -> Go to attach policies directly -> Give it administrator access
3) Click on the user created -> security credentials -> create access key -> select AWS CLI and agree to the terms -> click next and skip the label step -> save the access key and secret access key (download the csv file)
4) Open Terminal -> “aws configure” -> paste access key -> paste secret access key -> set default region (or press enter if already configured) -> press enter to skip default output format
5) Create Notebook Locally -> create venv -> pip install requirements.txt:
numpy==1.26.4
sagemaker==2.232.3
boto3==1.35.53
scikit-learn==1.2.2