---
title: "Hugo Anyone"
date: 2017-12-22T16:28:06-05:00
draft: false
---

***12.22.2017***
### Hugo anyone?
### Finishing up the Discovery Filtering works
* unifying the filters
  - placing the filter init button and the filtering module in the same section of the DOM
  - giving them the same background colors so all the subcomponents are visually linked and unifying the controls
  - removing the second (and last button in the DOM ) close button and changing the filter to button to close when expanded
    + eliminates a DOM element and could close the tab loop
      * Q: _Should this close the loop or does the tab chain jump out of the filtering drop down and go right into the page results._
      * A: My initial instinct is no, but I think its a reasonable question to ask
  - Tasked w/ moving the search results count below the results sorter & filter buttons
