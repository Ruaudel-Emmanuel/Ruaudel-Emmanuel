# 👋 Emmanuel Ruaudel — Consultant & développeur d'outils métier

> 🇫🇷 **Version française** plus bas — 🇬🇧 [English version](#-english-version)

> **J'aide les dirigeants de PME à libérer 5 à 10 h/semaine** en automatisant leurs tâches répétitives —
> et je construis moi-même les outils qui le font : sites web, apps Android, infrastructure VPS, workflows IA.

📍 Rennes · 🌐 [Mon portfolio](https://rennesdev.fr/portofolio.html)

---

## 🎯 Missions & objectifs

- **Automatiser le quotidien des PME/TPE** : formulaires → devis → emails, veille concurrentielle, alertes et rapports — avec un retour mesuré en heures gagnées.
- **Construire des outils simples et réellement utilisés** : applications web et Android, légères, hors-ligne quand il le faut, publiées sur le Play Store.
- **Faire tourner une infrastructure complète en autonomie** : VPS Linux, Docker, supervision, sauvegardes chiffrées, CI/CD — tout est documenté, versionné et automatisé.
- **IA pragmatique** : modèles locaux (Ollama) pour les données personnelles, API quand c'est pertinent — le bon outil au bon endroit.

---

## 📊 Métriques

### Impact client (consulting)

| Métrique | Valeur |
|---|---|
| Temps récupéré par dirigeant | **5 à 10 h/semaine** |
| Gain par brique automatisée (catalogue de 15 briques : devis, relances, reporting, collecte multi-canaux…) | **1 à 5 h/semaine par brique** |
| Cycle de devis automatisé (typique) | **48 h → 15 min** |
| Erreurs de saisie / oublis de facturation | **fortement réduites** (règles métier + relances automatiques) |

*Chaque mission commence par la mesure du temps perdu aujourd'hui, et se conclut sur le temps récupéré — pas de technologie « pour la technologie ».*

### L'infrastructure en chiffres (réel, public)

| Métrique | Valeur |
|---|---|
| Conteneurs Docker supervisés | **10** |
| CI obligatoire sur chaque pull request | **100 %** (build Android vérifié avant merge) |
| Dépendances mises à jour + mergées | **automatiquement chaque semaine, 0 clic** |
| Journal quotidien de l'infrastructure | **commité automatiquement chaque soir** |
| Incidents | **issue ouverte automatiquement, clôturée à la résolution** |
| Sauvegardes | **chiffrées, hors du serveur, hebdomadaires** |

---

## 🛠️ Stacks

| Domaine | Technologies |
|---|---|
| Langages | ![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black) ![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white) ![HTML/CSS](https://img.shields.io/badge/HTML%2FCSS-E34F26?logo=html5&logoColor=white) |
| Web & API | ![Node.js](https://img.shields.io/badge/Node.js-339933?logo=nodedotjs&logoColor=white) ![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?logo=postgresql&logoColor=white) ![Docker](https://img.shields.io/badge/Docker-2496ED?logo=docker&logoColor=white) |
| Mobile | ![Android](https://img.shields.io/badge/Android-3DDC84?logo=android&logoColor=black) ![Capacitor](https://img.shields.io/badge/Capacitor-119EFF?logo=capacitor&logoColor=white) ![Play Store](https://img.shields.io/badge/Play_Store-414141?logo=googleplay&logoColor=white) |
| Automatisation & IA | ![n8n](https://img.shields.io/badge/n8n-EA4B71?logo=n8n&logoColor=white) ![Ollama](https://img.shields.io/badge/Ollama-000000?logo=ollama&logoColor=white) ![Telegram Bots](https://img.shields.io/badge/Telegram-26A5E4?logo=telegram&logoColor=white) |
| Infra & DevOps | ![Ubuntu](https://img.shields.io/badge/Ubuntu-E95420?logo=ubuntu&logoColor=white) ![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?logo=githubactions&logoColor=white) ![Caddy](https://img.shields.io/badge/Caddy-DD5A6A) ![Cloudflare](https://img.shields.io/badge/Cloudflare-F38020?logo=cloudflare&logoColor=white) |

---

## 🏆 Projets phares

### 1. Nav.rennesdev — navigateur web « mode lecture » avec IA locale
Un navigateur simplifié qui **extrait le contenu des pages et l'analyse avec un modèle IA local** (résumé, questions/réponses) — les données ne quittent jamais le serveur.
- Node.js sans dépendance, authentification, HTTPS, Docker
- IA : Ollama sur le VPS, déchargement automatique de la RAM
- **`Nav.rennesdev`** → [repo](https://github.com/Ruaudel-Emmanuel/Nav.rennesdev)

### 2. Lecteur-PDF — app Android 100 % hors ligne
Lecteur PDF avec **PDF.js embarqué** (aucun CDN), zoom, mode sombre mémorisé, **zéro permission Android** (ni réseau ni stockage).
- Capacitor 8 · CI GitHub Actions · release signée
- Publié sur le **Play Store** (test fermé)
- **`Lecteur-PDF`** → [repo](https://github.com/Ruaudel-Emmanuel/Lecteur-PDF)

### 3. Suivi Interventions — suivi de chantier Android
Application de suivi pour le terrain : interventions, photos directes, export.
- Capacitor + caméra · build CI à chaque PR · dépendances mises à jour **et mergées automatiquement** chaque semaine
- Publié sur le **Play Store**
- **`construction-site-tracker`** → [repo](https://github.com/Ruaudel-Emmanuel/construction-site-tracker)

### 4. rennesdev-vps-ops — l'infrastructure qui fait tout tourner
Le cœur technique de mon activité, **documenté et versionné comme un projet à part entière** :
- 10 conteneurs Docker (n8n, PostgreSQL, Ollama, monitoring…), reverse proxy, sauvegardes chiffrées
- Bots Telegram de contrôle, watchdog qui **ouvre/clôt ses propres issues GitHub**
- CI sur les builds Android, dépendances auto-mergées, journal quotidien commité automatiquement
- **`rennesdev-vps-ops`** → [repo](https://github.com/Ruaudel-Emmanuel/rennesdev-vps-ops)

### 5. surveillance-tarifaire — veille concurrentielle automatisée
Suivi automatique des tarifs concurrents : collecte planifiée, comparaison, alertes.
- Python · planification · rapports automatiques
- **`surveillance-tarifaire`** → [repo](https://github.com/Ruaudel-Emmanuel/surveillance-tarifaire)

---

## ⚙️ Ce GitHub s'administre en grande partie tout seul

Preuve par l'exemple de ce que je vends aux PME :

- 🧪 **CI sur chaque PR** : build Android vérifié avant tout merge (check requis pour merger)
- 🔄 **Dépendances** : PR chaque semaine, mergées automatiquement si la CI est verte
- 📔 **Journal quotidien** : l'état de l'infrastructure est commité automatiquement chaque soir
- 🚨 **Incidents** : le watchdog du serveur **ouvre et clôt ses propres issues** GitHub
- 📊 Templates d'issues/PR et protections de branches sur tous les dépôts actifs

---

## 📬 Contact

- 🌐 [Portfolio](https://rennesdev.fr/portofolio.html)
- 💬 via GitHub (ouvert aux discussions, missions et opportunités)

---

## 📊 Activité

<p><img src="https://github-readme-stats.vercel.app/api?username=Ruaudel-Emmanuel&show_icons=true&theme=default" height="150" /></p>
<p><img src="https://streak-stats.demolab.com?user=Ruaudel-Emmanuel" height="150" /></p>

---
---

<a id="-english-version"></a>
## 🇬🇧 English version

# 👋 Emmanuel Ruaudel — Consultant & business-tools developer

> **I help small-business owners free up 5 to 10 hours a week** by automating their repetitive tasks —
> and I build the tools that do it myself: websites, Android apps, VPS infrastructure, AI workflows.

📍 Rennes, France · 🌐 [My portfolio](https://rennesdev.fr/portofolio.html) · 🇫🇷 [Version française](#-emmanuel-ruaudel--consultant--développeur-doutils-métier)

---

## 🎯 Mission & goals

- **Automate the daily grind of small businesses**: forms → quotes → emails, competitive watch, alerts and reports — with results measured in hours saved.
- **Build simple tools that actually get used**: web and Android apps, lightweight, offline-capable when needed, published on the Play Store.
- **Run a full infrastructure on my own**: Linux VPS, Docker, monitoring, encrypted backups, CI/CD — everything documented, version-controlled and automated.
- **Pragmatic AI**: local models (Ollama) for personal data, APIs when appropriate — the right tool in the right place.

---

## 📊 Metrics

### Client impact (consulting)

| Metric | Value |
|---|---|
| Time freed per business owner | **5 to 10 hours/week** |
| Gain per automated building block (catalogue of 15 blocks: quotes, follow-ups, reporting, multi-channel intake…) | **1 to 5 hours/week per block** |
| Automated quote turnaround (typical) | **48 h → 15 min** |
| Data-entry errors / missed invoicing | **sharply reduced** (business rules + automatic follow-ups) |

*Every engagement starts by measuring the time lost today and ends with the time recovered — no technology "for technology's sake".*

### The infrastructure in numbers (real, public)

| Metric | Value |
|---|---|
| Supervised Docker containers | **10** |
| CI enforced on every pull request | **100%** (Android build verified before merge) |
| Dependencies updated & merged | **automatically every week, zero clicks** |
| Daily infrastructure journal | **committed automatically every evening** |
| Incidents | **issue opened automatically, closed on resolution** |
| Backups | **encrypted, off-server, weekly** |

---

## 🛠️ Tech stack

JavaScript · Python · Node.js · PostgreSQL · Docker · Android (Capacitor) · Play Store · n8n · Ollama · Telegram bots · GitHub Actions · Caddy · Cloudflare · Linux/Ubuntu

---

## 🏆 Featured projects

### 1. Nav.rennesdev — "reading mode" web browser with local AI
A simplified browser that **extracts page content and analyses it with a local AI model** (summarise, Q&A) — data never leaves the server.
- Dependency-free Node.js, authentication, HTTPS, Docker
- AI: Ollama on the VPS, automatic RAM unloading
- [repo](https://github.com/Ruaudel-Emmanuel/Nav.rennesdev)

### 2. Lecteur-PDF — fully offline Android app
PDF reader with **embedded PDF.js** (no CDN), zoom, remembered dark mode, **zero Android permissions** (no network, no storage).
- Capacitor 8 · GitHub Actions CI · signed release
- Published on the **Play Store** (closed testing)
- [repo](https://github.com/Ruaudel-Emmanuel/Lecteur-PDF)

### 3. Suivi Interventions — construction-site tracking app
Field tracking app: interventions, direct photos, exports.
- Capacitor + camera · CI build on every PR · dependencies updated **and merged automatically** every week
- Published on the **Play Store**
- [repo](https://github.com/Ruaudel-Emmanuel/construction-site-tracker)

### 4. rennesdev-vps-ops — the infrastructure that runs everything
The technical core of my business, **documented and versioned as a real project**:
- 10 Docker containers (n8n, PostgreSQL, Ollama, monitoring…), reverse proxy, encrypted backups
- Telegram control bots, a watchdog that **opens and closes its own GitHub issues**
- CI on Android builds, auto-merged dependencies, daily auto-committed journal
- [repo](https://github.com/Ruaudel-Emmanuel/rennesdev-vps-ops)

### 5. surveillance-tarifaire — automated competitor price watch
Automatic tracking of competitors' prices: scheduled collection, comparison, alerts.
- Python · scheduling · automated reports
- [repo](https://github.com/Ruaudel-Emmanuel/surveillance-tarifaire)

---

## ⚙️ This GitHub largely runs itself

Proof by example of what I sell to small businesses:

- 🧪 **CI on every PR**: Android build verified before any merge (required check)
- 🔄 **Dependencies**: PR every week, merged automatically when CI is green
- 📔 **Daily journal**: infrastructure state committed automatically every evening
- 🚨 **Incidents**: the server watchdog **opens and closes its own GitHub issues**
- 📊 Issue/PR templates and branch protection on all active repos

---

## 📬 Contact

- 🌐 [Portfolio](https://rennesdev.fr/portofolio.html)
- 💬 via GitHub (open to conversations, missions and opportunities)
