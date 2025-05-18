Students Complaint Management System
A Flask-based web application for managing and tracking student complaints in an educational environment. This system allows students to submit complaints, and admins to view, assign, and update their statuses. It integrates with Azure services for file storage, database, monitoring, and logic apps for email notifications.

🔗 GitHub Repo: Capstone Project

🚀 Features
📝 Student complaint submission form

🖼️ File uploads stored securely in Azure Blob Storage

🗂️ Complaint data saved in Azure SQL Database

📬 Email notifications via Azure Logic Apps

📊 Admin dashboard to view, assign, and update complaints

🔐 Application Insights logging for monitoring and diagnostics

🛠️ Tech Stack
Layer	Technology
Backend	Python, Flask
Storage	Azure Blob Storage
Database	Azure SQL Database
Email Alert	Azure Logic App
Monitoring	Azure Application Insights
Authentication	(Handled via Flask sessions / keys)

📁 Folder Structure
bash

Capstone-project/
├── templates/
│   ├── submit_complaint.html
│   ├── student_dashboard.html
│   └── admin_dashboard.html
├── app.py
├── .env
└── requirements.txt

⚙️ Setup Instructions

1. Clone the repository
bash

git clone https://github.com/kg-512004/Capstone-project.git
cd Capstone-project

2. Set up a virtual environment
bash

python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate

3. Install dependencies
bash

pip install -r requirements.txt

4. Configure Environment Variables
Create a .env file in the project root with the following variables:

env
