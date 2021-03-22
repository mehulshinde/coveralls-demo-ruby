[![Coverage Status](https://coveralls.io/repos/github/coverallsapp/coveralls-demo-ruby/badge.svg?branch=travis)](https://coveralls.io/github/coverallsapp/coveralls-demo-ruby?branch=travis)

# coveralls-ruby-demo for Travis CI

[Coveralls](https://coveralls.io/) demo project, using:

* [Ruby](https://www.ruby-lang.org/) — *Language*
* [Rspec](https://rspec.info/) — *Testing Library*
* [Simplecov](https://github.com/colszowka/simplecov) — *Code Coverage Library*

And these services:

* [Travis CI](http:://travis-ci.org) — *CI Service*
* [Coveralls](https://coveralls.io/) — *Test Coverage Service*

# Welcome

If you've gotten this far, we can assume:

<dl>
  <dt>1. You understand <a href="https://github.com/coverallsapp/coveralls-demo-ruby#1-understand-test-coverage-in-this-project">how test coverage works in this project</a>.</dt>
  <dd>If not, start back at the <a href="https://github.com/coverallsapp/coveralls-demo-ruby">master README</a>.</dd>

  <dt>2. You've chosen <a href="https://travis-ci.org/">Travis CI</a> as your CI Service.</dt>
  <dd>If not, head back to the <a href="https://github.com/coverallsapp/coveralls-demo-ruby">master README</a> and <a href="https://github.com/coverallsapp/coveralls-demo-ruby#which-ci-service-will-you-use">choose a different CI / branch</a>.</dd>
</dl>

# Configure your project for Coveralls & Travis CI

This project is configured to send test coverage results to [Coveralls](https://coveralls.io/) from [Travis CI](https://travis-ci.org/) using the [Coveralls Universal Coverage Reporter](https://github.com/coverallsapp/coverage-reporter). It does not use the [coveralls-ruby](https://github.com/lemurheavy/coveralls-ruby) gem.
