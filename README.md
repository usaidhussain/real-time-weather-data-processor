# Real-Time Weather Monitoring System

## Objective

This system monitors real-time weather data from the OpenWeatherMap API at configurable intervals for several Indian metros. It processes the data to provide daily summaries, such as average, maximum, and minimum temperatures, along with the dominant weather condition. The system also features an alerting mechanism based on configurable thresholds for specific weather conditions, like exceeding temperature limits.

## Features

- **Real-Time Data Retrieval**: Periodic data fetching from OpenWeatherMap API for multiple locations.
- **Data Processing**:
  - Temperature conversion from Kelvin to Celsius.
  - Daily weather summaries including:
    - Average Temperature
    - Maximum Temperature
    - Minimum Temperature
    - Dominant Weather Condition
- **Alerting System**: Configurable thresholds that trigger alerts if specific weather conditions are met.
- **Optional Visualization**: Historical trends and daily summaries can be visualized.

## Technologies Used

- **Python**: For data processing and API interaction.
- **MySQL**: Used for storing weather summaries and alert configurations.
- **Flask**: (Optional) Web API for managing and displaying data.
- **Matplotlib/Plotly**: (Optional) Visualization libraries for historical weather data.

## Setup Instructions

### Step 1: Install Required Dependencies

Create a `requirements.txt` file with the following dependencies:

```txt
Flask==2.0.1
Flask-MySQLdb==0.2.0
PyMySQL==1.0.2
SQLAlchemy==1.4.22
requests==2.25.1
matplotlib==3.4.3
plotly==5.3.1
