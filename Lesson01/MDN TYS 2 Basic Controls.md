### MDN Test Your skills: Basic controls
Recovered from the [Internet Archive's Wayback Machine](https://web.archive.org/web/20250302145836/https://developer.mozilla.org/en-US/docs/Learn_web_development/Extensions/Forms/Test_your_skills:_Basic_controls).

# Basic controls 1
This task starts you off nice and gently by asking you to create two <input> elements, for a user's ID and password, along with a submit button.

Create appropriate inputs for user ID and password.
You should also associate them with their text labels semantically.
Create a submit button inside the remaining list item, with button text of "Log in".
Try updating the live code below to recreate the finished example:

<img width="793" height="156" alt="image" src="https://github.com/user-attachments/assets/e2bf7258-b33f-4a7e-ba13-d7d03afab21b" />

```html
<form>
  <ul>
    <li>
      User ID

    </li>
    <li>
      Password

    </li>
    <li>

    </li>
  </ul>
</form>
```

# Basic controls 3
The next task requires you to create working sets of checkboxes and radio buttons, from the provided text labels.

Turn the first `<fieldset>`'s contents into a set of radio buttons — you should only be able to select one pony character at once.
Make it so that the first radio button is selected upon page load.
Turn the second `<fieldset>`'s content into a set of checkboxes.
Add a couple more hotdog choices of your own.
Try updating the live code below to recreate the finished example:

<img width="793" height="378" alt="image" src="https://github.com/user-attachments/assets/0c2793fa-94fa-4ead-9013-f096afda6e4a" />

```html
<form>
        <fieldset>
          <legend>Who is your favorite pony?</legend>
          <ul>
            <li>
              <label for="pinkie">Pinkie Pie</label>

            </li>
            <li>
              <label for="rainbow">Rainbow Dash</label>

            </li>
            <li>
              <label for="twilight">Twilight Sparkle</label>

            </li>
          </ul>
        </fieldset>
        <fieldset>
          <legend>Hotdog preferences</legend>
          <ul>
            <li>
              <label for="vegan">Vegan</label>

            </li>
            <li>
              <label for="onions">Onions</label>

            </li>
          </ul>
        </fieldset>
        <button>Submit</button>
      </form>
```

# Basic controls 3
The final task in this set requires you to create a file picker.

Create a basic file picker.
Allow the user to pick multiple files at once.
Allow the file picker to accept JPG and PNG images only.
Try updating the live code below to recreate the finished example:

<img width="793" height="127" alt="image" src="https://github.com/user-attachments/assets/a5a96bc6-b9a6-492f-b86c-99a62893931d" />

<form>
    <ul>
      <li>
        <label for="gallery-img">Choose gallery images to upload</label>

      </li>
    </ul>
  <button>Submit</button>
</form>
