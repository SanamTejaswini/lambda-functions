# Athena notification

This Lambda function does the following

1. triggeres a athena query to a cloudtrail athena table and creates a outfile file in a output bucket
2. creates a S3 pre-signed URL for the file so it can be used to get the file in a certain timeframe
3. sends a SNS email to subscribers with the link.