# Guida alla contribuzione

Grazie per contribuire! Queste regole ci aiutano a lavorare come un vero team di sviluppo.

## 🔄 Flusso di lavoro

1. Scegli (o crea) una **Issue** e assegnatela a te
2. Aggiorna il branch `develop`
3. Crea un branch dedicato
4. Lavora con commit piccoli e chiari
5. Apri una **Pull Request** verso `develop`
6. Aspetta la review, correggi se richiesto
7. Dopo l'approvazione, il merge lo fa chi ha aperto la PR

## 🌿 Branch

| Branch | Uso |
|--------|-----|
| `main` | Versione stabile. **Protetto**: niente push diretti |
| `develop` | Integrazione del lavoro in corso |
| `feature/<nome>` | Nuova funzionalità, es. `feature/player-audio` |
| `fix/<nome>` | Correzione bug, es. `fix/login-errore` |
| `docs/<nome>` | Solo documentazione |

Non lavorare mai direttamente su `main` o `develop`.

## ✍️ Messaggi di commit

Usiamo **Conventional Commits**:

```
<tipo>: <descrizione breve al presente>
```

Tipi: `feat`, `fix`, `docs`, `style`, `refactor`, `test`, `chore`.

Esempi:

```
feat: aggiunge il pulsante play al player
fix: corregge la query di ricerca delle playlist
docs: aggiorna le istruzioni di setup
```

## 🔀 Pull Request

- Titolo chiaro, nello stesso stile dei commit
- Collega la Issue (`Closes #12`)
- Descrivi cosa hai cambiato e come testarlo
- Almeno **1 approvazione** di un altro membro prima del merge
- Una PR deve fare **una cosa sola**: se è troppo grande, dividila
- Non fare mai merge di una PR che non hai testato

## 👀 Code review

- Sii gentile e costruttivo: critica il codice, non la persona
- Rispondi alle review entro 24 ore se possibile
- Usa i commenti per spiegare il perché, non solo il cosa

## 🧑‍💻 Standard di codice

**Java**
- Classi in `PascalCase`, metodi e variabili in `camelCase`
- Un metodo, una responsabilità
- Commenta solo ciò che non è ovvio dal codice

**HTML / CSS**
- HTML semantico (`header`, `nav`, `main`, `section`)
- Classi CSS in `kebab-case`
- Niente stili inline

**MySQL**
- Tabelle e colonne in `snake_case`
- Ogni modifica allo schema va in `database/` con un file di migrazione

## 🐛 Segnalare bug e proporre idee

Apri una **Issue** con:

- Descrizione del problema o dell'idea
- Passi per riprodurlo (per i bug)
- Comportamento atteso e comportamento reale
- Label corretta: `bug`, `feature`, `frontend`, `backend`, `database`

## 🔐 Sicurezza

- **Mai** committare password, chiavi API o file `.env`
- Usa un file di configurazione locale incluso nel `.gitignore`

## ✅ Checklist prima della PR

- [ ] Il codice compila e funziona in locale
- [ ] Ho testato la funzionalità
- [ ] Ho aggiornato la documentazione se serve
- [ ] Il branch è aggiornato con `develop`
- [ ] Ho collegato la Issue
