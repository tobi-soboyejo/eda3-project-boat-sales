# **Exploratory Data Analysis Project 2 (Nigerian Higher Education Institutions)**
A beginner exploratory data analysis project on Boat Sales Data. 

# **Introduction** 
This project is meant to be a basic, beginner, level exploratory data analysis project on data about boat sales. The creator of the dataset proposes a scenario where we are data analyst at a boat/yacht club and our goal is to provide useful data for our marketing team.

## **Data Sourcing/Credits**
The dataset used for this project can be found on Kaggle, **"Boat Sales"**. This dataset was created by user **Karthik Bhandary**. 

### **Objectives:**
As mentioned above the objective is to act as a data analyst for a boat company and provide useful insights for the marketing team. 
Here is a list of question I chose to answer:

1. Number of boats made of a certain material. What material is most popular for recent users?
2. Number of boats made from a specific country. Are there any countries that customers prefer to buy their boats from?
3. Number of boats that are used or new. Do buyers prefer used or new boats?
4. How many views have the expensive boats received compared to the cheaper ones? 
5. Number of boats per year built. What years have the highest production of boats?

## **Data Description**

- **Price**: boat price listed in different currencies (e.g. EUR, Â£, CHF etc.) on the website.
- **Boat Type**: type of the boat.
- **Manufacturer**: manufacturer of the boat.
- **Type**: condition of the boat and engine type (e.g. New, Used etc.).
- **Year Built**: year of the boat built.
- **Length**: length in meter of the boat.
- **Width**: width in meter of the boat.
- **Material**: material of the boat (e.g. GRP, PVC, etc.).
- **Location**: location of the boat is listed.
- **Number of views**: number of the views of the list last 7 days.

## **Exploratory Data Analysis**
After cleaning the data and structuring it in the right way (splitting columns to create new ones, converting currencies, etc.), I moved onto the analysis.

- This plot visualizes the popularity of material.
  - We can clearly see that **GRP** is the most popular material type. 

![(Plot 1) EDA3 - Boat_Sales](https://github.com/tobi-soboyejo/eda3-project-boat-sales/assets/155042996/6ab6e136-1400-4b76-8bd4-22ebe7760fa0)

- This plot shows the countries that manufactuer the most boats.
  - We can see that **Germany, Italy, Switzerland, France and Spain** are the largest boat producers.

![(Plot 2) EDA3 - Boat Sales](https://github.com/tobi-soboyejo/eda3-project-boat-sales/assets/155042996/a8419387-a5a9-4126-afe7-ff35f9307a29)

- This graph shows the percentage of each type of boat available on the company site.
  - Used boats are the most common.

![(Plot 3) EDA3_Boat_Sales](https://github.com/tobi-soboyejo/eda3-project-boat-sales/assets/155042996/6ace72a9-8f5e-46f7-bca4-16c6be2cc699)

- This graph visualizes the amount of boats produced per year over time. **(Question 5)**
  - Boat production greatly increased in 2020.

![(Plot 4) EDA3 - Boat_Sales](https://github.com/tobi-soboyejo/eda3-project-boat-sales/assets/155042996/43c05d36-5d85-4465-b4ab-4cec764066ed)

- The plot below visualizes the amount of views received in the last 7 days by boats made in each country. **(Question 2)**. 
  - Switzerland made boats have received a lot of attention from customers over the past week. The marketing team could use this information.

![(Plot 5) EDA3 - Boat_Sales](https://github.com/tobi-soboyejo/eda3-project-boat-sales/assets/155042996/bd0739de-93ec-4b6a-a0bc-d68bc9570f6d)

- This plot shows the amount of views received in the last 7 days by boats of a certain condition. **(Question 3)**.
  - There is clear interest in used boats over the last seven days, but there also seems to be a slight preference between the types of new boats that customers choose to look at.

![(Plot 6) EDA3 - Boat_Sales](https://github.com/tobi-soboyejo/eda3-project-boat-sales/assets/155042996/e494e25a-bb23-481f-b7ec-4203247caf8a)

- This plot visualizes the amount of views received in the last 7 days by boats made in each year. 
  - Boats made in the year 2020 received far more views in total compared to boats made from other years. This makes sense since there was such a large increase in boat production over that year. Either that, or the boats listed on this company site heavily favor boats made in that year.

![(Plot 7) EDA3 - Boat Sales](https://github.com/tobi-soboyejo/eda3-project-boat-sales/assets/155042996/9c0a124a-f0a3-4fc1-ab0d-6fbdb9a1c996)

- This plot visualizes the relationship between views received in the last 7 days and manufacturer.
  - The manufacturer "Bayliner Power Boats" has clearly been the most popular over the past week. **(Question 4)**

![(Plot 8) EDA3 - Boat_Sales](https://github.com/tobi-soboyejo/eda3-project-boat-sales/assets/155042996/46cc5e06-448f-4370-b7b1-b3f53d74ca6b)

- This plot shows the popularity of material types over the past 7 days. **( Question 1)**
  - **GRP** is the most popular on average, but there appears to be an interest in boats made from **plastic** over the past week.

![(Plot 9) EDA3 - Boat_Sales](https://github.com/tobi-soboyejo/eda3-project-boat-sales/assets/155042996/b05bbf9b-d3ad-47d3-842a-108c4c65e503)

- This plot visualizes the relationship between boat price and views over the last week. **(Question 4)**
  - The majority of views are target towards more affordable boats, which is good because those viewers are more likely to be buying something they can afford, making a sale more likely. As expected there are views for the extremely expensive boats that customers like to look at for window shopping.

![(Plot 10) EDA3 - Boat_Sales](https://github.com/tobi-soboyejo/eda3-project-boat-sales/assets/155042996/8f6c13bb-99a2-4852-aea5-39ecc7f24ff7)

 
