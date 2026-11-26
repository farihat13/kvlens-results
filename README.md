# kvlens-results

The paper's results tree: the files graph-storage-artifact reads as `paper-results/` (its derive scripts and every
study driver with `--root paper-results`). `files.sha256` lists every other file's sha256, sorted by path; check it with
`sha256sum -c files.sha256`.

This commit holds every result except the latency figure's timings (`timings/`, `summary/<dataset>/<scale>/grid-latency/`),
which come in their own commit.
