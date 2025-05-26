
# ☁️ Cloud-Based Service for Basic Data Analytics

A web application that allows users to **upload**, **sort**, **search**, and **classify** PDF and DOCX documents in the **cloud** using Supabase storage. Built with Python and Flask.

---

## 🔧 Features

- ✅ Upload documents (.pdf / .docx) directly to **Supabase**
- 🔠 Sort documents by **Title** (not filename)
- 🔍 Search inside documents for keywords with **highlighted results**
- 🧠 Classify documents into predefined categories (Technical / IT / Other)
- 📊 View statistics: number of files, total size, and operations time
- 📥 Download documents with **highlighted** content

---

## 💡 Technologies

| Layer      | Tech Stack                       |
|------------|----------------------------------|
| Backend    | Python 3.10+, Flask              |
| Cloud      | Supabase (Storage)               |
| PDF Reader | PyMuPDF (`fitz`)                 |
| DOCX Reader| `python-docx`                    |
| Frontend   | HTML, CSS (Jinja2 templates)     |

---

## 📁 Folder Structure

```
Cloud-Based-Service-for-Basic-Data-Analytics/
├── app.py                  # Main Flask application
├── templates/              # HTML pages
├── static/                 # CSS files
├── requirements.txt
└── README.md
```

---

## 🚀 Getting Started

1. **Install requirements**
   ```bash
   pip install -r requirements.txt
   ```

2. **Set up Supabase**
   - Create a project at [https://supabase.com](https://supabase.com)
   - Create a storage bucket called `documents` and make it public
   - Add your Supabase URL and API key in `app.py`

3. **Run the app**
   ```bash
   python app.py
   ```

---

## 📸 Screenshots

![UploadPage](https://github.com/user-attachments/assets/d7b279cd-e93a-4543-b609-275cbe25b6a4)
![SortPage](https://github.com/user-attachments/assets/82ca2750-773e-4d51-8fda-e2a160d422a7)
![SearchPage](https://github.com/user-attachments/assets/6adf7e8d-2d38-4f94-8d8b-de99286f0572)
![DownloadHighlightedDoc](https://github.com/user-attachments/assets/e4e53647-c6cd-4057-a1bb-ffc480ea0ba1)
![HighlightedKeywords](https://github.com/user-attachments/assets/8406f450-f4f6-4749-a8e6-929ad79097bb)
![Catgories](https://github.com/user-attachments/assets/35081d29-d7be-487a-a541-350439e36451)
---
Nader Mohamed Hasan Abu Sulieman
---

> Developed as part of Cloud & Distributed Systems Course Assignment – 2025  
> IUG - Faculty of Information Technology, Department of Software Development
