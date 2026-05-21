<div align="center">

# Hey, I'm Norbert Shema 👋🏾

[![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&size=24&duration=3000&pause=1000&color=3F8CFF&center=true&vCenter=true&width=800&lines=Software+Engineer+%F0%9F%9A%80;Cloud+%26+Backend+Builder+%E2%98%81%EF%B8%8F;ML+%26+AI+Tinkerer+%F0%9F%A4%96;ColorStack+Fellow+%F0%9F%8F%86)](https://git.io/typing-svg)

**I am all about code, working with smart AI models, and always learning.**

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/norbert-shema-9714681a4/)
[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:shemanorbert11@gmail.com)

</div>

---

## About Me

```python
class Norbert:
    def __init__(self):
        self.name       = "Norbert Shema"
        self.role       = "Software Engineer"
        self.education  = "New grad Software Engineering @ Husson University (2026)"
        self.location   = "Charlotte, North Carolina 📍"
        self.fellowship = "ColorStack Fellow — Top Black/Latinx engineers in the U.S. 🏆"

        self.stack      = ["Python", "Java", "SQL", "JavaScript", "Go", "C++"]
        self.cloud      = ["AWS", "Firebase", "Azure", "Docker", "CI/CD"]
        self.ml         = ["XGBoost", "Random Forest", "Scikit-learn", "Pandas", "NumPy"]

        self.currently  = "Scaling cloud systems & exploring AI-driven tooling 🔭"
        self.fun_fact   = "I keynoted to 200+ tech professionals about AI & education equity 🎤"

    def hello(self):
        print(f"Hi! I'm {self.name} — I build things that scale, learn, and matter.")

me = Norbert()
me.hello()
```

---

## 🛠️ Tech Stack

**Languages**

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=java&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![Go](https://img.shields.io/badge/Go-00ADD8?style=for-the-badge&logo=go&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=cplusplus&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)
![HTML/CSS](https://img.shields.io/badge/HTML%2FCSS-E34F26?style=for-the-badge&logo=html5&logoColor=white)

**Frameworks & Libraries**

![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white)
![Airflow](https://img.shields.io/badge/Airflow-017CEE?style=for-the-badge&logo=apacheairflow&logoColor=white)
![Scikit-learn](https://img.shields.io/badge/Scikit--learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white)

**Cloud & DevOps**

![AWS](https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazonaws&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white)
![Firebase](https://img.shields.io/badge/Firebase-FFCA28?style=for-the-badge&logo=firebase&logoColor=black)
![Azure](https://img.shields.io/badge/Azure-0078D4?style=for-the-badge&logo=microsoftazure&logoColor=white)

---

## 🚀 Featured Projects

### 🐾 ScoobySquad AI Agent *(Live)*
> `Python` `Next.js` `Javascript` `n8n` `Google Gemini` `Supabase` `PostgreSQL` `Google OAuth` `Sweep&Go API.`

🔗 **[scoobysquad.com](https://scoobysquad.com/)** — An AI-powered customer service and booking agent built for a real, live pet waste removal business. Handles **100% of customer inquiries and bookings autonomously** with zero human intervention.

- Grounded the agent in live CRM data via the Sweep&Go API — eliminated hallucinated pricing/availability that plagued static-text early versions
- Built end-to-end auth flow: Supabase Google OAuth → session token validation in n8n → secure webhook processing
- Conversation logging to Google Sheets for owner visibility; SSR-optimized Next.js frontend for local SEO
- Chose n8n over a custom backend to handle complex escalation routing and multi-step tool calls within budget

| Metric | Result |
|--------|--------|
| 👤 Live users | **45** |
| 🤖 Human interventions | **0** |
| 🔄 Autonomous completion rate | **100%** |

```
User (Browser)
     │
     ▼
┌─────────────────────────┐
│   Next.js Frontend      │  ← SSR for SEO, Material UI, Google OAuth
│   (Vercel)              │
└────────────┬────────────┘
             │ Authenticated webhook (Supabase session token)
             ▼
┌─────────────────────────┐
│   n8n Workflow Engine   │  ← Orchestrates logic, escalation routing,
│                         │    tool calls, and API integrations
└──┬──────────┬───────────┘
   │          │
   ▼          ▼
┌──────┐  ┌───────────────────┐
│Gemini│  │  Sweep&Go API     │  ← Live CRM: customer data, availability
│ LLM  │  │  (Business CRM)   │
└──────┘  └───────────────────┘
   │
   ▼
┌─────────────────────────┐
│   Supabase (PostgreSQL) │  ← FAQ storage, session data, built-in auth
└─────────────────────────┘
   │
   ▼
┌─────────────────────────┐
│   Google Sheets         │  ← Conversation logs — owner dashboard
└─────────────────────────┘
```

---

### 🏦 Cloud Payroll & Identity System
> `SQL Server` `Next.js` `Firebase` `SSMS` `Material UI`

A full-stack cloud payroll platform built for real-world enterprise scenarios.
- Designed a relational schema in Microsoft SQL Server for complex employee records, tax data & multi-tier RBAC
- Migrated from local to AWS cloud architecture, improving global data availability for sensitive financial operations
- Integrated **Firebase Auth** for enterprise-grade identity management with a clean Next.js + Material UI frontend

---

### 📈 Predictive Vehicle Pricing Engine
> `Python` `WEKA` `Scikit-learn` `XGBoost` `Random Forest`

An ML pipeline that identifies key vehicle pricing drivers with high precision.
- Trained and evaluated **XGBoost & Random Forest** models using 10-fold cross-validation
- Optimized feature selection to surface the most impactful pricing signals

---

## 💼 Experience Highlights

| Role | Company | Impact |
|------|---------|--------|
| 🛠 Software Engineer Intern | Born2Serve *(Chicago, IL)* | CI/CD pipeline → **-40% deploy latency**; AWS migration → **337% user growth** |
| 🤖 ML Data Intern | Invisible Technologies *(SF, CA)* | LLM training & evaluation; automated pipelines → **-30% manual data handling** |

---

## 🏆 Leadership & Recognition

- 🥇 **ColorStack Fellow** — 1 of 30 selected from 1,000+ applicants (top 3% of Black/Latinx engineers in the U.S.)
- 🎤 **Keynote Speaker** at the Assessment Network of New York (ANNY) — presented AI research & education equity frameworks to 200+ tech professionals

---

<div align="center">

*"Build things that scale, learn, and matter."* 🚀

</div>

## 🌐 Connect with Me  
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/norbert-shema-9714681a4/)  
📧 **Email:** shemanorbert11@gmail.com  

---
⭐ *"Always learning, always building."*
