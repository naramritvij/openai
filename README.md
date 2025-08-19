# NOra University Chatbot

NOra is a simple chatbot scaffold for answering university questions.

## Setup

Create a virtual environment and install dependencies.

### macOS / Linux
```bash
python3 -m venv .venv
source .venv/bin/activate
```

### Windows PowerShell
```powershell
python -m venv .venv
.\\.venv\\Scripts\\Activate.ps1
```

Install requirements:
```bash
pip install -r requirements.txt
```

## Data
Copy the following PDFs into `data/pdfs/`:
- `COE.pdf`
- `COS.pdf`
- `CPS.pdf`

The FAISS index output will be stored in `data/index/`.

## Overview
1. Ingest PDFs to build the index (script coming soon).
2. Run the Streamlit app:
   ```bash
   streamlit run app.py
   ```
