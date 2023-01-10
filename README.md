# ChopChopAction
ChopChopAction an GitHub action for dynamic application security testing on web applications

This action will scan your web application for vulnerabilities using [ChopChop](https://github.com/isontheline/ChopChop).

## Inputs

### `host`
**Required** The host to scan. Example : `https://foobar.com`.

## Example usage
```
uses: actions/chopchop@v1
with:
  host: 'https://foobar.com'
```