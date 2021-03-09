**Ecommerce - Demowebshop Automation**

As part of this project, TOSCA Automation scripts are built on Ecommerce Web application provided by Tricentis. 
This portal allows the user to navigate through product categories and do shopping/Order Management.

**Scenarios Automated:**

**Scenario 1: Order Report Generation**

Creating an Order Report by fetching all the available orders from Order - Account Management section of the Demowebshop user and adding it to the Excel file. After generating the report send the Excel attachment via outlook email and verifying for the email at receiver end.

Application Involved:
1. Web/GUI application (Demowebshop)
2. Excel
3. Outlook

TOSCA Features Used:
1. MAIL Engine 3.0(SMTP,IMAP)
2. EXCEL Engine 3.0
3. TBox XModules.

Things to Note:
1. Identifying the correct email protocol setting available for the account. 
2. Use SMTP for sending email and IMAP/POP3 for receving email.

Reference: https://support.tricentis.com/community/article.do?number=KB0015095

**Scenario 2: Product Management**

Navigating through Product Category  "Apparels & Shoes" by choosing different display options: 4,8 and 12. 
Performing Digital Downloads and verifying the downloaded file content.
Placing an Order by choosing different Payment Methods.

Application Involved:
1. Web/GUI application (Demowebshop)
2. Notepad File

TOSCA Features Used:
1. Template & Instances Concepts used to create multiple instances of test cases covering different data variations (Ordering with different Payment methods and verifying the product display with different display options).
2. Test Case Design (TCD) used to store data and pass on the value to the templates.
3. File Operations module used for File Existence & File Content Verificaton.
4. Loop concept: While and Tbox Evaluation tool used for Item count verification.
