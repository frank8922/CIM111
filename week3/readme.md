###Finishing up Wordpress

####Introduction to FTP
FTP - File Transfer Protocol, is how you transfer files onto your server. Comes in 2 versions: FTP and SFTP which is secure.

####To set or reset your ftp password

In your dreamhost dashboard, go to Users > Manage Users

[Cyberduck](https://cyberduck.io)

####File structure

Important files are located in wp-content. The structure is broken down like:

* wp-content
 * index.php
 * plugins
 * themes
 * upgrade
 * uploads
 
 ####Backing up
 
 The main folder you want to save is the uploads folder. But you can back up the wp-content just in case.

 In wordpress, you want to go to Tools > Export > Download Export File

###First Website (100 Points) - Due Feb 2nd

Create a simple 3 page Wordpress site. 
* Install Wordpress (20 Points)
 * Install a theme (15 Points)
 * Add Menu (15 Points)
* 3 Pages Include: (30 Points)
 * Intro page
   * Include an image of yourself
    * Bio
 * Resume page
 * Interest page
  * Should Include a minimum of 5 Images (10 Points)
* Presentation (10 Points)


#Intro to HTML

###INTRO TO BRACKETS

####What is Brackets?

Brackets is a text editor. While most html can be written notepad or text edit. More modern text editors like Brackets give you advanced options and features that make your life a little easier.

SETTING UP YOUR WORK ENVIRONMENT

When ever you start a new project, you should normally start with these 3 folder and your index.html file in your directory. The index file is the default file a server looks for in your directory.

css or stylesheets
images or media
js or javascript
index.html
INTRO TO HTML



```

<!DOCTYPE html>

<html>

    <head>
        <title>My super awesome website!!!</title>
    </head>

    <body>
        <h1>Hello World!!!!</h1>
    </body>


</html>

```

Important HTML Tags

Head

doctype - Defines the document type
html - Defines an HTML document
head - Defines information about the document
title - Defines a title for the document
link - Defines the relationship between a document and an external resource
meta - Defines metadata about an HTML document
style - Defines style information for a document i.e. CSS
script - Defines a client-side script
noscript - Defines an alternate content for users that do not support client-side scripts
Comments

<!-- ... -->  - Defines a comment
Sections

body - Defines the document's body
article - Defines an article
nav - Defines navigation links
aside - Defines content aside from the page content
section
header - Defines a header for a document or section
footer - Defines a footer for a document or section
h1-h6 - Defines HTML headings
main - Specifies the main content of a document
address - Defines contact information for the author/owner of a document/article
br - Inserts a single line break
Grouping

p - Defines a paragraph
hr - Defines a thematic change in the content
pre - Defines preformatted text
blockquote - Defines a section that is quoted from another source
ol - Defines an ordered list
ul - Defines an unordered list
li - Defines a list item
figure - Specifies self-contained content
figcaption - Defines a caption for a <figure> element
div - Defines a section in a document
Tables

table - Defines a table
tr - Defines a row in a table
th -Defines a header cell in a table
td - Defines a cell in a table


Forms

form - Defines an HTML form for user input
fieldset - Groups related elements in a form
label - Defines a label for an <input> element
input -Defines an input control
button - Defines a clickable button
select - Defines a drop-down list
option - Defines an option in a drop-down list
textarea - Defines a multiline input control (text area)


Embedded

img - Defines an image
iframe - Defines an inline frame
embed - Defines a container for an external (non-HTML) application
object - Defines an embedded object
video - Defines a video or movie
audio - Defines sound content
canvas - Used to draw graphics, on the fly, via scripting (usually JavaScript)


Text-level

a - Defines a hyperlink
em - Defines emphasized text
strong - Defines important text
i - Defines a part of text in an alternate voice or mood
b - Defines bold text
u - Underline
s - Defines text that is no longer correct
small - Defines smaller text
abbr - Defines an abbreviation or an acronym
q - Defines a short quotation
cite
<!DOCTYPE HTML>

<html>

    <head>
        <title>My super dupper awesome website!!!!!</title>
    </head>

    <body>
        <h1>This is a largest header</h1>

        <h2>heading 2</h2>

        <h3>heading 2</h3>

        <h4>heading 2</h4>

        <h5>heading 2</h5>

        <h6>heading 2</h6>

        <p>
            I this is my most favorite class. It is amazing!!!!!
        </p>

        <p>
            This content has a
            </br></br></br></br> break

        </p>

        <p>
            This is a <em>italics</em> tag.
        </p>

        <p>
            This is a <b>bold</b> tag.
        </p>

        <b>This is also bold</b>
        <em>This is also italics</em>

        <p>
            This is also kind of <i>italics</i>.
        </p>

         <p>
            This is a <strong>strong</strong> tag.
        </p>

        <ol>
            <li>pizza</li>
            <li>Chicken Nuggets</li>
            <li>Sesame Chicken</li>
        </ol>

        <ul>
            <li>
                Cheese Cake
                <ol>
                    <li>Chocolate Swirl</li>
                    <li>Key Lime</li>
                    <li>Strawberry</li>
                </ol>

            </li>
            <li>Ice Cream</li>
            <li>Brownies</li>
        </ul>



    </body>

</html>


Assignment:

Go over HTML5 Doctor/ w3schools html types above

Create an html page with a basic bio
head
Add a title
body
Use a header tag
paragraph tag


