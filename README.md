# Inbox AI Agent

An intelligent AI-powered system built with n8n to reduce manual email handling and save 40+ hours for agencies.

---

## 🚨 Problem
- Over 67% of mid-sized agencies in India lose incoming leads due to late replies and poor follow-ups, allowing competitors to act faster.
- Teams spend 5+ hours every day managing emails instead of focusing on high-priority work that actually drives the business forward.
- Critical messages like client deadlines and offers often reach leadership late, causing missed opportunities and delayed decisions.

---

## 💡 Solution
- When an email arrives, the AI agent reads and understands the message, then takes the appropriate action automatically.
- New leads receive instant replies without human intervention, ensuring competitors never get a chance to respond first.
- High-priority emails are summarized and instantly notified to leadership, so they don’t need to check every message and can focus on productive work.

---

## ⚙️ How It Works
1. Incoming emails are monitored automatically
2. AI analyzes intent and context
3. n8n workflows trigger the appropriate actions
4. Emails are replied to, tagged, summarized, or routed automatically

---

## 📈 Impact
- ⏱ Saves **40+ hours per month**
- 📉 Reduces repetitive email tasks
- ⚡ Improves response time and efficiency
- 📊 Increases team productivity during work hours
- 🎯 Helps teams focus on high-priority tasks
- 🏆 Enables agencies to stay ahead of competitors without extra effort

---

## ▶️ How to Execute the Workflow

This repository contains an n8n workflow JSON file. Execution happens inside n8n, not on GitHub.

---

### Step 1: Import the Workflow into n8n
1. Open your n8n instance (local, cloud, or self-hosted)
2. Go to **Workflows**
3. Click **Import from File**
4. Select:
5. Click **Import**

---

### Step 2: Configure Required Credentials
For security reasons, credentials are not included in the JSON file.

You need to configure:
- Email credentials (IMAP / Gmail / Outlook)
- AI provider credentials (OpenAI or equivalent)
- Any third-party APIs used in the workflow

Red-highlighted nodes indicate missing credentials.

---

### Step 3: Test the Workflow
1. Use the **Manual Trigger** (if available)
2. Click **Execute Workflow**
3. Verify that:
- Emails are processed correctly
- AI classification works as expected
- Actions (reply, notify, route) are triggered

---

### Step 4: Activate the Workflow
Once testing is successful:
- Toggle the **Active** switch (top-right)
- The workflow will now run automatically whenever new emails arrive

---

## 🔄 What Happens During Execution
1. Incoming emails are monitored automatically
2. AI analyzes the email intent and context
3. n8n workflows determine the correct action
4. Emails are replied to, tagged, summarized, or routed accordingly

---

## 🔒 Security Notes
- No API keys or credentials are stored in this repository
- Always configure credentials directly inside n8n
- Replace any sensitive values with placeholders before exporting workflows

---

## 📦 Files Included
- `Inbox AI Agent.json` — main n8n workflow file


---

## 👨‍💻 Author
**Buvanesh**  
Automation Specialist  
📫 Email: buvaneshmg.io@gmail.com  
🔗 LinkedIn: www.linkedin.com/in/buvaneshselvaraj
