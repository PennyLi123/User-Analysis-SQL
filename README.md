# User-Analysis
# Project Overview
Utilise SQL to assist a e-commerce toy product company in enhancing its business growth by performing user analysis.

# SQL skills used in this project
* Subqueriers
* Left Join
* Case when
* Group by
* Order by
* Distinct
* Temporary table
* Windows function

# Built with
* MySql workbench 

# Dataset Schema
Work with six related tables, which contain eCommerce data about:
• Website Activity
• Products
• Orders and Refunds

# Dataset Schema
<img src="https://github.com/PennyLi123/Sales-Analysis-SQL/blob/master/Schema.png" width="430">


# Query Result - User Analysis
### 1. How many of e-commerce website visitors come back to the website for another session?

<img src="https://github.com/PennyLi123/User-Analysis-SQL/blob/main/User%20Analysis%20Q1.jpg" width="150">



### 2. What is the minimum, maximum, and average time between the first and second session for customers who do come back?

<img src="https://github.com/PennyLi123/User-Analysis-SQL/blob/main/User%20Analysis%20Q2.jpg" width="390">


Repeat visitors are coming back about a month later, on average.

### 3. Which channels are repeat visitors come back through? If its all direct type-in, or if company paying for these customers with paid search ads multiple times.

<img src="https://github.com/PennyLi123/User-Analysis-SQL/blob/main/User%20Analysis%20Q3.jpg" width="250">


When customers come back for repeat visits, they come mainly through organic search, direct type-in, and paid brand.
Only about 1/3 come through a paid channel, and brand clicks are cheaper than non-brand. 
So all in all, company is not paying very much for these subsequent visits.

### 4. Comparison of conversion rates and revenue per session for repeat sessions vs new sessions.

<img src="https://github.com/PennyLi123/User-Analysis-SQL/blob/main/User%20Analysis%20Q4.jpg" width="330">


Repeat sessions are more likely to convert, and produce more revenue per session.






