# 👶 Analyzing American Baby Name Trends (SQL Project)

In this project, we explore **101 years** of baby name data from the **U.S. Social Security Administration (SSA)** to understand how American naming trends have changed over time. Using SQL, we analyze which names have stood the test of time, identify trendy versus timeless names, and uncover popularity patterns by gender, year, and spelling.

---

## 🧠 Project Objectives

This project focuses on answering the following questions:

- 📜 Which **American names** have been popular for over **100 years**?
- 🕰 What is the **type of popularity** for each name: **timeless** or **trendy**?
- 👧 What are the **top 10 most popular female names** of all time?
- 🔠 What is the most popular **female name ending in "a"** since **2015**?
- 👦 What are the most popular **male names by year**?
- 🏆 Which **male name** has been the most popular for the **largest number of years**?

---

## 🗃️ Dataset Overview

The SSA dataset contains baby names recorded annually in the United States from **1880 to 2020**. Each row includes:

| Column       | Description                               |
|--------------|-------------------------------------------|
| `year`       | Year of the baby name registration        |
| `name`       | Baby's first name                         |
| `gender`     | Gender (`M` or `F`)
