# Administrator

This document covers why there is an administrator user role that it's not covered on the Role Analysis document and it's use cases,

##About

As we mentioned earlier, the Role Analysis document only covered 4 user roles *(student, institution, validator and company)* who interact with the application. So why now there is a new unmentioned Role? Well, thats because it's ment to deal with edge cases where the application by itself can't find a solution.

Usually, this role can be left to a  database/system administrator or similar but considering the nature of the project, we decided that it will be better to have another role, where a non technical user can fix those edge cases.

To reduce security risks, the administrator perk is granted by the database administrator, and can be granted to any of the existing roles.

##Tasks

### Maintaining personal skills.

This is the clearest use case for the Administrator role. Personal skills are keyword selected from a list of predefined words. Those will rarely change but there's always a posibility where the application needs a new personal skill.

### Force a profile to be private.

Let's imagine that a student had a security breach and his password to talented europe was compromised and a malicious user edits the student profile adding inapropiate content. Aside from contacting the student, since we cannot leave the inapropiate content public, we need to be able to make a student profile private. 

### Block/Ban malicious users.

While we're going to implement countermeasures to avoid spambots and similar, there's always a chance where a malicious user could setup a company account with for example an ad/message instead of a company name and start spamming students with contact notifications. The administrator should be able to delete/block those fake companies.

### Devalidate a student.

A student inputs some incorrect data when he creates his profile, because of any reason, the validator doesn't detect it and passes the data as correct.

While the application is going to allow the institution to rollback a validation within a certain timeframe, its possible that this mistake goes unnoticed for a higher time, or the institution itself disappears, or is too busy to do anything about it.
