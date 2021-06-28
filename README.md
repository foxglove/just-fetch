# @foxglove/just-fetch

Isomorphic ponyfill wrapping native browser fetch and node-fetch.

### Usage

```ts
import fetch from "@foxglove/just-fetch";
```

Usage is the same whether you are targeting browsers or node.js. The browser
target returns the native `window.fetch` implementation, and in node.js the
`node-fetch` library is returned.

### License

@foxglove/just-fetch is released under the [MIT License](/LICENSE.md).
