# ChopChopAction
ChopChopAction an GitHub action for dynamic application security testing on web applications

This action will scan your web application for vulnerabilities using [ChopChop](https://github.com/isontheline/ChopChop).

## Inputs

### `host`
**Required** The host to scan. Example : `https://example.net`.

### `maxSeverity`
**Optional** The maximum severity to be allowed. Examples : "Low" / "Medium" / "High". Default : `Low`.

### `httpRequestTimeout`
**Optional** The maximum time to wait for a HTTP response. Default : `10`.

## Example usage
```
uses: actions/chopchop@v1
with:
  host: 'https://example.net'
```