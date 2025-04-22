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

* `okapi_url`
* `okapi_tenant`
* `okapi_username`
* `okapi_password`

The `okapi_url` must not end with a slash.

Example for folio-etesting-snapshot-kong:

| name | value |
| --- | --- |
| `okapi_url` | `https://folio-etesting-snapshot-kong.ci.folio.org` |
| `okapi_tenant` | `diku` |
| `okapi_username` | `diku_admin` |
| `okapi_password` | `admin` |

https://folio-org.atlassian.net/wiki/spaces/FOLIOtips/pages/952270854/Bruno has more details how to use Bruno with FOLIO.
