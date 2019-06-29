# Topic 1 - HTML

## Description

HTML (Hypertext Markup Language) **is not a programming language**; it is a *markup language* used to tell your browser how to structure the web pages you visit.
It can be as complicated or as simple as the web developer wishes it to be. HTML consists of a series of elements, which you use to enclose, wrap, or mark up different parts of the content to make it appear or act a certain way.


This topic will be very important to start creating the base of UI programing.

## Goals and knowledge to achieve

Through the rest of this section you will create a basic HTML document. After finishing this section you will:

- Be able to create HTML documents that displays text, images, tables, lists
- Understand how to structure HTML documents, and what the basic building blocks are
- Understand best practices to write valid, accessible, and semantic HTML markup.

## Index

1. [HTML Basics](#html-basic)
2. [Semantic & DOCTYPE](#html-semantic)
3. [W3C Accessibility](#html-a19y)

## Exercises

After this presentation and reading of the HTML documentation, we are ready for fun. It's time to develop, are you ready?

> Is prefered a 'commit' point by point... That way is posible to see the progress and identify the problems easily.

1 - Docs
- [Introduction to HTML](https://developer.mozilla.org/en-US/docs/Learn/HTML/Introduction_to_HTML)
- [HTML & CSS](https://www.w3.org/standards/webdesign/htmlcss.html)
- [HTML & Form validation](https://developer.mozilla.org/en-US/docs/Learn/HTML/Forms/Form_validation)
- [HTML - Multimedia](https://developer.mozilla.org/en-US/docs/Learn/HTML/Multimedia_and_embedding)

1.A
- Create a basic .html file with a header displaying **"Hello World"**.
- Change the header to **"My todo list"**.
- Add a list of **"todo items"** for your daily chores.

1.B

- Create another .html file. Create a table for your expenses.
- Create another .html file. Add an image, a video, and a sound.

1.C

- Create a "sign up" form with fields for: first name, last name, email, birthday, a dropdown to choose your favourite sport, and a text-area to include a small bio for the user. Add a button at the end to submit the form, and another one to clear the form. Add relevant validation rules for all fields (like required fields, valid email).
- Test your HTML files in at least Firefox, Chrome, IE, and Chrome for Android or iOS Safari.

2 - Docs

- [What does it all mean?](https://diveintohtml5.info/semantics.html)
- [Meta-viewport](https://www.quirksmode.org/mobile/metaviewport/)

2.A

- Add *doctype* to the previously created HTML documents. See what happens if you remove it.
- Add metatags to the document.
- Add the meta viewport tag. Check what happens in a mobile browser with or without it.
- Validate your markup: W3C Validator.

3 - Docs

- [W3C - Accessibility](https://www.w3.org/standards/webdesign/accessibility)
- [ChromeVox](https://chrome.google.com/webstore/detail/chromevox/kgejglhpjiefppelpmljglcjbhoiplfn?hl=en)
- [Accessibility Developer Tools](https://chrome.google.com/webstore/detail/accessibility-developer-t/fpkknkljclfencbdbgkenhalefipecmb?hl=en)

3.A

- Validate your markup to see if it is accessible.
- Install a screen reader like ChromeVox, and test your HTML document.
- Install Accessibility Developer Tools, and perform an audit on your markup.

## Conclusion

> By now, you should have several html files with different examples of how to create lists, tables, add images, headers, etc. All the markup is syntactically valid, is semantic, passes the HTML validator, and is accessible.

[<- To index](../README.md#title) - [Topic 2 - Javascript ->](./topic2.md)