# 📑 Event-Invoice-Generator-Automation-n8n

![n8n](https://img.shields.io/badge/Workflow-n8n-FF6C37?style=flat&logo=n8n&logoColor=white)
![Xero](https://img.shields.io/badge/Accounting-Xero_API-13B5EA?style=flat&logo=xero&logoColor=white)
![OpenAI](https://img.shields.io/badge/AI-GPT--4o-412991?style=flat&logo=openai&logoColor=white)
![Google Drive](https://img.shields.io/badge/Storage-Google_Drive-4285F4?style=flat&logo=googledrive&logoColor=white)
![JavaScript](https://img.shields.io/badge/Logic-JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)

---

## 🚀 The Solution: Autonomous Financial Document Synthesis
In professional event management and accounting, the transition from "Raw Data" to "Client-Ready Document" is often a manual bottleneck. This project is a **Fully Automated Document Generation Engine** that bridges the gap between the **Xero Accounting API** and high-fidelity HTML reports.

By utilizing **OpenAI’s GPT-4o** to act as an intelligent data architect, the system extracts complex JSON invoice payloads, structures them into clean markdown, and then programmatically synthesizes them into styled HTML5 documents—storing the final result directly in **Google Drive** for immediate use. 🤖📈✨

---

## ✅ Problems Solved
- **🛑 Manual Formatting Fatigue:** Eliminates the need to manually copy data from Xero into Word or Google Doc templates, saving hours per week. ⏳
- **🛑 Human Calculation Errors:** By pulling directly from the Xero API, the system ensures that every line item, tax calculation, and total is 100% accurate and reflects the official record. 🎯
- **🛑 Inconsistent Brand Identity:** Uses a centralized JavaScript/CSS styling node to ensure every generated document follows the exact same professional aesthetic and corporate branding. 🎨
- **🛑 Data Fragmentation:** Automatically centralizes all generated invoices into a specific Google Drive hierarchy, creating an organized, searchable audit trail. 📂

---

## 🖼️ System Architecture

### Workflow Orchestration (Xero-to-HTML Pipeline)
The complete logic flow—from secure API ingress to AI-powered structuring and cloud persistence.
<div align="center">
  <img src="https://raw.githubusercontent.com/Muneeb20019/Automated-HTML-Document-Generation-from-Xero-API-using-n8n/main/Xero%20Invoice.jpeg" width="100%" alt="n8n Xero Workflow Architecture" style="border-radius:10px; box-shadow: 0 4px 8px 0 rgba(0, 0, 0, 0.2);"/>
</div>

---

## 🧠 Core Technical Pillars

### 1. 🔗 Secure REST API Ingress (Xero OAuth 2.0)
The system connects to the **Xero REST API** using enterprise-grade authentication. It retrieves a massive, unstructured JSON payload containing customer details, payment terms, and multi-line itemized lists. This ensures the data is always "Live" and pulled directly from the source of truth.

### 2. 🤖 AI-Neural Structuring (GPT-4o)
Raw accounting JSON is often too complex and "noisy" for simple templates. I implemented a **Prompt Engineering** layer where **OpenAI GPT-4o**:
- Filters out unnecessary backend metadata.
- Categorizes line items for better readability.
- Transforms the data into a **Structured Markdown Table**, acting as an intelligent middle-layer between raw data and final design. 🧠🔍

### 3. 🎨 Dynamic HTML5 & CSS Synthesis
Once the AI has structured the data, a custom **JavaScript Code Node** performs the final rendering:
- **HTML5 Templating:** Converts markdown into semantic HTML tags for document clarity.
- **Inline CSS Injection:** Programmatically applies brand-specific colors, typography, and borders to the document.
- **Responsive Design:** Ensures the generated invoice looks polished on desktop PDF viewers, tablets, and mobile devices. 💻✨

### 4. 📂 Automated Cloud Persistence (Google Drive API)
The final stage closes the loop by interfacing with the **Google Drive API**. The system:
- **Dynamic File Naming:** Automatically names files (e.g., `Invoice_ClientName_Date.html`) for easy retrieval.
- **Folder Mapping:** Locates the correct destination folder based on the project or client ID.
- **Binary Creation:** Creates the file and writes the HTML content, ensuring the document is ready for immediate client delivery. 📤☁️

---

## ✨ Advanced Technical Features
- **⚙️ Dynamic Payload Normalization:** Capable of handling invoices with any number of line items without breaking the document layout or CSS borders.
- **🛡️ Fault-Tolerant API Handling:** Implements secure credential management to ensure sensitive financial data remains private and protected during the entire transfer.
- **⏳ Low-Latency Generation:** The entire process—from Xero trigger to Google Drive file availability—completes in under 10 seconds.

---

## 🛠️ Technical Stack
| Layer | Technology |
| :--- | :--- |
| **🔄 Automation** | **n8n** (State Management & API Orchestration) |
| **🧠 AI Brain** | **OpenAI GPT-4o** (Intelligent Data Transformation) |
| **💰 Source Data** | **Xero REST API** (Financial Source of Truth) |
| **💾 Cloud Storage** | **Google Drive API** (Document Persistence) |
| **📜 Scripting** | **JavaScript / Node.js** (HTML/CSS Document Synthesis) |

---

## ✍️ Author
**Muneeb Ali Khan**
- **GitHub:** [@Muneeb20019](https://github.com/Muneeb20019)
- **LinkedIn:** [Muneeb Ali Khan](https://www.linkedin.com/in/muneeb-ali-khan-2a1675365)

---

## 📜 License
This project is licensed under the MIT License.
   
