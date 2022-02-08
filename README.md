# Hello ! Myself Naveen, I am a front-end developer

## Here I will explain you what and how to use the HTML5 semantic tags in Frontend Mentor.io

---

## This is the base of a HTML Code (Boilerplate)

### Observer what all it contains its all connected to the semantic tags

```
<!DOCTYPE html>
<html lang="en">
	<head>
		<meta charset="UTF-8" />
		<meta http-equiv="X-UA-Compatible" content="IE=edge" />
		<meta name="viewport" content="width=device-width, initial-scale=1.0" />
		<title>Document</title>
	</head>
	<body>

	</body>
</html>
```

- Here we have `<html lang="en">` it will tell the HTML Language

  - next here we put `<head>` tag in which we have meta tags [Learn more about meta tags](https://www.w3schools.com/tags/tag_meta.asp)

  - Then we put the body tag which will contain all the page contents [Learn about body](https://www.w3schools.com/tags/tag_body.asp)

### What are Semantic Elements?

- A semantic element clearly describes its meaning to both the browser and the developer.

#### Lets take some examples

- non-semantic elements: `<div>` and `<span>` - Tells nothing about its content.
- semantic elements: `<header>`, `<aside>`, and `<section>` - Clearly defines its content.

## Here you can see the layout of a semantic page

![Semantic Layout](https://www.w3schools.com/html/img_sem_elements.gif)

#### The direct children of the body must be wrapped in semantic tags to indicate users about the various purposes of different parts of a webpage.

```
	<body>
		<main class="container">

			<div class="wrapper">

				<header class="title">
					<h1> some title</h1>
				</header>

				<p>some sub paragraph</p>

			</div>

		</main>

	</body>
```

#### HTML `<header>` Element

The `<header>` element represents a container for introductory content or a set of navigational links.

### A `<header>` element typically contains:

    1 one or more heading elements (<h1> - <h6>)
    2 logo or icon
    3 authorship information

### A header for an `<article>`:

```
<article>
  <header>
    <h1>What Does WWF Do?</h1>
    <p>WWF's mission:</p>
  </header>
  <p>WWF's mission is to stop the degradation of our planet's natural environment,
  and build a future in which humans live in harmony with nature.</p>
</article>
```

### A Image Tag

Image tags `(<img>)` must contain alternative text (alt=" ") for a screen reader to read out loud to the user.

For example,

`<img src="images/flower.jpg" alt="Pink flower">`

However, images with no semantic meaning—such as those which are solely decorative—or of limited informational value, should have their alt attributes set to the empty string ("").

[Learn More Here](https://www.w3schools.com/html/default.asp)

#### If this helps you just drop a star to this repo

---

Author : [Naveen Gumaste](https://twitter.com/crazi_monk)
