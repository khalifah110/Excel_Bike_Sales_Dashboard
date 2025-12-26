# Excel_Bike_Sales_Dashboard

<img width="849" height="485" alt="Full" src="https://github.com/user-attachments/assets/782545c7-5d15-4e89-9697-e9ee82e687ae" />


## 📌 Project Overview
The goal of this project was to analyze customer demographics and identify key patterns that influence bike purchases. By processing raw data and creating an interactive dashboard, I transformed a complex dataset into actionable insights regarding income, age, and regional trends.

---

## 🛠️ Data Cleaning Process

Before building the dashboard, I performed several data cleaning steps to ensure the data was professional and easy to interpret:

### 1. Standardizing Categories (Find & Replace)
The raw data contained single-letter abbreviations that were not user-friendly. I used the *Replace* function to standardize the following:
* *Marital Status:* Changed M to Married and S to Single.
* *Gender:* Changed F to Female and M to Male.

<img width="1920" height="1008" alt="Sigel" src="https://github.com/user-attachments/assets/2646129b-3022-4094-ade6-033cd01ed6a8" />

<img width="739" height="381" alt="Married" src="https://github.com/user-attachments/assets/3450511e-b2e4-4b42-9cb1-3c44ec12405b" />

<img width="1920" height="1008" alt="Female" src="https://github.com/user-attachments/assets/dc2e7fd4-db18-4123-a6b0-7fe81458524a" />

<img width="1920" height="1008" alt="Male" src="https://github.com/user-attachments/assets/ef4ef234-7e4d-4701-bb33-2816c1216064" />


### 2. Age Bracket Logic
To better visualize the "Age Range Of Buyers," I used the LOOKUP function to group individual ages into specific categories. This allowed for a much cleaner bar chart analysis.

*Formula used:*
```Excel
=LOOKUP(H2,{25,31,41,51,61,71,81},{"25-30","31-40","41-50","51-60","61-70","71-80","81-90"})
```
---

## 📊 Dashboard Analysis

The dashboard consists of four primary visualizations, each providing a different perspective on the data:

### 1. Average Income Per Purchase (Bar Chart)
This chart displays the average income of customers, segmented by gender. It highlights whether higher-income earners are more likely to purchase a bike compared to those who do not.

<img width="666" height="411" alt="1" src="https://github.com/user-attachments/assets/4d6ce05f-86d5-4056-9138-ad8943a99699" />


### 2. Age Range Of Buyers (Bar Chart)
Using the age brackets created during cleaning, this chart shows which specific age groups have the highest volume of bike purchases.

<img width="697" height="494" alt="age" src="https://github.com/user-attachments/assets/65914db4-fe1d-4267-99c5-ac85cc1222ef" />


### 3. Customer Commute vs. Purchase (Line Chart)
This visualization tracks how the distance a customer commutes affects their decision to buy a bike. It helps identify if bikes are being used for short-distance travel or recreation.

<img width="884" height="487" alt="Screenshot 2025-12-26 084757" src="https://github.com/user-attachments/assets/2970e115-7de4-4efb-9989-f38ac036d69b" />


### 4. Regional Sales Distribution (Pie Chart)
A geographic breakdown showing the percentage of customers across North America, Europe, and the Pacific regions.

<img width="942" height="578" alt="Screenshot 2025-12-26 084146" src="https://github.com/user-attachments/assets/bf1dc24e-9086-4a90-9946-76d414284db5" />


---

## ⚡ Interactivity (Slicers)

<div align="left">

<h4>Marital Status (Married vs. Single)</h4>
<img src="https://github.com/user-attachments/assets/4ef3317f-58d8-4b03-a655-cbb60ed43b87" width="450"/>

<h4>Education (Graduate Degree, Bachelors, High School, etc.)</h4>
<img src="https://github.com/user-attachments/assets/959d42ba-3f90-450b-ae40-f10b36a6cbcd" width="450"/>

<h4>Regions (Europe, North America, Pacific)</h4>
<img src="https://github.com/user-attachments/assets/7cd0eb7c-eafc-47cd-8a48-58f91b43fb25" width="450"/>

</div>


---

## 🚀 Key Skills Demonstrated
* *Data Cleaning:* Using Find & Replace and logical functions.
* *Advanced Formulas:* Implementing LOOKUP for data categorization.
* *Data Visualization:* Creating Charts (Bar, Line, Pie).
* *UI/UX Design:* Using Slicers and layout principles for an interactive user experience.

## 📊 Key Insights & Findings

After analyzing the data through the dashboard, the following industry-standard insights were identified:

* *Regional Dominance:* North America represents the largest market share, accounting for *51%* of the total bike consumers.
* *Income Correlation:* There is a direct positive correlation between income and purchasing power; both *Male and Female* segments with higher average incomes showed a significantly higher frequency of bike purchases.
* *Core Demographics:* Consumers between the ages of *25 and 70* constitute the primary market. Specifically, the *31-40 age bracket* showed the highest peak in purchasing activity.
* *Commute Influence:* Proximity is a major factor in sales; customers with a commute distance of *0 to 1 miles* (extending up to 5 miles) are the most likely to purchase a bike, indicating a preference for short-distance cycling.


