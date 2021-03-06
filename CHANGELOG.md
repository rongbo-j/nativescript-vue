<a name="2.0.0-alpha.1"></a>
# [2.0.0-alpha.1](https://github.com/nativescript-vue/nativescript-vue/compare/v2.0.0-alpha.0...v2.0.0-alpha.1) (2018-07-15)


### Bug Fixes

* action bar rendering - issue [#276](https://github.com/nativescript-vue/nativescript-vue/issues/276) ([#278](https://github.com/nativescript-vue/nativescript-vue/issues/278)) ([db6df39](https://github.com/nativescript-vue/nativescript-vue/commit/db6df39))



<a name="2.0.0-alpha.0"></a>
# [2.0.0-alpha.0](https://github.com/nativescript-vue/nativescript-vue/compare/v1.4.0-alpha.0...v2.0.0-alpha.0) (2018-07-04)


### Bug Fixes

* Detect boolean attributes and expand them if value is empty ([#171](https://github.com/nativescript-vue/nativescript-vue/issues/171)) ([72f2102](https://github.com/nativescript-vue/nativescript-vue/commit/72f2102))
* don't create view without data ([ba4e994](https://github.com/nativescript-vue/nativescript-vue/commit/ba4e994)), closes [#229](https://github.com/nativescript-vue/nativescript-vue/issues/229)
* fix consecutive v-if's and v-for's ([821d726](https://github.com/nativescript-vue/nativescript-vue/commit/821d726)), closes [#127](https://github.com/nativescript-vue/nativescript-vue/issues/127) [#240](https://github.com/nativescript-vue/nativescript-vue/issues/240)
* fix v-if in ActionBar ([95054ee](https://github.com/nativescript-vue/nativescript-vue/commit/95054ee)), closes [#76](https://github.com/nativescript-vue/nativescript-vue/issues/76)


### Features

* add refresh shortcut for ListView ([b809f0f](https://github.com/nativescript-vue/nativescript-vue/commit/b809f0f)), closes [#193](https://github.com/nativescript-vue/nativescript-vue/issues/193)
* allow multiple nodes in <ios> and <android> tags ([7bf8b10](https://github.com/nativescript-vue/nativescript-vue/commit/7bf8b10))
* improve v-show to support <transition> ([3e50a90](https://github.com/nativescript-vue/nativescript-vue/commit/3e50a90))
* include typedefinitions in npm package ([7286e67](https://github.com/nativescript-vue/nativescript-vue/commit/7286e67)), closes [#262](https://github.com/nativescript-vue/nativescript-vue/issues/262) [#263](https://github.com/nativescript-vue/nativescript-vue/issues/263)
* wrap all elements in functional Vue components ([#267](https://github.com/nativescript-vue/nativescript-vue/issues/267)) ([a4e2fa5](https://github.com/nativescript-vue/nativescript-vue/commit/a4e2fa5)), closes [#127](https://github.com/nativescript-vue/nativescript-vue/issues/127) [#266](https://github.com/nativescript-vue/nativescript-vue/issues/266) [#241](https://github.com/nativescript-vue/nativescript-vue/issues/241)


### BREAKING CHANGES

* All elements are now Vue components, in some cases where a ref is used to get the
nativeView will have to be updated to use `this.$refs.element.$el.nativeView` instead of
`this.$refs.element.nativeView`. There may be other breaking changes this introduces that are not
known at this point.



<a name="1.4.0-alpha.0"></a>
# [1.4.0-alpha.0](https://github.com/nativescript-vue/nativescript-vue/compare/v1.3.2-rc.4...v1.4.0-alpha.0) (2018-05-07)


### Features

* allow custom getRootView implementation ([4ec580c](https://github.com/nativescript-vue/nativescript-vue/commit/4ec580c))
* use the new run method instead of the old start method ([d840d3c](https://github.com/nativescript-vue/nativescript-vue/commit/d840d3c))


### BREAKING CHANGES

* nativescript 3.x will no longer work with this change because application.run has
been added in 4.0



<a name="1.3.2-rc.4"></a>
## [1.3.2-rc.4](https://github.com/nativescript-vue/nativescript-vue/compare/v1.3.2-rc.3...v1.3.2-rc.4) (2018-04-22)


### Bug Fixes

* add missing setStyleScope method ([eb03732](https://github.com/nativescript-vue/nativescript-vue/commit/eb03732))
* check for existence of meta before accessing it ([a67119e](https://github.com/nativescript-vue/nativescript-vue/commit/a67119e))
* check for parentNode before calling .meta on it ([45cb46d](https://github.com/nativescript-vue/nativescript-vue/commit/45cb46d))



<a name="1.3.2-rc.3"></a>
## [1.3.2-rc.3](https://github.com/nativescript-vue/nativescript-vue/compare/v1.3.2-rc.2...v1.3.2-rc.3) (2018-04-22)


### Features

* support for frame elements ([bb14c23](https://github.com/nativescript-vue/nativescript-vue/commit/bb14c23))



<a name="1.3.2-rc.2"></a>
## [1.3.2-rc.2](https://github.com/nativescript-vue/nativescript-vue/compare/v1.3.2-rc.1...v1.3.2-rc.2) (2018-04-18)


### Features

* **bootstrap:** use the launch event instead of a navigation entry ([13192b0](https://github.com/nativescript-vue/nativescript-vue/commit/13192b0))



<a name="1.3.2-rc.1"></a>
## [1.3.2-rc.1](https://github.com/nativescript-vue/nativescript-vue/compare/v1.3.2-rc.0...v1.3.2-rc.1) (2018-04-18)


### Bug Fixes

* **bootstrap:** re-mount when activity is re-created ([850b12b](https://github.com/nativescript-vue/nativescript-vue/commit/850b12b))



<a name="1.3.2-rc.0"></a>
## [1.3.2-rc.0](https://github.com/nativescript-vue/nativescript-vue/compare/v1.3.1...v1.3.2-rc.0) (2018-04-15)


### Bug Fixes

* destroy modal vm when modal is closed ([#131](https://github.com/nativescript-vue/nativescript-vue/issues/131)) ([1fd7c81](https://github.com/nativescript-vue/nativescript-vue/commit/1fd7c81))
* return mounted component ([#132](https://github.com/nativescript-vue/nativescript-vue/issues/132)) ([a9187b7](https://github.com/nativescript-vue/nativescript-vue/commit/a9187b7))



<a name="1.3.1"></a>
## [1.3.1](https://github.com/nativescript-vue/nativescript-vue/compare/v1.3.0...v1.3.1) (2018-03-10)


### Bug Fixes

* allow using for attribute in custom components ([3114cca](https://github.com/nativescript-vue/nativescript-vue/commit/3114cca))
* assign to existing instead of replacing ([ce3e9ea](https://github.com/nativescript-vue/nativescript-vue/commit/ce3e9ea))



<a name="1.3.0"></a>
# [1.3.0](https://github.com/nativescript-vue/nativescript-vue/compare/v1.2.0...v1.3.0) (2018-02-27)


### Bug Fixes

* allow deepProxy to be used in expressions ([d7646ee](https://github.com/nativescript-vue/nativescript-vue/commit/d7646ee))
* fix list view template selector getting the wrong item ([d648a57](https://github.com/nativescript-vue/nativescript-vue/commit/d648a57))


### Features

* add transition component ([4951821](https://github.com/nativescript-vue/nativescript-vue/commit/4951821)), closes [#110](https://github.com/nativescript-vue/nativescript-vue/issues/110)



<a name="1.2.0"></a>
# [1.2.0](https://github.com/nativescript-vue/nativescript-vue/compare/v1.1.3...v1.2.0) (2018-02-22)


### Features

* silence framework output by default ([0e5c55b](https://github.com/nativescript-vue/nativescript-vue/commit/0e5c55b))



<a name="1.1.3"></a>
## [1.1.3](https://github.com/nativescript-vue/nativescript-vue/compare/v1.1.2...v1.1.3) (2018-02-21)



<a name="1.1.2"></a>
## [1.1.2](https://github.com/nativescript-vue/nativescript-vue/compare/v1.0.0...v1.1.2) (2018-02-21)


### Bug Fixes

* fix option name for pageRouting ([8a8446f](https://github.com/nativescript-vue/nativescript-vue/commit/8a8446f))


### Features

* add <android> and <ios> elements ([ed96746](https://github.com/nativescript-vue/nativescript-vue/commit/ed96746))
* add platform-dependent property setting ([f981816](https://github.com/nativescript-vue/nativescript-vue/commit/f981816))



<a name="1.0.0"></a>
# [1.0.0](https://github.com/nativescript-vue/nativescript-vue/compare/v1.0.0-alpha.1...v1.0.0) (2018-02-13)



<a name="1.0.0-alpha.1"></a>
# [1.0.0-alpha.1](https://github.com/nativescript-vue/nativescript-vue/compare/v1.0.0-alpha.0...v1.0.0-alpha.1) (2018-02-12)



<a name="1.0.0-alpha.0"></a>
# [1.0.0-alpha.0](https://github.com/nativescript-vue/nativescript-vue/compare/v0.7.12...v1.0.0-alpha.0) (2018-02-12)



<a name="0.7.12"></a>
## [0.7.12](https://github.com/nativescript-vue/nativescript-vue/compare/v0.7.11...v0.7.12) (2018-01-30)


### Bug Fixes

* fix nested components in v-template ([30a11bf](https://github.com/nativescript-vue/nativescript-vue/commit/30a11bf)), closes [#107](https://github.com/nativescript-vue/nativescript-vue/issues/107)
* reload css on livesync ([b2ac1b5](https://github.com/nativescript-vue/nativescript-vue/commit/b2ac1b5))



<a name="0.7.11"></a>
## [0.7.11](https://github.com/nativescript-vue/nativescript-vue/compare/v0.7.10...v0.7.11) (2018-01-26)


### Bug Fixes

* improve console.dir output ([848440a](https://github.com/nativescript-vue/nativescript-vue/commit/848440a))



<a name="0.7.10"></a>
## [0.7.10](https://github.com/nativescript-vue/nativescript-vue/compare/v0.7.9...v0.7.10) (2018-01-24)


### Bug Fixes

* disable pageRouting when not in use ([7def3e2](https://github.com/nativescript-vue/nativescript-vue/commit/7def3e2)), closes [#98](https://github.com/nativescript-vue/nativescript-vue/issues/98)



<a name="0.7.9"></a>
## [0.7.9](https://github.com/nativescript-vue/nativescript-vue/compare/v0.7.8...v0.7.9) (2018-01-23)


### Bug Fixes

* don't import Vue in utils ([7335fd0](https://github.com/nativescript-vue/nativescript-vue/commit/7335fd0))



<a name="0.7.8"></a>
## [0.7.8](https://github.com/nativescript-vue/nativescript-vue/compare/v0.7.7...v0.7.8) (2018-01-10)


### Bug Fixes

* fix v-model not working for non-components ([4cc399e](https://github.com/nativescript-vue/nativescript-vue/commit/4cc399e))



<a name="0.7.7"></a>
## [0.7.7](https://github.com/nativescript-vue/nativescript-vue/compare/v0.7.6...v0.7.7) (2018-01-10)


### Bug Fixes

* don't throw error when livesyncing css ([8365141](https://github.com/nativescript-vue/nativescript-vue/commit/8365141)), closes [#63](https://github.com/nativescript-vue/nativescript-vue/issues/63)



<a name="0.7.6"></a>
## [0.7.6](https://github.com/nativescript-vue/nativescript-vue/compare/v0.7.5...v0.7.6) (2018-01-10)


### Bug Fixes

* fix view already has a parent bug ([e252544](https://github.com/nativescript-vue/nativescript-vue/commit/e252544)), closes [#59](https://github.com/nativescript-vue/nativescript-vue/issues/59) [#78](https://github.com/nativescript-vue/nativescript-vue/issues/78)


### Features

* allow silencing the console ouput ([8f98ad7](https://github.com/nativescript-vue/nativescript-vue/commit/8f98ad7)), closes [#99](https://github.com/nativescript-vue/nativescript-vue/issues/99)



<a name="0.7.5"></a>
## [0.7.5](https://github.com/nativescript-vue/nativescript-vue/compare/v0.7.4...v0.7.5) (2017-12-23)


### Features

* support array properties in v-view directive ([a49ca5d](https://github.com/nativescript-vue/nativescript-vue/commit/a49ca5d)), closes [#80](https://github.com/nativescript-vue/nativescript-vue/issues/80)



<a name="0.7.4"></a>
## [0.7.4](https://github.com/nativescript-vue/nativescript-vue/compare/v0.7.3...v0.7.4) (2017-12-23)



<a name="0.7.3"></a>
## [0.7.3](https://github.com/nativescript-vue/nativescript-vue/compare/v0.7.2...v0.7.3) (2017-12-23)



<a name="0.7.2"></a>
## [0.7.2](https://github.com/nativescript-vue/nativescript-vue/compare/v0.7.1...v0.7.2) (2017-12-23)


### Bug Fixes

* proper v-model for tab-view ([ef26448](https://github.com/nativescript-vue/nativescript-vue/commit/ef26448)), closes [#50](https://github.com/nativescript-vue/nativescript-vue/issues/50)


### Features

* warn when using v-for on a list-view ([2ddd253](https://github.com/nativescript-vue/nativescript-vue/commit/2ddd253))



<a name="0.7.1"></a>
## [0.7.1](https://github.com/nativescript-vue/nativescript-vue/compare/v0.7.0...v0.7.1) (2017-12-22)


### Bug Fixes

* don't color console output unless Vue.config.debug is true ([14e5ed4](https://github.com/nativescript-vue/nativescript-vue/commit/14e5ed4))
* update sample with new list-view syntax ([e2b5225](https://github.com/nativescript-vue/nativescript-vue/commit/e2b5225))


### Features

* allow setting custom iterator, fixes [#58](https://github.com/nativescript-vue/nativescript-vue/issues/58) ([7aba01c](https://github.com/nativescript-vue/nativescript-vue/commit/7aba01c))



<a name="0.7.0"></a>
# [0.7.0](https://github.com/nativescript-vue/nativescript-vue/compare/v0.6.0...v0.7.0) (2017-12-21)


### Features

* Add improved <list-view> syntax: for="item in items" ([81af134](https://github.com/nativescript-vue/nativescript-vue/commit/81af134))
* update sample app to new list-view syntax ([0318163](https://github.com/nativescript-vue/nativescript-vue/commit/0318163))
* update to vue v2.5.13 ([67a1d6a](https://github.com/nativescript-vue/nativescript-vue/commit/67a1d6a))



<a name="0.6.0"></a>
# [0.6.0](https://github.com/nativescript-vue/nativescript-vue/compare/v0.5.1...v0.6.0) (2017-12-21)


### Features

* replace console.log with better support for nested / circular objects ([83aaccf](https://github.com/nativescript-vue/nativescript-vue/commit/83aaccf))



<a name="0.5.1"></a>
## [0.5.1](https://github.com/nativescript-vue/nativescript-vue/compare/v0.5.0...v0.5.1) (2017-12-18)



<a name="0.5.0"></a>
# [0.5.0](https://github.com/nativescript-vue/nativescript-vue/compare/v0.4.0...v0.5.0) (2017-12-18)



<a name="0.4.0"></a>
# [0.4.0](https://github.com/nativescript-vue/nativescript-vue/compare/v0.3.1...v0.4.0) (2017-12-14)


### Bug Fixes

* assign template bag to current instance ([dd74d2f](https://github.com/nativescript-vue/nativescript-vue/commit/dd74d2f))


### Features

* Better templating syntax ([51d2ca4](https://github.com/nativescript-vue/nativescript-vue/commit/51d2ca4))
* updated list-view to use the new v-template ([5a9e377](https://github.com/nativescript-vue/nativescript-vue/commit/5a9e377))



<a name="0.3.1"></a>
## [0.3.1](https://github.com/nativescript-vue/nativescript-vue/compare/v0.3.0...v0.3.1) (2017-11-26)



<a name="0.3.0"></a>
# [0.3.0](https://github.com/nativescript-vue/nativescript-vue/compare/v0.2.0...v0.3.0) (2017-11-24)


### Features

* Add router transitions  ([#86](https://github.com/nativescript-vue/nativescript-vue/issues/86)) ([381843e](https://github.com/nativescript-vue/nativescript-vue/commit/381843e))



<a name="0.2.0"></a>
# [0.2.0](https://github.com/nativescript-vue/nativescript-vue/compare/v0.1.25...v0.2.0) (2017-11-20)



<a name="0.1.25"></a>
## [0.1.25](https://github.com/nativescript-vue/nativescript-vue/compare/v0.1.24...v0.1.25) (2017-11-20)



<a name="0.1.24"></a>
## [0.1.24](https://github.com/nativescript-vue/nativescript-vue/compare/v0.1.23...v0.1.24) (2017-11-17)


### Features

* Added view directive ([#80](https://github.com/nativescript-vue/nativescript-vue/issues/80)) ([611eb83](https://github.com/nativescript-vue/nativescript-vue/commit/611eb83))



<a name="0.1.23"></a>
## [0.1.23](https://github.com/nativescript-vue/nativescript-vue/compare/v0.1.22...v0.1.23) (2017-10-20)



<a name="0.1.22"></a>
## [0.1.22](https://github.com/nativescript-vue/nativescript-vue/compare/v0.1.21...v0.1.22) (2017-10-15)



<a name="0.1.21"></a>
## [0.1.21](https://github.com/nativescript-vue/nativescript-vue/compare/v0.1.20...v0.1.21) (2017-10-15)



<a name="0.1.20"></a>
## [0.1.20](https://github.com/nativescript-vue/nativescript-vue/compare/v0.1.19...v0.1.20) (2017-10-15)



<a name="0.1.19"></a>
## [0.1.19](https://github.com/nativescript-vue/nativescript-vue/compare/v0.1.18...v0.1.19) (2017-10-15)



<a name="0.1.18"></a>
## [0.1.18](https://github.com/nativescript-vue/nativescript-vue/compare/v0.1.17...v0.1.18) (2017-10-15)



<a name="0.1.17"></a>
## [0.1.17](https://github.com/nativescript-vue/nativescript-vue/compare/v0.1.16...v0.1.17) (2017-10-13)



<a name="0.1.16"></a>
## [0.1.16](https://github.com/nativescript-vue/nativescript-vue/compare/v0.1.15...v0.1.16) (2017-10-09)



<a name="0.1.15"></a>
## [0.1.15](https://github.com/nativescript-vue/nativescript-vue/compare/v0.1.14...v0.1.15) (2017-10-04)



<a name="0.1.14"></a>
## [0.1.14](https://github.com/nativescript-vue/nativescript-vue/compare/v0.1.13...v0.1.14) (2017-10-04)



<a name="0.1.13"></a>
## [0.1.13](https://github.com/nativescript-vue/nativescript-vue/compare/v0.1.12...v0.1.13) (2017-10-04)



<a name="0.1.12"></a>
## [0.1.12](https://github.com/nativescript-vue/nativescript-vue/compare/v0.1.11...v0.1.12) (2017-10-01)



<a name="0.1.11"></a>
## [0.1.11](https://github.com/nativescript-vue/nativescript-vue/compare/v0.1.10...v0.1.11) (2017-10-01)



<a name="0.1.10"></a>
## [0.1.10](https://github.com/nativescript-vue/nativescript-vue/compare/v0.1.9...v0.1.10) (2017-09-28)



<a name="0.1.9"></a>
## [0.1.9](https://github.com/nativescript-vue/nativescript-vue/compare/v0.1.8...v0.1.9) (2017-09-26)



<a name="0.1.8"></a>
## [0.1.8](https://github.com/nativescript-vue/nativescript-vue/compare/v0.1.7...v0.1.8) (2017-09-26)



<a name="0.1.7"></a>
## [0.1.7](https://github.com/nativescript-vue/nativescript-vue/compare/v0.1.6...v0.1.7) (2017-09-25)



<a name="0.1.6"></a>
## [0.1.6](https://github.com/nativescript-vue/nativescript-vue/compare/v0.1.5...v0.1.6) (2017-09-19)



<a name="0.1.5"></a>
## [0.1.5](https://github.com/nativescript-vue/nativescript-vue/compare/v0.1.4...v0.1.5) (2017-08-10)



<a name="0.1.4"></a>
## [0.1.4](https://github.com/nativescript-vue/nativescript-vue/compare/v0.1.3...v0.1.4) (2017-07-14)



<a name="0.1.3"></a>
## [0.1.3](https://github.com/nativescript-vue/nativescript-vue/compare/v0.1.2...v0.1.3) (2017-07-09)



<a name="0.1.2"></a>
## 0.1.2 (2017-07-09)



