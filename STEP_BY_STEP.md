
# Learn HTML by Building a Photo App

Course designed by Quincy Larson, freeCodeCamp.org

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

</details>

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

Identify the main section of this page by adding a `<main>` opening tag before the `h1` element, and a `</main>` closing tag after the `p` element.


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

## Step 7 | Add an Image to the Webapp
You can add images to your website by using the `img` element. `img` elements have an opening tag without a closing tag. A tag for an element without a closing tag is known as a self-closing tag.

Add an `img` element below the `p` element. At this point, no image will show up in the browser.

## Step 8 | Add a URL to the Image Source
HTML *attributes* are special words used inside the opening tag of an element to control the element's behavior. The `src` *attribute* in an `img `element specifies the image's *URL* (where the image is located).

Here is an example of an img element with a src attribute pointing to the freeCodeCamp logo:

<details>
<summary> <h3> Example Code </h3></summary>

```html
<img src=img src="https://cdn.freecodecamp.org/platform/universal/fcc_secondary.svg" >
```
</details>

Inside the existing img element, add a src attribute with this URL: 
`![faces.png](https://cdn.freecodecamp.org/platform/universal/fcc_secondary.svg)`

## Step 9 | Add an Alt Attribute to the Image
All `img` elements should have an `alt` attribute. The `alt` attribute's text is used for screen readers to improve accessibility and is displayed if the image fails to load.

Here is an example of an `img` element with an `alt` attribute:

<details>
<summary> <h3> Example Code </h3></summary>

```html
<img src="cat.jpg" alt="A cat">
```
</details>

Inside the `img` element, add an `alt` attribute with this text:
A cute orange cat lying on its back


## Step 10 | Create a Hyperlink
You can link to another page with the anchor `a` element.

Here is an example linking to `https://www.freecodecamp.org`:

<details>
<summary> <h3> Example Code </h3></summary>

```html
<a href="https://www.freecodecamp.org"></a>
```
</details>

Add an anchor element after the paragraph that links to `https://freecatphotoapp.com`. At this point, the link won’t show up in the preview.


## Step 11 | Add Link Text to a Hyperlink
A link's text must be placed between the opening and closing tags of an anchor `a` element.

Here is an example of a link with the text click here to go to freeCodeCamp.org:

<details>
<summary> <h3> Example Code </h3></summary>

```html
<a href="https://www.freecodecamp.org">click here to go to freeCodeCamp.org</a>
```

Add the anchor text link to cat pictures to the anchor element. This will become the link's text.
</details>


## Step 12 | Add a link to the gallery
You can turn any text into a link, such as the text inside of a `p` element.


<details>
<summary> <h3> Example Code </h3></summary>

```html
<p>I think <a href="https://www.freecodecamp.org">freeCodeCamp</a> is great.</p>
```
</details>

In the text of your p element, turn the words cat photos into a link by adding opening and closing anchor `a` tags around these words. Then set the href attribute to `https://freecatphotoapp.com`

## Step 13 | Remove the Second Link
Now that you turned the text cat photos inside the `p `element into a link, you don't need the second link below the `p` element. Delete the entire anchor element below the p element.


## Step 14 | Add target attribute to open links in a new tab
To open links in a new tab, you can use the target attribute on the anchor `a` element.

The `target` attribute specifies where to open the linked document.`target="_blank"` opens the linked document in a new tab or window.

Here is the basic syntax for an `a` element with a target attribute:


<details>
<summary> <h3> Example Code </h3></summary>

```html
<a href="https://www.freecodecamp.org" target="_blank">freeCodeCamp</a>

```
</details>

Add a target attribute with the value `_blank` to the anchor `a` element's opening tag, so that the link opens in a new tab.


## Step 15 | Turn an Image into a Link
In previous steps you used an anchor element to turn text into a link. Other types of content can also be turned into a link by wrapping it in anchor tags.

Here is an example of turning an image into a link:

<details>
<summary> <h3> Example Code </h3></summary>

```html
<a href="example-link">
  <img src="image-link.jpg" alt="A photo of a cat.">
</a>
```
</details>

Turn the image into a link by surrounding it with necessary element tags. 
Use `https://freecatphotoapp.com` as the anchor's href attribute value.


## Step 16 | Add a Section Element
Before adding any new content, you should make use of a `section` element to separate the cat photos content from the future content.

The `section` element is used to define *sections* in a document, such as *chapters*, *headers*, *footers*, or any other sections of the document. It is a **semantic** element that helps with **SEO** and **accessibility**.

<details>
<summary> <h3> Example Code </h3></summary>

```html
<section>
  <h2>Section Title</h2>
  <p>Section content...</p>
</section>
```
</details>

Take your `h2`, comment, `p`, and anchor `a ` elements and nest them in a section element.


## Step 17 | Add a New Section
It is time to add a new `section`. Add a second `section` element below the existing `section` element.

## Step 18 | Add a subheading Element
Within the second `section` element, add a new `h2`element with the text *Cat Lists*.


## Step 19 | Add a Lower Rank Heading Element
When you add a lower rank heading element to the page, it's implied that you're starting a new subsection.

After the last `h2` element of the second `section` element, add an `h3` element with this text:

`Things cats love:`

## Step 20 | Add an Unordered List
To create an **unordered list** of items, you can use the `ul` element.

After the h3 element with the Things cats love: text, add an **unordered list**, `ul` element. Note that nothing will be displayed at this point.

## Step 21 | Add List Items to the Unordered List
The `li` element is used to create a list item in an ordered or unordered list.

Here is an example of list items in an unordered list:

<details>
<summary> <h3> Example Code </h3></summary>

```html
<ul>
  <li>milk</li>
  <li>cheese</li>
</ul>
```
</details>
Within the `ul` element nest three *list items* to display three things cats love:

`cub` `kitten` `puppy` 

## Step 22 | add an new image to the webapp
After the **unordered list**, add a new image with a `src` attribute value set to:

`https://cdn.freecodecamp.org/curriculum/cat-photo-app/lasagna.jpg`

And its `alt `attribute value to: `A slice of lasagna on a plate.`


## Step 23 | Add a Figure Element
The `figure` element represents self-contained content and will allow you to associate an image with a *caption*.

Nest the image you just added within a `figure` element.

## Step 24 | Add a Caption to an Image
A **figure caption**,`figcaption` element is used to add a **caption** to describe the image contained within the `figure` element.

Here is an example of a `figcaption` element with the caption of *A cute cat*:

<details>
<summary> <h3> Example Code </h3></summary>

```html
<figure>
  <img src="image.jpg" alt="A description of the image">
  <figcaption>A cute cat</figcaption>
</figure>
```
</details>

After the image nested in the figure element, add a `figcaption` element with text set to:
`People cherish puppies; Everyone likes puppies.`


## Step 26 | Add a Lower Rank Heading Element
After the *figure* element, add another `h3` element with the text:

`Top 3 things cats hate:`

## Step 27  | Add an Ordered List
The code for an ordered list `ol` is similar to an unordered list, but list items in an ordered list are numbered when displayed.

After the second section element's last `h3` element, add an ordered list with these three *list items*:

`Lack of flexible working` `Poor work-life balance` `quiet firing`

## Step 28 | Add a Figure Element
After the *ordered list*, add another *figure* element.

## Step 29 | Add an Image to a Figure Element
Inside the *figure* element you just added, nest an `img` element with a `src` attribute set to https://cdn.freecodecamp.org/curriculum/cat-photo-app/cats.jpg.

# Step 30 | Add an alternative attribute to an Image
To improve **accessibility** of the *image* you added, add an `alt` attribute with the text:

`Five cats looking around a field.`

## Step 31 | Add a Caption to an Image
After the last `img` element, add a `figcaption `element with the text `Cats hate other cats`.

## Step 32 | Add Strong Element in the Figcaption
The `strong `element is used to indicate that some text is of *strong importance* or *urgent*.

In the figcaption you just added, indicate that hate is of strong importance by wrapping it in a strong element.

## Step 33 | Add a New Section
It is time to add a new section. Add a third `section` element below the second `section` element.

## Step 34 | Add a Heading Element
Inside the third `section` element, add an `h2` element with the text:

`Cat Form`

## Step 35  | Add a Form Element
Now you will add a web form to collect information from users.

The `form` element is used to get information from a user like their name, email, and other details.

After the `Cat Form` heading, add a `form` element.

## Step 36 | Add an Action Attribute to a Form
The `action` attribute indicates where form data should be sent.

Here is an example of a `form` element with an `action` attribute:
<details>
<summary> <h3> Example Code </h3></summary>

```html
<form action="/submit-url"></form>
```
</details>

In the example, `action="/submit-url"` tells the browser that the form data should be sent to the path `/submit-url`.

Add an action attribute with the value `https://freecatphotoapp.com/submit-cat-photo` to the form element.

## Step 37 | Add an Input Element
The `input` element allows you several ways to collect data from a *web form*. Like i`mg` elements, input elements are **self-closing** and do not need closing tags.

Nest an `input` element in the form element.

## Step 38 | Add a Type Attribute to an Input Element
There are many kinds of inputs you can create using the `type` attribute. You can easily create a password field, reset button, or a control to let users select a file from their computer.

Create a *text field* to get text input from a user by adding the `type` attribute with the value `text`to the input element.

## Step 39 | Add a Name Attribute to an Input Element
In order for a form's data to be accessed by the location specified in the `action` attribute, you must give the text field a `name` attribute and assign it a value to represent the data being submitted.

Here is an example of an input element with a `name` attribute:

<details>
<summary> <h3> Example Code </h3></summary>

```html
<input type="text" name="name">
```
</details>

Add the `name` attribute with the value `catphotourl` to your text field.



## Step 40 | Add a Placeholder Attribute to an Input Element
*Placeholder* text is used to give people a **hint ** about what kind of information to enter into an input.

Here is an example of an `input` element with a `placeholder` set to Ex. Jane Doe:
<details>
<summary> <h3> Example Code </h3></summary>

```html
<input type="text" placeholder="Ex. Jane Doe">
```
</details>

Add the *placeholder* text `cat photo URL` to your `input` element.


## Step 41 | Add a Required Attribute to an Input Element
To prevent a user from submitting your form when required information is missing, you need to add the `required` attribute to an `input` element. There's no need to set a value to the `required` attribute. Instead, just add the word required to the `input` element, making sure there is space between it and other attributes.


## Step 42 | Create a Submit Button
The `button` element is used to create a clickable button.

Add a `button` element with the text `Submit` below the `input` element. The default behavior of clicking a form button without any attributes submits the form to the location specified in the form's `action` attribute.


## Step 43 | Add a Button Element with a Type Attribute
Even though you added your button below the text input, they appear next to each other on the page. That's because both `input` and `button` elements are *inline* elements, which don't appear on new lines.

The button you added will submit the form by default. However, relying on default behavior may cause confusion. Add the `type` attribute with the value submit to the button to make it clear that it is a submit button.

## Step 44 | Add Radio Buttons
You can use `radio` buttons for questions where you want only one answer out of multiple options.

Here is an example of a `radio` button with the option of cat:

<details>
<summary> <h3> Example Code </h3></summary>

```html
<input type="radio"> cat
```
</details>
Remember that `input` elements are self-closing.

Before the text input, add a radio button with the option set as:

`Indoor`

## Step 45 | Add a Label Element for the input
`label` elements are used to help associate the text for an `input `element with the `input` element itself (especially for assistive technologies like screen readers).

Here is an example of a `label` element with a `radio` button:

<details>
<summary> <h3> Example Code </h3></summary>

```html
<label><input type="radio"> cat</label>
```
</details>

In the example, clicking on the word "cat" will also select the `radio` button.

Nest your `radio` button inside a label element.


## Step 46 | Add an Id Attribute to a Radio Button
The `id` attribute is used to identify specific HTML elements. Each id attribute's value must be unique from all other id values for the entire page.

Here is an example of an `input` element with an id attribute:

<details> 
<summary> <h3> Example Code </h3></summary>

```html
<input id="email">
```
</details>

Add an `id` attribute with the value indoor to the `radio` button. When elements have multiple attributes, the order of the attributes doesn't matter.

## Step 47 | Create another Radio Button
Create another `radio `button below the first one. *Nest* it inside a `label `element with `Outdoor` as the `label` text. Give the `radio` button an `id` attribute with `outdoor` as the value.


## Step 48 | Add a Name Attribute to a Radio Button
Notice that both `radio` buttons can be selected at the same time. To make it so selecting one radio button automatically deselects the other, both buttons must have a `name` attribute with the same value.

Here is an example of two `radio` buttons with the same `name `attribute:

<details> 
<summary> <h3> Example Code </h3></summary>

```html
<input type="radio" name="meal"> Breakfast
<input type="radio" name="meal"> Lunch
```
</details>

Add the `name `attribute with the value `indoor-outdoor` to both `radio` buttons.


## Step 49 | Add a Value Attribute to a Radio Button
If you select the Indoor radio button and submit the form, the form data for the button is based on its `name` and `value` attributes. Since your `radio` buttons do not have a `value` attribute, the form data will include *indoor-outdoor=on*, which is not useful when you have multiple buttons.

Add a `value` attribute to both radio buttons. For convenience, set the button's v`alue` attribute to the same value as its id attribute.


## Step 50 | Add a Fieldset Element for the radio buttons
The `fieldset` element is used to group related `inputs `and `labels` together in a web form. `fieldset` elements are *block-level* elements, meaning that they appear on a **new line**.

Nest the Indoor and Outdoor `radio` buttons within a `fieldset` element, and don't forget to indent the `radio` buttons.