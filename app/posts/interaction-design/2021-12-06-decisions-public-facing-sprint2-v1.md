---
  title: Public facing search design decisions (sprint 2 - version 1)
  date: 2021-12-06
  related:
    items:
    - text: Beta sprint 2 prototype
      href: https://rpr-prototype.herokuapp.com/#beta-sprint-2
    - text: DevOps 1772 Find information and data
      href: https://dev.azure.com/AmakaMgbeji/Regulated%20Professions%20Register%20%28RPR%29%20-%20BETA%20PHASE/_backlogs/backlog/Regulated%20Professions%20Register%20%28RPR%29%20-%20BETA%20PHASE%20Team/Stories/?showParents=true&workitem=1772
    - text: DevOps 1924 Search professions
      href: https://dev.azure.com/AmakaMgbeji/Regulated%20Professions%20Register%20%28RPR%29%20-%20BETA%20PHASE/_backlogs/backlog/Regulated%20Professions%20Register%20%28RPR%29%20-%20BETA%20PHASE%20Team/Stories/?showParents=true&workitem=1924
    - text: DevOps 1828 2.1.1 RA Search journey - by name - Search screen
      href: https://dev.azure.com/AmakaMgbeji/Regulated%20Professions%20Register%20%28RPR%29%20-%20BETA%20PHASE/_backlogs/backlog/Regulated%20Professions%20Register%20%28RPR%29%20-%20BETA%20PHASE%20Team/Stories/?showParents=true&workitem=1828
    - text: DevOps 1837 2.2.1 RA Search journey - by prof - Search screen
      href: https://dev.azure.com/AmakaMgbeji/Regulated%20Professions%20Register%20%28RPR%29%20-%20BETA%20PHASE/_backlogs/backlog/Regulated%20Professions%20Register%20%28RPR%29%20-%20BETA%20PHASE%20Team/Stories/?showParents=true&workitem=1837
---

## Overview 

We had a co-design session for the public facing search (professions or RAs) and key design decisions made are as follows.

### User flow design

We tend to believe users would like to see a listing of professions (or RAs) even before they enter anything in the keyword search and filters, so we created `user flow 1` in [our prototype](https://rpr-prototype.herokuapp.com/#beta-sprint-2). However, we also want to test whether a filters-only page will be less confusing for users, so we created `user flow 2` in [the prototype](https://rpr-prototype.herokuapp.com/#beta-sprint-2). 

Our devs will build `user flow 1` first and we will see usability testings result to decide whether we want to change it. 


[![View image in full size](01.png)](01.png)*Public facing - Finding professions user flow*

[![View image in full size](02.png)](02.png)*Public facing - Finding RAs user flow*

[![View image in full size](prototype-index-page.png)](prototype-index-page.png)*Prototype index page*

### Filtering tools

In the co-design session, we have many suggestions about what filtering tools should we provide to our users. After taking available space on the page into considerations, we decided to implement three filtering tools for now:
* keyword search (profession / RA)
* nations
* industry / sector

And it is the same for both `finding professions` and `finding RAs`. We will iterate based on UR findings. 

### Screen size

We agreed that the public facing service would be mostly for mobile users. There we decided to adopt a mobile first approach when designing the interface.

[![View image in full size](03.png)](03.png)*Public facing - devices*


### Links

Co-design information is on this [Miro board](https://miro.com/app/board/o9J_lkEVwtI=/?moveToWidget=3458764514455848497&cot=14).

[Beta sprint 2 prototype](https://rpr-prototype.herokuapp.com/#beta-sprint-2)
