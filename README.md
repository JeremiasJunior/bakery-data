# bakery-data

## Overview

This project's primary goal is to gather public data from the Brazilian government's IRS, store the data in a Microsoft SQL Server using Amazon RDS, query the data from bakeries in the state of sao paulo using the facilities database, use API calls to gather geolocation data based on zip codes, and visualize the data with Tableau.

## Project Description

The project is designed to automate the process of collecting and managing data from the Brazilian government's IRS. It encompasses several key components:

## Data Gathering

The data gathering process involves downloading and extracting data from the Brazilian IRS. This project includes code to automate this process. It checks for new data, downloads it, and extracts it into designated directories. The gathered data includes information about establishments, companies, partners, tax details, and more.

## Database Setup

This project also includes scripts for setting up the necessary database tables and importing the collected data into the database. You should customize the database settings in the scripts before executing them.

To set up the database, run the following scripts:

1. **Create Tables:** This script creates the required tables in the database to store the gathered data.

2. **Import Data:** Another script is responsible for importing data from the extracted files into the database tables.

## Geolocation Data

One feature of this project is using API calls to gather geolocation data based on zip codes. The data is fetched and stored in the database, enhancing the dataset with geographical information.

## Data Visualization

To visualize the collected data, the project is integrated with Tableau. You can use Tableau to create insightful visualizations and reports based on the gathered data.
