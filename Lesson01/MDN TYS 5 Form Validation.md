### MDN Test Your skills: Form structure
Recovered from the [Internet Archive's Wayback Machine](https://web.archive.org/web/20250302135047/https://developer.mozilla.org/en-US/docs/Learn_web_development/Extensions/Forms/Test_your_skills:_Form_validation).

# Form validation 1
In this task, we are providing you with a simple support query form, and we want you to add some validation features to it:

1. Make all of the input fields mandatory to complete before the form can be submitted.
2. Change the type of the "Email address" and "Phone number" fields to make the browser apply some more specific validation suitable for the data being asked for.
3. Give the "User name" field a required length of between 5 and 20 characters, the "Phone number" field a maximum length of 15 characters, and the "Comment" field a maximum length of 200 characters.

Try submitting your form — it should refuse to submit until the above constraints are followed, and give suitable error messages. To help, you might want to consider adding some simple CSS to show when a form field is valid or invalid.

# Form validation 2
Now we want you to take the same form you saw in the previous task (use your previous answer if you want to), and add some more specific pattern validation to the first three fields using regular expressions.

1. All of the user names in our application consist of a single letter, followed by a dot, followed by three or more letters or numbers. All letters should be lowercase.
2. All of the email addresses for our users consist of one or more letters (lower or upper case) or numbers, followed by "@bigcorp.eu".
3. Remove the length validation from the phone number field if it is present, and set it so that it accepts 10 digits — either 10 digits in a row, or a pattern of three digits, three digits, then four digits, separated by either spaces, dashes, or dots.

# Form validation 3
In our final task for this set, we are providing you with a similar example to what you saw in the accompanying article — an email address entry input. We would like you to use the constraint validation API, plus some form validation attributes, to program some custom error messages.

1. Make the input mandatory to fill in, and give it a minimum length of 10 characters.
2. Add an event listener that checks whether the inputted value is an email address, and whether it is long enough. If it doesn't look like an email address or is too short, provide the user with appropriate custom error messages.
