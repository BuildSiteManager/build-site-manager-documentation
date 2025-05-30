# Société

Dans cette section, nous allons voir comment gérer les membres d'une société ainsi que leurs rôles.

## Employés

Pour ajouter un employé à votre société, cliquez sur le bouton `+` en haut de la liste.
![company_employee](./assets/img/company_employee.png)

Remplissez le formulaire avec les informations demandées, puis cliquez sur le bouton sauvegarder en vert en bas à droite de la fenêtre de dialogue.
![company_employee_add](./assets/img/company_employee_add.png)

On remarque l'apparition du nouvel employé dans la liste des employés de la société avec un petit symbole de lien. Ce symbole indique que l'employé n'est pas lié à un compte utilisateur.
![company_employee_added](./assets/img/company_employee_added.png)

En cliquant sur ce symbole, on a la possibilité de créer un code d'invitation qui peut être donné à l'utilisateur.
![company_employee_link](./assets/img/company_employee_link.png)
![company_employee_link_code](./assets/img/company_employee_link_code.png)

L'utilisateur rentrera alors ce code d'invitation comme expliqué dans la section [S'enregistrer](./register.fr.md).

!!! note
    Pour inviter l'utilisateur afin qu'il puisse saisir les information de l'employé dès qu'il saisit le code d'invitation, cliquez simplement sur le bouton `INVITER` et transmettez le code d'invitation à l'utilisateur.

## Rôles
Les rôles contiennent des permissions, ces permissions permettent d'effectuer des actions dans l'application. Par défaut, un rôle appelé `Admin` est créé et possède un accès complet à l'application.

!!! warning Remarque
    Au moins un rôle ayant des accès complets doit être attribué à un utilisateur de la société. L'application ne laissera pas modifier les rôles si cette condition n'est pas respectée.

![company_role](./assets/img/company_role.png)

### Attribuer des rôles

Une fois l'utilisateur sélectionné dans la liste de gauche, on peut modifier les rôles qui lui sont attribués en sélectionnant les rôles dans la liste de droite.

!!! note
    Le détail des rôles peut être visualisé en cliquant sur le petit ![company_role_information](./assets/img/company_role_information.png) à côté du nom du rôle. 

### Créer un rôle

Pour créer un rôle, cliquez sur le bouton `+` en haut de la liste des rôles. 

![company_role_create](./assets/img/company_role_create.png)

Saisissez un nom pour le rôle, puis vous avez 2 possibilités :

1. Créer un rôle avec accès complet à l'application en cochant la case `Accès complet`.
2. Créer un rôle avec des permissions personnalisées en décochant la case `Accès complet` et en sélectionnant les permissions dans la liste.

Dans le deuxième cas, nous allons créer un rôle `Ressources humaines` qui aura accès à la gestion des employés.

![company_role_create_rh](./assets/img/company_role_create_rh.png)

Une fois ce rôle créé, nous allons l'attribuer à un utilisateur, dans notre cas ce sera l'utilisateur `Alice`.

![company_role_assign](./assets/img/company_role_assign.png)

!!! warning Attention
    Il ne faut pas oublier de cliquer sur le bouton sauvegarder en vert en bas à droite de la fenêtre de pour enregistrer les modifications. Sinon les séléctions ne seront pas prises en compte.

Voici ce que voit l'utilisateur `Alice` dans son interface après avoir rafraîchi la page.

![company_role_assigned_view_by_alice](./assets/img/company_role_assigned_view_by_alice.png)

Alice voit effectivement la liste des employés de la société, mais elle n'a pas accès aux rôles, ni aux permissions. Elle ne peut donc pas modifier les rôles des autres utilisateurs.