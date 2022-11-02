# Module3challenge - Kyle Albright


# User Story
```
AS AN employee with access to sensitive data
I WANT to randomly generate a password that meets certain criteria
SO THAT I can create a strong password that provides greater security

```


## Acceptance Criteria

```
GIVEN I need a new, secure password
WHEN I click the button to generate a password
THEN I am presented with a series of prompts for password criteria
WHEN prompted for password criteria
THEN I select which criteria to include in the password
WHEN prompted for the length of the password
THEN I choose a length of at least 8 characters and no more than 128 characters
WHEN asked for character types to include in the password
THEN I confirm whether or not to include lowercase, uppercase, numeric, and/or special characters
WHEN I answer each prompt
THEN my input should be validated and at least one character type should be selected
WHEN all prompts are answered
THEN a password is generated that matches the selected criteria
WHEN the password is generated
THEN the password is either displayed in an alert or written to the page
```

### Usage

    When the user clicks generate password, it will prompt them to pick a number from 8-128. If the user enters an invalid number, 
It will display what they chose and ask them to try again. If user picks a valid number, it will display their choice and then proceed
to the next step. 

The next four steps will take them through choices of characters. They can choose lowerCase, upperCase, numbers, and special characters. 
After a choice has been made, it will notify the user what they chose. If the user did not choose any of the options, the alert window will shut down, 
and it will prompt to click generate password again; restarting from the beginning.

If all fields have been filled out correctly, the password will be generated according to the users specifications.




### Resources

* w3schools.com
* stackoverflow.com
* developer.mozilla.org/en-US/




###



![Screenshot (8)](https://user-images.githubusercontent.com/110487869/192423384-710cd1f6-2ed5-4f98-8ae8-fc812572456f.png)

![Screenshot (9)](https://user-images.githubusercontent.com/110487869/192423429-39d5d270-3c51-4031-8410-769b90407f74.png)

![Screenshot (10)](https://user-images.githubusercontent.com/110487869/192423438-ca33f08d-a5f8-4a67-92ab-270ae12e1715.png)
