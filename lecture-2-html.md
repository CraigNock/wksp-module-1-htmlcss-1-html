# 1.1.2 - HTML or How To Make Lasagna*

---

_actually it's HyperText Markup Language_

---

## Pop Quiz!

- What is HTML?
- What is CSS?
html is your content and markup
css is your styling of the html
---

## Pop Quiz!

- Which is more important?

<img src="./assets/batman_thinking.jpg" />

html(that's your content)
---

## Anatomy of an HTML element

<img src="./assets/html_element.png" />

---

## Anatomy of an HTML element

<img src="./assets/html_element_2.png" />

---

## Basic HTML Template

```HTML
<!DOCTYPE html>
<html>

    <head>
        <title>A Basic HTML Template</title>
    </head>
    <body>
        <!-- all content here -->
    </body>

</html>
```

[More about the doctype.](https://www.w3schools.com/tags/tag_doctype.asp)

---

## Choosing the RIGHT tag for the job

Tags should be chosen based on the semantic value of the content

---

## Choosing the RIGHT tag for the job

Tags should NEVER be chosen based on presentation, or look

NEVER
---

This means that these tags are essentially off-limits

`<big>`, `<small>`, `<i>`, `<b>`, `<br />`, `&nbsp;`, `<hr />`

They have no semantic value.

NEVER

---

Anytime you catch yourself thinking...

"I should use x because I need it to look like ..."

stop ✋
no
---

### Semantic HTML = Google

1. It pleases Google.
    - Easier for its algorithm to crawl and index site
    - Meaning a better ranking in search results
    - Less of a need to "game" the Google algorithm

---

### Semantic HTML = Accessibility

<img src="./assets/accessibility_stats.png" />

---

### Semantic HTML = Accessibility

- [22% of Canadians over the age of 15% live with _at least_ one disability (6.2 million)](https://siteimprove.com/en-ca/blog/a-complete-overview-of-canada-s-accessibility-laws/).

---

### Semantic HTML = Accessibility

- [The Accessible Canada Act (Bill C-81)](https://www.parl.ca/DocumentViewer/en/42-1/bill/C-81/first-reading)

---

### Semantic HTML = Accessibility

- On June 21, 2019, The Accessible Canada Act became law after receiving Royal Assent.

---

### Semantic HTML = Accessibility

- Fines of up to $250,000. 😬

---
Web must be accessible, good html is foundation of that
Right first time is better
No <div> itis

🙏 Always write good HTML. 🙏

---

## Common HTML Tags (4.01+)
ONLY EVER ONE H1

- Block-level elements (take up whole width of page generally)
    - `<h1>`, `<h2>`, `<h3>`, `<h4>`, `<h5>`, `<h6>`, `<p>`
    - `<ul>`, `<ol>`, `<li>`, `<blockquote>`, `<table>`(rare),
    - `<form>`(to do with forms)
    - `<div>`(containers to style easier)
- Inline elements (won't cause new line)
    - `<img>`, `<a>`(links), `<span>`(allows to target small text for styling), `<button>`
    - `<input>`, `<label>`, `<select>`, `<textarea>`
    - `<abbr>`(abreviation hover text) 

[Source](https://www.w3resource.com/html/HTML-block-level-and-inline-elements.php)

---

## HTML 5 Semantic Tags (Will use. Basically positional tags)

- `<header>`, `<footer>`, `<nav>`(navigation bar), `<section>`, `<main>`, `<aside>`
- `<figure>`(image with caption), `<figcaption>`, `<summary>`
- `<time>`(not used much), 

---

## HTML 5 Semantic Tags

<img src="./assets/html5.png" />

---