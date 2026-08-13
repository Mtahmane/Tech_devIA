


# Tech_devIA
# Moussa Tagalfi Touré

## Ingénieur Logiciel & IA — Fullstack | Architecte de solutions intelligentes

Je suis **Moussa Tagalfi Touré**, ingénieur informatique spécialisé en **génie logiciel et intelligence artificielle**, avec une passion particulière pour la conception de produits numériques robustes, intelligents et utiles.

Mon approche combine **ingénierie logicielle, développement Fullstack, architecture système et intelligence artificielle** pour transformer des problématiques complexes en solutions technologiques concrètes.

Je conçois et développe des applications web, des plateformes métier, des API, des systèmes distribués et des solutions d’IA intégrant notamment la **Generative AI, les systèmes RAG, les VoiceBots et l’automatisation intelligente**. Mon expertise couvre l’ensemble de la chaîne technique, du besoin métier jusqu’à l’architecture, au développement, au déploiement et à l’amélioration continue.

### Ma vision

Pour moi, le logiciel ne doit pas simplement fonctionner : il doit **résoudre un problème réel, être maintenable, évoluer avec les besoins et apporter une véritable valeur à ses utilisateurs**.

Je privilégie donc une approche fondée sur la compréhension du problème, la simplicité architecturale, la robustesse technique et l’impact métier.

### Ce que je construis

* Applications web et plateformes Fullstack
* Architectures backend et API
* Solutions SaaS et systèmes métier
* Applications intégrant l’IA générative
* Systèmes RAG et assistants intelligents
* VoiceBots et interfaces conversationnelles
* Systèmes distribués et microservices
* Solutions data et automatisation
* Dashboards et applications orientées IA

Mon environnement technique s'étend notamment de **Python, TypeScript/JavaScript, React et Next.js** à **FastAPI, Django, NestJS, Spring Boot, PostgreSQL, MongoDB, Redis, Docker, Kubernetes, Kafka et AWS**.

### Mon parcours

Mon expérience s'est construite dans différents environnements professionnels, notamment dans les secteurs des **télécommunications, de la régulation, du développement logiciel et de l'innovation technologique**. J'ai notamment travaillé sur des projets de digitalisation, des solutions de surveillance basées sur l'IA et des systèmes intelligents exploitant le RAG et les interfaces vocales.

Aujourd'hui, je cherche à mettre cette combinaison de compétences techniques et analytiques au service de **projets ambitieux capables de produire un impact concret en Afrique et au-delà**.

> **Je ne me contente pas d'écrire du code. Je conçois des systèmes qui transforment des idées et des problèmes complexes en solutions numériques concrètes.**

Ingénieur logiciel &amp; IA spécialisé en développement Fullstack et architecture de solutions intelligentes. Je conçois des applications web, systèmes distribués et solutions d’IA générative, avec une approche orientée performance, innovation et impact métier.


```python
readme_content = """# 🚀 Projets Personnels & Professionnels Privés

Bienvenue sur la présentation de mes projets privés de développement et d'Intelligence Artificielle. Ce document synthétise les problématiques techniques résolues, les architectures logicielles et les responsabilités exercées.

---

## 📑 Sommaire des Projets Privés

1. [Voicebot_Rag (VoiceBot Intelligent & Multilingue RAG)](#1-voicebot_rag--voicebot-intelligent--multilingue-rag)
2. [front_pool_secretariat (Gestion du Secrétariat AMRTP)](#2-front_pool_secretariat--gestion-du-secrétariat-amrtp)
3. [frontend_amrtp (Plateforme Web AMRTP)](#3-frontend_amrtp--plateforme-web-principale-amrtp)
4. [home-moussa-tagalfi-tour-mali-telecom-platform (Plateforme Télécom Mali)](#4-home-moussa-tagalfi-tour-mali-telecom-platform--plateforme-télécom)
5. [IA_voicebot & Voicebot (Moteur VoiceBot & Traitement Vocal)](#5-ia_voicebot--voicebot--moteurs-dintelligence-artificielle-vocale)

---

## 1. Voicebot_Rag — VoiceBot Intelligent & Multilingue (RAG)

### 📌 Description du problème technique résolu
Accès difficile à l'information administrative et technique pour des utilisateurs parlant des langues locales (Bambara, Peul, Français) sans maîtrise de la recherche textuelle complexe.
Le système résout ce défi grâce à un **Pipeline RAG (Retrieval-Augmented Generation)** couplé à une chaîne **STT (Speech-to-Text)** et **TTS (Text-to-Speech)** multilingue :
- **Conversion vocale & reconnaissance multilingue :** Captation du signal audio, débruitage, transcription fine en langues locales/français.
- **Indexation vectorielle :** Découpage (*chunking*) et vectorisation de documents réglementaires/techniques pour restitution sans hallucination.
- **Synthèse vocale naturelle :** Génération automatique de réponses vocales contextualisées dans la langue détectée.

### 🛠️ Stack Technique
- **Langage & Frameworks :** Python, LangChain / LlamaIndex, FastAPI
- **IA / NLP / Audio :** OpenAI API / Whisper, FAISS / ChromaDB (Vector Store), Tacotron2 / Coqui TTS
- **Déploiement & DevOps :** Docker, Ollama / Hugging Face Transformers

### 🖼️ Aperçu de l'interface / Démonstration

```text
+-----------------------------------------------------------------------+
|  🎙️  VOICEBOT RAG INTERFACE                                           |
+-----------------------------------------------------------------------+
|  [ Langue détectée : Bambara 🇲🇱 ]                                    |
|                                                                       |
|  👤 Utilisateur : (Message Vocal enregistré 0:04)                     |
|     └── Transcription : "A ni sogoma, N'be fɛ ka mɔgɔ dɛmɛ..."      |
|                                                                       |
|  🔍 Recherche Vectorielle RAG :                                        |
|     └── Documents extraits : [doc_reglement_telecom_v2.pdf - 94%]     |
|                                                                       |
|  🤖 Voicebot : (Lecture audio synthétisée 🔊 0:08)                   |
|     └── Texte : "Aw ni ce! Aw bɛ se ka..."                            |
+-----------------------------------------------------------------------+

```

*(Remarque : Remplacez ce schéma par le fichier gif/png correspondant : `docs/screenshots/voicebot_rag_demo.gif`)*

### 👨‍💻 Liste des responsabilités

* Conception et implémentation complète du pipeline RAG (chunking, embedding, retrieval).
* Intégration des modèles Speech-to-Text et Text-to-Speech adaptés aux spécificités linguistiques.
* Optimisation du temps de réponse (latence réduite pour une interaction vocale fluide).

---

## 2. front_pool_secretariat — Application de Gestion du Secrétariat AMRTP

### 📌 Description du problème technique résolu

Digitalisation, traçabilité et sécurisation des flux de courrier, bordereaux et documents administratifs au sein du secrétariat central de l'AMRTP.
L'application résout les goulets d'étranglement de traitement physique :

* **Workflow de validation :** Enregistrement, numérotation automatique, imputation aux services destinataires.
* **Suivi en temps réel :** Tableaux de bord de statut (Reçu, En traitement, Validé, Archivé).
* **Gestion des accès restreints :** Rôles et autorisations stricts par niveau hiérarchique.

### 🛠️ Stack Technique

* **Frontend :** TypeScript, React.js, TailwindCSS
* **State Management & Querying :** Redux Toolkit / React Query, Axios
* **UI Components :** Lucide Icons, Headless UI, Datepicker components

### 🖼️ Aperçu de l'interface / Démonstration

```text
+-----------------------------------------------------------------------+
| 📂 AMRTP - Secrétariat Central | Dashboard Courriers                  |
+-----------------------------------------------------------------------+
| [ + Nouveau Courrier ]  [ 🔍 Rechercher par N° / Expéditeur ]         |
|-----------------------------------------------------------------------|
| ID      | Expéditeur       | Objet              | Statut    | Action  |
|-----------------------------------------------------------------------|
| CR-1042 | Min. Numérique   | Rapport Annuel     | En cours  | [Voir]  |
| CR-1041 | Orange Mali      | Demande Fréquence  | Validé    | [Voir]  |
| CR-1040 | Sotelma-Malitel  | Notification       | Traité    | [Voir]  |
+-----------------------------------------------------------------------+

```

*(Fichier image recommandé : `docs/screenshots/secretariat_dashboard.png`)*

### 👨‍💻 Liste des responsabilités

* Lead Développeur Frontend sur le module Secrétariat.
* Conception de l'interface utilisateur responsive et ergonomique sous TailwindCSS.
* Connexion aux API REST backend et gestion de l'état global de l'application.

---

## 3. frontend_amrtp — Plateforme Web Principale AMRTP

### 📌 Description du problème technique résolu

Centralisation des services numériques, démarches réglementaires et portails d'information de l'Autorité de Régulation des Télécommunications/TIC et Postes (AMRTP).
Problématiques résolues :

* **Performance & SEO :** Temps de chargement optimisé pour des requêtes haute fréquence.
* **Sécurité des formulaires :** Soumission sécurisée de dossiers d'agrément et requêtes d'opérateurs.
* **Design System institutionnel :** Cohérence visuelle stricte répondant aux charte graphiques officielles.

### 🛠️ Stack Technique

* **Frontend :** TypeScript, React.js / Next.js, TailwindCSS
* **Build Tool :** Vite / Webpack
* **CI/CD :** GitHub Actions, Docker containers

### 🖼️ Aperçu de l'interface / Démonstration

```text
+-----------------------------------------------------------------------+
| 🏛️ PORTAIL OFFICIEL AMRTP MALI                                        |
+-----------------------------------------------------------------------+
| [ Accueil ] [ Réglementation ] [ Agrément ] [ E-Services ] [ Contact ]|
|-----------------------------------------------------------------------|
|  |-----------------------------------------------------------------|  |
|  |  Plateforme Numérique de Gestion des Autorisations & Opérateurs  |  |
|  |  [ Faire une demande d'agrément ]  [ Suivre mon dossier ]      |  |
|  |-----------------------------------------------------------------|  |
+-----------------------------------------------------------------------+

```

*(Fichier image recommandé : `docs/screenshots/frontend_amrtp_main.png`)*

### 👨‍💻 Liste des responsabilités

* Développement des composants UI TypeScript réutilisables.
* Intégration des formulaires complexes de demande d'autorisation en ligne avec validation côté client.
* Optimisation de l'accessibilité web et du responsive design.

---

## 4. home-moussa-tagalfi-tour-mali-telecom-platform — Plateforme Télécom

### 📌 Description du problème technique résolu

Plateforme métier orientée suivi, statistiques et supervision du secteur des télécommunications.
Problématiques résolues :

* **Aggrégation de données :** Visualisation de métriques de couverture réseau et d'indicateurs de performance (KPI).
* **Cartographie/Tableaux de bord :** Visualisation dynamique des infrastructures et de la qualité de service (QoS).

### 🛠️ Stack Technique

* **Languages & Frameworks :** TypeScript, React, Chart.js / Recharts
* **Styling :** TailwindCSS, CSS Modules

### 🖼️ Aperçu de l'interface / Démonstration

```text
+-----------------------------------------------------------------------+
| 📊 MALI TELECOM PLATFORM - KPI MONITORING                             |
+-----------------------------------------------------------------------+
| [ Taux de Couverture : 87.4% ]   [ Abonnés Mobiles : 18.2M ]         |
|                                                                       |
|  [ Graphique de Performance QoS ]   [ Répartition 3G/4G/5G par Région] |
|   /\--/\---/                        [■ Bamako  ■ Sikasso  ■ Mopti]    |
|  /  \  \  /                                                           |
+-----------------------------------------------------------------------+

```

*(Fichier image recommandé : `docs/screenshots/mali_telecom_platform.png`)*

### 👨‍💻 Liste des responsabilités

* Architecture frontend et mise en place des tableaux de bord analytiques.
* Intégration des librairies de graphiques interactifs.

---

## 5. IA_voicebot & Voicebot — Moteurs d'Intelligence Artificielle Vocale

### 📌 Description du problème technique résolu

Modules de traitement backend dédiés aux workflows audio/voix et au traitement automatique du langage naturel (NLP) pour alimenter les différents agents virtuels.
Problématiques résolues :

* Pre-processing audio (réduction de bruit, segmentation d'intervalles de silence).
* Normalisation du texte et alignement pour la synthèse vocale en langues locales.

### 🛠️ Stack Technique

* **Langage :** Python
* **Bibliothèques Audio/IA :** PyTorch, Librosa, SoundFile, Whisper API, Transformers

### 🖼️ Aperçu de l'interface / Démonstration

```text
[ Audio Input (.wav) ] ➔ [ Noise Filter ] ➔ [ Whisper STT ] ➔ [ Intent Parser ] ➔ [ Response Generator ]

```

*(Fichier image recommandé : `docs/diagrams/voicebot_architecture.png`)*

### 👨‍💻 Liste des responsabilités

* Développeur Backend / IA.
* Conduite des tests de précision de transcription audio et optimisation du pipeline Python.

---

*Fichier généré pour le profil GitHub de **Moussa Tagalfi Touré**.*
"""

with open("README.md", "w", encoding="utf-8") as f:
f.write(readme_content)

print("README.md generated successfully.")

```

```text?code_stdout&code_event_index=1
README.md generated successfully.


```

Voici le contenu complet structuré pour votre fichier **README.md**, personnalisé selon vos projets privés identifiés sur votre profil.

Le fichier `README.md` a été directement généré et est prêt à être intégré à la racine de votre repository GitHub :

---

### Aperçu du contenu du `README.md` :

```markdown
# 🚀 Projets Personnels & Professionnels Privés — Moussa Tagalfi Touré

Ce document récapitule mes principaux projets privés en développement logiciel et en Intelligence Artificielle.

---

## 📑 Sommaire

1. [Voicebot_Rag (VoiceBot Intelligent & Multilingue RAG)](#1-voicebot_rag--voicebot-intelligent--multilingue-rag)
2. [front_pool_secretariat (Gestion du Secrétariat AMRTP)](#2-front_pool_secretariat--gestion-du-secrétariat-amrtp)
3. [frontend_amrtp (Plateforme Web Principale AMRTP)](#3-frontend_amrtp--plateforme-web-principale-amrtp)
4. [home-moussa-tagalfi-tour-mali-telecom-platform (Plateforme Télécom)](#4-home-moussa-tagalfi-tour-mali-telecom-platform--plateforme-télécom)
5. [IA_voicebot & Voicebot (Moteurs IA Vocale)](#5-ia_voicebot--voicebot--moteurs-dintelligence-artificielle-vocale)

---

## 1. Voicebot_Rag — VoiceBot Intelligent & Multilingue (RAG)

### 📌 Problème technique résolu
Permettre l'accès aux informations institutionnelles et réglementaires pour des utilisateurs s'exprimant en langues locales (Bambara, Peul, Français, etc.) sans dépendre de la recherche textuelle classique.
- **Pipeline RAG (Retrieval-Augmented Generation) :** Recherche vectorielle sur documents indexés pour garantir des réponses exactes et sans hallucinations.
- **Speech-to-Text (STT) & Text-to-Speech (TTS) :** Traitement de la voix en entrée et restitution audio fluide dans la langue détectée.

### 🛠️ Stack Technique
- **Langage & Frameworks :** Python, LangChain / LlamaIndex, FastAPI
- **IA / NLP / Audio :** OpenAI API / Whisper, FAISS / ChromaDB (Vector Database), Coqui TTS
- **DevOps & Outils :** Docker, Hugging Face / Ollama

### 🖼️ Capture d'écran / Démonstration (Interface / Workflow)

```text
+-----------------------------------------------------------------------+
|  🎙️  VOICEBOT RAG INTERFACE                                           |
+-----------------------------------------------------------------------+
|  [ Langue détectée : Bambara 🇲🇱 ]                                    |
|                                                                       |
|  👤 Utilisateur : (Message Vocal 0:04)                               |
|     └── Transcription : "A ni sogoma, N'be fɛ ka mɔgɔ dɛmɛ..."      |
|                                                                       |
|  🔍 Recherche Vectorielle RAG :                                        |
|     └── Documents extraits : [doc_reglement_telecom_v2.pdf - 94%]     |
|                                                                       |
|  🤖 Voicebot : (Lecture audio synthétisée 🔊 0:08)                   |
|     └── Texte : "Aw ni ce! Aw bɛ se ka..."                            |
+-----------------------------------------------------------------------+

```

*(Placez vos captures ou GIFs animés réels sous : `docs/screenshots/voicebot_rag.gif`)*

### 👨‍💻 Responsabilités (Projet IA)

* Conception et implémentation du pipeline complet Retrieval-Augmented Generation (RAG).
* Intégration et optimisation des modèles STT et TTS multilingues adaptés aux langues locales.
* Optimisation de la latence globale pour une interaction vocale fluide.

---

## 2. front_pool_secretariat — Application de Gestion du Secrétariat AMRTP

### 📌 Problème technique résolu

Digitalisation, traçabilité et sécurisation de la gestion des courriers (départ/arrivée), bordereaux et imputations administratives au sein de l'AMRTP.

* Workflow complet d'enregistrement, numérotation automatique et attribution aux services.
* Suivi en temps réel des statuts des dossiers avec gestion stricte des droits d'accès.

### 🛠️ Stack Technique

* **Frontend :** TypeScript, React.js, TailwindCSS
* **State Management & Querying :** Redux Toolkit / React Query, Axios
* **UI Components :** Lucide Icons, Headless UI

### 🖼️ Capture d'écran / Démonstration

```text
+-----------------------------------------------------------------------+
| 📂 AMRTP - Secrétariat Central | Dashboard Courriers                  |
+-----------------------------------------------------------------------+
| [ + Nouveau Courrier ]  [ 🔍 Rechercher par N° / Expéditeur ]         |
|-----------------------------------------------------------------------|
| ID      | Expéditeur       | Objet              | Statut    | Action  |
|-----------------------------------------------------------------------|
| CR-1042 | Min. Numérique   | Rapport Annuel     | En cours  | [Voir]  |
| CR-1041 | Orange Mali      | Demande Fréquence  | Validé    | [Voir]  |
+-----------------------------------------------------------------------+

```

### 👨‍💻 Responsabilités

* Lead Développeur Frontend de l'interface du Secrétariat.
* Création de composants réutilisables et ergonomiques avec TailwindCSS.
* Intégration des API REST et gestion centralisée des états d'application.

---

## 3. frontend_amrtp — Plateforme Web Principale AMRTP

### 📌 Problème technique résolu

Mise en place du portail institutionnel et de téléservices pour les acteurs du secteur des télécoms au Mali (demandes d'agréments, formulaires réglementaires, dépôts de dossiers).

### 🛠️ Stack Technique

* **Frontend :** TypeScript, React.js / Next.js, TailwindCSS
* **Outils :** Vite / Webpack, GitHub Actions, Docker

### 👨‍💻 Responsabilités

* Intégration responsive respectant la charte graphique officielle.
* Validation dynamique des formulaires complexes côté client.

---

## 4. home-moussa-tagalfi-tour-mali-telecom-platform — Plateforme Télécom

### 📌 Problème technique résolu

Centralisation et visualisation d'indicateurs de performance (KPI), cartographie de couverture réseau et métriques du marché des télécoms.

### 🛠️ Stack Technique

* **Frontend :** TypeScript, React, Chart.js / Recharts, TailwindCSS

### 👨‍💻 Responsabilités

* Développement des graphiques interactifs et tableaux de bord analytiques.

---

## 5. IA_voicebot & Voicebot — Moteurs IA Vocale

### 📌 Problème technique résolu

Développement des modules backend audio pour le nettoyage du signal sonore, la segmentation vocale et le prétraitement NLP.

### 🛠️ Stack Technique

* **Langage & Libs :** Python, PyTorch, Librosa, Whisper API, SoundFile

```

```
