This repository contains the final project for the **Systems and Methods for Big and Unstructured Data (SMBUD)** course. The project focuses on the implementation and analysis of a large-scale NoSQL database using real-world real estate data.


👥 Authors
Eric Piotti
Lucrezia Maestrello 

Academic Year: 2024-2025 

## 📝 Project Overview
The objective of this project was to select a modern database technology and perform complex analytical queries on a dataset containing at least 20,000 data points. We chose MongoDB due to its suitability for handling large data volumes and its compatibility with the document-based format of real estate listings.

The analysis involves a comprehensive snapshot of the Houston housing market as of June 5, 2024.

## 📊 Dataset: Houston Housing Market 2024
The dataset provides a detailed view of the Houston, Texas real estate landscape.

Source: Natasha Lekh, collected via Zillow APIs.

Volume: Approximately 27,000 documents.

Structure: Documents include fields for unique identifiers (zpid), pricing, structural details (beds, baths, area), geographical coordinates, and broker information.

License: CC BY-NC-SA 4.0.

## 🔍 Analytical Queries
The project implements 20 sophisticated queries  designed to simulate standard and interesting real estate market analyses. These include:

Market Trends: Calculating the average price of properties per Zip code and identifying the 10 real estate agents with the most listings.

Geospatial Analysis: Finding homes within 5 miles of downtown Houston using coordinate-based calculations .

Economic Insights: Identifying "luxury homes" (priced > $1,000,000) and calculating their average price by property type.

Data Accuracy: Comparing the listed price against the Zillow "Zestimate" to find the properties with the smallest price difference.

Specific Filters: Finding listings with price reductions of at least 25% from their original value and homes where the estimated rent exceeds 10% of the property value.

## 🛠️ Implementation Details
Database: MongoDB.

Analyses: Performed using MongoDBAtlas

​
