🚀 E-Commerce Order Management with Salesforce CRM

A full-stack web application integrating an e-commerce platform with Salesforce CRM for seamless order and customer management.

✨ Features

🛍 Product Browsing – Customers can browse the product catalog.

🛒 Order Placement – Add products to cart and place orders.

📦 Order Tracking – Track order status in real-time.

🔗 Salesforce Integration:

👥 Create Leads automatically in Salesforce.

💼 Orders are synced as Opportunities.

🔄 Real-time order updates reflected on the dashboard.

🛠 Technologies Used
Layer	Technology	Icon
Backend	Python (Flask)	🐍
Frontend	HTML, CSS	🌐
Database	SQLite	🗄️
Salesforce API	REST API	☁️
⚡ Setup Instructions
Prerequisites

🐍 Python 3.7+

🛠 Salesforce Developer Account

🔑 Salesforce Connected App credentials

Installation

Clone the repository:

git clone https://github.com/Habeebkhan1312/E-Commerce-Order-Management-with-Salesforce-CRM.git
cd E-Commerce-Order-Management-with-Salesforce-CRM


Install dependencies:

pip install -r requirements.txt


Configure Salesforce Integration:
Set up your Salesforce Connected App and get Client ID & Client Secret.

Create .env file in root:

SALESFORCE_CLIENT_ID=your_client_id
SALESFORCE_CLIENT_SECRET=your_client_secret
SALESFORCE_USERNAME=your_salesforce_username
SALESFORCE_PASSWORD=your_salesforce_password
SALESFORCE_SECURITY_TOKEN=your_security_token


⚠️ Never commit .env to GitHub!

Initialize the Database:

python seed_db.py


Run the Application:

python app.py


Open your browser at http://localhost:5000 🖥️

👩‍💻 Usage

🛒 Browse products on the homepage.

✅ Add products to cart and checkout.

📊 Track order status after login.

🤝 Contributing

Contributions are welcome! Please:

Fork the repo

Create a new branch (git checkout -b feature-name)

Submit a Pull Request

📄 License

This project is licensed under MIT License – see LICENSE
 for details.
