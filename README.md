# Repro for https://github.com/webpack/webpack/issues/17288

## Instructions

```
npm install
npm run build
npm start
```

## Expected behavior

Log from each line is the same (probably `{ default: 'default' }`)

## Actual behavior

```
Import CJS default from mjs:  { default: 'default' }
Import CJS default from mts:  default
```
