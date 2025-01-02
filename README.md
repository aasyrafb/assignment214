# assignment214

Answer the following:
- Does SNS guarantee exactly once delivery to subscribers? 
1. No, SNS does not guarantee exactly-once delivery

- What is the purpose of the Dead-letter Queue (DLQ)? This a feature available to SQS/SNS/EventBridge.
1. Messages cannot be successfully delivered or processed.

- How would you enable a notification to your email when messages are added to the DLQ?
1. Create an SNS Topic.
2. Subscribe your email to the SNS Topic.
3. Configure the DLQ (SQS or SNS) to send notifications to the SNS Topic when messages are added.

Create a public github repository that has a README.md file, containing the above answers.

Submission is the url to your public github repository.