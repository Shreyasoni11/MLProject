# Instahyre Job Analysis - Machine Learning Project
The machine learning project involves scraping data from a professional networking platform called Instahyre using the Python library Beautiful Soup, selenium or a similar tool. The collected data was analyzed to provide insights using Python libraries, Pandas, NumPy, Seaborn, SQL, Excel and Power BI. The goal is to create a search bar where users can input skills such as Java, Python, or other relevant skills and predict the results by using different ML models. Here, best fit Classification models were used. Once a keyword is searched, the following information will be displayed: Most common experience level, Most common industry, Most common Company Class, Number of Jobs available.

<div align="center">
   <img src="https://github.com/Sidharthaagasti31/JOB_Analysis/assets/50338854/3afbe40e-c9e0-491d-8162-d7a15fc63009" alt="Data Analytics" width="300" height="200" >
</div>

## OBJECTIVE
This job analysis project aims to analyze and evaluate various job roles within an organization to gain insights into their responsibilities, skills, and qualifications. job analysis provides you with valuable insights that can inform your job search strategy, improve your application materials, and guide your career decisions. By utilizing job analysis information, you can present yourself as a strong candidate, align your career aspirations with suitable roles, and identify areas for professional development.

## TOOLS USED

<img src="https://github.com/Sidharthaagasti31/Sidharthaagasti31/assets/50338854/dc8316b6-70d3-416d-9910-cbf8fec92834" alt="excel" height=70 width=70 ><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/python/python-original.svg" alt="python" width="70" height="70"/> </a> <a href="https://scikit-learn.org/" target="_blank" rel="noreferrer">  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/mysql/mysql-original-wordmark.svg" alt="mysql" width="70" height="70"/> </a> <a href="https://pandas.pydata.org/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/2ae2a900d2f041da66e950e4d48052658d850630/icons/pandas/pandas-original.svg" alt="pandas" width="70" height="70"/> </a> <a href="https://pugjs.org" target="_blank" rel="noreferrer"> <img src="https://seaborn.pydata.org/_images/logo-mark-lightbg.svg" alt="seaborn" width="70" height="70"/> </a>  <img src="https://github.com/Sidharthaagasti31/Sidharthaagasti31/assets/50338854/fab946d7-1e30-4707-9a9e-8f7248dd5123" alt="power bi" width="40" height="70"/> 

## Key Features:

*Web Scraping:* The project includes a web scraping script that extracts job descriptions from [instahyre](https://www.instahyre.com/search-jobs/) job portals and websites. It collects relevant data such as job titles, responsibilities, skills, experience and other job-related information.

*Data Processing:* The extracted job data is processed and transformed using pandas and numpy libraries. The data is cleaned, structured, and prepared for analysis. This step ensures the data is in a suitable format for further exploration and modeling.

*Analysis and Insights:* The project utilizes exploratory data analysis, pandas-profileing techniques,power bi to gain insights into job trends, common skills, and qualifications. It includes statistical analysis, data visualization, and descriptive analytics to uncover patterns and relationships within the job data.

*Dashboard Visualization:* The project provides an interactive dashboard using Power BI. The dashboard presents key findings and visualizations, enabling users to explore and interact with the analyzed job data. It includes dynamic charts, filters, and drill-down capabilities to facilitate data exploration and decision-making.

## Project Structure:

The project is organized into the following components:

*Web Scraping Script:* Contains the Python script responsible for scraping job descriptions from various websites and job portals. It utilizes "Selenium" library for web scraping.

*Data Processing:* Includes Python scripts that process and clean the scraped job data. It utilizes pandas and numpy libraries for data manipulation and transformation.

*Exploratory Data Analysis:* Contains Jupyter notebooks or Python scripts that perform exploratory data analysis on the processed job data. It includes statistical analysis, data visualization, and feature engineering.

*Power BI Dashboard:* Provides the Power BI files that contain the interactive dashboard for visualizing the analyzed job data.

## Key Findings
![MY DASHBOARD](https://github.com/Sidharthaagasti31/JOB_Analysis/assets/50338854/ffc3265d-872d-4fea-90a8-3d2a1da5416e)

*Most In-Demand Skills:* Through the analysis of job descriptions, it was found that the most in-demand skills in IT sector are Java,Python,.NET,Angular programming And for NON IT sector its communication skills, and project management and sales . These skills consistently appeared as requirements in a significant number of job postings.

*Most In-Demand Jobs:* Through the analysis  it was found that the most in-demand jobs are Software engineer , Sales and business and Data Anlysis.

*Preferred Experience:* The analysis revealed that employers prioritize candidates are those having 2-5 year as preferred experiences.

*Trends in Job Titles:* The analysis revealed emerging job titles and roles that have gained prominence in recent years. Examples include Backend and fullend webdeveloper product managers etc. This indicates the evolving job market and the need for professionals with specialized skills in emerging fields.

*Trends Job Vacancy:* On analysing the data we got to know that most number of job vacancy are for data related jobs like data scientis and data analysi despite most demanding roles are siftware engineer and web developer.

*Geographical Patterns:* The analysis of job postings across different regions highlighted geographic variations in job requirements and skill preferences. For instance, IT and technology-related positions were more prevalent in Bangaluru and Hydrabad areas, while manufacturing roles were prominent in specific regions lilke Mumbai and Delhi.



### machine learning model:
After analysing data , created machine learning models used for predictions of number of job vacancies , size of company , designation of job and industry type from user input skills which then trained using various models which includes kmeans , and various classification models and saved before deploying the Streamlit web application. The model should take user-input skills and provide predictions for the number of jobs available, company size, industry type, and job designation. Model with best desired metrics was selected and integrated to webapp

![models](https://github.com/Shreyasoni11/MLProject/assets/136992653/03efa0a1-5b2b-490c-8a61-8239be5a1aac)


### created webapp:
After creating models and importing the models using pickle , created a webapp using Streamlit . Below is the snap of webapp.
![Web capture_28-8-2023_201925_localhost](https://github.com/Sidharthaagasti31/JOB_Analysis/assets/50338854/99cee3a6-8426-4527-a536-3c5b53d9c737)
 
## 🏥 Challenges and Learnings

**1. Feature Engineering:** Handled complex features, especially those with diverse and numerous categories. 

**2. Model Selection:**  Explored different ML models to identify the Best models.

**3. Hyperparameter Tunning:**  Hyperparameter tuning was time-consuming due to limited time for model development

**4. Model Deployment:**  Explored model deployment options.

 
## 🏥 Conclusion

In conclusion, the dynamic nature of the job market in India necessitates a deep and data-driven understanding of its evolving trends. Through this comprehensive project, we have endeavored to illuminate the intricate landscape of the Indian job market, leveraging rigorous analysis to identify and unravel key trends that influence its trajectory. The insights gleaned from this endeavor hold profound implications for job seekers, employers, and policymakers alike. Armed with an awareness of these trends, individuals can navigate their career paths with greater foresight, while organizations can refine their hiring strategies and workforce development initiatives to align with the shifting demands of the market.
