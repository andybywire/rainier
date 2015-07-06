#Rainier Statamic Theme

Rainier is a responsive theme for Statamic based on the Foundation 5 framework. 

* [Statamic](http://statamic.com/) is a flat-file CMS. It's great for easily separating content from style and for easily spinning up content-driven projects. 
* [Foundation 5](http://foundation.zurb.com/) is the mobile-first responsive web framework from ZURB

Rainier brings together the SASS version of Foundation 5 with Statamic's templating engine. I've built out the key pages for Statamic's wilderness-based sample site using semantic markup and have created a custom SASS stylesheet to render the page as a "Foundation-ified" version of Statamic's [Acadia](http://themes.statamic.com/acadia/) theme. Check out a demo [here](http://rainier.andyfitzgerald.org).

To use Rainier, clone this repository to your Statamic "themes" folder, then change the theme name in your settings.yaml file (located in Statamic's _config folder). The theme contains all of the Foundation dependencies needed for a SASS workflow, though you'll need a couple of additional resources installed in your enviroment to compile the CSS docs (follow the [Libsass and Grunt](http://foundation.zurb.com/docs/sass.html) instructions in Foundations docs).

Like Foundation itself, Rainier is intended to be used as a base from which to build other projects. I put this together mostly to have a solid starting point for my own projects – and to get a better feel for Statamic, Foundation, and SASS can be used together. Please do feel free to contribute and/or make suggestions or requests. 