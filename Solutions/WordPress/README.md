# WordPress Multi-AZ AL2023

## Description

This template installs a highly-available, scalable WordPress deployment using a multi-AZ Amazon RDS database instance for storage, Load balancer, EC2 instance and other required resources. It demonstrates using the AWS CloudFormation bootstrap scripts to deploy WordPress on EC2 with Amazon Linux 2023 AMI, PHP 8 and Apache 2.4.

It has been tested in Mumbai (ap-south-1) region with t4g.micro EC2 instance and db.t4g.micro RDS instance. It shows its compatible with AL2023 AMI and ARM64 architecture.


## Instructions

Follow these simple steps to deploy WordPress site using WordPress_Multi_AZ_AL2023.yaml.

1) Login to your AWS account, go to CloudFormation and create a new stack by uploading WordPress_Multi_AZ_AL2023.yaml.
   
2) Select the options for your stack.

3) Wait for the stack to be created. You will find load balancer URL in the Outputs tab. Open that URL to start WordPress installation.

4) Once the WordPress is installed, you can login to WordPress admin panel.

5) You can verify the Apache and PHP versions by logging into server using SSH.