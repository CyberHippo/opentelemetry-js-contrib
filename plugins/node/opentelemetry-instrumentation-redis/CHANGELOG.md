# Changelog

## [0.29.0](https://github.com/open-telemetry/opentelemetry-js-contrib/compare/instrumentation-redis-v0.28.0...instrumentation-redis-v0.29.0) (2022-03-02)


### ⚠ BREAKING CHANGES

* **mysql*,redis:** net.peer.ip -> db.connection_string

### Bug Fixes

* **mysql*,redis:** net.peer.ip -> db.connection_string ([bf39b90](https://github.com/open-telemetry/opentelemetry-js-contrib/commit/bf39b908fd64cec92c862b2deca5d760ddcf4509))
* **opentelemetry-instrumentation-redis:** add condition before error print ([#897](https://github.com/open-telemetry/opentelemetry-js-contrib/issues/897)) ([f1d2fd0](https://github.com/open-telemetry/opentelemetry-js-contrib/commit/f1d2fd084c8e3e494e3606c4eca53158495f43f6))

## [0.28.0](https://www.github.com/open-telemetry/opentelemetry-js-contrib/compare/instrumentation-redis-v0.27.0...instrumentation-redis-v0.28.0) (2022-01-24)


### Features

* re-enable TAV ([#823](https://www.github.com/open-telemetry/opentelemetry-js-contrib/issues/823)) ([2e14f46](https://www.github.com/open-telemetry/opentelemetry-js-contrib/commit/2e14f46b3f7221ae51ffa12313997f007c300e21))


### Bug Fixes

* redis instrumentation startup stream check [#666](https://www.github.com/open-telemetry/opentelemetry-js-contrib/issues/666) ([#818](https://www.github.com/open-telemetry/opentelemetry-js-contrib/issues/818)) ([81b3190](https://www.github.com/open-telemetry/opentelemetry-js-contrib/commit/81b3190af64bda14f87c5b0cbd6172bafda26408))
* rename lerna's --include-filtered-dependencies option ([#817](https://www.github.com/open-telemetry/opentelemetry-js-contrib/issues/817)) ([cf268e7](https://www.github.com/open-telemetry/opentelemetry-js-contrib/commit/cf268e7a92b7800ad6dbec9ca77466f9ee03ee1a))
* use localhost for services in CI ([#816](https://www.github.com/open-telemetry/opentelemetry-js-contrib/issues/816)) ([f497313](https://www.github.com/open-telemetry/opentelemetry-js-contrib/commit/f4973133e86549bbca301983085cc67788a10acd))


### Dependencies

* The following workspace dependencies were updated
  * devDependencies
    * @opentelemetry/contrib-test-utils bumped from ^0.28.0 to ^0.29.0

## [0.27.0](https://www.github.com/open-telemetry/opentelemetry-js-contrib/compare/instrumentation-redis-v0.26.0...instrumentation-redis-v0.27.0) (2021-11-30)


### Features

* use latest instrumentation base ([#769](https://www.github.com/open-telemetry/opentelemetry-js-contrib/issues/769)) ([7aff23e](https://www.github.com/open-telemetry/opentelemetry-js-contrib/commit/7aff23ebebbe209fa3b78c2e7f513c9cd2231be4))


### Dependencies

* The following workspace dependencies were updated
  * devDependencies
    * @opentelemetry/contrib-test-utils bumped from ^0.27.0 to ^0.28.0

## [0.26.0](https://www.github.com/open-telemetry/opentelemetry-js-contrib/compare/instrumentation-redis-v0.25.0...instrumentation-redis-v0.26.0) (2021-10-22)


### Features

* support API and SDK 1.0 ([#706](https://www.github.com/open-telemetry/opentelemetry-js-contrib/issues/706)) ([096b694](https://www.github.com/open-telemetry/opentelemetry-js-contrib/commit/096b694bbc3079f0ab4ee0462869b10eb8185202))



### Dependencies

* The following workspace dependencies were updated
  * devDependencies
    * @opentelemetry/contrib-test-utils bumped from ^0.25.0 to ^0.27.0
