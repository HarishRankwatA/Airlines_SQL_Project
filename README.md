# Airlines Project using SQL & SQLite  

## 📌 Project Overview
This project focuses on analyzing airline operations using **SQL queries on a SQLite database** within a **Jupyter Notebook**.  
It demonstrates how to extract insights from flight, passenger, ticket, and revenue data through structured queries.  

## 🔹 Key Features
- **Flight Analysis**: Number of flights, routes, and schedules.  
- **Revenue Insights**: Total and average ticket revenue by aircraft type.  
- **Passenger Data**: Distribution of passengers and ticket bookings.  
- **Seat & Aircraft Details**: Number of seats per aircraft, aircraft utilization.  
- **SQL Operations**: Joins, grouping, aggregations, and subqueries.  

## 📊 Tools Used
- **SQLite** – Database engine  
- **Python (Jupyter Notebook)** – Query execution & analysis  
- **Pandas** – Data manipulation  
- **Matplotlib / Seaborn** – Data visualization (if used)  

## 📂 Project Files
- `Airlines_Project_using_SQL.ipynb` – Main notebook containing SQL queries & analysis  
- `sample_airlines.db` – Sample SQLite database (demo version, smaller than original)  

## 📂 Database Schema (Sample)
Key tables in the database include:  
- **Flights** – Flight ID, aircraft code, departure/arrival info  
- **Tickets** – Ticket ID, booking details, passenger info  
- **Boarding_Passes** – Ticket + seat assignment per flight  
- **Seats** – Seat number, aircraft code, seat type/class  
- **Aircrafts** – Aircraft model, total seats, configuration  

## 📷 Example Queries & Outputs
- **Total Revenue by Aircraft**  
- **Average Ticket Price per Flight**  
- **Number of Seats per Aircraft Model**  
- **Passenger Ticket Distribution**  

## 🚀 How to Use
1. Clone the repository:  
   ```bash
   git clone https://github.com/yourusername/Airlines-SQL-Project.git
   cd Airlines-SQL-Project
