---
title: "Fox Sports: Deep Dive"
date: 2025-02-16T16:17:10+20:00
tags: ["data engineering", "sports analytics", "ETL", "AWS", "Databricks"]
# hero: /images/posts/writing-posts/sports.jpg
description: Deep dive into my sexperience as a Senior Data Engineer at Fix Sports building the Sports Data Platform
theme: Toha
menu:
  sidebar:
    name: 'Fox Sports: Deep Dive'
    identifier: test_overview
    weight: 500
---


# **Fox Sports**
Senior Data Engineer, Sports Data Platform
New York

## **Abstract**
The Fox Sports Data Platform was built to process, enrich, and serve real-time/historical sports data for major leagues like the **NFL, MLB, and NBA**. The project involved **building a scalable ETL pipeline** capable of handling on average **1TB+ semi-structured data**, exposing insights via **low-latency APIs**, and integrating **AI-driven sports analytics** to enhance fan engagement, next gen stats for sportscasters and overall data visibility.

This deep dive covers:
- The **vision** behind the platform
- The **business and technical value**
- My **specific role and leadership contributions**
- **Challenges faced & how they were overcome**
- How this experience prepares me for engineering challenges at **startups** and large orgs alike

---

## **1️⃣ Vision**
**Why was this project initiated?**  
- The data products division @ Fox Sports ideated a **real-time, scalable sports data pipeline** for **live broadcasts, analytics, and AI-powered insights** (next-gen stats).  
- The existing system was **expensive, and difficult to scale both vertically and horizontally** with increasing demand.  
- We aimed to **reduce framework redundancy i.e. make it sport agnostic, streamline ETL workflows, improve query speeds, and enable real-time AI integration**.

---

## **2️⃣ Value: Business & Technical Impact**
### **📈 Business Value**
- **Faster Insights:** Enabled low-latency lookups for enriched **sports rankings, highly granular play-by-play data, player stats, and predictions** (*beta*).
<!-- - **API Optimization:** GraphQL APIs handling **10,000+ requests/day** improved response times by **50%**.
- **Cost Efficiency:** **Databricks optimizations reduced processing costs** by **20%**. -->

### **⚙️ Technological Impact**
- **Transitioned to Medallion Architecture (Bronze → Silver → Gold)** for efficient data processing.
- **Delta Lake adoption** enabled versioning, ACID transactions, and optimized query performance.
- **Integrated Generative AI (LLaMA3.1, Amazon Bedrock, Amzaon Polly)** for event summarization (in-point) and AI commentary.
- **Data Governance and visibility** was acheived through automated data dicitionary scripts as well as **Unity Catalog** for detailed lineage trackig
- **Databricks jobs** was utilized for orchestration and **MLflow** for expirement tracking, model promotion and registry, etc.

---

## **3️⃣ My Role**
### **🔹 Architecture & Tech Stack**
- **Built ETL Pipelines** using **PySpark, Spark SQL, and Pydantic** for structured data ingestion
- **Designed & Optimized Data Lakehouse** using **AWS S3, Databricks, and Delta Lake**
- **Developed GraphQL APIs** for **real-time query access**

[View on Eraser![](https://app.eraser.io/workspace/yU5IYX8PGwQAzCe855Fy/preview?elements=qfRjMXwdAEnOVqBlLC0n2g&type=embed)](https://app.eraser.io/workspace/yU5IYX8PGwQAzCe855Fy?elements=qfRjMXwdAEnOVqBlLC0n2g)

### **Why Medallion/Delta Lake**
Why did we choose Medallion or Delta Lake based Lakehouse arch *in this context*

#### Pros
#### Cons

### **🔹 Leadership & Ownership**
- **Led a team of 4 offshore engineers**, managing and delegating tasks via **Jira** and following a **Kanban** framework to keep track of tasks and bugs.
<!-- - **Collaborated with ML teams** to implement **metadata management for real-time predictions**. -->
- Collaborated with multiple stakeholders across the spectrum - **Software Engineers, Data Scientists, TPM's**, etc.
<!-- - **Worked cross-functionally with product managers and analysts** to align data requirements. -->
- **Mentored** junior developers and performed code reviews, pair porogramming, etc, for enhanced colloab between engineers.

---

## **4️⃣ Challenges**
### **🔹 Technical Challenges**
- **High-latency queries on 1TB+ datasets** → Solved using **Delta Lake partitioning and ElastiCache**.
- **Vendor APIs had inconsistent formats** → Standardized using **Pydantic data models**.
- **GraphQL APIs struggling under heavy traffic** → Implemented **query caching & pagination**.

### **🔹 Business & Leadership Challenges**
- **Aligning cross-functional teams (engineering, analytics, ML)** → Led **biweekly syncs & detailed documentation**.
- **Onboarding offshore engineers unfamiliar with sports analytics** → Created a **knowledge-sharing framework**.

---

## **5️⃣ Conclusion & Key Takeaways**
- **Handling Complex Scientific Data**: Just as sports data is **semi-structured and real-time**, so is **biomedical and cheminformatics data**.
- **Building Scalable Data Platforms**: Expertise in **Databricks, AWS, and Snowflake** applies directly to **Montai’s infrastructure needs**.
- **AI/ML Integration**: Experience with **LLMs and real-time analytics** will help **enhance scientific data processing**.
- **Built a scalable real-time sports data pipeline** for Fox Sports.
- **Optimized data processing, reduced costs, and improved API performance**.
- **Led cross-functional collaboration across engineering, ML, and product teams**.
- **Directly applicable skills for Montai: scalable ETL, cloud infrastructure, AI-driven data processing**.
---

📩 **[Contact me on LinkedIn](https://www.linkedin.com/in/vishnu-nagesh-kumar/)**  


<!-- ## **6️⃣ ** -->

