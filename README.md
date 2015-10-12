# Memot Docker Image

[![Docker Repository on Quay.io](https://quay.io/repository/dtan4/memot/status "Docker Repository on Quay.io")](https://quay.io/repository/dtan4/memot)
[![MIT License](http://img.shields.io/badge/license-MIT-blue.svg?style=flat)](LICENSE)

Docker Image for [Memot](https://github.com/dtan4/memot).
Please see [Memot Github repository](https://github.com/dtan4/memot) for more information about Memot.

## Image Repository

[__quay.io/dtan4/memot__](https://quay.io/repository/dtan4/memot)

## Supported Tags

- `latest`
  - Ruby 2.2.3
  - Memot 0.1.0 [![Gem Version](https://badge.fury.io/rb/memot.svg)](https://badge.fury.io/rb/memot)

## Usage

```bash
$ docker run \
    --rm \
    -e MEMOT_DROPBOX_APP_KEY=... \
    -e MEMOT_DROPBOX_APP_SECRET=... \
    -e MEMOT_DROPBOX_ACCESS_TOKEN=... \
    -e MEMOT_EVERNOTE_TOKEN=... \
    -e MEMOT_EVERNOTE_SANDBOX=false \
    -e MEMOT_NOTES=... \
    quay.io/dtan4/memot:latest \
    memot -i 30
```

## License

[![MIT License](http://img.shields.io/badge/license-MIT-blue.svg?style=flat)](LICENSE)
