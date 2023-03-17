# SIKM-TODO List

*Afiq Akram - FE5144619*

Berikut ini *pseudocode* dari TODO List yang telah saya buat.

```
Start
FUNCTION register(username, password):
    IF username is not empty AND password is not empty:
        IF username is not taken:
            SAVE username and password to database
            RETURN "Registration successful"
        ELSE:
            RETURN "Username is already taken"
    ELSE:
        RETURN "Username and password cannot be empty"

FUNCTION login(username, password):
    IF username and password match database record:
        RETURN "Login successful"
    ELSE:
        RETURN "Incorrect username or password"
Initialize task list

Loop until user exits:
   Display menu:
      - Add task
      - View tasks
      - Complete task
      - Exit

   Get user input

   If input is "Add task":
      Get task description from user
      Add task to task list

   If input is "View tasks":
      Display all tasks in task list

   If input is "Complete task":
      Get task number from user
      Mark task as completed in task list

   If input is "Exit":
      Exit loop

End
```
