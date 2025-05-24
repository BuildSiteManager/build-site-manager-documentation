# Company

In this section, we will see how to manage company members and their roles.

## Employees

To add an employee to your company, click the `+` button at the top of the list.
![company_employee](./assets/img/company_employee.png)

Fill out the form with the required information, then click the green save button at the bottom right of the dialog window.
![company_employee_add](./assets/img/company_employee_add.png)

You will see the new employee appear in the company employee list with a small link symbol. This symbol indicates that the employee is not linked to a user account.
![company_employee_added](./assets/img/company_employee_added.png)

By clicking this symbol, you can create an invitation code to give to the user.
![company_employee_link](./assets/img/company_employee_link.png)
![company_employee_link_code](./assets/img/company_employee_link_code.png)

The user will then enter this invitation code as explained in the [Register](./register.en.md) section.

!!!note
    To invite the employee and allow them to create the employee as soon as they enter the invitation code, simply click the `INVITE` button and give the code to the user.

## Roles
Roles contain permissions, which allow actions to be performed in the application. By default, a role called `Admin` is created and has full access to the application.

!!! warning Note
    At least one user in the company must have a role with full access. The application will not allow role modifications if this condition is not met.

![company_role](./assets/img/company_role.png)

### Assign roles

Once a user is selected in the left list, you can modify the roles assigned to them by selecting roles in the right list.

!!! note
    Role details can be viewed by clicking the small ![company_role_information](./assets/img/company_role_information.png) next to the role name.

### Create a role

To create a role, click the `+` button at the top of the roles list.

![company_role_create](./assets/img/company_role_create.png)

Enter a name for the role, then you have two options:

1. Create a role with full access by checking the `Full access` box.
2. Create a role with custom permissions by unchecking the `Full access` box and selecting permissions from the list.

In the second case, we will create a `Human Resources` role with access to employee management.

![company_role_create_rh](./assets/img/company_role_create_rh.png)

Once this role is created, we will assign it to a user, in our case, user `Alice`.

![company_role_assign](./assets/img/company_role_assign.png)

!!! warning Attention
    Don't forget to click the green save button at the bottom right of the window to save changes. Otherwise, selections will not be applied.

Here is what user `Alice` sees in her interface after refreshing the page.

![company_role_assigned_view_by_alice](./assets/img/company_role_assigned_view_by_alice.png)

Alice can see the list of company employees but does not have access to roles or permissions. She cannot modify other users' roles.
