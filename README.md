
# ☁️ Cloud-Based Service for Basic Data Analytics

## Introduction
This project including the development of a cloud-based program/service designed to analyze collection of  PDF and Word documents efficiently. The service provides three core functions: 
1.	Sorting documents based on their titles (not filenames)
2.	Searching for specific keywords in documents, with highlighted matched results.
3.	Classifying documents, using a predefined classification tree.
4.	Statistics, such as (documents size, count, times for operations)

To meet requirements, the application was deployed using Render –a cloud hosting service. Cloud service was setup using Supabase – a free open source Firebase alternative platform. All operations are executed in Supabase Storage. This ensures scalability, accessibility and a real-world distributed cloud system.
This documentation or report, including the software design, functions, implementation and deployment steps. It also mentioned the the challenges and the techniques used to ensure that the application meets the requirements.
The cloud-based development methodology which adapted is Agile Cloud Methodology. Where the application was developed incrementally and adapted based on user requirements.

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

![‏‏لقطة الشاشة (19)](https://github.com/user-attachments/assets/a08d32b9-e505-42df-b1bc-e55de12071c2)
![‏‏لقطة الشاشة (20)](https://github.com/user-attachments/assets/8e61b747-ffe3-4981-910a-a87b191a3908)
![‏‏لقطة الشاشة (21)](https://github.com/user-attachments/assets/1a47f403-b72c-4d23-9f36-0dc6733f8f35)
![‏‏لقطة الشاشة (22)](https://github.com/user-attachments/assets/4af05212-0c53-4849-a0c4-bb08fff6b398)
![‏‏لقطة الشاشة (23)](https://github.com/user-attachments/assets/f9616479-c4fc-4002-8572-4aec79fa07fc)
![‏‏لقطة الشاشة (24)](https://github.com/user-attachments/assets/cea787ea-39e1-451d-94d7-4c2008750478)
![‏‏لقطة الشاشة (25)](https://github.com/user-attachments/assets/1349862a-72cb-4f09-995f-b61172f11906)
![‏‏لقطة الشاشة (26)](https://github.com/user-attachments/assets/b9d75f4e-9a92-4505-8cc3-e1c09f9621ae)
![‏‏لقطة الشاشة (27)](https://github.com/user-attachments/assets/3b62dcee-05eb-428f-b7c3-6beff97af892)
![‏‏لقطة الشاشة (28)](https://github.com/user-attachments/assets/aeda0446-99d0-4b09-8732-bf813e186b17)

---
Nader Mohamed Hasan Abu Sulieman
---

> Developed as a part of Cloud and Distributed Systems course assignment – 2025  
> IUG - Faculty of Information Technology, Department of Software Development
