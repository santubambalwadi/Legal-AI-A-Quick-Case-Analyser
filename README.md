# **📜 Legal Document Analyzer** 🚀  

An **AI-powered tool** that extracts, summarizes, classifies, and translates legal documents. It supports **PDF, DOCX, and TXT**, including scanned PDFs using **OCR**.  

## **🔍 Features**  
✅ Extracts text from **PDF, DOCX, and TXT** (supports scanned PDFs via OCR).  
✅ Summarizes **long legal documents** (handles **50+ pages**).  
✅ Classifies documents into legal categories (**Property Dispute, Criminal Case, Corporate Law, etc.**).  
✅ Provides a **Risk Score** (**Low, Medium, High**) based on classification.  
✅ Supports **translation into 11 Indian languages**.  
✅ AI **chatbot** for answering legal queries based on document context.  
✅ **Downloadable PDF report** with summary, classification, and risk score.  

## **🛠️ Tech Stack**  
- **Backend:** Python, Flask, Transformers.  
- **AI Models:** `flan-t5-large` (for chatbot & text refinement).  
- **Frontend:** HTML, CSS, JavaScript .  
- **Translation:** `deep-translator` (Google Translate API).  
- **Storage:** Local `uploads/` directory for document processing.  

## **🚀 Installation & Setup**  

### **1️⃣ Clone the Repository**  
```bash
git clone https://github.com/your-username/legal-document-analyzer.git
cd legal-document-analyzer
```

### **2️⃣ Create a Virtual Environment (Optional but Recommended)**
```bash
python -m venv venv
source venv/bin/activate  # On macOS/Linux
venv\Scripts\activate  # On Windows
```

### **3️⃣ Install Dependencies**
```bash
pip install -r requirements.txt

### **4️⃣ Run the Application**
```bash
python app.py
```
The app will be available at **http://127.0.0.1:5000/**  

## **📂 Project Structure**
```
Legal-Doc-Analyzer/
│── app.py                  # Flask Backend (Main Logic)
│── templates/
│   ├── index.html          # Frontend UI
│── static/
│   ├── styles.css          # Styling
│   ├── script.js           # Handles Chatbot, Analysis, Translation
│── uploads/                # Stores Uploaded Documents
│── requirements.txt        # Dependencies
│── README.md               # Documentation
```
## **🛠️ How It Works**
1️⃣ **Upload a legal document** (PDF, DOCX, TXT).  
2️⃣ **The app extracts text** (OCR used for scanned PDFs).  
3️⃣ **Summarization is performed** using chunk-based processing (**handles 50+ pages**).  
4️⃣ **Classification determines** the legal category (**e.g., Property Dispute, Criminal Case**).  
5️⃣ **Risk Score is assigned** (**Low, Medium, High**).  
6️⃣ **Users can translate** the summary into **5 languages**.  
7️⃣ **Chatbot answers legal queries** based on document content.  
8️⃣ **Users can download a report** with all processed data.  

## **📜 Supported Languages for Translation**
- **English (en)**
- **Kannada (ka)**
- **Hindi (hi)**
- **Tamil (ta)**
- **Marathi (mr)**
- **Telugu (te)**


## **💡 Future Enhancements**
🚀 **Automated Legal Precedent Finder** – Suggests similar cases from legal databases.  
🚀 **Legal Term Explanations** – Definitions of complex legal jargon when hovered over.  
🚀 **Integration with e-Courts API** – Fetch related legal cases directly.  

## **📌 Contribution**
Want to improve this project? **Fork, modify, and submit a pull request!** 🎯  

## **📜 License**
This project is licensed under the **MIT License** – free to use, modify, and distribute.  
