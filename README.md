# Health-Future-Map
AVVIO
1. Estrai tutto il contenuto dello ZIP in una cartella.
2. Installa Node.js LTS da https://nodejs.org/ (solo la prima volta).
3. Fai doppio clic su "Avvia piattaforma.bat".
4. Il browser si aprirà su http://127.0.0.1:4173.
5. All'apertura compare una richiesta di consenso: scegli Sì per autorizzare la creazione automatica delle cartelle oppure No per continuare con il solo archivio interno del browser.

CARTELLE AUTOMATICHE
- Health Future Map non chiede di scegliere una destinazione.
- Se autorizzi, il server locale crea e gestisce le cartelle esclusivamente dentro "Cartelle pazienti", nella cartella della piattaforma.
- La gerarchia viene predisposta automaticamente: Regione → Ospedale → Codice paziente e nominativo → Sessione → PDF.
- Se una cartella esiste già, viene riutilizzata: non viene duplicata.
- Quando selezioni una persona già presente, il sistema riutilizza il suo codice e la relativa cartella.
- I PDF restano anche nell'archivio interno del browser; con il consenso viene scritta inoltre una copia fisica nella cartella dedicata.
- Se rifiuti il consenso o il server locale non è disponibile, il flusso continua usando l'archivio locale del browser come prima.
- In questo caso, dopo l'esportazione del report DNA compare il pulsante “Vai ai PDF del paziente”, che apre direttamente la cartella del paziente e l'ultima sessione nell'archivio interno.

PRIVACY E LIMITI
La richiesta iniziale autorizza la scrittura locale nella sola cartella "Cartelle pazienti" della piattaforma. Non viene chiesta né usata una cartella scelta dall'utente. Il server ascolta solo sull'indirizzo locale 127.0.0.1.
I dati e i profili inclusi nel prototipo sono dimostrativi/fittizi. Non caricare dati sanitari reali e non usare il prototipo per decisioni cliniche.

OSPEDALI
Le denominazioni presenti nell'archivio sono nomi di strutture reali usati come riferimenti dimostrativi, ma l'elenco non è un censimento ufficiale completo e può non essere aggiornato. La fonte istituzionale per verificare denominazioni, codici e stato di attività è l'anagrafe del Ministero della Salute:
https://www.salute.gov.it/new/it/banche-dati/elenco-aziende-sanitarie-locali-e-strutture-di-ricovero/
La banca dati ministeriale pubblica le strutture di ricovero attive al 1° ottobre 2026 ed è aggiornata annualmente. Le voci già presenti nel prototipo non sono state presentate come verifica individuale di ogni singola struttura.

FUNZIONI
- Analisi DNA didattica interamente nel browser.
- Selezione di strutture e profili fittizi.
- Cartelle virtuali e PDF nell'archivio interno del browser.
- Copia fisica locale dei PDF se viene concesso il consenso iniziale.
- Interfaccia adattiva: i pulsanti Videocall e App Cerotto si dispongono accanto alla navigazione o vanno a capo sotto il logo in base allo spazio disponibile.

LINK VIDEO SPIEGAZIONE GOOGLE DRIVE
https://drive.google.com/file/d/1igSK3B9X9hzXm3oK0vt4i1-nlywHzxl6/view?usp=sharing

NOTA
Le firme genetiche incluse nel progetto sono artificiali e dimostrative. I colori non sono diagnosi, non stimano una probabilità individuale e non indicano una prognosi. Il progetto non sostituisce il parere di un medico.
