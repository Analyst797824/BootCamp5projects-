# Data Skills Bootcamp 

# Executive Summary
Across the duration of this programme, I have developed a comprehensive and strategically aligned skill set spanning data analysis, business intelligence, database management, cloud technologies, and Python‑based analytics. Each module contributed to building a robust capability in managing, interpreting, and operationalising data to support organisational decision‑making and long‑term business performance.

# Foundational Data Skills
During the initial phase, I established a strong foundation in data handling through Excel, SQL, and core analytical methodologies. This included structured approaches to:
- Data preparation
- Data transformation
- Quality assurance
with a strong emphasis on governance, compliance, and accuracy. I also strengthened my ability to communicate analytical insights clearly and concisely to senior stakeholders.

# Business Intelligence & Visualisation
The programme expanded into modern visualisation tools, including Tableau and Power BI, where I learned to convert raw datasets into meaningful dashboards and performance narratives. Through:
- Trend analysis
- Moving averages
- Visual storytelling
I developed the capability to highlight business patterns and support strategic planning across both commercial and public‑sector contexts.

# Databases & SQL
I deepened my understanding of relational databases and SQL, applying these principles to real‑world business scenarios. Key areas included:
- Designing database schemas
- Enforcing referential integrity
- Executing targeted queries
This reinforced the importance of disciplined data modelling and efficient query design to support operational and strategic objectives.

# Cloud Computing & Azure
The cloud computing module provided a strategic perspective on how platforms such as Microsoft Azure enable scalable, secure, and resilient data operations. Through hands‑on labs, I gained experience with:
- Data ingestion
- Data transformation
- Cloud storage
- Analytics services
I also learned to architect cloud‑based solutions that balance compliance, automation, and future scalability. Scenario‑based work strengthened my ability to translate business requirements into cloud architectures that support organisational growth.

# Python for Data Analysis
The Python module enhanced my technical proficiency in:
- Data manipulation
- Data exploration
- Data visualisation
using Pandas. I applied analytical logic to real‑world datasets, produced reproducible outputs, and automated elements of the analysis process. This reinforced Python’s role in modern business intelligence workflows and strengthened my ability to deliver structured, insight‑driven analysis.

# Conclusion
Collectively, this programme has significantly advanced my technical capability, analytical confidence, and strategic understanding of how data underpins effective decision‑making. I am now well equipped to contribute within a data‑driven organisation by:
- Delivering high‑quality analysis
- Designing scalable solutions
- Supporting operational and strategic objectives
- Producing robust, evidence‑based insights

# Week 1: Introduction to Data and Excel
Throughout this workbook, I strengthened my technical skills and analytical discipline across key data‑handling tools and methodologies. The exercises enabled me to practise structured techniques for data preparation, transformation, and interpretation using Excel, SQL, and visualisation methods.
I also learned to emphasise accuracy, governance, and compliance in data‑driven environments. Additionally, I improved my ability to distil complex analytical results into clear, concise insights for senior stakeholders, ensuring that recommendations are evidence‑based and commercially relevant.
This experience boosted my confidence in delivering high‑quality analysis, complying with regulatory standards, and communicating findings effectively in line with organisational expectations and professional best practices.
![week1_image](https://github.com/Analyst797824/BootCamp5projects-/blob/main/Screenshot%202%20WB1.png)

Both revenue and profit are going up every year. Revenue starts around $10M in 2017 and climbs to about $30M by 2021.
Profit starts around $4M and rises to roughly $13M over the same period.
There’s a small dip in revenue in 2019, but it picks up again strongly afterwards.
Profit keeps increasing steadily with no dips
The business is growing consistently, making more money and keeping more of it each year. Even when revenue slowed slightly in 2019, the overall trend stayed positive.

# Week 2: Introduction to Visual Tools — Tableau & Power BI
Over the course of this workbook, I strengthened my capability to work with modern data tools and analytical techniques while developing a structured, professional approach to interpreting and presenting insights.
The activities enabled me to apply Tableau, Excel, and Power BI in practical scenarios, reinforcing my ability to transform raw datasets into clear, meaningful outputs that support decision‑making. I also deepened my understanding of analytical methods such as:
- Trend analysis
- Moving averages
- Visual storytelling
These techniques helped me highlight performance patterns and guide strategic planning.
Beyond technical development, I gained a stronger awareness of how data informs organisational priorities—whether identifying market trends, understanding customer behaviour, or supporting public‑sector decision‑making. This week strengthened my communication skills and improved my readiness to contribute effectively in a data‑driven corporate environment.
![week2_image](https://github.com/Analyst797824/BootCamp5projects-/blob/main/Screenshot%208%20WB2.png)

Simple Summary of the Dashboard
Product 3 is the top performer in terms of sales — it brings in the highest average sales amount.
Products 1 and 2 also perform strongly, sitting just behind Product 3.
The remaining products generate much lower sales, with a noticeable drop after the top three.
Quantity Trend (Running Sum Line)
The running‑sum line shows how the total average quantity sold builds up as you move from Product 1 to Product 10.
Big jumps happen at Product 1, Product 2, and especially Product 3, showing these products sell in much higher quantities.
After Product 3, the increases are much smaller, meaning the other products contribute less to total quantity.
Big Picture
A small group of products — mainly Product 3, Product 1, and Product 2 — drive most of the sales and quantity. The rest contribute modestly.
![week2_image](https://github.com/Analyst797824/BootCamp5projects-/blob/main/Screenshot%2010%20WB2.png)

This dashboard compares actual sales to the target for each month in FY2018.
Top Summary Numbers
Sales: $6.09M
Target: $6.20M
Variance: –$103K (meaning sales were slightly below target)
Variance Margin: –1.67%
Monthly Charts
Each month shows two bars:
Light blue = Actual sales
Dark blue = Target
You can quickly see which months hit or missed the target.
In several months, sales are close to the target, but overall the year ends just below the goal.
Big Picture
The company performed almost on target, missing the yearly goal by a small amount. Monthly performance varies, but the gap is not large.
If you want, I can help you turn this into a clean insight for a report or portfolio.

# Week 3: Introduction to Databases and SQL
Throughout this workbook, I strengthened my understanding of core database concepts and enhanced my practical capability in applying SQL and relational database design principles to real business scenarios.
I worked through foundational topics including:
- Primary and foreign keys
- Data relationships
- Join operations
I also developed a structured approach to designing and implementing a functional database for a retail environment. This included translating business requirements into a logical schema, defining table structures, enforcing referential integrity, and using SQL to create, populate, and maintain a reliable data system.
The SQL practical tasks reinforced my ability to extract meaningful insights from large datasets using targeted queries. By working through real‑world scenarios—such as demographic analysis, population trends, and geographic filtering—I strengthened my ability to write efficient queries and align technical work with business objectives.
Overall, this week enhanced my technical proficiency, improved my confidence in SQL, and strengthened my ability to deliver actionable insights that support business performance and operational efficiency.
![week3_image](https://github.com/Analyst797824/BootCamp5projects-/blob/main/Screenshot%2011%20WB3.png)

Simple Summary of the ERD. 
This diagram shows how data is organised in a retail system — from buying stock to selling products to customers 
1. Suppliers & Purchases
The business buys products from Suppliers.
Each purchase is recorded in Purchase Transactions, which store the supplier, cost, quantity, and date.
2. Inventory
All products are stored in the Inventory table.
It includes product details like name, category, selling price, and stock levels.
Inventory links back to suppliers so you know who provided each product.
3. Sales
When a customer buys something, a Sales Transaction is created.
Each sale can have multiple items, which are stored in Sales Items (product, quantity, selling price).
4. Customers
Customers are tracked in the Customer table using a Loyalty Card Number.
Their details include name, contact info, date of birth, join date, and loyalty points.
 Big Picture
The system connects:
Suppliers → Purchases → Inventory → Sales → Customers This creates a full flow of information from stocking products to selling them and tracking customer activity.
If you want, I can also help you write a more formal explanation for a report or turn this into a narrative for your portfolio.

# Week 5: Fundamentals of Microsoft Azure
Throughout this workbook, I strengthened my understanding of cloud computing principles and developed a strategic perspective on how modern cloud platforms—particularly Microsoft Azure—support data‑driven operations.
The tasks enabled me to explore:
- Cloud service models (IaaS, PaaS, SaaS)
- Deployment options (public, private, hybrid, community)
- Regulatory considerations (GDPR, DPA 2018)
I deepened my knowledge of the practical benefits of cloud adoption, including scalability, cost efficiency, resilience, and improved collaboration.
Hands‑on Azure labs enhanced my technical capability in:
- Data ingestion
- Data transformation
- Cloud storage
- Analytics services
I also explored non‑relational data, analytics tooling, and services such as Azure SQL Database, Azure Blob Storage, Azure Data Factory, and Azure Synapse Analytics.
The “Paws & Whiskers” case study strengthened my ability to translate business requirements into a structured cloud architecture, considering security, automation, backup, and scalability.
Overall, this week improved my technical confidence and strategic understanding of cloud‑based data solutions, equipping me to design compliant architectures and support organisations in leveraging Azure for efficiency and insight generation.

![week5_image](https://github.com/Analyst797824/BootCamp5projects-/blob/main/Screenshot%2013%20WB5.png)

Full Summary of the Dashboard: 
This Power BI dashboard provides an overview of sales performance across product categories, quantities sold, and geographic regions. It brings together three key visuals to help understand what products are selling, how much is being sold, and where revenue is coming from 
1. Revenue by Category (Bar Chart)
This chart shows how much revenue each product category generates.
Categories like Caps, Cleaners, Decals, and others are compared side by side.
You can quickly see which categories bring in the most money and which ones contribute less.
 2. Quantity Sold by Category (Pie Chart)
This visual shows the percentage share of total quantity sold for each product category.
Categories such as Touring Bikes, Jerseys, Road Bikes, Mountain Bikes, etc., are displayed with both percentages and actual quantities.
It highlights which product types are most popular in terms of units sold, not revenue.
 3. Revenue by City (Map Visual)
This map shows where revenue is coming from geographically.
Cities across North America, Europe, and Asia are plotted.
Larger or darker markers indicate higher revenue, helping identify strong markets and regions with lower sales.
 4. Data Model (Right Panel)
The dashboard uses two tables:
orders (CustomerID, OrderDate, ProductID, Quantity, Revenue)
products (Category, ProductID, ProductName)
These tables are linked to allow category-level and product-level analysis.
  Overall Insight
The dashboard gives a well-rounded view of sales performance:
You see which categories earn the most revenue,
Which products sell the most units,
And which cities generate the highest revenue.
It’s a clean, multi‑angle snapshot of product performance and market distribution — ideal for identifying best‑selling categories, strong regions, and opportunities for improvement.

# Week 6: Introduction to Python for Data Analysis
Throughout this workbook, I strengthened my technical capabilities in Python programming, data manipulation, and analytical problem‑solving, while developing a structured, professional approach to working with real‑world datasets.
Using Pandas, I gained hands‑on experience in:
- Loading and exploring data
- Indexing and slicing
- Grouping and aggregation
- Advanced transformations
- Visualisation
The practical tasks involving the GDP dataset enhanced my confidence in extracting insights, validating assumptions, and visualising trends. I produced reproducible outputs and automated elements of the analysis process, reinforcing Python’s role in modern business intelligence workflows.
This week also helped refine my ability to work collaboratively, interpret structured exercises, and apply analytical thinking to unfamiliar datasets. The combination of coding practice, data exploration, and visualisation strengthened my appreciation for accuracy, clarity, and reproducibility in a professional data environment.
Overall, I am now more confident in using Python to prepare, analyse, and present data, and better equipped to support operational and strategic decision‑making through robust, well‑structured analysis.

![week6_image](https://github.com/Analyst797824/BootCamp5projects-/blob/main/Screenshot%202026-01-13%20195634%20wb%206.png)

Overview of the Dashboard. This Python-created dashboard gives a full picture of how 90 students performed overall, across classes, and by gender. It highlights key statistics, how marks are distributed, and where performance differences appear 
1. Overall Performance (Top Summary)
Total students: 90
Pass rate: 78.9%
Mean & Median: Both 71.34, showing the marks are fairly balanced around the middle.
This gives you a quick snapshot of how well the group performed as a whole.
2. Distribution of Marks (Top Left)
The histogram shows how marks are spread from low to high.
A red dashed line marks the pass threshold (60).
A green line marks the average score (71.34).
Most students score above the pass mark, and many cluster around the 70s.
This helps you see whether the class is struggling, average, or strong — in this case, mostly strong.
 3. Students per Class (Top Right)
Shows how many students are in Class A, B, and C.
Bars are split into Passed (green) and Failed (red).
You can instantly see which classes have more passes or more failures.
It’s a quick way to compare class performance.
 4. Mean Mark by Class & Gender (Bottom Heatmap)
Each cell shows the average mark for a specific class and gender.
Colour intensity shows performance:
Red = higher marks
Blue = lower marks
For example:
In Class B, males score higher than females.
In Class C, females score slightly higher.
This highlights performance differences across groups.
Big Picture
The dashboard shows:
Most students are performing well.
Pass rates are strong.
Some classes and genders perform differently.
Marks cluster around the 70s, with relatively few low scores.
It’s a clean, well‑designed view of student performance from multiple angles.

