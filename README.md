# AI-Document-OCR-Data-Extraction-Workflow
An AI-powered OCR automation workflow built with n8n. It extracts text and structured data from images/documents, converts it into JSON or text format, and automatically sends the processed data to designated team members. Ideal for businesses managing large document batches, invoices, or records
# AI Document OCR & Data Extraction Workflow (n8n Automation)

This project is an **AI-powered OCR workflow** built using **n8n**, designed to convert images or scanned documents into structured data such as JSON, text, or formatted output.  
It is ideal for companies that handle large numbers of documents and want to automate the process of extracting information and sending it to the correct team member.

With this workflow, you can:

- Upload or receive an image/document  
- Extract text using OCR  
- Convert it into JSON or text format  
- Clean and structure the extracted data  
- Automatically send the processed data to a specific person (boss or department) via email  

---

## 🚀 Features

- 🖼️ **OCR extraction** from images, PDFs, or scanned documents  
- 🧠 Converts OCR output into **JSON, plain text, or structured fields**  
- 🔗 Connected using **Webhook** for easy integration  
- 📧 Sends extracted data automatically to selected email addresses  
- 🗂️ Ideal for invoices, receipts, business documents, forms, etc.  
- 🔄 Fully automated workflow inside **n8n**  
- 🧩 Can be expanded to store the data in Google Sheets, Notion, Airtable, or a database  

---

## 🧠 Tech Stack

- **n8n** – workflow automation  
- **OCR Node / External OCR API** – for text extraction  
- **Webhook Trigger** – to receive documents  
- **OpenAI (optional)** – for data cleaning or formatting  
- **Email Node** – for sending the extracted data  
- **JSON / Text Converter Nodes** – for output formatting  

---

## 📂 Repository Structure


---

## 🔧 How It Works

1. **User uploads a document**  
   (Through website, form, API, or platform connected to n8n)

2. **Webhook receives the document**  
   n8n picks up the image/PDF instantly.

3. **OCR extracts text**  
   The workflow reads the document using OCR.

4. **AI or structured logic converts it**  
   Into clean:
   - JSON  
   - text  
   - key-value pairs  
   - or custom fields  

5. **Send via email**  
   The processed document data is automatically emailed to the designated boss or department.

6. *(Optional)* Save data into Sheets, CRM, or database.

---

## 🛠️ Setup Instructions

### 1. Import Workflow

1. Open **n8n**  
2. Go to: **Workflows → Import from file**  
3. Upload: `ocr-data-extraction-workflow.json`

---

### 2. Configure Webhook

- Open the webhook node  
- Copy the URL  
- Use it in your website/API to send images or documents

---

### 3. Configure OCR

- Add your OCR API (if external)  
- Or use built-in OCR node in n8n  
- Map input image to OCR node

---

### 4. Configure Output Format

You can choose:

- JSON  
- Text  
- Extract specific data like:
  - Invoice number  
  - Date  
  - Total amount  
  - Customer name

---

### 5. Configure Email Notifications

In **Send Email Node**:

- Add your Gmail/SMTP credentials  
- Set **To:** your boss or specific department  
- Email body includes extracted data from OCR

---

## 📦 Use Cases

- Invoice processing  
- Receipt extraction  
- Converting scanned documents into structured data  
- Sending digitized documents to management  
- Automating office paperwork  
- HR form digitization  
- Client document verification  

---

## 🎓 Why This Project Is Valuable

This workflow demonstrates:

- OCR technology  
- AI-based data processing  
- Automation skills in n8n  
- Real business value  
- Data digitization  
- Integration through webhook  
- Automated email workflows  

It is excellent for:

- GitHub portfolios  
- LinkedIn project posts  
- University applications  
- Freelance use cases  
- Automation roles  

---

## 👤 Author

**Rai Usman**  
GitHub: [@Usman-rai](https://github.com/Usman-rai)
