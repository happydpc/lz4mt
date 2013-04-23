﻿# lz4mt

lz4mt is platform independent, multi-threading, [lz4 stream v1.4](https://docs.google.com/document/d/1gZbUoLw5hRzJ5Q71oPRN6TO4cRMTZur60qip-TE7BhQ/edit?pli=1) implementation in C++11.

## How to compile (MSVC2012)

 - Open `platform_msvc2012/lz4mt.sln`
 - Select platform and configuration.
 - Press F7 (build)

## How to compile (Linux)

 - Just run `make`.
 - `./lz4mt` will be build.

## Restriction

 - Some function is not implemented yet
   - `-y`: force overwrite.
   - stdin, stdout stream mode.

## See also

 - [lz4 Extremely Fast Compression algorithm](https://code.google.com/p/lz4/)
