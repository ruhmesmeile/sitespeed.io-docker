# browsertime

This Docker get you [Browsertime](https://github.com/tobli/browsertime) 1.0.0-alpha with Chrome and Firefox installed.

## Usage

The ```--rm -v "$(pwd)":/browsertime``` will make the result stored on your host.

### Timings using Chrome
```
docker run --privileged -v "$(pwd)":/browsertime  sitespeedio/browsertime browsertime https://www.sitespeed.io -b chrome --experimental.video
```

### Timings using Firefox
```
 docker run --privileged -v "$(pwd)":/browsertime  sitespeedio/browsertime browsertime https://www.sitespeed.io -b firefox --experimental.video
```
