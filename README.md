# AWS SAA Project – Static Website Hosting

## Objective
To host a highly available, secure, and cost‑effective static website using AWS Free Tier services.

## AWS Services Used
- Amazon S3
- Amazon CloudFront
- AWS Certificate Manager (ACM)
- IAM

## Architecture
User → CloudFront → S3

## Implementation Steps
1. Created an S3 bucket and enabled static website hosting
2. Uploaded index.html and error.html files
3. Configured CloudFront distribution with S3 as origin
4. Enabled HTTPS using ACM certificate
5. Accessed website through CloudFront URL

## Security
- Blocked public access to S3 bucket
- Allowed access only via CloudFront
- Used IAM least privilege

## Cost Consideration
- Entire project built within AWS Free Tier
- No Route 53 used to avoid charges

## Outcome
Successfully hosted a static website with high availability and HTTPS.
Screen shots 
Added screen shots for reference
