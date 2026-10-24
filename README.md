# @x12i/xentra-types usage example

Shared TypeScript contracts and Zod schemas for Xentra.

This consuming application demonstrates **validate incoming json and report contract errors** using the published npm package, pinned to `0.2.0`.

## Run

Requires Node.js 24 or newer and npm. The example needs no service credentials.

```sh
npm install --ignore-scripts
npm start
```

## Example

[`src/index.mjs`](src/index.mjs) contains the complete example. Assertions check the demonstrated behavior and the program prints a small result.

## When to use the package

- Validate Xentra payloads using the shared runtime schemas.
- Share domain contracts across the SDK, API and React consumers.

## Links

- [npm package](https://www.npmjs.com/package/@x12i/xentra-types)
- [Implementation monorepo](https://github.com/x12i/xentra)
- [Reviewed package source](https://github.com/x12i/xentra/tree/004372e6695509bf2e95d2e4e53d4534e81dd312/packages/types)

The `package.json` in this repository is private to prevent accidental publication of the example application under an npm package name.
