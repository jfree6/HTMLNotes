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
