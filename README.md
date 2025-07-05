# Data-Capstone-Project-1

📊 911 Emergency Calls - Data Analysis & Visualization

A data analysis and visualization project using a real-world 911 emergency calls dataset from Montgomery County, Pennsylvania.
The goal was to extract meaningful insights about emergency calls and visualize patterns across time, type, and location.

🧠 Project Objectives
Analyze 911 call data to find:
Most common emergency types (Traffic, EMS, Fire)
Peak hours and days for emergency calls
Trends across months and specific dates
Visualize these insights using plots like:
Countplots
Time series plots
Heatmaps and Clustermaps
📁 Dataset
Source: Kaggle - 911 Calls Dataset
Size: ~50,000+ records
Columns:
lat, lng: Location coordinates
desc: Description of the call
zip, twp: ZIP code and township
title: Reason of the emergency
timeStamp: Time of the call
e: Dummy column
📌 Key Insights
🚗 Traffic-related emergencies are the most frequent.
🕓 Most calls occur during working hours and weekdays.
📅 Call volume trends show monthly spikes and daily patterns.
🔥 Seaborn heatmaps show highest activity in specific hours vs. days.
🛠️ Tools & Libraries Used
Library	Purpose
pandas	Data wrangling & preprocessing
numpy	Numerical operations
matplotlib	Plotting graphs
seaborn	Advanced visualizations
📈 Visualizations Included
✅ Countplot of call reasons
✅ Countplot by day of week & month
✅ Time series plot of calls by date
✅ Heatmap: Day of Week vs Hour
✅ Clustermaps: Temporal patterns
📜 How to Run
# Clone this repository
git clone https://github.com/Ayankhann00/911-calls-analysis.git

# Navigate to folder
cd 911-calls-analysis

# Install dependencies
pip install pandas matplotlib seaborn numpy

# Run the script
python3 911_analysis.py
📌 Make sure 911.csv is in the same directory as your Python script.
📷 Sample Plots
<details> <summary>📊 Click to see visual examples</summary>
911 Calls by Reason

Monthly Call Trend

Heatmap of Calls by Hour & Day

</details>
🔗 Dataset Credit
Dataset by Mike Chirico on Kaggle
💡 What I Learned
Advanced pandas functions like .groupby(), .apply(), .map()
Time series analysis using datetime objects
Data storytelling using Seaborn and Matplotlib
Pattern detection using pivot tables and heatmaps
🚀 Future Work
Add geographic mapping using plotly or folium
Perform anomaly detection on spikes in call volume
Build an interactive dashboard (e.g., Streamlit or Dash)
🙌 Connect with Me
Ayan Khan
📍 NUST University | 💻 Data Science Enthusiast
📫 LinkedIn | GitHub

\Check my Plots Below 

![plot2](https://github.com/user-attachments/assets/df1078a2-568a-46fb-8cb4-77531f311b43)
![plot8](https://github.com/user-attachments/assets/553bd8dd-8598-4f90-8e1c-52c86e7b134b)
![plot10](https://github.com/user-attachments/assets/8b90e24b-62d7-4ce9-bf7b-1561e1a921f1)
![plot5](https://github.com/user-attachments/assets/2644a075-de16-4565-9635-10ade7a6fc7b)




