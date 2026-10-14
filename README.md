# FinSvAI – Finlandssvensk AI

Webbplats för **FinSvAI**, ett samlande initiativ kring AI och svenskan i Finland.

## Lokal förhandsvisning

Sidan är helt statisk. Öppna bara `index.html` i webbläsaren, eller kör:

```bash
python3 -m http.server 8000
# http://localhost:8000
```

## Publicering med GitHub Pages

1. Skapa ett repo på GitHub, t.ex. `finlandssvensk-ai.github.io` (siten blir då tillgänglig
   på `https://finlandssvensk-ai.github.io`) – eller vilket som helst repo namnet
   `<org>.github.io/<repo>`.
2. Pusha filerna:
   ```bash
   git remote add origin git@github.com:<org>/<repo>.git
   git push -u origin main
   ```
3. I GitHub: **Settings → Pages → Source: Deploy from a branch → `main` / root → Save**.

## Redigera

Allt innehåll ligger i `index.html` (text) och `styles.css` (design). Skicka en pull
request med dina ändringar.
