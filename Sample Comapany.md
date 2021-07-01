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

- Default Letter Head
A Finance Book is a book against which all the accounting entries are booked.
- Default Holiday List

- Standard Working Hours
- Default Terms and Conditions
- Country
- Tax ID
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

### 3.3 Import Items Using Data Import Tool,

## Import Contact and Addresses
Home > CRM > Sales Pipeline > Contact

Create one contact with all details then import customers using data import tool,## take not of adding 1 on default email and number so that they appear

## STEP 4 - Configuring Buying

### 4.1 Create a supplier
> Home > Buying > Supplier > Supplier

Create Supplier
### 4.2 Create Supplier Group
- Supplier Groups is a way to classify supplier based on the product they supply to the company 
### 4.3 Go to Buying settings  
**To access buying settings got to**
> Home > Buying > Settings > Buying Settings
 - Select Default Supplier Group
 - Configure what should be the default value of Supplier Group when creating a new Supplier. For example,if most of your suppliers supply you hardware, you can set the default as 'Hardware'.
 
 ### 4.4 Configure what should be the default Price List 
 - Select the default Buying Price List and save 
 ### 4.5 Maintain Price throughout the purchasing cycle 
 - Still under settings,tick maintain price so that a price doesnt change throughout the purchasing process
 
 ## Step 5 Selling 
 ### 5.0 Create customer Groups 
 > CRM > Settings > Customer Group.
 
 This comes with 4 preconfigured values but you can edit them to your specific groups
 
 ### 5.1 Create customer 
 **to add new customer add a new customer go to**
> Home > Selling > Customers
or 
> Home > CRM > Sales Pipeline
### 5.2 Selling settings
- Selling Settings is where you can define properties and validations which will be applied to the masters and transactions involved in the sales cycle.
> Home > Selling > Settings > Selling Settings

- **Under selling settings,thus where you configure the following 
- Customer Naming series.
- Default Territory.
- Default Customer Group.
- Default Price list.
- Quotation Validity Days.
- Choose if sales order is required before Invoice or delivery note 


## Payroll
### Payroll Settings 
> Home > Payroll > Payroll Settings 
Here you configure the following 
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

### 

## HR Module 

### Employment Type
> Home > Human Resources > Employee > Employment Type
- Create the type of employment e.g permanent,contract,casual 
### Create Department 
> Home > Human Resources > Employee > Department
- Create a new department on top of the ones which come pre configured by ERPNEXT 
### Create Designantion 
> Home > Human Resources > Employee > Designation
- Create new designation,these are titles given to employees 
### Staffing Plan
> Home > Human Resources > Recruitment > Staffing Plan
- Job Openings can only be created as per the number of vacancies and budget as per the active Staffing Plan.
### Create Leave Type 
> Home > Human Resources > Leaves > Leave Type
- Create leave type,adding to the ones frappe has pre configure,
- Create Leave policy,allocating allowed days ad rules fro each leave

### Adjust HR Settings

> Home > Human Resources > Settings > HR Settings
- Set Retirement age
- Working Hours 
- Change Employee Naming Series
- Stop Bithday reminders
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



 



