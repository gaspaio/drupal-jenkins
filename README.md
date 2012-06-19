Drupal Jenkins
========

Ant scripts and associated config files for use in Drupal related jenkins jobs.

Not stable yet. Documentation is coming, slowly ...

Applications
========

JSHint
--------
A more configurable and community friendly version of JSLint, for validating JS syntax and style.
* see www.jshint.com for option descriptions, install instructions, etc.

The options are stored in a file : build/tools/jshint/jshint.json.
They try to enforce basic best practices while reducing false positives.

You can also use it standalone :

$ jshint --config jshint.json <my-js-dir>


CSSLint
--------
Syntax and style validation for css files.
Most options are not really usefull, since they enforce one view of CSS rather than communly accepted best practices.
Some of them are practical and, at the very least, CSSLint checks the syntax.

The Ant task for CSSLinting reads the options for the file build/tools/csslint/csslint.rules and generates the command line.
* see www.csslint.net for option descriptions, install instructions, etc.