# aws-vpc-cf
Cloudformation-based VPC exercise

## Commands used

To create a new stack:

```
$ aws cloudformation create-stack --stack-name dev-vpc --template-body file://my-vpc.yml
```

To update an existing stack:

```
$ aws cloudformation update-stack --stack-name dev-vpc --template-body file://my-vpc.yml
```

To delete an existing stack:

```
$ aws cloudformation delete-stack --stack-name dev-vpc
```
