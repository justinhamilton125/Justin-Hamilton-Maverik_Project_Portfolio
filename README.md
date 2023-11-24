
**[Click Here to view my Portfolio Repository with all Folders Related to Maverik Project](https://github.com/justinhamilton125/Justin_Hamilton_Maverik_Project_Portfolio)**

This repository is designed to show all individual contributions that I (Justin Hamilton) made to the Maverik Modeling Project. This repository as been made seperate from my current portfolio to maintain privacy of the Maverik Data.

# [Project 1: Maverik Predictive Modeling for Future Stores - MSBA Capstone (Linked)](https://github.com/justinhamilton125/Justin_Hamilton_Maverik_Project_Portfolio/tree/main/Project%201:%20Maverik%20Modeling%20Project)

## Project Overview:

**Project Objective:** 
Maverik will be able to implement the model created in order to predict daily sales for diesel fuel, unleaded fuel, merchandise, and food sales for the entire first year of a store's operation. This model needs to surpass the performance metrics used by the current Maverik model in predicting these 4 product sales. 

**Business Problem:**
Maverik desires to know the predicted daily sales for each of the 4 main products diesel fuel, unleaded fuel, merchandise, and food sales. Having these daily predictions allows for better planning for seasonality and setting realistic goals and expectations for what each new store can bring in revenue. These predictions will allow Maverik to match the needs of estimated supply and demand. 


**Analytic Problem:**
This project focuses on developing a model that will predict daily sales for 365 days for each of the 4 key indicators (target variables) of unleaded gasoline, diesel fuel, in store merchandise, and food service sales. This model's daily predictions are to be based off past time series data of the stores sales per our 4 target variables, attributes of each stores offerings, and seasonality that occurs through customer behavior through the year. The variables unleaded and diesel are in gallons sold, while in store merchandise and food services are in dollars. 

The model is to surpass current performance metrics of the model that is being used by Maverik and allow for simple implementation for a user friendly capability. 



[Link to a More Detailed Business Problem Statement Submitted by Group](https://github.com/justinhamilton125/IS-6813-Maverick-Case-Competition/blob/main/Business%20Problem%20Statement%20Final%20Draft/IS%206813%20Maverick%20Business%20Problem%20Statement.pdf)


[Link to a More Detailed Business Problem Statement Contributions of Justin Hamilton](https://github.com/justinhamilton125/Justin_Hamilton_Maverik_Project_Portfolio/blob/main/Project%201%3A%20Maverik%20Modeling%20Project/Business%20Problem%20Statement%20Files/Business%20Problem%20Statement%20Justin%20Hamilton%20Individual%20Contributition.pdf)


## Solution to Business Problem
Our group's solution to the business problem involved implementing a Gradient Boosting Model. This model yielded a Kaggle score of 0.656 and an AUC of 0.669, indicating its reasonable performance.

Based on our model's analysis, we identified several important factors that significantly influence the likelihood of loan default:

1. A high number of enquiries were made to the Credit Bureau just one day before the loan application
2. Clients provide a work phone during the application process
3. Clients residing in regions of the city with lower ratings, as determined by their address
4. Loans used for purchasing high-priced goods
5. A large number of enquiries were made to the Credit Bureau within one hour prior to the application
6. Mismatch between the client's permanent address and contact address

These findings can be crucial for Home Credit to assess the creditworthiness of applicants and make informed lending decisions that will lead to minimized risk, cost, increasing revenue, and profit for the company.


[![Link to Features Ranked by Importance Graph](https://github.com/justinhamilton125/Justin_Hamilton_Portfolio/blob/main/Project%201%3A%20Home%20Credit%20Default%20Model%20Files/Images/Feature%20Importance%20Solution%20Graph.png)](https://github.com/justinhamilton125/Justin_Hamilton_Portfolio/blob/main/Project%201%3A%20Home%20Credit%20Default%20Model%20Files/Images/Feature%20Importance%20Solution%20Graph.png)


## Individual Contribution

Throughout the phases of this project, I contributed by,

**Exploratory Data Analysis:**

- Defining the Project Objective, Business Problem, and Analytic Problem.
- Identifying which of the variables were categorical and continuous for Store Qualitative Attributes.
- If a variable was categorical, gathering all possible levels of that variable.
- Visualizing across all stores the different services that were offered at how many store locations.
- Developing histograms of the continuous store attributes to see the patterns of Maverik developing all stores and what common patterns exist across stores.
- Conducted a survey research on what customer preference, then weighting each attribute of a store to develop a composite score ranking which store customers may find preferrable. 


[Link to Jupyter Notebook of EDA Individual Contributions of Justin Hamilton](https://github.com/justinhamilton125/Justin_Hamilton_Maverik_Project_Portfolio/blob/main/Project%201%3A%20Maverik%20Modeling%20Project/Exploratory%20Data%20Analysis%20Files/Justin%20Hamilton%20EDA%20(2).ipynb)


[Link to Jupyter Notebook of EDA Final Draft Group Submissions](https://github.com/justinhamilton125/IS-6813-Maverick-Case-Competition/blob/main/EDA%20Final%20Draft/Group%207%20EDA%20Final%20Draft.ipynb)


**Modeling:**

- Prepared data frames by merging qualitative and time series data against the store ID for the model to learn from the data set.
- Encoding each of the categorical predictors for our model to correctly predict against these values and learn patterns.
- Encoding the dates as categorical variables for the model to learn the seasonality patterns of sales of all 4 sales metrics.
- Splitting the data sets into test and training sets
- Built a SARIMA model to predict daily sales for a year based on information fed into the model on attributes and sales of dates.
- Creating an output with 365 sales per day based on the current date.
- Using hyper parameter tuning for a train set, building the model, then testing the model against a test set to give us the best performing SARIMA model based on R-Squared and RMSE values. 
- Developing a table that is easier to read predicted outputs.
- Creating a user interface that allows a user to input all qualitative information about a store, user inserts it, then prints the 365 days of the years sales.
- Inserted a simple code that also allows the customer to run the model against a CSV file to gather predicted sales for each 4 units. (Unleaded gallons, diesel gallons, in store merchandise, and food service sales in dollars)


[Link to Modeling Individual Contributions in Jupyter Notebook of Justin Hamilton](https://github.com/justinhamilton125/Justin_Hamilton_Maverik_Project_Portfolio/blob/main/Project%201%3A%20Maverik%20Modeling%20Project/Modeling%20Files/Justin%20Hamilton%20Modeling%20Contribution%20October%2030%2C%202023.ipynb)

[Link to Modeling Group Final Draft in Jupyter Notebook](https://github.com/justinhamilton125/IS-6813-Maverick-Case-Competition/blob/main/Model%20Final%20Draft/Capstone%20Modeling%20Assignment%20Group%207%20(1).ipynb)


**Presentation**
- Delivered a professional presentation outlining the solutions for Home Credit
- Designed visually appealing and informative slides to effectively communicate the solution and rationale to Home Credit

[Link to PowerPoint Slide Deck Individual Portion](https://github.com/justinhamilton125/Justin_Hamilton_Portfolio/blob/main/Project%201%3A%20Home%20Credit%20Default%20Model%20Files/Justin%20Hamilton%20Presentation%20Portion%20Slide%20Deck.pptx)

## Impact/Business Value:

Implementing this user friendly predictive model allows Maverik to plan effectively for all key areas of the business. This predictive model allows finance to understand the estimates that should be occuring quarterly, operations to meet the supply and demanded seen by each store based on predictive sales data, marketing to know which stores to increase advertising to in the area to increase revenue thus increasing profit, and management to see which stores may need more staffing based on having more sales (indicating there to be more need for service at the location). It is clear that this model has the ability to support each of the main functions of running a successful business such as Maverik. Using this model will allow for proper planning of each new store, while still seeing opportunities to increase revenue in stores, thus increasing total profit of Maverik.  

## Difficulties Along the Way

Throughout the project, the main difficulty our group came across was meeting the expectations of the client (Maverik), computation cost of building the models, and determining of all good models which would be the best. Our group found that generally, Maverik was unclear or uncertain on the result that they were looking for from us. This taught us that it is highly important to always ask questions when facing the client to ensure that we meet the expectations and requirements of the client. With the large predictions of the models, we also ran into difficulties of computation cost as most users computers had only 8 GB of RAM. This limited the output that our code could generate, but could generate better outputs when ran on a more powerful computer. We found that we had many well performing models, but with so many well performing models it could become difficult to know which of them were the best to send to Maverik because each model had its' own pros and cons it could become difficult the universally used on in recommendation and application to Maverik. 

## Key Take Aways
Throughout this project my main key takeaways were that 
- Ask, Ask, Ask. The best way that you can meet the desires of the client is by having an open discussion and always asking questions. Things change, so should the approach to solving the problem for the client's best success.

- When implementing a model, the user is the end game. Once a model is built and performs well, it is most important for the client or user to easily replicate the results they desire by running this model on their own. 

- Collaboration and contribution between data analysts is key. Building the right model takes time, so to increase effiency each data analyst can bring their own perspective and talent to the project to meet all the client's needs. Projects work best when each individual brings their own strengths and weaknesses, then working together to make an even stronger group result. After all, you can't have a feast if every body brings the same dish.
