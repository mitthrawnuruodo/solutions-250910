# Lesson Task: Expansion Tasks for the 3-Page Website
## 1. Add a Button
* On `index.html`, add a button under the main text.
* When clicked, it should take the user to the About page.
    * Hint: Use a `<button>` and JavaScript (`window.location.href = "about.html"`).

## 2. Add a Form
* On `contact.html`, add a simple form:
    * Name (text input)
    * Email (email input)
    * Message (textarea)
    * Submit and Reset buttons
* Add labels for each field.
* For now, the form doesn’t need to send data anywhere — just build the structure.
    * Can you notice any difference when using post or get method?

## 3. Add an Image
* On `about.html`, insert an image of something meaningful (e.g. a placeholder like `https://cataas.com/cat?width=300&height=200`).
* Add an alt text that describes the image.
* Wrap the image in a `<figure>` with a `<figcaption>` explaining it.

## 4. Add a List
* On `index.html`, create a list of three favorite hobbies or interests:
* Use an unordered list (`<ul>`).
* For at least one hobby, add a nested list of sub-items.

## 5. Add a Table
* On `about.html`, create a table showing three things you’ve learned so far:
    * Column 1: Topic
    * Column 2: Example tag
    * Column 3: Short note
* Add a table header row with `<th>`.

## 6. Add Some Inline Styles
Try using the `style` attribute on a few elements:
* Change the color of one heading.
* Add a background color to one `<div>` or `<section>`.
* Make one paragraph centered.

(Later you’ll replace inline styles with CSS, but practice here is fine.)

## 7. Add Text Formatting
* On any page, try out text formatting tags:
    * Use `<strong>` or `<em>` in a sentence.
    * Highlight something with `<mark>`.
    * Add a math or chemistry example with `<sup>` or `<sub>`.
    * Use `<abbr>` with a tooltip (e.g. HTML, CSS).

## 8. Explore in the Browser
* Open `index.html` with **Live Server**.
* Click the “**Go to About**” button on Home to test JavaScript navigation.
* Check the **figure + caption** and **table** on About.
* Fill and **submit/reset** the form on Contact (it won’t send anywhere yet).
* Use **Inspect** to view elements, attributes, and inline styles.
* Try swapping the image URL with some alternatives if a placeholder service is temporarily down.