# :gear: `setup-seki`

## About

This action can be run on `ubuntu-latest`, `windows-latest`, and `macos-latest` GitHub Actions runners, and will install and expose a specified version of the `seki` CLI on the runner environment.

## Usage

Setup the `seki` CLI:

```yaml
steps:
- uses: oscarbc96/setup-seki@v1
```

A specific version of the `seki` CLI can be installed:

```yaml
steps:
- uses: oscarbc96/setup-seki@v1
  with:
    version:
      0.0.9
```

## Inputs
The actions supports the following inputs:

- `version`: The version of `seki` to install, defaulting to `0.0.9`
