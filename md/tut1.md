---
title: "Tutorial: Building a Simple One-Page Bookshop Gallery"
author: "Abdulla Ebrahim Subah"
institute: "University of Bahrain"
topic: "Tutorial"
fonttheme: "professionalfonts"
fontsize: 10pt
linkstyle: bold
dpi: 300
date: \today{}
lang: en-US
header-includes:
  - \usepackage{setspace}
  - \setstretch{1.5}
---

# Objective

The goal of this tutorial is to create a simple one-page website for a fictional bookshop gallery. The website will showcase a few book titles with their cover images, descriptions, and prices. You will use **HTML** for structure and **CSS** for styling, with the help of the **Picocss** framework. This exercise allows beginners to explore various HTML tags, CSS properties, and the use of an external CSS framework.

# Project Overview

You are tasked with building a one-page website for a fictional bookshop called **"Al Warraq"**. The page will display a selection of books, each with a title, cover image, short description, and price. Additionally, the page should have a simple header, navigation bar, and footer.

The design will be responsive, meaning it should look good on both desktop and mobile devices. You will use the **Picocss** framework to simplify styling and ensure consistency.

# Features to Implement

1. **Header & Navigation:**
   - A header section with the title of the bookshop.
   - A simple navigation bar with links to other sections (e.g., Home, About, Contact).

2. **Bookshop Gallery:**
   - A grid or list displaying books.
   - Each book entry should include:
     - A cover image.
     - A title.
     - A brief description (1-2 sentences).
     - The price.
   - Use semantic HTML tags like `<section>`, `<article>`, and `<figure>` to structure the content.

3. **Footer:**
   - A footer with social media links (e.g., Facebook, Twitter) and contact information.

4. **Responsive Design:**
   - Ensure the layout adapts to both desktop and mobile devices using simple CSS media queries.

5. **Picocss Framework:**
   - Use the **Picocss** framework to provide base styling for your page.
   - You can customize colors, fonts, and spacing using CSS.

\newpage
# Picocss Setup

1. You will use **Picocss** to help with the basic layout and design. Include the Picocss stylesheet in the `<head>` of your HTML document:

```html
<link
  rel="stylesheet"
  href="https://cdn.jsdelivr.net/npm/@picocss/pico@2/css/pico.min.css"
>
```

2. Picocss will already style basic HTML elements, but you can add custom styles to make the website more personalized. For instance, you can customize the header, gallery layout, and footer.

# Section Breakdown

## 1. Header & Navigation

- Create a header with the title **"Al Warraq"**.
- Below the header, create a simple navigation bar with links to *Home*, *About*, and *Contact*. These links won't go anywhere for now (use `#` as the `href`).

### Example HTML structure:

```html
<header>
  <h1>Al Warraq</h1>
  <nav>
    <ul>
      <li><a href="#">Home</a></li>
      <li><a href="#">About</a></li>
      <li><a href="#">Contact</a></li>
    </ul>
  </nav>
</header>
```

## 2. Bookshop Gallery

- Use a `<section>` tag to contain the book gallery.
- For each book, use a `<figure>` element to wrap the book cover image and details.
- Inside the `<figure>`, use a `<figcaption>` to wrap the book’s title.
- Use an `<article>` tag to structure each book's information (title, description, price).

### Example HTML structure:

```html
<section class="book-gallery">
  <article class="book">
    <figure>
      <img src="https://placehold.co/300x400/orange/white?text=The\nBook" alt="Book Cover">
      <figcaption>
        <h2>Book Title</h2>
        <p>A short description of the book goes here.</p>
        <p class="price">$19.99</p>
      </figcaption>
    </figure>
  </article>
  <!-- Add more books similarly -->
</section>
```
\newpage
## 3. Footer

- Create a simple footer with social media links and contact info.
- You can use `<footer>`, and include basic information such as email or phone number.

### Example HTML structure:

```html
<footer>
  <p>Follow us on:</p>
  <ul>
    <li><a href="#">Facebook</a></li>
    <li><a href="#">Twitter</a></li>
    <li><a href="#">Instagram</a></li>
  </ul>
  <p>Contact: info@alwarraq.com</p>
</footer>
```
\newpage
# CSS Styling

While Picocss handles much of the styling, you’ll add your own CSS to make the page unique and responsive.

### Example CSS:

```css
/* Custom styles for Al Warraq */
header {
  text-align: center;
  margin-bottom: 2rem;
}

.book-gallery {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
  gap: 1rem;
}

.book img {
  width: 100%;
  height: auto;
}

.book .price {
  font-weight: bold;
  color: #2a9d8f;
}
```
\newpage
```css
footer {
  text-align: center;
  margin-top: 2rem;
  padding: 1rem 0;
  background-color: #f4f4f9;
}

footer ul {
  list-style: none;
  padding: 0;
}

footer ul li {
  display: inline;
  margin-right: 1rem;
}

@media (max-width: 600px) {
  .book-gallery {
    grid-template-columns: 1fr;
  }
}
```
\newpage
# Requirements Checklist

1. **Header:**
   - Includes the website title.
   - Includes a navigation bar with 3 links.

2. **Bookshop Gallery:**
   - Contains at least 4 books.
   - Each book has a cover image, title, description, and price.

3. **Footer:**
   - Includes social media links and contact details.

4. **Picocss Integration:**
   - Picocss is correctly linked in the `<head>`.

5. **Custom CSS:**
   - Use custom CSS to design the layout, spacing, and font styles.

6. **Responsive Design:**
   - Test the design on both desktop and mobile views.

Happy Hacking!

# Additional Resources

- **Picocss Documentation:** <https://picocss.com>
- **HTML Reference:** <https://developer.mozilla.org/en-US/docs/Web/HTML>
- **CSS Reference:** <https://developer.mozilla.org/en-US/docs/Web/CSS>
