# eslint-config

Set of ESLint rules.

## Install

`npm i @rcmedeiros/eslint-config`

## Usage

Make sure you have an ESLint plugin installed

In the project's root , create the file `eslintrc.json` and paste:

```json
{
    "extends": "@rcmedeiros"
}
```

If you use mocha , create the file `eslintrc.json` in your test folder and paste:

```json
{
    "env": {
        "mocha": true
    },
    "rules": {
        "no-unused-expressions": "off"
    }
}

```
