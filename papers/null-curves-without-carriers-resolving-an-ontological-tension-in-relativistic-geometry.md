---
layout: default
title: '[2025] Null Curves Without Carriers: Resolving an Ontological Tension in Relativistic Geometry'
description: 'Publication metadata and archived raw LaTeX source by John C. W. McKinley.'
permalink: /papers/null-curves-without-carriers-resolving-an-ontological-tension-in-relativistic-geometry/
paper: true
---
{% raw %}
# [2025] Null Curves Without Carriers: Resolving an Ontological Tension in Relativistic Geometry
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
{% endraw %}
