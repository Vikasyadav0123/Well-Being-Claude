# Windows Digital Wellbeing App

A real-time desktop activity tracking system that monitors application usage on Windows and provides detailed insights through a web-based dashboard.

---

## Overview

This application tracks active windows and applications running on a Windows system. It collects usage data and presents it in a structured format through charts, statistics, and timelines.

---

## Features

- Real-time application usage tracking  
- Daily screen time calculation  
- Hourly activity analysis  
- Weekly usage insights  
- Application-wise usage distribution  
- Window title tracking  
- Live dashboard with auto-refresh  

---

## Project Structure

Well-Being-Cloud/

- app.py          : Main entry point  
- server.py       : Backend API server  
- tracker.py      : Tracks active window and usage  
- storage.py      : Stores collected data  
- tray.py         : System tray integration  
- main.py         : Initializes the application  
- dashboard.html  : Frontend dashboard  
- .gitignore  
- README.md  

---

## Working

1. tracker.py continuously monitors the active application and window title  
2. storage.py saves usage data locally  
3. server.py provides API endpoints such as:
   - /api/today  
   - /api/week  
4. dashboard.html fetches the data and displays:
   - Usage statistics  
   - Charts  
   - Timeline  

---

## How to Run

1. Clone the repository  
git clone https://github.com/your-username/Well-Being-Cloud.git  

2. Navigate to the project folder  
cd Well-Being-Cloud  

3. Install dependencies  
pip install -r requirements.txt  

4. Run the application  
python app.py  

5. Open the dashboard in browser  
http://localhost:5000  

---

## Tech Stack

Frontend: HTML, CSS, JavaScript, Chart.js  
Backend: Python  
System Monitoring: Windows APIs / psutil  
Data Handling: Custom storage logic  

---

## Use Cases

- Productivity tracking  
- Screen time analysis  
- Work pattern analysis  
- Digital wellbeing monitoring  

---

## Privacy

All usage data is stored locally on the system. No external data sharing is performed.

---

## Future Scope

- AI-based usage recommendations  
- Focus mode and app blocking  
- Notifications and alerts  
- Cloud synchronization  

---

## Author

Vikas Yadav
