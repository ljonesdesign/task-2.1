You need to put the external css external link tags with the rel attribute
in the index.html file. Look in the index.html file to see the comment for where they go.

[help if you need it: How to do CSS links](http://www.w3schools.com/css/css_howto.asp)

Look at the site in a browser before you add these one by one, so that you can see the changes as you make them.

```
style.css     (then save and refresh and resize the browser to check the responsive views)
nav.css       (read the NOTE below. You have to update line 23 if you want to see a change when you refresh.
               Just adding the link will not change the nav links layout.
               Do both, then save and refresh and resize the browser to check the responsive views)
responsive.css (then save and refresh and resize the browser to check the responsive views)

```

NOTE on nav.css: on line 23 of the index file you will need to find the start ```<nav>``` tag and you will have to add ```class=""``` . It is your responsibility to figure out what you must put in between the ```" "``` to make it work.
Hint: the answer is in the nav.css file.

