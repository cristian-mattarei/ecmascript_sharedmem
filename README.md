# ecmascript_sharedmem

This is a specification for Shared Memory and Atomics for ECMAScript, a proposal submitted to Ecma TC39 and currently at Stage 2 in the ECMAScript approval process.

## Documentation and other materials

* [Formatted specification](http://tc39.github.io/ecmascript_sharedmem/shmem.html)
* [Simple tutorial introduction](TUTORIAL.md)
* [Demo programs and other examples](DEMOS.md)
* [Frequently asked questions](FAQ.md)
* [High-level design issues, cross-cutting concerns, security concerns, etc](DISCUSSION.md)
* Slide decks for presentations given to Ecma TC39:
  * [September 2015](https://github.com/tc39/ecmascript_sharedmem/blob/master/tc39/presentation-sept-2015.odp)
  * [January 2016](https://github.com/tc39/ecmascript_sharedmem/blob/master/tc39/presentation-jan-2016.odp)
* [asm.js companion specification](http://tc39.github.io/ecmascript_sharedmem/asmjs_shmem.html)

## Firefox and Chrome implementations

Both Firefox and Chrome ship with prototype implementations of the proposal; these are largely compatible.

* The feature is enabled by default in Firefox Nightly; starting with Firefox 46, users of Developer Edition, Aurora, Beta, and Release can visit `about:config` and set the option `javascript.options.shared_memory` to `true`.
* The feature is off by default in Chrome, but can be enabled by passing the command line options `--js-flags=--harmony-sharedarraybuffer` and `--enable-blink-feature=SharedArrayBuffer`.  (Known to work in Chrome 48.)

## Miscellaneous

The sources for the specs are in the tc39/ subdirectory and the formatted versions are generated with the `format.sh` script.

