# bsc-sentry-patch

The patch for BSC sentries

# Installation

Download the patch:
```bash
git clone https://github.com/bloXroute-Labs/bsc-sentry-patch
```

Apply patch to your [bsc](https://github.com/bnb-chain/bsc) node source code:
```bash
git apply /path/to/announce_only.patch
```

Build geth:
```bash
make geth
```

Run as you usually do.