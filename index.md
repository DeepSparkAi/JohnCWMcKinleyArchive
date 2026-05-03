---
layout: default
title: John Christian William McKinley LaTeX Archive
render_with_liquid: false
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

```

</details>

---

### [2026] Retrocausal Objections Are Disallowed for the Photon
*   **DOI:** [10.5281/zenodo.19648209](https://doi.org/10.5281/zenodo.19648209)
*   **Date:** 18 April 2026

<details markdown="1">
<summary><b>Click to view Raw LaTeX Source</b></summary>

```latex

```

</details>

---

### [2026] Iron Filings Do Not Prove Field Substance — A Short Interpretive No-Go
*   **DOI:** [10.5281/zenodo.19639455](https://doi.org/10.5281/zenodo.19639455)
*   **Date:** 17 April 2026

<details markdown="1">
<summary><b>Click to view Raw LaTeX Source</b></summary>

```latex

```

</details>

---

### [2026] Wavefunction Prediction Does Not License a Photon Path — A Short Interpretive No-Go
*   **DOI:** [10.5281/zenodo.19504772](https://doi.org/10.5281/zenodo.19504772)
*   **Date:** 12 April 2026

<details markdown="1">
<summary><b>Click to view Raw LaTeX Source</b></summary>

```latex

```

</details>

---

### [2026] No Closed Physical System Internally Fixes the Onset and Direction of a New Causal Chain
*   **DOI:** [10.5281/zenodo.19464781](https://doi.org/10.5281/zenodo.19464781)
*   **Date:** 7 April 2026

<details markdown="1">
<summary><b>Click to view Raw LaTeX Source</b></summary>

```latex

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

```

</details>

---

### [2025] Taking Null Proper Time Seriously: An Interpretive Clarification of Null Proper Time
*   **DOI:** [10.5281/zenodo.18004632](https://doi.org/10.5281/zenodo.18004632)
*   **Date:** 22 December 2025

<details markdown="1">
<summary><b>Click to view Raw LaTeX Source</b></summary>

```latex

```

</details>

---

### [2025] No Rest Frame, No Persistence: A Kinematic Constraint on Photon Interpretation
*   **DOI:** [10.5281/zenodo.18005884](https://doi.org/10.5281/zenodo.18005884)
*   **Date:** 21 December 2025

<details markdown="1">
<summary><b>Click to view Raw LaTeX Source</b></summary>

```latex

```

</details>

---

### [2025] The Timeless Light Model: A Minimal Interpretive Completion of Relativistic Constraints
*   **DOI:** [10.5281/zenodo.18012564](https://doi.org/10.5281/zenodo.18012564)
*   **Date:** 21 December 2025

<details markdown="1">
<summary><b>Click to view Raw LaTeX Source</b></summary>

```latex

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

---
