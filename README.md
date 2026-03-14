# AWS S3 Static Website Deployment
This project demonstrates how to host a static website using Amazon S3.

## AWS Services Used
Amazon S3
Static Website Hosting
Bucket Policy for public access

## Deployment Steps
1. Created S3 bucket: olusola.systems-cloud-portfolio
2. Enabled Static Website Hosting
3. Uploaded index.html
4. Configured public read access
5. Accessed the website using the S3 website endpoint

##Architecture


## Result
The HTML page is served directly from the S3 bucket.

## Lessons:

Public access is restricted by default in Amazon S3. Even after disabling Block Public Access for the purpose of static website hosting, a bucket policy must explicitly allow the s3:GetObject action so that objects in the bucket can be retrieved over the internet.

Note:
This configuration was used for learning and portfolio purposes. In production environments, S3 buckets are typically kept private and accessed through a CDN such as Amazon CloudFront
