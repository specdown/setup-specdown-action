# Setup Specdown

Put specdown on the path

## Inputs

### `version`

**Optional** Version to install, for example `0.55.5`. Default
`"latest"`.

## Example usage

### Checking all markdown files

``` yaml
  lint-markdown:
    runs-on: ubuntu-latest
    steps:
    - uses: actions/checkout@v2
    - uses: PurpleBooth/setup-specdown-action@v0.1.0
```

## More information

See [specdown/specdown](https://github.com/specdown/specdown)
