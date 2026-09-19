# 🏦 Sistema Bancomat Interattivo (ATM Simulation)

Un'applicazione di simulazione bancaria e di sicurezza sviluppata inizialmente tramite logica visuale su **Flowgorithm** ed esportata in **Java**. Il progetto simula le operazioni fondamentali di uno sportello bancomat automatico con controlli rigorosi sull'autenticazione.

---

## ⚙️ Funzionalità Principali

*   **Autenticazione Multifattore (MFA):** Controllo iniziale dell'indirizzo email e della password con un sistema integrato a **3 tentativi massimi**. In caso di fallimento prolungato, l'account viene bloccato per sicurezza.
*   **Verifica di Sicurezza di Secondo Livello:** Controllo incrociato sui dati anagrafici (Nome e Cognome) memorizzati nel database per prevenire furti d'identità.
*   **Menu Interattivo di Gestione Conto:**
    1.  **Deposito:** Versamento di denaro contante con aggiornamento in tempo reale del saldo.
    2.  **Prelievo:** Ritiro di denaro dal conto corrente.
    3.  **Blocco Conto:** Sospensione immediata e cautelare della carta bancaria.
    4.  **Assistenza Clienti:** Invio di una richiesta di supporto per essere ricontattati da un operatore.

---

## 🛠️ Tecnologie Utilizzate

*   **Flowgorithm v4.2:** Progettazione del flusso logico tramite diagrammi di flusso.
