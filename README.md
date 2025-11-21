# AI-Powered Expense Tracker

A serverless expense management application that uses AI to automatically extract information from receipt images and provides intelligent financial insights.

## 🌟 Features

- **Smart Receipt Processing**: Upload receipt photos and let AI automatically extract amounts, merchant names, and categories using Amazon Rekognition OCR
- **AI Financial Insights**: Get personalized spending recommendations and analysis powered by Amazon Bedrock
- **Secure Authentication**: User signup and login with Amazon Cognito
- **Real-time Dashboard**: Visualize spending patterns with interactive charts and breakdowns by category
- **Serverless Architecture**: Built entirely on AWS serverless services for automatic scaling and cost efficiency
- **Responsive Design**: Clean, mobile-friendly interface built with React

## 🛠️ Tech Stack

**Frontend:**
- React 18
- Recharts for data visualization
- Hosted on AWS S3 + CloudFront

**Backend (AWS Services):**
- Amazon Cognito - Authentication
- API Gateway - RESTful API endpoints
- AWS Lambda - Serverless compute (Node.js/Python)
- Amazon DynamoDB - NoSQL database
- Amazon S3 - Receipt image storage
- Amazon Rekognition - OCR text extraction
- Amazon Bedrock - AI-powered insights
- CloudWatch - Monitoring and logging

## 🏗️ Architecture

[Include your architecture diagram here]

Event-driven serverless architecture:
1. User uploads receipt → S3
2. S3 event triggers Lambda function
3. Lambda calls Rekognition for text extraction
4. Parsed data stored in DynamoDB
5. AI analysis triggered on-demand via Bedrock

## 🚀 Live Demo

[Your live URL here]

**Test Account:** demo@expense-tracker.com / Demo123!

## 💡 Key Learning Outcomes

- Implemented serverless event-driven architecture
- Integrated multiple AWS services with proper IAM roles
- Built RESTful APIs with API Gateway and Lambda
- Applied AI/ML services for practical use cases
- Managed state with DynamoDB NoSQL patterns
- Deployed production-ready applications with CI/CD

## 📈 Future Enhancements

- [ ] Add budget setting and alerts
- [ ] Multi-currency support
- [ ] Export data to CSV/PDF
- [ ] Recurring expense detection
- [ ] Split expenses with friends
