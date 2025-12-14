# Build-an-Image-Editing-Serverless-App-using-AWS-Service
Deploy a serverless web application to edit images using Amazon Bedrock
🎨 Workshop Overview
Welcome to the Deploy a serverless web application to edit images using Amazon Bedrock workshop! In this hands-on workshop, you'll build a complete serverless image editing application using various AWS services. This solution features secure user authentication, persistent data storage, AI-powered image generation and editing capabilities, and a modern web interface.

🏗️ Architecture Overview
This workshop will guide you through building a modern, serverless image editing application with the following components:

Architecture Diagram

Authentication: Amazon Cognito for user management
Database: Amazon DynamoDB for image generation data storage
Compute: AWS Lambda for serverless business logic
API: Amazon API Gateway for REST endpoints
AI: Amazon Bedrock with Titan Image Generator G1 for image editing
Frontend: AWS Amplify for web application hosting
🎯 Learning Objectives
By the end of this workshop, you will:

✅ Understand serverless architecture patterns
✅ Implement secure authentication with Cognito
✅ Design NoSQL databases with DynamoDB
✅ Build REST APIs with API Gateway
✅ Create serverless functions with Lambda
✅ Integrate AI services with Amazon Bedrock
✅ Deploy web applications with AWS Amplify
✅ Generate and edit images with Titan Image Generator G1

⏱️ Estimated Time
Total Workshop Time: 1 hour (60 minutes)

🔧 Prerequisites
AWS Account with appropriate permissions
Basic knowledge of AWS services
Familiarity with REST APIs
Understanding of serverless concepts
👥 Target Audience
This workshop is designed for:

Developers building serverless applications on AWS
SRE Engineers interested in serverless architectures
AI/ML Engineers exploring generative AI integration
Technical Professionals interested in image editing solutions
Experience Level: Intermediate (200) - participants should have basic AWS experience and understand fundamental cloud concepts.

💰 Cost Considerations
This workshop uses several AWS services with pay-as-you-go pricing:

Amazon Cognito: $0.0055 per monthly active user (MAU) after first 50,000

Amazon DynamoDB: $0.25 per GB per month for on-demand storage

AWS Lambda: $0.20 per 1M requests + compute time charges

Amazon API Gateway: $3.50 per million API calls

Amazon Bedrock: Pay-per-use for AI model invocations

Amazon Titan Image Generator G1: $0.008 per image generated

AWS Amplify: $0.01 per build minute + hosting costs

Estimated Workshop Cost: $2-5 for completion and testing, depending on usage patterns.

For accurate pricing estimates, use the AWS Pricing Calculator .

🌍 Workshop Region
This workshop is designed for deployment in us-east-1 (N. Virginia) or us-west-2 (Oregon) regions. All resources and configurations are optimized for these regions. You can use any region where Amazon Bedrock  is available.

📋 Workshop Sections
Module	Section	Description	Time
Lab	1. Create Amazon Cognito User Pool and a Cognito User	Create User Pool and configure authentication	15 min
2. Create a DynamoDB table	Set up database for image generation data	10 min
3. Create an AWS Lambda Function	Deploy backend logic for image processing	15 min
4. Create an Amazon API Gateway	Build REST API with secure endpoints	10 min
5. Create an AWS Amplify application	Deploy and configure web application	10 min
6. Test the application	Verify functionality	5 min
Workshop Total	Complete Image Editing Application		55 min
🎯 Workshop Outcome
Upon completion of this workshop, you will:

Gain knowledge of how to leverage various AWS services to build a web application
Learn how to deploy Amazon Cognito user pool for authentication
Learn how to create a DynamoDB table for persistent data storage
Learn how to deploy AWS Lambda functions with secure IAM policies
Learn how to create an API Gateway with Cognito integration
Deploy an AWS Amplify application for frontend hosting
Use the deployed web application to edit images with AI-powered prompts
🚀 Getting Started
Ready to build your serverless image editing application?

Proceed through the workshop modules in order:

Lab - Deploy a serverless web application to edit images using Amazon Bedrock

🧹 Cleanup
Don't forget to Cleanup the environment after completing the labs.

Note: If you have run this workshop in your own account we recommend you cleanup all the resources to avoid any further charges. If you participated in an AWS run workshop you do not have to complete this step.
License Summary
The documentation is made available under the Creative Commons Attribution-ShareAlike 4.0 International License. Download the LICENSE .

The sample code within this documentation is made available under the MIT-0 license. Download the LICENSE-SAMPLECODE .
