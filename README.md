# munin-tickers

Crypto, forex and stock tickers for munin

[![Build Status](https://travis-ci.org/nijel/munin-tickers.svg?branch=master)](https://travis-ci.org/nijel/munin-tickers)
[![codecov](https://codecov.io/gh/nijel/munin-tickers/branch/master/graph/badge.svg)](https://codecov.io/gh/nijel/munin-tickers)

This is really hacky set of plugins for [Munin](http://munin-monitoring.org/)
to be able to monitor prices of various assets.

Most of the plugins use HTML scraping so they are quite fragile, use with
caution.

Curently supported sources:

* [Bitstamp](https://www.bitstamp.net/)
* [Conseq](https://www.conseq.cz/)
* [1Forge](https://1forge.com/)
* [ING Bank](http://www.ingbank.cz/)
* [Partners IS](http://www.partnersis.cz/)
* [Prague Stock Exchange](https://www.pse.cz/)
* CZK exchange rates from several banks:
    * [ČNB](http://www.cnb.cz/)
    * [Fio](https://www.fio.cz/)
    * [UniCredit Bank](https://www.unicreditbank.cz/)
    * [Komerční banka](https://www.kb.cz/)
    * [ČSOB](https://www.csob.cz/portal/)
