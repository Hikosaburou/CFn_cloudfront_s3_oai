# CFn_cloudfront_s3_oai
Cloudfront + S3 Origin (OAI) 設定用の CFn テンプレート

# Usage

### Create Stack

```
aws cloudformation create-stack \
  --stack-name <YOUR STACK NAME> \
  --template-body file://cloud_formation/cfntemplate.yaml \
  --parameters ParameterKey=OwnerTagValue,ParameterValue=<YOUR NAME>
```

### Update Stack

```
aws cloudformation update-stack \
  --stack-name <YOUR STACK NAME> \
  --template-body file://cloud_formation/cfntemplate.yaml \
  --parameters ParameterKey=OwnerTagValue,ParameterValue=<YOUR NAME>
```
