# 01 HTML CSS Git: Code Refactor (Week 1 Homework)

## Horiseon website
A simple website for a search engine optimization company. I was tasked with making the website more accessible using semantic tags, alt text for images, etc.

## Changes to code

* Added more descriptive title.
* Replaced <div> tags with relevant semantic tags when possible, and updated the CSS to style those tags (eliminating some classes).
* Combined three redundant classes ("benefit-lead", "benefit-brand" "benefit-cost") into "benefit" class.
* Addeed alt text for all non-background images (see "Open questions" section).

## Open questions

* The large "hero" image, as it is labeled a background image and linked in the CSS, was not given alt text. To me, this raises a question: what determines if an image deserves/needs alt text? Is it just whether it's linked in the CSS?
* I couldn't figure out how to make the header background behave and cover the links once they rearrange as you shrink the viewport.