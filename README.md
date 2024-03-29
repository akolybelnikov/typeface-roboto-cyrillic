# typeface-roboto-cyrillic

The CSS and web font files to easily self-host “Roboto” with cyrillic characters.

## Install

`npm install --save typeface-roboto-cyrillic`

## Use

Typefaces assume you’re using webpack to process CSS and files. Each typeface
package includes the necessary font files (woff, eot, ttf) and
a CSS file with font-face declarations pointing at these files.

You will need to have webpack setup to load css and font files. Many tools built
with Webpack will work out of the box with Typefaces such as [Gatsby](https://github.com/gatsbyjs/gatsby)
and [Create React App](https://github.com/facebookincubator/create-react-app).

To use, simply require the package in your project’s entry file e.g.

```javascript
// Load Roboto typeface
require('typeface-roboto')
```

or

```javascript
// Load Roboto typeface
import "typeface-roboto-cyrillic"
```
