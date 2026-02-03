# budget-tracker
M-PESA Spending Analyzer
#Overview
The M-PESA Spending Analyzer is a financial data analysis system designed to help users understand their personal transaction patterns and spending behavior.

The system processes transaction message data and converts it into structured financial insights, enabling better awareness of money flow, spending categories, and usage trends.

This project focuses on improving financial visibility and decision-making through automated transaction analysis and visualization.

#What the System Does

Accepts transaction message data as input

Extracts key financial details from transactions

Organizes spending into meaningful categories

Stores transaction records securely

Generates summaries and financial insights

Presents spending patterns through visual dashboards

The system aims to transform raw transaction data into understandable financial information.

#Setup Instructions
1. Clone Repository
git clone https://github.com/wales31/budget-tracker.git
cd mpesa-spending-analyzer

2. Create Virtual Environmen-
python -m venv venv
source venv/bin/activate   # Linux/Mac
venv\Scripts\activate      # Windows

3. Install Dependencies
pip install -r requirements.txt

4. Run Backend Server
cd backend
uvicorn main:app --reload


Server will run at:

http://127.0.0.1:8000

5. Access API Documentation
http://127.0.0.1:8000/docs


#Tech Stack

Backend:

-Python

-FastAPI

-SQLAlchemy

Database:
-PostgreSQL (scalable deployment)

Frontend
-HTML
-CSS
-JavaScript

#Data Processing
Python text processing
Transaction categorization logic
