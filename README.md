# 🎧 Spotify Clone

Progetto **didattico** che replica le funzionalità base di Spotify. Lo sviluppiamo come un vero team di prodotto per fare pratica con **Git/GitHub** e applicare le regole del corso fullstack.

> ⚠️ Progetto a scopo esclusivamente formativo. Non è affiliato a Spotify AB. Usiamo solo brani liberi da diritti.

## 🎯 Obiettivi

- Imparare a lavorare in team con Git, branch, Pull Request e code review
- Applicare un flusso di sviluppo realistico (Issue → branch → PR → merge)
- Costruire un'applicazione fullstack completa

## 🧰 Stack tecnologico

| Livello   | Tecnologia            |
|-----------|-----------------------|
| Frontend  | HTML, CSS (+ JavaScript) |
| Backend   | Java                  |
| Database  | MySQL                 |
| Versioning| Git + GitHub          |

## 📁 Struttura del repository

```
spotify-clone/
├── frontend/     # pagine HTML, CSS e script
├── backend/      # applicazione Java (API)
├── database/     # schema.sql e dati di esempio
├── docs/         # documentazione, mockup, diagrammi
├── README.md
└── CONTRIBUTING.md
```

## ✨ Funzionalità (MVP)

- [ ] Registrazione e login utente
- [ ] Catalogo brani, artisti e album
- [ ] Player audio (play, pausa, avanti, indietro)
- [ ] Creazione e gestione playlist
- [ ] Ricerca di brani, artisti e album

## 🚀 Come avviare il progetto

### Prerequisiti

- JDK 17 o superiore
- MySQL 8
- Git
- Un editor di codice (VS Code, IntelliJ, ecc.)

### Setup

```bash
# 1. Clona il repository
git clone https://github.com/<organizzazione>/spotify-clone.git
cd spotify-clone

# 2. Crea il database
mysql -u root -p < database/schema.sql

# 3. Configura le credenziali del database nel backend
#    (vedi backend/ e non committare mai password!)

# 4. Avvia il backend e apri frontend/index.html
```

## 👥 Team e ruoli

| Membro | Ruolo |
|--------|-------|
| _Nome 1_ | Product Owner |
| _Nome 2_ | Backend |
| _Nome 3_ | Frontend |

I ruoli ruotano a ogni sprint per permettere a tutti di provare ogni area.

## 🤝 Come contribuire

Leggi [CONTRIBUTING.md](CONTRIBUTING.md) prima di aprire la tua prima Pull Request.

## 📄 Licenza

Distribuito con licenza MIT. Vedi il file `LICENSE`.
