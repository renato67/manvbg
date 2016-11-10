# Configurazione dell' applicativo di Back Office{#configurazione-dell-applicativo-di-back-office}

questa parte (il B.O) è altamente configurabile. può essere plasmato sui bisogni dell' utente. Vediamo le principali configurazioni.

## Configurazione di un flusso{#Configurazione-di-un-flusso}

Il flusso, consiste nel percorso che le informazioni disponibili e da ricercare debbono fare per essere impiegate al fine di produrre un atto formale. Esso viene generalmente elaborato da un gruppo di persone che vede (come minimo) una persona del comune interessato (che conosce i passaggi che il dato deve compiere) e una persona della nostra azienda (che sa come tradurre queste informazioni nel linguaggio che deve essere utilizzato per costruire il programma). Il risultato dell' incontro, produce un diagramma di flusso che viene poi tradotto nel linguaggio che l' applicativo riconosce.
Un valido esempio di flusso generato é rappresentato dalle immagini contenute in questa sezione: [sezione 6](../utilizzo_dellapplicativo_di_back_office/gestione_di_una_pratica.md)
Come si può vedere:
* dal confronto fra una nostra persona ed un impiegato Comunale, vengono raccolte informazioni 
* 
Queste informazioni vengono tradotte in diagramma di flusso
* Il diagramma in codice (parte del programma)

Nei vari passaggi, ogni attore traduce nel proprio linguaggio le informazioni ricevute. Infine cio che si ottiene é che l' operazione usualmente svolta mnemonicamente da una persona, potrà essere riprodotta dall' interazione fra il programma e qualsiasi persona che potrà fornire semplici informazioni.
Elenchiamo di seguito, come passi vengono tradotti:

Come si evince dal diagramma di flusso (il primo blocco rappresenta la presentazione di una domanda, questa fase può essere compiuta sia da un operatore del comune che dall' utente finale (utilizzando lo sportello di front Office o inviando una semplice PEC)

Analiziamo il il primo caso:

![](/assets/mn_ins_istanza.jpg)

tramite la voce di menù idicato, sarà possibile accedere la parte del programma di BO che consente l' inserimento di una Istanza.
![](/assets/ sk_ins_Istanze.jpg)
La videata, consente l' inserimento di una pratica (Istanza) contenente i dati necessari (contrassegnati dall' asterisco - cerchiati in rosso nell' immagine -) e altri dati che possono arricchire l' individuazione del soggetto trattato.
Gli stessi dati possono essere inseriti analogamente - tramite Front Office - dall' utente.

# Schede Dinamiche

Queste, sono costituite da un insieme di dati, codice e aspetto di presentazione: alcuni dati, sono valorizzati dal contenuto di un campo che risiede nel DB. 
I menu attinenti questa operazione, sono accessbili - ognuno nella propria area - tramite il seguente menu:

![](/assets/mn_sk_dinameiche.jpg)

come si evince dall' immagine, in questo menù è possibile accedere:

* modelli
* campi
* regole

### modelli
questa sezione permette a seguito della ricerca, l' individuazione delle schede già presenti, 
![](/assets/sk_ricerca_sk_dinamiche.jpg)
o la possibilità di crearne di nuove (anche come copia dalle esistenti).

### campi

![](/assets/sk_campi.jpg)
più o meno con il solito schema, é possibile fare la ricerca o creare nuovi campi (da utilizzare nelle schede)

### regole
![](/assets/sk_regole.jpg)
la scheda serve a definire le regole che relazionano i campi. Come si può vedere, sono numerose le opzioni per relazionare tale campi.
