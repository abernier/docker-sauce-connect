# Docker Sauce Labs Connect

This docker image runs [Sauce Labs Connect](https://wiki.saucelabs.com/display/DOCS/Sauce+Connect+Proxy) 4.5.3 on Java 8.

# Usage

```sh
docker run -p 4445:4445 -e SAUCE_USERNAME=abernier -e SAUCE_ACCESS_KEY=********-****-****-****-************ sauce-connect -x https://eu-central-1.saucelabs.com/rest/v1
```
