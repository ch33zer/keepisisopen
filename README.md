keepisisopen
============

This is a bookmarklet that will stop isis from prompting you to keep it open every 3 seconds!

Install
---------

Copy the following line to your clipboard

    javascript:(function(){window.confirm=function(a){return true;};})();

Now create a new bookmark called whatever you want (Keep Isis Opened works for the lazy)

Paste the line you copied above into the URL field of the new bookmark.

You're done!

Use
--------
1. Go to a page on isis
2. Click the bookmark

Todos/Notes
---------

I wouldn't use this if I was actively using isis to change classes and stuff, since this will automaticly accept all prompts which is a bad thing if you are doing sensitive work

If you navigate to a different page on isis then you will need to press the bookmark again

Don't worry about pressing it multiple times. It won't break anything. 

If you want to disable it, just refresh the page
