# ChopChopAction
ChopChopAction is an GitHub action for dynamic application security testing on web applications

This action will scan your web application for vulnerabilities using [ChopChop](https://github.com/isontheline/ChopChop).

## Inputs

### `host`
**Required** The host to scan. Example : `https://example.net`.

### `maxSeverity`
**Optional** The maximum severity to be allowed. Examples : "Low" / "Medium" / "High". Default : `Low`.

### `httpRequestTimeout`
**Optional** The maximum time to wait for a HTTP response. Default : `10`.

### `signatures`
**Optional** The path to the signatures file. Default : `/tmp/chopchop.yml`.

### `userAgent`
**Optional** The user agent to use while making HTTP requests. Default : `ChopChop`.

## Example usage
```
uses: isontheline/ChopChopAction@v1
with:
  host: 'https://example.net'
```