# Generatore di Storie per Bambini

Questo progetto è un sito web in **HTML + Tailwind CSS** che permette di generare storie per bambini personalizzate, utilizzando un modello AI (es. OpenAI GPT).

---

## Come funziona
1. Compila i campi: nome, età, interessi, città, personaggi preferiti.
2. Clicca su **Impostazioni** e inserisci la tua API Key del provider AI.
3. Premi **Genera storia** e il sito produrrà automaticamente un racconto su misura.
4. Puoi anche usare la modalità **Demo** (senza API) per vedere un esempio.

---

## Pubblicazione su GitHub Pages

1. Crea un repository su GitHub (es. `storie_bambini`).
2. Carica i file del progetto (in particolare `index.html`).
3. Vai nelle **Settings → Pages** e scegli `main` branch, cartella `/ (root)`.
4. Dopo qualche minuto il sito sarà visibile a:
   ```
   https://TUONOMEUTENTE.github.io/storie_bambini/
   ```

---

## Caricamento con Git (terminal)
```bash
git init
git add index.html
git commit -m "Prima versione del sito di storie"
git branch -M main
git remote add origin https://github.com/TUONOMEUTENTE/storie_bambini.git
git push -u origin main
```

---

## Privacy
La chiave API viene salvata solo localmente nel browser dell’utente (LocalStorage) e non viene condivisa.

---

👶 ✨ Realizzato per rendere la lettura e la fantasia più divertenti!
