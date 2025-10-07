🧭 **Introduction**  
Morning AI Assistant is a no-code automation project built with **Zapier**.  
It gathers unread emails and Google Calendar events, summarizes them using **AI by Zapier**, and sends you a personalized **morning plan** to your inbox every day.  

This helps you start the day with a clear picture of your tasks, meetings, and a focused 3-point action plan.  

---

## 🛠️ Project Type  
Automation / No-code / AI Assistant  

---

## 🚀 Deployed App  
- **Frontend**: Not Applicable  
- **Backend**: Zapier Automation (Zaps)  
- **Database**: Google services (Gmail + Calendar)  

---

## 📁 Directory Structure  
MorningAssistant/
│
├── Zap1/ # Collect unread emails + save to Digest
├── Zap2/ # Daily scheduled summary with AI
├── Visuals/
│ ├── Zap1.png
│ ├── Zap2.png
│ └── SampleEmail.png
├── README.md

---

## 📸 Screenshots
<img width="1914" height="821" alt="Screenshot 2025-10-07 110718" src="https://github.com/user-attachments/assets/d581f289-94c9-4d53-a393-061b4cf5de77" />
<img width="1917" height="823" alt="Screenshot 2025-10-07 110635" src="https://github.com/user-attachments/assets/fba9d5ea-44a5-44e1-9a3f-e637ba0df77d" />
<img width="999" height="667" alt="Screenshot 2025-10-07 105841" src="https://github.com/user-attachments/assets/86691fff-0655-4855-94ac-29b1d44cfb30" />

---

## ✨ Features  
- Collect unread emails daily from Gmail  
- Fetch calendar events for the day  
- Store email data in **Digest by Zapier**  
- Generate personalized summaries using **AI by Zapier**  
- Deliver daily briefing email with:  
  - **Email summaries**  
  - **Today’s Calendar Events**  
  - **3-Point Action Plan**  

---

## 🎯 Design Decisions or Assumptions  
- Zapier chosen to keep it **no-code and beginner-friendly**  
- Digest used to store and release multiple emails at once  
- AI by Zapier generates summaries and action plans in natural language  
- Google Calendar provides daily events  
- Output sent via Gmail for accessibility  

---

## 🧪 Installation & Getting Started  

1. Clone this repository (for docs + visuals):  
```bash
git clone https://github.com/yourusername/morning-assistant.git
cd morning-assistant
```
2. In Zapier:
   Zap 1: Gmail → Digest (store unread emails)
   Zap 2: Schedule → Release Digest → AI by Zapier → Gmail
3. Set schedule time (e.g., 8:00 AM daily)

---

## 📌 Usage
Every morning, you’ll receive an email like this:
Email Summaries
   “A Google alert requires action: Secure your account.”
   “3 new Discord messages waiting.”
Today’s Calendar
   10:00 AM: Team Meeting
   2:00 PM: Doctor’s Appointment
3-Point Action Plan
   Secure your Google account
   Check Discord messages
   Write a LinkedIn post

---

## 🔐 Credentials
Requires Gmail & Google Calendar integration with Zapier
AI by Zapier (beta) enabled in your account

---

## 🌐 APIs Used
Gmail (Zapier integration)
Google Calendar (Zapier integration)
AI by Zapier

---

## 📮 API Endpoints
Not applicable — handled internally by Zapier

---

## 🧰 Technology Stack
Zapier (No-code automation)
AI by Zapier (Natural Language Summarization)
Gmail (email summaries)
Google Calendar (event fetching)
