# HHA504_assignment_cloudcosts
The objective of this assignment is to introduce you to the cost management and billing interfaces of Azure and Google Cloud Platform (GCP). By the end of this assignment, you will be able to navigate these platforms to understand how cloud costs are tracked and managed.


# Exploring the cost management dashboard for Azure and Google Cloud Platform (GCP) 

### *Azure* 
#### _**Dashboard**_
__What tools and report are available__

  Change scope - allows you to manage control access to one or more resources 
  Control access - provides you with all end users information  such as role, scope, and type of user
  Reporting and analytics - provides cost analysis to provide valuable insight and control spending patterns 

__Where would you monitor costs and set budgets or alerts__
![Azure cost man](https://github.com/user-attachments/assets/504ea756-897c-4643-81ea-61e218cae149)

#### _**Hypothetical Budgeting**_
__Create a budget for a hypothetical monthly spend (e.g., $8)__
![azure hypothetical budget ](https://github.com/user-attachments/assets/1a4e9254-7221-4649-a3c7-a10b0cc01183)

__Set up a notification to alert you when your hypothetical spending reaches 80% of the budget__
![azure forcasting ](https://github.com/user-attachments/assets/41d7769e-ef91-4d8b-9fc6-c0b0209a12f8)

#### _**Cost Management Features**_ 
__Review the available options for forecasting future costs based on your budget.__

Azure has pricing calculators which are options in order to predict based on a set budget whether what you are looking for is does exceed threshold set.
The Azure advizor tool also provides customized reccomendations the help you to optimize resources based on set budget and forcasted spending 
Then there is MS Cost management which are a set of tools that can be used to monitor , allocate , and optimize azure cloud resources , instances, database, storage, and VM's 

__Explore the cost-saving recommendations provided by Azure Advisor (even if no data is present, you can see where these recommendations would appear)__

Based on Azure Advisor under the recommendation ribbon to the cost tab you will find that it has several cost saving options such as AI servicing which can reduce cost in document intelligence, computer vision, speech service , translator , LUIS, Language service resources. They also have analytic tools that help manage data that are  unused, stopped, or empty resources In addition they also include a right-size resource that helps optimize cost. 
Advisor also can give cost saving recommendations for compute to manage for VM and disk management 
They also provide similar cost saving recommendation similar to their analytic tools for database , management and governance,  networking , reserve instances , web, and storage 
Just a couple of points to make about these options. I like that it's actually not all listed based on category, such as database or storage. I like how they make it easily known based on simple goals like operational excellence. I also find it interesting in the Advisor tool that they will even score specific areas to give you a visual idea of how you are doing in a particular area


### *GCP*
#### _**Dashboard**_
__Summaries Billing Overview and Reports section and how GCP presents cost data__ 

Billing overview - in this view on google billing overview you will find a chart that can tracks both weekly [ 7 - day view ] and Monthly cloud spending. Underneath those tab bars you will find a cost with a dollar amount, next you will see credits used. Finally there are total cost and forcasted total cost details that will inform you of spending and future or expected spending.

Report Section - Will includie similar items as the billing overview such as total cost and focasted total cost. You can even download a csv file down below with the following data fields - service , cost , discounts , promotions and others ,  subtotal, and percent changes. Google cloud platform also nicely displays these details right above the download table csv file option. They have a barchart or line graph that easily shows that data. You can also see details such a cumulative amounts and get alerts when usage cost are available. 

#### _**Hypothetical Budgeting**_ 
__Create a budget in GCP for the same hypothetical amount ($8)__
![hypothetical_budgeting-hha507](https://github.com/user-attachments/assets/f4c24ac3-0113-4c36-895b-3511a6b2ab5d)
__Set up a notification to alert you when your costs approach the budget limit__
![GCP_forcasting ](https://github.com/user-attachments/assets/872127e2-cc4e-417e-8bcc-da9df71d41e3)

#### _**Cost Management Features**_ 
__Summarize “Cost breakdown” and “budget & alerts”__

Cost breakdown-  Can be used to show end users and management base usage cost and hoe these cost reflect onto accounts credits, adjustments, and taxes at your total cost. 
They breakdown cost in 3 ways 
1. usage cost
2. subtotal
3. total
   
At the bottom of the breakdown window you will also be able to capture these 3 factors onto a csv file that will report cost breakdown , effective rate, and their amounts 

__Investigate “recommendation” section and understand potential cost saving suggested__
Under Google Clouds Platforms "*Active Assist*" tool is a reccomendations hub that has a variety of different areas to help you improve in cost , performance, security , reliability, management, and sustainability. 
In this instance we will discuss just cost reccomendations, it talks about deleting inused or idling resources, possibly downsizing VM based on workload needs. They have a new reccomendation and open recomendation lists. Then they also based on those recommendations give you a projected or potential monthly saving by deleiting , downsizing ,or rethinking different resources and VM's.

What I also found really interesting when investigating GCP reccomendation hub they also have a finOps hub which is a secondary tab under cost optimization that outline High-priority task. In addition they also have potential savingd that give users to opimize resources. They also provide you are Findop score to improve practices. I think that this feature is really cools because it talks about optimization of cloud spending reduces carbon impact and provides you with a carbon footprint view that estimates gas emmissions based on GCP service usage. 

