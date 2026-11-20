# heartleo/homebrew-tap

Homebrew formulae for [heartleo](https://github.com/heartleo)'s tools.

> [!IMPORTANT]
> **The `zlib` formula was renamed to `zlib-cli`.**
> Many websites still show the old command. Use this one:
>
> ```bash
> brew install heartleo/tap/zlib-cli
> ```
>
> Installed the old `zlib` formula from this tap? Homebrew does not move it to
> the new name, and `brew upgrade` never updates it. Replace it once. The first
> command removes `zlib` only when it is the old command, never Homebrew's own
> library:
>
> ```bash
> brew list zlib | grep -q bin/zlib && brew uninstall zlib
> brew install heartleo/tap/zlib-cli
> ```
>
> The installed command is still `zlib`.
>
> Project: [heartleo/zlib](https://github.com/heartleo/zlib), a CLI for Z-Library.
