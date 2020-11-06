# **Analisi dei dati di rete in una comunità di musicisti Jazz**

## Obiettivo

Analizzare la struttura di rete della comunità dei musicisti Jazz, individuando:
* i musicisti con maggior numero di legami
* livello di coesione della rete
* eventuali sotto-comunità (gruppi particolarmente coesi o isolati dal contesto)

## Metodologia
Si costruisce un grafo non orientato a partire da un corpus di incisioni, dove:
* i nodi sono rappresentati da tutti i musicisti che abbiano partecipato ad almeno una incisione
* gli spigoli sono rapprensentati dalla partecipazione di due musicisti ad almeno una incisione in comune (pertanto, due musicisti si considerano "collegati" da uno spigolo se compaiono assieme in almeno una incisione)

## Fonte
I dati sono reperiti dal sito www.jazzdisco.com che offre un catalogo di numerose incisioni di musica Jazz corredate della relativa formazione
