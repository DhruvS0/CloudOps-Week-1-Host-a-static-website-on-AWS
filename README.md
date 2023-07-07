# CloudOps-Week-1-Host-a-static-website-on-AWS
### Host a static website on AWS  and implement CICD using the S3, CloudFront, Route53

![Architecture](https://github.com/DhruvS0/CloudOps-Week-1-Host-a-static-website-on-AWS/assets/113872537/d095b016-7d5c-40dd-8300-67179c70219f)

To host a website on AWS for free, you can take advantage of the AWS Free Tier, which offers limited free usage for certain AWS services. Here's how you can host a website on AWS using free services:

#### Create an AWS Account:

Go to the AWS website (https://aws.amazon.com/).
Click on "Create an AWS Account" and follow the instructions to create a new account.
Provide the necessary information and payment details (although you won't be charged for free services within the Free Tier limits).

#### Choose the Appropriate Free Services:

AWS offers several services that are part of the Free Tier. For hosting a static website, you can use the following services:
Amazon S3: Use S3 to store and serve your website files.
Amazon CloudFront: Set up a CDN for improved performance and global distribution.
AWS Route 53: Configure DNS for your domain or subdomain.

#### Configure Amazon S3:

Follow the steps mentioned in the previous response to create an S3 bucket and configure it for website hosting.
Upload your website files to the S3 bucket.
Make sure to set the appropriate permissions for public access. i.e., Turn off the block public access and write a public policy as shown below.
![Bucket Policy](https://github.com/DhruvS0/CloudOps-Week-1-Host-a-static-website-on-AWS/assets/113872537/86b45c36-fa12-4457-9d51-c51e92625a86)

#### Set Up Amazon CloudFront:

Create a CloudFront distribution for your website to improve its performance.
Follow the steps mentioned in the previous response to configure CloudFront with your S3 bucket as the origin.
While we create CloudFront distribution, we need to generate certificates for our domain name.
![image](https://github.com/DhruvS0/CloudOps-Week-1-Host-a-static-website-on-AWS/assets/113872537/542c94b2-44de-42c8-a6be-e7eaae141b1a)
Enable the option to redirect HTTP to HTTPS for better security.
![CloudFront-Distribution](https://github.com/DhruvS0/CloudOps-Week-1-Host-a-static-website-on-AWS/assets/113872537/c72b6c0e-41ac-494a-8125-4bccf6678702)


#### Configure AWS Route 53:

Follow the steps mentioned in the previous response to set up Route 53 and create a record set.
Point the record set to your CloudFront distribution, so your website is accessible through your domain or subdomain.
![image](https://github.com/DhruvS0/CloudOps-Week-1-Host-a-static-website-on-AWS/assets/113872537/e7803e96-c1b8-49a9-84a7-dd032fa3f249)

By following these steps, you can host a static website on AWS using the free services within the AWS Free Tier limits. Keep in mind that the Free Tier has usage limits, and if your website exceeds those limits, you may incur charges. Make sure to review the AWS Free Tier documentation to understand the specific usage limits and durations associated with the free services.

#### Create a Pipeline to automate the changes in github file.
![image](https://github.com/DhruvS0/CloudOps-Week-1-Host-a-static-website-on-AWS/assets/113872537/432d48c9-b328-4dde-990f-2b3ce77274b8)

#### Website Hosted
![Final-webpage-hosted](https://github.com/DhruvS0/CloudOps-Week-1-Host-a-static-website-on-AWS/assets/113872537/47a1fe0d-d048-4d15-9fc6-ce9ef67bc42d)

