**The Password Generator** 🔏

*WELCOME!*

This project was designed as a homework assignment for UWA's coding bootcamp.

HTML and CSS and Javascript documents create a random password generator. This application emphasizes the use of Javascript to generate a random, secure password for the user.

This project has the following features:

A Generate button
This will send the user a series of prompts and confirms
After user data is collected, a random password will be generated using Javascrip

A Textarea
This textarea will display the users password once it has been generated

A Copy button
This will copy the generated password to the user's devices clipboard

**SCREENSHOTS**

1) The user will be prompted to choose from the following password criteria: 8 and 128 characters
![alt text](https://github.com/hergemony/Password-Generator/blob/main/assets/Screen%20Shot%202022-03-03%20at%205.31.11%20pm.png?raw=true)

2)The user will recieve a confirm for:
Password containing special characters, numbers, and uppercase
Either 4 variables individual ones, or 3 with toLowerCase to Uppercase conversion
This will need to randomly generate a selection or randomly select array data, so math.random and math.floor will need to be used.
![alt text](https://github.com/hergemony/Password-Generator/blob/main/assets/Screen%20Shot%202022-03-03%20at%205.31.28%20pm.png?raw=true)

3) The application should validate user input and ensure that at least one character type is selected.
If, else if statement
![alt text](https://github.com/hergemony/Password-Generator/blob/main/assets/Screen%20Shot%202022-03-03%20at%205.31.33%20pm.png?raw=true)


4) Once all prompts are answered, the user will be presented with a password matching the answered prompts. Displaying the generated password in an alert is acceptable, but attempt to write the password to the page instead.
Event listener will determine the password output with function to populate the value into the test area.

![alt text](https://github.com/hergemony/Password-Generator/blob/main/assets/Screen%20Shot%202022-03-03%20at%205.31.40%20pm.png?raw=true)


5) The user should also have the option to click a button to copy the password to their clipboard.
Copy execCommand in event listener
![alt text](https://github.com/hergemony/Password-Generator/blob/main/assets/Screen%20Shot%202022-03-03%20at%205.31.45%20pm.png?raw=true)


**Javascript features**
- Variable declaration area
- An event listener (onclick) called generatePassword 
- A prompt for the user to input a number between 8-128
- This variable is changed to an integer using ParseInt()
- This will validate that the input is a number within range, or is a number
- This then uses the input to determine the types (or choices) or letters of characters used, using an if statement
- This then assigns values to the variables using arrays for character, number or alphabet
- Another variable is created to concatenate the above variables
- A 'for loop' will loop through the enter prompt until it reaches the number entered by user.
- A password variable takes the value from the 'for loop', and converts it to a string
- The string value then populates into the text area for the user using a UserInput function.
- An event listener (onclick) has also been created for the copy to clipboard feauture called copyPassword.

**Github Repository Features**
One HTML Pages (Index.html - Contains basic user input items and buttons with divs and ids)
Two CSS Pages
- Styles.css
- Reset.css
Contains centering and styling for html user input features
Contains media queries
One Javascript Page * Contains: * Variables, including arrays and value placeholders * Two event listeners * Two if/else if statements * One function outside of first event listener
Images of screenshots to show example of 'The Password Generator' in action

*Thank you for viewing!*

Github Profile Link => https://github.com/hergemony

Deployed Application Link => https://hergemony.github.io/Password-Generator/

❤ Hergemony Digital Services 2022 ❤


Acknowledgments:
The Teachers, Tutors and Team @ UWA CODING BOOTCAMP