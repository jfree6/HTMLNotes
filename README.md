#HTML/CSS Notes

##HTML

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
