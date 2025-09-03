### MDN Test Your skills: Arrays
Recovered from the [Internet Archive's Wayback Machine](https://web.archive.org/web/20250302142015/https://developer.mozilla.org/en-US/docs/Learn_web_development/Core/Scripting/Test_your_skills:_Arrays).

# Arrays 1
Let's start off with some basic array practice. In this task we'd like you to create an array of three items, stored inside a variable called `myArray`. The items can be anything you want — how about your favorite foods or bands?

Next, modify the first two items in the array using simple bracket notation and assignment. Then add a new item to the beginning of the array.

Try updating the JavaScript code below to recreate the finished example:

<img width="480" height="41" alt="image" src="https://github.com/user-attachments/assets/2dba0df0-1434-4ff0-9f6f-7ee3bfb1c161" />

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

// Don't edit the code below here!

section.innerHTML = ' ';
let para1 = document.createElement('p');
para1.textContent = `Array: ${ myArray }`;

section.appendChild(para1);    
```

# Arrays 2
Now let's move on to another task. Here you are provided with a string to work with. We'd like you to:

1. Convert the string into an array, removing the + characters in the process. Save the result in a variable called `myArray`.
2. Store the length of the array in a variable called `arrayLength`.
3. Store the last item in the array in a variable called `lastItem`.

Try updating the JavaScript code below to recreate the finished example:

<img width="475" height="105" alt="image" src="https://github.com/user-attachments/assets/a2d6d858-0ddf-4d2b-93ce-9c9665403da8" />

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

let myString = 'Ryu+Ken+Chun-Li+Cammy+Guile+Sakura+Sagat+Juri';

// Don't edit the code below here!

section.innerHTML = ' ';
let para1 = document.createElement('p');
para1.textContent = `Array: ${ myArray }`;

let para2 = document.createElement('p');
para2.textContent = `The length of the array is ${ arrayLength }.`;

let para3 = document.createElement('p');
para3.textContent = `The last item in the array is "${ lastItem }".`;

section.appendChild(para1);
section.appendChild(para2);
section.appendChild(para3);    
```

# Arrays 3
For this array task, we provide you with a starting array, and you will work in somewhat the opposite direction. You need to:

1. Remove the last item in the array.
2. Add two new names to the end of the array.
3. Go over each item in the array and add its index number after the name inside parentheses, for example `Ryu (0)`. Note that we don't teach how to do this in the Arrays article, so you'll have to do some research.
4. Finally, join the array items together in a single string called `myString`, with a separator of `"-"`.

Try updating the JavaScript code below to recreate the finished example:

<img width="856" height="39" alt="image" src="https://github.com/user-attachments/assets/1198cb35-abc3-44ce-a0b7-246a5c84efbb" />

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
let myArray = [ "Ryu", "Ken", "Chun-Li", "Cammy", "Guile", "Sakura", "Sagat", "Juri" ];

// Add your code here

// Don't edit the code below here!

section.innerHTML = ' ';

let para1 = document.createElement('p');
para1.textContent = myString;

section.appendChild(para1);    
```

# Arrays 4
For this array task, we provide you with a starting array listing the names of some birds.

1. Find the index of the `"Eagles"` item, and use that to remove the `"Eagles"` item.
2. Make a new array from this one, called `eBirds`, that contains only birds from the original array whose names begin with the letter "E". Note that `startsWith()` is a great way to check whether a string starts with a given character.

If it works, you should see `"Emus,Egrets"` appear in the page.

<img width="126" height="42" alt="image" src="https://github.com/user-attachments/assets/f9fa7102-ff56-43dd-87c9-b32be456ad7b" />

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
const birds = [ "Parrots", "Falcons", "Eagles", "Emus", "Caracaras", "Egrets" ];

// Add your code here

// Don't edit the code below here!

section.innerHTML = ' ';

const para1 = document.createElement('p');
para1.textContent = eBirds;

section.appendChild(para1);    
```
