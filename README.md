# Wordpress Core CSS

Used for Wordpress generated classes within the WYSIWYG editor - [https://wordpress.org/documentation/article/css/](https://wordpress.org/documentation/article/css/#wordpress-generated-classes)

`npm` package for wordpress core styles.

This will need to be updated if wordpress core changes.

## Usage
- Install to npm package using `npm install git+ssh://git@github.com/keefyhub/wordpress-core-css.git --saveDev`
- To use the CSS from the `node_modules` folder, use [sass-module-importer](https://www.npmjs.com/package/sass-module-importer) (or similar) and import using `@import 'wordpress-core-css';`
