# COVID19, un confronto tra Paesi

Evoluzione del COVID19 in alcuni Paesi Occidentali
<br />  

----

[Cosa potresti trovare qui](./short.README.italiano.md#Cosa-potresti-trovare-qui)  
[Considerazioni iniziali](./short.README.italiano.md#considerazioni-iniziali)  
[Realizzazione dei grafici](./short.README.italiano.md#realizzazione-dei-grafici)  
[La conclusione](./short.README.italiano.md#la-conclusione)  
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

Per verificare, dato che il sito [worldometers](https://www.worldometers.info/coronavirus/#countries) raccoglie da tutto il mondo i numeri che anche la TV ci propina, possiamo prendere da esso i dati numerici e metterli in un grafico:

<img src="https://github.com/fpirri/covid19/raw/master/history/images/archive/2020-04-28%20Total%20Deaths%20raw%20data.png">

Come si vede, a fine Aprile gli USA erano il paese piu' colpito **(<-- e' una bugia!!)**.

Facciamo subito alcune considerazioni che potranno chiarire quanto questo modo di fornire informazioni sia sbagliato.  

* Primo:
    * non confronterai mai il numero di decessi del (piccolo) stato di Andorra con quelli di tutti gli Stati Uniti d'America.  
* Secondo:
    * e' fuorviante confrontare i numeri di un Paese in cui l'epidemia e' agli inizi con uno nel quale l'epidemia sia al culmine.  

Vediamo allora cosa possiamo fare.
  
----
   
<br />

----  

Realizzazione dei grafici
----

Secondo la prima osservazione fatta sopra, potremo confrontare tra loro i Paesi trasformando i dati numerici puri in un rapporto con la popolazione totale del paese in oggetto. Per esempio, possiamo contare il numero di decessi per ogni milione di abitanti.  
Per la seconda osservazione dovremmo anche contare per ogni paese i giorni a partire  dall'inizio dell'epidemia, almeno fino al culmine dell'epidemia stessa.  
Qui definiamo come inizio dell'epidemia il giorno in cui un paese raggiunge i 5 decessi per ogni milione di abitanti.
La scelta e' fatta per dare una validita' statistica sufficientemente simile per tutti i paesi.  
Altri scelgono il giorno del primo decesso. Io ritengo che il giorno del primo decesso sia molto inaffidabile, data anche la tendenza in tutti i paesi a minimizzare l'inizio dell'epidemia.  
**NOTA**: non c'e' stato un solo paese nel quale il leader non abbia minimizzato l'epidemia che stava per arrivare.  

Il grafico che avevamo visto prima diviene ora:

<img src="https://github.com/fpirri/covid19/raw/master/history/images/archive/2020-04-28%20Countries%20Total%20Deaths%20per%20Million.png">
  
Come e' possibile vedere, le cose cambiano molto ma rimane difficile fare dei confronti accurati.  

Decidiamo allora di usare gli stessi dati per vedere l'andamento giornaliero dei decessi per milione di abitanti nei vari paesi.
Usiamo una media su sette giorni per eliminare periodicita' nella rilevazione dei dati in molti paesi.  
Otteniamo il seguente grafico:  

<img src="https://github.com/fpirri/covid19/raw/master/history/images/archive/2020-04-28%20Countries%20Daily%20Deaths%20per%20Million.wma.all.png">

Come si vede, la Spagna ha un numero di decessi giornalieri quasi sempre superiore a tutti gli altri.  
Vediamo anche che la Germania presenta quasi sempre un numero di decessi giornalieri molto minore di tutti gli altri.  
Per gli altri paesi si hanno situazioni miste e non e' evidente chi sia migliore di un altro.  

Prendendo spunto da quello che spesso si fa per arrivare ad una graduatoria numerica, assegnamo un insieme di punti ai vari paesi usando i seguenti parametri:  
- totale dei decessi per milione in tutto il periodo;
- valore di picco dei decessi giornalieri;
- durata totale del periodo di crisi.
  
Mettiamo, nello stesso foglio di calcolo usato per i grafici, alcune tabelle per calcolare un punteggio per ciascun Paese.
  
Il procedimento usato per arrivare a questo risultato e' illustrato in dettaglio nella [versione estesa](./README.italiano.md) del confronto.  
 
Vediamo sotto la graduatoria calcolata.  
  
----
   
<br />

----  

La conclusione
----
  
Con il foglio di calcolo disponibile su sito si arriva alla seguente graduatoria dei Paesi, calcolata il 10 Maggio 2020:  
  
*    Germany   60
*    USA      46
*    Sweden   38
*    France    25
*    UK      24
*    Italy     16
*    Spain     10
 
L'analisi numerica conferma cio' che avevamo visto sul grafico, cioe' che il giorno 11 Maggio la Germania e' la migliore e la Spagna l'ultima. Il foglio sara' ricalcolato giornalmente fino al 30 Giugno 2020.  
  
La graduatoria misura le differenze tra i paesi quantitativamente in modo migliore dell'esame visivo dei grafici, quindi posso dire che il primo obiettivo della riflessione e' raggiunto.  
Tuttavia, sono tutt'altro che soddisfatto perche' la graduatoria trovata non e' in accordo con la severita' delle misure che i vari governi hanno preso.  
  
Mascherine, guanti e distanziamento sociale sono stati la risposta al virus in molte parti del mondo.  
Gli esperti avvisano che evitare i contatti con gli infetti riduce di molto il contagio. La logica dice che hanno ragione.  

Eppure, la graduatoria non e' congrua:
* L'Italia ha effettuato per prima le misure piu' drastiche, le ha seguite bene, e si ritrova penultima;
* La Svezia si e' rifiutata di applicare misure restrittive, tuttavia sta decisamente meglio di Spagna, Italia, Francia e Regno Unito;
* L'USA del vituperato Trump sta meglio di tutti gli altri, a pochi punti dalla Germania;
* La Germania sta molto meglio di tutti quanti, tuttavia le misure da essa intraprese non sono state affatto le piu' dure.

La stessa logica di prima mi dice che **esiste qualcosa che non so** ma che ha un grande effetto.  
  
Credo che il *qualcosa* possa essere trovato solo con la scienza.  
  
**Sara' necessario un grande sforzo di ricerca scientifica per fornire risposte convincenti.**

Passata la paura, lo sforzo verra' fatto?
La risposta dipende da tutti noi.

----
   
<br />

----  

Come approfondire
----

Una [versione estesa](./README.italiano.md) e' disponibile in questo sito.  
In essa vengono esaminati i dati e presentati i criteri con maggiori dettagli.

Il sito contiene anche un foglio di calcolo [LibreOffice Calc](https://github.com/fpirri/covid19/raw/master/covid19%20evaluation.ods) che puo'essere scaricato ed usato per propri esperimenti con i dati.  
Esiste anche una  [versione excel](https://github.com/fpirri/covid19/raw/master/history/last/covid19%20evaluation.xlsx) che cerco di mantenere aggiornata.
La versione e' salvata da LibreOffice Calc, e non e' garantita la piena compatibilita'.  

