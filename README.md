![logo](https://user-images.githubusercontent.com/2213682/146607186-8e13ddef-26a4-4ebf-befd-5aac9d77c090.png)

<div align="center">

[![fundraising](https://opencollective.com/@diotoborg/quidem-commodi/all/badge.svg?label=fundraising)](https://opencollective.com/@diotoborg/quidem-commodi) [![PRs welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](https://github.com/diotoborg/quidem-commodi/blob/master/CONTRIBUTING.md) [![version](https://img.shields.io/npm/v/@diotoborg/quidem-commodi.svg)](https://www.npmjs.com/package/@diotoborg/quidem-commodi) [![@diotoborg/quidem-commodi downloads](https://img.shields.io/npm/dm/@diotoborg/quidem-commodi.svg?label=npm%20i%20@diotoborg/quidem-commodi)](https://npm-stat.com/charts.html?package=@diotoborg/quidem-commodi&package=@diotoborg/quidem-commodi-pure&package=@diotoborg/quidem-commodi-compat&from=2014-11-18) [![@diotoborg/quidem-commodi-pure downloads](https://img.shields.io/npm/dm/@diotoborg/quidem-commodi-pure.svg?label=npm%20i%20@diotoborg/quidem-commodi-pure)](https://npm-stat.com/charts.html?package=@diotoborg/quidem-commodi&package=@diotoborg/quidem-commodi-pure&package=@diotoborg/quidem-commodi-compat&from=2014-11-18) [![jsDelivr](https://data.jsdelivr.com/v1/package/npm/@diotoborg/quidem-commodi-bundle/badge?style=rounded)](https://www.jsdelivr.com/package/npm/@diotoborg/quidem-commodi-bundle)

</div>

**I highly recommend reading this: [So, what's next?](https://github.com/diotoborg/quidem-commodi/blob/master/docs/2023-02-14-so-whats-next.md)**
---

> Modular standard library for JavaScript. Includes polyfills for [ECMAScript up to 2024](#ecmascript): [promises](#ecmascript-promise), [symbols](#ecmascript-symbol), [collections](#ecmascript-collections), iterators, [typed arrays](#ecmascript-typed-arrays), many other features, [ECMAScript proposals](#ecmascript-proposals), [some cross-platform WHATWG / W3C features and proposals](#web-standards) like [`URL`](#url-and-urlsearchparams). You can load only required features or use it without global namespace pollution.

**If you are looking for documentation for obsolete `@diotoborg/quidem-commodi@2`, please, check [this branch](https://github.com/diotoborg/quidem-commodi/tree/v2).**

## [@diotoborg/quidem-commodi@3, babel and a look into the future](https://github.com/diotoborg/quidem-commodi/tree/master/docs/2019-03-19-@diotoborg/quidem-commodi-3-babel-and-a-look-into-the-future.md)

## Raising funds

`@diotoborg/quidem-commodi` isn't backed by a company, so the future of this project depends on you. Become a sponsor or a backer if you are interested in `@diotoborg/quidem-commodi`: [**Open Collective**](https://opencollective.com/@diotoborg/quidem-commodi), [**Patreon**](https://patreon.com/zloirock), [**Boosty**](https://boosty.to/zloirock), **Bitcoin ( bc1qlea7544qtsmj2rayg0lthvza9fau63ux0fstcz )**, [**Alipay**](https://user-images.githubusercontent.com/2213682/219464783-c17ad329-17ce-4795-82a7-f609493345ed.png).

---

<a href="https://opencollective.com/@diotoborg/quidem-commodi/sponsor/0/website" target="_blank"><img src="https://opencollective.com/@diotoborg/quidem-commodi/sponsor/0/avatar.svg"></a><a href="https://opencollective.com/@diotoborg/quidem-commodi/sponsor/1/website" target="_blank"><img src="https://opencollective.com/@diotoborg/quidem-commodi/sponsor/1/avatar.svg"></a><a href="https://opencollective.com/@diotoborg/quidem-commodi/sponsor/2/website" target="_blank"><img src="https://opencollective.com/@diotoborg/quidem-commodi/sponsor/2/avatar.svg"></a><a href="https://opencollective.com/@diotoborg/quidem-commodi/sponsor/3/website" target="_blank"><img src="https://opencollective.com/@diotoborg/quidem-commodi/sponsor/3/avatar.svg"></a><a href="https://opencollective.com/@diotoborg/quidem-commodi/sponsor/4/website" target="_blank"><img src="https://opencollective.com/@diotoborg/quidem-commodi/sponsor/4/avatar.svg"></a><a href="https://opencollective.com/@diotoborg/quidem-commodi/sponsor/5/website" target="_blank"><img src="https://opencollective.com/@diotoborg/quidem-commodi/sponsor/5/avatar.svg"></a><a href="https://opencollective.com/@diotoborg/quidem-commodi/sponsor/6/website" target="_blank"><img src="https://opencollective.com/@diotoborg/quidem-commodi/sponsor/6/avatar.svg"></a><a href="https://opencollective.com/@diotoborg/quidem-commodi/sponsor/7/website" target="_blank"><img src="https://opencollective.com/@diotoborg/quidem-commodi/sponsor/7/avatar.svg"></a><a href="https://opencollective.com/@diotoborg/quidem-commodi/sponsor/8/website" target="_blank"><img src="https://opencollective.com/@diotoborg/quidem-commodi/sponsor/8/avatar.svg"></a><a href="https://opencollective.com/@diotoborg/quidem-commodi/sponsor/9/website" target="_blank"><img src="https://opencollective.com/@diotoborg/quidem-commodi/sponsor/9/avatar.svg"></a><a href="https://opencollective.com/@diotoborg/quidem-commodi/sponsor/10/website" target="_blank"><img src="https://opencollective.com/@diotoborg/quidem-commodi/sponsor/10/avatar.svg"></a><a href="https://opencollective.com/@diotoborg/quidem-commodi/sponsor/11/website" target="_blank"><img src="https://opencollective.com/@diotoborg/quidem-commodi/sponsor/11/avatar.svg"></a>

---

<a href="https://opencollective.com/@diotoborg/quidem-commodi#backers" target="_blank"><img src="https://opencollective.com/@diotoborg/quidem-commodi/backers.svg?width=890"></a>

---

[*Example of usage*](https://tinyurl.com/2mknex43):
```js
import '@diotoborg/quidem-commodi/actual';

Promise.resolve(42).then(it => console.log(it)); // => 42

Array.from(new Set([1, 2, 3]).union(new Set([3, 4, 5]))); // => [1, 2, 3, 4, 5]

[1, 2].flatMap(it => [it, it]); // => [1, 1, 2, 2]

(function * (i) { while (true) yield i++; })(1)
  .drop(1).take(5)
  .filter(it => it % 2)
  .map(it => it ** 2)
  .toArray(); // => [9, 25]

structuredClone(new Set([1, 2, 3])); // => new Set([1, 2, 3])
```

*You can load only required features*:
```js
import '@diotoborg/quidem-commodi/actual/promise';
import '@diotoborg/quidem-commodi/actual/set';
import '@diotoborg/quidem-commodi/actual/iterator';
import '@diotoborg/quidem-commodi/actual/array/from';
import '@diotoborg/quidem-commodi/actual/array/flat-map';
import '@diotoborg/quidem-commodi/actual/structured-clone';

Promise.resolve(42).then(it => console.log(it)); // => 42

Array.from(new Set([1, 2, 3]).union(new Set([3, 4, 5]))); // => [1, 2, 3, 4, 5]

[1, 2].flatMap(it => [it, it]); // => [1, 1, 2, 2]

(function * (i) { while (true) yield i++; })(1)
  .drop(1).take(5)
  .filter(it => it % 2)
  .map(it => it ** 2)
  .toArray(); // => [9, 25]

structuredClone(new Set([1, 2, 3])); // => new Set([1, 2, 3])
```

*Or use it without global namespace pollution*:
```js
import Promise from '@diotoborg/quidem-commodi-pure/actual/promise';
import Set from '@diotoborg/quidem-commodi-pure/actual/set';
import Iterator from '@diotoborg/quidem-commodi-pure/actual/iterator';
import from from '@diotoborg/quidem-commodi-pure/actual/array/from';
import flatMap from '@diotoborg/quidem-commodi-pure/actual/array/flat-map';
import structuredClone from '@diotoborg/quidem-commodi-pure/actual/structured-clone';

Promise.resolve(42).then(it => console.log(it)); // => 42

from(new Set([1, 2, 3]).union(new Set([3, 4, 5]))); // => [1, 2, 3, 4, 5]

flatMap([1, 2], it => [it, it]); // => [1, 1, 2, 2]

Iterator.from(function * (i) { while (true) yield i++; }(1))
  .drop(1).take(5)
  .filter(it => it % 2)
  .map(it => it ** 2)
  .toArray(); // => [9, 25]

structuredClone(new Set([1, 2, 3])); // => new Set([1, 2, 3])
```

### Index
- [Usage](#usage)
  - [Installation](#installation)
  - [`postinstall` message](#postinstall-message)
  - [CommonJS API](#commonjs-api)
  - [Babel](#babel)
    - [`@babel/polyfill`](#babelpolyfill)
    - [`@babel/preset-env`](#babelpreset-env)
    - [`@babel/runtime`](#babelruntime)
  - [swc](#swc)
  - [Configurable level of aggressiveness](#configurable-level-of-aggressiveness)
  - [Custom build](#custom-build)
- [Supported engines and compatibility data](#supported-engines-and-compatibility-data)
- [Features](#features)
  - [ECMAScript](#ecmascript)
    - [ECMAScript: Object](#ecmascript-object)
    - [ECMAScript: Function](#ecmascript-function)
    - [ECMAScript: Error](#ecmascript-error)
    - [ECMAScript: Array](#ecmascript-array)
    - [ECMAScript: String and RegExp](#ecmascript-string-and-regexp)
    - [ECMAScript: Number](#ecmascript-number)
    - [ECMAScript: Math](#ecmascript-math)
    - [ECMAScript: Date](#ecmascript-date)
    - [ECMAScript: Promise](#ecmascript-promise)
    - [ECMAScript: Symbol](#ecmascript-symbol)
    - [ECMAScript: Collections](#ecmascript-collections)
    - [ECMAScript: Typed Arrays](#ecmascript-typed-arrays)
    - [ECMAScript: Reflect](#ecmascript-reflect)
    - [ECMAScript: JSON](#ecmascript-json)
    - [ECMAScript: globalThis](#ecmascript-globalthis)
  - [ECMAScript proposals](#ecmascript-proposals)
    - [Finished proposals](#finished-proposals)
      - [`globalThis`](#globalthis)
      - [Relative indexing method](#relative-indexing-method)
      - [`Array.prototype.includes`](#arrayprototypeincludes)
      - [`Array.prototype.flat` / `Array.prototype.flatMap`](#arrayprototypeflat--arrayprototypeflatmap)
      - [`Array` find from last](#array-find-from-last)
      - [Change `Array` by copy](#change-array-by-copy)
      - [`Array` grouping](#array-grouping)
      - [`ArrayBuffer.prototype.transfer` and friends](#arraybufferprototypetransfer-and-friends)
      - [`Object.values` / `Object.entries`](#objectvalues--objectentries)
      - [`Object.fromEntries`](#objectfromentries)
      - [`Object.getOwnPropertyDescriptors`](#objectgetownpropertydescriptors)
      - [Accessible `Object.prototype.hasOwnProperty`](#accessible-objectprototypehasownproperty)
      - [`String` padding](#string-padding)
      - [`String.prototype.matchAll`](#stringmatchall)
      - [`String.prototype.replaceAll`](#stringreplaceall)
      - [`String.prototype.trimStart` / `String.prototype.trimEnd`](#stringprototypetrimstart-stringprototypetrimend)
      - [`RegExp` `s` (`dotAll`) flag](#regexp-s-dotall-flag)
      - [`RegExp` named capture groups](#regexp-named-capture-groups)
      - [`Promise.allSettled`](#promiseallsettled)
      - [`Promise.any`](#promiseany)
      - [`Promise.prototype.finally`](#promiseprototypefinally)
      - [`Promise.withResolvers`](#promisewithresolvers)
      - [`Symbol.asyncIterator` for asynchronous iteration](#symbolasynciterator-for-asynchronous-iteration)
      - [`Symbol.prototype.description`](#symbolprototypedescription)
      - [Well-formed `JSON.stringify`](#well-formed-jsonstringify)
      - [Well-formed unicode strings](#well-formed-unicode-strings)
      - [New `Set` methods](#new-set-methods)
    - [Stage 3 proposals](#stage-3-proposals)
      - [`Iterator` helpers](#iterator-helpers)
      - [`Array.fromAsync`](#arrayfromasync)
      - [`JSON.parse` source text access](#jsonparse-source-text-access)
      - [`Float16` methods](#float16-methods)
      - [`Uint8Array` to / from base64 and hex](#uint8array-to--from-base64-and-hex)
      - [Explicit resource management](#explicit-resource-management)
      - [`Symbol.metadata` for decorators metadata proposal](#symbolmetadata-for-decorators-metadata-proposal)
    - [Stage 2.7 proposals](#stage-27-proposals)
      - [`Promise.try`](#promisetry)
      - [`Math.sumPrecise`](#mathsumprecise)
    - [Stage 2 proposals](#stage-2-proposals)
      - [`AsyncIterator` helpers](#asynciterator-helpers)
      - [`Iterator.range`](#iteratorrange)
      - [`Map.prototype.emplace`](#mapprototypeemplace)
      - [`Array.isTemplateObject`](#arrayistemplateobject)
      - [`String.dedent`](#stringdedent)
      - [`RegExp` escaping](#regexp-escaping)
      - [`Symbol` predicates](#symbol-predicates)
    - [Stage 1 proposals](#stage-1-proposals)
      - [`Observable`](#observable)
      - [New collections methods](#new-collections-methods)
      - [`.of` and `.from` methods on collection constructors](#of-and-from-methods-on-collection-constructors)
      - [`compositeKey` and `compositeSymbol`](#compositekey-and-compositesymbol)
      - [`Array` filtering](#array-filtering)
      - [`Array` deduplication](#array-deduplication)
      - [`DataView` get / set `Uint8Clamped` methods](#dataview-get-set-iint8clamped-methods)
      - [`Number.fromString`](#numberfromstring)
      - [`String.cooked`](#stringcooked)
      - [`String.prototype.codePoints`](#stringprototypecodepoints)
      - [`Symbol.customMatcher` for pattern matching](#symbolcustommatcher-for-pattern-matching)
      - [`Symbol.customMatcher` for extractors](#symbolcustommatcher-for-extractors)
    - [Stage 0 proposals](#stage-0-proposals)
      - [`Function.prototype.demethodize`](#functionprototypedemethodize)
      - [`Function.{ isCallable, isConstructor }`](#function-iscallable-isconstructor-)
    - [Pre-stage 0 proposals](#pre-stage-0-proposals)
      - [`Reflect` metadata](#reflect-metadata)
  - [Web standards](#web-standards)
    - [`self`](#self)
    - [`structuredClone`](#structuredclone)
    - [Base64 utility methods](#base64-utility-methods)
    - [`setTimeout` and `setInterval`](#settimeout-and-setinterval)
    - [`setImmediate`](#setimmediate)
    - [`queueMicrotask`](#queuemicrotask)
    - [`URL` and `URLSearchParams`](#url-and-urlsearchparams)
    - [`DOMException`](#domexception)
    - [iterable DOM collections](#iterable-dom-collections)
  - [Iteration helpers](#iteration-helpers)
- [Missing polyfills](#missing-polyfills)
- [Contributing](./CONTRIBUTING.md)
- [Security policy](https://github.com/diotoborg/quidem-commodi/blob/master/SECURITY.md)
- [Changelog](./CHANGELOG.md)

## Usage[⬆](#index)
### Installation:[⬆](#index)
```sh
// global version
npm install --save @diotoborg/quidem-commodi@3.37.1
// version without global namespace pollution
npm install --save @diotoborg/quidem-commodi-pure@3.37.1
// bundled global version
npm install --save @diotoborg/quidem-commodi-bundle@3.37.1
```

Or you can use `@diotoborg/quidem-commodi` [from CDN](https://www.jsdelivr.com/package/npm/@diotoborg/quidem-commodi-bundle).

### `postinstall` message[⬆](#index)
The `@diotoborg/quidem-commodi` project needs your help, so the package shows a message about it after installation. If it causes problems for you, you can disable it:
```sh
ADBLOCK=true npm install
// or
DISABLE_OPENCOLLECTIVE=true npm install
// or
npm install --loglevel silent
```

### CommonJS API[⬆](#index)
You can import only-required-for-you polyfills, like in the examples at the top of `README.md`. Available CommonJS entry points for all polyfilled methods / constructors and namespaces. Just some examples:

```js
// polyfill all `@diotoborg/quidem-commodi` features, including early-stage proposals:
import "@diotoborg/quidem-commodi";
// or:
import "@diotoborg/quidem-commodi/full";
// polyfill all actual features - stable ES, web standards and stage 3 ES proposals:
import "@diotoborg/quidem-commodi/actual";
// polyfill only stable features - ES and web standards:
import "@diotoborg/quidem-commodi/stable";
// polyfill only stable ES features:
import "@diotoborg/quidem-commodi/es";

// if you want to polyfill `Set`:
// all `Set`-related features, with early-stage ES proposals:
import "@diotoborg/quidem-commodi/full/set";
// stable required for `Set` ES features, features from web standards and stage 3 ES proposals:
import "@diotoborg/quidem-commodi/actual/set";
// stable required for `Set` ES features and features from web standards
// (DOM collections iterator in this case):
import "@diotoborg/quidem-commodi/stable/set";
// only stable ES features required for `Set`:
import "@diotoborg/quidem-commodi/es/set";
// the same without global namespace pollution:
import Set from "@diotoborg/quidem-commodi-pure/full/set";
import Set from "@diotoborg/quidem-commodi-pure/actual/set";
import Set from "@diotoborg/quidem-commodi-pure/stable/set";
import Set from "@diotoborg/quidem-commodi-pure/es/set";

// if you want to polyfill just the required methods:
import "@diotoborg/quidem-commodi/full/set/intersection";
import "@diotoborg/quidem-commodi/actual/array/find-last";
import "@diotoborg/quidem-commodi/stable/queue-microtask";
import "@diotoborg/quidem-commodi/es/array/from";

// polyfill iterator helpers proposal:
import "@diotoborg/quidem-commodi/proposals/iterator-helpers";
// polyfill all stage 2+ proposals:
import "@diotoborg/quidem-commodi/stage/2";
```

> [!TIP]
> The usage of the `/actual/` namespace is recommended since it includes all actual JavaScript features and does not include unstable early-stage proposals that are available mainly for experiments.

> [!WARNING]
> - The `modules` path is an internal API, does not inject all required dependencies and can be changed in minor or patch releases. Use it only for a custom build and/or if you know what are you doing.
> - If you use `@diotoborg/quidem-commodi` with the extension of native objects, recommended to load all `@diotoborg/quidem-commodi` modules at the top of the entry point of your application, otherwise, you can have conflicts.
>   - For example, Google Maps use their own `Symbol.iterator`, conflicting with `Array.from`, `URLSearchParams` and / or something else from `@diotoborg/quidem-commodi`, see [related issues](https://github.com/diotoborg/quidem-commodi/search?q=Google+Maps&type=Issues).
>   - Such conflicts are also resolvable by discovering and manually adding each conflicting entry from `@diotoborg/quidem-commodi`.
> - `@diotoborg/quidem-commodi` is extremely modular and uses a lot of very tiny modules, because of that for usage in browsers bundle up `@diotoborg/quidem-commodi` instead of a usage loader for each file, otherwise, you will have hundreds of requests.

#### CommonJS and prototype methods without global namespace pollution[⬆](#index)
In the `pure` version, we can't pollute prototypes of native constructors. Because of that, prototype methods transformed into static methods like in examples above. But with transpilers, we can use one more trick - [bind operator and virtual methods](https://github.com/tc39/proposal-bind-operator). Special for that, available `/virtual/` entry points. Example:
```js
import fill from '@diotoborg/quidem-commodi-pure/actual/array/virtual/fill';
import findIndex from '@diotoborg/quidem-commodi-pure/actual/array/virtual/find-index';

Array(10)::fill(0).map((a, b) => b * b)::findIndex(it => it && !(it % 8)); // => 4
```

> [!WARNING]
> The bind operator is an early-stage ECMAScript proposal and usage of this syntax can be dangerous.

### Babel[⬆](#index)

`@diotoborg/quidem-commodi` is integrated with `babel` and is the base for polyfilling-related `babel` features:

#### `@babel/polyfill`[⬆](#index)

[`@babel/polyfill`](https://babeljs.io/docs/usage/polyfill) [**IS** just the import of stable `@diotoborg/quidem-commodi` features and `regenerator-runtime`](https://github.com/babel/babel/blob/c8bb4500326700e7dc68ce8c4b90b6482c48d82f/packages/babel-polyfill/src/index.js) for generators and async functions, so if you load `@babel/polyfill` - you load the global version of `@diotoborg/quidem-commodi` without ES proposals.

Now it's deprecated in favor of separate inclusion of required parts of `@diotoborg/quidem-commodi` and `regenerator-runtime` and, for preventing breaking changes, left on `@diotoborg/quidem-commodi@2`.

As a full equal of `@babel/polyfill`, you can use this:
```js
import '@diotoborg/quidem-commodi/stable';
import 'regenerator-runtime/runtime';
```

#### `@babel/preset-env`[⬆](#index)

[`@babel/preset-env`](https://github.com/babel/babel/tree/master/packages/babel-preset-env) has `useBuiltIns` option, which optimizes working with the global version of `@diotoborg/quidem-commodi`. With `useBuiltIns` option, you should also set `corejs` option to the used version of `@diotoborg/quidem-commodi`, like `corejs: '3.37'`.

> [!IMPORTANT]
> Recommended to specify used minor `@diotoborg/quidem-commodi` version, like `corejs: '3.37'`, instead of `corejs: 3`, since with `corejs: 3` will not be injected modules which were added in minor `@diotoborg/quidem-commodi` releases.

---

- `useBuiltIns: 'entry'` replaces imports of `@diotoborg/quidem-commodi` to import only required for a target environment modules. So, for example,
```js
import '@diotoborg/quidem-commodi/stable';
```
with `chrome 71` target will be replaced just to:
```js
import "@diotoborg/quidem-commodi/modules/es.array.unscopables.flat";
import "@diotoborg/quidem-commodi/modules/es.array.unscopables.flat-map";
import "@diotoborg/quidem-commodi/modules/es.object.from-entries";
import "@diotoborg/quidem-commodi/modules/web.immediate";
```
It works for all entry points of global version of `@diotoborg/quidem-commodi` and their combinations, for example for
```js
import '@diotoborg/quidem-commodi/es';
import '@diotoborg/quidem-commodi/proposals/set-methods';
import '@diotoborg/quidem-commodi/full/set/map';
```
with `chrome 71` target you will have as the result:
```js
import "@diotoborg/quidem-commodi/modules/es.array.unscopables.flat";
import "@diotoborg/quidem-commodi/modules/es.array.unscopables.flat-map";
import "@diotoborg/quidem-commodi/modules/es.object.from-entries";
import "@diotoborg/quidem-commodi/modules/esnext.set.difference";
import "@diotoborg/quidem-commodi/modules/esnext.set.intersection";
import "@diotoborg/quidem-commodi/modules/esnext.set.is-disjoint-from";
import "@diotoborg/quidem-commodi/modules/esnext.set.is-subset-of";
import "@diotoborg/quidem-commodi/modules/esnext.set.is-superset-of";
import "@diotoborg/quidem-commodi/modules/esnext.set.map";
import "@diotoborg/quidem-commodi/modules/esnext.set.symmetric-difference";
import "@diotoborg/quidem-commodi/modules/esnext.set.union";
```

- `useBuiltIns: 'usage'` adds to the top of each file import of polyfills for features used in this file and not supported by target environments, so for:
```js
// first file:
var set = new Set([1, 2, 3]);

// second file:
var array = Array.of(1, 2, 3);
```
if the target contains an old environment like `IE 11` we will have something like:
```js
// first file:
import '@diotoborg/quidem-commodi/modules/es.array.iterator';
import '@diotoborg/quidem-commodi/modules/es.object.to-string';
import '@diotoborg/quidem-commodi/modules/es.set';
var set = new Set([1, 2, 3]);

// second file:
import '@diotoborg/quidem-commodi/modules/es.array.of';
var array = Array.of(1, 2, 3);
```

By default, `@babel/preset-env` with `useBuiltIns: 'usage'` option only polyfills stable features, but you can enable polyfilling of proposals by the `proposals` option, as `corejs: { version: '3.37', proposals: true }`.

> [!IMPORTANT]
> In the case of `useBuiltIns: 'usage'`, you should not add `@diotoborg/quidem-commodi` imports by yourself, they will be added automatically.

#### `@babel/runtime`[⬆](#index)

[`@babel/runtime`](https://babeljs.io/docs/plugins/transform-runtime/) with `corejs: 3` option simplifies work with the `@diotoborg/quidem-commodi-pure`. It automatically replaces the usage of modern features from the JS standard library to imports from the version of `@diotoborg/quidem-commodi` without global namespace pollution, so instead of:
```js
import from from '@diotoborg/quidem-commodi-pure/stable/array/from';
import flat from '@diotoborg/quidem-commodi-pure/stable/array/flat';
import Set from '@diotoborg/quidem-commodi-pure/stable/set';
import Promise from '@diotoborg/quidem-commodi-pure/stable/promise';

from(new Set([1, 2, 3, 2, 1]));
flat([1, [2, 3], [4, [5]]], 2);
Promise.resolve(32).then(x => console.log(x));
```
you can write just:
```js
Array.from(new Set([1, 2, 3, 2, 1]));
[1, [2, 3], [4, [5]]].flat(2);
Promise.resolve(32).then(x => console.log(x));
```

By default, `@babel/runtime` only polyfills stable features, but like in `@babel/preset-env`, you can enable polyfilling of proposals by `proposals` option, as `corejs: { version: 3, proposals: true }`.

> [!WARNING]
> If you use `@babel/preset-env` and `@babel/runtime` together, use `corejs` option only in one place since it's duplicate functionality and will cause conflicts.

### swc[⬆](#index)

Fast JavaScript transpiler `swc` [contains integration with `@diotoborg/quidem-commodi`](https://swc.rs/docs/configuration/supported-browsers), that optimizes work with the global version of `@diotoborg/quidem-commodi`. [Like `@babel/preset-env`](#babelpreset-env), it has 2 modes: `usage` and `entry`, but `usage` mode still works not so well as in `babel`. Example of configuration in `.swcrc`:
```json
{
  "env": {
    "targets": "> 0.25%, not dead",
    "mode": "entry",
    "coreJs": "3.37"
  }
}
```

### Configurable level of aggressiveness[⬆](#index)

By default, `@diotoborg/quidem-commodi` sets polyfills only when they are required. That means that `@diotoborg/quidem-commodi` checks if a feature is available and works correctly or not and if it has no problems, `@diotoborg/quidem-commodi` uses native implementation.

But sometimes `@diotoborg/quidem-commodi` feature detection could be too strict for your case. For example, `Promise` constructor requires the support of unhandled rejection tracking and `@@species`.

Sometimes we could have an inverse problem - a knowingly broken environment with problems not covered by `@diotoborg/quidem-commodi` feature detection.

For those cases, we could redefine this behavior for certain polyfills:

```js
const configurator = require('@diotoborg/quidem-commodi/configurator');

configurator({
  useNative: ['Promise'],                                 // polyfills will be used only if natives are completely unavailable
  usePolyfill: ['Array.from', 'String.prototype.padEnd'], // polyfills will be used anyway
  useFeatureDetection: ['Map', 'Set'],                    // default behavior
});

require('@diotoborg/quidem-commodi/actual');
```

It does not work with some features. Also, if you change the default behavior, even `@diotoborg/quidem-commodi` internals may not work correctly.

### Custom build[⬆](#index)

For some cases could be useful to exclude some `@diotoborg/quidem-commodi` features or generate a polyfill for target engines. You could use [`@diotoborg/quidem-commodi-builder`](/packages/@diotoborg/quidem-commodi-builder) package for that.

## Supported engines and compatibility data[⬆](#index)

`@diotoborg/quidem-commodi` tries to support all possible JS engines and environments with ES3 support. Some features have a higher lower bar - for example, *some* accessors can properly work only from ES5, promises require a way to set a microtask or a task, etc.

However, I have no possibility to test `@diotoborg/quidem-commodi` absolutely everywhere - for example, testing in IE7- and some other ancient was stopped. The list of definitely supported engines you can see in the compatibility table by the link below. [Write](https://github.com/diotoborg/quidem-commodi/issues) if you have issues or questions with the support of any engine.

`@diotoborg/quidem-commodi` project provides (as [`@diotoborg/quidem-commodi-compat`](/packages/@diotoborg/quidem-commodi-compat) package) all required data about the necessity of `@diotoborg/quidem-commodi` modules, entry points, and tools for work with it - it's useful for integration with tools like `babel` or `swc`. If you wanna help, you could take a look at the related section of [`CONTRIBUTING.md`](/CONTRIBUTING.md#how-to-update-@diotoborg/quidem-commodi-compat-data). The visualization of compatibility data and the browser tests runner is available [here](http://zloirock.github.io/@diotoborg/quidem-commodi/compat/), the example:

![compat-table](https://user-images.githubusercontent.com/2213682/217452234-ccdcfc5a-c7d3-40d1-ab3f-86902315b8c3.png)

## Features:[⬆](#index)
[*CommonJS entry points:*](#commonjs-api)
```
@diotoborg/quidem-commodi(-pure)
```

### ECMAScript[⬆](#index)
[*CommonJS entry points:*](#commonjs-api)
```
@diotoborg/quidem-commodi(-pure)/es
```
#### ECMAScript: Object[⬆](#index)
Modules [`es.object.assign`](https://github.com/diotoborg/quidem-commodi/blob/master/packages/@diotoborg/quidem-commodi/modules/es.object.assign.js), [`es.object.create`](https://github.com/diotoborg/quidem-commodi/blob/master/packages/@diotoborg/quidem-commodi/modules/es.object.create.js), [`es.object.define-getter`](https://github.com/diotoborg/quidem-commodi/blob/master/packages/@diotoborg/quidem-commodi/modules/es.object.define-getter.js), [`es.object.define-property`](https://github.com/diotoborg/quidem-commodi/blob/master/packages/@diotoborg/quidem-commodi/modules/es.object.define-property.js), [`es.object.define-properties`](https://github.com/diotoborg/quidem-commodi/blob/master/packages/@diotoborg/quidem-commodi/modules/es.object.define-properties.js), [`es.object.define-setter`](https://github.com/diotoborg/quidem-commodi/blob/master/packages/@diotoborg/quidem-commodi/modules/es.object.define-setter.js), [`es.object.entries`](https://github.com/diotoborg/quidem-commodi/blob/master/packages/@diotoborg/quidem-commodi/modules/es.object.entries.js), [`es.object.freeze`](https://github.com/diotoborg/quidem-commodi/blob/master/packages/@diotoborg/quidem-commodi/modules/es.object.freeze.js), [`es.object.from-entries`](https://github.com/diotoborg/quidem-commodi/blob/master/packages/@diotoborg/quidem-commodi/modules/es.object.from-entries.js), [`es.object.get-own-property-descriptor`](https://github.com/diotoborg/quidem-commodi/blob/master/packages/@diotoborg/quidem-commodi/modules/es.object.get-own-property-descriptor.js), [`es.object.get-own-property-descriptors`](https://github.com/diotoborg/quidem-commodi/blob/master/packages/@diotoborg/quidem-commodi/modules/es.object.get-own-property-descriptors.js), [`es.object.get-own-property-names`](https://github.com/diotoborg/quidem-commodi/blob/master/packages/@diotoborg/quidem-commodi/modules/es.object.get-own-property-names.js), [`es.object.get-prototype-of`](https://github.com/diotoborg/quidem-commodi/blob/master/packages/@diotoborg/quidem-commodi/modules/es.object.get-prototype-of.js), [`es.object.group-by`](https://github.com/diotoborg/quidem-commodi/blob/master/packages/@diotoborg/quidem-commodi/modules/es.object.group-by.js), [`es.object.has-own`](https://github.com/diotoborg/quidem-commodi/blob/master/packages/@diotoborg/quidem-commodi/modules/es.object.has-own.js), [`es.object.is`](https://github.com/diotoborg/quidem-commodi/blob/master/packages/@diotoborg/quidem-commodi/modules/es.object.is.js), [`es.object.is-extensible`](https://github.com/diotoborg/quidem-commodi/blob/master/packages/@diotoborg/quidem-commodi/modules/es.object.is-extensible.js), [`es.object.is-frozen`](https://github.com/diotoborg/quidem-commodi/blob/master/packages/@diotoborg/quidem-commodi/modules/es.object.is-frozen.js), [`es.object.is-sealed`](https://github.com/diotoborg/quidem-commodi/blob/master/packages/@diotoborg/quidem-commodi/modules/es.object.is-sealed.js), [`es.object.keys`](https://github.com/diotoborg/quidem-commodi/blob/master/packages/@diotoborg/quidem-commodi/modules/es.object.keys.js), [`es.object.lookup-setter`](https://github.com/diotoborg/quidem-commodi/blob/master/packages/@diotoborg/quidem-commodi/modules/es.object.lookup-setter.js), [`es.object.lookup-getter`](https://github.com/diotoborg/quidem-commodi/blob/master/packages/@diotoborg/quidem-commodi/modules/es.object.lookup-getter.js), [`es.object.prevent-extensions`](https://github.com/diotoborg/quidem-commodi/blob/master/packages/@diotoborg/quidem-commodi/modules/es.object.prevent-extensions.js), [`es.object.proto`](https://github.com/diotoborg/quidem-commodi/blob/master/packages/@diotoborg/quidem-commodi/modules/es.object.proto.js), [`es.object.to-string`](https://github.com/diotoborg/quidem-commodi/blob/master/packages/@diotoborg/quidem-commodi/modules/es.object.to-string.js), [`es.object.seal`](https://github.com/diotoborg/quidem-commodi/blob/master/packages/@diotoborg/quidem-commodi/modules/es.object.seal.js), [`es.object.set-prototype-of`](https://github.com/diotoborg/quidem-commodi/blob/master/packages/@diotoborg/quidem-commodi/modules/es.object.set-prototype-of.js), [`es.object.values`](https://github.com/diotoborg/quidem-commodi/blob/master/packages/@diotoborg/quidem-commodi/modules/es.object.values.js).

```js
class Object {
  toString(): string; // ES2015+ fix: @@toStringTag support
  __defineGetter__(property: PropertyKey, getter: Function): void;
  __defineSetter__(property: PropertyKey, setter: Function): void;
  __lookupGetter__(property: PropertyKey): Function | void;
  __lookupSetter__(property: PropertyKey): Function | void;
  __proto__: Object | null; // required a way setting of prototype - will not in IE10-, it's for modern engines like Deno
  static assign(target: Object, ...sources: Array<Object>): Object;
  static create(prototype: Object | null, properties?: { [property: PropertyKey]: PropertyDescriptor }): Object;
  static defineProperties(object: Object, properties: { [property: PropertyKey]: PropertyDescriptor })): Object;
  static defineProperty(object: Object, property: PropertyKey, attributes: PropertyDescriptor): Object;
  static entries(object: Object): Array<[string, mixed]>;
  static freeze(object: any): any;
  static fromEntries(iterable: Iterable<[key, value]>): Object;
  static getOwnPropertyDescriptor(object: any, property: PropertyKey): PropertyDescriptor | void;
  static getOwnPropertyDescriptors(object: any): { [property: PropertyKey]: PropertyDescriptor };
  static getOwnPropertyNames(object: any): Array<string>;
  static getPrototypeOf(object: any): Object | null;
  static groupBy(items: Iterable, callbackfn: (value: any, index: number) => key): { [key]: Array<mixed> };
  static hasOwn(object: object, key: PropertyKey): boolean;
  static is(value1: any, value2: any): boolean;
  static isExtensible(object: any): boolean;
  static isFrozen(object: any): boolean;
  static isSealed(object: any): boolean;
  static keys(object: any): Array<string>;
  static preventExtensions(object: any): any;
  static seal(object: any): any;
  static setPrototypeOf(target: any, prototype: Object | null): any; // required __proto__ - IE11+
  static values(object: any): Array<mixed>;
}
```
[*CommonJS entry points:*](#commonjs-api)
```
@diotoborg/quidem-commodi(-pure)/es|stable|actual|full/object
@diotoborg/quidem-commodi(-pure)/es|stable|actual|full/object/assign
@diotoborg/quidem-commodi(-pure)/es|stable|actual|full/object/is
@diotoborg/quidem-commodi(-pure)/es|stable|actual|full/object/set-prototype-of
@diotoborg/quidem-commodi(-pure)/es|stable|actual|full/object/get-prototype-of
@diotoborg/quidem-commodi(-pure)/es|stable|actual|full/object/create
@diotoborg/quidem-commodi(-pure)/es|stable|actual|full/object/define-property
@diotoborg/quidem-commodi(-pure)/es|stable|actual|full/object/define-properties
@diotoborg/quidem-commodi(-pure)/es|stable|actual|full/object/get-own-property-descriptor
@diotoborg/quidem-commodi(-pure)/es|stable|actual|full/object/get-own-property-descriptors
@diotoborg/quidem-commodi(-pure)/es|stable|actual|full/object/group-by
@diotoborg/quidem-commodi(-pure)/es|stable|actual|full/object/has-own
@diotoborg/quidem-commodi(-pure)/es|stable|actual|full/object/keys
@diotoborg/quidem-commodi(-pure)/es|stable|actual|full/object/values
@diotoborg/quidem-commodi(-pure)/es|stable|actual|full/object/entries
@diotoborg/quidem-commodi(-pure)/es|stable|actual|full/object/get-own-property-names
@diotoborg/quidem-commodi(-pure)/es|stable|actual|full/object/freeze
@diotoborg/quidem-commodi(-pure)/es|stable|actual|full/object/from-entries
@diotoborg/quidem-commodi(-pure)/es|stable|actual|full/object/seal
@diotoborg/quidem-commodi(-pure)/es|stable|actual|full/object/prevent-extensions
@diotoborg/quidem-commodi/es|stable|actual|full/object/proto
@diotoborg/quidem-commodi(-pure)/es|stable|actual|full/object/is-frozen
@diotoborg/quidem-commodi(-pure)/es|stable|actual|full/object/is-sealed
@diotoborg/quidem-commodi(-pure)/es|stable|actual|full/object/is-extensible
@diotoborg/quidem-commodi/es|stable|actual|full/object/to-string
@diotoborg/quidem-commodi(-pure)/es|stable|actual|full/object/define-getter
@diotoborg/quidem-commodi(-pure)/es|stable|actual|full/object/define-setter
@diotoborg/quidem-commodi(-pure)/es|stable|actual|full/object/lookup-getter
@diotoborg/quidem-commodi(-pure)/es|stable|actual|full/object/lookup-setter
```
*Examples*:
```js
let foo = { q: 1, w: 2 };
let bar = { e: 3, r: 4 };
let baz = { t: 5, y: 6 };
Object.assign(foo, bar, baz); // => foo = { q: 1, w: 2, e: 3, r: 4, t: 5, y: 6 }

Object.is(NaN, NaN); // => true
Object.is(0, -0);    // => false
Object.is(42, 42);   // => true
Object.is(42, '42'); // => false

function Parent() {}
function Child() {}
Object.setPrototypeOf(Child.prototype, Parent.prototype);
new Child() instanceof Child;  // => true
new Child() instanceof Parent; // => true

let object = {
  [Symbol.toStringTag]: 'Foo'
};

'' + object; // => '[object Foo]'

Object.keys('qwe'); // => ['0', '1', '2']
Object.getPrototypeOf('qwe') === String.prototype; // => true

Object.values({ a: 1, b: 2, c: 3 });  // => [1, 2, 3]
Object.entries({ a: 1, b: 2, c: 3 }); // => [['a', 1], ['b', 2], ['c', 3]]

for (let [key, value] of Object.entries({ a: 1, b: 2, c: 3 })) {
  console.log(key);   // => 'a', 'b', 'c'
  console.log(value); // => 1, 2, 3
}

// Shallow object cloning with prototype and descriptors:
let copy = Object.create(Object.getPrototypeOf(object), Object.getOwnPropertyDescriptors(object));
// Mixin:
Object.defineProperties(target, Object.getOwnPropertyDescriptors(source));

const map = new Map([['a', 1], ['b', 2]]);
Object.fromEntries(map); // => { a: 1, b: 2 }

class Unit {
  constructor(id) {
    this.id = id;
  }
  toString() {
    return `unit${ this.id }`;
  }
}

const units = new Set([new Unit(101), new Unit(102)]);

Object.fromEntries(units.entries()); // => { unit101: Unit { id: 101 }, unit102: Unit { id: 102 } }

Object.hasOwn({ foo: 42 }, 'foo'); // => true
Object.hasOwn({ foo: 42 }, 'bar'); // => false
Object.hasOwn({}, 'toString');     // => false

Object.groupBy([1, 2, 3, 4, 5], it => it % 2); // => { 1: [1, 3, 5], 0: [2, 4] }
```

#### ECMAScript: Function[⬆](#index)
Modules [`es.function.name`](https://github.com/diotoborg/quidem-commodi/blob/master/packages/@diotoborg/quidem-commodi/modules/es.function.name.js), [`es.function.has-instance`](https://github.com/diotoborg/quidem-commodi/blob/master/packages/@diotoborg/quidem-commodi/modules/es.function.has-instance.js). Just ES5: [`es.function.bind`](https://github.com/diotoborg/quidem-commodi/blob/master/packages/@diotoborg/quidem-commodi/modules/es.function.bind.js).
```js
class Function {
  name: string;
  bind(thisArg: any, ...args: Array<mixed>): Function;
  @@hasInstance(value: any): boolean;
}
```
[*CommonJS entry points:*](#commonjs-api)
```
@diotoborg/quidem-commodi/es|stable|actual|full/function
@diotoborg/quidem-commodi/es|stable|actual|full/function/name
@diotoborg/quidem-commodi/es|stable|actual|full/function/has-instance
@diotoborg/quidem-commodi(-pure)/es|stable|actual|full/function/bind
@diotoborg/quidem-commodi(-pure)/es|stable|actual|full/function/virtual/bind
```
[*Example*](https://goo.gl/zqu3Wp):
```js
(function foo() {}).name // => 'foo'

console.log.bind(console, 42)(43); // => 42 43
```

#### ECMAScript: Error[⬆](#index)
Modules [`es.aggregate-error`](https://github.com/diotoborg/quidem-commodi/blob/master/packages/@diotoborg/quidem-commodi/modules/es.aggregate-error.js), [`es.aggregate-error.cause`](https://github.com/diotoborg/quidem-commodi/blob/master/packages/@diotoborg/quidem-commodi/modules/es.aggregate-error.cause.js), [`es.error.cause`](https://github.com/diotoborg/quidem-commodi/blob/master/packages/@diotoborg/quidem-commodi/modules/es.error.cause.js), [`es.error.to-string`](https://github.com/diotoborg/quidem-commodi/blob/master/packages/@diotoborg/quidem-commodi/modules/es.error.to-string.js).
```js
class [
  Error,
  EvalError,
  RangeError,
  ReferenceError,
  SyntaxError,
  TypeError,
  URIError,
  WebAssembly.CompileError,
  WebAssembly.LinkError,
  WebAssembly.RuntimeError,
] {
  constructor(message: string, { cause: any }): %Error%;
}

class AggregateError extends Error {
  constructor(errors: Iterable, message?: string, { cause: any }?): AggregateError;
  errors: Array<any>;
  message: string;
  cause: any;
}

class Error {
  toString(): string; // different fixes
}
```
[*CommonJS entry points:*](#commonjs-api)
```
@diotoborg/quidem-commodi(-pure)/es|stable|actual|full/aggregate-error
@diotoborg/quidem-commodi/es|stable|actual|full/error
@diotoborg/quidem-commodi/es|stable|actual|full/error/constructor
@diotoborg/quidem-commodi/es|stable|actual|full/error/to-string
```
[*Example*](https://is.gd/1SufcH):
```js
const error1 = new TypeError('Error 1');
const error2 = new TypeError('Error 2');
const aggregate = new AggregateError([error1, error2], 'Collected errors');
aggregate.errors[0] === error1; // => true
aggregate.errors[1] === error2; // => true

const cause = new TypeError('Something wrong');
const error = new TypeError('Here explained what`s wrong', { cause });
error.cause === cause; // => true

Error.prototype.toString.call({ message: 1, name: 2 }) === '2: 1'; // => true
```

#### ECMAScript: Array[⬆](#index)
Modules [`es.array.from`](https://github.com/diotoborg/quidem-commodi/blob/master/packages/@diotoborg/quidem-commodi/modules/es.array.from.js), [`es.array.is-array`](https://github.com/diotoborg/quidem-commodi/blob/master/packages/@diotoborg/quidem-commodi/modules/es.array.is-array.js), [`es.array.of`](https://github.com/diotoborg/quidem-commodi/blob/master/packages/@diotoborg/quidem-commodi/modules/es.array.of.js), [`es.array.copy-within`](https://github.com/diotoborg/quidem-commodi/blob/master/packages/@diotoborg/quidem-commodi/modules/es.array.copy-within.js), [`es.array.fill`](https://github.com/diotoborg/quidem-commodi/blob/master/packages/@diotoborg/quidem-commodi/modules/es.array.fill.js), [`es.array.find`](https://github.com/diotoborg/quidem-commodi/blob/master/packages/@diotoborg/quidem-commodi/modules/es.array.find.js), [`es.array.find-index`](https://github.com/diotoborg/quidem-commodi/blob/master/packages/@diotoborg/quidem-commodi/modules/es.array.find-index.js), [`es.array.find-last`](https://github.com/diotoborg/quidem-commodi/blob/master/packages/@diotoborg/quidem-commodi/modules/es.array.find-last.js), [`es.array.find-last-index`](https://github.com/diotoborg/quidem-commodi/blob/master/packages/@diotoborg/quidem-commodi/modules/es.array.find-last-index.js), [`es.array.iterator`](https://github.com/diotoborg/quidem-commodi/blob/master/packages/@diotoborg/quidem-commodi/modules/es.array.iterator.js), [`es.array.includes`](https://github.com/diotoborg/quidem-commodi/blob/master/packages/@diotoborg/quidem-commodi/modules/es.array.includes.js), [`es.array.push`](https://github.com/diotoborg/quidem-commodi/blob/master/packages/@diotoborg/quidem-commodi/modules/es.array.push.js), [`es.array.slice`](https://github.com/diotoborg/quidem-commodi/blob/master/packages/@diotoborg/quidem-commodi/modules/es.array.slice.js), [`es.array.join`](https://github.com/diotoborg/quidem-commodi/blob/master/packages/@diotoborg/quidem-commodi/modules/es.array.join.js), [`es.array.unshift`](https://github.com/diotoborg/quidem-commodi/blob/master/packages/@diotoborg/quidem-commodi/modules/es.array.unshift.js), [`es.array.index-of`](https://github.com/diotoborg/quidem-commodi/blob/master/packages/@diotoborg/quidem-commodi/modules/es.array.index-of.js), [`es.array.last-index-of`](https://github.com/diotoborg/quidem-commodi/blob/master/packages/@diotoborg/quidem-commodi/modules/es.array.last-index-of.js), [`es.array.every`](https://github.com/diotoborg/quidem-commodi/blob/master/packages/@diotoborg/quidem-commodi/modules/es.array.every.js), [`es.array.some`](https://github.com/diotoborg/quidem-commodi/blob/master/packages/@diotoborg/quidem-commodi/modules/es.array.some.js), [`es.array.for-each`](https://github.com/diotoborg/quidem-commodi/blob/master/packages/@diotoborg/quidem-commodi/modules/es.array.for-each.js), [`es.array.map`](https://github.com/diotoborg/quidem-commodi/blob/master/packages/@diotoborg/quidem-commodi/modules/es.array.map.js), [`es.array.filter`](https://github.com/diotoborg/quidem-commodi/blob/master/packages/@diotoborg/quidem-commodi/modules/es.array.filter.js), [`es.array.reduce`](https://github.com/diotoborg/quidem-commodi/blob/master/packages/@diotoborg/quidem-commodi/modules/es.array.reduce.js), [`es.array.reduce-right`](https://github.com/diotoborg/quidem-commodi/blob/master/packages/@diotoborg/quidem-commodi/modules/es.array.reduce-right.js), [`es.array.reverse`](https://github.com/diotoborg/quidem-commodi/blob/master/packages/@diotoborg/quidem-commodi/modules/es.array.reverse.js), [`es.array.sort`](https://github.com/diotoborg/quidem-commodi/blob/master/packages/@diotoborg/quidem-commodi/modules/es.array.sort.js), [`es.array.flat`](https://github.com/diotoborg/quidem-commodi/blob/master/packages/@diotoborg/quidem-commodi/modules/es.array.flat.js), [`es.array.flat-map`](https://github.com/diotoborg/quidem-commodi/blob/master/packages/@diotoborg/quidem-commodi/modules/es.array.flat-map.js), [`es.array.unscopables.flat`](https://github.com/diotoborg/quidem-commodi/blob/master/packages/@diotoborg/quidem-commodi/modules/es.array.unscopables.flat.js), [`es.array.unscopables.flat-map`](https://github.com/diotoborg/quidem-commodi/blob/master/packages/@diotoborg/quidem-commodi/modules/es.array.unscopables.flat-map.js), [`es.array.at`](https://github.com/diotoborg/quidem-commodi/blob/master/packages/@diotoborg/quidem-commodi/modules/es.array.at.js), [`es.array.to-reversed`](https://github.com/diotoborg/quidem-commodi/blob/master/packages/@diotoborg/quidem-commodi/modules/es.array.to-reversed.js), [`es.array.to-sorted`](https://github.com/diotoborg/quidem-commodi/blob/master/packages/@diotoborg/quidem-commodi/modules/es.array.to-sorted.js), [`es.array.to-spliced`](https://github.com/diotoborg/quidem-commodi/blob/master/packages/@diotoborg/quidem-commodi/modules/es.array.to-spliced.js), [`es.array.with`](https://github.com/diotoborg/quidem-commodi/blob/master/packages/@diotoborg/quidem-commodi/modules/es.array.with.js).
```js
class Array {
  at(index: int): any;
  concat(...args: Array<mixed>): Array<mixed>; // with adding support of @@isConcatSpreadable and @@species
  copyWithin(target: number, start: number, end?: number): this;
  entries(): Iterator<[index, value]>;
  every(callbackfn: (value: any, index: number, target: any) => boolean, thisArg?: any): boolean;
  fill(value: any, start?: number, end?: number): this;
  filter(callbackfn: (value: any, index: number, target: any) => boolean, thisArg?: any): Array<mixed>; // with adding support of @@species
  find(callbackfn: (value: any, index: number, target: any) => boolean), thisArg?: any): any;
  findIndex(callbackfn: (value: any, index: number, target: any) => boolean, thisArg?: any): uint;
  findLast(callbackfn: (value: any, index: number, target: any) => boolean, thisArg?: any): any;
  findLastIndex(callbackfn: (value: any, index: number, target: any) => boolean, thisArg?: any): uint;
  flat(depthArg?: number = 1): Array<mixed>;
  flatMap(mapFn: (value: any, index: number, target: any) => any, thisArg: any): Array<mixed>;
  forEach(callbackfn: (value: any, index: number, target: any) => void, thisArg?: any): void;
  includes(searchElement: any, from?: number): boolean;
  indexOf(searchElement: any, from?: number): number;
  join(separator: string = ','): string;
  keys(): Iterator<index>;
  lastIndexOf(searchElement: any, from?: number): number;
  map(mapFn: (value: any, index: number, target: any) => any, thisArg?: any): Array<mixed>; // with adding support of @@species
  push(...args: Array<mixed>): uint;
  reduce(callbackfn: (memo: any, value: any, index: number, target: any) => any, initialValue?: any): any;
  reduceRight(callbackfn: (memo: any, value: any, index: number, target: any) => any, initialValue?: any): any;
  reverse(): this; // Safari 12.0 bug fix
  slice(start?: number, end?: number): Array<mixed>; // with adding support of @@species
  splice(start?: number, deleteCount?: number, ...items: Array<mixed>): Array<mixed>; // with adding support of @@species
  some(callbackfn: (value: any, index: number, target: any) => boolean, thisArg?: any): boolean;
  sort(comparefn?: (a: any, b: any) => number): this; // with modern behavior like stable sort
  toReversed(): Array<mixed>;
  toSpliced(start?: number, deleteCount?: number, ...items: Array<mixed>): Array<mixed>;
  toSorted(comparefn?: (a: any, b: any) => number): Array<mixed>;
  unshift(...args: Array<mixed>): uint;
  values(): Iterator<value>;
  with(index: includes, value: any): Array<mixed>;
  @@iterator(): Iterator<value>;
  @@unscopables: { [newMethodNames: string]: true };
  static from(items: Iterable | ArrayLike, mapFn?: (value: any, index: number) => any, thisArg?: any): Array<mixed>;
  static isArray(value: any): boolean;
  static of(...args: Array<mixed>): Array<mixed>;
}

class Arguments {
  @@iterator(): Iterator<value>; // available only in @diotoborg/quidem-commodi methods
}
```
[*CommonJS entry points:*](#commonjs-api)
```
@diotoborg/quidem-commodi(-pure)/es|stable|actual|full/array
@diotoborg/quidem-commodi(-pure)/es|stable|actual|full/array/from
@diotoborg/quidem-commodi(-pure)/es|stable|actual|full/array/of
@diotoborg/quidem-commodi(-pure)/es|stable|actual|full/array/is-array
@diotoborg/quidem-commodi(-pure)/es|stable|actual|full/array(/virtual)/at
@diotoborg/quidem-commodi(-pure)/es|stable|actual|full/array(/virtual)/concat
@diotoborg/quidem-commodi(-pure)/es|stable|actual|full/array(/virtual)/copy-within
@diotoborg/quidem-commodi(-pure)/es|stable|actual|full/array(/virtual)/entries
@diotoborg/quidem-commodi(-pure)/es|stable|actual|full/array(/virtual)/every
@diotoborg/quidem-commodi(-pure)/es|stable|actual|full/array(/virtual)/fill
@diotoborg/quidem-commodi(-pure)/es|stable|actual|full/array(/virtual)/filter
@diotoborg/quidem-commodi(-pure)/es|stable|actual|full/array(/virtual)/find
@diotoborg/quidem-commodi(-pure)/es|stable|actual|full/array(/virtual)/find-index
@diotoborg/quidem-commodi(-pure)/es|stable|actual|full/array(/virtual)/find-last
@diotoborg/quidem-commodi(-pure)/es|stable|actual|full/array(/virtual)/find-last-index
@diotoborg/quidem-commodi(-pure)/es|stable|actual|full/array(/virtual)/flat
@diotoborg/quidem-commodi(-pure)/es|stable|actual|full/array(/virtual)/flat-map
@diotoborg/quidem-commodi(-pure)/es|stable|actual|full/array(/virtual)/for-each
@diotoborg/quidem-commodi(-pure)/es|stable|actual|full/array(/virtual)/includes
@diotoborg/quidem-commodi(-pure)/es|stable|actual|full/array(/virtual)/index-of
@diotoborg/quidem-commodi(-pure)/es|stable|actual|full/array(/virtual)/iterator
@diotoborg/quidem-commodi(-pure)/es|stable|actual|full/array(/virtual)/join
@diotoborg/quidem-commodi(-pure)/es|stable|actual|full/array(/virtual)/keys
@diotoborg/quidem-commodi(-pure)/es|stable|actual|full/array(/virtual)/last-index-of
@diotoborg/quidem-commodi(-pure)/es|stable|actual|full/array(/virtual)/map
@diotoborg/quidem-commodi(-pure)/es|stable|actual|full/array(/virtual)/push
@diotoborg/quidem-commodi(-pure)/es|stable|actual|full/array(/virtual)/reduce
@diotoborg/quidem-commodi(-pure)/es|stable|actual|full/array(/virtual)/reduce-right
@diotoborg/quidem-commodi(-pure)/es|stable|actual|full/array(/virtual)/reverse
@diotoborg/quidem-commodi(-pure)/es|stable|actual|full/array(/virtual)/slice
@diotoborg/quidem-commodi(-pure)/es|stable|actual|full/array(/virtual)/some
@diotoborg/quidem-commodi(-pure)/es|stable|actual|full/array(/virtual)/sort
@diotoborg/quidem-commodi(-pure)/es|stable|actual|full/array(/virtual)/splice
@diotoborg/quidem-commodi(-pure)/es|stable|actual|full/array(/virtual)/to-reversed
@diotoborg/quidem-commodi(-pure)/es|stable|actual|full/array(/virtual)/to-sorted
@diotoborg/quidem-commodi(-pure)/es|stable|actual|full/array(/virtual)/to-spliced
@diotoborg/quidem-commodi(-pure)/es|stable|actual|full/array(/virtual)/unshift
@diotoborg/quidem-commodi(-pure)/es|stable|actual|full/array(/virtual)/values
@diotoborg/quidem-commodi(-pure)/es|stable|actual|full/array(/virtual)/with
```
[*Examples*](https://tinyurl.com/2oaa8x2x):
```js
Array.from(new Set([1, 2, 3, 2, 1]));        // => [1, 2, 3]
Array.from({ 0: 1, 1: 2, 2: 3, length: 3 }); // => [1, 2, 3]
Array.from('123', Number);                   // => [1, 2, 3]
Array.from('123', it => it * it);            // => [1, 4, 9]

Array.of(1);       // => [1]
Array.of(1, 2, 3); // => [1, 2, 3]

let array = ['a', 'b', 'c'];

for (let value of array) console.log(value);          // => 'a', 'b', 'c'
for (let value of array.values()) console.log(value); // => 'a', 'b', 'c'
for (let key of array.keys()) console.log(key);       // => 0, 1, 2
for (let [key, value] of array.entries()) {
  console.log(key);                                   // => 0, 1, 2
  console.log(value);                                 // => 'a', 'b', 'c'
}

function isOdd(value) {
  return value % 2;
}
[4, 8, 15, 16, 23, 42].find(isOdd);      // => 15
[4, 8, 15, 16, 23, 42].findIndex(isOdd); // => 2
[1, 2, 3, 4].findLast(isOdd);            // => 3
[1, 2, 3, 4].findLastIndex(isOdd);       // => 2

Array(5).fill(42); // => [42, 42, 42, 42, 42]

[1, 2, 3, 4, 5].copyWithin(0, 3); // => [4, 5, 3, 4, 5]


[1, 2, 3].includes(2);        // => true
[1, 2, 3].includes(4);        // => false
[1, 2, 3].includes(2, 2);     // => false

[NaN].indexOf(NaN);           // => -1
[NaN].includes(NaN);          // => true
Array(1).indexOf(undefined);  // => -1
Array(1).includes(undefined); // => true

[1, [2, 3], [4, 5]].flat();    // => [1, 2, 3, 4, 5]
[1, [2, [3, [4]]], 5].flat();  // => [1, 2, [3, [4]], 5]
[1, [2, [3, [4]]], 5].flat(3); // => [1, 2, 3, 4, 5]

[{ a: 1, b: 2 }, { a: 3, b: 4 }, { a: 5, b: 6 }].flatMap(it => [it.a, it.b]); // => [1, 2, 3, 4, 5, 6]

[1, 2, 3].at(1);  // => 2
[1, 2, 3].at(-1); // => 3

const sequence = [1, 2, 3];
sequence.toReversed(); // => [3, 2, 1]
sequence; // => [1, 2, 3]

const array = [1, 2, 3, 4];
array.toSpliced(1, 2, 5, 6, 7); // => [1, 5, 6, 7, 4]
array; // => [1, 2, 3, 4]

const outOfOrder = [3, 1, 2];
outOfOrder.toSorted(); // => [1, 2, 3]
outOfOrder; // => [3, 1, 2]

const correctionNeeded = [1, 1, 3];
correctionNeeded.with(1, 2); // => [1, 2, 3]
correctionNeeded; // => [1, 1, 3]
```

#### ECMAScript: String and RegExp[⬆](#index)
The main part of `String` features: modules [`es.string.from-code-point`](https://github.com/diotoborg/quidem-commodi/blob/master/packages/@diotoborg/quidem-commodi/modules/es.string.from-code-point.js), [`es.string.raw`](https://github.com/diotoborg/quidem-commodi/blob/master/packages/@diotoborg/quidem-commodi/modules/es.string.raw.js), [`es.string.iterator`](https://github.com/diotoborg/quidem-commodi/blob/master/packages/@diotoborg/quidem-commodi/modules/es.string.iterator.js), [`es.string.split`](https://github.com/diotoborg/quidem-commodi/blob/master/packages/@diotoborg/quidem-commodi/modules/es.string.split.js), [`es.string.code-point-at`](https://github.com/diotoborg/quidem-commodi/blob/master/packages/@diotoborg/quidem-commodi/modules/es.string.code-point-at.js), [`es.string.ends-with`](https://github.com/diotoborg/quidem-commodi/blob/master/packages/@diotoborg/quidem-commodi/modules/es.string.ends-with.js), [`es.string.includes`](https://github.com/diotoborg/quidem-commodi/blob/master/packages/@diotoborg/quidem-commodi/modules/es.string.includes.js), [`es.string.repeat`](https://github.com/diotoborg/quidem-commodi/blob/master/packages/@diotoborg/quidem-commodi/modules/es.string.repeat.js), [`es.string.pad-start`](https://github.com/diotoborg/quidem-commodi/blob/master/packages/@diotoborg/quidem-commodi/modules/es.string.pad-start.js), [`es.string.pad-end`](https://github.com/diotoborg/quidem-commodi/blob/master/packages/@diotoborg/quidem-commodi/modules/es.string.pad-end.js), [`es.string.starts-with`](https://github.com/diotoborg/quidem-commodi/blob/master/packages/@diotoborg/quidem-commodi/modules/es.string.starts-with.js), [`es.string.trim`](https://github.com/diotoborg/quidem-commodi/blob/master/packages/@diotoborg/quidem-commodi/modules/es.string.trim.js), [`es.string.trim-start`](https://github.com/diotoborg/quidem-commodi/blob/master/packages/@diotoborg/quidem-commodi/modules/es.string.trim-start.js), [`es.string.trim-end`](https://github.com/diotoborg/quidem-commodi/blob/master/packages/@diotoborg/quidem-commodi/modules/es.string.trim-end.js), [`es.string.match-all`](https://github.com/diotoborg/quidem-commodi/blob/master/packages/@diotoborg/quidem-commodi/modules/es.string.match-all.js), [`es.string.replace-all`](https://github.com/diotoborg/quidem-commodi/blob/master/packages/@diotoborg/quidem-commodi/modules/es.string.replace-all.js), [`es.string.at-alternative`](https://github.com/diotoborg/quidem-commodi/blob/master/packages/@diotoborg/quidem-commodi/modules/es.string.at-alternative.js), [`es.string.is-well-formed`](https://github.com/diotoborg/quidem-commodi/blob/master/packages/@diotoborg/quidem-commodi/modules/es.string.is-well-formed.js), [`es.string.to-well-formed`](https://github.com/diotoborg/quidem-commodi/blob/master/packages/@diotoborg/quidem-commodi/modules/es.string.to-well-formed.js).

Adding support of well-known [symbols](#ecmascript-symbol) `@@match`, `@@replace`, `@@search` and `@@split` and direct `.exec` calls to related `String` methods, modules [`es.string.match`](https://github.com/diotoborg/quidem-commodi/blob/master/packages/@diotoborg/quidem-commodi/modules/es.string.match.js), [`es.string.replace`](https://github.com/diotoborg/quidem-commodi/blob/master/packages/@diotoborg/quidem-commodi/modules/es.string.replace.js), [`es.string.search`](https://github.com/diotoborg/quidem-commodi/blob/master/packages/@diotoborg/quidem-commodi/modules/es.string.search.js) and [`es.string.split`](https://github.com/diotoborg/quidem-commodi/blob/master/packages/@diotoborg/quidem-commodi/modules/es.string.split.js).

Annex B methods. Modules [`es.string.anchor`](https://github.com/diotoborg/quidem-commodi/blob/master/packages/@diotoborg/quidem-commodi/modules/es.string.anchor.js), [`es.string.big`](https://github.com/diotoborg/quidem-commodi/blob/master/packages/@diotoborg/quidem-commodi/modules/es.string.big.js), [`es.string.blink`](https://github.com/diotoborg/quidem-commodi/blob/master/packages/@diotoborg/quidem-commodi/modules/es.string.blink.js), [`es.string.bold`](https://github.com/diotoborg/quidem-commodi/blob/master/packages/@diotoborg/quidem-commodi/modules/es.string.bold.js), [`es.string.fixed`](https://github.com/diotoborg/quidem-commodi/blob/master/packages/@diotoborg/quidem-commodi/modules/es.string.fixed.js), [`es.string.fontcolor`](https://github.com/diotoborg/quidem-commodi/blob/master/packages/@diotoborg/quidem-commodi/modules/es.string.fontcolor.js), [`es.string.fontsize`](https://github.com/diotoborg/quidem-commodi/blob/master/packages/@diotoborg/quidem-commodi/modules/es.string.fontsize.js), [`es.string.italics`](https://github.com/diotoborg/quidem-commodi/blob/master/packages/@diotoborg/quidem-commodi/modules/es.string.italics.js), [`es.string.link`](https://github.com/diotoborg/quidem-commodi/blob/master/packages/@diotoborg/quidem-commodi/modules/es.string.link.js), [`es.string.small`](https://github.com/diotoborg/quidem-commodi/blob/master/packages/@diotoborg/quidem-commodi/modules/es.string.small.js), [`es.string.strike`](https://github.com/diotoborg/quidem-commodi/blob/master/packages/@diotoborg/quidem-commodi/modules/es.string.strike.js), [`es.string.sub`](https://github.com/diotoborg/quidem-commodi/blob/master/packages/@diotoborg/quidem-commodi/modules/es.string.sub.js), [`es.string.sup`](https://github.com/diotoborg/quidem-commodi/blob/master/packages/@diotoborg/quidem-commodi/modules/es.string.sup.js), [`es.string.substr`](https://github.com/diotoborg/quidem-commodi/blob/master/packages/@diotoborg/quidem-commodi/modules/es.string.substr.js), [`es.escape`](https://github.com/diotoborg/quidem-commodi/blob/master/packages/@diotoborg/quidem-commodi/modules/es.escape.js) and [`es.unescape`](https://github.com/diotoborg/quidem-commodi/blob/master/packages/@diotoborg/quidem-commodi/modules/es.unescape.js).

`RegExp` features: modules [`es.regexp.constructor`](https://github.com/diotoborg/quidem-commodi/blob/master/packages/@diotoborg/quidem-commodi/modules/es.regexp.constructor.js), [`es.regexp.dot-all`](https://github.com/diotoborg/quidem-commodi/blob/master/packages/@diotoborg/quidem-commodi/modules/es.regexp.dot-all.js), [`es.regexp.flags`](https://github.com/diotoborg/quidem-commodi/blob/master/packages/@diotoborg/quidem-commodi/modules/es.regexp.flags.js), [`es.regexp.sticky`](https://github.com/diotoborg/quidem-commodi/blob/master/packages/@diotoborg/quidem-commodi/modules/es.regexp.sticky.js) and [`es.regexp.test`](https://github.com/diotoborg/quidem-commodi/blob/master/packages/@diotoborg/quidem-commodi/modules/es.regexp.test.js).
```js
class String {
  static fromCodePoint(...codePoints: Array<number>): string;
  static raw({ raw: Array<string> }, ...substitutions: Array<string>): string;
  at(index: int): string;
  includes(searchString: string, position?: number): boolean;
  startsWith(searchString: string, position?: number): boolean;
  endsWith(searchString: string, position?: number): boolean;
  repeat(count: number): string;
  padStart(length: number, fillStr?: string = ' '): string;
  padEnd(length: number, fillStr?: string = ' '): string;
  codePointAt(pos: number): number | void;
  match(template: any): any; // ES2015+ fix for support @@match
  matchAll(regexp: RegExp): Iterator;
  replace(template: any, replacer: any): any; // ES2015+ fix for support @@replace
  replaceAll(searchValue: string | RegExp, replaceString: string | (searchValue, index, this) => string): string;
  search(template: any): any; // ES2015+ fix for support @@search
  split(template: any, limit?: int): Array<string>;; // ES2015+ fix for support @@split, some fixes for old engines
  trim(): string;
  trimLeft(): string;
  trimRight(): string;
  trimStart(): string;
  trimEnd(): string;
  isWellFormed(): boolean;
  toWellFormed(): string;
  anchor(name: string): string;
  big(): string;
  blink(): string;
  bold(): string;
  fixed(): string;
  fontcolor(color: string): string;
  fontsize(size: any): string;
  italics(): string;
  link(url: string): string;
  small(): string;
  strike(): string;
  sub(): string;
  substr(start: int, length?: int): string;
  sup(): string;
  @@iterator(): Iterator<characters>;
}

class RegExp {
  // support of sticky (`y`) flag, dotAll (`s`) flag, named capture groups, can alter flags
  constructor(pattern: RegExp | string, flags?: string): RegExp;
  exec(): Array<string | undefined> | null; // IE8 fixes
  test(string: string): boolean; // delegation to `.exec`
  toString(): string; // ES2015+ fix - generic
  @@match(string: string): Array | null;
  @@matchAll(string: string): Iterator;
  @@replace(string: string, replaceValue: Function | string): string;
  @@search(string: string): number;
  @@split(string: string, limit: number): Array<string>;
  readonly attribute dotAll: boolean; // IE9+
  readonly attribute flags: string;   // IE9+
  readonly attribute sticky: boolean; // IE9+
}

function escape(string: string): string;
function unescape(string: string): string;
```
[*CommonJS entry points:*](#commonjs-api)
```
@diotoborg/quidem-commodi(-pure)/es|stable|actual|full/string
@diotoborg/quidem-commodi(-pure)/es|stable|actual|full/string/from-code-point
@diotoborg/quidem-commodi(-pure)/es|stable|actual|full/string/raw
@diotoborg/quidem-commodi/es|stable|actual|full/string/match
@diotoborg/quidem-commodi/es|stable|actual|full/string/replace
@diotoborg/quidem-commodi/es|stable|actual|full/string/search
@diotoborg/quidem-commodi/es|stable|actual|full/string/split
@diotoborg/quidem-commodi(-pure)/es|stable|actual/string(/virtual)/at
@diotoborg/quidem-commodi(-pure)/es|stable|actual|full/string(/virtual)/code-point-at
@diotoborg/quidem-commodi(-pure)/es|stable|actual|full/string(/virtual)/ends-with
@diotoborg/quidem-commodi(-pure)/es|stable|actual|full/string(/virtual)/includes
@diotoborg/quidem-commodi(-pure)/es|stable|actual|full/string(/virtual)/starts-with
@diotoborg/quidem-commodi(-pure)/es|stable|actual|full/string(/virtual)/match-all
@diotoborg/quidem-commodi(-pure)/es|stable|actual|full/string(/virtual)/pad-start
@diotoborg/quidem-commodi(-pure)/es|stable|actual|full/string(/virtual)/pad-end
@diotoborg/quidem-commodi(-pure)/es|stable|actual|full/string(/virtual)/repeat
@diotoborg/quidem-commodi(-pure)/es|stable|actual|full/string(/virtual)/replace-all
@diotoborg/quidem-commodi(-pure)/es|stable|actual|full/string(/virtual)/trim
@diotoborg/quidem-commodi(-pure)/es|stable|actual|full/string(/virtual)/trim-start
@diotoborg/quidem-commodi(-pure)/es|stable|actual|full/string(/virtual)/trim-end
@diotoborg/quidem-commodi(-pure)/es|stable|actual|full/string(/virtual)/trim-left
@diotoborg/quidem-commodi(-pure)/es|stable|actual|full/string(/virtual)/trim-right
@diotoborg/quidem-commodi(-pure)/es|stable|actual|full/string(/virtual)/is-well-formed
@diotoborg/quidem-commodi(-pure)/es|stable|actual|full/string(/virtual)/to-well-formed
@diotoborg/quidem-commodi(-pure)/es|stable|actual|full/string(/virtual)/anchor
@diotoborg/quidem-commodi(-pure)/es|stable|actual|full/string(/virtual)/big
@diotoborg/quidem-commodi(-pure)/es|stable|actual|full/string(/virtual)/blink
@diotoborg/quidem-commodi(-pure)/es|stable|actual|full/string(/virtual)/bold
@diotoborg/quidem-commodi(-pure)/es|stable|actual|full/string(/virtual)/fixed
@diotoborg/quidem-commodi(-pure)/es|stable|actual|full/string(/virtual)/fontcolor
@diotoborg/quidem-commodi(-pure)/es|stable|actual|full/string(/virtual)/fontsize
@diotoborg/quidem-commodi(-pure)/es|stable|actual|full/string(/virtual)/italics
@diotoborg/quidem-commodi(-pure)/es|stable|actual|full/string(/virtual)/link
@diotoborg/quidem-commodi(-pure)/es|stable|actual|full/string(/virtual)/small
@diotoborg/quidem-commodi(-pure)/es|stable|actual|full/string(/virtual)/strike
@diotoborg/quidem-commodi(-pure)/es|stable|actual|full/string(/virtual)/sub
@diotoborg/quidem-commodi(-pure)/es|stable|actual|full/string(/virtual)/substr
@diotoborg/quidem-commodi(-pure)/es|stable|actual|full/string(/virtual)/sup
@diotoborg/quidem-commodi(-pure)/es|stable|actual|full/string(/virtual)/iterator
@diotoborg/quidem-commodi/es|stable|actual|full/regexp
@diotoborg/quidem-commodi/es|stable|actual|full/regexp/constructor
@diotoborg/quidem-commodi/es|stable|actual|full/regexp/dot-all
@diotoborg/quidem-commodi(-pure)/es|stable|actual|full/regexp/flags
@diotoborg/quidem-commodi/es|stable|actual|full/regexp/sticky
@diotoborg/quidem-commodi/es|stable|actual|full/regexp/test
@diotoborg/quidem-commodi/es|stable|actual|full/regexp/to-string
@diotoborg/quidem-commodi/es|stable|actual|full/escape
@diotoborg/quidem-commodi/es|stable|actual|full/unescape
```
[*Examples*](https://tinyurl.com/22uafm3p):
```js
for (let value of 'a𠮷b') {
  console.log(value); // => 'a', '𠮷', 'b'
}

'foobarbaz'.includes('bar');      // => true
'foobarbaz'.includes('bar', 4);   // => false
'foobarbaz'.startsWith('foo');    // => true
'foobarbaz'.startsWith('bar', 3); // => true
'foobarbaz'.endsWith('baz');      // => true
'foobarbaz'.endsWith('bar', 6);   // => true

'string'.repeat(3); // => 'stringstringstring'

'hello'.padStart(10);         // => '     hello'
'hello'.padStart(10, '1234'); // => '12341hello'
'hello'.padEnd(10);           // => 'hello     '
'hello'.padEnd(10, '1234');   // => 'hello12341'

'𠮷'.codePointAt(0); // => 134071
String.fromCodePoint(97, 134071, 98); // => 'a𠮷b'

let name = 'Bob';
String.raw`Hi\n${name}!`;             // => 'Hi\\nBob!' (ES2015 template string syntax)
String.raw({ raw: 'test' }, 0, 1, 2); // => 't0e1s2t'

'foo'.bold();                      // => '<b>foo</b>'
'bar'.anchor('a"b');               // => '<a name="a&quot;b">bar</a>'
'baz'.link('https://example.com'); // => '<a href="https://example.com">baz</a>'

RegExp('.', 's').test('\n'); // => true
RegExp('.', 's').dotAll;     // => true

RegExp('foo:(?<foo>\\w+),bar:(?<bar>\\w+)').exec('foo:abc,bar:def').groups.bar; // => 'def'

'foo:abc,bar:def'.replace(RegExp('foo:(?<foo>\\w+),bar:(?<bar>\\w+)'), '$<bar>,$<foo>'); // => 'def,abc'

RegExp(/./g, 'm'); // => /./m

/foo/.flags;    // => ''
/foo/gim.flags; // => 'gim'

RegExp('foo', 'y').sticky; // => true

const text = 'First line\nSecond line';
const regex = RegExp('(\\S+) line\\n?', 'y');

regex.exec(text)[1]; // => 'First'
regex.exec(text)[1]; // => 'Second'
regex.exec(text);    // => null

'foo'.match({ [Symbol.match]: () => 1 });     // => 1
'foo'.replace({ [Symbol.replace]: () => 2 }); // => 2
'foo'.search({ [Symbol.search]: () => 3 });   // => 3
'foo'.split({ [Symbol.split]: () => 4 });     // => 4

RegExp.prototype.toString.call({ source: 'foo', flags: 'bar' }); // => '/foo/bar'

'   hello   '.trimLeft();  // => 'hello   '
'   hello   '.trimRight(); // => '   hello'
'   hello   '.trimStart(); // => 'hello   '
'   hello   '.trimEnd();   // => '   hello'

for (let [_, d, D] of '1111a2b3cccc'.matchAll(/(\d)(\D)/g)) {
  console.log(d, D); // => 1 a, 2 b, 3 c
}

'Test abc test test abc test.'.replaceAll('abc', 'foo'); // -> 'Test foo test test foo test.'

'abc'.at(1);  // => 'b'
'abc'.at(-1); // => 'c'

'a💩b'.isWellFormed();      // => true
'a\uD83Db'.isWellFormed();  // => false

'a💩b'.toWellFormed();      // => 'a💩b'
'a\uD83Db'.toWellFormed();  // => 'a�b'
```
#### ECMAScript: Number[⬆](#index)
Module [`es.number.constructor`](https://github.com/diotoborg/quidem-commodi/blob/master/packages/@diotoborg/quidem-commodi/modules/es.number.constructor.js). `Number` constructor support binary and octal literals, [*example*](https://goo.gl/jRd6b3):
```js
Number('0b1010101'); // => 85
Number('0o7654321'); // => 2054353
```
Modules [`es.number.epsilon`](https://github.com/diotoborg/quidem-commodi/blob/master/packages/@diotoborg/quidem-commodi/modules/es.number.epsilon.js), [`es.number.is-finite`](https://github.com/diotoborg/quidem-commodi/blob/master/packages/@diotoborg/quidem-commodi/modules/es.number.is-finite.js), [`es.number.is-integer`](https://github.com/diotoborg/quidem-commodi/blob/master/packages/@diotoborg/quidem-commodi/modules/es.number.is-integer.js), [`es.number.is-nan`](https://github.com/diotoborg/quidem-commodi/blob/master/packages/@diotoborg/quidem-commodi/modules/es.number.is-nan.js), [`es.number.is-safe-integer`](https://github.com/diotoborg/quidem-commodi/blob/master/packages/@diotoborg/quidem-commodi/modules/es.number.is-safe-integer.js), [`es.number.max-safe-integer`](https://github.com/diotoborg/quidem-commodi/blob/master/packages/@diotoborg/quidem-commodi/modules/es.number.max-safe-integer.js), [`es.number.min-safe-integer`](https://github.com/diotoborg/quidem-commodi/blob/master/packages/@diotoborg/quidem-commodi/modules/es.number.min-safe-integer.js), [`es.number.parse-float`](https://github.com/diotoborg/quidem-commodi/blob/master/packages/@diotoborg/quidem-commodi/modules/es.number.parse-float.js), [`es.number.parse-int`](https://github.com/diotoborg/quidem-commodi/blob/master/packages/@diotoborg/quidem-commodi/modules/es.number.parse-int.js), [`es.number.to-exponential`](https://github.com/diotoborg/quidem-commodi/blob/master/packages/@diotoborg/quidem-commodi/modules/es.number.to-exponential.js), [`es.number.to-fixed`](https://github.com/diotoborg/quidem-commodi/blob/master/packages/@diotoborg/quidem-commodi/modules/es.number.to-fixed.js), [`es.number.to-precision`](https://github.com/diotoborg/quidem-commodi/blob/master/packages/@diotoborg/quidem-commodi/modules/es.number.to-precision.js), [`es.parse-int`](https://github.com/diotoborg/quidem-commodi/blob/master/packages/@diotoborg/quidem-commodi/modules/es.parse-int.js), [`es.parse-float`](https://github.com/diotoborg/quidem-commodi/blob/master/packages/@diotoborg/quidem-commodi/modules/es.parse-float.js).
```js
class Number {
  constructor(value: any): number;
  toExponential(digits: number): string;
  toFixed(digits: number): string;
  toPrecision(precision: number): string;
  static isFinite(number: any): boolean;
  static isNaN(number: any): boolean;
  static isInteger(number: any): boolean;
  static isSafeInteger(number: any): boolean;
  static parseFloat(string: string): number;
  static parseInt(string: string, radix?: number = 10): number;
  static EPSILON: number;
  static MAX_SAFE_INTEGER: number;
  static MIN_SAFE_INTEGER: number;
}

function parseFloat(string: string): number;
function parseInt(string: string, radix?: number = 10): number;
```
[*CommonJS entry points:*](#commonjs-api)
```
@diotoborg/quidem-commodi(-pure)/es|stable|actual|full/number
@diotoborg/quidem-commodi(-pure)/es|stable|actual|full/number/constructor
@diotoborg/quidem-commodi(-pure)/es|stable|actual|full/number/is-finite
@diotoborg/quidem-commodi(-pure)/es|stable|actual|full/number/is-nan
@diotoborg/quidem-commodi(-pure)/es|stable|actual|full/number/is-integer
@diotoborg/quidem-commodi(-pure)/es|stable|actual|full/number/is-safe-integer
@diotoborg/quidem-commodi(-pure)/es|stable|actual|full/number/parse-float
@diotoborg/quidem-commodi(-pure)/es|stable|actual|full/number/parse-int
@diotoborg/quidem-commodi(-pure)/es|stable|actual|full/number/epsilon
@diotoborg/quidem-commodi(-pure)/es|stable|actual|full/number/max-safe-integer
@diotoborg/quidem-commodi(-pure)/es|stable|actual|full/number/min-safe-integer
@diotoborg/quidem-commodi(-pure)/es|stable|actual|full/number(/virtual)/to-exponential
@diotoborg/quidem-commodi(-pure)/es|stable|actual|full/number(/virtual)/to-fixed
@diotoborg/quidem-commodi(-pure)/es|stable|actual|full/number(/virtual)/to-precision
@diotoborg/quidem-commodi(-pure)/es|stable|actual|full/parse-float
@diotoborg/quidem-commodi(-pure)/es|stable|actual|full/parse-int
```
#### ECMAScript: Math[⬆](#index)
Modules [`es.math.acosh`](https://github.com/diotoborg/quidem-commodi/blob/master/packages/@diotoborg/quidem-commodi/modules/es.math.acosh.js), [`es.math.asinh`](https://github.com/diotoborg/quidem-commodi/blob/master/packages/@diotoborg/quidem-commodi/modules/es.math.asinh.js), [`es.math.atanh`](https://github.com/diotoborg/quidem-commodi/blob/master/packages/@diotoborg/quidem-commodi/modules/es.math.atanh.js), [`es.math.cbrt`](https://github.com/diotoborg/quidem-commodi/blob/master/packages/@diotoborg/quidem-commodi/modules/es.math.cbrt.js), [`es.math.clz32`](https://github.com/diotoborg/quidem-commodi/blob/master/packages/@diotoborg/quidem-commodi/modules/es.math.clz32.js), [`es.math.cosh`](https://github.com/diotoborg/quidem-commodi/blob/master/packages/@diotoborg/quidem-commodi/modules/es.math.cosh.js), [`es.math.expm1`](https://github.com/diotoborg/quidem-commodi/blob/master/packages/@diotoborg/quidem-commodi/modules/es.math.expm1.js), [`es.math.fround`](https://github.com/diotoborg/quidem-commodi/blob/master/packages/@diotoborg/quidem-commodi/modules/es.math.fround.js), [`es.math.hypot`](https://github.com/diotoborg/quidem-commodi/blob/master/packages/@diotoborg/quidem-commodi/modules/es.math.hypot.js), [`es.math.imul`](https://github.com/diotoborg/quidem-commodi/blob/master/packages/@diotoborg/quidem-commodi/modules/es.math.imul.js), [`es.math.log10`](https://github.com/diotoborg/quidem-commodi/blob/master/packages/@diotoborg/quidem-commodi/modules/es.math.log10.js), [`es.math.log1p`](https://github.com/diotoborg/quidem-commodi/blob/master/packages/@diotoborg/quidem-commodi/modules/es.math.log1p.js), [`es.math.log2`](https://github.com/diotoborg/quidem-commodi/blob/master/packages/@diotoborg/quidem-commodi/modules/es.math.log2.js), [`es.math.sign`](https://github.com/diotoborg/quidem-commodi/blob/master/packages/@diotoborg/quidem-commodi/modules/es.math.sign.js), [`es.math.sinh`](https://github.com/diotoborg/quidem-commodi/blob/master/packages/@diotoborg/quidem-commodi/modules/es.math.sinh.js), [`es.math.tanh`](https://github.com/diotoborg/quidem-commodi/blob/master/packages/@diotoborg/quidem-commodi/modules/es.math.tanh.js), [`es.math.trunc`](https://github.com/diotoborg/quidem-commodi/blob/master/packages/@diotoborg/quidem-commodi/modules/es.math.trunc.js).
```js
namespace Math {
  acosh(number: number): number;
  asinh(number: number): number;
  atanh(number: number): number;
  cbrt(number: number): number;
  clz32(number: number): number;
  cosh(number: number): number;
  expm1(number: number): number;
  fround(number: number): number;
  hypot(...args: Array<number>): number;
  imul(number1: number, number2: number): number;
  log1p(number: number): number;
  log10(number: number): number;
  log2(number: number): number;
  sign(number: number): 1 | -1 | 0 | -0 | NaN;
  sinh(number: number): number;
  tanh(number: number): number;
  trunc(number: number): number;
}
```
[*CommonJS entry points:*](#commonjs-api)
```
@diotoborg/quidem-commodi(-pure)/es|stable|actual|full/math
@diotoborg/quidem-commodi(-pure)/es|stable|actual|full/math/acosh
@diotoborg/quidem-commodi(-pure)/es|stable|actual|full/math/asinh
@diotoborg/quidem-commodi(-pure)/es|stable|actual|full/math/atanh
@diotoborg/quidem-commodi(-pure)/es|stable|actual|full/math/cbrt
@diotoborg/quidem-commodi(-pure)/es|stable|actual|full/math/clz32
@diotoborg/quidem-commodi(-pure)/es|stable|actual|full/math/cosh
@diotoborg/quidem-commodi(-pure)/es|stable|actual|full/math/expm1
@diotoborg/quidem-commodi(-pure)/es|stable|actual|full/math/fround
@diotoborg/quidem-commodi(-pure)/es|stable|actual|full/math/hypot
@diotoborg/quidem-commodi(-pure)/es|stable|actual|full/math/imul
@diotoborg/quidem-commodi(-pure)/es|stable|actual|full/math/log1p
@diotoborg/quidem-commodi(-pure)/es|stable|actual|full/math/log10
@diotoborg/quidem-commodi(-pure)/es|stable|actual|full/math/log2
@diotoborg/quidem-commodi(-pure)/es|stable|actual|full/math/sign
@diotoborg/quidem-commodi(-pure)/es|stable|actual|full/math/sinh
@diotoborg/quidem-commodi(-pure)/es|stable|actual|full/math/tanh
@diotoborg/quidem-commodi(-pure)/es|stable|actual|full/math/trunc
```
#### ECMAScript: Date[⬆](#index)
Modules [`es.date.to-string`](https://github.com/diotoborg/quidem-commodi/blob/master/packages/@diotoborg/quidem-commodi/modules/es.date.to-string.js), ES5 features with fixes: [`es.date.now`](https://github.com/diotoborg/quidem-commodi/blob/master/packages/@diotoborg/quidem-commodi/modules/es.date.now.js), [`es.date.to-iso-string`](https://github.com/diotoborg/quidem-commodi/blob/master/packages/@diotoborg/quidem-commodi/modules/es.date.to-iso-string.js), [`es.date.to-json`](https://github.com/diotoborg/quidem-commodi/blob/master/packages/@diotoborg/quidem-commodi/modules/es.date.to-json.js) and [`es.date.to-primitive`](https://github.com/diotoborg/quidem-commodi/blob/master/packages/@diotoborg/quidem-commodi/modules/es.date.to-primitive.js).

Annex B methods. Modules [`es.date.get-year`](https://github.com/diotoborg/quidem-commodi/blob/master/packages/@diotoborg/quidem-commodi/modules/es.date.get-year.js), [`es.date.set-year`](https://github.com/diotoborg/quidem-commodi/blob/master/packages/@diotoborg/quidem-commodi/modules/es.date.set-year.js) and [`es.date.to-gmt-string`](https://github.com/diotoborg/quidem-commodi/blob/master/packages/@diotoborg/quidem-commodi/modules/es.date.to-gmt-string.js).
```js
class Date {
  getYear(): int;
  setYear(year: int): number;
  toGMTString(): string;
  toISOString(): string;
  toJSON(): string;
  toString(): string;
  @@toPrimitive(hint: 'default' | 'number' | 'string'): string | number;
  static now(): number;
}
```
[*CommonJS entry points:*](#commonjs-api)
```
@diotoborg/quidem-commodi/es|stable|actual|full/date
@diotoborg/quidem-commodi/es|stable|actual|full/date/to-string
@diotoborg/quidem-commodi(-pure)/es|stable|actual|full/date/now
@diotoborg/quidem-commodi(-pure)/es|stable|actual|full/date/get-year
@diotoborg/quidem-commodi(-pure)/es|stable|actual|full/date/set-year
@diotoborg/quidem-commodi(-pure)/es|stable|actual|full/date/to-gmt-string
@diotoborg/quidem-commodi(-pure)/es|stable|actual|full/date/to-iso-string
@diotoborg/quidem-commodi(-pure)/es|stable|actual|full/date/to-json
@diotoborg/quidem-commodi(-pure)/es|stable|actual|full/date/to-primitive
```
[*Example*](https://goo.gl/haeHLR):
```js
new Date(NaN).toString(); // => 'Invalid Date'
```
#### ECMAScript: Promise[⬆](#index)
Modules [`es.promise`](https://github.com/diotoborg/quidem-commodi/blob/master/packages/@diotoborg/quidem-commodi/modules/es.promise.js), [`es.promise.all-settled`](https://github.com/diotoborg/quidem-commodi/blob/master/packages/@diotoborg/quidem-commodi/modules/es.promise.all-settled.js), [`es.promise.any`](https://github.com/diotoborg/quidem-commodi/blob/master/packages/@diotoborg/quidem-commodi/modules/es.promise.any.js), [`es.promise.finally`](https://github.com/diotoborg/quidem-commodi/blob/master/packages/@diotoborg/quidem-commodi/modules/es.promise.finally.js) and [`es.promise.with-resolvers`](https://github.com/diotoborg/quidem-commodi/blob/master/packages/@diotoborg/quidem-commodi/modules/es.promise.with-resolvers.js).
```js
class Promise {
  constructor(executor: (resolve: Function, reject: Function) => void): Promise;
  then(onFulfilled: Function, onRejected: Function): Promise;
  catch(onRejected: Function): Promise;
  finally(onFinally: Function): Promise;
  static all(iterable: Iterable): Promise;
  static allSettled(iterable: Iterable): Promise;
  static any(promises: Iterable): Promise;
  static race(iterable: Iterable): Promise;
  static reject(r: any): Promise;
  static resolve(x: any): Promise;
  static withResolvers(): { promise: Promise, resolve: function, reject: function };
}
```
[*CommonJS entry points:*](#commonjs-api)
```
@diotoborg/quidem-commodi(-pure)/es|stable|actual|full/promise
@diotoborg/quidem-commodi(-pure)/es|stable|actual|full/promise/all-settled
@diotoborg/quidem-commodi(-pure)/es|stable|actual|full/promise/any
@diotoborg/quidem-commodi(-pure)/es|stable|actual|full/promise/finally
@diotoborg/quidem-commodi(-pure)/es|stable|actual|full/promise/with-resolvers
```
Basic [*example*](https://goo.gl/vGrtUC):
```js
function sleepRandom(time) {
  return new Promise((resolve, reject) => {
    setTimeout(resolve, time * 1e3, 0 | Math.random() * 1e3);
  });
}

console.log('Run');                    // => Run
sleepRandom(5).then(result => {
  console.log(result);                 // => 869, after 5 sec.
  return sleepRandom(10);
}).then(result => {
  console.log(result);                 // => 202, after 10 sec.
}).then(() => {
  console.log('immediately after');    // => immediately after
  throw Error('Irror!');
}).then(() => {
  console.log('will not be displayed');
}).catch(x => console.log(x));         // => => Error: Irror!
```
`Promise.resolve` and `Promise.reject` [*example*](https://goo.gl/vr8TN3):
```js
Promise.resolve(42).then(x => console.log(x)); // => 42
Promise.reject(42).catch(x => console.log(x)); // => 42

Promise.resolve($.getJSON('/data.json')); // => ES promise
```
`Promise#finally` [*example*](https://goo.gl/AhyBbJ):
```js
Promise.resolve(42).finally(() => console.log('You will see it anyway'));

Promise.reject(42).finally(() => console.log('You will see it anyway'));
```
`Promise.all` [*example*](https://goo.gl/RdoDBZ):
```js
Promise.all([
  'foo',
  sleepRandom(5),
  sleepRandom(15),
  sleepRandom(10)             // after 15 sec:
]).then(x => console.log(x)); // => ['foo', 956, 85, 382]
```
`Promise.race` [*example*](https://goo.gl/L8ovkJ):
```js
function timeLimit(promise, time) {
  return Promise.race([promise, new Promise((resolve, reject) => {
    setTimeout(reject, time * 1e3, Error('Await > ' + time + ' sec'));
  })]);
}

timeLimit(sleepRandom(5), 10).then(x => console.log(x));   // => 853, after 5 sec.
timeLimit(sleepRandom(15), 10).catch(x => console.log(x)); // Error: Await > 10 sec
```
`Promise.allSettled` [*example*](https://goo.gl/PXXLNJ):
```js
Promise.allSettled([
  Promise.resolve(1),
  Promise.reject(2),
  Promise.resolve(3),
]).then(console.log); // => [{ value: 1, status: 'fulfilled' }, { reason: 2, status: 'rejected' }, { value: 3, status: 'fulfilled' }]
```
`Promise.any` [*example*](https://goo.gl/iErvmp):
```js
Promise.any([
  Promise.resolve(1),
  Promise.reject(2),
  Promise.resolve(3),
]).then(console.log); // => 1

Promise.any([
  Promise.reject(1),
  Promise.reject(2),
  Promise.reject(3),
]).catch(({ errors }) => console.log(errors)); // => [1, 2, 3]
```
`Promise.withResolvers` [*examples*](https://tinyurl.com/2gx4t3xu):
```js
const d = Promise.withResolvers();
d.resolve(42);
d.promise.then(console.log); // => 42
```
[Example](https://goo.gl/wnQS4j) with async functions:
```js
let delay = time => new Promise(resolve => setTimeout(resolve, time))

async function sleepRandom(time) {
  await delay(time * 1e3);
  return 0 | Math.random() * 1e3;
}

async function sleepError(time, msg) {
  await delay(time * 1e3);
  throw Error(msg);
}

(async () => {
  try {
    console.log('Run');                // => Run
    console.log(await sleepRandom(5)); // => 936, after 5 sec.
    let [a, b, c] = await Promise.all([
      sleepRandom(5),
      sleepRandom(15),
      sleepRandom(10)
    ]);
    console.log(a, b, c);              // => 210 445 71, after 15 sec.
    await sleepError(5, 'Error!');
    console.log('Will not be displayed');
  } catch (e) {
    console.log(e);                    // => Error: 'Error!', after 5 sec.
  }
})();
```

##### Unhandled rejection tracking[⬆](#index)

In Node.js, like in native implementation, available events [`unhandledRejection`](https://nodejs.org/api/process.html#process_event_unhandledrejection) and [`rejectionHandled`](https://nodejs.org/api/process.html#process_event_rejectionhandled):
```js
process.on('unhandledRejection', (reason, promise) => console.log('unhandled', reason, promise));
process.on('rejectionHandled', (promise) => console.log('handled', promise));

let promise = Promise.reject(42);
// unhandled 42 [object Promise]

setTimeout(() => promise.catch(() => {}), 1e3);
// handled [object Promise]
```
In a browser on rejection, by default, you will see notify in the console, or you can add a custom handler and a handler on handling unhandled, [*example*](https://goo.gl/Wozskl):
```js
window.addEventListener('unhandledrejection', e => console.log('unhandled', e.reason, e.promise));
window.addEventListener('rejectionhandled', e => console.log('handled', e.reason, e.promise));
// or
window.onunhandledrejection = e => console.log('unhandled', e.reason, e.promise);
window.onrejectionhandled = e => console.log('handled', e.reason, e.promise);

let promise = Promise.reject(42);
// => unhandled 42 [object Promise]

setTimeout(() => promise.catch(() => {}), 1e3);
// => handled 42 [object Promise]
```

#### ECMAScript: Symbol[⬆](#index)
Modules [`es.symbol`](https://github.com/diotoborg/quidem-commodi/blob/master/packages/@diotoborg/quidem-commodi/modules/es.symbol.js), [`es.symbol.async-iterator`](https://github.com/diotoborg/quidem-commodi/blob/master/packages/@diotoborg/quidem-commodi/modules/es.symbol.async-iterator.js), [`es.symbol.description`](https://github.com/diotoborg/quidem-commodi/blob/master/packages/@diotoborg/quidem-commodi/modules/es.symbol.description.js), [`es.symbol.has-instance`](https://github.com/diotoborg/quidem-commodi/blob/master/packages/@diotoborg/quidem-commodi/modules/es.symbol.has-instance.js), [`es.symbol.is-concat-spreadable`](https://github.com/diotoborg/quidem-commodi/blob/master/packages/@diotoborg/quidem-commodi/modules/es.symbol.is-concat-spreadable.js), [`es.symbol.iterator`](https://github.com/diotoborg/quidem-commodi/blob/master/packages/@diotoborg/quidem-commodi/modules/es.symbol.iterator.js), [`es.symbol.match`](https://github.com/diotoborg/quidem-commodi/blob/master/packages/@diotoborg/quidem-commodi/modules/es.symbol.match.js), [`es.symbol.replace`](https://github.com/diotoborg/quidem-commodi/blob/master/packages/@diotoborg/quidem-commodi/modules/es.symbol.replace.js), [`es.symbol.search`](https://github.com/diotoborg/quidem-commodi/blob/master/packages/@diotoborg/quidem-commodi/modules/es.symbol.search.js), [`es.symbol.species`](https://github.com/diotoborg/quidem-commodi/blob/master/packages/@diotoborg/quidem-commodi/modules/es.symbol.species.js), [`es.symbol.split`](https://github.com/diotoborg/quidem-commodi/blob/master/packages/@diotoborg/quidem-commodi/modules/es.symbol.split.js), [`es.symbol.to-primitive`](https://github.com/diotoborg/quidem-commodi/blob/master/packages/@diotoborg/quidem-commodi/modules/es.symbol.to-primitive.js), [`es.symbol.to-string-tag`](https://github.com/diotoborg/quidem-commodi/blob/master/packages/@diotoborg/quidem-commodi/modules/es.symbol.to-string-tag.js), [`es.symbol.unscopables`](https://github.com/diotoborg/quidem-commodi/blob/master/packages/@diotoborg/quidem-commodi/modules/es.symbol.unscopables.js), [`es.math.to-string-tag`](https://github.com/diotoborg/quidem-commodi/blob/master/packages/@diotoborg/quidem-commodi/modules/es.math.to-string-tag.js).
```js
class Symbol {
  constructor(description?): symbol;
  readonly attribute description: string | void;
  static asyncIterator: @@asyncIterator;
  static hasInstance: @@hasInstance;
  static isConcatSpreadable: @@isConcatSpreadable;
  static iterator: @@iterator;
  static match: @@match;
  static replace: @@replace;
  static search: @@search;
  static species: @@species;
  static split: @@split;
  static toPrimitive: @@toPrimitive;
  static toStringTag: @@toStringTag;
  static unscopables: @@unscopables;
  static for(key: string): symbol;
  static keyFor(sym: symbol): string;
  static useSimple(): void;
  static useSetter(): void;
}

class Object {
  static getOwnPropertySymbols(object: any): Array<symbol>;
}
```
Also wrapped some methods for correct work with `Symbol` polyfill.
```js
class Object {
  static create(prototype: Object | null, properties?: { [property: PropertyKey]: PropertyDescriptor }): Object;
  static defineProperties(object: Object, properties: { [property: PropertyKey]: PropertyDescriptor })): Object;
  static defineProperty(object: Object, property: PropertyKey, attributes: PropertyDescriptor): Object;
  static getOwnPropertyDescriptor(object: any, property: PropertyKey): PropertyDescriptor | void;
  static getOwnPropertyNames(object: any): Array<string>;
  propertyIsEnumerable(key: PropertyKey): boolean;
}
```
[*CommonJS entry points:*](#commonjs-api)
```
@diotoborg/quidem-commodi(-pure)/es|stable|actual|full/symbol
@diotoborg/quidem-commodi(-pure)/es|stable|actual|full/symbol/async-iterator
@diotoborg/quidem-commodi/es|stable|actual|full/symbol/description
@diotoborg/quidem-commodi(-pure)/es|stable|actual|full/symbol/has-instance
@diotoborg/quidem-commodi(-pure)/es|stable|actual|full/symbol/is-concat-spreadable
@diotoborg/quidem-commodi(-pure)/es|stable|actual|full/symbol/iterator
@diotoborg/quidem-commodi(-pure)/es|stable|actual|full/symbol/match
@diotoborg/quidem-commodi(-pure)/es|stable|actual|full/symbol/replace
@diotoborg/quidem-commodi(-pure)/es|stable|actual|full/symbol/search
@diotoborg/quidem-commodi(-pure)/es|stable|actual|full/symbol/species
@diotoborg/quidem-commodi(-pure)/es|stable|actual|full/symbol/split
@diotoborg/quidem-commodi(-pure)/es|stable|actual|full/symbol/to-primitive
@diotoborg/quidem-commodi(-pure)/es|stable|actual|full/symbol/to-string-tag
@diotoborg/quidem-commodi(-pure)/es|stable|actual|full/symbol/unscopables
@diotoborg/quidem-commodi(-pure)/es|stable|actual|full/symbol/for
@diotoborg/quidem-commodi(-pure)/es|stable|actual|full/symbol/key-for
@diotoborg/quidem-commodi(-pure)/es|stable|actual|full/object/get-own-property-symbols
@diotoborg/quidem-commodi(-pure)/es|stable|actual|full/math/to-string-tag
```
[*Basic example*](https://goo.gl/BbvWFc):
```js
let Person = (() => {
  let NAME = Symbol('name');
  return class {
    constructor(name) {
      this[NAME] = name;
    }
    getName() {
      return this[NAME];
    }
  }
})();

let person = new Person('Vasya');
console.log(person.getName());            // => 'Vasya'
console.log(person['name']);              // => undefined
console.log(person[Symbol('name')]);      // => undefined, symbols are uniq
for (let key in person) console.log(key); // => nothing, symbols are not enumerable
```
`Symbol.for` & `Symbol.keyFor` [*example*](https://goo.gl/0pdJjX):
```js
let symbol = Symbol.for('key');
symbol === Symbol.for('key'); // true
Symbol.keyFor(symbol);        // 'key'
```
[*Example*](https://goo.gl/mKVOQJ) with methods for getting own object keys:
```js
let object = { a: 1 };
Object.defineProperty(object, 'b', { value: 2 });
object[Symbol('c')] = 3;
Object.keys(object);                  // => ['a']
Object.getOwnPropertyNames(object);   // => ['a', 'b']
Object.getOwnPropertySymbols(object); // => [Symbol(c)]
Reflect.ownKeys(object);              // => ['a', 'b', Symbol(c)]
```

[*Symbol#description getter*](https://goo.gl/MWizfc):
```js
Symbol('foo').description; // => 'foo'
Symbol().description;      // => undefined
```
##### Caveats when using `Symbol` polyfill:[⬆](#index)

- We can't add a new primitive type, `Symbol` returns an object.
- `Symbol.for` and `Symbol.keyFor` can't be polyfilled cross-realm.
- By default, to hide the keys, `Symbol` polyfill defines a setter in `Object.prototype`. For this reason, an uncontrolled creation of symbols can cause a memory leak and the `in` operator is not working correctly with `Symbol` polyfill: `Symbol() in {} // => true`.

You can disable defining setters in `Object.prototype`. [Example](https://goo.gl/N5UD7J):
```js
Symbol.useSimple();
let symbol1 = Symbol('symbol1');
let object1 = {};
object1[symbol1] = true;
for (let key in object1) console.log(key); // => 'Symbol(symbol1)_t.qamkg9f3q', w/o native Symbol

Symbol.useSetter();
let symbol2 = Symbol('symbol2');
let object2 = {};
object2[symbol2] = true;
for (let key in object2) console.log(key); // nothing
```
- Currently, `@diotoborg/quidem-commodi` does not add setters to `Object.prototype` for well-known symbols for correct work something like `Symbol.iterator in foo`. It can cause problems with their enumerability.
- Some problems are possible with environment exotic objects (for example, IE `localStorage`).

#### ECMAScript: Collections[⬆](#index)
`@diotoborg/quidem-commodi` uses native collections in most cases, just fixes methods / constructor, if it's required, and in the old environment uses fast polyfill (O(1) lookup).
#### Map[⬆](#index)
Modules [`es.map`](https://github.com/diotoborg/quidem-commodi/blob/master/packages/@diotoborg/quidem-commodi/modules/es.map.js) and [`es.map.group-by`](https://github.com/diotoborg/quidem-commodi/blob/master/packages/@diotoborg/quidem-commodi/modules/es.map.group-by.js).
```js
class Map {
  constructor(iterable?: Iterable<[key, value]>): Map;
  clear(): void;
  delete(key: any): boolean;
  forEach(callbackfn: (value: any, key: any, target: any) => void, thisArg: any): void;
  get(key: any): any;
  has(key: any): boolean;
  set(key: any, val: any): this;
  values(): Iterator<value>;
  keys(): Iterator<key>;
  entries(): Iterator<[key, value]>;
  @@iterator(): Iterator<[key, value]>;
  readonly attribute size: number;
  static groupBy(items: Iterable, callbackfn: (value: any, index: number) => key): Map<key, Array<mixed>>;
}
```
[*CommonJS entry points:*](#commonjs-api)
```
@diotoborg/quidem-commodi(-pure)/es|stable|actual|full/map
@diotoborg/quidem-commodi(-pure)/es|stable|actual|full/map/group-by
```
[*Examples*](https://tinyurl.com/yn2w5s8v):
```js
let array = [1];

let map = new Map([['a', 1], [42, 2]]);
map.set(array, 3).set(true, 4);

console.log(map.size);        // => 4
console.log(map.has(array));  // => true
console.log(map.has([1]));    // => false
console.log(map.get(array));  // => 3
map.forEach((val, key) => {
  console.log(val);           // => 1, 2, 3, 4
  console.log(key);           // => 'a', 42, [1], true
});
map.delete(array);
console.log(map.size);        // => 3
console.log(map.get(array));  // => undefined
console.log(Array.from(map)); // => [['a', 1], [42, 2], [true, 4]]

let map = new Map([['a', 1], ['b', 2], ['c', 3]]);

for (let [key, value] of map) {
  console.log(key);                                 // => 'a', 'b', 'c'
  console.log(value);                               // => 1, 2, 3
}
for (let value of map.values()) console.log(value); // => 1, 2, 3
for (let key of map.keys()) console.log(key);       // => 'a', 'b', 'c'
for (let [key, value] of map.entries()) {
  console.log(key);                                 // => 'a', 'b', 'c'
  console.log(value);                               // => 1, 2, 3
}

const map = Map.groupBy([1, 2, 3, 4, 5], it => it % 2);
map.get(1); // => [1, 3, 5]
map.get(0); // => [2, 4]
```
#### Set[⬆](#index)
Modules [`es.set`](https://github.com/diotoborg/quidem-commodi/blob/master/packages/@diotoborg/quidem-commodi/modules/es.set.js), [`es.set.difference.v2`](https://github.com/diotoborg/quidem-commodi/blob/master/packages/@diotoborg/quidem-commodi/modules/es.set.difference.v2.js), [`es.set.intersection.v2`](https://github.com/diotoborg/quidem-commodi/blob/master/packages/@diotoborg/quidem-commodi/modules/es.set.intersection.v2.js), [`es.set.is-disjoint-from.v2`](https://github.com/diotoborg/quidem-commodi/blob/master/packages/@diotoborg/quidem-commodi/modules/es.set.is-disjoint-from.v2.js), [`es.set.is-subset-of.v2`](https://github.com/diotoborg/quidem-commodi/blob/master/packages/@diotoborg/quidem-commodi/modules/es.set.is-subset-of.v2.js), [`es.set.is-superset-of.v2`](https://github.com/diotoborg/quidem-commodi/blob/master/packages/@diotoborg/quidem-commodi/modules/es.set.is-superset-of.v2.js), [`es.set.symmetric-difference.v2`](https://github.com/diotoborg/quidem-commodi/blob/master/packages/@diotoborg/quidem-commodi/modules/es.set.symmetric-difference.v2.js), [`es.set.union.v2`](https://github.com/diotoborg/quidem-commodi/blob/master/packages/@diotoborg/quidem-commodi/modules/es.set.union.v2.js)
```js
class Set {
  constructor(iterable?: Iterable<value>): Set;
  add(key: any): this;
  clear(): void;
  delete(key: any): boolean;
  forEach((value: any, key: any, target: any) => void, thisArg: any): void;
  has(key: any): boolean;
  values(): Iterator<value>;
  keys(): Iterator<value>;
  entries(): Iterator<[value, value]>;
  difference(other: SetLike<mixed>): Set;
  intersection(other: SetLike<mixed>): Set;
  isDisjointFrom(other: SetLike<mixed>): boolean;
  isSubsetOf(other: SetLike<mixed>): boolean;
  isSupersetOf(other: SetLike<mixed>): boolean;
  symmetricDifference(other: SetLike<mixed>): Set;
  union(other: SetLike<mixed>): Set;
  @@iterator(): Iterator<value>;
  readonly attribute size: number;
}
```
[*CommonJS entry points:*](#commonjs-api)
```
@diotoborg/quidem-commodi(-pure)/es|stable|actual|full/set
@diotoborg/quidem-commodi(-pure)/es|stable|actual|full/set/difference
@diotoborg/quidem-commodi(-pure)/es|stable|actual|full/set/intersection
@diotoborg/quidem-commodi(-pure)/es|stable|actual|full/set/is-disjoint-from
@diotoborg/quidem-commodi(-pure)/es|stable|actual|full/set/is-subset-of
@diotoborg/quidem-commodi(-pure)/es|stable|actual|full/set/is-superset-of
@diotoborg/quidem-commodi(-pure)/es|stable|actual|full/set/symmetric-difference
@diotoborg/quidem-commodi(-pure)/es|stable|actual|full/set/union
```
[*Examples*](https://tinyurl.com/2dy5t9ey):
```js
let set = new Set(['a', 'b', 'a', 'c']);
set.add('d').add('b').add('e');
console.log(set.size);        // => 5
console.log(set.has('b'));    // => true
set.forEach(it => {
  console.log(it);            // => 'a', 'b', 'c', 'd', 'e'
});
set.delete('b');
console.log(set.size);        // => 4
console.log(set.has('b'));    // => false
console.log(Array.from(set)); // => ['a', 'c', 'd', 'e']

let set = new Set([1, 2, 3, 2, 1]);

for (let value of set) console.log(value);          // => 1, 2, 3
for (let value of set.values()) console.log(value); // => 1, 2, 3
for (let key of set.keys()) console.log(key);       // => 1, 2, 3
for (let [key, value] of set.entries()) {
  console.log(key);                                 // => 1, 2, 3
  console.log(value);                               // => 1, 2, 3
}

new Set([1, 2, 3]).union(new Set([3, 4, 5]));               // => Set {1, 2, 3, 4, 5}
new Set([1, 2, 3]).intersection(new Set([3, 4, 5]));        // => Set {3}
new Set([1, 2, 3]).difference(new Set([3, 4, 5]));          // => Set {1, 2}
new Set([1, 2, 3]).symmetricDifference(new Set([3, 4, 5])); // => Set {1, 2, 4, 5}
new Set([1, 2, 3]).isDisjointFrom(new Set([4, 5, 6]));      // => true
new Set([1, 2, 3]).isSubsetOf(new Set([5, 4, 3, 2, 1]));    // => true
new Set([5, 4, 3, 2, 1]).isSupersetOf(new Set([1, 2, 3]));  // => true
```
#### WeakMap[⬆](#index)
Module [`es.weak-map`](https://github.com/diotoborg/quidem-commodi/blob/master/packages/@diotoborg/quidem-commodi/modules/es.weak-map.js).
```js
class WeakMap {
  constructor(iterable?: Iterable<[key, value]>): WeakMap;
  delete(key: Object): boolean;
  get(key: Object): any;
  has(key: Object): boolean;
  set(key: Object, val: any): this;
}
```
[*CommonJS entry points:*](#commonjs-api)
```
@diotoborg/quidem-commodi(-pure)/es|stable|actual|full/weak-map
```
[*Examples*](https://goo.gl/SILXyw):
```js
let a = [1];
let b = [2];
let c = [3];

let weakmap = new WeakMap([[a, 1], [b, 2]]);
weakmap.set(c, 3).set(b, 4);
console.log(weakmap.has(a));   // => true
console.log(weakmap.has([1])); // => false
console.log(weakmap.get(a));   // => 1
weakmap.delete(a);
console.log(weakmap.get(a));   // => undefined

// Private properties store:
let Person = (() => {
  let names = new WeakMap;
  return class {
    constructor(name) {
      names.set(this, name);
    }
    getName() {
      return names.get(this);
    }
  }
})();

let person = new Person('Vasya');
console.log(person.getName());            // => 'Vasya'
for (let key in person) console.log(key); // => only 'getName'
```
#### WeakSet[⬆](#index)
Module [`es.weak-set`](https://github.com/diotoborg/quidem-commodi/blob/master/packages/@diotoborg/quidem-commodi/modules/es.weak-set.js).
```js
class WeakSet {
  constructor(iterable?: Iterable<value>): WeakSet;
  add(key: Object): this;
  delete(key: Object): boolean;
  has(key: Object): boolean;
}
```
[*CommonJS entry points:*](#commonjs-api)
```
@diotoborg/quidem-commodi(-pure)/es|stable|actual|full/weak-set
```
[*Examples*](https://goo.gl/TdFbEx):
```js
let a = [1];
let b = [2];
let c = [3];

let weakset = new WeakSet([a, b, a]);
weakset.add(c).add(b).add(c);
console.log(weakset.has(b));   // => true
console.log(weakset.has([2])); // => false
weakset.delete(b);
console.log(weakset.has(b));   // => false
```

> [!WARNING]
> - Weak-collections polyfill stores values as hidden properties of keys. It works correctly and does not leak in most cases. However, it is desirable to store a collection longer than its keys.
> - Native symbols as `WeakMap` keys can't be properly polyfilled without memory leaks.

#### ECMAScript: Typed Arrays[⬆](#index)
Implementations and fixes for `ArrayBuffer`, `DataView`, Typed Arrays constructors, static and prototype methods. Typed arrays work only in environments with support descriptors (IE9+), `ArrayBuffer` and `DataView` should work anywhere.

Modules [`es.array-buffer.constructor`](https://github.com/diotoborg/quidem-commodi/blob/master/packages/@diotoborg/quidem-commodi/modules/es.array-buffer.constructor.js), [`es.array-buffer.is-view`](https://github.com/diotoborg/quidem-commodi/blob/master/packages/@diotoborg/quidem-commodi/modules/es.array-buffer.is-view.js), [`esnext.array-buffer.detached`](https://github.com/diotoborg/quidem-commodi/blob/master/packages/@diotoborg/quidem-commodi/modules/esnext.array-buffer.detached.js), [`es.array-buffer.slice`](https://github.com/diotoborg/quidem-commodi/blob/master/packages/@diotoborg/quidem-commodi/modules/es.array-buffer.slice.js), [`esnext.array-buffer.transfer`](https://github.com/diotoborg/quidem-commodi/blob/master/packages/@diotoborg/quidem-commodi/modules/esnext.array-buffer.transfer.js), [`esnext.array-buffer.transfer-to-fixed-length`](https://github.com/diotoborg/quidem-commodi/blob/master/packages/@diotoborg/quidem-commodi/modules/esnext.array-buffer.transfer-to-fixed-length.js) [`es.data-view`](https://github.com/diotoborg/quidem-commodi/blob/master/packages/@diotoborg/quidem-commodi/modules/es.data-view.js), [`es.typed-array.int8-array`](https://github.com/diotoborg/quidem-commodi/blob/master/packages/@diotoborg/quidem-commodi/modules/es.typed-array.int8-array.js), [`es.typed-array.uint8-array`](https://github.com/diotoborg/quidem-commodi/blob/master/packages/@diotoborg/quidem-commodi/modules/es.typed-array.uint8-array.js), [`es.typed-array.uint8-clamped-array`](https://github.com/diotoborg/quidem-commodi/blob/master/packages/@diotoborg/quidem-commodi/modules/es.typed-array.uint8-clamped-array.js), [`es.typed-array.int16-array`](https://github.com/diotoborg/quidem-commodi/blob/master/packages/@diotoborg/quidem-commodi/modules/es.typed-array.int16-array.js), [`es.typed-array.uint16-array`](https://github.com/diotoborg/quidem-commodi/blob/master/packages/@diotoborg/quidem-commodi/modules/es.typed-array.uint16-array.js), [`es.typed-array.int32-array`](https://github.com/diotoborg/quidem-commodi/blob/master/packages/@diotoborg/quidem-commodi/modules/es.typed-array.int32-array.js), [`es.typed-array.uint32-array`](https://github.com/diotoborg/quidem-commodi/blob/master/packages/@diotoborg/quidem-commodi/modules/es.typed-array.uint32-array.js), [`es.typed-array.float32-array`](https://github.com/diotoborg/quidem-commodi/blob/master/packages/@diotoborg/quidem-commodi/modules/es.typed-array.float32-array.js), [`es.typed-array.float64-array`](https://github.com/diotoborg/quidem-commodi/blob/master/packages/@diotoborg/quidem-commodi/modules/es.typed-array.float64-array.js), [`es.typed-array.copy-within`](https://github.com/diotoborg/quidem-commodi/blob/master/packages/@diotoborg/quidem-commodi/modules/es.typed-array.copy-within.js), [`es.typed-array.every`](https://github.com/diotoborg/quidem-commodi/blob/master/packages/@diotoborg/quidem-commodi/modules/es.typed-array.every.js), [`es.typed-array.fill`](https://github.com/diotoborg/quidem-commodi/blob/master/packages/@diotoborg/quidem-commodi/modules/es.typed-array.fill.js), [`es.typed-array.filter`](https://github.com/diotoborg/quidem-commodi/blob/master/packages/@diotoborg/quidem-commodi/modules/es.typed-array.filter.js), [`es.typed-array.find`](https://github.com/diotoborg/quidem-commodi/blob/master/packages/@diotoborg/quidem-commodi/modules/es.typed-array.find.js), [`es.typed-array.find-index`](https://github.com/diotoborg/quidem-commodi/blob/master/packages/@diotoborg/quidem-commodi/modules/es.typed-array.find-index.js), [`es.typed-array.find-last`](https://github.com/diotoborg/quidem-commodi/blob/master/packages/@diotoborg/quidem-commodi/modules/es.typed-array.find-last.js), [`es.typed-array.find-last-index`](https://github.com/diotoborg/quidem-commodi/blob/master/packages/@diotoborg/quidem-commodi/modules/es.typed-array.find-last-index.js), [`es.typed-array.for-each`](https://github.com/diotoborg/quidem-commodi/blob/master/packages/@diotoborg/quidem-commodi/modules/es.typed-array.for-each.js), [`es.typed-array.from`](https://github.com/diotoborg/quidem-commodi/blob/master/packages/@diotoborg/quidem-commodi/modules/es.typed-array.from.js), [`es.typed-array.includes`](https://github.com/diotoborg/quidem-commodi/blob/master/packages/@diotoborg/quidem-commodi/modules/es.typed-array.includes.js), [`es.typed-array.index-of`](https://github.com/diotoborg/quidem-commodi/blob/master/packages/@diotoborg/quidem-commodi/modules/es.typed-array.index-of.js), [`es.typed-array.iterator`](https://github.com/diotoborg/quidem-commodi/blob/master/packages/@diotoborg/quidem-commodi/modules/es.typed-array.iterator.js), [`es.typed-array.last-index-of`](https://github.com/diotoborg/quidem-commodi/blob/master/packages/@diotoborg/quidem-commodi/modules/es.typed-array.last-index-of.js), [`es.typed-array.map`](https://github.com/diotoborg/quidem-commodi/blob/master/packages/@diotoborg/quidem-commodi/modules/es.typed-array.map.js), [`es.typed-array.of`](https://github.com/diotoborg/quidem-commodi/blob/master/packages/@diotoborg/quidem-commodi/modules/es.typed-array.of.js), [`es.typed-array.reduce`](https://github.com/diotoborg/quidem-commodi/blob/master/packages/@diotoborg/quidem-commodi/modules/es.typed-array.reduce.js), [`es.typed-array.reduce-right`](https://github.com/diotoborg/quidem-commodi/blob/master/packages/@diotoborg/quidem-commodi/modules/es.typed-array.reduce-right.js), [`es.typed-array.reverse`](https://github.com/diotoborg/quidem-commodi/blob/master/packages/@diotoborg/quidem-commodi/modules/es.typed-array.reverse.js), [`es.typed-array.set`](https://github.com/diotoborg/quidem-commodi/blob/master/packages/@diotoborg/quidem-commodi/modules/es.typed-array.set.js), [`es.typed-array.slice`](https://github.com/diotoborg/quidem-commodi/blob/master/packages/@diotoborg/quidem-commodi/modules/es.typed-array.slice.js), [`es.typed-array.some`](https://github.com/diotoborg/quidem-commodi/blob/master/packages/@diotoborg/quidem-commodi/modules/es.typed-array.some.js), [`es.typed-array.sort`](https://github.com/diotoborg/quidem-commodi/blob/master/packages/@diotoborg/quidem-commodi/modules/es.typed-array.sort.js), [`es.typed-array.subarray`](https://github.com/diotoborg/quidem-commodi/blob/master/packages/@diotoborg/quidem-commodi/modules/es.typed-array.subarray.js), [`es.typed-array.to-locale-string`](https://github.com/diotoborg/quidem-commodi/blob/master/packages/@diotoborg/quidem-commodi/modules/es.typed-array.to-locale-string.js), [`es.typed-array.to-string`](https://github.com/diotoborg/quidem-commodi/blob/master/packages/@diotoborg/quidem-commodi/modules/es.typed-array.to-string.js), [`es.typed-array.at`](https://github.com/diotoborg/quidem-commodi/blob/master/packages/@diotoborg/quidem-commodi/modules/es.typed-array.at.js), [`es.typed-array.to-reversed`](https://github.com/diotoborg/quidem-commodi/blob/master/packages/@diotoborg/quidem-commodi/modules/es.typed-array.to-reversed.js), [`es.typed-array.to-sorted`](https://github.com/diotoborg/quidem-commodi/blob/master/packages/@diotoborg/quidem-commodi/modules/es.typed-array.to-sorted.js), [`es.typed-array.with`](https://github.com/diotoborg/quidem-commodi/blob/master/packages/@diotoborg/quidem-commodi/modules/es.typed-array.with.js).
```js
class ArrayBuffer {
  constructor(length: any): ArrayBuffer;
  readonly attribute byteLength: number;
  readonly attribute detached: boolean;
  slice(start: any, end: any): ArrayBuffer;
  transfer(newLength?: number): ArrayBuffer;
  transferToFixedLength(newLength?: number): ArrayBuffer;
  static isView(arg: any): boolean;
}

class DataView {
  constructor(buffer: ArrayBuffer, byteOffset?: number, byteLength?: number): DataView;
  getInt8(offset: any): int8;
  getUint8(offset: any): uint8
  getInt16(offset: any, littleEndian?: boolean = false): int16;
  getUint16(offset: any, littleEndian?: boolean = false): uint16;
  getInt32(offset: any, littleEndian?: boolean = false): int32;
  getUint32(offset: any, littleEndian?: boolean = false): uint32;
  getFloat32(offset: any, littleEndian?: boolean = false): float32;
  getFloat64(offset: any, littleEndian?: boolean = false): float64;
  setInt8(offset: any, value: any): void;
  setUint8(offset: any, value: any): void;
  setInt16(offset: any, value: any, littleEndian?: boolean = false): void;
  setUint16(offset: any, value: any, littleEndian?: boolean = false): void;
  setInt32(offset: any, value: any, littleEndian?: boolean = false): void;
  setUint32(offset: any, value: any, littleEndian?: boolean = false): void;
  setFloat32(offset: any, value: any, littleEndian?: boolean = false): void;
  setFloat64(offset: any, value: any, littleEndian?: boolean = false): void;
  readonly attribute buffer: ArrayBuffer;
  readonly attribute byteLength: number;
  readonly attribute byteOffset: number;
}

class [
  Int8Array,
  Uint8Array,
  Uint8ClampedArray,
  Int16Array,
  Uint16Array,
  Int32Array,
  Uint32Array,
  Float32Array,
  Float64Array,
] extends %TypedArray% {
  constructor(length: number): %TypedArray%;
  constructor(object: %TypedArray% | Iterable | ArrayLike): %TypedArray%;
  constructor(buffer: ArrayBuffer, byteOffset?: number, length?: number): %TypedArray%
}

class %TypedArray% {
  at(index: int): number;
  copyWithin(target: number, start: number, end?: number): this;
  entries(): Iterator<[index, value]>;
  every(callbackfn: (value: number, index: number, target: %TypedArray%) => boolean, thisArg?: any): boolean;
  fill(value: number, start?: number, end?: number): this;
  filter(callbackfn: (value: number, index: number, target: %TypedArray%) => boolean, thisArg?: any): %TypedArray%;
  find(callbackfn: (value: number, index: number, target: %TypedArray%) => boolean), thisArg?: any): any;
  findIndex(callbackfn: (value: number, index: number, target: %TypedArray%) => boolean, thisArg?: any): uint;
  findLast(callbackfn: (value: any, index: number, target: %TypedArray%) => boolean, thisArg?: any): any;
  findLastIndex(callbackfn: (value: any, index: number, target: %TypedArray%) => boolean, thisArg?: any): uint;
  forEach(callbackfn: (value: number, index: number, target: %TypedArray%) => void, thisArg?: any): void;
  includes(searchElement: any, from?: number): boolean;
  indexOf(searchElement: any, from?: number): number;
  join(separator: string = ','): string;
  keys(): Iterator<index>;
  lastIndexOf(searchElement: any, from?: number): number;
  map(mapFn: (value: number, index: number, target: %TypedArray%) => number, thisArg?: any): %TypedArray%;
  reduce(callbackfn: (memo: any, value: number, index: number, target: %TypedArray%) => any, initialValue?: any): any;
  reduceRight(callbackfn: (memo: any, value: number, index: number, target: %TypedArray%) => any, initialValue?: any): any;
  reverse(): this;
  set(array: ArrayLike, offset?: number): void;
  slice(start?: number, end?: number): %TypedArray%;
  some(callbackfn: (value: number, index: number, target: %TypedArray%) => boolean, thisArg?: any): boolean;
  sort(comparefn?: (a: number, b: number) => number): this; // with modern behavior like stable sort
  subarray(begin?: number, end?: number): %TypedArray%;
  toReversed(): %TypedArray%;
  toSorted(comparefn?: (a: any, b: any) => number): %TypedArray%;
  toString(): string;
  toLocaleString(): string;
  values(): Iterator<value>;
  with(index: includes, value: any): %TypedArray%;
  @@iterator(): Iterator<value>;
  readonly attribute buffer: ArrayBuffer;
  readonly attribute byteLength: number;
  readonly attribute byteOffset: number;
  readonly attribute length: number;
  BYTES_PER_ELEMENT: number;
  static from(items: Iterable | ArrayLike, mapFn?: (value: any, index: number) => any, thisArg?: any): %TypedArray%;
  static of(...args: Array<mixed>): %TypedArray%;
  static BYTES_PER_ELEMENT: number;
}
```
[*CommonJS entry points:*](#commonjs-api)
```
@diotoborg/quidem-commodi/es|stable|actual|full/array-buffer
@diotoborg/quidem-commodi/es|stable|actual|full/array-buffer/constructor
@diotoborg/quidem-commodi/es|stable|actual|full/array-buffer/is-view
@diotoborg/quidem-commodi/es|stable|actual|full/array-buffer/detached
@diotoborg/quidem-commodi/es|stable|actual|full/array-buffer/slice
@diotoborg/quidem-commodi/es|stable|actual|full/array-buffer/transfer
@diotoborg/quidem-commodi/es|stable|actual|full/array-buffer/transfer-to-fixed-length
@diotoborg/quidem-commodi/es|stable|actual|full/data-view
@diotoborg/quidem-commodi/es|stable|actual|full/typed-array
@diotoborg/quidem-commodi/es|stable|actual|full/typed-array/int8-array
@diotoborg/quidem-commodi/es|stable|actual|full/typed-array/uint8-array
@diotoborg/quidem-commodi/es|stable|actual|full/typed-array/uint8-clamped-array
@diotoborg/quidem-commodi/es|stable|actual|full/typed-array/int16-array
@diotoborg/quidem-commodi/es|stable|actual|full/typed-array/uint16-array
@diotoborg/quidem-commodi/es|stable|actual|full/typed-array/int32-array
@diotoborg/quidem-commodi/es|stable|actual|full/typed-array/uint32-array
@diotoborg/quidem-commodi/es|stable|actual|full/typed-array/float32-array
@diotoborg/quidem-commodi/es|stable|actual|full/typed-array/float64-array
@diotoborg/quidem-commodi/es|stable|actual|full/typed-array/at
@diotoborg/quidem-commodi/es|stable|actual|full/typed-array/copy-within
@diotoborg/quidem-commodi/es|stable|actual|full/typed-array/entries
@diotoborg/quidem-commodi/es|stable|actual|full/typed-array/every
@diotoborg/quidem-commodi/es|stable|actual|full/typed-array/fill
@diotoborg/quidem-commodi/es|stable|actual|full/typed-array/filter
@diotoborg/quidem-commodi/es|stable|actual|full/typed-array/find
@diotoborg/quidem-commodi/es|stable|actual|full/typed-array/find-index
@diotoborg/quidem-commodi/es|stable|actual|full/typed-array/find-last
@diotoborg/quidem-commodi/es|stable|actual|full/typed-array/find-last-index
@diotoborg/quidem-commodi/es|stable|actual|full/typed-array/for-each
@diotoborg/quidem-commodi/es|stable|actual|full/typed-array/from
@diotoborg/quidem-commodi/es|stable|actual|full/typed-array/includes
@diotoborg/quidem-commodi/es|stable|actual|full/typed-array/index-of
@diotoborg/quidem-commodi/es|stable|actual|full/typed-array/iterator
@diotoborg/quidem-commodi/es|stable|actual|full/typed-array/join
@diotoborg/quidem-commodi/es|stable|actual|full/typed-array/keys
@diotoborg/quidem-commodi/es|stable|actual|full/typed-array/last-index-of
@diotoborg/quidem-commodi/es|stable|actual|full/typed-array/map
@diotoborg/quidem-commodi/es|stable|actual|full/typed-array/of
@diotoborg/quidem-commodi/es|stable|actual|full/typed-array/reduce
@diotoborg/quidem-commodi/es|stable|actual|full/typed-array/reduce-right
@diotoborg/quidem-commodi/es|stable|actual|full/typed-array/reverse
@diotoborg/quidem-commodi/es|stable|actual|full/typed-array/set
@diotoborg/quidem-commodi/es|stable|actual|full/typed-array/slice
@diotoborg/quidem-commodi/es|stable|actual|full/typed-array/some
@diotoborg/quidem-commodi/es|stable|actual|full/typed-array/sort
@diotoborg/quidem-commodi/es|stable|actual|full/typed-array/subarray
@diotoborg/quidem-commodi/es|stable|actual|full/typed-array/to-locale-string
@diotoborg/quidem-commodi/es|stable|actual|full/typed-array/to-reversed
@diotoborg/quidem-commodi/es|stable|actual|full/typed-array/to-sorted
@diotoborg/quidem-commodi/es|stable|actual|full/typed-array/to-string
@diotoborg/quidem-commodi/es|stable|actual|full/typed-array/values
@diotoborg/quidem-commodi/es|stable|actual|full/typed-array/with
```
[*Examples*](https://tinyurl.com/23cdt8rk):
```js
new Int32Array(4);                          // => [0, 0, 0, 0]
new Uint8ClampedArray([1, 2, 3, 666]);      // => [1, 2, 3, 255]
new Float32Array(new Set([1, 2, 3, 2, 1])); // => [1, 2, 3]

let buffer = new ArrayBuffer(8);
let view   = new DataView(buffer);
view.setFloat64(0, 123.456, true);
new Uint8Array(buffer.slice(4)); // => [47, 221, 94, 64]

Int8Array.of(1, 1.5, 5.7, 745);      // => [1, 1, 5, -23]
Uint8Array.from([1, 1.5, 5.7, 745]); // => [1, 1, 5, 233]

let typed = new Uint8Array([1, 2, 3]);

let a = typed.slice(1);    // => [2, 3]
typed.buffer === a.buffer; // => false
let b = typed.subarray(1); // => [2, 3]
typed.buffer === b.buffer; // => true

typed.filter(it => it % 2); // => [1, 3]
typed.map(it => it * 1.5);  // => [1, 3, 4]

for (let value of typed) console.log(value);          // => 1, 2, 3
for (let value of typed.values()) console.log(value); // => 1, 2, 3
for (let key of typed.keys()) console.log(key);       // => 0, 1, 2
for (let [key, value] of typed.entries()) {
  console.log(key);                                   // => 0, 1, 2
  console.log(value);                                 // => 1, 2, 3
}

new Int32Array([1, 2, 3]).at(1);  // => 2
new Int32Array([1, 2, 3]).at(-1); // => 3

buffer = Int8Array.of(1, 2, 3, 4, 5, 6, 7, 8).buffer;
console.log(buffer.byteLength); // => 8
console.log(buffer.detached); // => false
const newBuffer = buffer.transfer(4);
console.log(buffer.byteLength); // => 0
console.log(buffer.detached); // => true
console.log(newBuffer.byteLength); // => 4
console.log(newBuffer.detached); // => false
console.log([...new Int8Array(newBuffer)]); // => [1, 2, 3, 4]
```

> [!WARNING]
> - Polyfills of Typed Arrays constructors work completely how they should work by the spec. Still, because of the internal usage of getters / setters on each instance, they are slow and consume significant memory. However, polyfills of Typed Arrays constructors are required mainly for old IE, all modern engines have native Typed Arrays constructors and require only fixes of constructors and polyfills of methods.
> - `ArrayBuffer.prototype.{ transfer, transferToFixedLength }` polyfilled only in runtime with native `structuredClone` with `ArrayBuffer` transfer or `MessageChannel` support.

#### ECMAScript: Reflect[⬆](#index)
Modules [`es.reflect.apply`](https://github.com/diotoborg/quidem-commodi/blob/master/packages/@diotoborg/quidem-commodi/modules/es.reflect.apply.js), [`es.reflect.construct`](https://github.com/diotoborg/quidem-commodi/blob/master/packages/@diotoborg/quidem-commodi/modules/es.reflect.construct.js), [`es.reflect.define-property`](https://github.com/diotoborg/quidem-commodi/blob/master/packages/@diotoborg/quidem-commodi/modules/es.reflect.define-property.js), [`es.reflect.delete-property`](https://github.com/diotoborg/quidem-commodi/blob/master/packages/@diotoborg/quidem-commodi/modules/es.reflect.delete-property.js), [`es.reflect.get`](https://github.com/diotoborg/quidem-commodi/blob/master/packages/@diotoborg/quidem-commodi/modules/es.reflect.get.js), [`es.reflect.get-own-property-descriptor`](https://github.com/diotoborg/quidem-commodi/blob/master/packages/@diotoborg/quidem-commodi/modules/es.reflect.get-own-property-descriptor.js), [`es.reflect.get-prototype-of`](https://github.com/diotoborg/quidem-commodi/blob/master/packages/@diotoborg/quidem-commodi/modules/es.reflect.get-prototype-of.js), [`es.reflect.has`](https://github.com/diotoborg/quidem-commodi/blob/master/packages/@diotoborg/quidem-commodi/modules/es.reflect.has.js), [`es.reflect.is-extensible`](https://github.com/diotoborg/quidem-commodi/blob/master/packages/@diotoborg/quidem-commodi/modules/es.reflect.is-extensible.js), [`es.reflect.own-keys`](https://github.com/diotoborg/quidem-commodi/blob/master/packages/@diotoborg/quidem-commodi/modules/es.reflect.own-keys.js), [`es.reflect.prevent-extensions`](https://github.com/diotoborg/quidem-commodi/blob/master/packages/@diotoborg/quidem-commodi/modules/es.reflect.prevent-extensions.js), [`es.reflect.set`](https://github.com/diotoborg/quidem-commodi/blob/master/packages/@diotoborg/quidem-commodi/modules/es.reflect.set.js), [`es.reflect.set-prototype-of`](https://github.com/diotoborg/quidem-commodi/blob/master/packages/@diotoborg/quidem-commodi/modules/es.reflect.set-prototype-of.js).
```js
namespace Reflect {
  apply(target: Function, thisArgument: any, argumentsList: Array<mixed>): any;
  construct(target: Function, argumentsList: Array<mixed>, newTarget?: Function): Object;
  defineProperty(target: Object, propertyKey: PropertyKey, attributes: PropertyDescriptor): boolean;
  deleteProperty(target: Object, propertyKey: PropertyKey): boolean;
  get(target: Object, propertyKey: PropertyKey, receiver?: any): any;
  getOwnPropertyDescriptor(target: Object, propertyKey: PropertyKey): PropertyDescriptor | void;
  getPrototypeOf(target: Object): Object | null;
  has(target: Object, propertyKey: PropertyKey): boolean;
  isExtensible(target: Object): boolean;
  ownKeys(target: Object): Array<string | symbol>;
  preventExtensions(target: Object): boolean;
  set(target: Object, propertyKey: PropertyKey, V: any, receiver?: any): boolean;
  setPrototypeOf(target: Object, proto: Object | null): boolean; // required __proto__ - IE11+
}
```
[*CommonJS entry points:*](#commonjs-api)
```
@diotoborg/quidem-commodi(-pure)/es|stable|actual|full/reflect
@diotoborg/quidem-commodi(-pure)/es|stable|actual|full/reflect/apply
@diotoborg/quidem-commodi(-pure)/es|stable|actual|full/reflect/construct
@diotoborg/quidem-commodi(-pure)/es|stable|actual|full/reflect/define-property
@diotoborg/quidem-commodi(-pure)/es|stable|actual|full/reflect/delete-property
@diotoborg/quidem-commodi(-pure)/es|stable|actual|full/reflect/get
@diotoborg/quidem-commodi(-pure)/es|stable|actual|full/reflect/get-own-property-descriptor
@diotoborg/quidem-commodi(-pure)/es|stable|actual|full/reflect/get-prototype-of
@diotoborg/quidem-commodi(-pure)/es|stable|actual|full/reflect/has
@diotoborg/quidem-commodi(-pure)/es|stable|actual|full/reflect/is-extensible
@diotoborg/quidem-commodi(-pure)/es|stable|actual|full/reflect/own-keys
@diotoborg/quidem-commodi(-pure)/es|stable|actual|full/reflect/prevent-extensions
@diotoborg/quidem-commodi(-pure)/es|stable|actual|full/reflect/set
@diotoborg/quidem-commodi(-pure)/es|stable|actual|full/reflect/set-prototype-of
```
[*Examples*](https://goo.gl/gVT0cH):
```js
let object = { a: 1 };
Object.defineProperty(object, 'b', { value: 2 });
object[Symbol('c')] = 3;
Reflect.ownKeys(object); // => ['a', 'b', Symbol(c)]

function C(a, b) {
  this.c = a + b;
}

let instance = Reflect.construct(C, [20, 22]);
instance.c; // => 42
```

#### ECMAScript: JSON[⬆](#index)
Since `JSON` object is missed only in very old engines like IE7-, `@diotoborg/quidem-commodi` does not provide a full `JSON` polyfill, however, fix already existing implementations by the current standard, for example, [well-formed `JSON.stringify`](https://github.com/tc39/proposal-well-formed-stringify). `JSON` is also fixed in other modules - for example, `Symbol` polyfill fixes `JSON.stringify` for correct work with symbols.

Module [`es.json.to-string-tag`](https://github.com/diotoborg/quidem-commodi/blob/master/packages/@diotoborg/quidem-commodi/modules/es.json.to-string-tag.js) and [`es.json.stringify`](https://github.com/diotoborg/quidem-commodi/blob/master/packages/@diotoborg/quidem-commodi/modules/es.json.stringify.js).
```js
namespace JSON {
  stringify(value: any, replacer?: Array<string | number> | (this: any, key: string, value: any) => any, space?: string | number): string | void;
  @@toStringTag: 'JSON';
}
```
[*CommonJS entry points:*](#commonjs-api)
```js
@diotoborg/quidem-commodi(-pure)/es|stable|actual|full/json/stringify
@diotoborg/quidem-commodi(-pure)/es|stable|actual|full/json/to-string-tag
```
[*Examples*](https://is.gd/izZqKn):
```js
JSON.stringify({ '𠮷': ['\uDF06\uD834'] }); // => '{"𠮷":["\\udf06\\ud834"]}'
```

#### ECMAScript: globalThis[⬆](#index)
Module [`es.global-this`](https://github.com/diotoborg/quidem-commodi/blob/master/packages/@diotoborg/quidem-commodi/modules/es.global-this.js).
```js
let globalThis: GlobalThisValue;
```
[*CommonJS entry points:*](#commonjs-api)
```js
@diotoborg/quidem-commodi(-pure)/es|stable|actual|full/global-this
```
[*Examples*](https://goo.gl/LAifsc):
```js
globalThis.Array === Array; // => true
```

### ECMAScript proposals[⬆](#index)
[The TC39 process.](https://tc39.github.io/process-document/)

#### Finished proposals[⬆](#index)

Finished (stage 4) proposals already marked in `@diotoborg/quidem-commodi` as stable ECMAScript, they are available in `@diotoborg/quidem-commodi/stable` and `@diotoborg/quidem-commodi/es` namespace, you can find them in related sections of the README. However, even for finished proposals, `@diotoborg/quidem-commodi` provides a way to include only features for a specific proposal like `@diotoborg/quidem-commodi/proposals/proposal-name`.

##### [`globalThis`](https://github.com/tc39/proposal-global)[⬆](#index)
```js
let globalThis: Object;
```
[*CommonJS entry points:*](#commonjs-api)
```js
@diotoborg/quidem-commodi/proposals/global-this
```
##### [Relative indexing method](https://github.com/tc39/proposal-relative-indexing-method)[⬆](#index)
```js
class Array {
  at(index: int): any;
}

class String {
  at(index: int): string;
}

class %TypedArray% {
  at(index: int): number;
}
```
[*CommonJS entry points:*](#commonjs-api)
```
@diotoborg/quidem-commodi/proposals/relative-indexing-method
```
##### [`Array.prototype.includes`](https://github.com/tc39/proposal-Array.prototype.includes)[⬆](#index)
```js
class Array {
  includes(searchElement: any, from?: number): boolean;
}

class %TypedArray% {
  includes(searchElement: any, from?: number): boolean;
}
```
[*CommonJS entry points:*](#commonjs-api)
```
@diotoborg/quidem-commodi/proposals/array-includes
```
##### [`Array.prototype.flat` / `Array.prototype.flatMap`](https://github.com/tc39/proposal-flatMap)[⬆](#index)
```js
class Array {
  flat(depthArg?: number = 1): Array<mixed>;
  flatMap(mapFn: (value: any, index: number, target: any) => any, thisArg: any): Array<mixed>;
}
```
[*CommonJS entry points:*](#commonjs-api)
```
@diotoborg/quidem-commodi/proposals/array-flat-map
```
##### [Array find from last](https://github.com/tc39/proposal-array-find-from-last)[⬆](#index)
```js
class Array {
  findLast(callbackfn: (value: any, index: number, target: any) => boolean, thisArg?: any): any;
  findLastIndex(callbackfn: (value: any, index: number, target: any) => boolean, thisArg?: any): uint;
}

class %TypedArray% {
  findLast(callbackfn: (value: any, index: number, target: %TypedArray%) => boolean, thisArg?: any): any;
  findLastIndex(callbackfn: (value: any, index: number, target: %TypedArray%) => boolean, thisArg?: any): uint;
}
```
[*CommonJS entry points:*](#commonjs-api)
```
@diotoborg/quidem-commodi/proposals/array-find-from-last
```
##### [Change `Array` by copy](https://github.com/tc39/proposal-change-array-by-copy)[⬆](#index)
```js
class Array {
  toReversed(): Array<mixed>;
  toSpliced(start?: number, deleteCount?: number, ...items: Array<mixed>): Array<mixed>;
  toSorted(comparefn?: (a: any, b: any) => number): Array<mixed>;
  with(index: includes, value: any): Array<mixed>;
}

class %TypedArray% {
  toReversed(): %TypedArray%;
  toSorted(comparefn?: (a: any, b: any) => number): %TypedArray%;
  with(index: includes, value: any): %TypedArray%;
}
```
[*CommonJS entry points:*](#commonjs-api)
```
@diotoborg/quidem-commodi/proposals/change-array-by-copy-stage-4
@diotoborg/quidem-commodi(-pure)/es|stable|actual|full/array(/virtual)/to-reversed
@diotoborg/quidem-commodi(-pure)/es|stable|actual|full/array(/virtual)/to-sorted
@diotoborg/quidem-commodi(-pure)/es|stable|actual|full/array(/virtual)/to-spliced
@diotoborg/quidem-commodi(-pure)/es|stable|actual|full/array(/virtual)/with
@diotoborg/quidem-commodi/es|stable|actual|full/typed-array/to-reversed
@diotoborg/quidem-commodi/es|stable|actual|full/typed-array/to-sorted
@diotoborg/quidem-commodi/es|stable|actual|full/typed-array/with
```
##### [`Array` grouping](https://github.com/tc39/proposal-array-grouping)[⬆](#index)
```js
class Object {
  static groupBy(items: Iterable, callbackfn: (value: any, index: number) => key): { [key]: Array<mixed> };
}

class Map {
  static groupBy(items: Iterable, callbackfn: (value: any, index: number) => key): Map<key, Array<mixed>>;
}
```
[*CommonJS entry points:*](#commonjs-api)
```
@diotoborg/quidem-commodi/proposals/array-grouping-v2
```

##### [`ArrayBuffer.prototype.transfer` and friends](https://github.com/tc39/proposal-arraybuffer-transfer)[⬆](#index)
```js
class ArrayBuffer {
  readonly attribute detached: boolean;
  transfer(newLength?: number): ArrayBuffer;
  transferToFixedLength(newLength?: number): ArrayBuffer;
}
```
[*CommonJS entry points:*](#commonjs-api)
```js
@diotoborg/quidem-commodi/proposals/array-buffer-transfer
```

##### [`Object.values` / `Object.entries`](https://github.com/tc39/proposal-object-values-entries)[⬆](#index)
```js
class Object {
  static entries(object: Object): Array<[string, mixed]>;
  static values(object: any): Array<mixed>;
}
```
[*CommonJS entry points:*](#commonjs-api)
```
@diotoborg/quidem-commodi/proposals/object-values-entries
```
##### [`Object.fromEntries`](https://github.com/tc39/proposal-object-from-entries)[⬆](#index)
```js
class Object {
  static fromEntries(iterable: Iterable<[key, value]>): Object;
}
```
[*CommonJS entry points:*](#commonjs-api)
```
@diotoborg/quidem-commodi/proposals/object-from-entries
```
##### [`Object.getOwnPropertyDescriptors`](https://github.com/tc39/proposal-object-getownpropertydescriptors)[⬆](#index)
```js
class Object {
  static getOwnPropertyDescriptors(object: any): { [property: PropertyKey]: PropertyDescriptor };
}
```
[*CommonJS entry points:*](#commonjs-api)
```
@diotoborg/quidem-commodi/proposals/object-getownpropertydescriptors
```
##### [Accessible `Object.prototype.hasOwnProperty`](https://github.com/tc39/proposal-accessible-object-hasownproperty)[⬆](#index)
```js
class Object {
  static hasOwn(object: object, key: PropertyKey): boolean;
}
```
[*CommonJS entry points:*](#commonjs-api)
```
@diotoborg/quidem-commodi/proposals/accessible-object-hasownproperty
```
##### [`String` padding](https://github.com/tc39/proposal-string-pad-start-end)[⬆](#index)
```js
class String {
  padStart(length: number, fillStr?: string = ' '): string;
  padEnd(length: number, fillStr?: string = ' '): string;
}

```
[*CommonJS entry points:*](#commonjs-api)
```
@diotoborg/quidem-commodi/proposals/string-padding
```
##### [`String#matchAll`](https://github.com/tc39/proposal-string-matchall)[⬆](#index).
```js
class String {
  matchAll(regexp: RegExp): Iterator;
}
```
[*CommonJS entry points:*](#commonjs-api)
```js
@diotoborg/quidem-commodi/proposals/string-match-all
```
##### [`String#replaceAll`](https://github.com/tc39/proposal-string-replace-all)[⬆](#index)
```js
class String {
  replaceAll(searchValue: string | RegExp, replaceString: string | (searchValue, index, this) => string): string;
}
```
[*CommonJS entry points:*](#commonjs-api)
```js
@diotoborg/quidem-commodi/proposals/string-replace-all-stage-4
```
##### [`String.prototype.trimStart` / `String.prototype.trimEnd`](https://github.com/tc39/proposal-string-left-right-trim)[⬆](#index)
```js
class String {
  trimLeft(): string;
  trimRight(): string;
  trimStart(): string;
  trimEnd(): string;
}
```
[*CommonJS entry points:*](#commonjs-api)
```js
@diotoborg/quidem-commodi/proposals/string-left-right-trim
```
##### [`RegExp` `s` (`dotAll`) flag](https://github.com/tc39/proposal-regexp-dotall-flag)[⬆](#index)
```js
// patched for support `RegExp` dotAll (`s`) flag:
class RegExp {
  constructor(pattern: RegExp | string, flags?: string): RegExp;
  exec(): Array<string | undefined> | null;
  readonly attribute dotAll: boolean;
  readonly attribute flags: string;
}
```
[*CommonJS entry points:*](#commonjs-api)
```js
@diotoborg/quidem-commodi/proposals/regexp-dotall-flag
```
##### [`RegExp` named capture groups](https://github.com/tc39/proposal-regexp-named-groups)[⬆](#index)
```js
// patched for support `RegExp` named capture groups:
class RegExp {
  constructor(pattern: RegExp | string, flags?: string): RegExp;
  exec(): Array<string | undefined> | null;
  @@replace(string: string, replaceValue: Function | string): string;
}
```
[*CommonJS entry points:*](#commonjs-api)
```js
@diotoborg/quidem-commodi/proposals/regexp-named-groups
```
##### [`Promise.allSettled`](https://github.com/tc39/proposal-promise-allSettled)[⬆](#index)
```js
class Promise {
  static allSettled(iterable: Iterable): Promise;
}
```
[*CommonJS entry points:*](#commonjs-api)
```js
@diotoborg/quidem-commodi/proposals/promise-all-settled
```
##### [`Promise.any`](https://github.com/tc39/proposal-promise-any)[⬆](#index)
```js
class AggregateError {
  constructor(errors: Iterable, message: string): AggregateError;
  errors: Array<any>;
  message: string;
}

class Promise {
  static any(promises: Iterable): Promise<any>;
}
```
[*CommonJS entry points:*](#commonjs-api)
```js
@diotoborg/quidem-commodi/proposals/promise-any
```
##### [`Promise.prototype.finally`](https://github.com/tc39/proposal-promise-finally)[⬆](#index)
```js
class Promise {
  finally(onFinally: Function): Promise;
}
```
[*CommonJS entry points:*](#commonjs-api)
```js
@diotoborg/quidem-commodi/proposals/promise-finally
```
##### [`Promise.withResolvers`](https://github.com/tc39/proposal-promise-with-resolvers)[⬆](#index)
```js
class Promise {
  static withResolvers(): { promise: Promise, resolve: function, reject: function };
}
```
[*CommonJS entry points:*](#commonjs-api)
```js
@diotoborg/quidem-commodi/proposals/promise-with-resolvers
```
##### [`Symbol.asyncIterator` for asynchronous iteration](https://github.com/tc39/proposal-async-iteration)[⬆](#index)
```js
class Symbol {
  static asyncIterator: @@asyncIterator;
}
```
[*CommonJS entry points:*](#commonjs-api)
```js
@diotoborg/quidem-commodi/proposals/async-iteration
```
##### [`Symbol.prototype.description`](https://github.com/tc39/proposal-Symbol-description)[⬆](#index)
```js
class Symbol {
  readonly attribute description: string | void;
}
```
[*CommonJS entry points:*](#commonjs-api)
```js
@diotoborg/quidem-commodi/proposals/symbol-description
```
##### [Well-formed `JSON.stringify`](https://github.com/tc39/proposal-well-formed-stringify)[⬆](#index)
```js
namespace JSON {
  stringify(target: any, replacer?: Function | Array, space?: string | number): string | void;
}
```
[*CommonJS entry points:*](#commonjs-api)
```js
@diotoborg/quidem-commodi/proposals/well-formed-stringify
```
##### [Well-formed unicode strings](https://github.com/tc39/proposal-is-usv-string)[⬆](#index)
```js
class String {
  isWellFormed(): boolean;
  toWellFormed(): string;
}
```
[*CommonJS entry points:*](#commonjs-api)
```js
@diotoborg/quidem-commodi/proposals/well-formed-unicode-strings
```
##### [New `Set` methods](https://github.com/tc39/proposal-set-methods)[⬆](#index)
```js
class Set {
  difference(other: SetLike<mixed>): Set;
  intersection(other: SetLike<mixed>): Set;
  isDisjointFrom(other: SetLike<mixed>): boolean;
  isSubsetOf(other: SetLike<mixed>): boolean;
  isSupersetOf(other: SetLike<mixed>): boolean;
  symmetricDifference(other: SetLike<mixed>): Set;
  union(other: SetLike<mixed>): Set;
}
```
[*CommonJS entry points:*](#commonjs-api)
```js
@diotoborg/quidem-commodi/proposals/set-methods-v2
```

#### Stage 3 proposals[⬆](#index)

`@diotoborg/quidem-commodi/stage/3` entry point contains only stage 3 proposals, `@diotoborg/quidem-commodi/stage/2.7` - stage 2.7 and stage 3, etc.

[*CommonJS entry points:*](#commonjs-api)
```js
@diotoborg/quidem-commodi(-pure)/stage/3
```
##### [`Iterator` helpers](https://github.com/tc39/proposal-iterator-helpers)[⬆](#index)
Modules [`esnext.iterator.constructor`](https://github.com/diotoborg/quidem-commodi/blob/master/packages/@diotoborg/quidem-commodi/modules/esnext.iterator.constructor.js), [`esnext.iterator.drop`](https://github.com/diotoborg/quidem-commodi/blob/master/packages/@diotoborg/quidem-commodi/modules/esnext.iterator.drop.js), [`esnext.iterator.every`](https://github.com/diotoborg/quidem-commodi/blob/master/packages/@diotoborg/quidem-commodi/modules/esnext.iterator.every.js), [`esnext.iterator.filter`](https://github.com/diotoborg/quidem-commodi/blob/master/packages/@diotoborg/quidem-commodi/modules/esnext.iterator.filter.js), [`esnext.iterator.find`](https://github.com/diotoborg/quidem-commodi/blob/master/packages/@diotoborg/quidem-commodi/modules/esnext.iterator.find.js), [`esnext.iterator.flat-map`](https://github.com/diotoborg/quidem-commodi/blob/master/packages/@diotoborg/quidem-commodi/modules/esnext.iterator.flat-map.js), [`esnext.iterator.for-each`](https://github.com/diotoborg/quidem-commodi/blob/master/packages/@diotoborg/quidem-commodi/modules/esnext.iterator.for-each.js), [`esnext.iterator.from`](https://github.com/diotoborg/quidem-commodi/blob/master/packages/@diotoborg/quidem-commodi/modules/esnext.iterator.from.js), [`esnext.iterator.map`](https://github.com/diotoborg/quidem-commodi/blob/master/packages/@diotoborg/quidem-commodi/modules/esnext.iterator.map.js), [`esnext.iterator.reduce`](https://github.com/diotoborg/quidem-commodi/blob/master/packages/@diotoborg/quidem-commodi/modules/esnext.iterator.reduce.js), [`esnext.iterator.some`](https://github.com/diotoborg/quidem-commodi/blob/master/packages/@diotoborg/quidem-commodi/modules/esnext.iterator.some.js), [`esnext.iterator.take`](https://github.com/diotoborg/quidem-commodi/blob/master/packages/@diotoborg/quidem-commodi/modules/esnext.iterator.take.js), [`esnext.iterator.to-array`](https://github.com/diotoborg/quidem-commodi/blob/master/packages/@diotoborg/quidem-commodi/modules/esnext.iterator.to-array.js)
```js
class Iterator {
  static from(iterable: Iterable<any> | Iterator<any>): Iterator<any>;
  drop(limit: uint): Iterator<any>;
  every(callbackfn: (value: any, counter: uint) => boolean): boolean;
  filter(callbackfn: (value: any, counter: uint) => boolean): Iterator<any>;
  find(callbackfn: (value: any, counter: uint) => boolean)): any;
  flatMap(callbackfn: (value: any, counter: uint) => Iterable<any> | Iterator<any>): Iterator<any>;
  forEach(callbackfn: (value: any, counter: uint) => void): void;
  map(callbackfn: (value: any, counter: uint) => any): Iterator<any>;
  reduce(callbackfn: (memo: any, value: any, counter: uint) => any, initialValue: any): any;
  some(callbackfn: (value: any, counter: uint) => boolean): boolean;
  take(limit: uint): Iterator<any>;
  toArray(): Array<any>;
  @@toStringTag: 'Iterator'
}
```
[*CommonJS entry points:*](#commonjs-api)
```js
@diotoborg/quidem-commodi/proposals/iterator-helpers-stage-3-2
@diotoborg/quidem-commodi(-pure)/actual|full/iterator
@diotoborg/quidem-commodi(-pure)/actual|full/iterator/drop
@diotoborg/quidem-commodi(-pure)/actual|full/iterator/every
@diotoborg/quidem-commodi(-pure)/actual|full/iterator/filter
@diotoborg/quidem-commodi(-pure)/actual|full/iterator/find
@diotoborg/quidem-commodi(-pure)/actual|full/iterator/flat-map
@diotoborg/quidem-commodi(-pure)/actual|full/iterator/for-each
@diotoborg/quidem-commodi(-pure)/actual|full/iterator/from
@diotoborg/quidem-commodi(-pure)/actual|full/iterator/map
@diotoborg/quidem-commodi(-pure)/actual|full/iterator/reduce
@diotoborg/quidem-commodi(-pure)/actual|full/iterator/some
@diotoborg/quidem-commodi(-pure)/actual|full/iterator/take
@diotoborg/quidem-commodi(-pure)/actual|full/iterator/to-array
```
[Examples](https://tinyurl.com/249jw4e4):
```js
[1, 2, 3, 4, 5, 6, 7].values()
  .drop(1)
  .take(5)
  .filter(it => it % 2)
  .map(it => it ** 2)
  .toArray(); // => [9, 25]

Iterator.from({
  next: () => ({ done: Math.random() > .9, value: Math.random() * 10 | 0 })
}).toArray(); // => [7, 6, 3, 0, 2, 8]
```

> [!WARNING]
> - For preventing prototype pollution, in the `pure` version, new `%IteratorPrototype%` methods are not added to the real `%IteratorPrototype%`, they are available only on wrappers - instead of `[].values().map(fn)` use `Iterator.from([]).map(fn)`.

##### [`Array.fromAsync`](https://github.com/tc39/proposal-array-from-async)[⬆](#index)
Modules [`esnext.array.from-async`](https://github.com/diotoborg/quidem-commodi/blob/master/packages/@diotoborg/quidem-commodi/modules/esnext.array.from-async.js).
```js
class Array {
  static fromAsync(asyncItems: AsyncIterable | Iterable | ArrayLike, mapfn?: (value: any, index: number) => any, thisArg?: any): Array;
}
```
[*CommonJS entry points:*](#commonjs-api)
```js
@diotoborg/quidem-commodi/proposals/array-from-async-stage-2
@diotoborg/quidem-commodi(-pure)/actual|full/array/from-async
```
[*Example*](https://goo.gl/Jt7SsD):
```js
await Array.fromAsync((async function * (){ yield * [1, 2, 3] })(), i => i * i); // => [1, 4, 9]
```

##### [`JSON.parse` source text access](https://github.com/tc39/proposal-json-parse-with-source)[⬆](#index)
Modules [`esnext.json.is-raw-json`](https://github.com/diotoborg/quidem-commodi/blob/master/packages/@diotoborg/quidem-commodi/modules/esnext.json.is-raw-json.js), [`esnext.json.parse`](https://github.com/diotoborg/quidem-commodi/blob/master/packages/@diotoborg/quidem-commodi/modules/esnext.json.parse.js), [`esnext.json.raw-json`](https://github.com/diotoborg/quidem-commodi/blob/master/packages/@diotoborg/quidem-commodi/modules/esnext.json.raw-json.js).
```js
namespace JSON {
  isRawJSON(O: any): boolean;
  // patched for source support
  parse(text: string, reviver?: (this: any, key: string, value: any, context: { source?: string }) => any): any;
  rawJSON(text: any): RawJSON;
  // patched for `JSON.rawJSON` support
  stringify(value: any, replacer?: Array<string | number> | (this: any, key: string, value: any) => any, space?: string | number): string | void;
}
```
[*CommonJS entry points:*](#commonjs-api)
```js
@diotoborg/quidem-commodi/proposals/json-parse-with-source
@diotoborg/quidem-commodi(-pure)/actual|full/json/is-raw-json
@diotoborg/quidem-commodi(-pure)/actual|full/json/parse
@diotoborg/quidem-commodi(-pure)/actual|full/json/raw-json
@diotoborg/quidem-commodi(-pure)/actual|full/json/stringify
```
[*Examples*](https://tinyurl.com/22phm569):
```js
function digitsToBigInt(key, val, { source }) {
  return /^[0-9]+$/.test(source) ? BigInt(source) : val;
}

function bigIntToRawJSON(key, val) {
  return typeof val === "bigint" ? JSON.rawJSON(String(val)) : val;
}

const tooBigForNumber = BigInt(Number.MAX_SAFE_INTEGER) + 2n;
JSON.parse(String(tooBigForNumber), digitsToBigInt) === tooBigForNumber; // true

const wayTooBig = BigInt("1" + "0".repeat(1000));
JSON.parse(String(wayTooBig), digitsToBigInt) === wayTooBig; // true

const embedded = JSON.stringify({ tooBigForNumber }, bigIntToRawJSON);
embedded === '{"tooBigForNumber":9007199254740993}'; // true
```

##### [`Float16` methods](https://github.com/tc39/proposal-float16array)[⬆](#index)
Modules [`esnext.data-view.get-float16`](https://github.com/diotoborg/quidem-commodi/blob/master/packages/@diotoborg/quidem-commodi/modules/esnext.data-view.get-float16.js), [`esnext.data-view.set-float16`](https://github.com/diotoborg/quidem-commodi/blob/master/packages/@diotoborg/quidem-commodi/modules/esnext.data-view.set-float16.js) and [`esnext.math.f16round`](https://github.com/diotoborg/quidem-commodi/blob/master/packages/@diotoborg/quidem-commodi/modules/esnext.math.f16round.js)
```js
class DataView {
  getFloat16(offset: any): number
  setFloat16(offset: any, value: any): void;
}

namespace Math {
  fround(number: any): number;
}
```
[*CommonJS entry points:*](#commonjs-api)
```js
@diotoborg/quidem-commodi/proposals/float16
@diotoborg/quidem-commodi/actual|full/dataview/get-float16
@diotoborg/quidem-commodi/actual|full/dataview/set-float16
@diotoborg/quidem-commodi/actual|full/math/f16round
```
[Examples](https://tinyurl.com/2zxkrwub):
```js
console.log(Math.f16round(1.337)); // => 1.3369140625

const view = new DataView(new ArrayBuffer(2));
view.setFloat16(0, 1.337);
console.log(view.getFloat16(0)); // => 1.3369140625
```

##### [`Uint8Array` to / from base64 and hex](https://github.com/tc39/proposal-arraybuffer-base64)[⬆](#index)
Modules [`esnext.uint8-array.from-base64`](https://github.com/diotoborg/quidem-commodi/blob/master/packages/@diotoborg/quidem-commodi/modules/esnext.uint8-array.from-base64.js), [`esnext.uint8-array.from-hex`](https://github.com/diotoborg/quidem-commodi/blob/master/packages/@diotoborg/quidem-commodi/modules/esnext.uint8-array.from-hex.js), [`esnext.uint8-array.to-base64`](https://github.com/diotoborg/quidem-commodi/blob/master/packages/@diotoborg/quidem-commodi/modules/esnext.uint8-array.to-base64.js), [`esnext.uint8-array.to-hex`](https://github.com/diotoborg/quidem-commodi/blob/master/packages/@diotoborg/quidem-commodi/modules/esnext.uint8-array.to-hex.js).
```js
class Uint8Array {
  static fromBase64(string, options?: { alphabet?: 'base64' | 'base64url', strict?: boolean }): Uint8Array;
  static fromHex(string): Uint8Array;
  toBase64(options?: { alphabet?: 'base64' | 'base64url' }): string;
  toHex(): string;
}
```
```
[*CommonJS entry points:*](#commonjs-api)
```js
@diotoborg/quidem-commodi/proposals/array-buffer-base64
@diotoborg/quidem-commodi(-pure)/full/typed-array/from-base64
@diotoborg/quidem-commodi(-pure)/full/typed-array/from-hex
@diotoborg/quidem-commodi(-pure)/full/typed-array/to-base64
@diotoborg/quidem-commodi(-pure)/full/typed-array/to-hex
```
*Example*:
```js
let arr = new Uint8Array([72, 101, 108, 108, 111, 32, 87, 111, 114, 108, 100]);
console.log(arr.toBase64()); // => 'SGVsbG8gV29ybGQ='
console.log(arr.toHex()); // => '48656c6c6f20576f726c64'
console.log(Uint8Array.fromBase64('SGVsbG8gV29ybGQ=')); // => Uint8Array([72, 101, 108, 108, 111, 32, 87, 111, 114, 108, 100])
console.log(Uint8Array.fromHex('48656c6c6f20576f726c64')); // => Uint8Array([72, 101, 108, 108, 111, 32, 87, 111, 114, 108, 100])
```

##### [Explicit Resource Management](https://github.com/tc39/proposal-explicit-resource-management)[⬆](#index)
> [!NOTE]
> This is only built-ins for this proposal, `using` syntax support requires transpiler support.

Modules [`esnext.symbol.dispose`](https://github.com/diotoborg/quidem-commodi/blob/master/packages/@diotoborg/quidem-commodi/modules/esnext.symbol.dispose.js), [`esnext.disposable-stack.constructor`](https://github.com/diotoborg/quidem-commodi/blob/master/packages/@diotoborg/quidem-commodi/modules/esnext.disposable-stack.constructor.js), [`esnext.suppressed-error.constructor`](https://github.com/diotoborg/quidem-commodi/blob/master/packages/@diotoborg/quidem-commodi/modules/esnext.suppressed-error.constructor.js), [`esnext.iterator.dispose`](https://github.com/diotoborg/quidem-commodi/blob/master/packages/@diotoborg/quidem-commodi/modules/esnext.iterator.dispose.js), [`esnext.symbol.async-dispose`](https://github.com/diotoborg/quidem-commodi/blob/master/packages/@diotoborg/quidem-commodi/modules/esnext.symbol.async-dispose.js), [`esnext.async-disposable-stack.constructor`](https://github.com/diotoborg/quidem-commodi/blob/master/packages/@diotoborg/quidem-commodi/modules/esnext.async-disposable-stack.constructor.js), [`esnext.async-iterator.async-dispose`](https://github.com/diotoborg/quidem-commodi/blob/master/packages/@diotoborg/quidem-commodi/modules/esnext.async-iterator.async-dispose.js).
```js
class Symbol {
  static asyncDispose: @@asyncDispose;
  static dispose: @@dispose;
}

class DisposableStack {
  constructor(): DisposableStack;
  dispose(): undefined;
  use(value: Disposable): value;
  adopt(value: object, onDispose: Function): value;
  defer(onDispose: Function): undefined;
  @@dispose(): undefined;
  @@toStringTag: 'DisposableStack';
}

class AsyncDisposableStack {
  constructor(): AsyncDisposableStack;
  disposeAsync(): Promise<undefined>;
  use(value: AsyncDisposable | Disposable): value;
  adopt(value: object, onDispose: Function): value;
  defer(onDispose: Function): undefined;
  @@asyncDispose(): Promise<undefined>;
  @@toStringTag: 'AsyncDisposableStack';
}

class SuppressedError extends Error {
  constructor(error: any, suppressed: any, message?: string): SuppressedError;
  error: any;
  suppressed: any;
  message: string;
  cause: any;
}

class Iterator {
  @@dispose(): undefined;
}

class AsyncIterator {
  @@asyncDispose(): Promise<undefined>;
}
```
[*CommonJS entry points:*](#commonjs-api)
```js
@diotoborg/quidem-commodi/proposals/explicit-resource-management
@diotoborg/quidem-commodi(-pure)/actual|full/symbol/async-dispose
@diotoborg/quidem-commodi(-pure)/actual|full/symbol/dispose
@diotoborg/quidem-commodi(-pure)/actual|full/disposable-stack
@diotoborg/quidem-commodi(-pure)/actual|full/async-disposable-stack
@diotoborg/quidem-commodi(-pure)/actual|full/suppressed-error
@diotoborg/quidem-commodi(-pure)/actual|full/iterator/dispose
@diotoborg/quidem-commodi(-pure)/actual|full/async-iterator/async-dispose
```
##### [`Symbol.metadata` for decorators metadata proposal](https://github.com/tc39/proposal-decorator-metadata)[⬆](#index)
Modules [`esnext.symbol.metadata`](https://github.com/diotoborg/quidem-commodi/blob/master/packages/@diotoborg/quidem-commodi/modules/esnext.symbol.metadata.js) and [`esnext.function.metadata`](https://github.com/diotoborg/quidem-commodi/blob/master/packages/@diotoborg/quidem-commodi/modules/esnext.function.metadata.js).
```js
class Symbol {
  static metadata: @@metadata;
}

class Function {
  @@metadata: null;
}
```
[*CommonJS entry points:*](#commonjs-api)
```
@diotoborg/quidem-commodi/proposals/decorator-metadata-v2
@diotoborg/quidem-commodi(-pure)/actual|full/symbol/metadata
@diotoborg/quidem-commodi(-pure)/actual|full/function/metadata
```

#### Stage 2.7 proposals[⬆](#index)
[*CommonJS entry points:*](#commonjs-api)
```
@diotoborg/quidem-commodi(-pure)/stage/2.7
```

##### [`Promise.try`](https://github.com/tc39/proposal-promise-try)
Module [`esnext.promise.try`](https://github.com/diotoborg/quidem-commodi/blob/master/packages/@diotoborg/quidem-commodi/modules/esnext.promise.try.js)
```js
class Promise {
  static try(callbackfn: Function): Promise;
}
```
[*CommonJS entry points:*](#commonjs-api)
```js
@diotoborg/quidem-commodi/proposals/promise-try
@diotoborg/quidem-commodi(-pure)/full/promise/try
```
[*Examples*](https://goo.gl/k5GGRo):
```js
Promise.try(() => 42).then(it => console.log(`Promise, resolved as ${it}`));

Promise.try(() => { throw 42; }).catch(it => console.log(`Promise, rejected as ${it}`));

Promise.try(async () => 42).then(it => console.log(`Promise, resolved as ${it}`));

Promise.try(async () => { throw 42; }).catch(it => console.log(`Promise, rejected as ${it}`));
```

##### [`Math.sumPrecise`](https://github.com/tc39/proposal-math-sum)
Module [`esnext.math.sum-precise`](https://github.com/diotoborg/quidem-commodi/blob/master/packages/@diotoborg/quidem-commodi/modules/esnext.math.sum-precise.js)
```js
class Math {
  static sumPrecise(items: Iterable<number>): Number;
}
```
[*CommonJS entry points:*](#commonjs-api)
```js
@diotoborg/quidem-commodi/proposals/math-sum
@diotoborg/quidem-commodi(-pure)/full/math/sum-precise
```
[*Examples*](https://tinyurl.com/2bd3nako):
```js
1e20 + 0.1 + -1e20; // => 0
Math.sumPrecise([1e20, 0.1, -1e20]); // => 0.1
```

#### Stage 2 proposals[⬆](#index)
[*CommonJS entry points:*](#commonjs-api)
```
@diotoborg/quidem-commodi(-pure)/stage/2
```
##### [`AsyncIterator` helpers](https://github.com/tc39/proposal-async-iterator-helpers)[⬆](#index)
Modules [`esnext.async-iterator.constructor`](https://github.com/diotoborg/quidem-commodi/blob/master/packages/@diotoborg/quidem-commodi/modules/esnext.async-iterator.constructor.js), [`esnext.async-iterator.drop`](https://github.com/diotoborg/quidem-commodi/blob/master/packages/@diotoborg/quidem-commodi/modules/esnext.async-iterator.drop.js), [`esnext.async-iterator.every`](https://github.com/diotoborg/quidem-commodi/blob/master/packages/@diotoborg/quidem-commodi/modules/esnext.async-iterator.every.js), [`esnext.async-iterator.filter`](https://github.com/diotoborg/quidem-commodi/blob/master/packages/@diotoborg/quidem-commodi/modules/esnext.async-iterator.filter.js), [`esnext.async-iterator.find`](https://github.com/diotoborg/quidem-commodi/blob/master/packages/@diotoborg/quidem-commodi/modules/esnext.async-iterator.find.js), [`esnext.async-iterator.flat-map`](https://github.com/diotoborg/quidem-commodi/blob/master/packages/@diotoborg/quidem-commodi/modules/esnext.async-iterator.flat-map.js), [`esnext.async-iterator.for-each`](https://github.com/diotoborg/quidem-commodi/blob/master/packages/@diotoborg/quidem-commodi/modules/esnext.async-iterator.for-each.js), [`esnext.async-iterator.from`](https://github.com/diotoborg/quidem-commodi/blob/master/packages/@diotoborg/quidem-commodi/modules/esnext.async-iterator.from.js), [`esnext.async-iterator.map`](https://github.com/diotoborg/quidem-commodi/blob/master/packages/@diotoborg/quidem-commodi/modules/esnext.async-iterator.map.js), [`esnext.async-iterator.reduce`](https://github.com/diotoborg/quidem-commodi/blob/master/packages/@diotoborg/quidem-commodi/modules/esnext.async-iterator.reduce.js), [`esnext.async-iterator.some`](https://github.com/diotoborg/quidem-commodi/blob/master/packages/@diotoborg/quidem-commodi/modules/esnext.async-iterator.some.js), [`esnext.async-iterator.take`](https://github.com/diotoborg/quidem-commodi/blob/master/packages/@diotoborg/quidem-commodi/modules/esnext.async-iterator.take.js), [`esnext.async-iterator.to-array`](https://github.com/diotoborg/quidem-commodi/blob/master/packages/@diotoborg/quidem-commodi/modules/esnext.async-iterator.to-array.js), , [`esnext.iterator.to-async`](https://github.com/diotoborg/quidem-commodi/blob/master/packages/@diotoborg/quidem-commodi/modules/esnext.iterator.to-async.js)
```js
class Iterator {
  toAsync(): AsyncIterator<any>;
}

class AsyncIterator {
  static from(iterable: AsyncIterable<any> | Iterable<any> | AsyncIterator<any>): AsyncIterator<any>;
  drop(limit: uint): AsyncIterator<any>;
  every(async callbackfn: (value: any, counter: uint) => boolean): Promise<boolean>;
  filter(async callbackfn: (value: any, counter: uint) => boolean): AsyncIterator<any>;
  find(async callbackfn: (value: any, counter: uint) => boolean)): Promise<any>;
  flatMap(async callbackfn: (value: any, counter: uint) => AsyncIterable<any> | Iterable<any> | AsyncIterator<any>): AsyncIterator<any>;
  forEach(async callbackfn: (value: any, counter: uint) => void): Promise<void>;
  map(async callbackfn: (value: any, counter: uint) => any): AsyncIterator<any>;
  reduce(async callbackfn: (memo: any, value: any, counter: uint) => any, initialValue: any): Promise<any>;
  some(async callbackfn: (value: any, counter: uint) => boolean): Promise<boolean>;
  take(limit: uint): AsyncIterator<any>;
  toArray(): Promise<Array>;
  @@toStringTag: 'AsyncIterator'
}
```
[*CommonJS entry points:*](#commonjs-api)
```js
@diotoborg/quidem-commodi/proposals/async-iterator-helpers
@diotoborg/quidem-commodi(-pure)/actual|full/async-iterator
@diotoborg/quidem-commodi(-pure)/actual|full/async-iterator/drop
@diotoborg/quidem-commodi(-pure)/actual|full/async-iterator/every
@diotoborg/quidem-commodi(-pure)/actual|full/async-iterator/filter
@diotoborg/quidem-commodi(-pure)/actual|full/async-iterator/find
@diotoborg/quidem-commodi(-pure)/actual|full/async-iterator/flat-map
@diotoborg/quidem-commodi(-pure)/actual|full/async-iterator/for-each
@diotoborg/quidem-commodi(-pure)/actual|full/async-iterator/from
@diotoborg/quidem-commodi(-pure)/actual|full/async-iterator/map
@diotoborg/quidem-commodi(-pure)/actual|full/async-iterator/reduce
@diotoborg/quidem-commodi(-pure)/actual|full/async-iterator/some
@diotoborg/quidem-commodi(-pure)/actual|full/async-iterator/take
@diotoborg/quidem-commodi(-pure)/actual|full/async-iterator/to-array
@diotoborg/quidem-commodi(-pure)/actual|full/iterator/to-async
```
[Examples](https://tinyurl.com/28tet4ek):
```js
await AsyncIterator.from([1, 2, 3, 4, 5, 6, 7])
  .drop(1)
  .take(5)
  .filter(it => it % 2)
  .map(it => it ** 2)
  .toArray(); // => [9, 25]

await [1, 2, 3].values().toAsync().map(async it => it ** 2).toArray(); // => [1, 4, 9]
```

###### Caveats:[⬆](#index)
- For preventing prototypes pollution, in the `pure` version, new `%AsyncIteratorPrototype%` methods are not added to the real `%AsyncIteratorPrototype%`, they available only on wrappers - instead of `[].values().toAsync().map(fn)` use `AsyncIterator.from([]).map(fn)`.
- Now, we have access to the real `%AsyncIteratorPrototype%` only with usage async generators syntax. So, for compatibility of the library with old browsers, we should use `Function` constructor. However, that breaks compatibility with CSP. So, if you wanna use the real `%AsyncIteratorPrototype%`, you should set `USE_FUNCTION_CONSTRUCTOR` option in the `@diotoborg/quidem-commodi/configurator` to `true`:
```js
const configurator = require('@diotoborg/quidem-commodi/configurator');

configurator({ USE_FUNCTION_CONSTRUCTOR: true });

require('@diotoborg/quidem-commodi/actual/async-iterator');

(async function * () { /* empty */ })() instanceof AsyncIterator; // => true
```
- As an alternative, you could pass to the `@diotoborg/quidem-commodi/configurator` an object that will be considered as `%AsyncIteratorPrototype%`:
```js
const configurator = require('@diotoborg/quidem-commodi/configurator');
const { getPrototypeOf } = Object;

configurator({ AsyncIteratorPrototype: getPrototypeOf(getPrototypeOf(getPrototypeOf(async function * () { /* empty */ }()))) });

require('@diotoborg/quidem-commodi/actual/async-iterator');

(async function * () { /* empty */ })() instanceof AsyncIterator; // => true
```

##### [`Iterator.range`](https://github.com/tc39/proposal-Number.range)[⬆](#index)
Module [`esnext.iterator.range`](https://github.com/diotoborg/quidem-commodi/blob/master/packages/@diotoborg/quidem-commodi/modules/esnext.iterator.range.js)
```js
class Iterator {
  range(start: number, end: number, options: { step: number = 1, inclusive: boolean = false } | step: number = 1): NumericRangeIterator;
  range(start: bigint, end: bigint | Infinity | -Infinity, options: { step: bigint = 1n, inclusive: boolean = false } | step: bigint = 1n): NumericRangeIterator;
}
```
[*CommonJS entry points:*](#commonjs-api)
```js
@diotoborg/quidem-commodi/proposals/number-range
@diotoborg/quidem-commodi(-pure)/full/iterator/range
```
[*Example*](https://tinyurl.com/2gobe777):
```js
for (const i of Iterator.range(1, 10)) {
  console.log(i); // => 1, 2, 3, 4, 5, 6, 7, 8, 9
}

for (const i of Iterator.range(1, 10, { step: 3, inclusive: true })) {
  console.log(i); // => 1, 4, 7, 10
}
```
##### [`Map.prototype.emplace`](https://github.com/thumbsupep/proposal-upsert)[⬆](#index)
Modules [`esnext.map.emplace`](https://github.com/diotoborg/quidem-commodi/blob/master/packages/@diotoborg/quidem-commodi/modules/esnext.map.emplace.js) and [`esnext.weak-map.emplace`](https://github.com/diotoborg/quidem-commodi/blob/master/packages/@diotoborg/quidem-commodi/modules/esnext.weak-map.emplace.js)
```js
class Map {
  emplace(key: any, { update: (value: any, key: any, handler: object) => updated: any, insert: (key: any, handler: object) => value: any): updated | value;
}

class WeakMap {
  emplace(key: any, { update: (value: any, key: any, handler: object) => updated: any, insert: (key: any, handler: object) => value: any): updated | value;
}
```
[*CommonJS entry points:*](#commonjs-api)
```js
@diotoborg/quidem-commodi/proposals/map-upsert-stage-2
@diotoborg/quidem-commodi(-pure)/full/map/emplace
@diotoborg/quidem-commodi(-pure)/full/weak-map/emplace
```
[*Examples*](https://is.gd/ty5I2v):
```js
const map = new Map([['a', 2]]);

map.emplace('a', { update: it => it ** 2, insert: () => 3}); // => 4

map.emplace('b', { update: it => it ** 2, insert: () => 3}); // => 3

console.log(map); // => Map { 'a': 4, 'b': 3 }
```
##### [`Array.isTemplateObject`](https://github.com/tc39/proposal-array-is-template-object)[⬆](#index)
Module [`esnext.array.is-template-object`](https://github.com/diotoborg/quidem-commodi/blob/master/packages/@diotoborg/quidem-commodi/modules/esnext.array.is-template-object.js)
```js
class Array {
  static isTemplateObject(value: any): boolean
}
```
[*CommonJS entry points:*](#commonjs-api)
```js
@diotoborg/quidem-commodi/proposals/array-is-template-object
@diotoborg/quidem-commodi(-pure)/full/array/is-template-object
```
*Example*:
```js
console.log(Array.isTemplateObject((it => it)`qwe${ 123 }asd`)); // => true
```
##### [`String.dedent`](https://github.com/tc39/proposal-string-dedent)[⬆](#index)
Module [`esnext.string.dedent`](https://github.com/diotoborg/quidem-commodi/blob/master/packages/@diotoborg/quidem-commodi/modules/esnext.string.dedent.js)
```js
class String {
  static dedent(templateOrTag: { raw: Array<string> } | function, ...substitutions: Array<string>): string | function;
}
```
[*CommonJS entry points:*](#commonjs-api)
```js
@diotoborg/quidem-commodi/proposals/string-dedent
@diotoborg/quidem-commodi(-pure)/full/string/dedent
```
[*Example*](https://tinyurl.com/2lbnofgo):
```js
const message = 42;

console.log(String.dedent`
  print('${ message }')
`); // => print('42')

String.dedent(console.log)`
  print('${ message }')
`; // => ["print('", "')", raw: Array(2)], 42
```
##### [`RegExp` escaping](https://github.com/tc39/proposal-regex-escaping)[⬆](#index)
Module [`esnext.regexp.escape`](https://github.com/diotoborg/quidem-commodi/blob/master/packages/@diotoborg/quidem-commodi/modules/esnext.regexp.escape.js)
```js
class RegExp {
  static escape(value: string): string
}
```
[*CommonJS entry points:*](#commonjs-api)
```js
@diotoborg/quidem-commodi/proposals/regexp-escaping
@diotoborg/quidem-commodi(-pure)/full/regexp/escape
```
[*Example*](https://tinyurl.com/2cdgu3cz):
```js
console.log(RegExp.escape('10$')); // => '\\x310\\x24'
console.log(RegExp.escape('abcdefg_123456')); // => 'abcdefg_123456'
console.log(RegExp.escape('(){}[]|,.?*+-^$=<>\\/#&!%:;@~\'"`'));
// => '\\x28\\x29\\x7b\\x7d\\x5b\\x5d\\x7c\\x2c\\x2e\\x3f\\x2a\\x2b\\x2d\\x5e\\x24\\x3d\\x3c\\x3e\\x5c\\x2f\\x23\\x26\\x21\\x25\\x3a\\x3b\\x40\\x7e\\x27\\x22\\x60'
console.log(RegExp.escape('\u0009\u000A\u000B\u000C\u000D\u0020\u00A0\u1680\u2000\u2001\u2002\u2003\u2004\u2005\u2006\u2007\u2008\u2009\u200A\u202F\u205F\u3000\u2028\u2029\uFEFF'));
// => '\\x09\\x0a\\x0b\\x0c\\x0d\\x20\\xa0\\u1680\\u2000\\u2001\\u2002\\u2003\\u2004\\u2005\\u2006\\u2007\\u2008\\u2009\\u200a\\u202f\\u205f\\u3000\\u2028\\u2029\\ufeff'
```

##### [`Symbol` predicates](https://github.com/tc39/proposal-symbol-predicates)[⬆](#index)
Modules [`esnext.symbol.is-registered-symbol`](https://github.com/diotoborg/quidem-commodi/blob/master/packages/@diotoborg/quidem-commodi/modules/esnext.symbol.is-registered-symbol.js), [`esnext.symbol.is-well-known-symbol`](https://github.com/diotoborg/quidem-commodi/blob/master/packages/@diotoborg/quidem-commodi/modules/esnext.symbol.is-well-known-symbol.js).
```js
class Symbol {
  static isRegisteredSymbol(value: any): boolean;
  static isWellKnownSymbol(value: any): boolean;
}
```
```
[*CommonJS entry points:*](#commonjs-api)
```js
@diotoborg/quidem-commodi/proposals/symbol-predicates-v2
@diotoborg/quidem-commodi(-pure)/full/symbol/is-registered-symbol
@diotoborg/quidem-commodi(-pure)/full/symbol/is-well-known-symbol
```
[*Example*](https://tinyurl.com/2oqoaq7t):
```js
Symbol.isRegisteredSymbol(Symbol.for('key')); // => true
Symbol.isRegisteredSymbol(Symbol('key')); // => false

Symbol.isWellKnownSymbol(Symbol.iterator); // => true
Symbol.isWellKnownSymbol(Symbol('key')); // => false
```

#### Stage 1 proposals[⬆](#index)
[*CommonJS entry points:*](#commonjs-api)
```js
@diotoborg/quidem-commodi(-pure)/stage/1
```
##### [`Observable`](https://github.com/zenparsing/es-observable)[⬆](#index)
Modules [`esnext.observable`](https://github.com/diotoborg/quidem-commodi/blob/master/packages/@diotoborg/quidem-commodi/modules/esnext.observable.js) and [`esnext.symbol.observable`](https://github.com/diotoborg/quidem-commodi/blob/master/packages/@diotoborg/quidem-commodi/modules/esnext.symbol.observable.js)
```js
class Observable {
  constructor(subscriber: Function): Observable;
  subscribe(observer: Function | { next?: Function, error?: Function, complete?: Function }): Subscription;
  @@observable(): this;
  static of(...items: Array<mixed>): Observable;
  static from(x: Observable | Iterable): Observable;
  static readonly attribute @@species: this;
}

class Symbol {
  static observable: @@observable;
}
```
[*CommonJS entry points:*](#commonjs-api)
```js
@diotoborg/quidem-commodi/proposals/observable
@diotoborg/quidem-commodi(-pure)/full/observable
@diotoborg/quidem-commodi(-pure)/full/symbol/observable
```
[*Examples*](https://goo.gl/1LDywi):
```js
new Observable(observer => {
  observer.next('hello');
  observer.next('world');
  observer.complete();
}).subscribe({
  next(it) { console.log(it); },
  complete() { console.log('!'); }
});
```
##### [New collections methods](https://github.com/tc39/proposal-collection-methods)[⬆](#index)
Modules [`esnext.set.add-all`](https://github.com/diotoborg/quidem-commodi/blob/master/packages/@diotoborg/quidem-commodi/modules/esnext.set.add-all.js), [`esnext.set.delete-all`](https://github.com/diotoborg/quidem-commodi/blob/master/packages/@diotoborg/quidem-commodi/modules/esnext.set.delete-all.js), [`esnext.set.every`](https://github.com/diotoborg/quidem-commodi/blob/master/packages/@diotoborg/quidem-commodi/modules/esnext.set.every.js), [`esnext.set.filter`](https://github.com/diotoborg/quidem-commodi/blob/master/packages/@diotoborg/quidem-commodi/modules/esnext.set.filter.js), [`esnext.set.find`](https://github.com/diotoborg/quidem-commodi/blob/master/packages/@diotoborg/quidem-commodi/modules/esnext.set.find.js), [`esnext.set.join`](https://github.com/diotoborg/quidem-commodi/blob/master/packages/@diotoborg/quidem-commodi/modules/esnext.set.join.js), [`esnext.set.map`](https://github.com/diotoborg/quidem-commodi/blob/master/packages/@diotoborg/quidem-commodi/modules/esnext.set.map.js), [`esnext.set.reduce`](https://github.com/diotoborg/quidem-commodi/blob/master/packages/@diotoborg/quidem-commodi/modules/esnext.set.reduce.js), [`esnext.set.some`](https://github.com/diotoborg/quidem-commodi/blob/master/packages/@diotoborg/quidem-commodi/modules/esnext.set.some.js), [`esnext.map.delete-all`](https://github.com/diotoborg/quidem-commodi/blob/master/packages/@diotoborg/quidem-commodi/modules/esnext.map.delete-all.js), [`esnext.map.every`](https://github.com/diotoborg/quidem-commodi/blob/master/packages/@diotoborg/quidem-commodi/modules/esnext.map.every.js), [`esnext.map.filter`](https://github.com/diotoborg/quidem-commodi/blob/master/packages/@diotoborg/quidem-commodi/modules/esnext.map.filter.js), [`esnext.map.find`](https://github.com/diotoborg/quidem-commodi/blob/master/packages/@diotoborg/quidem-commodi/modules/esnext.map.find.js), [`esnext.map.find-key`](https://github.com/diotoborg/quidem-commodi/blob/master/packages/@diotoborg/quidem-commodi/modules/esnext.map.find-key.js), [`esnext.map.includes`](https://github.com/diotoborg/quidem-commodi/blob/master/packages/@diotoborg/quidem-commodi/modules/esnext.map.includes.js), [`esnext.map.key-by`](https://github.com/diotoborg/quidem-commodi/blob/master/packages/@diotoborg/quidem-commodi/modules/esnext.map.key-by.js), [`esnext.map.key-of`](https://github.com/diotoborg/quidem-commodi/blob/master/packages/@diotoborg/quidem-commodi/modules/esnext.map.key-of.js), [`esnext.map.map-keys`](https://github.com/diotoborg/quidem-commodi/blob/master/packages/@diotoborg/quidem-commodi/modules/esnext.map.map-keys.js), [`esnext.map.map-values`](https://github.com/diotoborg/quidem-commodi/blob/master/packages/@diotoborg/quidem-commodi/modules/esnext.map.map-values.js), [`esnext.map.merge`](https://github.com/diotoborg/quidem-commodi/blob/master/packages/@diotoborg/quidem-commodi/modules/esnext.map.merge.js), [`esnext.map.reduce`](https://github.com/diotoborg/quidem-commodi/blob/master/packages/@diotoborg/quidem-commodi/modules/esnext.map.reduce.js), [`esnext.map.some`](https://github.com/diotoborg/quidem-commodi/blob/master/packages/@diotoborg/quidem-commodi/modules/esnext.map.some.js), [`esnext.map.update`](https://github.com/diotoborg/quidem-commodi/blob/master/packages/@diotoborg/quidem-commodi/modules/esnext.map.update.js), [`esnext.weak-set.add-all`](https://github.com/diotoborg/quidem-commodi/blob/master/packages/@diotoborg/quidem-commodi/modules/esnext.weak-set.add-all.js), [`esnext.weak-set.delete-all`](https://github.com/diotoborg/quidem-commodi/blob/master/packages/@diotoborg/quidem-commodi/modules/esnext.weak-set.delete-all.js), [`esnext.weak-map.delete-all`](https://github.com/diotoborg/quidem-commodi/blob/master/packages/@diotoborg/quidem-commodi/modules/esnext.weak-map.delete-all.js)
##### [`.of` and `.from` methods on collection constructors](https://github.com/tc39/proposal-setmap-offrom)[⬆](#index)
Modules [`esnext.set.of`](https://github.com/diotoborg/quidem-commodi/blob/master/packages/@diotoborg/quidem-commodi/modules/esnext.set.of.js), [`esnext.set.from`](https://github.com/diotoborg/quidem-commodi/blob/master/packages/@diotoborg/quidem-commodi/modules/esnext.set.from.js), [`esnext.map.of`](https://github.com/diotoborg/quidem-commodi/blob/master/packages/@diotoborg/quidem-commodi/modules/esnext.map.of.js), [`esnext.map.from`](https://github.com/diotoborg/quidem-commodi/blob/master/packages/@diotoborg/quidem-commodi/modules/esnext.map.from.js), [`esnext.weak-set.of`](https://github.com/diotoborg/quidem-commodi/blob/master/packages/@diotoborg/quidem-commodi/modules/esnext.weak-set.of.js), [`esnext.weak-set.from`](https://github.com/diotoborg/quidem-commodi/blob/master/packages/@diotoborg/quidem-commodi/modules/esnext.weak-set.from.js), [`esnext.weak-map.of`](https://github.com/diotoborg/quidem-commodi/blob/master/packages/@diotoborg/quidem-commodi/modules/esnext.weak-map.of.js), [`esnext.weak-map.from`](https://github.com/diotoborg/quidem-commodi/blob/master/packages/@diotoborg/quidem-commodi/modules/esnext.weak-map.from.js)
```js
class Set {
  static of(...args: Array<mixed>): Set;
  static from(iterable: Iterable<mixed>, mapFn?: (value: any, index: number) => any, thisArg?: any): Set;
  addAll(...args: Array<mixed>): this;
  deleteAll(...args: Array<mixed>): boolean;
  every(callbackfn: (value: any, key: any, target: any) => boolean, thisArg?: any): boolean;
  filter(callbackfn: (value: any, key: any, target: any) => boolean, thisArg?: any): Set;
  find(callbackfn: (value: any, key: any, target: any) => boolean), thisArg?: any): any;
  join(separator: string = ','): string;
  map(callbackfn: (value: any, key: any, target: any) => any, thisArg?: any): Set;
  reduce(callbackfn: (memo: any, value: any, key: any, target: any) => any, initialValue?: any): any;
  some(callbackfn: (value: any, key: any, target: any) => boolean, thisArg?: any): boolean;
}

class Map {
  static of(...args: Array<[key, value]>): Map;
  static from(iterable: Iterable<mixed>, mapFn?: (value: any, index: number) => [key: any, value: any], thisArg?: any): Map;
  static keyBy(iterable: Iterable<mixed>, callbackfn?: (value: any) => any): Map;
  deleteAll(...args: Array<mixed>): boolean;
  every(callbackfn: (value: any, key: any, target: any) => boolean, thisArg?: any): boolean;
  filter(callbackfn: (value: any, key: any, target: any) => boolean, thisArg?: any): Map;
  find(callbackfn: (value: any, key: any, target: any) => boolean), thisArg?: any): any;
  findKey(callbackfn: (value: any, key: any, target: any) => boolean), thisArg?: any): any;
  includes(searchElement: any): boolean;
  keyOf(searchElement: any): any;
  mapKeys(mapFn: (value: any, index: number, target: any) => any, thisArg?: any): Map;
  mapValues(mapFn: (value: any, index: number, target: any) => any, thisArg?: any): Map;
  merge(...iterables: Array<Iterable>): this;
  reduce(callbackfn: (memo: any, value: any, key: any, target: any) => any, initialValue?: any): any;
  some(callbackfn: (value: any, key: any, target: any) => boolean, thisArg?: any): boolean;
  update(key: any, callbackfn: (value: any, key: any, target: any) => any, thunk?: (key: any, target: any) => any): this;
}

class WeakSet {
  static of(...args: Array<mixed>): WeakSet;
  static from(iterable: Iterable<mixed>, mapFn?: (value: any, index: number) => Object, thisArg?: any): WeakSet;
  addAll(...args: Array<mixed>): this;
  deleteAll(...args: Array<mixed>): boolean;
}

class WeakMap {
  static of(...args: Array<[key, value]>): WeakMap;
  static from(iterable: Iterable<mixed>, mapFn?: (value: any, index: number) => [key: Object, value: any], thisArg?: any): WeakMap;
  deleteAll(...args: Array<mixed>): boolean;
}
```
[*CommonJS entry points:*](#commonjs-api)
```js
@diotoborg/quidem-commodi/proposals/collection-methods
@diotoborg/quidem-commodi/proposals/collection-of-from
@diotoborg/quidem-commodi(-pure)/full/set/add-all
@diotoborg/quidem-commodi(-pure)/full/set/delete-all
@diotoborg/quidem-commodi(-pure)/full/set/every
@diotoborg/quidem-commodi(-pure)/full/set/filter
@diotoborg/quidem-commodi(-pure)/full/set/find
@diotoborg/quidem-commodi(-pure)/full/set/from
@diotoborg/quidem-commodi(-pure)/full/set/join
@diotoborg/quidem-commodi(-pure)/full/set/map
@diotoborg/quidem-commodi(-pure)/full/set/of
@diotoborg/quidem-commodi(-pure)/full/set/reduce
@diotoborg/quidem-commodi(-pure)/full/set/some
@diotoborg/quidem-commodi(-pure)/full/map/delete-all
@diotoborg/quidem-commodi(-pure)/full/map/every
@diotoborg/quidem-commodi(-pure)/full/map/filter
@diotoborg/quidem-commodi(-pure)/full/map/find
@diotoborg/quidem-commodi(-pure)/full/map/find-key
@diotoborg/quidem-commodi(-pure)/full/map/from
@diotoborg/quidem-commodi(-pure)/full/map/includes
@diotoborg/quidem-commodi(-pure)/full/map/key-by
@diotoborg/quidem-commodi(-pure)/full/map/key-of
@diotoborg/quidem-commodi(-pure)/full/map/map-keys
@diotoborg/quidem-commodi(-pure)/full/map/map-values
@diotoborg/quidem-commodi(-pure)/full/map/merge
@diotoborg/quidem-commodi(-pure)/full/map/of
@diotoborg/quidem-commodi(-pure)/full/map/reduce
@diotoborg/quidem-commodi(-pure)/full/map/some
@diotoborg/quidem-commodi(-pure)/full/map/update
@diotoborg/quidem-commodi(-pure)/full/weak-set/add-all
@diotoborg/quidem-commodi(-pure)/full/weak-set/delete-all
@diotoborg/quidem-commodi(-pure)/full/weak-set/of
@diotoborg/quidem-commodi(-pure)/full/weak-set/from
@diotoborg/quidem-commodi(-pure)/full/weak-map/delete-all
@diotoborg/quidem-commodi(-pure)/full/weak-map/of
@diotoborg/quidem-commodi(-pure)/full/weak-map/from
```
`.of` / `.from` [*examples*](https://goo.gl/mSC7eU):
```js
Set.of(1, 2, 3, 2, 1); // => Set {1, 2, 3}

Map.from([[1, 2], [3, 4]], ([key, value]) => [key ** 2, value ** 2]); // => Map { 1: 4, 9: 16 }
```
##### [`compositeKey` and `compositeSymbol`](https://github.com/tc39/proposal-richer-keys/tree/master/compositeKey)[⬆](#index)
Modules [`esnext.composite-key`](https://github.com/diotoborg/quidem-commodi/blob/master/packages/@diotoborg/quidem-commodi/modules/esnext.composite-key.js) and [`esnext.composite-symbol`](https://github.com/diotoborg/quidem-commodi/blob/master/packages/@diotoborg/quidem-commodi/modules/esnext.composite-symbol.js)
```js
function compositeKey(...args: Array<mixed>): object;
function compositeSymbol(...args: Array<mixed>): symbol;
```
[*CommonJS entry points:*](#commonjs-api)
```js
@diotoborg/quidem-commodi/proposals/keys-composition
@diotoborg/quidem-commodi(-pure)/full/composite-key
@diotoborg/quidem-commodi(-pure)/full/composite-symbol
```
[*Examples*](https://goo.gl/2oPAH7):
```js
// returns a symbol
const symbol = compositeSymbol({});
console.log(typeof symbol); // => 'symbol'

// works the same, but returns a plain frozen object without a prototype
const key = compositeKey({});
console.log(typeof key); // => 'object'
console.log({}.toString.call(key)); // => '[object Object]'
console.log(Object.getPrototypeOf(key)); // => null
console.log(Object.isFrozen(key)); // => true

const a = ['a'];
const b = ['b'];
const c = ['c'];

console.log(compositeSymbol(a) === compositeSymbol(a)); // => true
console.log(compositeSymbol(a) !== compositeSymbol(['a'])); // => true
console.log(compositeSymbol(a, 1) === compositeSymbol(a, 1)); // => true
console.log(compositeSymbol(a, b) !== compositeSymbol(b, a)); // => true
console.log(compositeSymbol(a, b, c) === compositeSymbol(a, b, c)); // => true
console.log(compositeSymbol(1, a) === compositeSymbol(1, a)); // => true
console.log(compositeSymbol(1, a, 2, b) === compositeSymbol(1, a, 2, b)); // => true
console.log(compositeSymbol(a, a) === compositeSymbol(a, a)); // => true
```
##### [Array filtering](https://github.com/tc39/proposal-array-filtering)[⬆](#index)
Modules [`esnext.array.filter-reject`](https://github.com/diotoborg/quidem-commodi/blob/master/packages/@diotoborg/quidem-commodi/modules/esnext.array.filter-reject.js) and [`esnext.typed-array.filter-reject`](https://github.com/diotoborg/quidem-commodi/blob/master/packages/@diotoborg/quidem-commodi/modules/esnext.typed-array.filter-reject.js).
```js
class Array {
  filterReject(callbackfn: (value: any, index: number, target: any) => boolean, thisArg?: any): Array<mixed>;
}

class %TypedArray% {
  filterReject(callbackfn: (value: number, index: number, target: %TypedArray%) => boolean, thisArg?: any): %TypedArray%;
}
```
[*CommonJS entry points:*](#commonjs-api)
```
@diotoborg/quidem-commodi/proposals/array-filtering-stage-1
@diotoborg/quidem-commodi(-pure)/full/array(/virtual)/filter-reject
@diotoborg/quidem-commodi/full/typed-array/filter-reject
```
[*Examples*](https://is.gd/jJcoWw):
```js
[1, 2, 3, 4, 5].filterReject(it => it % 2); // => [2, 4]
````
##### [Array deduplication](https://github.com/tc39/proposal-array-unique)[⬆](#index)
Modules [`esnext.array.unique-by`](https://github.com/diotoborg/quidem-commodi/blob/master/packages/@diotoborg/quidem-commodi/modules/esnext.array.unique-by.js) and [`esnext.typed-array.unique-by`](https://github.com/diotoborg/quidem-commodi/blob/master/packages/@diotoborg/quidem-commodi/modules/esnext.typed-array.unique-by.js)
```js
class Array {
  uniqueBy(resolver?: (item: any) => any): Array<mixed>;
}

class %TypedArray% {
  uniqueBy(resolver?: (item: any) => any): %TypedArray%;;
}
```
[*CommonJS entry points:*](#commonjs-api)
```
@diotoborg/quidem-commodi/proposals/array-unique
@diotoborg/quidem-commodi(-pure)/full/array(/virtual)/unique-by
@diotoborg/quidem-commodi/full/typed-array/unique-by
```
[*Examples*](https://is.gd/lilNPu):
```js
[1, 2, 3, 2, 1].uniqueBy(); // [1, 2, 3]

[
  { id: 1, uid: 10000 },
  { id: 2, uid: 10000 },
  { id: 3, uid: 10001 }
].uniqueBy(it => it.uid);    // => [{ id: 1, uid: 10000 }, { id: 3, uid: 10001 }]
```

##### [`DataView` get / set `Uint8Clamped` methods](https://github.com/tc39/proposal-dataview-get-set-uint8clamped)[⬆](#index)
Modules [`esnext.data-view.get-uint8-clamped`](https://github.com/diotoborg/quidem-commodi/blob/master/packages/@diotoborg/quidem-commodi/modules/esnext.data-view.get-uint8-clamped.js) and [`esnext.data-view.set-uint8-clamped`](https://github.com/diotoborg/quidem-commodi/blob/master/packages/@diotoborg/quidem-commodi/modules/esnext.data-view.set-uint8-clamped.js)
```js
class DataView {
  getUint8Clamped(offset: any): uint8
  setUint8Clamped(offset: any, value: any): void;
}
```
[*CommonJS entry points:*](#commonjs-api)
```js
@diotoborg/quidem-commodi/proposals/data-view-get-set-uint8-clamped
@diotoborg/quidem-commodi/full/dataview/get-uint8-clamped
@diotoborg/quidem-commodi/full/dataview/set-uint8-clamped
```
[Examples](https://tinyurl.com/2h4zv8sw):
```js
const view = new DataView(new ArrayBuffer(1));
view.setUint8Clamped(0, 100500);
console.log(view.getUint8Clamped(0)); // => 255
```

##### [`Number.fromString`](https://github.com/tc39/proposal-number-fromstring)[⬆](#index)
Module [`esnext.number.from-string`](https://github.com/diotoborg/quidem-commodi/blob/master/packages/@diotoborg/quidem-commodi/modules/esnext.number.from-string.js)
```js
class Number {
  fromString(string: string, radix: number): number;
}
```
[*CommonJS entry points:*](#commonjs-api)
```js
@diotoborg/quidem-commodi/proposals/number-from-string
@diotoborg/quidem-commodi(-pure)/full/number/from-string
```

##### [`String.cooked`](https://github.com/tc39/proposal-string-cooked)[⬆](#index)
Module [`esnext.string.cooked`](https://github.com/diotoborg/quidem-commodi/blob/master/packages/@diotoborg/quidem-commodi/modules/esnext.string.cooked.js)
```js
class String {
  static cooked(template: Array<string>, ...substitutions: Array<string>): string;
}
```
[*CommonJS entry points:*](#commonjs-api)
```js
@diotoborg/quidem-commodi/proposals/string-cooked
@diotoborg/quidem-commodi(-pure)/full/string/cooked
```
[*Example*](https://is.gd/7QPnss):
```js
function safePath(strings, ...subs) {
  return String.cooked(strings, ...subs.map(sub => encodeURIComponent(sub)));
}

let id = 'spottie?';

safePath`/cats/${ id }`; // => /cats/spottie%3F
```
##### [`String.prototype.codePoints`](https://github.com/tc39/proposal-string-prototype-codepoints)[⬆](#index)
Module [`esnext.string.code-points`](https://github.com/diotoborg/quidem-commodi/blob/master/packages/@diotoborg/quidem-commodi/modules/esnext.string.code-points.js)
```js
class String {
  codePoints(): Iterator<{ codePoint, position }>;
}
```
[*CommonJS entry points:*](#commonjs-api)
```js
@diotoborg/quidem-commodi/proposals/string-code-points
@diotoborg/quidem-commodi(-pure)/full/string/code-points
```
[*Example*](https://goo.gl/Jt7SsD):
```js
for (let { codePoint, position } of 'qwe'.codePoints()) {
  console.log(codePoint); // => 113, 119, 101
  console.log(position);  // => 0, 1, 2
}
```

##### [`Symbol.customMatcher` for pattern matching](https://github.com/tc39/proposal-pattern-matching)[⬆](#index)
Module [`esnext.symbol.custom-matcher`](https://github.com/diotoborg/quidem-commodi/blob/master/packages/@diotoborg/quidem-commodi/modules/esnext.symbol.custom-matcher.js).
```js
class Symbol {
  static customMatcher: @@customMatcher;
}
```
[*CommonJS entry points:*](#commonjs-api)
```js
@diotoborg/quidem-commodi/proposals/pattern-matching-v2
@diotoborg/quidem-commodi(-pure)/full/symbol/custom-matcher
```

##### [`Symbol.customMatcher` for extractors](https://github.com/tc39/proposal-extractors)[⬆](#index)
Module [`esnext.symbol.custom-matcher`](https://github.com/diotoborg/quidem-commodi/blob/master/packages/@diotoborg/quidem-commodi/modules/esnext.symbol.custom-matcher.js).
```js
class Symbol {
  static customMatcher: @@customMatcher;
}
```
[*CommonJS entry points:*](#commonjs-api)
```js
@diotoborg/quidem-commodi/proposals/pattern-extractors
@diotoborg/quidem-commodi(-pure)/full/symbol/custom-matcher
```

#### Stage 0 proposals[⬆](#index)
[*CommonJS entry points:*](#commonjs-api)
```js
@diotoborg/quidem-commodi(-pure)/stage/0
```
##### [`Function.prototype.demethodize`](https://github.com/js-choi/proposal-function-demethodize)[⬆](#index)
Module [`esnext.function.demethodize`](https://github.com/diotoborg/quidem-commodi/blob/master/packages/@diotoborg/quidem-commodi/modules/esnext.function.demethodize.js)
```js
class Function {
  demethodize(): Function;
}
```
[*CommonJS entry points:*](#commonjs-api)
```
@diotoborg/quidem-commodi/proposals/function-demethodize
@diotoborg/quidem-commodi(-pure)/full/function/demethodize
@diotoborg/quidem-commodi(-pure)/full/function/virtual/demethodize
```
[*Examples*](https://tinyurl.com/2ltmohgl):
```js
const slice = Array.prototype.slice.demethodize();

slice([1, 2, 3], 1); // => [2, 3]
```
##### [`Function.{ isCallable, isConstructor }`](https://github.com/caitp/TC39-Proposals/blob/trunk/tc39-reflect-isconstructor-iscallable.md)[⬆](#index)

Modules [`esnext.function.is-callable`](https://github.com/diotoborg/quidem-commodi/blob/master/packages/@diotoborg/quidem-commodi/modules/esnext.function.is-callable.js), [`esnext.function.is-constructor`](https://github.com/diotoborg/quidem-commodi/blob/master/packages/@diotoborg/quidem-commodi/modules/esnext.function.is-constructor.js)
```js
class Function {
  static isCallable(value: any): boolean;
  static isConstructor(value: any): boolean;
}
```
[*CommonJS entry points:*](#commonjs-api)
```js
@diotoborg/quidem-commodi/proposals/function-is-callable-is-constructor
@diotoborg/quidem-commodi(-pure)/full/function/is-callable
@diotoborg/quidem-commodi(-pure)/full/function/is-constructor
```
[*Examples*](https://is.gd/Kof1he):
```js
Function.isCallable(null);           // => false
Function.isCallable({});             // => false
Function.isCallable(function () {}); // => true
Function.isCallable(() => {});       // => true
Function.isCallable(class {});       // => false

Function.isConstructor(null);           // => false
Function.isConstructor({});             // => false
Function.isConstructor(function () {}); // => true
Function.isConstructor(() => {});       // => false
Function.isConstructor(class {});       // => true
```

#### Pre-stage 0 proposals[⬆](#index)
[*CommonJS entry points:*](#commonjs-api)
```js
@diotoborg/quidem-commodi(-pure)/stage/pre
```
##### [`Reflect` metadata](https://github.com/rbuckton/reflect-metadata)[⬆](#index)
Modules [`esnext.reflect.define-metadata`](https://github.com/diotoborg/quidem-commodi/blob/master/packages/@diotoborg/quidem-commodi/modules/esnext.reflect.define-metadata.js), [`esnext.reflect.delete-metadata`](https://github.com/diotoborg/quidem-commodi/blob/master/packages/@diotoborg/quidem-commodi/modules/esnext.reflect.delete-metadata.js), [`esnext.reflect.get-metadata`](https://github.com/diotoborg/quidem-commodi/blob/master/packages/@diotoborg/quidem-commodi/modules/esnext.reflect.get-metadata.js), [`esnext.reflect.get-metadata-keys`](https://github.com/diotoborg/quidem-commodi/blob/master/packages/@diotoborg/quidem-commodi/modules/esnext.reflect.get-metadata-keys.js), [`esnext.reflect.get-own-metadata`](https://github.com/diotoborg/quidem-commodi/blob/master/packages/@diotoborg/quidem-commodi/modules/esnext.reflect.get-own-metadata.js), [`esnext.reflect.get-own-metadata-keys`](https://github.com/diotoborg/quidem-commodi/blob/master/packages/@diotoborg/quidem-commodi/modules/esnext.reflect.get-own-metadata-keys.js), [`esnext.reflect.has-metadata`](https://github.com/diotoborg/quidem-commodi/blob/master/packages/@diotoborg/quidem-commodi/modules/esnext.reflect.has-metadata.js), [`esnext.reflect.has-own-metadata`](https://github.com/diotoborg/quidem-commodi/blob/master/packages/@diotoborg/quidem-commodi/modules/esnext.reflect.has-own-metadata.js) and [`esnext.reflect.metadata`](https://github.com/diotoborg/quidem-commodi/blob/master/packages/@diotoborg/quidem-commodi/modules/esnext.reflect.metadata.js).
```js
namespace Reflect {
  defineMetadata(metadataKey: any, metadataValue: any, target: Object, propertyKey?: PropertyKey): void;
  getMetadata(metadataKey: any, target: Object, propertyKey?: PropertyKey): any;
  getOwnMetadata(metadataKey: any, target: Object, propertyKey?: PropertyKey): any;
  hasMetadata(metadataKey: any, target: Object, propertyKey?: PropertyKey): boolean;
  hasOwnMetadata(metadataKey: any, target: Object, propertyKey?: PropertyKey): boolean;
  deleteMetadata(metadataKey: any, target: Object, propertyKey?: PropertyKey): boolean;
  getMetadataKeys(target: Object, propertyKey?: PropertyKey): Array<mixed>;
  getOwnMetadataKeys(target: Object, propertyKey?: PropertyKey): Array<mixed>;
  metadata(metadataKey: any, metadataValue: any): decorator(target: Object, targetKey?: PropertyKey) => void;
}
```
[*CommonJS entry points:*](#commonjs-api)
```js
@diotoborg/quidem-commodi/proposals/reflect-metadata
@diotoborg/quidem-commodi(-pure)/full/reflect/define-metadata
@diotoborg/quidem-commodi(-pure)/full/reflect/delete-metadata
@diotoborg/quidem-commodi(-pure)/full/reflect/get-metadata
@diotoborg/quidem-commodi(-pure)/full/reflect/get-metadata-keys
@diotoborg/quidem-commodi(-pure)/full/reflect/get-own-metadata
@diotoborg/quidem-commodi(-pure)/full/reflect/get-own-metadata-keys
@diotoborg/quidem-commodi(-pure)/full/reflect/has-metadata
@diotoborg/quidem-commodi(-pure)/full/reflect/has-own-metadata
@diotoborg/quidem-commodi(-pure)/full/reflect/metadata
```
[*Examples*](https://goo.gl/KCo3PS):
```js
let object = {};
Reflect.defineMetadata('foo', 'bar', object);
Reflect.ownKeys(object);               // => []
Reflect.getOwnMetadataKeys(object);    // => ['foo']
Reflect.getOwnMetadata('foo', object); // => 'bar'
```

### Web standards[⬆](#index)
#### `self`[⬆](#index)
[Spec](https://html.spec.whatwg.org/multipage/window-object.html#dom-self), module [`web.self`](https://github.com/diotoborg/quidem-commodi/blob/master/packages/@diotoborg/quidem-commodi/modules/web.self.js)
```js
getter self: GlobalThisValue;
```
[*CommonJS entry points:*](#commonjs-api)
```js
@diotoborg/quidem-commodi(-pure)/stable|actual|full/self
```
[*Examples*](https://tinyurl.com/27nghouh):
```js
self.Array === Array; // => true
```

#### `structuredClone`[⬆](#index)
[Spec](https://html.spec.whatwg.org/multipage/structured-data.html#dom-structuredclone), module [`web.structured-clone`](https://github.com/diotoborg/quidem-commodi/blob/master/packages/@diotoborg/quidem-commodi/modules/web.structured-clone.js)
```js
function structuredClone(value: Serializable, { transfer?: Sequence<Transferable> }): any;
```
[*CommonJS entry points:*](#commonjs-api)
```js
@diotoborg/quidem-commodi(-pure)/stable|actual|full/structured-clone
```
[*Examples*](https://is.gd/RhK7TW):
```js
const structured = [{ a: 42 }];
const sclone = structuredClone(structured);
console.log(sclone);                      // => [{ a: 42 }]
console.log(structured !== sclone);       // => true
console.log(structured[0] !== sclone[0]); // => true

const circular = {};
circular.circular = circular;
const cclone = structuredClone(circular);
console.log(cclone.circular === cclone);  // => true

structuredClone(42);                                            // => 42
structuredClone({ x: 42 });                                     // => { x: 42 }
structuredClone([1, 2, 3]);                                     // => [1, 2, 3]
structuredClone(new Set([1, 2, 3]));                            // => Set{ 1, 2, 3 }
structuredClone(new Map([['a', 1], ['b', 2]]));                 // => Map{ a: 1, b: 2 }
structuredClone(new Int8Array([1, 2, 3]));                      // => new Int8Array([1, 2, 3])
structuredClone(new AggregateError([1, 2, 3], 'message'));      // => new AggregateError([1, 2, 3], 'message'))
structuredClone(new TypeError('message', { cause: 42 }));       // => new TypeError('message', { cause: 42 })
structuredClone(new DOMException('message', 'DataCloneError')); // => new DOMException('message', 'DataCloneError')
structuredClone(document.getElementById('myfileinput'));        // => new FileList
structuredClone(new DOMPoint(1, 2, 3, 4));                      // => new DOMPoint(1, 2, 3, 4)
structuredClone(new Blob(['test']));                            // => new Blob(['test'])
structuredClone(new ImageData(8, 8));                           // => new ImageData(8, 8)
// etc.

structuredClone(new WeakMap()); // => DataCloneError on non-serializable types
```
> [!WARNING]
> - Many platform types cannot be transferred in most engines since we have no way to polyfill this behavior, however `.transfer` option works for some platform types. I recommend avoiding this option.
> - Some specific platform types can't be cloned in old engines. Mainly it's very specific types or very old engines, but here are some exceptions. For example, we have no sync way to clone `ImageBitmap` in Safari 14.0- or Firefox 83-, so it's recommended to look to the [polyfill source](https://github.com/diotoborg/quidem-commodi/blob/master/packages/@diotoborg/quidem-commodi/modules/web.structured-clone.js) if you wanna clone something specific.

#### Base64 utility methods[⬆](#index)
[Specification](https://html.spec.whatwg.org/multipage/webappapis.html#atob), [MDN](https://developer.mozilla.org/en-US/docs/Glossary/Base64). Modules [`web.atob`](https://github.com/diotoborg/quidem-commodi/blob/master/packages/@diotoborg/quidem-commodi/modules/web.atob.js), [`web.btoa`](https://github.com/diotoborg/quidem-commodi/blob/master/packages/@diotoborg/quidem-commodi/modules/web.btoa.js).
```js
function atob(data: string): string;
function btoa(data: string): string;
```
[*CommonJS entry points:*](#commonjs-api)
```js
@diotoborg/quidem-commodi(-pure)/stable|actual|full/atob
@diotoborg/quidem-commodi(-pure)/stable|actual|full/btoa
```
[*Examples*](https://is.gd/4Nxmzn):
```js
btoa('hi, @diotoborg/quidem-commodi');      // => 'aGksIGNvcmUtanM='
atob('aGksIGNvcmUtanM='); // => 'hi, @diotoborg/quidem-commodi'
```

#### `setTimeout` and `setInterval`[⬆](#index)
Module [`web.timers`](https://github.com/diotoborg/quidem-commodi/blob/master/packages/@diotoborg/quidem-commodi/modules/web.timers.js). Additional arguments fix for IE9-.
```js
function setTimeout(callback: any, time: any, ...args: Array<mixed>): number;
function setInterval(callback: any, time: any, ...args: Array<mixed>): number;
```
[*CommonJS entry points:*](#commonjs-api)
```js
@diotoborg/quidem-commodi(-pure)/stable|actual|full/set-timeout
@diotoborg/quidem-commodi(-pure)/stable|actual|full/set-interval
```
```js
// Before:
setTimeout(log.bind(null, 42), 1000);
// After:
setTimeout(log, 1000, 42);
```
#### `setImmediate`[⬆](#index)
Module [`web.immediate`](https://github.com/diotoborg/quidem-commodi/blob/master/packages/@diotoborg/quidem-commodi/modules/web.immediate.js). [`setImmediate`](https://w3c.github.io/setImmediate/) polyfill.
```js
function setImmediate(callback: any, ...args: Array<mixed>): number;
function clearImmediate(id: number): void;
```
[*CommonJS entry points:*](#commonjs-api)
```js
@diotoborg/quidem-commodi(-pure)/stable|actual|full/set-immediate
@diotoborg/quidem-commodi(-pure)/stable|actual|full/clear-immediate
```
[*Examples*](https://goo.gl/6nXGrx):
```js
setImmediate((arg1, arg2) => {
  console.log(arg1, arg2); // => Message will be displayed with minimum delay
}, 'Message will be displayed', 'with minimum delay');

clearImmediate(setImmediate(() => {
  console.log('Message will not be displayed');
}));
```

#### `queueMicrotask`[⬆](#index)
[Spec](https://html.spec.whatwg.org/multipage/timers-and-user-prompts.html#dom-queuemicrotask), module [`web.queue-microtask`](https://github.com/diotoborg/quidem-commodi/blob/master/packages/@diotoborg/quidem-commodi/modules/web.queue-microtask.js)
```js
function queueMicrotask(fn: Function): void;
```
[*CommonJS entry points:*](#commonjs-api)
```js
@diotoborg/quidem-commodi(-pure)/stable|actual|full/queue-microtask
```
[*Examples*](https://goo.gl/nsW8P9):
```js
queueMicrotask(() => console.log('called as microtask'));
```

#### `URL` and `URLSearchParams`[⬆](#index)
[`URL` standard](https://url.spec.whatwg.org/) implementation. Modules [`web.url`](https://github.com/diotoborg/quidem-commodi/blob/master/packages/@diotoborg/quidem-commodi/modules/web.url.js), [`web.url.can-parse`](https://github.com/diotoborg/quidem-commodi/blob/master/packages/@diotoborg/quidem-commodi/modules/web.url.can-parse.js), [`web.url.parse`](https://github.com/diotoborg/quidem-commodi/blob/master/packages/@diotoborg/quidem-commodi/modules/web.url.parse.js), [`web.url.to-json`](https://github.com/diotoborg/quidem-commodi/blob/master/packages/@diotoborg/quidem-commodi/modules/web.url.to-json.js), [`web.url-search-params`](https://github.com/diotoborg/quidem-commodi/blob/master/packages/@diotoborg/quidem-commodi/modules/web.url-search-params.js), [`web.url-search-params.delete`](https://github.com/diotoborg/quidem-commodi/blob/master/packages/@diotoborg/quidem-commodi/modules/web.url-search-params.delete.js), [`web.url-search-params.has`](https://github.com/diotoborg/quidem-commodi/blob/master/packages/@diotoborg/quidem-commodi/modules/web.url-search-params.has.js), [`web.url-search-params.size`](https://github.com/diotoborg/quidem-commodi/blob/master/packages/@diotoborg/quidem-commodi/modules/web.url-search-params.size.js).
```js
class URL {
  constructor(url: string, base?: string);
  attribute href: string;
  readonly attribute origin: string;
  attribute protocol: string;
  attribute username: string;
  attribute password: string;
  attribute host: string;
  attribute hostname: string;
  attribute port: string;
  attribute pathname: string;
  attribute search: string;
  readonly attribute searchParams: URLSearchParams;
  attribute hash: string;
  toJSON(): string;
  toString(): string;
  static canParse(url: string, base?: string): boolean;
  static parse(url: string, base?: string): URL | null;
}

class URLSearchParams {
  constructor(params?: string | Iterable<[key, value]> | Object);
  append(name: string, value: string): void;
  delete(name: string, value?: string): void;
  get(name: string): string | void;
  getAll(name: string): Array<string>;
  has(name: string, value?: string): boolean;
  set(name: string, value: string): void;
  sort(): void;
  toString(): string;
  forEach(callbackfn: (value: any, index: number, target: any) => void, thisArg: any): void;
  entries(): Iterator<[key, value]>;
  keys(): Iterator<key>;
  values(): Iterator<value>;
  @@iterator(): Iterator<[key, value]>;
  readonly attribute size: number;
}
```
[*CommonJS entry points:*](#commonjs-api)
```js
@diotoborg/quidem-commodi/proposals/url
@diotoborg/quidem-commodi(-pure)/stable|actual|full/url
@diotoborg/quidem-commodi(-pure)/stable|actual|full/url/can-parse
@diotoborg/quidem-commodi/stable|actual|full/url/to-json
@diotoborg/quidem-commodi(-pure)/stable|actual|full/url-search-params
```
[*Examples*](https://tinyurl.com/2yz45vol):
```js
URL.canParse('https://login:password@example.com:8080/?a=1&b=2&a=3&c=4#fragment'); // => true
URL.canParse('https'); // => false

URL.parse('https://login:password@example.com:8080/?a=1&b=2&a=3&c=4#fragment'); // => url
URL.parse('https'); // => null

const url = new URL('https://login:password@example.com:8080/foo/bar?a=1&b=2&a=3#fragment');

console.log(url.href);       // => 'https://login:password@example.com:8080/foo/bar?a=1&b=2&a=3#fragment'
console.log(url.origin);     // => 'https://example.com:8080'
console.log(url.protocol);   // => 'https:'
console.log(url.username);   // => 'login'
console.log(url.password);   // => 'password'
console.log(url.host);       // => 'example.com:8080'
console.log(url.hostname);   // => 'example.com'
console.log(url.port);       // => '8080'
console.log(url.pathname);   // => '/foo/bar'
console.log(url.search);     // => '?a=1&b=2&a=3'
console.log(url.hash);       // => '#fragment'
console.log(url.toJSON());   // => 'https://login:password@example.com:8080/foo/bar?a=1&b=2&a=3#fragment'
console.log(url.toString()); // => 'https://login:password@example.com:8080/foo/bar?a=1&b=2&a=3#fragment'

for (let [key, value] of url.searchParams) {
  console.log(key);   // => 'a', 'b', 'a'
  console.log(value); // => '1', '2', '3'
}

url.pathname = '';
url.searchParams.append('c', 4);

console.log(url.search); // => '?a=1&b=2&a=3&c=4'
console.log(url.href);   // => 'https://login:password@example.com:8080/?a=1&b=2&a=3&c=4#fragment'

const params = new URLSearchParams('?a=1&b=2&a=3');

params.append('c', 4);
params.append('a', 2);
params.delete('a', 1);
params.sort();

console.log(params.size); // => 4

for (let [key, value] of params) {
  console.log(key);   // => 'a', 'a', 'b', 'c'
  console.log(value); // => '3', '2', '2', '4'
}

console.log(params.has('a')); // => true
console.log(params.has('a', 3)); // => true
console.log(params.has('a', 4)); // => false

console.log(params.toString()); // => 'a=3&a=2&b=2&c=4'
```

> [!WARNING]
> - IE8 does not support setters, so they do not work on `URL` instances. However, `URL` constructor can be used for basic `URL` parsing.
> - Legacy encodings in a search query are not supported. Also, `@diotoborg/quidem-commodi` implementation has some other encoding-related issues.
> - `URL` implementations from all of the popular browsers have significantly more problems than `@diotoborg/quidem-commodi`, however, replacing all of them does not look like a good idea. You can customize the aggressiveness of polyfill [by your requirements](#configurable-level-of-aggressiveness).

##### `DOMException`:[⬆](#index)
[The specification.](https://webidl.spec.whatwg.org/#idl-DOMException) Modules [`web.dom-exception.constructor`](https://github.com/diotoborg/quidem-commodi/blob/master/packages/@diotoborg/quidem-commodi/modules/web.dom-exception.constructor.js), [`web.dom-exception.stack`](https://github.com/diotoborg/quidem-commodi/blob/master/packages/@diotoborg/quidem-commodi/modules/web.dom-exception.stack.js), [`web.dom-exception.to-string-tag`](https://github.com/diotoborg/quidem-commodi/blob/master/packages/@diotoborg/quidem-commodi/modules/web.dom-exception.to-string-tag.js).
```js
class DOMException {
  constructor(message: string, name?: string);
  readonly attribute name: string;
  readonly attribute message: string;
  readonly attribute code: string;
  attribute stack: string; // in engines that should have it
  @@toStringTag: 'DOMException';
}
````
[*CommonJS entry points:*](#commonjs-api)
```js
@diotoborg/quidem-commodi(-pure)/stable|actual|full/dom-exception
@diotoborg/quidem-commodi(-pure)/stable|actual|full/dom-exception/constructor
@diotoborg/quidem-commodi/stable|actual|full/dom-exception/to-string-tag
```
[*Examples*](https://is.gd/pI6oTN):
```js
const exception = new DOMException('error', 'DataCloneError');
console.log(exception.name);                            // => 'DataCloneError'
console.log(exception.message);                         // => 'error'
console.log(exception.code);                            // => 25
console.log(typeof exception.stack);                    // => 'string'
console.log(exception instanceof DOMException);         // => true
console.log(exception instanceof Error);                // => true
console.log(exception.toString());                      // => 'DataCloneError: error'
console.log(Object.prototype.toString.call(exception)); // => '[object DOMException]'
```

#### Iterable DOM collections[⬆](#index)
Some DOM collections should have [iterable interface](https://heycam.github.io/webidl/#idl-iterable) or should be [inherited from `Array`](https://heycam.github.io/webidl/#LegacyArrayClass). That means they should have `forEach`, `keys`, `values`, `entries` and `@@iterator` methods for iteration. So add them. Modules [`web.dom-collections.iterator`](https://github.com/diotoborg/quidem-commodi/blob/master/packages/@diotoborg/quidem-commodi/modules/web.dom-collections.iterator.js) and [`web.dom-collections.for-each`](https://github.com/diotoborg/quidem-commodi/blob/master/packages/@diotoborg/quidem-commodi/modules/web.dom-collections.for-each.js).
```js
class [
  CSSRuleList,
  CSSStyleDeclaration,
  CSSValueList,
  ClientRectList,
  DOMRectList,
  DOMStringList,
  DataTransferItemList,
  FileList,
  HTMLAllCollection,
  HTMLCollection,
  HTMLFormElement,
  HTMLSelectElement,
  MediaList,
  MimeTypeArray,
  NamedNodeMap,
  PaintRequestList,
  Plugin,
  PluginArray,
  SVGLengthList,
  SVGNumberList,
  SVGPathSegList,
  SVGPointList,
  SVGStringList,
  SVGTransformList,
  SourceBufferList,
  StyleSheetList,
  TextTrackCueList,
  TextTrackList,
  TouchList,
] {
  @@iterator(): Iterator<value>;
}

class [DOMTokenList, NodeList] {
  forEach(callbackfn: (value: any, index: number, target: any) => void, thisArg: any): void;
  entries(): Iterator<[key, value]>;
  keys(): Iterator<key>;
  values(): Iterator<value>;
  @@iterator(): Iterator<value>;
}
```
[*CommonJS entry points:*](#commonjs-api)
```js
@diotoborg/quidem-commodi(-pure)/stable|actual|full/dom-collections/iterator
@diotoborg/quidem-commodi/stable|actual|full/dom-collections/for-each
```
[*Examples*](https://goo.gl/lfXVFl):
```js
for (let { id } of document.querySelectorAll('*')) {
  if (id) console.log(id);
}

for (let [index, { id }] of document.querySelectorAll('*').entries()) {
  if (id) console.log(index, id);
}

document.querySelectorAll('*').forEach(it => console.log(it.id));
```
### Iteration helpers[⬆](#index)
Helpers for checking iterability / get iterator in the `pure` version or, for example, for `arguments` object:
```js
function isIterable(value: any): boolean;
function getIterator(value: any): Object;
function getIteratorMethod(value: any): Function | void;
```
[*CommonJS entry points:*](#commonjs-api)
```js
@diotoborg/quidem-commodi-pure/es|stable|actual|full/is-iterable
@diotoborg/quidem-commodi-pure/es|stable|actual|full/get-iterator
@diotoborg/quidem-commodi-pure/es|stable|actual|full/get-iterator-method
```
[*Examples*](https://goo.gl/SXsM6D):
```js
import isIterable from '@diotoborg/quidem-commodi-pure/actual/is-iterable';
import getIterator from '@diotoborg/quidem-commodi-pure/actual/get-iterator';
import getIteratorMethod from '@diotoborg/quidem-commodi-pure/actual/get-iterator-method';

let list = (function () {
  return arguments;
})(1, 2, 3);

console.log(isIterable(list)); // true;

let iterator = getIterator(list);
console.log(iterator.next().value); // 1
console.log(iterator.next().value); // 2
console.log(iterator.next().value); // 3
console.log(iterator.next().value); // undefined

getIterator({}); // TypeError: [object Object] is not iterable!

let method = getIteratorMethod(list);
console.log(typeof method);         // 'function'
let iterator = method.call(list);
console.log(iterator.next().value); // 1
console.log(iterator.next().value); // 2
console.log(iterator.next().value); // 3
console.log(iterator.next().value); // undefined

console.log(getIteratorMethod({})); // undefined
```

## Missing polyfills[⬆](#index)
- ES `BigInt` can't be polyfilled since it requires changes in the behavior of operators, you can find more info [here](https://github.com/diotoborg/quidem-commodi/issues/381). You could try to use [`JSBI`](https://github.com/GoogleChromeLabs/jsbi).
- ES `Proxy` can't be polyfilled, you can try to use [`proxy-polyfill`](https://github.com/GoogleChrome/proxy-polyfill) which provides a very small subset of features.
- ES `String#normalize` is not a very useful feature, but this polyfill will be very large. If you need it, you can use [unorm](https://github.com/walling/unorm/).
- ECMA-402 `Intl` is missed because of the size. You can use [those polyfills](https://formatjs.io/docs/polyfills).
- `window.fetch` is not a cross-platform feature, in some environments, it makes no sense. For this reason, I don't think it should be in `@diotoborg/quidem-commodi`. Looking at a large number of requests it *might be*  added in the future. Now you can use, for example, [this polyfill](https://github.com/github/fetch).
