# Overview

{{cookiecutter.project_short_description}}

## Prerequisites

Install bundler with `gem install bundle`.  This is ruby's package manager.
Install rubocop globally.  `gem install rubocop`

## Getting Started

Run `bundle install` to install packages.

## Testing

`rspec`

## Fixing lint warnings/errors

Run `rubocop -a` to autofix fixable violations.
If you get `You must use Bundler 2 or greater with this lockfile.`, you can delete the Gemfile.lock and regenerate it with `bundle install`.

## Credits

Project created with [cookiecutter](https://github.com/cookiecutter/cookiecutter)
 from template [cookiecutter-getting-started](https://github.com/rt-learn-ruby/cookiecutter-ruby)
