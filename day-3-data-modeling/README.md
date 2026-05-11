1. Difference Between App, Object, Record, and Field
⁠Term                        Meaning                                Example
App            Collection of related features and tabs      College Admission app
Object         Stores a type of data                        Student Object
Record         Single entry inside an object                Rahul’s student details
Field          Individual information in a record           Name, Phone Number

2. Standard                          vs            Custom Objects
Already provided by Salesforce                     Created by users
Common business data                               Business-specific data
Examples: Account, Contact, Opportunity            Examples: Student, Course
Cannot be fully removed                            Can be customized completely

3. College Data Model

Objects
* Student
* Course
* Admission
* Faculty

Relationships
* One student can apply for many admissions.
* One course can have many students.
* Faculty can manage multiple courses.


4. Formula Fields
   A Formula Field automatically calculates values based on other fields.

Example 1:
Calculate total fee after discount.
Total Fee = Course Fee - Discount
Example 2:
Display Full Name.
First Name + Last Name

5. Validation Rules
    Validation rules are used to stop users from entering incorrect data.

Example 1:
Phone number must contain 10 digits.
Rule:
If phone number length is not 10, show error.

Example 2:
Student age should be greater than 17.
Rule:
If age < 17, admission cannot be submitted.

6. Reflection: Why Structured Enterprise Data Matters
 In organizations like colleges or companies, large amounts of data are generated daily. If data is not structured properly, it becomes difficult to track records, generate reports, and make decisions. Structured data helps improve efficiency, reduces mistakes, supports automation, and allows users to quickly find important information. It also helps management analyze business performance and provide better services to customers or students.
