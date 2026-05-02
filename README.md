# homebrew-localpress

Homebrew tap for [localpress](https://github.com/gfargo/localpress) — local-compute WordPress media optimization.

## Install

```bash
brew tap gfargo/localpress
brew install localpress
```

Or in one step:

```bash
brew install gfargo/localpress/localpress
```

## Upgrade

```bash
brew upgrade localpress
```

## What is localpress?

`localpress` is a CLI tool that uses your laptop's CPU and GPU to compress images, remove backgrounds, convert formats, and round-trip with desktop editors — then syncs the results back to your remote WordPress site via the REST API. No recurring credits. No cloud SaaS. No plugin to install on the WP side.

```bash
# Connect a WordPress site
localpress init

# Audit your media library
localpress audit

# Optimize unprocessed images
localpress optimize --unoptimized --apply

# Remove background with local AI
localpress remove-bg 123

# Open in your editor, watch for saves, sync back
localpress edit 123
```

## Source

Formula source lives in the [main localpress repo](https://github.com/gfargo/localpress/blob/main/Formula/localpress.rb) and is updated automatically on each release.
