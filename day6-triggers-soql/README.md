1. What is SOQL?
SOQL stands for Salesforce Object Query Language. It is used in Salesforce to retrieve data from objects, similar to how SQL is used in databases. SOQL helps users fetch records like students, contacts, accounts, or opportunities based on specific conditions.

2. What is an Apex Trigger?
An Apex Trigger is a piece of code that runs automatically when certain actions happen in Salesforce, such as creating, updating, or deleting records. Triggers are used to automate complex business logic that cannot be handled only with configuration tools.

4. Your Trigger Use Cases (5 Examples)
1. Automatic Student ID Generation
Generate a unique student ID when a student record is created.
2. Set Count Update
Reduce available seats automatically after admission confirmation.
3. Admission Status Notification
Send notification to students when admission status changes.

5. Query Examples (English Query Ideas)
Example 1
Show all students who applied for Computer Science course.
Example 2
Find students whose admission status is approved.
Example 3
Display students with pending fee payment.

6. Reflection: Why Enterprise Systems React Automatically to Data Changes
Enterprise systems react automatically to data changes because organizations handle large amounts of information every day. Manual monitoring of every change is difficult and time-consuming. Automatic reactions help systems update records instantly, send notifications, maintain accuracy, and enforce business rules without human intervention. This improves efficiency, reduces errors, speeds up business processes, and ensures smooth communication between departments. Automation also helps organizations provide faster and more reliable services to customers or students.

Difference Between Before Trigger and After Trigger

A Before Trigger runs before a record is saved into the database. It is mainly used to validate data, update field values, or check conditions before saving the record. Since it works before saving, it is faster for modifying record values.

An After Trigger runs after the record is successfully saved in the database. It is mainly used for actions like sending emails, creating related records, updating other objects, or sending notifications. After triggers are useful when actions depend on the record being saved first.
