Week 9: Learning Data Engineering in Public - Here's what I learned this week.

1. INSERT Statement: This SQL command allows you to insert data into a PostgreSQL table by specifying the columns you want to populate. This week, I used it to insert location data from a reference table into my target table.

2. UNION Statement: The UNION operator in SQL enables you to combine data from multiple tables into a single result set, similar to the append function in Power BI. I applied this to consolidate location data from all my reference tables into a single dimension (DIM) table, including data for Boroughs, Counties, Cities, and more.

3. \copy Command (PostgreSQL Extension): The \copy command is a PostgreSQL-specific utility that allows you to copy data from a CSV file into a PostgreSQL table. I encountered an issue with the Connecticut municipality table, which lacked a column specifying the type of municipality. To work around this, I sourced the information from Wikipedia, loaded it into a CSV, and then used \copy to import it into PostgreSQL.

It's been over two months, and I'm still going strong. Each week brings new challenges and insights. Admittedly, this week was a bit shorter since my little one was under the weather, but I still managed to accomplish some key tasks. I'm currently in the transformation phase of my work with the NYC taxicab dataset. For now, I'm working with a single table containing 66,000 rows and running the pipeline locally. The full dataset consists of 12 Parquet tables.

Happy Friday!

I'll be back at it on Tuesday Morning!

Have a great Labor Day Weekend!