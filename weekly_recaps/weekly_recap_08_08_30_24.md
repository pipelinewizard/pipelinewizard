Week 8: Learning Data Engineering in Public - Here's what I learned this week.

1. git reset HEAD~n: This command allows you to reset your commit history to a specific point while keeping your working directory intact, but it un-stages any changes that were staged previously. I found this incredibly useful when I accidentally tried to commit a .env file with over 8,000 files attached. Luckily this is fixed now.

2. postgis extension - PostGIS is a powerful spatial database extension for PostgreSQL that lets you store, query, and manipulate geographic and spatial data types. Last week, I thought I was done with the transformation stage of the NYC taxicab dataset. Turns out, I was wrong! I completely overlooked the start and end latitude/longitude fields in the ride table. You’d think I’d pay special attention to location data when working with a taxicab dataset, right? 🤭

3. ST_Contains function - This handy function in the postgis module allows you to check if one geometric point is contained within another. It proved invaluable when I was integrating NYC borough and neighborhood data into the database. Now I am able to see what borough and neighborhood the rider was picked up from and dropped off.

It’s hard to believe it’s already been 2 months on this journey—it feels like it’s flown by! Working with the NYC taxicab dataset has been incredibly educational, especially in terms of databases and SQL. Looking back, I wish I’d started working on personal projects like this sooner. Despite my confidence last week, I’m still in the transformation stage—guess I was a bit naive! 😂

Happy Friday!

I'll be back at it on Monday Morning!
https://lnkd.in/g-gENgjc
