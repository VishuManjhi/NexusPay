📬 NexusPay
A subscription tracking and email reminder service built with the MEN stack (MongoDB, Express, Node.js) that uses Arcjet for API protection and Upstash QStash for scheduled email delivery.

🚀 Features
🔐 Secure API requests using Arcjet

⏰ Automated scheduling with Upstash 

📧 Sends email reminders before subscription renewals

🗄 MongoDB for storing subscription and user data

⚡ Express + Node.js backend for fast performance

🛠 Tech Stack

Backend: Node.js + Express

Database: MongoDB

Security: Arcjet

Scheduler: Upstash QStash

Email Service: (e.g., Nodemailer)

📦 Installation
Clone the repository

bash
Copy
Edit
git clone https://github.com/yourusername/subscription-system.git
cd subscription-system
Install dependencies

bash
Copy
Edit
npm install
Set environment variables
Create a .env file in the root directory and add:

ini
Copy
Edit
MONGO_URI=your_mongodb_uri
ARCJET_KEY=your_arcjet_key
QSTASH_TOKEN=your_qstash_token
EMAIL_USER=your_email_address
EMAIL_PASS=your_email_password
Run the server

bash
Copy
Edit
npm start
📋 API Endpoints
➕ Add a Subscription
POST /subscriptions

json
Copy
Edit
{
  "email": "user@example.com",
  "service": "Netflix",
  "renewalDate": "2025-08-20"
}
📄 Get All Subscriptions
GET /subscriptions

⚙ How It Works
Users add subscriptions with an email and renewal date.

QStash schedules reminder jobs based on the renewal date.

Arcjet protects API routes from abuse.

The system sends email reminders before the renewal date.

📜 License
MIT License – free to use and modify.

