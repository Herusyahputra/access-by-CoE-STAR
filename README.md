# access-by-CoE-STAR

# Access by CoE STAR 🚆🤖📱

A Smart Integrated Information System developed by the Center of Excellence (CoE) Smart Transportation and Robotics (STAR) – Telkom University. This system connects train station data, mobile access, and AI-driven services to enhance railway operations and user experience for both visitors and operators.

---

## 🔧 Features

1. **Big Plugin Integration (SI Module)**
   - Modular system core built as a centralized Service Integration (SI) plugin.
   - Facilitates extension with future modules for operations, admin, or analytics.

2. **Train Schedule Display**
   - Real-time visualization of train arrival/departure times at stations.
   - Integrated with KAI's schedule data via secured API.

3. **Integrated Database System**
   - Unified database schema for station information, user access logs, emergency chat history, and system analytics.
   - Built with PostgreSQL and connected using RESTful services.

4. **Mobile Application Access**
   - Cross-platform mobile app (Flutter) for passengers and operators.
   - Features include: schedule viewing, QR-based station entry, and emergency contact.

5. **KAI Access Integration**
   - Authenticated access via KAI's service API (OAuth 2.0).
   - Validates user tickets or staff credentials for system access.

6. **AI-Powered Emergency Chatbot**
   - AI agent to assist users during emergencies (fire, health, lost item).
   - Natural language understanding (NLU) using Rasa or OpenAI API.
   - Accessible via app and station kiosk.

---

## 📦 Tech Stack

- **Frontend**: Flutter (Mobile), React (Web Panel)
- **Backend**: Node.js + Express.js
- **AI Agent**: Rasa (or OpenAI API), custom intents
- **Database**: PostgreSQL + Redis (for session)
- **APIs**: REST + OAuth2 (KAI)
- **Deployment**: Docker, NGINX, Firebase Cloud Messaging

---

## 🚀 Getting Started

1. Clone the repository:
   ```bash
   git clone https://github.com/CoESTAR/access-system.git
   cd access-system
