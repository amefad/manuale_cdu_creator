Il Plugin CDU Creator
==================================
Il **Plugin CDU Creator** genera automaticamente il Certificato di Destinazione Urbanistica (CDU) a partire dal layer vettoriale dei terreni catastali e dai layers vettoriali dello strumento urbanistico vigente (PUC, PRG, ecc.). L'output finale è un file .pdf contenete tutte le informazioni relative allo strumento urbanistico recuperate dalle tabelle degli attributi dei layers che si intersecano con la particella catastale selezionata dall'utente.

I principali input del Plugin CDU Creator sono i dati dei terreni catastali, che devono essere caricati all'interno di un progetto QGIS come layer vettoriale poligonale, e i dati relativi allo strumento urbanistico vigente anch'essi da caricare nel progetto QGIS come layer vettoriali poligonali. Per il corretto funzionamento del Plugin, il layer dei terreni catastali decve essere obbligatoriamente nominato **terreni_catastali**, mentre i layers dello strumento urbanistico dovranno essere organizzati in gruppi e sottogruppi (n.b. per la corretta organizzazione dei dati al fine di consentire il corretto funzionamento del plugin, si rimanda al paragrafo *Preparazione dei Dati*). :ref:`richiesta-accesso`

Il Plugin compila il CDU per la particella catastale selezionata nel layer **terreni_catastali**. L'utente può selezionare la particella con i comuni strumentio di selezione di QGIS oppure utilizzando l'interfaccia grafica del plugin, selezionando prima il foglio dal menù a tendina e quindi il numero della particella dal relativo menù a tendina. Qualora l'utente selezioni una particella con gli strumenti di selezione di QGIS e anche tramite i menù dell'interfaccia grafica, il CDU verrà compilato per la particella selezionata tramite l'interfaccia grafica del plugin.
**N.B.:** il plugin CDU Creator compila il CDU per una singola particella. Qualora si voglia compilare il CDU per più particelle è necessarrio lanciare il processo più volte selezionando le singole particelle.

Come già anticipato nell'introduzione di questo manuale, l'output finale del plugin è un file .pdf contenete le informazioni necessarie per la creazione del CDU. Il file .pdf può essere personalizzato aggiungendo ad esempio un titolo, un logo e una sezione testuale semplicemente inserendo il testo che dovrà comparire come titolo, selezionando un file .png da usare come logo e un file .txt per la sezione testuale. Questi elementi devono essere selezionati tramite l'interfaccia grafice (si veda il pragrafo *Graphical User Interface* per maggiori dettagli).

Preparazione dei Dati
--------------------------------------------


Graphical User Interface
--------------------------------------------


.. image:: img/gui.png

* **1 - 
* **2 - 
* **3 - 


Example
--------------------------------------------


