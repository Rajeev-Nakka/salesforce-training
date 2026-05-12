**Salesforce Summer Training – Day 3**

--------------------------------------------------------------------------------------------------------

1. Difference Between: •	App •	Object •	Record •	Field 

👉🏻 **App**

An app is basically a collection of tools (objects, tabs, etc.) built for a specific purpose.

Example: A College Management App

 👉🏻**Object**

An object is like a table in a database.

Example: Student, Course

👉🏻 **Record**

A record is one entry inside an object.

Example: One student’s details

👉🏻 **Field**

A field is a column in that object.

Example: Name, Age, Email

-----------------------------------------------------------------------------------------------------------------------------

2. Standard vs Custom Objects

👉🏻 **Standard Objects**
   
These are already provided by Salesforce.

Example: Account, Contact

👉🏻 **Custom Objects**

These are created based on our own requirements.

Example: Student__c, Course__c

--------------------------------------------------------------------------------------------------------------------------
  
4. My College Data Model 
Include: •	Objects •	Relationships •	Diagram/image

**Objects I Created**

-->Student

-->Faculty

-->Course

-->Department

**Relationships I Thought Through**

-->A Department has many Faculty

-->A Department has many Courses

-->A Faculty teaches multiple Courses

-->A Course has many Students

All of these are mostly one-to-many relationships using Lookup.

**Diagram/image**

Department

↓

Faculty ----→ Course ----→ Student


-------------------------------------------------------------------------------------------------------------------------

6. Formula Fields 

--> **Full Name**

Instead of typing full name every time, combine first name and last name automatically.

Why?
Avoids repetition and mistakes.

--> **Remaining Seats**

Total Seats - Filled Seats

Why?
Gives real-time availability without manual calculation.

--> **Percentage**

(Marks Obtained / Total Marks) * 100

Why?
No need to calculate manually again and again.

---------------------------------------------------------------------------------------------------------------------

7. Validation Rules 

--> Email should not be empty

Prevents missing important contact info.

--> Age should not be negative

Avoids invalid or unrealistic data.

--> Course seats should not exceed limit
   
Prevents overbooking.

-------------------------------------------------------------------------------------------------------------------

8. Reflection
   
Why structured enterprise data matters 

At first, I thought Excel could do everything. But after today, it’s clear that:

.Excel doesn’t handle relationships well

.Data can easily become messy and inconsistent

.No automation or validation by default

.Hard to scale for real businesses

**Salesforce solves this by keeping everything structured and connected.**

---------------------------------------------------------------------------------------------------------------------------

**Reflective Questions** 

1.	Why can’t companies manage everything using Excel sheets?

  Because it’s hard to manage large and connected data, and errors are very common.

2.	Why are relationships important between objects? 

They connect data just like in real life (students → courses → departments).

3.	What problems happen if data is inconsistent? 

It leads to wrong decisions and confusion.

4.	Why should repetitive calculations be automated? 

Saves time and avoids human mistakes.

5.	Why should invalid data be blocked early? 

Because fixing it later is harder and risky.

6.	Why is Salesforce called a metadata-driven platform? 

Because we can build everything (objects, logic, rules) without coding — just configuration.




