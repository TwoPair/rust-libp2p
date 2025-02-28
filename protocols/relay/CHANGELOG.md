# 0.7.0 [2022-02-22]

- Update to `libp2p-core` `v0.32.0`.

- Update to `libp2p-swarm` `v0.34.0`.

- Merge NetworkBehaviour's inject_\* paired methods (see PR 2445).

[PR 2445]: https://github.com/libp2p/rust-libp2p/pull/2445

# 0.6.1 [2022-02-02]

- Remove empty peer entries in `reservations` `HashMap`. See [PR 2464].

[PR 2464]: https://github.com/libp2p/rust-libp2p/pull/2464

# 0.6.0 [2022-01-27]

- Update dependencies.

- Migrate to Rust edition 2021 (see [PR 2339]).

[PR 2339]: https://github.com/libp2p/rust-libp2p/pull/2339

# 0.5.0 [2021-11-16]

- Use `instant` instead of `wasm-timer` (see [PR 2245]).

- Update dependencies.

[PR 2245]: https://github.com/libp2p/rust-libp2p/pull/2245

# 0.4.0 [2021-11-01]

- Make default features of `libp2p-core` optional.
  [PR 2181](https://github.com/libp2p/rust-libp2p/pull/2181)

- Update dependencies.

- Implement `Debug` for `RelayHandlerEvent` and `RelayHandlerIn`. See [PR 2183].

[PR 2183]: https://github.com/libp2p/rust-libp2p/pull/2183

# 0.3.0 [2021-07-12]

- Update dependencies.

# 0.2.0 [2021-04-13]

- Update `libp2p-swarm`.

# 0.1.0 [2021-03-17]

- First release supporting all major features of the circuit relay v1
  specification. [PR 1838](https://github.com/libp2p/rust-libp2p/pull/1838).
