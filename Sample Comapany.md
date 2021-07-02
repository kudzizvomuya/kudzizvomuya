# Sample-Erpnext-Company

Sample ERPNEXT company for testing 

## STEP 1

Please follow the steps. They will make importing documents easier

### 1.1 Create South African Holiday list 

| Date | Day | Holiday |
|:---:|:---:|:---:|
| 1 January | Friday | New Year's Day |
| 21 March | Sunday | Human Rights Day |
| 22 March | Monday	| Human Rights Day Holiday |
| 2 April |	Friday | Good Friday |
| 5 April	| Monday	| Family Day |
| 27 April | Tuesday | Freedom Day |
| 1 May	| Saturday | Workers' Day |
| 16 June	| Wednesday	| Youth Day |
| 9 August | Monday	| National Women's Day |
| 24 September | Friday | Heritage Day
| 16 December |	Thursday | Day of Reconciliation |
| 25 December |	Saturday | Christmas Day |
| 26 December |	Sunday | Day of Goodwill |
| 27 December |	Monday | Day of Goodwill Holiday |

### 1.2 Create Bank

Create your **Bank** and also add their Swift codes in the field SWIFT CODE:

- Standard Bank - SBZAZAJJ
- ABSA - ABSAZAJJ
- Nedbank - NEDSZAJJ 
- Capitec - CABLZAJJ
- FNB - FIRNZAJJ
- African Bank - AFRCZAJJ


### 1.3 Create Bank Account types

- Savings Account 
- Business Cheque Account 
- Credit Card Account

### 1.4 Add Bank accounts

ServalSupport has 2 operating bank accounts.

| Bank 1 | Details |
| ------------ | ------------ |
| **Bank** | Nedbank |
| **Account Number** | 1385065702 |
| **Account Type** | Business Cheque Account |
| **Branch** | The Glen |
| **Branch Code** | 138537 |



| Bank 2 | Details |
| ------------ | ------------ |
| **Bank** | ABSA | 
| **Account Type** | Business Cheque Account | 
| **Account Number** | 9180773124 | 
| **Branch** | Centurion | 
| **Branch Code** | 630445 | 


### Edit Chart of Accounts

### 1.5 Enter Company Info

The following defaults can be set for a company:

- Default Finance Book
 > Accounting > Finance Book > new finance book
 - **add Serval Support**
A Finance Book is a book against which all the accounting entries are booked.

- Default Letter Head
> Accounting > Company > Default Letterhead > Create New Letter Head

Upload the company's letterhead to appaer on all print formarts 

- Standard Working Hours

These are the standard working hours
- Default Terms and Conditions


Uploading and creation of the buying and selling terms of condition 
- Country

Country of operation ,defined when erpnext is set up for the first time,it determines the currency a well.
- Tax ID

The registered tax number with SARS in south africa 
- Date of Establishment


### 1.6 

## STEP 2
- [ ]  
    - [x]  Add Shareholders under Equity as group
    - [x]  Add Shareholders John and Sam as Child Accounts under Shareholders
    - [x]  Create a Journal entry for Marius R60 000 and Walter R40 000 and Nedbank R120 000  ⇒ Save and Submit (Rules)
    - [ ]  **NOTE:** Marius and Walter money are in ABSA Bank
    - [ ]  **Nedbank Secured Loan** is in Nedbank Account
    - [ ]  
- [ ]  Tax Details - South African Tax Laws
- [ ]  Journal Entries
- [ ]  Example: Rent an Office 

## STEP 3 - Create Items

### 3.1 Create item group 

#### An Item Group is a way to classify items based on types.

Depending on the type of product, you can categorize an item under its respective field. If the product is service-oriented, 
assign it under the Item Group - service. If the product is used as a raw-material, assign it under the Raw Material category. 
In case, an item is used only in trading, you can categorize it under an Item Group called Trading.


**To access the Item Group list, go to:**

> Home > Stock > Items and Pricing > Item Group

### 3.1 Create Warehouse 

> Home > Stock > Settings > Warehouse

### 3.1 Check & Create Units of Measurement



### 3.2 Create Brands for different products
> Home > Stock > Brand
- Add product brands for stock and fixed assets

### 3.3 Import Items Using Data Import Tool,
> Home > Data Import and Settings > Import Data
- Create import list based on the doc type
### 3.3.1 Import Items 
> Data Import > Add New Data Import >Items 
- Attach xls or csv below is an  

| Item Code   | Item Group| Default Unit of Measure | Item Name | Maintain Stock | Image | 
| ----------- | ----------- | ----------- | ----------- | ----------- | ----------- |
| MAC100      | Products    | Nos | Mac Book Pro 15' | 1 | /file/Mac-i9.jpeg |

-below is the blank template 
[Item.xlsx](https://github.com/kudzizvomuya/kudzizvomuya/files/6753408/Item.xlsx)


## Import Contact and Addresses
Home > CRM > Sales Pipeline > Contact

- Create one contact with all details then import customers using data import tool,## take not of adding 1 on default email and number so that they appear

| ID | First Name | Last Name | Email Address | Address | Salutation | Gender | Phone | Mobile No | Is Primary (Email IDs) | Is Primary Phone (Contact Numbers ) |
|---- | ---- | ---- | ---- | ---- | ---- | ---- | ---- | ---- | ---- | ---- |
|     | Jack | Reacher | jk@gmoil.com | 34 Sentossa Randburg | Mr | Male | +27718365022 | +27718365022 | 1 | 1 |
 - Below is the blank template 
 [Contact.xlsx](https://github.com/kudzizvomuya/kudzizvomuya/files/6753410/Contact.xlsx)

## STEP 4 - Configuring Buying
- Navigate to buying 
> Home > Buying 

- This will lead you the buying module 
- First you navigate to the Buying setting
> Home > Buying > Buying Setting

![ERPNEXT_BUYING](https://user-images.githubusercontent.com/85683217/124272573-35fb0d00-db3f-11eb-97f9-55455a924992.gif)


1. Change Supplier Naming Series,SUpplier naming series is the unique name that can be given to a supplier in ERPNEXT,it can be the customer name or a system generated ,In our case we choose the system generated ,So we choose naming series 
2. Select the default supplier group,thus as a computer company most of our suppliers are hardware suppliers so we set the defult supplier group to 'Hardware'
3. We select the default buying list,this is a list with the prices of the items we are buying,so the items price will be fetched from the price list,We can modify the price list by clicking the arrow in front of it,there you can state the countries where its applicable
4. Select 'Yes' for Purchase order to be required before a purchase invoice is made 
5. Select 'No' for purchase invoice creation to be allowed before reciept,an invoice can be submitted to finance before delivery 
6. Tick Mintain rate throughout the purchase cycle,ERPNExt will check and validate if there
7. Choose Acton to take if the price on the invoice differs from the quote 
8. Assign role to overide stop action,if there is difference in price,
### 4.1 Create a supplier
> Home > Buying > Supplier > Supplier

- To Add a new Supplier go to Buying,Select Supplier.If its for the 1st time select create new supplier,Else if there are exisiting supplier click add supplier from the top right corner 
![Supplier Creation ](https://user-images.githubusercontent.com/85683217/124273107-e832d480-db3f-11eb-821c-d0a19f1d30b2.gif)

- To import new suppliers in bulk using the data import tool you can use the template below:
 [Supplier.xlsx](https://github.com/kudzizvomuya/kudzizvomuya/files/6753796/Supplier.xlsx)

### 4.2 Create Supplier Group
- There are different types of suppliers based on the goods and products they supply. To create supplier group its recommended to create a supplier 1st.We have created our supplier from the previous stage 
> Home > Buying > Supplier Group
![Supplier Group](https://user-images.githubusercontent.com/85683217/124277680-9e4ced00-db45-11eb-8c1d-59eec9c1bd57.gif)
- The Supplier Group 'Software' is now added

 ## Step 5 Selling 
 ### 5.0 Create customer Groups 
 > CRM > Settings > Customer Group.
 - This comes with 4 preconfigured values but you can edit them to your specific groups
 ### 5.1 Create customer 
 **to add new customer add a new customer go to**
> Home > Selling > Customers
or 
> Home > CRM > Sales Pipeline
### 5.2 Selling settings
- Selling Settings is where you can define properties and validations which will be applied to the masters and transactions involved in the sales cycle.
> Home > Selling > Settings > Selling Settings

 **Under selling settings,thus where you configure the following**
- Customer Naming series.
- Default Territory.
- Default Customer Group.
- Default Price list.
- Quotation Validity Days.
- Choose if sales order is required before Invoice or delivery note 
##  6.0 Payroll
### 6.1 Payroll Settings 
> Home > Payroll > Payroll Settings 

**Here you configure the following**
- Calculate Payroll Working Days Based On
- Max working hours against Timesheet
- Email Salary Slip to Employee based on their preffered email 
- Encrypt Salary Slips in Emails
- Show Leave Balances in Salary Slip
### Payroll Period
> Home > Payroll > Payroll Period
- Enter the payroll period 
### Income Tax Slab
> Home > Payroll > Imcome Tax Slab

- Add the tax tables according to SARS Tax Tables 

| Taxable Income(R)   | Rate of TAX |
| ------------------- | ---------------- |
|1 – 216 200    |18% of Income Taxable     |
| 216 201 -337 800   | 38 916 + 26% of Taxable Income above 216 200  |
|337 801 – 467 500 | 70 532 + 31% of taxable income above 337 80 |
|467 501 – 613 600 | 110 739 + 36% of taxable income above 467 500 |
|613 601 – 782 200 | 163 335 + 39% of taxable income above 613 600 |
|782 201 – 1 656 600 | 229 089  + 41% of taxable income above 782 200 |
|1 656 601 and above |587 593 + 45% of taxable income above 1 656 600 |

### Salary Component 
> Home > Payroll > Salary Component
- Configure the salary components and formulars 
### Salary Structure 
> Home > Payroll > Salary Structure 
### Salary Structure Assignment
> Home > Payroll > Salary Structure Assignment 
- Assign a salary structure to an individual 
### Payroll Entry 
> Home > Payroll > Payroll Entry 
- Create a payroll entry 
### Additional Salary 

### Retention Bonus
> Home > Payroll > Retention Bonus
- Add retention bonus if the selected employees has one 
### Employee Incentive 
> Home > Payroll > Employee Incentive 
- Configuration of incentive so that it appears on the payslip 

## HR Module 
### Employment Type
> Home > Human Resources > Employee > Employment Type
- Create the type of employment e.g permanent,contract,casual 
- 
### Create Department 
> Home > Human Resources > Employee > Department
- Create a new department on top of the ones which come pre configured by ERPNEXT 
### Create Designantion 
> Home > Human Resources > Employee > Designation
- Create new designation,these are titles given to employees 


| Designantion | Description | Skill (Skills) |
| ----------- | ----------- | ----------- |
| Construction Manager | The construction manager is responsible for overseeing the entirety of the project from start to finish. | Project Management |

### Staffing Plan
> Home > Human Resources > Recruitment > Staffing Plan
- Job Openings can only be created as per the number of vacancies and budget as per the active Staffing Plan.
### Create Leave Type 
> Home > Human Resources > Leaves > Leave Type
- Create leave type,adding to the ones frappe has pre configure,
- Create Leave policy,allocating allowed days ad rules fro each leave

### Adjust HR Settings

> Home > Human Resources > Settings > HR Settings
- Set Retirement age to 65 
- set stndard Working Hours 8 
- Change Employee Naming Series 
- Untick Stop Bithday reminders
- Set expenses approver to mandatory 
- Set the leave application and approval notifications 
- Activate check vacancy on Job Offer Creation 

## Shift Type 
> Home > Human Resources > Shift Management > Shift Type
- Configure the shift types( Night,Day,Morning)
- You can also configure auto attendance on the shift type creation 

### Add Employee 
> Home > Human Resources > Employee
- Add the employee deatils having pre configured all of the above
- Export one record from the data import tool and use for large data uploads.  

## FIXED ASSETS 
## Create asset in Fixed Asset Item Group
> Home > Stock > Item > add item
- Create new item in item then tick the Is fixed asset box.
## Create Asset Category 
- Create an the asset category 
## Create Asset Locations 
- Create asset location 
- 
## Maufacturing 
### Create warehouse 
> Home > Stock > Settings > Warehouse
- Create new manufacturing warehouse and warehouse tree
### Create Workstation 
> Home > Manufacturing > Bill of Materials > Workstation
- A Workstation stores information regarding the place where the workstation operations are carried out.
### Create Operation 
> Home > Manufacturing > Bill of Materials > Operation
- An Operation refers to any manufacturing operation performed on the raw materials to process it further in the manufacturing path.
### Create Finished Good & Raw Material in Items
> Home > Stock > Items and Pricing > Item
- Create Finished goods and raw materials in items.
### Create BOM 
> Home > Manufacturing > Bill of Materials > Bill of Materials
- A Bill of Materials (BOM) is at the heart of the Manufacturing system and the most important document that will help to create other document types like Work Orders and Job Cards.
### Create Workorder 
> Home > Manufacturing > Production > Work Order
- Create a workorder,A Bill of Materials (BOM) is at the heart of the Manufacturing system and the most important document that will help to create other document types like Work Orders and Job Cards.
### Configure Manufacturing Settings 
> Home > Manufacturing > Manufacturing Settings 
- In the settings you configure 
- Allow multiple consumption of Raw Material
- Disable and enable capacity planning(Allow overtime,allow production on holiday)
- Configure default warehouses for (WIP,Scrap and Finished Goods)
- Enable auto updating of BOM
## Projects 
A Project is a planned piece of work that is designed to find information about something, to produce something new, or to improve something.
### Create Project
> Home > Project > Project
- Create new project
### Create Tasks
> Home > Project > Tasks > New Task
- Create project Tasks 

### Create Timesheets 
> Home > Project > Timehseets > Add Timesheet
### Create Activity Type
> Home > Project > Activity Type > New Activity 
- Create new activity on the activity list,Activity Type is a list of different types of activities against which a Timesheet can be made.

## SUPPORT
This refers to the help desk,to track customer tickets and issues, maintain server levels and track response and resolutions
###
> Home > Support >Issue Type
- Create Support issue types 
> Home > Support > Service Level Agreement
- Create service level agreements 
> Home > Support > Maintanance Schedule 
- Create new maintanance Schedule 
## QUALITY 
> Home > Quality > Quality Goal 
- Create a new quality goal 
> Home > Quality > Quality Procedures
- Create new quality procedure 
> Home > Quality > Quality Feedback > 
- New Quality Feedback Template 



 



