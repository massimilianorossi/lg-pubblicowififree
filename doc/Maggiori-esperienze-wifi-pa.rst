Le Maggiori esperienze della WI-FI pubblica nella PA
====================================================

Analizzeremo in questo capitolo alcuni esempi di soluzione per
l’implementazione del Wi-Fi pubblico nella PA muovendo da esperienze
realizzate nelle città di Roma e Milano che, come molte altre PA locali
hanno dato impulso al Wi-Fi pubblico. Per quanto riguarda la PA centrale
è possibile invece evidenziare l’ esempio virtuoso costituito dal
protocollo di Intesa siglato da MISE, MIBACT e Agenzia per l’Italia
Digitale  [11]_

La soluzione di Roma Capitale
-----------------------------

Roma Capitale [12]_, mediante il progetto Digit Roma permette ai
cittadini e a tutti coloro che si trovano occasionalmente in città (per
lavoro, per turismo…) di avere accesso alla connessione gratuita ad
internet, attraverso una rete di hotspot WiFi.

La registrazione avviene recandosi presso uno dei punti di accesso con
il proprio dispositivo mobile (notebook, smartphone o tablet) dotato di
un'interfaccia Wi-Fi, e consiste, connettendosi all’SSID DIGIT-Roma e
tramite “\ *captive portal*\ ”, nel fornire nome, cognome, e-mail e
numero di telefono mobile. Nell’ambito della procedura di registrazione
l'utente è richiesto di effettuare una chiamata gratuita al numero
indicato, per convalidare la registrazione. Una volta chiusa la
chiamata, il sistema invia una mail con username e password alla casella
email indicata nella procedura di registrazione.

Dal momento dell'identificazione è necessario effettuare il primo
accesso entro le successive 24 ore, altrimenti la registrazione viene
annullata e occorrerà ripetere l'operazione.

Una volta effettuata la registrazione, sarà possibile fruire di 4 ore di
connessione gratuita al giorno, conteggiate sulla base dell'effettivo
tempo di navigazione nell'arco delle 24 ore.

Negli ultimi mesi a Roma Capitale è stata attivata anche la procedura di
autenticazione tramite SPID ovvero il sistema pubblico di
identificazione.

La soluzione basata su SPID svincola evidentemente il soggetto erogatore
da tutti gli oneri derivanti dalla necessità di
registrazione/identificazione e conseguente generazione delle
credenziali.

Tale soluzione non è tuttavia utilizzabile qualora il soggetto
richiedente sia uno straniero.

La soluzione del comune di Milano
---------------------------------

Nelle zone di copertura ciascun utente ha a disposizione, per la
navigazione, un servizio di accesso ad internet illimitato 24 ore su 24,
7 giorni su 7 ad alta velocità.

La registrazione avviene, una volta rilevata la rete wireless tramite
SSID, direttamente sul dispositivo attraverso la pagina di benvenuto
dove dovranno essere fornite le informazioni richieste tra le quali
obbligatoriamente andrà inserito il numero di cellulare di un gestore
telefonico italiano o straniero sul quale verrà inviato un SMS gratuito
con il codice di accesso. L'accesso alla rete OpenWifiMilano [13]_
avviene connettendosi al link ricevuto via SMS che conterrà anche il
codice di accesso che potrà essere utilizzato anche con altri sistemi
(tablet, PC portatili, etc.). Il suddetto codice è valido
permanentemente.

Come possiamo notare sia a Milano che Roma la registrazione può avvenire
attraverso la SIM del dispositivo mobile. Questa procedura di
identificazione è indiretta in quanto, per vedersi assegnare una scheda
SIM da un gestore telefonico, necessariamente occorre essere stati
identificati.

Il Progetto Wifi.Italia.it
--------------------------

In questo quadro tecnologico, con l’obiettivo di fornire un sistema di
accesso semplificato e unico per i cittadini italiani e i turisti,
nonché favorire razionalizzazioni di spesa e riuso dei sistemi
tecnologici adottati dalle Amministrazioni Pubbliche è nato il progetto
wifi.italia.it (`www.wifi.italia.it <http://www.wifi.italia.it>`__).

Il sistema wifi.italia.it, la cui architettura prende spunto da un
progetto di integrazione delle reti Wi-Fi nato nelle università europee
e ormai esteso in tutto il mondo chiamato Eduroam [14]_, è basato
completamente su standard aperti ed è in preparazione il rilascio di
tutto il SW in licenza Open Source, in collaborazione con developers.it
promosso dalla Presidenza del Consiglio.

A seguito del Protocollo di Intesa sottoscritto da AgID, MiSE e MiBACT
“Per la diffusione di piattaforme digitali al servizio del turista nel
territorio italiano” che prevede diverse iniziative volte a favorire la
digitalizzazione dei servizi in ambito turistico e culturale, il MISE ha
provveduto, attraverso Infratel Italia SpA, allo sviluppo di una APP per
dispositivi mobili, con la quale gli utenti possono accedere in maniera
automatica e semplice a tutte le reti Wi-Fi federate al progetto. L’APP
multipiattaforma, una volta scaricata e installata, richiede all’utente
la registrazione (da febbraio 2018 è attiva anche la registrazione con
credenziali SPID) che si conclude con la creazione sul dispositivo di
credenziali di accesso utilizzate, in maniera completamente trasparente
all’utente, nella richiesta di autorizzazione alla rete. L’utente, una
volta autorizzato, può usufruire del servizio gratuito di connettività
Internet fornito dalle sedi della PA. La banda dedicata al servizio,
così come le soglie sul numero massimo di utenti o di allocazione
temporale per utente, secondo la logica federata, sono quelle definite
dalla rete che sta fornendo il servizio di accesso ad internet in quel
momento. La soluzione resa disponibile allo stato consente l’esclusivo
accesso per il tramite di dispositivi mobili (smartphone e tablet).
Entro l’estate 2018 sarà disponibile anche una soluzione per p.c.

L'idea di funzionamento del sistema si basa, pertanto, sulla
disponibilità per gli utenti, di una APP che riconosce e interagisce con
un SSID unico “wifi.italia.it”.

Non appena un utente entra nell’area di copertura di un Access Point
appartenente alla rete integrata, l’APP procede, in maniera del tutto
trasparente, all’autenticazione e accede alla rete. Una notifica avverte
l’utente che l’operazione è andata a buon fine. Quindi l’utente non deve
selezionare alcuna rete e non deve passare per alcun Captive Portal,
infatti l’accesso avviene in automatico.

Le reti Wi-Fi delle pubbliche amministrazioni, per diventare parte del
sistema, devono quindi configurare i loro Access Point con un nuovo
SSID, senza necessariamente dismettere gli altri servizi e/o SSID,
impostato con autenticazione 802.1x verso un Authentication Server
Radius remoto gestito da Infratel Italia.

Secondo questa architettura, la APP e il sistema wifi.italia.it
gestiscono oltre alla prima (e unica) registrazione dell’utente,
l’autenticazione dello stesso sulla rete. Una volta che l’utente viene
autenticato con la APP la navigazione è totalmente gestita dalla rete
che lo sta “ospitando “in quel momento.

Conseguentemente il sistema wifi.italia.it raccoglie e gestisce i dati
di registrazione degli utenti e di quelli relativi alle loro
autenticazioni sulle reti federate, anonimizzandoli e solo per i fini
dell’esecuzione del servizio. Mentre i dati di navigazione, con il
riferimento all’utente codificato e interpretabile solo da
wifi.italia.it, ma non dalla rete, sono invece, raccolti e gestiti
esclusivamente dalle reti federate secondo le modalità proprie di
ciascuna rete

L’adesione al sistema permetterà alle amministrazioni di dismettere i
sistemi di autenticazione e gestione delle identità degli utenti, allo
stato attivi, per utilizzare l’accesso all’SSID **“wifi.italia.it”**.

L’adozione di tale soluzione da parte della PA, consentirebbe loro di
eliminare i costi per la gestione di tali sistemi, nonché il carico, ed
i relativi costi, in termine di gestione dei dati degli utenti, ai fini
della legislazione sulla sicurezza dei dati personali.
