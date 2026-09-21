# openssl-win64-v3.5.8

Prebuilt OpenSSL 3.5.8 libraries and headers for Windows x64, used as an
immutable pinned fallback dependency by Kurlyk.

## Provenance

```text
Upstream:             Shining Light Productions Win32/Win64 OpenSSL
Version:              3.5.8
Original filename:    Win64OpenSSL-3_5_8.exe
Original download URL: https://slproweb.com/download/Win64OpenSSL-3_5_8.exe
SHA256:               0125ee1ea63bf288630161e75b60554b83e00c739441233f8f9703dc4a8f32f9
Retrieved on:         2026-09-21
Architecture:         Windows x64
Toolchain / package type: MSVC-compatible full developer installer (not Light)
```

The SHA256 value is the checksum published in the official Shining Light
Productions hash manifest. The repository contains the extracted development
files needed by the Kurlyk CMake fallback; the original installer is not stored
here.

## Contents

```text
include/openssl/...
bin/libssl-3-x64.dll
bin/libcrypto-3-x64.dll
lib/VC/x64/MD/libssl.lib
lib/VC/x64/MD/libcrypto.lib
lib/VC/x64/MD/libssl_static.lib
lib/VC/x64/MD/libcrypto_static.lib
license.txt
```

The snapshot is intentionally kept at a fixed commit. Update it by importing a
new upstream installer into a new commit and recording its provenance above.
