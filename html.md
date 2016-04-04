# HTML

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

Inside of the closing and opening tags, we can place content such as text.

```html
<tagname>This is content</tagname>
```

We can even put tags inside of other tags, just make sure you're closing the tags in the right order.

```html
<tagname>This is content <tagname2>This is other content</tagname2></tagname>
```

Of course though, there are no tags called `<tagname>`, there are more descriptive tags we can use to build our webpages. Some available tags are:

- `<p>` - Paragraphs used to 'wrap' text.
- `<header>` - The header tag is used to show the header of a page or section.
- `<section>` - A section of the page.
- `<article>` _ An article, or group of content on the page.
- `<h1>`, `<h2>`, `<h3>` - Content headings. Can be used to create importance of content throughout page. An `h1` is the more important heading on the page.
- `<footer>` - The footer tag can be used to group content together that completes the page or the section.

## Links
The Internet is made up of files that we can load into our browsers. To see these pages we need to use 'links' to see them. Within our web pages, we can make text or a button 'link' to another page so we can help people navigate the Internet.

A link is what is known as an 'anchor' tag and works just like a `<p>` tag, but also requires some additional information.

```html
<a>Text to click</a>
```

To tell the link where to go, we need to put an 'attribute' called `href` in the opening tag. This attribute also takes a value of where we want to link to.

```html
<a href="http://google.com">Text to click</a>
```

## Images
Besides text on the internet, there are also images. Images are used in HTML a bit different than other tags. First of all, they have no closing tag because we don't need to give it any content!

```html
<img>
```

To tell the `img` tag what image to load in, we provide a `src` attribute that points to the location of the image file.

```html
<img src="dog.jpg">
```

With every image we include, it's important to also include another attribute that will help people understand what image should be there if they are blind or the image doesn't load. We can do this by providing another attribute called `alt` where we put out alternate text, or a small description of the image.

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

## Lists

Images and links are great! But what if we want to create some organization in our content? In HTML we have lists to help us do this, there is the `ul`, `ol` and `li` tag. 

```html
<ul>
	<li>List item</li>
</ul>
```

`ul` is an unordered list, inside of this tag we can put as many `li` tags inside of it as we want. `li` tags are list item tags, these will hold our content.

```html
<ol>
	<li>List item</li>
</ol>
```

`ol` is an ordered list, the only different between this tag and the `ul` tag is that an `ol` tag is used to create an ordered list of items. Visually a `ol` will have numbers beside each item, while a `ul` will just have bullets.

#### When to use `ul` vs `ol`

When should you use a `ul` or an `ol`. Well if you need you information in a specific order, pick `ol`. For example a list of your top 5 favourite movies. 

```html
<ol>
	<li>Harry Potter and the Deathly Hallows Part 2</li>
	<li>Harry Potter and the Deathly Hallows Part 1</li>
	<li>Harry Potter and the Half-Blood Prince</li>
	<li>Harry Potter and the Order of the Phoenix</li>
	<li>Harry Potter and the Goblet of Fire</li>
</ol>
```

If you don't mind the order that the content comes in, use a `ul`. For example, a list of groceries would work well as a `ul`.

```html
<ul>
	<li>Cheese</li>
	<li>Chips</li>
	<li>Ice Cream</li>
	<li>Broccoli</li>
</ul>
```







