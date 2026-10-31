# Final analysis release — version 1.0.1

Date: 31 October 2026. This is the final-version entry for *PLS-SEM for compositional data: coordinate invariance and measurement assessment*.

Download [PUBLIC_RELEASE_FINAL.zip](PUBLIC_RELEASE_FINAL.zip) and extract it. The archive contains 36 files, including one 506-record observation CSV with 33 original allocation components, complete dictionaries, the final R/Python programs, verified experiment draws and the editable formal paper. Observed zeros are preserved. No old nominal SN coordinates or private source-linkage records are included.

Archive SHA-256: `dd7984f859d895ec1f5f6b07ff64664733d9808dce24f0a248650ee4f03111d3`

From the extracted directory, run:

```sh
python reproduce.py
```

Provide `--rscript=/path/to/Rscript` if needed. The default verified workflow regenerates every table while refitting empirical points, rotations and predictions; completed simulation/bootstrap draws are summarized rather than falsely represented as newly recomputed. `--mode=recompute` provides full from-seed numerical regeneration; optional lavaan is needed only for factor ML. `python build_manuscript.py` compiles the formal source using a separately installed TeX engine.

The [file manifest](PUBLIC_RELEASE_MANIFEST.md) lists every packaged file, its paper purpose and SHA-256 digest. Source records were authorized for public sharing after pseudonymization; matching and zero-mechanism limitations remain documented. See the archive's `VERSION_NOTES.md`, `NOTICE.md` and `docs/` for scope and attribution. Files elsewhere at repository root are historical and superseded.
