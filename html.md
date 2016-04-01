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

## Links
The internet is made up of files that we can load into our browsers. To see these pages we need to use 'links' to see them. Within our web pages, we can make text or a button 'link' to another page so we can help people navigate the internet.

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

## Links
