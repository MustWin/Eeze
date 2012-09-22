#Eeze v0.3

[http://eeze.us](http://eeze.us)


##What  
Eeze is a clean slate for professional developers creating custom applications. eeze.min.css comes out of the box at under 5K (**before** G-Zipping, you can gain ~2k by swapping to the HTML5 Reset) and sets up a great LESS workflow with base LESS in one folder and user defined LESS in stylesheets/less/app-modules.

##Why
Unlike [Twitter Bootstrap](http://twitter.github.com/bootstrap/) or [Skeleton](https://github.com/dhgamache/Skeleton), Eeze comes as a minimal starting point for your app. I’ve only included the most common building blocks and base file structure that you might need to create a custom application. There are no base preset styles to work around, delete, or overwrite. Just clone the app and start writing *your* code in seconds.

##Files:

* `images/`

* `stylesheets/`

  * `less/`

    * `app-modules/`
      * `application.less` - empty to start
      * `buttons.less` - empty to start
      * `copyright.less` - just a simple copyright stamper.
      * `media-queries.less` - sets up your media queries, pulls all the "responsive-" less files.
      * `responsive-full.less`, responsive-mobile.less, responsive-tablet.less - width-specific stylesheets
      * `typography` - empty to start, 
      * `variables` - empty to start,

    * `eeze-modules/`

      * `grids/`
        * `1140-grid.less` - Eeze defaults to [http://cssgrid.net](http://cssgrid.net)'s 1140-grid _(update `stylesheets/less/eeze.less` to change to your preference.)
        * `960-grid.less` - TODO_

      * `resets/`
        * `html5-doctor.less` - use the html5 doctor reset
        * `normalize.less` - Eeze defaults to `normalize.css`

      * `copyright.less` - just a simple copyright stamper.
      * `css3.less` - the basic css3 less mixins, when used they automatically add the browser specific styles to your CSS
      * `reusables` - 11 base styles that seem indespensible

    * `app.less` - compiles the application less styles
    * `eeze.less` - compiles your custom eeze.css file
    * `guide.less` - compiles the style guide css, guide.css

  * `app.css` - out of the box compiles CSS (doesn't look like much, it shouldn't until you write this part.)
  * `eeze.min.css` - the standard eeze file has normalize, 1140 grid, and some base files  
  * `guide.css` - has some basic crutches used only for the style guide view guide.html  

* `base.html` - base elements of a modern front end HTML5 template
* `guide.html` - this is your style guide, as you make changes to your LESS and compile new versions of app.css and eeze.css these will be reflected here (guide.less might need some tweaking to use your styles if you don't use the same variable names.)

    

Documentation is coming soon to [http://eeze.us](http://eeze.us)


###Project Info:

Eeze front-end application starter kit   
by Wil Everts (@cousinwil)  
[http://eeze.us](http://eeze.us)  
Version 0.3 - 9/21/2012  

_Copyright 2012, Wil Everts  
Dual licensed under the MIT or GPL Version 2 licenses._