# Power BI Sales Transaction Dashboard

---

## 🔗 Access the Dashboard
 
* 📄 **Dashboard Report:**
  👉 [Click here to view the dashboard](./Dashboard/)

---


## 1. Background and Overview

This personal project dashboard provides a detailed analysis of global **sales transactions** across countries, customers, and products. It highlights customer behavior, product performance, revenue trends, and transaction status. The data covers **2018 to 2019**, offering a foundation for understanding buying patterns and business cycles over time.

The purpose of this project is to:

* Monitor revenue and order trends
* Track successful vs. canceled orders
* Identify top-selling products and their price patterns
* Discover country-wise product contributions

---

## 2. Data Structure Overview

The dataset consists of a single transactional table with the following key fields:

| Column Name                   | Description                            |
| ----------------------------- | -------------------------------------- |
| `TransactionID`               | Unique ID for each transaction         |
| `CustomerID`                  | Customer identifier                    |
| `Country`                     | Country where the transaction occurred |
| `DMY`                         | Transaction date (Day-Month-Year)      |
| `ProductID`, `ProductName`    | Product identifiers and names          |
| `Price`                       | Unit price of product                  |
| `Quantity`                    | Number of units ordered                |
| `Status`                      | Order status (Succeed / Cancelled)     |
| `Measure Revenue`             | Total revenue generated                |
| `Measure Average Order Value` | Average revenue per order              |

---

## 3. Executive Summary

### Overall Key Metrics

* **Total Customers**: 4,738
* **Total Quantity Sold**: 261,000 units
* **Total Revenue**: \$2.89 Million
* **Average Order Value (AOV)**: \$610

### Transaction Breakdown

* **Successful Transactions**:

  * Customers: 4,300
  * Quantity: 264,864

* **Cancelled Transactions**:

  * Customers: 438
  * Quantity: –3,795 (returned or removed)

> Insight: This indicates a **high transaction success rate**, with minimal impact from cancellations.

---

## 4. Insight Deep Dive

### a. Product-Level Performance

| Product Name                      | Quantity Sold | Unit Price |
| --------------------------------- | ------------- | ---------- |
| Medium Ceramic Top Storage Jar    | 74,217        | \$17.51    |
| Small Chinese Style Scissor       | 4,504         | \$38.03    |
| World War 2 Gliders Asstd Designs | 3,792         | \$37.56    |
| Vintage Doily Jumbo Bag Red       | 1,502         | \$12.38    |
| Metal Sign Take It Or Leave It    | 1,416         | \$32.73    |

> Insight: Products like **Storage Jars** dominate by volume, while others like **Scissors** and **Gliders** have higher price points, contributing significantly to revenue.

---

### b. Revenue Trend by Month & Year

* **December 2018**:

  * Revenue: \$48,580.21
  * Top Country: EIRE
  * Top Product: *12 Egg House Painted Wood*

* **January 2019**:

  * Revenue spike to **\$855,921.87**
  * Country: Australia
  * Product: *12 Egg House Painted Wood*

* **Mid-2019**:

  * Revenue dropped to \~\$13,286.85 (e.g., Belgium, *10 Colour Spaceboy Pen*)
  * Stayed below \$0.5M in most months

* **November 2019**:

  * Recovery to \$342,099.84
  * Country: Australia
  * Product: *10 Colour Spaceboy Pen*

* **December 2019**:

  * Highest peak: **\$1,110,413.49**
  * Country: Austria
  * Product: *12 Coloured Party Balloons*