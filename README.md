# hex-matrix-mathlib

Mathlib correspondence proofs for [`hex-matrix`](https://github.com/kim-em/hex-matrix):
the dense integer-matrix core's operations and the Bareiss determinant are shown
to agree with Mathlib's `Matrix` / `Matrix.det`. Proof-only (no benchmarks).

```
require HexMatrixMathlib from git "https://github.com/kim-em/hex-matrix-mathlib.git" @ "<rev>"
```

Depends on `hex-matrix` and Mathlib (both pinned). Development happens in
[`hex-dev`](https://github.com/kim-em/hex-dev).
