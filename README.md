AWS S3 Static Website Hosting

Project Overview

This project demonstrates how to host a static website using Amazon S3 and distribute content globally using Amazon CloudFront.

Services Used

- Amazon S3
- Amazon CloudFront

Architecture

User
↓
CloudFront
↓
Amazon S3 Bucket

Project Steps

1. Created an Amazon S3 bucket.
2. Enabled Static Website Hosting.
3. Uploaded HTML website files.
4. Configured public access permissions.
5. Tested the S3 Website Endpoint.
6. Created a CloudFront distribution.
7. Connected CloudFront to the S3 website.
8. Verified website access through CloudFront.

Screenshots

Website Hosted on Amazon S3

This screenshot shows the static website successfully hosted using the Amazon S3 Website Endpoint before CloudFront was configured.

![Website Hosted on S3](screenshots/without_cloudfront.png)

CloudFront Distribution Configuration

This screenshot shows the CloudFront distribution configuration using the S3 website endpoint as the origin.

![CloudFront Configuration](screenshots/Cloudfront_AWS.png)

Website Delivered Through CloudFront

This screenshot shows the website successfully being served through Amazon CloudFront after the distribution was deployed.

![Website Through CloudFront](screenshots/with_cloudfront.png)

Learning Outcomes

- Understanding Amazon S3
- Static Website Hosting
- CloudFront CDN Basics
- Website Deployment on AWS
