# 📃 HTML Basics

## What is HTML? (Hypert Text Mark Language)?

- HTML is the standard markup language for creating Web Pages.
- HTML describes a structure of a Web Page.
- HTML elements label pieces of content such as "this is paragraph", "this is a heading", "this is a link", etc.
- 👀 Tags are not case-sensitive.
- 📝 The W3C recommends writing all tags in lowercase.

## What is a Tag?

- A tag is a keyword surrounded by angle brackets, like `<html>`.
- Most tags must be opened `<html>` and closed `</html>`.
- 👀 Elements of a single tag are called <strong>void elements<strong/>.

## Attributes

- Provide additional information about an element.
- For an element with more than one attribute, the attributes should be separated by spaces.
- The attribute , followed by an equal sign
- An attribute value, wrapped by opening and closing quotation marks.
- Boolean can only have one value, wich is generally the same as the attribute name.
- The boolean attribute is considered to be true if the attribute is present on the element, regardless of the value.


## Single or double quotes?

- The HTML standard does not care if you use single or double quotes.
- Make sure you don't mix single and double quotes in the same document.
- However, if you use one type of quote, you can include the other type inside the attribute value.

## Character References

```html
| Symbol | Character Reference |
|--------|---------------------|
| &      | &amp;               |
| <      | &lt;                |
| >      | &gt;                |
| "      | &quot;              |
| '      | &apos;              |
|        | &nbsp;              |
| –      | &ndash;             |
```

## HTML Basic Structure

```html
<!DOCTYPE html> -> Declaration defines this document to be HTML5
<html> -> Root element of an HTML page
<head> -> This label contains meta-information about HTML page
<title>Page Title</title> -> This element show in the browser's title bar
</head>
<body> -> Define a container for the visible content, such as headings, paragraphs, images, hyperlinks, etc.

<h1>My First Heading</h1> -> Element defines a large heading, <h1> to <h6> are headings
<p>My first paragraph.</p> -> Element defines a paragraph

</body>
</html>
```
## HTML History

- 1991 | Tim Berners-Lee invented HTML.
- 1995 | HTML 2.0 was published.
- 1997 | HTML 3.2 was published.
- 1999 | HTML 4.01 was published.
- 2014 | W3C HTML 5 was published.
- 2017 | W3C HTML 5.2 was published.

## What is W3C(World Wide Web Consortium)?

- Is the main internations standards organization for the World Wide Web.
- It is responsible for maintaining the web standards.
- Is the company that defines standards for HTML, CSS, XML, etc.
