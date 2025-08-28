### MDN Test Your skills: Other controls
Recovered from the [Internet Archive's Wayback Machine](https://web.archive.org/web/20250302143206/https://developer.mozilla.org/en-US/docs/Learn_web_development/Extensions/Forms/Test_your_skills:_Other_controls).

# Other controls 1
In our first "other controls" assessment, we'll get you to create a multi-line text input.

1. Create a basic multi-line text input.
2. Associate it semantically with the provided "Comment" label.
3. Give the input 35 columns, and 10 rows of space in which to add comments.
4. Give the comments a maximum length of 100 characters.

To create the input, update the HTML code in the editor below:

<img width="792" height="243" alt="image" src="https://github.com/user-attachments/assets/573446a2-2103-443f-9eae-eee5cabbcf03" />

```html
<form>
  <h2>Enter your comment</h2>
  <ul>
    <li>
      <label for="name">Name:</label>
      <input type="text" name="name" id="name">
    </li>
    <li>
      <label for="comment">Comment:</label>
      <!-- add your input here  -->
    </li>
    <li>
      <button>Submit comment</button>
    </li>
  </ul>
</form>
```

# Other controls 2
Now it's time to have a go at implementing a drop-down select menu, to allow a user to pick their favorite food from the choices provided.

1. Create your basic select box structure.
2. Associate it semantically with the provided "food" label.
3. Inside the list, split the choices up into 2 subgroups — "mains" and "snacks".

To create the menu, update the HTML code in the editor below:

<img width="795" height="159" alt="image" src="https://github.com/user-attachments/assets/9c1f34f9-ce65-4b99-ac20-33711c50d013" />

```html
<form>
  <ul>
    <li>
      <label for="food">Pick your favorite food:</label>

          Salad
          Curry
          Pizza
          Fajitas

          Biscuits
          Crisps
          Fruit
          Breadsticks

    </li>
    <li>
      <button>Submit choice</button>
    </li>
  </ul>
</form>    
```
