# AI-Powered SEO Audit Tool

A simple AI-powered SEO audit tool built using **n8n Cloud**, **OpenAI**, and a lightweight HTML frontend.

Users can submit a website URL and their email address to receive:
- Technical SEO analysis
- Content quality insights
- Actionable recommendations

The audit is processed via an n8n automation and delivered by email.

---

## 🧩 How it Works

1. User enters website URL + email on the frontend
2. Frontend sends data to an n8n Webhook
3. n8n workflow:
   - Scrapes the website
   - Runs AI-powered SEO analysis
   - Formats the results
   - Sends the report via email

---

## 📁 Project Structure

🔗 Live Demo:  
https://thenoobmlengineer.github.io/seo-audit-tool/
