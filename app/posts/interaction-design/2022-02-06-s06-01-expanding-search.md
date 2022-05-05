---
  title: Expanding search
  date: 2022-02-06
  related:
    items:
    - text: Beta sprint 6 prototype
      href: https://rpr-prototype.herokuapp.com/#beta-sprint-6
   
---

## Overview 

Two key issues about keyword search on the public facing side:
* People used different words for keyword search
* Absence of content for the case of zero search results

[![View image in full size](01.png)](01.png)*Keyword search*

[![View image in full size](01.png)](01.png)*Zero search results*

--- 

### Design collaboration

In our workshop, we:
* Analyzed the constraints of our current keyword search functions
* Looked at how DfE Teaching vacancies and Civil Service Jobs handle keyword searches
* Brainstorming on quick wins and long-term approaches

[![View image in full size](03.png)](03.png)*Possible improvements on search*

--- 

### Important decisions

We decided to implement the following quick wins:
* Implement elastic search for professions
* Adding keywords field to professions
* Move sector filters above nations for professions
* Improve the wordings when there's no search results for professions


[![View image in full size](04.png)](04.png)*Zero search results message*

--- 

### Links

[Design collaboration on search - Miro board](https://miro.com/app/board/uXjVOaZc0VI=/?moveToWidget=3458764518178575548&cot=14)
