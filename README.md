# Obox

Obox is a OneWebsite-flavored style framework based on Materialize CSS that can be installed as a node package. See the full documentation [here](http://www.volusion-static.netlify.com/styleguide).


### Installation

Add this line to your application's package.json where the version number is the latest [release](https://github.com/volusiondx/obox/releases):

    "obox": "git://github.com/volusiondx/obox.git#v0.0.1",

And then run:

    $ npm install obox


### Integrating scss

Add this to your base scss file:

    @import 'obox/sass/materialize';

#### Compiling

The obox styles will be included the next time you compile your css.

### Integrating javascript

To include javascript files, include the following in your base js file:

    window.materialize = require('obox/js/bin/materialize.js');


### Obox and Materialize CSS

Obox is based on [Materialize CSS](http://materializecss.com/).

Custom additions include...

* Margin and padding helpers
* Gutter widths
* Borders
* Lists and definition lists
* Added link and button hover color
* Custom media queries
* Responsive text alignment
* xs, s, m, l, and xl prefixes
* .text- prefixed text helpers
* Full change log [here](http://www.volusion-static.netlify.com/styleguide)


## Development

1. Check out this repo

2. Make your changes locally

3. Commit your changes (but don't push yet)

4. In your terminal, cd into the obox folder and run the following command where patch, minor, or major is the update type. Note the new version number.

    `$ npm version patch|minor|major`


5. Merge/push your changes to the master branch on github

6. On github, go to "releases" and create a new release tagged "vx.x.x" with the version number from step 3 (title and description don't matter)

7. To get the latest changes in your application, go into your application and update the version number in the package.json file

_Note:_ As you develop locally, it may be helpful to point your package.json to a local copy of obox with this:

    "obox": "file:/Applications/MAMP/htdocs/obox",


## Contributing

Bug reports and pull requests are welcome on GitHub at https://github.com/volusiondx/obox.


## License

The package is available as open source under the terms of the [MIT License](http://opensource.org/licenses/MIT).
