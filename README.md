<!-- Copyright 2026 Dotphoton AG -->

# Jetraw Homebrew tap

`jr`, the Jetraw command line, for macOS on Apple silicon.

    brew install jetraw/tap/jetraw-cli

This puts `jr` on your `PATH`. Then log in with your Jetraw account:

    jr login

## Shell completion

Homebrew installs completion for zsh, bash and fish. In zsh, the macOS default,
Tab completes `jr` once `compinit` runs; if it does not, add this line to
`~/.zshrc` and open a new terminal:

    autoload -Uz compinit && compinit

For bash and fish, see Homebrew's [Shell Completion](https://docs.brew.sh/Shell-Completion).

## Upgrade and uninstall

    brew upgrade jetraw-cli
    brew uninstall jetraw-cli

Homebrew's own `jr` formula is an unrelated tool with the same command name;
only one of the two can be installed.

## License

Proprietary, © Dotphoton AG. `jr` is provided for use with a Jetraw account under the
[Jetraw Services Agreement](https://platform.jetraw.com/legal/services-agreement); see
[LICENSE](LICENSE).

The formula and releases in this repository are published from Dotphoton's
release pipeline; changes made here directly are overwritten.
