# aws-s3
A collection of CloudFormation templates to automate S3 buckets and their surrounding services.

## Billing
Creates a billing bucket for itemised bills, a CloudWatch Alarm and SNS topic to alert when bills breach a threshold.
```
  ./aws-s3 create billing.json example.com somebody@example.com 100
```

