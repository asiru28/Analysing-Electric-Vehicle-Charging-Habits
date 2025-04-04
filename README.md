# Analysing-Electric-Vehicle-Charging-Habits

# Overview

As electric vehicles (EVs) continue to rise in popularity, the demand for accessible and reliable charging infrastructure in residential settings has become critical. This project examines EV charging behaviour in apartment buildings, focusing on usage patterns, peak times, and the availability of shared versus private charging stations. The aim is to support property managers in making informed decisions around EV charging station planning and management.

# Objectives

- Analyse EV charging habits across multiple apartment complexes.
- Compare usage between shared and private charging stations.
- Identify peak charging times and days of the week.
- Provide recommendations to improve access and reduce charging station congestion.

# Data Source

The dataset is publicly available under a CC BY 4.0 licence via Kaggle.
It is stored in a PostgreSQL database under the table charging_sessions, with key fields including:
- garage_id, user_id, user_type (Shared or Private)
- start_plugin, end_plugout, duration_hours, el_kwh
- start_plugin_hour, end_plugout_hour, month_plugin, weekdays_plugin

# Tools Used

- DataLab – for data analysis and visualisation within an interactive notebook environment
- PostgreSQL – for structured data storage and querying

# Insights

- Shared charging stations are often in high demand, especially during evenings and weekends.
- Usage varies significantly by building and user type.
- Many users charge during off-peak hours, suggesting flexibility in charging behaviour.
- Electricity consumption (kWh) generally correlates with longer session durations.

# Key Findings

- Evening hours (after 17:00) are the most popular for charging sessions, particularly in shared stations.
- Sunday and Friday show high charging activity, indicating weekend travel patterns.
- Shared stations experience more congestion compared to private ones, often leading to availability issues.
- Certain garages (e.g., AdO3, Bl2) consistently report higher demand, suggesting the need for expansion.

# Recommendations

- Increase the number of shared charging ports in high-demand garages to reduce user frustration.
- Introduce booking systems or usage limits during peak hours to ensure fair access.
- Encourage off-peak charging through incentives or pricing strategies to balance load.
- Monitor charging habits regularly to adapt infrastructure planning as EV adoption grows.
