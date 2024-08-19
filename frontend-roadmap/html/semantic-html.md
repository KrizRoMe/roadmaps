# ☑️ Sematic HTML

A semantic elements clearly describes its meaning to both the browser and the developer.

## Semantic Elements

Many webs contain elements like: `<div id="nav"></div>, <div class="header">, <div id="footer">`, which are not semantic,
because they don't tell anything about their content.

Examples of semantic elements:
```html
- <article> -> It's used to represent a standalone piece of content.
- <aside> -> This might include things like a suplementary content
- <details> -> Tag is used to mark up a collapsible set of content.
- <summary> -> Tag is used to provide a summary or a legend for the content of a <details> element.
- <figure> -> Tag especifies self-contained content, like illustrations, diagrams, photos, etc.
- <figcaption> -> Defines a caption for a <figure> element.
- <footer> -> Tag is used to mark up tyhe bottom section of a page.
- <header> -> Tag is used to mark up the top section of a page.
- <main> -> Tag is used to mark up the main content of a page.
- <mark> -> Tag is used to highlight text.
- <nav> -> Tag is used to mark up the navigation links.
- <section> -> Tag is used to mark up a section of a page that are thematically grouped together.
- <time> -> Tag is used to mark up a specific time or a range of time.
- <address> -> Tag is used to mark up contact information.
- <table> -> Tag is used to mark up a table with columns and rows of data.
```
## Non-Semantic Elements

```html
- <div> -> It's a container for styling purposes.
- <span> -> It's an inline container.
```

## Role Attribute

- The role attribute is used to define the purpose of an element.
- The names of roles are important to create AOM (Accessible Object Model).
- The semantic element or <strong>role</strong> it's important to assistances technologies and search engines.

```html
<div role="banner">
  <span role="heading" aria-level="1">Three words</span>
  <div role="navigation">
    <a>one word</a>
    <a>one word</a>
    <a>one word</a>
    <a>one word</a>
  </div>
</div>
```

## 👁️ Extra Information

- According W3C HTML documentation: "A section is a thematic grouping of content, typically with a heading."
- We can have several `<header>` elements in one document.
- We can have several `<footer>` elements in one document.
- Notice that NOT all links of a document should be inside a `<nav>` element.
- We can make non-semantic elements semantic by adding a role attribute.