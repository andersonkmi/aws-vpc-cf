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

## References

- [Building a VPC with CloudFormation - Part 1](https://www.infoq.com/articles/aws-vpc-cloudformation)
- [Building a VPC with CloudFormation - Part 2](https://www.infoq.com/articles/aws-vpc-cloudformation-part2)
