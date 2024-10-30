# My-Personal-Trainer
## DESCRIZIONE
My Personal Trainer è un'applicazione disponibile su mobile e PC che offre un'esperienza di personal training virtuale, che fornisce schede di allenamento mirate e schede nutrizionali.

## TAGLINE
Il tuo personal trainer e nutrizionista a portata di click

## PROBLEMA RISOLTO
Necessità di avere un accesso facile alle proprie schede nutrizionali e di allenamento, ovunque ci si trovi

## COMPETITORS
Nike Training Club, Freeletics, Fitbod

## REQUISITI
### REQUISITI FUNZIONALI

![Diagramma dei casi d'uso](https://yuml.me/rick/My-Personal-Trainer.svg)

#### Gestione Utenti
- Registrazione nuovo utente (nickname, email e password obbligatori).
- Login utente.
- Modifica profilo utente (modifica nickname, email e password).
- Visualizzazione profilo utente.

#### Gestione Servizi
- Acquisto di schede di allenamento basate su obiettivi specifici.
- Acquisto di schede nutrizionali basate su obiettivi specifici.
- Acquisto di pacchetto combinato (allenamento e nutrizione).
- Visualizzazione e gestione dei servizi acquistati.

#### Accesso ai Contenuti
- Accesso alle schede di allenamento acquistate.
- Accesso alle schede nutrizionali acquistate.
- Accesso ai video delle esecuzioni degli esercizi (se presenti).
- Download o visualizzazione dei contenuti sul dispositivo (mobile o PC).

#### Amministrazione
- Gestione utenti (abilitazione/disabilitazione account).
- Gestione degli acquisti e rinnovi dei servizi.
- Monitoraggio dei contenuti e segnalazioni di eventuali problemi.


### REQUISITI NON FUNZIONALI
#### Performance
- Tempo di risposta massimo per il caricamento di pagine: 2 secondi.
- Tempo di risposta massimo per il download delle schede: 3 secondi.
- Supporto simultaneo di almeno 1000 utenti attivi.
- Funzionalità ottimizzate sia per mobile che per PC.

#### Sicurezza
- Criptazione delle password.
- Verifica email durante la registrazione.
- Backup settimanali dei dati utente e dei contenuti.
- Protezione contro attacchi DDoS.

#### Usabilità
- Interfaccia user-friendly, responsive su mobile e PC.
- Navigazione intuitiva per accesso rapido ai contenuti acquistati.
- Guida integrata per l’uso dei servizi.

#### Affidabilità
- Uptime garantito al 99.9%.
- Sistema di backup e recupero dati in caso di errori.
- Monitoraggio del sistema per rilevamento e risoluzione tempestiva di errori.


### REQUISITI DI DOMINIO
#### Gestione Servizi
- Struttura dei contenuti adattata a differenti livelli di fitness e obiettivi nutrizionali.
- Categorizzazione dei piani di allenamento e nutrizione per obiettivi specifici (es. perdita peso, aumento massa muscolare, mantenimento).
- Supporto per aggiornamenti periodici delle schede.

#### Conformità
- Conformità con il GDPR per la gestione dei dati personali.
- Informative chiare sui termini di utilizzo e licenze dei contenuti.
- Possibilità di recesso o cancellazione dell’abbonamento secondo le normative.
