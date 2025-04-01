# Airbnb_data_analysis_EDA
Overview

This project performs an exploratory data analysis (EDA) on an Airbnb dataset to uncover patterns, trends, and insights. The analysis includes data visualization, statistical insights, and geographic mappings to better understand Airbnb listings, room types, pricing, and distribution across various locations.

# Dataset

The dataset consists of 48,895 rows and 16 columns, containing information about Airbnb listings, including:
> Listing ID
> Host ID & Name
> Neighbourhood & Neighbourhood Group
> Latitude & Longitude (for mapping)
> Room Type
> Price & Availability
> Number of Reviews & Reviews per Month

# Objectives

> Determine the structure and unique values in the dataset.
> Handle missing values.
> Visualize neighbourhood distributions using maps and scatter plots.
> Analyze room type distributions.
> Identify the top Airbnb listings based on reviews and availability.

# Exploratory Data Analysis (EDA) Steps

# 1. Data Cleaning

> Identified and replaced missing values in the reviews_per_month column with 0.
> Checked for duplicates and inconsistencies in listing information.

# 2. Data Visualization

> Geospatial Visualization: Used the Folium library to create an interactive map displaying Airbnb locations.
> Scatter Plots: Plotted neighbourhood groups using latitude and longitude to identify clustering.
> Room Type Distribution: Analyzed the popularity of different room types.

# 3. Unique Value Analysis
> Identified three types of rooms: Entire home/apartment, Private room, Shared room.
> Found five different neighbourhood groups.

# 4. Top Listings Analysis
> Examined the top 10 Airbnb listings.
> Found anomalies, such as Sonder (NYC) having an unusually high listing count.

# Technologies Used
> Python
> Pandas & NumPy (Data Manipulation)
> Matplotlib & Seaborn (Data Visualization)
> Folium (Geospatial Mapping)
> Jupyter Notebook (Interactive Analysis) 

# How to Run the Project

1) Clone the repository: https://github.com/yashverma8290/Airbnb_data_analysis_EDA.git
2) Navigate to the project directory: cd Airbnb-EDA
3) Install dependencies: pip install -r requirements.txt
4) Open Jupyter Notebook: jupyter notebook
5) Run the Airbnb_data_analysis_EDA.ipynb notebook to execute the analysis.

# Key Insights
> Most Airbnb listings are entire apartments or private rooms.
> Certain neighbourhood groups have significantly higher Airbnb listings.
> High review counts and availability do not always correlate with pricing.

# Contributing
Contributions are welcome! If you find any issues or improvements, feel free to fork the repository and submit a pull request.



