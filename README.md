eslint-config-atlas
===================

sane and safe eslint config to use and/or extend

[![build status](https://img.shields.io/travis/sonnyp/eslint-config-atlas/master.svg?style=flat-square)](https://travis-ci.org/sonnyp/eslint-config-atlas/branches)

This [eslint](http://eslint.org/) config provides a sane and safe eslint config to use and/or extend.

### Usage

```
npm install eslint eslint-config-atlas --save
```

and extend this configuration, see [Extending Configuration Files](http://eslint.org/docs/user-guide/configuring#extending-configuration-files) eslint documentation.

### Examples

JSON .eslintrc

```
{
  extends: [
    'atlas'
  ]
}
```

YAML .eslintrc

```
extends:
  - 'atlas'
```
