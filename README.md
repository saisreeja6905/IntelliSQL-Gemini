# IntelliSQL: Intelligent SQL Querying with LLMs Using Gemini Pro

IntelliSQL is an AI-powered Natural Language to SQL (NL2SQL) system that allows users to query databases using plain English instead of writing SQL manually.

The application uses Google Gemini Pro to understand user questions, generate SQL queries, execute them on a SQLite database, and display results through an interactive Streamlit web interface.

This project demonstrates how Large Language Models can simplify database interaction and enable conversational data analytics.

---

## Features
- Convert natural language questions into SQL queries
- Automatic query execution on database
- Real-time results display
- Interactive Streamlit interface
- Beginner-friendly database interaction
- Works without prior SQL knowledge

---

## Tech Stack
- Python
- Streamlit
- SQLite
- Google Gemini API
- Prompt Engineering
- Natural Language Processing (NLP)

---

## Project File Structure

IntelliSQL-Intelligent-SQL-Querying-with-LLMs-Using-Gemini/
│
├── 1. Project Initialization and Planning Phase/
│   ├── Problem Statements.docx
│   ├── Project Planning.docx
│   └── Project Proposed Solution.docx
│
├── 2. Data Collection and Preprocessing Phase/
│   ├── Data Exploration and Preprocessing.docx
│   ├── Data Quality Report.docx
│   └── Raw Data Sources and Data Quality Report.docx
│
├── 3. Model Development Phase/
│   ├── Feature Selection Report.docx
│   ├── Initial Model Training Code & Validation.docx
│   └── Model Selection Report.docx
│
├── 4. Model Optimization and Tuning Phase/
│   └── Model Optimization and Tuning Phase.docx
│
├── 5. Project Files Submission and Documentation/
│   ├── app.py
│   └── data.db
│
├── 6. Project Demonstration/
│   └── Final Project Report.pdf
│
└── README.md


---

## System Workflow
1. User enters query in English
2. Gemini Pro converts it into SQL
3. SQL runs on SQLite database
4. Results shown instantly in UI

---

## Installation

1. Clone Repository
git clone https://github.com/saisreeja6905/intellisql.git
cd intellisql

2. Install Dependencies
pip install streamlit python-dotenv google-generativeai
OR
pip install -r requirements.txt

3. Add API Key
Create a .env file in project folder:
API_KEY=your_gemini_api_key_here

Get API key from:
https://aistudio.google.com/app/apikey

---

## Database Setup
Create the database and sample data:
python create_db.py

---

## Run Application
streamlit run app.py

Open in browser:
http://localhost:8501

---

## Example Queries
- Show all students
- Students in MCom class
- Count total records
- Students scoring above 80 marks
- List students placed in TCS

---

## Future Improvements
- Multiple table support
- Upload custom datasets
- Chat history memory
- Support for MySQL/PostgreSQL
- Schema auto detection

---

## Use Cases
- Educational database learning
- Conversational analytics
- Business data exploration
- Non-technical database access

---

## Author
Developed as part of AI/ML Internship Project
