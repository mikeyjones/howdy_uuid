# howdy_uuid

[![Package Version](https://img.shields.io/hexpm/v/howdy_uuid)](https://hex.pm/packages/howdy_uuid)
[![Hex Docs](https://img.shields.io/badge/hex-docs-ffaff3)](https://hexdocs.pm/howdy_uuid/)

A Gleam project

## Quick start

```gleam
    import howdy/uuid

    // Generation
    uuid.v4_string()
    // -> "f7e321c7-4a4b-4287-a8b8-1ae35b5538ce"

    // Decoding
    "f7e321c7-4a4b-4287-a8b8-1ae35b5538ce"
        |> uuid.from_string()
        |> result.map(uuid.version)
    // -> Ok(uuid.V4)
```

## Installation

If available on Hex this package can be added to your Gleam project:

```sh
gleam add howdy_uuid
```

and its documentation can be found at <https://hexdocs.pm/howdy_uuid>.
