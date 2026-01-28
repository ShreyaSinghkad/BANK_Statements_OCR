# BANK_Statements_OCR
OCR-based extraction and API for structured data from Bank Statements.
# Bank Statement OCR & Dashboard

A complete pipeline to process **bank statement PDFs**:

- **OCR** to extract text from PDFs  
- **Parse** extracted text to a structured schema  
- **Validate** against a Pydantic schema  
- **Store** data in **MongoDB Atlas**  
- **Expose API** via **FastAPI**  
- **Interactive dashboard** via **Streamlit** for viewing & analyzing statements

---

## **Features**

- Upload one or more PDFs for OCR processing  
- Extract transactions, account details, opening/closing balances  
- Parse and validate against a structured schema  
- Save parsed statements to **MongoDB**  
- Fetch statements via **FastAPI endpoints**  
- Streamlit dashboard for:
  - Upload PDFs
  - Display OCR text
  - Display parsed transactions
  - Filter by **account number**
  - Download results as JSON

---


## **Project Structure**

bank-statement-ocr/
│
├── app.py # Streamlit UI
├── fastapi_app.py # FastAPI backend
├── ocr_utils.py # Functions for OCR & parsing PDFs
├── requirements.txt # Required Python packages
├── README.md
└── example_pdfs/ # Optional: example PDFs for testing

