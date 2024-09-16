-About Dataset
Various details about cell phones listed on Amazon, such as product name, price, rating, number of ratings, and technical specifications like RAM, storage, screen size, and more.

-Dataset Overview
This dataset contains detailed information about cellphones listed on Amazon, scraped using Selenium and BeautifulSoup. It includes product details such as the name, price, ratings, specifications (RAM, storage, screen size, etc.), and additional metadata like the number of ratings and discount percentage. The dataset was designed to provide insights into cellphone features, pricing trends, and customer feedback on one of the world's largest e-commerce platforms.

-Source
The data was scraped from Amazon's cellphone category pages over multiple pages (up to 250 pages). Given Amazon's structure, the dataset includes a wide variety of cellphone brands and models, including older and newer releases.

-Data Fields
ID: Unique identifier for each product.
Product Name: The name of the cellphone.
Product Link: URL link to the Amazon product page.
Image Link: URL link to the product image on Amazon.
Price (Dollar): The price of the cellphone in USD.
Discount Percentage: Discount percentage, if applicable, calculated as the difference between the original price and the current price.
Price Before Discount: Original price of the cellphone, if available.
Rating (out of 5): Customer rating, extracted from the product page.
Number of Ratings: The total number of customer ratings for the product.
Brand: Brand of the cellphone.
Operating System: The operating system of the cellphone (e.g., Android, iOS).
RAM (GB): Amount of RAM in GB.
Storage (GB): Internal storage capacity in GB.
Screen Size (Inches): Screen size in inches.
Cellular Technology: Cellular technology (e.g., 4G, 5G).
**CPU **: CPU Speed.
CPU Model: CPU model used in the cellphone.
Available Colors: Available colors for the cellphone model.
Potential Uses
Product Comparison: This dataset can be used to compare various cellphone brands and models based on price, RAM, storage, and other features.
Trend Analysis: Analyze price trends, discount patterns, and customer preferences based on ratings and reviews.
Machine Learning: Build machine learning models to predict price trends, ratings, or sales volume.
Exploratory Data Analysis (EDA): Perform EDA to discover patterns, outliers, and insights into the cellphone market.

-Data Cleaning
The dataset has been cleaned to remove duplicates and standardize data entries. Missing values were handled where possible, and units of measurement (e.g., RAM, storage) have been converted for consistency.

-Limitations
Dynamic Content: Prices, ratings, and availability may change on Amazon over time, meaning this dataset represents a snapshot of the listings at the time of scraping.

