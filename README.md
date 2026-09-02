# homebrew-clift

Homebrew tap for [Clift](https://github.com/leazoot/clift), the attachment
bridge for coding agents running over SSH.

```sh
brew install leazoot/clift/clift
```

That installs `clift` and `clift-relayd` from the release archives on the
main repository, checked against the SHA-256 digests recorded in the formula.
The formula is generated from each release's `SHA256SUMS` by
`scripts/update-packaging.sh` in the main repository and copied here
verbatim; report problems with it [there](https://github.com/leazoot/clift/issues).

Every release is also signed with Sigstore. Homebrew does not check those
signatures; `SECURITY.md` in the main repository shows how to.
