# [@citrusui/poole](https://npmjs.com/package/@citrusui/poole)

A fork of [Poole](http://getpoole.com) that I use for my own projects.

**Note:** As this repo is designed to be modularized, only Sass files are included. This fork _does not_ contain any layouts or includes for Jekyll -- you'll need to implement them yourself.

# What's New

- Added files
  - Implementation of [`sass-lint`](https://github.com/brigade/scss-lint) using [these rules](.sass-lint.yml)
  - Basic button styles (`_buttons.scss`)
  - Navbar styles (`_navbar.scss`)

- Styles
  - Lots of formatting changes
  - Eliminate almost all vendor prefixes
  - Every color is now specified as a variable
  - Added `-webkit-tap-highlight-color: transparent`

# What's Removed

A few styles have been removed as they are too specific for my needs. They may be reintroduced at a later time:

- Masthead (`_masthead.scss`)
- Message (`_message.scss`)
- Table (`_base.scss`)

## License

Poole is originally developed by Mark Otto under the [MIT license](https://github.com/poole/poole/blob/master/LICENSE.md). 
