[![Version     ](https://img.shields.io/gem/v/bundler.svg?style=flat)](https://rubygems.org/gems/bundler)
[![Build Status](https://img.shields.io/travis/bundler/bundler/master.svg?style=flat)](https://travis-ci.org/bundler/bundler)
[![Code Climate](https://img.shields.io/codeclimate/github/bundler/bundler.svg?style=flat)](https://codeclimate.com/github/bundler/bundler)
[![Inline docs ](http://inch-ci.org/github/bundler/bundler.svg?style=flat)](http://inch-ci.org/github/bundler/bundler)

# Bundler: a gem to bundle gems

[![Join the chat at https://gitter.im/azhararmar/bundler](https://badges.gitter.im/azhararmar/bundler.svg)](https://gitter.im/azhararmar/bundler?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)

Bundler makes sure Ruby applications run the same code on every machine.

It does this by managing the gems that the application depends on. Given a list of gems, it can automatically download and install those gems, as well as any other gems needed by the gems that are listed. Before installing gems, it checks the versions of every gem to make sure that they are compatible, and can all be loaded at the same time. After the gems have been installed, Bundler can help you update some or all of them when new versions become available. Finally, it records the exact versions that have been installed, so that others can install the exact same gems.

### Installation and usage

```
gem install bundler
bundle init
echo 'gem "rspec"' >> Gemfile
bundle install
bundle exec rspec
```

See [bundler.io](http://bundler.io) for the full documentation.

### Troubleshooting

For help with common problems, see [ISSUES](https://github.com/bundler/bundler/blob/master/ISSUES.md).

### Other questions

To see what has changed in recent versions of Bundler, see the [CHANGELOG](https://github.com/bundler/bundler/blob/master/CHANGELOG.md).

Feel free to chat with the Bundler core team (and many other users) on IRC in the  [#bundler](irc://irc.freenode.net/bundler) channel on Freenode, or via email on the [Bundler mailing list](http://groups.google.com/group/ruby-bundler).

### Contributing

If you'd like to contribute to Bundler, that's awesome, and we <3 you. There's a guide to contributing to Bundler (both code and general help) over in [DEVELOPMENT](https://github.com/bundler/bundler/blob/master/DEVELOPMENT.md).

### Code of Conduct

Everyone interacting in the Bundler project’s codebases, issue trackers, chat rooms, and mailing lists is expected to follow the [Bundler code of conduct](https://github.com/bundler/bundler/blob/master/CODE_OF_CONDUCT.md).
