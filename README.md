# asdf-nsc

[![CI](https://github.com/dex4er/asdf-nsc/actions/workflows/ci.yml/badge.svg)](https://github.com/dex4er/asdf-nsc/actions/workflows/ci.yml)

[NSC](https://github.com/nats-io/nsc) plugin for the [asdf](https://github.com/asdf-vm/asdf) version manager.

NSC is a tool for creating NATS account and user access configurations.

## Prerequisites

- jq (only if `GITHUB_API_TOKEN` environment variable is used)
- unzip

## Install

```shell
asdf plugin-add nsc https://github.com/dex4er/asdf-nsc.git
asdf install nsc latest
asdf global nsc latest
```

## Use

Check out the [asdf](https://github.com/asdf-vm/asdf) readme for instructions.
