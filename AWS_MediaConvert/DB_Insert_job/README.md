# Insert to MongoDB

Once the Media convert job is completed we have another step which is to put the S3 URL in MongoDB

The Lambda trigger is set for eventbridge with rule of Mediaconvert Job status COMPLETE

NOTE : AWS Lambda python version does not have mongodb library "pymongo" so for that you need to use docker, install everything and extract the required thing in a zipped format.

You can follow the below blog to see how to get the libraries : 
  
https://poc2ops.medium.com/serverless-using-python-libraries-that-are-not-part-of-aws-lamba-93aeb6851f72

