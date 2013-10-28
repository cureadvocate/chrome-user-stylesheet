A custom user stylesheet for Google Chrome.

This stylesheet forces Inconsolata on all elements, with one exception.

Browsing GitHub with Inconsolata looks terrible, as GitHub uses the Octicons web font to display its icons.  This stylesheet contains a more specific CSS rule that overrides Inconsolata on elements whose class names contain the substring octicon.



### TODO

- [ ] Add CSS rule to use a CJK-friendly font for pages that need it.