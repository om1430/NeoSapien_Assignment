# NeoSapien_Assignment

## Setup Instructions

1) Prerequisites:

   Python 3.8+ ( I used Google Colab) 

   Standard Python libraries:
   pandas, matplotlib.

2) Code with Analysis
   https://github.com/om1430/NeoSapien_Assignment/blob/main/NeoSapien_Assignment_Om_Chouhan.ipynb

## Approach

1) Data Processing:

   The log data was cleaned and preprocessed for analysis using pandas.
   Metrics were calculated using custom functions for accuracy and efficiency.
   
2) Visualizations:

   matplotlib was used to generate clear and intuitive plots for response times, error rates, and usage patterns.
   
3) Anomaly Detection:

   Simple statistical thresholds (e.g., standard deviation-based limits) were used to flag anomalies.


## Key Insights

1) Response Times:

   Endpoint /api/resource1 had the highest p95 response time.
   
   Periods of high latency were correlated with peak usage hours.
   
2) Error Patterns:

   Majority of errors were 500-series, indicating server-side issues.
   
   Error rates spiked between 3-5 PM, suggesting potential bottlenecks.
   
3) Peak Usage:

   Usage patterns suggest an increase in traffic during weekday afternoons.

## Future Improvements

Integrate advanced anomaly detection techniques using machine learning models or Deep learning Models like ANN, CNN LSTM etc.

Enhance visualizations using interactive tools like Plotly or Dash.


