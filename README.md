# Dovetta Nicolas - Rilievi e perizie
### 5^B Informatica, I.I.S. "G. Vallauri" - Fossano (CN)

Per vedere il sito publicato online clicca [qui](https://progetto-foto-dovetta.herokuapp.com/).
L'utente amministrativo di prova è: 
* User id: gopos90913@ichkoch.com
* Password: Ut3nteAdm1n-Pr0va

L'utente normale di prova è: 
* User id: madibe8247@ichkoch.com
* Password: Ut3nteN0rmal3-Pr0va

## Classi di utenti
### Admin
L'amministratore ha il pieno accesso al portale web e all'applicazione.
Dal portale può visualizzare i report e eventualmente cambiarne le note associate o visualizzare il percorso dalla sua posizione alla posizione dove è stato inserito il report; può creare utenti di tipo admin o user e può visualizzarne i dati di base e modificarli o rigenerare la password.

### User
Accede solo all'applicazione e la sua unica opzione è quella di creare dei report che, una volta fatto l'upload, non può modificare.

## Rapida introduzione al progetto
### Applicazione_Android
All'interno di questa cartella è presente tutta l'applicazione per la creazione di report. Funziona solo su android e comprende una pagina di login e una dove è possibile definire le caratteristiche del report (titolo, note e immagini).
Una volta scattata l'immagine il software provvederà a farne l'upload automaticamente.

### Gestionale_Web
Caricato al link sopracitato, contiene tutte le api per la gestione dell'applicazione e le pagine del gestionale web nella cartella static.
La pagina principale del portale web visualizza una mappa con tutti i report.
Cliccando sul link della navbar "Manage user" possiamo visualizzare le persone con gli account dividendoli per account attivi e da attivare. Quì abbiamo la possibilità di modificare i loro dati di base.
Mentre se clicchiamo sul link denominato "Create user" abbiamo la possibilità di creare un nuovo utente.


N.B. Gli amministratori possono cambiare solo la loro password. La password dei nuovi utenti o la funzione di rigenerazione della password utilizza delle meccaniche interne al server per generare la password e consegnarla all'utente interessato tramite una mail. Una volta effettuato il cambio password iniziale gli utenti normali non potranno più cambiarla e dovranno chiedere a un amministratore di rigenerarne una per loro.