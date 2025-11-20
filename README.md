![Banner](ZombieApocalypseScenario.png)

## Project Overview:

This project is a creative data analysis exercise built around a fictional scenario set in the year 2047. This a fictional, academic scenario. In this narrative, I served as the Lead Infectious Disease Data Analyst for the White House after the CDC sent over a dataset containing early information about a zombie outbreak. While the story is fictional, the analysis is completely real and demonstrates my ability to: Import and explore datasets, interpret and structure raw data, build effective visualizations, communicate insights to non-technical audiences, and work within a Jupyter Notebook analysis workflow

**What I learned:**
While going throught this project I developed my technical and communication skills to organize the data in a thoughtful way, and present it to stakeholders so they could understand the data and act accordingly. I worked closely with pandas and built my skills in understanding data types and missing values. I created multiple types of charts and when to use them. Overall this project, though fictional, reinforced my ability to turn raw data into clear insights to be used in making business decisions.

## Files and Program Used in This Project
**Python**
`/report.ipynb` + Main analysis notebook  
`/MOCK_DATA.csv` + Dataset provided for the scenario

## Methods & Workflow:
**1. Import the Dataset**
   
Loaded the CDC-provided data set `MOCK_DATA.csv` to begin exploration.

**2. Inspect the Data Structure**
   
Used the DataFrame `.info()` method to review: 
column types, null values, memory usage, and total rows/columns

**3. Organize the Data to Show the First Five Rows**

This provides leadership with a quick overview of the most urgent data.

![First Five Rows with Code](Code_FirstFiveRows.jpg)

**4. Organized the Data to Show Infection by State Into a Column Chart**

This helped to visualize which states had the most zombie infections.

![Infection by State](ByStateBarChart.jpg)

**5. Organized the Data to Show Infection by Gender Using a Pie Chart**

This helped to show how infections were distributed across genders.

![Infection by Gender](ByGenderPieChart.jpg)

**6. Organized the Data to Show Infected vs. Not Infected by Gender Into a Stacked Column Chart**
This helped to compared infection states within each gender.

![Infected vs. Not Infected](ByGenderColumn.jpg)

## Key Insights:
A. Some states had significantly higher infection activity, indicating early outbreak clusters.

B. Infection rates were relatively balanced across genders.

C. Stacked analysis helped identify which gender groups had higher non-infection counts, suggesting behavioral or exposure differences.
