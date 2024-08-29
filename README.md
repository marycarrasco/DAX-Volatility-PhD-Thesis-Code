# PhD-Thesis-Python-codes

Overview
This repository contains code for the thesis titled "Empirical Analysis of Volatility Smiles in the German DAX Options Market: 2017-2022," part of a PhD in Big Data and Quantitative Finance. The analysis focuses on examining volatility smiles within the German DAX options market over the specified period, utilizing historical data to derive insights into volatility dynamics.

Repository Structure
data/: Directory containing historical data files.
scripts/: Directory containing Python scripts for data processing and visualization.
results/: Directory for output files such as Excel spreadsheets and generated plots.
Data
The data used for this analysis is historical data of the German DAX index from 2017 to 2022. The data is read from a CSV file located in the data/ directory.

Installation
To run the scripts in this repository, you will need to have the following Python libraries installed:

numpy
pandas
matplotlib
seaborn

You can install these libraries using pip:

bash
Copiar código
pip install numpy pandas matplotlib seaborn

Usage
Data Preparation: The script reads and preprocesses the historical data. It cleans and formats the data, and then saves it in Excel files for further analysis.

Data Processing: The script processes the data to compute "Cambio de precio débil" and "Cambio de precio abrupto," and saves the results in Excel files.

Visualization: The script contains a function Graf_Precio_Trim to generate visualizations of price changes over different trimesters. It plots data for each year and saves the plots as images.

Running the Scripts
To execute the scripts, ensure that the path to the CSV file in the _path variable is correct. Then, run the script using Python:

bash
Copiar código
python path/to/your/script.py
License
This repository is licensed under the MIT License. See the LICENSE file for more details.

Author
María Carrasco
PhD in Big Data and Quantitative Finance

Acknowledgments
Special thanks to Dr. Ana María Lara Bocanegra and Lucía Guerra for their guidance and support throughout the research process.

Feel free to adjust any details as needed!
