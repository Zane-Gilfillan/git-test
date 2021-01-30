# study-room
i'll keep this repo up during the bootcamp to knock out practice work and the like

# css positioning practice
just going to keep this folder going for the day for people to practice with *shrugs*

An element with ```position: relative;``` is positioned relative to its normal position.

Setting the top, right, bottom, and left properties of a relatively-positioned element will cause it to be adjusted away from its normal position. Other content will not be adjusted to fit into any gap left by the element.


An element with ```position: fixed;``` is positioned relative to the viewport, which means it always stays in the same place even if the page is scrolled. The top, right, bottom, and left properties are used to position the element.

A fixed element does not leave a gap in the page where it would normally have been located.


An element with ```position: absolute;``` is positioned relative to the nearest positioned ancestor (instead of positioned relative to the viewport, like fixed).

However; if an absolute positioned element has no positioned ancestors, it uses the document body, and moves along with page scrolling.


I added an extra div element named ```browser-push``` in order for the ```position: fixed;``` activities to be a little more clear.
