# automerge-tldraw

A React hook which binds a TLDraw instance to a dedicated Automerge document. Also included is a DEFAULT_STORE.

Usage of TLDraw is subject to the TLDraw license: it is free for non-commercial projects, but for commercial projects you must acquire a license.

The current implementation is passably efficient but could be further optimized. It works reasonably well on complex drawings. It's likely there are still bugs and there are no tests. The presence API is very sketchy and needs work.

(Pull requests are welcome!)

## Usage

See the [example repo](https://github.com/pvh/tldraw-automerge-example). Call get a TLStore via `const store = useAutomerge(docHandle, userId)` and pass that to the `<TLDraw>` component.

## Credits

This work is based on example code by Steve Ruiz of TLDraw and also some work by Liangrun Da.
