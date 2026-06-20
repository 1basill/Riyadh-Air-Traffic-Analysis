# Riyadh Airport Flights Data Exploratory Analysis

> Why do 74% of Riyadh's flights go international,  
> and what does that mean for airport strategy?

## Project Overview
This project analyzes King Khalid International Airport flight data using Python, Pandas, and PowerBI to extract meaningful insights about airline performance, destinations, terminals, and airport traffic to improve insights and decision-making.


<img width="467" height="263" alt="image" src="https://github.com/user-attachments/assets/8dd11ccb-60ab-41fc-b372-b3b05b87f6f7" />



## Objective 
- Load and process flight data using Python  
- Identify and clean missing and inconsistent data  
- Analyze flight activity associated with Riyadh Airport(RUH)  
- Analyze flight patterns during different time periods  
- Identify the busiest airlines and popular tourist destinations  
- Produce Relevant visualizations for actionable insights  


## Data Description 
- Flight Number  
- Aircraft Model   
- Airline Name / code(IATA, ICAO)  
- Flight Status  
- Scheduled time (UTC and local)  
- Airports information (origin / destination)  
- Departure and Arrival Schedules  


## Key Insight
- Airline Performance: Top 3 airlines (Saudia, Flynas, Flyadeal) account for 78.05% of total  
- Destination Performance : Top 3 Cities (Jeddah,Dubai,Cairo) account for 32.8% of total  
- Operational Peak : Identifying a major traffic surge between 20:00 – 23:00 , where the airport handles nearly 25.75% of its daily operations  
- Seasonal Data Note: flight volume is generally stable by months, and the lower numbers in March and October are caused by partial data collection during those months
-  Route Type: 73.74% of RUH flights are international vs 26.26% domestic


## Business Recommendations

- **Peak staffing:** 25.75% of operations happen in 3 hours (20:00–23:00)
  → Increase ground staff during this window to reduce delays

- **Airline risk:** Top 3 airlines = 78% of traffic
  → Incentivize new carriers to reduce concentration risk

- **Route optimization:** Jeddah, Dubai, Cairo = 32.8% of flights
  → Dedicated fast-track lanes for these routes


## Tools 
Categories  | Tools
------------- | -------------
Programming  | Python
Data Manipulation  | Pandas
Data Visualization | PowerBI, Matplotlib
Data Source | Parquet 
Processing Format | csv


## Dataset Source: 
https://www.kaggle.com/datasets/mohammedalsubaie/king-khalid-international-airport-flights-dataset


 
 
