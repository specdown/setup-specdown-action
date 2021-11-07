# Setup Specdown

Setup Specdown in your github action

## Inputs

### `version`

**Optional** Version to install, for example `0.55.5`. Default
`"latest"`.

## Example usage

### Installing the latest version

``` yaml
  specdown:
    runs-on: ubuntu-latest
    steps:
    - uses: actions/checkout@v2
    - uses: specdown/setup-specdown-action@v0.2.3
    - run: specdown run README.md
```

## More information

See [specdown/specdown](https://github.com/specdown/specdown)
