# Change Log
All notable changes to this project will be documented in this file.

## [2.1.0] - 2018-03-02

### Added

- Request to /stock/time-series endpoint
- Request to /official-price endpoint
- Request to /stock/ohlc endpoint
- Request to /stock/short-interest endpoint 
- Request to /stock/threshold-securities endpoint
- Request to /ref-data/daily-list/symbol-directory endpoint
- Request to /ref-data/daily-list/corporate-actions endpoint
- Request to /ref-data/daily-list/dividends endpoint
- Request to /ref-data/daily-list/next-day-ex-date endpoint

### Changed

- Fixed WebSocket implementation, it is actually working right now
- Reorganized Chart model and requests. Library supports all types of chart requests 
- Increased code coverage

## [2.0.1] - 2017-12-28

### Added

- Fields High & Low to Quote object

## [2.0.0] - 2017-11-25

### Added

- Support to Stock API Endpoint
- Support to new Market Data API Endpoints

### Changed

- Library design, introduced new generic way to create requests. 

## [1.1.0] - 2017-04-21

### Added

- Support to RefData/Symbols API Endpoint

## [1.0.2] - 2017-03-21

### Added

- Introduced WebSockets implementation for Market Volume data
- Lots of unit tests

### Changed 

- Refactored WebSocket implementation. Separated objects for different Async Requests.
- Fixed problem with Double values display


[1.0.2]: https://github.com/WojciechZankowski/iextrading4j/compare/IT4J_RELEASE_1_0_1...IT4J_RELEASE_1_0_2
[1.1.0]: https://github.com/WojciechZankowski/iextrading4j/compare/IT4J_RELEASE_1_0_2...IT4J_RELEASE_1_1_0
[2.0.0]: https://github.com/WojciechZankowski/iextrading4j/compare/IT4J_RELEASE_1_1_0...IT4J_RELEASE_2_0_0
[2.0.1]: https://github.com/WojciechZankowski/iextrading4j/compare/IT4J_RELEASE_2_0_0...IT4J_RELEASE_2_0_1
[2.1.0]: https://github.com/WojciechZankowski/iextrading4j/compare/IT4J_RELEASE_2_0_1...IT4J_RELEASE_2_1_0
