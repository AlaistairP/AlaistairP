# Hi, I'm Alaistair Preece 👋

I'm a student based in Ireland with a strong interest in computer science, embedded systems, and building things that solve real problems. I enjoy working across the full stack — from hardware sensors to APIs to automated pipelines.

---

## 🚀 Featured Project

### 🔥 [Wildfire Early Detection System — CS Student Assignment 2026](https://github.com/AlaistairP/Environmental-Project-2026)

A real-time wildfire risk detection system built around a **Raspberry Pi Pico**, a **MacBook**, and a three-tier hardware/software architecture. The system reads live environmental sensor data, models fire spread risk using a formula derived from the **Canadian Wildland Fire Information System**, and automatically fires a **Twilio SMS/phone call alert** when risk reaches a critical threshold — all without any user input once the system is running.

> **Stack:** Python · MicroPython · Raspberry Pi Pico · Twilio API · Open-Meteo API · pyserial · NumPy · Shell scripting

**Key features:**
- 🌡️ Live temperature and soil moisture readings via DHT11 and ADC sensors on the Pico
- 📡 Historical weather data pulled from the Open-Meteo API, validated against real wildfire events (2020 LNU Lightning Complex fires, 2023 Lahaina fires)
- 📊 Rate of Spread model based on the Rothermel surface fire spread formula — outputs LOW / MEDIUM / HIGH fire risk per hour
- 📲 Twilio integration sends an SMS and places a phone call when HIGH risk is detected
- 🔁 Fully automated pipeline — potentiometer threshold on the Pico triggers the entire MacBook analysis sequence via USB serial and `subprocess`
- 🔐 API keys managed via environment variables (not hardcoded)

---

## 🛠️ Skills & Tools

![Python](https://img.shields.io/badge/-Python-3776AB?style=flat&logo=python&logoColor=white)
![MicroPython](https://img.shields.io/badge/-MicroPython-2B2728?style=flat&logo=micropython&logoColor=white)
![JavaScript](https://img.shields.io/badge/-JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)
![React](https://img.shields.io/badge/-React-61DAFB?style=flat&logo=react&logoColor=black)
![HTML](https://img.shields.io/badge/-HTML5-E34F26?style=flat&logo=html5&logoColor=white)
![CSS](https://img.shields.io/badge/-CSS3-1572B6?style=flat&logo=css3&logoColor=white)
![Git](https://img.shields.io/badge/-Git-F05032?style=flat&logo=git&logoColor=white)
![Raspberry Pi](https://img.shields.io/badge/-Raspberry%20Pi-A22846?style=flat&logo=raspberrypi&logoColor=white)

---

## 📂 Other Projects

| Project | Description | Stack |
|---------|-------------|-------|
| [curling-project](https://github.com/AlaistairP/curling-project) | Applied Maths modelling project — estimates coefficient of restitution of curling stone collisions via video analysis, with KaTeX-rendered equations and SVG diagrams | React · KaTeX |
| [study-timetable-2](https://github.com/AlaistairP/study-timetable-2) | Browser-based Leaving Cert study timetable | HTML · CSS |

---

## 📬 Contact

- Twitter / X: [@AlaistairP](https://twitter.com/AlaistairP)
- GitHub: [github.com/AlaistairP](https://github.com/AlaistairP)
