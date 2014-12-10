# HTML Boilerplate Transcription

### Here is the breakdown of each HTML element in the `index.html` file from the _HTML5 Boilerplate Project._

#### `<!DOCTYPE html>` [MDN](https://developer.mozilla.org/en-US/docs/Web/Guide/HTML/HTML5/Introduction_to_HTML5)

Used to indicate that your HTML content uses HTML 5. Doing so will cause even browsers that don't presently support HTML5 to ender into standards mode, which means that they'll interpret the long-established parts of HTML in an HTML5-compliant way while ignoring the new features of HTML5 they don't support.

----

#### `<head>` [MDN](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/head)

Provides general information (metadata) about the document, including its title and links to or definitions of scripts and style sheets.

**EXAMPLE**:
```html
<head>
  <meta charset="utf-8">
  <title>"That's no moon..."</title>
```

----

#### `<meta>` [MDN](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/meta) -

Represents any metadata information that cannot be represented by one of the other meta-related elements (`<base>, <link>, <script>, <style> or <title>`).

**EXAMPLE**:
```html
<meta charset="utf-8"> <!-- a charset declaration used for the serialized-form of the webpage. -->
<meta name="description" content=""> <!-- a document-level metadata, applying to the whole page. -->
<meta http-equiv="X-UA-Compatible" content="IE=edge"> <!-- a pragma directive: information normally given from the webserver on how the webpage should be served. -->
```

----

#### `<link>` [MDN](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/link) -

Specifies relationships between the current document and an external resource. Possible uses for this element include defining a relational framework for navigation. This Element is most used to link to style sheets.

**EXAMPLE**
```html
<link rel="stylesheet" href="css/normalize.css">
<link rel="stylesheet" href="css/main.css">
```

---

#### `<script>` [MDN](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/script) -

Is used to embed or reference an executable script within an HTML or XHTML document. _Note: It is recommended these be placed at the END of the document, so as to prevent any errors when loading the page._

**EXAMPLE**
```html
<script src="js/vendor/modernizr-2.6.2.min.js"></script>
```

----

#### `<body>` [MDN](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/body) -

Represents the content of an HTML document. There can be [ONLY ONE](http://hetediksor.hu/wp-content/uploads/2013/01/highlander.gif) `<body>` element in a document...

**EXAMPLE**
```html
<body>
  THE ENTIRE DOCUMENT
</body>
```

----

#### `<p>` [MDN](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/p) -

Represents a paragraph of text; a [block-level element](https://developer.mozilla.org/en-US/docs/Web/HTML/Block-level_elements).

**EXAMPLE**

```html
<p>"Horizontal boosters...! Alluvial dampers...! Well that's not it. Bring me the hydrospanner!"</p>

```
----
