Salesforce-Summer-Training-Day2
------------------------------------------------------------------------------------------------------------------------

1. What is Salesforce Platform?

The Salesforce Platform is a cloud-based platform that allows you to:

.Build and run business applications

.Manage customer relationships (CRM)

.Automate workflows and processes

.Store and analyze data

-----------------------------------------------------------------------------------------------------------------------

2. Explain: App, Object, Tab

👉🏻App

An App is a collection of tools grouped together for a specific purpose.

Example:

1)Sales App → Leads, Accounts, Opportunities

2)HR App → Employees, Recruitment

👉🏻Object

An Object is like a table in a database that stores data.

Types:

Standard Objects → Contact, Account

Custom Objects → Student, Property

Example:

Object: Student

Fields: Name, Age, Course

👉🏻Tab

A Tab is a UI element (button/menu) used to access an object or feature.

Example:

Clicking “Contacts” tab opens Contact records

------------------------------------------------------------------------------------------------------------------------------

3. Difference: Configuration vs Coding
   
👉🏻 **Configuration**

Configuration means customizing the system using built-in tools available in the Salesforce Platform without writing any code.

It is a click-based approach, where you use features like:

Object Manager (to create objects and fields)

Flow Builder (for automation)

Validation Rules (for data checks)

Profiles and Permissions (for access control)

👉🏻 **Coding**

Coding means writing custom logic using programming languages like Apex and building UI using Lightning Web Components.

It is used when:

Requirements are complex

Configuration cannot solve the problem

External system integration is needed

Coding is more powerful and flexible, but:

It requires programming skills

It takes more time

Maintenance is more complex

**Configuration = Click-based**

**Coding = Code-based**

------------------------------------------------------------------------------------------------------------------------
4. Your System Design (Example)

👉🏻 App

College Management App built on the Salesforce Platform

This app is used to manage student, course, and faculty information in a centralized system.

👉🏻Objects

-----> **Student**

1.Name

2.Roll Number

3.Marks

4.Grade

-----> **Course**

1.Course Name

2.Duration

-----> **Faculty**

1.Name

2.Subject

👉🏻User Interaction

1.Admin → Creates students and assigns courses

2.Faculty → Updates student marks

3.System → Calculates grade automatically

4.Student → Views their details and results

