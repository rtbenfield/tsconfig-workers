# TSConfig base for Cloudflare Workers

This packages provides a base TSConfig file for use within Cloudflare Workers projects. It's intended to complement the excellent [@tsconfig/bases](https://github.com/tsconfig/bases) project.

## Usage

Add the package to your `"devDependencies"`:

```sh
npm install --save-dev @rtbenfield/tsconfig-workers
```

Add to your `tsconfig.json`:

```json
"extends": "@rtbenfield/tsconfig-workers"
```

### Usage with @tsconfig/bases

It's recommended to use this base alongside [@tsconfig/strictest](https://www.npmjs.com/package/@tsconfig/strictest):

Add both packages to your `"devDependencies"`:

```sh
npm install --save-dev @rtbenfield/tsconfig-workers @tsconfig/strictest
```

Add to your `tsconfig.json`:

```json
"extends": ["@tsconfig/strictest", "@rtbenfield/tsconfig-workers"]
```
