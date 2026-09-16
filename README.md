# EV Charging Station Demand, Cost and Customer Behavior Analysis Using Python

Analysis of 8,354 electric vehicle charging sessions to understand demand patterns, energy consumption, and cost drivers — and to recommend how station operators should plan capacity.

Tools: Python · Pandas · NumPy · Matplotlib · Seaborn

# Business questions
How does charging demand vary across the hours of the day, and when does it peak?
Does demand behave differently on weekdays and weekends?
Which vehicle types and which stations account for the most demand?
What drives the cost of a charging session?
What causes customers to wait, and how long do they wait?

# Key Findings
1 Cars have the highest number of charging sessions with 2,833 sessions, followed by Two-Wheelers (2,761) and Buses (2,760).

2 Buses have the highest average energy consumption at 39.45 kWh, while Two-Wheelers have the lowest at 38.71 kWh.

3 Buses have the highest average charging cost at 396.70, showing that their charging sessions are slightly more expensive on average.

4 Two-Wheelers have the highest average charging demand at 54.54, making them the highest-demand vehicle type in the dataset.

5 Bus users have the highest average waiting time at 9.61 minutes, while Two-Wheeler users have the lowest at 9.43 minutes.

6 Time of day has the strongest observed pattern in charging demand. Demand is highest around 5:00 PM and lowest around 2:00 AM. This shows that charging demand changes more with time than with vehicle type, weather, or day type.

7 Weather conditions and day of the week show relatively small differences in charging-session volume in this dataset.

# Recommendations
1 Plan staff and charging capacity by time
Increase staff and charging capacity during busy hours, especially 7:00–11:00 AM and 5:00–9:00 PM.
Based on: Time-of-day demand analysis.

2 Offer off-peak discounts
Provide lower prices during 11:00 AM–4:00 PM and overnight to encourage charging during less busy periods.
Based on: Peak and off-peak demand analysis.

3 Investigate waiting time
Investigate station-level operational factors such as charger allocation, charging duration, and station utilization to understand the additional factors contributing to customer waiting time.
Based on: Queue length and waiting time analysis.

4 Encourage shorter charging during peak hours
Encourage efficient charging during peak hours by promoting shorter charging sessions where operationally appropriate.
Based on: SOC and charging-duration analysis.

5 Review investment and priority planning
Focus mainly on time-based demand rather than weather or vehicle type. Also, check whether the charging priority system is working effectively.
Based on: Station, vehicle type, weather, and priority analysis.

# Dataset
Source:[Kaggle](https://www.kaggle.com/datasets/ziya07/electric-vehicle-charging-demand-dataset?)

Records: 8,354 charging sessions

Key fields: vehicle type, energy consumed (kWh), charging cost, waiting time, charging duration, station ID, weather conditions, timestamp
