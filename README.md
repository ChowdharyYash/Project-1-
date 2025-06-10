# Music Store Database Analysis - SQL Project

## Overview

This project demonstrates advanced SQL analysis techniques applied to a music store database through 15 comprehensive queries. The analysis extracts actionable business insights from multiple data dimensions including sales transactions, customer behavior, product performance, and geographic distribution to support strategic decision-making and business growth.

## Project Objectives

The primary goal of this analysis is to provide comprehensive answers to key business questions that can guide strategic decisions for the music store's growth and optimization. Through systematic SQL queries, I've analyzed various aspects of the business including customer behavior, product performance, and geographical sales distribution.

## Installation and Setup

To replicate this analysis on your local machine, follow these steps:

### Prerequisites
- SQL database management system (PostgreSQL, MySQL, or similar)
- Database client tool (PgAdmin4, MySQL Workbench, or equivalent)

### Database Setup
1. Create a new database in your chosen DBMS
2. Execute the table creation scripts following the schema structure shown below
3. Import the CSV data files from the <a href="https://github.com/ChowdharyYash/Project-1-/tree/main/dataset">dataset directory</a>

**Important:** To maintain referential integrity, import the tables in the following order: artist → genre → album → track → customer → invoice → invoice_line → playlist → playlist_track.

## Database Schema

The database follows a normalized structure with clear relationships between entities. The schema diagram below illustrates the table relationships and key constraints:

![Schema Diagram](https://github.com/ChowdharyYash/Project-1-/blob/main/MusicDatabaseSchema.png)

## Technologies Used
* **Database Management System:** PostgreSQL
* **Database Administration Tool:** PgAdmin4
* **Query Language:** SQL

## Analysis Performed

This project comprises 15 comprehensive SQL queries that analyze multiple dimensions of the music store's business. The complete analysis can be found in the <a href="https://github.com/ChowdharyYash/Project-1-/blob/main/analysis.sql">analysis.sql</a> file. The queries are organized into the following categories:

### Employee & Organizational Analysis
* Senior employee identification for organizational hierarchy understanding
* Performance metrics by employee level

### Geographic & Market Analysis
* Invoice distribution by country to identify key markets
* City-level revenue analysis for strategic event planning
* Country-wise purchase patterns and preferences

### Customer Intelligence
* High-value customer identification and segmentation
* Customer spending patterns by artist and genre
* Geographic customer distribution analysis

### Product Performance Analysis
* Genre popularity metrics with focus on Rock music segment
* Artist performance rankings by track count and sales
* Individual track performance and popularity metrics
* Song length analysis for playlist optimization

### Financial Analytics
* Top invoice value identification
* Average pricing analysis by music genre
* Customer lifetime value calculations by country
* Revenue optimization opportunities

## Key Findings and Insights

The analysis yielded valuable insights across multiple business dimensions:

### Organizational Insights
* Identified senior-most employee based on organizational hierarchy for leadership structure understanding

### Market Performance
* Discovered top revenue-generating cities for targeted promotional events and music festivals
* Mapped invoice distribution across countries to identify primary and emerging markets
* Analyzed country-specific genre preferences for localized marketing strategies

### Customer Behavior
* Identified highest-value customers for VIP programs and retention strategies
* Analyzed customer spending patterns across different artists and genres
* Segmented rock music listeners for targeted genre-specific campaigns

### Product Insights
* Determined most popular artists by both track count and purchase volume
* Identified tracks exceeding average length for playlist curation
* Analyzed genre-wise pricing variations for pricing strategy optimization

### Revenue Optimization
* Located geographic concentrations of high-value transactions
* Identified cross-selling opportunities through customer-artist affinity analysis
* Discovered pricing patterns across different music genres

## Business Implications and Recommendations

Based on the comprehensive analysis, the following strategic initiatives are recommended:

### 1. Customer Relationship Management
* Implement VIP programs for high-value customers identified through spending analysis
* Develop personalized marketing campaigns based on customer-artist affinity data
* Create country-specific customer retention strategies

### 2. Geographic Expansion Strategy
* Host promotional events in cities with highest revenue concentration
* Tailor inventory to country-specific genre preferences
* Develop market entry strategies for high-potential underserved regions

### 3. Product Portfolio Optimization
* Expand rock music catalog based on demonstrated demand patterns
* Feature top-performing artists prominently in marketing materials
* Curate playlists based on song length analysis for different use cases

### 4. Revenue Enhancement
* Implement dynamic pricing strategies based on genre-specific price elasticity
* Develop artist-specific promotional bundles for high-affinity customers
* Focus sales efforts on countries and cities with highest transaction values

### 5. Operational Efficiency
* Align staffing decisions with organizational hierarchy insights
* Optimize inventory management based on purchase pattern analysis
* Streamline marketing spend allocation based on ROI by geography

## Technical Query Highlights

This project demonstrates proficiency in advanced SQL concepts through several complex queries:

### Window Functions Implementation (Query 10 & 11)
```sql
ROW_NUMBER() OVER(PARTITION BY customer.country ORDER BY COUNT(invoice_line.quantity) DESC)
```
Used for identifying top performers within each geographic segment

### Complex CTEs for Multi-Step Analysis (Query 9)
```sql
WITH best_selling_artist AS (...)
```
Demonstrates ability to break down complex problems into manageable components

### Multi-Table JOINs (Query 6-10)
Successfully joined up to 6 tables in a single query while maintaining query performance and readability

### Aggregate Functions with Business Logic (Query 14)
Combined financial calculations with formatting for business-ready output

## Conclusion

This analysis demonstrates the power of SQL in extracting meaningful business insights from transactional data. Through 15 comprehensive queries, the project provides a complete view of the music store's operations, from employee structure to customer behavior and financial performance. The findings offer a data-driven foundation for strategic decision-making across multiple business functions.

## Skills Demonstrated

### Technical Proficiencies
* **Advanced SQL Techniques:** 
  - Complex multi-table JOINs (up to 6 tables in single queries)
  - Common Table Expressions (CTEs) for modular query design
  - Window functions (ROW_NUMBER with PARTITION BY) for ranking analysis
  - Subqueries for filtering and conditional logic
  - Aggregate functions with GROUP BY for statistical analysis

* **Database Concepts:**
  - Understanding of relational database design and normalization
  - Efficient query optimization through proper JOIN sequences
  - Data type handling and string manipulation

### Analytical Capabilities
* **Business Intelligence:** Translating complex business questions into SQL queries
* **Data Analysis:** Statistical analysis including averages, rankings, and distributions
* **Strategic Thinking:** Converting data insights into actionable business recommendations
* **Problem Solving:** Systematic approach to multi-dimensional business problems

### Query Complexity Examples
* **Hierarchical Analysis:** Employee level-based queries
* **Geographic Segmentation:** Multi-level geographic analysis (country, city)
* **Customer Analytics:** Lifetime value and behavioral pattern analysis
* **Product Performance:** Multi-attribute product analysis
* **Financial Metrics:** Revenue calculations and pricing analysis

## Contributing

I welcome contributions to extend this analysis. To contribute:

1. Fork this repository
2. Create a new branch for your analysis
3. Submit a pull request with a clear description of your additions

For questions or issues, please refer to the <a href="https://github.com/ChowdharyYash/ChowdharyYash/issues/1">issues page</a>.

## Contact Information

- **GitHub:** <a href="https://github.com/ChowdharyYash">github.com/ChowdharyYash</a>
- **LinkedIn:** <a href="https://www.linkedin.com/in/yash2011/">linkedin.com/in/yash2011</a>

## Acknowledgments

This project was enhanced with insights from various SQL learning resources, including this comprehensive <a href="https://youtu.be/VFIuIjswMKM">tutorial on advanced SQL analysis techniques</a>.

## License

This project is available for educational and portfolio purposes. Feel free to use the queries and methodology for your own learning and analysis projects.

---

## Technical Stack

![postgresql](https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=amazondynamodb&logoColor=white)
![GitHub](https://img.shields.io/badge/github-%23121011.svg?style=for-the-badge&logo=github&logoColor=white)
