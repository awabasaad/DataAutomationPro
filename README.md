# 📊 DataAutomationPro  
### Automated Data Pipeline — API → Filter → Export → Logs → (Optional) Google Sheets

DataAutomationPro is a complete automation workflow built using Python.  
It demonstrates real-world skills in **API integration, data processing, CSV/JSON automation, and optional Google Sheets synchronization**.

This tool is designed for businesses and individuals who need fast, reliable, and repeatable data extraction and cleanup workflows.

---

## 🚀 Features

✔ Fetch data from REST APIs  
✔ Filter, clean, and process records dynamically  
✔ Export data into CSV and JSON formats  
✔ Full logging system (run.log) for debugging and auditing  
✔ Optional upload to Google Sheets using Service Account  
✔ Modular and scalable Python architecture  
✔ Works smoothly on **Google Colab** or any Python environment  

---

## 🧩 Project Structure
DataAutomationPro/
│── app.py
│── config.json
│── requirements.txt
│── .gitignore
│── README.md
│── modules/
│ ├── api_client.py
│ ├── data_processor.py
│ └── google_sheets.py
│── output/
│ ├── filtered_users.csv
│ └── filtered_users.json
│── logs/

---

## 🔧 How It Works

1️⃣ **API Fetching**  
The system sends a request to an external REST API, retrieves JSON data, and loads it for processing.

2️⃣ **Filtering & Processing**  
Data is filtered based on conditions defined in `config.json` (e.g., filter by city).

3️⃣ **Export to CSV & JSON**  
Cleaned records are saved into:
- `output/filtered_users.csv`
- `output/filtered_users.json`

4️⃣ **Logging**  
All operations are saved in:
- `logs/run.log`

5️⃣ **Optional Google Sheets Upload**  
If a `service_account.json` file is provided (not included for security reasons), the processed data can be uploaded directly to Google Sheets.

---

## ⚙️ How to Run (on Google Colab)

Upload the ZIP file into Colab and unzip it:

```python
!unzip DataAutomationPro.zip


---

## 🔧 How It Works

1️⃣ **API Fetching**  
The system sends a request to an external REST API, retrieves JSON data, and loads it for processing.

2️⃣ **Filtering & Processing**  
Data is filtered based on conditions defined in `config.json` (e.g., filter by city).

3️⃣ **Export to CSV & JSON**  
Cleaned records are saved into:
- `output/filtered_users.csv`
- `output/filtered_users.json`

4️⃣ **Logging**  
All operations are saved in:
- `logs/run.log`

5️⃣ **Optional Google Sheets Upload**  
If a `service_account.json` file is provided (not included for security reasons), the processed data can be uploaded directly to Google Sheets.

---

## ⚙️ How to Run (on Google Colab)

Upload the ZIP file into Colab and unzip it:

```python
!unzip DataAutomationPro.zip



🔐 Google Sheets Integration (Optional)

To activate Google Sheets upload:

Create a Service Account JSON file from Google Cloud.

Place it in the root folder as:

service_account.json


⚠️ Important:
Do NOT upload service_account.json to public GitHub repositories.
It is already protected using .gitignore.


📌 Why This Project Is Useful

Automates repetitive daily tasks

Reduces human error

Ensures consistent data output

Easy to customize for any API

Ideal for businesses, dashboards, and workflow automation

📬 Contact

If you need custom automation tools, API integrations, or data workflows, feel free to reach out.
