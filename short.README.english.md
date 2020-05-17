# COVID19, a country comparison

Presenting data to compare how some western countries fight with coronavirus - Short version  
<br />  

----

[What you may find here](./short.README.english.md#what-you-may-find-here)  
[Basics](./short.README.english.md#basics)  
[Chart & discussion](./short.README.english.md#charts--discussion)  
[The result](./short.README.english.md#the-result)  
[Expand](./short.README.english.md#expand)  
  
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

TV and newspapers bombard us daily with industrial quantities of numerical data and always end up indicating the nation that has the largest number of deaths.  
First it had been China, then Italy, then again the United States.  
  
To check, given that the [worldometers](https://www.worldometers.info/coronavirus/#countries) site collects numbers from all over the world that even TV offers us, we can take the numerical data from it and put them in a graph:

<img src="https://github.com/fpirri/covid19/raw/master/history/images/archive/2020-04-28%20Total%20Deaths%20raw%20data.png">

As you can see, at the end of April the USA was the most affected country (**<- it's a lie !!**).

Let us immediately make some considerations that will clarify how wrong this way of providing information is.

* First:
    * you will never compare the number of deaths in the state of Andorra with those in all the United States of America.
* Second:
    * it is misleading to compare the numbers of a country where the epidemic is starting with one in which the epidemic is at its peak.

So let's see what we can do.
 <br />

----

# Charts & discussion
----  

According to the first observation made above, we will be able to compare the countries by transforming the pure numerical data into a relationship with the total population of the country in question.  
For example, we can count the number of deaths per million inhabitants.  
For the second observation we should also count for each country the days from the beginning of the epidemic, at least until the climax of the epidemic itself.  
Here we define the day when a country reaches 5 deaths per million inhabitants as the beginning of the epidemic. The choice is made to give a sufficiently similar statistical validity for all countries.  
Others choose the day of the first death.  
I believe that the day of the first death is very unreliable, also given the tendency in all countries to minimize the beginning of the epidemic.  
NOTE: There hasn't been a single country where the leader hasn't minimized the outbreak.  

The graph we had seen before becomes now:

<img src="https://github.com/fpirri/covid19/raw/master/history/images/archive/2020-04-28%20Countries%20Total%20Deaths%20per%20Million.png">
  
As you can see, things change a lot but accurate comparisons remain difficult.  
  
So we decide to use the same data to see the daily trend of deaths per million inhabitants in the various countries. We use a seven-day average to eliminate periodicity in data collection in many countries.
We get the following graph:
<img src="https://github.com/fpirri/covid19/raw/master/history/images/archive/2020-04-28%20Countries%20Daily%20Deaths%20per%20Million.wma.all.png">

As can be seen, Spain has a number of daily deaths almost always higher than all the others.  
We also see that Germany almost always has far fewer daily deaths than all the others.  
For other countries there are mixed situations and it is not clear who is better than another.  
  
Taking a cue from what is often done to arrive at a numerical ranking, we assign a set of points to the various countries using the following parameters:
* total deaths per million throughout the period;
* peak value of daily deaths;
* total duration of the crisis period.
  
We put, in the same spreadsheet used for the graphs, some tables to calculate a score for each country.

The procedure used to achieve the result is illustrated in detail in the [extended version](https://github.com/fpirri/covid19/blob/master/README.english.md) of the comparison.  
  
Let's see below the calculated ranking.  

----

<br />

The Result
----  

 With the spreadsheet available on the site you get to the following ranking of countries, calculated on May 11th, 2020:   

-    Germany 60
-    USA 46
-    Sweden 38
-    France 25
-    UK 24
-    Italy 16
-    Spain 10
  
The numerical analysis confirms what we had seen on the graph, that is, on May 11th Germany is the best and Spain the last. The sheet will be recalculated daily until 30 June 2020.  
    
The ranking measures the differences between countries quantitatively better than the visual examination of the graphs, so I may say that the first objective of the reflection is achieved.  
However, I am far from satisfied because the ranking found does not agree with the severity of the measures that the various governments have taken.  
  
Masks, gloves and social distancing have been the answer to the virus in many parts of the world.
Experts warn that avoiding contact with the infected greatly reduces the infection. Logic says they are right.
  
Yet the data (and the consequent numerical ranking) are not entirely congruous:
* Italy carried out the most drastic measures first, followed them well, and finds itself penultimate;
* Sweden refused to apply restrictive measures, however it is far better than Spain, Italy, France and the United Kingdom;
* The USA of the reviled Trump is better than all the others above, a few points from Germany;
* Germany is the best, however the measures it has taken have not been the hardest at all.
  
The same logic as before tells me that **there is something that I don't know** but that has a great effect.  
  
I believe *something* can only be found with science.
  
**A great deal of scientific research effort will be needed to provide convincing answers.**  

Once the fear is over, will the effort be made?  
The answer depends on all of us.  
  
----

<br />

EXPAND
----  

An [extended version](https://github.com/fpirri/covid19/blob/master/README.english.md) is available on this site.  
It examines the data and presents the criteria with more details.  
  
The site also contains a LibreOffice Calc [spreadsheet](https://github.com/fpirri/covid19/raw/master/covid19%20evaluation.ods) that can be downloaded and used for your own data experiments.  
There is also an [excel version](https://github.com/fpirri/covid19/raw/master/history/last/covid19%20evaluation.xlsx) that I try to keep up to date. The version is saved by LibreOffice Calc, and full compatibility is not guaranteed.

