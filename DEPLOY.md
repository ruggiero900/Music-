# Pubblicare OPEN MUSIC da smartphone

## Cloudflare Pages con GitHub
1. Crea un repository GitHub (ad esempio `open-music`).
2. Carica nella radice del repository il contenuto della cartella `open-music` (non lo ZIP intero).
3. Accedi a Cloudflare Dashboard > Workers & Pages > Create > Pages > Connect to Git.
4. Seleziona il repository.
5. Configura framework `Vite`, comando build `npm run build`, directory di output `dist`.
6. Avvia il deployment. Dopo una build riuscita Cloudflare assegna un indirizzo `*.pages.dev`.
7. Apri il sito da smartphone, prova la ricerca e riproduci almeno tre file audio.

## Avvertenze
- La ricerca Wikimedia Commons non garantisce che ogni risultato sia un brano musicale o sia riproducibile da ogni browser.
- Verifica le licenze e le attribuzioni sulle pagine dei file.
- Non esiste un URL pubblico finché il deployment non viene completato.
- Il progetto non è stato compilato con successo nell'ambiente di generazione; eventuali errori della build devono essere corretti prima di considerarlo pronto.
