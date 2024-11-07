# Data Scientist and Machine Learning Specialist

## Professional Summary

Data Scientist and Machine Learning Specialist with expertise in tech-sales, logistics, finance, and quantitative analysis. Currently pursuing a Master’s in Data Science and Machine
Learning. Certified Azure Data Scientist Associate. Skilled in Python, R, SQL, Microsoft Azure, Tableau, mathematics and statistics. Experienced in
data visualization and analysis to drive business decisions. Developed ML clustering projects for e-commerce customer segmentation and personal
deep learning projects on Kaggle for image classification and computer vision.

## Education

- **M.S., Data Science & Machine Learning** - Hellenic Open University (2023-present)
- **M.S., Logistics & Supply Chain Management** - Aristotle University of Thessaloniki (March 2017)
- **B.S., Economics** - Aristotle University of Thessaloniki (March 2015)

## Work Experience

### Data Scientist & ML Engineer, Freelancing (October 2023-Present)
- Developing and implementing machine learning clustering models for customer segmentation, optimizing marketing strategies and improving
  customer targeting for e-commerce companies.
- Participated in Kaggle competitions, creating deep learning models for label and image classification, and enhancing computer vision
  techniques, with projects available on my GitHub.

### SaaS B2B Sales & Strategy Analyst, Revenue Dpt @ Cyclopt (January 2022 - May 2024)
- **Data Analysis**: Leveraged data to drive sales strategy and client engagement.
- **Visualization**: Utilized Power BI to visualize sales metrics and generate insights.

### Account Manager, Sales Dpt @ Softweb Adaptive Solutions (May 2021 - January 2022)
- **Client Management**: Maintained and grew client relationships through data-informed strategies.

### Transportation Manager @ Makios Logistics (April 2018 - July 2019)
- **Operational Efficiency**: Implemented data-driven solutions to optimize logistics operations.

## Projects

### [Soil Data Clustering](https://github.com/AlexandrosPol/Data-Science-Projects/blob/main/Soil%20Types%20Identification%20Analysis/Soil%20Dataset%20-%20k%20means%20clustering.R)
- **Objective**: Performed k-means clustering on soil data from Northern Greece to identify distinct soil types, supporting optimized agricultural practices.
- **Tools**: R, KMeans Clustering, ggplot2, factoextra.
- **Process**:
  - **Data Cleaning**: Removed non-informative columns and handled missing values to ensure data quality.
  - **Data Transformation**: Scaled the data to standardize features, ensuring equal contribution in distance calculations for clustering.
  - **Modeling & Evaluation**:
    - Used the **Elbow Method** to identify the optimal number of clusters.
    - Applied the **Silhouette Method** to validate cluster cohesion and separation.
  - **Visualization**: Visualized clusters using ggplot2 and factoextra.
  - **Feature Reduction**: Tested clustering on a simplified dataset with key soil properties.
- **Result**: Identified three main soil clusters with clearer separation in the simplified dataset.

#### Elbow Plot
![Elbow Plot](images/Elbow%20Method%20for%20Choosing%20Optimal%20k.png)

#### Silhouette Score Plot
![Silhouette Plot](images/Average%20Silhouette%20Scores%20for%20Different%20k.png)

#### Cluster Plot
![Cluster Plot](images/Cluster%20plot.png)

#### Cluster Plot with Simplified Dataset
![Cluster Plot Simplified](images/Clustering%20with%20Simplified%20Dataset.png)

### [Country Visitation Pattern Mining with Apriori Algorithm](https://github.com/AlexandrosPol/Data-Science-Projects/blob/main/Countries%20Visitation%20Analysis/Countries%20Dataset%20-%20apriori%20algorithm.R)
- **Objective**: To explore frequent country visitation patterns using association rule mining. By uncovering relationships between commonly visited countries, this analysis offers insights for potential joint tourism promotion strategies.
- **Tools**:
  - **Language**: R
  - **Libraries**: `arules` for association rule mining
- **Dataset Overview**: A dataset of transactional country visitations, where each row represents a set of countries visited by a single traveler. The dataset includes 55 unique countries.
- **Process**:
  - **Data Preparation**: Loaded transactional data and inspected for frequently visited countries.
  - **Apriori Algorithm**: Applied with minimum support of 0.2 and confidence of 0.8.
  - **Parameter Tuning**: Adjusted support threshold iteratively to explore changes in rule generation.
  - **Rule Inspection**: Sorted by support to identify top patterns, like the association between Cyprus and Greece.
- **Modeling & Evaluation**:
  - **Key Findings**:
    - **Cyprus => Greece**: High likelihood of visiting Greece after Cyprus.
    - Rules with high support indicate common travel patterns, suggesting actionable insights.
  - **Parameter Tuning Visualization**:
    ![Support vs. Number of Rules Plot](images/Support%20vs.%20Number%20of%20Rules%20Plot.png)
- **Business Implications**:
  - **Tourism Strategy**: Joint tourism campaigns for Cyprus and Greece.
  - **Marketing Insights**: Promote culturally similar regions together for enhanced visitor experience.
- **Challenges and Improvements**:
  - **Challenges**: Parameter tuning to balance rule quantity and relevance.
  - **Future Improvements**: Explore other algorithms or finer threshold adjustments.
- **Conclusion**: This analysis highlights key visitation patterns, with actionable insights for tourism marketing in regions with frequent travel associations.

### [Abalone Age Prediction](https://github.com/AlexandrosPol/Data-Science-Projects/blob/main/Abalone%20Age%20Prediction/Abalone%20Dataset%20-%20linear%20regression%2Bpca.R)
Applied linear regression and principal component analysis (PCA) to predict the age of abalone from physical measurements.

### [Titanic Survival Prediction](https://github.com/AlexandrosPol/Data-Science-Projects/blob/main/Titanic%20Survival%20Prediction/Titanic%20Survival%20Prediction.ipynb)
Analyzing the Titanic dataset to predict survival rates using machine learning in Python. The project demonstrates data cleaning, exploratory data analysis, and the application of classification algorithms.

### [Card Deck - Image Classification](https://github.com/AlexandrosPol/Data-Science-Projects/blob/main/Card%20Deck%20-%20Image%20Classification%20with%20PyTorch/card-deck-image-classification-with-pytorch.ipynb)
This project involves classifying images of playing cards into their respective categories using deep learning. The dataset consists of images of playing cards, and the task is to correctly identify the rank and suit of each card. The project employs a convolutional neural network (CNN) implemented in PyTorch. The model is trained using a transfer learning approach with a pre-trained network from the timm library, specifically designed for image classification tasks.

### [Credit Card Fraud Detection](https://github.com/AlexandrosPol/Data-Science-Projects/tree/main/Credit%20Card%20Fraud%20Detection)
This project involves building a deep learning neural network to detect fraudulent transactions in credit card data. The dataset is highly imbalanced, so techniques like SMOTE are used to improve detection. The model achieves high accuracy and precision for both fraud and non-fraud cases.

### Skills and Technologies

- **Programming Languages:** Proficient in R for statistical analysis and predictive modeling. Additionally, skilled in Python with experience using Jupyter Notebook, NumPy, pandas, scikit-Learn, torch, torchvision, matplotlib, and seaborn for data manipulation and visualization.
- **Database Management:** Proficient in SQL, with certifications in PostgreSQL and experience using pgAdmin as a DBMS.
- **Data Visualization and Analysis Tools:**
  - Tableau Public Profile: [View my Tableau visualizations](https://public.tableau.com/app/profile/alexandros.polyzoidis/vizzes). A showcase of my ability to translate complex datasets into actionable insights through engaging visualizations.
  - Power BI: Utilized for sales metrics and client engagement insights.

### Certifications
- **15 Days of SQL: The Complete SQL Masterclass 2024**
  - Developed proficiency in using **PostgreSQL** and **pgAdmin** for database management and complex SQL queries.

- **Python A-Z™: Python For Data Science With Real Exercises!**
  - Gained hands-on experience with **Python** programming in **Jupyter Notebooks**, utilizing libraries like **NumPy**, **pandas**, **matplotlib**, and **seaborn** for data analysis and visualization.

- **R Programming A-Z™: R For Data Science With Real Exercises!**
  - Enhanced data analysis and statistical modeling skills using **R** in **RStudio**, implementing a variety of data manipulation and visualization techniques.

- **Tableau A-Z™**: Hands-On Tableau Training for Data Science**
  - Acquired expertise in Tableau for creating powerful data visualizations and dashboards to communicate data-driven findings.

- **Microsoft Certified: Azure Data Scientist Associate**:
  - Designing and creating a suitable working environment for data science workloads.
  - Exploring data.
  - Training machine learning models.
  - Implementing pipelines.
  - Running jobs to prepare for production.
  - Managing, deploying, and monitoring scalable machine learning solutions.
  
## Contact
Connect with me on [LinkedIn](https://www.linkedin.com/in/alexandrospolyzoidis/).
For collaboration or inquiries, email me at [apolyzoidis@hotmail.com](mailto:apolyzoidis@hotmail.com).

