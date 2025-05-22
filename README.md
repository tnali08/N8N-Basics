# N8N-Basics
This repository will give you a fundamentals and hands-on experience on N8N Learnings
Introductory:
What is N8N why do we use it?
It is an open source automation tool that lets you connect different apps, services and databases without writing tons of code
It helps to automate repetitive tasks and build mini backends
It automates the connection, Sync airtable entries using google sheets, Uses Open-AI to reply to the customers, it builds webhook triggers which actually stores and process the data and it also extract API Pipelines to transsform Database

why people use N8N?
it is an open source for free, it has 400+ integrations and cloud services available, easy to access, secured full control over data

How it works?

Trigger--> Function Node--> slack--> save to database

who uses it?

Developers, Startups, Devops and Product Teams

Showing a example workflow of simple automation workflow:

![image](https://github.com/user-attachments/assets/5ba66b67-5796-4619-8138-79999e9bb7eb)
The above error message explains about the problem in node
Firstly, it is important to connect and enable the chat modelsub-node

![image](https://github.com/user-attachments/assets/5b8c324e-a32c-46e2-91f1-9ab9ea425fae)

Response from the enabled  chat mode using AI agent!!



 n8n Workflow steps:

Go to n8n Editor → Import workflow.

Paste this JSON or upload the .json file.

Replace "YOUR_CREDENTIAL_ID" with your actual OpenAI credential ID example: (tej27_openAI) in n8n.

Activate the webhook trigger and use a tool like Postman to test:

POST to http://localhost:5678/webhook/chat-message

Body: { "message": "Hello, how are you?" }

