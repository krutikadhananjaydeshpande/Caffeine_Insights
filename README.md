# Procaffeinator

## Overview
Procaffeinator is a data analysis project that helps you understand the relationship between your coffee intake and various productivity metrics. By logging daily data about your coffee consumption, energy levels, focus, mood, sleep quality, and productivity, you can gain insights into your optimal coffee consumption for maximum productivity.

## Features
- Daily data logging of coffee consumption and productivity metrics
- Data visualization including correlation heatmaps, scatter plots, and time series analysis
- Calculation of optimal coffee consumption for maximum productivity
- Easy-to-use Python scripts for data collection and analysis

## Requirements
- Python 3.7+
- pandas
- matplotlib
- seaborn

## Installation
1. Clone this repository:
git clone https://github.com/yourusername/procaffeinator.git
cd procaffeinator

2. Install the required packages:
   pip install -r requirements.txt

## Usage

### Data Collection
Run the data collection script daily to log your coffee consumption and productivity metrics:
python data_collection.py

Follow the prompts to enter your daily data.

### Data Analysis
After collecting data for a period (ideally at least a month), run the analysis script:
python data_analysis.py

This will generate several visualizations and output key insights about your coffee consumption and productivity.

## File Structure
- `data_collection.py`: Script for daily data logging
- `data_analysis.py`: Script for analyzing collected data
- `coffee_data.csv`: CSV file storing all collected data
- `requirements.txt`: List of Python package dependencies

## Visualizations
The analysis script generates several visualizations:
1. Correlation Heatmap (`correlation_heatmap.png`)
2. Coffee Consumption vs. Productivity Scatter Plot (`coffee_vs_productivity.png`)
3. Time Series of Coffee Consumption and Productivity (`time_series.png`)
4. Average Productivity vs. Coffee Consumption Bar Chart (`avg_productivity_vs_coffee.png`)

## Contributing
Contributions to improve Procaffeinator are welcome. Please feel free to submit a Pull Request.


## Contact
For any questions or feedback, please open an issue on this GitHub repository.

Happy tracking and may your coffee always lead to productivity! ☕📈
   
