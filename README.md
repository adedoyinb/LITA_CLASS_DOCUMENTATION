# LITA_CLASS_DOCUMENTATION
##### A summmarised docummentation of my data analysis learning journew with LITA The incubator hub

## TABLE OF CONTENT

### [PROJECT TITLE](#project-title)

### [PROJECT OVERVIEW](#project-overview)

### [DATA SOURCES](#data-sources)

### [DATA FORMS](#data-forms)

### [TOOLS USED](#tools-used)

### [DATA CLEANING AND PREPARATION](#data-cleaning-and-preparation)

### [EXPLORATORY DATA ANALYSIS](#exploratory-data-analysis)

### [DATA ANALYSIS](#data-analysis)

### [DATA VISUALISATION](#data-visualisation)

---
## PROJECT TITLE: BASICS OF DATA ANALYSIS
---
### PROJECT OVERVIEW: This documentation takes you through the basic knowledge to be acquired to be an entry level data analyst. It focuses on explaining the key functions used needed to achieve basic goals in datat analysis such as data clean up, creation and visualisation and proper story telling or report. 
### WHAT IS DATA ANALYSIS?
- Data analysis involes the inspecting, cleanind, transformation and modelling data to discover new info, draw cocclusions and support decision making.

### DATA SOURCES
- Open source data
- Keggle
- nigerian bewries
- bshop enterprises

### DATA FORMS
- Structured data (Data in tabular form like spreadsheet or database)
- Semi structured data (XML and JSON files)
- Unstructured data ( No predefined format e.g media files, email)

### TOOLS USED
- Microsoft Excel - (Data entry, data cleanup and analysis)
- SQL- Standard Query Language (Data entry, data management and retrieval)
- Power bi- (Data visualisation and report)
- Github - (Data analyst Portfolio building)

### DATA CLEANING AND PREPARATION: After the entry or collection of data from whatever source, the first step in analysis is the cleanup of the data. This may involve the use of various functions in excel and SQL 
#### EXCEL FUNCTIONS FOR DATA CLEAN UP AND PREPARATION
- TRIM: Removes extra spaces from text, leaving only single spaces between words
- CLEAN: Removes non-printable characters from text
- LEFT, RIGHT, MID: Extracts parts of text from a cell (left, right, or middle).
- IF: Creates conditional logic to clean or categorize data.
E.G, =IF(A1>=50, "Pass", "Fail")
If A1 = 60, the formula returns "Pass".
If A1 = 45, the formula returns "Fail".

#### SQL QUERIES FOR DATA CLEAN UP AND PREPARATION 
- TRIM; Removes leading and trailing spaces from a string.
Example: SELECT TRIM(' Example '); returns 'Example'
- UPPER/LOWER; Converts text to uppercase or lowercase.
Example: SELECT UPPER('hello'); returns 'HELLO'.
Example: SELECT LOWER('HELLO'); returns 'hello'
- CASE WHEN; A conditional statement for handling different scenarios or values.
Example: SELECT CASE WHEN column = 'A' THEN 'Group 1' ELSE 'Group 2' END FROM table
---
### EXPLORATORY DATA ANALYSIS : Exploratory Data Analysis (EDA) is the process of investigating and summarizing datasets to discover patterns, trends, relationships, and anomalies, often before applying more complex statistical models. EDA involves both graphical and statistical techniques, helping analysts understand the data's underlying structure, spot errors, and gain insights that inform decision-making and further analysis.  
####  Pivot tables: the use of Pivot Tables in Excel is an essential part of Exploratory Data Analysis (EDA). Pivot tables help to quickly summarize, analyze, and explore large datasets by organizing and aggregating data in a flexible way, which is key to understanding trends, relationships, and patterns in the data. 
The image below is an example of a pivot table that has categorised the total sum of revenue from each region from a dataset 

![image](https://github.com/user-attachments/assets/233c43c8-d221-4b26-b2c7-5f5a287504f1) 

#### EDA in SQL is performed using various queries and techniques to explore and understand the data. some of the functions used include;
- IS NULL or IS NOT NULL: This condition is used to identify missing or null values in the data.
- COUNT(), SUM(), AVG(), MIN(), and MAX(): Functions like this help generate descriptive statistics it summarizes the data and get a high-level overview.
- GROUP BY: Functions like this are used for sorting and filtering to detect outliers. For example, finding the top or bottom values in a dataset can reveal outliers.
```sql
SELECT * FROM sales_data ORDER BY price DESC LIMIT 10;
```

### DATA VISUALISATION: Data visualization is the graphical representation of information and data. By using visual elements like charts, graphs, and maps, data visualization tools provide an accessible way to see and understand trends, outliers, and patterns in data. It helps stakeholders make informed decisions by turning complex data sets into visual insights that are easier to comprehend. 
#### IMPORTANCE OF DATA VISUALISATION 
- Improves Understanding: Makes complex data more accessible and easier to interpret.
- Helps detect trends and correlations that might not be evident in raw data.
- Enhances Decision-Making providing clear and compelling visuals.
- Increases Engagement
#### Achieving Data Visualization in Excel
Tools like Excel and Power bi are used for data visualisation
Excel provides Different types of Charts including bar charts, line charts, pie charts, scatter plots, and more that can be customized abd labelled.
Using Pivot Charts: Pivot charts are linked to pivot tables and allow for dynamic exploration of data. You can filter data interactively, which updates the chart automatically.
#### Achieving Data Visualization in Power BI
Power BI is a powerful business analytics tool that provides advanced data visualization capabilities
- Power BI allows you to connect to a wide variety of data sources (Excel files, databases, cloud services) for real-time analytics.
- Its dashboards are interactive, allowing users to click on visualizations to filter data and see details in real-time.
- Reports can be published to the Power BI service, making it easy to share insights across the organization.
- It can be configured to refresh data in real-time, ensuring users always have access to the latest information.

![image](https://github.com/user-attachments/assets/d58191ce-7970-48fa-b514-71be1108a38a) 
Image of a Power Bi chart

![image](https://github.com/user-attachments/assets/887fe853-2ed7-4ada-80be-7a6f6f83a115)
Imahe of an Excel chart
