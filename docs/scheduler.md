# Calendrier des heures

Cette section explique comment saisir des heures dans le calendrier des heures.

Le calendrier des heures possède, par defaut, des cellules d'une durée de 15 minutes et est disposé au format jour/semaine/mois.

![scheduler](./assets/img/scheduler.png)

## Saisir des heures

En cliquant sur une cellule du calendrier, une page s'ouvre pour et permet la sélection d'un élément de projet dont l'utilisateur est autorisé à saisir des heures.
![scheduler_form](./assets/img/scheduler_form.png)

### Rechercher rapidement un projet
Pour rechercher rapidement un projet, il suffit de saisir des mots-clés dans le champ de recherche.

par exemple, si la tâche est nommée: 
```Recherche de partis et estimation sommaire des coûts de construction - 4.31 Avant-projet - Mon premier projet```

alors il suffit de saisir des portions de mots-clés comme `partis`, `estimation`, `mon premi`, `proj`

avec les mots `prem` et `rech`, la tache sera trouvée.

![scheduler_search_list](./assets/img/scheduler_search_list.png)

### Saisir des heures

Une fois le projet sélectionné, il suffit de sélectionner le type d'heure et de définir un commentaire si nécessaire.

Une fois validé, cliquer sur le bouton sauvegarder en vert en bas à droite de la fenêtre de dialogue.
puis étirez la cellule pour définir la durée de l'heure saisie.
![scheduler_stretch](./assets/img/scheduler_stretch.png)

### Utilisation des favoris

Une fois que des heures ont été saisies, l'option des favoris met a disposition les derniers projets saisis pour une saisie ultra rapide.

En cliquant sur la petite étoile au dessus de la liste des tâches, les derniers projets saisis sont affichés.

![scheduler_favorites](./assets/img/scheduler_favorites.png)


### Editer ou supprimer une heure saisie

En cliquant sur les trois petits points à droite de la cellule, un menu s'affiche pour éditer ou supprimer l'heure saisie.

![scheduler_edit](./assets/img/scheduler_edit.png)

### Utiliser le compteur de temps

Un pseudo compteur de temps est disponible pour saisir des heures, le bouton rose en bas à droite de l'écran permet de rentrer une heures avec sa durée avec quelques conditions:

- L'heure saisie est le jour même
- L'heure saisie commence à la fin de la dernière heure saisie et s'étend jusqu'à l'heure actuelle
- Si aucune heure n'a été saisie, alors l'heure saisie commence à 8h00 et s'étend jusqu'à l'heure actuelle
- Si une heure déjà saisie dépasse l'heure actuelle, alors une cellule s'ajoute à la suite.

![scheduler_counter](./assets/img/scheduler_counter.png)
![scheduler_counter_stack](./assets/img/scheduler_counter_stack.png)