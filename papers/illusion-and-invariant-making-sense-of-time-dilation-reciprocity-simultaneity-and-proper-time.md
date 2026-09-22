---
layout: default
title: '[2025] Illusion and Invariant: Making Sense of Time Dilation — Reciprocity, Simultaneity, and Proper Time'
description: 'Publication metadata and archived raw LaTeX source by John C. W. McKinley.'
permalink: /papers/illusion-and-invariant-making-sense-of-time-dilation-reciprocity-simultaneity-and-proper-time/
paper: true
---
{% raw %}
# [2025] Illusion and Invariant: Making Sense of Time Dilation — Reciprocity, Simultaneity, and Proper Time
*   **DOI:** [10.5281/zenodo.17083276](https://doi.org/10.5281/zenodo.17083276)
*   **Date:** 8 September 2025

<details markdown="1">
<summary><b>Click to view Raw LaTeX Source</b></summary>

```latex
\documentclass[12pt,letterpaper]{article}

% ------- Packages -------
\usepackage[margin=1in]{geometry}
\usepackage[T1]{fontenc}
\usepackage[utf8]{inputenc}
\usepackage{lmodern}
\usepackage{microtype}
\usepackage{amsmath,amssymb,amsthm,mathtools}
\usepackage{enumitem}
\usepackage[most]{tcolorbox}
\tcbset{colback=gray!5,colframe=black,boxrule=0.6pt,arc=2mm}
\newtcolorbox{conceptbox}[1]{breakable,title={#1},fonttitle=\bfseries}
\newtcolorbox{notebox}[1]{breakable,title={#1},fonttitle=\bfseries}

\usepackage{hyperref}
\hypersetup{colorlinks=true,linkcolor=blue,urlcolor=blue,citecolor=blue}
\usepackage{orcidlink}

% ====== Theorems/Defs (optional if needed) ======
\newtheorem{definition}{Definition}
\newtheorem{proposition}{Proposition}

%------ Metadata -------
\title{Illusion and Invariant: Making Sense of Time Dilation\\\large Reciprocity, Simultaneity, and Proper Time}
\author{John C. W. McKinley\orcidlink{0009-0005-7097-5035}\\Independent Researcher}
\date{September 8, 2025}

\begin{document}
\maketitle

\begingroup
  \footnotetext[0]{This version published at
  \href{https://doi.org/10.5281/zenodo.17083276}{https://doi.org/10.5281/zenodo.17083276}.}
\endgroup

\begin{abstract}
A recurring conceptual snag in special relativity is that each inertial observer sees the other's clock as running slow during separation, yet a real, permanent age difference can appear at reunion. This paper explains why there is no paradox. The symmetric ``your clock is slow'' statements are \emph{frame-dependent} comparisons tied to different simultaneity conventions, whereas the difference in accumulated time at reunion is a \emph{frame-invariant} proper-time integral along distinct worldlines. Acceleration does not enter the ideal-clock rate directly; instead, it \emph{enables} different spacetime paths between the same endpoints. A Doppler tick-count (Bondi \(k\)-calculus) example shows how both observers can independently account for the final difference without any simultaneity bookkeeping. Experimental evidence is summarized.
\end{abstract}

\begin{conceptbox}{Executive summary (three lines)}
\textbf{(1)} ``Your clock is slow'' while coasting is a \emph{frame choice}, not missing seconds.\\
\textbf{(2)} Changing speed rotates your personal ``now'' across distance (a tilted slice).\\
\textbf{(3)} The permanent difference comes from \emph{different worldlines}. Acceleration (or gravity-assisted turning) \emph{enables} different paths; the proper-time integral \emph{decides} the outcome.
\end{conceptbox}

\paragraph{Companion note (the ``what'' paper).}
For a compact treatment of \emph{what} slows time (gravitational potential and speed), see the companion paper \emph{Mass Slows Time. Speed Slows Time.} \cite{mckinleyMass2025}. Here we focus on \emph{why} symmetry in-flight coexists with an invariant, permanent result at reunion.

\section{Scope}
We work in flat spacetime (special relativity). Gravitational effects can be included separately (see \cite{mckinleyMass2025}); they do not alter the logic here: the in-flight, reciprocal comparisons are about simultaneity conventions, whereas the reunion result is the path-dependent, frame-invariant proper time.

\section{Symmetry in Flight: What the Reciprocity Really Says}
When two inertial observers, \(A\) and \(B\), pass and then coast apart:
\begin{itemize}[leftmargin=1.25em]
  \item In \(A\)'s inertial frame, distant events judged ``simultaneous'' with \(A\)'s now are paired using \(A\)'s Einstein-synchronized lattice. With that pairing, \(B\)'s moving clock is found to \emph{run slow}.
  \item In \(B\)'s inertial frame, the same logic applies with \(B\)'s simultaneity convention, and \(A\)'s clock is found to \emph{run slow}.
\end{itemize}
There is no contradiction because these are \emph{different pairings of distant events}. They are statements about \emph{comparisons} across space, not about physically removing seconds from anyone's wristwatch.

\section{Invariant at Reunion: Proper Time as Path Length}
For an ideal clock with speed \(v(t)\) in some inertial chart \(t\),
\begin{equation}
\label{eq:proper-time}
d\tau = dt\,\sqrt{1-\frac{v(t)^2}{c^2}}, \qquad
\Delta\tau = \int_{A}^{B} dt\,\sqrt{1-\frac{v(t)^2}{c^2}}.
\end{equation}
The integral \(\Delta\tau\) is a Lorentz scalar: all observers agree on each clock's final reading when the clocks are \emph{co-located} again at \(B\). Acceleration does not appear explicitly in \eqref{eq:proper-time} (clock postulate); it matters only insofar as it changes the velocity history---i.e., which worldline is taken between \(A\) and \(B\).

\section{Simultaneity as a Tilted Slice (and Turnaround as a Rotation)}
\label{sec:tilted}
Let time be vertical and space horizontal. In your rest frame, your ``now'' is a horizontal slice. In a frame moving relative to you, the ``now'' slice is \emph{tilted}. If you change speed (turnaround), the slice you call ``now'' \emph{rotates} across distant events.

\begin{figure}[h!]
\centering
\begin{verbatim}
t ^
  |   inbound-now  /            (your "now" rotates when you change speed)
  |               /
  |  outbound-now/______
  +----------------------------> x
\end{verbatim}
\caption{Relativity of simultaneity. Changing velocity changes which distant events you label as ``now.'' This resolves the reciprocity without touching anyone's wristwatch.}
\label{fig:tilted-slice}
\end{figure}

This picture explains why the traveler can reassign large swaths of distant ``now'' at turnaround, reconciling each leg's reciprocal ``slow/slow'' judgments with the final, invariant proper-time difference.

\section{Worked Example: Bondi Tick-Counting (No Simultaneity Needed)}
\label{sec:bondi}
Consider a symmetric out-and-back at speed \(v=\beta c\), with outbound and inbound Earth-frame durations both \(T\). Define
\[
\gamma=\frac{1}{\sqrt{1-\beta^2}},\qquad
k=\sqrt{\frac{1+\beta}{1-\beta}}.
\]
Let the traveler \(B\) emit a beep train at proper rate \(f_0\). Earth receives the beeps with relativistic Doppler factors:
\begin{itemize}[leftmargin=1.25em]
  \item During recession (before the turnaround signal arrives), the received rate is \(f_0/k\) for a received interval of \(R_{\text{recede}}=T(1+\beta)\).
  \item During approach, the received rate is \(k f_0\) for \(R_{\text{approach}}=T(1-\beta)\).
\end{itemize}
Total beeps received at Earth:
\begin{align}
N_{A\leftarrow B}
&=\left(\frac{R_{\text{recede}}}{k}+k\,R_{\text{approach}}\right)f_0
= \left(\frac{T(1+\beta)}{k}+k\,T(1-\beta)\right)f_0 \nonumber\\
&= 2T\,\sqrt{1-\beta^2}\,f_0
= \frac{2T}{\gamma}\,f_0
= \Delta\tau_B f_0. \label{eq:bondi-earth}
\end{align}
Thus Earth can infer the traveler's \(\Delta\tau_B\) by \emph{counting beeps}---no simultaneity grids required. Symmetrically,
\begin{equation}
N_{B\leftarrow A} = \Delta\tau_A f_0,
\end{equation}
so each party's tick-count integrates to the other's proper time. For a concrete choice \(\beta=0.8\), \(T=5~\mathrm{y}\), one finds \(\gamma=5/3\), \(k=3\), \(\Delta\tau_A=10~\mathrm{y}\), \(\Delta\tau_B=6~\mathrm{y}\).

\section{Acceleration: The Enabler, Not the Rate Law}
The ideal-clock rate depends on instantaneous speed, not acceleration. However, to \emph{reunite} after different inertial legs, at least one worldline must include non-inertial segments (thrust, brake, gravity assist). Those segments \emph{enable} different paths between the same endpoints. In flat spacetime, the straight inertial worldline between fixed events maximizes proper time; bent paths accumulate less.

\section{Evidence}
The symmetry picture and the reunion invariant are both strongly supported:
\begin{itemize}[leftmargin=1.25em]
  \item \textbf{Transverse Doppler / time dilation:} Ives--Stilwell and storage-ring muon experiments confirm the \(\gamma\) factor \cite{ives1938,bailey1977}.
  \item \textbf{Transported clocks:} Hafele--Keating and GNSS practice show kinematic and gravitational effects combine as expected; final co-located clock readings match predictions \cite{hafele1972,ashby2003,vessot1980}.
\end{itemize}

\section{Conclusion}
There is no paradox. The reciprocal ``slow/slow'' statements during separation are frame-dependent comparisons that hinge on simultaneity conventions; the reunion difference is an invariant proper-time integral. Acceleration does not directly slow an ideal clock; it selects a different spacetime path. Tick-counting shows how both observers can predict the same permanent result without any simultaneity grids.

\section*{Acknowledgments}
Thanks to readers who suggested using the three-line summary and tilted-slice diagram as a compact resolution tool across audiences.

\begin{thebibliography}{99}

\bibitem{einstein1905}
A. Einstein, Zur Elektrodynamik bewegter K\"{o}rper (On the Electrodynamics of Moving Bodies), \emph{Annalen der Physik} \textbf{17}, 891--921 (1905). \href{https://doi.org/10.1002/andp.19053221004}{doi:10.1002/andp.19053221004}.

\bibitem{minkowski1908}
H. Minkowski, Raum und Zeit (Space and Time), (1908/1909).

\bibitem{bondi1964}
H. Bondi, \emph{Relativity and Common Sense}, Heinemann (1964).

\bibitem{ives1938}
H. E. Ives and G. R. Stilwell, An experimental study of the rate of a moving atomic clock, \emph{JOSA} \textbf{28}, 215--226 (1938). \href{https://doi.org/10.1364/JOSA.28.000215}{doi:10.1364/JOSA.28.000215}.

\bibitem{bailey1977}
J. Bailey et al., Measurements of relativistic time dilation for positive and negative muons in a circular orbit, \emph{Nature} \textbf{268}, 301--305 (1977). \href{https://doi.org/10.1038/268301a0}{doi:10.1038/268301a0}.

\bibitem{hafele1972}
J. C. Hafele and R. E. Keating, Around-the-World Atomic Clocks: Observed Relativistic Time Gains, \emph{Science} \textbf{177}, 168--170 (1972). \href{https://doi.org/10.1126/science.177.4044.168}{doi:10.1126/science.177.4044.168}.

\bibitem{ashby2003}
N. Ashby, Relativity in the Global Positioning System, \emph{Living Reviews in Relativity} \textbf{6} (2003). \href{https://doi.org/10.12942/lrr-2003-1}{doi:10.12942/lrr-2003-1}.

\bibitem{vessot1980}
R. F. C. Vessot and M. W. Levine, Test of relativistic gravitation with a space-borne hydrogen maser, \emph{Physical Review Letters} 45, 2081--2084 (1980). \href{https://doi.org/10.1103/PhysRevLett.45.2081}{doi:10.1103/PhysRevLett.45.2081}.


% Companion paper (the "what" paper)
\bibitem{mckinleyMass2025}
J. C. W. McKinley, \emph{Mass Slows Time. Speed Slows Time. Concept, Derivations, and Evidence}, Zenodo (2025). \href{https://doi.org/10.5281/zenodo.17083288}{doi:10.5281/zenodo.17083288}.

\end{thebibliography}

\end{document}
```

</details>

---
{% endraw %}
