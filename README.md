# HTML - CSS - JS
| TABLE OF CONTENTS   |
| ------------------- |
| [ HTML document structure ](#)                       |

A typical HTML document will have the following structure:

	1. Document declaration
	2. Document root tag
	3. Document head and it's related tags
	4. Document body and it's related tags

_We will be study the *&lt;head&gt;* and *&lt;body&gt;* related tags in subsequent section. but before we go any futher, let's just look at what is `document declaration`._

The `DOCTYPE` declaration tag is used by the web browser to understand the version of the HTML used in the document. There are many other declaration types which can be used in HTML document depending on what version of HTML is being used. Current version of HTML is _`HTML5`_ and it makes use of the following declaration: *&lt;!DOCTYPE html&gt;*.

```` html
<!--/ @tshikororoda
  Folder: hds/hds.index.html
  It's specified before the HTML root tag

-->

<!DOCTYPE html> <!-- HTML5 document version declaration -->

````


| Tags 		       | Description                                             |
| -------------- | ------------------------------------------------------- |
|`<!DOCTYPE...>` | _This tag defines the document type and HTML version._  |

```` html
<!--/@tshikororoda
 Folder: hds/hds.index.html
 Document root tag

-->

<!DOCTYPE html> <!-- HTML5 document version declaration -->
<html dir="ltr" lang="en">

</html>

````

| Tags 		       | Description |
| -------------- | ----------- |
| _`<html>`_     | _This tag encloses the complete HTML document and mainly comprises of document header which is represented by `<head>...</head>` and document body which is represented by `<body>...</body>`tags._ |

_`dir`_ and _`lang`_ are attributes of `HTML elements`. Attributes provide additional information about elements. Always specified attributes at the start tag: _&lt;element lang="language_code"&gt;_. The _`dir`_ attribute specifies the text direction of the element's content. The _`lang`_ attribute specifies the language of the element's content.

Document head and its related tags

```` html
<!--/@tshikororoda
 Folder: hds/hds.index.html
 Document head and its related tags

-->

<!DOCTYPE html> <!-- HTML5 document version declaration -->
<html dir="ltr" lang="en">
  <head>

<!--____________________________________________
  [ Document header related tags here ]
-->

    <meta charset     ="utf-8" />
    <meta http-equiv  ="X-UA-Compatible"  content="IE=edge" />
    <meta name        ="viewport"         content="width=device-width; initial-scale=1.0" />

    <title> Document Appropriate Skelton </title>

  </head>

</html>

````

| Tags 		   | Description |
| -----------| ----------- |
| `<head>`   | _This tag represents the document's header which can keep other HTML tags like `<title>, <meta>` etc._ |
| `<title>`  | _The `<title>` tag is used inside the `<head>` tag to mention the document title._                     |

Document body and its related tags

```` html
<!--/@tshikororoda
 Folder: hds/hds.index.html
 Document head and its related tags

-->

<!DOCTYPE html> <!-- HTML5 document version declaration -->
<html dir="ltr" lang="en">
  <head>

<!--____________________________________________
  [ Document header related tags here ]
-->

    <meta charset     ="utf-8" />
    <meta http-equiv  ="X-UA-Compatible"  content="IE=edge" />
    <meta name        ="viewport"         content="width=device-width; initial-scale=1.0" />

    <title> Document Appropriate Skelton </title>

  </head>
  <body>
    <!--____________________________________________
      [ Document body related tags here ]
    -->

    <h1> &#39;Document Appropriate Skelton&#39; </h1>
    <p> This is the document structure. </p>

  <body>
</html>

````
| Tags 		  | Description |
| --------- | --------------------------------------------------------------------------------------------------- |
| `<body>`  | _This tag represents the document's body which keeps other HTML tags like `<h1>, <div>, <p>` etc._  |
| `<h1>`    | _This tag represents the heading._                                                                  |
| `<p>`     | _This tag represents a paragraph._                                                                  |

*`Last modified: 2022-06-16, time: 16:05PM`*
