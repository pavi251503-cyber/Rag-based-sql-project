🧠 RAG-Based SQL Query System (Human-in-the-Loop)

A secure and intelligent Text-to-SQL system using Retrieval-Augmented Generation (RAG) with human approval, role-based access control, and audit logging.

This project allows users to query databases using natural language while maintaining safety, transparency, and control.

 Project Features

- 🔐 JWT-based authentication  
- 👥 Role-Based Access Control (RBAC)  
- 🧠 RAG-based SQL generation  
- 🧍 Human-in-the-loop approval  
- 🧾 Complete audit logging  
- 🔒 SQL injection protection  
- ⚡ FastAPI backend  

🏗️ Architecture Overview
User
↓
Authentication (JWT)
↓
RAG Retrieval (Vector DB)
↓
SQL Generator (LLM)
↓
Human Approval
↓
Query Execution
↓
Audit Logs

 Run in Google Colab (Recommended)

🔹 Step 1: Open Google Colab
Go to 👉 https://colab.research.google.com  
Click New Notebook

🔹 Step 2: Clone the Repository
```python
!git clone https://github.com/pavi251503-cyber/Rag-based-sql-project.git
%cd Rag-based-sql-project
🔹 Step 3: Install Dependencies
!pip install -r requirements.txt
🔹 Step 4: Set Environment Variables
import os

os.environ["OPENROUTER_API_KEY"] = "your_openrouter_api_key"
os.environ["SECRET_KEY"] = "your_secret_key"
🔹 Step 5: Run FastAPI using ngrok
!pip install pyngrok
🔹 Step 6: Open API Docs

Open this in browser:
<your-ngrok-url>/docs

Default Login Credentials
Username	   Password
admin	        admin123
john.doe	   password123
jane.smith	  password123

Example Query
Show all customers who placed orders in the last month
