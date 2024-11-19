# Netflix_User_Analysis
This analysis provides valuable insights into user demographics and behavior, focusing on various factors such as gender, age, device usage, subscription types, and revenue. We aim to understand the relationship between key attributes like age, subscription plan, and revenue, offering actionable insights for business decision-making

The Analysis followed different steps and has been fully developed using pandas/numpy/matplotlib and seaborn in VScode studio.

The Analysis has been developed using the Netflix UserBase DataSet from Kaggle.

The dataset provides a snapshot of a sample Netflix userbase, showcasing various aspects of user subscriptions, revenue, account details, and activity. Each row represents a unique user, identified by their User ID. The dataset includes information such as the user's subscription type (Basic, Standard, or Premium), the monthly revenue generated from their subscription, the date they joined Netflix (Join Date), the date of their last payment (Last Payment Date), and the country in which they are located.

Additional columns have been included to provide insights into user behavior and preferences. These columns include Device Type (e.g., Smart TV, Mobile, Desktop, Tablet) and Account Status (whether the account is active or not). The dataset serves as a synthetic representation and does not reflect actual Netflix user data. 

Using the data to understand user trends, preferences, and revenue generation within a hypothetical Netflix userbase.

# Step 1 Exploratory Analysis 
It's been mainly focused on discovering the shape and type of data in the dataset. It is crucial to discover what data we are working, if we have any null value and what column we will need to use.
![image](https://github.com/user-attachments/assets/6dc8c233-e38d-46f4-8867-a2868d3b1bf7)

# Step 2 Transformation
I had to transform my data and create new variables and metrics that would allow me to better return valuable insights.

- Creation Column Currency
  ![image](https://github.com/user-attachments/assets/409ed528-d3fa-4cca-8958-277ff45ba289)
- Creation column that would display the exchange value of the currency vs US dollar
  ![image](https://github.com/user-attachments/assets/25065a9f-3329-4b54-a6e8-f58a750918e1)
This would facilitate the comparison of the different revenues in different countries
# Step 3 Analysis
1) Number of Users by Country
 ![image](https://github.com/user-attachments/assets/57e4d12b-7523-4c97-9e70-2dca4426d5f9)
2) Revenue in US $ by Country
   ![image](https://github.com/user-attachments/assets/6481a2ee-2fa4-4010-b12d-38bb51af4145)
3) Average spending by Country - in this case we can see how in average European countries have a higher revenue pro capita
![image](https://github.com/user-attachments/assets/3a2ab997-9382-4fc0-9272-90a676832322)
# Step 4 Demographic Analysis of Users
1) Users by gender - this shows a slightly higher usage of Netflix among Female users
   ![image](https://github.com/user-attachments/assets/4cf1e9b4-bd8c-454d-b596-0d0853bce637)
2) Revenue by gender - Revenue follows the same pattern of the above chart
![image](https://github.com/user-attachments/assets/c9f32e85-33f7-4279-906c-b91efdcd4ee6)
3) Countries such as  Australia, Italy, and France show a larger male audience
  ![image](https://github.com/user-attachments/assets/8f0d920e-290e-4822-9d25-d8d577fa0eca)
# Step 5 Analysis of User Generation Category 
Using a lambda function we assigned the generational categories GEN X, millennials, and gen z based on the age of the user.
1) User by Category of generation
![image](https://github.com/user-attachments/assets/5ada5d9c-ec7a-47c3-a5d3-747c052ecafb)
2) Category of generation per Country
![image](https://github.com/user-attachments/assets/3b481585-85bf-4a58-990e-dbebc817a24a)
3) Cross Analysis - Gender distribution within each gender category in each country
![image](https://github.com/user-attachments/assets/f98d6761-3b86-43f8-b8dd-de57589d7d74)
# Step 6 Analysis of User Device
1) Total audience by device
 ![image](https://github.com/user-attachments/assets/bbc95ccc-d144-40ac-a2c3-4ae376be8d05)
2) Device usage by Gender
 ![image](https://github.com/user-attachments/assets/baf90cde-87d0-4f7c-ae08-c43a7356cccf)
3) Device Usage by Country
![image](https://github.com/user-attachments/assets/e77d8534-70a8-43c6-bc34-bb0be5e54f09)
4) Device Usage by Gender and Country 
![image](https://github.com/user-attachments/assets/396ec4e0-df2f-42af-8894-1765e18824c4)
# Age Distribution Analysis
We have tried to estimate the average age of the Netflix user population using the sample of the data frame and the t-distribution we obtained that the true mean lies between 36 and 40 years old.
![image](https://github.com/user-attachments/assets/b50f9d48-800d-44a1-ad65-e70831f893c7)
However, the majority of users fall into the categories:
25-30 years old, 38-42 years old and 46 - 51
![image](https://github.com/user-attachments/assets/94cfef5c-8310-4194-9287-d40413a752b6)
Within these categories especially the last one prefers to use a Laptop or Smart TV for accessing Netflix
![image](https://github.com/user-attachments/assets/b68be295-dd6a-4343-b506-f24ce58c5a08)



