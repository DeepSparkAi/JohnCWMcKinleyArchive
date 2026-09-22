---
layout: default
title: '[2025] Taking Null Proper Time Seriously: An Interpretive Clarification of Null Proper Time'
description: 'Publication metadata and archived raw LaTeX source by John C. W. McKinley.'
permalink: /papers/taking-null-proper-time-seriously-an-interpretive-clarification-of-null-proper-time/
paper: true
---
{% raw %}
# [2025] Taking Null Proper Time Seriously: An Interpretive Clarification of Null Proper Time
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
{% endraw %}
