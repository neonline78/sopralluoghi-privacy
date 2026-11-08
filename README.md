# Informativa sulla Privacy - Applicazione "Sopralluoghi"

*Ultimo aggiornamento: Novembre 2026*

L'applicazione **Sopralluoghi** è progettata per gestire i dati dei sopralluoghi sul dispositivo e trasferirli alle destinazioni scelte dall'utente. La presente informativa descrive i dati trattati e le relative modalità di gestione.

---

### 1. Tipologia di dati trattati e finalità

L'applicazione richiede l'accesso ad alcune funzioni hardware e risorse del dispositivo esclusivamente per scopi operativi e tecnici legati allo svolgimento dei sopralluoghi:

* **Fotocamera (`CAMERA`):** Utilizzata unicamente per scattare fotografie, registrare video dello stato dei luoghi e scansionare documenti/verbali cartacei tramite le librerie Google ML Kit Document Scanner.
* **Microfono (`RECORD_AUDIO`):** Utilizzato per la registrazione dell'audio nei video acquisiti e per la dettatura vocale degli appunti peritali.
* **Geolocalizzazione (`ACCESS_FINE_LOCATION`, `ACCESS_COARSE_LOCATION`):** Utilizzata per rilevare le coordinate geografiche al momento dell'inizio del rilievo, ricavare l'indirizzo civico tramite geocodifica inversa per nominare la cartella del sopralluogo e apporre il timbro/sigillo sulle immagini e sul brogliaccio riepilogativo.
* **Memoria e File Locali:** L'applicazione archivia i file generati all'interno della cartella privata dell'app nel dispositivo (`getExternalFilesDir`).

---

### 2. Archiviazione, Trasferimento e Condivisione dei Dati

I dati sono conservati sul dispositivo o inviati alle destinazioni e ai servizi che l’utente sceglie di utilizzare:

* **Nessun server proprietario:** Gli sviluppatori dell'applicazione non dispongono di server centralizzati, database remoti o sistemi di telemetria proprietari in grado di raccogliere, archiviare o visualizzare i dati degli utenti.
* **Google Drive:** Se l'utente collega il proprio account, l'app usa l'autorizzazione `drive.file` per creare e gestire i file e le cartelle dell'app. I file dei sopralluoghi scelti per la sincronizzazione vengono trasferiti all'account Drive collegato. L'app non accede agli altri file del Drive.
* **NAS Locale (Protocollo SMB):** Se l'utente configura un NAS, l'app trasferisce i file direttamente al server indicato tramite SMB. Nome utente e password NAS sono cifrati sul dispositivo con AES-GCM usando una chiave custodita in Android Keystore; i dati cifrati sono esclusi dai backup. Le credenziali vengono inviate al NAS configurato per autenticare il collegamento e non a server gestiti dallo sviluppatore.
* **Servizi Google:** Il collegamento Drive, Google Play Billing, lo scanner documenti e le funzioni Android/Google di riconoscimento vocale o geocodifica possono coinvolgere i relativi servizi Google secondo le impostazioni del dispositivo e dell'account. L'app non gestisce server proprietari né usa i dati per pubblicità o profilazione.

---

### 3. Acquisti in-app e Abbonamenti

Le transazioni economiche relative all'acquisto della licenza o alla sottoscrizione dell'abbonamento sono gestite interamente da **Google Play Billing** (Google LLC). L'applicazione non acquisisce né conserva i dati di pagamento o le carte di credito dell'utente, che rimangono protetti dai sistemi di sicurezza di Google.

---

### 4. Diritti dell'utente e Cancellazione dei Dati

Tutti i contenuti multimediali, appunti e documenti generati risiedono sotto il controllo diretto dell'utente:
* I file conservati sul dispositivo restano fino a quando l'utente li elimina dall'app, usa la funzione di pulizia o disinstalla l'app. La disinstallazione rimuove i dati locali dell'app.
* Le copie già trasferite su Google Drive o sul NAS restano nella destinazione finché l'utente non le elimina da lì; l'eliminazione della copia locale non rimuove le copie remote.
* Per revocare l'accesso dell'app a Google Drive, l'utente può disconnettere l'account dalle impostazioni dell'app o dalle impostazioni di sicurezza del proprio Account Google (sezione "App di terze parti con accesso all'account").

---

### 5. Contatti

Per qualsiasi chiarimento o richiesta riguardante la presente Informativa sulla Privacy, è possibile contattare lo sviluppatore all'indirizzo email di supporto indicato sulla scheda del Google Play Store.
