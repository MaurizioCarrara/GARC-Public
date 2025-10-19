# G.A.R.C. – General Aviation Report Creator  

![Python](https://img.shields.io/badge/Python-3.9+-3776AB?logo=python&logoColor=white)
![Dash](https://img.shields.io/badge/Dash-Plotly-00D4FF?logo=plotly&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-Data_Analysis-150458?logo=pandas&logoColor=white)
![Status](https://img.shields.io/badge/Status-v2.1-success)
![License](https://img.shields.io/badge/License-Private-red)

**G.A.R.C. (General Aviation Report Creator)** is a Python application developed with the Dash framework.  
Its purpose is to provide an efficient and secure way to analyze General Aviation flight data through an interactive web interface accessible locally.  

The application connects to an encrypted server, retrieves the flight database, and generates a set of analytical reports and visualizations directly in the browser.  

---

## Data Management & Security  
- Flight data are stored on a secured, encrypted server.  
- Each session retrieves the necessary data on demand, which are held only in memory and discarded once the app is closed.  
- This approach ensures both **data security** and **system efficiency**, avoiding unnecessary local storage.

  ![Download_data](https://github.com/MaurizioCarrara/GARC-Public/blob/main/GIFs/downloadDB.gif)
---

## Current Features (v2.1)  
- **Data filtering** by date range and airport.  
- **Automatic generation of analytical reports**, combining multiple visualizations and tables (equivalent to 5 A4 pages if exported).  
- **Web-based interface** running on `localhost`, allowing easy access and navigation without external deployment.  

![Data Selectors](https://github.com/MaurizioCarrara/GARC-Public/blob/main/GIFs/Selectors.gif)  

---

## Roadmap (v3.0)  
Planned enhancements include:  
- **Linear regression models** for movements and MTOW (Maximum Take-Off Weight).  
- **Rate of change analysis** for key metrics.  
- **Multi-page architecture** for better report organization and scalability.  

---

## Known Limitations  
- Data loading speed is dependent on hardware performance.  
- Codebase (functions and classes) is currently being refactored for improved efficiency and maintainability.  

---

## Project Goal  
The G.A.R.C. project demonstrates the ability to design and implement a complete **data analysis pipeline**:  
- Secure data retrieval → Processing → Visualization → Reporting.  
It highlights practical skills in **Python, Dash, data modeling, and reporting automation**, with direct applicability to aviation data management and beyond.  

---

