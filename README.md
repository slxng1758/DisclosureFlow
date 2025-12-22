# Financial RAG Assistant

AI-powered Q&A system for financial documents using RAG.

## Setup
```bash
# Install dependencies
pip install -r requirements.txt

# Install Ollama
# Visit: https://ollama.ai
ollama pull llama3.2

# Add PDFs to data/ folder
# Then run:
python ingest.py

# Launch app
streamlit run app.py
```

## Features
- 📄 Indexes financial PDFs
- 🤖 Natural language Q&A
- 📚 Source citations
- ⚡ Local LLM (no API costs)
```

3. **Save**

---

## **📥 Step 5: Download PDFs**

### **In your browser:**

1. Go to: https://investor.nvidia.com/sec-filings/
2. Download **latest 10-K** (Annual Report)
3. Download **2 recent 10-Qs** (Quarterly Reports)

### **Move to project:**

1. **Drag and drop** the 3 PDFs from your Downloads folder
2. **Drop them into the `data/` folder** in VSCode sidebar

**Your structure should now be:**
```
📁 finance-rag
├── 📁 data/
│   ├── 📄 pdfs of financial data!
├── 📄 ingest.py
├── 📄 app.py
├── 📄 requirements.txt
└── 📄 README.md