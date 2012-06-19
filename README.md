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


