## Step 1 | Set the Heading Element level 1 as the main heading
HTML elements have an opening and closing tag with content in between.

Here is the basic syntax:



<details>
<summary> <h3> Example Code </h3></summary>

```html
<openingTag>content</closingTag>
```
</details>

The first element you will learn about is the `h1` element. The `h1` element is a heading element and is used for the main heading of a webpage.

<details>
<summary> <h3> Example Code </h3></summary>

```html  
<h1>This is a main heading</h1>
```
</details>

Change the text of the h1 element below from *Hello World* to *CatPhotoApp* and watch the change in the browser preview.

When you are done, press the **Check Your Code** button to see if it's correct.


## Step 2 | Add an Heading Element level 2 as a subheading
The `h1` through `h6` heading elements are used to signify the importance of content below them. The lower the number, the higher the importance, so `h2` elements have less importance than `h1` elements.

<details>
<summary><h3>Example Code </h3></summary>

```html
<h1>most important heading element</h1>
<h2>second most important heading element</h2>
<h3>third most important heading element</h3>
<h4>fourth most important heading element</h4>
<h5>fifth most important heading element</h5>
<h6>least important heading element</h6>
```
</details>

Only use one `h1` element per page and place lower importance headings below higher importance headings.

Below the `h1` element, add an `h2 `element with this text :  Perky Photos


## Step 3 | Add a Paragraph Element
The `p `element is used to create a paragraph of text on websites. Create a `p` element below your `h2` element and give it the following text, See more motiviting photos in the gallery.

## Step 4 | Add a Comment in HTML
Commenting allows you to leave messages without affecting the browser display. It also allows you to make code inactive. A comment in HTML starts with `<!--`, contains any number of lines of text, and ends with `-->`.

Here is an example of a comment with the `TODO: Remove h1`:

<details>
<summary> <h3> Example Code </h3></summary>

```html
<!-- TODO: Remove h1 -->
 ```



Add a comment above the p element with this text:

`TODO: Add link to photos`

## Step 5 | Add a Main Element
HTML5 has some elements that identify different content areas. These elements make your HTML easier to read and help with Search Engine Optimization (SEO) and accessibility.

The `main` element is used to represent the main content of the body of an HTML document. Content inside the `main` element should be unique to the document and should not be repeated in other parts of the document.

<details>
<summary> <h3> Example Code </h3></summary>

```html
<main>
  <h1>Most important content of the document</h1>
  <p>Some more important content...</p>
</main>
```
</details>

Identify the main section of this page by adding a <main> opening tag before the `h1` element, and a </main> closing tag after the `p` element.


## Step 6 | Nest Elements and indent
In the previous step, you put the `h1`,`h2`, *comment*, and `p` elements inside the main element. This is called *nesting*. Nested elements should be placed two spaces further to the right of the element they are nested in. This spacing is called *indentation* and it is used to make HTML easier to read.

Here is an example of *nesting* and *indentation*:

<details>
<summary> <h3> Example Code </h3></summary>

```html
<main>
  <h1>Most important content of the document</h1>
  <p>Some more important content...</p>
</main>
```
</details>
The `h1` element, `h2` element and the *comment* are indented two spaces more than the main element in the code below. Use the space bar on your keyboard to add two more spaces in front of the `p` element so that it is indented properly as well.

