**Gestione Contratti di Vendita**
----------------------------------

Con gli “ordini di contratto/offerta” vengono gestiti degli accordi di  vendita rispetto ad un determinato Cliente e per una determinata serie di articoli. 
Questo consente di definire il quantitativo previsto, il prezzo concordato e la validità attraverso due date di inizio e fine.

Vengono, quindi, generate delle offerte contenenti diversi articoli, qtà e prezzi che rappresentano dei contratti di fornitura verso i Clienti. 
Non sono degli ordini veri e propri in quanto non devono impegnare la merce, ma definiscono semplicemente le quantità e i prezzi concordati.
A fronte di tali contratti vengono inseriti gli ordini effettivi (riportando con copia incolla il riferimento di commessa padre) che dovranno scalare il quantitativo di ordine programmato.
La decurtazione della quantità viene fatta su un campo d’appoggio, mentre la quantità in riga resta come storico per statistiche. 
Inoltre, l’offerta ha data di inizio e una data di fine validità a livello di riga e in funzione della validità si da la possibilità o meno di legare l’offerta all’OV.
