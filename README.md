# 📄 ProposalPilot – Intelligent RFP Analysis for Strategic Decision-Making

ProposalPilot is an AI-powered web platform that simplifies the process of responding to complex Requests for Proposals (RFPs). By leveraging advanced NLP models and modern web technologies, the system automatically compares RFP documents against proposal responses, identifies compliance gaps, and provides actionable insights.

---

## 🧠 Key Features

- 🧾 **Automated RFP & Proposal Parsing** – Upload PDF/DOCX files for smart document analysis.
- 🔍 **AI-Powered Gap Detection** – Identify mismatches and compliance issues using LLMs.
- 📊 **Interactive Dashboard** – Visual representation of clause-level comparison results.
- 📤 **Downloadable Reports** – Generate structured PDF/CSV gap reports.
- 🗂 **Secure File Handling** – Temporary, sanitized document processing.
- 💬 **(Optional)** Chat Interface for Q&A from document context.

---

## 🎯 Objectives

- Automate the manual and error-prone RFP analysis process.
- Compare RFPs and responses using semantic understanding.
- Identify missing, inconsistent, or misaligned content.
- Deliver real-time analysis and feedback to users.
- Leverage Groq’s LLMs with LangChain for deep document comprehension.

---

## ⚙️ Tech Stack

### 🔐 Backend
- **Language & Frameworks**: Python 3.x, FastAPI, Uvicorn
- **AI/NLP**: Groq LLM via LangChain, Retrieval-Augmented Generation (RAG)
- **Database**: MongoDB (Atlas), Firebase (Optional – Auth/Chat)
- **Security**: JWT, OAuth 2.0, bcrypt, CORS, Helmet

### 🌐 Frontend
- **Framework**: React.js (Vite / Next.js), TypeScript
- **Styling**: Tailwind CSS, Material UI / Ant Design
- **State Management**: Redux / Context API
- **Routing & API**: React Router, Axios

---

## 📦 Installation

### 🔧 Backend (FastAPI)
```bash
cd ProposalPilot-Backend
python -m venv venv
source venv/bin/activate  # on Windows: venv\Scripts\activate
pip install -r requirements.txt
uvicorn main:app --reload
```

### 🌐 Frontend (React)
```bash
cd ProposalPilot-Frontend
npm install
npm run dev
```

### ☁️ Deployment

| Component     | Platform/Service               |
|---------------|-------------------------------|
| Frontend      | Vercel                        |
| Backend       | AWS EC2 / Render / DigitalOcean |
| Database      | MongoDB Atlas                 |
| Domain & SSL  | GoDaddy / Cloudflare          |

---

### 🖼️ System Architecture

<pre>
👤 User
  ↓ Uploads Documents
   
🌐 React Frontend (Vite + TailwindCSS)
  ↓ Sends API Requests
   
⚙️ FastAPI Backend
  ↓ Processes & Integrates with
   
🧠 LangChain + Groq LLM
  ↓ Stores / Fetches Data
   
🗄️ MongoDB Atlas (Cloud Database)
</pre>

---
### 📸 UI Screenshots & 🎥 Demonstration

#### 🔍 Interface Previews

#### Home Page  
![Home Page](ProposalPilot-Frontend/assets/HomePage1.png)  
![Home Page](ProposalPilot-Frontend/assets/HomePage2.png)

#### Uploading RFP Document and Analyzing  
![Uploading and Analyzing](ProposalPilot-Frontend/assets/Upload_RFP.png)

#### Dashboard of Uploaded RFP  
![Dashboard](ProposalPilot-Frontend/assets/Dashboard.png)

#### Compliance Check for Individual  
![Compliance Check](ProposalPilot-Frontend/assets/Compliance.png)

#### Analysis Forms or Attachments in Document  
![Analysis Forms](ProposalPilot-Frontend/assets/AnalysisForms.png)

#### Submission Requirements  
![Submission Requirements](ProposalPilot-Frontend/assets/Submission.png)

#### Risk Analysis  
![Risk Analysis](ProposalPilot-Frontend/assets/Risk.png)


---

#### ▶️ Demo Video

Watch the full walkthrough of ProposalPilot in action:

[![Watch Demo](https://img.youtube.com/vi/YOUR_VIDEO_ID/0.jpg)](https://www.youtube.com/watch?v=YOUR_VIDEO_ID)

---

### 🚀 Usage

1. Start both **backend** and **frontend** servers.
2. Open your browser at: [http://localhost:3000](http://localhost:3000)
3. Upload your RFP and proposal documents.
4. View the analysis and download insightful reports.
5. Optionally, interact with the **AI chat assistant** for deeper insights.

---

### 📌 Functional Requirements

- 📄 Upload and parse documents (PDF, DOCX)
- 🧠 NLP-powered compliance gap detection
- 📥 Download detailed analysis reports
- 📊 Real-time feedback and interactive visualizations

---

### 🔒 Non-Functional Requirements

- 🔐 High security using JWT authentication
- 📱 Responsive UI (mobile + desktop)
- 🕒 99.9% uptime for high availability
- ⚙️ Scalable backend supporting multiple users/documents

---

### 🧭 Future Enhancements

- ✅ Real-time team collaboration & annotations
- 🤖 Smart auto-generated proposal sections
- 📁 Integration with Google Drive / SharePoint
- 📊 Advanced analytics dashboards (e.g., success scoring)
- 🌐 Multi-language document support

---

### 👩‍💻 Team Members

| Name            | GitHub Profile                          |
|------------------|-----------------------------------------|
| Manasi Bharati   | [Manasi0304](https://github.com/Manasi0304) |
| Akshada Mane     | [AkshadaMane26](https://github.com/AkshadaMane26) |

#### 🎓 Project Guide: Dr. L. A. Bewoor  
**Institution:** Vishwakarma Institute of Information Technology, Pune

---

### 📚 References

- **AI RFP Response Automation** – Addepto  
- **Gap Analysis Automation** – VisibleThread  
- **Evaluating AI for Federal RFP Proposal Writing** – GovBrief  
- **Research proposal content extraction using NLP**

---

### 📄 License

This project is licensed under the **MIT License**. See the [LICENSE](./LICENSE) file for more details.

---

> _Designed to transform the way RFP responses are crafted – faster, smarter, and more accurate using AI._


---


