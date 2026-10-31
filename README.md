# PLS-SEM for compositional data

## Final manuscript version — 31 October 2026

**Use the [final analysis release](final/README.md), version 1.0.0.** Download and extract [PUBLIC_RELEASE_FINAL.zip](final/PUBLIC_RELEASE_FINAL.zip). It contains the authorized pseudonymized 506-record observations with original zeros, independent influence-source allocations, final estimator and simulation code, completed numerical draws, all table generators and the formal LaTeX source.

Run `python reproduce.py` inside the extracted `PUBLIC_RELEASE_FINAL` directory. See its README for Rscript selection, verified replay versus full recomputation, optional ML software and PDF compilation. The package runs without any legacy workbook or private source file. The release manifest provides per-file SHA-256 digests and paper purposes.

## Version and data correction

The loose scripts and workbooks at repository root are retained as a historical version. They are superseded for the final manuscript and must not be used to regenerate its tables. The final release excludes outcome-derived nominal SN coordinates, uses the separate Family/Friends/Other non-family allocation and no longer reports COMP-CR as reliability. `VERSION_NOTES.md` inside the release explains the material change and the two disclosed record-matching assumptions. Existing Git history is preserved.

The final method concerns conditional coordinate equivariance of a specified score procedure. It does not claim a new logratio geometry, common-factor consistency, a reliability interpretation for loading norms or improved root-only prediction in this application. Chen, Zhang and Hron (2021), DOI 10.1080/02664763.2020.1795813, establish the prior compositional PLS-regression invariance result.

Permission to publish both pseudonymized allocation sources was confirmed by the corresponding author. Direct identifiers and private source-linkage records are not in the release. No new software/data reuse license has been selected; see `NOTICE.md` in the archive.
