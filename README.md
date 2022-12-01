# CanvasJS

I encourage you to go through the commits to see the process.

If you are working with adding Mr. Cameron's demonstration code, there is something subtle that you might miss (I certainly did!): There is an added attribute of `tabindex='1'` on the canvas HTML tag.  If you miss that, your keypress events will not get grabbed by the event listener.  Alternatively, you can attach the key event listener to the built-in window object instead of the canvas tag.
