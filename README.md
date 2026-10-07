# Customer Feedback Automation

## Project Overview

This project is an automated customer feedback management system built using Microsoft Forms, Excel and Power Automate.

The automation collects customer feedback, stores the responses in an Excel table, evaluates the customer's rating and sends an appropriate email notification.

## Project Objective

The objective of this project is to reduce manual customer-feedback processing by automatically:

* Collecting customer feedback
* Storing feedback in Excel
* Checking customer ratings
* Sending thank-you emails for positive feedback
* Alerting the customer-service team when feedback requires attention

## Technologies Used

* Microsoft Forms
* Microsoft Excel
* Power Automate
* Outlook

## ⚙️ How the Automation Works

```text
Customer submits feedback
          ↓
Microsoft Forms
          ↓
Get response details
          ↓
Add response to Excel table
          ↓
Check customer rating
          ↓
     Rating >= 4?
       ↙       ↘
     YES        NO
      ↓          ↓
Thank-you     Alert
email         customer-service team
```

##  Customer Feedback Form

The form collects:

* Customer Name
* Email Address
* Product/Service
* Rating
* Feedback
* Recommendation

## Excel Data

Customer responses are stored in an Excel table containing information such as:

| Field        | Description                                 |
| ------------ | ------------------------------------------- |
| CustomerName | Customer's name                             |
| Email        | Customer's email address                    |
| Product      | Product or service                          |
| Rating       | Customer rating from 1–5                    |
| Feedback     | Customer comments                           |
| Recommend    | Whether the customer recommends the service |
| Date         | Date of submission                          |

## Power Automate Flow

The Power Automate workflow contains the following main steps:

1. **When a new response is submitted**
2. **Get response details**
3. **Add a row into an Excel table**
4. **Check whether the rating is greater than or equal to 4**
5. **Send a thank-you email for positive feedback**
6. **Send an alert to the customer-service team for lower ratings**

## Business Value

This automation demonstrates how Power Automate can be used to:

* Reduce repetitive manual work
* Improve response times
* Automatically identify negative feedback
* Improve customer communication
* Centralise customer feedback data

## Screenshots

Screenshots demonstrating the Microsoft Form, Excel table and Power Automate workflow are included in the `Screenshots` folder.

## Future Improvements

Possible improvements include:

* Power BI customer-feedback dashboard
* Automatic feedback categorisation
* Customer-service follow-up tracking
* Teams notifications
* Sentiment analysis
* Monthly feedback reports

## Skills Demonstrated

* Microsoft Power Automate
* Microsoft Forms
* Excel data management
* Workflow automation
* Conditional logic
* Email automation
* Business process automation
* Basic data analysis

