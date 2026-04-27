# OCR-Based Operational Data Automation

## 🔍 Overview
This project is an OCR-based automation system designed to reduce manual data processing in operational workflows.

The system extracts text from documents, processes it into structured data, and prepares it for reporting and analysis.

✅ Reduced manual data processing time by ~30%  
✅ Improved data accuracy and reporting efficiency  
✅ Designed for scalable and asynchronous processing  

---

## 🚀 Key Features
- OCR text extraction using PaddleOCR  
- Asynchronous processing with FastAPI and RabbitMQ  
- Worker-based architecture for scalability  
- Text cleaning and preprocessing pipeline  
- Structured output for downstream reporting  

---

## 🏭 Use Case
This system is applicable in real-world operational environments such as:
- Document and report processing automation  
- Invoice and form data extraction  
- Reducing manual data entry in industrial workflows  
- Supporting operational reporting and analysis  

---

## 👥 Team
This project was developed collaboratively by:
- Novalyina Ghassani – OCR pipeline & data processing  
- Hilmi Fauziyyah – System integration  & Backend/API development  

---

## 🧠 System Architecture
- **FastAPI** handles incoming requests  
- **RabbitMQ** manages task queue asynchronously  
- **Worker** processes OCR tasks  
- **OCR Engine** extracts and cleans text  

---

## 🛠 Tech Stack
- Python  
- FastAPI  
- RabbitMQ  
- PaddleOCR  
- OpenCV  
- Pandas  

---

## ⚙️ How It Works
1. User uploads a document via API  
2. Request is sent to RabbitMQ queue  
3. Worker processes the document asynchronously  
4. OCR extracts text from the document  
5. Text is cleaned and structured  
6. Output is returned for reporting or storage  

---

## ⚙️ Installation & Setup

### 1. Clone Repository
```bash
git clone https://github.com/NovalyinaGhassani/ocr-engine.git
cd ocr-engine

### 2. Install Dependencies
pip install -r requirements.txt

### 3. Run FastAPI Server
uvicorn main:app --reload

### 4. Start Worker (RabbitMQ must be running)
python worker.py

---

## 📊 Example Workflow

Input:

Scanned document / image

Process:

OCR extraction
Text cleaning
Data structuring

Output:

Structured text data ready for reporting

---

## 📈 Impact

This project demonstrates:

Ability to design scalable systems using asynchronous architecture
Practical implementation of OCR for real operational problems
Strong understanding of data processing and automation workflows
Application of AI/ML tools in industrial contexts

---

## 🔮 Future Improvements
Add model optimization for higher OCR accuracy
Implement UI dashboard for monitoring
Integrate database for persistent storage
Add support for multiple document formats

