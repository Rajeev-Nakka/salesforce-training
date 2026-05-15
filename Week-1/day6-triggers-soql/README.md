    Salesforce-Summer-Training–Day-6  

------------------------------------------------------------------------------------------------------------------------------------------------------------

1. What is SOQL?

SOQL (Salesforce Object Query Language) is used to retrieve data from Salesforce objects.

Similar to SQL but designed for Salesforce

Used to fetch records from objects like Student, Course, Faculty

Works with relationships between objects

Example:

Get all students

Get students in a specific course

------------------------------------------------------------------------------------------------------------------------------------------------------------

2.What is an Apex Trigger?

An Apex Trigger is a piece of code that runs automatically when certain events happen in Salesforce.

Key Points:

Executes before or after data changes

Helps automate business logic

Works on events like:

Insert , update , Delete


------------------------------------------------------------------------------------------------------------------------------------------------------------

3.Differences Between 

👉🏻 Flow vs Trigger

Flow (Declarative):

Type: No-code / Low-code

Complexity: Suitable for simple to moderate logic

Flexibility: Limited compared to coding

Use Case: Best for basic automation tasks

Maintenance: Easy to maintain and update

 👉🏻 Apex Trigger (Programmatic):

 Type: Code-based

Complexity: Handles complex business logic

Flexibility: Highly flexible and customizable

Use Case: Used for advanced logic and integrations

Maintenance: Requires a developer to manage

➡️ Before vs After Trigger

👉🏻 Before Trigger:

Execution Time: Runs before the record is saved to the database

Use Case: Used for validation and modifying field values

Database State: Changes are not yet committed

Example: Setting default values before saving

👉🏻 After Trigger:

Execution Time: Runs after the record is saved

Use Case: Used for sending notifications and updating related records

Database State: Changes are already committed

Example: Sending email after record creation


------------------------------------------------------------------------------------------------------------------------------------------------------------

4.Trigger Use Cases (College Management System)

a) Student Registration

Event: After Insert

Action: Send welcome email

b) Course Capacity Full

Event: After Update

Action: Notify faculty

c) Attendance Drop

Event: After Update

Action: Send warning notification

d) Fee Payment Completed

Event: After Update

Action: Update student status to "Active"

e) New Faculty Assigned

Event: After Insert/Update

Action: Notify students of the course

------------------------------------------------------------------------------------------------------------------------------------------------------------

5. Flow vs Trigger Decision

--> Simple email notification

Use: Flow

Reason: Easy to implement without code

--> Complex fee eligibility check

Use: Apex Trigger

Reason: Requires complex logic and conditions

--> Updating related records

Use: Flow

Reason: Can be handled declaratively

--> External API integration

 Use: Apex Trigger

Reason: Needs coding and external handling

--> Bulk data processing

Use: Apex Trigger

Reason: Better performance and control

------------------------------------------------------------------------------------------------------------------------------------------------------------

6. Query Examples (English)

Find all students enrolled in Course A

Find all courses handled by Faculty X

Find students with attendance below 75%

Find students who have not paid fees

Find courses with available seats

------------------------------------------------------------------------------------------------------------------------------------------------------------

7. Reflection

Why do enterprise systems need event-driven behavior?

-> Systems deal with large and continuous data

-> Immediate response to changes is required

-> Reduces manual work

-> Improves efficiency and accuracy

-> Enables real-time decision making

------------------------------------------------------------------------------------------------------------------------------------------------------------

Reflective Questions

1. Why do systems need triggers?

To automatically perform actions when data changes

2. Difference between polling and event-driven systems?

Polling: Continuously checks for updates

Event-driven: Responds only when an event occurs

3. Why are database queries important?

Help retrieve specific data efficiently

4. When should Flows be preferred over Triggers?

When logic is simple

When no coding is required

For quick automation

5. What problems happen if automation becomes too complex?

Difficult to maintain

Performance issues

Hard to debug

6. Why should developers think before automating?

Prevents errors at scale

Avoids unwanted actions

Maintains system performance

------------------------------------------------------------------------------------------------------------------------------------------------------------
