```
% rustup run nightly-2017-07-06 cargo build
    Finished dev [unoptimized + debuginfo] target(s) in 0.0 secs
% rustup run nightly cargo build 
   Compiling capnpc-segfault v0.1.0 (file:///home/faux/code/testcase/capnpc-segfault)
error: failed to run custom build command for `capnpc-segfault v0.1.0 (file:///home/faux/code/testcase/capnpc-segfault)`
process didn't exit successfully: `/home/faux/code/testcase/capnpc-segfault/target/debug/build/capnpc-segfault-ab9e5352d648474a/build-script-build` (signal: 11, SIGSEGV: invalid memory reference)
% rustup run nightly rustc --version       
rustc 1.20.0-nightly (696412de7 2017-07-06)
```
