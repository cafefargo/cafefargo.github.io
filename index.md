---
title       : Developing Data Products Course Project - Slidify
subtitle    : 
author      : cafefargo
job         : 
framework   : io2012        # {io2012, html5slides, shower, dzslides, ...}
highlighter : highlight.js  # {highlight.js, prettify, highlight}
hitheme     : tomorrow      # 
widgets     : []            # {mathjax, quiz, bootstrap}
mode        : selfcontained # {standalone, draft}
---

## Calculate Combinations of People to ride in your new car

You are thinking about buying a new car.  Since you are such a popular person and adored by all, you realize when you drive the new car home, the whole neighborhood will be in your driveway, gathering around your car to check out your new ride.  Before you know it, everyone will want a ride in your new car.  Also, since the people in your neighborhood are highly sociable, you know each neighbor will want to ride with all the other neighbors (if physcially possible), even if that means riding in your new car more than once.  You have not decided yet what size car you are going to get.  Will you get the little sports car with room for one passenger (not including the driver)?  Will you just say the heck with it and buy a school bus so you only have give your neighbors one ride?  Will you get something in between?  This application will allow you to specify how many people want to ride in your new car, how many passenger seats your car has, and then calculates the number of possible combinations of passengers.  This determines how many separate rides you have to give to your neighbors to satisfy all the combinations, where order does not matter.

---
## How it works

Enter total people who want to ride in the car.

Enter the number of passenger seats in the car (not including the driver's seat).  Then, click Submit.

Note: If a number entered is not an integer, it will be rounded (i.e. 1.6 becomes 2, 1.4 becomes 1).
Negative signs are ignored.

It will return the number of possible combinations (where order does not matter) for all the passengers, given the number of people who want a ride and the number of passenger seats.


---

## Example

Assume 5 people want a ride.

Assume your car has 3 passenger seats (not including the driver).


```r
choose(5,3)
```

```
## [1] 10
```

We see there are 10 combinations that have been calculated and displayed, using an R expression, where order does not matter.  Therefore, you need to give 10 rides to satisfy all the possible combinations.

---

## Key reasons to get this application

It's free.

It does not track you.

Oh yeah, did I mention it's free?

