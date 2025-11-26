<p align="center">
   <img width="931" height="907" alt="Screenshot 2025-11-26 115446" src="https://github.com/user-attachments/assets/8ec0495b-8988-43fa-97bb-2cc82430b54f" />

</p>


<p align="center">
  <b>AI-Powered Code Generation & Explanation Platform</b>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/build-passing-brightgreen"/>
  <img src="https://img.shields.io/badge/python-3.10%2B-blue"/>
  <img src="https://img.shields.io/badge/license-MIT-yellow"/>
</p>

---



# 🧠 CodeGenie  
Futuristic AI Code Explainer & Intelligent Code Generation Platform  
Helping developers understand code the way humans do — with clarity, structure, and context.

---

## 🔗 Quick Links

| Category | Link |
|----------|------|
| 🐳 Docker Support | Yes |
| 💡 Supported Languages | Python · JavaScript · SQL |


---


## 🌟 Introduction

Most AI code assistants generate answers that sound correct but lack real understanding of structure, intent, and flow.

CodeGenie solves this using:

✅ AST-powered Python analysis  
✅ Model-driven JS & SQL reasoning  
✅ Context-aware explanation logic  

Originally created during an **Infosys Springboard Internship**, it has evolved into a practical engineering-grade AI assistant.

---



## 🚀 Key Features

### 👤 User Features

| Feature | Description |
|---------|-------------|
| 🔐 JWT Authentication | Signup, login, refresh tokens |
| 📧 OTP Recovery | Gmail SMTP password reset |
| 🧠 AST Code Explanation | Structure-aware understanding |
| ✍️ Text → Code | Generate Python/JS/SQL code |
| 🌐 Language Support | Python, JavaScript, SQL |
| ⭐ Feedback System | Ratings + comments |
| 🕘 History Tracking | Full logs + timestamps |
| 🔧 Profile Settings | Change password + theme |

---

### 🛠 Admin Features

✅ Manage roles (max 2 admins)  
✅ Track user activity  
✅ Monitor language popularity  
✅ Trending prompts analytics  
✅ Feedback sentiment + word clouds  
✅ Global search  
✅ System + model metrics  

---



## 🧩 Architecture Overview

### Includes:

- Streamlit UI  
- Python backend services  
- Transformer model inference  
- Python AST parsing  
- SQLite persistent DB  
- JWT authentication  
- OTP email recovery  

---



## 🛠 Tech Stack

| Layer | Technology |
|-------|------------|
| Frontend | Streamlit |
| Backend | Python |
| Models | HuggingFace Transformers |
| Parsing | Python AST |
| Database | SQLite |
| Auth | JWT + bcrypt |
| Email OTP | Gmail SMTP |
| Deployment | Docker |
| Optimization | 4-bit quantization |

---

## 🤖 Models Used

| Model | Purpose |
|-------|---------|
| Phi / Gemma | Python explanation |
| CodeBERT | JS/SQL analysis |
| CodeLlama | Code generation |
| DeepSeek-Coder | Multi-language generation |
| StarCoder2 | Pattern rewrite |
| AST Engine | Structural code understanding |

---


## 📂 Project Structure

```
CodeGenie/
│
├── app.py                     # Streamlit UI
│
├── backend/
│   ├── auth.py                # JWT auth + roles + OTP
│   ├── generator.py           # Code generation engine
│   ├── explainer.py           # AST explanation logic
│   ├── ast_engine.py          # Python AST parser
│   ├── history.py             # Query logging
│   ├── feedback.py            # Ratings + analytics
│   ├── admin.py               # Admin APIs
│   └── models.py              # SQLite models
│
├── requirements.txt
├── Dockerfile
├── .env.example
│
└── screenshots/               # UI screenshots + banner + dividers
```

---


## ❄️ Installation & Setup

### Requirements
✅ Python 3.10+  
✅ Git  
✅ (Optional) Docker  

### Install
```bash
git clone https://github.com/kalyani20017/Infosys_Springboard
cd Infosys_Springboard
pip install -r requirements.txt
```

### Environment Setup
```
JWT_SECRET_KEY=your_key_here
SMTP_EMAIL=your_email_here
SMTP_PASSWORD=your_app_pass_here
```

### Run App
```bash
streamlit run app.py
```

---



## 📝 Usage Guide

✅ Login / Signup  
✅ Choose mode: Generate or Explain  
✅ Select language  
✅ Enter prompt or code  
✅ View structured output  
✅ Rate result  
✅ Browse history  

---



## 📸 Screenshots

### 1️⃣ Login Page
<img width="1591" height="728" alt="login_page" src="https://github.com/user-attachments/assets/6058d382-a1dc-4c43-9a0c-228b13e6261d" />


### 2️⃣ Sign Up Page
<img width="1596" height="728" alt="sign_up " src="https://github.com/user-attachments/assets/addf1aec-ad11-4ca3-ae0a-a7dbb7f44866" />


### 3️⃣ AI Chat Assistant
<img src="screenshots/ai_chat.png"/>

### 4️⃣ Code Explainer
<img src="screenshots/code_explainer.png"/>

### 5️⃣ Code Generator
<img src="screenshots/code_generator.png"/>

### 6️⃣ History Page
<img src="screenshots/history_page.png"/>

### 7️⃣ Profile Page
<img src="screenshots/profile_page.png"/>

### 8️⃣ Password Recovery Page
<img width="1598" height="733" alt="password_recovery" src="https://github.com/user-attachments/assets/bf42bb11-35d9-477b-92f6-d27c3dbf3bc8" />


---


## 🧭 Roadmap

✅ Docker deployment  
✅ GPU acceleration  
🔜 VS Code extension  
🔜 Visual AST Explorer  
🔜 GitHub repo code ingestion  
🔜 Export explanations as PDF  
🔜 Dependency graph visualizer  

---


## 📜 License

MIT License

---

<p align="center">
“A good education builds confidence, improves knowledge, and shapes dreams.”
</p>
