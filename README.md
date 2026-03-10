# 📧 Outlook AI Quest

Benvenuto in **Outlook AI Quest**, un gioco interattivo a quiz progettato per testare e migliorare le tue conoscenze sull'Intelligenza Artificiale applicata a Microsoft Outlook e all'ecosistema Microsoft 365.

## 🎮 Panoramica del Gioco

Questo progetto è una web app interattiva in stile retro-arcade (con grafica a 8-bit, font *Press Start 2P*, scanlines e musiche/effetti a tema) che ti guida attraverso i concetti chiave dell'IA per Outlook. Smetti di lavorare in modo tradizionale e inizia a pilotare l'intelligenza artificiale per ottimizzare il tuo flusso di lavoro!

Il gioco è strutturato in diversi livelli tematici, ognuno con una serie di domande a risposta multipla. Più risposte corrette fornisci consecutivamente, maggiore sarà il tuo punteggio grazie al sistema di Combo. Attento però: hai solo 3 vite a disposizione e un timer che scorre in base alla difficoltà scelta!

## 📚 Argomenti Trattati (Livelli)

Il percorso di apprendimento è diviso in 7 stage:

1.  **Copilot Base**: Fondamenti su cos'è Copilot in Outlook e le sue funzioni principali (es. suggerimenti di risposte, bozze, riassunti, FindTime).
2.  **Prompt & Ruoli**: Tecniche e framework per scrivere prompt efficaci (RTF, RISEN, RODES, Chain of Thought).
3.  **Agenti & Limiti**: Comprendere come funzionano gli LLM (Large Language Models), i limiti della "Context Window", i token e il fenomeno dell'allucinazione (Sycophancy).
4.  **Sicurezza (Purview & DLP)**: Integrazione dell'IA con la sicurezza aziendale, etichette di riservatezza (Sensitivity Labels) e log di eDiscovery.
5.  **Power Automate**: Combinare l'RPA (Robotic Process Automation) con l'IA per automatizzare flussi di lavoro, smistamento email e task in modo deterministico.
6.  **Copilot Studio**: La differenza tra agenti semplici (M365) e agenti avanzati/pro-code che possono eseguire transazioni tramite API verso sistemi esterni (es. SAP, Salesforce).
7.  **💀 Boss Finale**: Una verifica completa e impegnativa su tutti i moduli affrontati.

## 🚀 Come Giocare

1.  Scarica o clona la repository.
2.  Apri il file `Outlook_AI_Quest.html` con un qualsiasi browser web moderno.
3.  Seleziona la difficoltà (inciderà sul tempo a disposizione per rispondere):
    *   **Facile**: 60 secondi
    *   **Media**: 30 secondi
    *   **Difficile**: 15 secondi
4.  Scegli il livello di partenza.
5.  Rispondi alle domande selezionando le opzioni A, B, C o D prima dello scadere del timer.
6.  A fine partita, visualizza il riepilogo per capire dove hai sbagliato e, se vuoi, scarica un certificato in formato PDF con i tuoi risultati!

## 🛠️ Tecnologie Utilizzate

*   **HTML5 & CSS3**: Per la struttura, i layout flex/grid e l'interfaccia utente. Ricco utilizzo di variabili CSS, animazioni `@keyframes` ed effetti visivi retrò (scanlines, CRT vignette, testo luminoso).
*   **Vanilla JavaScript (ES6)**: Per gestire la logica di gioco, lo stato, i timer, le manipolazioni DOM, il tracciamento dei punteggi/highscores (in `localStorage`) e l'audio procedurale.

## 💡 Obiettivo Didattico

L'obiettivo di "Outlook AI Quest" non è solo intrattenere, ma soprattutto formare in modo dinamico e coinvolgente. Attraverso il meccanismo di feedback immediato (spiegazione post-risposta), il giocatore apprende best practice e logiche di funzionamento direttamente sul campo, superando il classico apprendimento passivo tramite slide.

---
*Progetto creato per il corso "IA per Outlook: Smetti di lavorare, inizia a pilotare!"*
