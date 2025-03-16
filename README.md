# Zomato Power BI Dashboard Development

## Introduction

### About the Project
This project aims to develop a comprehensive Power BI dashboard for Zomato, providing valuable insights into restaurant performance, customer feedback, pricing trends, and cuisine diversity. By leveraging Power BI’s data visualization capabilities, the dashboard will facilitate informed decision-making for stakeholders.

### About Zomato
Zomato is a globally recognized online platform that connects users with restaurants by providing restaurant listings, reviews, ratings, menus, and food delivery services. Established in 2008, Zomato operates in multiple countries, offering insights into dining trends, customer preferences, and restaurant operations. This dashboard will enhance the analysis of restaurant data, helping businesses optimize their services and improve customer satisfaction.

## Objectives
- Develop an interactive dashboard that visualizes key Zomato business metrics.
- Provide insights into restaurant locations, average ratings, order patterns, and cuisine diversity.
- Facilitate data-driven decision-making through structured reporting.

## Data Collection

### Datasets Required
- **Restaurant Details**: Name, location, ratings, services offered.
- **Menu Items & Pricing**: Dishes, prices, and availability.
- **Order History & Types**: Online orders, dine-in, takeaway data.
- **Customer Information & Reviews**: User ratings and feedback.
- **Cuisine Types**: Classification of restaurants by cuisine.

### Data Sources
- Zomato public datasets.
- Manually curated Excel files (e.g., ‘menu.xlsx,’ ‘orders.xlsx,’ ‘restaurant.xlsx’).

## Data Preparation

### Cleaning
- Remove inconsistencies and duplicate entries.
- Standardize city names (e.g., correcting "Sí£o Paulo" to "São Paulo").

### Transformation
- Create new columns for restaurant names and addresses.
- Normalize the data by creating separate tables for cuisines and services.
- Establish relationships between tables for optimized querying.

## Key Metrics & Visualizations
- **Total Restaurants**: Number of restaurants categorized by country, city, and area.
- **Average Ratings**: Identify highest and lowest-rated restaurants.
- **Average Cost**: Compare pricing trends across different restaurants.
- **Cuisine Variety**: List restaurants offering the most diverse cuisines.
- **Order Patterns**: Analyze trends in online orders and dine-in services.

## Dashboard Features

### Filters
- Geographic filters (country, city, area).
- Rating-based categorization.
- Cuisine type selection.
- Service availability (online ordering, reservations).

### Interactivity
- Drill-down options for a detailed view of specific restaurants and trends.

### Map Integration
- Visualization of restaurant distribution across different regions.

### Custom Design
- Align dashboard aesthetics with Zomato’s branding guidelines.

## Technical Implementation

### Data Integration
- Import multiple datasets into Power BI.

### Dashboard Layout
- **Page 1**: Overview of restaurant data.
- **Page 2**: Customer reviews and ratings analysis.
- **Page 3**: Cuisine trends and order analysis.
- **Page 4**: Cost analysis and affordability insights.

## Getting Started

### Prerequisites
- Power BI Desktop installed on your machine.
- Access to Zomato public datasets and curated Excel files.

### Installation
1. Clone the repository to your local machine.
2. Open the `.pbix` file in Power BI Desktop.
3. Load the necessary datasets into Power BI.
4. Follow the data transformation and cleaning steps as described in the Data Preparation section.

### Usage
Once the dashboard is loaded into Power BI, you can:
- Explore interactive visualizations using filters and drill-down features.
- Analyze restaurant performance, customer feedback, and pricing trends.
- Customize the dashboard layout as per your needs.

## Contributing
Feel free to fork the repository, make changes, and submit pull requests. Please ensure that your contributions align with the project objectives and maintain a consistent coding style.

