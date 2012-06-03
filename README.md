# grunt-contrib

A collection of general use grunt tasks (*currently in alpha*).

## Getting Started
Install this grunt plugin next to your project's [grunt.js gruntfile][getting_started] with: `npm install grunt-contrib`

Then add this line to your project's `grunt.js` gruntfile:

```javascript
grunt.loadNpmTasks('grunt-contrib');
```

[grunt]: https://github.com/cowboy/grunt
[getting_started]: https://github.com/cowboy/grunt/blob/master/docs/getting_started.md

## Included Tasks
#### [`clean`](/gruntjs/grunt-contrib/blob/master/docs/clean.md)
Clear files and folders.

#### [`coffee`](/gruntjs/grunt-contrib/blob/master/docs/coffee.md)
Compile CoffeeScript files into JavaScript.

#### [`handlebars`](/gruntjs/grunt-contrib/blob/master/docs/handlebars.md)
Compile handlebars templates to JST file.

#### [`jade`](/gruntjs/grunt-contrib/blob/master/docs/jade.md)
Compile Jade templates to HTML.

#### [`jst`](/gruntjs/grunt-contrib/blob/master/docs/jst.md)
Compile underscore templates to JST file.

#### [`less`](/gruntjs/grunt-contrib/blob/master/docs/less.md)
Compile LESS files to CSS

#### [`mincss`](/gruntjs/grunt-contrib/blob/master/docs/mincss.md)
Minify CSS files.

#### [`stylus`](/gruntjs/grunt-contrib/blob/master/docs/stylus.md)
Compile Stylus files into CSS.

#### [`zip`](/gruntjs/grunt-contrib/blob/master/docs/zip.md)
Zip files and folders.


## Contributing

#### Configuration
In order to ensure a consistent configuration style, task submissions should retreive their optional parameters with the included grunt helper, [options](/gruntjs/grunt-contrib/blob/master/docs/options.md).

#### Testing
Tests must be included with your submission.  New tasks can be added to the config in `test/grunt.js`, please see existing tests for guidance.  *Currently, testing with grunt is a bit cumbersome--this will be addressed in a future release.*

#### Running Tests
```bash
npm install grunt -g
npm install
npm test
```

## Release History

* 2012/06/03 - v0.0.4 - Cleanup release with zip task addition.
* 2012/05/17 - v0.0.3 - Cleanup release.  Getting task configuration consistent.
* 2012/05/01 - v0.0.2 - Remove some debugging code.
* 2012/05/01 - v0.0.1 - Alpha release.

## License
Copyright (c) 2012 "Cowboy" Ben Alman & contributors.
Licensed under the MIT license.
