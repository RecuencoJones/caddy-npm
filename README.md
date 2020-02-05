[![npm version](https://badge.fury.io/js/caddy.svg)](https://badge.fury.io/js/caddy)

# caddy-npm

Installs [caddy](https://github.com/caddyserver/caddy) with `npm` using [go-npm](https://github.com/sanathkr/go-npm).

## Publishing

Update `version` field in `package.json` with the latest release of `caddy`.
Also check `goBinary.url` object to make sure binaries have matching versions.

Then run:

```
npm publish
```
