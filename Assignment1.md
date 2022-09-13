# Assignment 1
## Improve the feature
### List the possible test scenarios based on sign-in page
#### Email
- prefix validation (does it exist in db)
- top level domain validation
- Verify email id can contain an IP address in square bracket.
- Verify email id can contain quotes.
- Verify email id can contain digits.
- Verify email id can contain an underscore.
- Verify top-level domain can contain a dot.
- Verify email id with a dash is considered valid.


#### Password
- String validation (uppercase, lowercase, numbers, symbols)
- Verify if the data in password field is either visible as asterisk or bullet signs
- Verify if a user is able to login with a new password only after he/she has changed the password.
- Check error message is displayed or not when the user click submits button without entering any value in the password field.  
- Check based on the inputted password text it should display the progress bar. (Weak, Medium & Strong)
- Check if the password view functionality is available so that the user can see the entered password. (Eye visible on the right side of the password text box)
- Check on the Click eye icon entered password should be visible in a readable format.
- Check the asterisk symbol for the password field if it is a mandatory field.
- Check the password min and max lenght
- Check if password field is empty 
- Check if password is hashed 

#### Both
- non-ascii characters
- Verify if a user will be able to login with a valid username and valid password. (need test case for each)
- Verify if a user cannot login with a valid username and an invalid password.
- Verify the messages for invalid login.
- Verify the time taken to log in with a valid username and password.
- Check for injections attacks (XSS and SQL injection)
- Check if the  form is able to submit if any of the fields is empty 


### Suggest how to improve QA and UI
- Having multiple sign in option
- Verify if the font, text color, and color coding of the Login page is as per the standard.
- Verify if this check box is not selected by default.
- If the user has signed up with Facebook or social media, verify that the user can log in with those credentials or not.
- Provide feedback during and after interactions which Indicate Whether an Interaction Will Be Successful (ex: green color ping).
- Password field shouldn't be optional
- Verify the ‘Forgot Password’ functionality
- When the user types the password it gets encrypted

[SLIDES ARE HERE](https://docs.google.com/presentation/d/1XdLUKa3FznYbQFPrWnkR2NUznxzb2erJXsdfAEIHJw4/edit?usp=sharing).
