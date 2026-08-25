# Informativa sulla privacy di Print3D Manager

**Ultimo aggiornamento: 25 agosto 2026**

_Questa è una traduzione della versione ufficiale in spagnolo, [PRIVACY_POLICY.md](../../PRIVACY_POLICY.md). In caso di discrepanza, prevale la versione spagnola._

Questa informativa spiega quali dati tratta Print3D Manager ("l'app"), con quale finalità, con quale base giuridica, per quanto tempo vengono conservati e quali opzioni hai. È scritta per descrivere esattamente ciò che l'app fa oggi, non funzionalità future.

## 1. Chi tratta i dati

Print3D Manager è un'app sviluppata in modo indipendente per la gestione di un laboratorio di stampa 3D (costi, stampanti, materiali, progetti, clienti, preventivi e fatture).

Contatto: **zhop3dlab@gmail.com**.

## 2. Principio generale: l'app è locale per impostazione predefinita

Tutte le informazioni che inserisci (stampanti, materiali, progetti, clienti, preventivi, fatture, inventario) vengono salvate **sul tuo dispositivo** per impostazione predefinita. Non hai bisogno di creare un account né di avere una connessione a internet per usare l'app con tutte le sue funzioni principali.

Nessun dato della tua attività viene inviato ai nostri server o a terzi, a meno che tu non abbia il piano Business e attivi volontariamente la sincronizzazione con il cloud (vedi sezione 3), o mentre viene mostrato un annuncio (vedi sezione 6).

## 3. Account e sincronizzazione con il cloud (piano Business, facoltativo)

Se hai il piano Business e decidi di creare un account (con email e password, o con il tuo account Google) per salvare i tuoi dati anche nel cloud e usarli su più dispositivi:

- **Dati dell'account**: indirizzo email e, se usi Google, il nome e l'immagine del profilo associati a quell'account Google.
- **Dati della tua attività**: se attivi la sincronizzazione, una copia dei tuoi progetti, clienti, stampanti, materiali, preventivi e fatture viene salvata in un database cloud (Google Firebase/Firestore), associato esclusivamente al tuo account e al tuo spazio di lavoro. Nessuno al di fuori del tuo account può accedere a questi dati.
- Puoi smettere di usare il cloud in qualsiasi momento e tornare a far funzionare l'app solo in locale.
- Puoi **eliminare il tuo account e tutti i dati cloud associati** in qualsiasi momento direttamente dall'app, in **Altro → Account → Elimina account e dati**. Questa azione è permanente e immediata.

Utilizziamo Google Firebase (Authentication e Firestore) come fornitore dell'infrastruttura per l'account e il cloud. Google agisce come responsabile del trattamento di questi dati secondo le proprie condizioni: <https://firebase.google.com/support/privacy>.

**Base giuridica**: trattiamo questi dati perché necessario per fornirti il servizio che hai sottoscritto (esecuzione di un contratto/utilizzo del piano Business) e, per l'email di contatto, con il tuo consenso al momento della creazione dell'account.

**Conservazione**: finché mantieni il tuo account attivo. Se lo elimini (Altro → Account → Elimina account e dati), i dati nel cloud vengono cancellati immediatamente. Se non crei mai un account, non viene generato alcun dato nel cloud.

**Trasferimenti internazionali**: l'infrastruttura di Google Firebase può trattare e archiviare dati in data center al di fuori del tuo paese, incluso al di fuori dello Spazio Economico Europeo. Google offre garanzie conformi al GDPR (clausole contrattuali standard) per questi trasferimenti — maggiori dettagli al link precedente.

## 4. Se usi l'app per gestire i dati dei tuoi clienti

Se salvi nell'app i dati dei tuoi clienti (nome, indirizzo, codice fiscale, email...) per preventivi e fatture, **sei tu il titolare del trattamento di tali dati** nei confronti dei tuoi clienti — proprio come se li gestissi in un foglio di calcolo o in un programma di fatturazione. Print3D Manager è solo lo strumento che usi per salvarli (e, se hai il piano Business con la sincronizzazione attiva, il responsabile del trattamento nel cloud).

Questo significa che sei tu a dover garantire di avere una base giuridica adeguata per trattare i dati dei tuoi clienti (di norma, il rapporto commerciale/contrattuale con loro) e a dover gestire le loro richieste di accesso, rettifica o cancellazione se te le rivolgono direttamente.

## 5. Dati che non lasciano mai il tuo dispositivo

- **File G-code**: se usi l'analizzatore di G-code, il file viene letto e analizzato interamente sul tuo dispositivo. Il contenuto del file non viene mai caricato su internet né condiviso con nessuno; solo tu vedi i dati estratti (tempo stimato, grammi, temperature).
- **Backup locali**: esportare/importare i tuoi dati in un file JSON (piani Pro e Business) è un'operazione completamente locale — il file viene salvato dove decidi tu (ad esempio, condividendolo tu stesso via email o salvandolo nel tuo spazio di archiviazione).
- **PDF di preventivi e fatture**: vengono generati sul tuo dispositivo. Condividerli o scaricarli è un'azione esplicita da parte tua; l'app non li invia a nessun server nostro.

## 6. Pubblicità

L'app mostra annunci tramite **Google AdMob** agli utenti del piano gratuito. AdMob può raccogliere identificatori pubblicitari dal tuo dispositivo per mostrare annunci (personalizzati o meno, a seconda delle impostazioni sulla privacy del tuo sistema operativo) e misurarne le prestazioni. Questo trattamento è effettuato da Google secondo la propria informativa sulla privacy: <https://policies.google.com/privacy> e la sua politica specifica per AdMob: <https://support.google.com/admob/answer/6128543>.

**Base giuridica**: consenso (gestito tramite le impostazioni sulla privacy del tuo dispositivo/di Google) e interesse legittimo a finanziare l'app gratuita tramite pubblicità.

Gli utenti dei piani a pagamento (Pro e Business) non vedono annunci.

## 7. Cosa NON facciamo

- Non vendiamo i tuoi dati a nessuno.
- Non accediamo al contenuto dei tuoi progetti, clienti o fatture, a meno che tu non abbia il piano Business e attivi espressamente la sincronizzazione nel cloud — e anche in tal caso non li esaminiamo manualmente.
- Non usiamo i dati della tua attività per addestrare modelli di intelligenza artificiale.
- Non richiediamo permessi per fotocamera, contatti, posizione o microfono — l'app non ne ha bisogno e non li richiede.

## 8. I tuoi diritti

Hai diritto ad accedere, rettificare, cancellare, limitare il trattamento, opporti e richiedere la portabilità dei tuoi dati. In pratica, dall'app puoi:

- **Vedere** quanti dati hai salvato localmente e nel cloud (Altro → Account).
- **Scaricare** una copia dei tuoi dati in un file JSON (piani Pro e Business, Altro → Dati).
- **Eliminare** il tuo account e tutti i dati cloud associati direttamente dall'app (Altro → Account → Elimina account e dati).
- **Disinstallare l'app** in qualsiasi momento, il che elimina tutti i dati salvati localmente sul tuo dispositivo.

Se hai bisogno di aiuto con uno di questi diritti, o hai dubbi su questa informativa, contatta **zhop3dlab@gmail.com**.

Se ritieni che la tua richiesta non sia stata gestita correttamente, hai diritto a presentare un reclamo all'autorità di controllo per la protezione dei dati del tuo paese (in Spagna, l'**Agencia Española de Protección de Datos**, <https://www.aepd.es>).

## 9. Minori

L'app non è rivolta a minori e non raccogliamo consapevolmente dati di minori.

## 10. Modifiche a questa informativa

Se questa informativa cambia in modo rilevante, la data all'inizio del documento verrà aggiornata. L'uso continuato dell'app dopo una modifica implica l'accettazione dell'informativa aggiornata.
