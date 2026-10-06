# Predicting the Virtual Market: Developing an Analysis System for the Counter-Strike 2 Game

An end-to-end data engineering and predictive analytics platform designed to monitor, process, and forecast virtual item prices in the Counter-Strike 2 market.

Key Features:
- **RPA Automation (UiPath):** Automated data scraping and extraction from marketplace platforms.
- **Real-Time ETL & Storage:** File system monitoring via `watchdog` to automatically sync Excel data into a SQLite database.
- **Interactive Dashboard (Python Dash):** A responsive web interface featuring real-time charts, data tables, and a custom "Case Opening Simulator".
- **Machine Learning (Prophet & XGBoost):** Advanced time-series forecasting and pattern recognition for price prediction.
- **Performance Optimization:** Integrated caching (`Flask-Caching`) and client-side state management (`dcc.Store`).
