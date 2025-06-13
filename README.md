# Neuverra AI Chatbot with Retrieval-Augmented Generation (RAG)

This project demonstrates the development of an AI-powered customer support chatbot for Neuverra, a fictional robotics and SaaS company. The chatbot uses Retrieval-Augmented Generation (RAG) techniques to ground responses in real customer support data, leveraging Microsoft Azure's AI Studio platform.

---

## 🏢 Business Scenario

Neuverra is a commercial supplier of industrial robotics hardware and SaaS platforms. As part of ongoing operations, Neuverra maintains customer support ticketing systems for resolving technical and operational issues. The objective of this AI chatbot is to assist users by providing natural language responses based on historical support ticket data.

---

## 📊 Dataset Summary

The support ticket dataset was generated using synthetic data tools and represents realistic scenarios. The original dataset included:

- ticket_id  
- customer_id  
- issue_description  
- ticket_status  
- submission_date  
- resolution_date  
- priority_level  
- assigned_support_agent

For optimal performance during RAG ingestion, the dataset was further cleaned, simplified, and converted into PDF format to serve as the grounding file for Azure AI Studio.

---

## 🛠 AI Development Approaches

Multiple methodologies were utilized to build and evaluate the AI chatbot within Microsoft Azure's cloud platform:

### 1️⃣ Azure Machine Learning Studio - Prompt Flow

One approach involved utilizing Azure's Prompt Flow feature for managing AI workflows, orchestrating prompts, and preparing data pipelines for AI retrieval tasks.

### 2️⃣ Azure AI Studio - Playground

Another approach leveraged Azure's Chat Playground interface for direct model grounding, conversational design, and custom prompt engineering.

### 3️⃣ Azure AI Studio - Assistants Playground (Final Build)

The final deployed solution was developed using Azure AI Studio’s Assistants Playground, which allowed for:

- Dataset ingestion via vector store
- File-based grounding of responses
- AI assistant instructions for data-restricted conversational output
- Successful RAG-based queries across multiple support scenarios

---

## 📷 Screenshots

The `/screenshots/` directory contains visual documentation of:

- Dataset preparation
- Data upload and ingestion into Azure AI Studio
- AI assistant configuration
- Live queries and sample RAG responses

---

## 🔎 Sample Queries

The chatbot successfully responded to queries including:

1. **"What are some of the most common types of issues reported by customers in these support tickets?"**
2. **"List several tickets that were reported as 'Urgent' priority."**
3. **"Are there multiple cases where firmware updates caused problems?"**
4. **"Summarize issues related to mobile control app failures."**

---

## 📂 Files Included

- `/datasets/`  
  - `Cleaned_Support_Tickets_UTF8.csv` (initial dataset)  
  - `Cleaned_Support_Tickets_UTF8-v2.csv` (AI-prepared dataset)
- `/pdfs/`  
  - `Cleaned_Support_Tickets_UTF8-v2.pdf` (PDF grounding file used for vector store ingestion)
- `/screenshots/`  
  - All major screenshots captured during development

---

## 💼 Professional Outcomes

This project demonstrates:

- Retrieval-Augmented Generation (RAG) AI architecture
- Natural language query design
- Microsoft Azure AI Studio platform utilization
- Data preparation for AI grounding
- Cloud-native AI application development

---

## 🔗 Technologies Used

- Microsoft Azure AI Studio (Prompt Flow, Playground, Assistants Playground)
- Azure Vector Store
- Synthetic Data Generation (Tonic Fabricate)
- PostgreSQL & SQL (initial data cleanup)
- CSV and PDF transformation workflows
- GitHub (documentation repository)

---
