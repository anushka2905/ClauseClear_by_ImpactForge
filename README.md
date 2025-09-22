# ClauseClear\_by\_ImpactForge

ClauseClear is an AI-powered platform that **simplifies complex legal documents** such as rental agreements, employment contracts, loan documents, vendor contracts, and Terms & Conditions.
Using **Google Cloud’s cutting-edge AI stack (Gemini, Vertex AI, Gemma, Code Assist)**, ClauseClear provides **clause-level summarization, risk detection, multilingual explanations, and interactive Q\&A** to empower individuals, startups, and small businesses to make informed legal decisions.

---

## 🚀 Key Features

1. **Clause-Level Simplification**

   * AI-generated plain-language summaries.
   * Multi-language + voice-based explanations.

2. **Risk & Obligation Detection**

   * Highlights obligations, protections, and hidden penalties.
   * Generates a **risk heatmap** for quick insights.

3. **Interactive Legal Q\&A**

   * Ask natural-language questions about clauses.
   * AI explains consequences, alternatives, and "what-if" scenarios.

4. **Comparisons & Tracking**

   * Compare **two contracts side-by-side** (e.g., loan offers, job contracts).
   * Track **changes across versions** of Terms of Service or agreements.

5. **Role-Based Summaries**

   * Tailored summaries (tenant vs landlord, employee vs employer).
   * Child/Elder-friendly contracts with icons/visuals.

6. **Admin/Expert Dashboard**

   * Legal experts validate AI outputs.
   * Analytics on common risky clauses flagged.

---

## 🏗️ Architecture

```
User → Web App / Mobile App
     → Backend API (Spring Boot / Flask / Node.js)
     → Google Cloud Services:
        - Vertex AI / Gemini → Summarization + Q&A
        - Gemma → Multilingual Simplification
        - Cloud Storage → Document Uploads
        - Firestore/SQL → User Data + History
     → Frontend (React / Thymeleaf / Flutter)
Admin → Dashboard (monitor flagged clauses, analytics)
```

---

## 📊 Use Case Diagram

```plantuml
@startuml
left to right direction
actor User as U
actor "Legal Expert/Admin" as A

rectangle "ClauseClear AI System" {
  usecase "Upload Contract / Agreement" as UC1
  usecase "Clause-Level Simplification" as UC2
  usecase "Risk & Obligation Detection" as UC3
  usecase "Ask Interactive Q&A" as UC4
  usecase "Multilingual / Voice Explanation" as UC5
  usecase "Compare Agreements" as UC6
  usecase "Role-Based Summary" as UC7
}

U --> UC1
U --> UC2
U --> UC3
U --> UC4
U --> UC5
U --> UC6
U --> UC7

A --> UC2
A --> UC3
@enduml
```

---

## 📱 Wireframes (Key Screens)

* **Landing Page** → Upload & Quick Demo
* **Document Upload** → Drag & Drop, Language Selector
* **Clause Summary View** → Side-by-side original + simplified clauses
* **Risk Dashboard** → Obligations checklist + risk heatmap
* **Q\&A Chat** → Ask questions, get instant legal explanations
* **Compare Contracts** → Side-by-side differences
* **Admin Dashboard** → Monitor, validate, and analyze risky clauses

---

## 💰 Estimated Implementation Cost

| Phase        | Infra & AI Cost         | Team Cost         | Total             |
| ------------ | ----------------------- | ----------------- | ----------------- |
| Prototype    | ₹0 – ₹5K (with credits) | Self/team effort  | \~₹5K             |
| MVP (6 mo)   | ₹30K – ₹60K/month       | Stipends ₹20K–40K | ₹2–3.5 Lakhs      |
| Scale (1 yr) | ₹5–8 Lakhs/month        | Team salaries     | ₹60–90 Lakhs/year |

---

## 🏆 Unique Selling Proposition (USP)

* **Clause-level AI** (not just document-level summarization).
* **Risk heatmap visualization** for quick decision-making.
* **Role-based views** (tenant, landlord, employee, employer).
* **Multi-language & voice support** → inclusivity.
* **Negotiation helper** suggesting fairer contract terms.

---

## ⚙️ Tech Stack

* **Frontend:** React / Flutter / Thymeleaf
* **Backend:** Spring Boot / Flask / Node.js
* **Database:** Firestore / PostgreSQL
* **AI Models:** Vertex AI, Gemini, Gemma, Code Assist
* **Cloud Infra:** Google Cloud Run, Cloud Storage

---

## 📌 How to Run (Prototype)

1. Clone the repo:

   ```bash
   git clone https://github.com/<your-repo>/ClauseClear_by_ImpactForge.git
   cd ClauseClear_by_ImpactForge
   ```
2. Install dependencies:

   ```bash
   npm install   # frontend  
   pip install -r requirements.txt   # backend  
   ```
3. Set up Google Cloud credentials & APIs.
4. Run backend:

   ```bash
   python app.py
   ```
5. Run frontend:

   ```bash
   npm start
   ```

---

## 👩‍💻 Team

* **ImpactForge**
  Innovators passionate about AI, law-tech, and social impact 🚀
