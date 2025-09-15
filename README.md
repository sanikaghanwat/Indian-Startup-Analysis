# Indian-Startup-Analysis
This project explores the Indian startup ecosystem using data analysis and visualization.

In India, many people hesitate to pursue entrepreneurship due to the fear of startup failure and the perception that traditional jobs are "safer." However, analyzing startup data can give insights into what drives success or failure — such as sector trends, funding patterns, founder background, investor preferences, city ecosystem, and survival rates.

# Problem Statement:
To analyze Indian startup ecosystem data to understand patterns in funding, founder background, sectors, and other factors that influence startup success or failure. The goal is to provide insights that can help entrepreneurs, investors, and policymakers make better decisions."
Data Cleaning & Preprocessing

# Dataset: 
        Date', 'Startup_Name', 'Sector', 'City', 'Funding_Type',
       'Funding_Amount', 'Education_Background', 'Age_Group',
       'Professional_Background', 'Gender_Mix', 'Initial_Investment',
       'Burn_Rate', 'Revenue_Model', 'Customer_Type', 'City_Tier',
       'Competition_Level', 'No_of_CoFounders', 'Status',
       'Survival_Duration_Years

# The dataset contained:

Missing values → Replaced with "Unknown" (categorical) or 0 / mean / median (numerical).

Duplicate records → Removed to avoid bias.

Basic formatting fixes → Converted Date to Year, standardized categories like Sector and Funding Type.

# Exploratory Data Analysis (EDA)  ((some sample screenshots))

The analysis was performed at three levels:

## Univariate Analysis

### Categorical: Sector, Funding Type, Gender Mix, Revenue Model.

<img width="1012" height="381" alt="image" src="https://github.com/user-attachments/assets/019c0e2e-0bea-4616-aead-4d9cad80a192" />
<img width="1001" height="500" alt="image" src="https://github.com/user-attachments/assets/c9ccb9cf-597a-4367-90ed-d5b60d9bc2a0" />
<img width="945" height="502" alt="image" src="https://github.com/user-attachments/assets/bc39b3d7-cd89-4ebe-9a5f-83089946e82f" />


### Numerical: Funding Amount, Initial Investment, Burn Rate, Survival Years.
<img width="1020" height="506" alt="image" src="https://github.com/user-attachments/assets/8cac535c-4d87-4b9f-aaac-3cc0546d0d29" />

### Bivariate Analysis

## Categorical vs Categorical (Sector vs Status).
<img width="809" height="513" alt="image" src="https://github.com/user-attachments/assets/9e2e85d0-7062-45a6-aff6-e881171954c9" />

##Categorical vs Numerical (Funding Type vs Funding Amount).

<img width="543" height="404" alt="image" src="https://github.com/user-attachments/assets/2338dab9-65a2-4d94-af83-5642aa049439" />

<img width="720" height="550" alt="image" src="https://github.com/user-attachments/assets/d9cb6689-38d0-421d-8ed7-c57d46973158" />


### Numerical vs Numerical (Funding Amount vs Initial Investment).

<img width="983" height="554" alt="image" src="https://github.com/user-attachments/assets/3a328683-ea27-4522-83bc-7853407f0227" />

### Multivariate Analysis

Most Common Sectors
<img width="925" height="555" alt="image" src="https://github.com/user-attachments/assets/e900ed5e-6b8e-41f2-a622-bfcc2ca284d0" />


Initial Investment across City Tiers
<img width="866" height="487" alt="image" src="https://github.com/user-attachments/assets/5257ccc9-dab4-4465-9a7f-be68bf2cfa3c" />


Competition Level vs Startup Status
<img width="890" height="503" alt="image" src="https://github.com/user-attachments/assets/f560eb79-82a1-44a6-ba6c-d8f007a8ec90" />

Survival Duration by Age Group
<img width="874" height="493" alt="image" src="https://github.com/user-attachments/assets/bfbb67a7-26ca-46e6-b8da-77fa476957fb" />

## Key Insights

#### Startup Hubs: Bengaluru (28%) leads, followed by Mumbai (19%), Delhi & Gurgaon. Tier 3 cities are also emerging.

#### Funding Trends: Private/Corporate funding (52.2%) dominates, followed by Seed/Angel (41.7%). Debt/Loan is negligible.

#### Boom & Decline: Peak in 2015–16 due to Startup India push; decline after 2017 as funding became selective.

#### Sector Leaders: Technology dominates, followed by Healthcare, Food, and E-Commerce.

#### Education: IIT & IIM founders lead, but dropouts also succeed.

#### Professional Background: Engineers & corporate professionals dominate; even teachers & academics are entering.

#### Age Factor: 20–39 years drive the ecosystem (74.3%). Some founders above 50 also succeed.

#### Gender: Men (60.7%) dominate; women-led startups only 9.9%. Mixed-gender teams (29.4%) are a positive sign.

####Customer & Revenue: B2B dominates; B2C has higher failures. Mixed models balance risk.

#### Survival: Startups typically survive ~10 years before scaling, exiting, or shutting down.

#### Outliers: Funding & investments show extreme outliers (few very high-funded startups).

#### Jewellery Sector: Highest average funding despite fewer startups.

#### Burn Rate: Agriculture has the highest burn; Tech is leaner.

#### Women-led Success: Strongest in Energy & Environment, Food & Hospitality, and Logistics & Travel.

## Future Scope

Build an interactive Power BI dashboard to visualize startup ecosystem trends.

Apply machine learning models to:

Predict startup survival chances.

Estimate funding success probability.

Identify factors influencing unicorn potential.

# Conclusion

The Indian startup story is one of ambition and resilience. From Bengaluru to Tier-3 cities, innovation is spreading beyond metros. Technology leads the way, but healthcare, food, and green sectors are quickly rising. Founders come from all walks of life—graduates, professionals, dropouts—proving success has no fixed formula. While many startups struggle to survive beyond 10 years, each failure fuels the next wave of ideas. With growing inclusivity and policy support, India’s startup ecosystem is set to shape not just businesses, but society itself.



