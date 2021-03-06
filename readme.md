# Webpack

Let's start with the basics. What is webpack and why would you want to use it?

Webpack in the simplest explanation, is a way to write your application in multiple JavaScript files and connect them to each other. This is not a new idea, tools like Require.js and Browserify have been doing it for years. In fact, this idea of writing your JS in separate files has become such a common way of organizing your application that browsers are beginning to [introduce support](http://stackoverflow.com/questions/33516906/which-browsers-support-import-and-export-syntax-for-ecmascript-6) for handling the import and export of JS.

This concept is officially called module bundling and webpack takes care of this and so much more.

What webpack does differently than browserify or require.js, is add additional tools to create development servers, hot module reloading (more on that soon) and the ability to load CSS, Fonts and Images directly into your JavaScript. As well, webpack helps keep application bloat down by allowing for scripts to be dynamically loaded in as they are needed, and using tree-shaking to remove extraneous code when bundling.

## Chapters
* [Installing Webpack](chapters/01-installing-webpack.md)
* [Using Webpack](chapters/02-using-webpack.md)
* [Understanding the Bundle](chapters/03-understanding-the-bundle.md)
* [Webpack Config File](chapters/04-webpack-config-file.md)
* [Webpack Dev Server](chapters/05-webpack-dev-server.md)
* [Loaders](chapters/06-loaders.md)
* [Production Building](chapters/07-production-building.md)
* [Loading Styles](chapters/08-loading-styles.md)
* [Loading Assets](chapters/09-loading-assets.md)
* [Sourcemaps](chapters/10-sourcemaps.md)
* [Tree Shaking](chapters/11-tree-shaking.md)
* [HTML Files](chapters/12-HTML-files.md)
* [Cachebusting](chapters/13-cachebusting.md)
