# py-less


serverless create --template aws-python3


sls config credentials --provider aws --key YOUR-KEY --secret YOUR-SECRET


sls deploy --stage dev


sls plugin search -q simulate
sls plugin install -n serverless-plugin-simulate
sls plugin install -n serverless-python-requirements


#running
sls simulate lambda -p 4000
sls simulate apigateway -p 5003 --lambda-port 4000
