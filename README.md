Questo repository contiene:

- gli script per elaborare gli Annali (le foto) dell'Ex Servizio Idrografico e Mareografico Nazionale mediante tesseract e R:

  - script per acquisire i dati mediante tesseract
  
  - script per trasformare i dati di testo in file excel
  
- i file excel con i dati di temperatura e precipitazione scannerizzati e corretti

- gli script per acquisire i dati dei sensori per la temperatura e precipitazione

## Dati Annali 

Dalla [pagina](http://centrofunzionale.regione.campania.it/#/pages/documenti/annali) web del Centro Funzionale Multirischi e' possibile scaricare gli Annali dell'ex SIMN. Si tratta di file immagini che richiedono tecniche di OCR per acquisirne i dati.

## Dati sensori Centro Funzionale Multirischi

Dalla [pagina](http://centrofunzionale.regione.campania.it/#/pages/sensori/archivio-termo) e' possibile scaricare i dati giornalieri in formato `.csv` per il periodo 2000-2020.

## Associazioni Annali e Sensori

Le stazioni che figurano negli Annali e che hanno dati nel periodo 2000-2020 sono [qui](./annali.md) riportate. Con queste stazioni potenzialmente si potrebbero calcolare i valori climatologici per il periodo 1991-2020 (unendo i dati online con i dati degli Annali). Attenzione: l'associazione sopra riportata si basa solo sul nome della stazione, le associazioni effettive fanno analizzate tenendo conto dell'anagrafica delle stazioni.

L'elenco dei sensori di temperatura e precipitazione per il periodo 2000-2020 e' riportato in [questa](./sensori.md) pagina.




























