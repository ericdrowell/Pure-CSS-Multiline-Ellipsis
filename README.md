#Pure CSS Multi-line Ellipsis

No JavaScript!  Cross Browser Compatible!  You're welcome.

##History

Let's face it.  Multi-line ellipsis on the web sucks.  That's why you're here.  You don't want to use a JavaScript solution because it just feels wrong to run JavaScript to style stuff.  Right?  Plus, it hurts your page perfomance.

I set out to see if it was possible to create a pure CSS solution with some CSS hackery.  I found this article, [http://www.mobify.com/blog/multiline-ellipsis-in-pure-css/](http://www.mobify.com/blog/multiline-ellipsis-in-pure-css/) on Mobify which is very inline with what I was thinking, but I don't think it's quite complete.  The solution that it offers is very, very hard to work with.  This github project starts with the solution from that article, and beats it into submission.  Among other things, this includes:

* Removing the Sass dependency (yes, Sass is awesome, but not everyone uses it)
* Separating the styling that's required to create the ellipsis effect (ellipsis.css) from page specific styling
* Adding all of this to Github so we (the community) can improve on it further

##Examples

* [Simple example](http://codepen.io/ericdrowell/pen/edgKB)
* [Ellipsis that's a clickable link](http://codepen.io/ericdrowell/pen/kesAF)
