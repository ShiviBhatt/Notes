# HTML
- it is the way to markup our content and to bridge the divide between the human language and computer language.
## WEB
- web is made up of 3 programming language HTML, CSS, Javascript
## HTML 
- HTML stands for hypertext markup language
- HTML marks up the content of the website, basically it tells user's computer what things are
- It also provides access to incredible amount of functionality that already built into the browser, we can call those functionality using html
- It is declarative language
- HTML provides a connection of meaning between human world and computer world.

### FORMATTING TEXT
- `<p>` stands for paragrah
- `<>` opening tag `</>` closing tag
- example of tags
    - `<h1>` Headline tag
    - `<p1>` Paragraph tag
    - `<article>` article tag
    - `<em>` emphasized
## CSS 
- Cascading style sheet
## JavaScript
Java Script is a programming language which provides the ability to create more powerful interctivity, the more complex rich an interface becomes, the more likely that javascript is used to make that experience seamless for the site's users.

## Document Object Model (DOM)
- The hierarchy and structure of HTML elements, often used for targeting elements in CSS and Java Script.

## Headlines
There are headlines upto `<h6>`

## Bold and Italics
- In html we want to distinguish between these two cases, we want browser when we want to emphasize and when we want to distinguish.
- The `<i>` is used to apply only visual italics while `<em>` element is used to put emphasis on something.
- The `<strong>` element conveys importance, seriousness and urgency
- If we want to bold certain words in the passage of text without conveying any meaning we can use `<b>` element.

## Lists
- There are three kind of lists
    - Ordered Lists
    - Unordered Lists
    - Definition Lists
Unordered List is used most often.
- `<li>` stands for list items
```
<li>flour</li>
<li>Sugar</li>
<li>baking powder</li>
<li>salt</li>
<li>non- diary milk</li>
<li>apple cider vinegar</li>
<li>vanilla</li>
```
- To make unordered list we use `<ul>`, we pick this because its the right choice to convey meaning.

```
<ul>
    <li>flour</li>
    <li>Sugar</li>
    <li>baking powder</li>
    <li>salt</li>
    <li>non- diary milk</li>
    <li>apple cider vinegar</li>
    <li>vanilla</li>
</ul>
```
- Ordered List `<ol>`
- Definition list `<dt>`
```
<dt> term </dt>
```
- Definition description `<dd>`
```
<dd>definition description</dd>
```
- Whole thing is wrapped up in definition list `<dl>`
```
<dl>
<dt>term</dt>
<dd> defnition term </dd>
</dl>
```

## Quotes
- `<blockquote>`
- `<cite>`
- `<q>`
## Inline Elements
- `<q>` , `<strong>` , `<b>`, `<i>` , `<em>`
## Block Level Elements
- `<blockquote>`, `<p>` , `<ul>`
- `<q>` - for inline phrases
- `<blockquote>` - block context

## Date and Time
- `<time datetime= "time">` `</time>`
## Code And other tags
- code
- `&lt` , `&gt`
- `<br>` - break line tag and its single simple line tag

## Sub script, Super Script and small tags
- subscripts -> character that are set below the text baseline example h20
example: 
```
<p> H <sub> 2 </sub> 0 </p>
<p> something that has a footnote <sup>2</sup>
<p> 2019
```
- small tag -> to convey that has very little prominence `<small>`

## MATH ML
- Markup language language for math

## HTML Attributes
- Global Attributes : Attributes that can be applied to any html element.
    - Four Common Global Attributes 
        - Class Attribute : allow us to target all elements with that class in our CSS or Java Script.
        Example : 
        ```
        <p class = "intro"> text </p>
        ```
        - Id Attribute : Allow us to target unique element with that id in our css and java script.
        Example : 
        ```
        <p class="intro" id="article-intro"> text </p>
        ```
        - `<blockquote contenteditable = "true">`
## Aria Roles
- HTML attributes that provide accessible information about that specific element.
example : `<h1 aria-label="Hellow World">`

## Navigation
- `<nav> </nav>`

## Responsive Width
- The srcset attribute : allows you to specify multiple files to be used based on either viewport width or image pixel width

## Responsive Pictures
- `<picture>` tag : used to display image in any size of screen using srcset attribute

## FigCaption
- `<figure>` : for anything that appears as figure, illustration something.
- `<figcaption>` : for demonstration of a concept which needs a caption.
- `<figcaption> </figcaption>` : this provides the browser with more semantic information about the content. , and wrap image and caption with `<figure>` tag
## Caption and Subtitle
- `<video controls> <track src = "filename.vtt" kind="captions" label="english" srclang="english" default></video>`
## Embeding
- Placing content  from one site into body of a page on another site.

## Generic Elements
- `<div>` : block level element
- `<span>` : inline element

## TABLE
```
<table class= "styled">
<tr>
    <th> Bird</th>
</tr>
<tr>
    <td>American</td>
    <td><img src = "link"></td>
</tr>
</table>
```