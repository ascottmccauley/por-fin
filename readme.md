#por-fin

por-fin is a [WordPress](http://wordpress.org) is a base installation used for creating sites using the [fin](https://github.com/ascottmccauley/fin) framework.

##Features

* [WordPress](http://wordpress.org) is loaded as a submodule in `/wp/`

* Themes, Plugins, and MU-Plugins are loaded from `/content/`

* `wp-config.php` will check for database info from `wp-local.php` first and then `wp-server.php`. So make sure that your production server does not keep the `wp-local.php` file!

* `/assets/` - The default location for uploads in the [fin](https://github.com/ascottmccauley/fin) framework. Make sure that this folder is writeable!

* `sitemap.xml` - The [fin](https://github.com/ascottmccauley/fin) framework automatically creates a fresh sitemap whenever posts are published. Make sure that this file is writeable!

* `.htaccess` - This file has the default rewrites needed for the [fin](https://github.com/ascottmccauley/fin) framework and a few other goodies thrown in like the [5G blacklist](http://perishablepress.com/5g-blacklist-2013/)

MIT Open Source License
=======================

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.