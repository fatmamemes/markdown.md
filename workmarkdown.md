
# User Managment İnterface

Please prepare the Uİ for the user managment screen with te requirments discribed below.

## Compomnets

The screen should have three main compomnets

- A table  in the left half of the screen that will display a list of all the users
- A form in the right half of the screen with the required fields to add or edit a user
- A header in the top of the page that contains one button to add a new user and one button to save the form and one checkbox to hide the disabled user in the list.

###  The Table Compomnet
          
-  A table  in the left half of the screen.
| ID | User Name    | Email                 |Enabel       |
| :- | :------------| :---------------------| :-----------|
| 1  | admin user   | admin@piworks.net     | true        |    
| 2  | test user    | testuser@piworks.net  | true        | 


-  A  form in the right half of the screen ,

|  User Name :      |`-->[HTML cod]:  will be input text` <input type="text" id="username" name="username"><br> 
| :-----------:     |:-                                                                                                                                                     |
| Display Name:     |`-->[HTML cod]: will be input text` <input type="text" id="displayname" name="displayname"><br>  
| Phone:            |`-->[HTML cod]: will be Input Type Tel` <input type="tel" id="phone" name="phone" placeholder="123-45-678" pattern="[0-9]{3}-[0-9]{2}-[0-9]{3}" required><br><br>
| Email:            |`-->[HTML cod]: will be Input Type Email` <input type="email" id="email" name="email"> 
| User Roles:       |             
  Enabeled
        

### Header İn The Top of The Page

- At the top of the page there should be an option to add new user, hide Disabled User, and save User.

 The user add table must be from the label column and the input type column,
and enabeled button of type boolean ,
And the input type for the user roles label: Multiple options in the html.


  
[![](https://img.shields.io/badge/-+New_user-blue.svg)](https://choosealicense.com/licenses/mit/)  
- [x] hide Disabled User 

[![](https://img.shields.io/badge/-Save_user-blue.svg)](https://choosealicense.com/licenses/mit/)

##  Color Discribtion

- **The header of the table**: on the right of the page should be bright blue, 
- **The row** where you add a new user should be light blue.