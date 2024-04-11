# Data Scientist

* * * *

## Education
**Cornell University (_August 2024_)**


Incoming MS in Information Systems with a concentration in Urban Tech student


**University of California, Berkeley (_May 2022_)**


B.A. Data Science and Economics

* * * *

## Professional Experience
### CSAA Insurance, an AAA Insurer
**Product Analyst (_July 2022 - Present_)**
- Developed AZ’s 3-year financial plan based on microeconomic trends, competitor activity, and historical KPI trends in Oracle Essbase
- Collaborated with actuaries and insurance agents to administer four premium rate changes for Auto & Property products
- Optimized territory factors by zip code to improve risk segmentation in pricing algorithm and mitigate adverse selection
- Unified logic for two disparate data warehouses by standardizing data querying in SQL and establishing framework to interpret results
- Leveraged unified logic to devise Power BI reports on consumer behaviors in digital sales, shared with senior PMs and external parters
- Migrated three monthly SAS reports to Snowflake cloud data warehouse using SQL, improving report efficiency and accessibility
- Identified $1.6M loss in direct written premium with four branch closures and presented findings to leadership
- Promoted from Product Analyst I to II in April 2023

**Product Management Intern (_Jun - Aug 2021_)**
- Researched prospects of electric vehicle insurance by assessing industry trends, competitor strategies, and government regulations
- Coordinated with claims analyst, actuaries, and product specialists to develop EV coverage geared towards company’s business needs
- Crafted short and long-term objectives of EV coverage as Minimum Viable Product (MVP), emphasizing growth opportunities 
- Presented elaborate business proposal to leadership, aligning with company’s 2030 growth and profitability vision

**Product Analyst Intern Intern (_May - Jul 2020_)**
- Conducted premium analysis to formulate CSAA’s competitive position against six market profiles and 53 companies in Maryland
- Investigated correlations between competitiveness and market share by zip code to uncover growth opportunities
- Presented competitive intelligence analysis to leadership to improve risk segmentation for future rate changes
- Assessed Auto and Property product dynamics by deriving cross elasticity of demand of Property rate change on Auto product retention

### Microfinance at Berkeley (_August 2019 - May 2020_)
- Led a team of four associates to accelerate growth for two local small businesses in retail and service industry 
- Designed an e-Commerce website prototype using Figma for retail business
- Developed detailed financial and marketing strategy to transform cafe’s patio space into an event venue 
- Navigated pandemic challenges by adjusting project timelines and transitioning to digital platforms to ensure achievement of objectives

### Tata Consultancy Services, Mumbai, India (_May - Jun 2019_)
- Employed Natural Language Toolkit (NLTK) models and functions for data cleaning and assigned attributes to semantic variables
- Assessed efficacy of Natural Language Processing (NLP) model in translating Spanish pharmaceutical descriptions to English 

### GetClarity Fintech Services, Mumbai, India (_May - Jun 2018_)
- Investigated correlation between text messages and propensity to loan default by data cleaning and conducting regression analysis on text messages of potential and current loans borrowers in Python using Randomized Control Trial analysis framework 

* * * *

## Data Management and Analytics Projects

## Current Projects

### Analysis of Bay Area Rapid Transit (BART) Ridership and Distance-Based Fare Model

**1. SQL Database of BART ridership and GTFS data** [_(Link)_](https://medium.com/@atmikapai/sql-database-for-bart-ridership-and-scheduling-data-8fadb40efc51)
- Constructed Extract-Transform-Load (ETL) pipeline to query, clean, and compile BART ridership data spanning 2001 to 2003 and 18 General Transit Specification Feed (GTFS) files and load into MySQL relational database (RDS) using Pandas, NumPy, and SQL
- Designed RDS schema through primary keys, foreign key constraints to establish relationships between the 19 tables in database
- Implemented reusable stored procedures in RDS schema to simplify data querying for temporal and geospatial ridership analysis 
- Deployed local database as Amazon Web Services RDS instance for automated backup and version maintenance

**2. A Journey Through BART Ridership Trends**
[_(Link)_](https://medium.com/@atmikapai/a-journey-through-bart-ridership-trends-5cfdd0819c0c)
- Dissected BART Ridership data from 1998 to Sep 2023, identified most popular stations pre and post-pandemic
- Evaluated post-pandemic ridership recovery by county using NumPy, Statsmodels

**3. BART’s Distance-Based Fare Model: Price and Income Elasticity of Demand** [_(Link)_](https://medium.com/@atmikapai/understanding-barts-distance-based-fare-model-d78751ca8454)
- Evaluated Price Elasticity of Demand (PED) for BART transit by exploiting natural experiment of 50% BART fare discount in Sep 2022; identified entry/exit routes with PED > 1 and formulated price reductions to engage ridership for those routes.
- Deterimined Income Elasticity of Demand for BART transit across counties and established nature and perception of transit service across Bay Area counties
- Analysis conducted in Python

**4. Forecasting BART's Ridership Trends using SARIMA and Prophet** [_(Link)_](https://medium.com/@atmikapai/forecasting-bart-ridership-sarmix-vs-prophet-8fdfae5f24bc)
- Leveraged Seasonal Autoregression Integrated Moving Average (SARIMA) and Prophet time-series forecasting models to forecast BART monthly weekday ridership till 2027
- Conducted forecasts on train and test set to evaluate model reliablity and accuracy
- Discovered ridership will not attain pre-pandemic levels till 2027

## Past Projects

### Effects of Selective Migration Policies on Student Emigration, Patenting in USA [_(Link)_](https://drive.google.com/file/d/118bfGKnELZRF4oGHpZtPU3rMLqZk8e_d/view)

- Researched history of visa programs (F-1, OPT-STEM, H1-B) to identify intervention period, treatment, and control groups
- Compiled dataset of student enrollment, graduates by major, and patents by patentor origin from accredited data repositories in R
- Leveraged Difference-in-Difference regression model with three intervention periods to capture impacts over time using STATA
- Discovered selective migration policies increased foreign student migration by 2.8 million, statistically significant at 1% 
- Identified no significant impact on U.S. patents; proposed data collection and inference approaches for future research
- Independently authored research paper, deepening research proficiency and statistical inference skills in R and STATA

### Empirical Investigation of Kuznets Environmental Model [_(Link)_](https://drive.google.com/file/d/12k7q0EfXI1s30T4mtamY6AXeOHi3ErKm/view?usp=sharing)
- Examined parabolic relationship between economic growth and environmental degradation as stipulated by Kuznet's Environmental model through linear regression analysis of log-transformed GDP and Environmental Performance Indicator (EPI) 
- Constructed panel dataset of 161 countries spanning 2007 to 2017 in R, leveraging World Bank dataset and Yale’s EPI dataset
- Tested for homoskedasticity, autocorrelation, and endogeneity to ensure OLS estimator was best linear unbiased estimator (BLUE) 
- Added time/entity fixed effects and two exogenous instrument variables to mitigate omitted variable and simultaneous causality bias
- Demonstrated through robust linear regression framework that contemporary empirical data supports Kuznet's Environmental model

### Effects of Stay-At-Home Mandates on COVID-19 Cases in USA [_(Link)_](https://drive.google.com/file/d/1pfOTcsmLRGOX9XDoZlF2-hBO46r8ue7u/view?usp=sharing)
- Bifurcated 3,143 US counties into treatment and control group based on COVID-19 government intervention stringency
- Employed OLS and WLS regression models to estimate impacts of strict quarantine mandates on COVID-19 cases using CDC dataset
- Assessed regression models’ performances across six intervention timeframes using RMSE and Choropleth library for map visualization
- Identified strict mandates had -3.3ppts impact on Covid-19 cases p.c. up till four months compared to lenient government interventions 

### Convolutional Neural Network (CNN) Classifier for Image Classification  [_(Link)_](https://github.com/atmikapai13/CS189/blob/main/cs189%20hw0.py)
- Engineered CNN model to classify diverse images from CIFAR-10 dataset using computer vision paradigm, PyTorch, and TensorFlow
- Extracted hierarchical and spatial image features using forward pass three-layer CNN and Rectified Linear Unit activation function
- Fine-tuned model hyper-parameters to optimize deep learning model, achieving 59.5% accuracy on test set

### Gaussian Classifier for Handwritten Digit Recognition  [_(Link)_](https://github.com/atmikapai13/CS189/blob/main/cs189%20hw0.py)
- Constructed classifier to categorize handwritten digits from MNIST dataset into numeric counterparts using Scipy and Scikit modules
- Leveraged Linear Discriminant Analysis for dimensionality reduction of pixel data to improve computational efficiency
- Modeled pixel value probabilities for different digit classes based on maximum likelihood estimation using Gaussian distributions
- Gaussian classifier achieved an accuracy of 81.7% on test set

### Cool Climate Networks [_(Link)_](https://coolclimate.berkeley.edu/)
- Created dashboards on transportation and climate change for climate action portal, EcoDataLab, using Python for data synthesis and Tableau for data visualizations

### Experiment Designer for Graduate Research 
- Selected as assistant to graduate researcher as part of UC Berkeley’s Undergraduate Student Researcher Mentoring program
- Tasked with designing survey experiment in English and Hindi to investigate belief adaption amid social media misinformation
- Crafted neutral questions to capture participants’ shifts in belief when responding to newspaper and Whatsapp chain messages in survey 
- Deployed survey experiment among friends and family in India to boost experiment participation and capture diverse perspectives

### Database Creation of Hawaiian Species’ Interactions 
- Selected as data migration assistant for UC Berkeley’s Essig Museum of Entomology
- Digitized Elwood Curtin Zimmerman’s 7 multivolume series on Hawaiian insect taxonomy in Microsoft Access
- Collaborated with four assistants to achieve project’s data management objectives ahead of schedule

* * * *

## Software Projects

###  Version Control System for Local File Management [_(Link)_](https://github.com/atmikapai13/CS61BL-Data-Structures/tree/main/Proj2%20-%20Gitlet)
- Constructed a version control system in Java to streamline local repository management, backup history views, and file restoration
- Utilized Java serialization to handle file object comprehension, and stored activity history within linked list and tree structures
- Conducted test cases for commit, branching, and merging functionalities, thereby ensuring integrity within version history

### Recreating 2048 Game [_(Link)_](https://github.com/atmikapai13/CS61BL-Data-Structures/tree/main/Proj0%20-%20Recreating%202048)
- Recreated 2048 game, a single-player computer game originally designed by Gabriele Cirulli in Java as part of CS61B: Data Structures coursework

### 2D Tile-Based World Generation and Exploration Game [_(Link)_](https://github.com/atmikapai13/CS61BL-Data-Structures/tree/main/Proj3%20-%20BYOW)
- Created a 2D tile-based game in Java in which user can explore and interact with objects in pseudorandomly simulated world
- Established classes, objects, and methods to define entities and user behaviors, leveraging object-oriented programming paradigm
- Developed immersive user interface in Java to enhance look and feel of 2D game engine

### Tower Defense Game [_(Link)_](https://github.com/atmikapai13/CS61A-Intro-to-Computer-Programs/tree/main/Proj3%20-%20Ants%20Vs.%20Zombies)
- Created a tower defense game, named called Ants Vs. Zombies using an object-oriented programming paradigm in Java 

### Scheme Interpreter [_(Link)_](https://github.com/atmikapai13/CS61A-Intro-to-Computer-Programs/tree/main/Proj3%20-%20Ants%20Vs.%20Zombies)
- Developed interpreter for a subset of Scheme language, integrating features like mathematical operations and user-defined procedures 
- Engineered interpreter’s evaluation mechanism to tokenize and parse Scheme code into abstract syntax tree (AST)
- Implemented tail call optimization to enhance performance and prevent stack overflow in recursive functions









