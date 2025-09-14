# U.S. Airline Flights Delay & Cancellations Analysis (2015)

Data Source: https://mavenanalytics.io/data-playground/airline-flight-delays

Records for 5,000,000+ commercial airline flights in 2015, compiled for the U.S. DOT Air Travel Consumer Report. Each record represents a single flight, including the airline name, flight number, origin/destination airport and flight distance, as well as scheduled/actual departure and arrival times.

# Project Overview

This project analyzes the U.S. domestic flight dataset for 2015, focusing on flight delays, cancellations, and airline performance.

The goal was to identify patterns and insights around:

    Seasonal and weekly flight volumes
    
    Departure delays and their severity
    
    Airport and airline reliability
    
    Cancellations and their causes

Through exploratory data analysis (EDA) using Python (Pandas, Matplotlib, Seaborn), we highlight operational inefficiencies and uncover trends that impact both airlines and passengers.

# Tools & Skills Used

    Python: Pandas, NumPy, Matplotlib, Seaborn
    
    Data Cleaning: Handling missing values, filtering cancellations, converting time formats
    
    Exploratory Data Analysis (EDA): Aggregations, group-bys, visualizations
    
    Airline Industry Knowledge: Delay classifications, cancellation codes interpretation

# Dataset

Records for 5,000,000+ commercial airline flights in 2015, compiled for the U.S. DOT Air Travel Consumer Report. Each record represents a single flight, including the airline name, flight number, origin/destination airport and flight distance, as well as scheduled/actual departure and arrival times.

Link: https://mavenanalytics.io/data-playground/airline-flight-delays

    Source: U.S. Department of Transportation (Bureau of Transportation Statistics).

# Key Analyses & Insights

=== Flight volume by MONTH (2015) ===

<img width="874" height="467" alt="image" src="https://github.com/user-attachments/assets/46d9193a-ad30-4f39-a16b-f2d0f46fde15" />

=== Flight volume by DAY_OF_WEEK (2015) ===

<img width="872" height="459" alt="image" src="https://github.com/user-attachments/assets/7c4ded26-2b0d-439f-bbd4-ce4a74c86a16" />

=== Departure delay summary (2015) ===

        Total flights that departed (CANCELLED==0): 5,729,195
        Number of departures with DEPARTURE_DELAY > 0: 2,123,078
        Percentage delayed on departure (of departures): 37.06%
        Average departure delay among delayed flights: 32.61 minutes

<img width="855" height="464" alt="image" src="https://github.com/user-attachments/assets/a038cc28-bc61-49ff-9a39-44196e59d3dc" />

=== Monthly % of delayed departures (2015) ===

<img width="843" height="464" alt="image" src="https://github.com/user-attachments/assets/27b1c59d-5c2a-4bed-a34e-dfa7cb65062f" />

=== Cancellations (2015) ===

    % of cancellations due to Weather (code 'B'): 54.35%
    % of cancellations due to Airline/Carrier (code 'A'): 28.11%

<img width="865" height="461" alt="image" src="https://github.com/user-attachments/assets/c07229ad-6540-4fcf-a883-01f502b16a2a" />

=== Airline on-time departure performance (2015) ===

      total_flights  on_time_count  on_time_pct
    AIRLINE                                           
    AS              171852         128311        74.66
    HA               76101          55961        73.54
    OO              578393         407212        70.40
    EV              556746         387243        69.55
    US              194648         132196        67.92
    DL              872057         589672        67.62
    MQ              279607         186375        66.66
    AA              715065         469515        65.66
    VX               61369          38003        61.93
    F9               90248          55389        61.37
    B6              262772         160760        61.18
    NK              115375          63342        54.90
    WN             1245812         679229        54.52
    UA              509150         252909        49.67

<img width="996" height="555" alt="image" src="https://github.com/user-attachments/assets/91822a52-0a0a-4070-96f5-f43d38844c35" />

# Visualizations

    The analysis produced:
    
    Bar charts of flight volume by month & day of week
    
    Line plots of % delays across months
    
    Histograms of departure delays
    
    Bar charts of cancellation reasons
    
    Airline performance comparison plots

These visualizations make trends and problem areas easy to identify.


# Business & Passenger Impact

    Airlines: Can use insights to improve scheduling buffers, crew management, and weather preparedness.
    
    Airports: Can allocate resources (gates, staff) around seasonal surges.
    
    Passengers: Helps in planning — avoiding risky airports/seasons, selecting more reliable airlines.


# Project Learnings

    Handling large datasets with Pandas efficiently.
    
    Interpreting domain-specific codes (e.g., cancellation reasons).
    
    Turning EDA into actionable insights.
    
    Creating visual narratives that communicate findings clearly.


# Next Steps

    Future improvements could include:
    
    Machine Learning: Predicting delays using weather + schedule features.
    
    Network Analysis: Studying hub airports and their cascading effects on delays.
    
    Interactive Dashboards: Deploying results on Power BI / Tableau / Streamlit.

Use Cases in Portfolio

    This project demonstrates:
    
    Data wrangling & cleaning
    
    Exploratory analysis for insights
    
    Visualization for storytelling
    
    Domain knowledge application (aviation + delays)





