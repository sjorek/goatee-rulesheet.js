
[goatee-rulesheet.js](http://sjorek.github.io/goatee-rulesheet.js/)
===================================================================

         _______  _______  _______  _______  _______  _______
        |    ___||       ||       ||_     _||    ___||    ___|
        |   | __ |   _   ||   _   |  |   |  |   |___ |   |___
        |   ||  ||  |_|  ||  |_|  |  |   |  |    ___||    ___|
        |   |_| ||       ||   _   |  |   |  |   |___ |   |___
        |_______||_______||__| |__|  |___|  |_______||_______|
                                         . ,
                                         (\\
                                      .--, \\__
                                       `-.     *`-.__
                                         |          ')
                                        / \__.-'-, ~;
                                       /     |   { /
                        ._..,-.-"``~"-'      ;    (
                     .;'                    ;'    ´
                ~;,./                      ;'
                   ';                     ;'
                    ';                 /;'|
                     |    .;._.,;';\   |  |
                     \   /  /       \  |\ |
                      \ || |         | )| )
                      | || |         | || |
                ~~~~~ | \| \  ~~~~~~ | \| \  ~~~~~~~
                "''"' `##`##' "'"''" `##`##' '"''"'"
                '"'"''"'"''"''"''"'"'''"'"'''"''"'"'
                ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
          _____ _____ __    ____ ____ _____ ____ ____ _____
         | __  |  |  |  |  |  __|  __|  |  |  __|  __|_   _|
         |    -|  |  |  |__|  __|__  |     |  __|  __| | |  
         |__|__|_____|_____|____|____|__|__|____|____| |_|  


A goatee is the perfect complement for handlebar mustaches. :-{>~

## Objective

GoateeRulesheets are the combination of goatee-script and the syntax of css.

Example:

    #selector, .another-selector {
        test: 1 + 2 * 3 ; /* line-breaks are optional */
        an-attribute: 'tester'.replace('r','d') ; aProperty: null
    }

Also see “[goatee.js](http://sjorek.github.io/goatee.js)”,
“[goatee-script.js](http://sjorek.github.io/goatee-script.js)” and
“[goatee-rules.js](http://sjorek.github.io/goatee-rules.js)”.


## Installation

    $ npm install -g goatee-rulesheet


## Usage

    $ goatee-rulesheet -h

    Usage: goatee-rulesheet [statements]... [options]

    statements     string passed from the command line to evaluate

    Options:
       -r STATEMENT, --run STATEMENT   string passed from the command line to
                                       evaluate
       -h, --help                      display this help message
       -i, --interactive               run an interactive `goatee-rules` read-
                                       execute-print-loop (repl)
       -m MODE, --mode MODE            [c]ompile, [e]valuate, [p]rint, [r]ender
                                       or [s]tringify statements, default:  [eval]
       -c, --compress                  compress the abstract syntax tree (ast)
       --nodejs OPTION                 pass one option directly to the 'node'
                                       binary, repeat for muliple options
       -v, --version                   display the version number and exit

    If called without options, `goatee-rules` will run interactive.

## Documentation

Read the [annotated sources](http://sjorek.github.io/goatee-rulesheet/).


## Development

### Install dependencies …

- [node.js](http://nodejs.org) _(≥ 0.10)_

  ### … for production version:

       $ npm install goatee-rulesheet.js --save

  ### … for development version:

      $ git clone https://github.com/sjorek/goatee-rulesheet.js
      $ cd goatee-rulesheet.js
      $ npm install

### Run build …

#### … in *nix-like environments:

    $ PATH=$PATH:./node_modules/.bin gulp

#### … in Windows environments:

    $ set path=%PATH%;.\node_modules\.bin
    $ setx path "%PATH%"
    $ gulp

_(not tested yet)_


## Credits go to …

- … Zachary Carter and all contributors of
  [jison parser generator](http://zaach.github.io/jison/)

- … Jeremy Ashkenas and all contributors of
  [Coffee-Script](http://coffeescript.org/)
  as a source of inspiration
