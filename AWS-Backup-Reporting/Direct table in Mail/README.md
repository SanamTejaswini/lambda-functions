# AWS-Backup Report in table format in email

This sends a email which will have a backup report as in a tabular formation.

You can add more fields are per your requirenment.

You need to add in line 42, which will be headers(column names)

In the for loop post in like 46 you need to derive your fields and append them in line 71

Note : AWS Lambda does not support tabulate by default, you can add a layer, check AWS lambda layer.

Or you can follow the below approach as get the full library and every in local and upload code to AWS Lambda as zip

https://poc2ops.medium.com/serverless-using-python-libraries-that-are-not-part-of-aws-lamba-93aeb6851f72