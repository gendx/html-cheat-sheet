# HTML Cheat Sheet
A reminder of HTML elements.

## Table of Contents
 - [HTML](#html)
   - [Minimal page](#minimal-page)
   - [Text content](#text-content)
     - [Headings](#headings)
     - [Paragraphs](#paragraphs)
     - [Formatting](#formatting)
     - [Quotes](#quotes)
   - [Links](#links)
   - [Images](#images)

## HTML
### Minimal page

```html
<!DOCTYPE html>
<html>
    <head>
        <meta charset="UTF-8">
        <title>Title</title>
    </head>
    <body>
        <!-- content here -->
    </body>
</html>
```

### Text content

#### Headings
```html
<h1>Main heading</h1>
<!-- etc -->
<h6>Level-6 heading</h6>
```

tag | element
--- | ---
**h1** | main heading
**h6** | least important heading

#### Paragraphs
```html
<p>Paragraph.<br/>
Other line.</p>
<p>Other paragraph.</p>
<hr/>
<p>See the line above.</p>
```

tag | element
--- | ---
**p** | paragraph
**br** | line break
**hr** | horizontal line

#### Formatting
```html
<em>Formatting</em> is <strong>important</strong> !
(a+b)<sup>2</sup> = a<sup>2</sup> + b<sup>2</sub> + 2ab
```

tag | element
--- | ---
**sub** | subscript
**sup** | superscript
**em** | emphasize
**strong** | important
**mark** | highlighted
**small** | small
**i** | italic
**b** | bold

#### Quotes
```html
<cite>This book</cite> was written by this author.
<q cite="url">quotation</q>
<blockquote cite="url">
Lorem ipsum<br/>
Lorem ipsum
</blockquote>
```

tag | element
--- | ---
**cite** | title of a work
**q** | inline quotation
**blockquote** | quotation

### Links
```html
<a href="url">link</a>
<a href="url" target=_blank>open in a new window</a>

<a href="#comments">watch comments</a>
<h2 id="comments">comments</h2>
```

tag | element
--- | ---
**a** | hyperlink

### Images
```html
<img src="image.png" alt="description" width="300" height="200" />
```

tag | element
--- | ---
**img** | image
