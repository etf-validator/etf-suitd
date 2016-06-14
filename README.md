# Test driver for running running SoapUI based test projects

[![Apache License 2.0](https://img.shields.io/badge/license-Apache%202.0-blue.svg)](http://www.apache.org/licenses/LICENSE-2.0.html)
[![Latest version](http://img.shields.io/badge/latest%20version-1.0.5.5-blue.svg)](http://services.interactive-instruments.de/etfdev-af/release/de/interactive_instruments/etf/etf-suitd/1.0.5.5/etf-suitd-1.0.5.5.zip)
[![Build Status](https://services.interactive-instruments.de/etfdev-ci/buildStatus/icon?job=etf-suitd)](https://services.interactive-instruments.de/etfdev-ci/job/etf-suitd/)

The test driver is loaded by the etf framework at runtime. The test driver
executes [SoapUI](https://www.soapui.org/) based test projects for testing
services.

Please use the [etf-webapp project](https://github.com/interactive-instruments/etf-webapp) for
reporting [issues](https://github.com/interactive-instruments/etf-webapp/issues) or
[further documentation](https://github.com/interactive-instruments/etf-webapp/wiki).


The project can be build and installed by running the gradlew.sh/.bat wrapper with:
```gradle
$ gradlew build install
```

ETF component version numbers comply with the [Semantic Versioning Specification 2.0.0](http://semver.org/spec/v2.0.0.html).

ETF is an open source test framework developed by [interactive instruments](http://www.interactive-instruments.de/en) for testing geo network services and data.