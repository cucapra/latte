+++
+++

LATTE is a venue for discussion, debate, and brainstorming at the intersection of hardware acceleration and programming languages research. The core mission is to bring ideas we love from software programming languages and tools to the world of hardware design.

LATTE is a venue for discussion, debate, and brainstorming at the intersection of hardware acceleration and programming languages research. The core mission is to bring ideas we love from software programming languages and tools to the world of hardware design. For more details on the workshop's focus, see [the call for papers][cfp].

## The 2026 Workshop

LATTE is a hybrid workshop; please consider attending either in person (in Rotterdam, co-located with [ASPLOS][]) or virtually (on Zoom). LATTE will be held on March 30.

## Call for Papers

Submit your **2-page position paper** via [HotCRP][hotcrp].
Important dates:

- Paper submission: **January 31, 2026**
- Author Notification: **February 20, 2026**
- Workshop: **March 22 or 23, 2026**

### Overview

The world deserves better tools for designing custom hardware accelerators. We believe the world of programming languages research can help. New language designs, compiler optimizations, program analyses, type systems, testing frameworks, auxiliary engineering tools like debuggers and profilers: all these topics have deep research traditions in software, and they all have a role to play in making hardware design better.

LATTE is a venue for discussion, debate, and brainstorming at the intersection of hardware acceleration and programming languages research. The core mission is to bring ideas we love from software programming languages and tools to the world of hardware design.

LATTE has a special focus on open-source research. We encourage work that comes with real, permissively licensed implementations.

For LATTE, "hardware" includes ASICs, FPGAs, CGRAs, and other reconfigurable hardware. While the scope is broad, here are a few ideas to get you started:

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
- Overviews of open-source projects, even when the novelty with respect to proprietary alternatives is limited

### Position Papers

The primary goal of the workshop is to enable discussion. It will accept **2-page position papers**.
The workshop will allocate short time slots to the papers, each paired with a discussion following [SNAPL][]'s discussion format:
“table discussion” where small breakout groups will discuss the paper, followed by plenary Q&A.

In order to make sure that papers are aligned with the topics of the workshop, they should explicitly address one (or more!) of these themes

- Hardware design tools MUST change
- Verification REMAINS the key challenge
- The tools we build NEED to interoperate with each other to be successful
- A *clearly and concisely articulated* theme of your own choosing. Apply the following tests when creating a theme: (1) does it apply more broadly than just your paper, and (2) can it be articulated with a short sentence.

For example, papers presenting a new tool or language are still encouraged, but rather than just presenting your new tool, try to make it fit with the themes by arguing that "Hardware description languages must change to address X,  that is why Y does Z".

In addition, we are looking for papers that propse new "themes" like these. The idea is to highlight key questions that we as a community should try to address. These papers will be given more time for deeper discussion during the workshop, and as such will be held to a higher standard than normal papers.

Position paper submissions will undergo peer review by a program committee of interdisciplinary experts working on both high-level (languages, compilers, drivers) and low-level (circuit optimization, interconnect design) problems in the area.

**Formatting.** Papers should use the two-column [the formatting guidelines for SIGPLAN conferences][sigplanconf] (the `acmart` format with the `sigplan` two-column option) and not exceed 2 pages, excluding references. Review is single-blind, so please include authors' names on the submitted PDF.
We provide [a LaTeX example][format-example] that contains the correct formatting.

Paper submission will is via [HotCRP][hotcrp].
The accepted papers will not be published in a proceeding—PDFs will instead appear on the workshop's website.

**Important guidelines.**
It's standard for papers to start with a general motivation: Moore's Law is doomed; specialized hardware is ascendant; Verilog is hard to use; etc.
*Please skip this part* in your LATTE position paper (and in eventual talks at the workshop).
The LATTE audience will already believe these things, so save the space & time and instead focus on your own unique ideas.
As much as possible, dispose with the framing and motivation so you can focus on the technical content.

Remember that the goal at LATTE is to stimulate discussion, not to disseminate fully polished results.
So don't be afraid to write up half-baked ideas and in-progress work: it's OK if your submission has zero bar charts, for example.

For examples of past position papers, consider looking at the programs for [LATTE ’25][latte-25] [LATTE ’24][latte-24], [’23][latte-23], [’22][latte-22], and [’21][latte-21].

**NOTE**: Using an LLM to fully generate your paper is ground for desk rejection. Using an LLM for small edits is fine, but keep in mind that we want to hear your ideas a phrased by you, not by the LLM.

We are also not interested in LLM-focused research. LATTE is a venue for discussing languages and tools by humans and for humans.

## Hybrid Format

LATTE 2026 will run in a hybrid format, i.e., it will be possible to join either in person (in Rotterdam) or online (on Zoom).
Talks at the workshop can use either modality, so please consider submitting even if you cannot attend in person.

## LATTE Matrix Chat

We have set up a matrix chat to keep the latte community in touch outside the
main latte event. [Join it here][matrix]. Any vaguely latte-related discussion
is encouraged! Showcase cool projects you built, discuss new ideas or problems
you've run into, or just hang out with the community.


[hotcrp]: https://latte.cs.cornell.edu/
[snapl]: http://cs.brown.edu/~sk/Memos/Conference-Discussion-Format/
[sigplanconf]: https://www.acm.org/binaries/content/assets/publications/consolidated-tex-template/acmart.pdf
[format-example]: https://github.com/cucapra/latte23/tree/main/camera-ready
[latte-21]: https://capra.cs.cornell.edu/latte21/
[latte-22]: https://capra.cs.cornell.edu/latte22/
[latte-23]: https://capra.cs.cornell.edu/latte23/
[latte-24]: https://capra.cs.cornell.edu/latte24/

[cfp]: @/cfp.md
[asplos]: https://www.asplos-conference.org/asplos2026/
[matrix]: https://matrix.to/#/#latte-chat:fossi-foundation.org


## Attending LATTE

LATTE is a hybrid workshop; please consider attending either in person (in Rotterdam, co-located with [ASPLOS][]) or virtually (on Zoom). LATTE will be held on March 30.

* To attend in person, [register to attend ASPLOS workshops][asplos-reg].
* To attend virtually, no conference registration is required. Please [sign up using this Zoom form][zoom] to receive a link to join.

[asplos-reg]: https://www.asplos-conference.org/asplos2026/registration/
[zoom]: https://cornell.zoom.us/meeting/register/UfYN6ksoTLSbmm7gO1ApOA

## LATTE Matrix Chat

We have set up a Matrix chat to keep the LATTE community in touch outside the
main latte event. [Join it here.][matrix] Any vaguely LATTE-related discussion
is encouraged! Showcase cool projects you built, discuss new ideas or problems
you've run into, or just hang out with the community.
We'll also use this for real-time communication during the workshop.

## Organizers

LATTE's organizing team this year is:

* [Rachit Nigam](https://rachit.pl), MIT & Jane Street
* [Adrian Sampson](https://www.cs.cornell.edu/~asampson/), Cornell
* [Frans Skarman](https://liu.se/en/employee/frask53), Munich University of Applied Sciences
* [Edward Wang](https://edwardw.compdigitec.com/), MIT

[hotcrp]: https://latte.cs.cornell.edu/
[snapl]: http://cs.brown.edu/~sk/Memos/Conference-Discussion-Format/
[sigplanconf]: https://www.acm.org/binaries/content/assets/publications/consolidated-tex-template/acmart.pdf
[format-example]: https://github.com/cucapra/latte23/tree/main/camera-ready
[latte-21]: https://capra.cs.cornell.edu/latte21/
[latte-22]: https://capra.cs.cornell.edu/latte22/
[latte-23]: https://capra.cs.cornell.edu/latte23/
[latte-24]: https://capra.cs.cornell.edu/latte24/
[latte-25]: https://capra.cs.cornell.edu/latte25/

[cfp]: @/cfp.md
[asplos]: https://www.asplos-conference.org/asplos2026/
[matrix]: https://matrix.to/#/#latte-chat:fossi-foundation.org
