# Software Verification (2026)

## Office hours

Please inform before (by email) that you plan to attend office hours.

| Instructor    | Schedule | E-mail |
| ------------- | -------- | ------ |
| Mário Pereira | Monday, 14h00 (Office 243) | mjp.pereira@fct.unl.pt |

<!-- ## Handouts -->

<!-- | Handout | Statement                           | Companion files                      | -->
<!-- |---------|-------------------------------------|--------------------------------------| -->
<!-- | 1       | [Handout 1 (.pdf)](sv_handout1.pdf) | [proper_cuts.v](proper_cuts.v)       | -->
<!-- | 2       | [Handout 2 (.pdf)](sv_handout2.pdf) | [delannoy.zip](delannoy.zip)         | -->
<!-- | 3       | [Handout 3 (.pdf)](sv_handout3.pdf) | [PairingHeap.java](PairingHeap.java) | -->

## Installation procedures

Throughout the Software Verification course we will be using several
tools to illustrate different aspects of deductive verification. As
so, I will be updating this section with the main installation
procedures and guidelines for each tool and framework.

### The OCaml language and ecosystem

The OCaml language is the language of choice for the implementation
for some of the tools used in the Software Verification course. <!-- We are -->
<!-- going to use OCaml during lectures, to present fundamental concepts -->
<!-- about languages and compilers, as well as in practical sessions to -->
<!-- implement and experiment with some of the main concepts presented -->
<!-- during lectures. -->

In order to install OCaml and the language ecosystem, please follow
the installation guide provided [here](install_ocaml.md).

### The Rocq proof assistant

> [!WARNING]
> Until very recently, Rocq was called the "Coq Proof Assistant". It
> is very likely that installation procedures, tutorials, and every
> kind of available documentation refers to Rocq and Coq
> interchangeably.

The Rocq proof assistant is going to be our tool of choice for the
first part of the Software Verification course.

In order to install Rocq, you can find comprehensive instructions
[here](https://rocq-prover.org/install). There, you will found
instructions on how to install Coq under Linux, Windows, or MacOS.

The Rocq Platform is an easy way to install the Rocq Proof Assistant
and basic packages. It is available for Linux, Windows, and MacOS.

Regarding editors, Rocq comes with its own IDE. This is installed with
the Rocq Platform. There are also very smooth integration of the proof
assistant with common text editors, such as VS Code, Emacs, or Vim.

<!-- ### The Why3 framework -->

<!-- The Why3 framework is going to be our tool of choice for the second -->
<!-- part of the Software Verification course. -->

<!-- In order to install Why3 and its ecosystem, please follow the -->
<!-- installation guide provided [here](install_why3.md). -->

<!-- The Why3 framework has been around for a few years now, and it has -->
<!-- been the subject of very intense development and research. You should -->
<!-- definitely know and check, on a regular basis, the following three -->
<!-- websites: -->

<!--   - The framework manual: https://www.why3.org/doc/ -->

<!--     Other than providing a very comprehensive presentation of the -->
<!--     framework and underlying tools, the third chapter is of mandatory -->
<!--     reading for those learning to do proofs with Why3. -->

<!--   - The standard library: https://www.why3.org/stdlib/ -->

<!--   - Finally, the huge gallery of verified programs: -->
<!--     https://toccata.gitlabpages.inria.fr/toccata/gallery/why3.en.html -->

<!--     This is probably the best source to learn specification and -->
<!--     programming using WhyML, the programming language of Why3. -->

## Planning

| Week | Date | Topics | Slides | Labs |
| ---- | ---- | ------ | ------ | ---- |
| 1 | 9 Sep | Verified Functional Programs: introduction | <!-- [Lecture 1 (slides)](lecture1.pdf) <br> [Lecture Notes](notes_fp.pdf) --> | |
| 1 | 9, 10 Sep | Introduction to the Rocq Proof Assistant | | <!-- [Lab 1 (.pdf)](lab1/lab1.pdf) <br> [Rocq file (.v)](lab1/lab1.v) <br> [Solutions (.v)](lab1/lab1_solutions.v) --> |
