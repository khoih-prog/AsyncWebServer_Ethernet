# AsyncWebServer_Ethernet

[![arduino-library-badge](https://www.ardu-badge.com/badge/AsyncWebServer_Ethernet.svg?)](https://www.ardu-badge.com/AsyncWebServer_Ethernet)
[![GitHub release](https://img.shields.io/github/release/khoih-prog/AsyncWebServer_Ethernet.svg)](https://github.com/khoih-prog/AsyncWebServer_Ethernet/releases)
[![contributions welcome](https://img.shields.io/badge/contributions-welcome-brightgreen.svg?style=flat)](#Contributing)
[![GitHub issues](https://img.shields.io/github/issues/khoih-prog/AsyncWebServer_Ethernet.svg)](http://github.com/khoih-prog/AsyncWebServer_Ethernet/issues)

<a href="https://www.buymeacoffee.com/khoihprog6" title="Donate to my libraries using BuyMeACoffee"><img src="https://cdn.buymeacoffee.com/buttons/v2/default-yellow.png" alt="Donate to my libraries using BuyMeACoffee" style="height: 50px !important;width: 181px !important;" ></a>
<a href="https://www.buymeacoffee.com/khoihprog6" title="Donate to my libraries using BuyMeACoffee"><img src="https://img.shields.io/badge/buy%20me%20a%20coffee-donate-orange.svg?logo=buy-me-a-coffee&logoColor=FFDD00" style="height: 20px !important;width: 200px !important;" ></a>


---
---

## Table of contents

* [Changelog](#changelog)
  * [Releases v1.5.1](#releases-v151)
  * [Releases v1.5.0](#releases-v150)
  * [Releases v1.4.1](#releases-v141)

---
---

## Changelog

#### Releases v1.5.1

1. Add examples [Async_AdvancedWebServer_SendChunked](https://github.com/khoih-prog/AsyncWebServer_Ethernet/tree/main/examples/Async_AdvancedWebServer_SendChunked) and [AsyncWebServer_SendChunked](https://github.com/khoih-prog/AsyncWebServer_Ethernet/tree/main/examples/AsyncWebServer_SendChunked) to demo how to use `beginChunkedResponse()` to send large `html` in chunks
2. Use `allman astyle` and add `utils`

#### Releases v1.5.0

1. Support using `CString` to save heap to send `very large data`. Check [request->send(200, textPlainStr, jsonChartDataCharStr); - Without using String Class - to save heap #8](https://github.com/khoih-prog/Portenta_H7_AsyncWebServer/pull/8) and [All memmove() removed - string no longer destroyed #11](https://github.com/khoih-prog/Portenta_H7_AsyncWebServer/pull/11)
2. Add multiple examples to demo the new feature

#### Releases v1.4.1

1. Initial coding to port [ESPAsyncWebServer](https://github.com/me-no-dev/ESPAsyncWebServer) to ESP8266 boards using W5x00 / ENC28J60 Ethernet.
2. Add more examples.
3. Add debugging features.
4. Bump up to v1.4.1 to sync with [AsyncWebServer_WT32_ETH01 v1.4.1](https://github.com/khoih-prog/AsyncWebServer_WT32_ETH01).


