---
layout: default
title: '[2025] Mass Slows Time. Speed Slows Time. Concept, Derivations, and Evidence'
description: 'Publication metadata and archived raw LaTeX source by John C. W. McKinley.'
permalink: /papers/mass-slows-time-speed-slows-time-concept-derivations-and-evidence/
paper: true
---
{% raw %}
# [2025] Mass Slows Time. Speed Slows Time. Concept, Derivations, and Evidence
*   **DOI:** [10.5281/zenodo.17083288](https://doi.org/10.5281/zenodo.17083288)
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
\newtcolorbox{axiombox}[1]{breakable,title={#1},fonttitle=\bfseries}
\newtcolorbox{notebox}[1]{breakable,title={#1},fonttitle=\bfseries}

\usepackage{hyperref}
\hypersetup{colorlinks=true,linkcolor=blue,urlcolor=blue,citecolor=blue}
\usepackage{orcidlink}

% ====== Theorems/Defs ======
\newtheorem{definition}{Definition}
\newtheorem{postulate}{Postulate}
\newtheorem{proposition}{Proposition}
\newtheorem{lemma}{Lemma}
\newtheorem{theorem}{Theorem}

%------ Metadata -------
\title{Mass Slows Time. Speed Slows Time.\\Concept, Derivations, and Evidence}
\author{John C. W. McKinley\orcidlink{0009-0005-7097-5035}\\Independent Researcher}
\date{September 8, 2025}

\begin{document}
\maketitle

\begingroup
  \footnotetext[0]{This version published at
  \href{https://doi.org/10.5281/zenodo.17083288}{https://doi.org/10.5281/zenodo.17083288}.}
\endgroup

\begin{abstract}
Two operational rules tell you when a clock accrues less proper time than another: mass in your environment slows time, and speed slows time. We state these as axioms, then give compact but rigorous derivations from special and general relativity, plus weak-field limits used in metrology and navigation. A worked scenario shows how a traveler can go to the future by flying very fast near a massive body. Citations and DOIs point to the experimental record and standard references. 
Explanatory prose sections and a worked scenario are included to build intuition.
\end{abstract}

\section{Scope and Intent}
\label{sec:intent}
Your own wristwatch always feels normal. Differences in aging appear only when clocks that followed different worldlines are compared later. The equations below compute the proper time \( \tau \) accumulated along a path and therefore predict which conditions make a clock run slow \cite{einstein1905,will2014}.

\paragraph{Companion note.} For the symmetry question (why each inertial observer sees the other slow during separation, yet a permanent difference appears only at reunion), see the companion paper \emph{Illusion and Invariant: Making Sense of Time Dilation} \cite{mckinleyIllusion2025}. In brief: the in-flight comparison is frame-dependent; the reunion comparison is a path-dependent invariant.

\section{The Slogan}
\label{sec:slogan}
\begin{axiombox}{Gravitational potential slows time. Speed slows time.}
\textbf{Gravity (potential) slows time:} being deeper in an external gravitational potential makes a clock run slow relative to clocks higher up. It is the surrounding mass distribution (via the metric/potential) that matters. Your personal rest mass is not a knob on your own time \cite{poundrebka1960,vessot1980,shapiro1964}.

\medskip
\textbf{Speed slows time:} spending more of the trip at high speed (relative to the local static frame) yields less accumulated proper time when clocks are reunited and compared \cite{einstein1905,bailey1977,hafelekeating1972a,hafelekeating1972b}.
\end{axiombox}

\section{Immediate Corollaries}
\label{sec:corollaries}
\begin{itemize}[leftmargin=1.25em]
  \item \textbf{Stacking rule.} Mass and speed effects stack. Fast motion near mass slows time more than either alone \cite{ashby2003}.
  \item \textbf{Local normality.} No clock looks odd to its owner. Slowness is a comparison story, revealed at the reunion \cite{hafelekeating1972b}.
  \item \textbf{Path dependence.} Same start and end does not guarantee same age. The route you take sets how much time you keep \cite{hafelekeating1972a,hafelekeating1972b}.
  \item \textbf{No catch up.} A clock that fell behind does not surge ahead later. It only stops falling behind as quickly when the slowing conditions end.
  \item \textbf{Personal mass caveat.} Eating a sandwich or lifting weights does not slow your time by itself. Environment and motion do.
\end{itemize}

\section{Mathematical Foundations and Derivations}
\label{sec:derivations}

\subsection{Special relativity: kinematic time dilation}
\label{subsec:SR}
In flat spacetime with Minkowski metric, the infinitesimal proper time along a timelike worldline is
\begin{equation}
\label{eq:SRlineelement}
d\tau^2 = dt^2 \left( 1 - \frac{v^2}{c^2} \right),
\end{equation}
so for uniform \( v \) one obtains
\begin{equation}
\label{eq:SRdilation}
d\tau = \frac{dt}{\gamma}, \qquad \gamma = \frac{1}{\sqrt{1 - v^2/c^2}}.
\end{equation}

\noindent\textit{Path principle (SR):}\quad
\(\displaystyle \Delta\tau=\int_{A}^{B}\!dt\,\sqrt{1-\frac{v(t)^2}{c^2}}\).
Different \(v(t)\) histories between the same endpoints \((A,B)\) yield different \(\Delta\tau\).

Integrating gives \( \tau = \int dt/\gamma \): the moving clock accumulates less proper time than the rest clock, in agreement with storage-ring muon data \cite{einstein1905,bailey1977}.

\noindent\textit{Operational check:} Doppler tick-counting (Bondi \(k\)-calculus) reproduces the same \(\Delta\tau\) without simultaneity conventions (see the companion paper \cite{mckinleyIllusion2025}).

\subsection{General relativity: gravitational redshift and stationary clocks}
\label{subsec:GRstatic}
Outside a non-rotating spherical body, the Schwarzschild line element reads
\begin{equation}
\label{eq:schwarzschild}
ds^2 = -\left(1 - \frac{2GM}{rc^2}\right)c^2 dt^2 + \left(1 - \frac{2GM}{rc^2}\right)^{-1} dr^2 + r^2 \left(d\theta^2 + \sin^2\theta\, d\phi^2\right).
\end{equation}
For a stationary clock at fixed \( r,\theta,\phi \) (hovering with engines), \( dr=d\theta=d\phi=0 \), so
\begin{equation}
\label{eq:GRhover}
d\tau = dt\, \sqrt{\,1 - \frac{2GM}{rc^2}\,}.
\end{equation}
A clock deeper in the potential (smaller \( r \)) accrues less proper time than one at larger \( r \). This redshift was verified terrestrially (Pound--Rebka) and with a suborbital maser clock (GP-A) \cite{poundrebka1960,vessot1980,schwarzschild1916}.

\subsection{Motion in a gravitational field: circular orbits}
\label{subsec:GRcircular}
Confine motion to the equatorial plane \( \theta=\pi/2 \) and circular radius \( r=\mathrm{const} \). With angular rate \( \Omega = d\phi/dt \),
\begin{equation}
\label{eq:GRcircular_general}
\frac{d\tau}{dt} = \sqrt{ \left(1 - \frac{2GM}{rc^2}\right) - \frac{r^2 \Omega^2}{c^2} }.
\end{equation}
For a free circular geodesic, \( \Omega^2 = GM/r^3 \), yielding
\begin{equation}
\label{eq:GRcircular_geodesic}
\frac{d\tau}{dt} = \sqrt{\,1 - \frac{3GM}{rc^2}\,}.
\end{equation}
No timelike circular geodesics exist for \( r \le 3GM/c^2 \) (the photon sphere). Equation \eqref{eq:GRcircular_geodesic} shows explicit stacking: gravity and orbital speed reduce \( d\tau/dt \) together.

\paragraph{Local-speed factorization.}
Relative to a static observer at radius \( r \), the locally measured speed of a tangentially moving craft is
\begin{equation}
\label{eq:localv}
v_{\mathrm{loc}} = \frac{r\,\Omega}{\sqrt{1 - 2GM/(rc^2)}}.
\end{equation}
Then \eqref{eq:GRcircular_general} factorizes as
\begin{equation}
\label{eq:factorized}
\frac{d\tau}{dt} = \sqrt{\,1 - \frac{2GM}{rc^2}\,}\;\frac{1}{\gamma_{\mathrm{loc}}}, \qquad
\gamma_{\mathrm{loc}} = \frac{1}{\sqrt{1 - v_{\mathrm{loc}}^2/c^2}}.
\end{equation}
Interpretation: take the gravitational redshift factor for a static clock at \( r \) and apply an additional special-relativistic time dilation using the local physical speed measured in that static frame \cite{will2014}.

\subsection{Weak-field, slow-motion limit}
\label{subsec:weakfield}
Let \( \Phi \) be the Newtonian potential (negative), so that \( g_{00} \simeq -\left(1 + 2\Phi/c^2\right) \). To first order in \( |\Phi|/c^2 \ll 1 \) and \( v^2/c^2 \ll 1 \),
\begin{equation}
\label{eq:weakfield}
\frac{d\tau}{dt} \simeq 1 + \frac{\Phi}{c^2} - \frac{v^2}{2c^2}.
\end{equation}
Consequences:
\begin{itemize}[leftmargin=1.25em]
\item \textbf{Head vs foot.} At height difference \( h \) near Earth, \( \Delta\Phi \simeq gh \), so the higher clock runs faster by a fractional rate \( gh/c^2 \). For \( h=1\,\mathrm{m} \), this is \( \sim 1.1\times 10^{-16} \), i.e., about \( 3.4\,\mathrm{ns} \) per year \cite{chou2010}.
\item \textbf{Navigation clocks.} Spaceborne clocks run faster from \( +\Phi/c^2 \) (higher altitude) and slower from \( -v^2/2c^2 \) (orbital speed). Both corrections are applied in GPS \cite{ashby2003}.
\end{itemize}

\section{Canonical Examples}
\label{sec:examples}

\subsection{Everyday ladder: head vs foot}
Standing up, your head sits higher than your feet and so it is farther from the center of Earth. Higher means slightly faster. The difference is tiny yet real. Lie down and the difference mostly vanishes. This has been measured directly with modern optical clocks \cite{chou2010}.

\subsection{Orbiting hardware: navigation satellites}
Satellites are high up and also moving fast. Higher tends to make them run fast. Fast motion tends to make them run slow. Engineers account for both in navigation systems \cite{ashby2003}.

\subsection{Fast decayers that live longer}
Short lived particles created in accelerators reach detectors that they could not reach if their internal clocks were not running slow from speed \cite{bailey1977}.

\section{Worked Scenario: One-way Trip to the Future}
\label{sec:super}
\begin{notebox}{Premise}
The present is hopeless. A traveler wants to reach the future. He chooses to combine both parts of the slogan: mass slows time and speed slows time.
\end{notebox}

\paragraph{Setup.}
He departs Earth in a robust ship. He descends toward the Sun to a safe but close orbit and accelerates to a speed extremely close to the speed of light. He maintains this for a chosen interval by his own watch.

\paragraph{Why it works.}
\begin{itemize}[leftmargin=1.25em]
  \item \textbf{Near mass.} Being deep in the Sun's gravity makes the shipboard clock run slow relative to clocks far from the Sun \cite{poundrebka1960,vessot1980,shapiro1964}.
  \item \textbf{High speed.} Flying very fast makes the shipboard clock run slow relative to stationary clocks\cite{einstein1905,bailey1977}.
  \item \textbf{Stacking.} Doing both near a star stacks the effects, so the shipboard clock advances much less than clocks on Earth that stayed higher and slower \cite{ashby2003}.
\end{itemize}

\paragraph{Return and comparison.}
After what feels like a short time on board, the traveler returns to Earth. Many more years have passed on Earth than ticked on his ship. His watch never behaved strangely to him. The difference appears when the clocks are compared \cite{hafelekeating1972a,hafelekeating1972b}.

\paragraph{Variations.}
\begin{itemize}[leftmargin=1.25em]
  \item \textbf{Hover vs orbit.} Even if the ship hovers at fixed altitude with engines rather than orbits, being deep in the well still slows the onboard clock \cite{vessot1980}.
  \item \textbf{Different stars.} A denser star produces stronger slowing when approached safely. A small asteroid produces very little.
  \item \textbf{Deep space version.} Far from any mass, speed alone still works. The stacked near star plan is stronger for the same onboard time \cite{einstein1905,bailey1977}.
\end{itemize}

\section{Operational Checklist}
\label{sec:checklist}
For any mission or story that needs a jump to the future:
\begin{enumerate}[leftmargin=1.25em]
  \item Pick a massive body if you want to amplify the mass part of the slogan. Pick deep space if you want fewer hazards.
  \item Plan a speed profile that keeps the traveler fast for long enough to matter.
  \item Decide which reference clocks you will compare against later. Earth clocks, deep space clocks, or both.
  \item Remember that the reveal is at the reunion. While traveling, the watch feels normal.
\end{enumerate}

\section{Conceptual Pitfalls to Avoid}
\label{sec:pitfalls}
\begin{itemize}[leftmargin=1.25em]
  \item Do not confuse external mass with personal mass. It is the mass around you that sets the gravitational slowing. Your rest mass is not the dial \cite{poundrebka1960,vessot1980}.
  \item Do not expect symmetry by default. Two travelers can age by different amounts if they take different routes, even if they start and end together \cite{hafelekeating1972a,hafelekeating1972b}.
  \item Do not promise make up time. Once lost, relative time does not get paid back later.
\end{itemize}

% ---- (Per strategy, the Frames/Simultaneity section has been removed from Paper 1.) ----

\section{Optional translation for delay first models}
\label{sec:tlm}
If you work in a delay first framing, treat gravity as a delay gradient over frames and speed as an additional rendering delay. The near star high speed plan steepens the gradient and increases the delay, so the traveler accrues less rendered time than the distant frame \cite{mckinley2025a,mckinley2025b,mckinley2025e}.

\section{References}
\begin{thebibliography}{99}

\bibitem{einstein1905}
A. Einstein, On the electrodynamics of moving bodies, \emph{Annalen der Physik} 17, 891--921 (1905). \href{https://doi.org/10.1002/andp.19053221004}{doi:10.1002/andp.19053221004}.

\bibitem{schwarzschild1916}
K. Schwarzschild, On the gravitational field of a mass point according to Einstein's theory, \emph{Sitzungsberichte der Koeniglich Preussischen Akademie der Wissenschaften} (1916). English translation available. \href{https://doi.org/10.1002/andp.19163561802}{doi:10.1002/andp.19163561802}.

\bibitem{will2014}
C. M. Will, The confrontation between general relativity and experiment, \emph{Living Reviews in Relativity} 17, 4 (2014). \href{https://doi.org/10.12942/lrr-2014-4}{doi:10.12942/lrr-2014-4}.

\bibitem{poundrebka1960}
R. V. Pound and G. A. Rebka Jr., Apparent weight of photons, \emph{Physical Review Letters} 4, 337--341 (1960). \href{https://doi.org/10.1103/PhysRevLett.4.337}{doi:10.1103/PhysRevLett.4.337}.

\bibitem{vessot1980}
R. F. C. Vessot and M. W. Levine, Test of relativistic gravitation with a space-borne hydrogen maser, \emph{Physical Review Letters} 45, 2081--2084 (1980). \href{https://doi.org/10.1103/PhysRevLett.45.2081}{doi:10.1103/PhysRevLett.45.2081}.

\bibitem{shapiro1964}
I. I. Shapiro, Fourth test of general relativity, \emph{Physical Review Letters} 13, 789--791 (1964). \href{https://doi.org/10.1103/PhysRevLett.13.789}{doi:10.1103/PhysRevLett.13.789}.

\bibitem{hafelekeating1972a}
J. C. Hafele and R. E. Keating, Around-the-world atomic clocks: Predicted relativistic time gains, \emph{Science} 177, 166--168 (1972). \href{https://doi.org/10.1126/science.177.4044.166}{doi:10.1126/science.177.4044.166}.

\bibitem{hafelekeating1972b}
J. C. Hafele and R. E. Keating, Around-the-world atomic clocks: Observed relativistic time gains, \emph{Science} 177, 168--170 (1972). \href{https://doi.org/10.1126/science.177.4044.168}{doi:10.1126/science.177.4044.168}.

\bibitem{ashby2003}
N. Ashby, Relativity in the Global Positioning System, \emph{Physics Today} 55, 41--47 (2003). \href{https://doi.org/10.1063/1.1485583}{doi:10.1063/1.1485583}.

\bibitem{chou2010}
C. W. Chou, D. B. Hume, T. Rosenband, and D. J. Wineland, Optical clocks and relativity, \emph{Science} 329, 1630--1633 (2010). \href{https://doi.org/10.1126/science.1192720}{doi:10.1126/science.1192720}.

\bibitem{bailey1977}
J. Bailey, K. Borer, F. Combley, H. Drumm, F. von Forstner, H. Krienen, F. Lange, E. Picasso, and R. R. Schardt, Measurements of relativistic time dilation for positive and negative muons in a circular orbit, \emph{Nature} 268, 301--305 (1977). \href{https://doi.org/10.1038/268301a0}{doi:10.1038/268301a0}.

% ---- Companion symmetry paper (published) ----
\bibitem{mckinleyIllusion2025}
J. C. W. McKinley, \emph{Illusion and Invariant: Making Sense of Time Dilation - Reciprocity, Simultaneity, and Proper Time}, Zenodo (2025). \href{https://doi.org/10.5281/zenodo.17083276}{doi:10.5281/zenodo.17083276}.

% ---- User's TLM anchor DOIs for optional section ----
\bibitem{mckinley2025a}
J. C. W. McKinley, Quantum Platform as Frame Generator, Zenodo (2025). \href{https://doi.org/10.5281/zenodo.16788735}{doi:10.5281/zenodo.16788735}.

\bibitem{mckinley2025b}
J. C. W. McKinley, Absorption-Frame Motion in TLM, Zenodo (2025). \href{https://doi.org/10.5281/zenodo.16791636}{doi:10.5281/zenodo.16791636}.

\bibitem{mckinley2025e}
J. C. W. McKinley, Mass as Delay, Zenodo (2025). \href{https://doi.org/10.5281/zenodo.16908749}{doi:10.5281/zenodo.16908749}.
\end{thebibliography}

\end{document}
```

</details>

---
{% endraw %}
