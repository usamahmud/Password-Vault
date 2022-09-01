# Password Vault #
A simple program to manage a users passwords securely.



## Features ##
  - Graphical user interface
  - Master password requried to enter the vault
  - Storing login credentials for different softwares
  - Reading login credentials after inputting software name
  - Automatic encrypting/decrypting of credentials using a Vigenere cipher
  - Password strength calculator
  - Password generator



## Login Screen ##

This login screen is displayed when the program is run. The master password is required to access the password vault. 

![login_screen](https://user-images.githubusercontent.com/112635095/188004975-d857623a-5bc5-48f3-b9e5-aa7ee8adb5fb.png)

If the program is being run for the first time (i.e. the master password text file does not exist), the user will need to create a master password.

![create_master_password](https://user-images.githubusercontent.com/112635095/188004973-a2419482-20ed-49ad-a81a-1f120ece33d1.png)

### Password Strength Checker ###

The user can check the strength of an entered password. The program evaluates the complexity of the password based on a simple algorithm.

![password_strength_checker](https://user-images.githubusercontent.com/112635095/188004971-820b149f-3dbe-48e3-bf57-c72f84ced604.png)

### Password Vault Entries ###

Once the user enters the master password, they have entered the password vault. The user will now be able to add and retrieve entries to and from the vault.

The user can use the random password generator to generate a password, which can be copied to the system clipboard.

![generate_random_password](https://user-images.githubusercontent.com/112635095/188004969-52e9f909-875b-4110-9337-0d2fbb0bf3da.png)

In order to add an entry to vault, the user will need to enter the software name, a username, and a password, which can be copied from the random password generator.

![new_password_entry](https://user-images.githubusercontent.com/112635095/188004977-a1322d8b-409e-4bde-bbaf-c180bb5aa54c.png)

The user can also retrieve credentials from the password vault by entering the name of the software. If the name of the software exists in the vault, the username and password will be displayed. The user will have the option of copying the retrieved password to the system clipboard.

![retrieve_password_entry](https://user-images.githubusercontent.com/112635095/188004979-546df3d9-95cd-402e-b8e5-252c272c7f98.png)

