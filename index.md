<!-- Google tag (gtag.js) -->
<script async src="https://www.googletagmanager.com/gtag/js?id=G-63M4ERY6GF"></script>
<script>
  window.dataLayer = window.dataLayer || [];
  function gtag(){dataLayer.push(arguments);}
  gtag('js', new Date());

  gtag('config', 'G-63M4ERY6GF');
</script>

# Welcome to My Portfolio

---
### Learn About My Projects

#### [Demand Forecasting - Service Parts in the Eletric Vehicle Industry](https://github.com/rayylin/Demand-Forecasting-Example--Service-Parts-in-the-Eletric-Vehicle-Industry/)
- Python, Sql Server, 
[<img src="./images/Forecasting.png?raw=true"/>](https://github.com/rayylin/Demand-Forecasting-Example--Service-Parts-in-the-Eletric-Vehicle-Industry)

Effective demand forecasting helps businesses optimize inventory, streamline production, improve raw material orders, and maintain cash flow. I will use Time Series, XGBoost, and Lasso to forecast service part demand in the Electric Vehicle industry. Additionally, I’ll demonstrate location pooling for rare, costly parts to reduce demand variability through risk pooling. Finally, I will explore methods to enhance forecasting accuracy and address demand forecasting challenges for supersession or NPI projects with no historical data.

---
#### Demand Forecasting with Sap
- SAP
<img src="./images/SapForecasting1.png?raw=true"/>
<img src="./images/SapForecasting2.png?raw=true"/>
This project performs a demand forecast of an electronic part. Demand forecasting is an important issue that could help businesses better allocate resources and arrange their production schedule. We have the sales data for the past two years. The product is sold in 235 locations and has 223,769 transactions. We focus on the US only. The raw data includes six columns, Location, Code, Year, Day, Sales, and Continent. We use SAP to perform demand forecasting with the Time Series model. We use Mean absolute percentage error (MAPE) to evaluate the performance. The MAPE value is 3.46%

---
#### [Online Shopping Website with Basket Analysis - with RAG chatbot](https://github.com/rayylin/RecommendationSys)
- Python (Flask), Sql Server, JavaScript
[![image](https://github.com/user-attachments/assets/28002e3f-34a5-4949-bc8e-6f67f159d258)](https://github.com/rayylin/RecommendationSys)
This project builds an online store using Python Flask, featuring product browsing, category filtering and a shopping cart. It integrates basket analysis with association rule mining to provide personalized product recommendations, enhancing user experience and boosting sales. The backend uses Flask with a relational database. 
![image](https://github.com/user-attachments/assets/b81eda1b-073e-41e3-847f-7be417ad4ae0)

To improve user experience, there is a virtual asssitant could answer customers' question. The assistant will perform RAG (Retrieval-augmented generation), so customers could asks questions about product details in the store. For example, customer could ask the assistant where is the food section, and the chatbot would answer the question based on the store location.
![image](https://github.com/user-attachments/assets/e4166147-6342-481a-9c7e-fc4808b4bc21)



---
#### Data Pipeline for Maintenance Management
- Alterxy, SQL Server
<img src="./images/Pipeline1.png?raw=true"/>
<img src="./images/Pipeline2.png?raw=true"/>
Managing maintenance plans for vehicles with thousands of parts is time-consuming. This project uses Alteryx to automate the process via a data pipeline. The model extracts data from CSV files and SQL Server, calculates vehicles needing maintenance, and forecasts upcoming maintenance demands. It updates critical information automatically each month.

---
#### Inventory Management System
[- C#(.net core MVC, signalR, HangFire), Programmable Search Engine on GCP, OpenAI API for summary](https://github.com/rayylin/InventoryManagement)
[![image](https://github.com/user-attachments/assets/379b487e-6d7b-47d6-84fe-4380dfdc0825)
](https://github.com/rayylin/InventoryManagement)
If a product's inventory is lower than its safety stock level, the system would send an email to notify the PIC to reorder. By leveraging background jobs (could be performed by Hangfire or Sql server Agent), we could trace our inventory level on a real-time basis. If we want to implement real-time notification, we could leverage signalR. We are going to simulate customer purchase, inventory order & delevery in this case. Also, we will use openai api to perform summarization for daily sales performance.
- C#(.Net winForm), SQL Server
<img src="./images/InvMgn.png?raw=true"/>
An Inventory Management System can help companies manage their orders, inventory, and customers. In this project, we use C# and .net to write an inventory management system. The system uses SQL Server as its database.

![image](https://github.com/user-attachments/assets/15bc2b2d-c8f8-419a-ae1b-f62bdc38aea4)

---
#### [Sales Performance Tracking Dashboard](https://github.com/rayylin/Power-BI_Purchase_order_analysis)
- Power BI, Sql Server, Python
[<img src="./images/PerformanceTrack.png?raw=true"/>](https://github.com/rayylin/Power-BI_Purchase_order_analysis)
In this project, I created an interactive Power BI dashboard to track KPIs, analyze sales data, and improve decision-making. It visualizes actual vs. expected sales, transaction, and store data, helping identify trends and factors affecting sales. Users can drill down for detailed insights on products, salespersons, and stores.

- Tableau
[![image](https://github.com/user-attachments/assets/ec3390ad-c5e2-4c01-b835-f61bc49967b1)](https://github.com/rayylin/Power-BI_Purchase_order_analysis)
In this project, I build an interactive dashboard to track and analyze KPIs and visualize information. The dashboard uses different plots to show the performance and trends of each product. The dashboard can also help users find abnormalities by drilling down the data to get more information. We find that the increasing costs affect the profit in Italy.

#### [Material Planning]([https://github.com/rayylin/Power-BI_Purchase_order_analysis](https://github.com/rayylin/Python-Production_Planning))
- Python
![image](https://github.com/user-attachments/assets/9651d480-4272-43ce-94c7-65d6a4ff5edd)
![image](https://github.com/user-attachments/assets/da56d799-52f6-4ee8-9f39-ead06089150c)
We cooperate with an animal food manufacturer, and they have limited storage space and are trying to maintain minimal inventory on hand. My task is to build a model for them to calculate when they should issue purchase orders. To achieve this goal, I use python to employ the Critical Path Method Algorithm to calculate the slack. The slack is how long we could delay without violating the deadline. We could order the raw materials for processes with slack later but would not delay the production schedule.

#### [Sales Performance Tracking Dashboard](https://github.com/rayylin/Power-BI_Purchase_order_analysis)
- Power BI, Sql Server, Python
[![image](https://github.com/user-attachments/assets/ead7c949-bcce-44b2-a940-54b4b804e493)
](https://github.com/rayylin/Python-Route_Optimization_by_KNN)
[![image](https://github.com/user-attachments/assets/d8db2b5a-9e5e-4d9f-9340-0f3bf6ba7de9)
](https://github.com/rayylin/Python-Route_Optimization_by_KNN)
A company now has five distribution centers (DCs) and wants to build a new one. We intend to help the company choose a location to establish a new distribution center. We want to assign warehouses of each state an appropriate DF, thereby minimizing the total distance of the network, as a longer distance implies a higher transportation cost. We have the coordinates for warehouses of each state and distribution centers. Notice that we should not change the coordinates of five existing distribution centers. We applied the KNN algorithm to minimize the total distance of the network.
