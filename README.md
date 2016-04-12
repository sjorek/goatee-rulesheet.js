
[goatee-rulesheets](http://sjorek.github.io/goatee-rulesheets/)
===============================================================

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
     _____ _____ __    _____ _____ _____ _____ _____ _____ _____ 
    | __  |  |  |  |  |   __|   __|  |  |   __|   __|_   _|   __|
    |    -|  |  |  |__|   __|__   |     |   __|   __| | | |__   |
    |__|__|_____|_____|_____|_____|__|__|_____|_____| |_| |_____|


A goatee is the perfect complement for handlebar mustaches. :-{>~

## Objective

GoateeRulesheets are the combination of goatee-script and the syntax of css.

Example:

    #selector {
        test: 1 + 2 * 3 ; /* line-breaks are optional */
        an-attribute: 'tester'.replace('r','d') ; aProperty: null
    }

Also see “[goatee-js](http://sjorek.github.io/goatee-js)”,
“[goatee-script](http://sjorek.github.io/goatee-script)” and
“[goatee-rules](http://sjorek.github.io/goatee-rules)”.


## Installation

    $ npm install -g goatee-rulesheets


## Usage

    $ goatee-rulesheets -h

    Usage: goatee-rulesheets [statements]... [options]

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

Read the [annotated sources](http://sjorek.github.io/goatee-rulesheets/).


## Development

Install dependencies:

- [git-scm](http://git-scm.com)
- [node.js *(≥ 0.10)*](http://nodejs.org)
- [pygments](http://pygments.org)

Install project:

    $ git clone https://github.com/sjorek/goatee-rulesheets
    $ cd goatee-rulesheets
    $ npm install

Run build in *nix-like environments:

    $ PATH=$PATH:./node_modules/.bin cake all

Run build in Windows environments (**not tested**):

    $ set path=%PATH%;.\node_modules\.bin
    $ setx path "%PATH%"
    $ cake all


## Credits go to …

- … Zachary Carter and all contributors of
  [jison parser generator](http://zaach.github.io/jison/)

- … Jeremy Ashkenas and all contributors of
  [Coffee-Script](http://coffeescript.org/)
  as a source of inspiration
