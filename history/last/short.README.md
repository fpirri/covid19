# COVID19, a country comparison

Presenting data to compare how some western countries fight with coronavirus  
<br />  

----

[What you may find here](https://github.com/fpirri/covid19/tree/master/history/last#what-you-may-find-here)  
[Basics](https://github.com/fpirri/covid19/tree/master/history/last#my-first-steps)  
[Chart & discussion](https://github.com/fpirri/covid19/tree/master/history/last#lets-analyze-)  
[Expand](https://github.com/fpirri/covid19/tree/master/history/last/#a-second-step)  
  
----
   
<br />

----  

What you may find here
----  

* A way to look at COVID19 data
* Basic hypotesys for a more meaningfull exploration of data
* Analysys of available data about a few western countries
* A few charts to compare data in a few countries
* Suggestion for a more in-depth exploration
 <br />

----

# Basics
----  

I looked for data on the website https://www.worldometers.info/coronavirus/#countries which presents a lot of data on almost all the nations of the world.  

The site places a lot of emphasis on the number of sick and healed, but also on the total deaths in each individual country.  
TV follows the same format and assigns the 'primacy' to the country with the highest number of deaths. Now it's up to the USA.  
The total number of deaths seems very important, so I took the data from the site and presented it on a single chart to better appreciate the differences.  

 <br />

----

# Charts & discussion
----  





[==> DETAILS: why to look at death](https://github.com/fpirri/covid19/tree/master/history/last/#details-why-to-look-at-death)

The chart collects the following countries: Italy, Spain, France, Sweden, UK, USA and Germany.  

<img src="https://github.com/fpirri/covid19/raw/master/history/images/archive/2020-04-28%20Total%20Deaths%20raw%20data.png">

Looking at the chart, the primacy is immediately assigned to the USA, which dominates all the other countries.  
But is that right?  
It does not seem correct to me to directly compare what happens in a country of 331 million inhabitants with what happens in a country of 10 million inhabitants like Sweden.  
Following Mats's thoughts, I then reported the number of deaths per million inhabitants on the chart.  

<img src="https://github.com/fpirri/covid19/raw/master/history/images/archive/2020-04-28%20Total%20Deaths%20per%20Million%20raw%20data.png">
   
Now USA appears to be the second least affected country among those examined.  
However, there is something important to consider: it does not seem fair to compare countries like Spain, where the pandemic is nearing its peak with countries where it has just started.
So, we should compare countries by counting the times since the start of the pandemic in each country.  
But wait, how do you find the departure date?  
One possible choice is the date of the first victim of the disease.  
 However this date appears not very reliable.
If we want to compare statistical events with each other we must use a characterizing moment that is quite similar for everyone.  
In a totally arbitrary way I choose the moment in which the country exceeds 5 deaths per million inhabitants.   
For the moment, I will postpone a discussion on this criterion further on. 
[==> DETAILS: Why 5 death per Million](https://github.com/fpirri/covid19/tree/master/history/last/#details-why-5-death-per-million)  

We therefore define 'start' the day on which each country exceeds 5 dead per million and align the data of each country from the start forward. We thus obtain the following chart, in which the data of each country starts for each one from its 'start'.
The X axis will then be called 'Days from start'.  
The result is shown below.

<img src="https://github.com/fpirri/covid19/raw/master/history/images/archive/2020-04-28%20Countries%20Total%20Deaths%20per%20Million.png">
  
As you can see, the chart remains very similar to the previous one, but with countries overlapping with respect to their 'start' day.  
Is there anything interesting in what we see?  
In my opinion, we identify Spain as the most affected country and Germany as the least affected by the disease.
The difference is truly remarkable: on the 30th day Spain presents 5.3 times the deaths per million of Germany.  

Furthermore, some countries appear to have similar developments,
Italy, France and UK, closer to Spain and USA and Sweden closer to Germany.  
However, it appears difficult to extract comparative data from what is seen in the chart.  
The worldometers website also reports data on daily deaths.
These data can also be obtained from the chart above, as a difference of the totals of two successive days, as it is easy to verify.  
So, we get the next chart.

<img src="https://github.com/fpirri/covid19/raw/master/history/images/archive/2020-04-28%20Countries%20Daily%20Deaths%20per%20Million.all.png">

Oh no! There is too much data to understand something.
So, let's leave Spain and Germany as extremes and add France only, to see what we get.

<img src="https://github.com/fpirri/covid19/raw/master/history/images/archive/2020-04-28%20Countries%20Daily%20Deaths%20per%20Million.SFG.png">

Humm ...  
You see, but it's not clear what.
Let's try with the Sweden and USA group.

<img src="https://github.com/fpirri/covid19/raw/master/history/images/archive/2020-04-28%20Countries%20Daily%20Deaths%20per%20Million.SSUG.png">

Damn ...   
There are periodicities in the data that only lead to confusion. It appears that various countries enter data weekly. What could we do to improve the situation?  
After a few experiments, a satisfactory result is obtained with a moving weighted average (Details below).  
NOTE: As of May 5, the worldometers website added the 3-day moving average on the daily death chart.

<img src="https://github.com/fpirri/covid19/raw/master/history/images/archive/2020-04-28%20Countries%20Daily%20Deaths%20per%20Million.wma.all.png">

Although all seven countries are above, the confusion is significantly lessened.  
So let's show the first group.

<img src="https://github.com/fpirri/covid19/raw/master/history/images/archive/2020-04-28%20Countries%20Daily%20Deaths%20per%20Million.wma.SIFUG.png">

It is confirmed that the first group, Italy with France and the UK, is fairly homogeneous, considering that at the beginning and at the end of the period the moving average is less effective.  
Let's move on to the second group, Sweden and USA.

<img src="https://github.com/fpirri/covid19/raw/master/history/images/archive/2020-04-28%20Countries%20Daily%20Deaths%20per%20Million.wma.SSUG.png">

Considering the weekly periodicity, very marked in Sweden, the second group also appears fairly homogeneous.

All the graphs present an initial phase of rapid growth. Then growth slows down to a maximum, followed by a slow descent.
The main differences concern the size of the maximum, with a worse / better ratio of about 4 times.  
The ascent duration seems surprisingly similar for all countries, with the peaks a few days apart. On TV I had received a message of great difference from one country to another.  

**Do I reached an answer?**  

NO, not really.  
I now have many more question to answer, such as:  
Why are the curves so similar?  
Why do countermeasures seem to have little influence on the times?  
Why is the descent much slower than the ascent?  
What other parameters should I look at immediately?  
What should we have done and we haven't done enough?  
Anyway, I will start next section with the most important new question in my mind.

----

<br />

EXPAND

----  


