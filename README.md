# AWS-Sagemaker-Autopilot-Train-BERT-Model-for-customer-feedbacks

### Introduction
In this project, Amazon Sagemaker Autopilot is used to train a BERT (NLP) model. The model analyzed customer feedback and classify the messages into positive (1), neutral (0) and negative (-1) sentiment.

### Table of Contents

- [1. Review transformed dataset](#c1w3-1.)
- [2. Configure the Autopilot job](#c1w3-2.)
  - [2.1. Upload data to S3 bucket](#c1w3-2.1.)
  - [2.2. S3 output for generated assets](#c1w3-2.2.)
  - [2.3. Configure the Autopilot job](#c1w3-2.3.)
    - [Exercise 1](#c1w3-ex-1)
- [3. Launch the Autopilot job](#c1w3-3.)
    - [Exercise 2](#c1w3-ex-2)
- [4. Track Autopilot job progress](#c1w3-4.)
  - [4.1. Autopilot job description](#c1w3-4.1.)
  - [4.2. Autopilot job status](#c1w3-4.2.)
  - [4.3. Review the SageMaker processing jobs](#c1w3-4.3.)
  - [4.4. Wait for the data analysis step to finish](#c1w3-4.4.)
  - [4.5. View generated notebooks](#c1w3-4.5.)
    - [Exercise 3](#c1w3-ex-3)
    - [Exercise 4](#c1w3-ex-4)
- [5. Feature engineering](#c1w3-5.)
    - [Exercise 5](#c1w3-ex-5)
- [6. Model training and tuning](#c1w3-6.)
  - [6.1. Wait for training and tuning](#c1w3-6.1.)
    - [Exercise 6](#c1w3-ex-6)
  - [6.2. Compare model candidates](#c1w3-6.2.)
    - [Exercise 7](#c1w3-ex-7)
  - [6.3. Review best candidate](#c1w3-6.3.)
    - [Exercise 8](#c1w3-ex-8)
- [7. Review all output in S3 bucket](#c1w3-7.)
- [8. Deploy and test best candidate model](#c1w3-8.)
  - [8.1. Deploy best candidate model](#c1w3-8.1.)
  - [8.2. Test the model](#c1w3-8.2.)
