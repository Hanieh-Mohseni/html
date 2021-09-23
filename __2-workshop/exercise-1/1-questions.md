# HTML Comprehension Questions

## Q1 - For each of the following HTML documents, is the HTML valid?

Type true/false in the provided [ ].

a) [ hello ] `<div><span>hello</div></span>` True

b) [ so making some new changes ]   false

```html
<ul>
<li>one</li>
</ol>  ------->  </ul>
```

c) [ ] `<ul></ul><img/><ol><li>one</li></ol>` True

## Q2 - What is a screenreader and why should we care about them?
How does a screenreader work?
A screen reader uses a Text-To-Speech (TTS) engine to translate on-screen information into speech, which can be heard through earphones or speakers. 
https://www.nomensa.com/blog/what-screen-reader

_Feel free to use the powers of Google here, but please provide link(s) to your source(s)_

## Q3 - For each of the following cases, which tags will be needed?

a) You want to create a webpage with the photos from your latest vacation
<img>

b) You want to create a website that lists all the art gallery websites in your city and links to their website.
<a> and <img>
https://www.w3schools.com/css/css_image_gallery.asp


c) You want to sell designer hats. You need to receive orders from the user.
?

## Q4 - Can a `button` be a child of a `button`? Explain your reasoning

It is not possible to nest a <button> with an <a> element as it isn't valid HTML5. According to HTML5 specification, the <a> tag must not have any interactive content descendant. 

## Q5 - What is the most generic tag you can use?
<HTML>, <Body>
## Q6 - What do the following achronyms stand for?

a) `a` : anchor 

b) `ol` : Ordered List element

c) `ul` : Unordered List element

d) `li` : list items

e) `tr`: Table Row element

f) `th` : a cell as header of a group of table cells.

g) `td` : Table Data Cell element

## Q7 - Usually, `td` elements are children of what kind of elements? 
table

## Q8 - What is the difference between td and th?
th is a cell as header of a group of table cells but td is a table Data Cell element .

## Q9 - Which tag makes the text appear bigger: h1 or h3?
h1

## Q10 - In which situation can you use self closing tags?
It makes little to no difference to a rendering engine in a browser that can parse markup written this way, so the tags can be considered redundant. For mobile users and browsers that can easily parse these pages, it is not necessary to close the tags. Not doing so can save on bandwidth as well. The problem arises when a browser is unable to parse markup written this way.

## Q11 - What is autofilling and why is it important?
The HTML autocomplete attribute lets web developers specify what if any permission the user agent has to provide automated assistance in filling out form field values, as well as guidance to the browser as to the type of information expected in the field.
## Q12 - Which attributes are always present in an img element?
src
## Q13 - Which attribute is always present for an anchor tag?
href