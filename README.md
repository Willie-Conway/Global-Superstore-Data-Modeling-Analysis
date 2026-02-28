# 📊 Global Superstore: Data Modeling & Interactive Dashboard Project

<p float="left">
    <img src="https://images.credly.com/size/340x340/images/024324c7-4d4c-4008-8db7-01e0d4222126/image.png" width="300" />
    <img src="https://github.com/Willie-Conway/Global-Superstore-Data-Modeling-Analysis-Project/blob/2df0f711740b64bd36b15d1eeddbb0b02e27a607/Data%20Modeling%20Project/Data%20Modeling%20Project/Screenshots/Global%20Superstore.png" width="300" />
</p>

![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)
![Tableau](https://img.shields.io/badge/Tableau-E97627?style=for-the-badge&logo=tableau&logoColor=white)
![Data Modeling](https://img.shields.io/badge/Data_Modeling-FF6B6B?style=for-the-badge&logo=database&logoColor=white)
![Business Intelligence](https://img.shields.io/badge/Business_Intelligence-FF9E0F?style=for-the-badge)
![Interactive Dashboard](https://img.shields.io/badge/Interactive_Dashboard-008DE4?style=for-the-badge&logo=dash&logoColor=white)

## 🎯 Project Overview

<p float="left">
    <img src="https://github.com/Willie-Conway/Global-Superstore-Data-Modeling-Analysis-Project/blob/b6407dbc539e01b84efd39112e01c3ccc3082c06/Data%20Modeling%20Project/Data%20Modeling%20Project/Screenshots/Profits%20in%20USA.png" width="300" />
    <img src="https://github.com/Willie-Conway/Data-Modeling-and-Analysis-Project/blob/e45ff7c59a5656bdafc3684bd06aad7cd495aadd/Data%20Modeling%20Project/Data%20Modeling%20Project/Screenshots/Screenshot%202024-09-22%20225420.png" width="300" />
    <img src="https://github.com/Willie-Conway/Global-Superstore-Data-Modeling-Analysis-Project/blob/b6407dbc539e01b84efd39112e01c3ccc3082c06/Data%20Modeling%20Project/Data%20Modeling%20Project/Screenshots/Sales%20Trend%20in%20USA.png" width="300" />
    <img src="https://github.com/Willie-Conway/Global-Superstore-Data-Modeling-Analysis-Project/blob/b6407dbc539e01b84efd39112e01c3ccc3082c06/Data%20Modeling%20Project/Data%20Modeling%20Project/Screenshots/Sales%20in%20USA.png" width="300" />
    <img src="https://github.com/Willie-Conway/Global-Superstore-Data-Modeling-Analysis-Project/blob/b6407dbc539e01b84efd39112e01c3ccc3082c06/Data%20Modeling%20Project/Data%20Modeling%20Project/Screenshots/USA%20Sales%20and%20Profits.png" width="300" />
    <img src="https://github.com/Willie-Conway/Global-Superstore-Data-Modeling-Analysis-Project/blob/b6407dbc539e01b84efd39112e01c3ccc3082c06/Data%20Modeling%20Project/Data%20Modeling%20Project/Screenshots/Screenshot%202024-09-22%20230605.png" width="300" />
</p>

This comprehensive project demonstrates end-to-end data engineering and business intelligence skills through the design, implementation, and analysis of Global Superstore's retail data. As a Data Analyst, I transformed raw business data into a structured database system and created interactive dashboards for actionable business insights.



## 📊 Live Dashboard Demo

[![View Dashboard](https://img.shields.io/badge/📊_View_Interactive_Dashboard-667EEA?style=for-the-badge&logo=tableau&logoColor=white)](https://public.tableau.com/app/profile/willie.conway2396/viz/GlobalSuperStore_17308735736410/USASalesandProfits) ![Preview](https://img.shields.io/badge/Preview-F97316?style=for-the-badge&logo=tableau&logoColor=white)
![Global-Superstore-Data-Modeling-Analysis-Project](https://github.com/Willie-Conway/Global-Superstore-Data-Modeling-Analysis-Project/blob/0027ad2fb9a2b13dc070f3cc6531ce1cf9a780bc/Data%20Modeling%20Project/Data%20Modeling%20Project/Screenshots/USA%20Sales%20and%20Profit.gif)

## 📁 Project Structure

```
📂 Data-Modeling-and-Analysis-Project/
│
├── 📂 Data Modeling Project/
│   ├── 📂 CSV/
│   │   ├── Customers.csv
│   │   ├── Global_Superstore_DB.csv
│   │   ├── Location.csv
│   │   ├── Orders.csv
│   │   ├── Products.csv
│   │   ├── Sales.csv
│   │   └── Time.csv
│   │
│   ├── 📂 Charts/
│   │   ├── Profits_in_USA.twb
│   │   ├── Sales_Trend_in_USA.twb
│   │   ├── Sales_in_USA.twb
│   │   ├── Star Schema Diagram.drawio
│   │   └── USA_Sales_and_Profits.twb
│   │
│   ├── 📂 SQL/
│   │   ├── Customers.sql
│   │   ├── Location.sql
│   │   ├── Orders.sql
│   │   ├── Products.sql
│   │   ├── Sales.sql
│   │   └── Time.sql
│   │
│   ├── 📂 Screenshots/
│   │   ├── ER Diagram.png
│   │   ├── Data Model.png
│   │   ├── Star Schema Diagram.png
│   │   ├── Map chart.png
│   │   ├── Bubble chart.png
│   │   ├── Sales Trend chart.png
│   │   └── Interactive Dashboard.png
│   │
│   ├── Global_Superstore_DB.xlsx
│   ├── Global_Superstore_DB_Model.mwb
│   └── Global_Superstore_DB - Orders.csv
│
├── 📜 LICENSE
├── 📜 README.md
└── 📜 STATEMENTS.md
```

## 🔄 Project Workflow & Visualizations

### **Step 1: Entity-Relationship Diagram Design** 🗃️
- **Entities**: Orders, Customers, Time, Location, Sales, Products
- **Relationships**: Complete business process modeling
- **Normalization**: 3rd Normal Form (3NF) for optimal performance
- **Tools**: MySQL Workbench ER Modeling

### **Step 2: Database Implementation** 🖥️
- **Schema Creation**: Forward engineering from ER diagram
- **Table Implementation**: 6 main tables with proper constraints
- **Data Loading**: Structured CSV imports
- **Tools**: MySQL Workbench, SQL Scripts

### **Step 3: Star Schema Design** ⭐
- **Fact Table**: Sales (core metrics aggregation)
- **Dimension Tables**: Product, Location, Time (analytical contexts)
- **Optimization**: For OLAP and business intelligence queries
- **Tools**: Draw.io for schema visualization

### **Step 4: Geospatial Sales Analysis** 🗺️
- **Map Visualization**: State-level sales performance in USA
- **Color Encoding**: Sales intensity by region
- **Interactivity**: Drill-down capabilities
- **Tools**: Tableau Geographical Mapping

### **Step 5: Profit Analysis** 💰
- **Bubble Chart**: State-level profit visualization
- **Size Encoding**: Profit magnitude
- **Tooltips**: Additional metrics (quantity, shipping costs)
- **Insights**: Profitability patterns across regions

### **Step 6: Temporal Trend Analysis** 📈
- **Line Chart**: Sales trends over time
- **Filtering**: Focus on high-performing states (>$40K sales)
- **Pattern Recognition**: Seasonal trends and growth patterns
- **Forecasting**: Trend identification for planning

### **Step 7: Interactive Dashboard** 📊
- **Unified View**: Combined all visualizations
- **Cross-Filtering**: Click interactions across charts
- **Business Focus**: USA sales, profits, and trends
- **Decision Support**: Actionable insights for stakeholders

## 🔍 Key Business Insights

### **Geographical Performance Patterns**
- **Top States**: California, New York, Texas show highest sales volume
- **Profit Margins**: Western states demonstrate higher profitability ratios
- **Regional Clusters**: Clear geographical patterns in customer purchasing behavior

### **Temporal Trends**
- **Seasonality**: Q4 shows significant sales spikes (holiday season)
- **Growth Trajectory**: Consistent year-over-year growth in key regions
- **Pattern Consistency**: Repeating seasonal patterns across multiple years

### **Product Performance**
- **Category Analysis**: Technology products yield highest margins
- **Volume vs Profit**: Some high-volume products have lower profitability
- **Regional Preferences**: Product popularity varies by geography

### **Customer Insights**
- **Segment Performance**: Corporate segment shows highest order values
- **Geographic Concentration**: Customer density correlates with economic centers
- **Purchase Patterns**: Repeat customers show higher average order values

## 🛠️ Technical Skills Demonstrated

### **Database Engineering**
![MySQL](https://img.shields.io/badge/MySQL_Workbench-4479A1?style=for-the-badge&logo=mysql&logoColor=white)
![Data Modeling](https://img.shields.io/badge/Data_Modeling-FF6384?style=for-the-badge&logo=database&logoColor=white)
![ER Design](https://img.shields.io/badge/ER_Diagram_Design-27AE60?style=for-the-badge)
![Star Schema](https://img.shields.io/badge/Star_Schema-8E44AD?style=for-the-badge)
![Database Normalization](https://img.shields.io/badge/Database_Normalization-3498DB?style=for-the-badge)

### **Tableau Visualization**
- **Geospatial Mapping** with custom color schemes
- **Multi-Chart Dashboards** with synchronized filters
- **Bubble Charts** for multi-dimensional analysis
- **Time Series Analysis** with trend lines
- **Interactive Tooltips** for detailed exploration

### **Data Engineering Workflow**
- **Source to Schema**: Raw CSV to structured database
- **Model Optimization**: 3NF normalization for performance
- **Schema Evolution**: From ER to star schema
- **Data Validation**: Ensuring integrity through constraints
- **Export/Import**: Seamless data pipeline creation

## 📊 Data Dictionary

| Entity | Key Fields | Description | Type |
|--------|------------|-------------|------|
| **Customers** | CustomerID, Segment, Region | Customer demographic and segmentation | Dimension |
| **Products** | ProductID, Category, SubCategory | Product hierarchy and classification | Dimension |
| **Orders** | OrderID, OrderDate, ShipDate | Order transaction details | Fact |
| **Sales** | SalesID, Quantity, Sales, Profit | Financial transaction metrics | Fact |
| **Location** | LocationID, City, State, Country | Geographical hierarchy | Dimension |
| **Time** | TimeID, Year, Quarter, Month | Time dimension for analysis | Dimension |

## 🚀 Project Implementation Guide

### **For Database Engineers**
1. **Review ER Diagram**: Examine entity relationships and normalization
2. **Study SQL Scripts**: Analyze table creation and constraint implementation
3. **Evaluate Star Schema**: Understand analytical optimization choices

### **For Business Analysts**
1. **Explore Dashboard**: Use interactive filters for regional analysis
2. **Analyze Trends**: Identify seasonal patterns and growth opportunities
3. **Compare Metrics**: Evaluate sales vs profit across different dimensions

### **For Data Science Teams**
1. **Data Structure**: Understand the prepared data pipeline
2. **Analysis Foundation**: Build upon the existing star schema
3. **Visualization Templates**: Reuse Tableau workbook structures

## 🏆 Project Achievements

✅ **Complete Database Design** from conceptual to physical model  
✅ **Dual Schema Implementation** (3NF + Star Schema) for different use cases  
✅ **4 Interactive Visualizations** with business context  
✅ **Unified Dashboard** with cross-filtering capabilities  
✅ **End-to-End Workflow** from raw data to business insights  
✅ **Professional Documentation** with implementation guide  

## 📋 Technical Specifications

### **Database Requirements**
- MySQL Workbench 8.0+
- SQL execution privileges
- 500MB+ storage for sample data

### **Visualization Requirements**
- Tableau Desktop or Tableau Public
- Web browser for demo video
- Screen resolution: 1920x1080 recommended

### **Data Characteristics**
- **Time Period**: Multi-year retail data
- **Geography**: Primarily USA with global context
- **Volume**: ~50,000 transactions
- **Dimensions**: 6 primary business entities

## 📝 Methodology

1. **Requirement Analysis**
   - Business use case understanding
   - Stakeholder needs assessment
   - Success criteria definition

2. **Conceptual Design**
   - Entity identification
   - Relationship mapping
   - ER diagram creation

3. **Logical Design**
   - Attribute definition
   - Normalization application
   - Schema optimization

4. **Physical Implementation**
   - SQL script generation
   - Table creation
   - Data population

5. **Analytical Layer**
   - Star schema design
   - Query optimization
   - View creation

6. **Visualization Development**
   - Chart type selection
   - Dashboard layout
   - Interactivity implementation

## 🎨 Design Philosophy

### **Database Design Principles**
- **Normalization**: Balance between performance and flexibility
- **Scalability**: Structure supporting future growth
- **Maintainability**: Clear naming conventions and documentation

### **Visualization Best Practices**
- **Color Theory**: Meaningful color encoding
- **Information Hierarchy**: Primary → Secondary → Tertiary focus
- **User Experience**: Intuitive interactions and navigation

### **Dashboard Composition**
- **Logical Grouping**: Related metrics positioned together
- **Progressive Disclosure**: Details available on demand
- **Mobile Responsiveness**: Considerations for different devices

## 🔗 Related Resources

- [MySQL Documentation](https://dev.mysql.com/doc/)
- [Tableau Learning Resources](https://www.tableau.com/learn)
- [Data Modeling Best Practices](https://www.ibm.com/topics/data-modeling)
- [Business Intelligence Guide](https://www.gartner.com/en/information-technology/glossary/business-intelligence-bi)

## 👥 Acknowledgments

- **Global Superstore** dataset providers
- **MySQL** development team for robust database tools
- **Tableau** for powerful visualization capabilities
- **Educational Institutions** supporting data engineering curriculum

## 📄 License

This project is licensed under the **MIT License** - see the [LICENSE](LICENSE) file for details. The dataset is fictional and created for educational purposes.

---

⭐ **This project demonstrates comprehensive data engineering and BI skills. Feedback welcome!** ⭐

*Project Completed: September 22, 2024*
*Last Updated: January 28, 2025*
