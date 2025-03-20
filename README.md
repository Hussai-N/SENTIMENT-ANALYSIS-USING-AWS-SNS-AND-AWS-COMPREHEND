# SENTIMENT-ANALYSIS-USING-AWS-SNS-AND-AWS-COMPREHEND

## Overview
This project implements sentiment analysis using AWS Comprehend and AWS Simple Notification Service (SNS). The system analyzes the sentiment of a given text and sends notifications based on the sentiment score.

## Features
- **Sentiment Analysis**: Uses AWS Comprehend to analyze text and determine whether the sentiment is positive, negative, neutral, or mixed.
- **Notifications**: AWS SNS is used to send notifications based on the sentiment result.

## Technologies Used
- **AWS Comprehend** for sentiment analysis
- **AWS SNS** for sending notifications

## Prerequisites
- An **AWS Account** with the necessary permissions
- AWS CLI configured with proper credentials

## Setup and Usage
1. **Create an SNS Topic** and subscribe an email or phone number to receive notifications.
2. **Use AWS Comprehend** to analyze text and obtain sentiment classification.
3. **Integrate SNS** to send sentiment results as notifications.

## Future Enhancements
- Store analysis results in DynamoDB
- Use S3 for bulk text processing

## License
This project is licensed under the MIT License. See `LICENSE` for details.

## Contributing
Feel free to fork this repository and submit pull requests for improvements!

## Contact
For any questions, reach out to `aadhilmd15@gmail.com`.
