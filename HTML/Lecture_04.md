# HTML and Project Structure

### 1.Semantic Tags
    1.Sematic / Non-Semantic Tags

### 2.Body Tag
   1.Header Tag
   2.Main Tag
        1.section Tag
        2.article Tag
        3.aside Tag
   3.Footer Tag

### 3.Folder Structure
   1.Recommeded Folder Structure

### 4.More Tags
   1.Navigation Tag
   2.Block and Inline Tags
   3.Div Tag
   4.Span Tag


## 1 Semantic Tags
    1.Semantic tags are used to define the meaning of the content. 
    2.They are used to describe the content of a web page. 
    3.The semantic tags are important because they help search engines understand the content of a web page and improve the user experience.
    4. Semantic tags are header, nav, main, footer, section, article, aside

    Example:
    ```html
        <header>
            <h1>My Website</h1>
        </header>
        <nav>
            <ul>
                <li><a href="#">Home</a></li>
                <li><a href="#">About</a></li>
                <li><a href="#">Contact</a></li>
            </ul>
        </nav>
        <main>
            <section>
                <h2>About Us</h2>
                <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed non risus. Suspendisse lectus tortor, dignissim sit amet, adipiscing nec, ultricies sed, dolor. Cras elementum ultrices diam. Maecenas ligula massa, varius a, semper congue, euismod non, mi. Proin porttitor, orci nec nonummy molestie, enim est eleifend mi, non fermentum diam nisl sit amet erat. Duis semper. Duis arcu massa, scelerisque vitae, consequat in, pretium a, enim. Pellentesque congue. Ut in risus volutpat libero pharetra tempor. Cras vestibulum bibendum augue. Praesent egestas leo in pede. Praesent blandit odio eu enim. Pellentesque sed dui ut augue blandit sodales. Vestibulum ante ipsum primis in faucibus orci luctus et ultrices posuere cubilia Curae; Aliquam nibh. Mauris ac mauris sed pede pellentesque fermentum. Maecenas adipiscing ante non diam sodales hendrerit.
                </p>
            </section>
            <section>
                <h2>Our Team</h2>
                <ul>
                    <li>John Doe</li>
                    <li>Jane Doe</li>
                    <li>Bob Doe</li>
                </ul>
            </section>
        </main>
        <footer>
            <p>&copy; 2022 My Website. All rights reserved.</p>
        </footer>
    ```

---
## 2 Non-Semantic Tags
Non-Semantic tags are used to define the structure of a webpage.

There are two non-semantic tags in HTML:

1.div - used to create a div
2.span - used to create a span
3.br - used to create a line break
4.i - used to create an italic text

```html
<div>
    <span>Span</span>
</div>
```

---

# Schematic Structure of Semantic Tags
    1.Header Tag
        1.h1 - used to define the largest heading
        2.h2 - used to define the second largest heading
        3.h3 - used to define the third largest heading
        4.h4 - used to define the fourth largest heading
        5.h5 - used to define the fifth largest heading
        6.h6 - used to define the sixth largest heading

    2.Navigation Tag
        1.nav - used to define the navigation
        2.ul - used to create an unordered list
        3.li - used to create a list item
        4.a - used to create a hyperlink

    3.Main Tag
        1.main - used to define the main content
        2.section - used to define a section
        3.article - used to define an article
        4.aside - used to define an aside

    4.Footer Tag
        1.footer - used to define the footer  

---

#### 1.Navigation Tag
Navigation tags are used to define the navigation of a webpage.

There are two navigation tags in HTML:

1.nav - used to define the navigation
2.ul - used to create an unordered list
3.li - used to create a list item
4.a - used to create a hyperlink

```html
<nav>
    <ul>
        <li><a href="#">Home</a></li>
        <li><a href="#">About</a></li>
        <li><a href="#">Contact</a></li>
    </ul>
</nav>
```

---

#### Block and Inline Tags
Block tags are used to define the structure of a webpage.
    1.Starts with a new line
    2.Takes up the full width of the page
    3.Styling can have marigins and paddings
    4.Width and height can be set
    Example: `<div>`,`<p>`,`<h1>`,`<ul>`,`<li>`

Inline tags are used to define the structure of a webpage.
    1.Does not start with a new line
    2.Takes up the width of the content
    3.No new line between elements
    4.Styling can't done easily
    Example: `<span>`,`<a>`,`<img>`

#### Div Tag
Div tag is just grouping tags together.
it is Block tag
```html
<div>
    <span>Span</span>
</div>
```

#### Span Tag
Span tag is used to create spans in a webpage.
it is Inline tag

```html
<span>Span</span>
```

---




