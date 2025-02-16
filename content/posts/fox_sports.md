---
title: "Fox Sports: Deep Dive (Senior Data Engineer)"
date: 2025-02-16T16:17:10+20:00
tags: ["data engineering", "sports analytics", "ETL", "AWS", "Databricks"]
# hero: /images/posts/writing-posts/analytics.svg
description: Deep dive into my sexperience as a Senior Data Engineer at Fix Sports building the Sports Data Platform
theme: Toha
menu:
  sidebar:
    name: test_sidebar
    identifier: test_overview
    weight: 500
---


# **Fox Sports: Deep Dive (Senior Data Engineer, Sports Data Platform)**

## **Abstract**
The Fox Sports Data Platform was built to process, enrich, and serve real-time sports data for major leagues like the **NFL, MLB, and NBA**. The project involved **building a scalable ETL pipeline** capable of handling **1TB+ semi-structured data**, exposing insights via **low-latency GraphQL APIs**, and integrating **AI-driven sports analytics** to enhance fan engagement.

This deep dive covers:
- The **vision** behind the platform
- The **business and technical value**
- My **specific role and leadership contributions**
- **Challenges faced & how they were overcome**
- How this experience prepares me for challenges at **Montai Therapeutics**

---

## **1️⃣ Vision**
**Why was this project initiated?**  
- Fox Sports wanted a **real-time, scalable sports data pipeline** for **live broadcasts, analytics, and AI-powered insights**.  
- The existing system was **slow, expensive, and difficult to scale** with increasing demand.  
- We aimed to **streamline ETL workflows, improve query speeds, and enable real-time AI integration**.

---

## **2️⃣ Value: Business & Technical Impact**
### **📈 Business Value**
- **Faster Insights:** Enabled real-time **sports rankings, player stats, and predictions**.
- **API Optimization:** GraphQL APIs handling **10,000+ requests/day** improved response times by **50%**.
- **Cost Efficiency:** **Databricks optimizations reduced processing costs** by **20%**.

### **⚙️ Technological Impact**
- **Transitioned to Medallion Architecture (Bronze → Silver → Gold)** for efficient data processing.
- **Delta Lake adoption** enabled versioning, ACID transactions, and optimized query performance.
- **Integrated Generative AI (LLaMA2, Amazon Bedrock)** for automated analysis.

---

## **3️⃣ My Role**
### **🔹 Architecture & Tech Stack**
- **Built ETL Pipelines** using **PySpark, Spark SQL, and Pydantic** for structured data ingestion.
- **Designed & Optimized Data Lakehouse** using **AWS S3, Databricks, and Delta Lake**.
- **Developed GraphQL APIs** for **real-time query access**.

### **🔹 Leadership & Ownership**
- **Led a team of 4 offshore engineers**, managing tasks via **Kanban & Jira**.
- **Collaborated with ML teams** to implement **metadata management for real-time predictions**.
- **Worked cross-functionally with product managers and analysts** to align data requirements.

---

## **4️⃣ Challenges & Solutions**
### **🔹 Technical Challenges**
- **High-latency queries on 1TB+ datasets** → Solved using **Delta Lake partitioning and ElastiCache**.
- **Vendor APIs had inconsistent formats** → Standardized using **Pydantic data models**.
- **GraphQL APIs struggling under heavy traffic** → Implemented **query caching & pagination**.

### **🔹 Business & Leadership Challenges**
- **Aligning cross-functional teams (engineering, analytics, ML)** → Led **biweekly syncs & detailed documentation**.
- **Onboarding offshore engineers unfamiliar with sports analytics** → Created a **knowledge-sharing framework**.

---

## **5️⃣ How This Prepares Me for Montai Therapeutics**
- **Handling Complex Scientific Data**: Just as sports data is **semi-structured and real-time**, so is **biomedical and cheminformatics data**.
- **Building Scalable Data Platforms**: Expertise in **Databricks, AWS, and Snowflake** applies directly to **Montai’s infrastructure needs**.
- **AI/ML Integration**: Experience with **LLMs and real-time analytics** will help **enhance scientific data processing**.

---

## **6️⃣ Conclusion & Key Takeaways**
- **Built a scalable real-time sports data pipeline** for Fox Sports.
- **Optimized data processing, reduced cos
