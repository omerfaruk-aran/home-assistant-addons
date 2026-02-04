## [2.0.1](https://github.com/RiDDiX/home-assistant-matter-hub/compare/v2.0.0...v2.0.1) (2026-02-04)


### Bug Fixes

* add water_heater to entity mapping dropdown and backend factories ([ccdda2b](https://github.com/RiDDiX/home-assistant-matter-hub/commit/ccdda2bc465aaa251e48a98d0f8d3ef89143f772))
* remove AutoMode feature from ClimateDevice to fix Behaviors have errors ([#82](https://github.com/RiDDiX/home-assistant-matter-hub/issues/82)) ([0a4af9e](https://github.com/RiDDiX/home-assistant-matter-hub/commit/0a4af9e473d0873a30306712762c9a710531d266))
* revert getSystemMode to v1.10.6 behavior - map Auto to Heat/Cool without AutoMode feature ([dd4fda3](https://github.com/RiDDiX/home-assistant-matter-hub/commit/dd4fda3198c5d573374e66b78cad58e2cd2986aa))
* suppress Invalid intervalMs errors to prevent FATAL crashes ([#74](https://github.com/RiDDiX/home-assistant-matter-hub/issues/74), [#76](https://github.com/RiDDiX/home-assistant-matter-hub/issues/76), [#79](https://github.com/RiDDiX/home-assistant-matter-hub/issues/79), [#80](https://github.com/RiDDiX/home-assistant-matter-hub/issues/80), [#82](https://github.com/RiDDiX/home-assistant-matter-hub/issues/82)) ([e171d0e](https://github.com/RiDDiX/home-assistant-matter-hub/commit/e171d0e04eabceb1689508f693251986811ebeb8))
* thermostat auto mode now correctly displays on Matter controllers ([#71](https://github.com/RiDDiX/home-assistant-matter-hub/issues/71)) ([d348265](https://github.com/RiDDiX/home-assistant-matter-hub/commit/d348265202541f3a61f4120af5e2b848d0b92615))


### Features

* add EntityIsolationService to isolate problematic entities at runtime ([8d81fd2](https://github.com/RiDDiX/home-assistant-matter-hub/commit/8d81fd24d8b014274d8288cbcb5e02e5715fbfaf))
* merge alpha fixes and update README for v1.10.5 stable release ([6ea28a3](https://github.com/RiDDiX/home-assistant-matter-hub/commit/6ea28a3a2a49712f03e33a0a801d8f53f75439c4))
* merge alpha into main for v2.0.0 release ([3f94d6d](https://github.com/RiDDiX/home-assistant-matter-hub/commit/3f94d6d9b13b54bd574dcfc7829629540550b052))
