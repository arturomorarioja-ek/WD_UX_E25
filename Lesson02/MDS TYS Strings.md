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
