---
layout: default
title: '[2026] Vacuum Is Not Frame-Independent: A Short Interpretive No-Go on Absolute Emptiness in Quantum Field Theory'
description: 'Publication metadata and archived raw LaTeX source by John C. W. McKinley.'
permalink: /papers/vacuum-is-not-frame-independent-a-short-interpretive-no-go-on-absolute-emptiness-in-quantum/
paper: true
---
{% raw %}
# [2026] Vacuum Is Not Frame-Independent: A Short Interpretive No-Go on Absolute Emptiness in Quantum Field Theory
*   **DOI:** [10.5281/zenodo.20100426](https://doi.org/10.5281/zenodo.20100426)
*   **Date:** 9 May 2026

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

\PassOptionsToPackage{capitalise,nameinlink,noabbrev}{cleveref}
\usepackage[numbers,sort&compress]{natbib}
\usepackage[colorlinks=true,linkcolor=blue,citecolor=blue,urlcolor=blue]{hyperref}
\newcommand{\doi}[1]{\href{https://doi.org/#1}{#1}}
\usepackage{cleveref}
\usepackage{orcidlink}
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
\lhead{Vacuum Is Not Frame-Independent}
\rhead{John C. W. McKinley}
\cfoot{\thepage}

\newtheorem{proposition}{Proposition}[section]
\newtheorem{definition}[proposition]{Definition}
\newtheorem{remark}[proposition]{Remark}
\newtheorem{corollary}[proposition]{Corollary}

\title{\textbf{Vacuum Is Not Frame-Independent}\\
\large A Short Interpretive No-Go on Absolute Emptiness in Quantum Field Theory}
\author{John C. W. McKinley \orcidlink{0009-0005-7097-5035}}
\date{May 9, 2026}

\begin{document}

\maketitle

\blfootnote{\scriptsize This version prepared for Zenodo. DOI: \href{https://doi.org/10.5281/zenodo.20100426}{10.5281/zenodo.20100426}.}

\begin{abstract}
The vacuum of quantum field theory is often described as empty space. This note states a narrow interpretive no-go result: vacuum is not a frame-independent inventory of absence. In quantum field theory, particle content is defined relative to a mode decomposition, and the positive-frequency splitting that defines that decomposition depends on a time parameter. Observers with inequivalent time descriptions can therefore disagree about whether a field state is vacuum or thermally populated. The Unruh and Hawking effects make this structure explicit. This does not show that particles are secretly present in the vacuum; it shows that particle content is not absolute. Vacuum is a frame-relative field-state assignment, not an observer-independent ontology of emptiness.
\end{abstract}

\section{Introduction}

Vacuum is often treated as the physical name for nothing being there. That description is too strong.

In quantum field theory, vacuum is not an observer-independent inventory of absolute emptiness. It is the state annihilated by a chosen set of annihilation operators, and those operators are defined only after a field has been decomposed into modes. The mode decomposition depends on a positive-frequency splitting. The positive-frequency splitting depends on a time description.

The claim of this note is narrow. It does not deny the usefulness of vacuum states. It does not deny the success of quantum field theory. It does not claim that vacuum is arbitrary. It denies only the stronger ontological inference that a vacuum assignment licenses an absolute statement that no particles are present, independent of frame, observer, or time parameter.

This no-go matters because several central effects in quantum field theory on curved or non-inertial backgrounds depend precisely on the non-absoluteness of particle content. The Unruh effect shows that an accelerated observer assigns thermal particle content to the inertial vacuum. Hawking radiation shows that a state vacuum-like in an early description can appear thermally populated to late-time exterior observers. These are not anomalies. They are consequences of how particle content is defined.

The no-go is simple:

\begin{quote}
No frame-relative vacuum definition licenses an observer-independent ontology of emptiness.
\end{quote}

\section{Field Modes and Vacuum}

For a free scalar field, one commonly expands the field operator in a set of modes,
\[
\hat{\phi}(x)=\sum_k \left(a_k u_k(x)+a_k^\dagger u_k^*(x)\right),
\]
where the choice of mode functions \(u_k\) fixes the annihilation and creation operators associated with that decomposition.

The vacuum associated with this decomposition is the state \(|0\rangle\) satisfying
\[
a_k |0\rangle = 0
\]
for all \(k\). This definition is precise. It is also basis-dependent. A different mode decomposition gives a different set of annihilation operators. A state annihilated by one set of operators need not be annihilated by another.

This is not a technical nuisance. It is the central point. In quantum field theory, particle content is derivative of a chosen representation of the field. It is not a primitive inventory of localized objects.

Positive-frequency modes are selected relative to a time parameter. If two observers, coordinate systems, or asymptotic regimes define inequivalent positive-frequency splittings, then they need not agree about particle content. A state described as vacuum in one decomposition can be described as populated in another.

\section{Definitions}

\begin{definition}[Mode decomposition]
A mode decomposition is a representation of a quantum field in terms of a chosen set of mode functions together with associated creation and annihilation operators.
\end{definition}

\begin{definition}[Positive-frequency splitting]
A positive-frequency splitting is the division of field modes into positive- and negative-frequency components relative to a chosen time parameter or time-translation structure.
\end{definition}

\begin{definition}[Vacuum state]
A vacuum state is a state annihilated by the annihilation operators associated with a particular mode decomposition.
\end{definition}

\begin{definition}[Frame-independent emptiness]
Frame-independent emptiness is the claim that a vacuum assignment establishes an observer-independent fact that no particles are present, independently of the mode decomposition or time description used.
\end{definition}

\section{The No-Go Result}

\begin{proposition}[Vacuum requires a mode decomposition]\label{proposition:vacuum-mode}
In quantum field theory, a vacuum state is defined relative to a chosen mode decomposition.
\end{proposition}

\begin{proof}
A vacuum state is specified by the condition that it is annihilated by a set of annihilation operators. Those annihilation operators are obtained only after a field has been decomposed into modes. Without the chosen decomposition, there is no fixed set of annihilation operators relative to which the vacuum condition can be stated. Therefore vacuum requires a mode decomposition.
\end{proof}

\begin{proposition}[Mode decomposition requires a time description]\label{proposition:mode-time}
A positive-frequency mode decomposition requires a time parameter or equivalent time-translation structure.
\end{proposition}

\begin{proof}
The distinction between positive and negative frequency is a distinction concerning oscillation with respect to time. To say that a mode has positive frequency is to define its temporal behavior relative to a time parameter or time-translation symmetry. If the time description changes in an inequivalent way, the positive-frequency splitting can change as well. Therefore a mode decomposition that depends on positive frequency requires a time description.
\end{proof}

\begin{proposition}[Inequivalent time descriptions can produce inequivalent vacua]\label{proposition:inequivalent-vacua}
Observers or regimes using inequivalent time descriptions need not agree on which state is vacuum.
\end{proposition}

\begin{proof}
Let one observer define annihilation operators \(a_k\) from one positive-frequency splitting, and let another define annihilation operators \(b_j\) from an inequivalent splitting. The two sets of operators can be related by a Bogoliubov transformation,
\[
b_j = \sum_k \left(\alpha_{jk} a_k + \beta_{jk} a_k^\dagger\right).
\]
If any \(\beta_{jk}\) coefficient is nonzero, then the state annihilated by all \(a_k\) is not generally annihilated by all \(b_j\). Thus a state vacuum for one decomposition can contain particles relative to another. Therefore inequivalent time descriptions can produce inequivalent vacua.
\end{proof}

\begin{proposition}[Vacuum disagreement is not a contradiction]\label{proposition:disagreement-not-contradiction}
If one observer assigns vacuum and another assigns particle content to the same field state, the disagreement is not a contradiction when their mode decompositions are inequivalent.
\end{proposition}

\begin{proof}
The two assignments answer different decomposition-relative questions. One asks whether the state is annihilated by one set of annihilation operators. The other asks whether it is annihilated by another. If the two decompositions are inequivalent, the answers need not agree. Since the predicate ``vacuum'' is being applied relative to different structures, the disagreement is not a logical contradiction. It is a feature of the formalism.
\end{proof}

\begin{proposition}[Vacuum does not license absolute emptiness ontology]\label{proposition:no-absolute-emptiness}
A vacuum assignment does not, by itself, establish frame-independent emptiness.
\end{proposition}

\begin{proof}
By \Cref{proposition:vacuum-mode}, vacuum requires a mode decomposition. By \Cref{proposition:mode-time}, that decomposition depends on a time description. By \Cref{proposition:inequivalent-vacua}, inequivalent time descriptions can produce inequivalent vacuum assignments. Therefore the statement that a state is vacuum is not, by itself, an observer-independent statement that no particles are present absolutely. It is a statement made relative to a decomposition. Thus vacuum does not license absolute emptiness ontology.
\end{proof}

\section{Examples: Unruh and Hawking}

The Unruh effect gives the cleanest example. An inertial observer describes the Minkowski vacuum as empty. A uniformly accelerated observer assigns thermal particle content to that same state, with temperature
\[
T_U=\frac{\hbar a}{2\pi c k_B}.
\]
The difference is not that one observer has found hidden particles sitting inside the vacuum. The difference is that the accelerated observer uses a different time description and therefore a different mode decomposition.

Hawking radiation gives the curved-spacetime version. A field state that is vacuum relative to an early asymptotic description need not be vacuum relative to the late-time exterior mode basis of a black-hole spacetime. The mismatch between early and late mode decompositions produces the thermal exterior result,
\[
T_H=\frac{\hbar c^3}{8\pi G M k_B}.
\]
Again, the lesson is not that particles were secretly waiting in the vacuum as localized objects. The lesson is that particle content is assigned relative to the relevant mode decomposition.

Both examples display the same interpretive restriction:

\begin{quote}
Vacuum is a frame-relative field-state assignment, not an absolute ontology of nothingness.
\end{quote}

\section{Conclusion}

Vacuum is not frame-independent emptiness.

Quantum field theory defines vacuum through annihilation operators, and annihilation operators are fixed by a mode decomposition. Since positive-frequency splitting depends on a time description, inequivalent time descriptions can yield inequivalent particle assignments. This is why one observer can describe a state as vacuum while another describes it as thermally populated.

The no-go result is therefore narrow but important. A vacuum assignment is a legitimate statement within a chosen field representation. It is not, by itself, a license to infer observer-independent absence. Absolute emptiness is stronger than the formalism supplies.

Vacuum is a frame-relative field-state assignment. It is not an absolute ontology of nothingness.

\begin{thebibliography}{9}

\bibitem[Fulling(1973)]{Fulling1973}
S.~A. Fulling.
\newblock Nonuniqueness of canonical field quantization in Riemannian space-time.
\newblock \emph{Physical Review D} \textbf{7}, 2850--2862 (1973).
\newblock \doi{10.1103/PhysRevD.7.2850}.

\bibitem[Davies(1975)]{Davies1975}
P.~C.~W. Davies.
\newblock Scalar particle production in Schwarzschild and Rindler metrics.
\newblock \emph{Journal of Physics A: Mathematical and General} \textbf{8}, 609--616 (1975).
\newblock \doi{10.1088/0305-4470/8/4/022}.

\bibitem[Hawking(1975)]{Hawking1975}
S.~W. Hawking.
\newblock Particle creation by black holes.
\newblock \emph{Communications in Mathematical Physics} \textbf{43}, 199--220 (1975).
\newblock \doi{10.1007/BF02345020}.

\bibitem[Unruh(1976)]{Unruh1976}
W.~G. Unruh.
\newblock Notes on black-hole evaporation.
\newblock \emph{Physical Review D} \textbf{14}, 870--892 (1976).
\newblock \doi{10.1103/PhysRevD.14.870}.

\bibitem[Birrell and Davies(1982)]{BirrellDavies1982}
N.~D. Birrell and P.~C.~W. Davies.
\newblock \emph{Quantum Fields in Curved Space}.
\newblock Cambridge University Press (1982).

\end{thebibliography}

\end{document}
```

</details>

---
{% endraw %}
