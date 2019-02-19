# Inset tester
More and more devices are getting "notches" and edge to edge displays.
This can cause some strange quirks with you designs.

This page will tell/show you what area should be considered "off screen". 
These `safe-area-inset-*` variables should always be respected when designing for these screens.

## Using these variables
You can use these variables in your css by using the `env()` (`constant()` on older iOS devices) function.

You can look in `index.html` for examples of this.

## License
MIT © [Maarten Schroeven](maarten@sonaryr.be)