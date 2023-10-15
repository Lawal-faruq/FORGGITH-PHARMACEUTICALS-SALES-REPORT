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
