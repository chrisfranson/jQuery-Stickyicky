# jQuery Stickyicky

jQuery Stickicky gives you very smooth sticky divs with just a single line of code. Available but broken solutions like [StickyScroll](https://github.com/rickharris/stickyscroll) have problems in many browsers with flickering. Stickyicky is smooth in Chrome, Firefox, Safari. We haven't checked IE yet.

I originally learned about this technique from Derek Allard on his blog [here](http://www.derekallard.com/blog/post/conditionally-sticky-sidebar).

To use it, load the jQuery file, and call it like so:

	$('#sticky_box').stickyicky();

If you want to add an offset to the top, you can do that by passing the number of pixels to offset by to the function:

	$('#sticky_box').stickyicky(50);

The above will trigger the stickyness at 50 pixels below the top of the browser window.