# Super quick overview of HTML and parts of a web page

There are ***three languages*** that all web browsers understand:

  1. **HTML** (HyperText Markup Language) -- the ***skeleton*** or the ***structure*** of the page.
  2. **CSS** (Cascading Style Sheets) -- the ***hair and makeup*** or the ***presentation*** of the page.
  3. **JavaScript** (or JS for short) -- the ***brains and nervous system*** that makes decisions, responds to the user, etc.

<br/>

:star: The bare minimum you need to create a web page is ***just an HTML file!*** CSS and JavaScript are entirely optional!

The three languages are saved as three corresponding file types: a `.html` file, a `.css` file, and a `.js` file. 

  > The most common file names, which we'll use today, are: `index.html`, `style.css`, and `script.js` -- just a convention, not a hard rule.

<br/>

## The anatomy of an HTML tag

This is all you need to know about HTML for today's class:

![html-tag-breakdown](https://user-images.githubusercontent.com/1555022/41072152-f7ab0328-69b0-11e8-84f8-8b4beb8628df.png)

<br/>

Beyond that, HTML is a relatively easy language to learn, since its only purpose is to ***label*** parts of your web page: "this is a paragraph, this is the title, this is an image, and they go in this order."

<br/>

  > **Note:** There are *tons* of free online resources to learn HTML! In just a few hours, you'll be able to make your own basic web pages with HTML. For today's class, any HTML for our pages will be *provided* and you'll

<br/>

## Linking JavaScript to your HTML file

Every time you visit a web page, your computer ***downloads all the files*** for that page! Most web pages use all the three native web languages: HTML, CSS, and JavaScript, so most web pages download *at least* those three files.

When you visit a page, your computer first downloads the HTML file. Then it reads that file line by line, from top to bottom, and the HTML file specifies ***which other files*** to download:

<br/>

![linking-html-to-js](https://user-images.githubusercontent.com/1555022/41072150-f5f176ca-69b0-11e8-80f5-21664334912f.png)

The red text and arrow highlights how the HTML file tells the web browser to also download the `script.js` file -- and now the JavaScript code in `script.js` can communicate with the HTML code in `index.html`!

<br/>

  > If you look closely in the image above, you'll also see how the HTML file links the `style.css` so that the HTML can talk to the CSS too. (And by extension, this also lets our JavaScript talk to the CSS if we want it to!)

<br/>
<hr/>

:trophy: ***Great job!*** **[Next up: let's do some group introductions and test out the browser console to run our first lines of JavaScript code!](https://github.com/LearnTeachCode/js-intro-dom/blob/master/1-intro-console.md)**
