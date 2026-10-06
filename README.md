# TradeMind — PWA definitiva

Versione installabile come app su Android/iPhone/desktop tramite browser compatibile.

## Installazione Android
1. Pubblica questa cartella su un hosting HTTPS (GitHub Pages, Netlify, Cloudflare Pages, ecc.).
2. Apri il sito con Chrome su Android.
3. Se compare il banner, scegli **Installa app**. In alternativa: **⋮ → Installa app** / **Aggiungi alla schermata Home**.
4. Dopo l'installazione TradeMind si apre in modalità app e continua a funzionare offline dopo il primo caricamento.

## Note
- I progressi dell'app sono salvati localmente nel browser del dispositivo.
- Non è necessario un account.
- Il Service Worker gestisce cache e funzionamento offline.
- Per aggiornare l'app, incrementare il nome della cache in `sw.js` (es. `trademind-v2`) quando si pubblica una modifica importante.
- Per una pubblicazione sul Play Store serve una fase aggiuntiva di packaging/signing (AAB/TWA) e le relative informazioni di privacy.
