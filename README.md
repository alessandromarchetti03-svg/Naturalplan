# NaturalPlan — Benessere olistico

Sito di NaturalPlan di Alessandro Marchetti: rilassamento, meditazioni, Pilates, libri e blog sui rimedi naturali.

## File (tutti nella cartella principale)
- `index.html` — tutto il sito (HTML, CSS e JavaScript in un unico file)
- `corpo.jpg`, `noia.jpg` — copertine dei libri
- `.nojekyll` — serve a GitHub Pages per pubblicare i file così come sono

## Pubblicare con GitHub Pages
1. Crea un nuovo repository (es. `naturalplan`) e carica tutti i file nella cartella principale.
2. Vai in **Settings → Pages**.
3. In **Source** scegli **Deploy from a branch**, branch `main`, cartella `/ (root)`, poi **Save**.
4. Dopo un minuto il sito sarà online su `https://<tuo-utente>.github.io/naturalplan/`.

## Dominio personalizzato
In **Settings → Pages → Custom domain** inserisci il dominio NaturalPlan, poi nel pannello del registrar aggiungi i record DNS indicati da GitHub. Attiva **Enforce HTTPS**.

## Contatti e privacy
Nessun modulo: il pulsante "Contattami" apre il programma di posta verso info@naturalplan.it. Il sito non usa cookie, quindi non serve il banner; l informativa è nella pagina #privacy.

## Modificare gli articoli
Gli articoli sono nell'elenco `const posts=[...]` dentro `index.html`. Ogni articolo ha: `id`, `d` (data AAAA-MM-GG), `t` (titolo), `c` (categoria), `ex` (anteprima), `b` (testo HTML) e `book` (`"corpo"`, `"noia"` oppure `null`).
