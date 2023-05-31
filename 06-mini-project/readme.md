# MINI PROJECT
- Making of MarioClub Website.

## HTML5 Semantic Tags
<main>- For the main content of a webpage, unique to that page.
<section>- Define a certain section of a webpage. Ex- Blog list, contact info.
<article>- Defines a bit of content which makes up an article.Ex- blog post,news post.
<aside>- Defines some content related to something else.Ex-Similar Blogs.
<header>- For the header of a website-contains the nav,title,etc.
<footer>- For the footer of a website.

## Chrome Developer Tools
- You can inspect the webpage and know a lot about your webpage.
- Can directly select selectors from the inspect option.
- Can apply code and check whether it will suit in the final code or not.
- Can be used for debugging.
- Using sources we can see all the files that make up the webpage. We can also edit them live.
- In console we can do javascript.
- We can also get preview of our website in different devices.

## More CSS Properties

#### Position and Layout
1. **Static**- No special positioning qualities given to this value but it keeps the element in normal document flow of the page.

2. **Relative**- We can shift the element around the page relative to it's original position in the page.
**Syntax**
```css
{
  position:relative;
  left:20px;
  bottom:20px;
}
```
- It will move away 20 pixels left from the original position and 20 pixels from the bottom of original position.

3.**Fixed**- here the element is relative to the viewport.Ex- we have navbar and we could give it position fixed. It will stay there even if we scroll down the page.
**Syntax**
```css
{
  position:fixed;
  left:0px;
  top:0px;
}
```

4.**Absolute**- Absolute position allows us to position things absolutely relative to it's closest parent, which is also given a position property that is not static.
**Syntax**
```css
{
position:absolute;
left:20px;
bottom:20px;
}
```
- 20 pixels left of the parent and 20 pixels from bottom of the parent.

5.**Sticky**- A mixture of static and fixed.

#### Pseudo Classes and Elements
- Pseudo classes and elements are both kind of special keywords that we can use in CSS and add to selectors so that we can target particular elements when they are in a particular state. 
- Ex- When we hover over an element or when a form field is in focus or when an element is the first child of the parent element.
**Syntax** for pseudo class
:hover
:focus
:first-child
**Syntax** for pseudo element
::after
::before
::selection
- Pseudo elements allows to inject dynamic content

## Introduction to Media Queries
- Making the webpage more responsive, i.e making it look good on all devices regardless of the width of the viewport, whether it is a mobile, a tablet or a desktop.

#### Responsive Design

**Media Queries**
- Tell the browser how to style an element at particular viewport dimensions.

**Viewport Meta Tag**
- Tells the browser what width the viewport should be.

**Responsive Images**
- Only load small images for mobile devices.
