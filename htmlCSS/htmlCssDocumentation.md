##### Aug 9, 2022

## Lesson 1
### Inline and block elements. 

The elements that occupy the space within in the boundary of it's opening and closing tags are *inline* elements. Eg. `<span>`, `<h1></h1>`, etc. 
And the elements that occupy the entire block, or say the entire space, from right to the left part of the screen, are called *block* elememnts. Eg. `<p></p>`

*Never skip the end tag.*

### Attributes 

1. They stand for the properties an element can give to texts or any other images. 
2. Within the tags.

`<a>` tag

This tag is used to put links in the webpages. `<a href="website url">text</a>` Here *href* is an attribute.

`<img>` tag

Used to insert images. `<img src="image url or directory">` Here *src* is an attribute.

`<p>` tag

The browser ignores all the spaces and the line changes within a paragraph.

`<hr>` tag

A break between two paragraphs, a horizontal line.

`<pre>` tag

This is interesting. This tag allows to display the texts as it is in the source. Even the tabs (this sucks). The font could be changed with `<pre style="font-family: Arial, Helvetica, sans-serif;">`

`<style>` tag

It's basically css and can be used as an attribute in other tags like: 

```html
<h3 style="background-color: red;">This is h3 with background color</h3>
    
    <p style="background-color: aqua;">This is a paragraph with aqua background</p>
    <p style="color: pink; background-color: brown;">The text is in pink</p>
    <p style="font-family:'Trebuchet MS', 'Lucida Sans Unicode', 'Lucida Grande', 'Lucida Sans', Arial, sans-serif">This is different font</p>
    <h4 style="text-align:center">This is centered text h4</h4>
<body style="background-color:powderblue;">
```

### Formatting

```html
<b> - Bold text
<strong> - Important text
<i> - Italic text
<em> - Emphasized text
<mark> - Marked text
<small> - Smaller text
<del> - Deleted text
<ins> - Inserted text
<sub> - Subscript text
<sup> - Superscript text
```

### Citation and Quotation

```html
<blockquote> - The text inside is indented.
<q></q> - Puts the text within quotation marks.
<abbr> - Tells the user what the abbreviation stands for when the cursor is hovered over it.
<address> - For specific address of people. The text within it is italic.
<cite> - The text is italic. 
<bdo dir="rtl"></bdo> - This text will be written from right to left. Interesting feature.
```

### Colors

We can just specify the color we want with just their names but also with the rgb values. 
```html
<h1 style="background-color:rgb(255, 99, 71);">...</h1>
<h1 style="background-color:#ff6347;">...</h1>
<h1 style="background-color:hsl(9, 100%, 64%);">...</h1>

<h1 style="background-color:rgba(255, 99, 71, 0.5);">...</h1>
<h1 style="background-color:hsla(9, 100%, 64%, 0.5);">...</h1>
```

### CSS Style

**Inline CSS** is the css style written within the tag. For example: `<h1 style="color:bisque">This is inline CSS</h1>`

**Internal CSS** is that css style when the style elements are written within the `<head><style></style></head>` element.

```html
<head>
<style>
        body {
            background-color: hsl(20, 23, 45);
        }
        h1 {
            color:rgb(45,45,65)
        }
        p {
            color: black;
        }
</style>
</head>
```

**External CSS** is the separate .CSS file that is linked to the html file. `<head><link rel="stylesheet" href="file path"</head>`


flexbox







