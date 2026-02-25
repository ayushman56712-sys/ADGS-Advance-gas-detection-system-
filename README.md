# ADGS-Advance-gas-detection-system-
This project is to tackle the hazardous gas detection , live tracking  and alerting system
IoT-Based Gas Leakage Monitoring System with Real-Time Dashboard

This project presents a smart IoT-based Gas Leakage Monitoring System developed using ESP32, gas sensors, GSM, GPS, and a Streamlit dashboard. It was created as a final-year engineering project at Centurion University of Technology and Management (CUTM), Bhubaneswar, to improve safety by detecting gas leaks and providing real-time alerts and visualization.

Project Overview

Gas leakage can cause serious accidents in homes and industries. This system continuously monitors gas concentration and logs the data. The recorded data is displayed on a professional web dashboard built with Streamlit, allowing users to monitor gas levels, alert status, and location in real time.

The dashboard automatically refreshes and provides safety warnings when gas levels exceed safe limits.

Key Features

-Real-time gas level monitoring (PPM)

-Automatic safety alerts and warning messages

-Live dashboard with Streamlit

-GPS location visualization on map

-Historical trend graph of gas levels

-Excel-based data logging system

-Auto-refreshing interface

-One-click executable launcher support

Technologies Used

Hardware:

-ESP32 Microcontroller

-MQ-Series Gas Sensor

-GSM Module

-GPS Module

Software:

-Python

-Streamlit

-Pandas

-Anaconda

-Excel

-Dashboard Functions

-The dashboard displays:

-Current gas level

-Alert status (Safe / Danger)

-Last update time

-Gas level trend graph

-Location map 

-Complete log data

If gas exceeds the safety threshold, the system shows a danger alert with safety instructions.

 How to Run
--streamlit run gas_dashboard.py

Then open:
--http://localhost:8501

Or run the provided EXE launcher.

Academic Information

Project Title: IoT-Based Gas Leakage Monitoring System
University: CUTM Bhubaneswar
Course: B.Tech Final Year Project

Future Improvements

Future enhancements may include cloud storage, mobile app integration, and SMS or email alerts.
