# style-guide

goaL:
- create my own style guide
- practice HTML & CSS fundamentals

inspo:
- https://www.sushiandrobots.com/style-guide

<br>
<br>
<br>

<h1>s k i l l s  t o  p r a c t i c e</h1>
<h2>HTML</h2>
<h3>Semantic markup</h3>

- know what all the html elements are & what they're used for,
- why are they meaningful/or not
  - h1-h6
  - abbreviation
  - paragraph
  - div, whats it for, why would/not you use a div,its a value of nothing
  - section
  - aside
  - main
  - article
<br>
<br>

<h3>Accessibility</h3>

- start with Syntax podcast by Scott Tolinksky & Wes Bos
- https://syntax.fm/show/072/accessibility

-https://dev.to/kenbellows/stop-using-so-many-divs-an-intro-to-semantic-html-3i9i

<br>
<br>


<h3>Attributes<h3>
<h4>ID</h4>

- often misused, it should be unique and only applied to one thing on the page, the same thing every time
- cool usage... if you put #id in the url bar, the browser will jump straight to that id
  - so you can jump straight to that part of the page
  - if your heading tags don't have the id's then you can't link someone to a specific section on the page
  - e.g. [https://reactjs.org/docs/getting-started.html#javascript-resources](https://reactjs.org/docs/getting-started.html#javascript-resources)
  - for gatsby or wordpress, there are plugins that will automatically generate ids
<br>
<br>


<h4>Form</h4>

- name, action,
- even if you are doing forms in javascript
- how you associate labels with inputs
- what happens when you submit it
- form submission
- use regular html attributes in javascript
<br>
<br>


<h4>Class</h4>

- can be used all over the place
- you're denoting what something is
- used for a CSS selector

<br>
<br>



<h2>CSS</h2>

<h3>Specificity</h3>

- the order in which css properties/visual components are applied
- different topics & selectors have different levels in CSS
- do not use important tag unless its Friday at 4.45pm, ok no don't do it
- don't do in something big, without spending the time to study it first
<br>
<br>


<h3>Selectors</h3>

- class, id, descendant, direct descendant, attribute
- area-open, area-selected, disabled selectors
<br>
<br>


<h3>Setting up Layouts</h3>

<h4>Flexbox & Grid</h4>

- and changing them with a breakpoint
- future: nested grid, subgrid, auto fit min max
<br>
<br>


<h4>Box model</h4>

- how padding, margin, border, effect the size of the box
- use dev tools and view the diagram
- most people use border box, but you should know how they effect one another without

[https://css-tricks.com/inheriting-box-sizing-probably-slightly-better-best-practice/](https://css-tricks.com/inheriting-box-sizing-probably-slightly-better-best-practice/)

<br>
<br>


<h4>Positioning</h4>

- too many devs using/abusing position absolute
- knowing how position works, in relation to its parents, and what their position are
- absolute, relative, fixed, sticky, static(default)
<br>
<br>


<h4>Forms & Inputs</h4>

- we need to make our styling of these look good in every browser
- respect the default and override it
- especially aligning forms, making them look like the mockup
- stateful html: inputs can be empty, have placeholders, have text in them, be invalid, valid, hovered, focused, visited links,
- visited link, you can not get the colour of a visited link via javascript. because there was a hack, where someone listed every url out there, then visited display block, the rest display none, then they grabbed the visible ones, and then you could link over links, and say if this link is purple, thats a security issue, because you can tell a users visiting history, while theyre on your website. so you can not get information from visited links styling via javascript
- field set tag - for groups of inputs, you can disable it (a form tag won't)
<br>
<br>


<h4>Block vs Inline vs Inline-block</h4>

- !! important study this !!
- what an element is,
- every HTML element has a default setting
- determines how an element takes up space on the page
- typically block elements are going to be 100% width or what specified, can take on a height, they're used as containers or a paragraph
    - h, paragraph
- inline, will fall inline
    - span, anchor tag
- inline-block
- display none
- huge foundational fundamentals
<br>
<br>


<h4>Sizing Units</h4>

- see podcast!!! https://syntax.fm/show/107/hasty-treat-css-units
- rems, ems, are sized based on something else, the parent item (similar to absolute & relative)
- why / why not use pixels, %
- pixels vs ems vs rems, know where the differences are & when to use
- % vs pixels, know when to use them, know why theyre there
- fr unit for grid, only need to learn this when learning grid
<br>
<br>


<h4>Typography</h4>

- knowing about collapsing margins
- !!! how margins work & line height
    - adjacent siblings, if there margins collide, they will collapse into the largest possible margin
    - this allows you to build very consistent looking typography systems
    - learning about collapsing margins helps you to write better css, less overrides, coz i'm letting css & html do the job they're meant to do
- a font stack!??
<br>
<br>


<h4>MEDIA QUERIES</h4>

- mobile first
    - things go from small up
- desktop first
