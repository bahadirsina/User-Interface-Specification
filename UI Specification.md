> # User-Interface-Specification

> ## Requirements
> The user management screen should allow administrators to perform Create and Read operations on user accounts. Specific requirements include:
> - Can create new users.
> - The created users can be displayed in a table along with their details.
> - Disabled users of new added users can be hidden. It will be good for filtering.

> ## UI Components
> The user management screen consists of the following components:

> 1. User List: View existing user accounts.
> 2. New User Button: The button where the information that must be entered for a new user is displayed.
> 3. Hide Disabled User Checkbox: Option to hide disabled users.
> 4. Save User Button: The button where the user whose relevant information is entered is saved and added to the table.
> 5. New User Form: A form used to add user details, including fields. This fields:
>   - **Username:** Users' names are written into the textfiel
>   - **Display Name:** The name of the users that you want to display on the screen is written into the textfield.
>   - **Phone:** The phone number of the users is written into the textfield.
>   - **Email:** Users' e-mail addresses are written into the textfield.
>   - **User Roles:** The roles the users have (Guest, Admin, SuperAdmin) are selected from the combobox.
>   - **Enabled:** Whether users are active or inactive (access restricted) is marked via the checkbox.

> ## Behaviour of the Page
> - At startup, the user management screen displays a list of existing user accounts with their information (ID, User Name, Email, Enabled) in the table.
> - When you click on the **New User** button, the user form opens on the right side of the screen to add a new user account.
> - When the **Hide Disabled User** Checkbox is checked, users whose Enabled property is false in the user list on the left will be hidden.
> - After clicking on the New User button and filling in the information in the New User form on the right, the user is registered to the system with the **Save User button** that appears on the top right.

> ## Initial Display
After loading the user management screen, the list table of existing user accounts and information, the New User button and the Hide Disabled User option are displayed at the top.
