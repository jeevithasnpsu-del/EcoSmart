# ♻️ EcoSmart – Smart Waste Management System

EcoSmart is an AI-powered Smart Waste Management System that combines **IoT, Machine Learning, Web Technologies, and Data Analytics** to improve waste collection, segregation, and monitoring. The platform provides real-time monitoring of smart bins, intelligent waste classification, route optimization, and environmental analytics through an interactive dashboard.

🌐 **Live Demo:** WEBSITE: https://ecosmart-j.netlify.app/
R ANALYTICS DASHBOARD: https://jee2920.shinyapps.io/smartecoplanet/

---

## 📖 Project Overview

Traditional waste management relies on fixed collection schedules, resulting in overflowing bins, unnecessary fuel consumption, and poor waste segregation.

EcoSmart solves these problems by integrating smart sensors, AI-based waste classification, and live monitoring to create an efficient and sustainable waste management ecosystem.

---

## 🚀 Features

### 📊 Interactive Dashboard
- Real-time smart bin monitoring
- Waste level visualization
- CO₂ savings tracker
- Temperature monitoring
- Humidity monitoring
- Methane level monitoring
- Battery status
- Sensor health monitoring
- Weekly waste collection analytics
- Active bin statistics
- Eco-friendly tips

### 🤖 AI Waste Classification
- Upload waste images
- Machine Learning based classification
- Identifies waste as:
  - Wet Waste
  - Dry Waste
  - Hazardous Waste

### 🗺️ Smart Bin Map
- Interactive map using Leaflet.js
- OpenStreetMap integration
- Locate nearby smart bins
- Monitor bin status in real time

### 📦 Throw Waste Module
- Simulates waste disposal
- Updates dashboard statistics
- Demonstrates smart segregation workflow

### 🚛 Route Optimization
- Detects bins above threshold
- Prioritizes urgent bins
- Optimizes collection routes
- Reduces fuel consumption

### 🔔 Smart Alerts
- Overflow alerts
- Sensor failure alerts
- Battery warnings
- Temperature anomaly alerts

---

## 🛠️ Technology Stack

**Frontend**
- React.js
- HTML5
- CSS3
- JavaScript (ES6+)
- Chart.js
- Leaflet.js
- OpenStreetMap
- HTML5 Canvas
- SVG

**Backend**
- Flask API
- Python

**Machine Learning**
- TensorFlow
- NumPy
- Pandas

**Database**
- Firebase Firestore
- Firebase Realtime Database
- Firebase Authentication

**IoT Hardware**
- ESP32 / NodeMCU
- Ultrasonic Sensor
- IR Sensor
- Soil Moisture Sensor
- Servo Motor (SG90)
- Buzzer
- LEDs

**Deployment**
- Netlify
- GitHub

---

## 📂 Project Structure
EcoSmart/
│
├── public/
├── src/
│ ├── components/
│ ├── pages/
│ ├── assets/
│ ├── services/
│ ├── hooks/
│ └── App.js
│
├── firebase/
├── flask-api/
├── package.json
└── README.md
---

## ⚙️ System Workflow
User
│
▼
Throw Waste
│
▼
IoT Sensors Collect Data
│
▼
Firebase Database
│
▼
AI Classification (Flask + TensorFlow)
│
▼
Dashboard Updates
│
▼
Bin Fill Level ≥ 80%
│
▼
Route Optimization
│
▼
Waste Collection


---

## 📈 Dashboard Metrics

- Wet Waste %
- Dry Waste %
- Hazardous Waste %
- Battery Status
- Sensor Status
- Bin Fill Level
- Temperature
- Humidity
- Methane Level
- CO₂ Saved
- Weekly Collection Report
- Active Bins

---

## 🎯 Objectives

- Promote sustainable waste management
- Reduce unnecessary collection trips
- Improve waste segregation accuracy
- Enable real-time monitoring
- Support smart city initiatives
- Reduce environmental pollution

---

## 💡 Future Enhancements

- Mobile Application
- QR Code-based Waste Tracking
- Reward System for Recycling
- Predictive Analytics
- GPS-enabled Collection Vehicles
- AI-powered Route Optimization
- Carbon Footprint Analytics
- Smart Notifications

---

## 📷 Screenshots

> Add screenshots of:
- Dashboard
- AI Classification
- Bin Map
- Throw Waste Module
- Analytics Charts

---

## 📦 Installation

Clone the repository:
```bash
git clone https://github.com/yourusername/ecosmart.git
```

Navigate to the project:
```bash
cd ecosmart
```

Install dependencies:
```bash
npm install
```

Run the project:
```bash
npm start
```

Run Flask API:
```bash
cd flask-api
pip install -r requirements.txt
python app.py
```

---

## 👨‍💻 Team

**EcoSmart Development Team**
- Frontend Development
- Backend Development
- Machine Learning
- IoT Integration
- Firebase Integration
- Data Analytics

---

## 📚 Academic Project

This project was developed as an interdisciplinary academic project integrating:
- Web Technology
- Internet of Things (IoT)
- Machine Learning
- Mobile Application Development
- Data Analytics
- Software Engineering

---

## 🌍 Impact

EcoSmart contributes toward:
- ♻️ Sustainable Cities
- 🌱 Climate Action
- 🚮 Smart Waste Collection
- 📊 Data-driven Decision Making
- 🌎 Cleaner Environment

---

## 📄 License

This project is developed for educational and academic purposes.

---

## ⭐ If you like this project, don't forget to star the repository!

Swap yourusername in the clone URL for your actual GitHub username/repo path before you commit it.

i also have r analytics dashboard https://jee2920.shinyapps.io/smartecoplanet/ give readme for tht

Synthesized Shiny dashboard architecture and drafted comprehensive README documentation
Synthesized Shiny dashboard architecture and drafted comprehensive README documentation

Can't fetch that one directly — shinyapps.io blocks automated access. I'll build this from what I know of your R Shiny dashboard (EcoSmart-BLR): multi-role RBAC, Firebase Auth/Realtime DB, IoT sensor simulation across Bangalore wards, linear regression fill prediction, PDF export, CI/CD to shinyapps.io. Flag anything that's drifted since.

markdown
# 🗑️ SmartEcoPlanet – R Analytics Dashboard for Bangalore Waste Management

SmartEcoPlanet is an R Shiny–powered analytics dashboard that brings **role-based smart waste monitoring, IoT sensor simulation, and ML-driven fill prediction** to Bangalore's municipal waste management workflow. Built for administrators, municipal officers, and field staff to track, predict, and report on smart bin activity across city wards in real time.

🌐 **Live Demo:** https://jee2920.shinyapps.io/smartecoplanet/

---

## 📖 Project Overview

Municipal waste teams often lack a unified, real-time view of bin status across a city — data is siloed, collection is reactive, and reporting is manual.

SmartEcoPlanet solves this with a single R Shiny dashboard that simulates IoT sensor data across Bangalore wards, applies machine learning to predict when bins will reach capacity, and gives every role — from citizens to admins — a tailored view of the system.

---

## 🚀 Features

### 🔐 Role-Based Access Control (RBAC)
Four distinct dashboard views, each scoped to what that role needs:
- **Admin** — full system oversight, all wards, all metrics
- **Municipal Officer** — ward-level monitoring and reporting
- **Collection Staff** — assigned bin routes and pickup status
- **Citizen** — nearby bin status and reporting tools

### 📡 IoT Sensor Simulation
- Simulated smart bin sensors deployed across Bangalore wards
- Live fill-level readings updated in real time
- Ward-by-ward breakdown of bin status

### 🤖 ML-Based Fill Prediction
- Linear regression model forecasting bin fill trajectory
- Flags bins approaching capacity before they overflow
- Supports proactive rather than reactive collection scheduling

### 📄 PDF Report Export
- One-click generation of shareable waste management reports
- Useful for municipal reporting and audits

### 🔥 Firebase Integration
- Firebase Authentication for secure, role-based login
- Firebase Realtime Database for live data sync across sessions

### 🛡️ Input Sanitization
- Hardened against malformed/malicious input on all user-facing forms

---

## 🛠️ Technology Stack

**Core**
- R
- R Shiny / Shiny Dashboard

**Auth & Data**
- Firebase Authentication
- Firebase Realtime Database

**Machine Learning**
- Linear Regression (fill-level prediction)

**Reporting**
- PDF export (R Markdown / rmarkdown-based generation)

**CI/CD & Deployment**
- GitHub Actions (automated pipeline)
- shinyapps.io

---

## 📂 Project Structure

SmartEcoPlanet/
│
├── app.R # Main Shiny app entry point
├── R/
│ ├── ui/ # UI modules per role
│ ├── server/ # Server logic per role
│ ├── auth/ # Firebase auth handlers
│ ├── models/ # ML fill-prediction logic
│ └── reports/ # PDF report generation
│
├── www/ # Static assets
├── .github/
│ └── workflows/ # CI/CD pipeline config
├── data/ # Simulated ward/sensor data
└── README.md


---

## ⚙️ System Workflow

User Login (Role-Based)
│
▼
Firebase Auth Verifies Role
│
▼
IoT Sensor Data Synced (Firebase Realtime DB)
│
▼
Fill-Level Prediction (Linear Regression)
│
▼
Role-Specific Dashboard Renders
│
▼
Admin/Officer Reviews Ward Data
│
▼
PDF Report Generated (on demand)


---

## 👥 User Roles

| Role | Access |
|---|---|
| Admin | Full system access, all wards, user management |
| Municipal Officer | Ward-level monitoring, reporting tools |
| Collection Staff | Assigned routes, pickup confirmation |
| Citizen | Nearby bin status, issue reporting |

---

## 🎯 Objectives

- Give municipal teams a real-time, ward-level view of waste bin status
- Predict bin overflow before it happens using ML
- Reduce manual reporting overhead with automated PDF exports
- Provide role-appropriate access so every stakeholder sees only what's relevant
- Support data-driven decisions for Bangalore's smart city waste strategy

---

## 💡 Future Enhancements

- Real IoT hardware integration (replacing simulated sensors)
- More advanced ML models (e.g. time-series forecasting) for fill prediction
- Route optimization for Collection Staff
- Mobile-friendly citizen reporting
- Historical trend analytics across wards

---

## 📦 Installation

Clone the repository:
```bash
git clone https://github.com/jeevithasnpsu-del/EcoSmart-BLR.git
```

Navigate to the project:
```bash
cd EcoSmart-BLR
```

Install R dependencies (in R console):
```r
install.packages(c("shiny", "shinydashboard", "firebase", "rmarkdown"))
```

Run the app:
```r
shiny::runApp()
```

---

## 🚀 CI/CD

This project uses GitHub Actions to automatically deploy to shinyapps.io on push to the main branch. See `.github/workflows/` for pipeline configuration.

---

## 👨‍💻 Team

**Built by Jeevitha M** as part of an ongoing portfolio of civic tech and smart city projects.

---

## 📚 Academic / Portfolio Project

This project was developed as part of an interdisciplinary smart city initiative integrating:
- Data Science
- Web Application Development (R Shiny)
- Machine Learning
- Cloud Database Integration (Firebase)
- CI/CD & DevOps

---

## 🌍 Impact

SmartEcoPlanet contributes toward:
- ♻️ Sustainable Cities
- 🌱 Climate Action
- 🚮 Smart, Data-Driven Waste Collection
- 📊 Transparent Municipal Reporting

---

## 📄 License

This project is developed for educational and portfolio purposes.

---

## ⭐ If you like this project, don't forget to star the repository!

# 🗑️ SmartEcoPlanet – R Analytics Dashboard for Bangalore Waste Management

SmartEcoPlanet is an R Shiny–powered analytics dashboard that brings **role-based smart waste monitoring, IoT sensor simulation, and ML-driven fill prediction** to Bangalore's municipal waste management workflow. Built for administrators, municipal officers, and field staff to track, predict, and report on smart bin activity across city wards in real time.

🌐 **Live Demo:** https://jee2920.shinyapps.io/smartecoplanet/

---

## 📖 Project Overview

Municipal waste teams often lack a unified, real-time view of bin status across a city — data is siloed, collection is reactive, and reporting is manual.

SmartEcoPlanet solves this with a single R Shiny dashboard that simulates IoT sensor data across Bangalore wards, applies machine learning to predict when bins will reach capacity, and gives every role — from citizens to admins — a tailored view of the system.

---

## 🚀 Features

### 🔐 Role-Based Access Control (RBAC)
Four distinct dashboard views, each scoped to what that role needs:
- **Admin** — full system oversight, all wards, all metrics
- **Municipal Officer** — ward-level monitoring and reporting
- **Collection Staff** — assigned bin routes and pickup status
- **Citizen** — nearby bin status and reporting tools

### 📡 IoT Sensor Simulation
- Simulated smart bin sensors deployed across Bangalore wards
- Live fill-level readings updated in real time
- Ward-by-ward breakdown of bin status

### 🤖 ML-Based Fill Prediction
- Linear regression model forecasting bin fill trajectory
- Flags bins approaching capacity before they overflow
- Supports proactive rather than reactive collection scheduling

### 📄 PDF Report Export
- One-click generation of shareable waste management reports
- Useful for municipal reporting and audits

### 🔥 Firebase Integration
- Firebase Authentication for secure, role-based login
- Firebase Realtime Database for live data sync across sessions

### 🛡️ Input Sanitization
- Hardened against malformed/malicious input on all user-facing forms

---

## 🛠️ Technology Stack

**Core**
- R
- R Shiny / Shiny Dashboard

**Auth & Data**
- Firebase Authentication
- Firebase Realtime Database

**Machine Learning**
- Linear Regression (fill-level prediction)

**Reporting**
- PDF export (R Markdown / rmarkdown-based generation)

**CI/CD & Deployment**
- GitHub Actions (automated pipeline)
- shinyapps.io

---

## 📂 Project Structure

SmartEcoPlanet/
│
├── app.R # Main Shiny app entry point
├── R/
│ ├── ui/ # UI modules per role
│ ├── server/ # Server logic per role
│ ├── auth/ # Firebase auth handlers
│ ├── models/ # ML fill-prediction logic
│ └── reports/ # PDF report generation
│
├── www/ # Static assets
├── .github/
│ └── workflows/ # CI/CD pipeline config
├── data/ # Simulated ward/sensor data
└── README.md


---

## ⚙️ System Workflow

User Login (Role-Based)
│
▼
Firebase Auth Verifies Role
│
▼
IoT Sensor Data Synced (Firebase Realtime DB)
│
▼
Fill-Level Prediction (Linear Regression)
│
▼
Role-Specific Dashboard Renders
│
▼
Admin/Officer Reviews Ward Data
│
▼
PDF Report Generated (on demand)


---

## 👥 User Roles

| Role | Access |
|---|---|
| Admin | Full system access, all wards, user management |
| Municipal Officer | Ward-level monitoring, reporting tools |
| Collection Staff | Assigned routes, pickup confirmation |
| Citizen | Nearby bin status, issue reporting |

---

## 🎯 Objectives

- Give municipal teams a real-time, ward-level view of waste bin status
- Predict bin overflow before it happens using ML
- Reduce manual reporting overhead with automated PDF exports
- Provide role-appropriate access so every stakeholder sees only what's relevant
- Support data-driven decisions for Bangalore's smart city waste strategy

---

## 💡 Future Enhancements

- Real IoT hardware integration (replacing simulated sensors)
- More advanced ML models (e.g. time-series forecasting) for fill prediction
- Route optimization for Collection Staff
- Mobile-friendly citizen reporting
- Historical trend analytics across wards

---

## 📦 Installation

Clone the repository:
```bash
git clone https://github.com/jeevithasnpsu-del/EcoSmart-BLR.git
```

Navigate to the project:
```bash
cd EcoSmart-BLR
```

Install R dependencies (in R console):
```r
install.packages(c("shiny", "shinydashboard", "firebase", "rmarkdown"))
```

Run the app:
```r
shiny::runApp()
```

---

## 🚀 CI/CD

This project uses GitHub Actions to automatically deploy to shinyapps.io on push to the main branch. See `.github/workflows/` for pipeline configuration.

---

## 👨‍💻 Team

**Built by Jeevitha M** as part of an ongoing portfolio of civic tech and smart city projects.

---

## 📚 Academic / Portfolio Project

This project was developed as part of an interdisciplinary smart city initiative integrating:
- Data Science
- Web Application Development (R Shiny)
- Machine Learning
- Cloud Database Integration (Firebase)
- CI/CD & DevOps

---

## 🌍 Impact

SmartEcoPlanet contributes toward:
- ♻️ Sustainable Cities
- 🌱 Climate Action
- 🚮 Smart, Data-Driven Waste Collection
- 📊 Transparent Municipal Reporting

---

## 📄 License

This project is developed for educational and portfolio purposes.

---

