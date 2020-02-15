# Memory Aid
Memory Aid for UX web development related code.


## Website must have
Think of it like a hamburger.
```
<!DOCTYPE html> . <!-- sesame seeds -->
<html> <!-- bun -->
<head> <!-- condiments -->
  <title></title>
</head>
<body> <!-- patty -->
    <!-- viewport -->
</body>
</html> <!-- bun -->
```

## Head
```
<meta chartset="utf-8">
```

## Comment
```
<!-- comment -->
```

## non breaking space
`&nbsp`

## syntatic
`<b>` `<i>` is style and shouldn't be in html.
`<strong>` `<em>` tells machines it is symatically important.

## Grouping and sectioning
semantics is not the job of the coder.

### Grouping
```
<header>
<footer>
<main>
```

### Sectioning
```
<nav>
<section>
<aside>
<article>
```

## Navigation
`<nav>` always has a list of links.
```
<nav>
  <ul>
    <li></li>
    <li></li>
    <li></li>
  </ul>
</nav>
```
* CSS will create the structure.
* used for assitive devices.

## Article
`<article>` can be used on any website and still make sense self contained.
Any example would be an article of clothing.

# Section
`<section>` themematic grouping of content. Can stand alone.

# Aside
`<aside>` might be a thing that gets included.

# Main
`<main>` only unique to the page. Not `<aside>`, not `<header>`, not `<footer`>

## AODA
AODA is the law.
It makes everything better. Grade 8 language, short sentences 2-3 sylables.

## ARIA
`<nav role="nav">` used for old browsers

## support for legacy browsers
<!--[if lt IE 9]> <script src="http://html5shim.googlecode.com/svn/trunk/html5.js"></script>
<![endif]-->

## comment
### html
`<!-- comment -->`

### css
`/* comment */`

## 3 ways to  style CSS
### Inline Style
`<p style="font-family:Arial;">some text</p>`
* Problem is that Google doesn't like this way of styling because of the code to content ratio.

### Head of document
```
<head>
  <style>
  p {
    font-family: Arial;
    }
  </style>
</head>
* Problem is that there is a lot of code for one page and only works on one page.

### In a .css file (a stylesheet)
```
<head>
  <link rel="stylesheet" type="text/css" href="css/style.css">
</head>
```

## CSS Syntax
```
  p { /* selector */
    font-family: Arial; /* property value */
    }
```
declarition

## Links
Change state using filters
`a:hover` a link when the user mouses over.
`a:visited` a link that has been visited.
`a:active` a link the moment it is clicked.

## CSS Tips
```
display:block;
width: 200px;
```
Tell element you will set the width 1st

```
list-style: none;
```
no bullets for navigation.

```
nav a {
  display: block;
  }
```
This will make it fill the while space. Good for mobile.

```
@media screen and (min-width: 800px)
```
Use a set of defined styles when the size matches the width.
https://www.w3schools.com/css/css3_mediaqueries_ex.asp

## links
`../` this will search outside of the current file folder.

## CSS Background image
`background: url() right center;`

## Bootstrap
### Grid
`col-lg-3 col-md-6 col-sm-12`
The higher the number the the more it takes up the screen.

### Responsive design meta tags
```
<meta name="viewport" content="width=device-width, initial-scale=1, shrink-to-fit=no">
<meta http-equiv="X-UA-Compatible" content="IE=edge">
```

### JavaScript Tags
```
<script src="https://code.jquery.com/jquery-3.4.1.slim.min.js" integrity="sha384-J6qa4849blE2+poT4WnyKhv5vZF5SrPo0iEjwBvKU7imGFAV0wwj1yYfoRSJoZ+n" crossorigin="anonymous"></script>
<script src="https://cdn.jsdelivr.net/npm/popper.js@1.16.0/dist/umd/popper.min.js" integrity="sha384-Q6E9RHvbIyZFJoft+2mJbHaEWldlvI9IOYy5n3zV9zzTtmI3UksdQRVvoxMfooAo" crossorigin="anonymous"></script>
```
