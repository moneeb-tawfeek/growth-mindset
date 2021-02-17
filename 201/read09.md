Form:  controls live inside a
<form> element. This element
should always carry the action
attribute and will usually have a method and id attribute too.
<br>
Forms can be sent using one of
two methods: get or post.
<br>
With the get method, the values
from the form are added to
the end of the URL specified in
the action attribute.
<br>
With the post method the
values are sent in what are
known as HTTP headers.
<br>

ex: 
<br>

form action="http://www.example.com/subscribe.php"
method="get">
<br>
The input element is used
to create several different form
controls.
<br>
form action="http://www.example.com/login.php">
p>Username:
input type="text" name="username" size="15"
maxlength="30" />
/p>
/form>
<br>
The textarea element
is used to create a mutli-line
text input. Unlike
<br>

ex:
<br>
form action="http://www.example.com/comments.php">
p>What did you think of this gig?</p>
textarea name="comments" cols="20" rows="4">Enter
your comments.../textarea>
/form>

<br>

Radio buttons allow users to pick
just one of a number of options.

<br>
form action="http://www.example.com/profile.php">
p>Please select your favorite genre:
<br />
input type="radio" name="genre" value="rock"
checked="checked" /> Rock
input type="radio" name="genre" value="pop" />
Pop
input type="radio" name="genre" value="jazz" />
Jazz
/p>
/form>
<br>
<br>

Checkboxes allow users to select
(and unselect) one or more
options in answer to a question.

<br>

select>
A drop down list box (also
known as a select box) allows
users to select one option from a
drop down list.

<br>
input : If you want to allow users to
upload a file (for example an
image, video, mp3, or a PDF),
you will need to use a file input
box.
<br>
form action="http://www.example.com/upload.php"
method="post">
p>Upload your song in MP3 format:</p>
input type="file" name="user-song" /><br />
input type="submit" value="Upload" />
/form>
 <br>
Table cells can have different borders and spacing in
different browsers, but there are properties you can
use to control them and make them more consistent.(padding , margin , tabel-collaps )

<br>


Events are the browser's way of indicating when
something has happened (such as when a page has
finished loading or a button has been clicked).

<br>

Binding is the process of stating which event you are
waiting to happen, and which element you are waiting
for that event to happen upon.
<br>

we can use event delegation to monitor for events
that happen on all of the children of an element.
