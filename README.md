# SDKMAN

Using SDKMAN with the Fish shell. It provide the `sdk` command and let you to use it transparently.

## Prerequisites

- [SDKMAN](http://sdkman.io)

## Installation

```
$ fisher unreliable-angels/sdkman
```

## Gotchas

Before using commands which SDKMAN provides (e.g. `kotlin`), you have to run at least one `sdk` command.
As a workaround, running `sdk help` or something in your `config.fish` will solve this problem:

```fish
sdk help > /dev/null
```

## Thanks

[Using SDKMAN with the Fish Shell](http://tedwise.com/2016/02/26/using-sdkman-with-the-fish-shell)
