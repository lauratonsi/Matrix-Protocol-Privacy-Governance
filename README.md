# Matrix.org: Decentralizzazione, E2EE e Data Sovereignty

## 📌 Visione del Progetto
In un ecosistema digitale dominato da "Walled Gardens" centralizzati, questo progetto analizza **Matrix** come alternativa federata per la comunicazione sicura. Il lavoro esplora il trade-off tra la resilienza delle reti distribuite e le sfide di compliance normativa, con un focus specifico sulla tutela della privacy secondo il GDPR.

## 🛠️ Architettura e Sicurezza
Analisi tecnica delle caratteristiche differenzianti del protocollo Matrix:
- **Federazione:** Struttura decentralizzata che elimina il "Single Point of Failure" tipico di piattaforme come Facebook/WhatsApp.
- **Crittografia E2EE:** Implementazione nativa dei protocolli **Olm** e **Megolm** per garantire che solo mittente e destinatario posseggano le chiavi di decifratura.
- **Data Sovereignty:** Possibilità per utenti e organizzazioni di ospitare il proprio *Homeserver*, mantenendo il controllo fisico e legale sui dati.
- **Interoperabilità:** Analisi del funzionamento dei **Bridges** per collegare ecosistemi chiusi (es. WhatsApp) alla rete Matrix.

## ⚖️ Analisi Normativa e GDPR (Case Study)
Il progetto include uno studio comparato sulla protezione dei dati, esaminando il caso **Discord** e la sanzione da 800.000€ imposta dalla **CNIL** (Garante Privacy Francese).
Le violazioni analizzate includono:
- **Art. 5 (Retention):** Mancata definizione di limiti alla conservazione dei dati.
- **Art. 25 (Privacy by Default):** Configurazioni di sicurezza inadeguate e gestione delle sessioni a finestra chiusa.
- **Art. 35 (DPIA):** Assenza di Valutazione d'Impatto per trattamenti su larga scala e minori.

## 📂 Contenuto del Repository
- **Paper di Ricerca:** Analisi dettagliata redatta in **LaTeX**.
- **Presentazione:** Slide riassuntive sviluppate con la classe **Beamer** per la divulgazione tecnica.
