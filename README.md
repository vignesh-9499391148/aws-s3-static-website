# AWS S3 Static Website Deployment

## Project Overview

This project demonstrates how to deploy a static website using Amazon S3 Static Website Hosting.

The website was developed using HTML and CSS and uploaded to an Amazon S3 bucket.

## Technologies Used

- Amazon Web Services (AWS)
- Amazon S3
- HTML5
- CSS3
- Git
- GitHub

## Architecture

```text
Website Visitor
      |
      v
Amazon S3 Static Website Hosting
      |
      v
index.html
```

## Deployment Steps

1. Created an S3 bucket in the Asia Pacific (Mumbai) region.
2. Uploaded `index.html` to the bucket.
3. Enabled Static Website Hosting.
4. Configured the index document as `index.html`.
5. Configured permissions for public access to the website.
6. Opened the S3 website endpoint and verified that the website loaded successfully.

## Live Website

**S3 Website URL:** Replace this text with your actual S3 website endpoint.

## Security Notes

- The direct S3 website endpoint uses HTTP, not HTTPS.
- Public access is enabled for this demonstration, so the bucket should contain only files intended for public viewing.
- Amazon CloudFront deployment is pending AWS account verification.

## Project Status

- [ ] Create S3 bucket
- [ ] Upload website files
- [ ] Enable Static Website Hosting
- [ ] Test website endpoint
- [ ] Configure CloudFront
- [ ] Serve the website through HTTPS using CloudFront

## Author

Vignesh K
