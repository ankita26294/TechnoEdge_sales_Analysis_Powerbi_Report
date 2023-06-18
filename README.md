# TechnoEdge_sales_Analysis_Powerbi_Report
The important thing in this project is how to get email attachments in Power BI without opening emails in Microsoft Outlook. This trick is very suitable for those who work in a company with a lot of data analysis work.

Imagine if we have 1000 email attachments and we want to make sense of that data in those email attachments (which can be Excel, CSV, PDF, or any other flat data files). Now, if we want to download, clean, and combine that data, it usually takes a huge amount of time.

To understand, let's imagine we have some data for every month with a subject name like "TechnoEdge Sales Monthly data - June 2023" in the email.
All you need is Power BI Desktop and a corporate email ID (Outlook in this example).

• To automate this process:

Open Microsoft Outlook -> Home tab -> Create rule -> In Subject contains, enter the same subject name "TechnoEdge Sales Monthly data" -> Move the item to folder -> Select folder -> Create a new folder named "Monthly Sales Data" -> OK
Then, all the emails that contain "TechnoEdge Sales Monthly data" as the subject (common subject line) will be moved to the particular folder.

• The most important part is how to get the email attachments directly in Power BI without opening any email:

Open Power BI Desktop -> Get Data -> Microsoft Exchange Online -> Type your email ID and connect. Then, you can see all the data from your Outlook, for example, inside Microsoft Power BI (calendar details, all the emails with attachments, meeting requests, people, etc.) -> Mail -> Transform data.
Now, all the emails have come to my Power BI. After that, you just select the folder "Monthly Sales Data," and we're finished.

• NB 1: You need to ensure that the column names match exactly, and the arrangement of columns may vary.

• NB 2: In your workspace, click on the name of your report, for example, "TechnoEdge Sales Analysis Report" -> Settings -> Edit credentials (if you want to give permission to Power Base Service to access your email attachments only) and change it to private sign-in.

The beauty of that, I haven't opened and downloaded any of those email attachments, and I copy-paste the data without using any coding language to combine it. It takes less than 15 minutes, and if I receive a new email, it will be automatically updated in my dashboard.

linkdin link:https://www.linkedin.com/in/ankita-chaudhari-a1a64b23a/
