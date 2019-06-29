# Topic 2 - CSS & HTML

[-> To index](../README.md#title)

## Documentation

- https://developer.mozilla.org/en-US/docs/Learn/CSS

# Exercises

**1) Selectors and properties**

Material:
 - [Selectors](https://developer.mozilla.org/en-US/docs/Learn/CSS/Introduction_to_CSS/Selectors)
 - [CSS3 selectors sheet](https://www.w3.org/TR/selectors-3/)
  
  
  Use the next html file to do the exercies
  ```
  <!doctype html>
  <html lang="en">
    <head>
      <meta charset="utf-8">
      <meta http-equiv="x-ua-compatible" content="ie=edge">
      <title></title>
      <meta name="viewport" content="width=device-width, initial-scale=1, shrink-to-fit=no">
    </head>
    <body>
      <header>

      </header>
        <nav>

        </nav>

        <section>
          <header>

          </header>

          <article>

          </article>

          <footer>

          </footer>
        </section>

        <aside>
        </aside>

      <footer>
      </footer>
    </body>

  </html>
```

1. Learn why is a best-practice to use a reset stylesheet [here](https://meyerweb.com/eric/tools/css/reset/). Then include [normalize.css](http://necolas.github.io/normalize.css/) before linking your style.css.
2. Add background to the header, footer, aside and nav.
3. Add a global font definition (at html element) with a value of 14px, using a font-family you like.
4. Center the header and footer text.

**2) Specificity**
- [Specificity](https://developer.mozilla.org/en-US/docs/Learn/CSS/Introduction_to_CSS/Cascade_and_inheritance#Specificity)

1. Add the following classes to the document created in exercice 1:
    - To ```<header>``` add class .header
    - To ```<footer>``` add class .footer
    - To ```<section>``` add class .content
    - To ```<nav>``` add class .navigation
    - To ```<aside>``` add class .sidebar
