# Static Website Hosting on AWS S3

## Overview
This project demonstrates how to host a static website on AWS S3. The website is accessible publicly via the S3 bucket endpoint.

## Features
- Static HTML, CSS, and JavaScript hosting
- Configurable error handling with `error.html`
- Public access via an S3 bucket endpoint

## Prerequisites
- AWS Account
- Basic knowledge of S3 and HTML

## Steps
1. Create an S3 bucket with a unique name.
2. Enable static website hosting and configure `index.html` and `error.html`.
3. Upload website files and set public permissions.
4. Add a bucket policy for public read access.
5. Access the website using the bucket endpoint.

## Files in This Repository
- `index.html`: Main landing page.
- `error.html`: Error page for handling invalid requests.
- `README.md`: Documentation for this project.

## Learn More
- [AWS S3 Documentation](https://docs.aws.amazon.com/s3/)
