---
Title: Loading times on travel webpages
Description: This is my report about loading times on websites.
Template: report
---

Loading times on travel webpages
=======================

This project looks at the loading times on travel webpages are and discuss options on how to improve them (if possible). 

Urval
-----------------------

I chose to continue this from Kmom04's Style on Swedens best travel websites available <a href="%base_url%?analysis/01_colors">here</a> so the webpages are the same as in there. In that the chosen travel websites are <a href="https://www.skyscanner.se/">skyscanner.se</a> , <a href="https://www.momondo.se/">momondo.se</a>  and <a href="https://www.flygresor.se/">flygresor.se</a>.

![momondo_website](%base_url%/image/momondo.png?w=150&h=150)
![flygresor_website](%base_url%/image/flygresor.png?w=150&h=150)
![skyscanner_website](%base_url%/image/skyscanner.png?w=150&h=150)

Metod
-----------------------

I chose three of each webpage's top sites. For each I measured their page speed with PageSpeed insights and then I used devtools to see the loading times and sizes.

Skyscanner pages:
<a href="https://www.skyscanner.se/flyg">Sida 1</a>
<a href="https://www.skyscanner.se/hotell">Sida 2</a>
<a href="https://www.skyscanner.se/hyrbil">Sida 3</a>

Flygresor pages:
<a href="https://www.flygresor.se/reseguider/">Sida 1</a>
<a href="https://hyrbil.flygresor.se">Sida 2</a>
<a href="https://www.flygresor.se/sista-minuten">Sida 3</a>

Momondo pages:
<a href="https://www.momondo.se/stays">Sida 1</a>
<a href="https://www.momondo.se/hyrbil">Sida 2</a>
<a href="https://www.momondo.se/paketresor">Sida 3</a>

Resultat
-----------------------

<a href="https://docs.google.com/spreadsheets/d/1jcZfalnuJr-jJhuNwmhXVQ3hfs7XGTKaROPleUMrbOU/edit?usp=sharing">Table over data</a>

<iframe class=iframe src="https://docs.google.com/spreadsheets/d/e/2PACX-1vSm7lOK-na0CXuxhC2awEpivkq1UKPiQtRS5pYoB5ZoCUf1n-31SesUb6VpwIYXU0xXq4lrRpj4LIoU/pubhtml?widget=true&amp;headers=false"></iframe>

The page speed from PageSpeed Insights show that the best one is flygresor.se, skyscanner second and last by a lot is momondo even though skyscanner works best on desktop. When it comes to load times form the analysis on the sites the lowest times where form momondo and the other two were quite similar. When it comes to sizes momondo has the smallest sizes for the pages and next is flygresor which are only a little better and last comes Skyscanner. 

Analys
-----------------------
I think that skyscanner could improve their sizes on their websites since they are quite larger than the other two. maybe which could be done by opimizing pictures for example. When it comes to flygresor it seemed like they had a good page speed over all and their values seems to be a middle ground. They had a perfect score for desktop on PageSpeed Insights and their next step would be to improve the ones for mobile as well but their mobile score is better than both the other's desktop score so it is not a bad to begin with. When it comes to momondo they should look into loaded resources which seems to be getting quite high but also their scores are very low from PageSpeed Insights for both mobile and desktop. They did not pass the test and it seemed to be because of Cumulative Layout Shift (CLS) even though other things like blocking time also impacted but when it comes to what differentiated them the most from the others (mainly skyscanner because flygresor had as good as perfect score on everything) it was definitely CLS which skyscanner had under control at none at all actually (even better than flygresor). Improvements that commonly could be done is look over the sizes of things which momondo seems to be best at since they have managed to keep their scores the lowest in that regard. A common effective way to reduce size is to make sure the correct file format is used then also find a good balance with size and quality. 

When it comes to ranking them I would in terms of load time put momondo first but since the score was so bad from PageScanner I would say that Flygresor takes the top, then Momondo and last skyscanner. I feel like flygresor kept being the middle row where it had values in between the two other ones which had the worst values in different places. This goes to show how good it can be to find a health middle ground. 

I think that what you perceive as fast and slow is relative to what you are used to and I have been used to waiting a while with slow internet and an old computer which probably has affected my tolerance for long loading times. However, you will notice quickly when pages are slower than others. I think that loading times that are getting over 2 - 2.5 seconds are noticeably longer than other pages. For these pages I found them to be working but okay but momondo did only qualify as fast since their loading times were okay by that standard.


Referenser
-----------------------


Övrigt
-----------------------

Ingrid Eriksson

