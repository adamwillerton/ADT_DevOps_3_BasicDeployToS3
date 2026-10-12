# ADT_DevOps_1_BasicDeployToS3
Simple deployment of static website to existing S3 bucket. 


Checkout code
-->
Authenticate to AWS
-->
Copy website files to S3
-->
S3 serves the website



In AWS:  
- create an S3 bucket with a unique name
- needs configuring to serve static web pages: https://docs.aws.amazon.com/AmazonS3/latest/userguide/HostingWebsiteOnS3Setup.html

In Github:
- Add basic files for static web page
- Add the following secrets to the settings of GitHub (Settings --> Secrets --> Actions:
  
    •	AWS_ACCESS_KEY_ID
  
    •	AWS_SECRET_ACCESS_KEY
  
    •	AWS_REGION
  
    •	S3_BUCKET_NAME
  
    •	AWS_SESSION_TOKEN

  These can be found on Learner Lab main page, AWS Details, AWS CLI

  

- Add the workflow file to GitHub


