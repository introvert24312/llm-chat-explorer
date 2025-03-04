# AI Chat Export Viewer

![GitHub release (latest by date)](https://img.shields.io/github/v/release/levysoft/ai-chat-export-viewer?label=latest) [![Github All Releases](https://img.shields.io/github/downloads/levysoft/ai-chat-export-viewer/total.svg)](https://github.com/levysoft/ai-chat-export-viewer/releases) [![License: GPL v3](https://img.shields.io/badge/License-GPLv3-yellow.svg)](https://opensource.org/licenses/GPLv3) [![Maintenance](https://img.shields.io/badge/Maintained%3F-yes-green.svg)](https://github.com/levysoft/ai-chat-export-viewer/graphs/commit-activity) [![GitHub contributors](https://img.shields.io/github/contributors/levysoft/ai-chat-export-viewer.svg)](https://github.com/levysoft/ai-chat-export-viewer/graphs/contributors) [![made-with-html](https://img.shields.io/badge/Made%20with-HTML-orange.svg)](https://developer.mozilla.org/en-US/docs/Web/HTML) [![made-with-css](https://img.shields.io/badge/Made%20with-CSS-blue.svg)](https://developer.mozilla.org/en-US/docs/Web/CSS) [![made-with-javascript](https://img.shields.io/badge/Made%20with-JavaScript-yellow.svg)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)

[ [English](README.md) | [Italiano](README.it.md) ]

Questa repository fornisce un'applicazione web per visualizzare ed analizzare le esportazioni delle chat da ChatGPT e Claude, con un forte focus sulla privacy. Tutti i dati vengono elaborati localmente nel browser, garantendo che le informazioni personali non vengano inviate a server esterni. Se desideri, puoi scaricare la pagina HTML per ispezionare il codice sorgente e verificare personalmente il funzionamento dell'applicazione.

## Contenuti

1. [Introduzione](#introduzione)
2. [Privacy e sicurezza](#privacy-e-sicurezza)
3. [Requisiti](#requisiti)
4. [Installazione](#installazione)
5. [Utilizzo](#utilizzo)
6. [Descrizione dell'applicazione](#descrizione-dellapplicazione)
7. [Struttura dei file](#struttura-dei-file)
8. [Screenshot](#screenshot)
9. [Feedback e contributi](#feedback-e-contributi)
10. [Changelog](#changelog)
11. [Autore](#autore)
12. [Licenza](#licenza)

## Introduzione

**Privacy Chat Export Viewer** è un'applicazione web che consente di caricare ed analizzare file JSON contenenti le conversazioni esportate da ChatGPT e Claude. L'interfaccia intuitiva permette di cercare e visualizzare facilmente le chat, offrendo una soluzione leggera e veloce senza compromettere la privacy dei dati.

## Privacy e sicurezza

L'applicazione è stata progettata con la massima attenzione alla privacy:
- **Elaborazione locale**: Tutti i dati vengono elaborati direttamente nel browser, senza invio a server esterni.
- **Nessun tracciamento**: I dati personali e la cronologia delle chat rimangono completamente sul dispositivo dell'utente.
- **Analisi del codice**: Se desideri approfondire o verificare il funzionamento, puoi scaricare la pagina HTML e analizzare il codice sorgente.

## Requisiti

- Browser web moderno (Chrome, Firefox, Edge, Safari)
- Connessione Internet per il caricamento iniziale degli asset (opzionale, per l'utilizzo offline è necessario scaricare tutti i file)

## Installazione

1. Clona la repository:
    ```sh
    git clone https://github.com/levysoft/ai-chat-export-viewer.git
    ```
2. Apri il file `index.html` nel tuo browser preferito.
3. *(Opzionale)* Per un utilizzo completamente offline, scarica tutti gli asset presenti nella repository.

## Utilizzo

1. Avvia l'applicazione aprendo il file `index.html` nel browser.
2. Trascina il file JSON (ad esempio, `conversations.json`) nell'area di upload oppure clicca per selezionarlo.
3. Visualizza l'elenco delle chat e seleziona quella che vuoi analizzare.
4. Usa la barra di ricerca per filtrare le conversazioni per titolo o contenuto.
5. Personalizza l'interfaccia modificando lingua, modalità dark e posizione dello scroll attraverso le impostazioni.
6. Se desideri analizzare il codice, puoi scaricare la pagina HTML e ispezionare il sorgente.

## Descrizione dell'applicazione

L'applicazione è sviluppata con HTML, CSS e JavaScript e offre le seguenti funzionalità:
- **Caricamento locale del file JSON**: I dati vengono letti e processati tramite l'oggetto `FileReader` senza essere inviati online.
- **Gestione delle conversazioni**: Supporta i formati di esportazione di ChatGPT e Claude, normalizzando l'ordine delle chat.
- **Interfaccia dinamica e responsive**: Una sidebar per navigare tra le chat e un'area di visualizzazione per i messaggi, con supporto alla ricerca e alla personalizzazione.
- **Modalità multilingua e dark/light**: L'interfaccia si adatta a diverse lingue e preferenze visive.
- **Condivisione locale**: È possibile copiare il link della chat per condividerlo, senza che i dati vengano memorizzati esternamente.

## Struttura dei file

ai-chat-export-viewer/ ├── index.html # Pagina principale dell'applicazione ├── assets/ # Cartella contenente immagini e screenshot │ ├── screenshot0.jpg │ ├── screenshot1.jpg │ └── screenshot2.jpg ├── README.md # Questo file └── LICENSE # File di licenza (GPL v3)

## Screenshot

Ecco alcuni screenshot dell'applicazione:

- **Pagina di upload**:
  ![Pagina di upload](assets/screenshot0.jpg)
- **Elenco delle chat**:
  ![Elenco chat](assets/screenshot1.jpg)
- **Dettaglio della conversazione**:
  ![Dettaglio chat](assets/screenshot2.jpg)

## Feedback e contributi

Il tuo feedback è prezioso! Se riscontri problemi o hai suggerimenti, apri un [issue](https://github.com/levysoft/ai-chat-export-viewer/issues) o invia una pull request. Contributi e proposte di miglioramento sono sempre benvenuti.

## Changelog

Tutte le modifiche e gli aggiornamenti dell'applicazione sono documentati nel file [CHANGELOG.md](./CHANGELOG.md).

## Autore

Antonio Troise

## Licenza

Questo progetto è rilasciato sotto la licenza [GNU GPL v3](https://www.gnu.org/licenses/gpl-3.0.en.html). Vedi il file LICENSE per maggiori dettagli.

