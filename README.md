E-Commerce Order Management with Salesforce CRM

This full-stack web application integrates an e-commerce platform with Salesforce CRM, enabling seamless order management and customer relationship management.

Features

Product Browsing: Customers can browse a catalog of products.

Order Placement: Customers can place orders through the platform.

Order Tracking: Customers can track the status of their orders.

Salesforce Integration:

New customers are automatically created as Leads in Salesforce Sales Cloud.

Orders are automatically created as Opportunities in Salesforce.

Real-time order status updates are synced back to the dashboard.

Technologies Used

Backend: Python (Flask)

Frontend: HTML, CSS

Database: SQLite

Salesforce Integration: Salesforce REST API

Setup Instructions
Prerequisites

Python 3.7 or higher

Salesforce Developer Account

Salesforce Connected App credentials (Client ID and Client Secret)

Installation

Clone the Repository:

git clone https://github.com/Habeebkhan1312/E-Commerce-Order-Management-with-Salesforce-CRM.git
cd E-Commerce-Order-Management-with-Salesforce-CRM


Install Dependencies:

pip install -r requirements.txt


Configure Salesforce Integration:

Set up your Salesforce Connected App and obtain the Client ID and Client Secret.

Set Up Environment Variables:

Create a .env file in the root directory and add the following variables:

SALESFORCE_CLIENT_ID=your_client_id
SALESFORCE_CLIENT_SECRET=your_client_secret
SALESFORCE_USERNAME=your_salesforce_username
SALESFORCE_PASSWORD=your_salesforce_password
SALESFORCE_SECURITY_TOKEN=your_security_token


Initialize the Database:

python seed_db.py


Run the Application:

python app.py


The application will be accessible at http://localhost:5000.

Usage

Browse Products: Navigate to the homepage to view available products.

Place Orders: Select products and proceed to checkout to place an order.

Track Orders: Log in to view and track the status of your orders.

Contributing

Contributions are welcome! Please fork the repository, create a new branch, and submit a pull request with your proposed changes.

License

This project is licensed under the MIT License - see the LICENSE
 file for details.
