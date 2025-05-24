# Autorisation sur les tâches

Cette section explique comment un chef de projet peut autoriser un utilisateur à saisir des heures sur les tâches d'un projet.

!!! warning Attention
    Pour pouvoir saisir des autorisations, l'utilisateur doit avoir les permissions nécessaires.

    ![task_role](./assets/img/task_role.png)

## Niveau des autorisations

Les autorisations peuvent être définies à plusieurs niveaux :
- **Global** : L'utilisateur peut saisir des heures sur toutes les tâches de tous les projets.
- **Projet** : L'utilisateur peut saisir des heures sur toutes les tâches d'un projet spécifique.
- **Phase** : L'utilisateur peut saisir des heures sur toutes les tâches d'une phase spécifique d'un projet.
- **Tâche** : L'utilisateur peut saisir des heures sur une tâche spécifique d'un projet.

### Définir une autorisation de niveau **Global**

Pour définir une autorisation de niveau global, il suffit de sélectionner l'utilisateur et de laisser les trois listes déroulantes vides. 

En appuyant sur le bouton `+`, l'autorisation sera créée et l'utilisateur pourra saisir des heures au niveau global.
![task_role_global](./assets/img/task_role_global.png)

### Définir une autorisation de niveau **Projet**

Pour définir une autorisation de niveau projet, il faut sélectionner l'utilisateur, le projet et laisser les deux autres listes déroulantes vides.

Idem, en appuyant sur le bouton `+`, l'autorisation sera créée et l'utilisateur pourra saisir des heures sur toutes les tâches du projet.

![task_role_project](./assets/img/task_role_project.png)

### Définir une autorisation de niveau **Phase** ou **Tâche**

Pour définir une autorisation de niveau phase ou tâche, il faut sélectionner l'utilisateur, le projet, la phase ou la phase et la tâche.

!!! info
    Si l'utilisateur a déjà une autorisation, et qu'une autorisation de niveau inférieur est saisie, alors un message d'avertissement s'affiche pour prévenir que l'autorisation sera contournée par une autre plus prioritaire.
    ![task_bypass](./assets/img/task_bypass.png)


