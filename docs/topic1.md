# Topic 1 - HTML

## Description

HTML (Hypertext Markup Language) **is not a programming language**; it is a *markup language* used to tell your browser how to structure the web pages you visit. It can be as complicated or as simple as the web developer wishes it to be. HTML consists of a series of elements, which you use to enclose, wrap, or mark up different parts of the content to make it appear or act a certain way. The enclosing tags can make a bit of content into a hyperlink to link to another page on the web, italicize words, and so on.

> Other technologies besides HTML are generally used to describe a web page's appearance/presentation (CSS [ -> to topic 2 - CSS & HTML](./topic2.md)) or functionality/behavior (JavaScript [ -> toTopic 3 - Javascript](./topic3.md)).

## Documentation

> Read and follow this documentation to start developing in the right way and avoid dragging errors from the beginning.

You have to think that the code that you are going to write will read it again and again in the future. Not only for you but also for other developers. That's why we need to write quality code.

- HTML
  - [HTML5 Basics](https://developer.mozilla.org/en-US/docs/Web/HTML)
  - [W3 - HTML](https://www.w3.org/standards/webdesign/htmlcss.html)
  - [HTML5 - Form validation](https://developer.mozilla.org/en-US/docs/Learn/HTML/Forms/Form_validation)
  - [HTML5 - Multimedia](https://developer.mozilla.org/en-US/docs/Learn/HTML/Multimedia_and_embedding)

- Semantic & DOCTYPE
  - [WHAT DOES IT ALL MEAN?](https://diveintohtml5.info/semantics.html)
  - [META-VIEWPORT](https://www.quirksmode.org/mobile/metaviewport/)

- W3C Accessibility
  - [W3 - ACCESSIBILITY](https://www.w3.org/standards/webdesign/accessibility)

## Tools

> Tools needed to test and audit the markup.

- [ChromeVox](https://chrome.google.com/webstore/detail/chromevox/kgejglhpjiefppelpmljglcjbhoiplfn?hl=en)
- [Accessibility Developer Tools](https://chrome.google.com/webstore/detail/accessibility-developer-t/fpkknkljclfencbdbgkenhalefipecmb?hl=en)


## Goals and knowledge to achieve

Through the rest of this section you will create a basic HTML document. After finishing this section you will:

- Be able to create HTML documents that displays text, images, tables, lists
- Understand how to structure HTML documents, and what the basic building blocks are
- Understand best practices to write valid, accessible, and semantic HTML markup.

## Exercises

After this presentation and reading of the HTML documentation, we are ready for fun. It's time to develop, are you ready?

> Just a suggest, i prefer a 'commit' point by point.. so, we can see your progress and identify a problem easily

#### HTML Basics

- 1
  - A
    - Create a basic .html file with a header displaying **"Hello World"**.
    - Change the header to **"My todo list"**.
    - Add a list of **"todo items"** for your daily chores.
  - B
    - Create another .html file. Create a table for your expenses.
    - Create another .html file. Add an image, a video, and a sound. (*Remember*: [HTML5 - Multimedia](https://developer.mozilla.org/en-US/docs/Learn/HTML/Multimedia_and_embedding))
  - C
    - Create a "sign up" form with fields for: first name, last name, email, birthday, a dropdown to choose your favourite sport, and a text-area to include a small bio for the user. Add a button at the end to submit the form, and another one to clear the form. Add relevant validation rules for all fields (like required fields, valid email). (*Remember*: [HTML5 - Form validation](https://developer.mozilla.org/en-US/docs/Learn/HTML/Forms/Form_validation))
    - Test your HTML files in at least Firefox, Chrome, IE, and Chrome for Android or iOS Safari.

- 2
  - Add *doctype* to the previously created HTML documents. See what happens if you remove it. (*Remember*: [HTML5 - DOCTYPE](https://diveintohtml5.info/semantics.html))
  - Add metatags to the document.
  - Add the meta viewport tag. Check what happens in a mobile browser with or without it. (*Remember*: [HTML5 - META-VIEWPORT](https://www.quirksmode.org/mobile/metaviewport/))
  - Validate your markup: W3C Validator (*Remember*: [HTML5 - META-VIEWPORT](http://validator.w3.org/))

- 3 Validate your markup to see if it is accessible: [Tools](./topic1.md#tools.md)
  - Install a screen reader like ChromeVox, and test your HTML document.
  - Install Accessibility Developer Tools, and perform an audit on your markup.

## Conclusion

> By now, you should have several html files with different examples of how to create lists, tables, add images, headers, etc. All the markup is syntactically valid, is semantic, passes the HTML validator, and is accessible.


[-> To index](../README.md#title)
