# Static Website Deployment to S3

This repository contains a personal website that is automatically deployed to AWS S3 using GitHub Actions.

## Deployment

The site is automatically deployed to S3 when changes are pushed to the main branch.

## Local Development

To work on this site locally, simply open the files in the `site` directory in your browser.

## GitHub Secrets Required

- `AWS_ACCESS_KEY_ID`: AWS access key with S3 permissions
- `AWS_SECRET_ACCESS_KEY`: AWS secret key
- `S3_BUCKET_NAME`: Name of the S3 bucket for deployment
- `CLOUDFRONT_DISTRIBUTION_ID` (optional): CloudFront distribution ID for cache invalidation