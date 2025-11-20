# Project: Control Logistic Analysis of Warehouse

## Overview

Warehouse efficieny is one of the key elements of well-working supply chain. That project focus on analyzing the warehouse procedures and searching for bottlenecks or places that can be improved. 
Utilizing the ABC/XYZ segmentation we can geoup items in our warehouse and find which elemnts are most important to us and need more interest and which are consuming our resources.

## Business Problem: Lack of actionable data 

The logistic dataset we used to this project have some gaps. We have many of data like time of packing or daily demand but we don't have data like weight of the items, their sizes or where are they
located. Without basic data like this we can't properly manage place like the warehouse. Best we can do in that situation is grouping the data to discover that we corectly divorce our time and money
in corect places.

## Metodology

For this project we used SQL to agregating the data, find the patterns and prepare it to the visualisation. For the graphic presentation of the results we used microsoft Power BI Desktop. The final effect
is dashboard which summarized the conclusion and indicates points that need to be improved or cheecked.

## Final Results 

#### 1. The warehouse we analized have a well-done politics of divisionig their resources like workers and time. The value per second indicator have the biggest value in the A group items which is correct.

#### 2. Capital is divisioned equaly by each category but the groceries need to be inspected because of slightly overestimated value of the capital Burden Index (CBI).

#### 3. Zones B and C have bottlenecks in the AX group what means we have to improve processes here. Because the lack of data we don't know what is the reason of that problem.

#### 4. Over 200 products have low buffer which 3days cover of demand in average. That products have historical stockout so this problem we have for a long time.

#### 5. There is difference in picking time between zones in the category level what is mean that we didn't standarized procesess here.

#### 6. Near 300 items from AX group have risk of stockout. The demand buffer is lower than the delivery time which means that we have a huge risk of losing money here.

## Recomendation 

#### 1. We need to collect the lacked data like the weight, product dimensions and the position in the storage rack (including the shelf)

#### 2. Analyze the process in the category level to examine that we don't lost our resources here











