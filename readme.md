# StudioJS

StudioJS is a rapidly growing collection of jQuery plugins for image cropping, resizing, and editing. 

All client-side components are released under the MIT license by their respective authors.

For a live demo,  [click here](http://studio.imageresizing.net/studio.html).

If you are upgrading, please [check the changelog for migration notes](https://github.com/nathanaeljones/studiojs/blob/master/changelog.md). Some backwards-incompatible changes have been made.

## Documentation Links

*[Migration notes](https://github.com/nathanaeljones/studiojs/blob/master/changelog.md)
*[ImageResizer.js docs](https://github.com/nathanaeljones/studiojs/blob/master/imageresizer.md)
*[Jcrop readme](https://github.com/tapmodo/Jcrop)
*[Jcrop website & docs](http://deepliquid.com/content/Jcrop.html)
*[jquery.jcrop.preview.js docs](https://github.com/nathanaeljones/studiojs/blob/master/jcrop-preview.md)
*[jquery.imagestudio.js docs](https://github.com/nathanaeljones/studiojs/blob/master/imagestudio.md)


## Overview of files

* jquery.Jcrop.js - A slightly modified version of [Jan. 2012 version of JCrop](https://github.com/tapmodo/Jcrop). I've made a pull request.
* jQuery.jcrop.preview.js - A tiny plugin to provide a live preview of the crop rectangle in an arbitrary container.
* ImageResizer.js - Provides a set of classes for querystring parsing and serialization, polygon math, and command string creation. Requires underscore.
* jquery.imagestudio.js - A configurable jquery UI plugin for creating a photo-editing widget in an arbitrary container. 

## Javascript Dependencies

Copies of all dependences can be found in the /libs folder. Most files in /libs are NOT required.

* jquery.Jcrop and Jcrop.preview.js require jQuery, 1.7 or higher preferred
* ImageResizer.js requires underscore.js
* jquery.imagestudio.js requires all of the above, plus jquery-ui.

## CSS dependencies

* Jcrop requires css/Jcrop.gif, css/jquery.Jcrop.css.
* ImageStudio requires jquery-ui-1.8.16.custom.css (and folder), css/jquery.imagestudio.css, css/loading.gif, css/delete-rect.gif


For support, use the Issues tab or e-mail support@imageresizing.net.




