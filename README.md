# Group3 - House Sales in King County, USA - Multiple Regression Model
#**Introduction**

The objective of this project is to develop a linear regression model for the House Sales in King County, USA dataset on this repository as kc_house_data.csv . The purpose of regression analysis is to determine if a set of predictor variables effectively predicts an outcome variable and to identify which variables significantly influence the outcome variable.

Regression Analysis involves three stages: analyzing data correlation and directionality, estimating the model by fitting the line, and evaluating the model's validity and usefulness.

**Stage 1: Data Preprocessing and EDA**
Import the dataset and perform data preprocessing, including handling null values and changing data types.
Conduct Exploratory Data Analysis (EDA) to identify correlations within the data.

**Stage 2: Model Creation**
Create a base model and abstract classes.
Define the LinearModel class as a subclass of the base model.
Implement the least squares and least mean squares linear regression classes.
Initialize the models and create methods for training the data.

**Stage 3: Model Validation**
Generate plots to visualize the predicted line and assess the model's validity.
Verify the model using least mean square and least squares with various data.

#**Overview and Background Information**

**Location and Population**

King County is located in the western part of Washington, USA and is the most populous county in the state.
The county is home to approximately 2.3 million residents, with two-thirds residing in the suburbs.

**Housing Data Analysis**

**Dataset**
The analysis is based on administrative data covering over 21,000 house sales in King County from May 2014 to May 2015.
The dataset includes information on house prices, number of bedrooms, year of construction, and home conditions.

**Housing Market**
King County offers a diverse range of housing options, including single-family homes, townhouses, condominiums, and apartments.

**Housing Varieties**
Single-family Homes: Offer a range of architectural and energy-efficient preferences.
Townhouses and Condominiums: Popular in urban areas like Seattle, providing affordability and convenience.

**Clientele**
Diverse Buyers: Catering to first-time homebuyers, families, young professionals, and retirees.
Tech Influence: The presence of tech giants impacts the demand for upscale, modern homes.

**Summary**
From the following summary, we can see the average prices of the houses per year and the population density based on where the houses are located alongside the prices they fetch based on the year built. 
As expected, the newest houses fetch the highest prices.

![Dashboard 1](https://github.com/Zircornn-Black/Group3/assets/158102409/2b280b45-f575-41a9-8253-32a437355546)


#**Analysis Objectives**

The analysis on house sales in King County aims to achieve the following objectives:

Identify key features strongly correlated with price.
Investigate the relationship between house size and price.
Analyze how price correlates with the condition and grade of the houses.
Explore the relationship between price and home features such as bedrooms, bathrooms, and location.
These objectives leverage data analysis and regression modeling to provide insights and recommendations for homeowners and real estate agencies, aiding in informed investment decisions.

#**Business Understanding**

Informed Decision-Making: Our predictive model uses various house features, and locational data to empower homebuyers with insights for informed purchasing decisions.

Key Influencing Factors: Understanding market trends, structral impacts, and locational variables is essential for informed homebuying decisions.

Maximizing Investments: Thorough research, predictive modeling, and guidance from professionals are crucial for optimizing investment potential in real estate.

**Objectives**
What features are the best predictors of house prices, and how might they impact their decision-making?
How can they optimize their investment potential in the real estate market?
**Modelling**
We used three main Regression models i.e Simple Linear Regression, Multiple Linear Regression and Polynomial Regression.

**Findings**
The polynomial model did the best in predicting house prices.
The square footage of a house is significantly related to its price, as evidenced by the linear regression model which accounts for 49.3% of the variance in housing prices, highlighting its importance as a factor in the housing market.

In addition, when buying a house, the buyer should consider the
grade, location, age, and if the property has a waterfront.

**Recommendations**
Potential buyers should prioritize square footage when considering a house purchase. 
However, it's essential to weigh other factors such as waterfront access, views, and the age of the property, as demonstrated by the multiple linear regression model.

**Next steps**
We need to explore alternative regression techniques to get improve the significance of the models and provide deeper insights from the data.

This can help us go through the following in details and give potential solutions.

**Housing Challenges**
>Housing Affordability: Rising housing costs pose challenges for low and middle-income families.

>Shortage of Housing Units: Intense competition among buyers due to a shortage of housing units.

>Traffic Congestion: Heavy traffic congestion in urban areas impacts commutes and accessibility.

>Climate Change Challenges: Rising sea levels and extreme weather events pose challenges for waterfront properties.

**Solutions**
>Proper Urban Planning: Investment in infrastructure and efficient public transportation to improve connectivity.

>Government Initiatives: Subsidy programs, partnerships with developers, and tax credits to incentivize affordable housing.

>Increasing Housing Supply: Streamlining permitting processes and zoning regulations to facilitate new housing construction.

>Climate Change Mitigation: Promoting green building practices and implementing climate-resilient design standards.

>By addressing these challenges and implementing solutions, this analysis aims to contribute to informed decision-making in the housing market in King County.

