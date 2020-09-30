# Boilerplate
Easy-to-use basic template for web development using webpack and babel

Final files are stored in the `dist` folder. This folder consist of the `assets` folder containing a `bundle.js`, a combination all javascript files and the `index.html`, the web page being rendered. Any `css` files should be stored in the `assets` folder and referenced in the `index.html`.

The `src` folder contains all the javascript files needed web development. This files will be compiled and joined using babel to form the aformentioned`bundle.js` file.

To run a local server during the development process use the command:`npm run dev`
 
To compile and build the final files use the command: `npm run build`
