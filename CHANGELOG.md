# Changelog
All notable changes to this project will be documented in this file.

## [Unreleased]

- Fix APP_BASE_URL slash (/) escaping
- Update plugins (eth-common@2.1.2, eth-lite@2.1.0)
- Allow custom ETH currency symbol
- Fix search results clicks not working on touchpads and with slower mouse clicks
- Support deployments on a domain sub-path (e.g. https://my.domain.tld/lite-explorer) via `APP_BASE_PATH` build-time env.
- Cosmetic updates to theme colors
- Fix Hotjar styling

## [1.0.0-beta.5] - 2019-06-21
- Add support for plugins through the [Alethio CMS](https://github.com/Alethio/cms)
- Support Basic Auth when connecting to the Ethereum node
- Fixed various bugs and issues
- Breaking changes
    - Remove all previous env vars except `APP_NODE_URL` and `APP_BASE_URL`
    - Remove network selector (better solution on the way)
    - Remove file scheme support (requires HTTP server)
    - Remove # routing