Cosa è il Wi-Fi
===============

Il Wi-Fi (Wireless Fidelity), detta anche rete wireless o rete Wi-Fi è
una tecnologia che permette ai dispositivi di scambiarsi dati senza
fili, utilizzando onde radio. Il WiFI, oggi, aggiornato e integrato da
sviluppi e innovazioni, è diventato uno dei principali standard per la
trasmissione dei dati in formato digitale ed è in continua diffusione e
crescita.

Atto costitutivo di questa tecnologia può considerarsi la decisione
della Federal Communications Commission (FCC) statunitense (l'ente
regolatore del settore delle telecomunicazioni) di liberare alcune
frequenze e renderle disponibili all'uso civile senza obbligo di
licenza. Nel 1997 con la prima versione ufficiale del protocollo
denominato “IEEE 802.11”, sviluppato da una delle commissioni del
Institute of Electrical and Electronic Engineers (IEEE), associazione
internazionale di scienziati professionisti che si occupa di ricerche
sulle nuove tecnologie, iniziò l’epoca delle trasmissioni wireless con
una connessione che raggiungeva la velocità di 2 Mbit al secondo. Due
anni più tardi, nel 1999, vedeva la luce il protocollo 802.11b, insieme
con il nome “Wi-Fi” e il relativo logo e nasceva ufficialmente la
tecnologia Wi-Fi. Da quel momento si è assistito al costante e continuo
sviluppo di questa tecnologia e all’evoluzione degli standard anche per
via della grande diffusione dei dispostivi mobili.

Gli standard del Wi-Fi
----------------------

In questo paragrafo mostreremo le tappe fondamentali delle
certificazioni dello IEEE che stabiliscono gli standard tecnologici sui
quali i produttori realizzano i loro dispositivi Wi-Fi. Ad oggi
gli \ `standard
Wi-Fi <http://www.fastweb.it/internet/guida-agli-standard-wi-fi-per-la-velocita-connessione/>`__
esistenti sono 9, anche se i più utilizzati sono 4. (QUALI?)

+-----------------+-----------------+-----------------+-----------------+
| Certificazione  | Velocità di     | Frequenza di    | Mezzo           |
|                 | trasmissione    | lavoro          | trasmissivo     |
|                 | max             |                 |                 |
+=================+=================+=================+=================+
| 802.11          | Da 1 a 2 Mb/s   | 2.4 GHz         | Infrarossi/onde |
|                 |                 |                 | radio           |
+-----------------+-----------------+-----------------+-----------------+
| 802.11b         | 11 Mb/s         | 2.4 GHz         | Onde Radio      |
+-----------------+-----------------+-----------------+-----------------+
| 802.11a         | 54 Mb/s         | 5,4 GHz         | Onde Radio      |
+-----------------+-----------------+-----------------+-----------------+
| 802.11g         | 54 Mb/s         | 2.4GHz          | Onde Radio      |
+-----------------+-----------------+-----------------+-----------------+
| 802.11n         | 300 Mb/s        | 2.4GHz/5,4 GHz  | Onde Radio      |
+-----------------+-----------------+-----------------+-----------------+
| 802.11ac        | 1300 Mb/s       | 5,4 GHz         | Onde Radio      |
+-----------------+-----------------+-----------------+-----------------+
| IEEE 802.11ad   | 6750 Mb/s       | 60 GHz          | Onde Radio      |
+-----------------+-----------------+-----------------+-----------------+

**Tabella 1: Tappe fondamentali implementazioni ordinate per velocità di
trasmissione crescente WIFI**

Come possiamo notare in tabella, l’evoluzione tecnologica avvenuta a
cavallo degli ultimi 20 anni, si focalizza sulla velocità di
trasmissione, ma come vedremo ne prossimi paragrafi anche nei sistemi di
sicurezza ed autenticazione.

Nel giugno 2003 venne rilasciata la certificazione 802.11g, che fa
segnare un netto miglioramento nelle prestazioni (sia per la forza del
segnale sia per i picchi di velocità raggiungibili) rispetto ai due
predecessori. Lo standard 802.11g lavora sulla banda di frequenza da 2,4
GHz, copre aree di circa 100 metri e permette teoricamente la
trasmissione di dati fino a 54Mbps (sebbene mediamente si attesti
attorno ai 22-24 Mbps). Un ulteriore avanzamento delle prestazioni si è
avuta con la certificazione 802.11n, rilasciata nel 2009. Questo nuovo
standard si basa sull'utilizzo di diverse
antenne \ `MIMO <http://www.fastweb.it/internet/cos-e-la-tecnologia-mimo/>`__ (multiple-input,
multiple-output) che lavorano sulle frequenze di 2,4 GHz e 5 GHz
consentendo velocità che possono, in teoria, arrivare anche 600 Mbps. A
questo è seguito lo standard 802.11ac, che ha portato le velocità di
connessione a 1,3 Gbps (il doppio rispetto allo standard n, oltre 20
volte più veloce rispetto allo standard g) per via della differente
divisione in sottobande della banda da 5 GHz e dall'impiego di
differenti standard di comunicazione. Negli ultimi anni, la Wi-Fi
Alliance ha studiato e definito altri tre standard che, sfruttando bande
di comunicazioni differenti, ampliano lo spettro delle possibili
applicazioni e utilizzi dello standard senza fili. L'IEEE
802.11ah sfrutta la banda da 1 gigahertz per connessioni più stabili e
meno soggette al rumore; \ `l'IEEE
802.11af <http://www.fastweb.it/internet/watch-il-progetto-per-integrare-wi-fi-e-uhf-televisivo/>`__,
detto anche super Wi-Fi, lavora sulla banda di comunicazione riservata
alle comunicazioni televisive per assicurare connessioni stabili e a
grande velocità; l'IEEE 802.11ad (detto
anche \ `WiGig <http://www.fastweb.it/web-e-digital/intel-punta-a-eliminare-i-cavi-dei-pc/>`__),
infine, lavora sulla banda di frequenza dei 60 GHz e, pur coprendo
distanze minori, può raggiungere la velocità di connessione di 7 gigabit
ed è utilizzabile per le applicazioni ‘smart home’ che richiedono una
banda sempre più ampia e stabile.

Architettura di una rete Wi-Fi
------------------------------

Una rete Wi-Fi è composta da uno o più Access Point (AP) che possono
essere adibiti a "sorgente" del segnale, e uno o più client che si
connettono ad essa.

A sua volta le rete Wi-Fi è generalmente collegata alla rete fissa;
l’Access Point può infatti essere considerato come il Gateway tra la
rete senza fili e quella fissa. Il segnale wireless di un singolo access
point solitamente copre un'area tra i 50 ed i 100 metri in base alla
configurazione architettonica dell'area coperta, ma può essere esteso in
diversi modi. Si
può \ `amplificare <http://www.fastweb.it/internet/come-amplificare-il-segnale-wi-fi-del-router/>`__,
ad esempio, attraverso il collegamento di differenti AP tramite cavo,
oppure creando un "ponte" wireless con ripetitori di segnali. Ogni AP
trasmette, ogni 100 ms, un pacchetto dati,
chiamato \ *beacon*\  [2]_ contenente lo SSID (Service Set Identifier)
che rappresenta l’identificativo della rete e altre informazioni, come
il protocollo di sicurezza utilizzato. Il client (qualsiasi dispositivo
dotato di scheda Wi-Fi o un ripetitore di segnale) può decidere di
connettersi alla rete seguendo diverse logiche: ad esempio, può
collegarsi alla rete con un SSID noto, ossia a una rete alla quale già
ci si è connessi in precedenza, oppure a quella dal segnale più forte e
che quindi garantisce le prestazioni migliori (modalità *always best
connected*).

Accesso e autenticazione alla rete Wi-Fi
----------------------------------------

Ogni volta che un client accede ad una rete wireless, si avvia un
processo di autenticazione che consiste in tre fasi: discovery della
rete, autenticazione e associazione. Ognuna di queste tre fasi avviene
con lo scambio di richieste e risposte tramite *beacons*. La fase di
autenticazione è la parte più delicata dell'intero processo.

Discovery della rete 
~~~~~~~~~~~~~~~~~~~~~~

Questa fase permette ad un client di individuare la presenza della rete,
cercando il segnale degli AP secondo determinate regole (segnale più
forte, velocità maggiore, ecc.); la rete trovata può essere aperta o
chiusa. Una rete wireless aperta si comporta in modo che gli AP inviino
periodicamente degli opportuni frame non cifrati che contengono tutte le
informazioni che servono ai client per collegarsi (SSID, velocità di
trasmissione, ecc.). In una rete chiusa, invece, è compito dei client
preoccuparsi di trovare gli AP tramite l'invio su varie frequenze di
opportuni frame di richiesta, in attesa che un AP in ascolto risponda
con un frame di risposta.

Autenticazione
~~~~~~~~~~~~~~

Una volta completata la fase di discovery, un client deve autenticarsi
presso l’AP con cui vuole comunicare. L'autenticazione è un processo che
permette a due soggetti in comunicazione di scambiare delle credenziali,
consentendo successivamente di verificare la validità delle stesse
attraverso protocolli specifici che utilizzano metodi di cifratura.

Associazione 
~~~~~~~~~~~~~

Se un client wireless è stato autenticato con successo, allora può
chiedere di essere associato alla rete. In pratica il client sceglie un
unico AP (generalmente secondo le strategie di discovery) che poi lo
abilita a collegarsi. Con la fase di associazione si conclude il
processo di autenticazione.

Sicurezza ed autenticazione 
----------------------------

Un ruolo cruciale nel progettare una rete sicura è giocato
dall’autenticazione delle parti in comunicazione, per garantire la
confidenzialità dei dati in transito. Infatti per autenticazione si
intende quel processo che permette di stabilire con certezza
l'interlocutore. La confidenzialità invece, si riferisce alla garanzia
che i dati in transito siano accessibili solo alle parti interessate, e
per questo scopo si utilizza la crittografia. Un utente che voglia
accedere ad un network deve possedere delle credenziali di accesso come
ad esempio un account o un certificato digitale, deve ad ogni modo
essere in grado di stabilire, in modo sicuro, che il Server oppure, per
le reti WI-FI l’Access Point che chiede le credenziali appartenga
effettivamente ad una rete legittima, in modo da non fornire le proprie
informazioni ad un sistema non autorizzato.

Molteplici sono state le soluzioni adottate per garantire la sicurezza
delle reti wireless che si sono evolute nel corso degli anni. I
meccanismi inerenti la cifratura e l'autenticazione erano direttamente
definiti dallo standard con il protocollo WEP
(Wired-Equivalent-Privacy), che ha in seguito mostrato gravi falle di
sicurezza. L’evoluzione di tale protocollo è il WPA (Wi-Fi Protected
Access) nelle due versioni: WPA e WPA2. Notiamo che esistono due
implementazioni di WPA2:

-  WPA2-PSK (pre-shared key) o personal

-  WPA2-Enterprise (o WPA2 802.1X).

La prima è destinata ad un uso personale e per piccole reti di ufficio,
mentre la seconda è per uso aziendale e di più complessa configurazione.
Per il corretto funzionamento del sistema di autenticazione
WPA2-Enterprise [3]_ si rende necessario un server di autenticazione
“\ *Radius*\ ” (Remote Authentication Dial In User Service).

Nel caso di una wireless, è l’AP che è adibito alle funzioni di
controllore di accesso. Il Radius, o un server/servizio di
autenticazione che risponda agli standard definiti dalle RFC 2865 e
2866, permette di validare l'identità dell'utente, trasmessa dal
controllore di accesso, e di rinviare a quest’ultimo i permessi
associati in funzione delle informazioni di identificazione fornite.
Inoltre, tale server permette di memorizzare e di rendere compatibili le
informazioni riguardanti gli utenti per, ad esempio, mantenerle per
renderle disponibili per attività giudiziaria (nel caso di un service
provider ad esempio).

Di seguito l'analisi del funzionamento di una rete resa sicura con lo standard 802.1x:

   1. Il controllore di accesso, avendo ricevuto precedentemente una
   richiesta di connessione da parte dell'utente, invia una richiesta di
   identificazione;

   2.L'utente risponde alla richiesta e invia una risposta al
   controllore di accesso, che la inoltra al server di autenticazione; 

   3.Il server di autenticazione invia la risposta di identificazione
   (metodo di identificazione) al controllore di accesso, che lo
   trasmette all'utente;

   4. L'utente, la cui identità è corretta, viene accettato sulla rete o
   su una parte di rete, secondo i permessi;

   5.Se l'identità dell'utente non si è potuta verificare, il server di
   autenticazione invia un rifiuto e il controllore di accesso rifiuterà
   l'accesso alla rete all'utente.


Sicurezza e prevenzione di potenziali attacchi
----------------------------------------------

Garantire la sicurezza di un sistema informativo e, delle informazioni
in esso contenute, si traduce nell’impedire a potenziali soggetti
attaccanti l’accesso o l’uso non autorizzato di informazioni e risorse.

Al fine di mitigare gli attacchi, la perdita di dati e utilizzo
improprio delle infrastrutture, si rende necessario impedire la
contraffazione ovvero la capacità di creazione e invio di falsi messaggi
creati con le credenziali di un utente autorizzato dal sistema.

Le tecniche intrusive di rete più comuni consistono nella:

-  capacità di inserimento di apparati wireless non autorizzati;

-  capacità di intercettazione passiva e monitoraggio del traffico di
   rete;

-  capacità di disturbo del segnale (jamming);

-  capacità di attacchi ai meccanismi di cifratura per via di debolezze
   riscontrate a livello protocollare per furto di dati;

-  errori nella configurazione della rete wireless.

Le tecniche di intrusione succitate, implementate con diverse tecnologie
ed in costante evoluzione, possono mettere a repentaglio la sicurezza
delle informazioni e dei dati, per i quali l’organizzazione deve
garantire:

-  Integrità: dati non modificati durante la trasmissione;

-  Segretezza e Riservatezza: cifratura dei dati in modo che non siano
   intercettabili;

-  Controllo Accessi: controllo accessi alle risorse da e per il
   sistema;

-  Disponibilità: un sistema deve essere disponibile almeno al 99,9% e
   solo per gli utenti accreditati;

-  Autenticazione: verifica dell’identità dichiarata dall’utente.

Con riguardo all’autenticazione ci possiamo riferire all’identificazione
certa degli utenti nella rete, degli host, delle applicazioni, dei
servizi e delle risorse [4]_


.. note::
.. [2] Frame non cifrati
.. [3] Questo tipo di gestione amministra correttamente non solo gli accessi ma anche i profili di servizio. L”802.1x si basa sul protocollo EAP (Extensible Authentication Protocol), definito dall”IETF, il cui ruolo è di trasportare delle informazioni di identificazione degli utenti. Il funzionamento del protocollo EAP è basato sull’utilizzo di un controllore di accesso, (l’authenticator), che stabilisce l’accesso alla rete per un utente (il supplicant).
.. [4] Le tecnologie standard che permettono questo includono alcuni protocolli di autenticazione come RADIUS (Remote Authentication Dial-In Users Service), Kerberos. Inoltre nuove tecnologie che si fondano su Certificati Digitali, Smart Card e Token si stanno imponendo sempre più nelle soluzioni per la definizione e verifica dell’identità.
