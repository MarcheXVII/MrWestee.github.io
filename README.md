# Mr Wes-Tee — The Tee-Shirt Dropout

Sito statico (un solo `index.html`, vanilla, niente build). Versione **principale**:
carrello come pannello lato cliente, **senza database/ordini reali**.

## Mettere online su GitHub Pages

1. Crea una nuova repository su GitHub (es. `mrwestee`), pubblica/public.
2. Carica il **contenuto di questa cartella** nella radice della repo
   (`index.html`, la cartella `FOTO/` e `.nojekyll`). `index.html` deve stare
   nella radice, non dentro una sottocartella.
3. Repo → **Settings → Pages** → *Build and deployment* → Source:
   **Deploy from a branch** → Branch: **main** / **/(root)** → **Save**.
4. Dopo ~1 minuto il sito è online su
   `https://<tuo-utente>.github.io/<nome-repo>/`.

## Note

- `.nojekyll` evita che GitHub Pages ignori i file (serve perché in `FOTO/`
  ci sono nomi che iniziano con `_`).
- Tutte le immagini sono in `FOTO/`; i percorsi nel sito sono già relativi
  (`FOTO/...`), quindi funziona sia in locale (doppio click) sia online.
