# Music Store Database Analysis - SQL Project

## Overview

This project demonstrates advanced SQL analysis techniques applied to a music store database. The analysis focuses on extracting actionable business insights from customer purchase patterns, sales trends, and inventory data to support data-driven decision making.

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

This project addresses several critical business questions through SQL analysis. The complete set of queries can be found in the <a href="https://github.com/ChowdharyYash/Project-1-/blob/main/analysis.sql">analysis.sql</a> file. Key areas of investigation include:

* **Genre Performance Analysis:** Identifying top-performing music genres by sales volume
* **Artist Popularity Metrics:** Determining which artists generate the most revenue
* **Song Purchase Patterns:** Analyzing individual track sales performance
* **Pricing Analysis:** Calculating average prices across different product categories
* **Geographic Sales Distribution:** Identifying key markets by country

## Key Findings

The analysis revealed several significant insights:

* **Genre Leadership:** Rock music dominates the sales charts, representing the highest revenue-generating genre
* **Top Artist:** Queens emerged as the most popular artist by total sales
* **Best-Selling Track:** "War Pigs" recorded the highest number of individual purchases
* **Pricing Strategy:** The average album price point is $1, indicating a competitive pricing model
* **Primary Market:** The United States represents the largest customer base by purchase volume

## Business Implications

Based on these findings, the following strategic recommendations can be made:

1. **Inventory Optimization:** Increase rock music inventory to meet demonstrated demand
2. **Artist Partnerships:** Develop promotional strategies featuring top-performing artists like Queens
3. **Geographic Focus:** Prioritize marketing efforts in the United States while exploring growth opportunities in emerging markets
4. **Pricing Review:** Consider testing price elasticity given the current low average price point

## Conclusion

This analysis demonstrates the power of SQL in extracting meaningful business insights from transactional data. The findings provide a clear roadmap for strategic decision-making in areas such as inventory management, marketing focus, and pricing strategies. By leveraging data-driven insights, the music store can optimize its operations and enhance customer satisfaction.

## Skills Demonstrated

* **SQL Proficiency:** Complex queries including JOINs, aggregations, subqueries, and CTEs
* **Data Analysis:** Statistical analysis and trend identification
* **Business Intelligence:** Translating data findings into actionable business recommendations
* **Database Design:** Understanding of relational database concepts and normalization
* **Problem Solving:** Structured approach to answering business questions with data

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
