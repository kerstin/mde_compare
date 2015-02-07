#MDE Compare
Test file for comparing different Markdown environments.

##Line breaks

###Newlines created by pressing the Enter key

This text is followed by a newline.
This text is followed by two newlines (resulting in an empty line).

This text immediately follows the line break method used above.

###Linebreaks created using the HTML `<br>` tag.

This text is immediately followed by a `<br>` tag.<br>
This text is immediately followed by two `<br>` tags.<br><br>This text immediately follows the line break method used above.

###Mixed line breaks

This text is immediately followed by two `<br>` tags and a newline.<br><br>
This text is followed by a newline, a `<br>` tag and another newline.
<br>
This text is followed by two newlines, a `<br>` tag and two more newlines.

<br>

This text immediately follows the line break method used above.

##Lists
###Unordered lists

This line is followed by a newline, which is immediately followed by bullets for different levels of list depth (which are all separated by newlines also)
* level 1
* level 1
    * level 2
        * level 3
    * level 2 again
* level 1 again 
This line immediately follows the newline after the last bullet point, "level 1 again".
<br>
This line is offset from the bullets below by two newlines/one empty line.

* level 1
* level 1
    * level 2
        * level 3
    * level 2 again
* level 1 again

This line is offset from the last bullet point, "level 1 again", by two newlines.
##Code Blocks

Examples of code blocks (actually: regular text containing HTML tags) generated using different methods.

###Backticks
These code blocks start and end with three backticks ```` ``` ````.

This line of text is followed by a newline
```This is some text formatted as code using backticks. It's regular text on purpose to test how different Markdown software handles wrapping of such text. I'll also throw a long HTML-formatted link in here: <a href="http://i.guim.co.uk/static/w-620/h--/q-95/sys-images/Film/Pix/pictures/2014/12/4/1417687817859/Forum-menace---an-image-f-011.jpg">http://i.guim.co.uk/static/w-620/h--/q-95/sys-images/Film/Pix/pictures/2014/12/4/1417687817859/Forum-menace---an-image-f-011.jpg</a>```

This line of text is followed by two newlines

```This is some text formatted as code using backticks. It's regular text on purpose to test how different Markdown software handles wrapping of such text. I'll also throw a long HTML-formatted link in here: <a href="http://i.guim.co.uk/static/w-620/h--/q-95/sys-images/Film/Pix/pictures/2014/12/4/1417687817859/Forum-menace---an-image-f-011.jpg">http://i.guim.co.uk/static/w-620/h--/q-95/sys-images/Film/Pix/pictures/2014/12/4/1417687817859/Forum-menace---an-image-f-011.jpg</a>```

###Spaces
These code blocks start with four spaces (i.e. they are indented).

This line of text is followed by a newline
    This is some text formatted as code using backticks. It's regular text on purpose to test how different Markdown software handles wrapping of such text. I'll also throw a long HTML-formatted link in here: <a href="http://i.guim.co.uk/static/w-620/h--/q-95/sys-images/Film/Pix/pictures/2014/12/4/1417687817859/Forum-menace---an-image-f-011.jpg">http://i.guim.co.uk/static/w-620/h--/q-95/sys-images/Film/Pix/pictures/2014/12/4/1417687817859/Forum-menace---an-image-f-011.jpg</a>

This line of text is followed by two newlines

    This is some text formatted as code using backticks. It's regular text on purpose to test how different Markdown software handles wrapping of such text. I'll also throw a long HTML-formatted link in here: <a href="http://i.guim.co.uk/static/w-620/h--/q-95/sys-images/Film/Pix/pictures/2014/12/4/1417687817859/Forum-menace---an-image-f-011.jpg">http://i.guim.co.uk/static/w-620/h--/q-95/sys-images/Film/Pix/pictures/2014/12/4/1417687817859/Forum-menace---an-image-f-011.jpg</a>

###Pre tag
These code blocks are surrounded by the HTML `<pre></pre>` tag (for pre-formatted text). Pre interprets HTML tags.

This line of text is followed by a newline (with pre it doesn't seem to make a difference if it's preceded by one, two or no newline; pre-formatted code blocks appear to always display below the text preceding them)
<pre>This is some text formatted as code using backticks. It's regular text on purpose to test how different Markdown software handles wrapping of such text. I'll also throw a long HTML-formatted link in here: <a href="http://i.guim.co.uk/static/w-620/h--/q-95/sys-images/Film/Pix/pictures/2014/12/4/1417687817859/Forum-menace---an-image-f-011.jpg">http://i.guim.co.uk/static/w-620/h--/q-95/sys-images/Film/Pix/pictures/2014/12/4/1417687817859/Forum-menace---an-image-f-011.jpg</a></pre>


