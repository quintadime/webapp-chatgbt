# Budget Reset

Sistema statico Budget Reset con landing page, web app gratuita e contenuti Reel.

## Struttura
- `/index.html` — landing page
- `/app/index.html` — Budget Reset Solo web app
- `/content/reel-content.csv` — 30 contenuti Reel importabili in Google Sheets
- `/docs/funnel.md` — architettura del sistema di acquisizione

## GitHub Pages
Repository → Settings → Pages → Deploy from a branch → `main` → `/ (root)` → Save.

La home sarà `/index.html` e l'app sarà `/app/`.

## App
L'app è client-side e salva i dati nel browser con `localStorage`. Non serve un database per il funzionamento base.

## Lead capture
La landing attuale è statica. Il collegamento a un provider email/CRM va configurato separatamente; non inserire credenziali o API key nel repository.

## Brand
- Background: `#1A1A1A`
- Testo: `#FFFFFF`
- Accento: `#C8F135`
- Secondario: `#888888`
