# ⚡ Electricity Consumption Dashboard



## 🎯 Project Overview
This project is an interactive dashboard built using Python and Dash to monitor and analyze electricity consumption of different devices. It helps users track daily energy usage, compare appliances, and estimate cost based on usage.



## ⚙️ Tech Stack
- Python – Core programming  
- Pandas – Data processing  
- Plotly Express – Data visualization  
- Dash – Web dashboard framework  


## 🏗️ Project Architecture
The project follows a single-file full-stack architecture using Dash, where both frontend and backend are handled in Python.

### Components:
- Backend – Data processing and logic  
- Frontend – UI components (graphs, dropdowns)  
- Callback system – Connects UI with backend  


## 🔄 Workflow

### Data Loading
- Reads CSV file using Pandas  
- Validates file existence  
- Handles missing data  

### Dynamic Column Detection
- Automatically detects columns like:
  - Date  
  - Device  
  - Power  
  - Usage Hours  

### Data Processing
- Converts date column to datetime  
- Calculates:
  - Energy (kWh) = (Power × Hours) / 1000  
  - Cost = Energy × rate  

### UI Development
- Title  
- Dropdown for device selection  
- Graphs:
  - Line chart (daily consumption)  
  - Bar chart (device comparison)  
  - Area chart (cost trend)  

### Interactivity
- Implemented using Dash callbacks  
- Updates graphs dynamically based on user selection  

### Data Visualization
- Line chart → Trends  
- Bar chart → Comparison  
- Area chart → Cost  

### Summary Metrics
- Total energy consumption  
- Total cost  



## ▶️ How to Run
python app.py

Open in browser:
http://localhost:8050



## 💡 Features
- Interactive dashboard  
- Real-time filtering  
- Automatic column detection  
- Cost estimation  
- Clean visualization  
- Error handling  



## 🚀 Challenges & Solutions

**Challenge:** Different CSV formats  
**Solution:** Dynamic column mapping  

**Challenge:** Data inconsistency  
**Solution:** Handled missing values using Pandas  

**Challenge:** Interactivity  
**Solution:** Dash callbacks for frontend-backend connection  



## 📈 Future Enhancements
- Date range filter  
- User authentication  
- Cloud deployment (AWS / Render / Heroku)  
- Real-time IoT data  
- Machine learning predictions  



## 🧠 Key Insight
This is a full-stack application where Dash handles frontend rendering while Python manages backend logic and data processing.


## 🙌 Acknowledgements
Inspired by modern data dashboards and energy monitoring systems.

## ⭐ Support
If you like this project, give it a ⭐ on GitHub!



## 📜 License
This project is open-source and available under the MIT License.
