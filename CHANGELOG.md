# Changelog

All notable changes to this project will be documented in this file. See [standard-version](https://github.com/conventional-changelog/standard-version) for commit guidelines.

### [1.12.1](https://github.com/johnwalley/allotment/compare/v1.12.0...v1.12.1) (2022-04-11)

## [1.12.0](https://github.com/johnwalley/allotment/compare/v1.11.2...v1.12.0) (2022-04-11)

### Features

- add onVisibleChange callback ([#222](https://github.com/johnwalley/allotment/issues/222)) ([39f9bec](https://github.com/johnwalley/allotment/commit/39f9bec2627b7496ee6270fe3ff67e8a1f90e94e))
- add preferredSize prop ([#229](https://github.com/johnwalley/allotment/issues/229)) ([3be2144](https://github.com/johnwalley/allotment/commit/3be21441660475a5c71c604dbb11ac84630df913))
- avoid unmounting pane with same key which changes position ([#226](https://github.com/johnwalley/allotment/issues/226)) ([f7d077a](https://github.com/johnwalley/allotment/commit/f7d077a1d71d51139ce7386be0538dcdd29c08e1))
- dynamic minSize and maxSize ([#227](https://github.com/johnwalley/allotment/issues/227)) ([d764ebe](https://github.com/johnwalley/allotment/commit/d764ebe241faead5bdecd9311135ff1f39a40935))

### Bug Fixes

- **deps:** update react monorepo to v18 ([#214](https://github.com/johnwalley/allotment/issues/214)) ([3263b4b](https://github.com/johnwalley/allotment/commit/3263b4b2a5a24e9d97e8ff4a2db3f783240ee97a))
- preferredSize should work with defaultSizes ([5398f2f](https://github.com/johnwalley/allotment/commit/5398f2fe6fa466fe6ed05fb3e7ced61745b8ca51))
- use custom onReset callback for programatic reset ([978c0be](https://github.com/johnwalley/allotment/commit/978c0be46b1427056b7ecc0101fe2090720354ad))

### [1.11.2](https://github.com/johnwalley/allotment/compare/v1.11.1...v1.11.2) (2022-04-02)

### Bug Fixes

- defaultSizes should not disable props on Allotment.Pane ([3837d87](https://github.com/johnwalley/allotment/commit/3837d87538089cea6c53635f9a657fcf75296b9e))

### [1.11.1](https://github.com/johnwalley/allotment/compare/v1.11.0...v1.11.1) (2022-03-26)

### Bug Fixes

- visible prop not working as expected ([d06931b](https://github.com/johnwalley/allotment/commit/d06931b7ba37248f4c61f0768d3ba571141b4fdf))

## [1.11.0](https://github.com/johnwalley/allotment/compare/v1.10.0...v1.11.0) (2022-03-09)

### Features

- add prop for setting proportionalLayout ([#179](https://github.com/johnwalley/allotment/issues/179)) ([4f8f68c](https://github.com/johnwalley/allotment/commit/4f8f68c3d2ae99108b97befc5ab787873c7e3f77))

## [1.10.0](https://github.com/johnwalley/allotment/compare/v1.9.1...v1.10.0) (2022-02-20)

### Features

- use className prop on Allotment component ([8e1b6bd](https://github.com/johnwalley/allotment/commit/8e1b6bde537d03318bd441b9dfdb2816c20bfb2c))

### [1.9.1](https://github.com/johnwalley/allotment/compare/v1.9.0...v1.9.1) (2022-02-20)

### Bug Fixes

- respect visible prop on initial render ([5daeeaf](https://github.com/johnwalley/allotment/commit/5daeeafdc50c810ade14f02492bb73ad343164fc))

## [1.9.0](https://github.com/johnwalley/allotment/compare/v1.8.0...v1.9.0) (2022-02-10)

### Features

- add className prop to Allotment.Pane ([#108](https://github.com/johnwalley/allotment/issues/108)) ([9486638](https://github.com/johnwalley/allotment/commit/94866382d2580220a3502f8194c18eb93cd721ec))

## [1.8.0](https://github.com/johnwalley/allotment/compare/v1.7.0...v1.8.0) (2022-02-08)

### Features

- add onReset callback ([#154](https://github.com/johnwalley/allotment/issues/154)) ([904a8e6](https://github.com/johnwalley/allotment/commit/904a8e6acbf3692b4f2cb7fa102799872c70243d))
- add resize method to component instance ([#121](https://github.com/johnwalley/allotment/issues/121)) ([d25bd91](https://github.com/johnwalley/allotment/commit/d25bd91bde05c33bdebf586868a38a03056d8d57))
- add visible prop to Pane ([#137](https://github.com/johnwalley/allotment/issues/137)) ([3b0542c](https://github.com/johnwalley/allotment/commit/3b0542c24165c0cb054ee12a682c1b153a2de5ad))

## [1.7.0](https://github.com/johnwalley/allotment/compare/v1.6.0...v1.7.0) (2022-01-22)

### Features

- separator color which works better on light and dark backgrounds ([a769262](https://github.com/johnwalley/allotment/commit/a769262de79658cda4866edbafe4ffb8e5f0773a))

### Bug Fixes

- call cancel hover after pointer up ([#129](https://github.com/johnwalley/allotment/issues/129)) ([b9a6e5f](https://github.com/johnwalley/allotment/commit/b9a6e5f10f89298e9935f14c9d52f63ec8527e2c))

### [1.6.0](https://github.com/johnwalley/allotment/compare/v1.5.2...v1.6.0) (2022-01-16)

### Bug Fixes

- allow changing order of panes ([cc38223](https://github.com/johnwalley/allotment/commit/cc38223e3f4315f61a50126630170c25ab8b5e1f))

### [1.5.2](https://github.com/johnwalley/allotment/compare/v1.5.1...v1.5.2) (2022-01-15)

This release was published without any updates and should be skipped.

### [1.5.1](https://github.com/johnwalley/allotment/compare/v1.5.0...v1.5.1) (2022-01-02)

### Bug Fixes

- set css custom variables if touch device detected ([2eb8c38](https://github.com/johnwalley/allotment/commit/2eb8c387009f013bd0440b83f4a41a53277c76ff))

## [1.5.0](https://github.com/johnwalley/allotment/compare/v1.4.2...v1.5.0) (2021-12-26)

### Features

- enable sash size to be customised in code ([#101](https://github.com/johnwalley/allotment/issues/101)) ([f177e48](https://github.com/johnwalley/allotment/commit/f177e48bdf4e12533b8e5dcdd76cd94802c83710))

### [1.4.2](https://github.com/johnwalley/allotment/compare/v1.4.1...v1.4.2) (2021-12-24)

### Bug Fixes

- replace remaining uses of sizes with defaultSizes ([cf5e2c1](https://github.com/johnwalley/allotment/commit/cf5e2c1dd77dd5a3edc4bd6f903acb824a90ed39))

### [1.4.1](https://github.com/johnwalley/allotment/compare/v1.4.0...v1.4.1) (2021-12-05)

### Bug Fixes

- defaultSizes needs to be used ([#77](https://github.com/johnwalley/allotment/issues/77)) ([cd2eae1](https://github.com/johnwalley/allotment/commit/cd2eae13116af91af00846e212452287cfb7c607))

## [1.4.0](https://github.com/johnwalley/allotment/compare/v1.3.0...v1.4.0) (2021-12-05)

### Features

- increase sash size on touch devices ([#66](https://github.com/johnwalley/allotment/issues/66)) ([20ab7d9](https://github.com/johnwalley/allotment/commit/20ab7d93ab836af864a67531b3c5c1244e23a3b8))

## [1.3.0](https://github.com/johnwalley/allotment/compare/v1.2.0...v1.3.0) (2021-12-03)

### Features

- add defaultSizes prop and deprecate sizes prop ([#72](https://github.com/johnwalley/allotment/issues/72)) ([2ece9ce](https://github.com/johnwalley/allotment/commit/2ece9ce2f8142d1c28b5394743d73f920f4489e2))
- add imperative reset method ([#69](https://github.com/johnwalley/allotment/issues/69)) ([aceb88f](https://github.com/johnwalley/allotment/commit/aceb88f2de9e454dfce2ccd35bc4e23c8d8e3cb7))

### Bug Fixes

- distribute space evenly when adding a pane ([#58](https://github.com/johnwalley/allotment/issues/58)) ([6feb767](https://github.com/johnwalley/allotment/commit/6feb767cb8a289f5c167ae981b435e4c02f50215))

## [1.2.0](https://github.com/johnwalley/allotment/compare/v1.1.0...v1.2.0) (2021-10-03)

### Features

- support setting initial sizes ([#14](https://github.com/johnwalley/allotment/issues/14)) ([b07415e](https://github.com/johnwalley/allotment/commit/b07415e0539ca28f123a143c88aa28de7ec80b75))

## [1.1.0](https://github.com/johnwalley/allotment/compare/v1.0.1...v1.1.0) (2021-09-30)

### Features

- set props on children ([#9](https://github.com/johnwalley/allotment/issues/9)) ([180ed52](https://github.com/johnwalley/allotment/commit/180ed52bced6d74860142092f27800728896d97e))

### Bug Fixes

- center sash ([#12](https://github.com/johnwalley/allotment/issues/12)) ([d2b7486](https://github.com/johnwalley/allotment/commit/d2b74867dae30ae05f3f20f4d4a29cc8ebc7a9e7))

### [1.0.1](https://github.com/johnwalley/allotment/compare/v1.0.0...v1.0.1) (2021-09-24)

### Bug Fixes

- remove requirement to use Allotment.Pane if using refs with children ([93a30bb](https://github.com/johnwalley/allotment/commit/93a30bb58c9d12b1a3b4a441f57613aea79e7923))

## 1.0.0 (2021-09-23)

### Features

- basic functionality ([#1](https://github.com/johnwalley/allotment/issues/1)) ([36b4442](https://github.com/johnwalley/allotment/commit/36b44425f9ea8d6d18e2e74cabfbc9813c52c0fd))
