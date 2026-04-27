# AI Photo Album

This project is a cloud-based photo album web application built for Cloud Computing Assignment 3.

The application allows users to upload photos, add optional custom labels, and search uploaded photos using natural language queries. Uploaded images are stored in Amazon S3, processed by AWS Lambda, labeled using Amazon Rekognition, indexed in Amazon OpenSearch, and searched through an API Gateway endpoint using Amazon Lex and a search Lambda function.

## Project Structure

```text
.
├── frontend/
│   ├── index.html
│   └── buildspec.yml
├── lambda-functions/
│   ├── index-photos/
│   │   └── lambda_function.py
│   └── search-photos/
│       └── lambda_function.py
└── cloudformation/
    └── cloudformation.yml