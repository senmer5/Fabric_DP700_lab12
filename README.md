# 🚴‍♀️ Real-Time Data Analysis with Microsoft Fabric Eventhouse

## 🎯 Project Purpose

The goal of this lab was to explore **Microsoft Fabric's Real-Time Intelligence capabilities** using an **eventhouse**. An eventhouse is used to ingest, store, and analyze streaming data in real time. In this hands-on exercise, I worked with a dataset about bike-sharing events and queried the data using both **Kusto Query Language (KQL)** and **Transact-SQL (T-SQL)** – all through a **no-code interface**.

---

## 🛠️ Steps Performed

### 1. Workspace Setup
- Created a new Microsoft Fabric workspace with Fabric capacity enabled.

### 2. Eventhouse Creation
- Opened the **Real-Time Intelligence Sample** under the **Real-Time Intelligence** workload.
- Automatically generated a new Eventhouse named `RTISample` with a preloaded **KQL database** and `Bikestream` table.

### 3. Querying Data with KQL
- Queried the `Bikestream` table using KQL.
- Displayed selected fields such as `Street` and `No_Bikes` with `project` operator.
- Renamed columns with user-friendly labels.
- Summarized total number of bikes using `summarize` and handled missing values using `case`, `isempty`, and `isnull`.
- Sorted results using both `sort by` and `order by`.
- Filtered data to specific neighbourhoods (e.g., `"Chelsea"`) using `where`.

### 4. Querying Data with T-SQL
- Used the T-SQL endpoint of the KQL database to run SQL-like queries.
- Retrieved data using `SELECT TOP`.
- Renamed fields using `AS`.
- Summarized bike counts grouped by `Neighbourhood`.
- Used `CASE` to handle null or empty values.
- Ordered and filtered the results using `ORDER BY` and `HAVING`.

### 5. Displayed Real-Time Metrics
- Displayed **total number of bikes per street** in a **5-second rolling window** using KQL queries.

### 6. Cleaned Up Resources
- Deleted the workspace to ensure no charges are incurred.

---

## 📘 What I Learned

- How to **ingest and route streaming data** via Microsoft Fabric Eventstream.
- How to work with **KQL databases** inside an eventhouse.
- Used the **no-code interface** to perform real-time data transformation.
- Built and executed **KQL** queries for summarization, filtering, and sorting.
- Used **Transact-SQL** as an alternative query method.
- Completed a full real-time data pipeline **without writing backend code**.

---

## ✅ Summary

This lab helped me gain hands-on experience in real-time data streaming with Microsoft Fabric. I was able to:
- Analyze live data streams,
- Use both KQL and T-SQL for querying,
- Perform data transformations through a visual interface.

---

## Screenshots

<img width="1039" alt="1" src="https://github.com/user-attachments/assets/16661106-a2a8-4966-aa9f-0a097bd8293a" />

<img width="1036" alt="2" src="https://github.com/user-attachments/assets/bf6db0ad-76f5-4548-b323-20de8732cddf" />

<img width="1106" alt="3" src="https://github.com/user-attachments/assets/6aaf0649-069c-418f-810b-86f7c61667f9" />

<img width="1105" alt="4" src="https://github.com/user-attachments/assets/8d7370b1-ad65-434c-accf-db1f36232925" />

<img width="1080" alt="5" src="https://github.com/user-attachments/assets/01ad195b-50c3-46cf-b839-f04cb6cf6561" />

<img width="1051" alt="6" src="https://github.com/user-attachments/assets/6679565f-f7a5-4f46-ab1a-55971de2db40" />

<img width="1355" alt="7" src="https://github.com/user-attachments/assets/890dcbf0-47ca-49a0-aee9-a6e11d30f6b5" />

<img width="907" alt="8" src="https://github.com/user-attachments/assets/d6496ef5-e357-4018-b072-9a7cadb649a6" />

<img width="1226" alt="9" src="https://github.com/user-attachments/assets/1bcf30f6-63e4-4485-9723-dffc10821389" />

<img width="1080" alt="10" src="https://github.com/user-attachments/assets/af0f4c22-7399-428c-8275-376d523cbbcf" />

<img width="1407" alt="11" src="https://github.com/user-attachments/assets/c41808d6-5436-4feb-916f-b698c397df6d" />
