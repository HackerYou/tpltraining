# CSS
HTML on it's own is not very pretty. That's where CSS comes in. It allows us to add colour, dimensions and personality to our content. CSS is a different language than HTML but they go together very well.

To style HTML with CSS, we first need to 'select' it. An example is a `<header>`. To select the element and apply styles, we write the name of the element without angle brackets followed by squiggly brackets

```css
header {}
```

Now inside of the curly braces we can put in 'properties', which are things we want to change to the style of the element. An example would be the background color. We can use a property called `background-color` and give it a colour to use.

```css
header {
	background-color: blue;
}
```

Notice how we put a `:` between the property name and the value? That's really important. As well, we finished the line with a `;` which acts almost like a period on a sentence. We can put multiple properties on elements and the `;` is how we separate them. Let's change the size of the text inside the `header`.

```css
header {
	background-color: blue;
	font-size: large;
}
```

When we added another property and value, we followed the same pattern: we gave it a property, separated it with a ':', provided a value and finished it with a `;`.

To style something else on the page, we create another selector and provide more properties.

```css
header {
	background-color: blue;
	font-size: large;
}

section {
	background-color: red;
}
```
