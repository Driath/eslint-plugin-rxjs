<a name="2.1.5"></a>
## [2.1.5](https://github.com/cartant/eslint-plugin-rxjs/compare/v2.1.4...v2.1.5) (2020-11-28)

## Changes

* Use `files` in `package.json` instead of `.npmignore`. ([99cb9ec](https://github.com/cartant/eslint-plugin-rxjs/commit/99cb9ec))

<a name="2.1.4"></a>
## [2.1.4](https://github.com/cartant/eslint-plugin-rxjs/compare/v2.1.3...v2.1.4) (2020-11-21)

## Fixes

* Fixed a problem with `no-cyclic-action` when used with effects/epics that return `Observable<void>`. ([79b9e82](https://github.com/cartant/eslint-plugin-rxjs/commit/79b9e82))

<a name="2.1.3"></a>
## [2.1.3](https://github.com/cartant/eslint-plugin-rxjs/compare/v2.1.2...v2.1.3) (2020-11-05)

## Fixes

* `no-ignored-subscription` should not effect failures for `Subscriber` instances passed to `subscribe`. ([72e11ec](https://github.com/cartant/eslint-plugin-rxjs/commit/72e11ec))

<a name="2.1.2"></a>
## [2.1.2](https://github.com/cartant/eslint-plugin-rxjs/compare/v2.1.1...v2.1.2) (2020-11-03)

## Changes

* Use the public TypeScript API (`getTypeArguments`) to obtain the type arguments in the `no-cyclic-action` rule. ([7f55bcb](https://github.com/cartant/eslint-plugin-rxjs/commit/7f55bcb))

<a name="2.1.1"></a>
## [2.1.1](https://github.com/cartant/eslint-plugin-rxjs/compare/v2.1.0...v2.1.1) (2020-11-03)

## Changes

* Use the public TypeScript API (`getTypeOfSymbolAtLocation`) to obtain the action type in the `no-cyclic-action` rule. ([56687db](https://github.com/cartant/eslint-plugin-rxjs/commit/56687db))

<a name="2.1.0"></a>
## [2.1.0](https://github.com/cartant/eslint-plugin-rxjs/compare/v2.0.1...v2.1.0) (2020-11-03)

## Changes

* Added the `no-cyclic-action` rule for effects and epics. ([5e03092](https://github.com/cartant/eslint-plugin-rxjs/commit/5e03092))

<a name="2.0.1"></a>
## [2.0.1](https://github.com/cartant/eslint-plugin-rxjs/compare/v2.0.0...v2.0.1) (2020-11-03)

## Changes

* Update rule metadata.

<a name="2.0.0"></a>
## [2.0.0](https://github.com/cartant/eslint-plugin-rxjs/compare/v1.0.3...v2.0.0) (2020-10-29)

## Breaking Changes

* `no-implicit-any-catch` is now enforced for error callbacks - and error methods on observers - passed to `subscribe` and `tap`, too. ([1b9234b](https://github.com/cartant/eslint-plugin-rxjs/commit/1b9234b))

<a name="1.0.3"></a>
## [1.0.3](https://github.com/cartant/eslint-plugin-rxjs/compare/v1.0.2...v1.0.3) (2020-10-27)

## Changes

* Specify Node 10 as the minimum `engines` in `package.json` and downlevel to ES2018.

<a name="1.0.2"></a>
## [1.0.2](https://github.com/cartant/eslint-plugin-rxjs/compare/v1.0.1...v1.0.2) (2020-10-25)

## Changes

* Deprecate `no-tap` in favour of `ban-operators`. `no-do`/`no-tap` was an early TSLint rule and `ban-operators` is the preferred rule for banning operators as it allows a message to be specified.

<a name="1.0.1"></a>
## [1.0.1](https://github.com/cartant/eslint-plugin-rxjs/compare/v1.0.0...v1.0.1) (2020-10-23)

## Changes

* Specify `engines` in `package.json`.
* Downlevel the TypeScript output to ES2019.