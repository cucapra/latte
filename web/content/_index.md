+++
+++

Submit your **2-page position paper** via [HotCRP][].
Important dates:

- Paper submission: **March 8, 2024**
- Author Notification: **February 21, 2023**
- Workshop: **March 26, 2023**

### Overview

**Motivation.**
Hardware acceleration is a key part of combating the stagnation of hardware performance scaling. Implementing accelerators with state-of-the-art hardware design flows, such as traditional HDLs and current HLS tools, remains a specialized task requiring EE training, proprietary toolchains, and extremely slow compile-edit-run cycles. While traditional approaches *might* be appropriate for developing general-purpose CPUs that will ship millions of units, they are an impediment to popularizing acceleration for the “long tail” of applications that could benefit from special-purpose hardware. With new language designs and new techniques inspired by traditional compilers research, there is an opportunity to turn accelerator construction from a years-long enterprise into a weekend project.

**Scope.**
LATTE is a venue for discussion, debate, and brainstorming at the intersection of hardware acceleration and programming languages research. The focus is on new languages and tools that aim to let domain specialists, not just hardware experts, produce efficient accelerators. A full range of targets are in scope: ASICs (silicon), FPGAs, CGRAs, or future reconfigurable hardware. A wide variety of research topics are in scope including, but not limited to:

- Domain-specific languages for accelerator design
- Compilers for optimizing hardware designs
- Verification, testing, and debugging techniques
- Virtualization schemes for specialized & reconfigurable hardware

LATTE solicits short position papers that need not fit the mold of a traditional publication:

- Early, in-progress research snapshots
- Experience reports on building or deploying accelerators and the tools involved
- Essays advocating for or against a general approach
- Retrospectives on past efforts on tools, languages, and techniques for accelerator design
- Calls for solutions to open challenges in the area (questions without answers)
- Demonstrations of real systems (to be shown off in a live demo at the workshop)

### Position Papers

The primary goal of the workshop is to enable discussion. It will accept **2-page position papers**.
The workshop will allocate short time slots to the papers, each paired with a discussion following [SNAPL][]'s discussion format:
“table discussion” where small breakout groups will discuss the paper, followed by plenary Q&A.

Position paper submissions will undergo peer review by a program committee of interdisciplinary experts working on both high-level (languages, compilers, drivers) and low-level (circuit optimization, interconnect design) problems in the area.

**Formatting.** Papers should use the two-column [the formatting guidelines for SIGPLAN conferences][sigplanconf] (the `acmart` format with the `sigplan` two-column option) and not exceed 2 pages, excluding references. Review is single-blind, so please include authors' names on the submitted PDF.
We provide [a LaTeX example][format-example] that contains the correct formatting.

Paper submission will is via [HotCRP][].
The accepted papers will not be published in a proceeding—PDFs will instead appear on the workshop's website.

**Important guidelines.**
It's standard for papers to start with a general motivation: Moore's Law is doomed; specialized hardware is ascendant; Verilog is hard to use; etc.
*Please skip this part* in your LATTE position paper (and in eventual talks at the workshop).
The LATTE audience will already believe these things, so save the space & time and instead focus on your own unique ideas.
As much as possible, dispose with the framing and motivation so you can focus on the technical content.

Remember that the goal at LATTE is to stimulate discussion, not to disseminate fully polished results.
So don't be afraid to write up half-baked ideas and in-progress work: it's OK if your submission has zero bar charts, for example.

For examples of past position papers, consider looking at the programs for [LATTE ’22][latte-22] and [’21][latte-21].

[hotcrp]: https://latte.cs.cornell.edu/
[snapl]: http://cs.brown.edu/~sk/Memos/Conference-Discussion-Format/
[sigplanconf]: https://www.acm.org/binaries/content/assets/publications/consolidated-tex-template/acmart.pdf
[format-example]: https://github.com/cucapra/latte23/tree/main/camera-ready
[latte-21]: https://capra.cs.cornell.edu/latte21/
[latte-22]: https://capra.cs.cornell.edu/latte22/


