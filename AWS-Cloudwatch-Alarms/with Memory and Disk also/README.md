# AWS-Cloudwatch-Alarms

This creates 4 alarms. 

1. CPU alarm with 90% threshold (line 28) and status check alarm
2. Memory and disk alarm for ec2. given that you have installed custom metrics for the server. you need to use AWS Cloudwatch agent for this.

Environmental variables : 

AccountName : Sandbox
Region : us-east-1
SNS :   arn:aws:sns:us-east-1:123456789:sns_name
id  : i-12345667

The code is little manual as you need to insert instnace id one by one.

Based on your situation you can update the funtion and put a loop and give a list of instance id's