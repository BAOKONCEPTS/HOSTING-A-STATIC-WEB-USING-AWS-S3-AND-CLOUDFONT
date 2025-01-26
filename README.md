# HOSTING-A-STATIC-WEB-USING-AWS-S3-AND-CLOUDFONT

## Oblective:
The project aims at hosting a static website using AWS S3 and CloudFont.The following step-by-step guides were used to host a static website with the integration of AWS S3 and CloudFont.

## Prerequisites
- AWS account with administrative privileges
- Basic knowledge of AWS services (S3, CloudFront, IAM)
- Familiarity with command-line interfaces (CLI)
br<img width="1280" alt="bucket polict set and configured - Copy" src="https://github.com/user-attachments/assets/35b46d76-57d6-46a9-bc2d-ca78352728fd" />

## Step 1: Create an S3 Bucket

- Log in to the AWS Management Console
- Navigate to the S3 dashboard
- 
- Click "Create bucket" and enter a unique name
- Choose a region and click "Create bucket"

## Step 2: Configure S3 Bucket Settings

- Enable versioning and server-side encryption
- Set up bucket policies for public read access
- Configure CORS (Cross-Origin Resource Sharing)

## Step 3: Upload Website Files to S3

- Use the AWS CLI or S3 console to upload your website files
- Organize files into folders (e.g., images, CSS, JS)

## Step 4: Set Up CloudFront Distribution

- Navigate to the CloudFront dashboard
- Click "Create distribution" and choose "Web" delivery method
- Enter your S3 bucket name and configure settings
- Choose a SSL/TLS certificate (e.g., ACM, CloudFront default)

## Step 5: Configure CloudFront Settings

- Set up caching behaviors and invalidation
- Configure edge locations and geo-restrictions
- Enable logging and monitoring

## Step 6: Test Your Website

- Verify that your website is accessible via the CloudFront domain name
- Test website functionality and performance

## Troubleshooting

- Check the AWS CloudFront and S3 documentation for troubleshooting guides
- Verify that your S3 bucket and CloudFront distribution are correctly configured


By following these steps, you can host a static website using AWS S3 and CloudFront.

# Author
## Okunola Babatunde
