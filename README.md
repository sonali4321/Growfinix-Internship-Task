# Growfinix
Data Analyst Internship

# 🏠 Interactive Real Estate Pricing Dashboard

## 📌 Project Overview

This project focuses on analyzing real estate property data and building an interactive dashboard to help stakeholders understand property pricing trends.

The dashboard allows users to analyze average property prices based on:

- Neighborhood
- Square Footage
- Property Type
- Number of Bedrooms
- Number of Bathrooms
- Proximity to Schools
- Property Location

The project integrates a SQL database with Microsoft Power BI to transform raw real estate data into meaningful business insights and interactive visualizations.

---

## 🎯 Project Objective

The main objective of this project is to:

- Connect a Business Intelligence tool directly to a SQL database.
- Analyze property listings and sales data.
- Identify average property prices by neighborhood.
- Understand the relationship between square footage and property prices.
- Analyze the impact of school proximity on property values.
- Create interactive visualizations and filters for stakeholders.
- Build a map-based dashboard for geographical property analysis.

---

## 🛠️ Tech Stack

| Technology | Purpose |
|---|---|
| MySQL | Database management |
| SQL | Data querying and analysis |
| Microsoft Power BI | Dashboard and visualization |
| DAX | KPI calculations |
| Excel/CSV | Dataset storage and preparation |

---

## 📂 Dataset Description

The project uses multiple datasets to analyze the real estate business.

### Properties

| Column | Description |
|---|---|
| property_id | Unique Property ID |
| property_name | Property Name |
| neighborhood | Property Location/Area |
| property_type | Apartment, Villa, House, etc. |
| price | Property Price |
| square_feet | Property Area |
| bedrooms | Number of Bedrooms |
| bathrooms | Number of Bathrooms |
| school_id | Nearby School ID |
| latitude | Property Latitude |
| longitude | Property Longitude |

---

### Customers

| Column | Description |
|---|---|
| customer_id | Unique Customer ID |
| customer_name | Customer Name |
| property_id | Related Property ID |
| contact | Customer Contact Information |

---

### Agents

| Column | Description |
|---|---|
| agent_id | Unique Agent ID |
| agent_name | Agent Name |
| experience | Years of Experience |
| commission | Agent Commission |

---

### Sales

| Column | Description |
|---|---|
| sale_id | Unique Sale ID |
| property_id | Related Property ID |
| customer_id | Customer ID |
| agent_id | Agent ID |
| sale_date | Date of Sale |
| sale_price | Final Sale Price |

---

### Schools

| Column | Description |
|---|---|
| school_id | Unique School ID |
| school_name | School Name |
| school_type | Type of School |
| proximity | Distance from Property |

---

## 🗄️ Database Structure

The project database contains the following tables:

```text
Real_Estate_Database
│
├── Properties
├── Customers
├── Agents
├── Sales
└── Schools
