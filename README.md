# AI Blog Writer – n8n Automation

This project is an AI-powered blog drafting automation built using n8n.

It takes a blog topic and target audience from Google Sheets, sends it to an AI model, and writes back a structured blog draft automatically.

## 🔹 Features

- Reads input from Google Sheets  
- Generates 800–1200 word blogs using AI  
- Enforces structured format:
  - Title  
  - Hook  
  - Introduction  
  - 3–4 subheadings  
  - Conclusion  
  - Takeaway  
- Writes output back to the same sheet  
- Fully automated  
- Live-demo ready
  
## 🔹 Tech Stack

- n8n (Automation)
- Google Sheets
- OpenRouter API (Mistral LLM)
  
## 🔹 Workflow Overview

1. User enters:
   - Topic
   - Target Audience  
   into Google Sheet

2. n8n:
   - Reads the row
   - Sends prompt to AI
   - Receives generated blog
   - Updates same row with output
  
   ## 🔹 How to Run Locally

1. Start n8n:

   n8n

2. Open in browser:

  http://localhost:5678

3. Import workflow JSON

4. Add credentials:
   - Google Sheets OAuth
   - OpenRouter API key

5. Add a topic in Google Sheet

6. Execute workflow

## 🔹 Output Format

- Professional blog format  
- Plain text (no markdown)  
- Product-manager friendly tone  
- 800–1200 words

## 🔹 Security

- No API keys stored in repository  
- All secrets handled using n8n credentials  
- Users must add their own credentials after import

## 🔹 Demo

- Add a new row in Google Sheet  
- Run workflow  
- Blog is generated automatically
  
## ⭐ Use Case

Built as part of an AI automation assignment to demonstrate:
- Prompt engineering  
- API integration  
- Automation design  
- Production-style workflow building

## 👤 Author

Zalak Rajvanshi


