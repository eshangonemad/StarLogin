# StarLogin
StarLogin is a user-friendly and versatile login interface designed to streamline the authentication process for your webapp. With its straightforward implementation and robust API, StarLogin offers a hassle-free solution for developers and users alike.

Want to implement StarLogin into your webapp? we have provided an implementation section to do so.

# Implementation

Here we will be focusing on HTML CSS and JS implementation.

Step 1)
Import the StarLogin script

     <script src='https://starlogin.eshanaditya.repl.co/site.script.starlogin.js'></script>
This code imports the script that recieves the user details (currently Email) after StarLogin Authentication.

Step 2)
Create Button

    <button onclick='InitLogin()'>StarKloud Login</login>

 Step 3)
 Handle user email
 

    alert(AUTH_EMAIL) 
Note that the AUTH_EMAIL variable is defined by the Login script

**Your User is Successfully Authenticated through StarLogin**
## How to launch StarLogin Window

To launch the StarLogin authentication window you must run the InitLogin() command in JavaScript

**Example (Html)**

    <button onclick='InitLogin'>StarLogin</button>

when the button is clicked :

**Output**
![StarLogin Page Launch When Button Clicked](https://starlogin.eshanaditya.repl.co/Brand_Resource/login.png)

