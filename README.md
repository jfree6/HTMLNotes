#HTML/CSS Notes

##HTML/CSS Book One

###Chapter 1 Notes

  HTML uses several tags to control how text is displayed on the page.

  These tags can contain attributes to alter the appearance and function of the
  contained object/text.

  Attributes consist of a name and value.

  Some commonly used tags:

| Tag | Use |
| --- | --- |
| html | opening/closing of an html segment |
| body | opening/closing of the body of a page|
| h1 | Heading |
| h2,...,6 | Sub-headings |
| p | Paragraph text |
| head | Header for the page(info about page) |
| title | title of page |

You can view the "source" of a page to see the html used to create that page.




###Chapter 2 Notes

  HTML will collapse white space.

  Some commonly used structural markup tags:

| Tag | Use |
| --- | --- |
| b | Bolds |
| i | Italics |
| sup | Supertext |
| sub | Subtext |
| /br | Line Break |
| /hr | Horizontal Line |

Some commonly used semantic markup tags:

| Tag | Use |
| --- | --- |
| strong | Strong importance(bold by default) |
| em | emphasis on text(Italics by default) |
| blockquote | for longer quotes |
| q | quotes around text |
| abbr | used for abreviations and acronyms(hover text) |
| cite | refering to a work(renders as italics) |
| dfn | Defining a term(some browsers Italics, some no change) |
| address | contact info for author of page(italics) |
| ins | inserted text(underlined) |
| del | "deleted" text(strikethrough) |
| s | strikethrough |



###Chapter 3 Notes

There are 3 types of lists:

***Ordered*** **&lt;ol&gt;**(numbered)

***Unordered*** **&lt;ul&gt;**(Bulleted)

***Definition*** **&lt;dl&gt;**

**&lt;li&gt;** is line items for **&lt;ol&gt;** and **&lt;ul&gt;**.

**&lt;dt&gt;** are the terms being defined and
**&lt;dd&gt;** are the definitions
 in **&lt;dl&gt;**.

Lists can be nested.

###Chapter 4 Notes

Links can connect webpages, email or another part of the same page.

Links can open in new windows or tabs.

Links use the tag **&lt;a&gt;**, the text between the open and close tags is what the user sees.

The *href* attribute is what it links to.

Links can go to a local html file or another webpage.

To link to a child/grandchild folder use path.

To link to a parent/grandparent folder use ../ or ../../ respectively

Use *mailto:* to link to an email

Use the ***target="_blank"*** attribute to have a link open in a new window

To link to another part of the same page use **#** and set an **id** attribute where you want it to link to

###Chapter 5 Notes

####Stock photos

www.istockphoto.com

www.gettyimages.com

www.veer.com

www.sxc.hu

www.fotolia.com

***img*** is the tag used for images

| attribute     | Use     |
| :------------- | :------------- |
| src       | Location of the image(url or local)       |
| alt | Text to be displayed if image does not load|
| title | hover text for image |
| height | height in pixels |
| width | width in pixels |

####Online Editors

www.photoshop.com

www.pixlr.com

www.splashup.com

www.ipiccy.com

###Chapter 6 Notes

| tag | use     |
| ------------- | ------------- |
| Table       | opens/closes table block       |
|td|table data|
|tr|table row|
|thead|table header|
|tbody|table body|
|tfoot|table footer|
|th|table head|

colspan merges a number of columns on that row

rowspan merges a number of rows in that column

###Chapter 7 Notes

| Tags | Use     |
| :------------- | :------------- |
|form|opens/closes a form block|
|input|Identifies that information will be received and in what form|
|textarea|multi line text block(col & rows)|
|select|Drop down list|
|option|drop down option|
|button|customize buttons|
|label|identifies text as a label for input request|
|fieldset|groups inputs together|
|legend|identifies/labels a fieldset|

| Attribute | Use     |
| :------------- | :------------- |
|action|***req.*** destination of info received|
|method|how to send info(*get=def*)|
|id|create a "name" for block (reference)|
|type|What type of data will be receive|
|name|What to call the data received|
|size|size of input box(does not limit input amount) *old*|
|maxlength|limits length of input|
|value|what to send to server when this option is selected|
|checked|what the default option will be|
|selected|default drop down option|
|multiple|ctrl/command to select > 1|
|for|identifies which form the labeled selection belongs to|
|placeholder|temp text before user types|

|Type=|Use|
|---|---|
|text|single line text input|
|password|single line text input that is "blocked" from view on browser(does not secure data transfer)|
|radio|pick one|
|checkbox|select all applicable|
|file|file upload(method=post)|
|submit|send to server|
|image|image for submit button|
|hidden|"secret" controls |
|date|input date|
|email|input email(some browsers auto check input)|
|url|input web page address(some browsers auto check input)
|search|single line text box for search input|

###Chapter 8 Notes

HTML5 uses &lt;!DOCTYPE html&gt; at the start of the page

&lt;!-- comment --&gt;

***class*** and ***id*** attributes go everywhere

***class*** allows info to be grouped

block level elements always start a new line

inline elements continue on the same line

***div*** allows elements to be blocked together

***span*** groups inline ^

***iframes*** are page within a page(uses src, height, width, seamless(new only))

***meta*** in the **head** and contains page info

###Chapter 9 Notes

####video

|attribute|Use|
|---|---|
|src|Location|
|poster|"preview" image(separate image)|
|width|<-see|
|height|<-see|
|controls|tells browser to use its own controls for video|
|autoplay|specify play on page load|
|loop|loops video|
|preload|tells browser to preload all(auto), metadata(info/stats) or none|

use ***source*** to specify multiple playable formats

src/type(include codecs)

####audio

|attribute|Use|
|---|---|
|src|Location|
|controls|tells browser to use its own controls|
|autoplay|specify play on page load|
|loop|loops video|
|preload|tells browser to preload all(auto), metadata(info/stats) or none|

use ***source*** to specify multiple playable formats

src/type(include codecs)

###Chapter 10 Notes

link a css page->link href="css/styles.css" type="text/css"
 rel="stylesheet" /

 inline css->
 style type="text/css"

|Selector|Use|
|---|---|
|* {}|All|
|h1 {}|matching type|
|.class or p.class {}|all of that class or of that class in those elements(respectively)|
|#id {}|targets id|
|parent>child {}|only targets child of parent|
|parent descendant {}|targets descendants of parent|
|sibling+adjacent|targets only adjacent immediately following sibling|
|sibling~general|all general of sibling|

###Chapter 11 Notes

|Color method|Example|
|---|---|
|RGB Values|color: rgb(100,100,90)|
|Hex Codes|color: #ee3e80|
|Color Name|color: ForestGreen|

opacity: 0.5

color: rgba(100,100,100,0.5)

hsl/hsla(hue, saturation, lightness, alpha(opacity))

###Chapter 12 Notes

|property|Example|
|---|---|
|font-family|font-family: "First Choice Font", Second, generic;|
|font-size|font-size: 12px(pixels) or 200%(of standard 16px(stackswithin descendants)) or 1.3em(1 em is equal to the width of the letter "m")|
|@font-face|@font-face {font-family: 'font name'; src: 'font.location; format: format of font'}|
|font-weight|font-weight: bold or normal|
|font-style|font-style: italic or oblique or normal|
|text-transform|text-transform: uppercase or lowercase or capitalize|
|text-decoration|text-decoration: none or underline or overline or line-through or blink|
|line-height|line-height: 1.4em|
|letter-spacing||
|word-spacing||
|alignment||
|vertical-align||
|text-indent||
|text-shadow||

| pseudo- | Use  |
| :------------- | :------------- |
|:first-letter|sets special values for first letter|
|:first-line|sets special values for first line|
|:link|sets special values for unclicked links|
|:visited|sets special values for clicked links|
|:hover|sets special values for when a user "hovers" over the object|
|:active|sets special values for when an object is activated|
|:focus|sets special values for when an object has focus|

###Chapter 13 Notes

| Property | Use     |
| :------------- | :------------- |
|width|<-see|
|height|<-see|
|min-width|<-see|
|max-width|<-see|
|min-height|<-see|
|max-height|<-see|
|overflow|tells browser what to do with content that exceeds the box(hidden/scroll)|
|border-(top/bottom/left/right)-width|<-see(thin/medium/thick or px)|
|border-style|solid/dotted/dashed/double/groove/ridge/inset/outset/hidden/none|
|border-color|<-see|
|border|allows an all-in-one config|
|padding-(top/bottom/left/right)|space between text and border(px)|
|margin|space between boxes(px)(set to auto on both sides to center)|
|display|inline<->block(inline/block/inline-block/none)|
|visibility|<-see(visible/hidden)|
|border-image|custom border(stretch/repeat/round(repeat w/scaling))|
|box-shadow|<-see (horizontal offset/vertical offset/blur distance/spread of shadow(px))|
|border-radius-(top/bottom/left/right)|rounds corners(px)|

###Chapter 14 Notes

list-style-type: (none/disc/circle/square(ul))

list-style-type: (decimal/decimal-leading-zero/lower-alpha/upper-alpha/lower-roman/upper-roman)

list-style-image: url(image url)

list-style-position: outside/inside

list-style(all in one)

Table properties(width/padding/text-transform/letter-spacing/font-size/border/text-align/background-color/:hover)

empty-cells:(hide/show inherit)

border-spacing:(px)

border-collapse: collapse

cursor:(auto/crosshair/default/pointer/move/text/wait/help/url("cursor.gif")

###Chapter 15 Notes

position: static = normal positioning

position: relative = in relation to where it would normally be positioned

position: absolute = the absolute position on the page

position: fixed = absolute positioning in relation to the browser window

z-index = layering

float = box items and send them in a particular direction

clear = blocks sibling content from appearing on the sides of selected content(l,r,b,n)

@import = import ruler from another style stylesheet

###Chapter 16 Notes

background-image = location/settings for a background image
    repeat = set how the image is repeated(x,y,no,fixed,scroll)

    position = combination (left, center, right) + (top, center, bottom)

###Chapter 17 Notes

Header = tag for Header

footer = tag for footer

nav = tag for navigation selections

article = tag for an article

aside = tag for asides related to an article

section = tag for section (related items)

hgroup = tag for grouping together multiple h tags

figure = tag for object related to article

figcaption = tag within a figure tag for adding a caption to the figure

## HTML/CSS Book Two

###Chapter 1 Notes

Structure your HTML for CSS

code to prep for old browsers:

<!&#45;&#45;[if lt IE 9]>

&lt;script src="//html5shiv.googlecode.com/

svn/trunk/html5.js"></script>

<![endif]&#45;&#45;>

div is empty block container

span is empty inline container

http://validator.w3.org html validator

###Chapter 2 Notes

Internal style sheet is in &lt;style&gt;&lt;/style&gt;

css validator: http://jigsaw.w3.org/css-validator

&lt;link href="location.css" rel="stylesheet"&gt;

linking in css: @import url()

###Chapter 3 Notes

class names are case sensitive

::before = add/edit something before

::after = add/edit something after

::selection = edit what happens when domething is highlighted by user

^= = begins with(ie: a[href^="http://"])

$= = begins with(ie: a[href$=".jpg"])

&ast;= = begins with(ie: a[href&ast;="poke"])

:first-child

:last-child

:nth-child(odd, even, xn+y)(x=how often y=where to start)

:first/last/nth-of-type

:not(not_this) (only simple selectors and pseudo and only once)

###Chapter 4 Notes

Here are examples of times when inheritance doesn’t strictly apply:

 As a general rule, properties that afect the placement of elements on the page
 or the margins, background colors, and borders of elements aren’t inherited.

 Web browsers use their own inherent styles to format various tags: Headings are
 big and bold, links are blue, and so on. When you define a font-size for the
 text on a page and apply it to the &lt;body> tag, headings still appear larger
 than paragraphs, and &lt;h1> tags are still larger than &lt;h2> tags. It’s the
 same when you apply a font color to the <body>; the links on the page still
 appear in good old-fashioned, web-browser blue.

 When styles conflict, the more specific style wins out. In other words, when
 you’ve specifically applied CSS properties to an element—like specifying the
 font size for an unordered list—and those properties conflict with any inherited
 properties—like a font-size set for the &lt;body> tag—the browser uses the font
 size applied to the &lt;ul> tag.

###Chapter 5 Notes

tag = 1

class = 10

id = 100

inline = 1000

tiebreaker is last style

###Chapter 6 Notes

The League of Movable Type (www.theleagueofmoveabletype.com).

Exljbris font foundry (www.exljbris.com).

Fontex.org (www.fontex.org).

The Open Font Library (http://openfontlibrary.org).

Font Squirrel (www.fontsquirrel.com).

Google Fonts (www.google.com/webfonts).

color list https://developer.mozilla.org/en-US/docs/CSS/color_value.

text size: xx-small, x-small, small, medium, large, x-large, and xx-large.

font-variant: small-caps

text-shadow: (amount right) (amount down) (how blurry) (color)


###Chapter 7 Notes

(margin(border(padding(content)padding)border)margin)

margins overlap padding does not

box-shadow:(amount right) (amount down) (how blurry) (color)

Fortunately, CSS3 ofers a property that lets you change how a browser calculates

the screen width (and height) of an element. The box-sizing property provides
three options:

The **content-box** option is the way browsers have always defined the screen
width and height of an element, as described on page 213. That is, the browser
adds the border widths and padding thicknesses to the values set for the width
and height properties to determine the tag’s onscreen width and height. Since
this is the default behavior, you don’t need to specify anything for content-box.

The **padding-box** option tells a browser that when you set a style’s width or
height property, it should include the padding as part of that value. For example,
say you give an element 20 pixels of left and right padding and set the width of
the element to 100 pixels. The browser will consider the padding part of that
100-pixel value. In other words, the content area will be only 60 pixels wide
(100 – 20 [left padding] – 20 [right padding]).

The **border-box** value includes both the padding and the border thickness as
part of the width and height values. This setting solves the problem of using
percentage values for widths discussed above. In other words, with the box-sizing
property set to border-box, when you set an element’s width to 50%, for instance,
that element will take up 50 percent of the space, even if you add padding and
borders to that element.

###Chapter 8 Notes

background images do not print

cover = stretch

contain = enlarge

background-image: repeating-(linear or radial)-gradient((direction), (color), (color) (where to start
change), (color) (where to start change), (color));(direction can be key word or
 degrees(deg))

###Chapter 9 Notes

Pay attention to specificity

You can edit the border on text

display: block/inline-block/inline

</li><li> to remove space between line items


###Chapter 10 Notes

transform: rotate(xdeg)/scale(X/Y)(x,y)/translate(X/Y)(down, right)/
skew(horizontal deg, vertical deg)/

transform-origin- change where the transform begins

transition: properties/all dutation(s) timing(linear/ease/ease-in/ease-out/ease-in-out)

transmition-delay: time to delay

@keyframes animation{
  from{
    start-state
  }
  50%{
    half-way
  }
  to{
    end-state
  }
}

animation: animation-name animation-duration loop-count

timing function work for animations

animation-play-state: play/paused

###Chapter 11 Notes

fieldset tags groups of related form questions

legend groups fieldsets

###Chapter 12 Notes

Page Layout types

Fixed width-page width that does not change with screen size(http://www.nytimes.com/)

Liquid- Uses percentages to adjust to window space, more complicated to correctly
use but makes the most of window real-estate.(http://maps.google.com)

Responsive Web Design(RWD)- Uses media queries to adjust page layout dependent on
screen size and use percentages to maximize screen real-estate.

###Chapter 13 Notes

Use a &lt;br> at the end of a div to ensure it extends to the bottom of the content
 or you can float the div

 multicolumn layout:

 column-count: number of columns;

 column-gap: space between columns;

 column-rule: SH "border:";

 column-rule-width:

 column-rule-style:

 column-rule-color:

column-width:

column:(width)(number)

column-fill:

column-span:

###Chapter 14 Notes

<meta name="viewport" content="width=device-width">(for responsive pages)

<link href="css/small.css" rel="stylesheet" media="((min/max)-width: Xpx) and
((min/max)-width: Ypx)">(HTML5 example)

@viewport { width: device-width; }(css equivalent)

Things to think about when adjusting:

Adjust columns

Use flexible widths

Adjust white-space

Adjust font sizes

Hide content for small screens

Use background images(instead of img tags)

Determine customer usage and build around that form(phone, tablet or desktop)
then adjust to the others

Put the file in your site, and then link it to your page using the <script> tag. For example:

<!--[if lte IE 8]>

<script src="respond.min.js"></script>

<![endif]-->

This little maneuver forces IE 8, 7, and 6 to understand media queries.

The first loads a basic style sheet for all devices, and the second and third load

style sheets using media queries, like this:

@import url(css/base.css); /* no media query, applies to all &ast;/

@import url(css/medium.css) (min-width:481px) and (max-width:768);

@import url(css/small.css) (max-width: 480px);

You can also embed a media query

directly inside a style sheet, like this:

@media (min-width: Xpx) and (max-width: Ypx){

body {

/*style properties go here*/

}

.style1 {

/*style properties go here*/

}

}

###Chapter 15 Notes

positions:

  absolute- the exact location that the object starts at

  relative- move the object this much this direction from where it would normally be

  fixed- stay at this location on the screen(does not scroll with page)

  static- normal positioning

viewport- a browsers screen/window size

tags are relative to their container

z-index controls stacking

visibility can hide/unhide objects

###Chapter 16 Notes

media types: all, braille, embossed, handheld, print, projection, screen, speech, tty, and tv

all - <see

screen - monitor only

print - applies when printed

if no media is specified () assumes all

print can be specified to remove/control parts that would not look good on paper

###Chapter 17 Notes

use comments and naming to clarify page function

use multiple classes when appropriate

group by both function and location

use comments when necessary to clarify

if needed use multiple stylesheets

use style clearing when needed to remove browser settings

use all tools/selector options available to you

test with ie and use separate sheets if needed
