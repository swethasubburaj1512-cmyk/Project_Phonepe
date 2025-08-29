📊 **PhonePe Pulse Data Dashboard**

This project extracts and analyzes PhonePe Pulse data and provides an interactive dashboard built with Streamlit and Plotly.

It has two main components:

Data Extraction (phonepe_extraction.py) → Extracts raw JSON data, cleans it, and stores into a MySQL database.

Dashboard (phonepe_dashboard_app.py) → Interactive Streamlit app that visualizes transactions, user growth, and insurance penetration across India.

**Features**

 Extracts multiple datasets: Transactions, Users, Insurance

 Cleans & normalizes state, district, pincode data

 Stores processed data in MySQL tables

 Interactive dashboard with filters for Year, Quarter, State, District

 Visualizations: Choropleth maps, bar charts, pie charts, KPIs, case studies

 Business case study modules for insights

**Technical Part**

**Python**

Libraries:

pandas
mysql-connector-python
plotly
streamlit
requests, json
Database: MySQL

📂** Project Structure**


PhonePe_Project/



 ├── phonepe_extraction.py      # Extracts JSON data → MySQL
 
 ├── phonepe_dashboard_app.py   # Streamlit Dashboard
 
 ├── requirements.txt           # Dependencies
 
 ├── README.md                  # Documentation
 
📊 **Available Tables**



aggregate_transaction

aggregate_user

map_transaction

map_user

top_transaction

top_user

aggregated_insurance

map_insurance

top_insurance 



📌 **Dashboard Section**



Home → Overview 
Business Case Study → Transaction, User, and Insurance analysis
Case Study Dashboard → Deep dive into
Transaction dynamics
Device dominance
Insurance penetration
Market expansion
User engagement


