# COVID19, un confronto tra Paesi

Evoluzione del COVID19 in alcuni Paesi Occidentali
<br />  

----

[Cosa potresti trovare qui](./short.README.italiano.md#Cosa-potresti-trovare-qui)  
[Considerazioni iniziali](./short.README.italiano.md#Considerazioni iniziali)  
[Realizzazione dei grafici](https://github.com/fpirri/covid19/tree/master/history/last#lets-analyze-)  
[Expand](https://github.com/fpirri/covid19/tree/master/history/last/#Realizzazione dei grafici)  
  
----
   
<br />

----  

Cosa potresti trovare qui
----  

* Un modo per esaminare i dati COVID19
* Una ipotesi di base per un'esplorazione più significativa dei dati
* Una analisi dei dati disponibili su alcuni paesi occidentali
* Alcuni grafici per confrontare i dati in alcuni paesi
* Un suggerimento per un'esplorazione più approfondita
 <br />

----

Considerazioni iniziali
----

TV e giornali ci bombardano giornalmente con quantita' industriali di dati numerici e finiscono sempre con l'indicare la Nazione che ha il piu' grande numero di decessi.  
Prima e' sata la Cina, poi l'Italia, ora gli Stati Uniti.  
Facciamo subito alcune considerazione che potranno chiarire quanto questo modo di fornire informazioni sia sbagliato.  

Primo punto: non confronterai mai il numero di decessi nello stato di Andorra con quelli di tutti gli Stati Uniti d'America.  
Secondo punto: e' fuorviante confrontare un Paese in cui l'epidemia e' agli inizi con uno nel quale l'epidemia sia al culmine.  

Vediamo allora cosa possiamo fare.
  
----
   
<br />

----  

Realizzazione dei grafici
----

Secondo la prima osservazione, potremo confrontare tra loro i Paesi trasformando i dati numerici puri in rapporto alla popolazione totale del paese in oggetto.  
Per la seconda osservazione dovremmo contare per ogni paese i giorni a partire  dall'inizio dell'epidemia.
Qui definiamo come inizio dell'epidemia il giorno in cui un paese raggiunge i 5 decessi per ogni milione di abitanti.
La scelta e' fatta per dare una validita' statistica sufficientemente simile per tutti i paesi.
Altri scelgono il giorno del primo decesso. Io ritengo che il giorno del primo decesso sia molto inaffidabile, data anche la tendenza in tutti i paesi a minimizzare l'inizio dell'epidemia.




Dopo di che dovremo traslare i dati giornalieri dei vari paesi allineandoli rispetto alla partenza in ciascun Paese.



Puoi andare su https://www.worldometers.info/coronavirus/#countries
e trovare un mucchio di dati: cosa ne fai?

Puoi acoltare la TV ed essere bombardato di numeri di infetti ecc.

la tv parla solo di numeri assoluti

devi ragionare su dati comparabili

se qualcuno ti dice che nel Principato di Monaco vengono investiti meno pedoni nello stato di New York, negli Stati Uniti deduci che a New York e 'molto pericoloso attraversare la strada?

Dovrai rassegnarti a parlare di percentuali e chiederti quanti sono gli abitanti del principato e quanti hanno lo Stato di New York.

Il numero totale di decessi sembra molto importante, quindi ho preso i dati dal sito e li ho presentati su un unico grafico per apprezzare meglio le differenze.



==> DETTAGLI: perché guardare alla morte

Il grafico raccoglie i seguenti paesi: Italia, Spagna, Francia, Svezia, Regno Unito, Stati Uniti e Germania.



Guardando il grafico, il primato viene immediatamente assegnato agli Stati Uniti, che dominano tutti gli altri paesi.
Ma è vero?
Non mi sembra corretto confrontare direttamente ciò che accade in un paese di 331 milioni di abitanti con ciò che accade in un paese di 10 milioni di abitanti come la Svezia.
Seguendo i pensieri di Mats, ho riportato sul grafico il numero di morti per milione di abitanti.



Ora gli Stati Uniti sembrano essere il secondo paese meno colpito tra quelli esaminati.
Tuttavia, c'è qualcosa di importante da considerare: non sembra giusto confrontare paesi come la Spagna, dove la pandemia si avvicina al suo apice con i paesi in cui è appena iniziata.
Quindi, dovremmo confrontare i paesi contando i tempi dall'inizio della pandemia in ciascun paese.
Ma aspetta, come trovi la data di partenza?
Una possibile scelta è la data della prima vittima della malattia.
Tuttavia questa data sembra non molto affidabile.
Se vogliamo confrontare eventi statistici tra loro, dobbiamo usare un momento caratterizzante che è abbastanza simile per tutti.
In un modo totalmente arbitrario scelgo il momento in cui il Paese supera i 5 decessi per milione di abitanti.
Per il momento, rimanderò più avanti una discussione su questo criterio.






----

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

Puoi andare su  https://www.worldometers.info/coronavirus/#countries 
e trovare un mucchio di dati: cosa ne fai?

Puoi acoltare la TV ed essere bombardato di numeri di infetti etc.

la tv parla solo di numeri assoluti

devi ragionare su dati comparabili

se qualcuno ti dice che nel Principato di Monaco vengono investiti meno pedoni che nello stato di New York, USA deduci che a New York e' molto pericoloso attraversare la strada?

Dovrai rassegnarti a parlare di percentuali e chieder quanti sono gli abitanti del principato e quanti quelli dello Stato di New York.



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


