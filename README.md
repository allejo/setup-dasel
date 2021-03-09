# Setup Dasel on GitHub Actions

[![build-test](https://github.com/allejo/setup-dasel/actions/workflows/test-run.yml/badge.svg)](https://github.com/allejo/setup-dasel/actions/workflows/test-run.yml)

[Dasel](https://github.com/TomWright/dasel) is an open source utility similar to `jq` but handles a lot more languages than just JSON. This GitHub Action allows you to easily install the `dasel` CLI without needing to remember the OS specific commands to download the executable.

## Usage

```yaml
- name: Setup `dasel` CLI
  uses: allejo/setup-dasel@v1
```

### Parameters

- `version` (optional) - The version of `dasel` to install; without specifying this value it will default to pulling the latest version

## License

[MIT](./LICENSE)
