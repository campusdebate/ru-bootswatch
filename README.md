Remugio- Bootswatch
==========

Bootswatch is a collection of free themes for [Bootstrap](http://getbootstrap.com/). Check it out at [bootswatch.com](http://bootswatch.com).

Usage
Customization
To modify a theme or create your own, follow the steps below in your terminal. You'll need to have Git and Node installed.

Download the repository.
Install dependencies: npm install

Make sure that you have grunt available in the command line. You can install grunt-cli as described on the Grunt Getting Started page.

Modify variables.less and bootswatch.less in one of the theme directories, or create your own in /custom.

Type grunt swatch:[theme] to build the CSS for a theme, e.g., grunt swatch:amelia for Amelia. Or type grunt swatch to build them all at once.

You can run grunt to start a server, watch for any changes to the LESS files, and automatically build a theme and reload it on change. Run grunt server for just the server, and grunt watch for just the watcher.
