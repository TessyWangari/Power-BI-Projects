



## Project 2 : Data Modeling with Power Bi [See project files here](https://github.com/TessyWangari/Power-BI-Projects/tree/main/2.Data%20Modeling%20with%20Power%20BI)
## BACK GROUND:
We are working with a company called Heavy Power Nutrition.
Our first mission at Heavy Power Nutrition is to help the Demand Generation team, which is under Pedro’s management, to create the B2B sales reports more easily.

It is essential that, from the reports generated, Pedro and his team can get insights on how to generate more demand for the sales team.

Pedro would like his analysts to stop doing so much manual work and start helping more with those analyses. This way they could use their time for tasks that would bring more strategic benefits to the company.

We got from him a sales spreadsheet from January/2013 to November/2013 that was extracted from the company’s system. Every end of the month the team needs to extract a new updated file and manually create some extra calculations, such as Net Sales, Cost of Sales, Gross Margin, etc. These calculations are marked in blue in the last columns of the table.

Every month it’s the same nightmare: analysts exporting a new base and repeating the same calculations
## DESCRIPTION
One of the tasks of the B2B Sales team at the beginning of every month is to separate Net Sales by Product Category and by Sales Supervisor. Each supervisor must receive an Excel file with the sales of their region, where there is a sheet for each Product Category.

Analysts create these reports in Excel pivot tables through a direct connection to the database that IT has left programmed in an Excel file.

This generates a huge repetitive workload at the beginning of the month, as analysts have to update each file manually and send them by email to supervisors.

On the other hand, Pedro needs to receive from his team only a consolidated file with all supervisors and all product categories. Besides, he requested that, in this consolidated file, an analysis be presented of which months each region has reached its monthly sales target.

To assist us in this process, he provided us with a file called Target.xlsx, which is a manual base for registering supervisors by regions and their respective targets by month, since the company’s ERP does not allow this registration of goals by supervisor neither by region.
## TASKS
1. Import into Power BI all four files for the individual supervisors and consolidate the data into a single table within Power BI.
2. Import into Power BI the table with the monthly target by region and perform an analysis of Net Sales x Target for the supervisors, to know in which months each of the supervisors reached the target.
3. Create the necessary transformations to build the proper data model using relationships between tables.
4. As much as we can do this consolidated analysis that Pedro asked for, the process is still far from ideal. Besides, do you see other problems that Pedro may face when analyzing the values coming from the Marketing team, from Mission #01, and the values coming from the Sales team, from Mission #02? What would you suggest to him to minimize these risks?



Other Power Bi Resources 

1. [EnterPrise DNA] (https://portal.enterprisedna.co/courses/1399444/lectures/32167265)
