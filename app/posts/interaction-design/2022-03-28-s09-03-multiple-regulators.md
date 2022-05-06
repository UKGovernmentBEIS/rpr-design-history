---
  title: Handling of multiple regulators
  date: 2022-03-28
  related:
    items:
    - text: Beta sprint 9 prototype
      href: https://rpr-prototype.herokuapp.com/#beta-sprint-9
   
---

## Overview 

Our current design can handle up to two regulators per profession. However, from the latest data we found that there are:
* 284 professions have one regulator
* 16 professions have two regulators
* 6 legal and financial professions with 3 to 6 regulators
* 6 professions related to fluorinated gases and ozone depleting gases, with 7 to 13 regulators
* 1 profession, Chartered Environmentalist, with 25 regulators

[![View image in full size](01.png)](01.png)*Regulators section on the current profession's page*

[![View image in full size](02.png)](02.png)*Current design on the adding professions journey* 

--- 

### 7 types of regulators

We had a couple of discussions with Leo and iterated on this ideas. As a result, we agreed to have these 7 types of regulators:
* Primary Regulator
* Additional Regulator
* Chartered Body
* Qualifying Body
* Oversight Body
* Enforcement Body
* Awarding Body

[![View image in full size](03.png)](03.png)*Regulator types and some examples*

--- 

### Iterated design

Based on the regulator types, we came up with an iterated design:
* Two tiers of regulator type
* Enforcement bodies (& awarding bodies) are tier-2 regulators and will be displayed in Qualifications
* Only tier-1 regulators will have the editing right

[![View image in full size](04.png)](04.png)*Public facing profession's page*

And we also prototyped the design to cover all 8 different scenarios:
* One Primary regulator
* One Chartered body
* One Primary regulator and one Additional regulators
* One Primary regulator, several Qualifying bodies and several Enforcement bodies
* Several Qualifying bodies
* Several Qualifying bodies and one Oversight body
* Several Chartered bodies
* One Chartered body and many Awarding bodies

--- 

### Links

[8 different scenarios for multiple regulator design](https://rpr-prototype.herokuapp.com/#beta-sprint-9)
