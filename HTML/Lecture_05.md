# List,Table and Form

## List
     1.Ordered List
     2.Type of Ordered List
         1.1.Decimal
         1.2.Alphabetical
         1.3.Roman
         1.4.Arabic
     3.Unordered List
     4.Type of Unordered List
         1.1.Disc
         1.2.Circle
         1.3.Square
         1.4.Decimal
         1.5.Alphabetical
         1.6.Roman
         1.7.Arabic
     5.Definition List
     6.Type of Definition List
         1.1.Definition
         1.2.Definition
         1.3.Definition
         1.4.Definition

## Table
    1.<tr>,<th>,<td> tags
    2.Caption
    3.Colspan

## Form
    1.Input tag
    2.Action attribute
    3.Name and value property
    4.label tag
    5.Exploring tag

## iFrame Tag
    1.iFrame tag


#### 1.List Tag
List tags are used to create lists in a webpage.
###### 1.Ordered List
        1.ol - used to create an ordered list
        2.li - used to create a list item
        3.type - used to define the type of the list
            1.1.Decimal
            1.2.Alphabetical
            1.3.Roman
            1.4.Arabic
            1.5.Lower Alphabetical
            1.6.Upper Alphabetical
            1.7.Lower Roman
            1.8.Upper Roman
            1.9.Lower Greek
            1.10.Upper Greek
**syntax:**
```html
<ol>
    <li>Item 1</li>
    <li>Item 2</li>
    <li>Item 3</li>
</ol>
```

Example:1.1.Decimal
```html
<ol type="1">
    <li>Item 1</li>
    <li>Item 2</li>
    <li>Item 3</li>
</ol>
```

Example:1.2.Alphabetical
```html
<ol type="a">
    <li>Item 1</li>
    <li>Item 2</li>
    <li>Item 3</li>
</ol>
```

Example:1.3.Roman
```html
<ol type="i">
    <li>Item 1</li>
    <li>Item 2</li>
    <li>Item 3</li>
</ol>
```

Example:1.4.Arabic
```html
<ol type="I">
    <li>Item 1</li>
    <li>Item 2</li>
    <li>Item 3</li>
</ol>
```

Example:1.5.Lower Alphabetical
```html
<ol type="a">
    <li>Item 1</li>
    <li>Item 2</li>
    <li>Item 3</li>
</ol>
```

Example:1.6.Upper Alphabetical
```html
<ol type="A">
    <li>Item 1</li>
    <li>Item 2</li>
    <li>Item 3</li>
</ol>
```

Example:1.7.Lower Roman
```html
<ol type="i">
    <li>Item 1</li>
    <li>Item 2</li>
    <li>Item 3</li>
</ol>
```

Example:1.8.Upper Roman
```html
<ol type="I">
    <li>Item 1</li>
    <li>Item 2</li>
    <li>Item 3</li>    
</ol>

```
---

###### 1.Unordered List
        1.ul - used to create an unordered list
        2.li - used to create a list item
        3.type - used to define the type of the list
            1.1.Disc
            1.2.Circle
            1.3.Square
            1.4.Decimal
         
**syntax:**
```html
<ul>
    <li>Item 1</li>
    <li>Item 2</li>
    <li>Item 3</li>
</ul>
```

Example:1.1.Disc
```html
<ul type="disc">
    <li>Item 1</li>
    <li>Item 2</li>
    <li>Item 3</li>
</ul>
```

Example:1.2.Circle
```html
<ul type="circle">
    <li>Item 1</li>
    <li>Item 2</li>
    <li>Item 3</li>
</ul>
```

Example:1.3.Square
```html
<ul type="square">
    <li>Item 1</li>
    <li>Item 2</li>
    <li>Item 3</li>
</ul>
```

Example:1.4.Decimal
```html
<ul type="decimal">
    <li>Item 1</li>
    <li>Item 2</li>
    <li>Item 3</li>
</ul>
```

---

#### 2.Table Tag
Table tags are used to create tables in a webpage.

Table tags in HTML:

1.table - used to create a table
2.tr - used to create a table row
3.th - used to create a table header
4.td - used to create a table data

**syntax:**
```html
<table>
    <caption>Table Caption</caption>
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
colspan and rowspan attributes are used to define the number of columns and rows in a table.

**colspan:**
    1.colspan - used to define the number of columns in a table
    2.rowspan - used to define the number of rows in a table

**syntax:**
```html
<table>
    <tr>
        <th>Heading 1</th>
        <th>Heading 2</th>
        <th>Heading 3</th>
    </tr>
    <tr>
        <td>Item 1</td>
        <td colspan="2">Item 2</td>
        <td>Item 3</td>
    </tr>
</table>
```
---

#### 3.Form Tag
Form tags are used to create forms in a webpage.

There are two form tags in HTML:

1.form - used to create a form
2.input - used to create an input field

**syntax:**
```html
<form>
    <input type="text" name="name" placeholder="Name">
    <input type="email" name="email" placeholder="Email">
    <input type="submit" value="Submit">
</form>
```

Action attribute is used to define the action of the form.
Name and value property is used to define the name and value of the input field.
label tag is used to define the label of the input field.
Exploring tag is used to define the exploring of the input field.

**syntax:**
```html
<form action="https://www.google.com" method="get">
    <input type="text" name="name" placeholder="Name">
    <input type="email" name="email" placeholder="Email">
    <input type="submit" value="Submit">
</form>
``` 

Label tag is used to define the label of the input field.
**syntax:**
```html
<form action="https://www.google.com" method="get">
    <label for="name">Name</label>
    <input type="text" name="name" id="name" placeholder="Name">
    <label for="email">Email</label>
    <input type="email" name="email" id="email" placeholder="Email">
    <input type="submit" value="Submit">
</form>
```

###### Exploring tags

**syntax:**
```html
<form action="https://www.google.com" method="get">
    <label for="name">Name</label>
    <input type="text" name="name" id="name" placeholder="Name">
    <label for="email">Email</label>
    <input type="email" name="email" id="email" placeholder="Email">
    <input type="submit" value="Submit">
    <input type="reset" value="Reset">
    <input type="button" value="Button">
    <input type="checkbox" name="checkbox" id="checkbox">
    <input type="radio" name="radio" id="radio">
    <select name="select">
        <option value="1">Option 1</option>
        <option value="2">Option 2</option>
        <option value="3">Option 3</option>
    </select>
    <textarea name="textarea" id="textarea" cols="30" rows="10"></textarea> 
    <input type="file" name="file" id="file">
    <input type="image" src="image.jpg" alt="Image">
    <input type="date" name="date" id="date">
    <input type="time" name="time" id="time">
    <input type="color" name="color" id="color">
    <input type="range" name="range" id="range">
</form>
``` 

Example for radio button:
```html
    <form>
        <input type="radio" name="gender" value="male">Male
        <input type="radio" name="gender" value="female">Female
        <input type="radio" name="gender" value="other">Other
    </form>
```

Example for checkbox:
```html
<form>
    <input type="checkbox" name="language" value="html">HTML
    <input type="checkbox" name="language" value="css">CSS
    <input type="checkbox" name="language" value="javascript">JavaScript
</form>
```
---

#### 4.iFrame Tag
iFrame tags are used to embed an iframe in a webpage.

There are two iFrame tags in HTML:

1.iframe - used to embed an iframe
2.src - used to define the source of the iframe

**syntax:**
```html
<iframe src="https://www.google.com" width="100%" height="500px"></iframe>
```

---

