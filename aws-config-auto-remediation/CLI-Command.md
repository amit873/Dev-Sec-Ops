# CLI Commands to Create CloudFormation Stacks
https://docs.aws.amazon.com/cli/latest/reference/cloudformation/deploy/index.html

## S3_BUCKET_VERSIONING_ENABLED.yaml
aws cloudformation deploy --template-file "S3_BUCKET_VERSIONING_ENABLED.yaml" --stack-name "s3-enable-versioning-remediation" --capabilities CAPABILITY_IAM

## S3_BUCKET_SERVER_SIDE_ENCRYPTION_ENABLED.yaml
aws cloudformation deploy --template-file "S3_BUCKET_SERVER_SIDE_ENCRYPTION_ENABLED.yaml" --stack-name "s3-bucket-encryption-enable" --capabilities CAPABILITY_IAM

## EC2_INSTANCE_NO_PUBLIC_IP.yaml
aws cloudformation deploy --template-file "EC2_INSTANCE_NO_PUBLIC_IP.yaml" --stack-name "ec2-instance-no-ip" --capabilities CAPABILITY_IAM

## APPROVED_AMIS_BY_ID.yaml
aws cloudformation deploy --template-file "APPROVED_AMIS_BY_ID.yaml" --stack-name "approved-ami" --capabilities CAPABILITY_IAM

## CloudFormation cheatsheet
https://theburningmonk.com/cloudformation-ref-and-getatt-cheatsheet/ 

