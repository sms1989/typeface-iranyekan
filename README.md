
# typeface-iranyekan

The CSS and web font files to easily self-host “Roboto”.

## Install

`npm install --save typeface-iranyekan`

## Use

Since the font is licensed you have to download the fonts from the [producer website](http://fontiran.com/%D9%81%D9%88%D9%86%D8%AA-%D8%A7%DB%8C%D8%B1%D8%A7%D9%86-%DB%8C%DA%A9%D8%A7%D9%86-iran-yekan/) and then put all the web fonts in `files`.

Typefaces assume you’re using webpack to process CSS and files. Each typeface
package includes all necessary font files (woff2, woff, eot, ttf, svg) and
a CSS file with font-face declarations pointing at these files.

You will need to have webpack setup to load css and font files. Many tools built
with Webpack will work out of the box with Typefaces such as [Gatsby](https://github.com/gatsbyjs/gatsby)
and [Create React App](https://github.com/facebookincubator/create-react-app).

To use, simply require the package in your project’s entry file e.g.

```javascript
// Load Roboto typeface
require('typeface-iranyekan')
```
