# minis.js

> TypeScript SDK to build Soapbox Minis.

[![CI](https://github.com/SoapboxSocial/minis.js/actions/workflows/main.yml/badge.svg)](https://github.com/SoapboxSocial/minis.js/actions/workflows/main.yml)
[![npm version](https://img.shields.io/npm/v/@soapboxsocial/minis.js)](https://www.npmjs.org/package/@soapboxsocial/minis.js)
[![bundlephobia](https://img.shields.io/bundlephobia/minzip/@soapboxsocial/minis.js)](https://bundlephobia.com/result?p=@soapboxsocial/minis.js@1.0.0)
[![code style: prettier](https://img.shields.io/badge/code_style-prettier-ff69b4.svg)](https://github.com/prettier/prettier)

## Table of Contents

- [Install](#install)
- [API](#api)
- [Building A Mini](#building-a-mini)
- [License](#license)

## Install

```sh
$ npm install --save @soapboxsocial/minis.js
```

OR

```sh
$ yarn add @soapboxsocial/minis.js
```

---

## API

<!-- Generated by documentation.js. Update this documentation by updating the source code. -->

#### Table of Contents

- [getUser](#getuser)
- [getMembers](#getmembers)
- [getRoom](#getroom)
- [onClose](#onclose)
  - [Parameters](#parameters)

### getUser

Get the current user of the Mini

Returns **[Promise](https://developer.mozilla.org/docs/Web/JavaScript/Reference/Global_Objects/Promise)&lt;User>**

### getMembers

Get all of the users in a Soapbox room

Returns **[Promise](https://developer.mozilla.org/docs/Web/JavaScript/Reference/Global_Objects/Promise)&lt;[Array](https://developer.mozilla.org/docs/Web/JavaScript/Reference/Global_Objects/Array)&lt;User>>**

### getRoom

Get the details of the Soapbox room

Returns **[Promise](https://developer.mozilla.org/docs/Web/JavaScript/Reference/Global_Objects/Promise)&lt;Room>**

### onClose

Function to handle when an app is closed, can be used for app state cleanup.

#### Parameters

- `callback` **[Function](https://developer.mozilla.org/docs/Web/JavaScript/Reference/Statements/function)**

## Building a Mini

If you want to build your own Soapbox Mini or have an idea that you'd like to run past us, [send us an email](mailto:support@soapbox.social).

## License

[MIT License](https://opensource.org/licenses/MIT) © [Soaper Inc.](https://soapbox.social/)
