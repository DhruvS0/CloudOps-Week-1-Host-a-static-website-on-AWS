# CloudOps-Week-1-Host-a-static-website-on-AWS
### Host a static website on AWS  and implement CICD using the S3, CloudFront, Route53
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
Make sure to set the appropriate permissions for public access.

#### Set Up Amazon CloudFront:

Create a CloudFront distribution for your website to improve its performance.
Follow the steps mentioned in the previous response to configure CloudFront with your S3 bucket as the origin.
Enable the option to redirect HTTP to HTTPS for better security.

#### Configure AWS Route 53:

Follow the steps mentioned in the previous response to set up Route 53 and create a record set.
Point the record set to your CloudFront distribution, so your website is accessible through your domain or subdomain.
By following these steps, you can host a static website on AWS using the free services within the AWS Free Tier limits. Keep in mind that the Free Tier has usage limits, and if your website exceeds those limits, you may incur charges. Make sure to review the AWS Free Tier documentation to understand the specific usage limits and durations associated with the free services.
