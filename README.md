# Coffee Bean Sales Dashboard

## Project Overview

This project analyses transactional coffee sales data using Microsoft Excel to identify patterns in product performance, regional revenue, and customer behaviour. The analysis integrates multiple datasets before building an interactive dashboard to explore key sales insights.

---

## Project Objective

The objective of this project was to analyse transactional sales data and develop an interactive Excel dashboard that allows users to explore sales performance across products, regions, and time through dynamic filtering and visualisation.

---

## Data Source

The analysis uses the **Coffee Bean Sales Raw Dataset**, which contains **1,000+ coffee sales transactions**, including order, customer, and product information.

Source:
https://www.kaggle.com/datasets/saadharoon27/coffee-bean-sales-raw-dataset/data

The raw dataset used for this project is also included in the `data/` folder of this repository.

---

## Data Model

The analysis integrates three related datasets:

- **Orders** – transactional sales data containing order ID, order date, customer ID, product ID, and quantity ordered.
- **Customers** – customer information containing customer ID, customer name, email, phone number, address, city, country, postcode, and loyalty card status.
- **Products** – product details containing product ID, coffee type, roast type, size, unit price, price per 100g, and profit per unit sold.

The **Orders** table acts as the central fact table, linking customer and product information to each transaction through **Customer ID** and **Product ID**. These relationships allow sales performance to be analysed across products, regions, and customer segments.

---

## Analysis Workflow

### 1. Data Preparation

### 2. Data Analysis

### 3. Dashboard Creation

---

## Dashboard Preview

---

## Repository Structure

coffee-bean-sales-dashboard  
│  
├── excel/  
│   └── coffee-bean-sales-dashboard.xlsx  
│  
├── data/  
│   └── raw datasets used for analysis  
│  
├── images/  
│   └── dashboard-preview.png  
│  
├── LICENSE  
└── README.md  
