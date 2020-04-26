# Understanding COVID19

A discussion about how some western countries fight with coronavirus  
<br />  

----

[What this document discuss](https://github.com/fpirri/covid19/tree/master/history/2020-04-25#what-this-document-discuss)  
[What you may find here](https://github.com/fpirri/covid19/tree/master/history/2020-04-25#what-you-may-find-here)  
[Where to start](https://github.com/fpirri/covid19/tree/master/history/2020-04-25#where-to-start)  
[A second step](https://github.com/fpirri/covid19/tree/master/history/2020-04-25#a-second-step)  
[How to contribute](https://github.com/fpirri/covid19/tree/master/history/2020-04-25#how-to-contribute)  
  
----

<br />

What this document discuss
----  

* This section is under construction

----

<br />

What you may find here
----  

* The amount of information you get in a single day regarding coronavirus is overwelming: what should you look at ? 
* Is there a way to use data available on the web to understand differences from a country to the next ?
* If the data we have are not reliable, can we, now or in the future, improve them in some way?
* Governments have acted against COVID19 at different times with different actions, what consequences, if there have been, can be highlighted by the data ?
* What do we have to prepare to act against the next flu ?
 <br />
  

----



Where to start
----  

It is really very difficult to understand what is happening in our world because of the coronavirus! 
This is an attempt to dispel the fog caused by the numbers that are thrown to us many times a day by the various news programs. The idea was born from a discussion on the following forum: https://e-catworld.com/2020/03/27/covid-19-thread-3-26-2020-mats-lewan-on-the-case-of-sweden/
  
Mats Lewan looked at the number of deaths in any given day in several countries and shared is thoughts in the blog.  
So I looked for data on the website https://www.worldometers.info/coronavirus/#countries which presents a lot of data on almost all the nations of the world.  
The site places a lot of emphasis on the number of sick and healed, but also on the total deaths in each individual country.  
TV follows the same format and assigns the 'primacy' to the country with the highest number of deaths. Now it's up to the USA.  
The total number of deaths seems very important, so I took the data from the site and presented it on a single graph to better appreciate the differences.  
The graph collects the following countries: Italy, Spain, France, Sweden, UK, USA and Germany.  

<img src="https://github.com/fpirri/covid19/raw/master/history/images/2020-04-25%20Total%20Deaths%20raw%20data.png">

Looking at the graph, the primacy is immediately assigned to the USA, which dominates all the other countries.  
But is that right?  
It does not seem correct to me to directly compare what happens in a country of 331 million inhabitants with what happens in a country of 10 million inhabitants like Sweden.  
Following Mats's thoughts, I then reported the number of deaths per million inhabitants on the graph.  

<img src="https://github.com/fpirri/covid19/raw/master/history/images/2020-04-25%20Total%20Deaths%20per%20Million%20raw%20data.png">
   
Now USA appears to be the second least affected country among those examined.  
However, there is something important to consider: it does not seem fair to compare countries like Spain, where the pandemic is nearing its peak with countries where it has just started.
So, we should compare countries by counting the times since the start of the pandemic in each country.  
But wait, how do you find the departure date?  
One possible choice is the date of the first victim of the disease.  
 However this date appears not very reliable.
If we want to compare statistical events with each other we must use a characterizing moment that is quite similar for everyone.  
In a totally arbitrary way I choose the moment in which the country exceeds 5 deaths per million inhabitants.   
For the moment, I will postpone a discussion on this criterion further on.  
We therefore define 'start' the day on which each country exceeds 5 dead and align the data of each country from the start forward. We thus obtain the following graph, in which the data of each country start for each from its 'start'.
The X axis will then be called 'Days from start'.  
The result is shown below.

<img src="https://github.com/fpirri/covid19/raw/master/history/images/2020-04-25%20Countries%20Total%20Deaths%20per%20Million.png">
  
As you can see, the graph remains very similar to the previous one, but with countries overlapping with respect to their 'start' day.  
Is there anything interesting in what we see?  
In my opinion, we identify Spain as the most affected country and Germany as the least affected by the disease.
The difference is truly remarkable: on the 30th day Spain presents 3.7 times the deaths per million of Germany.  

Furthermore, some countries appear to have similar developments,
Italy, France and UK, closer to Spain and USA and Sweden closer to Germany.  
However, it appears difficult to extract comparative data from what is seen in the graph.  
The worldometers website also reports data on daily deaths.
These data can also be obtained from the graph above, as a difference of the totals of two successive days, as it is easy to verify.  
So, we get the next graph.

<img src="https://github.com/fpirri/covid19/raw/master/history/images/2020-04-25%20Countries%20Daily%20Deaths%20per%20Million.all.png">

Oh no! There is too much data to understand something.
So, let's leave Spain and Germany as extremes and add France to see what we get.

<img src="https://github.com/fpirri/covid19/raw/master/history/images/2020-04-25%20Countries%20Daily%20Deaths%20per%20Million.SFG.png">

Humm ...  
You see, but it's not clear what.
Let's try with the Sweden and USA group.

<img src="https://github.com/fpirri/covid19/raw/master/history/images/2020-04-25%20Countries%20Daily%20Deaths%20per%20Million.SSUG.png">

Well.   
There are periodicities in the data that only lead to confusion. It appears that various countries enter data weekly. What could we do to improve the situation?  
After a few experiments, a satisfactory result is obtained with a moving weighted average (Details below).

<img src="https://github.com/fpirri/covid19/raw/master/history/images/2020-04-25%20Countries%20Daily%20Deaths%20per%20Million.wma.01.png">

Although all seven countries are above, the confusion is significantly lessened.  
So let's show the first group.

<img src="https://github.com/fpirri/covid19/raw/master/history/images/2020-04-25%20Countries%20Daily%20Deaths%20per%20Million.wma.02.png">

It is confirmed that the first group, Italy with France and the UK, is fairly homogeneous, considering that at the beginning and at the end of the period the moving average is less effective.  
Let's move on to the second group, Sweden and USA.

<img src="https://github.com/fpirri/covid19/raw/master/history/images/2020-04-25%20Countries%20Daily%20Deaths%20per%20Million.wma.03.png">

Considering the weekly periodicity, very marked in Sweden, the second group also appears fairly homogeneous.

----

<br />

A second step
----  

* This section is under construction

----
<br />  

----

<br />

How to contribute
----  

* If you like, you can 'open an issue' on github (2nd element in the top menu)  
* I will post a link to this document on the forum: https://e-catworld.com/
You can comment there, if you like

----
<br />  

----



PLEASE NOTE: this is WORK IN PROGRESS
===

This document is very disorganized: I am trying to coordinate my thoughts, but I cannot find a common thread in the many things I read online.
I need help. Do you have any suggestion?
<br />


----

[How you can contribute](https://github.com/fpirri/gothings-install#How-you-can-contribute)  
[Document short description](https://github.com/fpirri/gothings-install#gothingssystem-short-description)  
[Choose what to look at](https://github.com/fpirri/gothings-install#gothingssystem-short-description)  
[Total Deaths per Country](https://github.com/fpirri/gothings-install#gothingssystem-short-description)  
[Why I write this document](https://github.com/fpirri/gothings-install#pre-installation-steps)  

----

<br />
----


OLD POST in the eCat forum
----

**Reported here for historical reasons**

How do countries fight with coronavirus?

Let's have a look at total deaths in a few western coountries:

![Alt text](this is a test!)
<img src="https://github.com/fpirri/covid19/blob/master/charts/2020-04-25/2020-04-25%20Countries%20Daily%20Deaths%20per%20Million.01.png">


ref.: https://stackoverflow.com/questions/13808020/include-an-svg-hosted-on-github-in-markdown/16462143#16462143

ref.: https://e-catworld.com/2020/03/27/covid-19-thread-3-26-2020-mats-lewan-on-the-case-of-sweden/

It is really very difficult to understand what is happening in our world because of the coronavirus! This is an attempt to dispel the fog caused by the numbers that are thrown to us many times a day by the various news programs. The idea was born from a discussion on the following forum: https://e-catworld.com/2020/03/27/covid-19-thread-3-26-2020-mats-lewan-on-the-case-of-sweden/

Mats Lewan raised a very interesting question, which I rewrite in this way: are the measures taken by the various governments effective? The choice to consider deaths as an essential element for a first assessment of the COVID19 crisis is a good choice: good Mats!

The crisis consists in a phase of exponential expansion of the infected people and dead, up to a maximum which will be followed by a phase of decrease, which may reach zero or settle on endemic values. I consider it essential to evaluate the extent of the crisis with a formal and objective method. I propose to consider as an efficacy parameter the number of days that have passed since the beginning of the infection until reaching the maximum number of deaths in a day, before the decrease in the number of daily deaths. Since this is a statistical phenomenon, the numbers must be large enough. I therefore propose the following criteria:

    the day on which the total deaths in a country exceeds the threshold of 5 deaths per million inhabitants is taken as the day of the start of the crisis;
    the end of the period will be taken on the day when the average for the following week is lower than the average for the week preceding the day in question.

At the present time the day of the maximum in the western world is unknown.

I propose to include in the evaluation also the dates of the 'lockdown' measures issued by the governments, to have a second measuring point (date M1).

These choices are an attempt to standardize the evaluation period with respect to the differences between the various nations. The number of days between the various events will allow to evaluate the effectiveness of the lockdown, where this was done.

Please have a look at the attached spreadsheet.
