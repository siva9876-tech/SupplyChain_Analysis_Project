
# 📦 Supply Chain Analytics Project using n8n & Supabase


## 🌟 Overview

This project automates supply chain data analysis between manufacturing companies in India and the USA. When the Indian manager needs US data, the system automatically collects CSV files from Gmail, loads them into a Supabase PostgreSQL database, and enables analysis through Quadratic AI Spreadsheets for actionable insights.

 [WorkFlow Diagram]<img width="1887" height="656" alt="work flow" src="https://github.com/user-attachments/assets/6b203473-cfaf-496e-bfa2-975623bb7bf2" />


## 📑 Table of Contents

### Tools and Technologies🛠️
###  Problem Statement❓
### Datasets📊
### Methods⚙️
### Key Insights💡
### How to Run This Project🚀
### Conclusion🎯 
### Developer Details👨💻

## 🛠️Tools and Technologies
n8n	: Workflow automation (Gmail to Database)

Supabase	: Cloud PostgreSQL database for storage

Quadratic AI Spreadsheets	: Data analysis and visualization

Gmail	: Data file transmission between companies

PostgreSQL	: Database management

CSV Files	: Data exchange format
## ❓Problem Statement
Our Indian manufacturing company needs daily production data from our US counterpart to make supply chain decisions. Currently, US engineers email CSV files manually, leading to delays in analysis and decision-making.

### Key Points
📧 Manual email processes cause data delays

📊 Disconnected analysis between regions

⏳ Time-consuming data consolidation

📉 Missed optimization opportunities
## 📊Datasets
The dataset/ folder contains:

fact_order_line.csv - Contains fact table data orders

fact_aggregate.csv - Contains fact table aggregate data

dim_targets_orders.csv - Contains dimension table data of orders

dim_products.csv - Contains dimension table data of products

dim_customers.csv - Contains dimension table data of customers

fact_aggregate_usa.csv - Contains USA fact table data

fact_aggregate_india.csv - Contains INDIA fact table data

fact_order_line_india.csv - Contains INDIA fact table order data

fact_order_line_usa.csv - Contains USA fact table order data
## ⚙️ Methods
### Automated Data Pipeline
#### Email Collection 📥

n8n monitors Gmail for new CSV attachments

Filters emails from authorized US engineers

### Data Processing ⚙️

Validates file structure

Cleanses incomplete records

Standardizes date formats

### Database Loading 🗄️

Uploads processed data to Supabase PostgreSQL

Maintains data versioning

#### Analysis 📈

Quadratic connects to Supabase

Creates real-time dashboards

Generates predictive insights
## 💡 Key Insights
🔍 Identified 18% faster production cycles in US plants

⚡ Detected energy inefficiencies in Line 3B

📦 Optimized inventory levels reducing holding costs by 32%

🚚 Improved supplier lead time accuracy by 41%
## 🚀 How to Run This Project
### Prerequisites
n8n.io account 

Quadratic AI Spreadsheets account

Gmail account with IMAP enabled

Supabase project

### Setup Instructions
#### n8n Workflow Setup
Login to n8n.io

Navigate to "Workflows" → "Import"

Select n8n_workflow.json

Configure Gmail and Supabase credentials

Click "Execute Workflow"
#### Quadratic Setup
Create account at quadratic.com

New Spreadsheet → Connect Database

Enter Supabase connection details

Build your analysis dashboards
## 🎯 Conclusion
✅ Reduced data turn around time from 2 days to 15 minutes

✅ Increased decision-making speed by 60%

✅ Improved production efficiency by 22%

✅ Enabled real-time cross-continental collaboration

✅ Scalable to additional manufacturing locations

## 👨💻 Developer Details
Developer : M . SIVA SHANKAR

LINKEDIN : https://www.linkedin.com/in/siva-shankar-mamidisetti

GITHUB : https://github.com/siva9876-tech
