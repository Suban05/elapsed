# Measures the Time Elapsed by a Block

[![DevOps By Rultor.com](http://www.rultor.com/b/yegor256/elapsed)](http://www.rultor.com/p/yegor256/elapsed)
[![We recommend RubyMine](https://www.elegantobjects.org/rubymine.svg)](https://www.jetbrains.com/ruby/)

[![rake](https://github.com/yegor256/elapsed/actions/workflows/rake.yml/badge.svg)](https://github.com/yegor256/elapsed/actions/workflows/rake.yml)
[![PDD status](http://www.0pdd.com/svg?name=yegor256/elapsed)](http://www.0pdd.com/p?name=yegor256/elapsed)
[![Gem Version](https://badge.fury.io/rb/elapsed.svg)](http://badge.fury.io/rb/elapsed)
[![Test Coverage](https://img.shields.io/codecov/c/github/yegor256/elapsed.svg)](https://codecov.io/github/yegor256/elapsed?branch=master)
[![Yard Docs](http://img.shields.io/badge/yard-docs-blue.svg)](http://rubydoc.info/github/yegor256/elapsed/master/frames)
[![Hits-of-Code](https://hitsofcode.com/github/yegor256/elapsed)](https://hitsofcode.com/view/github/yegor256/elapsed)
[![License](https://img.shields.io/badge/license-MIT-green.svg)](https://github.com/yegor256/elapsed/blob/master/LICENSE.txt)

Here is how you can measure and log the time of a block:

```ruby
require 'elapsed'
elapsed do
  run_something_slow
end
```

That's it.

## How to contribute

Read
[these guidelines](https://www.yegor256.com/2014/04/15/github-guidelines.html).
Make sure you build is green before you contribute
your pull request. You will need to have
[Ruby](https://www.ruby-lang.org/en/) 3.0+ and
[Bundler](https://bundler.io/) installed. Then:

```bash
bundle update
bundle exec rake
```

If it's clean and you don't see any error messages, submit your pull request.