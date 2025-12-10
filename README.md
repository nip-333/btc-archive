# btc-archive

Bitcoin block header archive for [NIP-333](https://nip-333.github.io).

## Contents

- `btc.archive.bin` — All completed epochs (immutable, grows each epoch)
- `btc.archive.bin.sha256` — SHA256 checksum

## Format

Raw binary, 80 bytes per header, concatenated in ascending order from block 0.

## Download

```
https://nip-333.github.io/btc-archive/btc.archive.bin
```

## Links

- [NIP-333 Specification](https://nip-333.github.io/spec/)
- [btc-current](https://github.com/nip-333/btc-current) — Current epoch headers
