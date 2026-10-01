# homebrew-bosun

Homebrew tap for [bosun](https://github.com/everydaydevopsio/bosun), an
event-driven AI code-review controller for Kubernetes.

## Install

```bash
brew install everydaydevopsio/bosun/bosun
bosun version
```

Or tap first:

```bash
brew tap everydaydevopsio/bosun
brew install bosun
```

## Upgrade

```bash
brew update && brew upgrade bosun
```

## What is in here

`Casks/bosun.rb` is generated and committed by
[GoReleaser](https://goreleaser.com) from the `publish_cli` job in
[`bosun/.github/workflows/publish.yml`](https://github.com/everydaydevopsio/bosun/blob/main/.github/workflows/publish.yml)
on every release. **Do not edit it by hand** — the next release overwrites it.

macOS binaries are signed with a Developer ID certificate and notarized by
Apple before the release is published, so they install without a Gatekeeper
prompt. Linux archives are published to the same GitHub Release.

To change what lands here, change `.goreleaser.yaml` in the bosun repository.

## License

bosun is MIT licensed. See
[everydaydevopsio/bosun](https://github.com/everydaydevopsio/bosun/blob/main/LICENSE).
