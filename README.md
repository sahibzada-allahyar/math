# Mathematics

Research papers and expository writing by Sahibzada Allahyar and collaborators, covering gaps between primes and the Riemann hypothesis in analytic number theory, and circuit lower bounds in computational complexity.

## Infinitely many small prime gaps of 180 or less

*Sahibzada Allahyar and Theodoros Yianni · 22 November 2026 · Zenodo v1 · 34 pages*

The paper shows that infinitely many pairs of consecutive primes differ by at most 180, assuming a recently proposed estimate for exponential sums over finite fields. The previous bound under the same hypothesis was 182, and the best bound known without it is 186. The deduction is verified in the Lean 4 proof assistant from four explicitly stated exponential sum bounds and an explicit list of numerical inequalities.

[Read the paper](preprint/prime-gaps-180/prime_gaps_at_most_180.pdf) · [Lean proof](preprint/prime-gaps-180/lean_proof.zip) · [Numerical checks](preprint/prime-gaps-180/numerical_checks.zip) · [Zenodo publication](https://doi.org/10.5281/zenodo.24430219) · [Cite the paper](#citing-the-prime-gaps-paper)

## From theta lifts to zeta zeros

*Exposition by Sahibzada Allahyar · 20 November 2026 · Revision 2 · 51 pages*

This guide to Levent Alpöge’s announced argument for the Riemann hypothesis explains how divisibility of theta periods enters a bound on prime sums. Section 1 introduces the main ideas. Sections 2–4 prove the implication from a bound on a smoothed prime sum to the Riemann hypothesis. Section 11 identifies the arithmetic results the exposition uses from Alpöge’s Lean formalization.

[Read the latest PDF](preprint/alpoge-riemann/reconstruction.pdf) · [Cite this exposition](#citing-this-exposition)

## Circuit lower bounds for 3-SAT

*Theodoros Yianni and Sahibzada Allahyar (equal first authors) · 3 November 2026 · Zenodo v5*

The paper gives a lower bound of $(17/7-o(1))n$ gates for 3-SAT in the authors’ binary encoding, where $n$ counts the bits describing the formula. The circuits may use arbitrary two-input Boolean gates, unrestricted depth, and shared intermediate results.

[Read the 3-SAT paper](preprint/3SAT_Circuit_Lower_Bound.pdf) · [Zenodo publication](https://zenodo.org/records/23925452) · [Lean proof packages](#lean-proofs) · [Cite the paper](#citing-the-3-sat-paper)

### Lean proofs

- [7/3 proof package](lean/lean_proofs_7_3.zip)
- [12/5 proof package](lean/lean_proofs_12_5.zip)
- [17/7 proof package](lean/lean_proofs_17_7.zip)

Each archive includes source files, pinned dependencies, and build instructions.

## Citation

### Citing the prime gaps paper

Allahyar, S., & Yianni, T. (2026). *Infinitely many small prime gaps of 180 or less* (Version v1). Zenodo. [DOI 10.5281/zenodo.24430219](https://doi.org/10.5281/zenodo.24430219).

<details>
<summary>BibTeX</summary>

```bibtex
@misc{allahyar_yianni_2026_primegaps180,
  author       = {Allahyar, Sahibzada and Yianni, Theodoros},
  title        = {Infinitely many small prime gaps of 180 or less},
  year         = {2026},
  month        = nov,
  howpublished = {Zenodo preprint},
  version      = {v1},
  doi          = {10.5281/zenodo.24430219},
  url          = {https://doi.org/10.5281/zenodo.24430219}
}
```

</details>

The DOI above identifies the version containing the paper, the Lean proof and the numerical checks. The [all-versions DOI](https://doi.org/10.5281/zenodo.24430218) resolves to the latest published version.

### Citing this exposition

For the announced argument and its Lean formalization, cite [Levent Alpöge’s original announcement](https://alpo.ge/remark.pdf). It describes his collaboration with Claude and links the Lean release in the first footnote.

If you draw on the presentation in this manuscript, you can cite the exposition as follows.

Allahyar, Sahibzada. *From theta lifts to zeta zeros: A reconstruction of Levent Alpöge’s announced argument.* Expository manuscript, revision 2, 20 November 2026, 51 pp. [Permanent link to this revision](https://github.com/sahibzada-allahyar/math/blob/rh-exposition-2026-11-20-r2/preprint/alpoge-riemann/reconstruction.pdf).

[BibTeX for this revision](https://raw.githubusercontent.com/sahibzada-allahyar/math/rh-exposition-2026-11-20-r2/preprint/alpoge-riemann/citation.bib) · [Earlier 46-page edition](https://github.com/sahibzada-allahyar/math/blob/rh-exposition-2026-11-20/preprint/alpoge-riemann/reconstruction.pdf)

<details>
<summary>BibTeX</summary>

```bibtex
@misc{allahyar2026theta,
  author       = {Allahyar, Sahibzada},
  title        = {From theta lifts to zeta zeros: A reconstruction of {Levent Alpöge}'s announced argument},
  year         = {2026},
  month        = nov,
  howpublished = {Expository manuscript},
  note         = {Revision 2, 20 November 2026, 51 pages},
  url          = {https://github.com/sahibzada-allahyar/math/blob/rh-exposition-2026-11-20-r2/preprint/alpoge-riemann/reconstruction.pdf}
}
```

</details>

### Citing the 3-SAT paper

Yianni, T., & Allahyar, S. (2026). *The first lower bound improvement on the unrestricted circuit complexity of 3-SAT. A step towards P ≠ NP.* (Version v5). Zenodo. [DOI 10.5281/zenodo.23925452](https://doi.org/10.5281/zenodo.23925452).

<details>
<summary>BibTeX</summary>

```bibtex
@misc{yianni_allahyar_2026_3sat,
  author       = {Yianni, Theodoros and Allahyar, Sahibzada},
  title        = {The first lower bound improvement on the unrestricted circuit complexity of {3-SAT}. A step towards {$P \neq NP$}.},
  year         = {2026},
  month        = nov,
  howpublished = {Zenodo preprint},
  version      = {v5},
  doi          = {10.5281/zenodo.23925452},
  url          = {https://doi.org/10.5281/zenodo.23925452}
}
```

</details>

The DOI above identifies the version containing the paper and all three Lean proof packages. The [all-versions DOI](https://doi.org/10.5281/zenodo.23892861) resolves to the latest published version.
