# WP Kickoff
## WordPress starter theme based on [Sage](https://github.com/roots/sage) and [Kickoff](https://github.com/trykickoff/kickoff)
###Sage - WP starter theme and Kickoff - a lightweight front-end framework for creating scalable, responsive sites

Maintained by [Rento Rinalds](https://github.com/rentodesign)

### Features
* Built in a mobile-first, responsive philosophy *(but can easily be used for fixed sites as well)*
* Sass compilation uses [autoprefixer](https://github.com/ai/autoprefixer) to dynamically add vendor prefixes so you don't even have to think about it. We still have many Sass mixins for many CSS3 features including gradients, REMs with fallbacks
* Starter content styles, including clean typography, lists, tables, etc
* Starter form element styles: stacked on small-screen to 2-column (if you choose) at the breakpoint of your choice
* **[Grunt](http://gruntjs.com)** used extensively to ease common development bottlenecks
 * Sass compilation using [libsass](https://github.com/sass/libsass) (using [grunt-sass](https://github.com/sindresorhus/grunt-sass))
 * Concatenation and minification of JS files with and [grunt-contrib-uglify](https://github.com/gruntjs/grunt-contrib-uglify)
 * Simple server using [grunt-contrib-connect](https://github.com/gruntjs/grunt-contrib-connect)
 * SVG Icon generation using [grunticon](https://github.com/filamentgroup/grunticon)
* [Theme wrapper](https://roots.io/sage/docs/theme-wrapper/)
* ARIA roles and microformats
* Posts use the [hNews](http://microformats.org/wiki/hnews) microformat
* [Multilingual ready](https://roots.io/wpml/) and over 30 available [community translations](https://github.com/roots/sage-translations)
 
Install the [Soil](https://github.com/roots/soil) plugin to enable additional features:

* Cleaner output of `wp_head` and enqueued assets
* Cleaner HTML output of navigation menus
* Root relative URLs
* Nice search (`/search/query/`)
* Google CDN jQuery snippet from [HTML5 Boilerplate](http://html5boilerplate.com/)
* Google Analytics snippet from [HTML5 Boilerplate](http://html5boilerplate.com/)

## Kickoff Demos and documentation
Kickoff's demo and documentation site is hosted at [trykickoff.github.io](http://trykickoff.github.io/).

## Installation

Clone the git repo - `git clone https://github.com/rentodesign/wp-kickoff.git` and then rename the directory to the name of your theme or website.

If you don't use [Bedrock](https://github.com/roots/bedrock), you'll need to add the following to your `wp-config.php` on your development installation:

```php
define('WP_ENV', 'development');
```

## Configuration

Edit `lib/config.php` to enable or disable theme features

Edit `lib/init.php` to setup navigation menus, post thumbnail sizes, post formats, and sidebars.

### Browser Compatibility
Kickoff has been tested in the following browsers:
- Chrome
- Safari
- Firefox 3+
- Opera 10+
- Internet Explorer 8+


