# eslint-config-chasevida

[![Version npm](https://img.shields.io/npm/v/eslint-config-chasevida.svg?style=flat-square)](https://www.npmjs.com/package/eslint-config-chasevida)
[![Dependencies](https://img.shields.io/david/peer/chasevida/eslint-config-chasevida.svg?style=flat-square)](https://david-dm.org/chasevida/eslint-config-chasevida)

A pretty common ESLint config setup that can be shared around. To get this working you simply install this via npm then add the followingn to your ESLint config file.

**Note:** This ESLint config is essentially a fork from [eslint-config-hapi](https://github.com/continuationlabs/eslint-config-hapi). Those devs are ace so best stick with theirs, this is just for a few styling differences that my team prefers.


## Install

```
npm install --save-dev eslint-config-chasevida
```

## Use

In your `.eslintrc.js` file add the following:

```
{
  "extends": "chasevida"
}
```

## Contributing

If you are submitting a PR to add or change an existing rule please make sure you run `$ npm run docs` to re-generate the README.md with the updated rule list. As a rule of thumb it should be one commit per rule for easy reference for changes.

**SemVer?**

Changes that are breaking e.g. upgrading from a warning to an exception should be a major bump. Downgrading to a warning should be a minor bump. Anything else related to a warning (say changing some config) could just be a patch I guess. Suggestions welcome on better ways to version this... could use a date based system¿?

## Rules
