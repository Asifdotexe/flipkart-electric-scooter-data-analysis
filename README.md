# Electric Scooter Listings Analysis

Welcome to the "Electric Scooter Listings Analysis" project repository! In this project, we analyze electric scooter listings data to gain insights into pricing trends, perform data cleaning and transformation, and conduct exploratory data analysis (EDA). The project is organized into three Jupyter Notebook files:

## 1. [Electric Scooter Price Web Scraping from FlipKart](Electric%20Scooter%20Price%20Web%20Scraping%20from%20FlipKart.ipynb)

In this notebook, we utilize web scraping techniques to extract electric scooter price data from FlipKart using Python libraries such as BeautifulSoup, pandas, requests, and csv. The gathered data serves as the foundation for our analysis, providing information on various scooter models and their respective prices.

## 2. [Electric Scooter Data Cleaning and Transformation](Electric%20Scooter%20Data%20Cleaning%20and%20Transformation.ipynb)

This notebook focuses on the crucial steps of data cleaning and transformation. Leveraging the power of numpy and pandas, we address missing values, handle outliers, and structure the data for meaningful insights. The clean dataset becomes the basis for our subsequent exploratory data analysis.

## 3. [Electric Scooter Exploratory Data Analysis](Electric%20Scooter%20Exploratory%20Data%20Analysis.ipynb)

In this notebook, we delve into the world of exploratory data analysis using pandas, matplotlib, and seaborn. Through statistical analysis and visualizations, we uncover patterns, trends, and relationships within the electric scooter data. This step enhances our understanding of the market and assists in making informed decisions.

# Setting Up the Virtual Environment

To ensure a smooth execution of the Electric Scooter Listings Analysis project, it's recommended to set up a virtual environment. This helps manage dependencies and ensures that the project runs with the specified library versions. Follow the steps below to create and activate the virtual environment:

1. **Create Virtual Environment:**
   Open a terminal or command prompt and navigate to the project directory. Run the following command to create a virtual environment named "venv" (you can replace "venv" with your preferred name):

   ```bash
   python -m venv venv
   ```

2. **Activate Virtual Environment:**
   Activate the virtual environment based on your operating system:

   - **For Windows:**
     ```bash
     .\venv\Scripts\activate
     ```

   - **For MacOS/Linux:**
     ```bash
     source venv/bin/activate
     ```

3. **Install Dependencies:**
   Once the virtual environment is activated, install the required dependencies using the following command:

   ```bash
   pip install -r requirements.txt
   ```

   This will install the necessary packages like BeautifulSoup, Pandas, Requests, Numpy, Matplotlib, and Seaborn.

Now you have a virtual environment set up with the required dependencies, ensuring a clean and isolated environment for running the Electric Scooter Listings Analysis project.