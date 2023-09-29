This is a customized version of  this template https://github.com/kourgeorge/arxiv-style, mainly adding the things I basically always use when creating a writeup + some goodies.

Changes include, but aren't limited to

- nicer fonts
- CI build when you push a semantic tag (e.g. `git tag 0.0.0; git push --tags) => you should always find a built pdf at the [releases tab](../../releases)
- added guide for making nice tables and alternating row colors by default.
- hyperref, cref, biblatex configured to number in order of occurence, backrefs for the citations
- smoother internal references (stolen from https://github.com/tmpethick  :-D )
