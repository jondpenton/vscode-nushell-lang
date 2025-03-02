# Change Log

All notable changes to the "vscode-nushell-lang" extension will be documented in this file.

## [Pre-Release]

- Initial release 0.0.1
  - proof of concept release
- 0.0.2
  - tweak sytnax highlighting
- 0.0.3
  - changed `set` to `let` since the language changed
- 0.0.4
  - changed line comment from `//` to `#`
  - updated readme screenshot and issue link
  - added all current nushell keywords
  - added all current nushell sub commands
  - fixed `[$var` bug
  - fixed `foo-bar` bug
- 0.0.5
  - updated screenshot with different themes
  - reorganized code a bit
- 0.0.6
  - fixed `my-ls` highlighting bug
  - added build ci and release pipeline
  - readme updates from `waldyrious` ty!
  - moved assets to a folder
- 0.0.7
  - made release work dynamically with versions
  - added icon
- 0.0.8
  - added ansi strip
  - added term size
  - added mod
  - fixed bug in escapes
  - fixed build-string
  - added alias
  - added char prompt
  - added char newline
  - added format
  - added $it.item
  - added $it.index
- 0.0.9
  - renamed dark theme to Nushell-Dark
  - added light theme named Nushell-Light
- 0.1.0
  - tweaked some dark colors
  - added source color for dark color
  - changed double quote regex
- 0.1.1
  - added def snippet for custom command
  - added defp snippet for custom command with a parameter
  - added defs snippet for custom command with a switch
  - added alias snippet for alias creation
- 0.1.2
  - added search keywords in package.json
  - added publisher name
  - updated screenshots
- 0.2.0
  - added intellisense aka auto-complete for commands and subcommands
- 0.2.1
  - tweaked the dark theme colors a tiny bit
  - updated commands and keywords
- 0.2.2
  - fixed a regression in syntax highlighting (thanks yume-chan)
- 0.3.0
  - updated commands to support all commands in nushell 0.32.0
  - updated intellisense to support all commands in nushell 0.32.0
  - added block parameter syntax highlighting
- 0.4.0
  - updated commands to support all commands in nushell 0.34.1
  - disabled intellisense completions
- 0.4.1
  - syntax changed to allow optional `$` in variable name
  - syntax changed to allow space after custom command parameters
  - added `in` to go with `for`
- 0.4.2
  - added contribute custom terminal feature it is easier to use nushell as a terminal in vscode
- 0.5.0
  - updated language to support 0.60.0 new keywords
  - fixed some bugs with highlighting
  - separated keywords for easier regex debugging
  - updated dependency versions
- 0.5.1
  - add `not-in` as a pseudo keyword to go with `in` and `else`
  - update screenshots showing else keyword
  - add `on-Enter` rules
  - fixed a bug with variable syntax coloring
- 0.5.2
  - add `true`, `false`, and `null` as pseudo keywords
  - changed the indentation rules
- 0.5.3
  - updated language punctuation recognition
  - added the ability to recognize block parameters as variables
  - split out part of the readme.md into building.md
- 0.6.0
  - Thanks to @Yethal we have a new syntax generating script to help making releases easier
  - Another item @Yethal contributed was a script to generate examples to test the syntax on
  - Other general cleanup
  - Supports most recent nushell syntax as of 0.66.4
  - @schuelermine fixed a type-o
- 0.7.0
  - better automatic syntax from @Yethal
  - better block variable highlighting
  - remove themes + some cleanup
  - tweak auto-generated syntax
- 0.8.0
  - added path for arm brew @melMass
  - update readme screenshots
  - add the old dark and light themes to repo for anyone who wants to use them
  - update example.nu for testing
  - update generate-example.nu to include all samples
  - update generate-patterns.nu to support the new language features
  - update language syntax to support new nushell 0.72 features (break, continue, return, loop, try, catch, mut, while, err>, out>, err+out>, out+err>)
- 1.0.0
  - Thanks to Gabin Lefranc (@glcraft) for a total rewrite of the textmate grammar for nushell!!
