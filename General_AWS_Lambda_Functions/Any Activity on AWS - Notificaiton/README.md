# AWS Autoscaling update

This Lambda function does the following

the cloudtrail logs files are taken from s3, unzipped and then analyzed based on the logic written, read it.

any user activity done on the account an SNS email is sent.

Note : the inbox will be spammed continuously so configure the filter properly.

you can put your "ignore part" in the below 

line 13, 44, 63, 79