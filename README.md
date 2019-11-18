# Automate content moderation and compliance with AI

Brand safety is a major concern as advertising becomes more automated. Issues with ad adjacency arise, contracts with brands or celebrities run out, and user-generated content can be difficult to manage. In this workshop, you learn how to use Amazon Rekognition, Amazon Textract, and Amazon Comprehend to detect inappropriate content or noncompliant use of content such as logos or celebrity faces. You leave with a scalable architecture that will save days of manual review in media moderation and compliance workflows.

In this workshop, we will use following AWS services:

* Amazon Rekognition
* Amazon Textract
* Amazon Comprehend
* Amazon DynamoDB
* AWS Lambda
* Amazon API Gateway
* Amazon S3
* Amazon SageMaker (For Jupyter Notebook)

## Learning Objectives

* Learn how to detect unsafe content including objects and explicit, suggestive or violent material.
* Learn how to detect faces, celebrities and custom celebrities.
* Learn how to detect unsafe text in images and documents.
* Learn how to use different APIs to build a comprehensive moderation solution.

## Pre-requisites

### AWS Account

In order to complete this workshop you will need an AWS Account with access to AWS IAM, Amazon S3, Amazon DynamoDB, AWS Lambda, AWS Step Functions, Amazon API Gateway, Amazon Rekognition, Amazon Textract, Amazon Comprehend and Amazon SageMaker.

All of the resources you will launch as part of this workshop are eligible for the AWS free tier if your account is less than 12 months old. See the [AWS Free Tier page](https://aws.amazon.com/free/) for more details.

## Modules

This workshop has following three modules.

1. [Starting with AI Services for Content moderation](1-starting-with-ai-services)
2. [Custom Comprehend model to detect unsae content](2-custom-comprehend)
3. [Comprehensive content moderation solution](3-moderation-solution)

## Cleanup
After you have completed the workshop, you can delete all of the resources using the following steps:
1. Delete CloudFormation stack created in the first module
2. Delete all Lambda functions and S3 bucket
