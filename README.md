# javascript-dom

When a browser renders a webpage from an HTML document, the browser creats a DOM (Document Object Model). This DOM can be use by JavaScript to add and/or manipulate elements in the document.

## Example DOM

For example, the following HTML:

```html
<!doctype html>
<html>
<head>
    <title>The JavaScript DOM</title>
</head>
<body>

    <h1>The JavaScript DOM</h1>

    <p>Mauris convallis dictum odio. Quisque euismod finibus.</p>

    <a href="https://codeadam.ca">codeadam.ca</a>
    
</body>
</html>
```

Would have the following DOM:

![DOM Chart](https://raw.githubusercontent.com/codeadamca/javascript-dom/main/dom-chart.png)

## Referencing Elements

The easiest method of referencing an element in the DOM is by giving the elements IDs:

```html
<!doctype html>
<html>
<head>
    <title>The JavaScript DOM</title>
</head>
<body>

    <h1 id="heading">The JavaScript DOM</h1>

    <p id="paragraph">Mauris convallis dictum odio. Quisque euismod finibus.</p>

    <a id="link" href="https://codeadam.ca">codeadam.ca</a>
    
</body>
</html>
```

To reference the heading we would use the `document.getElementById('heading')`. We can then use a DOM element to change the properties of the element. For example, to change the heading to red we would use the following JavaScript:

```javascript
document.getElementById('heading').style.color = "red";
```

To change the `href` value of the link we would use the following JavaScript:

```javascript
document.getElementById('link').href = "https://codeadam.ca/learning/javascript-dom.html";
```

## Trying It Out

Create a new HTML document, add a heading, some images, and some paragraphs. Use [Lipsum](https://lipsum.com/) for some quick paragraph content. Add some JavaScript to the HTML document that will complete the following objectives:

1. Change the text colour of the `h1` element.
2. Change the text of the first `p` element.
3. Change the border colour of one of the `img` elements.
4. Change the background colour of the `body` element.

## Tutorial Requirements:

* [Visual Studio Code](https://code.visualstudio.com/) or [Brackets](http://brackets.io/) (or any code editor)

Full tutorial URL: https://codeadam.ca/learning/javascript-dom.html

<a href="https://codeadam.ca">
<img src="https://codeadam.ca/images/code-block.png" width="100">
</a>
