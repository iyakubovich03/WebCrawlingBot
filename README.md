# 🚀 Web Crawling Job Alert Bot

This project automatically monitors job platforms and sends instant Telegram alerts when new software engineering internship opportunities are posted.

Once deployed, the crawler runs continuously using GitHub Actions, allowing you to apply to new roles immediately without manually browsing job sites.

---

## ✅ Prerequisites

- GitHub account  
- Telegram account  
- Basic knowledge of GitHub repositories  

---

## 📦 Setup Instructions

### 1. Create Your Repository

1. Create a new GitHub repository.
2. Copy all files from this repository into your new repository.
3. Push the files to GitHub.

---

### 2. Create a Telegram Bot

1. Open Telegram and search for **@BotFather**.
2. Start a chat and run `/start`.
3. Create a new bot using `/newbot`.
4. Follow the instructions.
5. Copy the bot token provided (this is your `TELEGRAM_TOKEN`).

---

### 3. Get Your Chat ID

1. Start a chat with your new bot.
2. Send any message (for example: `Hello`).
3. Open the following URL in your browser:

### 4. Add GitHub Secrets

In your repository:

1. Go to **Settings → Secrets and variables → Actions**
2. Click **New repository secret**
3. Add the following secrets:

| Name           | Value          |
|----------------|----------------|
| TELEGRAM_TOKEN | Your bot token |
| CHAT_ID        | Your chat ID   |

---

### 5. Run the Workflow

1. Go to the **Actions** tab.
2. Select the crawler workflow.
3. Click **Run workflow** to trigger it manually once.

After the first run, the workflow will automatically execute every 15–30 minutes.

---

## 📬 How It Works

- The crawler scans job platforms for new listings.
- It filters and removes duplicate postings.
- When a new job is detected, you receive an instant Telegram notification.
- You can apply immediately without wasting time searching manually.

---

## 🎯 Benefits

- Fully automated job monitoring  
- Real-time alerts  
- Cloud-based execution  
- No manual searching required  

---

## ⚠️ Disclaimer

This project is intended for educational and personal use. Please respect the terms of service of the websites you crawl.

---

## 📫 Support

If you have questions or suggestions, feel free to open an issue or submit a pull request.
