# Mon Projet

Ce projet s'inscrit dans le cadre de mon cursus scolaire à CentraleSupélec. Il vise à utiliser des réseaux de neurones pour détecter les émotions dans divers contextes. J'ai opté pour la détection d'émotions dans des textes écrits, permettant de déterminer si le ton est joyeux, triste, etc. Cette application présente de nombreuses utilisations potentielles, telles que l'amélioration des réponses des chatbots ou l'aide aux personnes autistes ayant des difficultés à reconnaître les émotions dans les messages.

Pour entraîner mon modèle, je vais utiliser la base de données IEMOCAP, qui contient de nombreuses transcriptions de dialogues étiquetées.

Ce projet a été réalisé en une semaine, conformément à la date limite fixée par l'école. Il est annoté et commenté afin d'expliquer mes choix.


# Configuration de l'Environnement Virtuel

Pour exécuter ce projet, je vous recommande d'utiliser un environnement virtuel. Cela permet de gérer les dépendances du projet de manière isolée. Voici comment mettre en place et activer un environnement virtuel.

## Prérequis

Assurez-vous d'avoir Python installé sur votre système. Ce projet devrait être compatible avec d'autres versions de Python 3.
assurez vous également d'avoir la possibilité de pouvoir installer des environnements virtuel également : pip install --user virtualenv 

## Installation

1. **Cloner le dépôt**  
   Pour commencer, clonez ce dépôt sur votre machine locale en utilisant la commande suivante : git clone https://github.com/AndeolF/Projet-reco-emotion-texte.git

2. **Naviguer dans le dossier du projet**  
Changez de répertoire pour aller dans le dossier du projet cloné : cd Projet-reco-emotion-texte

3. **Créer l'environnement virtuel**  
Exécutez la commande suivante pour créer un environnement virtuel dans le répertoire du projet : python -m venv env

Cela crée un dossier `env` qui contiendra tous les packages Python nécessaires.

4. **Activer l'environnement virtuel**  
Avant de travailler sur votre projet, vous devez activer l'environnement virtuel. Vous pouvez le faire avec les commandes suivantes :

- Sur Windows :  env\Scripts\activate

- Sur macOS et Linux :  source env/bin/activate

Vous saurez que l'environnement virtuel est activé car le nom de l'environnement (`env`) apparaîtra sur votre ligne de commande.

5. **Installer les dépendances**  
Avec l'environnement virtuel activé, installez les dépendances requises en exécutant : pip install -r requirements.txt

## Exécution du projet

Avec l'environnement configuré et les dépendances installées, vous pouvez maintennat exectuer le projet

## Désactivation de l'environnement virtuel

Lorsque vous avez terminé de travailler dans l'environnement virtuel, vous pouvez le désactiver en exécutant : deactivate

