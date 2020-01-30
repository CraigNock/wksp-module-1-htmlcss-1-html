# HTML Comprehension Questions
test

## Q1 - For each of the following HTML documents, is the HTML valid?

Type true/false in the provided [ ].

a) [false] `<div><span>hello</div></span>`

b) [false]

```html
<ul>
<li>one</li>
</ol>
```

c) [true] `<ul></ul><img/><ol><li>one</li></ol>`

technically valid, probably not best practice though


## Q2 - What is a screenreader and why should we care about them?

_Feel free to use the powers of Google here, but please provide link(s) to your source(s)_

Software primarily used by the blind or visually impaired (also people with learning disabilities) to present webpages in a non-visual or alternate visual manner. For example to braille or audio.

Source : https://en.wikipedia.org/wiki/Screen_reader

It is important to know and care about screen readers, as it is important to write html that is easily read by them. Without doing so, your content will not be appropriately Accessible.


## Q3 - For each of the following cases, which tags will be needed?

a) You want to create a webpage with the photos from your latest vacation

img, figure (also standard h1, div, p etc if adding text content)

b) You want to create a website that lists all the art gallery websites in your city and links to their website.

ul or ol, li, anchor, possibly img and figure if displaying logos or examples. also headers, divs and paragraphs

c) You want to sell designer hats. You need to receive orders from the user.

headers, paragraphs, ol, ul, li, img, figure, input, button, select, option

## Q4 - Can a button be a child of a button? Explain your reasoning

No: A button can contain no interactive content. Only Phrasing.
It's not meant to contain other elements, just to be a button.


## Q5 - What is the most generic tag you can use?

div


## Q6 - What do the following achronyms stand for?

a) `a` anchor

b) `ol` ordered list

c) `ul` unordered list

d) `li` list item

e) `tr` table row

f) `th` table head

g) `td` table data


## Q7 - Usually, `td` elements are children of what kind of elements?
tr : table row


## Q8 - What is the difference between td and th?

th is table head; indicating the title(header) of a column of the table
td is table data; used to input a cell of data into the row of the table

## Q9 - Which tag makes the text appear bigger: h1 or h3?

h1

## Q10 - In which situation can you use self closing tags?

if the tags have no children (ie img)

## Q11 - What is autofilling and why is it important?

form data automatically being filled in without user interaction
It saves a lot of time and hassle, makes a site more user friendly.

## Q12 - Which attributes are always present in an img element?

scr : the source of the image
alt : alternate text description of the image

## Q13 - Which attribute is always present for an anchor tag?

href : the reference for the link

