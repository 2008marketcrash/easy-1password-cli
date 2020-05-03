# easy-1password-cli
Simple wrapper around [1Password CLI](https://1password.com/downloads/command-line) to provide an application-like experience on the terminal.

### Features

The major features offered by `easy-1password-cli` are:
- Automatic session management: Your session token for 1Password is only active while you're using the tool. It is proactively invalidated by the tool before exit.
- User friendly formatting: You can format `JSON` output by appending `| format` at the end of the command.
- Clipboard management: TODO.

### Dependencies

This tool relies on [1Password CLI](https://support.1password.com/command-line/) and [jq](https://stedolan.github.io/jq/) to work properly. You can check the versions using `easy1p --version`.

### Installation

Currently `easy-1password-cli` is just a bash script. You can put it anywhere in your `$PATH`.

### Usage

TODO.
