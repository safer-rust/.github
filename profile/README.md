## Working Group on Unsafe Rust
This organization focuses on unsafe Rust, with an emphasis on the proper usage of unsafe code to ensure memory safety in real-world Rust system development.

## Vision
To mitigate the risks associated with unsafe code usage in the Rust ecosystem.

## Rationale
Documentation for unsafe code is an essential companion to the code itself. 
It serves not only as a protocol between library providers and users, but also as a bridge toward formally verifying code soundness. 
Therefore, establishing systematic and reliable ways to document and verify unsafe code is crucial for improving the safety of the Rust ecosystem.


### Roadmap 
- Establish a standard for documenting unsafe code. See the [draft](https://github.com/safer-rust/rust-safety-standard).
- Provide an ergonomic way to document unsafe code. See the [safety-tag](https://github.com/safer-rust/safety-tags) project.
- Make the documentation convertible into contracts, which is also the goal of the [safety-tag](https://github.com/safer-rust/safety-tags) project.
- Automatically verify the soundness of unsafe code usage. See the [RAPx](https://github.com/safer-rust/RAPx) project.
