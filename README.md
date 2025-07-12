# 🌟 Limerick City Digital Assistant  
**Serverless AI City Guide & Hotel Booking on AWS**

---

## ✨ Overview

A modern, serverless AI-powered assistant for Limerick, Ireland—helping users discover attractions, check hotel room availability, and book rooms instantly via chat. This project showcases advanced AWS and AI/ML expertise with a fully cloud-native, scalable design.

---

## 🚀 Key Features

- **Conversational AI:** Ask about places, events, or hotels in Limerick and receive instant, personalized answers.
- **Live Hotel Booking:** Check room availability and book a room at the Strand Hotel directly from chat.
- **Instant Notifications:** Get booking confirmations via email, automatically.

---

## 🧠 Cloud & AI/ML Skills Demonstrated

- **Amazon Bedrock:** Conversational AI agent (Claude 3 Sonnet) and knowledge base.
- **AWS Lambda:** Stateless backend logic for availability checks and booking workflows.
- **DynamoDB:** Fast, scalable storage for hotel inventory and bookings.
- **Amazon S3:** Storage for guides, brochures, and directories.
- **Amazon SES:** Real-time booking confirmation emails.
- **IAM:** Secure, least-privilege access for all resources.

---

## 🛠️ AWS & Machine Learning Components

| Service / Tool         | Category            | Purpose / Role in Project                                                                                 |
|------------------------|---------------------|-----------------------------------------------------------------------------------------------------------|
| Amazon Bedrock         | AI/ML (LLM)         | Conversational AI agent (Claude 3 Sonnet) for chat and intent parsing                                     |
| Bedrock Knowledge Base | AI/ML (RAG)         | Retrieval-augmented generation using Titan Text Embedding V2 for semantic search over city PDFs           |
| Amazon S3              | Cloud Storage       | Stores city guides, hotel brochures, and food directories as PDF files                                    |
| AWS Lambda             | Serverless Compute  | Backend logic for room availability lookup and booking workflows                                          |
| DynamoDB               | NoSQL Database      | Persists hotel room inventory and booking records                                                         |
| Amazon SES             | Cloud Messaging     | Sends booking confirmation emails to users                                                                |
| IAM                    | Security            | Manages least-privilege roles and access policies for all AWS resources                                   |
| YAML Action Groups     | Integration         | Maps Bedrock agent actions to Lambda ARNs for orchestration                                               |
| CloudWatch (implied)   | Monitoring          | Logs Lambda and agent activity for debugging and monitoring                                               |
| Titan Text Embedding V2| AI/ML (Embedding)   | Converts document passages into vector embeddings for semantic search in Bedrock Knowledge Base           |

---

## 🏗️ Architecture Diagram

![Architecture](https://github.com/TarunBezawada11/Limerick-City-AI-Agent/blob/main/Final%20Architecture.png)

---

## ⚡ How It Works

1. **User asks a question** (e.g., “What’s happening in Limerick?” or “Is a river-view room available?”).
2. **AI agent responds** with up-to-date info or room availability.
3. **Booking request:** User books a room via chat.
4. **Workflow:** Lambda functions check inventory, process bookings, and trigger email notifications.

---

