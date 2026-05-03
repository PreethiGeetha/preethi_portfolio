# Preethi's Portfolio — Hosted on AWS S3 + CloudFront

## Live URL
https://d3t40z34m8s4qm.cloudfront.net/
## What I Built
A responsive single-page portfolio hosted on AWS S3 
and served via CloudFront with HTTPS.

## Steps I Took
1. Built index.html and styles.css locally
2. Pushed code to GitHub
3. Created S3 bucket and enabled static website hosting
4. Added bucket policy to allow public access
5. Uploaded files to S3
6. Created CloudFront distribution with HTTPS
7. Fixed 504 error by setting origin protocol to HTTP only
8. Created CloudFront invalidation to clear cache

## Technologies Used
- HTML, CSS
- AWS S3 (static hosting)
- AWS CloudFront (CDN + HTTPS)
- Git + GitHub
