# KMS.-Sql-case-study-
Kultra Megastores (KMS) SQL Data Analysis Project 

--- 

## 📚 Table of Contents
- [Introduction](#introduction)
- [Project Topic](#project-topic)
- [Project Overview](#project-overview)
- [Data Source](#data-source)
- [Case Scenarios Overview](#case-scenarios-overview)
- [Case Scenarios](#case-scenarios)
  - [Case Scenario 1: Sales & Profitability Analysis](#case-scenario-1-sales--profitability-analysis)
    - [Question 1](#question-1)
    - [Question 2](#question-2)
    - [Question 3](#question-3)
    - [Question 4](#question-4)
    - [Question 5](#question-5)
  - [Case Scenario 2: Customer Behavior & Returns Analysis](#case-scenario-2-customer-behavior--returns-analysis)
    - [Question 6](#question-6)
    - [Question 7](#question-7)
    - [Question 8](#question-8)
    - [Question 9](#question-9)
    - [Question 10](#question-10)
    - [Question 11](#question-11)
- [Tools Used](#tools-used)
- [Contact](#contact) 

--- 

## 🚀 Introduction
This is the **Digital Skill Up Africa* (DSA) Data Analysis Capstone Project**.  
After about two months of intensive learning and evaluations while working with **Excel, SQL, and Power BI**, I have built robust analytical skills. 

This repository focuses on the **SQL case study** component. 

--- 

## 📝 Project Topic
**Kultra Megastores (KMS)** Inventory & Sales Analysis using SQL. 

--- 

## 🔍 Project Overview
This project analyzes the **Kultra Megastores (KMS)** inventory data using SQL to uncover key insights on **sales, shipping patterns, customer behavior, and profitability** from **2009 to 2012**. 

The goal is to help KMS make **informed business decisions** that optimize revenue, control costs, and enhance customer engagement. 

--- 

## 📂 Data Source
I sourced the data from the **DSA Learning Management System via Canva**, consisting of two main files: 

- `KMS SQL Case Study`
- `Order Status` 

These contain detailed records of transactions, customer segments, product categories, sales values, discounts, shipping methods, and return data. 

--- 

## 🗂️ Case Scenarios Overview
There are two primary areas of analysis: 

### 📊 Case Scenario 1: Sales & Profitability Analysis
Aims to help KMS understand **what drives revenue and costs**, and where there are opportunities to improve profitability. 

### 👥 Case Scenario 2: Customer Behavior & Returns Analysis
Focuses on:
- Tailoring marketing & sales strategies to top customers.
- Reducing losses from returns by knowing **who returns items and from where**.
- Optimizing shipping to save costs without delaying deliveries. 

--- 

## 🗂️ Case Scenarios 

--- 

### Case Scenario 1: Sales & Profitability Analysis 

#### Question 1
**Which product category had the highest sales?** 

- ✅ **SQL Query:**
    ```[see]
    -- (KMS_case_study.sql)
    ``` 

- ✅ **Evaluation:**  
    The analysis revealed that **Technology** is the highest-grossing product category.  
    This suggests strong customer demand and possibly higher margins in this segment. 

- 🔍 **Recommendation:**  
    KMS should continue investing in technology products, consider expanding the range, and use targeted campaigns to further capitalize on this strength. 

--- 

#### Question 2
**What are the top 3 and bottom 3 regions in terms of sales?** 

- ✅ **SQL Query:**
    ``[`see]
    --(KMS_case_study.sql)
    ``` 

- ✅ **Evaluation:**  
    - **Top 3 regions:** West, Ontario, Prince  
    - **Bottom 3 regions:** Nunavut, Northwest Territories, Yukon 

    This indicates clear regional differences in purchasing behavior. 

- 🔍 **Recommendation:**  
    KMS should focus promotional resources on high-performing regions while exploring why sales lag in the bottom regions—whether due to logistics, lack of demand, or inadequate marketing. 

--- 

#### Question 3
**What were the total sales of appliances in Ontario?** 

- ✅ **SQL Query:**
    ```[see]
    ---(KMS_case_study.sql)
    ``` 

- ✅ **Evaluation:**  
    The query returned `NULL`, meaning there were **no recorded sales of appliances in Ontario**.  
    This may indicate either:
    - Appliances were **not stocked or promoted** in Ontario during the period.
    - Or there is **low consumer demand for appliances** in this region. 

- 🔍 **Recommendation:**  
    KMS should investigate customer preferences in Ontario or consider a test marketing campaign for appliances to assess potential demand. 

--- 

#### Question 4
**Advise the management of KMS on what to do to increase revenue from the bottom 10 customers.** 

- ✅ **SQL Query:**
    ```[see]
    -- (KMS_case_study.sql)
    ``` 

- ✅ **Evaluation:**  
    The bottom 10 customers contribute minimally to overall revenue. 

- 🔍 **Recommendation:**  
    - Offer **personalized promotions**, e.g., “Spend ₦20,000, get 10% off,” to encourage larger purchases.
    - Provide **targeted product recommendations** based on purchase history.
    - Use **customer satisfaction surveys** to identify obstacles to spending more.  
    This could help convert them into higher-value customers. 

--- 

#### Question 5
**KMS incurred the most shipping costs using which shipping method?** 

- ✅ **SQL Query:**
    ```[see]
    -- (KMS_case_study.sql)
    ``` 

- ✅ **Evaluation:**  
( KMS incurred the most shipping cost using Express Air ) * 

--- 

### Case Scenario 2: Customer Behavior & Returns Analysis 

#### Question 6
**Who are the most valuable customers and what products do they typically purchase?** 

- ✅ **SQL Query:**
    ```[see]
    --(KMS_case_study.sql)
    ``` 

--- 

#### Question 7
**Which small business customer had the highest sales?** 

- ✅ **SQL Query:**
    ```[see]
    --(KMS_case_study.sql)
    ` 

--- 

#### Question 8
**Which corporate customer placed the most number of orders in 2009-2012?** 

- ✅ **SQL Query:**
    ```[see](KMS_case_study.sql)
    ``` 

--- 

#### Question 9
**Which consumer customer was the most profitable one?** 

- ✅ **SQL Query:**
    ```[see](KMS_case_study)
    `` 

--- 

#### Question 10
**Which consumer returned items and what segment did they belong to?** 

- ✅ **SQL Query:**
    ``[see](KMS_case_study)
    `` 

--- 

#### Question 11
**Is KMS appropriately spending on shipping based on order priority?*
    ``` 

- ✅ **Evaluation**
-Express Air is used for high-priority orders and cheaper method (truck) for less urgent ones. 

--- 

## 🛠️ Tools Used
- **SQL Server Management Studio (SSMS)** applying:
    - Data Definition Language (DDL)
    - Data Query Language (DQL)
    - `GROUP BY`, `ORDER BY`, `BETWEEN`, `IN`
    - SQL `JOIN`
    - Aggregations like `SUM`, `COUNT`
    - `UNION ALL` 

---
