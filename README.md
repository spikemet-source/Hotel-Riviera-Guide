# Hotel Riviera Fiumicino – Guest Guide

Mini-sito informativo multilingue pensato per GitHub Pages e smartphone.

## Struttura

- `index.html` – pagina principale
- `style.css` – grafica responsive
- `script.js` – selezione lingua
- `assets/images/` – immagini dell'hotel

## Immagini da sostituire

Caricare nella cartella `assets/images/` questi file:

- `hero.jpg` – foto principale / esterno / vista mare
- `hotel-exterior.jpg` – esterno dell'hotel
- `room.jpg` – camera
- `breakfast.jpg` – colazione
- `beach.jpg` – Fiumicino / mare

Potete usare anche altri nomi, ma in quel caso dovete modificare i percorsi dentro `index.html`.

## Informazioni da aggiornare

Nel file `index.html` cercare e sostituire:

- `HH:MM`
- `€ XX / persona`
- `NOME_WIFI`
- `PASSWORD_WIFI`
- `+390000000000`
- indirizzo e indicazioni
- tassa di soggiorno
- condizioni del parcheggio
- condizioni della navetta

Le traduzioni e i testi multilingue sono nel file `script.js`.

## Pubblicazione con GitHub Pages

1. Create un repository GitHub, ad esempio `hotel-riviera-guest-guide`.
2. Caricate `index.html`, `style.css`, `script.js` e la cartella `assets`.
3. Nel repository aprite **Settings → Pages**.
4. In **Build and deployment** scegliete **Deploy from a branch**.
5. Selezionate il branch `main` e la cartella `/ (root)`.
6. Salvate.
7. Dopo qualche minuto GitHub mostrerà l'indirizzo della pagina.

## QR code

Una volta pubblicata la pagina, create un QR code che punti all'indirizzo GitHub Pages. Potete stamparlo su:

- cartoncino in camera
- reception
- welcome card
- messaggi pre-arrivo
- email

## Consiglio

Non inserire nella pagina dati sensibili, numeri di carte di credito o credenziali. Per eventuali dati che cambiano spesso, mantenere il testo il più semplice possibile così da poterlo aggiornare velocemente.
