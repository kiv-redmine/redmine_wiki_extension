Redmine Wiki Extensions Plugin
==============================

[![Build Status](https://travis-ci.org/kiv-redmine/redmine_wiki_extensions.svg?branch=testing)](https://travis-ci.org/kiv-redmine/redmine_wiki_extensions) [![Inline docs](http://inch-ci.org/github/kiv-redmine/redmine_wiki_extensions.svg?branch=master)](http://inch-ci.org/github/kiv-redmine/redmine_wiki_extensions)


Wiki Extensions is a plugin which adds several useful wiki macros to Redmine.

http://www.r-labs.org/wiki/r-labs/Wiki_Extensions_en

Plugin installation
---------------------------

1. Copy the plugin directory into the plugins directory

2. Migrate plugin:
   rake redmine:plugins:migrate RAILS_ENV=production

3. Start Redmine

4. Add wiki extensions module into your project.

Note
---------------------------

This plugin works only on production mode.

Language contributors
---------------------------

* ru.yml - Dim A
* fr.yml - Pascal Menut
* de.yml - Albrecht Backhaus
* it.yml - earcar
* sv.yml - Henrik Jönsson
* es.yml - Francisco Benítez León
* no.yml - Thomas Nygreen
* pt.yml - Marcelo Fernandes
* pt-BR.yml - Marcelo Fernandes
* pl.yml - Łukasz Rymarczyk
* zh.yml - Tim lin,  Steven Wong
* cs.yml - Strnadj

How to run build on travis?
---------------------------
First of all try to run tests in your environment:

```ruby
ruby plugins/redmine_more_blocks_extension/test/**/*.rb
```

If everyhting is ok, push your changes into master branch and run merge script, which merge master into testing and push to remote (github):

```bash
./push_for_test.sh
```
