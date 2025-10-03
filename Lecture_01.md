# Basics of HTML

## 1. Staring Up
    1.First file using Text Editor
    2.File extension
    3.Opening project in VS code
    4.index.html
## 2.Basic of HTML
    1.What are HTML tags
    2.Using Emmet ! to genrate code
    3.Basic HTML page
    4.Comments
    5.Case Sensitivity
    6.HTML Tags
        1.Heading
        2.Paragraph
        3.Image
        4.Link
        5.List
        6.Table
        7.Form
        8.Div
        9.Span

---

### 1.1 First file using Text Editor

1.Create Folder in your system
2.Create a file named index.html
3.Open the file in your text editor
4.Write some code in the file
    ```html
     <!DOCTYPE html>
     <html lang="en">
     <head>
         <meta charset="UTF-8">
         <meta http-equiv="X-UA-Compatible" content="IE=edge">
         <meta name="viewport" content="width=device-width, initial-scale=1.0">
         <title>Document</title>
     </head>
     <body>
        <h1>Hello World</h1>
     </body>
     </html>
    ```
5.Save the file
6.Open the file in your browser
7.See the result

---

### 1.2 File extension

1.HTML files have the .html extension
2.CSS files have the .css extension
3.JavaScript files have the .js extension
4.Images have the .jpg, .png, .gif, etc.


---

### 1.3 Opening project in VS code
1.Open the folder in VS code
2.Open the index.html file
3.Press ** shift + 1 ** to open the command palette you will see basic structure of HTML file
4.Write some code in the file
```html
<!DOCTYPE html> <---- This is the doctype means it is a HTML document
<html lang="en"> <---- This is the root element of the HTML document
<head> <---- This is the head element of the HTML document which contains meta tags and title tag which is used to define the title of the webpage and meta tags which are used to define the character encoding and viewport
    <meta charset="UTF-8"> <---- This is the character encoding of the webpage, UTF-8 is the most commonly used character encoding
    <meta http-equiv="X-UA-Compatible" content="IE=edge"> <---- This is the meta tag which is used to define the browser compatibility of the webpage and the content attribute specifies the browser version that the webpage is compatible with IE=edge means it is compatible with all versions of Internet Explorer and Edge
    <meta name="viewport" content="width=device-width, initial-scale=1.0"> <---- This is the meta tag which is used to define the viewport of the webpage, the content attribute specifies the width and initial-scale attributes which are used to define the initial zoom level of the webpage
    <title>Document</title> <---- This is the title tag which is used to define the title of the webpage and the content attribute specifies the title of the webpage
</head>
<body> <---- This is the body element of the HTML document which contains the content of the webpage
    <h1>Hello World</h1>
</body>
</html>
```
5.Save the file
6.Click on live server button

---
## 1.4 index.html
index.html is the default file that is opened when you open a folder in VS code.

It is the starting point of your webpage.

---

## 2.Basic of HTML
HTML is the markup language used to give structure and meaning to the content of a webpage.
## 2.1  What are HTML tags
HTML tags are used to define the structure of a webpage.

HTML tags are enclosed in angle brackets < and >.

```html
<h1>Heading</h1>
<p>Paragraph</p>
<img src="image.jpg" alt="Image">
<a href="https://www.google.com">Google</a>
<br>
<hr>
<div>
<span>
etc.
```

---

## 2.2 Using Emmet ! to genrate code
Emmet is a code snippet manager for HTML,CSS,JavaScript,etc.

It is a plugin for VS code that provides a set of shortcuts to generate code snippets.

To use Emmet, you need to install the Emmet extension in VS code.

## 2.3 Basic HTML page

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    <h1>Hello World</h1>
</body>
</html>
```

---

## 2.4 Comments
Comments are used to add notes to your code.

They are ignored by the browser and are not displayed on the webpage.

Comments start with the <!-- and end with -->

```html
<!-- This is a comment -->
```

---

## 2.5 Case Sensitivity
The HTML specification defines the case sensitivity of HTML tags and attributes.

However, it is recommended to use lowercase tags and attributes for better compatibility with different browsers.

```html
<h1>Heading</h1>
<p>Paragraph</p>
<img src="image.jpg" alt="Image">
<a href="https://www.google.com">Google</a>
<br>
<hr>
<div>
<span>
etc.
```

---

### Home Work 

1.Create a index.html stem and try to print "Hey I'm Learning HTML by Enari Coding Channel"
2.Exporle HTML tags in [w3schools](https://www.w3schools.com/html/default.asp)