User Interface Specification Document for User Creation Admin Panel:

Overview:
We are creating a user creation interface admin panel for our company.
The purpose of this panel is to allow us to easily manage our user accounts by creating new accounts, updating existing accounts, and deactivating inactive accounts. There are two sections. And those sections must include the things below.

Scheme:

```
User Creation Admin Panel
|
|___  Header Section
|     |
|     |___ Create User Button
|     |___ Hide Disabled Users Button
|     |___ Save User Button
|
|___ Main Content Section
      |
      |___  User Database
      |     |
      |     |___ ID
      |     |___ User Name
      |     |___ Email
      |     |___ Enabled Status
      |
      |___  New User Creation Panel
            |
            |___ Username
            |___ Display Name
            |___ Phone
            |___ Email
            |___ User Roles
            |___ Enabled
```

1 - Header Section:

1.1 - Create User Button: This button will be located in the left of header section. When clicked, it will open the panel to create a new user.
1.2 - Hide Disabled Users Button: This button will be located in right of the "Create User Button" in header section. When clicked, it will toggle the display of disabled users in the user database.
1.3 - Save User Button: This button will be located in the right of header section. When clicked, it must save the user.


2 - Main Content Section:

2.1 - User Database: The user database will be displayed on the left side of the main content section. It will show a list of all users in the system, along with their ID, username, email address, and enabled status.
2.2 - New User Creation Panel: When the Create User Button is clicked or a when a previously created user is pressed in the database panel, a new panel will open on the right side of the main content section. This panel will allow us to enter the details of the new user.

New User Creation Panel:
The new user creation panel will include the following fields:

2.2.1 - Username: This field is of text type and will be saved for database.
2.2.2 - Display Name: This field is of text type.
2.2.3 - Phone: This field is of text type and must be controlled whether the number written can be a real number
2.2.4 - Email: This field is of text type and must be controlled whether the email address written is a real email address
2.2.5 - User Roles: This field can be set to one of three options: Guest, Admin, or Super Admin.
2.2.6 - Enabled: This field is required and will determine whether the user account is enabled or disabled.
