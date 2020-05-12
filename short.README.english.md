# COVID19, a country comparison

Presenting data to compare how some western countries fight with coronavirus - Short version  
<br />  

----

[What you may find here](./short.README.english.md#what-you-may-find-here)  
[Basics](./short.README.english.md#basics)  
[Chart & discussion](./short.README.english.md#charts--discussion)  
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
  
To check, given that the worldometers site collects numbers from all over the world that even TV offers us, we can take the numerical data from it and put them in a graph:

<img src="https://github.com/fpirri/covid19/raw/master/history/images/archive/2020-04-28%20Total%20Deaths%20raw%20data.png">

As you can see, at the end of April the USA was the most affected country (**<- it's a lie !!**).

Let us immediately make some considerations that will clarify how wrong this way of providing information is.

* First point: you will never compare the number of deaths in the state of Andorra with those in all the United States of America.
* Second point: it is misleading to compare the numbers of a country where the epidemic is starting with one in which the epidemic is at its peak.

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
  
As you can see, the US is moving back strongly. To begin making a comparison, we make a graph of deaths on each single day:

<img src="https://github.com/fpirri/covid19/raw/master/history/images/archive/2020-04-28%20Countries%20Daily%20Deaths%20per%20Million.wma.all.png">

The above graph was normalized using a seven day weighted moving average. The worldometers site mentioned above presents data separated by country with a simple moving average over three days.

However, we must note that the visual comparison on a single chart for seven countries is not easy to do.

----

<br />

EXPAND
----  

https://github.com/fpirri/covid19/raw/master/covid19%20evaluation.ods
An [extended version](https://github.com/fpirri/covid19/blob/master/README.english.md) is available on this site.  
It examines the data and presents the criteria with more details.  
  
The site also contains a LibreOffice Calc [spreadsheet](https://github.com/fpirri/covid19/raw/master/covid19%20evaluation.ods) that can be downloaded and used for your own data experiments.  
There is also an excel version that I try to keep up to date. The version is saved by LibreOffice Calc, and full compatibility is not guaranteed.

