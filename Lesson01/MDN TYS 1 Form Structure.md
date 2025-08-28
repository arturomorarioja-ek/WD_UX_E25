# Form structure 1
In this task we want you to structure the provided form features:

1. Separate out the first two and second two form fields into two distinct containers, each with a descriptive legend (use "Personal details" for the first two, and "Comment information" for the second two).
2. Mark up each text label with an appropriate element so that it is semantically associated with its respective form field.
3. Add a suitable set of structural elements around the label/field pairs to separate them out.

<img width="799" height="306" alt="image" src="https://github.com/user-attachments/assets/95d77a8c-b50d-4e0a-8959-fcb90530d821" />

```html
<form>
  Name:
  <input type="text" id="name" name="name">

  Age:
  <input type="number" id="age" name="age">

  Comment:
  <input type="text" id="comment" name="comment">

  Email:
  <input type="email" id="email" name="email">
</form>
```
