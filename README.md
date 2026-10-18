
# Robot Installation Analytics | Power BI Dashboard

### Dashboard Overview

![Robot Installation Dashboard Overview](./screenshots/Robot%20Installation%20Dashboard%20Overview.png)

![Power BI](https://img.shields.io/badge/Power%20BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)
![Power Query](https://img.shields.io/badge/Power%20Query-0078D4?style=for-the-badge&logo=microsoft&logoColor=white)
![DAX](https://img.shields.io/badge/DAX-339933?style=for-the-badge&logo=microsoft&logoColor=white)

An interactive **Microsoft Power BI dashboard** for analyzing robot installations across geographical locations, customers, robot types, controller types, and industrial applications.

This project demonstrates practical skills in data preparation, data modeling, DAX calculations, KPI reporting, and interactive business intelligence dashboard development.

> **Portfolio project:** The repository presents the dashboard's capabilities and analytical approach. The underlying installation dataset and Power BI report file are not included because they are not available for public distribution.

## 1. Project Overview

The Robot Installation Analytics Dashboard was developed to provide a consolidated view of robot installation data across multiple locations, customers, and industrial applications.

The dashboard enables users to explore installation quantities through KPI cards, charts, and interactive image-based filtering. Selecting an industrial application, such as Arc Welding, Spot Welding, Handling, Painting filters the relevant visuals to support focused analysis.

The project demonstrates how Power BI can transform structured installation data into an interactive reporting experience for business analysis and decision support.

## 2. Business Objectives

The dashboard was designed to help users:

- Monitor the total number of installed robot units.
- Understand the number of customers represented in the data.
- Compare installations across geographical locations.
- Analyze installations by robot type and controller type.
- Evaluate the distribution of installations across industrial applications.
- Compare robot installation quantities across individual customers.
- Explore application-specific data through interactive image-based filtering.

## 3. Dashboard Preview

### Application-Based Filtering: Arc Welding

![Arc Welding Application Filter](./screenshots/Arc%20Welding%20Application%20Filter.png)

### Customer Specific Filer

![Customer Based Installation Analysis](./screenshots/Customer%20Specific%20Filter.png)

## 4. Key Dashboard Features

### 4.1 KPI Cards

**Total Units**
- Displays the total number of installed robot units represented in the report.

**Count of Customers**
- Displays the number of customers represented in the dashboard.

These KPIs provide a high-level summary of the installation data.

### 4.2 Location-Wise Installation Analysis

Analyzes robot installation quantities across the following locations:

- Gurgaon
- Pune
- Chennai
- Bangalore
- Gujarat

This view supports geographical comparisons and helps identify locations with higher installation volumes.

### 4.3 Robot Type Analysis

Displays the distribution of installed robots by robot type.

The visual helps users compare installation quantities across different robot types and understand their representation in the dataset.

### 4.4 Controller Type Analysis

Shows the distribution of installed robots by controller type.

This enables users to explore the composition of installations across controller categories.

### 4.5 Industrial Application Analysis

The dashboard includes:

- An application-wise pie chart showing the distribution of installations.
- Application-wise quantity visuals for comparing installation volumes across applications.
- Image-based application selection for focused analysis.

**Arc Welding** is one of the applications represented in the dashboard.

### 4.6 Customer-Wise Installation Analysis

Displays robot installation quantities for individual customers.

This view supports comparisons of installation volumes across customers.

Customer-level examples are not reproduced here because the underlying installation records are not being published.

### 4.7 Interactive Image-Based Filtering

The dashboard includes application images that users can select to filter the report.

For example, selecting the **Arc Welding** image filters the relevant KPI cards, charts, and other data visuals to the selected application.

This interaction provides an intuitive way to explore application-specific installation data without relying exclusively on conventional slicers or dropdowns.

## 5. Business Questions Answered

The dashboard supports analysis of questions such as:

1. How many robot units are represented in the installation data?
2. How many customers are represented in the report?
3. How are installations distributed across locations?
4. Which robot types account for the installation quantities?
5. How are installations distributed by controller type?
6. How do installation quantities vary across industrial applications?
7. How do installation volumes compare across customers?
8. How does the installation profile change when a specific application, such as Arc Welding, is selected?

These questions help users explore installation patterns and compare different dimensions of the available data.

## 6. Analytical Observations

The dashboard analysis highlights the following areas of interest:

- **Top Region:** **Gurgaon** *leads total deployment volume.*
- **Leading Robot:** **AR1440** *accounts for the highest installation share.*
- **Dominant Application:** **Arc Welding** *represents approximately half of the analyzed applications.*

Arc Welding was reported as representing approximately 50% in the project analysis. This figure should be interpreted as a share of the analyzed installation data only if that is what the underlying calculation measures. It should not be described as an industry-wide market share without independent market data.

These observations describe the current analysis and should not be interpreted as conclusions about the entire robotics market.

## 7. Technical Implementation

### Data Preparation and Cleaning

Power Query was used for data preparation and cleaning.

The transformation process prepared the data for analysis within Power BI. Specific cleaning operations are not listed individually because only the confirmed use of Power Query and data cleaning is documented here.

### Data Modeling

Data modeling and relationships were implemented to support analysis across the relevant dimensions of the installation data.

### DAX Calculations

DAX measures and calculated columns were used in the project.

The dashboard includes KPI cards for Total Units and Count of Customers. Exact DAX formulas are not included because the formulas have not been documented in this repository.

### Interactive Reporting

The dashboard uses interactive visualizations and image-based application filtering to let users explore different subsets of the installation data.

Selecting an application updates the relevant visuals according to the selected filter.

## 8. Tools and Technologies

| Technology | Application |
|---|---|
| Microsoft Power BI | Dashboard development and data visualization |
| Power Query | Data preparation and cleaning |
| DAX | Measures and calculated columns |
| Data modeling | Relationships and analytical structure |
| Interactive visualizations | Exploring installation data across multiple dimensions |

## 9. Skills Demonstrated

This project demonstrates practical experience with:

- Power BI dashboard development
- Power Query data preparation and cleaning
- DAX measures and calculated columns
- Data modeling and relationships
- KPI reporting
- Data visualization and comparative analysis
- Customer-wise and location-wise analysis
- Industrial application analysis
- Interactive image-based filtering
- Translating business questions into analytical dashboard views

These skills are relevant to Data Analyst, Power BI Developer, and Business Intelligence Analyst roles.

## 10. Business Value

The dashboard provides a consolidated way to explore robot installation data and compare installation quantities across multiple dimensions.

Potential business uses include:

- Reviewing geographical installation distribution.
- Comparing customer-level installation volumes.
- Understanding the distribution of robot and controller types.
- Examining the relative representation of industrial applications.
- Exploring application-specific installation data interactively.

These are intended analytical uses of the dashboard, not claims of measured financial impact or operational improvement.

## 11. How to Explore the Project

The repository provides documentation and screenshots illustrating the dashboard's design and functionality.

To explore the project:

1. Review the dashboard overview screenshot.
2. Examine the installation analysis across locations, customers, robot types, and controller types.
3. Review the Arc Welding filtered-view screenshot to understand the interactive filtering behavior.
4. Read the technical implementation section to understand the Power Query, DAX, and data modeling techniques used.

The Power BI file and underlying Excel dataset are not included in this public repository. Therefore, the report cannot be opened or interacted with directly from GitHub.

## 12. Repository Structure

```text
robot-installation-power-bi-dashboard/
├── README.md
└── screenshots/
    ├── dashboard-overview.png
    ├── arc-welding-filter.png
    └── customer-analysis-details.png
```

The `screenshots/` directory contains the screenshots used in this README.

The Power BI report and source dataset are intentionally excluded from the public repository.

## 13. Future Enhancements

Possible enhancements for a future version or a separate copy of the dashboard include:

- Introducing additional KPIs where supported by the data.
- Adding drill-through pages for detailed customer or application analysis.
- Improving navigation and analytical guidance for report users.
- Adding a geographical map if the available location data supports meaningful mapping.

These are potential future improvements and are not represented as completed features of the current dashboard.

---

**Note:** *The underlying dataset and Power BI (.pbix) file are proprietary and excluded from this public repository. This README and the accompanying screenshots demonstrate my dashboard design, data modeling, and reporting capabilities.*

