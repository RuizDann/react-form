# React Registration Form

I created a registration form where users are able to sign up.

## The form is provided in an uncontrolled fashion and contains the following inputs:
- First Name
- Last Name
- Email
- Password
- Role

## The rules for the form to be valid are as follows:
- The first name cannot be empty.
- The email must be a valid email address and can't be empty. A function called `validateEmail` has already been provided for you to check if the email is valid. It returns `true` if the email is valid, otherwise `false` is returned.
- The password must be at least 8 characters long.
- The role must be either individual or business.
- The form shows an error message if the password is less than 8 characters long.

Lastly, the form clears after a successful submission.
