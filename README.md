# Instacart-EDA
Instacart Market Basket Analysis EDA

### Introduction
Instacart is an American technology company that operates as a same-day grocery delivery and pick up service in the U.S. and Canada. Customers shop for groceries through the Instacart mobile app or Instacart.com from various retailer partners. The order is shopped and delivered by an Instacart personal shopper.

### Objectives:
<ul>
  <li>Analyze the anonymized data of 3 million grocery orders from more than 200,000 Instacart users open sourced by Instacart</li>
  <li>Deploy a detailed EDA</li>
  <li>Descriptive Analytics to visually present</li>
    <ul>
      <li>Busiest day of the week  </li>
      <li>Busiest hour of the day </li>
      <li>Best seller product and Department (separately) </li>
      <li>Highest reorder of products</li>
      <li>Histogram of customer retention (reordering)</li>
    </ul>
      
      
  <li>Enrich the analytics</li> 
</ul>

### Data Description

The dataset contains the following 6 files
<ol type="1">
  <li>aisles.csv </li>
      This file contains different aisles and there are total 134 unique aisles.
  <li>departments.csv</li>
      This file contains different departments and there are total 21 unique departments.
  <li>orders.csv</li>
      This file contains all the orders made by different users. From below analysis, we can conclude following:
      <ul>
        <li>There are total 3421083 orders made by total 206209 users.</li>
        <li>Based on the plot of 'Orders VS Day of Week' we can map 0 and 1 as Saturday and Sunday respectively based on the             assumption that most of the people buy groceries on weekends.</li>
        <li>Majority of the orders are made during the day time.</li>
        <li>Based on the heatmap between 'Day of Week' and 'Hour of Day,' we can say that Saturday afternoons and Sunday                 mornings are prime time for orders.</li>
      </ul>
  <li>products.csv</li>
  This file contains the list of total 49688 products and their aisle as well as department. The number of products in         different aisles and different departments are different.
  <li>order_products__prior.csv</li>
  <li>order_products__train.csv</li>
</ul>

