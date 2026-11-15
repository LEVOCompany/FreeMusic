# FreeMusic - 🎧 Spotify Clone Features

This is an educational project that replicates Spotify's core functionality. We're developing it as a real product team to practice using Git/GitHub and apply the full-stack course rules.

> ⚠️ This project is for educational purposes only. It is not affiliated with Spotify AB. We only use royalty-free music.

## 🎯 Objectives

- Learn to work as a team with Git, branches, pull requests, and code reviews
- Apply a realistic development flow (Issue → branch → PR → merge)
- Build a complete full-stack application

## 🧰 Technology Stack

| Layer | Technology |
|-----------|-----------------------|
| Frontend | HTML, CSS (+ JavaScript) |
| Backend | Java |
| Database | MySQL |
| Versioning| Git + GitHub |

## 📁 Repository Structure

```
spotify-clone/
├── frontend/ # HTML pages, CSS, and scripts
├── backend/ # Java application (API)
├── database/ # schema.sql and sample data
├── docs/ # documentation, mockups, diagrams
├── README.md
└── CONTRIBUTING.md
```

## ✨ Features (MVP)

- [ ] User Registration and Login
- [ ] Song, Artist, and Album Catalog
- [ ] Audio Player (Play, Pause, Forward, Backward)
- [ ] Playlist Creation and Management
- [ ] Search for Songs, Artists, and Albums

## 🚀 How to Start the Project

### Prerequisites

- JDK 17 or higher
- MySQL 8
- Git
- A code editor (VS Code, IntelliJ, etc.)

### Setup

```bash
# 1. Clone the repository
git clone https://github.com/<organization>/spotify-clone.git
cd spotify-clone

# 2. Create the database
mysql -u root -p < database/schema.sql

# 3. Configure the database credentials in the backend
# (see backend/ and never commit passwords!)

# 4. Start the backend and open frontend/index.html
```

## 👥 Teams and Roles

| Member | Role |
|--------|-------|
| Ernesto Vinasco | Product Owner |
| _Name 2_ | Backend |
| _Name 3_ | Frontend |

Roles rotate each sprint to allow everyone to test each area.

## 🤝 How to Contribute

Please read [CONTRIBUTING.md](CONTRIBUTING.md) before submitting your first Pull Request.

## 📄 License

Distributed under the MIT License. See the `LICENSE' file`.
