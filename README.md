# URL Poly

A polyfill for the [URL web api](https://developer.mozilla.org/en-US/docs/Web/API/URL).

## Install

```
npm install url-poly
```

## Usage

```
import URL from 'url-poly'

// create a URL
const url = new URL(window.location)
```

When you're ready to drop support for IE, just remove the import and your code will work the same.