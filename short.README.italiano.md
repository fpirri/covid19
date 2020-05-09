# COVID19, un confronto tra Paesi

Evoluzione del COVID19 in alcuni Paesi Occidentali
<br />  

----

[Cosa potresti trovare qui](./short.README.italiano.md#Cosa-potresti-trovare-qui)  
[Considerazioni iniziali](./short.README.italiano.md#considerazioni-iniziali)  
[Realizzazione dei grafici](./short.README.italiano.md#realizzazione-dei-grafici)  
[Come approfondire](./short.README.italiano.md#come-approfondire)  
  
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
Prima era stata la Cina, poi l'Italia, poi ancora gli Stati Uniti.  

Per verificare, dato che il sito *worldometers* raccoglie da tutto il mondo i numeri che anche la TV ci propina, possiamo prendere [da esso](https://www.worldometers.info/coronavirus/#countries) i dati numerici e metterli in un grafico:

<img src="https://github.com/fpirri/covid19/raw/master/history/images/archive/2020-04-28%20Total%20Deaths%20raw%20data.png">

Come si vede, a fine Aprile gli USA erano il paese piu' colpito **(<-- e' una bugia!!)**.

Facciamo subito alcune considerazione che potranno chiarire quanto questo modo di fornire informazioni sia sbagliato.  

Primo punto: non confronterai mai il numero di decessi nello stato di Andorra con quelli di tutti gli Stati Uniti d'America.  
Secondo punto: e' fuorviante confrontare i numeri di un Paese in cui l'epidemia e' agli inizi con uno nel quale l'epidemia sia al culmine.  

Vediamo allora cosa possiamo fare.
  
----
   
<br />

----  

Realizzazione dei grafici
----

Secondo la prima osservazione fatta sopra, potremo confrontare tra loro i Paesi trasformando i dati numerici puri in un rapporto con la popolazione totale del paese in oggetto. Per esempio, possiamo contare i morti per ogni milione di abitanti.  
Per la seconda osservazione dovremmo contare per ogni paese i giorni a partire  dall'inizio dell'epidemia, almeno fino al culmine dell'epidemia stessa.  
Qui definiamo come inizio dell'epidemia il giorno in cui un paese raggiunge i 5 decessi per ogni milione di abitanti.
La scelta e' fatta per dare una validita' statistica sufficientemente simile per tutti i paesi.
Altri scelgono il giorno del primo decesso. Io ritengo che il giorno del primo decesso sia molto inaffidabile, data anche la tendenza in tutti i paesi a minimizzare l'inizio dell'epidemia.  
**NOTA**: non c'e' stato un solo paese nel quale il leader non abbia minimizzato l'epidemia che stava per arrivare.  

Il grafico che avevamo visto prima diviene ora:

<img src="https://github.com/fpirri/covid19/raw/master/history/images/archive/2020-04-28%20Countries%20Total%20Deaths%20per%20Million.png">
  
Per cominciare a fare una comparazione, realizziamo un grafico relativo ai decessi in ogni singolo giorno:

<img src="https://github.com/fpirri/covid19/raw/master/history/images/archive/2020-04-28%20Countries%20Daily%20Deaths%20per%20Million.wma.all.png">

Il grafico sopra e' stato normalizzato usando un media mobile pesata su sette giorni. Il sito [worldometers](https://www.worldometers.info/coronavirus/#countries) usato sopra presenta i dati separati per singolo paese con una media mobile semplice su tre  giorni.  

Dobbiamo comunque notare che il confronto visivo su un grafico singolo per sette paesi non e' facile da interpretare.  
 
----
   
<br />

----  

Come approfondire
----

Una [versione estesa](,/README.italiano.md) e' disponibile in questo sito.  
In esso vengono esaminati i dati e presentati i criteri con maggiori dettagli.

Il sito contiene anche un foglio di calcolo [LibreOffice Calc]()  che puo'essere scaricato ed usato per propri esperimenti con i dati.  
Esiste anche una  [versione excel](https://github.com/fpirri/covid19/raw/master/history/last/covid19%20evaluation.xlsx) che cerco di mantenere aggiornata.
La versione e' salvata da LibreOffice Calc, e non e' garantita la piena compatibilita'.  

