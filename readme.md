# StockedHome Assets Folder

This folder contains all the static assets used in the StockedHome application.

## Logos

The following vectors are available:
* `logo-notification.svg` - A hand-greyscaled version of `logo.svg` for use in the notification bar.
    * `logo-notification.svg` - Inkscape name metadata included.
* `logo-background.svg` - A copy of `logo.svg` with a blue (`#146fc7`) background.
    * Inkscape name metadata included.
* `logo.svg` - The main logo, minified for optimized asset sizes.
    * `logo-source.svg` - Inkscape name metadata included.

Any raster images will be named as &lt;vector&gt;.&lt;size&gt;.&lt;extension&gt;, where &lt;vector&gt; is the name of the vector file, &lt;size&gt; is the size of the raster image, and &lt;extension&gt; is the file extension. For example, `logo-background.128.png` is a 128x128 pixel PNG render of `logo-background.svg`.

favicon.ico includes 32x32, 48x48, 64x64, and 128x128 renders of `logo-background.svg`.
