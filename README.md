# SigmaOS-microphone

Microphone management (ALSA/PulseAudio input devices, capture)

- **Category:** Desktop
- **Engine:** microphone
- **Tier:** 2
- **Language:** Rust
- **Provides:** sigmamicrophone

Part of the [SigmaOS](https://github.com/AaryanSinghChauhan09/SigmaOS)
multi-repository component ecosystem.

## Build & Test

```sh
cargo build
cargo test
```

## Contract

This component declares its interface in `COMPONENT.toml`:

- `provides` — capabilities other components may depend on
- `depends_on` — component names this component requires

## License

Apache-2.0 — see [LICENSE](LICENSE).
