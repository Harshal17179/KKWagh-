# 🎓 College Admission Agent (RAG-Based)

## 📌 Overview
The **College Admission Agent** is an AI-powered assistant designed to simplify the **college admission process**.  
It leverages **Retrieval-Augmented Generation (RAG)** to provide instant, reliable answers to admission-related queries such as:
- Eligibility criteria  
- Admission policies  
- Course selection guidance  
- Fee structures  
- Application deadlines  
- FAQs  

Built using **IBM Cloud Lite Services** and **IBM Granite Foundation Models**, this solution enhances transparency, reduces manual inquiries, and improves the applicant experience.

---

## 🚀 Features
- ✅ Real-time query answering using institutional databases  
- ✅ Auto-summarization of admission policies and FAQs  
- ✅ Smart course recommendations based on student profiles  
- ✅ Transparent fee structure and deadline reminders  
- ✅ Multilingual & voice-based support (future scope)  

---

## 🛠️ Technology Stack
- **IBM Cloud Lite Services**  
- **IBM Watsonx AI Studio & Runtime**  
- **IBM Granite Foundation Model**  
- **Natural Language Processing (NLP)**  
- **Retrieval-Augmented Generation (RAG)**  
- **Python (Flask/FastAPI for backend)**  

---

## 📂 Project Structure
```
├── data/                  # Sample admission policies, FAQs, fee data
├── notebooks/             # Jupyter notebooks for prototyping
├── app/                   # Backend application (Flask/FastAPI)
│   ├── main.py            # Entry point for API server
│   ├── rag_pipeline.py    # RAG-based retrieval and response pipeline
│   └── utils/             # Helper functions
├── requirements.txt       # Project dependencies
├── README.md              # Project documentation
└── LICENSE                # License file (if applicable)
```

---

## ⚙️ Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/college-admission-agent.git
   cd college-admission-agent
   ```

2. Create a virtual environment and activate it:
   ```bash
   python -m venv venv
   source venv/bin/activate   # On Windows: venv\Scripts\activate
   ```

3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

---

## ▶️ Usage
1. Run the backend service:
   ```bash
   python app/main.py
   ```
2. Open browser / API client and query:
   ```
   http://localhost:5000/query?question="What is the eligibility for B.Tech?"
   ```

---

## 📊 Results
- Reduced admission desk workload  
- Improved applicant transparency & satisfaction  
- Real-time updates from trusted institutional data  

---

## 🔮 Future Scope
- Multilingual support  
- Voice-activated queries  
- Integration with online admission portals  
- Personalized admission guidance  

---

## 🎓 IBM Certification
- [Getting Started with AI (Credly) ](https://www.credly.com/badges/1bb8371f-4e1d-49b5-bf03-13fe5beaec2a/public_url) 

---

## 🤝 Contributing
Contributions are welcome! Please open an issue or submit a pull request.

---

## 📜 License
This project is licensed under the MIT License - see the LICENSE file for details.
