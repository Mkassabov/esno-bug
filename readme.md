# Esno Bug Reproduction

## What is the bug

When upgrading from esno 0.14.0 to 0.15.0 imports aliased via typescript's `path` no longer work

## Structure of Examples

There is a folder called v0.14.0 and a folder called v0.15.0 these are exactly the same except for the version of esno (named respectively to the folder).

## Running the examples

Both examples can be run the exact same way

### install dependencies

```
npm install
```

### run code

```
npm run start
```

## Other Notes about this repo

- vscode eslint doesn't really like multiple eslint files in the same folder so a .vscode that handles this is included
