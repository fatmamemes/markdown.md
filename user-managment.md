
# User Managment İnterface

Please prepare the UI for the user managment screen with the requirments discribed below.

## Compomnets

The screen should have three main compomnets

- A table  in the left half of the screen that will display a list of all the users
- A form in the right half of the screen with the required fields to add or edit a user
- A header in the top of the page that contains one button to add a new user and one button to save the form and one checkbox to hide the disabled user in the list.

###  The Table Compomnet
          
A table  in the left half of the screen.

| ID⇳| User Name ⇳  | Email                ⇳|Enabel      ⇳|
| :- | :------------| :---------------------| :-----------|
| 1  | admin user   | admin@piworks.net     | true        |    
| 2  | test user    | testuser@piworks.net  | true        | 

All columns should have arrow icon with a funnel icon (referring to filtering ability), to sort the table ascendant/descendant by a specific column.
###  The Form Compomnet
A  form in the right half of the screen, that should be in a "label: field" format.

The form should have a full width title with light gray background with a text "New User".

Approximate Example:

```
New User
```
|  User Name :      |   | 
| :-----------:     |:-:|                                                                                                                                                 |
| Display Name:     |   | 
| Phone:            |   | 
| Email:            |   |
| User Roles:       |   |             
| Enabeled:         |   |       

- The User Name, Display Name, Phone and Email should be normal input fields of the suitable type.
- The User Roles should be a select box field.
- The enabled field should be a checkbox.

Please note that the form should not be in a table, and for sure without a border, the example above is only approximate and for explanation purposes.

### The Header Compomnet
At the top of the page there should be an button to add new user, an option to hide disabled users, and a button to save the form.

Approximate Example:

[![](https://img.shields.io/badge/-+New_user-blue.svg)]()  
- [x] hide Disabled User 
[![](https://img.shields.io/badge/-Save_user-blue.svg)]()

##  Color Description

- The buttons: Bright blue (as in the example)
- **The header of the table**: Bright blue
- **The row** Line by line, white & Light blue