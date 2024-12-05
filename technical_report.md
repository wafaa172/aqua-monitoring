Multi-Sensor IoT System for Monitoring Fish Farms
1. Introduction
Egypt is facing critical challenges such as climate change, water pollution, and the necessity to improve its scientific and technological environment. These challenges significantly impact aquaculture, contributing 79% of the country’s fish production. To address these challenges, our Capstone project focuses on designing a multi-sensor IoT system for monitoring water quality parameters—specifically turbidity, temperature, and pH—in fish farms to improve sustainability and mitigate the effects of climate change.

2. Design Requirements
The design requirements for the IoT system are as follows:

Real-time updates every 2 minutes.
Data storage for one year.
Battery life of 6 months on a single lithium battery.
Ability to send real-time alerts and provide analytics via a dashboard.
Turbidity levels should not exceed 10 NTU.
The temperature must remain between 25°C to 30°C.
pH levels should remain within a safe range to avoid heavy metal solubility and protect aquatic life.
3. System Design and Methodology
A. Sensors and Components
Temperature Sensor (DS18B20): Measures water temperature.
pH Sensor: Measures the pH level of the water.
Turbidity Sensor: Measures the clarity of the water, which is affected by pollutants.
Buzzer: Provides an alert if a parameter exceeds the threshold.
B. Energy Considerations
To meet the design requirements for energy efficiency, the system was configured to update every 2 minutes instead of every 30 seconds as initially planned. The reduced update frequency ensures lower power consumption, thus extending the battery life.

C. Data Transmission
The system collects data at 2-minute intervals and transmits it to ThingSpeak for analysis and visualization. This ensures continuous monitoring while also optimizing battery usage. Alerts are generated when parameters exceed set thresholds, and data is stored for up to one year for later analysis.

4. Calculations
A. Energy Calculations (Updated)
Power Consumption: The system uses 0.405A as previously calculated.
With data transmission occurring every 2 minutes (instead of 30 seconds), the power consumption for data transmission is reduced by a factor of four.
This adjustment will increase the system’s battery life by approximately four times compared to the 30-second update frequency, making it feasible for continuous operation for 6 months on a single lithium battery.

B. Data Storage and Real-time Monitoring
Data is transmitted and stored on ThingSpeak at 2-minute intervals, ensuring real-time monitoring and historical data collection. The system meets the design requirements of storing data for one year and providing real-time feedback via alerts and a dashboard.

5. Solution Justification
The system was selected for its ability to integrate advanced sensors and provide real-time data updates while addressing the challenges of energy consumption, data reliability, and long-term battery life. The integration of these sensors ensures accurate monitoring of key water quality parameters, which are critical for sustainable fish farming.

6. Conclusion
The designed multi-sensor IoT system offers a sustainable solution to the challenges facing Egypt’s aquaculture industry. By monitoring turbidity, temperature, and pH levels, the system helps ensure optimal conditions for fish farming while mitigating the impacts of climate change and water pollution. The solution aligns with Egypt’s Grand Challenges and meets the identified design requirements, offering a reliable, energy-efficient, and cost-effective system for real-time monitoring and data visualization.
