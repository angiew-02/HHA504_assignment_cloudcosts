# HHA504_assignment_cloudcosts
The objective of this assignment is be introduced to the cost management and billing interfaces of Azure and Google Cloud Platform (GCP). By the end of this assignment, you will be able to navigate these platforms to understand how cloud costs are tracked and managed.
# 1. Explore the Cost Management Dashboards
### *Azure*
##### Location to Monitoring Costs and Set Budgets or Alerts

![Azure cost mangement](https://github.com/user-attachments/assets/6bc33e67-fc92-46a9-923a-515220816c13)
### *GCP*
Billing Overview: Consist of cost, credits used, and total cost in the last 7 days and current month. it also has a forest total cost feature in which it can predict future spendings. As well as a graph that shows top projects and top services. Another feature is on the overview is the ability to create a budget alert and to view billing health checks.

![GCP Billing overview](https://github.com/user-attachments/assets/c4c27862-4444-4cf5-acba-5f91f25e998f)
Reports: Similar to billing overview as it contains the toal cost spending for the last 7 days and the forested total cost for the current month. It also contains the ability to download the reports as a csv file. There is also line or bar graph avaible for usage cost making it easy for people to view. 

![GCP reports](https://github.com/user-attachments/assets/6791ca0e-bc69-4ce2-93ba-2e75fe5a42af)
# 2. Setting Up a Hypothetical Budget
### *Azure*
##### Budget for a hypothetical monthly spend of $8

![Azure hypothetical spend](https://github.com/user-attachments/assets/4e29838b-e7b6-4859-853e-e7ce3b6fabce)
##### Setting up a notification to alert when hypothetical spending reaches 80% of the budget

![Azure alert notification](https://github.com/user-attachments/assets/85bdd672-de5c-4857-ba59-54f602d7c69c)

### *GCP*
##### Budget for a hypothetical monthly spend of $8

![GCP hypothetical spend](https://github.com/user-attachments/assets/c123c9ee-b6ea-400b-826a-f76f449603a1)
##### Setting up a notification to alert when costs approach the budget limit

![GCP alert notification](https://github.com/user-attachments/assets/b60c7c41-8073-4312-9088-07cb86973e69)
# 3. Investigate Cost Management Features
### *Azure*
##### Review the available options for forecasting future costs based on the budget
There are many options for forecasting future costs in Azure. The first option is the cost analysis feature under cost management which can allow you to track your current and past spendings and therefore help predict future expenses. Another option is the pricing calculator which allows for an you to estimate the cost of the services offered Azura before actually using it which can allow you to compare different service options that fit within your budget. There is also an advisor recommendation section under cost management which analyzes usage patterns and make suggestions for saving cost. 
##### Explore the cost-saving recommendations provided by Azure Advisor
  Azure advisor provides many cost-saving recommendations such as AI services that saves cost of resources in intelligence, computer vision, speech service, translator, LUIS, and language service. They also have analytic services which allow for deleting unused and  stopped resources as well as scaling down or scale in resources to manage cost. Compute services is also another recommednation which allows to manage disk management and VM. 
  The cost management features that I found most interesting in Azure is that how they are able to analyze the services I use and don't use so that they can make recomendations on deleting or stopping them and saving cost. This feature is benefical as sometimes I can have many services downloaded and may forget about them but would still be charged for them but with this feature, I can save cost on services I do not use. 
### *GCP*
##### Explore the "Cost Breakdown" and "Budgets & alerts" features to see how GCP allows tracking and managing costs
Cost Breakdown: This feature allows for tracking and managing costs by breaking it down into 3 components which are usage cost, subtotal, and toal. In the cost breakdown section, there is a bar graph in which you can view your cost. You can also view a report on the cost breakdown for usage cost and cost in bar or line graph form. lastly there is an option for you to download the cost report in a csv file that reports on cost breakdown, the effective rates, and the amounts.

Bugets & Alerts: This feature allows for you to set you budget that you want to spend and can an alert to notify you and billing administrations that your cost exceeds the budget you have put down. 
##### Investigate the "Recommendations" section under GCP Billing to understand potential cost-saving suggestions
  There are many potential suggestions for cost-saving avalible in GCP such as the active assist which can help decrease cost by identifying waste, highlight over-provision resources, and optimizing price models. For example, a recommendation to downsize VM that you are using less of or shutting down persistant disk. 
  The cost management features that I found most interesting in GCP was with FinOps hub. This feature allows for monitoring and communicating your current savings and make new recommended opportunities to save on cost. This feature displays a dashboard with all the active savings, recent and past usages, and current commitments gathered by Cloud Bulling and Recommender. This can allow for you to easily see your potential savings per month on projects or services. This feeature includes 3 ways to optimize practices which are turning off idle resources, right sizing instances, and purchasing committed use discounts. 
