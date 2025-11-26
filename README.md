# Auto Email Marketing System

A smart email marketing workflow that sends daily automated product recommendations to subscribers.  
n8n selects top-performing products and sends them as email campaigns.

---

## 🚀 Features
- Fetches product list from API/RSS.
- Automatically selects the top 5 products by rating/price.
- Generates clean email templates.
- Sends emails to clients stored in Google Sheets.
- Works automatically every day.

---

## 🧩 Workflow Structure
**Node 1 — Select Top 5 Products**  
Filters the highest-rated items from the feed.

**Node 2 — Build Email Template**  
Formats products into HTML text for email.

**Node 3 — Gmail Send**  
Sends emails automatically to all contacts in Google Sheets.

---

## 🛠 Tools & Technologies
- n8n
- Google Sheets
- Gmail API
- Affiliate feeds

---

## 📄 Workflow File
Add your exported JSON here:
