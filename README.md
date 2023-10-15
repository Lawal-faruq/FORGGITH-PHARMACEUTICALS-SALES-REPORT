# FORGGITH-PHARMACEUTICALS-SALES-REPORT

Forggith Pharmaceuticals, a fictional pharmaceutical manufacturing company based in Germany, is at the forefront of producing life-saving medical drugs. Their commitment to delivering high-quality pharmaceuticals is matched only by their dedication to strategic decision-making.

As a Power BI developer, I was entrusted with the task of crafting comprehensive Power BI reports that not only illuminate the current state of the company's operations but also serve as indispensable tools in shaping effective strategies and tactics. It's essential to note that the data utilized in these reports is entirely fictional, providing a simulated yet insightful representation of what Forggith Pharmaceuticals could extract from their actual operations.

This document outlines the key insights that Forggith Pharmaceuticals seeks to derive from this simulated data through the Power BI reports.

1.	**THE OVERVIEW PAGE** (Sliced by Year, Month, Quarter, Sales Team)
  * Total Revenue
  * Total Revenue YTD
  * Total Revenue SPLY
  * YOY Difference
  * Total Revenue by Year
  * YTD Revenue Progress
  * YTD Revenue by Product Categories
  * YOY difference by Sales Rep

2.	**THE EXECUTIVE REPORT** (Sliced by Year, Month, Quarter, Sales Team)
  * Total Quantity Sold
  * Total Target
  * Total Target Quantity
  * Total Revenue YTD VS Target YTD
  * Previous Year Revenue VS Previous Year Target
  * Total Revenue by Sales Channel
  * Total revenue by Product Class
  * Total revenue by Sub Channel
  * Top ten city by Revenue Generated
  * MOM Revenue growth %

3.	**THE PRODUCT REPORT** (Sliced by Year, Month, Product Category, Sales Team)
  * Total Transaction
  * Total Revenue & Total Target by Sales Rep
  * Total Revenue by Product Name
  * Total Revenue Vs Total Target
  * Total Quantity Sold Vs Total Target Quantity

# **Project Methodology**
Understanding the Dataset:

In undertaking this Power BI project for Forggith Pharmaceuticals, I adhered to a systematic methodology aimed at solving real-life data analysis challenges. The initial phase involved a comprehensive exploration of the dataset, wherein I meticulously deciphered the meaning of each column. This process culminated in the creation of a detailed data dictionary, providing a foundational understanding of the dataset's intricacies. The data dictionary image is shown below:

![Image 1](https://github.com/Lawal-faruq/FORGGITH-PHARMACEUTICALS-SALES-REPORT/assets/107109677/b466b172-7203-477c-af5b-748f9ece94fc)

# **Dashboard Design Blueprint** 

Having meticulously grasped the nuances of the dataset, traversing from the fact table to dimension tables, the next pivotal step in the project was to conceptualize the final dashboard. Armed with insights derived from the data, I translated ideas into a tangible form by crafting a detailed template. This process involved the humble yet effective tools of pen and paper, allowing for a visual representation that served as the guiding blueprint for the forthcoming Power BI dashboard.

![Image 2](https://github.com/Lawal-faruq/FORGGITH-PHARMACEUTICALS-SALES-REPORT/assets/107109677/d148a7f5-28b4-4cab-8b37-026c1e43a7f6)

# **Data Cleaning and Transformation**
With the dataset thoroughly understood and the dashboard design envisioned, the subsequent focus shifted to ensuring the data's integrity and relevance. Leveraging Power Query, I meticulously executed data cleaning and transformation processes, mitigating the risk of errors in subsequent stages.

A pivotal facet of the transformation centered on the Target table, a linchpin in our analysis. The current state of the Target data, as illustrated below, posed challenges to the depth of our insights. Consequently, strategic transformations were applied to elevate the data's quality, setting the stage for robust analysis and informed decision-making.

![Image 3](https://github.com/Lawal-faruq/FORGGITH-PHARMACEUTICALS-SALES-REPORT/assets/107109677/1aa71b23-66e7-4f96-beaa-dd891854f4c7)

Let's describe the first transformation step:

**Unpivoting for Enhanced Readability:**

The initial stride in refining the Target table involved a crucial transformation: unpivoting the year columns. This strategic move was instrumental in reshaping the data, fostering a more streamlined and accessible format. The resulting configuration not only enhances readability but also lays the groundwork for more dynamic and insightful analyses.

![Image 4](https://github.com/Lawal-faruq/FORGGITH-PHARMACEUTICALS-SALES-REPORT/assets/107109677/619c0d9d-9f5c-46d0-9381-34ab7bc5bb3f)

**Creating Date Columns:**

The journey to refine the Target table continued with a pivotal step—merging the month and year columns. This harmonious union resulted in the creation of a cohesive date column, lending temporal context to the dataset. Such a transformation not only enhances the structure of the data but also opens avenues for time-based analyses, enriching the depth of insights derived from the Power BI reports.

![Image 5](https://github.com/Lawal-faruq/FORGGITH-PHARMACEUTICALS-SALES-REPORT/assets/107109677/5993d8fa-414b-4285-880c-ab5fa289c4d7)

**Refining Datatypes:**

In the concluding phase of Target table transformation, meticulous attention was devoted to refining datatypes. Specifically, the month column underwent a transformation, transitioning into a date datatype. This final adjustment not only ensures data consistency but also aligns with the standardized format conducive to seamless integration within the Power BI framework.

![Image 6](https://github.com/Lawal-faruq/FORGGITH-PHARMACEUTICALS-SALES-REPORT/assets/107109677/040d007c-a3fb-4d99-a409-d13fb40f8bed)

# **Data Modeling:**

With the data now cleansed and transformed to its optimal state, the focus seamlessly transitions to the vital stage of data modeling. This phase involves the meticulous structuring of both fact and dimension tables, laying the foundation for a robust analytical framework.

The fact tables, brimming with essential transactional data, are intricately modeled to capture nuanced relationships and dependencies. Simultaneously, dimension tables, housing key descriptors, are shaped to provide context and granularity to the analysis.

This intricate interplay between fact and dimension tables serves as the bedrock upon which subsequent analyses and the final Power BI dashboard are constructed.

![Image 7](https://github.com/Lawal-faruq/FORGGITH-PHARMACEUTICALS-SALES-REPORT/assets/107109677/7d2caef5-07dc-401a-95cc-7e81762bc507)

# **Measures**
With the data meticulously modeled, the focus shifts to the creation of indispensable measures that form the quantitative backbone of the analysis. A comprehensive suite of measures is strategically devised, catering to the diverse analytical needs of the project.
From fundamental metrics such as total revenue to nuanced indicators like revenue Year-to-Date (YTD), each measure is thoughtfully constructed to distill actionable insights. This meticulous process not only ensures accuracy in reporting but also empowers stakeholders with the precise metrics crucial for strategic decision-making.

![Image 8](https://github.com/Lawal-faruq/FORGGITH-PHARMACEUTICALS-SALES-REPORT/assets/107109677/14c26b12-eef0-4bec-8fe8-9e6a92286907)

Then to analysis proper…

![Image 9](https://github.com/Lawal-faruq/FORGGITH-PHARMACEUTICALS-SALES-REPORT/assets/107109677/deaedf36-7d50-44ad-880c-800731d11970)

The culmination of the analysis reveals a panoramic view of Forggith Pharmaceuticals' performance. The total revenue across all years stands at a substantial $11.41 billion, with 2024 emerging as the most prosperous fiscal year. However, a notable observation surfaces as a 7.3% decline in revenue is noted between 2024 and 2025, signaling a pivotal aspect demanding strategic attention.

Key Highlights:
 * The product category wielding the highest revenue for the current year is Antiseptics, boasting a commendable total revenue of $532 million.
 * A standout performer in the sales team, Stella Given, demonstrates exceptional prowess, surpassing previous achievements.
This page serves as a valuable lens for external stakeholders, providing a comprehensive snapshot of Forggith Pharmaceuticals' business performance. The nuanced insights empower decision-makers to gauge the company's trajectory, identify areas of strength, and address challenges strategically.


Within the Executive Page, a nuanced exploration of revenue dynamics reveals compelling trends for Forggith Pharmaceuticals.
The foremost revenue generator is the Analgesics product category, boasting an impressive $2.31 billion, closely followed by Antiseptics, contributing significantly with $2.15 billion.
City-wise, Butzbach emerges as a standout revenue contributor, injecting a substantial $96 million into the company's financial stream.
The Pharmacy channel takes center stage in sales, commanding 52.9% of the market share.
To provide deeper insights, a dynamic tooltip enriches the Total Revenue by Sales Channel. This feature unveils the top three sales representatives, showcasing their individual revenue contributions. Additionally, a detailed breakdown of quantity sold by product name enhances understanding of sales performance.

This executive-level overview equips leadership with a comprehensive understanding of critical revenue drivers, facilitating strategic decision-making.
