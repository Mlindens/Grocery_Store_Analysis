# Grocery Store Analysis

Grocery Store Analysis has 2 year's worth of data (1997-1998) from a fictitious small mom-and-pop grocery store chain.

## Preview




## Dataset Overview

While this dataset is on the smaller side, it still contains valuable information about each store, sales data, product data, and customers.
Here's a quick rundown of what you can expect from the dataset:

* Store data: Information such as store location, address, sqft, remodel date, etc.
* Sales data: Information such as transaction date, stock date, order quantity, customer, location, etc.
* Product data: Information such as discount price, product brand, product name, recycable, product cost, product retail price, etc.
* Customer details: Information about each customer, such as name, birth date, e-mail, address, membership program status, etc.

## Analysis

1. Executive overview: Calculating last year's revenue by month, store location, newly remodeled stores, as well as quantity sold by month and last year's revenue by day of week. 
2. Customer overview: Total unique customers, last year's revenue averaged per customer, last year's revenue by membership, last year's revenue by age, total customers by membership, total customer by gender, total customers by age.
3. Profit insight: Consists of a decomposition tree to leverage the AI of Power BI to calculate the total profit by year, country and month. Decomposition tree has several datafields for its calculation, such as retail price, product brand, date, weight, etc.

## Key Questions Explored

1. Last year's revenue: For all stores, by month, day of week, by store location, and total amount for the year.
2. Total number of stores: Across all locations.
3. Quantity sold: By month.
4. Amount of newly remodeled stores: Across all locations.
5. Last year's revenue: For newly remodeled stores only, total amount for the year.
6. Unique customers: Total number across all stores.
7. Customers by membership: Total number of customers by membership.
8. Customers by gender: Total number of customers by age groups.
9. Last year's revenue: By age groups, by membership, average per customer.
10. Total profit: By country, product retail price, product weight, transaction date. 

## Summary of Findings

* Last year's revenue:
  * All stores: $1.2M
  * By month (highest): December $120,160
  * By month (lowest): October $92,435
  * Day of week (highest): Thursday $181,201
  * Day of week (lowest): Tuesday $162,625
  * Store location (Canada): $107,780
  * Store location (Mexico): $478,938
  * Store location (USA): $612,731
* Total number of stores: 24
* Quantity sold:
  * By month (highest): December 56,729
  * By month (lowest): October 43,945
* Amount of newly remodeled stores: 8
* Last year's revenue for newly remodeled stores: $225,391
* Total unique customers: 10,281
* Customers by membership:
  * Bronze: 55.47%
  * Normal: 23.54%
  * Silver: 9.34%
  * Golden: 11.65%
* Customers by gender:
  * Female: 49.58%
  * Male: 50.42%
* Customers by Age:
   * Age 35-44: 62
   * Age 45-54: 1,424
   * Age 55-64: 1,511
   * Age 65-74: 1,488
   * Age 75 and older: 5,796
* Last year's revenue by age group:
   * Age 35-44: $6,877
   * Age 45-54: $156,179
   * Age 55-64: $173,154
   * Age 65-74: $187,288
   * Age 75 and older: $675,810
* Last year's revenue by membership:
   * Bronze: $673,323
   * Normal: $274,154
   * Silver: $100,360
   * Gold: $151,471
* Last year's revenue, average per customer: $116.65
* Decomposition Tree AI findings:
  * Most profitable country: USA totalling $702,790
    * Most profitable product brand in USA: Hermanos
  * Lowest profit day across all stores: 1/4/1997
    * Least profitable product brand on this day: Moms
  * Least profitable country: Canada
    * Most profitable product brand in Canada: Ebony

Data Source: Maven Analytics

