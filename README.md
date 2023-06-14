# StarLogin
StarLogin is a user-friendly and versatile login interface designed to streamline the authentication process for your web app. With its straightforward implementation and robust API, StarLogin offers a hassle-free solution for developers and users alike.

Want to implement StarLogin into your web app? we have provided an implementation section to do so.

# Implementation

Here we will be focusing on HTML CSS and JS implementation.

Step 1)
Import the StarLogin script

     <script src='https://starlogin.eshanaditya.repl.co/site.script.starlogin.js'></script>
This code imports the script that receives the user details (currently Email) after StarLogin Authentication.

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

##StarLogin Official Button
	You can use the official StarLogin Button to ease your development experience. We have documented how to do so down below.

Step 1)
Import the StarLogin Button CSS (Currently for Light Mode Only)

    <link rel="stylesheet" type="text/css" href="https://starlogin.eshanaditya.repl.co/starlogin.button.css" />

Step 2)
Place the Pre-Styled Button using the code below

    
    <button class="starloginwhite" onclick='InitLogin()'>
      <div class="starkloud-logo"></div>
      <span class="button-text">Sign in with StarKloud</span>  
    </button>
When code is run:
![enter image description here](https://starlogin.eshanaditya.repl.co/Brand_Resource/button.light.png)
Note:  The button glows StarKloud Blue when hovered on

