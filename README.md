
# Delivery Performance Analysis 

## Project Overview

This project analyzes a comprehensive food delivery dataset to extract valuable insights on delivery performance, customer satisfaction, and operational efficiency. Using SQL, various key aspects such as delivery ratings, delivery times, vehicle conditions, traffic impact, peak hours, and the effect of festivals on delivery performance are explored. Advanced queries also include recursive date generation and predictive insights to support real-time decision-making.

The analysis aims to help delivery companies optimize operations, improve customer satisfaction, and identify bottlenecks in their delivery process.

---

## Business Problem

In the highly competitive food delivery industry, timely deliveries and high customer satisfaction are critical. Companies face challenges including:

- Delays due to traffic, weather, or vehicle conditions.
- Variations in delivery performance across cities and delivery personnel.
- Managing peak demand periods efficiently.
- Predicting late deliveries to proactively manage customer expectations.
- Understanding the impact of external factors like festivals and weather on delivery efficiency.

Addressing these issues helps reduce delivery time, improve customer ratings, and optimize resource allocation.

---

## Solution & Approach

To solve these problems, this project uses **SQL-based exploratory data analysis and predictive queries** on delivery datasets, focusing on:

- Tracking delivery ratings and performance over time.
- Comparing average delivery times across different cities, vehicle conditions, and traffic levels.
- Identifying popular order types and frequent delivery locations.
- Analyzing delivery delays during festivals and peak hours.
- Using recursive CTEs to generate complete daily delivery counts, even for days with no orders.
- Segmenting delivery times into buckets and categorizing traffic and weather conditions to predict late deliveries.
- Ranking delivery personnel by their efficiency and ratings to recognize top performers.

This data-driven approach helps businesses optimize delivery logistics, plan for high-demand periods, and enhance customer experience through improved operational insights.

---


## Overview of outputs

-- Most popular food order type in each city
![image](https://github.com/user-attachments/assets/fc9151f4-4748-4497-b458-d796e1595f62)
output
![image](https://github.com/user-attachments/assets/e3c87a8f-43d7-4e09-8308-ad37c1b5bd77)

-- Festival vs. Non-Festival delivery time comparison
![image](https://github.com/user-attachments/assets/be66004e-205e-4c88-a4b6-8feaea9f1e1d)
output
![image](https://github.com/user-attachments/assets/66b35de3-9491-4b07-ac7a-11e4b6563020)

-- Top delivery person by delivery time & rating
![image](https://github.com/user-attachments/assets/9bcd2fbc-d238-4b14-9846-220a90b3bde8)
output
![image](https://github.com/user-attachments/assets/26608dc2-eeca-4c43-873a-4b13c604170c)

-- How delivery times vary by city
![image](https://github.com/user-attachments/assets/3ee68bcc-632e-4c10-974b-bbc0ff347e8c)
output
![image](https://github.com/user-attachments/assets/d6767f96-40b9-47fa-b827-69f41055d754)

-- Daily Delivery Count 
![image](https://github.com/user-attachments/assets/176f7b92-e433-4e03-bbf5-0d7a815a05b6)
output
![image](https://github.com/user-attachments/assets/1d829ef8-05e5-4372-8549-73336a599873)

--  Average rating by age group
![image](https://github.com/user-attachments/assets/b62dc563-48e7-4859-96d9-6fc6068cb0a3)
output
![image](https://github.com/user-attachments/assets/94cf8f57-8860-46f3-94fd-dd9197ed4bf1)











## Repository Structure

- `scripts` — Contains all SQL scripts for data analysis and queries.
- `README.md` — Project overview and documentation.
- `dataset` — Folder for sample or raw data files.
- `reports/` — Summary reports or export results.

---

## Technologies Used

- MySQL for database and querying
- SQL concepts: window functions, recursive CTEs, aggregation
- GitHub for version control and project management


---

## How to Use

1. Clone the repository.
2. Load your food delivery dataset into your SQL environment.
3. Run the SQL scripts in the `sql/` folder step-by-step.
4. Explore and modify queries to fit your specific business needs.
5. Use insights to guide operational improvements and predictive modeling.

---

## Author
### — Sudeshna Dey
###  — Contact & Contributions

#### 📧 Email: sudeshnadey1000@gmail.com
#### 🔗 LinkedIn: https://www.linkedin.com/in/sudeshna-dey-724a811a0/
 Have feedback or suggestions? I'm always open to improving and collaborating!
 
If you find this project helpful:
⭐ Give it a star
Thanks for visiting — and happy data analyzing!

