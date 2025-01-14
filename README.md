Fork for zsh completion

- zimfw: add this line in ~/.zimrc
```
zmodule yun-cloud/exercism-cli
```

modified by
```
mkdir -p shell/zsh/functions
cp shell/exercism_completion.zsh shell/zsh/functions/_exercism
```

# Exercism Command-line Interface (CLI)

[![Build Status](https://travis-ci.org/exercism/cli.svg?branch=master)](https://travis-ci.org/exercism/cli)
[![Go Report Card](https://goreportcard.com/badge/github.com/exercism/cli)](https://goreportcard.com/report/github.com/exercism/cli)

The CLI is the link between the [Exercism][exercism] website and your local work environment. It lets you download exercises and submit your solution to the site.

This CLI ships as a binary with no additional runtime requirements.

## Installing the CLI

Instructions can be found at [exercism/cli/releases](https://github.com/exercism/cli/releases)

## Contributing

If you wish to help improve the CLI, please see the [Contributing guide][contributing].

[exercism]: http://exercism.io
[contributing]: /CONTRIBUTING.md
