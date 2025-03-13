# Hospitality Analysis Project

This project analyzes hospitality data to gain insights into booking trends, revenue generation, and hotel performance. The analysis is performed using Python and Pandas, leveraging several datasets to provide a comprehensive view of the hospitality business.

## Table of Contents

1.  [Introduction](#introduction)
2.  [Datasets](#datasets)
3.  [Data Import and Exploration](#data-import-and-exploration)
4.  [Dependencies](#dependencies)
5.  [Usage](#usage)

## Introduction

The goal of this project is to explore and analyze hospitality data to understand key performance indicators and trends. By examining booking information, hotel details, and room characteristics, this analysis aims to provide actionable insights for optimizing business strategies and improving customer satisfaction.

## Datasets

The project utilizes the following datasets, provided as CSV files:

*   `dim_date.csv`: Contains date-related information.
*   `dim_hotels.csv`: Includes details about the hotels, such as property ID, name, category, and city.
*   `dim_rooms.csv`: Contains information about the room types.
*   `fact_aggregated_bookings.csv`: Aggregated booking data.
*   `fact_bookings.csv`: Detailed booking information, including booking ID, property ID, dates, number of guests, room category, booking platform, ratings, booking status, and revenue.

## Data Import and Exploration

The analysis begins with importing the necessary libraries and loading the datasets into Pandas DataFrames. The structure and content of each DataFrame are then explored to understand the data types, missing values, and overall data quality.

### Example: Exploring Bookings Data

The `fact_bookings.csv` dataset is read into a DataFrame named `df_bookings`, and its structure is examined using `.head()`, `.describe()`, and `.info()` methods.

