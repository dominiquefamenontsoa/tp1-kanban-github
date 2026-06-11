# TP1 — Kanban, GitHub & GitHub Projects

> Travaux pratiques BUT Informatique 1ère année — Semestre 2  
> Gestion visuelle de tâches et collaboration sur du code

---

## Description

Ce dépôt regroupe le travail réalisé dans le cadre du TP1 portant sur trois outils complémentaires de gestion de projet et de développement collaboratif :

- **Les tableaux Kanban** : méthode visuelle de gestion des tâches
- **GitHub** : plateforme d'hébergement de code et de collaboration
- **GitHub Projects** : outil Kanban intégré à GitHub

Le TP est réalisé en groupe de 2 étudiants.

---

## Prérequis

- Un navigateur web (Chrome, Firefox, Edge...)
- Un compte GitHub : [https://github.com](https://github.com)
- Git installé sur votre machine : [https://git-scm.com](https://git-scm.com)

---

## Installation

1. Cloner le dépôt sur votre machine :

```bash
git clone https://github.com/votre-username/tp1-kanban-github.git
```

2. Se placer dans le dossier :

```bash
cd tp1-kanban-github
```

3. Ouvrir les fichiers avec votre éditeur de texte habituel (VS Code, Notepad++, etc.).

---

## Utilisation

### Consulter le corrigé des questions

Le fichier `docs/corrige.docx` contient les réponses rédigées à toutes les questions de vérification des trois parties du TP.

### Suivre l'avancement du TP

Le tableau Kanban est accessible via l'onglet **Projects** de ce dépôt.  
Chaque tâche du TP correspond à une carte, déplacée de colonne en colonne au fil de l'avancement.

### Exemple de workflow complet

```
# 1. Créer une branche pour une tâche
git checkout -b feature/rediger-readme

# 2. Modifier les fichiers
# ...

# 3. Enregistrer les modifications
git add .
git commit -m "Ajoute le README du projet"

# 4. Pousser la branche
git push origin feature/rediger-readme

# 5. Ouvrir une Pull Request sur GitHub avec "Closes #numéro"
```

---

## Contenu du dépôt

```
tp1-kanban-github/
├── README.md          # Ce fichier
├── docs/
│   └── corrige.docx   # Réponses aux questions de vérification
└── kanban/
    └── tableau.md     # Description du tableau Kanban physique réalisé
```

---

## Tableau Kanban (GitHub Projects)

Le projet est géré via **GitHub Projects** (vue Board).  
Les colonnes utilisées sont :

| Colonne | Rôle |
|-------|------|
|  Todo | Tâches identifiées, pas encore commencées |
|  In Progress | Tâches en cours (limite WIP : 3) |
|  Done | Tâches terminées |

---

## Contribuer

Ce dépôt est un projet pédagogique de groupe fermé. Les contributions externes ne sont pas acceptées.

Si vous êtes membre du groupe :

1. Créez une **issue** pour décrire la tâche ou le problème
2. Créez une **branche** dédiée (`feature/nom-de-la-tache`)
3. Faites des **commits** clairs (`Ajoute...`, `Corrige...`, `Met à jour...`)
4. Ouvrez une **pull request** avec `Closes #numéro` dans la description
5. Attendez la relecture d'un autre membre avant de fusionner

---

## Équipe

| Membre                 | Coordonnées                       |
|------------------------|-----------------------------------|
| Amina DJAYJI           | amina.djayji@etu.u-pec.fr         |
| Dominique FAMENONTSOA  | famenontsoa.dominique@etu.u-pec.fr|

---

## Licence

Ce projet est réalisé dans un cadre pédagogique — IUT de Créteil-Vitry, UPEC.
