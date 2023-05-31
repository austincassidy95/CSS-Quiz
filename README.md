👋 Welcome!
=================

**Let's go over how to use Glitch and edit the template...**

Updates to your code will instantly be rendered in the preview panel and the live site. To view the site in a separate window, click the Settings button at the top of the preview panel \(three dots\); you may need to refresh that window to display changes.

To view the public URL of your site, click the big "Share" button at the top of the editor. You can also add collaborators \(such as your instructor\) there. 

You can visit the official documentation for more info about [using Glitch](https://help.glitch.com/kb/section/2/).

---

## Project Files

### ← `README.md`

You're currently viwing this file.

### ← `index.html`

Where you'll write the *content* of your website. 

### ← `style.css`

CSS files add *visual styling rules* to your content.

Don't use inline CSS or put it in the `<head>`of your site. This makes it hard to keep track of where a given CSS style is defined. It's much easier to keep your content and visual styles separate so that one can be updated without worrying about the other.


### ← `Assets`

Import assets like images or music, to add them to your project. Select an image to get its URL and paste that into your HTML.

A file's URL will look like: 

`https://cdn.glitch.global/04330931-9ec7-4111-8860-97fb6dc1ff85/your-file-name.jpg?v=1656016313331`

And you would add that to your site with an [<img>](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/img) element like this:

`<img alt="description of image" src="https://cdn.glitch.global/04330931-9ec7-4111-8860-97fb6dc1ff85/your-file-name.jpg?v=1656016313331"`


---

## ⚙️ The Grid Layout

This template creates a simple one page website based on a 12 column grid. 

The grid is created with the CSS property `display: grid` which you can read in this [beginner's guide](https://www.freecodecamp.org/news/a-beginners-guide-to-css-grid-3889612c4b35) or this [other guide](https://elad.medium.com/css-grid-for-beginners-ee649080529b). CSS Tricks has a [comprehensive glossery](https://css-tricks.com/snippets/css/complete-guide-grid/) of grid properties that may also b helpful.

The immediate child elements of `<main>` elements will be arranged into the grid automatically, as space permits. I.e. if an element is occupying 9/12 columns, there won't be space for something set to `grid-column: span 6;` ...so that second element would be bumped down to the next row. Using this bumping behavior, you may not even need to define rows with [grid-template-rows](https://developer.mozilla.org/en-US/docs/Web/CSS/grid-template-rows).

Give elements a unique `class` and then set how many columns or rows they should occupy in `styles.css` with [grid-column](https://developer.mozilla.org/en-US/docs/Web/CSS/grid-column) or [grid-row](https://developer.mozilla.org/en-US/docs/Web/CSS/grid-row).

You can nest HTML elements inside one another or even apply `display: grid` to a grid item within the main grid. 

---


ℹ️ HTML & CSS Support
-------------

Both the HTML and CSS files included extensive comments \(displayed in gray\) to help you figure out what each line of code does. To turn any line of code into a comment \(or uncomment it\), press `⌘ + Foreward Slash` \(Mac\) or `CTRL + Foreward Slash` \(Windows\).

Try changing lots of things to see what happens in the rendered website!

You can always [rewind](https://help.glitch.com/kb/article/21-rewind/) to previous states of your proejct is you mess something up. 

For more help with the basics of HTML and CSS, check out [Interneting is Hard](https://internetingishard.com/html-and-css/).
