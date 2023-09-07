# TRANSPORT DASHBOARD

## Introduction

For a long time, analyzing the state of transportation has faced difficulties due to the challenging access to information. Today, in light of the recent digital revolution that the world has experienced, a new field emerges: Business Intelligence, also known as decision informatics. This term encompasses all the technologies that enable any organization to analyze their data for the purpose of decision-making. It relies heavily on dashboards, which are indispensable tools for decision support systems. Dashboards assist decision-makers at all levels of the organization, facilitating interaction with data, including deep data mining to extract valuable information. Indeed, this project aims to implement this tool with the goal of creating a decision-making system, starting from the analysis of needs, proceeding through the ETL process, and culminating in the creation of the Dashboard.

## General Context

This project focuses on creating an interactive dashboard that allows users to visualize the transportation status, including bus and subway departure times, as well as the number of stops per station, among other criteria. This project is commissioned by the Société de transport de Montréal (STM) for various regions in Montreal. The data is sourced from the GOOGLE TRANSPORT API, also known as GTFS static or static feed, to distinguish it from the GTFS-realtime extension. GTFS static defines a common file format for public transportation schedules and associated geographical information. To facilitate analysis, it is necessary to store, manage, and present this data in a way that simplifies analysis, enabling the extraction of relevant insights and informed decision-making

## Problematic

Every state has an interest in knowing which stations experience significant delays on different days of the week and during holidays. This involves leveraging the generated data for exploration, simplification, and optimization of the analysis. This leads us to pose the following question: How can we measure and analyze the state of transportation in different regions of Montreal?

## Tools 

- *excel*
- *Sql Server Management*
- *SSIS*
- *PowerBI*

## Data Source 
https://www.stm.info/

## Data Warehouse Design

![](https://github.com/elanssariyassine/TRANSPORT_BI_ETL_DASHBOARD/blob/main/Design.png)

 


