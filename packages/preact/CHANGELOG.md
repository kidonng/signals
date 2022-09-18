# @preact/signals

## 1.0.4

### Patch Changes

- [#147](https://github.com/preactjs/signals/pull/147) [`3556499`](https://github.com/preactjs/signals/commit/355649903b766630b62cdd0f90a35d3eafa99fa9) Thanks [@developit](https://github.com/developit)! - Improve performance when rendering Signals as Text in Preact.

* [#148](https://github.com/preactjs/signals/pull/148) [`b948745`](https://github.com/preactjs/signals/commit/b948745de7b5b60a20ce3bdc5ee72d47d47f38ec) Thanks [@marvinhagemeister](https://github.com/marvinhagemeister)! - Move `types` field in `package.json` to the top of the entry list to ensure that TypeScript always finds it.

- [#153](https://github.com/preactjs/signals/pull/153) [`0da9ce3`](https://github.com/preactjs/signals/commit/0da9ce3c6f57cef67c3e84f0d829421aee8defff) Thanks [@developit](https://github.com/developit)! - Optimize the performance of prop bindings in Preact

- Updated dependencies [[`f2ba3d6`](https://github.com/preactjs/signals/commit/f2ba3d657bf8169c6ba1d47c0827aa18cfe1c947), [`160ea77`](https://github.com/preactjs/signals/commit/160ea7791f3adb55c562f5990e0b4848d8491a38), [`4385ea8`](https://github.com/preactjs/signals/commit/4385ea8c8358a154d8b789685bb061658ce1153f), [`b948745`](https://github.com/preactjs/signals/commit/b948745de7b5b60a20ce3bdc5ee72d47d47f38ec), [`00a59c6`](https://github.com/preactjs/signals/commit/00a59c6475bd4542fb934474d82d1e242b2ac870)]:
  - @preact/signals-core@1.1.1

## 1.0.3

### Patch Changes

- ab5bd99: Fix swapping and HMR for signals when used as text

## 1.0.2

### Patch Changes

- 2383684: Correctly replace props-value with peeked value
- Updated dependencies [5644c1f]
  - @preact/signals-core@1.0.1

## 1.0.1

### Patch Changes

- c7c0d91: Add marker for devtools to `Text` that is created when a signal is passed into JSX

## 1.0.0

### Major Changes

- 2ee8489: The v1 release for the signals package, we'd to see the uses you all
  come up with and are eager to see performance improvements in your
  applications.

### Patch Changes

- Updated dependencies [ab22ec7]
- Updated dependencies [2ee8489]
- Updated dependencies [b56abf3]
  - @preact/signals-core@1.0.0

## 0.0.4

### Patch Changes

- 702a9c5: Update TypeScript types to mark computed signals as readonly
- 5f8be64: Optimize size of CJS & UMD bundles.
- Updated dependencies [702a9c5]
  - @preact/signals-core@0.0.5

## 0.0.3

### Patch Changes

- 812e7b5: Fix `batch()` not re-exported from preact adapter
- 8e9bf67: Fix incorrect TypeScript paths
- f71ea95: Avoid incrementing Preact adapter when core changes
- Updated dependencies [4123d60]
  - @preact/signals-core@0.0.4

## 0.0.2

### Patch Changes

- 1e4dac5: Add `prepublishOnly` scripts to ensure we're publishing fresh packages
- 9ccf359: Align signal rendering in Text positions with VDOM text rendering - skip rendering of `null`, `undefined` and `boolean` values.
- 1171338: Fix wrong path for TypeScript definitions in `package.json`
- Updated dependencies [1e4dac5]
  - @preact/signals-core@0.0.3
