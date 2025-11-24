# CodeGenie - AI-Powered Code Explanation & Generation Platform

CodeGenie is an AI-driven platform designed to help students, developers, educators, and teams work smarter and faster.  
It offers a seamless and secure environment for understanding, generating, and analyzing code across multiple programming languages, combining strong authentication, AI models, user tracking, feedback systems, and admin management in a single cohesive application.

---

## Why CodeGenie?

Modern developers read and write more code than ever before. CodeGenie simplifies this by providing:

- Clear, human-readable explanations of code snippets in English  
- High-quality AI-generated code from natural language prompts  
- A full history of user activity and generated content  
- A powerful admin dashboard with detailed analytics and control  
- Secure, role-based authentication and recovery tools  

It is the perfect environment for both learning and professional coding.

---

## Features

### 🔐 Authentication & Account Security
- Secure login/signup using JWT  
- Email and password verification with password hashing  
- Optional email verification and role-based permissions (Admin, User)  
- Access + refresh token handling with auto-refresh  
- OTP-based password recovery through Gmail SMTP  
- Optional security questions for fallback recovery  

---

## 📸 UI Preview

> Upload your image to the repo (e.g., `/images/login.png`)  
> Then replace the path below.

```markdown
![CodeGenie Login UI](images/352011fc-513d-4e7c-98f9-09ed197f83d0.png)
CodeGenie/
│
├── app.py                       # Streamlit frontend UI and navigation
│
├── backend/
│   ├── auth.py                  # JWT authentication and security logic
│   ├── generator.py             # AI code generation engine
│   ├── explainer.py             # Code explanation engine
│   ├── models.py                # Database schema and helpers
│   ├── history.py               # User activity logging
│   ├── feedback.py              # Reviews and sentiment analysis
│   └── admin.py                 # Admin controls and analytics
│
├── requirements.txt             # Python dependencies
├── .env.example                 # Environment variable template
└── README.md
1. Clone the repository
git clone https://github.com/yourusername/CodeGenie.git
cd CodeGenie
2. Configure environment variables

Copy .env.example → .env and fill in:

JWT secrets

Gmail SMTP credentials

Admin email

Database paths

3. Start the application
streamlit run app.py
🔒 Security

CodeGenie prioritizes security using:

JWT access & refresh tokens

Role-based access control

Password hashing

OTP recovery

Admin account limit

Full audit logging
