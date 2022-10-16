# wasmtest
A simple test of compiling C to WebAssembly

#Compiling

This is compiled using [emscripten](https://emscripten.org).

Run:

`emcc hello.c -o hello.js`

This should create two files, `hello.js` and `hello.wasm`

To test it has built successfully, run the javascript using node:

`node hello.js`
