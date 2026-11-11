# 👋 Emmanuel Ruaudel — Directeur de la Transformation Numérique

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

### 1. rennesdev-vps-ops — l'infrastructure qui fait tout tourner
Le cœur technique de mon activité, **documenté et versionné comme un projet à part entière** :
- 10 conteneurs Docker (n8n, PostgreSQL, monitoring…), reverse proxy, sauvegardes chiffrées
- Bots Telegram de contrôle, watchdog qui **ouvre/clôt ses propres issues GitHub**
- CI sur les builds Android, dépendances auto-mergées, journal quotidien commité automatiquement
- [repo](https://github.com/Ruaudel-Emmanuel/rennesdev-vps-ops)

### 2. surveillance-tarifaire — veille concurrentielle automatisée
Suivi automatique des tarifs concurrents : collecte planifiée, comparaison, alertes.
- Python · planification · rapports automatiques
- [repo](https://github.com/Ruaudel-Emmanuel/surveillance-tarifaire)

### 3. GitHub Auditor — audit IA quotidien de tous mes projets
Un workflow n8n qui **analyse chaque matin à 06h00** tous mes dépôts GitHub actifs via **l'API Mistral** et m'envoie un rapport constructif sur Telegram.
- Le LLM adopte le rôle d'**« Architecte Collaborateur »** (Staff Engineer enthousiaste)
- 4 dimensions d'analyse : Issues, Bugs/Risques, Code Review, PR
- Zéro ressource serveur consommée : le VPS reste léger
- [repo](https://github.com/Ruaudel-Emmanuel/GitHub-Auditor)


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
