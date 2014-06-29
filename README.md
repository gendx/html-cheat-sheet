# HTML Cheat Sheet
A reminder of HTML elements.

## Table of Contents
 - [Minimal page](#minimal-page)
 - [Head](#head)
 - [Text content](#text-content)
   - [Headings](#headings)
   - [Paragraphs](#paragraphs)
   - [Formatting](#formatting)
   - [Quotes](#quotes)
 - [Links](#links)
 - [Images](#images)
 - [Tables](#tables)
   - [Basic table](#basic-table)
   - [Advanced table](#advanced-table)


## Minimal page
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

## Head
```html
<head>
    <title>Title</title>
    <base href="base-url" />
    <link href="style.css" rel="stylesheet" type="text/css" />
    <style type="text/css">
        /* CSS code */
    </style>
    <script src="script.js"></script>
    <script>
        // Javascript code
    </script>
    <meta charset="UTF-8">
    <meta name="keywords" content="keywords">
    <meta name="description" content="description">
    <meta name="author" content="name">
    <meta http-equiv="refresh" content="10">
</head>
```

tag | element
--- | ---
**title** | page title
**base** | base url for all links
**link** | link to external source
**style** | CSS inside HTML page
**script** | Javascript code
**meta** | metadata
**meta** *http-equiv*="refresh" *content*="10" | auto-refresh page in 10s


## Text content

### Headings
```html
<h1>Main heading</h1>
<!-- etc -->
<h6>Level-6 heading</h6>
```

tag | element
--- | ---
**h1** | main heading
**h6** | least important heading

### Paragraphs
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

### Formatting
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

### Quotes
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


## Links
```html
<a href="url">link</a>
<a href="url" target=_blank>open in a new window</a>

<a href="#comments">watch comments</a>
<h2 id="comments">comments</h2>
```

tag | element
--- | ---
**a** | hyperlink


## Images
```html
<img src="image.png" alt="description" width="300" height="200" />
```

tag | element
--- | ---
**img** | image


## Tables

### Basic table
```html
<table>
<tr>
    <th>heading 1</th>
    <th>heading 2</th>
</tr>
<tr>
    <td>line 1, column 1</td>
    <td>line 1, column 2</td>
</tr>
<tr>
    <td>line 2, column 1</td>
    <td>line 2, column 2</td>
</tr>
</table>
```

tag | element
--- | ---
**table** | table
**tr** | table row
**th** | table heading
**td** | table cell

### Advanced table
```html
<table>
<caption>caption</caption>
<colgroup>
    <col span="2" style="..." />
    <col style="..." />
</colgroup>
<thead>
    <tr>
        <th>heading 1</th>
        <th>heading 2</th>
        <th>heading 3</th>
    </tr>
</thead>
<tfoot>
    <tr>
        <th>footer 1</th>
        <th>footer 2</th>
        <th>footer 3</th>
    </tr>
</tfoot>
<tbody>
    <tr>
        <td>line 1, column 1</td>
        <td>line 1, column 2</td>
        <td>line 1, column 3</td>
    </tr>
    <tr>
        <td>line 2, column 1</td>
        <td>line 2, column 2</td>
        <td>line 2, column 3</td>
    </tr>
</tbody>
</table>
```

tag | element
--- | ---
**caption** | caption
**colgroup** | defines groups of columns
**col** | defines column's properties
**thead** | groups headings together
**tfoot** | groups footers together
**tbody** | groups other rows
