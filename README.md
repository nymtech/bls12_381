# nym-bls12_381-fork

This is a temporary fork of zkcrypto's `bls12_381` crate until [https://github.com/zkcrypto/bls12_381/issues/10](https://github.com/zkcrypto/bls12_381/issues/10) is resolved. We have created this fork as we need to be able to serialize Gt so that we can create the lookup table for baby-step-giant-step algorithm. Our published crate uses the `temp/experimental-serdect-updated` branch.

For the original crate and readme, please refer to [https://github.com/zkcrypto/bls12_381](https://github.com/zkcrypto/bls12_381).
