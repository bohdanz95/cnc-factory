# CNC Factory: nasconditi dal capo

Gioco stealth 3D nel browser, ambientato in uno stabilimento che lavora pale di turbina.
Fuma 3 sigarette e resta al telefono durante il turno 07:00–15:00 senza farti beccare dai cinque capi.

**Gioca:** https://bohdanz95.github.io/cnc-factory/

## Online con i colleghi (2–4 giocatori)

1. Apri il gioco dal link qui sopra e tocca **GIOCA ONLINE**.
2. Chi crea la stanza riceve un codice di 4 lettere: lo manda su WhatsApp con **Invia invito**.
3. Gli altri inseriscono il codice (o aprono il link dell'invito) e toccano **ENTRA**.
4. L'host sceglie la durata e tocca **INIZIA IL TURNO**.

I capi sono gli stessi per tutti. Si può fare a pugni (pulsante rosso **Pugno**, sul computer G o clic):
tre colpi di fila mandano K.O. per 3 secondi. Ogni pugno fa rumore, e se un capo vede la rissa scatta il richiamo.

Note: la connessione è diretta tra i telefoni (WebRTC tramite PeerJS). Chi crea la stanza deve tenere il gioco aperto in primo piano.
Su alcune reti mobili la connessione può non partire: col Wi-Fi funziona meglio.

## Comandi

- Telefono: pollice sinistro per muoverti, trascina a destra per guardare, pulsanti a destra (meglio in orizzontale)
- Computer: WASD, Shift corri, C abbassati, Q/E sporgiti, F telefono, R fuma, G o clic pugno, Spazio nasconditi, V visuale

## File

- `index.html`: il gioco
- `vendor/`: three.js e PeerJS, serviti dal sito invece che da CDN
- `photos/`: volti dei personaggi, pavimento, pareti, tessuto, capelli e poster del reparto

Le foto vanno servite dallo stesso sito: aprendo `index.html` con doppio clic dal disco non si caricano.
Solo i caratteri arrivano da Google Fonts.
