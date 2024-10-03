# Data Vista Project Report

## Title: Data Vista: Sales Data Analysis and Visualization

### Project Statement
We aim to develop a comprehensive data analysis and visualization platform for sales data. This platform will provide actionable insights into sales performance, trends, and patterns through interactive and user-friendly visualizations. It will support detailed comparisons across products, regions, and time periods while also analyzing customer purchasing patterns based on their location. The ultimate goal is to empower businesses with deep insights and data-driven recommendations to enhance decision-making and drive growth.


**Dataset Link**: [Sales and Customer Dataset](https://www.kaggle.com/datasets/abhisinha8531/sales-and-customer-dataset)  
- Total number of rows in dataset: 1,000,000  
- Total number of columns in dataset: 28

  
### Expected Outcomes:
- **Enhanced Sales Insights**: Comprehensive understanding of sales performance and trends.
- **Improved Decision-Making**: Data-driven recommendations for strategic business decisions.
- **Optimized Sales Strategies**: Identification of high-performing products and regions.
- **Customer-Centric Approach**: In-depth analysis of customer behavior and preferences.
- **Increased Efficiency**: Streamlined reporting and visualization of complex sales data.
- **Predictive Analytics**: Forecasting future sales and identifying potential growth areas.
- **Scalability**: A platform capable of growing with the business and handling increasing data complexity.

### Project Undertaken under:
Infosys Springboard Summer Internship Program 4.0


## Table of Contents

- [Abstract](#abstract)
- [Project Timeline and Descriptions](#project-timeline-and-their-descriptions)
  - [Week 1: Project Initialization and Planning](#week-1-project-initialization-and-planning)
  - [Week 2: System Design and Initial Implementation](#week-2-system-design-and-initial-implementation)
  - [Data Preprocessing](#data-preprocessing)
  - [ER Diagram](#er-diagram)
  - [Week 3: Data Analysis Design and Implementation](#week-3-data-analysis-design-and-implementation)
  - [Technologies Used](#technologies-used)
  - [Week 4: Integration and Testing Phase I](#week-4-integration-and-testing-phase-i)
  - [Project Implementation Screenshots](#project-implementation-screenshots)
  - [Week 5: Advanced Analysis Features](#week-5-advanced-analysis-features)
  - [Week 6: Integration and Testing Phase II](#week-6-integration-and-testing-phase-ii)
  - [Approach Towards Adding Filters in Power BI](#approach-towards-adding-filters-in-power-bi)
  - [Role-Wise Dashboards](#role-wise-dashboards)
  - [Week 7: Visualization Design and Implementation](#week-7-visualization-design-and-implementation)
  - [Week 8: Final Testing and Deployment](#week-8-final-testing-and-deployment)
- [Deliverables](#deliverables)
- [Project Outcomes](#project-outcomes)
- [Key Achievements Using Power BI](#key-achievements-using-power-bi)
- [Conclusion](#conclusion)

---


## Project Timeline and Their Descriptions:

### Week 1: Project Initialization and Planning
- Understand project requirements and objectives.
- Conduct a competency gap analysis.
- Create a competency plan and define necessary actions.
- Understand the sequence of tasks.
- Set up the development environment with required tools.

### Week 2: System Design and Initial Implementation
- Design database tables (schema) for storing sales data.
- Implement database tables and test data entries.
- Implement basic frontend modules (e.g., basic data display).
- Implement data segmentation.

**Dataset Link**: [Sales and Customer Dataset](https://www.kaggle.com/datasets/abhisinha8531/sales-and-customer-dataset)  
- Total number of rows in dataset: 1,000,000  
- Total number of columns in dataset: 28  

### Data Preprocessing
- **Data Cleaning**:
  - Handling missing values by imputation (mean, median, mode) or removal.
  - Removing duplicates to ensure accurate analysis.
  - Converting data types for accurate analysis (dates, numbers, etc.).
- **Data Transformation**:
  - Manipulating date and time data for features like fiscal quarters, month, year, etc.
  - Normalization and scaling for improved model performance.
  - Feature engineering (e.g., calculating total sales, creating categorical features).
- **Outlier Detection and Handling**:
  - Detected and handled using statistical methods.
- **Data Integration**:
  - Merged sales data from multiple sources.
- **Data Aggregation and Summarization**:
  - Used to calculate total sales, trends, and patterns.
- **Data Validation and Quality Assurance**:
  - Automated checks for logical inconsistencies.

### ER Diagram

> [Space for ER diagram image]

### Week 3: Data Analysis Design and Implementation
- Designed dashboards for additional data analysis features.
- Enhanced frontend for better data representation.

### Technologies Used:
- **Amazon RDS**: For scalable, reliable data storage.
- **Power BI**: For cleaning, filtering, and creating interactive dashboards.
- **Flask**: For backend services.
- **Amazon EC2**: For computational power to run the application.

---

## Project Implementation Screenshots

> [Space for screenshots of welcome page, login page, and dashboards]

---

## Week 5: Advanced Analysis Features
- Implemented trend analysis, forecasting, and additional filters.

## Week 6: Integration and Testing Phase II
- Tested advanced analysis modules and frontend features.

### Approach Towards Adding Filters in Power BI:
1. **Creating a Slicer**:
   - Navigate to "Visualizations" > Slicer.
   - Drag relevant fields (e.g., Sale Date, Product).
2. **Connecting Slicer to Data**:
   - Ensure the slicer connects to the dataset.
3. **Adding Tabular Data Visualization**:
   - Add table visualization and drag necessary fields.
4. **Implementing Drill-Through**:
   - Right-click on data point > Drill Through > New Drill Through.
   - Filter based on slicer selection.
5. **Adding "See More" Functionality**:
   - Add button to navigate to the detailed view.
6. **Testing and Publishing**:
   - Test slicer filtering, drill-through, and publish the report.

### Role-Wise Dashboards:
- **Product Manager Dashboard**
- **Sales Manager Dashboard**
- **Product Team Dashboard**
- **Sales Team Dashboard**

---

## Week 8: Final Testing and Deployment
- Conducted system testing, fixed defects, and performed acceptance tests.

## Deliverables:
- Fully functional data analysis and visualization platform.

## Project Outcomes:
- Improved decision-making through data-driven insights.

## Key Achievements Using Power BI:
- Interactive, dynamic dashboards.
- Detailed analysis with drill-through and filters.

---

## Conclusion
The Data Vista project showcases the power of data visualization and analysis in driving business growth through strategic insights. By leveraging tools like Power BI, businesses can identify trends, optimize sales strategies, and make informed decisions.
