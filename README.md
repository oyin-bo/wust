# WebAssembly Rust environment

This is an attempt to make rust (and cargo?) portable on top of WASM.

Current (as of 12th Jan 2025) requirements to build this code:

* [Look at Rust docs for clues](https://rustc-dev-guide.rust-lang.org/building/how-to-build-and-run.html)
* Check out this git repository
* Do the submodule init/update to get rust source
* Go to rust and try `./x setup`
  * if it fails, probably dependency failures
  * if you're on Linux, do `sudo apt install build-essentials`

That's where I am at currently, will check in later with more.
