# Final public release manifest — version 1.0.0, 31 October 2026

Repository entry: https://github.com/yide109/PLS-SEM-Compositional-Data/tree/main/final

This is the self-contained final analysis release. The author confirmed sharing authority for both sets of pseudonymized allocations. It contains one observation CSV, retaining all observed zeros; no original respondent identifiers, Excel linkage records, old nominal SN coordinates, historical outputs or raw survey workbooks are included. Retained order permits exact numerical reproduction; the two order-based match assumptions remain explicitly flagged. No new reuse license is granted on the authors' behalf.

Verified reproduction refits empirical point models, rotations and prediction and summarizes the completed Monte Carlo/bootstrap draws. It is not a claim of a new full Monte Carlo/bootstrap rerun. Full recomputation code is provided separately. Portable verification with R 4.6.2 and Python 3.12.14 passed; the completed draws were generated under R 4.6.1. The immutable GitHub commit for this release is recorded in the separately delivered repository-version record and editorial checklist, because a commit cannot include its own identifier.

The manifest excludes its own digest. Each listed file is necessary to run, interpret, check, cite or build the final paper; per-file SHA-256 values follow.

| File | Bytes | Paper purpose | SHA-256 |
|---|---:|---|---|
| `.gitignore` | 84 | Exclude generated output directories and local temporary artifacts. | `5668e7dfc8cd080dbb2cd89ebd571ad7d180f4d49b998d88f5f19f58e54be5fc` |
| `build_manuscript.py` | 1148 | Compile the standalone manuscript with generated tables. | `bf31bbc26012ac69b1c17f03b1387d28ab2b901b7ea020a2b56ced311cdca036` |
| `CITATION.cff` | 513 | Repository/version citation metadata. | `be74e8469549fdc57b73492e9378b7b2e2e52771372fd17de1ba94c2d0d03557` |
| `data/analysis.csv` | 86755 | Tables 6–9 and empirical results: 506 observations, 33 original components, folds and matching flags. | `7adb8bc29a2867db1f5c397f953001eadbefd501120de6bf617c5c8cb14b62c0` |
| `data/dictionary.csv` | 7251 | Variable definitions, units, role and interpretation; Appendix A. | `67864d5c24cec4946cb515a184cba7fdcce15cd8d8c1ca625725c70a74771b8f` |
| `data/items.csv` | 1096 | Complete questionnaire wording and source question mapping; Table 10 / Appendix A. | `a1caa673ad07c1eef9ab4e5c98dc4fe2d550e52ae6f6876cf3931f3e6a1da773` |
| `data/README.md` | 3030 | Provenance, record matching and zero-processing protocol for Section 6. | `ce2dbc55e4c2b10de71c6312547621349f7dab124e42bd299c9c45fb57a3e3e9` |
| `data/release_authorization.json` | 469 | Author-confirmed authority for public sharing of both allocation sources. | `f743ad9c369863d7a307cc27004664693fe4640d42f80bb895e3ef79e80a74da` |
| `docs/ENVIRONMENT.md` | 885 | Original/current software and random-number environment. | `6b3ba07890bd757cb6b13a637a9564af8894926bd841ebc888819fea8e63e064` |
| `docs/METHOD_SCOPE.md` | 1420 | Estimation target, prior literature and mathematical limitations. | `8d2a226efa2613f58cf5682e33b448fbf4d6ebef931ce766b0bf3c5df6ae4e06` |
| `docs/REPRODUCIBILITY.md` | 3545 | Run order, seeds, sample sizes, output/table mapping and replay distinction. | `272fc02c6a9d05482a519344d331e86ec6742e311aadede0d9eb102b7f8f07fe` |
| `make_tables.py` | 9262 | Generate Tables 1–10, including item wording appendix, from numerical inputs. | `1a6852b8c3a3c3367523286e98e2be87a18616d9e297e91b30524caec9dab538` |
| `NOTICE.md` | 799 | Sharing authority, attribution and absence of an author-selected reuse license. | `3907e78bc6811fa3e56bf1fc30c43d8f9b74eeb201b38e44552937b045667107` |
| `paper/manuscript.tex` | 40518 | Editable formal paper; all substantive current methods, results and references. | `865fe449a6393bbd05bc07297fd73897800bab84325aff01db4afd29c5eb2149` |
| `paper/README.md` | 686 | Instructions for optional PDF compilation. | `622bbebee802469d8437e39bdbea72800eb0aa4f126549421aec7d4783da906e` |
| `R/estimator.R` | 6093 | Specified Mode-A score iteration, loading slopes, prediction and rotation comparisons. | `e084d50e69d9c2a658484d5672c73a5e1a6002ef06840981e713440473bf3a34` |
| `R/geometry.R` | 573 | ILR/CLR geometry, orthogonal rotations and complete-vector distance calculations. | `f2b2309b0c730f40c3762a3381139dffdcf5b7a08a6ca7919d2b47b56328df3a` |
| `R/runtime.R` | 1446 | Portable command-line parsing, source loading and environment records. | `916e5f5cd19e369cba6444937c6679f6b0266cd2d50b8584f5a4c523c1e6b30e` |
| `R/scenarios.R` | 2174 | Three common-factor scenarios and equation-specific R-squared targets; Section 5. | `de212a740ab8aee964f1e98398e59a9e2fcda0d682cadbc6447fc9937fae40be` |
| `R/zero_handling.R` | 694 | Explicit positive approximation schemes for observed zeros; Sections 4 and 6. | `734f76c29e0fd845412ec69eec30c1d639d7f94aff3535ec04ea925e57e2d180` |
| `README.md` | 5235 | Final-version entry, scope, quick start and data/model limitations. | `ece14d4a4d7bc2e9bd77da5af2a32f0cfe77c041a17e14dda894a65a70515824` |
| `release.json` | 605 | Machine-readable version, data dimensions and computational scope. | `346cd086cce4e7597ab7613b549cf0dcee971ad2def1e698d0fbe66095d39b1a` |
| `reproduce.py` | 1058 | One-command numerical and table reproduction, hash checks and mode selection. | `d93ee0f955e1692a75a368ee84b8cf865372ca2e4e963d02829952155500b9a2` |
| `run_checks.R` | 2521 | Permanent 33 mathematical and numerical checks; not a temporary test. | `5fa3ff1c8ec0329453f3d05f91990785da7cb5e2ffd7c940488cadaf6b1d6873` |
| `run_empirical.R` | 9858 | Final-data estimation, bootstrap or verified draws, rotations, prediction and sensitivities. | `a536948924511b185a2545d33005442861769af6865f22ba98d53d3cda76ed3e` |
| `run_factor_benchmark.R` | 3715 | From-seed identified common-factor ML comparisons (requires lavaan). | `65e19b5d3005156519750010761ef73c545c4934f546b0c37601c13f7a048d3c` |
| `run_final.R` | 3276 | Numerical orchestration and completed-draw summarization; every result table input. | `25f23cd691332e7b7036221f47055ce2d1db4a341845a08e998943af92f6f9a8` |
| `run_simulation.R` | 4778 | From-seed Monte Carlo, matched CLR and coordinate-standardized comparators. | `0658d6e632046888f21a2c26bb6f57336c483f5f393a96bea90fcdb493da54ec` |
| `vendor/generator_reference.R` | 1681 | Attributed upstream generator used for covariance/path equivalence checks. | `68f7807f051402ea75f817e09408f167920ce5d9dce3cfb982a6b5672dda7a3b` |
| `verified/bootstrap_paths.csv.gz` | 729663 | 16,000 requested bootstrap fits (15,999 converged); Tables 7 and 9 and intervals. | `bf410219cabb370531206e3caf1a2bdb71b06c9a4604784dd37fafbb293f4387` |
| `verified/factor_ml_draws.csv.gz` | 11621 | 200 paired ML/PLS samples; Table 5. | `de776995a9bdb09072d323a99f9716d09eef682cd9c2b03bfa25150a591db05d` |
| `verified/manifest.json` | 654 | SHA-256 integrity checks on completed numerical inputs. | `9aee7882cf89d41c0b5e0ce6ee1d175777be048e5366d503a97e54cb0adc5e0a` |
| `verified/scenario_rotations.csv` | 18225 | 75 scenario rotation comparisons; Table 3. | `55f86be0f8fd45f7e5af0f885f45b2d75b325d1c857f47b7220a5cdb9664a835` |
| `verified/simulation_draws.csv.gz` | 542132 | 21,600 comparator outputs for 5,400 samples; Tables 2 and 4. | `5862cdf3575b1f5c7cb4e9f499b6bec4027a75eb4aae33344e1a7bab7fca2beb` |
| `VERSION_NOTES.md` | 1231 | Material version/data-correction statement; legacy files are superseded. | `e888da54efc63217891d15081e96e15c2015692e42978ba6cf47a1d105cbbd76` |
