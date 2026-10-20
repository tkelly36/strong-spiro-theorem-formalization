# A Strengthened Smoother-Spread Theorem

[Open the formalization viewer](https://tkelly36.github.io/strong-spiro-theorem-formalization/#StrongSpiroTheorem).

This static viewer presents the completed Trellis formalization of Tom Kelly's strengthened Spiro theorem, together with Spiro's Theorem 2.7 and its intermediate stopping conclusion. It includes paired TeX/Lean statements and proofs, searchable nodes, the dependency outline, and the Lean semantic closures of the statements.

The snapshot was exported from **Trellis cycle 117, Complete**, with **82/82 nodes reported closed**: 67 proof nodes, 14 definition nodes, and one special preamble. All 81 ordinary nodes have Lean and natural-language source panels. No captured Lean panel contains `sorry`, `admit`, or `sorryAx`.

## Reading the formalization

- [Strengthened theorem](https://tkelly36.github.io/strong-spiro-theorem-formalization/#StrongSpiroTheorem)
- [Spiro's Theorem 2.7](https://tkelly36.github.io/strong-spiro-theorem-formalization/#SpiroTheorem27)
- [Snapshot provenance](https://tkelly36.github.io/strong-spiro-theorem-formalization/#build-info)

Open a proof disclosure to compare the natural-language and Lean arguments. Click a cited node or a dependency to follow it. Each ordinary node also provides downloads of its displayed TeX and Lean excerpts.

## Source and validation

`snapshot/live-tablet.json` preserves the exported live-viewer panels and semantic-closure links. The viewer's Snapshot Info page records its SHA-256 and export details. This is a reading snapshot, not a standalone Lake checkout: the live viewer does not expose the Preamble source, toolchain and Lake files, final Git revision, or target axiom probes. Those are not reconstructed or claimed here. The excerpts omit their original file headers and should be read in the context of the original Lean project.

## Static page

`index.html` contains the complete viewer interface and exported proof data. It runs directly in a browser, with MathJax loaded from its public CDN for mathematical typesetting. GitHub Pages serves this file from the main branch. The viewer can download its embedded JSON data and each displayed Lean/TeX excerpt.

The export validation checks completeness, closed statuses, proof placeholders, dependency references, and acyclicity. It does not replace a fresh Lean kernel build or a human correspondence audit of the original project.

## Credits

The mathematical manuscript is by Tom Kelly. The formalization and semantic closures were produced with [Trellis](https://github.com/wpegden/trellis), created by Wesley Pegden, using Lean and Mathlib. The static reading interface follows the author's other Trellis formalization viewers.
