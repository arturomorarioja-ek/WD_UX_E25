### MDN Test Your skills: HTML5 controls
Recovered from the [Internet Archive's Wayback Machine](https://web.archive.org/web/20250302135053/https://developer.mozilla.org/en-US/docs/Learn_web_development/Extensions/Forms/Test_your_skills:_HTML5_controls).

# HTML controls 1
First, let's explore some input types. Create appropriate inputs for a user to update their details for:

1. Email
2. Website
3. Phone number
4. Favorite color

Try updating the live code below to recreate the finished example:

<img width="794" height="259" alt="image" src="https://github.com/user-attachments/assets/64ee9796-8d1b-49d0-a2a6-018f3764a310" />

```html
<form>
  <h2>Edit your preferences</h2>
  <ul>
    <li>
      <label for="e-mail">Email</label>

    </li>
    <li>
      <label for="website">Website</label>

    </li>
    <li>
      <label for="phone">Phone number</label>

    </li>
    <li>
      <label for="fave-color">Favorite color</label>

    </li>
    <li>
      <button>Update preferences</button>
    </li>
  </ul>
</form>    
```

# HTML controls 2
Next, we want you to implement a slider control to allow the user to choose a maximum number of people to invite to their party.

1. Implement a basic slider control to go along with the provided label.
2. Give it a minimum value of 1, maximum value of 30, initial value of 10 and element `id` of `max-invite`.
3. Create a corresponding output element to put the current value of the slider into. Give it a class of `invite-output`, and semantically associate it with the input. If you do this correctly, the JavaScript included on the page will automatically update the output value when the slider is moved.

Try updating the live code below to recreate the finished example:

<img width="796" height="128" alt="image" src="https://github.com/user-attachments/assets/9633787e-6364-4117-9a0a-55d4040849e0" />

HTML code:
```html
<form>
  <ul>
    <li>
      <label for="max-invite">Select maximum number of invitations</label>
      
    </li>
    <li>
      <button>Submit</button>
    </li>
  </ul>
</form>
```

JavaScript code:
```javascript
const invite = document.querySelector('#max-invite');
const output = document.querySelector('.invite-output');

output.textContent = invite.value;

invite.addEventListener('input', function() {
  output.textContent = invite.value;
});
```

If you are creating the project in a standalone repo (not in CodePen or similar), you need to include the JavaScript code in a file `js/script.js` and link it by including the following line in the `<head>` of your HTML file:
```html
<script src="js/script.js" type="module"></script>
```
