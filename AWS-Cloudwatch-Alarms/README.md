# AWS-Cloudwatch-Alarms

This creates 2 alarms. CPU alarm with 90% threshold (line 28) and status check alarm

Environmental variables : 

AccountName : Sandbox
Region : us-east-1
SNS :   arn:aws:sns:us-east-1:123456789:sns_name
id  : i-12345667

The code is little manual as you need to insert instnace id one by one.

Based on your situation you can update the funtion and put a loop and give a list of instance id's