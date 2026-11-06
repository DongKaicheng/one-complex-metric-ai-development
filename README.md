# AI-assisted development materials

Supplement to *One complex metric and geometric adelic nefness*.

This repository contains an English account of the AI assistance used in
developing and revising the mathematical manuscript, together with a
selected archive of the retained mathematical work.

## Paper

**One complex metric and geometric adelic nefness** (preprint, 2026).

- [Paper PDF](https://github.com/DongKaicheng/one-complex-metric-ai-development/releases/download/paper-v2026-11-06/One_Complex_Metric_and_Geometric_Adelic_Nefness.pdf)
- [Editable LaTeX source](https://github.com/DongKaicheng/one-complex-metric-ai-development/releases/download/paper-v2026-11-06/One_Complex_Metric_LaTeX_20261106.zip)
- [Paper release dated 6 November 2026](https://github.com/DongKaicheng/one-complex-metric-ai-development/releases/tag/paper-v2026-11-06)

This is the author's revised paper edition with the acknowledgements and AI-use disclosure after the Introduction. The earlier source snapshots inside the frozen AI-development archive below are preserved unchanged.

## Files

- [English AI-assisted development report](AI_Assisted_Development_Report_EN.pdf):
  a concise account of mathematical drafting, proof-route exploration,
  checking and expository revision, mapped to the latest supplied source.
- [Mathematical work-process archive](One_Complex_Metric_AI_Work_Process_GitHub_20261106.zip):
  26 selected historical records, three earlier manuscript snapshots,
  checking notes, a proof-step map, and the exact latest supplied source
  with a matching rebuilt PDF.

The archive includes a separate suggested AI-use disclosure paragraph
for author review. The reference manuscript inside the frozen archive has not been changed; the revised paper edition is linked separately above.

The ZIP is preserved as the frozen pre-upload snapshot. Any preparation
status inside it describes that snapshot; this repository's commit and
release record its subsequent publication.

## Scope and version

Edition: 6 November 2026. The reference is the LaTeX source supplied on that
date. The separately supplied PDF differs from the source; the version note
inside the archive records this distinction. Current proof locators use
the PDF rebuilt from the preserved source.

The earlier prescribed-Bergman-metric exploration is kept separate from
the geometric argument retained in the current manuscript. Earlier
AI checking statements retain their original manuscript target.

This is a selected development archive, not a complete native conversation
export or an independent mathematical certification. Unrecovered exchanges
remain explicitly missing. Private operational records and account
identifiers are excluded from the public selection.

## Reading and verification

Read the English report first. After extracting the archive, open its
README for the manuscript map and historical record index.

From the extracted archive directory, the included offline check can be run
with Python:

~~~console
python scripts/verify_archive.py
~~~

The check verifies file integrity, local links and manuscript-source
bindings. It does not certify the mathematical conclusions or historical
priority.

No blanket reuse license or independent endorsement is assigned by these
materials.
