# 🌲 Smart Forest Environmental Monitoring & Early Warning System

<p align="center">

![Python](https://img.shields.io/badge/Python-3.11-blue?style=for-the-badge&logo=python)
![Flask](https://img.shields.io/badge/Flask-Backend-black?style=for-the-badge&logo=flask)
![Arduino](https://img.shields.io/badge/Arduino-Uno-00979D?style=for-the-badge&logo=arduino)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-Database-336791?style=for-the-badge&logo=postgresql)
![HTML5](https://img.shields.io/badge/HTML5-Frontend-E34F26?style=for-the-badge&logo=html5)
![CSS3](https://img.shields.io/badge/CSS3-Styling-1572B6?style=for-the-badge&logo=css3)
![JavaScript](https://img.shields.io/badge/JavaScript-Interactive-F7DF1E?style=for-the-badge&logo=javascript)
![Status](https://img.shields.io/badge/Project-Completed-success?style=for-the-badge)

</p>

---

# 📌 Project Overview

The **Smart Forest Environmental Monitoring & Early Warning System** is an IoT-based solution designed to continuously monitor environmental conditions in forest areas and provide early warnings for hazardous situations.

The system collects real-time data from multiple environmental sensors connected to an **Arduino Uno**, including:

- 🌡 Temperature
- 💧 Humidity
- 🌫 Carbon Dioxide (CO₂)
- 🔥 Fire Detection

The collected data is transmitted to a **Flask REST API**, stored in a **PostgreSQL database**, and displayed on a responsive **web dashboard** that enables users to monitor sensor values, visualize trends, and receive alerts whenever dangerous conditions are detected.

This project demonstrates the integration of **Embedded Systems**, **Internet of Things (IoT)**, **Backend Development**, **Database Management**, and **Web Development** into a complete real-world monitoring solution.

---

# 🚀 Features

- 🌲 Real-Time Environmental Monitoring
- 🌡 Live Temperature Monitoring
- 💧 Humidity Monitoring
- 🌫 CO₂ Level Monitoring
- 🔥 Fire Detection
- 🚨 Early Warning Alert System
- 📊 Interactive Dashboard
- 📈 Historical Data Visualization
- 🔐 User Authentication
- 👤 Admin Dashboard
- 🗄 PostgreSQL Database Integration
- 🌐 Flask REST API
- 📱 Responsive Web Interface

---

# 🛠 Technology Stack

## Hardware

- Arduino Uno
- MQ Gas Sensor (CO₂ / Smoke)
- Temperature Sensor
- Humidity Sensor
- Jumper Wires
- Breadboard
- USB Communication

---

## Software

- Python
- Flask
- PostgreSQL
- HTML5
- CSS3
- JavaScript

---

## Development Tools

- Arduino IDE
- Visual Studio Code
- pgAdmin
- Git
- GitHub

---

# ⚙ System Architecture

```
                     Environmental Sensors
      (Temperature • Humidity • CO₂ • Fire)
                         │
                         ▼
                  Arduino Uno Board
                         │
                         ▼
                   Flask REST API
                         │
                         ▼
                 PostgreSQL Database
                         │
                         ▼
                Interactive Web Dashboard
                         │
                         ▼
                  Users / Administrators
```

---

# 📂 Project Structure

```
Smart-Forest-Environmental-Monitoring-System
│
├── Hardware
│   ├── Arduino_Code.ino
│   ├── Hardware_Setup.jpg
│   └── Circuit_Diagram.png
│
├── Backend
│   ├── app.py
│   ├── requirements.txt
│
├── Frontend
│   ├── index.html
│   ├── style.css
│   └── script.js
│
├── Database
│   └── forestmonitoring.sql
│
├── Documentation
│   └── Project_Report.pdf
│
├── Images
│   ├── Hardware.jpg
│   ├── Dashboard.png
│   ├── Login.png
│   ├── Alerts.png
│   └── Architecture.png
│
└── README.md
```

---

# 📷 Hardware Setup

Replace the image below after uploading your hardware picture.

```text
Images/Hardware.jpg
```

```markdown
![Hardware Setup](Images/Hardware.jpg)
```

---

# 📷 Dashboard Preview

Upload dashboard screenshots inside the **Images** folder.

```markdown
![Dashboard](Images/Dashboard.png)
```

---

# 📷 Login Page

```markdown
![Login](Images/Login.png)
```

---

# 📷 Alert System

```markdown
![Alerts](Images/Alerts.png)
```

---

# 🗄 Database

The project uses **PostgreSQL** for storing:

- Sensor Readings
- Temperature Data
- Humidity Data
- CO₂ Levels
- Fire Alerts
- User Accounts
- Historical Records

---

# 🌐 REST API

The Flask backend provides APIs for:

- Receiving sensor data
- Storing readings
- Fetching historical records
- User authentication
- Dashboard data
- Alert generation

---

# 📊 Dashboard Features

The web dashboard provides:

- Live Sensor Monitoring
- Interactive Charts
- Environmental Statistics
- Fire Detection Status
- CO₂ Monitoring
- Temperature Trends
- Humidity Trends
- Alert Notifications
- User Login
- Administrator Controls

---

# 🔥 Fire Detection

The system continuously monitors fire-related conditions.

Whenever dangerous values exceed predefined thresholds:

- Fire Alert is generated
- Dashboard updates immediately
- Alert is stored in database

---

# 🌫 CO₂ Monitoring

The MQ Gas Sensor continuously monitors CO₂ concentration.

The dashboard displays:

- Current CO₂ Level
- Historical CO₂ Data
- Alert Status

---

# 🌡 Temperature Monitoring

The system records temperature in real time.

Users can visualize:

- Current Temperature
- Temperature Trends
- Historical Records

---

# 💧 Humidity Monitoring

Humidity values are continuously monitored and stored.

The dashboard displays:

- Current Humidity
- Historical Humidity
- Trend Analysis

---

# 💡 Future Improvements

- 📱 Android Mobile Application
- ☁ Cloud Deployment
- 📩 Email Notifications
- 📲 SMS Alerts
- 📍 GPS-Based Node Tracking
- 🤖 Machine Learning for Fire Prediction
- 📡 Wireless Sensor Network Expansion
- 🌍 Multi-location Monitoring

---

# 📈 Skills Demonstrated

- Internet of Things (IoT)
- Embedded Systems
- Arduino Programming
- Sensor Integration
- Python Development
- Flask API Development
- PostgreSQL Database Design
- HTML5
- CSS3
- JavaScript
- Dashboard Development
- REST API Design
- Database Management
- Git & GitHub
- Problem Solving

---

# 📚 Installation

### Clone Repository

```bash
git clone https://github.com/YOUR_USERNAME/Smart-Forest-Environmental-Monitoring-System.git
```

---

### Install Python Packages

```bash
pip install -r requirements.txt
```

---

### Run Flask Server

```bash
python app.py
```

---

### Open Website

```
http://localhost:5000
```

---

# 🤝 Contributing

Contributions are welcome!

Feel free to fork this repository, create a new branch, and submit a pull request.

---

# 📄 License

This project is available under the MIT License.

---

# 👩‍💻 Author

## **Areeba Shahid**

**Machine Learning | Artificial Intelligence | IoT | Software Engineering**

📧 Email: your-email@example.com

🔗 GitHub: https://github.com/AreebaShahid6

🔗 LinkedIn: https://www.linkedin.com/in/YOUR-LINKEDIN

---

## ⭐ If you found this project useful, consider giving it a Star!

It helps support the project and encourages future improvements.
