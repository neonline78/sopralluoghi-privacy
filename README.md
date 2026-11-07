# Informativa sulla Privacy - Applicazione "Sopralluoghi"

*Ultimo aggiornamento: Novembre 2026*

L'applicazione **Sopralluoghi** è progettata e sviluppata nel rispetto assoluto della riservatezza dei dati personali degli utenti e dei professionisti. La presente informativa descrive le modalità di trattamento dei dati raccolti tramite l'applicazione.

---

### 1. Tipologia di dati trattati e finalità

L'applicazione richiede l'accesso ad alcune funzioni hardware e risorse del dispositivo esclusivamente per scopi operativi e tecnici legati allo svolgimento dei sopralluoghi:

* **Fotocamera (`CAMERA`):** Utilizzata unicamente per scattare fotografie, registrare video dello stato dei luoghi e scansionare documenti/verbali cartacei tramite le librerie Google ML Kit Document Scanner.
* **Microfono (`RECORD_AUDIO`):** Utilizzato per la registrazione dell'audio nei video acquisiti e per la dettatura vocale degli appunti peritali.
* **Geolocalizzazione (`ACCESS_FINE_LOCATION`, `ACCESS_COARSE_LOCATION`):** Utilizzata per rilevare le coordinate geografiche al momento dell'inizio del rilievo, ricavare l'indirizzo civico tramite geocodifica inversa per nominare la cartella del sopralluogo e apporre il timbro/sigillo sulle immagini e sul brogliaccio riepilogativo.
* **Memoria e File Locali:** L'applicazione archivia i file generati all'interno della cartella privata dell'app nel dispositivo (`getExternalFilesDir`).

---

### 2. Archiviazione, Trasferimento e Condivisione dei Dati

L'applicazione adotta una politica di **trasferimento diretto "zero intermediari"**:

* **Nessun server proprietario:** Gli sviluppatori dell'applicazione non dispongono di server centralizzati, database remoti o sistemi di telemetria proprietari in grado di raccogliere, archiviare o visualizzare i dati degli utenti.
* **Google Drive:** Se l'utente decide di collegare il proprio account Google, l'app utilizza l'autorizzazione limitata `drive.file` per creare e gestire unicamente i file e le cartelle creati dall'app stessa. Nessun altro dato personale o file presente sul Drive dell'utente viene letto, modificato o condiviso.
* **NAS Locale (Protocollo SMB):** Se l'utente configura l'archiviazione su un server NAS, il trasferimento dei file avviene esclusivamente tramite connessione diretta locale tra il dispositivo dell'utente e l'infrastruttura di rete configurata dall'utente stesso. Le credenziali di accesso inserite risiedono cifrate nelle memorie locali del dispositivo e non vengono mai trasmesse all'esterno.
* **Nessuna profilazione o cessione a terzi:** Non viene effettuata alcuna attività di profilazione commerciale, tracciamento pubblicitario o cessione di dati a soggetti terzi.

---

### 3. Acquisti in-app e Abbonamenti

Le transazioni economiche relative all'acquisto della licenza o alla sottoscrizione dell'abbonamento sono gestite interamente da **Google Play Billing** (Google LLC). L'applicazione non acquisisce né conserva i dati di pagamento o le carte di credito dell'utente, che rimangono protetti dai sistemi di sicurezza di Google.

---

### 4. Diritti dell'utente e Cancellazione dei Dati

Tutti i contenuti multimediali, appunti e documenti generati risiedono sotto il controllo diretto dell'utente:
* L'utente può eliminare i sopralluoghi in qualsiasi momento dall'interfaccia dell'app o disinstallando l'applicazione stessa.
* Per revocare l'accesso dell'app a Google Drive, l'utente può disconnettere l'account dalle impostazioni dell'app o accedere alle impostazioni di sicurezza del proprio Account Google (sezione "App di terze parti con accesso all'account").

---

### 5. Contatti

Per qualsiasi chiarimento o richiesta riguardante la presente Informativa sulla Privacy, è possibile contattare lo sviluppatore all'indirizzo email di supporto indicato sulla scheda del Google Play Store.
