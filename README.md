# Cisco-Introduction-to-Cybersecurity
Course

Cisco verifies the earner of this badge successfully completed the Introduction to Cybersecurity course. 

The holder of this student-level credential has introductory knowledge of cybersecurity, including the global implications of cyber threats on industries, and why cybersecurity is a growing profession. 
They understand vulnerabilities and threat detection and defense. 

They also have insight into opportunities available with pursuing cybersecurity certifications.

Contents:

Vulnerabilità hardware

Vulnerabilità software 
- Overflow del buffer
- Input non validato
- Race condition
- Punti deboli nelle procedure di sicurezza
- Problemi di controllo degli accessi

Tipologie di malware
- Spyware
- Adware
- Bot
- Ransomware
- Scareware
- Rootkit
- Virus
- Trojan Horse
- Worm
- Man-In-The-Middle (MitM)
- Man-In-The-Mobile (MitMo)

Sintomi del malware

•	Aumento nell'utilizzo di CPU.

•	Riduzione nella velocità del computer.

•	Il computer spesso si blocca o si arresta in modo anomalo.

•	Riduzione nella velocità di navigazione nel Web.

•	Problemi inspiegabili con le connessioni di rete.

•	File modificati.

•	File eliminati.
•	Presenza di file, programmi o icone desktop sconosciuti.

•	Processi sconosciuti in esecuzione.

•	I programmi si disattivano o riconfigurano autonomamente.

•	Invio di e-mail senza che l'utente ne sia a conoscenza o abbia acconsentito.


Social engineering
- Pretexting
- Tailgating
- Something for Something (Quid pro quo)

Violazione delle password Wi-Fi
- Social engineering
- Attacchi "brute-force": 
- Network sniffing

Phishing

Exploit delle vulnerabilità (4 fasi)

Minacce avanzate persistenti (APT)

Attacchi Denial-of-Service (DoS) 
- Overwhelming Quantity of Traffic
- Maliciously Formatted Packets

Attacco Distributed DoS (DDoS) 

Alterazione SEO
- SEO poisoning

Attacco misto
- malware che sono un ibrido degli schemi di worm, Trojan horse, spyware, keylogger, spam e phishing
tramite messaggi e-mail spam, messaggistica istantanea o siti Web legittimi 
- DDoS in combinazione con e-mail di phishing
- Molti dei worm più dannosi per i computer come Nimbda, CodeRed, BugBear, Klez e Slammer sono classificati più specificatamente come attacchi misti
- I recenti worm Conficker e ZeuS/LICAT sono stati classificati come attacchi misti

Riduzione dell'impatto

Protezione dei dispositivi di elaborazione
•	Mantenere il firewall attivo
•	Utilizzare antivirus e antispyware
•	Gestire sistema operativo e browser
•	Proteggere tutti i dispositivi

Dispositivi IoT
- I dispositivi IoT espongono l'utente ad un rischio persino maggiore dei dispositivi di elaborazione. 
La maggior parte dei dispositivi IoT continua a mantenere il firmware originale. Se nel firmware vengono individuate vulnerabilità, è probabile che il dispositivo IoT rimanga vulnerabile.
Protezione è avere dispositivi IoT in una rete isolata condivisa solo con altri dispositivi IoT. (SHODAN)

Utilizzare le reti wireless in sicurezza
- SSID (Service Set Identifier) e password
- crittografare la comunicazione wireless abilitando le funzioni di sicurezza wireless e crittografia WPA2 sul router wireless. 
- il router wireless può essere configurato per non trasmettere lo SSID
- non accedere ad alcun dato personale sensibile o inviarlo tramite una rete wireless pubblica
eavesdropping: altri possano intercettare i dati 
- utilizzare tunnel e servizi VPN crittografati
- gli hacker possono eseguire l'exploit della funzionalità Bluetooth per intercettare le trasmissioni su alcuni dispositivi, stabilire controlli degli accessi in remoto, distribuire malware e scaricare le batterie. Per evitare questi problemi, disattivare la funzionalità Bluetooth quando non è in uso.




Utilizzare password univoche per ogni account online

Suggerimenti per la scelta di una buona password:

•	Non utilizzare parole o nomi tratti da un dizionario in qualsiasi lingua sia

•	Non utilizzare errori ortografici comuni di parole del dizionario

•	Non utilizzare nomi di computer o di account

•	Se possibile, usa caratteri speciali come ! @ # $ % ^ & * ( )

•	Utilizzare una password composta da almeno dieci caratteri




Utilizzare passphrase anziché password

Suggerimenti per la scelta di una buona passphrase: 

•	Scegliere un'affermazione significativa

•	Aggiungere caratteri speciali come ! @ # $ % ^ & * ( )

•	Maggiore è la lunghezza e migliore è la passphrase

•	Evitare frasi comuni o famose, ad esempio testi di una canzone famosa


Crittografare i dati
- Windows Encrypting File System (EFS) 

Eseguire il backup dei dati
- dispositivo Network Attached Storage (NAS), 
- hard drive esterno, pen drive, CD/DVD
- servizio di cloud storage come Amazon Web Services (AWS)
sicurezza in caso di incendio, furto o altre catastrofi 

Eliminazione permanente dei dati
- Per cancellare i dati in modo che non siano più recuperabili, devono essere sovrascritti più volte con valori uno e zero. 
- Per evitare il recupero di file eliminati: SDelete di Microsoft, Shred per Linux e Secure Empty Trash per Mac OSX
- Il solo modo per avere la certezza che i dati o i file non siano recuperabili, è distruggere fisicamente l'hard drive o la periferica di memorizzazione
- Anche copie memorizzate online su cloud devono essere eliminate

Autenticazione a due fattori
- nome utente e password o PIN (Personal Identification Number) 
- secondo token (fisico o scansione biometrica)

Open Authorization (OAuth) 2.0
- Protocollo che agisce da intermediario permette alle credenziali degli utenti finali di accedere alle applicazioni di terze parti 
senza esporre la password

Non condividere troppe informazioni sui social media
- Non è consigliabile condividere informazioni come data di nascita, indirizzo e-mail o numero di telefono sul proprio profilo. 
- Utilizzare uno strumento per la gestione delle password per gestirle.

Privacy di e-mail e browser Web

Chi ha accesso fisico al computer o al router, può vedere quali siti Web sono stati visitati tramite la cronologia del browser Web, la cache e anche i file di log.

Usare modalità di esplorazione in privato:

•	Microsoft Internet Explorer: InPrivate

•	Google Chrome: Incognito

•	Mozilla Firefox: scheda Private / finestra Private

•	Safari: Private: Private browsing


Proteggere l'azienda

- firewall, appliance di sicurezza e software attualmente utilizzati, best-practice
- botnet, tattiche kill chain, sicurezza basata sui comportamenti, uso di NetFlow per il monitoraggio delle reti.
- team CSIRT, manuale della sicurezza, strumenti impiegati dai professionisti della cybersecurity per rilevare e prevenire gli attacchi alle reti.


Tipi di firewall

•	Firewall a livello di rete – il filtro opera in base agli indirizzi IP d'origine e di destinazione

•	Firewall a livello di trasporto – il filtro opera in base alle porte dati d'origine e di destinazione nonché sugli stati delle connessioni

•	Firewall a livello applicativo – il filtro opera in base ad applicazioni, programmi e servizi

•	Firewall per il controllo di applicazioni basato sul contesto – il filtro opera in base a utente, dispositivo, ruolo, applicazione e profilo della minaccia

•	Server proxy – esegue il filtraggio delle richieste di contenuti Web quali URL, dominio, mezzi di comunicazione ecc

•	Server proxy reverse – posizionati davanti ai server Web, i server proxy reverse proteggono, nascondono, eseguono l'offload e distribuiscono gli accessi ai server Web

•	Firewall NAT (Network Address Translation) – nasconde o maschera gli indirizzi privati degli host di rete

•	Firewall basato su host – esegue il filtraggio delle chiamate a porte e servizi di sistema nell'ambito del sistema operativo di un determinato computer


Scansione delle porte

- strumento per la scansione delle porte (Nmap)

- La scansione Nmap indicherà tutti i servizi in esecuzione (ad esempio i servizi Web, i servizi e-mail ecc.) e i numeri delle porte. 
In generale, la scansione di una porta restituisce uno dei tre risultati seguenti:

•	Aperta o Accettata – L'host ha risposto indicando che un servizio è in ascolto sulla porta.

•	Chiusa, Rifiutata o Non in ascolto – L'host ha risposto indicando che i tentativi di connessione alla porta verranno rifiutati.

•	Filtrata, Interrotta o Bloccata – Non è stata ricevuta alcuna risposta dall'host.


Significa condurre una scansione delle porte Nmap nei confronti del tuo firewall o dell'indirizzo IP pubblico del tuo router. 
- Nmap Online Port Scanner 

Appliance di sicurezza

Le appliance di sicurezza possono essere HW costituite da dispositivi autonomi, come i router e i firewall, schede installate all'interno di dispositivi di rete oppure da moduli dotati di processore e memoria cache propri. 
Le appliance di sicurezza possono anche essere SW costituite da strumenti software eseguiti all'interno di dispositivi di rete. 

Categorie generali:

Router - instradamento e numerose funzionalità firewall quali filtraggio del traffico, capacità di eseguire un sistema di prevenzione delle intrusioni (IPS) nonché di funzionalità VPN per un tunneling crittografato sicuro. 

Firewall - Next Generation Firewall offrono tutte le funzionalità di un router nonché quelle di gestione e analisi evoluta della rete. 

IPS - i dispositivi IPS sono dedicati alla prevenzione delle intrusioni. 

VPN - tecnologie server e client VPN (Virtual Private Network) per il tunneling crittografato sicuro.

Malware/Antivirus - strumento evoluto di protezione dal malware presente nei router, firewall, dispositivi IPS e appliance di sicurezza e-mail e Web può anche essere installato, come software, nei computer host.

Altri dispositivi di sicurezza - appliance di sicurezza e-mail e Web, dai dispositivi per la decrittografia, server per il controllo degli accessi client 

Rilevamento degli attacchi in tempo reale

-- Attacco Zero-Day:

Il software non è perfetto. Quando un hacker sfrutta un errore contenuto in un software prima che il creatore di quest'ultimo possa porvi rimedio, si è in presenza di un attacco zero-day. 

•	Scansione in tempo reale dalla periferia all'endpoint - il rilevamento degli attacchi in tempo reale richiede l'esecuzione di scansioni per mezzo di firewall e di dispositivi di rete IDS/IPS. Inoltre, è necessario avvalersi anche di strumenti di rilevamento di malware client/server di nuova generazione dotati di collegamenti con centri globali per lo studio delle minacce. 

•	Attacchi DDoS e risposta in tempo reale - il DDoS è una delle principali minacce che richiedono un rilevamento e una risposta in tempo reale. È molto difficile difendersi dagli attacchi DDoS, poiché questi ultimi hanno origine da centinaia, se non migliaia, di host zombie e assumono l'apparenza di traffico legittimo.
Gli attacchi DDoS periodici compromettono i server Internet e la disponibilità della rete. 

Proteggersi dal malware
- difendersi dalla presenza costante di attacco zero-day nonché dalle minacce avanzate persistenti (APT, Advanced Persistent Threat) che rubano dati 
- Un Threat Grid analizza milioni di file e li associa a centinaia di milioni di altri artefatti malware analizzati, fornendo una visione globale degli attacchi, delle campagne e della distribuzione del malware. E' un software client/server implementato negli endpoint host, come i server standalone o in altri dispositivi di sicurezza di rete. 

Best-practice per la sicurezza

•	Eseguire la valutazione dei rischi – conoscere il valore di ciò che si sta proteggendo aiuta a giustificare le spese in materia di sicurezza.

•	Creare una policy di sicurezza – creare una policy che definisca chiaramente regole aziendali, mansioni e aspettative.

•	Misure per la sicurezza fisica – limitare l'accesso agli armadi di rete, ai luoghi dove si trovano i server nonché ai dispositivi antincendio.

•	Misure di sicurezza nei confronti delle risorse umane – è necessario condurre ricerche adeguate sul dipendenti e prevedere un controllo del background di ciascuno.

•	Eseguire e testare i backup – eseguire backup periodici e verificare che essi consentano il recupero dei dati.

•	Mantenere patch e aggiornamenti per la sicurezza – aggiornare periodicamente sistemi operativi e programmi a bordo di server, client e dispositivo di rete.

•	Attuare il controllo degli accessi – configurare ruoli e livelli di privilegi diversificati in base agli utenti e utilizzare sistemi di autenticazione forte.

•	Verificare periodicamente la capacità di reazione agli incidenti – costituire un team per la reazione agli incidenti ed eseguire test sulla risposta in caso di emergenza nel caso di diversi scenari.

•	Implementare uno strumento per il monitoraggio, l'analisi e la gestione della rete - scegliere una soluzione per il monitoraggio di sicurezza che si integri con altre tecnologie.

•	Implementare dispositivi per la sicurezza di rete – usare router, firewall e altre appliance di sicurezza di nuova generazione.

•	Implementare una soluzione completa per la sicurezza degli endpoint – usare software antimalware e antivirus a livello aziendale.

•	Educare gli utenti – educare utenti e dipendenti ad adottare procedure di sicurezza.

•	Crittografare i dati – crittografare tutti i dati aziendali sensibili, comprese le e-mail.



Linee guida
- NIST (National Institute of Standards and Technology) 
- CSRC (Computer Security Resource Center)

Botnet

I botnet possono essere costituiti da decine, o anche centinaia, di migliaia di bot. Questi bot possono essere attivati per distribuire malware, lanciare attacchi DDoS, diffondere e-mail di spam o eseguire attacchi brute-force per la violazione delle password. I botnet sono generalmente controllati per mezzo di un server di comando e controllo.

La kill chain 

cybersecurity, la kill chain descrive le fasi di un attacco ai sistemi informatici. 

Fase 1. Ricognizione - gli hacker raccolgono informazioni sull'obiettivo.

Fase 2. Adescamento - gli hacker creano un payload dannoso di tipo exploit da inviare all'obiettivo.

Fase 3. Dirottamento - gli hacker inviano il payload dannoso di tipo exploit all'obiettivo per mezzo di e-mail o altri metodi.

Fase 4. Exploit - l'exploit viene eseguito.

Fase 5. Installazione - il malware e le backdoor vengono installate all'interno dell'obiettivo.

Fase 6. Comando e controllo - il controllo remoto dell'obiettivo viene assunto per mezzo di un canale o di un server di comando e controllo.

Fase 7. Azione - gli hacker eseguono azioni dannose quali il furto di informazioni oppure sferrano, dall'interno della rete, ulteriori attacchi nei confronti di altri dispositivi attuando nuovamente le fasi della kill chain. 


• Quali sono i segnali di un attacco in corso in ciascuna fase della kill chain? 

• Quali strumenti di sicurezza sono necessari per rilevare i segnali di attacco in ciascuna delle fasi?

• Vi sono lacune nella capacità dell'azienda di rilevare un attacco?


Sicurezza basata sui comportamenti

- Honeypot - strumenti di rilevamento basati sui comportamenti che attirano gli hacker 
Quando gli hacker sono all'interno dell'honeypot, gli amministratori di rete possono acquisire, registrare e analizzare il loro comportamento. 

- Cyber Threat Defense - si tratta di un'architettura di sicurezza che impiega il rilevamento basato sui comportamenti e gli indicatori per fornire maggiore visibilità, contesto e controllo. In caso di attacco, l'obiettivo è conoscere "chi", "cosa", "dove", "quando" e "in che modo"



NetFlow
- raccoglie informazioni sul flusso dei dati all'interno delle reti
raccoglie, archivia e analizza dati in ingresso, in uscita e in transito nella rete
è in grado di determinare comportamenti di riferimento 

CSIRT

Molte grandi aziende dispongono di un gruppo CSIRT (Computer Security Incident Response Team) preposto alla ricezione, analisi e reazione agli incidenti in materia di sicurezza informatica
Per prevenire gli incidenti di sicurezza, il CSIRT Cisco effettua una valutazione proattiva delle minacce, pianifica la riduzione del rischio, analizza le tendenze mostrate dalle violazioni ed esamina l'architettura di sicurezza

FIRST (Forum of Incident Response and Security Teams)

NSIE (National Safety Information Exchange)

DSIE (Defense Security Information Exchange)

DNS-OARC (Operations Analysis and Research Center)


Manuale della sicurezza

il manuale per la sicurezza deve adempiere ai seguenti compiti:

•	Rilevare i computer infettati da malware.

•	Rilevare attività di rete sospette.

•	Rilevare tentativi di autenticazione irregolari.

•	Descrivere e illustrare il traffico in ingresso e in uscita.

•	Fornire informazioni di riepilogo su tendenze, statistiche e conteggi.

•	Garantire modalità di accesso rapide e fruibili a statistiche e metriche.

•	Correlare gli eventi per tutte le origini dati interessate.



Strumenti per la prevenzione e il rilevamento degli incidenti


•	SIEM – i sistemi SIEM (Security Information and Event Management, gestione di eventi e informazioni sulla sicurezza) sono costituiti da software che raccoglie e analizza gli allarmi relativi alla sicurezza, i log e altri dati cronologici e in tempo reale provenienti dai dispositivi di sicurezza presenti nella rete.


•	DLP – i sistemi DLP (Data Loss Prevention) sono elementi software o hardware progettati per impedire il furto o la fuoriuscita di dati sensibili dalle reti. I sistemi DLP possono concentrarsi sull'autorizzazione all'accesso ai file, lo scambio o la copia di dati, il monitoraggio delle attività degli utenti e molto altro. I sistemi DLP sono progettati per monitorare e proteggere dati che presentino tre stati diversi: dati in uso, dati in movimento e dati a riposo. I dati in uso sono principalmente riferiti ai client; i dati in movimento sono quelli che si muovono attraverso la rete e i dati a riposo sono riferiti all'archiviazione dei dati. 


•	ISE e TrustSec – gli strumenti Cisco ISE (Identity Services Engine) e TrustSec intervengono sull'accesso alle risorse di rete creando policy che segmentano l'accesso stesso in categorie (ospiti, utenti mobili, dipendenti) senza aggiungere complessità. La classificazione del traffico si basa sull'identità degli utenti o dei dispositivi. 

IDS e IPS
(IDS, Intrusion Detection System)
Se viene rilevata una corrispondenza, l'IDS registra il rilevamento e crea un avviso destinato all'amministratore di rete ma non impedisce il verificarsi degli attacchi. 


(IPS, Intrusion Prevention System) 
Può bloccare o rifiutare traffico in base a regole positive o in caso di corrispondenza della firma. 
Analisi in tempo reale di traffico e porte, registrazioni, ricerca e analisi della corrispondenza dei contenuti; può rilevare tentativi di verifica, attacchi e operazioni di scansione delle porte. si integra all'interno di strumenti di terze parti per la creazione di report e analisi di prestazioni e log.
Es. Snort e Cisco Sourcefire.






