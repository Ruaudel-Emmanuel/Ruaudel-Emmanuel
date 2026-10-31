# 👋 Emmanuel Ruaudel — Directeur de la Transformation Numérique

> 🇬🇧 English version

> **J'aide les dirigeants de TPE/PME à libérer 5 à 10 h/semaine** en automatisant leurs tâches répétitives —
> et je pilote la transformation de bout en bout : audit des processus, cas d'usage IA à fort ROI,
> déploiement, fiabilisation et accompagnement du changement.

📍 Rennes · 🌐 [Mon portfolio](https://rennesdev.fr/portofolio.html)

---

## 🎯 Missions & objectifs

- **Automatiser le quotidien des TPE/PME** : formulaires → devis → emails, veille concurrentielle, alertes et rapports — avec un retour mesuré en heures gagnées.
- **Construire des outils simples et réellement utilisés** : applications web et Android, légères, hors ligne quand il le faut, publiées sur le Play Store.
- **Faire tourner une infrastructure complète en autonomie** : VPS Linux, Docker, supervision, sauvegardes chiffrées, CI/CD — tout est documenté, versionné et automatisé.
- **IA pragmatique** : LLM via API (Mistral) par défaut — l'auto-hébergement a été testé puis écarté au profit de la sobriété ressources — le bon outil au bon endroit.

---

## 📊 Métriques

### Impact client (conseil)
   Métrique | Valeur |
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
 | Automatisation & IA | ![n8n](https://img.shields.io/badge/n8n-EA4B71?logo=n8n&logoColor=white) ![Mistral](https://img.shields.io/badge/Mistral-FF7000?logo=mistralai&logoColor=white) ![Telegram Bots](https://img.shields.io/badge/Telegram-26A5E4?logo=telegram&logoColor=white) |
 | Infra & DevOps | ![Ubuntu](https://img.shields.io/badge/Ubuntu-E95420?logo=ubuntu&logoColor=white) ![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?logo=githubactions&logoColor=white) ![Caddy](https://img.shields.io/badge/Caddy-DD5A6A) ![Cloudflare](https://img.shields.io/badge/Cloudflare-F38020?logo=cloudflare&logoColor=white) |

---

## 🏆 Projets phares

### 1. Nav.rennesdev — navigateur web « mode lecture » avec IA locale
Un navigateur simplifié qui **extrait le contenu des pages et l'analyse avec un modèle IA local** (résumé, questions/réponses) — les données ne quittent jamais le serveur.
- Node.js sans dépendance, authentification, HTTPS, Docker
- IA : analyse via API Mistral — Ollama local testé puis abandonné (trop gourmand en RAM pour le VPS)
- [repo](https://github.com/Ruaudel-Emmanuel/Nav.rennesdev)

### 2. Lecteur-PDF — app Android 100 % hors ligne
Lecteur PDF avec **PDF.js embarqué** (aucun CDN), zoom, mode sombre mémorisé, **zéro permission Android** (ni réseau ni stockage).
- Capacitor 8 · CI GitHub Actions · release signée
- Publié sur le **Play Store** (test fermé)
- [repo](https://github.com/Ruaudel-Emmanuel/Lecteur-PDF)

### 3. rennesdev-vps-ops — l'infrastructure qui fait tout tourner
Le cœur technique de mon activité, **documenté et versionné comme un projet à part entière** :
- 10 conteneurs Docker (n8n, PostgreSQL, monitoring…), reverse proxy, sauvegardes chiffrées
- Bots Telegram de contrôle, watchdog qui **ouvre/clôt ses propres issues GitHub**
- CI sur les builds Android, dépendances auto-mergées, journal quotidien commité automatiquement
- [repo](https://github.com/Ruaudel-Emmanuel/rennesdev-vps-ops)

### 4. Fiscale-vps — facturation électronique conforme, locale, sans abonnement
Générateur **Factur-X** (PDF/A-3 + XML embarqué) conforme EN 16931 — pensé pour préparer les TPE/PME à l'obligation 2026, sans SaaS ni abonnement.
- Python (reportlab + factur-x) · interface web légère · validation veraPDF
- [repo](https://github.com/Ruaudel-Emmanuel/Fiscale-vps)

### 5. surveillance-tarifaire — veille concurrentielle automatisée
Suivi automatique des tarifs concurrents : collecte planifiée, comparaison, alertes.
- Python · planification · rapports automatiques
- [repo](https://github.com/Ruaudel-Emmanuel/surveillance-tarifaire)

### 6. GitHub Auditor — audit IA quotidien de tous mes projets
Un workflow n8n qui **analyse chaque matin à 06h00** tous mes dépôts GitHub actifs via **l'API Mistral** et m'envoie un rapport constructif sur Telegram.
- Le LLM adopte le rôle d'**« Architecte Collaborateur »** (Staff Engineer enthousiaste)
- 4 dimensions d'analyse : Issues, Bugs/Risques, Code Review, PR
- Zéro ressource serveur consommée : le VPS reste léger
- [repo](https://github.com/Ruaudel-Emmanuel/GitHub-Auditor)

### 7. Scan ubuntu-latest — veille CI/CD GitHub Actions
Un workflow n8n qui **scanne chaque matin à 05h00** l'ensemble de mes workflows GitHub Actions pour détecter l'utilisation de `runs-on: ubuntu-latest`. En vue du passage Ubuntu 24.04 → 26.04, ce scan identifie les workflows à migrer et génère un rapport avec **l'API Mistral** sur Telegram.
- Les repos concernés (dont Lecteur-PDF) sont **déjà figés sur ubuntu-24.04**
- Rapport Telegram automatisé avec analyse LLM, aucun secret dans le code
- [workflow exporté](https://github.com/Ruaudel-Emmanuel/rennesdev-vps-ops/tree/main/workflows/scan-ubuntu-latest)

---

## ⚙️ Ce GitHub s'administre en grande partie tout seul

Preuve par l'exemple de ce que je vends aux PME :

- 🧪 **CI sur chaque PR** : build Android vérifié avant tout merge (check requis pour merger)
- 🔄 **Dépendances** : PR chaque semaine, mergées automatiquement si la CI est verte
- 📔 **Journal quotidien** : l'état de l'infrastructure est commité automatiquement chaque soir
- 🚨 **Incidents** : le watchdog du serveur **ouvre et clôt ses propres issues** GitHub
- 📊 Templates d'issues/PR et protections de branches sur tous les dépôts actifs

---

## 📦 Workflows n8n archivés (trace historique)

Ces dépôts étaient des **exports de workflows n8n** (JSON + README), créés automatiquement lors des sessions de développement. Ils ont été **supprimés le 02/10/2026** pour nettoyer le profil GitHub ; les données sont sauvegardées en local.

`n8n-to-Github` · `Daily-Github` · `Ai-agent-convervationel` · `AI-personnal-assistant` · `rss-discord` · `mail-auto` · `Newsletter-podcast` · `Mail-to-sheet` · `Cold-Lead-Reactivation` · `Deep-research` · `Parallel-Batch-Processing` · `Local_Agent_IA` · `rss-codeur`

---

## 📬 Contact

- 🌐 [Portfolio](https://rennesdev.fr/portofolio.html)
- 💬 via GitHub (ouvert aux discussions, missions et opportunités)

---

## 📊 Activité

<p><img src="https://raw.githubusercontent.com/Ruaudel-Emmanuel/live-readme/main/assets/github-activity.svg" alt="Activité GitHub en direct — générée automatiquement chaque matin" width="560" /></p>
<p><img src="https://github-readme-stats.vercel.app/api?username=Ruaudel-Emmanuel&show_icons=true&theme=default" height="150" /></p>
<p><img src="https://streak-stats.demolab.com?user=Ruaudel-Emmanuel" height="150" /></p>

---

<a id="-english-version"></a>
## 🇬🇧 English version

# 👋 Emmanuel Ruaudel — Digital Transformation Director

> **I help small-business owners free up 5 to 10 hours a week** by automating their repetitive tasks —
> and I run the transformation end to end: process audit, high-ROI AI use cases, deployment,
> reliability and change management.

📍 Rennes, France · 🌐 [My portfolio](https://rennesdev.fr/portofolio.html)

---

## 🎯 Mission & goals

- **Automate the daily grind of small businesses**: forms → quotes → emails, competitive watch, alerts and reports — with results measured in hours saved.
- **Build simple tools that actually get used**: web and Android apps, lightweight, offline-capable when needed, published on the Play Store.
- **Run a full infrastructure on my own**: Linux VPS, Docker, monitoring, encrypted backups, CI/CD — everything documented, version-controlled and automated.
- **Pragmatic AI**: LLMs via API (Mistral) by default — self-hosting tested then dropped for resource efficiency — the right tool in the right place.

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

JavaScript · Python · Node.js · PostgreSQL · Docker · Android (Capacitor) · Play Store · n8n · Mistral API · Telegram bots · GitHub Actions · Caddy · Cloudflare · Linux/Ubuntu

---

## 🏆 Featured projects

### 1. Nav.rennesdev — "reading mode" web browser with local AI
A simplified browser that **extracts page content and analyses it with a local AI model** (summarise, Q&A) — data never leaves the server.
- Dependency-free Node.js, authentication, HTTPS, Docker
- AI: analysis via Mistral API — local Ollama tested then dropped (too RAM-hungry for the VPS)
- [repo](https://github.com/Ruaudel-Emmanuel/Nav.rennesdev)

### 2. Lecteur-PDF — fully offline Android app
PDF reader with **embedded PDF.js** (no CDN), zoom, remembered dark mode, **zero Android permissions** (no network, no storage).
- Capacitor 8 · GitHub Actions CI · signed release
- Published on the **Play Store** (closed testing)
- [repo](https://github.com/Ruaudel-Emmanuel/Lecteur-PDF)

### 3. rennesdev-vps-ops — the infrastructure that runs everything
The technical core of my business, **documented and versioned as a real project**:
- 10 Docker containers (n8n, PostgreSQL, monitoring…), reverse proxy, encrypted backups
- Telegram control bots, a watchdog that **opens and closes its own GitHub issues**
- CI on Android builds, auto-merged dependencies, daily auto-committed journal
- [repo](https://github.com/Ruaudel-Emmanuel/rennesdev-vps-ops)

### 4. Fiscale-vps — compliant e-invoicing, local, subscription-free
A **Factur-X generator** (PDF/A-3 + embedded XML, EN 16931 compliant) — built to prepare SMEs for the 2026 mandate, with no SaaS and no subscription.
- Python (reportlab + factur-x) · lightweight web UI · veraPDF validation
- [repo](https://github.com/Ruaudel-Emmanuel/Fiscale-vps)

### 5. surveillance-tarifaire — automated competitor price watch
Automatic tracking of competitors' prices: scheduled collection, comparison, alerts.
- Python · scheduling · automated reports
- [repo](https://github.com/Ruaudel-Emmanuel/surveillance-tarifaire)

### 6. GitHub Auditor — daily AI audit of all my projects
An n8n workflow that **every morning at 06:00** analyses all my active GitHub repos using **the Mistral API** and sends a constructive report to Telegram.
- The LLM acts as an **"Architecte Collaborateur"** (enthusiastic Staff Engineer)
- 4 analysis dimensions: Issues, Bug/Risk, Code Review, PR
- Zero server resources consumed: the VPS stays lean
- [repo](https://github.com/Ruaudel-Emmanuel/GitHub-Auditor)

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
