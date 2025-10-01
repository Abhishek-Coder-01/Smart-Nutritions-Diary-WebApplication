# Smart Nutrition Diary

**Smart Nutrition Diary** is a web app to track, analyze, and improve daily eating habits. Users can log foods, view nutritional breakdowns, and maintain a food diary. Built with Flask (Python) and Tailwind CSS for a modern, responsive UI.

---

## 🔍 Table of Contents
- [Features](#-features)
- [Tech Stack](#-tech-stack)
- [Screenshots](#-screenshots)
- [Getting Started](#-getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
  - [Database Setup](#database-setup)
  - [Run Locally](#run-locally)
- [Generating `requirements.txt`](#generating-requirementstxt)
- [Project Structure](#project-structure)
- [API Endpoints / Routes (Example)](#api-endpoints--routes-example)
- [Deployment Tips](#deployment-tips)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

---

## 🥗 Features
- Add / edit / delete food entries (meals & snacks).
- Daily and weekly food diary view.
- Nutrient breakdown: calories, protein, carbs, fats, vitamins, minerals.
- Search food database (local or external API).
- User authentication (register / login) and session-based dashboards.
- Responsive UI with Tailwind CSS (CDN option supported).
- Optional Firebase authentication or 3rd-party sign-in integrations.

---

## 🛠 Tech Stack
- **Frontend:** HTML, Tailwind CSS, JavaScript (vanilla)
- **Backend:** Flask (Python), Jinja2 templates
- **Database:** SQLite (default) — can swap to Postgres or Firebase
- **Icons:** FontAwesome (CDN)

---

## 📸 Screenshots:
### 1. Home
<img width="1908" height="1027" alt="Screenshot 2025-10-02 020140" src="https://github.com/user-attachments/assets/6849e338-d1c3-4028-b0c0-253f02bb72ca" />

### 2. How It Works
<img width="1909" height="998" alt="Screenshot 2025-10-02 020209" src="https://github.com/user-attachments/assets/2136b346-0284-4cb8-bb7e-f9bdbd3d78d9" />

### 3. Ready to transform of Nutrition
<img width="1919" height="1026" alt="Screenshot 2025-10-02 020232" src="https://github.com/user-attachments/assets/0a014050-3a4b-469c-a1be-7d6a9a3431af" />

### 4. Register
<img width="623" height="1018" alt="Screenshot 2025-10-02 020325" src="https://github.com/user-attachments/assets/bc67021d-a27d-4f4b-a885-fd5377674c54" />

### 5. Login
<img width="588" height="785" alt="Screenshot 2025-10-02 020341" src="https://github.com/user-attachments/assets/5711da6b-9486-4819-9705-5c9cdb55f2da" />

### 6. Food Diary
<img width="1898" height="882" alt="Screenshot 2025-10-02 020605" src="https://github.com/user-attachments/assets/d09ef58e-be2f-45f0-96e7-1f514bcbe04d" />

### 7. Food Diary
<img width="1907" height="909" alt="Screenshot 2025-10-02 020652" src="https://github.com/user-attachments/assets/cfa73a6d-1c75-4752-9e07-c7da0fe2f59e" />



---

## 🚀 Getting Started
https://smart-nutritions-diary-webapplication.onrender.com/

### Prerequisites
- Python 3.10+ (recommended)
- `pip`
- (Optional) `git`, virtualenv/venv


## 📁 Project Structure 
<img width="657" height="842" alt="image" src="https://github.com/user-attachments/assets/437ed87a-b645-43f8-83e2-0a901dace3e4" />


### Installation (local)
1. Clone the repo:
   ```bash
   git clone https://github.com/abhsihek0coder-01/smart-nutrition-diary.git
   cd smart-nutrition-diary

2. Set up environment variables
   FLASK_APP=app.py
   FLASK_ENV=development
   ABBREV.csv
   DATABASE_URL=sqlite:///instance/db.sqlite3


   
   
