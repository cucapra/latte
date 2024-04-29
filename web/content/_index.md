+++
+++

LATTE is a venue for discussion, debate, and brainstorming at the intersection of hardware acceleration and programming languages research. The core mission is to bring ideas we love from software programming languages and tools to the world of hardware design. For more details on the workshop's focus, see [the call for papers][cfp].

## LATTE Matrix Chat

We have set up a matrix chat to keep the latte community in touch outside the
main latte event. [Join it here][matrix]. Any vaguely latte-related discussion
is encouraged! Showcase cool projects you built, discuss new ideas or problems
you've run into, or just hang out with the community.

## Attending LATTE

LATTE is a hybrid workshop; please consider attending either in person (in San Diego, co-located with [ASPLOS][]) or virtually (on Zoom). LATTE will be held in the mornings on April 27--28, 2024.

* To attend in person, [register to attend ASPLOS workshops][asplos-reg].
* To attend virtually, no conference registration is required. Please [sign up in this Zoom form][zoom] to receive a link to join.

## Program

Here's tentative schedule for the two days of the workshop.
All times are in San Diego time (US Pacific).

Talks in the sessions are 7 minutes, each with 1 minute of short clarification questions.
Each session will have 6 minutes of shared discussion time directed toward all the authors in a given session.

### Saturday, April 27

| Time (Pacific) | Event |
|----------------|-------|
| 8:45–9am | Introductions and Overview |
| 9–10am | [Invited Talk: Vighnesh Iyer and Joonho Whangbo](#invited-talk) |
| 10–10:30am | Break |
| 10:30–11am | [Session 1](#session-1): Processors and SoCs |
| 11–11:30am | [Session 2](#session-2): Reconfigurable Architectures |
| 11:30–11:50am | [Session 3](#session-3): Opinions and Directions |
| noon–1pm | Lunch Discussion |

### Sunday, April 28

| Time (Pacific) | Event |
|----------------|-------|
| 8:45–9:45am | [Keynote: Tatiana Shpeisman](#keynote) |
| 9:45–10:05am | [Session 4](#session-4): Systems |
| 10–10:30am | Break |
| 10:30–11am | [Session 5](#session-5): The Toolchain |
| 11–11:30am | [Session 6](#session-6): HDLs |
| 11:30-noon | Discussion: Building a Community |
| noon–1pm | Lunch Discussion |

## Talk Sessions

We'll post the papers (linked from the titles below) soon.
For authors: final versions of accepted position papers are due on April 23 via [HotCRP][].

{{ program() }}

## Keynote

We are thrilled to host a keynote by [Tatiana Shpeisman][tatiana] of [Modular][] on Sunday!

**Mojo: A Unified Programming Language for Heterogeneous Systems Programming**

[Tatiana Shpeisman][tatiana], [Modular][]

Modern computer applications, such as Generative AI, are inherently complex, requiring multiple levels of programming abstractions to achieve necessary performance and programmability . These applications are usually built in multiple programming languages, some of them designed specifically for concrete hardware targets. For example, most machine learning systems are built using a combination of Python, C++ and CUDA. This complexity hinders developer productivity and makes it more difficult to maintain and extend software systems.

In this talk, we will describe Mojo - a new programming language designed to alleviate complexity of AI and other complex systems programming. Mojo combines programmability of Python with performance of C, delivering multiple orders of magnitude performance improvements over Python. It also supports multiple hardware targets, which is a must for modern AI programming. We will describe the philosophy behind Mojo design and give an overview of Mojo features and capabilities including support for heterogeneous execution. We will illustrate the power of Mojo by its application to Modular’s MAX platform that uses Mojo for both internal development and custom extensions.

---

[Tatiana Shpeisman][tatiana] is a founding team member and senior technologist at Modular where she works on building the next generation programming infrastructure for AI.  Before joining Modular, she was Sr. Engineering Manager at Google and Director of Programming Systems Research at Intel. Tatiana has dedicated her professional career to building technologies that improve performance and programmability of software systems including work on Mojo, MLIR, AI compute and transactional memory. Tatiana has >40 peer reviewed research papers and >60 issued patents.

[tatiana]: https://www.modular.com/team/tatiana-shpeisman
[modular]: https://www.modular.com

## Invited Talk

We will host an overview talk and demo by [Vighnesh Iyer][vighnesh] and [Joonho Whangbo][joonho] of UC Berkeley on Saturday!

**The Next Paradigm of Hardware Design: Chipyard Overview and Calyx Integration Demo**

[Vighnesh Iyer][vighnesh] & [Joonho Whangbo][joonho], UC Berkeley

<span class="button">
<a href="https://vighneshiyer.github.io/2024_04-latte-the_next_paradigm_of_hw_design.html#/2/0/2">Slides</a>
</span>

Agile hardware design methodologies enable small teams to build complex SoCs by rethinking the existing hardware design paradigm, which requires hundreds, if not thousands of engineers to build SoCs.

In the first part of the talk, we will review Chipyard and FireSim which are tools that open up possibilities to agile hardware development by enabling rapid SoC designs and simulation.

In the second part of the talk, we will present our views, as hardware designers, about potential innovations in design abstractions, languages, and simulators to deliver a paradigm shift in hardware design.
We will discuss the importance of a rapid iteration loop, ideas for mixed-abstraction design frontends, semantics-preserving IRs, and how all these fit into our existing infrastructure.

---

[Vighnesh Iyer][vighnesh] is a PhD candidate at UC Berkeley advised by Prof. Bora Nikolic working on research in hardware design methodology, sampled simulation, and hardware verification.

[Joonho Whangbo][joonho] is a PhD student at UC Berkeley advised by Prof. Sophia Shao and Prof. Krste Asanovic working on hardware tooling and RTL simulation.

[vighnesh]: https://vighneshiyer.com
[joonho]: https://joonho3020.github.io

[cfp]: @/cfp.md
[asplos]: https://www.asplos-conference.org/asplos2024/
[asplos-reg]: https://www.asplos-conference.org/asplos2024/attend/#registration
[zoom]: https://cornell.zoom.us/meeting/register/tJYlceCgpjkvEtcBL_b7hFWpbShI_Je4mSU8
[hotcrp]: https://latte.cs.cornell.edu
[matrix]: https://matrix.to/#/#latte-chat:fossi-foundation.org
