# AI Invoice Processing System

An intelligent invoice processing workflow built with **n8n**, **Google Gemini**, and **Google Sheets**. This project automates the extraction and processing of invoice data, reducing manual data entry and improving the accuracy of financial record management.

---

# 📌 Overview

The **AI Invoice Processing System** streamlines invoice management by automatically receiving invoices, extracting key information using AI, and storing structured data in Google Sheets. Designed for businesses and finance teams, this workflow eliminates repetitive manual tasks and accelerates invoice processing.

---

# ✨ Features

* 📄 Automatically processes incoming invoice documents.
* 🤖 Uses Google Gemini AI to extract invoice details.
* 🧾 Extracts key information, including:

  * Invoice Number
  * Vendor Name
  * Invoice Date
  * Due Date
  * Total Amount
  * Currency
  * Tax Amount (if available)
* 📊 Stores extracted invoice data in Google Sheets.
* ⚡ Reduces manual data entry and processing time.
* 🔄 Easily customizable for different invoice formats.

---

# 🏗️ Workflow

```text
Invoice Upload / Email / Webhook
               │
               ▼
      Extract Invoice Content
               │
               ▼
       Google Gemini Analysis
               │
               ▼
     Structured Data Extraction
               │
               ▼
      Save to Google Sheets
```

---

# 🛠️ Technologies Used

* n8n
* Google Gemini 2.5 Flash
* Google Sheets API
* LangChain AI Agent
* OCR / Document Processing (if applicable)

---

# 📋 Prerequisites

Before using this workflow, ensure you have:

* An n8n instance
* Google Gemini API credentials
* Google Sheets OAuth credentials
* A configured invoice input source (Email, Webhook, Google Drive, etc.)

---

# 🚀 Installation

1. Clone this repository.
2. Import the workflow JSON into n8n.
3. Configure Google Gemini credentials.
4. Configure Google Sheets credentials.
5. Configure the invoice input source.
6. Activate the workflow.

---

# ⚙️ How It Works

1. An invoice is received through the configured input source.
2. The workflow extracts the invoice content.
3. Google Gemini analyzes the document.
4. Key invoice details are extracted into structured fields.
5. The processed data is stored in Google Sheets.
6. The extracted data is ready for reporting or accounting workflows.

---

# 📊 Example Output

| Field          | Example           |
| -------------- | ----------------- |
| Invoice Number | INV-2026-001      |
| Vendor         | ABC Supplies Ltd. |
| Invoice Date   | 2026-07-25        |
| Due Date       | 2026-08-24        |
| Total Amount   | $1,250.00         |
| Currency       | USD               |

---

# 💼 Use Cases

* Invoice automation
* Accounts payable processing
* Financial record management
* AI-powered document processing
* Expense tracking
* Business workflow automation

---

# 🔮 Future Enhancements

* OCR support for scanned invoices
* PDF and image invoice processing
* ERP integration (SAP, Oracle, QuickBooks)
* Duplicate invoice detection
* Approval workflow automation
* Multi-currency support
* Email notifications
* Analytics dashboard

---

# 🤝 Contributing

Contributions are welcome! Feel free to fork this repository, submit issues, or open pull requests to improve the workflow.

---

# 📄 License

This project is licensed under the MIT License.

---

# 👨‍💻 Author

**Muneeb**

<img width="1920" height="905" alt="AI Invoice Processing System" src="https://github.com/user-attachments/assets/8b7cb415-e6fe-4163-abf1-36d07053d408" />

AI Automation Developer passionate about building intelligent workflows using **n8n**, **Google Gemini**, and modern APIs to automate business processes.

---

⭐ If you found this project useful, consider giving it a star on GitHub!

