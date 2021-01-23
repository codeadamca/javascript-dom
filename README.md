# javascript-dom

When a browser renders a webpage from an HTML document, the browser creats a DOM (Document Object Model). This DOM can be use by JavaScript to add and/or manipulate elements in the document.

##Example DOM

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

To reference the heading we would use the `document.getElementById('heading')`. We can then use a DOM element to change the properties of the element. FOr example, to chagne the heading to red we would sue the following JavaScript:

```javascript
document.getElementsById('heading')[0].style.color = "red";
```

## 
