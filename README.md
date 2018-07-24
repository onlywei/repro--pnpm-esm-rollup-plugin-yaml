# repro--pnpm-esm-rollup-plugin-yaml
Repro repo for an issue when using pnpm with esm and rollup-plugin-yaml

To see the failure case, follow these steps:

1. Clone the repo and `cd` into it
2. Run `pnpm i`
3. Run `pnpm test`

Notice the error. There should not be an error.

Note that it does not matter if `index.js` uses `import` nor `require()`. Both loading methods fail.
