# Project: Control Logistics Analysis of a Warehouse

## Overview

Warehouse efficiency is one of the key elements of a well-functioning supply chain. This project focuses on analyzing the warehouse procedures and searching for bottlenecks or areas that can be improved. Utilizing ABC/XYZ segmentation, we can group items in our warehouse and identify which elements are most important to us and need more attention, and which are consuming our resources.

## Business Problem: Lack of actionable data 

The logistics dataset we used for this project has some gaps. We have a lot of data, such as time of packing or daily demand, but we lack data like item weight, their sizes, or their location. Without essential data like this, we can't properly manage a place like a warehouse. The best we can do in this situation is grouping the data to confirm that we correctly allocate our time and money in the right places.

## Metodology

For this project, we used SQL to aggregate the data, find patterns, and prepare it for visualization. For the graphic presentation of the results, we used Microsoft Power BI Desktop. The final output is a dashboard that summarizes the conclusions and indicates points that need to be improved or checked.

## Final Results 

#### 1. The warehouse we analyzed has a well-executed policy for dividing its resources, such as workers and time. The value per second indicator has the highest value in the A group items, which is correct.

#### 2. Capital is divided equally by each category, but the groceries need to be inspected because of a slightly overestimated value of the Capital Burden Index (CBI).

#### 3. Zones B and C have bottlenecks in the AX group, which means we have to improve processes here. Due to the lack of data, we don't know what the reason for this problem is.

#### 4. Over 200 products have a low buffer, which covers 3 days of demand on average. These products have a history of stockouts, indicating this problem has persisted for a long time.

#### 5. There is a difference in picking time between zones at the category level, which indicates that we haven't standardized processes here.

#### 6. Nearly 300 items from the AX group have a risk of stockout. The demand buffer is lower than the delivery time, which means we have a huge risk of losing money here.

<img width="1196" height="666" alt="Zrzut ekranu 2025-11-20 104632" src="https://github.com/user-attachments/assets/8bb7942d-f4c0-4744-bf63-fabb2880c458" />

## Recommendations 

#### 1. We need to collect the missing data, such as weight, product dimensions, and the position in the storage rack (including the shelf).

#### 2. Analyze the process at the category level to examine that we aren't losing our resources here.

#### 3. Eliminate the stockout risk for the most important products by increasing the safety buffer.

## Sources of the data

https://www.kaggle.com/datasets/ziya07/logistics-warehouse-dataset











