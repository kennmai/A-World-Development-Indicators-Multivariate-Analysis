## A World Development Indicators Multivariate Analysis
*Contributors to this project include Maia Kennedy, Jordan Anderson, and Courtney Chen from the University of California, Berkeley*

![WB](https://github.com/user-attachments/assets/8103756e-9cae-40e3-b219-213cf0035f69)

This project investigates the World Bank - World Development Indicators to answer a major question: Is primary school enrollment linked to labor force participation and unemployment in low-, middle-, and high-income countries across genders?

**Project Overview:**
Each year, the World Bank updates their World Development Indicators, a dataset that spans over 217 economies measuring key indicators that allow analysis on the world scale. Insights are thematically based and include: poverty & inequality, people, environment, economy, states and markets, global links amongst others. This project investigates a niche area, merging the topics of youth labor, unemployment, gender equity and school enrollment, and its effects on poverty. We selected these variables because they intersect in ways that are critical for understanding how systemic inequalities affect social development and poverty alleviation efforts.

**Methodology and Approach:**
Using Python and fundamental data analysis techniques, we analyzed the WDI dataset to uncover relationships between the selected variables. The process involved:

* Data Wrangling: Cleaned and pre-processed data using Numpy, Pandas and other Python libraries to ensure the dataset was ready for analysis, handling missing values and standardizing the formats of the variables.
* Exploratory Data Analysis (EDA): Conducted visualization and descriptive statistics (e.g., histograms, scatter plots) using Matplotlib and Seaborn to understand the distribution and relationships between variables.
* Correlation and Multivariate Analysis: Applied correlation matrices to assess initial relationships and explore the interactions between primary school enrollment, labor force participation, and unemployment, controlling for income level and gender.
* Country Grouping: Analyzed the dataset by income group (low, middle, high) and gender to identify if different patterns exist across these dimensions, emphasizing their relevance in understanding inequality.

**Results and Insights:**
The analysis reveals that the relationship between **primary school enrollment** and **labor force participation** differs across income groups. In upper-middle and high-income countries, higher enrollment is associated with higher unemployment for both males and females. For most **female groups**, the relationship between school enrollment and labor force participation is negative, while for **males**, it tends to be neutral or positive. Notably, **school enrollment** shows a stronger correlation with labor force participation for **females** than for males, regardless of the direction of the relationship. These findings highlight the complex interplay between **education**, **labor markets**, and **economic development**, with income level playing a key role in shaping these dynamics.
