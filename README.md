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

Project Workspace Snapshot:
**Requirement Section**
![image](https://user-images.githubusercontent.com/80340488/110894712-5861e400-831e-11eb-826c-456bef81b3f0.png)

**Modules Section**
![image](https://user-images.githubusercontent.com/80340488/110894829-9e1eac80-831e-11eb-9013-21e0fee4b94d.png)

**Test Case Section**
![image](https://user-images.githubusercontent.com/80340488/110894610-2a7c9f80-831e-11eb-896f-92613d4da9a9.png)

**Test Case Design Section**
![image](https://user-images.githubusercontent.com/80340488/110894871-b0004f80-831e-11eb-9a01-b35fa1715959.png)

**Execution Section**
![image](https://user-images.githubusercontent.com/80340488/110894962-d920e000-831e-11eb-8cf8-58ab46e94cdb.png)

**Test Data Services**
![image](https://user-images.githubusercontent.com/80340488/110895026-f9509f00-831e-11eb-9207-3763643856b9.png)

**Execution Summary**
![image](https://user-images.githubusercontent.com/80340488/110895337-901d5b80-831f-11eb-89f1-06be6fd96eb7.png)


