# Customer-Data-Preprocessing-and-Analysis

## Project Description

This project involves preprocessing customer data, including credit card details, by loading JSON files, correcting errors, handling missing values, and encoding features. It also includes visualizations like salary vs. age plots to uncover trends, preparing the data for analysis or predictive modeling.

## Required Libraries

This project requires the following Python libraries:

- `csv`: For handling CSV file operations.
- `json`: For reading and parsing JSON files.
- `pandas`: For data manipulation and analysis.
- `seaborn`: For data visualization.
- `math`: For mathematical operations.
- `matplotlib`: For generating visual plots.

You can install these libraries by running the following command:

```bash
pip install pandas seaborn matplotlib

## How to Run the Notebook

### Option 1: Run Locally with Jupyter Notebook

To run the notebook locally, follow these steps:

1. Ensure you have Jupyter Notebook installed. You can install it via pip if needed:
   ```bash
   pip install notebook

2. Install the required libraries:

bash
pip install pandas seaborn matplotlib

3. Download the notebook and dataset to your local machine.

4. Open a terminal or command prompt and run:

bash
   jupyter notebook
5. In the browser window that opens, navigate to the customer_data_preprocessing.ipynb file and open it.

6. Run the cells in the notebook to start the analysis.

### Option 2: Run on Google Colab

You can also run this notebook on Google Colab without needing to install anything locally.

1. Open the notebook in Google Colab by clicking the link below:

   **Open in Google Colab**

2. Upload the dataset (if prompted) to Colab.

3. Run each cell in the notebook to start the analysis.

### Project Structure

- `customer_data_preprocessing.ipynb`: Jupyter notebook containing the preprocessing and analysis code.
- `dataset/`: Folder containing the customer data (JSON or CSV files).
- `plots/`: Folder containing the visualizations generated during analysis.

### Data Processing Overview

The project involves the following preprocessing steps:

- Loading JSON files with customer data.
- Cleaning the data by correcting errors and handling missing values.
- Encoding categorical features for analysis.
- Visualizing trends, such as salary vs. age, using plots.
