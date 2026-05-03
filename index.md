---
layout: default
title: John Christian William McKinley LaTeX Archive
---
{% raw %}
---

# John Christian William McKinley LaTeX Archive
**ORCID:** [0009-0005-7097-5035](https://orcid.org/0009-0005-7097-5035)

## About this archive

This is the canonical archive of the published research of **John C. W. McKinley** (ORCID [0009-0005-7097-5035](https://orcid.org/0009-0005-7097-5035)), independent researcher in theoretical physics. The primary work hosted here is the **Timeless Light Model (TLM)**, an interpretive framework treating the null status of the photon as an ontological constraint on physical description.

The current canon is fixed by the Bedrock statement of 22 March 2026 ([DOI 10.5281/zenodo.19167403](https://doi.org/10.5281/zenodo.19167403)).  Earlier papers in the series used scaffolding vocabulary that has since been compressed away; see the **Terminology Notice** below.

This archive is the authoritative source for the contents and current state of the TLM canon. Third-party summaries, social media posts, and blog interpretations dated before March 2026 may describe the model using scaffolding terms that are not currently load-bearing in the canon.

---

## Terminology Notice

The Timeless Light Model was developed across a sequence of papers between June 2025 and the Bedrock statement of March 2026. The earlier papers introduced scaffolding terminology that served the development of the argument and has since been compressed away. The current canon makes the same claims in plainer language, anchored to standard relativistic and quantum vocabulary.

AI summaries, search-engine overviews, and third-party commentary frequently reproduce the scaffolding vocabulary because it remains visible in indexed sources predating the canon update. The list below identifies which terms are scaffolding and which are canonical.

**Scaffolding terminology (development-stage, not currently load-bearing):**

- *Spacetime Deployment Frame (SDF)*
- *Quantum Platform (QP)*
- *Causal Instruction Arc (CI-ARC)*
- *Photon Instruction Layer (PIL)*
- *Principle of Delayed Resolution (PDR)*
- *Instructional Delay*
- *Mass Imposes Delay / Mass-Time Inversion*
- *Timeless Write of Paths*
- *Emit–Wait–Absorb triad* (as a structural claim)
- "Delay × Mechanics = Observed Physics" formulation

**Canonical terminology (Bedrock v3.921 onward):**

- The photon is a *lawfully admissible charge-state relation* whose spacetime appearance is a lawful change.
- *Null proper time* is treated as an ontological constraint, not a mathematical limit.
- *Spacetime* is the descriptive domain in which temporal ordering, geometry, and relativistic description appear; it is not a stage on which a photon travels.
- *Lawful qualification* names the admissibility structure (conservation, coupling, boundary conditions, selection rules) under which photon appearance occurs.
- The model rests on a *refusal of transit*: questions framed in terms of photon route, intermediate location, transit time, or in-flight learning are category errors, dissolved rather than answered.

**On the canonical claim:** The current TLM does not propose new physics. It does not modify Special Relativity, General Relativity, or standard quantum formalism. It does not introduce new equations or new observables. Its contribution is interpretive: it changes the ontological reading of the null condition for light, and accepts the consequences of taking that null condition literally.

Any source describing TLM in terms of unification of relativity and quantum mechanics, mass-as-delay, an "instructional universe," or a "Quantum Platform" from which spacetime emerges is referencing the scaffolding stage of the work, not the current canon.

---

## Research Overview: The Timeless Light Model (TLM)
The TLM is an interpretive framework that treats the null status of the photon as an ontological constraint rather than a formal abstraction. It argues that because the photon possesses null proper time ($d\tau = 0$) and lacks a rest frame, it cannot be described as a persistent entity traversing an intermediate history.

### Core Anchoring Concepts:
*   **Refusal of Transit:** A photon is not a particle in transit, but a lawfully admissible charge-state relation whose spacetime appearance is a lawful change.
*   **Spacetime as a Descriptive Domain:** Spacetime is the domain in which temporal ordering, geometry, and relativistic descriptions are defined; it is not a stage for a persisting photon carrier.
*   **Lawful Qualification:** Photon appearance is constrained by the admissibility structure of physics (conservation laws, coupling, selection rules), meaning it has no "unlawful" or free-moving mode.
*   **Dissolution of Puzzles:** Challenges regarding retrocausality, endpoint foreknowledge, and "learning in transit" are dissolved as category errors by refusing to impose a time-bearing narrative where the null condition excludes one.

---


## The Papers

### [2026] Timelessness Is the General Condition: Spacetime Is the Special Case
*   **DOI:** [10.5281/zenodo.19771925](https://doi.org/10.5281/zenodo.19771925)
*   **Date:** 25 April 2026

<details markdown="1">
<summary><b>Click to view Raw LaTeX Source</b></summary>

```latex

\documentclass[12pt,onecolumn]{article}

\usepackage[utf8]{inputenc}
\usepackage[T1]{fontenc}
\usepackage{lmodern}
\usepackage[margin=1in]{geometry}
\usepackage{setspace}
\usepackage{microtype}
\usepackage{amsmath,amssymb,amsthm,bm}
\usepackage{booktabs}
\usepackage{float}
\usepackage{rotating}
\usepackage{tikz}

\PassOptionsToPackage{capitalise,nameinlink,noabbrev}{cleveref}
\usepackage[numbers,sort&compress]{natbib}
\usepackage[colorlinks=true,linkcolor=blue,citecolor=blue,urlcolor=blue]{hyperref}
\usepackage{orcidlink}
\usepackage{cleveref}
\usepackage{fancyhdr}

\newcommand\blfootnote[1]{%
  \begingroup
  \renewcommand\thefootnote{}\footnote{#1}%
  \addtocounter{footnote}{-1}%
  \endgroup
}

\setlength{\headheight}{14pt}
\pagestyle{fancy}
\fancyhf{}
\lhead{Timelessness Is the General Condition}
\rhead{John C. W. McKinley}
\cfoot{\thepage}

\newtheorem{proposition}{Proposition}[section]
\newtheorem{definition}[proposition]{Definition}
\newtheorem{remark}[proposition]{Remark}
\newtheorem{lemma}[proposition]{Lemma}

\title{\textbf{Timelessness Is the General Condition: Spacetime Is the Special Case}}
\author{John C. W. McKinley \orcidlink{0009-0005-7097-5035}}
\date{April 25, 2026}

\begin{document}

\maketitle

\blfootnote{\scriptsize This version published at \url{https://doi.org/10.5281/zenodo.19771925}.}

\begin{abstract}
This paper advances one claim: timelessness is the general condition, and
spacetime is the special case. On this view, lawful reality is not fundamentally
ordered by an internal timed middle. Timed sequence belongs instead to spacetime,
the special regime in which order, geometry, and measured duration appear. The
argument rests on three grounds: time is non-absolute in general relativity, time
is absent in the null case, and spacetime cannot be the condition of its own
appearance.
\end{abstract}


\section{Introduction}

This paper advances one claim: timelessness is the general condition, and
spacetime is the special case.

The null case is where this hierarchy first becomes visible inside established
physics. The published photon-side no-go sequence
\citep{McKinleyNullProperTime2025,McKinleyNoRestFrame2025,McKinleyNullCurves2025,McKinleyWavefunctionNoPath2026,McKinleyRetrocausal2026}
establishes that null proper time withholds an internally timed and spatially
traversed photon middle. The present paper does not re-prove those restrictions.
It treats them as the exposed form of a more general rule: timed spacetime
sequence is not the senior condition of lawful reality, but a special regime in
which order, geometry, and measured duration appear.

That is the reversal. The universe is not best understood as a fundamentally
timed system in which rare timeless cases occasionally appear. The order is the
opposite. Timeless lawful relation is general. Timebound spacetime appearance is
special.

The bedrock statement of TLM \citep{McKinleyBedrock2026} already
contains, in compressed form, the claim that some lawful physical relations are
not governed by internal time variables. The present paper foregrounds that
claim and establishes the resulting hierarchy---timelessness as general,
spacetime as special---on grounds independent of the null case alone.


\section{The Main Claim}

The claim of the present paper is that timed spacetime sequence is not the
universal default, but a special regime of observed order, duration, geometry,
and record. Timeless lawful relation is the general condition. Spacetime is the
special case.

\begin{definition}[General condition]
The general condition is the senior condition from which displayed special cases
are understood.
\end{definition}

\begin{definition}[Special case]
A special case is a constrained regime in which what is more general appears under
added structure.
\end{definition}

\begin{proposition}
Timeless lawful relation is the general condition, and spacetime is the special
case.
\end{proposition}

\begin{proof}
Time is not the senior condition of lawful reality.

First, in general relativity, time is non-absolute. Measured duration varies with
gravitational field, motion, and spacetime geometry. A feature that bends with
the displayed regime is not the most general condition; it is a feature of that
regime.

Second, in the null case, time is absent rather than merely flexible. The photon
has no internal proper time, no rest-frame persistence template, and no licensed
timed middle. The published null-case no-go sequence therefore shows that lawful
physical relation need not be internally time-ordered.

Third, cosmogenesis itself cannot be treated as an event already inside ordinary
spacetime sequence. If spacetime is what appears, then spacetime cannot also be the prior condition
that explains its own appearance. The pre-spacetime condition is therefore not governed by ordinary spacetime
time.

Together these points establish the hierarchy. Time is non-absolute within
spacetime, absent in the null case, and not prior to spacetime itself. It is not
the universal container of lawful reality. Timeless lawful relation is therefore
the general condition, and spacetime is the special case.
\end{proof}

Ordinary interpretation tends to assume that timebound sequence is basic and that
timelessness, if admitted at all, is exceptional. The present claim reverses that
order. Timeless lawful relation is basic. Spacetime sequence is the specialized
regime.


\section{Conclusion}

This paper has advanced one claim: timelessness is the general condition, and
spacetime is the special case.

Time is non-absolute in general relativity, absent in the null case, and not
prior to spacetime in the order of conditioning. Together these establish the
hierarchy. Timed sequence is not the senior condition of lawful reality. It is
the special regime in which order, geometry, and measured duration appear.

Timelessness is general. Spacetime is special.

\begin{thebibliography}{99}

\bibitem{McKinleyNullProperTime2025}
J. C. W. McKinley, \emph{Taking Null Proper Time Seriously: An Interpretive Clarification of Null Proper Time},
Zenodo (2025). \href{https://doi.org/10.5281/zenodo.18004632}{doi:10.5281/zenodo.18004632}.

\bibitem{McKinleyNoRestFrame2025}
J. C. W. McKinley, \emph{No Rest Frame, No Persistence: A Kinematic Constraint on Photon Interpretation},
Zenodo (2025). \href{https://doi.org/10.5281/zenodo.18005884}{doi:10.5281/zenodo.18005884}.

\bibitem{McKinleyNullCurves2025}
J. C. W. McKinley, \emph{Null Curves Without Carriers: Resolving an Ontological Tension in Relativistic Geometry},
Zenodo (2025). \href{https://doi.org/10.5281/zenodo.18028886}{doi:10.5281/zenodo.18028886}.

\bibitem{McKinleyWavefunctionNoPath2026}
J. C. W. McKinley, \emph{Wavefunction Prediction Does Not License a Photon Path},
Zenodo (2026). \href{https://doi.org/10.5281/zenodo.19504772}{doi:10.5281/zenodo.19504772}.

\bibitem{McKinleyRetrocausal2026}
J. C. W. McKinley, \emph{Retrocausal Objections Are Disallowed for the Photon},
Zenodo (2026). \href{https://doi.org/10.5281/zenodo.19648209}{doi:10.5281/zenodo.19648209}.

\bibitem{McKinleyBedrock2026}
J. C. W. McKinley,
\emph{A Minimal Structural Statement of the Timeless Light Model},
Zenodo (2026).
DOI:\,\href{https://doi.org/10.5281/zenodo.19167403}{10.5281/zenodo.19167403}.

\end{thebibliography}

\end{document}

```

</details>

---

### [2026] If a New Causal Chain Begins, a Non-Internal Contribution Exists
*   **DOI:** [10.5281/zenodo.19752798](https://doi.org/10.5281/zenodo.19752798)
*   **Date:** 24 April 2026

<details markdown="1">
<summary><b>Click to view Raw LaTeX Source</b></summary>

```latex
\documentclass[12pt,onecolumn]{article}

\usepackage[utf8]{inputenc}
\usepackage[T1]{fontenc}
\usepackage{lmodern}
\usepackage[margin=1in]{geometry}
\usepackage{microtype}
\usepackage{setspace}
\usepackage{amsmath,amssymb,amsthm}


\newcommand\blfootnote[1]{%
  \begingroup
  \renewcommand\thefootnote{}\footnote{#1}%
  \addtocounter{footnote}{-1}%
  \endgroup
}


\usepackage[colorlinks=true,linkcolor=blue,citecolor=blue,urlcolor=blue]{hyperref}
\usepackage{orcidlink}
\PassOptionsToPackage{capitalise,nameinlink,noabbrev}{cleveref}
\usepackage{cleveref}

\usepackage{fancyhdr}

\setstretch{1.08}

\pagestyle{fancy}
\fancyhf{}
\setlength{\headheight}{14pt}
\lhead{If a New Causal Chain Begins, a Non-Internal Contribution Exists}
\rhead{John C. W. McKinley}
\cfoot{\thepage}

\newtheorem{proposition}{Proposition}
\newtheorem{definition}{Definition}
\newtheorem{remark}{Remark}

\title{\textbf{If a New Causal Chain Begins, a Non-Internal Contribution Exists}
}
\author{John C. W. McKinley\,\orcidlink{0009-0005-7097-5035}
}
\date{April 24, 2026}

\begin{document}
\maketitle


\blfootnote{\scriptsize This version published at \url{https://doi.org/10.5281/zenodo.19752798}.}

\begin{abstract}
No closed physical system internally fixes the onset and direction of a new causal chain among multiple lawful possibilities.\cite{McKinley2026Closed} If a new causal chain nonetheless begins, then some contribution not contained within the closed physical description must exist. The claim concerns only the existence of such a contribution. It does not identify its ontology.
\end{abstract}

\section*{Statement}

The central thesis of this note is simple:

\begin{quote}
\textbf{Core Thesis.} The beginning of a new causal chain in a closed physical
system requires a non-internal contribution.
\end{quote}


Let $S(t)$ denote a closed physical state description of a system over some interval. Suppose that, at a definite moment $t^\ast$, a new causal chain begins and that more than one lawful continuation is available. Since no closed physical system internally fixes either the onset of that chain or its realized direction\cite{McKinley2026Closed}, the beginning of the chain requires some contribution not contained within $S(t)$.

\begin{definition}[Closed physical description]
A \emph{closed physical description} is a description containing only the laws, state-terms, and causal resources internal to the system under consideration.
\end{definition}

\begin{definition}[Non-internal contribution]
A \emph{non-internal contribution} is a contribution that is not contained within the closed physical description $S(t)$.
\end{definition}


\begin{proposition}[Existence of a non-internal contribution]
Since a closed physical description does not internally fix the onset and direction of
a new causal chain among multiple lawful possibilities, the beginning of such a chain
requires a non-internal contribution.
\end{proposition}

\begin{proof}
By hypothesis, a new causal chain begins at a definite moment and a particular lawful continuation is realized. By the closed-system initiation no-go,\cite{McKinley2026Closed} the closed physical description does not internally fix either the onset of that chain or its realized direction. Therefore the beginning of the chain is not fully supplied by the closed description alone. Since the chain nonetheless begins, some contribution not contained within the closed physical description must exist. Hence a non-internal contribution exists.
\end{proof}

\begin{remark}[Existence claim only]
The present note makes an existence claim only. It does not specify the nature, magnitude, persistence, or interpretation of the non-internal contribution whose existence follows from the beginning of the chain.
\end{remark}

\begin{remark}[Not a characterization]
To conclude that a non-internal contribution exists is not to determine whether it is best described as an initiating increment, a boundary contribution, or under some further characterization. Those questions lie beyond the scope of the present note.
\end{remark}

\begin{remark}[Dependence on the prior no-go]
This result is conditional on the prior no-go: No closed physical system internally fixes the onset and direction of a new causal chain among multiple lawful possibilities.\cite{McKinley2026Closed}
\end{remark}

\section*{Falsifier}

The claim of this note fails if either of the following is shown:
\begin{enumerate}
    \item a closed physical description internally fixes the onset and direction of a new causal chain after all, or
    \item a new causal chain begins even though nothing beyond the closed physical description contributes to its beginning.
\end{enumerate}

\section*{Conclusion}

Since a closed physical description does not internally fix the onset and direction
of a new causal chain among multiple lawful possibilities, the beginning of such a
chain requires some non-internal contribution.


\begin{thebibliography}{1}

\bibitem{McKinley2026Closed}
J. C. W. McKinley, \emph{No Closed Physical System Internally Fixes the Onset and Direction of a New Causal Chain: A Structural No-Go Result}, Zenodo (2026). DOI:\,\href{https://doi.org/10.5281/zenodo.19464781}{10.5281/zenodo.19464781}.

\end{thebibliography}

\end{document}
```

</details>

---

### [2026] Retrocausal Objections Are Disallowed for the Photon
*   **DOI:** [10.5281/zenodo.19648209](https://doi.org/10.5281/zenodo.19648209)
*   **Date:** 18 April 2026

<details markdown="1">
<summary><b>Click to view Raw LaTeX Source</b></summary>

```latex
\documentclass[12pt,letterpaper]{article}

\usepackage[T1]{fontenc}
\usepackage[utf8]{inputenc}
\usepackage{lmodern}
\usepackage{microtype}
\usepackage[margin=1in]{geometry}

\newcommand\blfootnote[1]{%
  \begingroup
  \renewcommand\thefootnote{}\footnote{#1}%
  \addtocounter{footnote}{-1}%
  \endgroup
}

\usepackage{fancyhdr}
\setlength{\headheight}{14pt}
\pagestyle{fancy}
\fancyhf{}
\lhead{Retrocausal Objections Are Disallowed for the Photon}
\rhead{John C. W. McKinley}
\cfoot{\thepage}

\usepackage{amsmath,amssymb,amsthm}
\newtheorem{proposition}{Proposition}
\newtheorem{definition}[proposition]{Definition}
\newtheorem{remark}[proposition]{Remark}

\usepackage{booktabs}
\usepackage{tikz}
\usepackage{float}

\PassOptionsToPackage{capitalise,nameinlink,noabbrev}{cleveref}

\usepackage[numbers,sort&compress]{natbib}
\usepackage[colorlinks=true,linkcolor=blue,citecolor=blue,urlcolor=blue]{hyperref}
\usepackage{orcidlink}
\usepackage{cleveref}

\title{Retrocausal Objections Are Disallowed for the Photon}
\author{John C. W. McKinley \orcidlink{0009-0005-7097-5035}}

\date{April 18, 2026}

\begin{document}
\maketitle

\begingroup
\blfootnote{\scriptsize This version published at \url{https://doi.org/10.5281/zenodo.19648209}.}
\endgroup

\begin{abstract}
There is no time factor for the photon. Therefore retrocausal objections regarding
the photon are disallowed. Such objections require a timed intermediate subject on
which backward influence, endpoint foreknowledge, or route-coordination problems
could be built. But the photon has no such time-bearing middle. What remains is a
lawful state change, while duration, delay, and geometric order belong to spacetime
description. The result is not new physics. It is the direct consequence of taking
the null case literally.
\end{abstract}

\section{Introduction}

A familiar objection to non-transit accounts of the photon is that they seem to
invite retrocausality. If the photon does not possess an internally timed middle,
then how can emission and absorption be lawfully related without the destination
already being built in from the future?

This paper makes a narrow no-go claim. There is no time factor for the photon.
Therefore retrocausal objections regarding the photon are disallowed.

The reason is simple. A retrocausal objection requires a timed intermediate
subject on which one may place backward influence, endpoint foreknowledge,
route-finding, waiting, updating, or other coordination across moments. But the
photon has no such timed middle. The objection therefore has no licensed target
in the photon case.

This paper does not re-prove established restrictions. It draws the next
consequence from them.









\section{Prior Restrictions Presupposed}

\begin{proposition}[Prior restrictions]
Within the present sequence, the following restrictions are presupposed:
\begin{enumerate}
    \item null proper time withholds an internal photon duration~\citep{McKinleyNullProper2025};
    \item the absence of a rest frame withholds the ordinary persistence template~\citep{McKinleyNoRest2025};
    \item null curves do not by themselves supply carrier histories~\citep{McKinleyNullCurves2025};
    \item wavefunction prediction does not license an intermediate photon path~\citep{McKinleyWaveNoPath2026}.
\end{enumerate}
\end{proposition}

\begin{remark}
These restrictions are not established anew here. They serve as the fixed
starting point for the present no-go.
\end{remark}

\section{The No-Go}

\begin{definition}[Retrocausal objection regarding the photon]
A retrocausal objection regarding the photon is an objection that presupposes a
timed photon middle and then attributes to it backward influence, endpoint
foreknowledge, route coordination, or timed adjustment across an intermediate span.
\end{definition}

\begin{proposition}[No-go]
There is no time factor for the photon. Therefore retrocausal objections
regarding the photon are disallowed.
\end{proposition}

\begin{proof}
A retrocausal objection requires a timed intermediate subject on which one may
place backward influence, endpoint foreknowledge, route-finding, waiting,
updating, or other coordination across moments. The photon has no time factor and
therefore no such timed middle. Hence no retrocausal objection regarding the
photon has a licensed target.
\end{proof}







\section{Spacetime as the Domain of Duration}

The no-go does not remove time from physics. It localizes duration to the correct
domain. Spacetime remains the domain of duration, delay, geometry, interval
structure, and observer-side order~\citep{McKinleyBedrock2026}.

\begin{definition}[Localization of duration]
Duration, delay, temporal order, and geometric separation belong to spacetime
description rather than to the defining photon relation itself.
\end{definition}

Thus when a source emits and an observer later detects, the interval may be vast
for clocks and geometry in spacetime. That does not imply a photon-side internally
lived duration. The long interval belongs to spacetime description. The photon
does not carry an internal timeline across it.

\section{Lawful Admissibility Without In-Flight Knowledge}

The disappearance of the retrocausal objection does not make photon appearance
arbitrary. There are no unlawful photons. Standard physics already contains the
structure governing admissible outcomes: amplitudes, coupling structure,
conservation laws, symmetry restrictions, boundary conditions, and final-state
availability. The present claim denies only that these should be narrated as the
internal itinerary of a persisting photon-object.

\begin{remark}
The retrocausal objection often assumes a false dilemma: either the photon travels and
learns where to go as it proceeds, or the future endpoint reaches backward to
constrain it. The present reading rejects both horns. It does not preserve an
internally timed photon middle and then add a backward influence to repair it. It
denies the internally timed middle itself.
\end{remark}

\begin{remark}
Wavefunction language remains fully available in this reading, but not as a
description of an internally traveling photon body. The wavefunction belongs to
the lawful admissibility of observable spacetime outcomes, not to a photon-side
middle.
\end{remark}

\begin{figure}[H]
\centering
\begin{tikzpicture}[scale=1.0]

  \draw[->] (0,0) -- (0,5.5) node[above] {$t$};
  \draw[->] (0,0) -- (7,0)   node[right] {$x$};

  \fill (1.2,1.2) circle (2pt) node[left] {$E$};
  \fill (5,4) circle (2pt) node[right] {$A$};

  \draw[dashed] (1.2,1.2) -- (5,4);

  \node at (2.5,3.0) {$ds^2=0$};

  \node[anchor=west] at (4.5,2.5) {\footnotesize lightlike relation only};
  \node[anchor=west] at (4.5,2.0) {\footnotesize not an occupied history};
  \node[anchor=west] at (4.5,1.5) {\footnotesize not a persisting traveler};

  \node[anchor=west] at (0.2,5.0) {\footnotesize Photon relation:};
  \node[anchor=west] at (0.2,4.55) {\footnotesize no internal time-bearing middle};

  \node[anchor=west] at (0.2,0.65) {\footnotesize Spacetime description:};
  \node[anchor=west] at (0.2,0.25)  {\footnotesize endpoint order and measured delay};

\end{tikzpicture}
\caption{The emission and absorption events are lightlike-related in spacetime
description, but the dashed segment is not to be read as an occupied intermediate
history of a persisting photon. The measured interval belongs to spacetime
description. The photon relation itself is not defined by an internal timeline.}
\end{figure}



\section{Conclusion}

There is no time factor for the photon. Therefore retrocausal objections regarding
the photon are disallowed.

Spacetime remains the domain of duration, delay, geometry, and observer-side
order. The photon relation itself is not defined by an internal timeline. The
long interval between source and observer is therefore a fact of spacetime
description, not evidence for a photon-side middle that must be coordinated from
the future.

The result is not new physics. It is the direct consequence of taking the null
case literally.



\begin{thebibliography}{9}


\bibitem[McKinley(2025a)]{McKinleyNullProper2025}
J. C. W. McKinley,
\emph{Taking Null Proper Time Seriously: An Interpretive Clarification of Null Proper Time},
Zenodo (2025).
DOI:\,\href{https://doi.org/10.5281/zenodo.18004632}{10.5281/zenodo.18004632}.

\bibitem[McKinley(2025b)]{McKinleyNoRest2025}
J. C. W. McKinley,
\emph{No Rest Frame, No Persistence: A Kinematic Constraint on Photon Interpretation},
Zenodo (2025).
DOI:\,\href{https://doi.org/10.5281/zenodo.18005884}{10.5281/zenodo.18005884}.

\bibitem[McKinley(2025c)]{McKinleyNullCurves2025}
J. C. W. McKinley,
\emph{Null Curves Without Carriers: Resolving an Ontological Tension in Relativistic Geometry},
Zenodo (2025).
DOI:\,\href{https://doi.org/10.5281/zenodo.18028886}{10.5281/zenodo.18028886}.

\bibitem[McKinley(2026b)]{McKinleyWaveNoPath2026}
J. C. W. McKinley,
\emph{Wavefunction Prediction Does Not License a Photon Path},
Zenodo (2026).
DOI:\,\href{https://doi.org/10.5281/zenodo.19504772}{10.5281/zenodo.19504772}.

\bibitem{McKinleyBedrock2026}
J. C. W. McKinley,
\emph{A Minimal Structural Statement of the Timeless Light Model},
Zenodo (2026).
DOI:\,\href{https://doi.org/10.5281/zenodo.19167403}{10.5281/zenodo.19167403}.

\end{thebibliography}

\end{document}
```

</details>

---

### [2026] Iron Filings Do Not Prove Field Substance — A Short Interpretive No-Go
*   **DOI:** [10.5281/zenodo.19639455](https://doi.org/10.5281/zenodo.19639455)
*   **Date:** 17 April 2026

<details markdown="1">
<summary><b>Click to view Raw LaTeX Source</b></summary>

```latex
\documentclass[12pt,letterpaper]{article}

\usepackage[T1]{fontenc}
\usepackage[utf8]{inputenc}
\usepackage{lmodern}
\usepackage{microtype}
\usepackage[margin=1in]{geometry}

\usepackage{fancyhdr}
\setlength{\headheight}{14pt}
\pagestyle{fancy}
\fancyhf{}
\lhead{Iron Filings Do Not Prove Field Substance}
\rhead{John C. W. McKinley}
\cfoot{\thepage}

\usepackage{amsmath,amssymb,amsthm}
\newtheorem{proposition}{Proposition}
\newtheorem{definition}[proposition]{Definition}
\newtheorem{remark}[proposition]{Remark}

\newcommand\blfootnote[1]{%
  \begingroup
  \renewcommand\thefootnote{}\footnote{#1}%
  \addtocounter{footnote}{-1}%
  \endgroup
}

\usepackage[numbers,sort&compress]{natbib}
\usepackage[colorlinks=true,linkcolor=blue,citecolor=blue,urlcolor=blue]{hyperref}
\usepackage{orcidlink}
\PassOptionsToPackage{capitalise,nameinlink,noabbrev}{cleveref}
\usepackage{cleveref}

\title{Iron Filings Do Not Prove Field Substance\\
\large A Short Interpretive No-Go}
\author{John C. W. McKinley\,\orcidlink{0009-0005-7097-5035}
}
\date{April 17, 2026}

\begin{document}
\maketitle


\blfootnote{\scriptsize This version published at \url{https://doi.org/10.5281/zenodo.19639455}.}
\blfootnote{\scriptsize Related work includes \emph{A Minimal Structural Statement of the Timeless Light Model}, Zenodo, 2026, DOI: \href{https://doi.org/10.5281/zenodo.19167403}{10.5281/zenodo.19167403}; and \emph{Wavefunction Prediction Does Not License a Photon Path}, Zenodo, 2026, DOI: \href{https://doi.org/10.5281/zenodo.19504772}{10.5281/zenodo.19504772}.}

\begin{abstract}
This paper makes one narrow interpretive no-go claim. The visible aggregation
of iron filings into extended spatial patterns around a magnet does not license
the conclusion that the patterned region is materially occupied by a persisting
substance. The filings are pieces of matter in spacetime responding under lawful
physical constraints to a magnetic environment. Their organized arrangement shows
how matter settles into a patterned outcome; it does not by itself establish that
the governing field pattern is materially occupied in the same ordinary sense as
the filings themselves. A visible response structure is not by itself substance
ontology.
\end{abstract}

\section{Introduction}

The iron-filings demonstration is visually persuasive. Matter settles into arcs
and bands around a magnet, and the eye is invited to say more than the
demonstration shows. Because the pattern is extended in space and visibly ordered,
it is easy to slide from a lawful response in matter to the stronger claim that
the patterned region is materially occupied by a persisting substance.

That further claim is not licensed.

The present paper makes one narrow point. The arrangement of filings shows that
matter placed in a magnetic environment responds lawfully and settles into a
structured visible pattern. It does not follow that the governing pattern is
itself a substance-like occupant of the region in the same ordinary sense as the
filings themselves.

This paper does not deny electromagnetism, magnetic fields, or standard
descriptive practice. It denies only the stronger ontological inference from
visible response structure to field substance.

\section{Scope}

The target is not Maxwell theory, quantum theory, or any predictive formalism.
The target is a common ontological overreach:

\begin{quote}
Because matter arranges itself into an extended pattern under lawful magnetic
conditions, the patterned region itself must be materially occupied by a
persisting substance spread through space.
\end{quote}

That inference is stronger than the evidence supports. A response pattern in
matter does not by itself settle the ontological status of what lawfully
constrains that response.

The narrower alternative is enough. One may say that the region is lawfully
structured for magnetic effect, and that suitably placed matter becomes
magnetized, reorients, and settles accordingly. None of that by itself proves a
material occupant of the region over and above the filings themselves.

\section{Definitions}

\begin{definition}[Response structure]
A response structure is an organized spatial arrangement of matter produced under
lawful physical constraints.
\end{definition}

\begin{definition}[Field substance]
Field substance, as meant here, is a persisting substance-like occupant of the
patterned region, treated as though it were physically present there in the same
ordinary sense that matter is physically present there.
\end{definition}

\section{The No-Go}

\begin{proposition}
The aggregation of iron filings into spatial patterns around a magnet does not
prove that the patterned region is materially occupied by a persisting substance.
\end{proposition}

\begin{proof}
Iron filings are pieces of matter in spacetime. When placed near a magnet, they
become magnetized, rotate, attract, and settle under local electromagnetic
conditions into an organized visible arrangement. What the demonstration directly
establishes is therefore that matter responds lawfully and non-randomly in the
relevant magnetic environment.

That is enough to show that the region is lawfully structured for magnetic
effect. It is not enough to show that the region is materially occupied by a
persisting substance in the same ordinary sense as the filings. The visible
pattern is composed of filings. The filings are what visibly occupy the region
as matter. Their ordered arrangement does not by itself settle whether the
governing structure should be read as a material occupant, a field description,
or a lawful constraint structure.

Therefore the aggregation of iron filings into spatial patterns around a magnet
does not prove that the patterned region is materially occupied by a persisting
substance.
\end{proof}

\section{Why the Inference Fails}

The persuasive force of the demonstration comes from a transfer. The eye sees
matter arranged in space and quietly attributes that same materiality to the
governing pattern itself. But the transfer is not logically forced.

What the demonstration shows is simple: matter is present, matter is responsive
to magnetic conditions, and matter can settle into a structured visible pattern.
What it does not show, by mere appearance, is that the patterned region contains
a persisting material substance.

The key distinction is therefore direct. A visible response structure is one
thing. Substance ontology is another.

\section{Response Structure and Ontology}

A response structure is an organized arrangement of matter under lawful
conditions. Substance ontology is a stronger claim about what materially exists
in the region as a persisting occupant.

The filings demonstration establishes the former, not the latter.

The field need not be treated as a thing in the region. It may instead be
treated as the lawful structure of the region. On that reading, electromagnetism
specifies what is lawfully true of the region and how suitable matter may behave
there. The filings then display that lawful structure by their behavior.

To infer field substance from the visible arrangement is therefore to transfer
ontology from response to rule. Matter visibly occupies the patterned region
because the filings themselves are matter. It does not follow that the governing
pattern is thereby materially occupied by a persisting substance.

\section{Relation to the Minimal Canon of TLM}

The present point aligns cleanly with the minimal canon of the Timeless Light
Model. The current bedrock statement holds that some lawful physical relations
are not governed by internal time variables, that spacetime is the domain of
ordered description, and that the photon is not a particle in transit but a
lawful change as it appears in spacetime \cite{McKinleyBedrock2026}. The
wavefunction no-go adds a related restriction: the mathematical success of the
wavefunction in predicting lawful absorption outcomes does not license the
conclusion that a photon follows an intermediate spacetime path between endpoints
\cite{McKinleyWaveNoGo2026}.

The present paper makes the analogous restraint at the level of visual pedagogy.
A visible pattern in matter does not license the conclusion that the patterned
region is materially occupied by a persisting substance. In the same way that
lawful outcome structure is not path ontology, visible response structure is not
substance ontology.

\begin{remark}
The central claim of this paper is independent and local. The filings
demonstration does not, by itself, settle the ontology of the patterned region.
The relation to TLM is therefore one of alignment, not dependence.
\end{remark}

\section{Conclusion}

This paper has made one narrow negative claim. The aggregation of iron filings
into extended spatial patterns around a magnet does not prove that the patterned
region is materially occupied by a persisting substance.

What the demonstration establishes is real and lawful: matter responds in a
structured way under magnetic conditions, and the resulting arrangement may be
extended and visible in space. What it does not by itself establish is the
further claim that the governing pattern is therefore a substance-like occupant
of the region in the same ordinary sense as the filings themselves.

Response structure is real. It is not by itself substance ontology.

\begin{thebibliography}{9}

\bibitem{McKinleyBedrock2026}
J. C. W. McKinley,
\emph{A Minimal Structural Statement of the Timeless Light Model},
Zenodo (2026).
DOI: \href{https://doi.org/10.5281/zenodo.19167403}{10.5281/zenodo.19167403}.

\bibitem{McKinleyWaveNoGo2026}
J. C. W. McKinley,
\emph{Wavefunction Prediction Does Not License a Photon Path: A Short Interpretive No-Go},
Zenodo (2026).
DOI: \href{https://doi.org/10.5281/zenodo.19504772}{10.5281/zenodo.19504772}.

\end{thebibliography}

\end{document}
```

</details>

---

### [2026] Wavefunction Prediction Does Not License a Photon Path — A Short Interpretive No-Go
*   **DOI:** [10.5281/zenodo.19504772](https://doi.org/10.5281/zenodo.19504772)
*   **Date:** 12 April 2026

<details markdown="1">
<summary><b>Click to view Raw LaTeX Source</b></summary>

```latex
\documentclass[12pt]{article}

% Encoding and fonts
\usepackage[utf8]{inputenc}
\usepackage[T1]{fontenc}
\usepackage{lmodern}
\usepackage{microtype}

% Layout
\usepackage[margin=1in]{geometry}
\usepackage{setspace}
\onehalfspacing

% Math and theorem environments
\usepackage{amsmath,amssymb,amsthm}
\newtheorem{proposition}{Proposition}

% Bibliography and links
\usepackage[numbers,sort&compress]{natbib}
\PassOptionsToPackage{capitalise,nameinlink,noabbrev}{cleveref}
\usepackage[colorlinks=true,linkcolor=blue,citecolor=blue,urlcolor=blue]{hyperref}
\usepackage{orcidlink}
\usepackage{cleveref}

% Header
\usepackage{orcidlink}
\usepackage{fancyhdr}
\pagestyle{fancy}
\fancyhf{}
\lhead{Wavefunction Prediction Does Not License a Photon Path}
\rhead{John C. W. McKinley}
\cfoot{\thepage}
\setlength{\headheight}{14pt}

\title{\textbf{Wavefunction Prediction Does Not License a Photon Path}\\
\large A Short Interpretive No-Go}
\author{John C. W. McKinley
\orcidlink{0009-0005-7097-5035}}
\date{April 12, 2026}

\begin{document}

\maketitle

\begingroup
\footnotetext{\scriptsize This version published at \url{https://doi.org/10.5281/zenodo.19504772}.}
\endgroup


\begin{abstract}
This paper makes one narrow interpretive no-go claim. The mathematical success of
the wavefunction in predicting lawful absorption outcomes does not license the
conclusion that a photon follows an intermediate spacetime path between endpoints.
For the photon, relativistic null structure withholds the ordinary timelike template of
internal duration, traversed route, and intermediate history. The wavefunction assigns
amplitudes---mathematical quantities whose combination determines the probabilities of
observed outcomes---and organizes the lawful structure of absorption events without
thereby describing where the photon is in between.

\end{abstract}

\section{Introduction}

This paper is narrow by design. It does not revise quantum mechanics, alter quantum field
theory, or introduce a new dynamical law. It makes a single interpretive claim about what
may be inferred from wavefunction prediction in the photon case.

The target is not the wavefunction as mathematics. Its predictive success is not in dispute.
The target is the extra step from successful prediction of lawful absorption outcomes
to the claim that the formalism thereby tells us where the photon is in between, or what intermediate
spacetime path it follows between endpoints.


That step is not licensed. For the photon, relativistic null structure---the lightlike case
in relativity, in which no proper time elapses along the path\footnote{\scriptsize See footnote \ref{fn:lightlike}.} and no rest frame exists for
the photon---withholds the ordinary timelike template of internal duration, traversed route,
and intermediate history. Prediction of an absorption point is not identification of an
intermediate photon path.

The same point covers interference, here understood as the patterned enhancement and
suppression of detector outcomes under fixed experimental conditions. Repeated trials under
fixed experimental conditions yield stable patterns in localized detector outcomes, and
standard quantum theory accounts for those patterns through the combination of quantum
amplitudes. What does not follow is that the lawfully weighted regions in the formalism
identify where the photon is in between. Lawful outcome structure is not path ontology.

The broader null-case restriction used here has already been developed elsewhere:
null proper time withholds an internal photon duration
\cite{McKinleyNullProperTime}, the absence of a rest frame withholds the
standard persistence template \cite{McKinleyNoRestFrame}, null curves do not
supply carrier histories \cite{McKinleyNullCurves}, and the minimal structural
statement of the Timeless Light Model compresses those restrictions into the
claim that the photon is not a particle in transit \cite{McKinleyBedrock}.

\section{The No-Go}

\begin{proposition}
The mathematical success of the wavefunction in predicting lawful absorption
outcomes does not license the conclusion that a photon follows an intermediate spacetime
path between endpoints.
\end{proposition}

\begin{proof}
The wavefunction contributes to the calculation of amplitudes, probabilities, and
outcome structure. That establishes predictive success. It does not by itself establish that
the formalism describes where a photon is between emission and absorption.

In the photon case, the added path claim is further blocked by relativistic null structure.
For a photon, no proper time elapses along the
null path\footnote{\label{fn:lightlike} \scriptsize A path of this kind has zero spacetime interval, written $ds^2 = 0$, which implies that no proper time elapses along it, written $d\tau = 0$. Here $\tau$ (tau)
denotes proper time, that is, the time recorded by a clock traveling with the object,
and $d$ denotes an infinitesimal increment. In relativity, a path with this zero-interval
character is called \textit{null} or \textit{lightlike}. This is what is meant here by
\textit{relativistic null structure}. For a photon, it means there is no elapsed internal
time along the path itself. In that sense, the null case withholds the ordinary timelike
template of an internally unfolding middle.}, no rest frame is available, and thus the ordinary timelike
template of internal duration, traversed route, and intermediate history is withheld. There is
therefore no internally timed or spatially traversed middle for the wavefunction to describe.

The same point covers interference, including approaches in which all
mathematically allowed routes between endpoints enter the calculation. In such
approaches, the routes function as terms contributing to the predicted outcome,
not as trajectories assigned to a persisting physical carrier.

Hence the mathematical success of the wavefunction in predicting lawful absorption
outcomes does not license the conclusion that a photon follows an intermediate spacetime
path between endpoints.
\end{proof}


\section{Conclusion}

The result is interpretive clarity. The mathematical success of the wavefunction in
predicting lawful absorption outcomes does not by itself justify the conclusion that a
photon follows an intermediate spacetime path between endpoints, because in the photon
case relativistic null structure already withholds the ordinary timelike template of an
internally timed and spatially traversed middle.


The wavefunction may continue to govern amplitudes, interference structure, and detector
statistics without being turned into a description of where the photon is in between.
What is removed is only the unlicensed inference from predictive success to transit ontology.

\begin{thebibliography}{99}


\bibitem{McKinleyNullProperTime}
J.~C.~W.~McKinley,
\textit{Taking Null Proper Time Seriously: An Interpretive Clarification of Null Proper Time},
Zenodo (2025).
DOI: \href{https://doi.org/10.5281/zenodo.18004632}{10.5281/zenodo.18004632}.

\bibitem{McKinleyNoRestFrame}
J.~C.~W.~McKinley,
\textit{No Rest Frame, No Persistence: A Kinematic Constraint on Photon Interpretation},
Zenodo (2025).
DOI: \href{https://doi.org/10.5281/zenodo.18005884}{10.5281/zenodo.18005884}.

\bibitem{McKinleyNullCurves}
J.~C.~W.~McKinley,
\textit{Null Curves Without Carriers: Resolving an Ontological Tension in Relativistic Geometry},
Zenodo (2025).
DOI: \href{https://doi.org/10.5281/zenodo.18028886}{10.5281/zenodo.18028886}.

\bibitem{McKinleyBedrock}
J.~C.~W.~McKinley,
\textit{A Minimal Structural Statement of the Timeless Light Model},
Zenodo (2026).
DOI: \href{https://doi.org/10.5281/zenodo.19167403}{10.5281/zenodo.19167403}.

\end{thebibliography}

\end{document}
```

</details>

---

### [2026] No Closed Physical System Internally Fixes the Onset and Direction of a New Causal Chain
*   **DOI:** [10.5281/zenodo.19464781](https://doi.org/10.5281/zenodo.19464781)
*   **Date:** 7 April 2026

<details markdown="1">
<summary><b>Click to view Raw LaTeX Source</b></summary>

```latex
\documentclass[12pt,onecolumn]{article}

\usepackage[utf8]{inputenc}
\usepackage[T1]{fontenc}
\usepackage{lmodern}
\usepackage[margin=1in]{geometry}
\usepackage{microtype}
\usepackage{setspace}
\usepackage{amsmath,amssymb,amsthm}





\usepackage{natbib}
\usepackage{orcidlink}
\usepackage{hyperref}
\hypersetup{colorlinks=true,linkcolor=blue,urlcolor=blue,citecolor=blue}
\usepackage{cleveref}
\usepackage{fancyhdr}

\setstretch{1.08}

\pagestyle{fancy}
\fancyhf{}
\setlength{\headheight}{14pt}
\lhead{Onset and Direction}
\rhead{John C. W. McKinley}
\cfoot{\thepage}

\newtheorem{proposition}{Proposition}
\newtheorem{definition}{Definition}
\newtheorem{remark}{Remark}

\title{\Large\textbf{No Closed Physical System Internally Fixes the Onset and Direction of a New Causal Chain}\\
\large A Structural No-Go Result}
\author{John C. W. McKinley\,\orcidlink{0009-0001-0878-8047}}
\date{7 April 2026}


\begin{document}
\maketitle




\begingroup
\renewcommand{\thefootnote}{}

\footnotetext{This version published at \href{https://doi.org/10.5281/zenodo.19464781}{\color{blue}https://doi.org/10.5281/zenodo.19464781}.}
 
\endgroup


\begin{abstract}
This note states a structural no-go claim. No closed physical system internally fixes both the onset of a new causal chain and the lawful target toward which it proceeds when multiple lawful targets are open. A closed physical description may govern lawful evolution once a process is underway, and it may specify which targets are lawfully available. What it does not by itself supply is a sufficient internal fixing condition that determines both why a new chain begins at one definite moment rather than not yet and why one lawful target is realized rather than another. The purpose of the note is not to add machinery, but to block the mistaken identification of lawful structure with actual fixation.
\end{abstract}



\section*{Introduction}
This note makes explicit a structural distinction that is often blurred: lawful propagation within a closed physical description is not the same as internal fixation of the onset of a new causal chain and the direction it takes. The paper’s target is not lawful evolution as such, but the mistake of treating lawful structure as though it already fixed definite onset and definite direction.

\section*{Statement}

The thesis of this note is simple:

\begin{quote}
\textbf{Core Thesis.} No closed physical system internally fixes the onset and direction of a new causal chain among multiple lawful possibilities.
\end{quote}

Let $S(t)$ denote a closed physical state description of a system over some interval. Suppose that, at a definite moment $t^\ast$, a new causal chain begins and that more than one lawful continuation is physically admissible. The claim is that the closed description does not itself fix either the onset of that chain or its realized direction.

\begin{definition}[Closed physical system]
A \emph{closed physical system} is a system whose description contains only the laws, state-terms, and causal resources internal to the system itself.
\end{definition}

\begin{definition}[Onset]
The \emph{onset} of a new causal chain is the definite fact that the chain begins at $t^\ast$ rather than not yet.
\end{definition}


\begin{definition}[Direction]
The \emph{direction} of a new causal chain is the realized lawful target toward which it proceeds.
\end{definition}

\begin{proposition}[No-go for internal fixation in closed systems]
No closed physical system internally fixes the onset and direction of a new causal chain among multiple lawful possibilities.
\end{proposition}

\begin{proof}
Assume for contradiction that a closed physical system internally fixes both the onset and the direction of a new causal chain. Then the closed description must contain a sufficient internal fixing condition that determines both why the chain begins at $t^\ast$ rather than not yet and why one lawful continuation is realized rather than another.

That requirement cannot be met in either of the only available ways.

First, if the alleged fixing condition is identified with some prior internal state, differentiation, or lawful structure, then the work of fixation has only been moved earlier. The same question immediately reappears: what internally fixes the relevance of that prior condition, and what internally fixes its realized outcome rather than another? Relocation is not resolution.

Second, if the closed description is said to provide only laws of propagation or a set of admissible continuations, then no sufficient internal fixing condition has been supplied at all. Propagation governs how a chain unfolds once underway. Admissibility specifies what may occur. Neither fixes the definite onset of a new chain or its realized direction.

So the closed description yields either displaced fixation or no fixation. Neither gives internal fixation of both onset and direction. This contradicts the assumption. Therefore no closed physical system internally fixes the onset and direction of a new causal chain among multiple lawful possibilities.
\end{proof}

\begin{remark}[Propagation is not onset]
A closed physical description may govern lawful evolution once a chain is underway. That is not the same as fixing the onset of a new chain.
\end{remark}

\begin{remark}[Admissibility is not direction]
A closed physical description may specify multiple lawful continuations. That is not the same as fixing which continuation is realized.
\end{remark}

\begin{remark}[Relocation is not resolution]
Reassigning the work of fixation to earlier internal structure does not solve the problem. It restates it at an earlier point.
\end{remark}

\begin{remark}[Scope]
This note addresses only whether a closed physical description internally fixes the onset and direction of a new causal chain.
\end{remark}

\section*{Falsifier}

This claim fails only if a closed physical description is exhibited that internally fixes both (i) the onset of a new causal chain and (ii) its realized direction among multiple lawful alternatives, without merely relocating either task to prior internal structure and without reducing the claim to propagation rules or admissibility conditions alone.

\section*{Conclusion}

Closed systems may contain laws, states, and lawful possibilities. That is not yet an internal fixing condition. The claim of the present note is that no closed physical description, taken strictly as closed, internally fixes both the onset and the direction of a new causal chain.
\end{document}
```

</details>

---

### [2026] A Minimal Structural Statement of the Timeless Light Model (v3.921)
*   **DOI:** [10.5281/zenodo.19167403](https://doi.org/10.5281/zenodo.19167403)
*   **Date:** 22 March 2026

<details markdown="1">
<summary><b>Click to view Raw LaTeX Source</b></summary>

```latex
\documentclass[12pt,letterpaper,onecolumn]{article}

% ---------- Encoding / fonts ----------
\usepackage[T1]{fontenc}
\usepackage[utf8]{inputenc}
\usepackage{lmodern}

% ---------- Page / spacing ----------
\usepackage[margin=1in,headheight=14pt]{geometry}
\usepackage{setspace}
\setstretch{1.12}
\usepackage{microtype}

% ---------- Math ----------
\usepackage{amsmath,amssymb,amsthm,bm}

% ---------- Tables / arrays ----------
\usepackage{booktabs,longtable,tabularx,array}
\newcolumntype{L}[1]{>{\raggedright\arraybackslash}p{#1}}

% ---------- Graphics / figures ----------
\usepackage{graphicx}
\usepackage{float}
\usepackage{tikz}
\usetikzlibrary{arrows.meta,decorations.pathreplacing}
\usepackage{rotating}

% ---------- Boxes / framing ----------
\usepackage[most]{tcolorbox}
\usepackage{framed}

% ---------- Lists ----------
\usepackage{enumitem}

% ---------- Header / footer ----------
\usepackage{fancyhdr}
\pagestyle{fancy}
\fancyhf{}
\lhead{Minimal Structural Statement of TLM}
\rhead{John C. W. McKinley}
\cfoot{\thepage}



\usepackage{natbib}
\usepackage{cleveref}
\usepackage{orcidlink}
\usepackage{hyperref}
\hypersetup{colorlinks=true,linkcolor=blue,urlcolor=blue,citecolor=blue}


% ---------- Theorem environments ----------
\newtheorem{proposition}{Proposition}[section]
\newtheorem{definition}[proposition]{Definition}
\newtheorem{remark}[proposition]{Remark}



% ---------- Quote box ----------
\newtcolorbox{tlmquote}{
  colback=gray!8,
  colframe=black,
  boxrule=0.6pt,
  arc=2pt,
  left=6pt,
  right=6pt,
  top=6pt,
  bottom=6pt
}

\title{\textbf{A Minimal Structural Statement of the Timeless Light Model}}
\author{John C. W. McKinley\orcidlink{0009-0005-7097-5035}}
\date{22 March 2026}

\begin{document}
\maketitle

\begingroup
\renewcommand{\thefootnote}{*}
\footnotetext{This paper supersedes earlier minimal statements of the Timeless Light Model by restating the minimal canon in a simpler and more direct form.}
\endgroup

\begingroup
\renewcommand{\thefootnote}{}
  \footnotetext{This version published at
  \href{https://doi.org/10.5281/zenodo.19167403}{https://doi.org/10.5281/zenodo.19167403}.}
\endgroup





\begin{abstract}
This paper introduces no new physical theory, equations, or empirical claims. Its purpose is to restate the minimal core of the Timeless Light Model (TLM) in a simpler and more direct form than earlier scaffolded presentations. The central claim is that the null status of the photon should be treated as an ontological constraint rather than as a merely formal result: if proper time is disallowed for the photon and no photon rest frame exists, then a temporally lived intermediate photon history is not licensed by the formalism. The present statement therefore adopts a compact canon: some lawful physical relations have no internal time variable; spacetime is the domain in which temporal ordering, geometry, and relativistic description appear; and a photon is a lawfully admissible charge-state relation whose spacetime appearance is a lawful change, not defined by internal time or internal space variables. On this reading, familiar puzzles concerning propagation, retrocausal objections, and endpoint foreknowledge are not solved by adding hidden process, but dissolved by refusing to impose a time-bearing story where the null condition already excludes one. In particular, null proper time, the absence of a rest frame, and the lack of defined rest-frame spatial predicates together exclude any transit-based photon ontology. The present claim is interpretive: it changes the ontological reading of null structure, not the formal machinery of SR, GR, QM, or QFT.
\end{abstract}





\clearpage

\section{Introduction and Scope}
Earlier papers in this series examined the interpretive consequences of well-established relativistic invariants, especially null proper time for massless excitations, the absence of a rest frame for photons, and the refusal of null curves as carrier histories \citep{McKinley2025NullProperTime,McKinley2025NoRestFrame,McKinley2025NullCurves}. They argued that familiar narratives concerning persistence, transit, and temporal ordering are not licensed by relativistic kinematics alone.

The present paper does not add to those results. It compresses them. The aim is to retain only what remains structurally necessary once null proper time is taken seriously without apology.


This paper:
\begin{itemize}
    \item does not modify Special Relativity,
    \item does not modify General Relativity,
    \item does not modify standard quantum formalism,
    \item does not introduce new equations,
    \item does not add new observables in this paper,
    \item does not rely on a photon-carrier ontology.
\end{itemize}

Its contribution is limited to clarification and compression.


\section{TLM Summary}\label{tlm}

The Timeless Light Model, in its present minimal-canon form, makes a narrow claim with broad interpretive consequences. Physics already assigns null interval status to lightlike structure and denies the photon a rest frame. TLM takes those facts literally. A photon is not a persisting object with an internally unfolding history through spacetime. It is a lawfully admissible charge-state relation whose spacetime appearance is a lawful change rather than a temporally or spatially persisting carrier. Terms such as transfer, emission, absorption, propagation, completion, travel, and landing therefore belong to spacetime description, not to the defining photon relation itself. For the photon, internal time and internal space are not defining variables.






\begin{tlmquote}
\textbf{Minimal Core}
\begin{enumerate}[leftmargin=2em]
    \item Null proper time means no internal time for the photon.
    \item No internal time implies no internal space for the photon.
    \item A photon is not a particle in transit, but a lawfully admissible charge-state relation whose spacetime appearance is a lawful change.

\end{enumerate}
\end{tlmquote}




\section{The Minimal Canon}

\begin{definition}[Time-free lawful structure]
Some lawful physical relations are not governed by internal time variables.
\end{definition}

This is the broad structural claim. It does not deny that many physical descriptions use time. It states only that not every lawful physical relation is of that kind.

\begin{definition}[Spacetime]
Spacetime is the domain in which temporal ordering, duration, geometry, interval structure, frame dependence, and other relativistic descriptions are defined.
\end{definition}

Spacetime is therefore the proper domain of process language, sequence language, path language, and observer-side descriptions such as emission, absorption, transit time, measurement record, geometric separation, and displayed pattern.

\begin{definition}[Photon: no internal time or space variables]
For the photon, the ordinary internal spacetime variables needed for a timed or spatially traversed story---including duration, sequence, path, distance, and intermediate location---are not part of the defining variable set \citep{McKinley2025NullProperTime}.
\end{definition}

This claim is stronger than merely saying that the relevant quantities equal zero. It marks the refusal to redescribe the photon in process terms once internal time has already been withheld.

\begin{proposition}[For the photon, no internal time implies no internal space]
For the photon, the absence of an internal time variable excludes an internal sequence of traversed spatial locations. Accordingly, path, covered distance, and intermediate location are not predicates of the photon.
\end{proposition}

This is not an added mechanism. It is the direct consequence of taking the null condition literally. If no internal temporal sequence exists, then no internal spatial traversal can be defined either.




\begin{definition}[Photon: short form]
A photon is not a particle in transit, but a lawful change as it appears in spacetime.
\end{definition}


\begin{definition}[Photon: long form]
A photon is a lawfully admissible charge-state relation whose spacetime appearance is a lawful change, not defined by internal time or internal space variables and not a temporally or spatially persisting carrier.
\end{definition}

\begin{remark}
Here ``lawfully admissible'' means consistent with the physical constraint structure already present in standard theory, including conservation laws, coupling structure, boundary conditions, and selection rules. The present claim is interpretive, not a replacement formalism: it concerns what null structure licenses ontologically, not whether standard relativistic or quantum calculations remain valid.
\end{remark}



\begin{remark}
What appears in spacetime as a photon is always a lawful, admissible change. There is no free or unlawful photon mode in the model.
\end{remark}

\begin{remark}
The term ``charge-state relation'' is deliberately non-process language. It names a lawful connection underlying spacetime-labeled emission and absorption without implying a photon path, internal duration, traveled distance, or propagating carrier.
\end{remark}









\section{Immediate Consequences of the Minimal Canon}

\begin{proposition}[No unlawful mode]
The photon has no unlawful mode. If it appears in spacetime at all, it appears lawfully, as the lawfully admissible realization of a charge-state relation. There is no free or unlawful photon mode in the model.
\end{proposition}




Questions presupposing a pre-lawful or unconstrained photon are category errors, because they assume an entity not licensed by the model's admissibility constraints.

\begin{proposition}[Localization of sequence]
Temporal ordering exists only in spacetime description.
\end{proposition}

Since order and duration are defined in spacetime, any notion of before, after, waiting, sequence, or transit belongs there. Such notions do not define the photon, because internal time is not part of the photon variable set.

\begin{proposition}[Localization of path]
Spatial path, covered distance, and intermediate location exist only in spacetime description.
\end{proposition}

Since path and geometric separation are defined in spacetime, they do not automatically describe an internal photon history. Such notions belong to observer-side geometry, not to the defining photon relation.

\begin{proposition}[No internal photon history]
The photon does not admit a temporally lived or spatially traversed intermediate history.
\end{proposition}

\begin{remark}\label{ns}
A photon possesses null proper time ($d\tau = 0$) and lacks a rest frame. In relativistic mechanics, the spatial predicates ordinarily used to define an object's spatial status---proper size, proper volume, and rest-location---are defined only relative to a rest state. Because the photon has no rest frame, these predicates are not defined for it in the usual sense.

Accordingly, the photon is not a spatial object in the ordinary physical sense. What is not spatially defined in that sense cannot occupy a sequence of intermediate positions. Without a sequence of positions, there is no trajectory; without a trajectory, there is no trip. Thus, the photon does not travel through space. What appears in spacetime is a lawful change between endpoints, not a persisting traveler between them.

\textbf{In summary:} null proper time $\rightarrow$ no rest frame $\rightarrow$ no defined rest-frame spatial predicates $\rightarrow$ no trajectory $\rightarrow$ no transit.

In compressed form: null proper time $\rightarrow$ no rest frame; no rest frame $\rightarrow$ no defined rest-frame spatial predicates; no such predicates $\rightarrow$ no traversed path; no traversed path $\rightarrow$ no intermediate history.
\end{remark}



\begin{remark}
The traveler picture survives only by treating the photon as though ordinary object-predicates continued to apply despite the absence of both proper time and rest-frame status.
\end{remark}

\begin{proposition}[No carrier ontology]
The photon is not a persisting carrier transporting stored information or energy through spacetime in a rest-frame-like sense.
\end{proposition}

This does not deny spacetime bookkeeping at endpoints. It denies that such bookkeeping requires a little object with an internal timed journey through intermediate places.

\begin{proposition}[No learning in transit]
There is no photon process of discovering, revising, or choosing a destination in transit.
\end{proposition}

Realization is constrained by lawful qualification, not by awareness, route-finding, or mid-course adjustment. Nothing in the photon description supports a timed or spatially traversing intermediate selection process.

\begin{proposition}[Category error of transit questions]
Questions framed in terms of photon transit, route, covered distance, intermediate location, landing choice, endpoint foreknowledge, or which endpoint comes ``first'' at bedrock are category errors.
\end{proposition}

Such questions presuppose a temporally ordered and spatially traversing intermediate object. In TLM, the photon is not defined as such an object. Accordingly, questions such as ``How does it know where to go?'', ``Where is it in between?'', ``How does it cross the distance?'', and ``Which is first, the downtick or the uptick?'' misapply spacetime predicates to what is not, at bedrock, a spacetime traveler.

\begin{proposition}[Retrocausal or absorber-style objections are misframed]
Objections framed in terms of backwards-in-time influence, in-flight updating, route selection, or spatial traversal are not fundamental to the photon description.
\end{proposition}

Such objections presuppose a temporally ordered or spatially traversing intermediate history. If no such history belongs to the photon, then the contradiction is introduced by the description rather than by the physics.

\begin{proposition}[No-mid-flight-energy reading]
The model does not require usable energy to be stored in a temporally or spatially persisting photon-object between endpoints.
\end{proposition}

Energy accounting remains a spacetime matter. The denial concerns the ontology of an intermediate carrier, not the validity of conservation law.

\section{Relation to Relativistic Structure}

\subsection{Null Proper Time}

The present statement presupposes the standard relativistic result that lightlike structure satisfies \(d\tau = 0\) \citep{Einstein1905,Wald1984}. TLM does not alter that result. It insists that this fact be read ontologically rather than treated as a decorative edge fact.

This paper does not claim that $d\tau = 0$ is new physics; it claims that the usual practice of treating that null fact as narratively disposable is interpretively unstable.


\subsection{No Rest Frame}

The absence of a photon rest frame withholds the ordinary kinematic resources needed for identity-through-time, persistence, and temporally internalized propagation. The revised photon law is designed to match that constraint rather than narrate around it.

Nothing in the present claim denies the standard propagator formalism for massless fields; the claim concerns what that formalism licenses ontologically, not whether the formalism remains valid.

\subsection{No Internal Spatial Traversal}

As noted in \cref{ns}, if no internal time variable exists for the photon, then no internal sequenced traversal is available either. Path, covered distance, and intermediate occupancy therefore belong only to spacetime description. On this reading, ``travel'' is an appearance-term, not a bedrock ontological commitment.




\subsection{Status of \(c\)}

On this reading, \(c\) belongs to spacetime description. It is part of the limiting causal structure of spacetime as described by relativity.




\section{Wavefunction and Lawful Qualification}

This paper does not replace standard quantum formalism. It treats the wavefunction as part of the lawful structure governing which photon-like changes appear in spacetime. In the present reading, the wavefunction is not a spacetime substance, not the wrapper of a tiny traveling bead, and not a description of where the photon is at intermediate times. It belongs instead to the lawful qualification of observable spacetime outcomes.

Here ``lawful qualification'' means that photon appearance in spacetime is not arbitrary. It is constrained by the admissibility structure already present in physics: quantum amplitudes, conservation principles, coupling structure, boundary conditions, symmetry-based selection rules, and other conditions required for a physically realizable outcome. What appears in spacetime as a photon is therefore not a persisting carrier moving between endpoints, but a lawfully qualified change.

The wavefunction does not supply an internal photon journey. It governs the admissible outcome structure under which observable photon appearance occurs.

\begin{remark}
This use of wavefunction language is intentionally conservative. It introduces no new quantum law and no additional ontology beyond the claim that photon appearance in spacetime is lawfully qualified rather than arbitrary.
\end{remark}

\begin{remark}
The null fact is already retained in the equations, but it is often abandoned in the accompanying narrative. TLM refuses that abandonment. Electromagnetic propagation is not interpreted as a substance or ``wave-thing'' traveling through spacetime. It is interpreted instead as a lawful spacetime pattern of admissible appearance, not as the history of a persisting photon-object between endpoints.
\end{remark}







\begin{figure}[htbp]
\centering
\begin{tikzpicture}[scale=1.15]

% Overall label
\node[align=center,font=\small\bfseries] at (3.0,7.5)
{\large Photon in TLM};

% Governing statement
\node[align=center] at (3.0,7.0)
{\small Null spacetime relation, not a photon transit history};


    % Axes
    \draw[->] (0,0) -- (0,4.4) node[above] {$t$};
    \draw[->] (0,0) -- (5.6,0) node[right] {$x$};

    % Endpoints
    \fill (1.0,0.9) circle (1.5pt) node[below left] {$E$};
    \fill (4.4,3.6) circle (1.5pt) node[above right] {$A$};

    % Null relation line
    \draw[thick,dashed] (1.0,0.9) -- (4.4,3.6);
    \node at (2.9,2.45) [above=2pt] {$ds^{2}=0$};

    % Endpoint drops
    \draw[densely dotted] (1.0,0.9) -- (1.0,0);
    \draw[densely dotted] (4.4,3.6) -- (4.4,0);

    % Brace / annotation for the line
    \draw[decorate,decoration={brace,amplitude=4pt}]
        (1.15,3.95) -- (4.25,3.95);
    \node[align=center] at (2.7,4.28) {\scriptsize lightlike relation only};


    % Main ontological statement
    \node[draw, rounded corners, align=center, fill=gray!8, inner sep=6pt]
        at (2.7,1.7)
        {\scriptsize not an occupied history\\[-1pt]\scriptsize not a persisting traveler};

    \node[align=center] at (3,5.5)
    {\small Photon:\\ \small no internal time- or space-bearing history};

    % Bottom annotation
    \node[align=center] at (3,-1.1)
        {\small Spacetime description:\\ \small endpoint labels and null relation};

\end{tikzpicture}
\caption{The dashed segment records that emission and absorption are null-related in spacetime description, \(ds^{2}=0\), but it is not to be read as an occupied intermediate history of a persisting photon. Here \(ds^{2}=0\) denotes a null spacetime interval: the emission and absorption events are lightlike-related in spacetime geometry, with zero proper time along the null relation.}




\label{fig:nullcontrast}
\end{figure}






\section{Compatibility and Conservativeness}

The revised bedrock is fully compatible with:
\begin{itemize}
    \item Special Relativity,
    \item General Relativity,
    \item standard operational quantum formalisms.
\end{itemize}

No equation is altered in this paper. The contribution is interpretive restriction, not replacement of existing predictive machinery.

\section{Minimality}

We briefly consider whether the canon can be reduced further.

If one removes time-free lawful structure, the model collapses back into ordinary process-language and loses the distinction required by the null case. If one removes spacetime as the domain of ordered description, one loses the domain in which ordinary physical records and relativistic statements are made. If one removes lawful qualification, the model no longer explains why not every imaginable outcome is physically realized. If one removes the photon law, the paper loses the specific ontological consequence that motivates the revision. If one removes the claim that, for the photon, internal time and internal space are not defining variables, the null condition is easily softened back into a disguised travel-story.

Accordingly, the canon is minimal under the present constraints:
\begin{enumerate}
    \item some lawful physical relations are not governed by internal time variables,
    \item spacetime contains temporal, geometric, and observer-side description,
    \item for the photon, internal time and internal space are not defining variables,
    \item the photon is not a particle in transit, but a lawful change as it appears in spacetime,
    \item in fuller form, the photon is a lawfully admissible charge-state relation whose spacetime appearance is a lawful change.

\end{enumerate}

\section{Discussion}

The point of TLM is not that physics lacked the key fact. The point is that physics has long retained the null condition for light in its equations while often continuing to speak as though the photon possessed a process-like internal story in spacetime. The present paper refuses that extra story. Once that refusal is made explicit, several familiar interpretive pressures weaken at once. Questions framed in terms of a traveling object, a lived middle, a route-like temporal sequence, or a covered spatial gap no longer strike bedrock.

This does not establish every larger TLM claim. It does, however, sharpen the foundation. The null case is no longer treated as a decorative exception. It becomes the controlling fact.

What appears in spacetime as a photon is never a free or unconstrained event. It is a lawful change, appearing only in a lawfully admissible form. The relevant lawfulness is broader than wavefunction formalism alone. It includes the full constraint structure of physical admissibility: conservation principles, interaction coupling, boundary conditions, symmetry-based selection rules, and final-state availability. Puzzles that assume a pre-lawful, freely improvising, or internally traveling photon are thereby dissolved, because they presuppose a mode of being not licensed by the model.

Null means null: not almost no time, not effectively no time, and not a hidden travel story preserved under softer language.

In TLM, the photon is not a free agent in spacetime, but a lawful change observable there. It has no unlawful mode and no persistence-based middle. Consequently, transport-based puzzles are misframed, because they presuppose a traveler where the model permits only lawful spacetime appearance.

The present paper does not add a further interpretive layer. It records the minimal remainder once null proper time is taken literally and persistence-based photon language is refused.







\section{Conclusion}

The Timeless Light Model admits a simpler bedrock statement than earlier formulations required. Some lawful physical relations are not governed by internal time variables. Spacetime is the domain in which temporal order, geometry, and relativistic description appear. For the photon, no internal time implies no internal space. A photon is not a particle in transit, but a lawful change as it appears in spacetime. In fuller form, the photon is a lawfully admissible charge-state relation whose spacetime appearance is a lawful change. On this reading, the photon is not a temporally or spatially persisting carrier and does not possess a lived intermediate history. The force of TLM lies in taking seriously a fact physics has lived with for over a century: null means null. What appears as a photon in spacetime appears only lawfully.



\section*{Glossary (TLM)}

\begin{description}

    \item[Charge-State Relation] The lawful relation underlying what spacetime description renders process-wise as emission, absorption, or transfer.
    \item[Lawfully Admissible]\label{lad} Here ``lawfully admissible'' means consistent with the physical constraint structure already present in standard theory, including conservation, coupling, boundary, and selection-rule conditions.

    \item[Photon] A photon is a lawfully admissible charge-state relation whose spacetime appearance is a lawful change, not a particle in transit.

    \item[Spacetime] The domain in which temporal ordering, duration, geometry, interval structure, and frame-dependent relativistic description appear.
    \item[Null Proper Time] The standard relativistic condition for lightlike structure, \(d\tau = 0\); in TLM, this is treated as an ontological constraint excluding an internally timed photon history.

    \item[Category Error] A question that presupposes predicates not licensed by the defining ontology. In the present context, questions about photon transit, path, or intermediate location are category errors.
\end{description}

\begin{thebibliography}{9}

\bibitem{McKinley2025NullProperTime}
McKinley, J. C. W.
\newblock \emph{Taking Null Proper Time Seriously: An Interpretive Clarification of Null Proper Time}.
\newblock Zenodo, 2025.
\newblock doi:\href{https://doi.org/10.5281/zenodo.18004632}{10.5281/zenodo.18004632}.

\bibitem{McKinley2025NullCurves}
McKinley, J. C. W.
\newblock \emph{Null Curves Without Carriers: Resolving an Ontological Tension in Relativistic Geometry}.
\newblock Zenodo, 2025.
\newblock doi:\href{https://doi.org/10.5281/zenodo.18028886}{10.5281/zenodo.18028886}.

\bibitem{McKinley2025NoRestFrame}
McKinley, J. C. W.
\newblock \emph{No Rest Frame, No Persistence: A Kinematic Constraint on Photon Interpretation}.
\newblock Zenodo, 2025.
\newblock doi:\href{https://doi.org/10.5281/zenodo.18005884}{10.5281/zenodo.18005884}.

\bibitem{Einstein1905}
Einstein, A.
\newblock Zur Elektrodynamik bewegter K\"orper.
\newblock \emph{Annalen der Physik} \textbf{17} (1905), 891--921.
\newblock doi:\href{https://doi.org/10.1002/andp.19053221004}{10.1002/andp.19053221004}.

\bibitem{Wald1984}
Wald, R. M.
\newblock \emph{General Relativity}.
\newblock University of Chicago Press, 1984.

\end{thebibliography}

\end{document}
```

</details>

---

### [2025] Null Curves Without Carriers: Resolving an Ontological Tension in Relativistic Geometry
*   **DOI:** [10.5281/zenodo.18028886](https://doi.org/10.5281/zenodo.18028886)
*   **Date:** 22 December 2025

<details markdown="1">
<summary><b>Click to view Raw LaTeX Source</b></summary>

```latex
\documentclass[12pt,onecolumn,a4paper]{article}

% ---------- Encoding, fonts, typography ----------
\usepackage[utf8]{inputenc}
\usepackage[T1]{fontenc}
\usepackage{lmodern}
\usepackage{microtype}

% ---------- Page layout ----------
\usepackage[margin=1in]{geometry}

% ---------- Math & theorems ----------
\usepackage{amsmath,amssymb,amsthm,bm}


% ---------- Graphics / TikZ / 3D ----------
\usepackage{graphicx}

\usepackage{tikz}
\usetikzlibrary{arrows.meta,positioning,calc,shapes.geometric,fit,backgrounds,shadows}
\usepackage{pgfplots}
\pgfplotsset{compat=1.18}
\usepackage{tikz-3dplot}
% Default 3D viewing angles (override per-figure if needed)
\tdplotsetmaincoords{70}{110}

% ---------- Tables & lists ----------
\usepackage{booktabs,longtable,tabularx,array}
\newcolumntype{L}[1]{>{\raggedright\arraybackslash}p{#1}}
\usepackage{enumitem}

% ---------- Boxes ----------
\usepackage[most]{tcolorbox}
\tcbset{colback=gray!5,colframe=black,boxrule=0.6pt,arc=2mm}
\newtcolorbox{axiombox}[1]{breakable,title={#1},fonttitle=\bfseries}

% ---------- Rotating ----------
\usepackage{rotating}

% ---------- Bibliography & links (load near the end) ----------
\usepackage{natbib}
\usepackage{orcidlink}
\usepackage{hyperref}
\hypersetup{colorlinks=true,linkcolor=blue,urlcolor=blue,citecolor=blue}
\usepackage{cleveref} % keep after hyperref
\usepackage{fancyhdr}
\setlength{\headheight}{14pt}
\pagestyle{fancy}
\fancyhf{}
\lhead{Null Curves Without Carriers}
\rhead{John C.\ W.\ McKinley}
\cfoot{\thepage}

\crefname{proposition}{Proposition}{Propositions}
\Crefname{proposition}{Proposition}{Propositions}
\crefname{definition}{Definition}{Definitions}
\Crefname{definition}{Definition}{Definitions}

\usepackage{mathtools}


\newtheorem{proposition}{Proposition}[section]
\newtheorem{definition}[proposition]{Definition}
\newtheorem{lemma}[proposition]{Lemma}
\newtheorem{remark}[proposition]{Remark}
\newtheorem{theorem}[proposition]{Theorem}
\newtheorem{postulate}[proposition]{Postulate}



\newcommand{\MassDelayLaw}{T \cdot m = \hbar / c^{2}}
\newcommand{\CausalSpeedLaw}{T \cdot C_{s} = 1}

\title{\textbf{Null Curves Without Carriers:\\
Resolving an Ontological Tension in Relativistic Geometry}}

\author{John C. W. McKinley\orcidlink{0009-0005-7097-5035}\\Independent Researcher}
\date{December 22, 2025}


\begin{document}
\maketitle

\begingroup
  \footnotetext[0]{This version published at
  \href{https://doi.org/10.5281/zenodo.18028886}{https://doi.org/10.5281/zenodo.18028886}.}
\endgroup



\begin{abstract}
Null curves occupy a central role in relativistic geometry: they generate light-cone
structure, encode causal accessibility, and govern the geometric-optics limit of
wave propagation. At the same time, null curves admit no rest frame and carry zero
proper time. This means that the familiar massive-particle persistence template
(rest frame plus proper time as an intrinsic succession parameter) does not extend
unchanged to the null case. A common pedagogical narrative often speaks as
if lightlike propagation were the history of a persisting carrier ``moving along''
the curve. The present paper isolates this interpretive slippage and argues for a
more literal reading: null curves should be understood primarily as geometric
constraint structures relating spacetime endpoints, not as ontic histories of
in-flight objects. No equations are modified and no predictions are altered; the
proposal is a discipline of interpretation that preserves the full causal and
geometric content of relativity while avoiding unforced surplus ontology. The
Timeless Light Model (TLM) is cited as one internally consistent ontology that
implements this endpoint-based reading.
\end{abstract}



\begin{remark}[Terminology and scope]
In standard mathematical usage, a ``worldline'' may denote any curve representing
the locus of events associated with an object or idealization. In this paper,
however, the term \emph{worldline as ontic history} is used more narrowly to denote
the history of a persisting physical bearer whose successive states are ordered by
an internal parameter associated with that bearer (e.g.\ proper time in the massive
case). The present argument targets the transfer of this \emph{rest-frame persistence
template} to null curves, not the mathematical legitimacy of null geodesics as curves
or as solutions to variational principles.
\end{remark}


\section{Introduction}

Null curves occupy a foundational position in relativistic physics. They define the
boundaries of light cones, determine causal accessibility, and encode how curvature
redirects lightlike influence. Standard presentations describe them as the paths of
massless excitations such as photons \cite{Rindler,MTW}.

At the same time, relativity assigns null curves zero proper time and no rest frame.
These invariants preclude duration, localization, and internal evolution along the
curve. The combination produces a tension that is usually passed over without
comment: null curves are treated as worldlines, yet the usual massive rest-frame persistence
template (rest frame + proper time as internal succession parameter) is unavailable
in the null case.


This paper argues that the tension is not merely pedagogical but categorical.
Worldlines, in the ordinary relativistic sense, are histories of persisting
entities. Null curves, by contrast, lack the structural features that make such a
reading available. Treating null curves as worldlines therefore imports a massive-particle
template into a domain where the invariants do not support it.

The present paper is the third in a structured sequence. Paper~1 develops the
null-proper-time motivation for a literal (non-in-flight) reading and is currently
in final preparation \cite{TakingNullProperTime}. Paper~2A establishes the negative
kinematic result that massless excitations admit no rest frame and therefore do not
support the ordinary rest-frame persistence template \cite{NoRestFrameNoPersistence}.
Paper~2B develops a minimal constructive interpretation consistent with that
constraint \cite{NoRestFrameConstructive}. The aim here is distinct: to clarify what
null curves themselves represent once the rest-frame template has been removed.



Rather than alleging any defect in the formalism, the target is a specific
interpretive habit: treating null curves as \emph{particle worldlines} in the same
sense as timelike worldlines. A more literal reading treats null curves as
indispensable geometric structures—causal boundaries and, in appropriate limits,
characteristics of wave propagation—without committing to persisting carriers that
occupy points along them.

\begin{remark}[On the sense of ``tension'']
The term ``tension'' is used here in a strictly interpretive and pedagogical sense.
No contradiction or defect in the relativistic formalism is alleged. Rather, the
claim is that a common informal narrative---treating null curves as worldlines of
persisting carriers in the same sense as timelike worldlines---imports structural
assumptions that the relativistic invariants themselves do not supply. The present
argument concerns the discipline of interpretation, not the consistency or empirical
adequacy of relativity.
\end{remark}




\section{Scope and Intent}

This work proposes no new dynamics and introduces no empirical claims. All standard relativistic and quantum formalisms are left intact. The aim is strictly interpretive: to clarify what null curves represent given the invariants already present in relativity.

Such clarification matters because ontology constrains theory-building. Any account
of spacetime emergence, quantum gravity, or causal structure that assigns dynamical
degrees of freedom along null directions must still confront the absence of
proper-time evolution there. The present paper does not propose a solution to such
programs, but isolates a constraint they must respect.

In particular, approaches that assign local dynamical degrees of freedom along null
directions must still account for the special status of null generators in the
geometric foundations of relativity \cite{GerochJang1975,Weatherall2011}.

\begin{remark}[Domain discipline]
The present argument operates at the level of relativistic kinematics and geometric
interpretation. In classical relativity, null geodesics function as structural
elements defining causal relations and optical limits. In quantum field theory,
``particle'' language is approximate, with detector responses and correlators
providing the primary observables. The claim advanced here is not that these
frameworks are inconsistent, but that literal particle-persistence narratives along
null curves are not forced by any of them.
\end{remark}



\begin{definition}[Rest-frame persistence template]
By the \emph{rest-frame persistence template} we mean the interpretive scheme in
which a physical entity is taken to persist by occupying successive spacetime
locations ordered by an internal parameter associated with that entity, typically
proper time defined in a rest frame.
\end{definition}

\begin{definition}[Internal evolution (rest-frame sense)]
By ``internal evolution'' we mean evolution tracked by an intrinsic time parameter
associated with the bearer, as provided by proper time in a rest frame for massive
systems. This does not refer to coordinate-time evolution of fields or correlators.
\end{definition}


\begin{proposition}[Limits of the persistence template for null cases]
For massless excitations, no rest frame exists and no proper-time parameter is
available to order an internal succession of states. Consequently, the
rest-frame persistence template applicable to massive systems does not extend
unchanged to null curves. While null curves remain geometrically indispensable,
interpreting them as ontic histories of persisting carriers requires additional
assumptions not fixed by relativistic invariants.
\end{proposition}

\begin{remark}
This proposition is classificatory rather than dynamical. It does not deny the use
of affine parameters, null geodesics, or field evolution in coordinate time. It
states only that the specific persistence narrative grounded in rest frames and
proper time lacks support in the massless case.
\end{remark}




\section{The Standard Interpretation and Its Failure}

Relativistic practice implicitly combines two ideas:
\begin{itemize}
\item A null curve as a geometric subset of spacetime.
\item A massless particle or excitation that ``travels'' along that curve.
\end{itemize}

For timelike curves, this pairing is coherent. Massive particles possess proper time, rest frames, and internal evolution, allowing them to occupy successive spacetime locations meaningfully.

For null curves, the massive rest-frame persistence template is unavailable. With no
rest frame and no proper-time parameter to serve as an intrinsic succession
parameter, the usual ``occupancy'' narrative becomes underdetermined by the
invariants: one may continue to use null geodesics as mathematical worldlines (e.g.\
affinely parameterized curves), but reading them as ontic histories in the same
sense as timelike worldlines adds interpretive structure not fixed by the theory.


The inconsistency is typically obscured by linguistic shorthand (``light travels along null geodesics'') rather than examined.

The resulting mismatch between geometric definition and particle-based narration
is typically treated as harmless shorthand in pedagogy, rather than as a signal
to reconsider what ontological commitments the formalism actually supports
\cite{Rindler,MTW}.

The point is not that this shorthand leads to incorrect calculations. It does not.
The issue is that the shorthand quietly imports an ontological picture—persistence
along a curve—that the relativistic invariants explicitly undercut. The resulting
mismatch is therefore not a computational error but a category error: treating a
geometric constraint as though it were the history of an entity.

Accordingly, this paper complements rather than duplicates the earlier no-go result:
Paper~2A shows that massless excitations cannot support rest-frame persistence, while
the present argument isolates a further point about the \emph{status of null curves
themselves} \cite{NoRestFrameNoPersistence}.

\subsection{The standard reply and its limits}

A standard response is that massless particles still possess worldlines, understood
as null curves parameterized by an affine parameter, and that the absence of proper
time does not preclude such a description. This reply is formally correct.

The present claim is more modest. An affine parameter supplies a mathematical
ordering along a curve, but it does not ground a notion of persistence analogous to
that provided by proper time in the massive case. In particular, it does not define
an internal clock, rest frame, or state succession intrinsic to the purported
carrier. Treating affine-parameter ordering as sufficient for ontic persistence
therefore reflects an interpretive choice rather than a requirement of the
formalism.

Accordingly, the argument does not deny that null curves may be called worldlines
in a mathematical sense. It denies only that the massive-particle persistence
template licensed by proper time transfers without residue to the null case.




\section{What Null Curves Represent}

In TLM, null curves are not histories but constraints. They relate spacetime endpoints—emission and absorption events—without implying occupancy between them.

The endpoints are ordinary events embedded in timelike frames. The null curve specifies:
\begin{itemize}
\item which spacetime separations are causally admissible,
\item how curvature conditions those relations,
\item how delay is rendered for massive observers.
\end{itemize}

Nothing exists along the curve itself. The curve functions as geometric bookkeeping for causality, not as a trace left by a traveler.

An instructive analogy is a straight line drawn between two points on paper. The line constrains direction and separation but is not an object moving between the points. Likewise, null curves constrain relations without hosting entities.

\section{Why Relativity Still Requires Null Curves}

Removing carriers does not weaken relativity. Null curves remain indispensable for:
\begin{itemize}
\item defining causal domains and horizons,
\item describing gravitational lensing and redirection,
\item establishing limits for clock synchronization and signaling.
\end{itemize}

These roles depend on geometry, not on objects inhabiting null directions. The metric governs relations among events, not the motion of massless things through spacetime.

In quantum field theory, lightlike propagators likewise encode correlations between endpoints rather than literal particle trajectories \cite{FeynmanQED,BrodskyLC}.

In this respect, null curves function analogously to light-cone support in field
theory, constraining correlations without themselves constituting particle
histories \cite{FeynmanQED,BrodskyLC}.

Nothing in general relativity requires null geodesics to be interpreted as
ontic particle histories; their role as generators of causal and optical
structure is fully independent of any carrier-based interpretation.



\subsection{Null geodesics as characteristics in the geometric-optics limit}

For a concise treatment of the geometric-optics limit and the conditions under
which null geodesics approximate wave propagation, see \cite{NYUGR15}.




The claim that null geodesics are not particle histories does \emph{not} deny their
physical role. In the geometric-optics approximation, wave propagation admits a
ray description in which rays follow null geodesics derived from Maxwell's equations
in curved spacetime \cite{NYUGR15}. This establishes why null
geodesics govern lensing and horizon structure without implying that a persisting
particle must occupy intermediate points between endpoints.





\section{Relationship to Absorber and Transactional Programs}

The present thesis is compatible with, and in part anticipated by, approaches
that treat emission--absorption as fundamentally relational rather than mediated
by in-flight carriers. Wheeler--Feynman direct-action electrodynamics removes
independent field degrees of freedom in favor of emitter--absorber interaction
along lightlike intervals \cite{WF1945}. Transactional interpretations likewise
describe quantum processes via emitter--absorber ``handshakes'' \cite{Cramer1986}.

This paper's contribution is narrower than proposing a new formalism: it isolates
a specific interpretive slippage in standard relativistic pedagogy---the
identification of null curves with worldlines of persisting particles---and
argues that a cleaner reading treats null curves as geometric constraint
structures relating endpoints. TLM is then presented as one consistent ontology
implementing that reading.

The present argument does not claim priority over these relational approaches, but
targets a narrower issue: the persistence of worldline language for null curves in
contexts where the invariants explicitly undermine any notion of an evolving
carrier \cite{WF1945,Cramer1986}.




\section{Integration with the Timeless Light Model}



One internally consistent way of implementing the endpoint-based reading of null
curves is provided by the Timeless Light Model (TLM). In that framework, massless
excitations are treated as complete causal correlations between emission and
absorption events, with spacetime geometry constraining how those correlations are
rendered for massive observers.

This resolves wave--particle duality without invoking traversal: interference and correlation arise from boundary-conditioned structure, not from entities propagating through space.

Nothing in the foregoing argument depends on adopting the full Timeless Light Model.
The anti-worldline reading of null curves follows directly from a literal
interpretation of relativistic invariants; Paper~2B is offered as one internally
consistent ontology implementing that reading \cite{NoRestFrameConstructive}.
For the broader null-proper-time motivation that led to the present sequence, see
Paper~1 \cite{TakingNullProperTime}.

\begin{remark}
Nothing in the foregoing argument depends on adopting TLM in particular. The
anti-persistence reading of null curves follows directly from a literal treatment of
relativistic invariants. TLM is offered only as one ontology that implements this
reading without modifying equations or predictions.
\end{remark}


\section{Consequences and Resolutions}

Once the carrier is removed, several long-standing puzzles dissolve:
\begin{itemize}
\item Photon aging never arises; nothing persists to age.
\item Superluminal paradoxes are avoided; relations are authored outside spacetime and rendered with delay.
\item Null directions carry no local degrees of freedom, constraining approaches to spacetime emergence.
\end{itemize}

The gain is conservative: fewer ontological commitments with no loss of predictive power.

These consequences align with existing results on the special role of null
structure in spacetime foundations, while removing an unnecessary particle-level
narrative from lightlike cases \cite{GerochJang1975,Weatherall2011}.

This reading also aligns naturally with light-cone formulations of quantum field
theory, where propagation is encoded through support on lightlike intervals and
boundary-conditioned correlators rather than through literal particle trajectories.
In such formulations, null structure constrains amplitudes without requiring
ontological persistence along null directions \cite{BrodskyLC,FeynmanQED}.

Taken together, the sequence supports a minimal interpretive chain: null proper time
motivates an endpoint-based reading \cite{TakingNullProperTime}, the absence of a rest
frame blocks the massive-persistence template \cite{NoRestFrameNoPersistence}, and null
curves are thereby best treated as geometric constraint structures rather than ontic
histories.



\section{Conclusion}

Null curves need not be read as worldlines of persisting carriers. They are geometric
constraint structures that encode the shape of causality in spacetime. Treating them as such resolves a persistent pedagogical conflation in relativistic interpretation and clarifies the status of lightlike structure once the rest-frame template is unavailable.

Together with the negative kinematic result concerning rest frames and the minimal
endpoint-based interpretation developed elsewhere, this completes a sequence of
clarifications: massless excitations do not persist, null curves do not host
entities, and the geometry of spacetime remains fully intact.

In this sense, the proposal is conservative rather than revisionary. It preserves
all standard relativistic results while recommending greater interpretive discipline
in how null structure is narrated. Null curves remain indispensable geometric
features of spacetime; what is relinquished is only an unforced picture of
persisting carriers occupying them.







\appendix
\section*{Appendix: Schematic Representation}

\begin{figure}[h!]
\centering
\begin{tikzpicture}[scale=1.1]
\draw[->] (0,-2) -- (0,2) node[above] {Time};
\draw[->] (-2,0) -- (2,0) node[right] {Space};

\filldraw (-1.5,-1.5) circle (2pt) node[below left] {Emission};
\filldraw (1.5,1.5) circle (2pt) node[above right] {Absorption};

\draw[thick,dashed] (-1.5,-1.5) -- (1.5,1.5)
node[yshift=-15,midway,right] {Null curve (constraint)};

\node at (0,-2.2) {No carrier along path};
\end{tikzpicture}

\caption{\textbf{Null curve as geometric constraint.}
A null curve connects emission and absorption events while encoding causal
admissibility and geometric structure. The diagram is not intended to represent
a persisting carrier occupying intermediate points along the curve. Rather, the
curve functions as a constraint relating endpoints within spacetime geometry,
consistent with the absence of a rest frame and proper-time evolution for massless
excitations.}
\end{figure}

\begin{thebibliography}{99}

\bibitem{Rindler}
W. Rindler,
\emph{Introduction to Special Relativity},
Oxford University Press (1991).

\bibitem{MTW}
C. W. Misner, K. S. Thorne, and J. A. Wheeler,
\emph{Gravitation},
W. H. Freeman (1973).

\bibitem{FeynmanQED}
R. P. Feynman,
\emph{QED: The Strange Theory of Light and Matter},
Princeton University Press (1985).

\bibitem{BrodskyLC}
S. J. Brodsky, H.-C. Pauli, and S. S. Pinsky,
``Quantum Chromodynamics and Other Field Theories on the Light Cone,''
\emph{Physics Reports} \textbf{301}, 299--486 (1998).
doi:10.1016/S0370-1573(97)00089-6.

\bibitem{PhotonProperTime}
J. C. W. McKinley,
\emph{Photon Proper Time: The Understated Invariant of Special Relativity},
Zenodo (2025).
doi:10.5281/zenodo.17190047.

\bibitem{PhotonsNotHere}
J. C. W. McKinley,
\emph{Photons Not in the Universe},
Zenodo (2025).
doi:10.5281/zenodo.17010029.


\bibitem{WF1945}
J. A. Wheeler and R. P. Feynman,
``Interaction with the Absorber as the Mechanism of Radiation,''
\emph{Rev. Mod. Phys.} \textbf{17}, 157--181 (1945).
doi:10.1103/RevModPhys.17.157.

\bibitem{Cramer1986}
J. G. Cramer,
``The Transactional Interpretation of Quantum Mechanics,''
\emph{Rev. Mod. Phys.} \textbf{58}, 647--687 (1986).
doi:10.1103/RevModPhys.58.647.

\bibitem{GerochJang1975}
R. Geroch and P.-S. Jang,
``Motion of a Body in General Relativity,''
\emph{J. Math. Phys.} \textbf{16}, 65--67 (1975).
doi:10.1063/1.522416.

\bibitem{Weatherall2011}
J. O. Weatherall,
``On the status of the geodesic principle in Newtonian and relativistic physics,''
\emph{Stud. Hist. Phil. Mod. Phys.} \textbf{42}, 276--281 (2011).
doi:10.1016/j.shpsb.2011.03.002.

\bibitem{Dold2025}
D. Dold,
``Deriving the Geodesic Principle,''
\emph{Philosophy of Physics} \textbf{1}, Article 3 (2025).
Available via PhilSci-Archive.

\bibitem{NYUGR15}
Y. Ali-Ha\"{\i}moud,
\emph{General Relativity Lecture 15: Geometric Optics in Curved Spacetime},
NYU lecture notes (2018).




\bibitem{TakingNullProperTime}
J.~C.~W.~McKinley,
\emph{Taking Null Proper Time Seriously: Completing the Relativistic Program},
preprint in preparation (2025).
DOI reserved: \href{https://doi.org/10.5281/zenodo.18004632}{10.5281/zenodo.18004632}.


\bibitem{NoRestFrameNoPersistence}
J.~C.~W.~McKinley,
\emph{No Rest Frame, No Persistence: A Kinematic Constraint on Photon Interpretation (v1.2)},
Zenodo (2025).
\href{https://doi.org/10.5281/zenodo.18005884}{doi:10.5281/zenodo.18005884}.

\bibitem{NoRestFrameConstructive}
J.~C.~W.~McKinley,
\emph{The Timeless Light Model: A Minimal Interpretive Completion of Relativistic Constraints (v2.0)},
Zenodo (2025).
\href{https://doi.org/10.5281/zenodo.18012564}{doi:10.5281/zenodo.18012564}.




\end{thebibliography}

\end{document}
```

</details>

---

### [2025] Taking Null Proper Time Seriously: An Interpretive Clarification of Null Proper Time
*   **DOI:** [10.5281/zenodo.18004632](https://doi.org/10.5281/zenodo.18004632)
*   **Date:** 22 December 2025

<details markdown="1">
<summary><b>Click to view Raw LaTeX Source</b></summary>

```latex
\documentclass[12pt,onecolumn,a4paper]{article}

% ---------- Encoding, fonts, typography ----------
\usepackage[utf8]{inputenc}
\usepackage[T1]{fontenc}
\usepackage{lmodern}
\usepackage{microtype}

% ---------- Page layout ----------
\usepackage[margin=1in]{geometry}
\usepackage{fancyhdr}
\pagestyle{fancy}
\fancyhf{}
\lhead{Rules and Executions}
\rhead{\thepage}

% ---------- Math & theorems ----------
\usepackage{amsmath,amssymb,amsthm,bm}
\newtheorem{definition}{Definition}
\newtheorem{postulate}{Postulate}
\newtheorem{proposition}{Proposition}
\newtheorem{lemma}{Lemma}
\newtheorem{theorem}{Theorem}

% ---------- Graphics / TikZ / 3D ----------
\usepackage{graphicx}

\usepackage{tikz}
\usetikzlibrary{arrows.meta,positioning,calc,shapes.geometric,fit,backgrounds,shadows}
\usepackage{pgfplots}
\pgfplotsset{compat=1.18}
\usepackage{tikz-3dplot}
% Default 3D viewing angles (override per-figure if needed)
\tdplotsetmaincoords{70}{110}

% ---------- Tables & lists ----------
\usepackage{booktabs,longtable,tabularx,array}
\newcolumntype{L}[1]{>{\raggedright\arraybackslash}p{#1}}
\usepackage{enumitem}

% ---------- Boxes ----------
\usepackage[most]{tcolorbox}
\tcbset{colback=gray!5,colframe=black,boxrule=0.6pt,arc=2mm}
\newtcolorbox{axiombox}[1]{breakable,title={#1},fonttitle=\bfseries}

% ---------- Rotating ----------
\usepackage{rotating}

% ---------- Bibliography & links (load near the end) ----------
\usepackage{natbib}
\usepackage{orcidlink}
\usepackage{hyperref}
\hypersetup{colorlinks=true,linkcolor=blue,urlcolor=blue,citecolor=blue}
\usepackage{cleveref} % keep after hyperref






\pagestyle{fancy}
\fancyhf{}
\rhead{John C. W. McKinley}
\lhead{Taking Null Proper Time Seriously}
\cfoot{\thepage}


\newcommand{\MassDelayLaw}{T \cdot m = \hbar / c^{2}}
\newcommand{\CausalSpeedLaw}{T \cdot C_{s} = 1}

\title{\textbf{Taking Null Proper Time Seriously:\\
An Interpretive Clarification of Null Proper Time}}

\author{John C. W. McKinley\orcidlink{0009-0005-7097-5035}\\Independent Researcher}
\date{December 22, 2025}


\begin{document}
\maketitle
\begingroup
  \footnotetext[0]{This version published at
  \href{https://doi.org/10.5281/zenodo.18004632}{https://doi.org/10.5281/zenodo.18004632}.}
\endgroup


\begin{abstract}
Special and General Relativity assign zero proper time to null paths, yet modern physical
discourse continues to treat photons as persisting entities within spacetime.
This paper argues that this tension is conceptual rather than mathematical.
This paper establishes the invariant motivation for such a reading but does not
attempt to supply a complete kinematic or interpretive framework.
Subsequent papers develop the consequences of null proper time in stages:
first as a negative kinematic constraint (absence of a rest frame),
then as a disciplined endpoint-based interpretation,
and finally as a clarification of the ontological status of null curves themselves.



\end{abstract}

\section{Introduction}

Relativity contains a striking statement that is rarely taken at face value:
massless excitations accrue zero proper time.
This result is universally accepted at the formal level, yet its ontological
implications are routinely softened by pedagogical language that speaks of photons
``traveling'' or ``existing between'' emission and absorption.

The assignment of zero proper time to null curves and the absence of a rest frame
for massless excitations are standard results in relativity and are treated as such
in pedagogical and foundational texts \cite{Rindler,MTW}.

Related discussions emphasizing the special status of lightlike propagation
and the absence of a rest-frame description for photons also appear in quantum
field theoretic contexts, including Feynman's operational treatment of photons
and light-cone formulations of relativistic dynamics \cite{FeynmanQED,BrodskyLC}.

Scope and Intent.—This paper does not propose a new dynamical theory, modify
quantum field theory, or replace existing relativistic formalisms.
Its aim is strictly ontological: to clarify what is—and is not—being committed
to when null proper time is assigned in relativity.
Such clarification constrains interpretation and theory-building without
introducing new equations or empirical claims.


This paper argues that such language represents a deferred conceptual step.
Just as Einstein accepted the literal consequences of Lorentz's equations
and removed the ether, the Timeless Light Model (TLM) accepts the literal
consequence of null proper time and removes the in--flight photon.
The aim is not revision but completion.

\paragraph{Relation to companion papers.}
This paper is the first in a structured sequence.
Its role is to take the relativistic assignment of null proper time at face value
and to argue that this invariant motivates interpretive restraint.
A companion paper establishes the negative kinematic result that massless
excitations admit no rest frame and therefore do not support the standard
persistence template.
A subsequent paper develops a minimal endpoint-focused interpretation
consistent with that constraint, and a further paper clarifies the status of null curves
once carrier-based readings are removed.
The present work should be read as motivational rather than exhaustive.

The kinematic, interpretive, and geometric developments referred to here
are presented in detail in companion papers \cite{NoRestFrame,TLMMinimal,NullCurves}.


\paragraph{On scope and contribution.}
This work is not offered as a source of new equations, derivations, or empirical predictions.
Its contribution is classificatory and constraint-based.
Relativistic kinematics already enforces that null paths admit no proper-time evolution and no rest frame.
What is underdetermined is how informal particle language should be interpreted once these facts are taken seriously.
The present paper makes one narrow contribution: it isolates a common category error—the importation of a massive-particle persistence template into null propagation—and shows that this import is not licensed by the invariants of the theory.
This is not a proposal of new physics but a restriction on permissible interpretation.



This work does not propose new empirical deviations from relativistic or quantum
predictions. Its contribution is conceptual: resolving a persistent ontological
inconsistency between the formal assignment of null proper time and the continued
use of in-flight particle narratives. Such clarification is not extraneous to physics;
it determines what structures are taken as physically real versus representational.


\section{Lorentz: Structure Without Ontology}

Lorentz introduced transformations that preserved the form of Maxwell's equations
under changes of inertial frame.
These transformations already singled out light as structurally unique.
Nevertheless, Lorentz retained a background ether and treated time distortions
as compensatory effects rather than ontological features.

Crucially, Lorentz did not ask what the equations implied about light's own
temporal status.
The formal structure existed, but its consequences were not pursued.

\section{Einstein: Taking the Equations Literally}

Einstein's 1905 move was not to invent new mathematics, but to accept the
existing equations at face value.
By discarding the ether and embracing the relativity of simultaneity,
Einstein allowed the formalism to dictate ontology.

This methodological step is central.
Einstein did not add machinery; he removed an unnecessary story.
The success of Special Relativity rests as much on this subtraction
as on any equation.

Einstein’s interpretive move was grounded in the same formal invariants
already present in the theory \cite{Einstein1905,Einstein1916}.


\section{The Modern Inconsistency}

Modern physics now occupies a position structurally analogous to the
pre--Einsteinian era.
It accepts the invariant statement that null paths have zero proper time,
yet continues to speak as if photons persist as entities within spacetime.

This produces a quiet inconsistency:
\begin{itemize}
\item Proper time defines physical persistence.
\item Null paths have no proper time.
\item Photons are nevertheless described as persisting objects.
\end{itemize}

The tension is not mathematical. It is narrative.

The removal of in-flight photon ontology does not deny interference phenomena,
cosmological correlations, or quantum amplitudes. These remain fully accounted
for by boundary-conditioned field correlations and endpoint constraints.
What is removed is the unnecessary assumption that a massless excitation
must persist as a localized entity between emission and absorption in order
for such correlations to exist.


\section{The Deferred Step}

If proper time measures physical duration, then null proper time implies
no internal duration.
If there is no internal duration, there can be no internal evolution.
What remains, absent further structure, is not a traveler but at most a relation between endpoints.

This conclusion follows directly from the formalism.
It requires no additional postulates.
The reluctance to adopt it is historical and pedagogical, not physical.

Whether and how this relation should be given an explicit ontological reading
is addressed in subsequent work; the present paper confines itself to
motivating the restriction.



% ---------- DROP-IN FOR LOGICAL 1 ----------
% Insert this immediately after \section{The Deferred Step}
% and before \subsection{Zero vs. Domain Non-Membership}

\subsection{Endpoint Probability Without Intermediate Dynamics}

A natural objection to the preceding argument is that quantum mechanics still assigns
a nontrivial probability distribution to where a photon is absorbed, often represented
by a wavefunction amplitude. This can tempt the reader to reintroduce an illicit picture:
a persisting ``thing'' that travels in between, but whose landing point is merely unknown.

Taken literally, null proper time forbids that picture. If a null excitation has no
internal duration, then there is no internal time-parameterized evolution to underwrite
a story of intermediate spacetime ``behavior.'' What remains is not an evolving
trajectory-object, but a boundary-defined correlation between emission and absorption
events.

On this reading, quantum probability is not a probability distribution over hidden
spacetime histories of a persisting in-flight entity. Rather, it is a weighting over
admissible absorber outcomes subject to the interaction structure and boundary
conditions of the experimental arrangement. The wavefunction is therefore not a
literal description of ``where the photon is'' at intermediate times; it is a calculational
object whose role is to assign relative likelihoods to endpoint events.

This matches the operational content of relativistic quantum field theory, where
photon language is introduced via asymptotic states and scattering, and propagators
encode correlations between events rather than worldlines of persisting classical objects.
The formalism computes amplitudes for emission--absorption outcomes, not a sequence
of internal stages occurring along a null path. Once the null proper-time invariant is
taken at face value, this should be expected rather than mysterious.

Accordingly, the ``not a little bullet'' warning is not merely pedagogical. It is the
direct interpretive consequence of the same invariant already emphasized here:
a null excitation cannot be coherently treated as a localized object that persists through
spacetime between its endpoints. Quantum mechanics does not force us to abandon
this conclusion; it functions naturally once intermediate persistence is not presumed.


\subsection{Zero vs.\ Domain Non-Membership}

In relativity, null paths are assigned zero proper time.
This statement is formally correct but ontologically ambiguous.
A value of zero may represent either a vanishing quantity within a domain
or the absence of domain membership altogether.

One possible interpretation, developed in later work and implemented within
the Timeless Light Model, treats null proper time as signaling domain non-membership, rather than
a vanishing spacetime duration.

A massless excitation does not experience a limiting duration within spacetime;
rather, it is \emph{not representable as an internally ordered process within}
the spacetime domain.
The assignment $\tau = 0$ therefore functions as a marker of domain non-membership,
not as a physical duration.

We denote this domain-external status as $Z_{U}$.
The symbol $Z_{U}$ does not represent a numerical value or limiting process,
but a categorical distinction:
processes associated with $Z_{U}$ are not temporally ordered and cannot be
represented as internal spacetime dynamics.

Interpreting $\tau = 0$ as signaling domain non-membership is not a semantic
redefinition of proper time, but a standard structural move:
\emph{a quantity that fails to parametrize internal evolution ceases to function
as a coordinate within that domain.}
The notation $Z_{U}$ serves only to prevent conflation of this case with
vanishing-but-defined spacetime durations.

The present paper does not require adoption of this notation; it is introduced
here only to flag a distinction that will be developed more carefully elsewhere.





\section{The Timeless Light Model}

The Timeless Light Model formalizes this conclusion.
Photons are treated as causal instructions associated with $Z_{U}$, possessing no
internal spacetime duration and therefore no in-flight spacetime ontology.
They are rendered only at emission and absorption.


In this framework, the Quantum Platform (QP) denotes the minimal,
non-temporally-ordered level at which conservation-consistent correlations
are fixed, while the Spacetime Deployment Frame (SDF) denotes the familiar
relativistic arena in which those correlations appear as temporally ordered
events with delay.


No additional ontological domain is posited; the claim follows as a structural
consequence of null duration.

The governing bridge laws,
\[
\MassDelayLaw, \qquad \CausalSpeedLaw,
\]
are unchanged.
They formalize relationships already implicit in relativistic and quantum mechanics.
TLM does not modify these relations; it reinterprets them as deployment constraints
governing how events appear in spacetime.
What changes is the ontology assigned to the null case.


Terms such as “Quantum Platform,” “Spacetime Deployment Frame,” and $Z_U$ are not proposed as additional physical structures or dynamical layers, but as bookkeeping devices for distinguishing endpoint-localized events from null-mediated relations once rest-frame persistence is unavailable.



\section{Why This Move Is Conservative}

The TLM:
\begin{itemize}
\item Modifies no relativistic equations,
\item Preserves all empirical predictions,
\item Introduces no new forces or constants,
\item Removes an unnecessary in--between ontology.
\end{itemize}

This mirrors Einstein's removal of the ether.
In both cases, the advance consists in taking an invariant seriously.

\section{Why the Step Was Deferred}

Several factors contributed to the delay:
diagrammatic habits,
the convenience of trajectory language,
and discomfort with endpoint--only causation.
None of these constitute physical objections.

History suggests that such resistance is typical when equations
outpace intuition.

\section{Summary}

Relativity already tells us that massless excitations have no internal duration.
The Timeless Light Model takes the additional step of recognizing that processes
with no internal duration cannot be internal spacetime processes at all.

This paper intentionally restricts its scope to interpretive clarification.
Whether future work exploits this clarification to derive new tests is a
separate question. The immediate aim is to align physical interpretation
with the invariants already present in the formalism.

Clarifying the status of null proper time also constrains how
future theories of quantum gravity, entanglement, or spacetime emergence
may legitimately assign dynamical degrees of freedom to massless excitations.
In particular, such theories must respect the absence of proper-time evolution
along null paths.

For example, any candidate theory that assigns local dynamical degrees of freedom
to massless excitations along null directions must still account for the absence
of internal temporal evolution along those paths. The TLM framing makes this
constraint explicit by treating null propagation as boundary-defined rather
than internally dynamical.

\begin{axiombox}{Scope Limits}
This paper:
\begin{itemize}
\item does not assert that photons do not occur or do not enter into interactions,
\item does not deny the utility of null geodesics, propagators, or wave descriptions,
\item does not supply a complete ontology of massless excitations,
\item does not claim uniqueness of the Timeless Light Model.
\end{itemize}
Its sole aim is to motivate interpretive restraint by taking null proper time seriously.
\end{axiombox}



\section{Conclusion}

Relativity assigns null proper time to massless paths.
This paper argues that $\tau = 0$ should be read as a marker of domain non-membership,
denoted $Z_{U}$, rather than as a vanishing duration within spacetime.
The Timeless Light Model completes a deferred ontological step in the relativistic
framework that began with Lorentz and was advanced decisively by Einstein.

Nothing is added.
Something is removed.
Clarity is the result.





\appendix
\section*{Appendix A: Null Paths and Ontology}

\begin{center}
\begin{tikzpicture}[scale=1.1]
\draw[->] (0,-2) -- (0,2) node[above] {Time};
\draw[->] (-2,0) -- (2,0) node[right] {Space};
\draw[thick] (-1.5,-1.5) -- (1.5,1.5);
\draw[thick] (-1.5,1.5) -- (1.5,-1.5);
\node at (1.6,1.4) {$ds^{2}=0$};
\end{tikzpicture}
\end{center}

Null paths define causal structure without internal duration.
They require endpoints but not intermediates.

\section*{Glossary (TLM)}

\begin{itemize}
\item \textbf{Quantum Platform (QP):} Timeless instruction layer where causal pairs are authored.
\item \textbf{Spacetime Deployment Frame (SDF):} Rendered arena where delay produces experience.
\item \textbf{Null Proper Time:} Zero elapsed time along massless paths.
\item \textbf{Instruction:} Endpoint--defined causal transfer without traversal.
\end{itemize}

\begin{thebibliography}{99}
\bibitem{Einstein1905}
A.~Einstein,
\emph{Zur Elektrodynamik bewegter K{\"o}rper},
Annalen der Physik \textbf{17}, 891--921 (1905).
\href{https://doi.org/10.1002/andp.19053221004}{doi:10.1002/andp.19053221004}.

\bibitem{Einstein1916}
A.~Einstein,
\emph{The Foundation of the General Theory of Relativity},
Annalen der Physik \textbf{49}, 769--822 (1916).
\href{https://doi.org/10.1002/andp.19163540702}{doi:10.1002/andp.19163540702}.

\bibitem{MTW}
C.~W.~Misner, K.~S.~Thorne, and J.~A.~Wheeler,
\emph{Gravitation},
W.~H.~Freeman, San Francisco (1973).

\bibitem{FeynmanQED}
R.~P.~Feynman,
\emph{QED: The Strange Theory of Light and Matter},
Princeton University Press, Princeton (1985).

\bibitem{Rindler}
W.~Rindler,
\emph{Introduction to Special Relativity},
Oxford University Press (1991).

\bibitem{BrodskyLC}
S.~J.~Brodsky, H.-C.~Pauli, and S.~S.~Pinsky,
``Quantum Chromodynamics and Other Field Theories on the Light Cone,''
\emph{Physics Reports} \textbf{301}, 299--486 (1998).
\href{https://doi.org/10.1016/S0370-1573(97)00089-6}{doi:10.1016/S0370-1573(97)00089-6}.

\bibitem{PhotonsNotHere}
J.~C.~W.~McKinley,
\emph{Photons Not in the Universe},
Zenodo (2025).
\href{https://doi.org/10.5281/zenodo.17010029}{doi:10.5281/zenodo.17010029}.

\bibitem{PhotonProperTime}
J.~C.~W.~McKinley,
\emph{Photon Proper Time: The Understated Invariant of Special Relativity},
Zenodo (2025).
\href{https://doi.org/10.5281/zenodo.17190047}{doi:10.5281/zenodo.17190047}.

\bibitem{DelayToC}
J.~C.~W.~McKinley,
\emph{DELAY TO C: A Fundamental Law Unifying Physics},
Zenodo (2025).
\href{https://doi.org/10.5281/zenodo.17392978}{doi:10.5281/zenodo.17392978}.

\bibitem{NoRestFrame}
J.~C.~W.~McKinley,
\emph{No Rest Frame, No Persistence: A Kinematic Constraint on Photon Interpretation},
Zenodo (2025).
\href{https://doi.org/10.5281/zenodo.18005884}{doi:10.5281/zenodo.18005884}.

\bibitem{TLMMinimal}
J.~C.~W.~McKinley,
\emph{The Timeless Light Model: A Minimal Interpretive Completion of Relativistic Constraints},
Zenodo (2025).
\href{https://doi.org/10.5281/zenodo.18012564}{doi:10.5281/zenodo.18012564}.

\bibitem{NullCurves}
J.~C.~W.~McKinley,
\emph{Null Curves Without Carriers: Resolving an Ontological Tension in Relativistic Geometry},
Zenodo (2025).
\href{https://doi.org/10.5281/zenodo.18028886}{doi:10.5281/zenodo.18028886}.




\end{thebibliography}

\end{document}

```

</details>

---

### [2025] No Rest Frame, No Persistence: A Kinematic Constraint on Photon Interpretation
*   **DOI:** [10.5281/zenodo.18005884](https://doi.org/10.5281/zenodo.18005884)
*   **Date:** 21 December 2025

<details markdown="1">
<summary><b>Click to view Raw LaTeX Source</b></summary>

```latex
\documentclass[12pt,onecolumn,a4paper]{article}

% ---------- Encoding, fonts ----------
\usepackage[utf8]{inputenc}
\usepackage[T1]{fontenc}
\usepackage{lmodern}
\usepackage{microtype}

% ---------- Layout ----------
\usepackage[margin=1in]{geometry}
\usepackage{fancyhdr}
\setlength{\headheight}{14pt}
\pagestyle{fancy}
\fancyhf{}

\lhead{No Rest Frame, No Persistence}
\rhead{John C.\ W.\ McKinley}
\cfoot{\thepage}

% ---------- Math ----------
\usepackage{amsmath,amssymb,amsthm}
\newtheorem{lemma}{Lemma}
\newtheorem{definition}{Definition}

% ---------- Graphics ----------
\usepackage{graphicx}
\usepackage{tikz}

% ---------- Bibliography & links ----------
\usepackage{natbib}
\usepackage{orcidlink}
\usepackage{hyperref}
\hypersetup{
  colorlinks=true,
  linkcolor=blue,
  citecolor=blue,
  urlcolor=blue
}
\usepackage{cleveref} % keep after hyperref




\title{\textbf{No Rest Frame, No Persistence:\\
A Kinematic Constraint on Photon Interpretation}}
\author{John C. W. McKinley\orcidlink{0009-0005-7097-5035}\\Independent Researcher}
\date{December 21, 2025}
\begin{document}
\maketitle

\begingroup
  \footnotetext[0]{This version published at
  \href{https://10.5281/zenodo.18005884}{https://doi.org/10.5281/zenodo.18005884}.}
\endgroup

\begin{abstract}
Special Relativity establishes that massless excitations admit no rest frame.
While this result is routinely acknowledged, its implications for persistence
and localization are rarely examined. In this paper we show that the absence of
a rest frame withholds the structural prerequisites required to define (i) invariant proper-time duration and temporal progression, (ii) rest-frame localization via hypersurfaces orthogonal to a unit timelike tangent, and (iii) worldline-based identity-through-time in the sense standardly used in relativistic mechanics. As a result, the common intuition of photons as persisting entities between emission and
absorption is not warranted by relativistic kinematics. This work introduces no
new dynamics and proposes no alternative ontology. It identifies a constraint
imposed by standard relativistic structure on permissible interpretation.
We do not deny the empirical adequacy of quantum electrodynamics or the utility of photon language in practice. Rather, we show that relativistic kinematics alone does not license the classical picture of a persisting in-flight entity between emission and absorption.



\end{abstract}



\section{Introduction}

Photons are routinely described as objects that travel through spacetime at
speed $c$. This description persists despite a well-known relativistic fact:
there exists no inertial frame in which a photon is ever at rest \citep{Rindler,MTW}.


The absence of a rest frame is typically treated as a calculational curiosity.
Here we argue that it has direct representational consequences. Specifically, we
show that relativistic kinematics withholds the geometric structures required
to define invariant proper-time duration (temporal progression), rest-frame localization, and worldline-based identity-through-time for massless excitations.




The conclusion is not that photons ``do not exist,'' but that the familiar persisting-particle-in-flight picture is a representational convenience not grounded in the kinematic invariants of special relativity.


This paper advances a \emph{negative} result only. It does not propose a new
ontology, modify existing theory, or deny the empirical adequacy of quantum
electrodynamics. Its sole aim is to clarify what standard relativity does and
does not license us to say.

\paragraph{Persistence as a kinematic bundle.}
In relativistic mechanics, ``persistence'' is not a primitive metaphysical posit but a bundle of kinematic structures: (i) proper-time evolution (hence intrinsic duration and temporal progression), (ii) rest-frame localization via hypersurfaces orthogonal to a unit timelike tangent, and (iii) identity assignment across temporally ordered events along a timelike worldline.
The claim of this paper can be stated without the word itself: \emph{massless excitations admit no rest frame and no proper time, and therefore lack invariant duration, rest-frame localization structure, and worldline-based identity-through-time}.


\section{Rest Frames and Physical Persistence}

We make explicit what will be meant by ``persistence'' in this paper.

\begin{definition}[Worldline persistence (kinematic bundle)]
An entity exhibits \emph{worldline persistence} in relativistic mechanics iff there exists a timelike curve $\gamma$ admitting a proper-time parametrization $\tau$ and an associated unit timelike tangent field
$u^\mu = dx^\mu/d\tau$ with $u^\mu u_\mu = -c^2$, such that all of the following kinematic structures are available:

\begin{enumerate}
\item \textbf{Temporal progression / duration:} events on $\gamma$ are invariantly ordered by $\tau$, supplying a nonzero intrinsic duration between distinct events ($\Delta\tau>0$ for distinct points on $\gamma$).
\item \textbf{Rest-frame localization:} at each event on $\gamma$, the orthogonal complement of $u^\mu$ defines an instantaneous rest space (a simultaneity hypersurface) on which spatial localization is defined.
\item \textbf{Identity across time:} dynamical or intrinsic properties may be assigned along $\gamma$ as properties of \emph{one and the same} entity across temporally ordered events, rather than merely as relations between endpoints.
\end{enumerate}

We will use ``non-persistence'' as shorthand for the simultaneous absence of these kinematic resources (no invariant proper-time duration, no rest-space localization structure, and no worldline-based identity assignment).
\end{definition}


In what follows, we treat ``persistence'' as shorthand for the availability of the three kinematic resources listed in Definition~1.


In relativistic physics, such identification is not
primitive; it is grounded in geometric structure.


For massive particles, a rest frame supplies the kinematic resources needed for invariant duration, rest-frame localization, and identity assignment across time.

\begin{itemize}
\item a timelike four-velocity,
\item a foliation of spacetime into simultaneity hypersurfaces,
\item a proper-time parameter governing internal evolution.
\end{itemize}

Together, these structures allow one to meaningfully assert invariant duration, rest-frame localization, and identity assignment across time for a localized object.






\begin{figure}[h]
\centering
\begin{tikzpicture}[scale=1.0]
  % axes
  \draw[->] (0,0) -- (0,4) node[above] {$ct$};
  \draw[->] (0,0) -- (4,0) node[right] {$x$};

  % timelike worldline
  \draw[thick] (1,0) -- (1.8,3.6) node[above] {timelike $\gamma(\tau)$};

  % orthogonal "rest space" slices (schematic)
  \draw[dashed] (0.3,1.0) -- (2.5,0.7);
  \draw[dashed] (0.4,2.0) -- (2.7,1.6);
  \draw[dashed] (0.5,3.0) -- (2.9,2.5);
  \node at (3.2,2.2) {rest-space slices};

  % null line
  \draw[thick] (0,0) -- (3.2,3.2) node[above right] {null $\ell$};

  % light cone boundary (optional)
  \draw[dotted] (0,0) -- (3.6,3.6);
\end{tikzpicture}

\caption{Timelike motion admits a unit timelike tangent and associated simultaneity hypersurfaces orthogonal to it (schematic). Null curves admit no such rest-space structure and therefore cannot support spacetime persistence in the worldline sense. The figure is schematic and intended only to illustrate the presence or absence of rest-space structure, not to depict physical trajectories.}
\label{fig:timelike-vs-null}


\end{figure}












\section{The No–Rest–Frame Result}

For massless excitations, the relativistic energy–momentum relation
\[
E = pc
\]
implies a null four-momentum. Any Lorentz transformation attempting to bring
such an excitation to rest requires a boost with divergent Lorentz factor
$\gamma \to \infty$.

No finite inertial transformation produces a rest frame for a photon. This is
not a limitation of coordinates or measurement; it is enforced by Lorentz
invariance itself \citep{Rindler}.

Equivalently, a rest frame would require a four-velocity $u^\mu$ proportional to the four-momentum $p^\mu$, but for massless excitations $p^\mu p_\mu = 0$, so no normalization to $u^\mu u_\mu = -c^2$ is possible.

\begin{lemma}[Worldline persistence requires timelike structure]
In relativistic spacetime, the kinematic resources needed for worldline persistence (Definition~1) require a timelike congruence with a unit timelike tangent field $u^\mu$ and a proper-time parameter $\tau$; in particular, they require invariant proper-time duration, rest-frame localization structure, and identity assignment across temporally ordered events.
\end{lemma}


\begin{proof}[Proof sketch]
To assign identity-through-time in spacetime one needs (a) an invariant ordering parameter and (b) a local notion of ``the object's space at an instant.'' 
For massive motion the invariant ordering parameter is proper time $\tau$, and the unit tangent field $u^\mu = dx^\mu/d\tau$ satisfies $u^\mu u_\mu = -c^2$. 
The orthogonal complement of $u^\mu$ at each event defines instantaneous rest-space and supports local localization on simultaneity hypersurfaces.

For a null curve $\gamma$, no proper time parametrization exists \citep{Wald,MTW}:
 $d\tau^2 = -ds^2/c^2 = 0$ along $\gamma$. 
Moreover, any tangent $k^\mu$ to a null curve satisfies $k^\mu k_\mu = 0$ and cannot be normalized to a unit timelike field. 
Although null geodesics admit affine parameters, such parameters lack invariant normalization and any associated orthogonal rest-space structure, and therefore cannot support identity-through-time in the sense of Definition~1.


Consequently there is no rest-space defined by orthogonality to a unit timelike tangent, and thus no kinematic structure available to underwrite worldline persistence.

Related discussions of congruences and relativistic structure can be found in \citep{Malament}.


This is not a semantic stipulation but a consequence of the geometric role played by unit timelike vectors in relativistic mechanics.


\end{proof}














\section{Consequences for Photon Interpretation}

Because massless excitations admit no rest frame, the kinematic resources listed in Definition~1 are unavailable. Without a rest frame (and hence without a unit timelike tangent and proper time):

\begin{itemize}
\item no invariant proper-time duration or intrinsic temporal progression,
\item no rest-frame localization structure (no orthogonal simultaneity hypersurfaces),
\item no worldline-based criterion for identity assignment across temporally ordered events.
\end{itemize}

Null geodesics retain causal and geometric meaning, but this meaning concerns
relations between events, not the persistence of objects between them.

Accordingly, the intuitive picture of a photon as a spacetime entity that exists
\emph{between} emission and absorption is not underwritten by relativistic
kinematics.


\section{Common Objections and Clarifications}

\subsection{Wavepackets and ``approximate localization''}
One may form localized electromagnetic wavepackets, but this does not restore a rest frame or a proper-time parameter for the excitation. 
Wavepacket localization is frame-dependent and does not supply a timelike unit tangent field $u^\mu$ underwriting identity-through-time in the worldline sense of Definition 1.

\subsection{Quantum field theory language}
In quantum field theory, ``a photon'' denotes a quantum of field excitation used in asymptotic state descriptions and scattering calculations. 
The present claim is compatible with this usage: it concerns the lack of kinematic resources in special relativity to interpret that excitation as a persisting in-flight object with a rest-frame-based identity-through-time. 
Propagators encode correlations between events, not trajectories of persisting classical particles.


\section{Relation to Null Proper Time}

A second expression of the same kinematic limitation is that null curves admit $d\tau = 0$ \citep{Wald}, so they cannot support intrinsic time-parameterized evolution. When combined with the absence of a rest frame, the result
is decisive: neither temporal nor spatial persistence can be coherently
defined.

Null geodesics track event-ordering relations but do not supply the kinematic bundle of invariant duration, rest-frame localization, and worldline-based identity assignment associated with persistence in Definition~1.





\section{Scope and Limits}

This analysis does not deny the utility or correctness of quantum field theory.
Photon propagators encode correlations between events, not the worldlines of
persisting particles. The formalism neither supplies nor requires a rest frame
for photons.

The present result is therefore interpretive but constraint-based: it identifies
what the theory withholds, not what must replace it.

\paragraph{Non-persistence is not non-existence.}
The present claim is not that massless excitations fail to occur or to enter into causal-scattering descriptions, but that relativistic kinematics does not supply invariant duration, rest-frame localization structure, or worldline-based identity assignment for them between emission and absorption.


This analysis is restricted to photons within special relativistic kinematics; no claims are made about hypothetical massless excitations beyond this domain.


\section{Conclusion}

Relativity forbids rest frames for massless excitations. 

This single invariant is sufficient to withhold the geometric prerequisites required for invariant duration, rest-frame localization, and worldline-based identity assignment. As a result, the interpretation of photons as persisting in-flight entities is not supported by relativistic structure.

This result does not deny the reality or utility of photons in physical theory; it restricts the representational content that relativistic kinematics alone can support.


What, if anything, should replace this intuition is a separate question.




\begin{thebibliography}{9}

\bibitem[Rindler(2001)]{Rindler}
W.~Rindler,
\emph{Relativity: Special, General, and Cosmological},
2nd ed.,
Oxford University Press (2001).

\bibitem[Wald(1984)]{Wald}
R.~M.~Wald,
\emph{General Relativity},
University of Chicago Press (1984).

\bibitem[Misner et~al.(1973)]{MTW}
C.~W.~Misner, K.~S.~Thorne, and J.~A.~Wheeler,
\emph{Gravitation},
W.~H.~Freeman (1973).

\bibitem[Malament(2012)]{Malament}
D. B. Malament,
\emph{Topics in the Foundations of General Relativity and Newtonian Gravitation Theory},
University of Chicago Press (2012).


\end{thebibliography}





\end{document}

```

</details>

---

### [2025] The Timeless Light Model: A Minimal Interpretive Completion of Relativistic Constraints
*   **DOI:** [10.5281/zenodo.18012564](https://doi.org/10.5281/zenodo.18012564)
*   **Date:** 21 December 2025

<details markdown="1">
<summary><b>Click to view Raw LaTeX Source</b></summary>

```latex
\documentclass[12pt,onecolumn,a4paper]{article}

% ---------- Encoding, fonts ----------
\usepackage[utf8]{inputenc}
\usepackage[T1]{fontenc}
\usepackage{lmodern}
\usepackage{microtype}



% ---------- Layout ----------
\usepackage[margin=1in]{geometry}
\usepackage{fancyhdr}
\setlength{\headheight}{14pt}
\pagestyle{fancy}
\fancyhf{}

\lhead{TLM: Minimal Interpretive Completion}
\rhead{John C.\ W.\ McKinley}
\cfoot{\thepage}

% ---------- Math ----------
\usepackage{amsmath,amssymb,amsthm}

% --- Theorem-like environments (shared counter) ---
% --- Theorem-like environments (shared counter) ---
\newtheorem{theorem}{Theorem}[section]
\newtheorem{proposition}[theorem]{Proposition}
\newtheorem{definition}[theorem]{Definition}
\newtheorem{remark}[theorem]{Remark}




% ---------- Graphics ----------
\usepackage{graphicx}
\usepackage{tikz}
% --- TikZ libraries for the null-path figure ---
\usetikzlibrary{arrows.meta,decorations.pathreplacing,positioning}


% ---------- Bibliography & links ----------
\usepackage{orcidlink}
\usepackage[numbers,sort&compress]{natbib} % or: [authoryear] if you prefer

\usepackage{hyperref}
\urlstyle{same}
\hypersetup{
  colorlinks=true,
  linkcolor=blue,
  citecolor=blue,
  urlcolor=blue
}

\usepackage[nameinlink,noabbrev]{cleveref} % keep after hyperref

\crefname{proposition}{Proposition}{Propositions}
\Crefname{proposition}{Proposition}{Propositions}
\crefname{definition}{Definition}{Definitions}
\Crefname{definition}{Definition}{Definitions}
\crefname{remark}{Remark}{Remarks}
\Crefname{remark}{Remark}{Remarks}



% (A) Add to PREAMBLE
% Put after your \newtheorem lines.
% ----------------------------

% A lightweight macro set to keep terminology disciplined
\newcommand{\tlm}{\textsc{TLM}}

\newcommand{\Aff}{\lambda} % affine parameter
\newcommand{\ProperTime}{\tau}


\title{\textbf{The Timeless Light Model:\\
A Minimal Interpretive Completion of Relativistic Constraints}}
\author{John C. W. McKinley\orcidlink{0009-0005-7097-5035}\footnote{This version published at \href{https://doi.org/10.5281/zenodo.18012564}{doi:10.5281/zenodo.18012564}.}\\Independent Researcher}



\date{December 21, 2025}

\begin{document}
\maketitle







\begin{abstract}
Building on the kinematic constraint that massless excitations admit no rest frame and no proper-time evolution, this paper addresses how photon language can be consistently interpreted once that constraint is taken seriously. The formalism leaves open a limited representational choice: one may remain instrumentalist or agnostic about physical interpretation, or one may adopt a minimal reading in which ``photon talk'' functions as shorthand for correlations between emission and absorption events.

We label this minimal reading the Timeless Light Model (\tlm{}). Here ``timeless'' means only that null propagation carries no proper-time evolution (\(\ProperTime = 0\)) along the associated null curve; it does \emph{not} assert acausal influence, new degrees of freedom, hidden variables, or modifications to relativity or QED. The aim is to align informal persistence-language with the structures actually present in relativistic and field-theoretic descriptions. \tlm{} is offered as one permissible interpretive guideline among several, not as a uniquely correct ontology.

Throughout, the terms ``photon'' and ``massless excitation'' are used interchangeably, with the latter preferred where kinematic precision is required. 
\end{abstract}


\section{Introduction}

Special Relativity constrains the structures available for describing physical
systems. In particular, the absence of a rest frame for massless excitations
removes the usual rest-frame resources used to ground the standard persistence narrative for localized massive systems.

For standard treatments of relativistic kinematics and null structure, see, e.g., \cite{Rindler}.

The purpose of this paper is to examine how photon language may be used
consistently once the relativistic kinematic facts are taken seriously—namely,
that massless excitations admit no inertial rest frame and no proper-time
parameter along null propagation. Given the absence of the structures that
normally underwrite rest-frame persistence for massive objects, we articulate
a minimal, conservative interpretive discipline for photon descriptions.



\begin{remark}[Scope and claims]
This paper is deliberately \emph{interpretive}. It makes no dynamical proposals, introduces no new fields, and claims no new empirical consequences. Its target is a narrow mismatch between common informal language (``a photon is a little object flying through space'') and the resources that relativistic and field-theoretic formalisms provide for massless excitations. Where the companion note \cite{NoRestFrame} states a negative constraint, the present note offers one conservative way to speak thereafter.
\end{remark}

In a companion paper \cite{NoRestFrame}, this constraint was established as a
purely negative result. The present work addresses the interpretive gap that
remains once that constraint is taken seriously.

\section{Rest-Frame Constraint for Massless Excitations}




\begin{proposition}[Rest-frame constraint]\label{prop:restframe}
For a massless excitation, there exists no inertial frame in which the excitation is at rest. Along any null curve associated with such an excitation, 
the proper time satisfies
\[
d\ProperTime = 0 .
\]
Consequently, the standard rest-frame-based notion of persistence available for massive localized systems is not defined in the same way for massless excitations.
\end{proposition}

This proposition is a direct consequence of relativistic kinematics and requires no additional assumptions. The present paper takes this constraint as given and asks only how photon language may be consistently interpreted once it is acknowledged.





\section{Representational Options After the Constraint}

Relativistic kinematics fixes invariant causal structure but underdetermines how informal particle language should be applied to massless excitations. Once the rest-frame constraint is acknowledged, several representational options remain open:

\begin{enumerate}
\item \emph{Purely calculational usage:} treat ``photon'' as a symbolic device within amplitudes and cross sections.
\item \emph{Underspecified usage:} refrain from assigning any physical reading beyond invariant correlations.
\item \emph{Endpoint-focused usage:} treat ``photon'' language as shorthand for null-mediated correlations between localized interaction events. 
\end{enumerate}


The Timeless Light Model adopts option (3) as a reading consistent with the kinematic structure.

Throughout, we use ``endpoint-description'' (also ``endpoint-focused'') to denote
a minimal interpretive stance in which localized interaction events
(emission, absorption, or interaction vertices) are treated as the primary
spacetime relata, while intermediate ``particle in flight'' language is regarded
as representational shorthand rather than as a claim of rest-frame persistence.




\section{Endpoint-Defined Descriptions of Null-Mediated Correlations}


If photon descriptions do not support a rest-frame-grounded persistence story,
their physical role is naturally understood in terms of relations between
emission and absorption events. This shift requires no modification of existing equations, only a reinterpretation of what those equations describe.

Endpoint-defined descriptions are already implicit in quantum field theory,
where creation and annihilation operators act at spacetime points and
propagators encode correlations rather than trajectories.

This perspective is standard in quantum field theory, where particles appear as asymptotic states and interactions are localized at vertices; see, e.g., \cite{WeinbergQFT,PeskinSchroeder}.

Field theory already encourages restraint about ``particle-in-flight'' ontology: interactions are localized at vertices, and propagation is encoded via Green functions/propagators that support predictions for correlations between events. \tlm{} adopts this familiar restraint as an explicit reading rather than as mere calculational etiquette.

This endpoint-focused reading is also consistent with how single-photon states are operationally defined in modern photonic quantum technologies \cite{OBrienQI}.



\subsection{Endpoint-Descriptions and Null Propagation}

We restate the rest-frame constraint established in \Cref{prop:restframe}
to emphasize its role in motivating the interpretive shift.


\begin{remark}[Modest kinematic point]
For massless excitations, the standard rest-frame grounded persistence picture available for massive localized systems is not available: there exists no inertial frame in which the excitation is at rest, and along null propagation the proper time satisfies \(d\ProperTime=0\). Consequently, any ``persistence'' narrative for photons is representational rather than rest-frame grounded in the manner applicable to massive objects.

This remark does \emph{not} deny the utility of null geodesics, affine parameters, or field evolution in coordinate time. It states only that the common massive-object template for persistence (rest frame + proper time as internal clock) does not transfer unchanged to massless excitations.
\end{remark}


\subsection{Terminology (minimal and operational)}
\begin{definition}[Persistence (rest-frame grounded)]
By ``persistence'' we mean the ordinary relativistic notion used for localized massive systems: identity of an object across a one-parameter family of spacelike hypersurfaces in a frame in which the object is at rest, with internal evolution parameterized by proper time.
\end{definition}

\begin{definition}[Timeless (as used here)]
In \tlm{}, ``timeless'' is shorthand for the kinematic fact that a null worldline has vanishing proper time,
\[
d\ProperTime = 0,
\]
so there is no invariant proper-time parameter available to describe internal evolution along the null worldline. No stronger metaphysical claim is intended.
\end{definition}




\begin{definition}[Endpoint-description (minimal)]
An ``endpoint-description'' is a description in which the physically recorded interaction events (emission/absorption, or more generally interaction vertices) are taken as the primary localized relata, and intermediate ``particle in flight'' language is treated as calculational or representational shorthand.
\end{definition}



\section{Endpoint Descriptions in Field Theory and Causation}


In quantum electrodynamics, the photon propagator encodes correlations between spacetime points rather than a persisting trajectory. In schematic form,
\[
D_{\mu\nu}(x-y)
= \int \frac{d^4 k}{(2\pi)^4}
\frac{-i g_{\mu\nu}}{k^2 + i\epsilon}
e^{-ik\cdot(x-y)} ,
\]
which supports predictions for interaction amplitudes without requiring an intermediate localized object with rest-frame persistence.

The Timeless Light Model does not reinterpret this formalism; it makes explicit the restrained reading already implicit in its use \cite{WeinbergQFT,PeskinSchroeder}.



\section{Relation to Photon Correlation Experiments}

Although empirically neutral, the endpoint-focused reading aligns naturally with experimental practice in quantum optics, where physically recorded quantities are correlations between detection events. Examples include Hanbury Brown--Twiss interferometry and coincidence measurements in quantum information experiments, where ``single-photon'' behavior is operationally defined through detection statistics rather than intermediate trajectories \cite{MandelWolf,HBTOriginal}.

In such contexts, the Timeless Light Model functions as a clarifying interpretive guide, not as an alternative theory.

A representative case is delayed-choice interferometry \cite{JacquesDelayedChoice},
which illustrates that the formalism assigns amplitudes to detection outcomes conditional
on experimental configuration, but does not require a persisting localized object
with a rest-frame internal history along a definite path. On the \tlm{} reading,
``which path'' language is treated as a representational convenience tied to endpoint
correlations and available records, rather than as a literal narrative of an
in-flight photon carrying an evolving internal state.






\begin{figure}[ht]
\centering
\begin{tikzpicture}[x=1cm,y=1cm,>=Latex, font=\small]

  % Axes
  \draw[->] (0,0) -- (0,6.2) node[above] {$ct$};
  \draw[->] (0,0) -- (6.2,0) node[right] {$x$};

  % Light cone (no text labels on the rays)
  \draw[thick] (0,0) -- (5.6,5.6);
  \draw[thick] (0,0) -- (-5.6,5.6);

  % Events: emission and absorption
  \fill (0.9,1.0) circle (2pt);
  \node[below left] at (0.8,1.1) {$E$};

  \fill (4.9,5.0) circle (2pt);
  \node[above right] at (4.7,5.1) {$A$};

  % Null path between endpoints
  \draw[very thick,->] (0.9,1.0) -- (4.9,5.0);

  % Proper-time annotation along the null segment (brace placed away from labels)
  \draw[decorate,decoration={brace,amplitude=8pt},thick]
    (1.1,1.2) -- (4.7,4.8)
    node[midway, left=15pt] {$\Delta \ProperTime = 0$};

  % Timelike worldline example (massive), label placed separately to avoid overlap
  \draw[thick,dashed] (2.2,0.7) -- (2.9,5.7);
  \node[align=left] at (3.9,5.9) {timelike\\(massive)};
  \node[below] at (2.2,0.7) {$m>0$};

  % Small label for the null ray (placed near A, not on top of anything)
  \node[align=left] at (6.0,4.55) {null\\(lightlike)};

\end{tikzpicture}
\caption{Minkowski diagram with emission $E$ and absorption $A$ connected by a null segment. Along a null path, the invariant proper time satisfies $\Delta\ProperTime=0$, so the rest-frame persistence template used for massive objects (timelike worldlines) does not transfer unchanged to massless excitations. The dashed timelike line is shown only for contrast with the massive-object persistence template.}
\label{fig:null-path}
\end{figure}
















\section{The Timeless Light Model (\tlm{}): An Interpretive Rule}
\begin{remark}[On terminology]
The term ``model'' is used here in a weak, non-technical sense, to denote a named
interpretive stance concerning the ontological reading of existing relativistic
and quantum invariants. The relations introduced are not laws in a Newtonian or
dynamical sense, but explicit statements of constraints already enforced
implicitly by the standard formalism. No new formal structure, equations, or
dynamical assumptions are introduced beyond those already present in
relativistic and quantum theory.
\end{remark}


The Timeless Light Model is a minimal interpretive reading of standard practice that makes one constraint on informal language explicit:


\begin{definition}[\tlm{} interpretive rule]
Throughout, ``photon'' is used as shorthand for a null-mediated relation between
interaction events (emission/absorption, or more generally vertex-to-vertex
correlation), not as the name of a persisting localized spacetime object with an
available rest-frame persistence story.
\end{definition}


Concretely, \tlm{} endorses the following weak commitments:
\begin{itemize}
\item \textbf{No persistence template import:} do not import the massive-object persistence template (rest frame + proper time clock) into photon language.
\item \textbf{Endpoint primacy:} treat localized interaction events as the primary ontic candidates; treat ``in flight'' talk as shorthand.
\item \textbf{No extra structure:} introduce no new dynamics, no preferred frames, no hidden variables, and no claims beyond standard SR/GR/QED predictions.
\end{itemize}

\begin{remark}[What \tlm{}\ is not]
\tlm{} is not a claim of superluminal influence, retrocausality, nonlocal signaling, or new physics. ``Timeless'' here means only \(\ProperTime=0\) along null propagation.
\end{remark}


\section{Consistency with Established Physics}

\tlm{} is compatible with Special Relativity, General Relativity, and quantum field
theory. It alters no equations, introduces no preferred frames, and makes no
claims about hidden variables or additional dimensions.

Its contribution is interpretive: it aligns ontology with the structures the
theory actually provides.

\section{Why This Completion Is Minimal}

\tlm{} adds no structure beyond what is required to interpret endpoint-defined descriptions coherently.
 It removes only an assumption—the persistence of photons
as spacetime objects—that is not supported by relativistic kinematics. 

In this sense, \tlm{} is conservative rather than revisionary.


\section{Motivation for an Explicit Interpretive Reading}

If the sole aim were calculation, no additional language would be required. The motivation for an explicit minimal reading is instead \emph{linguistic and pedagogical}: to prevent a recurrent category error in which massive-object persistence intuitions are inadvertently applied to massless excitations. The proposed reading enforces a simple discipline while leaving all computations unchanged.

In this restricted sense, \tlm{} is ``minimal.'' It introduces no postulates about dynamics, measurement, or ontology beyond what is already implicit in relativistic and field-theoretic structure. Its sole contribution is to make explicit a \emph{constraint on informal interpretation} that follows directly from the absence of a rest frame and proper-time evolution for null propagation \cite{NoRestFrame}.

Naming this interpretive stance serves a practical purpose: it renders the constraint explicit, citable, and reusable across contexts where photon language risks importing unsupported persistence narratives. No claim is made that \tlm{} constitutes a competing physical theory; it is offered solely as a disciplined interpretive guideline aligned with existing formalism.



\section{Alternatives and Comparison}

Other responses to the no-go result remain viable. Instrumentalism avoids
ontology altogether; agnosticism defers the question. \tlm{} differs only in
offering a concrete interpretive framework while remaining empirically neutral.

 Related interpretive restraint is common in field-theoretic practice, even when not made explicit at the ontological level \cite{WeinbergQFT}. This restraint is consistent with longstanding views in axiomatic and algebraic quantum field theory, where particle ontology is treated as secondary to local field observables and event structure \cite{HaagQFT}.




\subsection{Relation to other event-based or correlation-first readings (brief)}
Event- or correlation-first ontologies have been developed in several distinct contexts.
For example, ``flash'' ontologies in spontaneous-collapse models take localized spacetime events as primitive rather than persisting particle trajectories \cite{GRW}.
Time-symmetric approaches such as the Transactional Interpretation similarly emphasize emitter--absorber boundary conditions rather than in-flight particle persistence, though they introduce additional interpretive machinery not assumed here \cite{CramerTI}.
These frameworks differ in dynamics and commitments: collapse approaches introduce stochastic modifications, and transactional approaches invoke additional interpretive structure.
By contrast, \tlm{} makes no dynamical additions and claims no time-symmetric mechanism; it is a kinematic discipline on informal photon language motivated solely by the absence of a rest frame and proper-time evolution for null propagation.

For extended discussion of related interpretive literature, see \Cref{app:literature}.





\section{Foreseeable Objections}

Expanded responses to common interpretive objections are collected in Appendix~\ref{app:objections}.

\subsection{``Null worldlines already exist; why is this new?''}
Agreed: \tlm{} introduces no new geometry. Its only contribution is to state explicitly that the massive-object persistence template should not be imported into photon talk.

\subsection{``This is just instrumentalism in disguise.''}
Not quite. Instrumentalism refuses ontology; \tlm{} permits a weak ontic reading (endpoint primacy) while still treating in-flight language as representational shorthand.

\subsection{``Affine parameters provide evolution, so timeless is misleading.''}
Affine parameters \(\Aff\) may parameterize null curves, but they are not proper time and do not supply a rest-frame internal clock. \tlm{} uses ``timeless'' only in the narrow sense of \(\ProperTime=0\).


\section{Conclusion}

The purpose of this paper is to examine how photon language may be used
consistently with Special Relativity, and to argue that treating ``photon'' as
shorthand for endpoint-defined interaction activity provides a minimal and
conservative reading of the formalism.

The companion note \cite{NoRestFrame} motivates a limited interpretive caution: for photons, the rest-frame grounded persistence story familiar from massive objects is not available in its standard form.
This note offers \tlm{} as one explicitly minimal interpretive stance among several permissible readings for respecting that caution: treat ``photon'' as shorthand for a null-mediated relation between interaction events, and treat in-flight persistence language as representational.

No claim of unique correctness is made. The proposal is a conservative reading that aims to reduce a common category error while leaving the formalism and its empirical content unchanged.

Nothing in this reading commits one to claims about the existence or non-existence
of photons beyond the interpretive scope defined here.





\appendix


\section{Extended Literature Context: Photon Ontology and Interpretive Restraint}
\label{app:literature}

This appendix situates the Timeless Light Model (\tlm{}) within a broader landscape
of existing discussions concerning photon ontology, particle persistence, and
interpretive restraint in relativistic quantum field theory. The purpose of this
survey is contextual rather than argumentative: no claim of priority, exclusivity,
or resolution of longstanding debates is made.

A recurring theme in modern quantum field theory is that particle concepts,
particularly for massless excitations, do not straightforwardly support a
localized, persisting object interpretation. In relativistic QFT, particles
appear most cleanly as asymptotic states, while local structure is carried by
fields and local observables rather than by particle trajectories
\cite{WeinbergQFT,HaagQFT}. This structural feature already encourages caution
about importing classical persistence narratives into photon language.

Related concerns arise in discussions of localization. It is widely noted in the
literature that photon localization does not admit a Lorentz-covariant position
operator in the same sense as for massive particles, and that localization is
therefore treated operationally—via detection statistics or wave-packet
descriptions—rather than in terms of sharp position eigenstates
\cite{Wightman1962,NewtonWigner1949,BialynickiBirula1996}.




This fact has motivated a range of views in which
photons are treated as delocalized field excitations or as bookkeeping devices for
energy--momentum transfer, rather than as pointlike entities with well-defined
worldlines. These results underscore the limited applicability of massive-particle
intuition to massless excitations.

Algebraic and axiomatic approaches to quantum field theory reinforce this
perspective by prioritizing local algebras of observables and event structure over
particle ontology \cite{HaagQFT}. Within such frameworks, particles are often
understood as emergent or approximate descriptors tied to specific regimes, rather
than as fundamental spacetime occupants. The present work is compatible with this
outlook, though it does not rely on algebraic machinery.

Pedagogical discussions in both relativity and quantum optics further reveal a
persistent mismatch between informal language and formal structure. Expressions
such as ``the photon travels through space'' or ``the photon experiences no time''
are common heuristics, but they are not literal consequences of relativistic
kinematics. The kinematic result that null worldlines carry vanishing proper time
already constrains how such language may be interpreted without contradiction.

Against this background, \tlm{} should be understood as a minimal interpretive
discipline rather than as a novel ontological proposal. Its contribution is to
state explicitly a restraint that is often applied implicitly in advanced
practice: namely, that the rest-frame-based persistence template used for massive
objects should not be imported wholesale into photon descriptions. In this sense,
\tlm{} functions as a pedagogical and linguistic clarification aligned with
existing formal results, rather than as a competing interpretation of quantum
field theory.



\section{Detailed Responses to Common Interpretive Objections}
\label{app:objections}

This appendix expands on several foreseeable objections that may arise in response
to the interpretive stance adopted in this paper. These remarks are intended to
clarify scope and intent rather than to argue for exclusivity or necessity.

\subsection*{``This is already standard quantum field theory''}

In one sense, this objection is correct. The formalism of relativistic quantum
field theory does not require a persisting, localized photon traveling through
space, and experienced practitioners routinely avoid such language in precise
contexts. The contribution of \tlm{} is not to introduce a new formal insight, but
to elevate this implicit restraint to an explicit interpretive rule. This
clarification is motivated by the persistent reappearance of massive-object
intuition in pedagogical, popular, and even technical discussions of photons.

\subsection*{``This is merely instrumentalism under another name''}

Instrumentalist approaches typically refrain from making any ontological
commitments. By contrast, \tlm{} permits a weak ontic reading in which localized
interaction events (emission, absorption, or interaction vertices) are treated as
the primary spacetime relata, while ``in-flight'' particle language is regarded as
representational shorthand. This position occupies a middle ground between strict
instrumentalism and robust particle ontology.

\subsection*{``Why call this a model at all?''}

The term ``model'' is used here in a deliberately weak sense, referring to a named
interpretive guideline rather than to a dynamical or predictive framework. Naming
the stance serves a practical purpose: it allows the interpretive constraint to be
clearly stated, referenced, and compared with alternatives. No claim is made that
\tlm{} constitutes a physical model in the sense of adding structure or modifying
the formalism.

\subsection*{``Interpretive papers lack scientific value''}

Interpretive clarification plays a well-established role in theoretical physics,
particularly where informal reasoning risks conflict with formal invariants. In
the present case, the clarification concerns the consequences of the null
proper-time condition for photon language. By aligning informal descriptions with
kinematic structure, \tlm{} aims to reduce category errors without altering
calculations or empirical content. Its value is therefore pedagogical and
conceptual rather than predictive.

\subsection*{``Does this imply nonlocality, retrocausality, or acausal influence?''}

No. The present work introduces no claims about causal mechanisms beyond those
already present in relativistic quantum field theory. References to endpoint
correlations are not intended to suggest signaling, time-symmetric dynamics, or
influences outside standard causal structure. ``Timeless'' is used strictly in the
kinematic sense of vanishing proper time along null propagation.




\begin{thebibliography}{99}

\bibitem{NoRestFrame}
J.~C.~W.~McKinley,
\emph{No Rest Frame, No Persistence: A Kinematic Constraint on Photon Interpretation},
Zenodo (2025),
\href{https://doi.org/10.5281/zenodo.18005884}{doi:10.5281/zenodo.18005884}.

\bibitem{Rindler}
W.~Rindler,
\emph{Introduction to Special Relativity},
Oxford University Press (1991).

\bibitem{WeinbergQFT}
S.~Weinberg,
\emph{The Quantum Theory of Fields, Vol.~I: Foundations},
Cambridge University Press (1995).

\bibitem{PeskinSchroeder}
M.~E.~Peskin and D.~V.~Schroeder,
\emph{An Introduction to Quantum Field Theory},
Westview Press (1995).

\bibitem{MandelWolf}
L.~Mandel and E.~Wolf,
\emph{Optical Coherence and Quantum Optics},
Cambridge University Press (1995).

\bibitem{HBTOriginal}
R.~Hanbury Brown and R.~Q.~Twiss,
``Correlation between photons in two coherent beams of light,''
\emph{Nature} \textbf{177}, 27--29 (1956).

\bibitem{OBrienQI}
J.~L.~O'Brien, A.~Furusawa, and J.~Vu\v{c}kovi\'c,
``Photonic quantum technologies,''
\emph{Nature Photonics} \textbf{3}, 687--695 (2009).

\bibitem{GRW}
G.~C.~Ghirardi, A.~Rimini, and T.~Weber,
\emph{Unified dynamics for microscopic and macroscopic systems},
Phys.\ Rev.\ D \textbf{34}, 470--491 (1986).

\bibitem{CramerTI}
J.~G.~Cramer,
\emph{The transactional interpretation of quantum mechanics},
Rev.\ Mod.\ Phys.\ \textbf{58}, 647--688 (1986).

\bibitem{HaagQFT}
R.~Haag,
\emph{Local Quantum Physics: Fields, Particles, Algebras},
2nd ed., Springer (1996).

\bibitem{JacquesDelayedChoice}
V.~Jacques, E.~Wu, F.~Grosshans, F.~Treussart, P.~Grangier, A.~Aspect, and J.-F.~Roch,
``Experimental realization of Wheeler's delayed-choice Gedanken Experiment,''
\emph{Science} \textbf{315}, 966--968 (2007).

\bibitem{NewtonWigner1949}
T.~D.~Newton and E.~P.~Wigner,
\emph{Localized States for Elementary Systems},
Rev.\ Mod.\ Phys.\ \textbf{21}, 400--406 (1949).
\href{https://doi.org/10.1103/RevModPhys.21.400}{doi:10.1103/RevModPhys.21.400}

\bibitem{Wightman1962}
A.~S.~Wightman,
\emph{On the Localizability of Quantum Mechanical Systems},
Rev.\ Mod.\ Phys.\ \textbf{34}, 845--872 (1962).
\href{https://doi.org/10.1103/RevModPhys.34.845}{doi:10.1103/RevModPhys.34.845}

\bibitem{BialynickiBirula1996}
I.~Bialynicki-Birula,
\emph{Photon Wave Function},
Prog.\ Opt.\ \textbf{36}, 245--294 (1996).
\href{https://doi.org/10.1016/S0079-6638(08)70316-0}{doi:10.1016/S0079-6638(08)70316-0}

\end{thebibliography}




\end{document}
```

</details>

---

### [2025] From Limit to Cause: c as Baseline Delay in the Timeless Light Model
*   **DOI:** [10.5281/zenodo.17393350](https://doi.org/10.5281/zenodo.17393350)
*   **Date:** 19 October 2025

<details markdown="1">
<summary><b>Click to view Raw LaTeX Source</b></summary>

```latex

```

</details>

---

### [2025] Timeless Means No Sequence: Clarifying the Emit–Wait–Absorb Triad in the Timeless Light Model
*   **DOI:** [10.5281/zenodo.17389830](https://doi.org/10.5281/zenodo.17389830)
*   **Date:** 19 October 2025

<details markdown="1">
<summary><b>Click to view Raw LaTeX Source</b></summary>

```latex

```

</details>

---

### [2025] Timeless Write of Paths: Interference as a Lawful Deployment in the Timeless Light Model (TLM)
*   **DOI:** [10.5281/zenodo.17393412](https://doi.org/10.5281/zenodo.17393412)
*   **Date:** 19 October 2025

<details markdown="1">
<summary><b>Click to view Raw LaTeX Source</b></summary>

```latex

```

</details>

---

### [2025] The Wait Phase and Interference: Timeless Rules Creating Quantum Patterns
*   **DOI:** [10.5281/zenodo.17383869](https://doi.org/10.5281/zenodo.17383869)
*   **Date:** 18 October 2025

<details markdown="1">
<summary><b>Click to view Raw LaTeX Source</b></summary>

```latex

```

</details>

---

### [2025] Timeless Means No Sequence: Clarifying the Emit–Wait–Absorb Triad in the Timeless Light Model
*   **DOI:** [10.5281/zenodo.17388300](https://doi.org/10.5281/zenodo.17388300)
*   **Date:** 18 October 2025

<details markdown="1">
<summary><b>Click to view Raw LaTeX Source</b></summary>

```latex

```

</details>

---

### [2025] Redefining Zero: The Extra-Universal State and the Timeless Light Model
*   **DOI:** [10.5281/zenodo.17336219](https://doi.org/10.5281/zenodo.17336219)
*   **Date:** 12 October 2025

<details markdown="1">
<summary><b>Click to view Raw LaTeX Source</b></summary>

```latex

```

</details>

---

### [2025] Time-Free Photons and Extra-Universal Nothingness: Addressing Speed and Existence Queries in the Timeless Light Model
*   **DOI:** [10.5281/zenodo.17337263](https://doi.org/10.5281/zenodo.17337263)
*   **Date:** 12 October 2025

<details markdown="1">
<summary><b>Click to view Raw LaTeX Source</b></summary>

```latex

```

</details>

---

### [2025] The Unmanned Quantum Platform: Timeless Origin of Instruction and Conservation in the TLM
*   **DOI:** [10.5281/zenodo.17329404](https://doi.org/10.5281/zenodo.17329404)
*   **Date:** 11 October 2025

<details markdown="1">
<summary><b>Click to view Raw LaTeX Source</b></summary>

```latex

```

</details>

---

### [2025] The Wait Phase and Creator-Law Framework in the Timeless Light Model (TLM v3.0)
*   **DOI:** [10.5281/zenodo.17284109](https://doi.org/10.5281/zenodo.17284109)
*   **Date:** 7 October 2025

<details markdown="1">
<summary><b>Click to view Raw LaTeX Source</b></summary>

```latex

```

</details>

---

### [2025] The Wait Phase in the Timeless Light Model (TLM v3.0): Explaining a Timeless Checkpoint for Novices and Experts
*   **DOI:** [10.5281/zenodo.17291452](https://doi.org/10.5281/zenodo.17291452)
*   **Date:** 7 October 2025

<details markdown="1">
<summary><b>Click to view Raw LaTeX Source</b></summary>

```latex

```

</details>

---

### [2025] Absorption-Only Evidence: Photons and Causal Instructions Exist Outside Spacetime
*   **DOI:** [10.5281/zenodo.17275105](https://doi.org/10.5281/zenodo.17275105)
*   **Date:** 5 October 2025

<details markdown="1">
<summary><b>Click to view Raw LaTeX Source</b></summary>

```latex

```

</details>

---

### [2025] No In-Between: Photon Knowledge and Energy Transfer in the Timeless Light Model
*   **DOI:** [10.5281/zenodo.17274555](https://doi.org/10.5281/zenodo.17274555)
*   **Date:** 5 October 2025

<details markdown="1">
<summary><b>Click to view Raw LaTeX Source</b></summary>

```latex

```

</details>

---

### [2025] What Crosses the Cosmos? Timeless Photon Instructions vs. Traveling Particles
*   **DOI:** [10.5281/zenodo.17247906](https://doi.org/10.5281/zenodo.17247906)
*   **Date:** 1 October 2025

<details markdown="1">
<summary><b>Click to view Raw LaTeX Source</b></summary>

```latex

```

</details>

---

### [2025] Bridge Laws in the Timeless Light Model: From Timeless Instructions to Rendered Spacetime
*   **DOI:** [10.5281/zenodo.17240091](https://doi.org/10.5281/zenodo.17240091)
*   **Date:** 30 September 2025

<details markdown="1">
<summary><b>Click to view Raw LaTeX Source</b></summary>

```latex

```

</details>

---

### [2025] Whose Frame is it Anyway? — On Photon Timelessness, Proper Time, and the Observer's Illusion
*   **DOI:** [10.5281/zenodo.17239624](https://doi.org/10.5281/zenodo.17239624)
*   **Date:** 30 September 2025

<details markdown="1">
<summary><b>Click to view Raw LaTeX Source</b></summary>

```latex

```

</details>

---

### [2025] Photon as Instruction, Not Traveler: Emission, Absorption, and the Myth of Flight
*   **DOI:** [10.5281/zenodo.17221119](https://doi.org/10.5281/zenodo.17221119)
*   **Date:** 28 September 2025

<details markdown="1">
<summary><b>Click to view Raw LaTeX Source</b></summary>

```latex

```

</details>

---

### [2025] Photon Thought Experiments and the Timeless Ontology: Why Photons and Quanta Are "Not Here"
*   **DOI:** [10.5281/zenodo.17216652](https://doi.org/10.5281/zenodo.17216652)
*   **Date:** 27 September 2025

<details markdown="1">
<summary><b>Click to view Raw LaTeX Source</b></summary>

```latex

```

</details>

---

### [2025] Why It Matters if a Marble Arrives Before Its Light: Causality and the Fragility of a Lawful Universe
*   **DOI:** [10.5281/zenodo.17205431](https://doi.org/10.5281/zenodo.17205431)
*   **Date:** 26 September 2025

<details markdown="1">
<summary><b>Click to view Raw LaTeX Source</b></summary>

```latex

```

</details>

---

### [2025] Gravity is Geometry. Reality Obeys Rules. Not the Newtonian Holodeck.
*   **DOI:** [10.5281/zenodo.17197557](https://doi.org/10.5281/zenodo.17197557)
*   **Date:** 25 September 2025

<details markdown="1">
<summary><b>Click to view Raw LaTeX Source</b></summary>

```latex

```

</details>

---

### [2025] Photon Proper Time: The Understated Invariant of Special Relativity
*   **DOI:** [10.5281/zenodo.17190047](https://doi.org/10.5281/zenodo.17190047)
*   **Date:** 24 September 2025

<details markdown="1">
<summary><b>Click to view Raw LaTeX Source</b></summary>

```latex

```

</details>

---

### [2025] Massless Things Do Not Experience Time
*   **DOI:** [10.5281/zenodo.17173126](https://doi.org/10.5281/zenodo.17173126)
*   **Date:** 22 September 2025

<details markdown="1">
<summary><b>Click to view Raw LaTeX Source</b></summary>

```latex

```

</details>

---

### [2025] If the Quantum Platform Is a Math Layer: An Interpretive Addendum to the Timeless Light Model
*   **DOI:** [10.5281/zenodo.17169440](https://doi.org/10.5281/zenodo.17169440)
*   **Date:** 21 September 2025

<details markdown="1">
<summary><b>Click to view Raw LaTeX Source</b></summary>

```latex

```

</details>

---

### [2025] Space Will Collapse to Protect c
*   **DOI:** [10.5281/zenodo.17164585](https://doi.org/10.5281/zenodo.17164585)
*   **Date:** 20 September 2025

<details markdown="1">
<summary><b>Click to view Raw LaTeX Source</b></summary>

```latex

```

</details>

---

### [2025] Causal Chain in the Timeless Light Model: Mass as Drag, Frame as Causal Site, Quantum Platform as Cause
*   **DOI:** [10.5281/zenodo.17139863](https://doi.org/10.5281/zenodo.17139863)
*   **Date:** 16 September 2025

<details markdown="1">
<summary><b>Click to view Raw LaTeX Source</b></summary>

```latex

```

</details>

---

### [2025] Time Travel is Real: Forwards But Not Backwards
*   **DOI:** [10.5281/zenodo.17140029](https://doi.org/10.5281/zenodo.17140029)
*   **Date:** 16 September 2025

<details markdown="1">
<summary><b>Click to view Raw LaTeX Source</b></summary>

```latex

```

</details>

---

### [2025] Unlimited Rocket Acceleration and Time Travel to the Future
*   **DOI:** [10.5281/zenodo.17139392](https://doi.org/10.5281/zenodo.17139392)
*   **Date:** 16 September 2025

<details markdown="1">
<summary><b>Click to view Raw LaTeX Source</b></summary>

```latex

```

</details>

---

### [2025] Why the Timeless Light Model is Not Obviously False
*   **DOI:** [10.5281/zenodo.17118184](https://doi.org/10.5281/zenodo.17118184)
*   **Date:** 15 September 2025

<details markdown="1">
<summary><b>Click to view Raw LaTeX Source</b></summary>

```latex

```

</details>

---

### [2025] Rules and Executions: Mathematics as Perfect Code, Physics as Finite Information
*   **DOI:** [10.5281/zenodo.17115196](https://doi.org/10.5281/zenodo.17115196)
*   **Date:** 14 September 2025

<details markdown="1">
<summary><b>Click to view Raw LaTeX Source</b></summary>

```latex

```

</details>

---

### [2025] Delay-Engineered Maneuverability: A Timeless Light Model Interpretation of "Tic Tac" UAP Kinematics
*   **DOI:** [10.5281/zenodo.17111402](https://doi.org/10.5281/zenodo.17111402)
*   **Date:** 12 September 2025

<details markdown="1">
<summary><b>Click to view Raw LaTeX Source</b></summary>

```latex

```

</details>

---

### [2025] Why Rockets Can't Go Faster Than Light
*   **DOI:** [10.5281/zenodo.17083607](https://doi.org/10.5281/zenodo.17083607)
*   **Date:** 9 September 2025

<details markdown="1">
<summary><b>Click to view Raw LaTeX Source</b></summary>

```latex

```

</details>

---

### [2025] Illusion and Invariant: Making Sense of Time Dilation — Reciprocity, Simultaneity, and Proper Time
*   **DOI:** [10.5281/zenodo.17083276](https://doi.org/10.5281/zenodo.17083276)
*   **Date:** 8 September 2025

<details markdown="1">
<summary><b>Click to view Raw LaTeX Source</b></summary>

```latex

```

</details>

---

### [2025] Mass Slows Time. Speed Slows Time. Concept, Derivations, and Evidence
*   **DOI:** [10.5281/zenodo.17083288](https://doi.org/10.5281/zenodo.17083288)
*   **Date:** 8 September 2025

<details markdown="1">
<summary><b>Click to view Raw LaTeX Source</b></summary>

```latex

```

</details>

---

### [2025] Hilbert Space as Frame Representation: A Timeless Light Model Reinterpretation
*   **DOI:** [10.5281/zenodo.17070118](https://doi.org/10.5281/zenodo.17070118)
*   **Date:** 6 September 2025

<details markdown="1">
<summary><b>Click to view Raw LaTeX Source</b></summary>

```latex

```

</details>

---

### [2025] From Descriptive Laws to Falsifiable Predictions: Testing the Timeless Light Model
*   **DOI:** [10.5281/zenodo.17017852](https://doi.org/10.5281/zenodo.17017852)
*   **Date:** 1 September 2025

<details markdown="1">
<summary><b>Click to view Raw LaTeX Source</b></summary>

```latex

```

</details>

---

### [2025] Handling Event Magnitude in the Timeless Light Model: A Minimal QP→SDF Instruction Interface
*   **DOI:** [10.5281/zenodo.17033795](https://doi.org/10.5281/zenodo.17033795)
*   **Date:** 1 September 2025

<details markdown="1">
<summary><b>Click to view Raw LaTeX Source</b></summary>

```latex

```

</details>

---

### [2025] The "No Mid-Flight Energy" Principle: Operational Consistency and Ontological Implications for the Timeless Light Model (TLM)
*   **DOI:** [10.5281/zenodo.17018871](https://doi.org/10.5281/zenodo.17018871)
*   **Date:** 1 September 2025

<details markdown="1">
<summary><b>Click to view Raw LaTeX Source</b></summary>

```latex

```

</details>

---

### [2025] The Emission Delay Law: A General Principle for the Realization of Quanta in the Timeless Light Model
*   **DOI:** [10.5281/zenodo.17032235](https://doi.org/10.5281/zenodo.17032235)
*   **Date:** 1 September 2025

<details markdown="1">
<summary><b>Click to view Raw LaTeX Source</b></summary>

```latex

```

</details>

---

### [2025] Dark Energy as Expansion Within GR: A Timeless Light Model Statement
*   **DOI:** [10.5281/zenodo.17010816](https://doi.org/10.5281/zenodo.17010816)
*   **Date:** 30 August 2025

<details markdown="1">
<summary><b>Click to view Raw LaTeX Source</b></summary>

```latex

```

</details>

---

### [2025] Minimum Frame Size: Discrete Deployment Limits in the Timeless Light Model
*   **DOI:** [10.5281/zenodo.17009716](https://doi.org/10.5281/zenodo.17009716)
*   **Date:** 30 August 2025

<details markdown="1">
<summary><b>Click to view Raw LaTeX Source</b></summary>

```latex

```

</details>

---

### [2025] Photons Not in the Universe: An Axiomatic Derivation from Masslessness and Non-Travel
*   **DOI:** [10.5281/zenodo.17010029](https://doi.org/10.5281/zenodo.17010029)
*   **Date:** 30 August 2025

<details markdown="1">
<summary><b>Click to view Raw LaTeX Source</b></summary>

```latex

```

</details>

---

### [2025] Mathematical Shadows of the Quantum Platform: From Trick to Ontology
*   **DOI:** [10.5281/zenodo.16977344](https://doi.org/10.5281/zenodo.16977344)
*   **Date:** 27 August 2025

<details markdown="1">
<summary><b>Click to view Raw LaTeX Source</b></summary>

```latex

```

</details>

---

### [2025] A Review of the Timeless Light Model: Foundations, Derivations, and Empirical Predictions
*   **DOI:** [10.5281/zenodo.16958221](https://doi.org/10.5281/zenodo.16958221)
*   **Date:** 26 August 2025

<details markdown="1">
<summary><b>Click to view Raw LaTeX Source</b></summary>

```latex

```

</details>

---

### [2025] Test Menu for the Timeless Light Model (TLM)
*   **DOI:** [10.5281/zenodo.16957884](https://doi.org/10.5281/zenodo.16957884)
*   **Date:** 26 August 2025

<details markdown="1">
<summary><b>Click to view Raw LaTeX Source</b></summary>

```latex

```

</details>

---

### [2025] Frame Display Law for TLM v2.0: EA-conditioned Rendering in a Single Spacetime Deployment Frame
*   **DOI:** [10.5281/zenodo.16936105](https://doi.org/10.5281/zenodo.16936105)
*   **Date:** 24 August 2025

<details markdown="1">
<summary><b>Click to view Raw LaTeX Source</b></summary>

```latex

```

</details>

---

### [2025] Ontology of Matter in the Timeless Light Model: From FRAME–CHARGE Toggles to Particles
*   **DOI:** [10.5281/zenodo.16939101](https://doi.org/10.5281/zenodo.16939101)
*   **Date:** 24 August 2025

<details markdown="1">
<summary><b>Click to view Raw LaTeX Source</b></summary>

```latex

```

</details>

---

### [2025] Timeless Light Model (TLM v2.0): Frameless Quanta, Framed Observers, and Bridge Laws
*   **DOI:** [10.5281/zenodo.16934697](https://doi.org/10.5281/zenodo.16934697)
*   **Date:** 23 August 2025

<details markdown="1">
<summary><b>Click to view Raw LaTeX Source</b></summary>

```latex

```

</details>

---

### [2025] Timeless Light Model vs Wheeler–Feynman Absorber Theory: A Disambiguation
*   **DOI:** [10.5281/zenodo.16924316](https://doi.org/10.5281/zenodo.16924316)
*   **Date:** 22 August 2025

<details markdown="1">
<summary><b>Click to view Raw LaTeX Source</b></summary>

```latex

```

</details>

---

### [2025] Quanta are Global, Frames are Local: A Rosetta Statement of the Timeless Light Model
*   **DOI:** [10.5281/zenodo.16917106](https://doi.org/10.5281/zenodo.16917106)
*   **Date:** 21 August 2025

<details markdown="1">
<summary><b>Click to view Raw LaTeX Source</b></summary>

```latex

```

</details>

---

### [2025] The Binary Law of Quanta: Location as a Timeless Choice
*   **DOI:** [10.5281/zenodo.16913425](https://doi.org/10.5281/zenodo.16913425)
*   **Date:** 20 August 2025

<details markdown="1">
<summary><b>Click to view Raw LaTeX Source</b></summary>

```latex

```

</details>

---

### [2025] TLM Addendum: Minimal Formalism and a Decisive Null Test
*   **DOI:** [10.5281/zenodo.16909382](https://doi.org/10.5281/zenodo.16909382)
*   **Date:** 20 August 2025

<details markdown="1">
<summary><b>Click to view Raw LaTeX Source</b></summary>

```latex

```

</details>

---

### [2025] Two Decrees for a Rendered Universe: Charge and Frame-in-Higgs as Sufficient Generators of the Standard Model within the Timeless Light Model
*   **DOI:** [10.5281/zenodo.16914685](https://doi.org/10.5281/zenodo.16914685)
*   **Date:** 20 August 2025

<details markdown="1">
<summary><b>Click to view Raw LaTeX Source</b></summary>

```latex

```

</details>

---

### [2025] Unified Quantization Principle: GR, SR, and QM as Quantized Deployments of Binary Quanta
*   **DOI:** [10.5281/zenodo.16913967](https://doi.org/10.5281/zenodo.16913967)
*   **Date:** 20 August 2025

<details markdown="1">
<summary><b>Click to view Raw LaTeX Source</b></summary>

```latex

```

</details>

---

### [2025] Generalized Pairing Law: No Quantum Emission Without an Absorber
*   **DOI:** [10.5281/zenodo.16893165](https://doi.org/10.5281/zenodo.16893165)
*   **Date:** 18 August 2025

<details markdown="1">
<summary><b>Click to view Raw LaTeX Source</b></summary>

```latex

```

</details>

---

### [2025] The Quanta Transfer Law
*   **DOI:** [10.5281/zenodo.16897573](https://doi.org/10.5281/zenodo.16897573)
*   **Date:** 18 August 2025

<details markdown="1">
<summary><b>Click to view Raw LaTeX Source</b></summary>

```latex

```

</details>

---

### [2025] The One Blind Spot That Hid Three Simple Solutions: A Testable Reinterpretation of Photon Ontology Outside Spacetime
*   **DOI:** [10.5281/zenodo.16871293](https://doi.org/10.5281/zenodo.16871293)
*   **Date:** 14 August 2025

<details markdown="1">
<summary><b>Click to view Raw LaTeX Source</b></summary>

```latex

```

</details>

---

### [2025] From Endpoint Pairing to Frame Splitting: Absorption-Frame Motion in the Timeless Light Framework
*   **DOI:** [10.5281/zenodo.16791636](https://doi.org/10.5281/zenodo.16791636)
*   **Date:** 10 August 2025

<details markdown="1">
<summary><b>Click to view Raw LaTeX Source</b></summary>

```latex

```

</details>

---

### [2025] Gravitons as Quantum Platform Geometry Instructions: A Timeless-Light Interpretation of Gravitational Wave Quanta
*   **DOI:** [10.5281/zenodo.16788039](https://doi.org/10.5281/zenodo.16788039)
*   **Date:** 10 August 2025

<details markdown="1">
<summary><b>Click to view Raw LaTeX Source</b></summary>

```latex

```

</details>

---

### [2025] The Quantum Platform as Frame Generator: Ontology, Anatomy, and Dark Matter Implications in TLM
*   **DOI:** [10.5281/zenodo.16788735](https://doi.org/10.5281/zenodo.16788735)
*   **Date:** 10 August 2025

<details markdown="1">
<summary><b>Click to view Raw LaTeX Source</b></summary>

```latex

```

</details>

---

### [2025] The Frame as Master: A Unified Foundation for the Timeless Light Model
*   **DOI:** [10.5281/zenodo.16787219](https://doi.org/10.5281/zenodo.16787219)
*   **Date:** 9 August 2025

<details markdown="1">
<summary><b>Click to view Raw LaTeX Source</b></summary>

```latex

```

</details>

---

### [2025] At Some Point, You Have to Make Room for a Creator of the Universe—Whether It Be God, Gods, or Unicorn Dreams
*   **DOI:** [10.5281/zenodo.16757589](https://doi.org/10.5281/zenodo.16757589)
*   **Date:** 7 August 2025

<details markdown="1">
<summary><b>Click to view Raw LaTeX Source</b></summary>

```latex

```

</details>

---

### [2025] Frame Pair Stretch and the ZeroSpace Postulate in the Timeless Light Model
*   **DOI:** [10.5281/zenodo.16777862](https://doi.org/10.5281/zenodo.16777862)
*   **Date:** 7 August 2025

<details markdown="1">
<summary><b>Click to view Raw LaTeX Source</b></summary>

```latex

```

</details>

---

### [2025] Why Rockets Can't Go Faster Than Light
*   **DOI:** [10.5281/zenodo.16758093](https://doi.org/10.5281/zenodo.16758093)
*   **Date:** 7 August 2025

<details markdown="1">
<summary><b>Click to view Raw LaTeX Source</b></summary>

```latex

```

</details>

---

### [2025] The Failure of the Newtonian Holodeck: Why a Universe Without Relativity Cannot Sustain Itself
*   **DOI:** [10.5281/zenodo.16750632](https://doi.org/10.5281/zenodo.16750632)
*   **Date:** 5 August 2025

<details markdown="1">
<summary><b>Click to view Raw LaTeX Source</b></summary>

```latex

```

</details>

---

### [2025] The Photon as a Timeless, Spaceless Energy Transfer
*   **DOI:** [10.5281/zenodo.16735683](https://doi.org/10.5281/zenodo.16735683)
*   **Date:** 4 August 2025

<details markdown="1">
<summary><b>Click to view Raw LaTeX Source</b></summary>

```latex

```

</details>

---

### [2025] A Falsifiable Prediction of Non-Gaussian Tails in the CMB from Timeless Quantum Physics
*   **DOI:** [10.5281/zenodo.16730256](https://doi.org/10.5281/zenodo.16730256)
*   **Date:** 3 August 2025

<details markdown="1">
<summary><b>Click to view Raw LaTeX Source</b></summary>

```latex

```

</details>

---

### [2025] Falsifiable Prediction of Horizon-Scale Phase Shifts in Gravitational Waves from the Timeless Light Model
*   **DOI:** [10.5281/zenodo.16730926](https://doi.org/10.5281/zenodo.16730926)
*   **Date:** 3 August 2025

<details markdown="1">
<summary><b>Click to view Raw LaTeX Source</b></summary>

```latex

```

</details>

---

### [2025] Why the Timeless Light Model Deserves Scientific Consideration: A Foundational Framework with Derivations, Critiques, and Experimental Proposals
*   **DOI:** [10.5281/zenodo.16724187](https://doi.org/10.5281/zenodo.16724187)
*   **Date:** 2 August 2025

<details markdown="1">
<summary><b>Click to view Raw LaTeX Source</b></summary>

```latex

```

</details>

---

### [2025] Mass Imposes Delay, Wavefunctions Define Terrain: A Two-Filter Ontology of Reality
*   **DOI:** [10.5281/zenodo.16672398](https://doi.org/10.5281/zenodo.16672398)
*   **Date:** 1 August 2025

<details markdown="1">
<summary><b>Click to view Raw LaTeX Source</b></summary>

```latex

```

</details>

---

### [2025] No Carrier Needed: Photon Instructions as Direct Energy State Transfers Without Propagation
*   **DOI:** [10.5281/zenodo.16666652](https://doi.org/10.5281/zenodo.16666652)
*   **Date:** 1 August 2025

<details markdown="1">
<summary><b>Click to view Raw LaTeX Source</b></summary>

```latex

```

</details>

---

### [2025] Light as Absent: Reclassifying the Photon as a Timeless Instruction
*   **DOI:** [10.5281/zenodo.16627550](https://doi.org/10.5281/zenodo.16627550)
*   **Date:** 31 July 2025

<details markdown="1">
<summary><b>Click to view Raw LaTeX Source</b></summary>

```latex

```

</details>

---

### [2025] Deriving Cornerstone Equations from TLM Axioms: Entropic Bridges to GR and QM
*   **DOI:** [10.5281/zenodo.16596589](https://doi.org/10.5281/zenodo.16596589)
*   **Date:** 30 July 2025

<details markdown="1">
<summary><b>Click to view Raw LaTeX Source</b></summary>

```latex

```

</details>

---

### [2025] Resolving Wave-Particle Duality Through the Proposed Timeless Light Model: Photons as Timeless Instructions and Waves as Deployed Delay
*   **DOI:** [10.5281/zenodo.16510862](https://doi.org/10.5281/zenodo.16510862)
*   **Date:** 28 July 2025

<details markdown="1">
<summary><b>Click to view Raw LaTeX Source</b></summary>

```latex

```

</details>

---

### [2025] Photon Out of Time: Why Light Experiences No Time—and What That Means for Physics
*   **DOI:** [10.5281/zenodo.16479322](https://doi.org/10.5281/zenodo.16479322)
*   **Date:** 27 July 2025

<details markdown="1">
<summary><b>Click to view Raw LaTeX Source</b></summary>

```latex

```

</details>

---

### [2025] Spacelessness as a Consequence of Timelessness in the Quantum Platform of the Timeless Light Model
*   **DOI:** [10.5281/zenodo.16350754](https://doi.org/10.5281/zenodo.16350754)
*   **Date:** 23 July 2025

<details markdown="1">
<summary><b>Click to view Raw LaTeX Source</b></summary>

```latex

```

</details>

---

### [2025] Stop Pretending General Relativity Is Conservative: Why Timeless Models Deserve a Seat at the Table
*   **DOI:** [10.5281/zenodo.16261059](https://doi.org/10.5281/zenodo.16261059)
*   **Date:** 21 July 2025

<details markdown="1">
<summary><b>Click to view Raw LaTeX Source</b></summary>

```latex

```

</details>

---

### [2025] Foundational Equations and Axiomatic Structure of the Timeless Light Model: A Synthesis Across Sixty Papers and Working Notes
*   **DOI:** [10.5281/zenodo.16187719](https://doi.org/10.5281/zenodo.16187719)
*   **Date:** 20 July 2025

<details markdown="1">
<summary><b>Click to view Raw LaTeX Source</b></summary>

```latex

```

</details>

---

### [2025] The Photon's Exile: A GR-Based Proof That Light Is Not in Spacetime
*   **DOI:** [10.5281/zenodo.16076902](https://doi.org/10.5281/zenodo.16076902)
*   **Date:** 18 July 2025

<details markdown="1">
<summary><b>Click to view Raw LaTeX Source</b></summary>

```latex

```

</details>

---

### [2025] Unified Physics by Subordination of GR to QM: Version 4.0 – Instructional Photons and Causal Rendering
*   **DOI:** [10.5281/zenodo.16019797](https://doi.org/10.5281/zenodo.16019797)
*   **Date:** 17 July 2025

<details markdown="1">
<summary><b>Click to view Raw LaTeX Source</b></summary>

```latex

```

</details>

---

### [2025] Quantum Platform as Causal Senior: General Relativity as Rendered Projection
*   **DOI:** [10.5281/zenodo.15960343](https://doi.org/10.5281/zenodo.15960343)
*   **Date:** 16 July 2025

<details markdown="1">
<summary><b>Click to view Raw LaTeX Source</b></summary>

```latex

```

</details>

---

### [2025] Unified Physics by Subordination of GR to QM: A Layered Reality Framework
*   **DOI:** [10.5281/zenodo.15956986](https://doi.org/10.5281/zenodo.15956986)
*   **Date:** 16 July 2025

<details markdown="1">
<summary><b>Click to view Raw LaTeX Source</b></summary>

```latex

```

</details>

---

### [2025] Unified Physics by Subordination of GR to QM: Quantum Phenomena as the Generator of the Classical Universe
*   **DOI:** [10.5281/zenodo.15868624](https://doi.org/10.5281/zenodo.15868624)
*   **Date:** 12 July 2025

<details markdown="1">
<summary><b>Click to view Raw LaTeX Source</b></summary>

```latex

```

</details>

---

### [2025] Causality Without Light Speed: Reframing c as Structure, Not Law
*   **DOI:** [10.5281/zenodo.15826480](https://doi.org/10.5281/zenodo.15826480)
*   **Date:** 7 July 2025

<details markdown="1">
<summary><b>Click to view Raw LaTeX Source</b></summary>

```latex

```

</details>

---

### [2025] Clarifying Cs: Deployment Rate, Delay, and Simulation Parameters in the Timeless Light Model
*   **DOI:** [10.5281/zenodo.15817350](https://doi.org/10.5281/zenodo.15817350)
*   **Date:** 6 July 2025

<details markdown="1">
<summary><b>Click to view Raw LaTeX Source</b></summary>

```latex

```

</details>

---

### [2025] Causal Instruction Arcs and the Timeless Light Model: A Unified Framework for Physics and Cosmology
*   **DOI:** [10.5281/zenodo.15813253](https://doi.org/10.5281/zenodo.15813253)
*   **Date:** 5 July 2025

<details markdown="1">
<summary><b>Click to view Raw LaTeX Source</b></summary>

```latex

```

</details>

---

### [2025] Gravitational Waves as Synchronization Events: A Testable Prediction from the Timeless Light Model
*   **DOI:** [10.5281/zenodo.15770287](https://doi.org/10.5281/zenodo.15770287)
*   **Date:** 29 June 2025

<details markdown="1">
<summary><b>Click to view Raw LaTeX Source</b></summary>

```latex

```

</details>

---

### [2025] Observer-Dependent Spacetime Collapse as a Relational Artifact of the Spacetime Deployment Frame
*   **DOI:** [10.5281/zenodo.15770329](https://doi.org/10.5281/zenodo.15770329)
*   **Date:** 29 June 2025

<details markdown="1">
<summary><b>Click to view Raw LaTeX Source</b></summary>

```latex

```

</details>

---

### [2025] On a Postulated Mass-Time Action Principle: A Novel Approach to Quantum Gravity
*   **DOI:** [10.5281/zenodo.15770207](https://doi.org/10.5281/zenodo.15770207)
*   **Date:** 29 June 2025

<details markdown="1">
<summary><b>Click to view Raw LaTeX Source</b></summary>

```latex

```

</details>

---

### [2025] The Mass-Time Invariant: A Causal Reinterpretation of Relativistic Spacetime Conservation Laws
*   **DOI:** [10.5281/zenodo.15769918](https://doi.org/10.5281/zenodo.15769918)
*   **Date:** 29 June 2025

<details markdown="1">
<summary><b>Click to view Raw LaTeX Source</b></summary>

```latex

```

</details>

---

### [2025] The Principle of Delayed Resolution: A Teleological Framework for Unifying Physical Mechanics
*   **DOI:** [10.2139/ssrn.5310483](https://doi.org/10.2139/ssrn.5310483)
*   **Date:** 26 June 2025

<details markdown="1">
<summary><b>Click to view Raw LaTeX Source</b></summary>

```latex

```

</details>

---

### [2025] DELAY TO C: A Fundamental Law Unifying Physics — Paper and Video Transcript
*   **DOI:** [10.5281/zenodo.17392978](https://doi.org/10.5281/zenodo.17392978)
*   **Date:** 22 June 2025

<details markdown="1">
<summary><b>Click to view Raw LaTeX Source</b></summary>

```latex

```

</details>
{% endraw %}

---
