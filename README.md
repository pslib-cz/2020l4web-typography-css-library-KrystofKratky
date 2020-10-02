# Typography CSS library
**Author:** *Kryštof Krátký*
## Demo site
Link to **[demo](http://www.github.io)** site for preview.
# Blog typography
## Implementation
```html
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <!--Link of style-->
    <link rel="stylesheet" href="./style.css">
    <!--Link of font family-->
    <link href="https://fonts.googleapis.com/css2?family=Work+Sans:ital@0;1&display=swap" rel="stylesheet">
    <title>Blog typography</title>
</head>
```
## Usage
This library changes styles of these tags:
* h1, h2, h3, h4, h5
* p, s, strong, b, i, q
* ul, ol, li
* figure, figcaption, img
* nav, header footer
### How to apply style to lists:
```html
<ul class="unordered-list">
            <li>List item</li>
            <ul class="unordered-list">
                <li>List item</li>
            </ul>
            <li>List item</li>
            <li>List item</li>
            <li>List item</li>
        </ul>
        <h4>Fourth-level heading</h4>
        <ol class="ordered-list">
            <li>List item</li>
            <ol class="ordered-list">
                <li>List item</li>
            </ol>
            <li>List item</li>
            <li>List item</li>
            <li>List item</li>
        </ol>
```
How to write an article:
```html
 <article>
            <h2>Second-level heading</h2>
            <p>Lorem ipsum <b>dolor</b> sit <strong>amet</strong> consectetur adipisicing elit. <i>Quisquam iure</i>, sed velit magni magnam modi
                quod! Rem,
                odit explicabo at <s>ipsum</s> quis mollitia pariatur sapiente, odio impedit voluptate et tempore!</p>
        </article>
```
## Components
* Image
* Header and navigation
* Footer
### Image
```html
<figure><img src="./assets/coffee-1030971_1920.jpg" alt="coffee">
            <figcaption>Capuccino</figcaption>
        </figure>
```
### Header and navigation
```html
<header>
            <h1>First-level heading</h1>
            <div class="header-panel">
                <p class="author"><span>name surname</span></p>
                <nav>
                    <h2>Navigation</h2>
                    <ul class="navigation-list">
                        <li><a href="">List item</a></li>
                        <li><a href="">List item</a></li>
                        <li><a href="">List item</a></li>
                    </ul>
                </nav>
            </div>
        </header>
```
### Footer
```html
 <footer>
            <p>&copy;Kryštof Krátký</p>
        </footer>
```