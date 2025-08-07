# IDR Calc

**IDR Calc** è una Progressive Web App (PWA) per il calcolo in tempo reale dell’**Iodine Delivery Rate** e della quantità di mezzo di contrasto, progettata per uso interno in reparto radiologico.  
Funziona anche **offline**, è **portabile** e non richiede alcuna installazione server.

## Funzionalità principali
- Calcolo **in tempo reale** (nessun pulsante "Calcola").
- Preset rapidi: *Standard*, *Basso flusso*, *High-IDR*.
- Modalità **libera** con avviso visivo.
- Validazione e messaggi di errore in tempo reale.
- **Dark/Light mode** con icona dinamica.
- Supporto multilingua (IT / EN).
- Storico locale con esportazione in **CSV** o **PDF**.
- Possibilità di copia rapida dei risultati negli appunti.
- Campo “Riferimento paziente” con controllo di univocità.
- Funziona **offline** grazie al Service Worker.

## Tecnologie usate
- **HTML / CSS / JavaScript**
- **Tailwind CSS** (via CDN)
- **Service Worker** per supporto offline
- **Local Storage** per lo storico

## Installazione locale
Clona il repository e apri `index.html` nel browser:

```bash
git clone https://github.com/Kallen4vn/idr-calc.git
cd idr-calc
