# Overview:
This project focuses on cleaning and transforming raw hotel booking data using Python and Pandas. The dataset contains information about guest names, company affiliations, room numbers, and booking dates. The primary goal was to handle missing values and reorganize the data for better reporting.

# Project's Objective:
The objective is to take a "dirty" dataset (containing headers mixed within rows and missing values) and:
1. Clean the dataset by removing null entries.
2. Perform feature engineering by creating calculated columns.
3. Backfill categorical data (Booking Sources) to associate every guest with their respective booking platform (Expedia, Hotels.com, etc.).
4. Visualize the volume of bookings per platform.

# Project based questions:
1. How many bookings were made by each company?
2. How can we simplify the room data for specific calculations?
3. How many records remain after removing incomplete entries?


# Project based questions - Advanced:
1. How do you isolate specific booking sources from a messy 'Date' column?
2. Which platform is the dominant booking source?
