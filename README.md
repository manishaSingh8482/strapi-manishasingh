# strapi-internship-manishasingh
manishasingh githubrepo for task 1


# Strapi Project Setup (Local)

This project demonstrates a basic **Strapi v5** setup running locally, including:
- Admin Panel
- Custom Collection Type
- Content creation
- Public REST API access

It was created as part of a hands-on learning task to understand Strapi fundamentals.

---

## 🛠 Prerequisites

Make sure you have the following installed:

- **Node.js**: v20.x (required for Strapi v5)
- **npm**: v9+ (comes with Node.js)
- **Git**

> Recommended: Use **NVM (Node Version Manager)** to manage Node versions.

---

## 🚀 Project Setup

### 1️⃣ Clone the repository
```bash
git clone https://github.com/<your-username>/strapi-task.git
cd strapi-task  

2️⃣ Install dependencies
npm install

3️⃣ Start Strapi in development mode
npm run develop


Strapi will start locally and the Admin Panel will be available at:

http://localhost:1337/admin

🔐 Admin Panel

On first run:

Open the Admin Panel URL

Create the first admin user

Log in to access Strapi dashboard

🧩 Content Type Created
Collection Type: First_entry

Fields:

Task_1 – Text (Short Text)

This content type was created using the Content-Type Builder.

🧩 Content Type Created
Collection Type: First_entry

Fields:

Task_1 – Text (Short Text)

This content type was created using the Content-Type Builder.

🔒 Permissions Configuration

To allow public access:

Go to Settings → Users & Permissions → Roles

Select Public

Enable:

find

findOne

Save changes

📂 Project Structure (Simplified)
strapi-task/
├── config/
├── database/
├── src/
├── package.json
├── package-lock.json
└── .gitignore


Note: node_modules and .env are intentionally excluded from version control.

🧪 Development Notes

Database: SQLite (default local database)

Environment: Local development

API tested via browser
