# less-plugin-lists

Lists/arrays manipulation functions for [Less](http://lesscss.org).

## Installation

    npm install -g less-plugin-lists
    
## Using with [`lessc`](http://lesscss.org/usage/#command-line-usage)

    lessc --lists file.less
    
For more details about using plugins with the command line Less compiler see 
[the corresponding section](http://lesscss.org/usage/#plugins-how-do-i-use-a-plugin-command-line) 
in the [Less documentation](http://lesscss.org).

## Using with common Less tools

- [`grunt-contrib-less`](https://github.com/gruntjs/grunt-contrib-less#usage-examples)
- [`gulp-less`] (https://github.com/plus3network/gulp-less#using-plugins)

## Programmatic Usage

See [Using a plugin in code](http://lesscss.org/usage/#plugins-using-a-plugin-in-code).

## Function Reference

`less-plugin-lists` extends Less with the following functions:
- [`at       `](docs/ref.md#at)        - returns the value at the specified position in a list.
- [`cat      `](docs/ref.md#cat)       - concatenates two or more lists.
- [`flatten  `](docs/ref.md#flatten)   - returns a one-dimensional list containing all elements of an input list.
- [`join     `](docs/ref.md#join)      - joins all elements of a list into a string.
- [`slice    `](docs/ref.md#slice)     - returns selected portion of a list.
- [`splice   `](docs/ref.md#splice)    - replaces or removes selected portion of a list and returns the modified copy.
- [`transpose`](docs/ref.md#transpose) - transposes rows and columns of a list.
- [`_inspect `](docs/ref.md#_inspect)  - return a string representation of a list with debug/log formatting.
