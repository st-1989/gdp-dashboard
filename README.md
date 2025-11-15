# :earth_americas: GDP dashboard

A Streamlit web application for visualizing and comparing GDP (Gross Domestic Product) data from different countries around the world.

[![Open in Streamlit](https://static.streamlit.io/badges/streamlit_badge_black_white.svg)](https://gdp-dashboard-template.streamlit.app/)

## Features

- **Interactive Time Range Selection**: Choose any time period between 1960 and 2022 using a dual slider
- **Multi-Country Comparison**: Select and compare GDP data for multiple countries simultaneously
- **Dynamic Visualization**: View GDP trends over time with interactive Plotly charts
- **Logarithmic Scale Option**: Toggle between linear and logarithmic scale for better comparison of countries with vastly different GDP values
- **GDP Metrics**: View current GDP values and growth multipliers for selected countries

## Data Source

This application uses GDP data from the [World Bank Open Data](https://data.worldbank.org/) website. The dataset currently covers years 1960-2022, though some datapoints for certain years may be missing.

## How to run it on your own machine

1. Install the requirements

   ```bash
   pip install -r requirements.txt
   ```

2. Run the app

   ```bash
   streamlit run streamlit_app.py
   ```

3. Open your browser and navigate to `http://localhost:8501`

## Technologies Used

- **Streamlit**: Web application framework
- **Pandas**: Data manipulation and analysis
- **Plotly**: Interactive data visualization
