# Understanding COVID19

A discussion about how some western countries fight with coronavirus  
<br />  

----

[What happened ?](https://github.com/fpirri/covid19/tree/master/history/last#what-happened-)  
[What you may find here](https://github.com/fpirri/covid19/tree/master/history/last#what-you-may-find-here)  
[My first steps](https://github.com/fpirri/covid19/tree/master/history/last#my-first-steps)  
[Let's analyze !](https://github.com/fpirri/covid19/tree/master/history/last#lets-analyze-)  
[Another step](https://github.com/fpirri/covid19/tree/master/history/last/#a-second-step)  
[How to contribute](https://github.com/fpirri/covid19/tree/master/history/last#how-to-contribute)  

[DETAILS](https://github.com/fpirri/covid19/tree/master/history/last/#how-to-contribute)  
  
----
I started writing this document as a personal reflection, trying to understand something about the ongoing pandemic.
I wondered how effective the measures of the governments of the various countries were and if they had been the best.
I have examined the official statistics relating to COVID19 and have documented myself. I discovered a good number of epidemiomogical theories in the last century that talked about herd immunity, social distancing and much more by inserting a series of formulas in the mixture.  
The history of this phase is in the section [My first steps](https://github.com/fpirri/covid19/tree/master/history/last/#my-first-steps) below.  
  
<br />

What happened ?
----  

  
2020-04-28 - In Italy we are all at home. We are inundated with news on COVID19 from the continuous television news, the newspapers do not talk about anything else and, in the chats (at a distance) with friends, we (almost) always discuss the coronavirus.  
The main actors of the various speeches are mainly two: the medical reports from the hospitals and the actions of the rulers.  
Third parties and distant actors are the experts, or presumed such.

The medical reports are fairly coherent with each other: it's a war, we risked losing it and we haven't come out yet.
Apart from the more or less distressing comments, there are no real discussions.

Various steps have followed on government policies:
1. Initially, the epidemic was heavily underestimated
2. Then the government begins to say that something will have to be done, however everything will be fine
3. Then the government wants to show that it does something and imposes restrictions on people's movements and starts to debate what to do ...
4. ... then there is a frantic succession of decisions in the government and in the various administrations, often contradicting each other ...
5. ... finally, government and population are convinced that the tragedy is epoch-making and resign themselves to following a series of measures to mitigate the economic consequences of the disaster.  

However, a not negligible part of the population remains scattered on different hypotheses and does not resign itself to common actions.  

A question comes naturally: **what are we doing is based on scientific analysis or is it based only on instinctive reactions?**  

Are the experts giving us the answer?  
Those we see on TV or who write in newspapers often appear 'characters' in search of notoriety. In fact, science is not done on TV or in newspapers, but by conducting experiments and, during a pandemic, it is not easy.  

There is also a strong suspicion that **they treat us like children** to whom it is good not to tell the naked and raw truth.  

Since we have time to waste, let's do some home science and see if we can understand something more.

**This document is an attempt to analyze the situation in a slightly more scientific way than watching television.**
   
<br />

----  

What you may find here
----  

* The amount of information you get in a single day regarding coronavirus is overwelming: what should you look at ? 
* Is there a way to use data available on the web to understand differences from a country to the next ?
* If the data we have are not reliable, can we, now or in the future, improve them in some way?
* Governments have acted against COVID19 at different times with different actions, what consequences, if there have been, can be highlighted by the data ?
* What do we have to prepare to act against the next flu ?
 <br />
  

----



My first steps
----  

It is really very difficult to understand what is happening in our world because of the coronavirus!   
I started discussing an idea by Mats Lewan on a blog.   
[==> DETAILS: the blog post](https://github.com/fpirri/covid19/tree/master/history/last/#details-ecat-blog-mats-lewan)  
  
Mats Lewan looked at the number of deaths in any given day in several countries and shared is thoughts in the blog.  

So I looked for data on the website https://www.worldometers.info/coronavirus/#countries which presents a lot of data on almost all the nations of the world.  
The site places a lot of emphasis on the number of sick and healed, but also on the total deaths in each individual country.  
TV follows the same format and assigns the 'primacy' to the country with the highest number of deaths. Now it's up to the USA.  
The total number of deaths seems very important, so I took the data from the site and presented it on a single chart to better appreciate the differences.  
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

Let's analyze !
----  
* This section is under construction  
Here I will try to add other parameters, such as the number of patients and others, in light of some of the theories that are being discussed.  

----

The first question we have to ask ourself is:
What do we know about COVID19 and what should we know better about it?  
The answer is disheartening: it seems that the important parameters are either unknown or very inaccurately known.
To understand this, I had to first study some epidemiological theories.
[==> DETAILS: the teory](https://github.com/fpirri/covid19/tree/master/history/last/#details-epidemiology)  

In an interview with the newspaper Il Tempo, Prof. Carlo Gaudio observed that in the 2000s we had 5 pandemics.
[==> DETAILS: A pandemic every 4 years](https://github.com/fpirri/covid19/tree/master/history/last/#details-a-pandemic-every-4-years)  
**So, we can expect the next virus between 2004 and 2007**.  
It is not really excluded that the next one will arrive before the effect of COVID19 is finished.  

So what parameters would we like to know?
Here is a brief and non-exhaustive list:
1. percentage of naturally immune people;
2. presence and duration of immunity for healed people;
3. difference, if any, between contagiosity by air transmission and by contact;
4. relationship between physical closeness, the time spent in proximity and the probability of contagion;
5. duration and contagiousness of the incubation period;
6. range of times for healing.

Not being able to experiment, we must try to deduce the parameters by observing what is happening in the affected countries.
To use a scientific method we should hypothesize a mathematical model and compare the real data with what is happening.  
  
Question: do we know what's happening quantitatively?
Here too the answer is almost negative: the reliability of the data we see is doubtful or even worse.

Nonetheless, we can use the data that is communicated to us and try to correct it afterwards as we did for the case of deaths.
[==> DETAILS: Why to look at Death](https://github.com/fpirri/covid19/tree/master/history/last#details-why-to-look-at-death)

----

<br />

----
[==> DETAILS](https://github.com/fpirri/covid19/tree/master/history/last/#details)  
  
----

<br />


Another step
----  

* This section is under construction

----
<br />  

----

<br />

How to contribute
----  

* If you like, you can 'open an issue' on github (2nd element in the top menu)  
* I will post about this document on the forum: https://e-catworld.com/
You can comment there, if you like.

<br />

----


# DETAILS
----  

* This section is under construction  
  
This section is organized into several parts. Each will discuss a particular point that needs a specific discussion.  
For example: why start with the dead?  
Or: why carry out the comparison starting from the value of 5 deaths per million inhabitants?  

<br />

----

# DETAILS: why to look at death

* Turn list into organic display
* Translation still to be done
* To be reviewed for publication

- dato molto controllato nel mondo occidentale
- molte diverse sorgenti sia ufficiali che indirette
 anagrafe comunale, cimiteri, registri parrocchiali, vox populi
- controllo statistico a posteriori
(un altro primato italiano?)
vedi: Rapporto_Istat_ISS.pdf & Decessi 2020
https://www.istat.it/it/files//2020/05/Rapporto_Istat_ISS.pdf  
https://www.istat.it/it/files/2020/03/Decessi_2020_Nota.pdf  
contenuto:
nel periodo 20/2-31/3 i morti passano da 65.592 (media periodo 2015-2019) a 90.946 con un incremento di 25.354 unità - quelli ufficialmente covid denunciati sono stati 13.710  
si potrebbero confrontare anche i dati di comunita' chiuse e con dati meglio conosciuti  

<br />

----

# DETAILS: Epidemiology

* Turn list into organic display
* Translation still to be done
* To be reviewed for publication

Senza entrare troppo nello specifico, i modelli dividono la popolazione in classi relative ai vari stadi della malattia. Le classi sono spesso individuate con una lettera:
* S    Susceptible
 * E    Exposed
 * I    Infected
 * R     Removed, Recovered or Death
 I modelli studiano  i passaggi da una classe all'altra per gli individui in una popolazione assegnata.
 Su internet troviamo il modello SIR, cioe' il modello Suscettibile-Infected-Removed ed altri.
 
Negli ultimi 100 anni si e' tentato di ottenere modelli matematici formali per analizzare l'andamento delle epidemie. Lo scopo principale del modello matematico e' quello di individuare a priori l'efficacia delle misure preventive che si vogliono usare.
Senza entrare troppo nello specifico, i modelli dividono la popolazione in classi relative ai vari stadi della malattia. Le classi sono spesso individuate con una lettera:
 * S    Susceptible
     * Individuals who may become infected
 * E    Exposed
     * Individuals who got the infection
     * the infection will become transmissible in a while
 * I    Infected
     * Individuals affected by the infection
     * they are a vehicle for further infections
 * R     Removed
      * Individuals no more counted owing to death or becoming immune
 * M    Martenally derived immunity
     * new born, which are not susceptible to infections for a given time
 * C Carrier
     * Individui che hanno la malattia latente (es. tubercolosy)
     * possono trasmetterla indefinitamente nel tempo
     
 le definizioni sembrano poter subire piccole variazioni

I modelli studiano  i passaggi da una classe all'altra per gli individui in una popolazione assegnata.
Il padre dei vari modelli e' il modello SIR: Suscettibile-Infected-Removed
[Mathematical modelling of infectious disease](https://en.wikipedia.org/wiki/Mathematical_modelling_of_infectious_disease)
Altri modelli sono stati sviluppati:
[Compartmental models in epidemiology](https://en.wikipedia.org/wiki/Compartmental_models_in_epidemiology)

SIRD
MSIR
Carrier state
SEIR 
SEIS
MSEIR
MSEIRS

 
  There are many modifications of the SIR model, including those that include births and deaths, where upon recovery there is no immunity (SIS model), where immunity lasts only for a short period of time (SIRS), where there is a latent period of the disease where the person is not infectious (SEIS and SEIR), and where infants can be born with immunity (MSIR). 


<br />

----

# DETAILS: 

* Turn list into organic display
* Translation still to be done
* To be reviewed for publication

Un esempio di come potrebbero essere fatte le cose ? ....

In 2018, Ciofi et al. pubblicano un lavoro estremamente interessante:  
[Mitigation Measures for Pandemic Influenza in Italy: An Individual Based Model Considering Different Scenarios](https://doi.org/10.1371/journal.pone.0001790)  
Il lavoro e' stato sottoposto alla pubblicazione nel 2017.
lavoro:
- si genera un modello di c

basic reproductive number (R 0 )


<br />

----

# DETAILS: A pandemic every 4 years

* Turn list into organic display
* Translation still to be done
* To be reviewed for publication

ref. a il tempo:
[Carlo Gaudio - Il Tempo](https://www.iltempo.it/salute/2020/04/11/news/date-e-numeri-parla-il-professor-carlo-gaudio-che-cosa-ci-insegnano-le-epidemie-1313244/)

<br />  

----

# DETAILS: Why 5 death per Million

* Turn list into organic display
* Translation still to be done
* To be reviewed for publication

- il primo morto appare poco certo e statisticamente troppo variabile
- necessita' di avere punti di uguale significato per tutti:
scegliamo 1 morto per milione o 2,3,4 ?
- oppure: un altro valore assoluto: 2, 3, ..., 10 morti per nazione
- oppure: meta' dell'intervallo tra 1 e 5 (?) morti per milione
- DA FARE:
vedere come cambia l'origine e/o il confronto se si fa una scelta diversa: come cambia la posizione del picco ?
-forse il confronto andrebbe fatto per aree geografiche ciascuna con 100k o piu' abitanti (perche' 100k, 500k e' meglio?

<br />  

----



PLEASE NOTE: this is WORK IN PROGRESS
===

This document is incomplete: I am trying to coordinate my thoughts, but I cannot find a common thread in the many things I read online.
I need help.  
 Do you have any suggestion?
<br />

----

Tentative sections.  
I accept suggestions.  

[Document short description]()  
Not easy!  
  
  
[Herd immunity]()  
Is it applicable?  
  

[Why I write this document]()  
Probably thi is not important.
  

[What this document discuss]()  

----

<br />
----


# DETAILS: eCat blog Mats Lewan

On April 26, I commented on an idea by Mats Lewan on the blog -eCat-.
As a reference, I report below what I wrote on the blog.
You find below a link to the blog. Please search for 'fpirri' to find my post.

----
[eCat Blog](https://e-catworld.com/2020/03/27/covid-19-thread-3-26-2020-mats-lewan-on-the-case-of-sweden/)  
----

How do countries fight with coronavirus?

Let's have a look at total deaths in a few western coountries:

<img src="https://e-catworld.com/wp-content/uploads/2020/03/Screenshot-2020-03-27-at-07.49.23.png">

ref.: https://e-catworld.com/2020/03/27/covid-19-thread-3-26-2020-mats-lewan-on-the-case-of-sweden/

It is really very difficult to understand what is happening in our world because of the coronavirus! This is an attempt to dispel the fog caused by the numbers that are thrown to us many times a day by the various news programs. The idea was born from a discussion on the following forum: https://e-catworld.com/2020/03/27/covid-19-thread-3-26-2020-mats-lewan-on-the-case-of-sweden/

Mats Lewan raised a very interesting question, which I rewrite in this way: are the measures taken by the various governments effective? The choice to consider deaths as an essential element for a first assessment of the COVID19 crisis is a good choice: good Mats!

The crisis consists in a phase of exponential expansion of the infected people and dead, up to a maximum which will be followed by a phase of decrease, which may reach zero or settle on endemic values. I consider it essential to evaluate the extent of the crisis with a formal and objective method. I propose to consider as an efficacy parameter the number of days that have passed since the beginning of the infection until reaching the maximum number of deaths in a day, before the decrease in the number of daily deaths. Since this is a statistical phenomenon, the numbers must be large enough. I therefore propose the following crhttp://blog.rubinetteria.com/come-sciogliere-le-incrostazioni-del-sapone/iteria:

    the day on which the total deaths in a country exceeds the threshold of 5 deaths per million inhabitants is taken as the day of the start of the crisis;
    the end of the period will be taken on the day when the average for the following week is lower than the average for the week preceding the day in question.

At the present time the day of the maximum in the western world is unknown.

I propose to include in the evaluation also the dates of the 'lockdown' measures issued by the governments, to have a second measuring point (date M1).

These choices are an attempt to standardize the evaluation period with respect to the differences between the various nations. The number of days between the various events will allow to evaluate the effectiveness of the lockdown, where this was done.

Please have a look at the attached spreadsheet.
