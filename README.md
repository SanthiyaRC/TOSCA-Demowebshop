Ecommerce - Demowebshop Automation

As part of this project, TOSCA Automation scripts are built on Ecommerce Web application provided by Tricentis. 
This portal allows the user to navigate through product categories and do shopping/Order Management.

Scenario Automated:
Creating an Order Report by fetching all the available orders from Order - Account Management section of the Demowebshop user and adding it to the Excel file. After generating the report send the Excel attachment via outlook email and verifying for the email at receiver end.

Application Involved:
1. Web/GUI application (Demowebshop)
2. Excel
3. Outlook

TOSCA Engines Used:
1. MAIL Engine 3.0(SMTP,IMAP)
2. EXCEL Engine 3.0
3. TBox XModules.

Things to Note:
1. Identifying the correct email protocol setting available for the account. 
2. Use SMTP for sending email and IMAP/POP3 for receving email.

Reference: https://support.tricentis.com/community/article.do?number=KB0015095
