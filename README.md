# market_profile
graphically display the market profile for any security using data downloaded from Tiingo

This is demonstration code only - it is not meant to be run straight out of the box.
Requires, at a minimum, a TIINGO data account from https://api.tiingo.com/. This account is currently free
for individual use and has a fairly sizable connection threshold to allow the downloading of
intraday and end-of-day symbol data. A second required parameter is the location of the symbol cache to minimize
usage of Tiingo bandwidth. Every full day of data, once downloaded, is cached for later use.

The reason for creating this code was to produce a (very) rough approximation of market profile tools
from professional trading platforms. This allows one to quickly see how the market auction for a particular
symbol is taking shape during the day.

For a detailed description of the Steidlmayer Market Profile TPO (Time Price Opportunity), see
https://en.wikipedia.org/wiki/Market_profile.

The Tiingo-python API is documented at https://tiingo-python.readthedocs.io
