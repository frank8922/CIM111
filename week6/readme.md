#### Introduction to FTP
FTP - File Transfer Protocol, is how you transfer files onto your server. Comes in 2 versions: FTP and SFTP which is secure.

#### To set or reset your ftp password

In your dreamhost dashboard, go to Users > Manage Users

[Cyberduck](https://cyberduck.io)

#### File structure

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


# Intro to HTML

[Slides](https://github.com/zevenrodriguez/CIM111/blob/master/slides/HTML.pdf)

### INTRO TO BRACKETS

#### What is Brackets?

Brackets is a text editor. While most html can be written notepad or text edit. More modern text editors like Brackets give you advanced options and features that make your life a little easier.

[Getting started](https://github.com/zevenrodriguez/CIM111/blob/master/week3/gettingStarted.html)

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

### Important HTML Tags

[Intro to Tags](https://github.com/zevenrodriguez/CIM111/blob/master/week3/basicTags.html)

#### Head

[doctype](http://www.w3schools.com/tags/tag_doctype.asp) - Defines the document type

[html](http://www.w3schools.com/tags/tag_html.asp) - Defines an HTML document

[head](http://www.w3schools.com/tags/tag_head.asp) - Defines information about the document

[title](http://www.w3schools.com/tags/tag_title.asp) - Defines a title for the document

[link](http://www.w3schools.com/tags/tag_link.asp) - Defines the relationship between a document and an external resource

[meta](http://www.w3schools.com/tags/tag_meta.asp) - Defines metadata about an HTML document

[style](http://www.w3schools.com/tags/tag_style.asp) - Defines style information for a document i.e. CSS

[script](http://www.w3schools.com/tags/tag_script.asp) - Defines a client-side script

[noscript](http://www.w3schools.com/tags/tag_noscript.asp) - Defines an alternate content for users that do not support client-side scripts

#### Comments

[```<!-- ... -->```](http://www.w3schools.com/tags/tag_comment.asp)  - Defines a comment

#### Sections

[body](http://www.w3schools.com/tags/tag_body.asp) - Defines the document's body

[article](http://www.w3schools.com/tags/tag_article.asp) - Defines an article

[nav](http://www.w3schools.com/tags/tag_nav.asp) - Defines navigation links

[aside](http://www.w3schools.com/tags/tag_aside.asp) - Defines content aside from the page content section

[header](http://www.w3schools.com/tags/tag_footer.asp) - Defines a header for a document or section

[footer](http://www.w3schools.com/tags/tag_footer.asp) - Defines a footer for a document or section

[h1-h6](http://www.w3schools.com/tags/tag_hn.asp) - Defines HTML headings

[main](http://www.w3schools.com/tags/tag_main.asp) - Specifies the main content of a document

[address](http://www.w3schools.com/tags/tag_address.asp) - Defines contact information for the author/owner of a document/article

[br](http://www.w3schools.com/tags/tag_br.asp) - Inserts a single line break

#### Grouping

[p](http://www.w3schools.com/tags/tag_p.asp) - Defines a paragraph

[blockquote](http://www.w3schools.com/tags/tag_blockquote.asp) - Defines a section that is quoted from another source

[ol](http://www.w3schools.com/tags/tag_ol.asp) - Defines an ordered list

[ul](http://www.w3schools.com/tags/tag_ul.asp) - Defines an unordered list

[li](http://www.w3schools.com/tags/tag_li.asp) - Defines a list item

[figure](http://www.w3schools.com/tags/tag_figure.asp) - Specifies self-contained content

[figcaption](http://www.w3schools.com/tags/tag_figcaption.asp) - Defines a caption for a ```<figure>``` element

[div](http://www.w3schools.com/tags/tag_div.asp) - Defines a section in a document

#### Tables

[table](http://www.w3schools.com/tags/tag_table.asp) - Defines a table

[tr](http://www.w3schools.com/tags/tag_tr.asp) - Defines a row in a table

[th](http://www.w3schools.com/tags/tag_th.asp) -Defines a header cell in a table

[td](http://www.w3schools.com/tags/tag_td.asp) - Defines a cell in a table

#### Forms

[form](http://www.w3schools.com/tags/tag_form.asp) - Defines an HTML form for user input

[fieldset](http://www.w3schools.com/tags/tag_fieldset.asp) - Groups related elements in a form

[label](http://www.w3schools.com/tags/tag_label.asp) - Defines a label for an <input> element

[input](http://www.w3schools.com/tags/tag_input.asp) -Defines an input control

[button](http://www.w3schools.com/tags/tag_button.asp) - Defines a clickable button

[select](http://www.w3schools.com/tags/tag_select.asp) - Defines a drop-down list

[option](http://www.w3schools.com/tags/tag_option.asp) - Defines an option in a drop-down list

[textarea](http://www.w3schools.com/tags/tag_textarea.asp) - Defines a multiline input control (text area)

#### Embedded

[img](http://www.w3schools.com/tags/tag_img.asp) - Defines an image

[iframe](http://www.w3schools.com/tags/tag_iframe.asp) - Defines an inline frame

[embed](http://www.w3schools.com/tags/tag_embed.asp) - Defines a container for an external (non-HTML) application

[object](http://www.w3schools.com/tags/tag_object.asp) - Defines an embedded object

[video](http://www.w3schools.com/tags/tag_video.asp) - Defines a video or movie

[audio](http://www.w3schools.com/tags/tag_audio.asp) - Defines sound content

[canvas](http://www.w3schools.com/tags/tag_canvas.asp) - Used to draw graphics, on the fly, via scripting (usually JavaScript)

#### Text-level

[a](http://www.w3schools.com/tags/tag_a.asp) - Defines a hyperlink

[em](http://www.w3schools.com/tags/tag_em.asp) - Defines emphasized text

[strong](http://www.w3schools.com/tags/tag_strong.asp) - Defines important text

[i](http://www.w3schools.com/tags/tag_i.asp) - Defines a part of text in an alternate voice or mood

[b](http://www.w3schools.com/tags/tag_b.asp) - Defines bold text

[u](http://www.w3schools.com/tags/tag_u.asp) - Underline

[s](http://www.w3schools.com/tags/tag_s.asp) - Defines text that is no longer correct

[small](http://www.w3schools.com/tags/tag_small.asp) - Defines smaller text

[abbr](http://www.w3schools.com/tags/tag_abbr.asp) - Defines an abbreviation or an acronym

[q](http://www.w3schools.com/tags/tag_q.asp) - Defines a short quotation

[cite](http://www.w3schools.com/tags/tag_cite.asp) -  tag defines the title of a work (e.g. a book, a song, a movie, a TV show, a painting, a sculpture, etc.)

*From w3schools*


## Uploading to your server

* Open and login to your ftp server
* Open the folder with your url on it
* Right click and create a new folder in your main directory
 * Name the folder hw
 * All of your assignements should be placed in this folder



# Homework

* Wordpress project due Oct 2nd & Oct 3rd


