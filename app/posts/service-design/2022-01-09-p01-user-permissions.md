---
  title: Central admin and regulator users will have different permissions
  date: 2022-01-09
   
---

## Overview 

After a lot of exploration, we designed a new "Draft and publish" approach to replace the original approval process. 

--- 

### Permissions so far

We had a lot of discussion on how to group permissions into regulator roles and central roles. 

[![View image in full size](01.png)](01.png)*Permissions so far*

--- 

### Iteration

We iterated on the current design and created two improved journeys, for:
* Administrators in the central organisation can create users in the own organisation and in a regulator, while administrators in a regulator can only create users in their own organisation
* Users in the central organisation can have additional permissions over those in a regulator

Having two paths means we ask the right questions in the right order.


[![View image in full size](02.png)](02.png)*Managing users - central admin vs Regulator users*

--- 

### Role selection

Within the central organisation, users can be:
* Editors who can edit regulator and profession information
* Registrars who can also create and link regulators and professions
* And Administrators who can also onboard and manage users
Users in the central organisation can act across all regulators and professions.

[![View image in full size](03.png)](03.png)*Role selection - Central admin*


Within a regulator, users can be Editors or Administrators.
* They can only act on their own regulator information and their own professions.
* So they don’t have the Registrar role

We’ve begun some implementation work which should be finished next sprint and ready to test with administrators.

[![View image in full size](04.png)](04.png)*Role selection - Regulator users*
