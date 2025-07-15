# Threat Monitoring System (TMS)

A lightweight, Flask-based web application designed to monitor login activities, detect anomalies, and alert administrators in real-time. Built with cybersecurity principles in mind, the system integrates log analysis, alerting, and database tracking into one unified platform.

## 🔐 Features

- **User Authentication** with login activity logging
- **Real-time log analyzer** for suspicious login patterns
- **Email alerts** for failed login attempts and anomalies
- **Supabase integration** for data storage
- **Redis integration (optional)** for rate limiting
- **Environment-based configuration** for sensitive keys and secrets

## 🛠 Tech Stack

- **Backend:** Flask (Python)
- **Database:** Supabase (PostgreSQL)
- **Email Notifications:** SMTP (Gmail)
- **Optional Tools:** Redis (rate limiting), Flask-Mail

## ⚙️ Setup Instructions

1. **Clone the repository:**
   ```bash
   git clone https://github.com/JestinEapen846/TMS.git
   cd TMS
