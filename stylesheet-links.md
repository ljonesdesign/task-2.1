You need to put the external css external link tags with the rel attribute
in the index.html file. Look in the index.html file to see the comment for where they go.

[help if you need it: How to do CSS links](http://www.w3schools.com/css/css_howto.asp)

Look at the site in a browser before you add these one by one, so that you can see the changes as you make them.

```
style.css      (then save and refresh and resize the browser to check the responsive views)
nav.css        (then save and refresh and resize the browser to check the responsive views)
responsive.css (then save and refresh and resize the browser to check the responsive views)

```

on line 23 of the index file you will need to find the start ```<nav>``` tag and you will have to add ```class=""``` . It is your responsibility to figure out what you must put in between the ```" "``` to make it work.

