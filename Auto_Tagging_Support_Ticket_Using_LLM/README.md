# 🏷️ Auto-Tagging Support Tickets Using LLM
Objective: Automatically tag support tickets into categories using a large language model (LLM).

## 📋 Project Overview

This project automatically categorizes customer support tickets using Large Language Models (LLMs). It compares three different approaches:
- **Zero-shot learning** - No examples provided
- **Few-shot learning** - With example demonstrations
- **Fine-tuned model** - Custom trained on domain data

The system outputs the **top 3 most probable categories** for each support ticket with confidence scores.

## 🎯 Features
- ✅ **Prompt engineering**
- ✅ **LLM-based text classification**
- ✅ **Zero-shot, few-shot Learning**
- ✅ **Multi-class classification** 
- ✅ **Probability ranking** for all categories
- ✅ **Entropy-based uncertainty measurement**

## 📊 Dataset

**Source:** [Customer Support on Twitter Dataset](https://www.kaggle.com/datasets/thoughtvector/customer-support-on-ticket)

**Size:** 
- Main dataset: 504,403 KB (twcs.csv)
- Sample dataset: 17 KB (sample.csv)

**Categories:**
| Category | Description |
|----------|-------------|
|"billing": "Issues related to payments, refunds, charges, subscriptions, pricing"|
|"technical": "Technical problems, bugs, app/website not working, errors, crashes"|
|"account_access": "Login issues, password reset, account locked, profile management"|
|"product_inquiry": "Questions about product features, specifications, availability"|
|"delivery_shipping": "Issues with order delivery, shipping delays, lost packages"|
|"return_refund": "Return requests, refund processing, exchange requests"|
|"customer_service": "General complaints, poor service, agent behavior"|
|"feature_request": "Suggestions for new features or improvements"|
|"cancellation": "Account or subscription cancellation requests"|

### Prerequisites

```bash
Python 3.8+,Pandas,Numpy,Sklearn
OpenAI API key (paid subscription)
Kaggle account (for dataset)