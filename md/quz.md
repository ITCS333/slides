# HTML Question

Use the following information to construct an HMTL page:
- The Page has to have an `html`, `head`, and `body` tags.
- Set the `title` of the page to `"MY PAGE"`.
- Inside the `body` tag, add a `mian` tag. set its `class` attribute to `grid`.
- Add an `article` tag nested inside the `main` tag, and set its `id` attribute to `a1`.

Your code goes after this line:
```html
<!DOCTYPE html>
```

# CSS Questions

Create a CSS stylesheet that meets the following requirements:

- Target the `body` element and set its `font-family` to `Arial, sans-serif`.

- Target a class called `container` with the following properties:
    - `max-width` of `1200` pixels
    - `margin` set to `auto`
    - `padding` of `20` pixels

- Style all `h1` elements within the `container` class to have:
    - `color` of `#333333`
    - `font-size` of `24` pixels
    - `text-align` `center`

```css
/* Start your CSS here */
```

Consider the following HTML and CSS code. Which styles will be applied to the paragraph with the class "highlight" inside the div with id "content"? Select all that apply.
```css
p {
    color: blue;
    font-size: 16px;
}

.highlight {
    color: red;
    font-weight: bold;
}

#content p {
    font-size: 18px;
    font-style: italic;
}

div p.highlight {
    text-decoration: underline;
}

p.highlight {
    color: green;
}
```
```html
<div id="content">
    <p class="highlight">This is a highlighted paragraph.</p>
</div>
```

Options:
- A) color: blue;
- B) color: red;
- C) color: green;
- D) font-size: 16px;
- E) font-size: 18px;
- F) font-weight: bold;
- G) font-style: italic;
- H) text-decoration: underline;

# PHP Question

Define an array called `products` with at least 3 items. Each item should have keys for `name`, `price`, and `quantity`.

```php
<?php
// Define the products array
```

Create a function called `calculateTotal` that takes the `products` array as an argument and returns the total value of all products (price * quantity).

```php
<?php
// Function to calculate total value
```

Use a loop to display each product's name and price in an HTML unordered list.
The resulting HTML should be similar to:
```html
<ul>
    <li>Product1 Name - 10 BD</li>
    <li>Product2 Name - 12 BD</li>
    <li>Product3 Name - 5 BD</li>
</ul>
```

Display the total value of all products in a paragraph using the `calculateTotal` function.
The resulting HTML should be similar to:
```html
<p>Total value of all products: 27 BD</p>
```

The `isset` function in PHP is used to check if a value is `null` or not. Use it in an `if` statement to make sure that the product name and price are not null. Write only the `if` statement.

```php
// Write only an if statement
```