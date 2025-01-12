# Economic Data Analysis with Pandas

This project uses the Federal Reserve Economic Data (FRED) API to analyze economic indicators, particularly focusing on unemployment rates and labor force participation rates across different states in the USA.

## Prerequisites

Before running this project, you need to have the following libraries installed:

- pandas
- numpy
- matplotlib
- plotly
- fredapi

You also need to have a FRED API key. You can obtain one by registering at https://fred.stlouisfed.org/docs/api/api_key.html

## Project Structure

The project consists of several main parts:

1. **S&P 500 Analysis**: Retrieves and plots S&P 500 data.
2. **Unemployment Rate Analysis**: 
   - Fetches unemployment rate data for all states
   - Creates visualizations including a line plot of all states and a bar chart of unemployment rates
3. **Labor Force Participation Rate Analysis**: 
   - Retrieves labor force participation rate data for all states
4. **Combined Analysis**: 
   - Creates a multi-panel plot comparing unemployment and participation rates for each state
   - Provides a detailed view for a specific state (California in this example)

## Key Visualizations

1. S&P 500 trend over time
2. Unemployment rates across all states (line plot)
3. Unemployment rates by state for May 2020 (bar chart)
4. Multi-panel plot of unemployment vs participation rates for each state
5. Detailed unemployment vs participation rate plot for California

## Usage

1. Set your FRED API key in the `fred_key` variable.
2. Run the script to generate all visualizations.
3. Modify the `state` variable in the last section to analyze a different state.

## Notes

- The script includes time delays between API calls to avoid hitting rate limits.
- Some data cleaning is performed to handle inconsistencies in state names and to remove unnecessary columns.
- The project uses the 'fivethirtyeight' style for matplotlib plots.

## Future Improvements

- Add more economic indicators for a more comprehensive analysis
- Implement interactive visualizations for easier data exploration
- Include statistical analysis of the relationships between different economic indicators