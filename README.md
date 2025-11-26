🛡️ JoCAPTCHA
Next-Gen Human Verification | Smart. Interactive. Bot-Resistant.
<p align="center"> <img src="https://img.shields.io/badge/Status-Active-success?style=for-the-badge"> <img src="https://img.shields.io/badge/Frontend-React-blue?style=for-the-badge"> <img src="https://img.shields.io/badge/Backend-FastAPI-green?style=for-the-badge"> <img src="https://img.shields.io/badge/Cache-Redis-red?style=for-the-badge"> <img src="https://img.shields.io/badge/License-MIT-yellow?style=for-the-badge"> </p>
<p align="center"> <img src="https://raw.githubusercontent.com/PKief/vscode-material-icon-theme/main/icons/shield.svg" width="120"> </p> <p align="center"> <b>Modern CAPTCHA alternative powered by behavior-based human interaction ➜ Odd-One-Out, Rotate & Drag challenges</b> </p>
✨ Key Features
🧩 Multi-Modal Human Challenges

JoCAPTCHA uses three intelligent challenge types that are easy for humans but nearly impossible for bots:

🟡 Odd-One-Out Challenge

Identify the image that doesn’t belong.

<p align="center"> <img src="https://media.giphy.com/media/v1.Y2lkPTc5MGI3NjExMnZ6b2J2NHB6cGx6aTFrb3Qybnl6OWp6MXE5Nndra2R3ZGh6b2dtOCZlcD12MV9naWZzX3NlYXJjaCZjdD1n/GeimqsH0TLDt4tScGw/giphy.gif" width="420"> </p>
🔵 Drag & Drop Challenge

Test motor skills by dragging an object to a target zone.

<p align="center"> <img src="https://media.giphy.com/media/5xaOcLT5QMLe0E0m2Ew/giphy.gif" width="420"> </p>
🟢 Rotate Challenge

Rotate an object until it reaches the correct upright angle.

<p align="center"> <img src="https://media.giphy.com/media/l41YtZOb9EUABnuqA/giphy.gif" width="420"> </p>
⚙️ Admin Playground

✔ Enable/disable specific challenge types
✔ Adjust challenge difficulty with a slider
✔ Test new settings instantly in a live demo widget

<p align="center"> <img src="https://media.giphy.com/media/QBd2kLB5qDmysEXre9/giphy.gif" width="480"> </p>
🛠️ Developer Console (Debug Panel)

A live observability panel for developers:

📡 Real-time API logs

🔌 FastAPI backend connection status

🧪 Human verification results

🔐 Auto-generated security tokens (JWT-like)

<p align="center"> <img src="https://media.giphy.com/media/3o7aCVp8wXzFf6TiNW/giphy.gif" width="480"> </p>
⚡ Performance Highlights

💨 Ultra-Fast Redis Storage → stores challenge state & settings
📦 Stateless FastAPI Server → horizontally scalable
⚛️ Optimized React UI → smooth micro-interactions
🔐 Security-oriented → bot-resistant challenge logic

🏗️ Tech Stack
Frontend

React

Tailwind

Lucide Icons

Backend

FastAPI

Python

Pydantic

Cache / Data

Redis

📦 Installation & Setup
1️⃣ Backend Setup (FastAPI)
cd backend

# Create venv
python -m venv venv

# Activate
venv\Scripts\activate    # Windows
source venv/bin/activate # macOS/Linux

# Install packages
pip install -r requirements.txt

# Run server
uvicorn app.main:app --reload


Backend available at:
👉 http://127.0.0.1:8000

2️⃣ Frontend Setup (React)
cd frontend/captcha-frontend

npm install
npm start


Frontend available at:
👉 http://localhost:3000

🎮 How to Use
➤ Open App

Go to http://localhost:3000

➤ Start Verification

Click Start Verification inside the Demo page.

➤ View Developer Console

Watch real-time API logs & challenge results.

➤ Configure CAPTCHA

Go to Playground

Adjust difficulty

Toggle challenge types

Save configuration

Test instantly in Demo

📁 Project Structure
jocaptcha/
├── backend/
│   ├── app/
│   │   ├── assets/           
│   │   ├── models/          
│   │   ├── routes/          
│   │   ├── services/        
│   │   ├── config.py        
│   │   ├── main.py          
│   │   └── redis_client.py  
│   └── requirements.txt
│
├── frontend/captcha-frontend/
│   ├── src/
│   │   ├── components/
│   │   │   ├── captcha/     
│   │   │   ├── layout/      
│   │   │   └── pages/       
│   │   ├── services/        
│   │   └── App.js           
│   └── tailwind.config.js
└── README.md

🌐 Demo GIF (Optional for GitHub Pages)

If you deploy this project, you can add a live demo GIF or link here.

⭐ Contribute

Pull requests are welcome!
If you'd like to add challenge types or improve the UI, feel free to open an issue.

📜 License

MIT License – free for commercial and personal use.

👤 Credits

Built by Shaijo George
Designed as a modern open-source CAPTCHA alternative.
