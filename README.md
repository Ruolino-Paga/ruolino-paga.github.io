# Ruolino Paga

Registro dei turni e stima della retribuzione per guardie particolari giurate: ore del mese, indennità, assegno unico, trattenute, lettura dei fogli turni in PDF, registro delle ore con calendario, timbratura di inizio e fine turno da mandare su WhatsApp.

Tutto gira nel browser del telefono: nessun server, nessun dato inviato. Il registro e i profili restano sul dispositivo; dal fondo della scheda Turni si salva una copia di sicurezza.

I valori di partenza sono quelli di un solo istituto. Nella scheda Contratto ognuno li adatta al proprio; il risultato è una stima da confrontare con la busta.

Tarato su otto buste paga 2026 dello stesso istituto, da gennaio ad agosto: scarto medio sul netto 0,8%, massimo 1,6%. Tabelle fiscali 2026 (IRPEF a tre aliquote, detrazioni, bonus, trattamento integrativo, imposta del 5% sugli aumenti contrattuali, assegno unico da circolare INPS n. 7/2026) con le fonti elencate nella scheda Contratto, sotto «Da dove vengono i numeri».

Apri la pagina e scegli «Aggiungi a schermata Home» per usarla come un'app, su Android e su iPhone.

Nella scheda Servizio: tabelle del contratto per data, carriera con livelli a 18 mesi e scatti di anzianità, detrazioni per coniuge e figli a carico. Nella scheda Busta: archivio delle buste paga in PDF (il Ruolino legge i numeri, non nome né codice fiscale, e confronta ogni mese con la stima), confronto voce per voce, trasferta a 8 € l'ora da gennaio 2027. Nella scheda Turni: registro dei turni, valore del turno e netto del mese, turni incollati da un messaggio, rotazione H24, esportazione nel calendario del telefono, cambio turno via link. Nella scheda Pratiche: scadenze di servizio con i promemoria, relazione di servizio, riepilogo dell'anno, notti che contano per la pensione, enti del settore, novità. Nella scheda Contratto: il proprio contratto si condivide con un link. C'è anche la modalità garitta, rosso scuro per la notte.

Nella scheda Turni c'è «Turni dal portale»: chi riceve i turni da un portale aziendale lo collega con codice e password. Il Ruolino scarica i turni, tiene una copia di ogni versione (con data, ora e impronta della pagina originale), li segna nel registro senza toccare i giorni segnati a mano e confronta le ore del portale, del registro e della busta. Il collegamento passa da un ponte che non salva niente; i file `config.js`, `nucleo.js` e `portale.js` hanno la sorgente nel repository Conta Ore e vengono copiati qui da `strumenti/sincronizza-ruolino.py`.

La sorgente `index.html` contiene anche le parti a tono leggero (encomio, medaglia del mese, gradi e mostrine, concorso, frasario): sono spente dall'attributo `data-edizione="istituzionale"` sull'elemento `html` e il calcolo non cambia.
