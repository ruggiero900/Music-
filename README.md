# OPEN MUSIC

Web app React + TypeScript + Material UI con ricerca e riproduzione di audio da Wikimedia Commons.

## Avvio

```bash
npm install
npm run dev
```

## Pubblicazione

1. Carica il progetto su GitHub.
2. Importa il repository su Cloudflare Pages, Netlify o Vercel.
3. Build command: `npm run build`.
4. Output directory: `dist`.
5. Pubblica: il provider assegnerà un URL HTTPS.

## Note

La ricerca Wikimedia Commons è pubblica e non richiede chiavi. I risultati sono filtrati in base alla licenza dichiarata nei metadati, ma la verifica dei diritti e delle attribuzioni rimane necessaria prima di usi ulteriori. I formati audio non sono tutti compatibili con tutti i browser. La riproduzione dipende anche dalla disponibilità del file e dalle policy CORS del servizio. La prima versione non integra Jamendo, FMA e Internet Archive. Preferiti, playlist e cronologia sono salvati localmente tramite localStorage, non IndexedDB. Nessun backend è necessario per questa prima versione.
