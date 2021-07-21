# Consignes

Pratiquer Git en travaillant sur le même projet, tout en construisant un recueil de pratiques (cheatsheet).

## Objectif

Le fichier [README.md](README.md) contient une liste de questions.
Il faut remplacer chacune de ces questions par un lien vers un fichier `.md` placé dans le bon dossier.
Ce fichier contiendra la question et ensuite la réponse détaillée.

Les questions à répondre vous seront attribuées aléatoirement.

## Règles concernant les fichiers réponses

Un fichier réponse doit :
* avoir un nom en la snake case, en minuscules.
* avoir l'extension `.md`
* reprendre la question posée, en titre h1 (`#`)
* le reste de son contenu est libre mais doit respecter la syntaxe Markdown. (Voir les [ressources](ressources.md))

Vous êtes libres d'inclure des images ou des références vers des pages web pertinentes (documentation officielle, blogs, Stack Overflow...)

## Règles concernant les branches et commits

* Une branche par question/réponse : pas d'autre modification.
* Le nom de la branche doit être le nom du fichier réponse, sans l'extension `.md`.
* les messages de commit doivent décrire succintement les modifications apportées, en anglais. 

## Règles concernant les fusions

* Il faut ouvrir une Pull Request (PR) pour qu'une branche réponse soit fusionnée dans la branche principale.
* Les PR doivent être relues par un·e autre participant·e.
* La relecture doit inclure des commentaires demandant modification si c'est pertinent : contenu, nom des branches / commits.
* Cette relecture doit être matérialisée par au moins un commentaire :+1: .
* Une fois la fusion réussie, une nouvelle question vous sera attribuée.

## FAQ

* L'accès au cours, notes, livres, internet etc n'est pas restreint.
* Le contenu des réponses participe à l'évaluation.
* Les "traces Git" (branches, commits, messages de commit, commentaires de relecture) participent à l'évaluation.
* Ce n'est pas pénalisant d'avoir plusieurs commits dans une branche réponse.
* Ce n'est pas pénalisant d'avoir des retours lors de la relecture de la PR, s'ils sont traités par la suite.
* N'hésitez pas à proposer de nouvelles questions.
* Une faute de frappe, un complément à apporter à la branche principale ? Créez une branche `hotfix/...` et passez par le processus de Pull Request.
* Une resource intéressante à partager ? Créez une branche `doc/...` en apportant des ajouts au fichier [ressources.md](ressources.md) général.
