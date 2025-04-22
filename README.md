# folio-bruno

A collection for the Bruno API client. Supports refresh token rotation (RTR).

## License

Copyright (C) 2025 The Open Library Foundation

This software is distributed under the terms of the Apache License,
Version 2.0. See the file "[LICENSE](LICENSE)" for more information.

## Install Bruno

Download the Bruno client from https://www.usebruno.com/downloads and
install it.

## Configure Global Environments

This Bruno collection requires these four variables being defined in a
global environment:

* `okapi\_url`
* `okapi\_tenant`
* `okapi\_username`
* `okapi\_password`

The `okapi\_url` must not end with a slash.

Example for folio-etesting-snapshot-kong:

| `okapi\_url` | `https://folio-etesting-snapshot-kong.ci.folio.org` |
| `okapi\_tenant` | `diku` |
| `okapi\_username` | `diku\_admin` |
| `okapi\_password` | `admin` |
