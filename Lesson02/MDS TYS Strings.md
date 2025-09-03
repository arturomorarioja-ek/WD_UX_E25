### MDN Test Your skills: Strings
Recovered from the [Internet Archive's Wayback Machine](https://web.archive.org/web/20250302154934/https://developer.mozilla.org/en-US/docs/Learn_web_development/Core/Scripting/Test_your_skills:_Strings).

# Strings 1
In our first strings task, we start off small. You already have half of a famous quote inside a variable called `quoteStart`; we would like you to:

1. Look up the other half of the quote, and add it to the example inside a variable called `quoteEnd`.
2. Concatenate the two strings together to make a single string containing the complete quote. Save the result inside a variable called `finalQuote`.

You'll find that you get an error at this point. Can you fix the problem with `quoteStart`, so that the full quote displays correctly?

Try updating the JavaScript code below to recreate the finished example:

<img width="631" height="42" alt="Untitled" src="https://github.com/user-attachments/assets/230f5bab-0aa7-4ef1-bdac-cf78018d1dbf" />

HTML code:
```html
<section class="preview">
</section>
```

CSS code:
```css
p {
  color: purple;
  margin: 0.5em 0;
}

* {
  box-sizing: border-box;
}
```

JavaScript code:
```javascript

// Add your code here

const quoteStart = 'Don't judge each day by the harvest you reap ';

// Don't edit the code below here!

section.innerHTML = ' ';
const para1 = document.createElement('p');
para1.textContent = finalQuote;

section.appendChild(para1);
```

# Strings 2
In this task you are provided with two variables, `quote` and `substring`, which contain two strings. We would like you to:

1. Retrieve the length of the quote, and store it in a variable called `quoteLength`.
2. Find the index position where `substring` appears in `quote`, and store that value in a variable called `index`.
3. Use a combination of the variables you have and available string properties/methods to trim down the original quote to "I do not like green eggs and ham.", and store it in a variable called `revisedQuote`.

Try updating the JavaScript code below to recreate the finished example:

<img width="286" height="74" alt="image" src="https://github.com/user-attachments/assets/b1db9ee3-7b77-4d96-bd30-7e896bdcccb9" />

HTML code:
```html
<section class="preview">
</section>
```

CSS code:
```css
p {
  color: purple;
  margin: 0.5em 0;
}

* {
  box-sizing: border-box;
}
```

JavaScript code:
```javascript
const quote = 'I do not like green eggs and ham. I do not like them, Sam-I-Am.';
const substring = 'green eggs and ham';

// Add your code here

// Don't edit the code below here!

section.innerHTML = ' ';
const para1 = document.createElement('p');
para1.textContent = `The quote is ${ quoteLength } characters long.`;
const para2 = document.createElement('p');
para2.textContent = revisedQuote;

section.appendChild(para1);
section.appendChild(para2);    
```

# Strings 3
In the next string task, you are given the same quote that you ended up with in the previous task, but it is somewhat broken! We want you to fix and update it, like so:

1. Change the casing to correct sentence case (all lowercase, except for upper case first letter). Store the new quote in a variable called `fixedQuote`.
2. In `fixedQuote`, replace "green eggs and ham" with another food that you really don't like.
3. There is one more small fix to do — add a period to the end of the quote, and save the final version in a variable called `finalQuote`.

Try updating the live code below to recreate the finished example:

<img width="344" height="74" alt="image" src="https://github.com/user-attachments/assets/faeafb24-d0c9-4ab4-ac5c-004bdb36bf88" />

HTML code:
```html
<section class="preview">
</section>
```

CSS code:
```css
p {
  color: purple;
  margin: 0.5em 0;
}

* {
  box-sizing: border-box;
}
```

JavaScript code:
```javascript
const quote = 'I dO nOT lIke gREen eGgS anD HAM';

// Add your code here

// Don't edit the code below here!

section.innerHTML = ' ';
const para1 = document.createElement('p');
para1.textContent = fixedQuote;
const para2 = document.createElement('p');
para2.textContent = finalQuote;

section.appendChild(para1);
section.appendChild(para2);
```

# Strings 4
In the final string task, we have given you the name of a theorem, two numeric values, and an incomplete string (the bits that need adding are marked with asterisks (`*`)). We want you to change the value of the string as follows:

1. Change it from a regular string literal into a template literal.
2. Replace the four asterisks with four template literal placeholders. These should be:
  i. The name of the theorem.
  ii. The two number values we have.
  iii. The length of the hypotenuse of a right-angled triangle, given that the two other side lengths are the same as the two values we have. You'll need to look up how to calculate this from what you have. Do the calculation inside the placeholder.

Try updating the JavaScript code below to recreate the finished example:

<img width="853" height="63" alt="image" src="https://github.com/user-attachments/assets/c719d347-b111-4dda-84e3-cd8247026298" />

HTML code:
```html
<section class="preview">
</section>
```

CSS code:
```css
p {
  color: purple;
  margin: 0.5em 0;
}

* {
  box-sizing: border-box;
}
```

JavaScript code:
```javascript
const theorem = 'Pythagorean theorem';

const a = 5;
const b = 8;

const myString = 'Using *, we can work out that that if the two shortest sides of a right-angled triangle have lengths of * and *, the length of the hypotenuse is *.';

// Don't edit the code below here!

section.innerHTML = ' ';
const para1 = document.createElement('p');
para1.textContent = myString;

section.appendChild(para1);    
```
