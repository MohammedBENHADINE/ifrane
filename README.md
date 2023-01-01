# MCUKernel

MCUKernel is a lightweight and fast operating system kernel written in Rust. It is designed to be easy to use and extend.

## Features

- Multithreading support
- Virtual memory management
- Basic userland support (syscalls, libc)
- Simple but powerful shell

## Building

To build MCUKernel, you will need a Rust compiler and the `cargo` build tool.

First, clone the repository:

```
git clone https://github.com/bennaniaya/mcukernel.git
cd mcukernel
```
Then, build the kernel with:
```
cargo build
```
To run the kernel in QEMU, use:
```
cargo run
```

## Contributing

We welcome contributions to MCUKernel! If you have an idea for a new feature or have found a bug, please open an issue on GitHub.

To contribute code, fork the repository and create a new branch with your changes. Then, open a pull request against the `master` branch.

## License

MCUKernel is licensed under the MIT License. See [LICENSE](LICENSE) for more information.
