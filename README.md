# 📬 NexusPay

A **subscription tracking and email reminder** service built with the **MEN stack** (MongoDB, Express, Node.js) that uses **Arcjet** for API protection and **Upstash QStash** for scheduled email delivery.

## 🚀 Features
- 🔐 **Secure API requests** using [Arcjet](https://arcjet.com/)
- ⏰ **Automated scheduling** with [Upstash QStash](https://upstash.com/qstash)
- 📧 Sends **email reminders** before subscription renewals
- 🗄 **MongoDB** for storing subscription and user data
- ⚡ **Express + Node.js** backend for fast performance

## 🛠 Tech Stack
- **Backend:** Node.js + Express
- **Database:** MongoDB
- **Security:** [Arcjet](https://arcjet.com/)
- **Scheduler:** [Upstash QStash](https://upstash.com/qstash)
- **Email Service:** Nodemailer (or preferred provider)

## 📦 Installation

```bash
# 1️⃣ Clone the repository
git clone https://github.com/yourusername/subscription-system.git
cd subscription-system

# 2️⃣ Install dependencies
npm install

# 3️⃣ Create a .env file in the root directory and add:
MONGO_URI=your_mongodb_uri
ARCJET_KEY=your_arcjet_key
QSTASH_TOKEN=your_qstash_token
EMAIL_USER=your_email_address
EMAIL_PASS=your_email_password

# 4️⃣ Run the server
npm start
