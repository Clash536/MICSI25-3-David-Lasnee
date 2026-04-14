# MICSI25-3-David-Lasne

## Objectif de l'exercice

Apprendre à utiliser Git/Github/Vscode :
<br>
- gestion des branches
<br>
- commits
<br>
- push
<br>
- merge
<br>

---

## Installation de Git
<br>

https://git-scm.com/

<br>

## Commandes

git clone	Cloner un repository
<br>
git checkout -b develop	Créer et se positionner sur une branche
<br>
touch file1 file2 file3	Créer des fichiers
<br>
git add .	Ajouter les fichiers au commit
<br>
git commit -m "message"	Enregistrer les modifications
<br>
git push origin develop	Envoyer la branche sur GitHub
<br>
git checkout main	Se déplacer sur la branche principale
<br>
git merge develop	Fusionner develop dans main
<br>
mv file1 file1.txt	Renommer un fichier
<br>
rm file3	Supprimer un fichier

<br>

## Diagramme du flow de commit avec les branch

main
│
├── Initialisation du projet
│
└── develop
      |── Création file1, file2, file3
      ├── Commit
      ├── Push
      ├── Création README
      ├── Modification fichiers
      ├── Commit
      │
      └── Merge vers main

---
title: Example Git diagram
---
gitGraph
   commit
   commit
   branch develop
   checkout develop
   commit
   commit
   checkout main
   merge develop
   commit
   commit
