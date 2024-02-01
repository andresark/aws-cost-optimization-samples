# AWS Cost Optimization Samples

This repository contains a collection of AWS CloudFormation templates that demonstrate various cost optimization techniques.

## enforce-tags.yaml

The `enforce-tags.yaml` file is a CloudFormation template that helps enforce tagging best practices within your AWS resources. It creates an AWS Config rule that checks whether resources have the required tags and takes remediation actions if the tags are missing.

## enforce-workhours.yaml

The `enforce-workhours.yaml` file is a CloudFormation template that helps enforce work hour restrictions for your AWS resources. It creates an AWS Lambda function and an Amazon CloudWatch Events rule that triggers the function based on a specified schedule. The function can perform actions such as stopping or terminating resources outside of the defined work hours.

## gp2-gp3-migration.yaml

The `gp2-gp3-migration.yaml` file is a CloudFormation template that facilitates the migration of Amazon EBS volumes from General Purpose SSD (gp2) to General Purpose SSD (gp3). It creates an AWS Lambda function and an Amazon CloudWatch Events rule that triggers the function based on a specified schedule. The function identifies eligible volumes and migrates them to the gp3 volume type, which can help optimize costs and performance.

Please refer to the individual YAML files for more details on their usage and configuration.
