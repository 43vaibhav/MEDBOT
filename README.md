# 🤖 MedBot – AI-Powered Health Assistant

MedBot is an AI chatbot that helps users **identify possible diseases** based on symptoms and provides **treatment suggestions, lifestyle tips, and Ayurvedic facts**.

---

## Features
- Symptom-based disease prediction  
- Medicine and lifestyle recommendations  
- Handles common-symptom cases (asks age, gender, lifestyle)  
- Advises necessary medical tests  
- Web interface with registration, dashboard, and health feed  

---

## Tech Stack
- Python & Django – Backend & AI logic  
- HTML, CSS, JavaScript – Frontend  
- NLP & AI Libraries – Symptom analysis  
- SQLite/MySQL – Database  
- Bootstrap – Responsive UI  

---

## Project Structure
```text
MedBot/
│
├── clean_code.py       # Core Python AI script
├── manage.py           # Django management
├── templates/          # HTML pages (login, dashboard, feed)
├── static/             # CSS & JS files
├── requirements.txt    # Python dependencies
├── README.md           # This file
└── media/              # Uploads / user files

## Installation & Usage

1. Clone the repo:
```bash
git clone https://github.com/43vaibhav/MedBot.git
cd MedBot
Install dependencies:

bash
Copy
Edit
pip install -r requirements.txt
Run the Django server:

bash
Copy
Edit
python manage.py runserver
Open browser at:

arduino
Copy
Edit
http://localhost:8000
Usage Instructions
Register/Login to access dashboard

Enter symptoms in the symptom checker

MedBot predicts possible diseases

Follow medicine & lifestyle suggestions

Explore common health tips in the feed

Contributing
Fork the repo

Make changes

Submit a pull request

License
MIT License – free to use, modify, and distribute

Author
Vaibhav Adhikari

GitHub: 43vaibhav


Future Enhancements
External medical API integration

Mobile-friendly UI

Multi-language support

Improved AI prediction accuracy
