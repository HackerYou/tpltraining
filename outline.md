# What is Code.
Code is a way that we as humans can interact with machines. When we use a computer, a phone or a tablet, we are using pre-defined commands to complete tasks.

We can write the commands ourselves by writing in languages designed for computers. To speak to computers via websites we write in HTML and CSS. Using these languages, we can add our own text, give it colour and even include images and videos!

When we write code, we are telling the computer how to translate our code into a language that the computer understands! It then takes our code and tells the tiny parts inside of the computer what to do in order to display it on our screen.

# HTML and CSS
The base languages used by computer, phone and tablet browsers to show webpages are HTML and CSS.

If you think of a webpage as a building, HTML is the foundation and layout while CSS is the design.

## HTML

HTML, or Hyper Text Markup Language is used to define the layout and structure of our web pages.
All webpages use HTML to define how the page should be read and what text and images should be included.

HTML helps us layout the webpage and organize our content into sections that make sense.

Let's take a look at the [Wikipedia page for HTML](https://en.wikipedia.org/wiki/HTML) and identify some common sections throughout. We can clearly see the content on the page organized into different sections such as titles, paragraphs and lists.

## CSS

CSS, or Cascading Style Sheets are how we give our web pages colour and personality. CSS exists as a separate language than HTML, however works well with it!

CSS allows us to change the colour of parts of our page, choose the font to use on our content and even help us layout parts of our page.

## Writing HTML

HTML is made up of predefined _tags_ that wrap our content and define how it should be presented. In the pre-written HTML that Thimble provides, we can see the following tags.

* `<html>`
* `<head>`
* `<body>`

In HTML, tags are written with an opening angle bracket, followed by the name of the tag and completed with a closing angle bracket.

```html
<tagname>
```

Most tags also have a matching closing tag that is written **almost** exactly the same way, except that before the tag name, we place a forward slash - `/` to denote that it is being closed.

```html
</tagname>
```

Inside of the closing and opening tags, we can place content such as text. The full group of opening tag, content and a closing tag is what is known as an _element_.

```html
<tagname>This is content</tagname>
```

We can even put tags inside of other tags, just make sure you're closing the elements in the right order
```html
<tagname>This is content <tagname2>This is other content</tagname></tagname>
```

Of course though, there are no tags called `<tagname>`, there are more descriptive tags we can use to build our webpages. Some available tags are:

- `<p>` - Paragraphs used to 'wrap' text.
- `<header>` - The header tag is used to show the header of a page or section
- `<section>` - A section of the page
- `<article>` _ An article, or group of content on the page
- `<h1>`, `<h2>`, `<h3>` - Content headings. Can be used to create importance of content throughout page.
- `<footer>` - The footer tag can be used to group content together that completes the page or the section.

### Links
The internet is made up of files that we can load into our browsers. To see these pages we need to use 'links' to see them. Within our web pages, we can make text or a button 'link' to another page so we can help people navigate the internet.

A link is what is known as an 'anchor' tag and works just like a `<p>` tag, but also requires some additional information.

```html
<a>Text to click</a>
```

To tell the link where to go, we need to put an 'attribute' called `href` in the opening tag. This attribute also takes a value of where we want to link to.

```html
<a href="http://google.com">Text to click</a>
```

### Images
Besides text on the internet, there are also images. Images are used in HTML a bit different than other tags. First of all, they have no closing tag because we don't need to give it any content!

```html
<img>
```

To tell the `img` tag what image to load in, we provide an `src` attribute that points to the location of the image file.

```html
<img src="dog.jpg">
```

With every image we include, it's important to also include another attribute that will help people understand what image should be there if they are blind or the image doesn't load. We can do this by providing another attribute called `alt` where we pass in 'alternate text'.

```html
<img src="dog.jpg" alt="A picture of a cool dog">
```

With every image, there should be a caption that helps explain the image. To group together the image and caption, we use a `<figure>` element as the 'parent' element and place the caption text in a `<figcaption>` tag.

```html
<figure>
	<img src="dog.jpg" alt="A picture of a cool dog">
	<figcaption>This is my dog Buddy</figcaption>
</figure>
```

## CSS
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

## Programming
Programming languages are used to communicate a set of instructions to a machine. There are many different programming languages for different situations / projects: Objective-C and Swift are used for iPhone apps. Java is used for Android Apps. Ruby, Python and PHP are great for websites and web apps.

The role of programming is to think of a solution to a real-world problem and break the solution down into "code" (simple mechanical instructions that the computer can understand). The computer simply runs the series of instructions in it's environment.

It also helps to try and "think like a computer."  Our spoken language vocabulary is very rich in comparison to most programming languages. We have to be much more explicit and break down instructions into very small steps when speaking to a computer.

**Let's try it together.**

Imagine an alien - of average human intelligence but **only very basic English vocabulary** - has landed in the classroom. How would you give this alien instructions for getting to the washrooms?  

Tell them it's "just down the hall"? Wait. What if they don't know what "hall" means?

We'll have to be more specific.  Think about breaking down all the little steps we take for granted that it takes to get to the washroom.

* Go to the door. Maybe we even have to specify which door out of multiple doors should be used. Maybe we even need to specify "walk forward 10 steps, turn to your left, walk 3 steps" to even *get* to the door.
* Open the door.
* Walk through the door.
* Turn to the right.
* etc.

### Exercise: Computerthink

In small groups, write out detailed step by step instructions for how to make a peanut butter and jelly sandwich. We'll compare your answers together to see just how specific you can get!

### Pseudocode

Sometimes when you're writing JavaScript and other programming language it can be helpful to road-map the detailed steps your program will carry out in plain English, just like we did above.  This is called **pseudocode** and it's a very helpful strategy for getting your ideas about how a program runs out down without worrying about the specific syntax of how to write it. Think of it like outlining an essay with point form notes before going back and filling in each point with complete sentences.

````
when the user scrolls down the page:
* measure how far they've scrolled
* if they've scrolled more than 400px
	- show a tooltip
* otherwise
	- hide the tooltip
````

# Thimble

[Mozilla Thimble](https://thimble.mozilla.org/en-US/) is a free, online tool that allows HTML and CSS to be written directly in the browser and instantly see the result. Thimble also offers the ability to create pre-written projects that can be modified ('remixed') by learners and then published and shared online.

Learners do not require an account to start coding but if you want to save projects, you will need to signup.

All HTML pages require some default, starter code in order to render properly.

```HTML
<!DOCTYPE html>
<html>
<head>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>Made with Thimble</title>
</head>
<body>

  <h1>Welcome to Thimble</h1>

  <p>Make something <strong>amazing</strong> with the web!</p>

</body>
</html>
```

This code will appear by default in any newly created HTML pages within Thimble. It helps tell the browser some information about the page and how to render it.
