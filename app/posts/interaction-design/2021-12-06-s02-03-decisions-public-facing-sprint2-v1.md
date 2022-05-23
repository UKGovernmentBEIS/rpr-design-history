---
  title: Public facing search design decisions (sprint 2)
  date: 2021-12-06
---

## Overview 

We had a co-design session for the public facing search (professions or RAs) and key design decisions made are as follows.

--- 

### User flow design

We tend to believe users would like to see a listing of professions (or RAs) even before they enter anything in the keyword search and filters, so we created `user flow 1` in our prototype. However, we also want to test whether a filters-only page will be less confusing for users, so we created `user flow 2` in the prototype. 

Our devs will build `user flow 1` first and we will see usability testings result to decide whether we want to change it. 


[![View image in full size](01.png)](01.png)*Public facing - Finding professions user flow*

[![View image in full size](02.png)](02.png)*Public facing - Finding RAs user flow*

[![View image in full size](prototype-index-page.png)](prototype-index-page.png)*Prototype index page*

--- 

### Filtering tools

In the co-design session, we have many suggestions about what filtering tools should we provide to our users. After taking available space on the page into considerations, we decided to implement three filtering tools for now:
* keyword search (profession / RA)
* nations
* industry / sector

And it is the same for both `finding professions` and `finding RAs`. We will iterate based on UR findings. 

--- 

### Screen size

We agreed that the public facing service would be mostly for mobile users. There we decided to adopt a mobile first approach when designing the interface.

[![View image in full size](03.png)](03.png)*Public facing - devices*
