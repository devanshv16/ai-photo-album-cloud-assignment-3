# AI Photo Album

This project is a cloud-based photo album web application built for Cloud Computing Assignment 3.

The application allows users to upload photos, add optional custom labels, and search uploaded photos using natural language queries. Uploaded images are stored in Amazon S3, processed by AWS Lambda, labeled using Amazon Rekognition, indexed in Amazon OpenSearch, and searched through an API Gateway endpoint using Amazon Lex and a search Lambda function.

## Project Structure

```text
.
├── front-end/
│   ├── index.html
├── lambda-functions/
│   ├── index-photos/
│   │   └── index-photos_lambda_function.py
│   └── search-photos/
│       └── search-photos_lambda_function.py
└── other-srcipts/
    └── backend-buildspec.yml
    └── cloudformation.yml
    └── frontend-buildspec.yml