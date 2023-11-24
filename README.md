
**[Click Here to view my Portfolio Repository with all Folders Related to Maverik Project](https://github.com/justinhamilton125/Justin_Hamilton_Maverik_Project_Portfolio)**

This repository is designed to show all individual contributions that I (Justin Hamilton) made to the Maverik Project. This repository as been made seperate from my current portfolio to maintain privacy of the Maverik Data.

# [Project 1: Maverik Predictive Modeling for Future Stores - MSBA Capstone (Linked)](https://github.com/justinhamilton125/Justin_Hamilton_Maverik_Project_Portfolio/tree/main/Project%201:%20Maverik%20Modeling%20Project)

## Project Overview:

**Project Objective:** 
Create a predictive model for Home Credit (Loan Brokerage) to identify safe candidates for lending. The model will use customer financial behavior data to determine whether a customer is likely to default on a loan. The project aims to increase revenue, enhance customer experience, and reduce default rates.


**Business Problem:**
Home Credit faces challenges in identifying safe borrowers among customers who are unfamiliar with banking. Lending to individuals with a higher likelihood of loan default leads to decreased profits and negative customer experiences.


**Analytic Problem:**

The project focuses on predicting the creditworthiness of customers based on their financial behavior data. The target variable is binary, where 1 represents customers with payment difficulties (not trustworthy borrowers) and 0 represents trustworthy borrowers with a positive repayment history. 

The objective is to develop a classification model that accurately identifies good borrowers.

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

- Defining the Project Objective, Business Problem, and Analytic Problem
- Listing and defining variables present in the provided datasets
- Exploring the datasets by creating dataframes
- Identifying common columns among the dataframes
- Analyzing summary statistics for all numeric columns in the dataframes
- Summarizing information for categorical variables in the datasets
- Obtaining unique values for categorical columns in the dataframes


[Link to Jupyter Notebook of EDA Individual Contributions of Justin Hamilton](https://github.com/justinhamilton125/Justin_Hamilton_Maverik_Project_Portfolio/blob/main/Project%201%3A%20Maverik%20Modeling%20Project/Exploratory%20Data%20Analysis%20Files/Justin%20Hamilton%20EDA%20(2).ipynb)


[Link to Jupyter Notebook of EDA Final Draft Group Submissions](https://github.com/justinhamilton125/IS-6813-Maverick-Case-Competition/blob/main/EDA%20Final%20Draft/Group%207%20EDA%20Final%20Draft.ipynb)


**Modeling:**

- Prepared dataframes by merging selected datasets to obtain relevant information
- Developed Multiple Regression, Random Forest Classifier, and Ensemble models
- Tuned hyperparameters for each model and evaluated their performance
- Identified and discussed top features influencing customer loan default
- Tested the models on the test set
- Created a Model Performance Summary Table for easy model comparison
- Discussed and analyzed the results of the top features influencing loan default prediction

[Link to Modeling Individual Contributions in Jupyter Notebook of Justin Hamilton](https://github.com/justinhamilton125/Justin_Hamilton_Maverik_Project_Portfolio/blob/main/Project%201%3A%20Maverik%20Modeling%20Project/Modeling%20Files/Justin%20Hamilton%20Modeling%20Contribution%20October%2030%2C%202023.ipynb)


[Link to Modeling Group Final Draft in Jupyter Notebook](https://github.com/justinhamilton125/IS-6813-Maverick-Case-Competition/blob/main/Model%20Final%20Draft/Capstone%20Modeling%20Assignment%20Group%207%20(1).ipynb)




**Presentation**
- Delivered a professional presentation outlining the solutions for Home Credit
- Designed visually appealing and informative slides to effectively communicate the solution and rationale to Home Credit

[Link to PowerPoint Slide Deck Individual Portion](https://github.com/justinhamilton125/Justin_Hamilton_Portfolio/blob/main/Project%201%3A%20Home%20Credit%20Default%20Model%20Files/Justin%20Hamilton%20Presentation%20Portion%20Slide%20Deck.pptx)

## Impact/Business Value:

Implementing this predictive model enables Home Credit to reduce costs by accurately identifying customers likely to default based on their historical data. It also minimizes the risk of granting loans to high-risk individuals. By using the model's predictions, Home Credit can selectively offer loans only to customers projected to have a low likelihood of defaulting. This strategic decision-making process effectively mitigates the risk of loan defaults, reduces non-payment costs, and increases revenue by lending to dependable borrowers. Consequently, this combination of risk reduction, cost optimization, and increased revenue leads to a substantial increase in overall profits for Home Credit.

## Difficulties Along the Way

Throughout this project, our group faced significant challenges related to the limited memory and processing capacity of our individual laptops. Each team member was using a laptop with minimal storage and computing power. As a result, running the models sometimes took up to 8 hours, leading to extended waiting times and difficulties in fine-tuning and training the models to achieve the desired results. The prolonged execution times hindered our ability to efficiently iterate and optimize the models according to our specific requirements.


## Key Take Aways
Throughout this project my main key takeaways were that 
- Collaboration empowers individuals, enabling them to discover superior solutions by leveraging diverse perspectives and insights from the data.

- Data analysis extends beyond merely identifying variables. While a good analysis yields solutions, a great analysis demonstrates its impact and connects it to a tangible business value.

- Cultivating a sense of curiosity is paramount in data analysis. Embracing curiosity allows us to derive meaningful insights from our solutions, encouraging deeper exploration of the data and uncovering novel and unexpected solutions. Staying curious throughout the analysis process motivates us to explore uncharted territories and unlocks valuable discoveries we may not have initially considered.
