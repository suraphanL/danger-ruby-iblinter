# Danger IBLinter

A danger plugin for IBLinter.

## Installation

```
gem 'danger-swiftlint'
```

This plugin requires `iblinter` executable binary.

## Usage

```
iblinter.binary_path = "./Pods/IBLinter/bin/iblinter"
iblinter.lint("./path/to/project", fail_on_warning: true, inline_mode: true)
```

## Development

1. Clone this repo
2. Run `bundle install` to setup dependencies.
3. Run `bundle exec rake spec` to run the tests.
4. Use `bundle exec guard` to automatically have tests run as you make changes.
5. Make your changes.