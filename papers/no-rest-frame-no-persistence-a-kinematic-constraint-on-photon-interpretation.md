---
layout: default
title: '[2025] No Rest Frame, No Persistence: A Kinematic Constraint on Photon Interpretation'
description: 'Publication metadata and archived raw LaTeX source by John C. W. McKinley.'
permalink: /papers/no-rest-frame-no-persistence-a-kinematic-constraint-on-photon-interpretation/
paper: true
---
{% raw %}
# [2025] No Rest Frame, No Persistence: A Kinematic Constraint on Photon Interpretation
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
{% endraw %}
