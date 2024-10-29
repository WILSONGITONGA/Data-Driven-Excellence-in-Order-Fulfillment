# Data-Driven-Excellence-in-Order-Delivery-Fulfillment
This project showcases How creating dynamic and interactive dashboards can be used to streamline and perfect order fulfillment by enabling  data driven decisions to fulfill order delivery and eliminate backlogs and delays.
## Business Overview/Problem.
At Streamline Logistics Solutions, they encounter several pressing challenges within their order fulfillment process:
- **Mounting Order Backlogs:** Current routing and resource allocation processes have resulted in a growing backlog of orders, compromising delivery timelines and, in turn, customer satisfaction.
- **Visibility Gap:** Customers often find themselves lacking real-time updates on their order progress, leading to communication gaps and rising dissatisfaction.
- **Customer Frustration:** The increasing frequency of customer complaints regarding delayed deliveries and suboptimal communication channels is beginning to cast a shadow on the company reputation for reliability.
- **Escalating Costs:** Operational expenses are on the rise due to overtime payments and the necessity for expedited shipping to clear order backlogs.
## Rationale for the Project:
Order Fulfillment is the process of receiving, processing, and delivering customer orders. It involves activities such as inventory management, order processing, picking and packing products, and shipping them to customers. While Backlogs in the context of order fulfillment refer to a situation where there is a delay or accumulation of unprocessed orders. 
Backlogs can result from various factors, including *high demand*, *operational inefficiencies*, or *unforeseen disruptions*, and they can negatively impact customer satisfaction, as customers may experience delays in receiving their orders. Eliminating backlogs is crucial to ensuring timely and reliable order fulfillment.
Order fulfillment is the Vital components of  operations in the Logistics and Supply Chain industry, where efficiency is not merely a goal but a necessity. 
## Significance of this project to Streamline Logistics Solutions.
- **Customer Satisfaction:** Enhancing Streamline Logistics Solutions order fulfillment processes directly translates into heightened customer satisfaction, thereby nurturing loyalty and long-term relationships.
- **Operational Efficiency:** Improved efficiency leads to cost savings and heightened profitability, bolstering Streamline Logistics Solutions competitive position within the industry.
- **Data-Driven Insights:** Harnessing data-driven insights empowers Streamline Logistics Solutions to optimize resource allocation and routing, ensuring timely deliveries and improved resource management.
- **Reputation Management:** Addressing these operational challenges is paramount to preserving Streamline Logistics Solutions' sterling reputation for delivering excellence consistently.
## Aim of The Project.
This project's primary objectives are to develop an **Excel interactive dashboard** that provides unparalleled visibility into Streamline Logistics Solutions' order fulfillment processes. Through this, Streamline Logistics Solutions' aim to:

- Efficiently allocate delivery resources based on order volume and location.
- Monitor order progress and proactively identify potential delays.
- Enhance customer communication with timely delivery status updates.
- Reduce order backlogs and operational costs.
- Elevate overall customer satisfaction and safeguard Streamline Logistics Solutions' reputation as an industry leader.
## Data Description.
**Step 1**
I explored the data to understand it.
This Project contains a single dataset and it comprises of;
- **Order ID:** A unique identifier for each customer order.
- **Delivery Address:** The address to which the order is to be delivered.
- **Order Timestamp:** The date and time when the order was placed (e.g., "2023-09-01 08:00").
- **Order Status:** The current status of the order (e.g., "In Progress" or "Completed").
- **Driver ID:** A unique identifier for each driver assigned to deliver orders.
- **Vehicle Info:** Information about the delivery vehicle used for the order.
- **Current Location:** The current location of the delivery driver during order delivery.
- **Delivery Time:** The total time taken for delivery, measured in minutes (e.g., "120 min").
- **Delays:**  Any delays that occurred during the delivery, measured in minutes (e.g., "15 min").
## Tools Used:
- **Microsoft Excel**:-
Excel served as the primary tool for this project, enabling the creation of an interactive dashboard that supported dynamic data visualization. The use of intermediate and advanced Excel functions was crucial for data manipulation and analysis.
## Project Scope.
- **Data Preprocessing:** Rigorous data formatting, and preparation for analysis, addressing any data anomalies.
- **Data Transformation:** Prepared the data for analysis by transforming, encoding, or normalizing it.
- **Exploratory Data Analysis:** Explore the data to understand its characteristics and discover patterns.
- **Data Analysis:** Analyzed data to understand pattern in order to generate insights that will be visualized.
- **Dashboard Design:** Crafting an interactive Excel dashboard with intuitive data visualization components.
- **Data Visualization:** Created visual representations to communicate insights effectively.
- **Interpretation and Insight Generation:** Extracted meaningful insights and interpreted the results.
-  **Documentation and Recommendations:** I Developed comprehensive documentation of the project.
##  Data Processing Tools Used.
Excel's data manipulation and analysis functions, such as pivot tables, charts, and graphs, were instrumental in processing and visualizing the order and delivery data effectively.
## Key Business Questions Addressed.
1.	How does delivery delay correlate with customer feedback?
2.	Which drivers have the highest average delay?
3.	Which routes are the most problematic in terms of delivery delay?
4.	Are certain types of vehicles associated with higher delays?
5.	How do “Expedited Rules” perform compared to “Custom Rules” in terms of delay?
## Excel Interactive Dashboard.
I created Excel Interactive Dashboard with the following Components:
1. **Order Status Overview:** A chart showing completed and backlogged orders.
2. **Average Delay By Drivers:** A chart displaying the top drivers with the highest average delays.
3. **Average Delay by Route:** A Bar chart showing delays for each Route.
4. **Vehicle Delay Overview:** A Bar chart Displaying average Delays for each vehicle type.
5. **Allocation Rules Performance:** A Bar chart comparing average delay for each allocation rule.
6. **Customer Feedback Distribution:** A pie chart showing the distribution of positive, Neutral and negative feedback.
7. **Order Hour Tracking Timeline:** A timeline or Gantt chart showing the progress of orders over time.
8. **Average Delay to delivery city:** A Bar chart to show the average delay usually associated with delivering to each city.


<img width="872" alt="DashBoard" src="https://github.com/user-attachments/assets/4d01d4da-56fc-43a3-92f4-2ce64075eade">


## Insights from the Dashboard.
1. **Order Backlog Issue:** There is a significant backlog with 767 out of 1500 orders not completed, this is a great concern since it can lead to customer dissatisfaction and operational challenges
2. **Delivery Delay:** The average delay across all the orders is approximately 14.51 minutes, this is significantly small but it can accumulate and lead to backlog.
3. **Feedback and delays:** Orders with positive feedback have slightly higher average delay than those with negative feedback, this shows that while delay is a concern other factors such as customer service, product quality or communication could be influencing feedback.
4. **Driver Performance:** Some drivers especially D86,D44 and D29 gave a notable higher delay than others. This suggests potential areas of training, route suggestions or vehicle maintenance.
5. **Route Delays:** Some routes especially route3, Route 1 and Route 2, consistently show higher delays. Investigating these routes for common obstacles, traffic patterns or longer distances can provide actionable insights.
6. **Vehicle Delays:** Deliveries made using Bike C experience slightly higher delays compared to those made with Van A.This might be due to limitations in speed, cargo capacity or the range of Bike C.
7. **Allocation Rule Inefficiencies:** Despite the intention to expedite deliveries, orders allocated using 'Expedited Rules' have a slightly higher delay compared to those allocated using both “Custom Rules" and Standard Rules. This might indicate inefficiencies in the 'Expedited Rules' allocation system.


## Recommendations.
1.	**Resources Allocation:** Given the backlog, it might be useful to allocate more resources to address the backlog and prevent further accumulation of orders.
2.	**Driver Training and Evaluation:** Drivers who have higher delays might need training, better route planning tools or vehicle maintenance checks.
3.	**Route Optimization:** Consider re-evaluating the routes with high delays. Traffic analysis, timely deliveries and other factors can also be assessed to optimize routes.
4.	**Vehicle Allocation:** Reassess the use of "Bike C" for deliveries, especially if they are used for longer routes or bulk deliveries.
5.	**Enhance Customer communication:** Given the feedback, enhancing the communication channel with customers regarding their status of their orders, expected delays or any other concern can help improve satisfaction.

### Project Done By:
**Wilson Gitonga**

www.wilsongitonga.com
