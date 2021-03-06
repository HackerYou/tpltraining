![](images/torontopubliclibrarylogo.png)

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

We keep doing this until our page is styled and ready to go!

## Cheat Sheet

background: This property is used to add colour and images to an element's background.

color: This property is used to colour our text. (You need to spell it the American way!)

font-size: The font-size property lets you determine how big or small your text should be. We can use values like 15px or 90px to add size!

font-weight: Do you want bold text, or just normal? Use the font-weight property to change the style of your text.

letter-spacing: Want to create some neat spaced out text? Use letter-spacing to put more or less space between each letter.

line-height: Text too close together? Use line-height to add space between lines!

width: Width allows us to add dimension to our elements. We can use values like 300px or 45%.

height: Height gives us the ability to size up our elements. 

padding: Want a little space on the inside of your elements? Add a some padding. 

margin: Need space between elements? Margin is good for that.

border-width: Want to set a border? Use border-width to decide how thick it should be.

border-style: Choose a solid, dotted, or dashed border.

border-color: Use colours like, red, green or palegoldenrod to give your borders some colour!

text-decoration: Want your text to have an underline? Use text-decoration to set an underline or overline.

More Resources: 
http://css.cool/
http://adamschwartz.co/magic-of-css/
http://www.flexboxdefense.com/
http://flexboxfroggy.com/
