# Financial-Asset-Analysis
📊This program analyzes a financial asset using Python and various data visualization libraries. It reads a CSV file containing financial data, performs analysis, and generates interactive plots and visualizations.

## Prerequisites

- Python 3.x
- Required libraries: `csv`, `json`, `sys`, `bokeh`, `pandas`, `matplotlib`, `seaborn`

## Installation

1. Clone the repository:


`git clone https://github.com/your-username/repository-name.git`

### 2.  Install the required libraries:

bashCopy code

`pip install -r requirements.txt` 

## Usage

### 1.  Provide the CSV file path:

`csvFilePath = r'path/to/your/data.csv'` 

### 2.  Run the program:

`python main.py` 

## Features

### CSV to JSON Conversion

The program reads a CSV file and converts it into a JSON format for further analysis. It preprocesses the data by removing the last 10 rows and filtering out rows with missing profit values.

`csv_to_json(csvFilePath)` 

### Balance Calculation

The program calculates the balance based on the profit column of the data. It generates a balance dataframe that represents the cumulative sum of profits.

`balance = calcule_balance(df, 'Profit')` 

### Multiple Figures Plotting

The program generates multiple figures using the `matplotlib` library. It plots the balance over time, profit vs. drawdown, and profit vs. drawdown vs. balance.

`plot_multiple_figures()` 

### Pie Chart Plotting

The program generates a pie chart to visualize the distribution of symbols in the dataset.

`plot_cercle()` 

### Heatmap Generation

The program generates a heatmap to analyze the profit distribution based on the day of the week and hour of the day.

`mapa_de_calor()` 

## Contributing

Contributions are welcome! If you find any issues or have suggestions for improvements, please open an issue or submit a pull request.

## License

This project is licensed under the MIT License

 ``Please note that this documentation assumes the program is organized as a Python package with a `main.py` file and a `requirements.txt` file for dependency installation. You may need to modify the instructions based on your specific project structure.``
