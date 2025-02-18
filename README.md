**Project Overview**

This repository contains data cleaning and exploratory data analysis (EDA) for a smartphone dataset. The dataset includes various smartphone specifications, such as brand, model, price, processor details, camera specifications, and battery capacity. The goal of this project is to preprocess the dataset, handle missing values, remove inconsistencies, and extract insights through EDA.

**Dataset Description**

- brand_name: The brand of the smartphone (e.g., OnePlus, Samsung, Apple).
- model: The specific model of the smartphone.
- price: The price of the smartphone (in INR or specified currency).

rating: The user rating of the smartphone.

has_5g: Boolean indicating whether the smartphone supports 5G.

has_nfc: Boolean indicating whether the smartphone supports NFC.

has_ir_blaster: Boolean indicating whether the smartphone has an IR blaster.

processor_brand: The brand of the processor (e.g., Snapdragon, MediaTek, Apple Bionic).

num_cores: The number of cores in the smartphone's processor.

processor_speed: The speed of the processor (in GHz).

battery_capacity: The battery capacity of the smartphone (in mAh).

fast_charging_available: Boolean indicating whether fast charging is supported.

fast_charging: Charging speed in watts (if applicable).

ram_capacity: RAM size of the smartphone (in GB).

internal_memory: Internal storage capacity (in GB).

screen_size: Screen size (in inches).

refresh_rate: Refresh rate of the display (in Hz).

resolution: Screen resolution.

num_rear_cameras: Number of rear cameras.

num_front_cameras: Number of front cameras.

os: Operating system (e.g., Android, iOS).

primary_camera_rear: Resolution of the primary rear camera (in MP).

primary_camera_front: Resolution of the primary front camera (in MP).

extended_memory_available: Boolean indicating whether external memory expansion is supported.

extended_upto: Maximum expandable storage capacity (in GB, if applicable).

🛠️ Data Cleaning Steps

The data cleaning process includes:

Handling missing values in numeric and categorical columns.

Removing duplicate entries.

Converting categorical columns to appropriate formats.

Handling inconsistent data (e.g., incorrect price formats, incorrect data types).

Normalizing text values for uniformity.

Dealing with outliers where necessary.

📊 Exploratory Data Analysis (EDA)

EDA aims to extract insights from the dataset through:

Summary statistics of numerical features.

Distribution plots of price, ratings, battery capacity, etc.

Correlation analysis between features.

Brand-wise comparison of price, RAM, and other features.

Feature importance analysis for predicting smartphone price.

Visualizations including histograms, scatter plots, and box plots.

📥 Dataset

Click here to access the dataset
