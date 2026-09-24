# ADT_DevOps_1_BasicDeployToS3
Simple deployment of static website to existing S3 bucket

In AWS:  
- create an S3 bucket with a unique name
- needs configuring to serve static web pages: https://docs.aws.amazon.com/AmazonS3/latest/userguide/HostingWebsiteOnS3Setup.html

- Add the following secrets to the settings of GitHub (Settings --> Secrets --> Actions:
  
    •	AWS_ACCESS_KEY_ID
  
    •	AWS_SECRET_ACCESS_KEY
  
    •	AWS_REGION
  
    •	S3_BUCKET_NAME
  
    •	AWS_SESSION_TOKEN

- Add the workflow file.


