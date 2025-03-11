# Understanding HTML Syntax

**Compiled on:** 11/03/2025  
**References:** Lecture by Dev Peter, W3Schools ([https://www.w3schools.com](https://www.w3schools.com)), and Personal Study  

## HTML Elements  
An HTML element is defined by a start tag, some content, and an end tag.

<!-- An image will go here showing a simple code structure of an HTML element -->

Some HTML elements have no content (like the `<br>` element). These elements are called empty elements. Empty elements do not have an end tag! Additionally, some elements are called self-closing tags, which do not have a closing tag.

---

## HTML Attributes  
HTML attributes provide additional information about HTML elements.

<!-- An image will go here showing a simple code structure of an HTML attribute -->

### Attributes can have the following features:
- All HTML elements can have attributes.
- Attributes provide additional information about elements.
- Attributes are always specified in the start tag.
- Attributes usually come in name/value pairs like: `name="value"`.

---

## HTML Text Formatting  
HTML contains several elements for defining text with a special meaning.

### Formatting elements were designed to display special types of text:

- `<b>` - Bold text  
- `<strong>` - Important text  
- `<i>` - Italic text  
- `<em>` - Emphasized text  
- `<mark>` - Marked text  
- `<small>` - Smaller text  
- `<del>` - Deleted text  
- `<ins>` - Inserted text  
- `<sub>` - Subscript text  
- `<sup>` - Superscript text  

The HTML `<b>` element defines bold text, without any extra importance.

The HTML `<strong>` element defines text with strong importance. The content inside is typically displayed in bold.

<!-- Some pictures go here to display the emphasis of the difference between semantics and non-semantics, syntax-only tags -->

---

## HTML Comments  
HTML comments are not displayed in the browser, but they can help document your HTML source code.

With comments, you can place notifications and reminders in your HTML code:

```html
<!-- This is a comment -->
<p>This is a paragraph.</p>
<!-- Remember to add more information here -->
```

### Hide Content  
Comments can be used to hide content temporarily:

```html
<p>This is a paragraph.</p>

<!-- <p>This is another paragraph </p> -->

<p>This is a paragraph too.</p>
```

Comments are also great for debugging HTML because you can comment out HTML lines of code, one at a time, to search for errors.

<!-- Some pictures go here emphasizing the importance of maintaining good practice of writing HTML comments as part of HTML documents in web projects -->

### Hide Inline Content  
Comments can be used to hide parts in the middle of the HTML code.

#### Example: Hide a part of a paragraph:

```html
<p>This <!-- great text --> is a paragraph.</p>
```

---

## HTML Quotation and Citation Elements  
The HTML `<blockquote>` element defines a section that is quoted from another source.

Browsers usually indent `<blockquote>` elements.

#### Example:
```html
<p>Here is a quote from WWF's website:</p>
<blockquote cite="http://www.worldwildlife.org/who/index.html">
For 60 years, WWF has worked to help people and nature thrive. As the world's leading conservation organization, WWF works in nearly 100 countries. At every level, we collaborate with people around the world to develop and deliver innovative solutions that protect communities, wildlife, and the places in which they live.
</blockquote>
```

<!-- Some pictures go here displaying the results of the above code -->

### HTML `<q>` for Short Quotations  
The HTML `<q>` tag defines a short quotation.

Browsers normally insert quotation marks around the quotation.

#### Example:
```html
<p>WWF's goal is to: <q>Build a future where people live in harmony with nature.</q></p>
```

<!-- Some pictures go here displaying the results of the above code -->

---

## HTML Abbreviations  
The HTML `<abbr>` tag defines an abbreviation or an acronym, like "HTML", "CSS", "Mr.", "Dr.", "ASAP", "ATM".

Marking abbreviations can give useful information to browsers, translation systems, and search engines.

#### Example:
```html
<p>The <abbr title="World Health Organization">WHO</abbr> was founded in 1948.</p>
```

<!-- Some pictures go here displaying the results of the above code -->

---

## HTML Address  
The HTML `<address>` tag defines the contact information for the author/owner of a document or an article.

The contact information can be an email address, URL, physical address, phone number, or social media handle.

The text in the `<address>` element usually renders in italic, and browsers will always add a line break before and after the `<address>` element.

#### Example:
```html
<address>
Written by John Doe.<br>
Visit us at:<br>
Example.com<br>
Box 564, Disneyland<br>
USA
</address>
```

<!-- Some pictures go here displaying the results of the above code -->

---

## HTML `<bdo>` for Bi-Directional Override  
BDO stands for Bi-Directional Override.

The HTML `<bdo>` tag is used to override the current text direction:

#### Example:
```html
<bdo dir="rtl">This text will be written from right to left</bdo>
```

<!-- Some pictures go here displaying the results of the above code -->
