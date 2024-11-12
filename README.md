# Customer-segmentation-for-subscription-service
## 📊 Project Overview
      The Customer Subscription Dashboard provides an in-depth analysis of customer behavior, subscription trends, 
      cancellations, renewals, and revenue insights for a subscription-based service. 
      The dashboard was built using Power BI and SQL to extract key insights and visualize the data effectively.

## ✨ Key Features:
      Subscription Overview: Visualizes total subscriptions, cancellations, renewals, and revenue trends.
      Customer Segmentation: Analyzes customer behavior based on subscription types and regions.
      Revenue Analysis: Highlights revenue performance and trends over time.

## 🗄️ Dataset
    The dataset used for this project contains the following columns:
    customerID: Unique identifier for each customer
    customerName: Name of the customer
    region: Customer's geographical region
    subscriptionType: Type of subscription (e.g., Basic, Premium, Enterprise)
    subscriptionStart: Start date of the subscription
    subscriptionEnd: End date of the subscription
    duration: Subscription duration in months
    canceled: Indicates whether the subscription was canceled (Yes/No)
    renewed: Indicates whether the subscription was renewed (Yes/No)
    revenue: Total revenue generated from the subscription

## 🛠️ Tools Used
     Power BI: For data visualization and dashboard creation
     SQL Server:  For querying and analysis of the dataset

## 📈 SQL Queries
      Here are some key SQL queries used in the project:

      Calculate Total Revenue:
      `SELECT SUM(revenue) AS total_revenue
       FROM subscriptions`

















     
