# WVU Pattern Library -- Masthead Search Bar Module

[![Build Status](https://travis-ci.org/wvu-patterns/wvu-patterns-search.svg?branch=master)](https://travis-ci.org/wvu-patterns/wvu-patterns-search)

Use [Bower](http://bower.io/) to install this module.

```bash
$ bower install --save wvu-patterns-search
```

## Dependencies

```
"wvu-search": "1.0.0",
"wvu-utilities-variables": "1.0.0",
"neat" : "1.7.2"
```

### SCSS Overrideable defaults

```scss


```

###Pattern Development

Requires:

* Ruby ~= 2.2.3
* NodeJS >= 4.1.2
* Gulp >= 3.8.11

*RVM is Preferred* but not required

####Installation

* `cd {install-dir}/wvu-patterns-search`
* `gem install bundler`
* `bundle install`
* `npm install`

####Pattern Testing

* `gulp test` will create a build directory so you can view pattern
* `gulp ci` will run lint test to make sure .scss file is valid
