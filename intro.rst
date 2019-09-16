Introduzione
==================

Credits
------------------------------------------

.. image:: img/Gter.png
https://www.gter.it/


Il Plugin QGIS **CDU Creator** e questo manuale sono stati sviluppati da Gter srl Innovazione in Geomatica GNSS e GIS.

Sia il Plugin che il manuale sono distribuiti con licenza Creative Commons Attribution 4.0 International License https://creativecommons.org/licenses/by/4.0/


Scopo
------------------------------------------
E’ noto che una delle esigenze più diffuse, fra gli oltre 9200 Comuni italiani, è la realizzazione dei Certificati di Destinazione Urbanistica (CDU).

Sono disponibili molte soluzioni online che però comportano spesso un costo che non tutti i Comuni possono affrontare. Inoltre i dati catastali non sempre sono pronti all'uso, necessitano di continui aggiornamenti e possono richiedere un affinamento delle comuni trasformazioni ottenute con i punti fiduciali al fine di ottenere la corretta georeferenziazione dei dati stessi.

Per queste ragioni ancora oggi molti uffici tecnici per effettuare operazioni di intersezione tra il catasto terreni e i layer urbanistici (vincoli, zone, ecc.) continuano a privilegiare soluzioni per nulla automatizzate invece che servirsi di Sistemi Informativi Territoriali, nonostante l’uso di tali sistemi potrebbe rendere la compilazione del CDU decisamente più semplice, veloce e precisa.

A partire da queste considerazioni, Gter ha sviluppato il **Plugin QGIS CDU Creator** con lo scopo di agevolare le attività di compilazione del CDU agli uffici tecnici fornendo uno strumento semplice e Open Source che consente appunto di ottenere un CDU impostando solo pochi parametri.

Il **Plugin CDU Creator** genera un file .pdf contenete tutte le informazioni necessarie per la validità del CDU a partire dai layers vettoriali dei terreni catastali e dello strumento urbanistico vigente (PUC, PRG, ecc.). I dati vettoriali dello strumento urbanistico, organizzati in gruppi e sottogruppi, vengono intersecati con la particella catastale selezionata dall'utente, le informazioni relative alle aree del piano interessate vengono automaticamente recuperate e stampate nel file .pdf. 

L'output finale è un file .pdf contente il CDU generato automaticamente e personalizzato in base ai parametri definiti tramite l'interfaccia grafica dall'utente. Il CDU conterrà quindi, non solo le informazione relative alle aree dello strumento urbanistico interessate ma anche la mappa con la visualizzazione della particella selezionata, titolo e logo del Comune definiti dall'utente e, se indicata, anche un paragrafo di introduzione al documento contenete eventuali riferimenti normativi, diciture o altro che devono essere indicati nel CDU per renderlo valido a tutti gli effetti.


Glossario
------------------------------------------

* CDU: Certificato di Destinazione Urbanistica
* PUC: Piano Urbanistico Comunale
* PRG: Piano Regolatore Generale
* GIS: Geographic Information System
* SIT: Sistemi Informativi Territoriali









.. _Gter srl: https://www.gter.it
