## 1 HTML Tags

### 1.1 Heading
Heading tags are used to define headings in a webpage.

There are six heading tags in HTML:

1.h1 - used to define the largest heading
2.h2 - used to define the second largest heading
3.h3 - used to define the third largest heading
4.h4 - used to define the fourth largest heading
5.h5 - used to define the fifth largest heading
6.h6 - used to define the sixth largest heading

```html
<h1>Heading</h1>
<h2>Heading</h2>
<h3>Heading</h3>
<h4>Heading</h4>
<h5>Heading</h5>
<h6>Heading</h6>
```

---

### 1.2 Paragraph
Paragraph tags are used to define paragraphs in a webpage.

There are two paragraph tags in HTML:

1.p - used to define a paragraph
2.br - used to create a line break

`lorem` it is a placeholder text that is used to demonstrate the usage of the `p` tag.

```html
<p>Paragraph</p>
<br>
```
#### 1.2.1 br tag
The `br` tag is used to create a line break. It is used to separate paragraphs.

```html
<p>Paragraph</p>
<br>
<p>Paragraph</p>
```

#### 1.2.2 hr tag
The `hr` tag is used to create a horizontal line. It is used to separate sections of content.

```html
<p>Paragraph</p>
<hr>
<p>Paragraph</p>
```

#### 1.2.3 span tag
The `span` tag is used to create a span. It is used to apply styles to text.
---

### 1.3 Image
Image tags are used to display images in a webpage.

There are two image tags in HTML:

1.img - used to display an image
2.a - used to create a hyperlink

```html
<img src="image.jpg" alt="Image">
<a href="https://www.google.com">Google</a>
```

---

### 1.4 Link / Anchor
Link tags are used to create hyperlinks in a webpage.

There are two link tags in HTML:

1.a - used to create a hyperlink
2.br - used to create a line break

```html
<a href="https://www.google.com">Google</a>
<br>
```

**target**- used to specify where to open the linked document (e.g. _blank, _self, _parent, _top)  
href - used to specify the URL of the linked document
`_blank` - used to open the linked document in a new window or tab
`_self` - used to open the linked document in the same frame as it was clicked (this is default)
`_parent` - used to open the linked document in the parent frame
`_top` - used to open the linked document in the full body of the window

Example:

```html
<a href="https://www.google.com" target="_blank">Google</a>
``` 

---
#### Bold / Italic /Underline / Strikethrough
`Bold` tag is used to make text bold. It is used to emphasize important information.

`Italic` tag is used to make text italic. It is used to emphasize important information.

`Underline` tag is used to underline text.

`Strikethrough` tag is used to strikethrough text.

Example:

```html
<p>This is a <b>bold</b> text.</p>
<p>This is an <i>italic</i> text.</p>
<p>This is an <u>underlined</u> text.</p>
<p>This is a <s>strikethrough</s> text.</p>
```

---

#### Blockquote
`Blockquote` tag is used to create a block of quoted text.
Example:

```html
<div>
  <blockquote cite="https://www.huxley.net/bnw/four.html">
    <p>
      Words can be like X-rays, if you use them properly—they’ll go through
      anything. You read and you’re pierced.
    </p>
  </blockquote>
  <p>—Aldous Huxley, <cite>Brave New World</cite></p>
</div>  
```

---

#### Code
`Code` tag is used to display code in a webpage.    

Example:    
```html
<code>This is a code</code>    
```
#### Pre
`Pre` tag is used to display preformatted text in a webpage.display as a block of text, with some formatting, such as font changes.

Example:    
```html
<pre>This is a 
    preformatted text</pre>    
```

#### Big / Small
`Big` tag is used to make text bigger. It is used to emphasize important information.
Example:    
```html
<p>This is a <big>big</big> text.</p>    
```
`Small` tag is used to make text smaller. It is used to emphasize important information.
Example:    
```html
<p>This is a <small>small</small> text.</p>    
```

### 1.5 List
List tags are used to create lists in a webpage.

There are two list tags in HTML:

1.ul - used to create an unordered list
2.ol - used to create an ordered list

```html
<ul>
    <li>Item 1</li>
    <li>Item 2</li>
    <li>Item 3</li>
</ul>
<ol>
    <li>Item 1</li>
    <li>Item 2</li>
    <li>Item 3</li>
</ol>
```

---

### 1.6 Table
Table tags are used to create tables in a webpage.

There are two table tags in HTML:

1.table - used to create a table
2.tr - used to create a table row

```html
<table>
    <tr>
        <th>Heading 1</th>
        <th>Heading 2</th>
        <th>Heading 3</th>
    </tr>
    <tr>
        <td>Item 1</td>
        <td>Item 2</td>
        <td>Item 3</td>
    </tr>
</table>
```

---

### 1.7 Form
Form tags are used to create forms in a webpage.

There are two form tags in HTML:

1.form - used to create a form
2.input - used to create an input field

```html
<form>
    <input type="text" name="name" placeholder="Name">
    <input type="email" name="email" placeholder="Email">
    <input type="submit" value="Submit">
</form>
```

---

### 1.8 Div
Div tags are used to create divs in a webpage.

There are two div tags in HTML:

1.div - used to create a div
2.span - used to create a span

```html
<div>
    <span>Span</span>
</div>
```

---

### 1.9 Span
Span tags are used to create spans in a webpage.

There are two span tags in HTML:

1.span - used to create a span
2.br - used to create a line break

```html
<span>Span</span>
<br>
```

## 1.10 Video
Video tags are used to embed videos in a webpage.

There are two video tags in HTML:

1.video - used to embed a video
2.br - used to create a line break

```html
<video src="video.mp4" controls>
    Your browser does not support the video tag.
</video>
<br>

```

autoplay - used to specify whether the video should start playing automatically
controls - used to specify whether the video controls should be displayed
loop - used to specify whether the video should loop
muted - used to specify whether the video should be muted
poster - used to specify the URL of an image to use as a poster frame
preload - used to specify whether the video should be preloaded
src - used to specify the URL of the video file

Example:

```html
<video src="video.mp4" controls autoplay loop muted poster="poster.jpg" preload>
    Your browser does not support the video tag.
</video>
```

## 1.11 Audio
Audio tags are used to embed audio in a webpage.

There are two audio tags in HTML:

1.audio - used to embed an audio
2.br - used to create a line break

```html
<audio src="audio.mp3" controls>
    Your browser does not support the audio tag.
</audio>
<br>        

```

autoplay - used to specify whether the audio should start playing automatically
controls - used to specify whether the audio controls should be displayed
loop - used to specify whether the audio should loop
muted - used to specify whether the audio should be muted
poster - used to specify the URL of an image to use as a poster frame
preload - used to specify whether the audio should be preloaded
src - used to specify the URL of the audio file

Example:

```html
<audio src="audio.mp3" controls autoplay loop muted poster="poster.jpg" preload>
    Your browser does not support the audio tag.
</audio>
```

## 1.12 Superscript / Subscript
Superscript tag is used to make text superscript. It is used to emphasize important information.

Subscript tag is used to make text subscript. It is used to emphasize important information.

Example:

```html
<p>This is a <sup>superscript</sup> text.</p>
<p>This is a <sub>subscript</sub> text.</p>    
``` 
---

## 2 HTML Attributes

### 2.1 Attributes
Attributes are used to add additional information to HTML tags.

There are two types of attributes in HTML:

1.Static attributes - used to define the value of an attribute
2.Dynamic attributes - used to define the value of an attribute

**synatx:** 

```
<tag attribute="value">Text Content</tag>

```

```html
<h1 id="heading">Heading</h1>
<p class="paragraph">Paragraph</p>
```

---

### 2.2 Static Attributes
Static attributes are used to define the value of an attribute.

There are two static attributes in HTML:

1.id - used to define the id of an element
2.class - used to define the class of an element

```html
<h1 id="heading">Heading</h1>
<p class="paragraph">Paragraph</p>
```

---

### 2.3 Dynamic Attributes
Dynamic attributes are used to define the value of an attribute.

There are two dynamic attributes in HTML:

1.src - used to define the source of an image
2.type - used to define the type of an input field

```html
<img src="image.jpg" alt="Image">
<input type="text" name="name" placeholder="Name">
```

---

## 3 Charecter Entities and Reserved Words

### 3.1 Charecter Entities
Charecter entities are used to display special characters in a webpage.
like < > & " '  etc.


## Home Work
1.Try to print Charecter Entities  and Reserved Words in HTML
2.Paly around with HTML tags try to create simple readable webpage with HTML tags
3.Try to print (a+b)<sup>2</sup> in HTML and see the result
4.Try to print H<sub>2</sub>SO<sub>4</sub> in HTML and see the result





