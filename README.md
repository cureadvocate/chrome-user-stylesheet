A custom user stylesheet for Google Chrome.

This stylesheet forces Inconsolata on all elements, with one exception.

Browsing GitHub with Inconsolata looks terrible, as GitHub uses the Octicons web font to display its icons.  This stylesheet contains a more specific CSS rule that overrides Inconsolata on elements whose class names contain the substring octicon.



### INSTALL (via [SuperUser](http://superuser.com/questions/594358/modify-chrome-user-agent-stylesheet))

1. In Google Chrome, go to URL about:version and take note of the "profile path".
2. Browse to the profile path in your file browser. Inside your profile folder, open the User StyleSheets folder. Inside "User StyleSheets", there should be a file called Custom.css, empty by default.
3. Just add your styles in Custom.css.