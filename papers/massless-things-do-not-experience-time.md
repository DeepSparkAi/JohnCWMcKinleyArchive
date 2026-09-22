---
layout: default
title: '[2025] Massless Things Do Not Experience Time'
description: 'Publication metadata and archived raw LaTeX source by John C. W. McKinley.'
permalink: /papers/massless-things-do-not-experience-time/
paper: true
---
{% raw %}
# [2025] Massless Things Do Not Experience Time
*   **DOI:** [10.5281/zenodo.17173126](https://doi.org/10.5281/zenodo.17173126)
*   **Date:** 22 September 2025

<details markdown="1">
<summary><b>Click to view Raw LaTeX Source</b></summary>

```latex
\documentclass[12pt, onecolumn]{article}

% ---------- Page & Layout ----------
\usepackage[margin=1in]{geometry}
\usepackage[T1]{fontenc}
\usepackage[utf8]{inputenc}
\usepackage{lmodern}
\usepackage{microtype} % For better typography

% ---------- Math ----------
\usepackage{amsmath,amssymb,amsthm}

% ---------- Lists ----------
\usepackage{enumitem}

% ---------- Figures & Floats ----------
\usepackage{graphicx}
\usepackage{float}
\usepackage{tikz}
\usetikzlibrary{shapes.geometric, arrows.meta, positioning}

% ---------- Links & References ----------
\usepackage{hyperref}
\hypersetup{colorlinks=true,linkcolor=blue,urlcolor=blue,citecolor=blue}
\usepackage{cleveref}

% ---------- Headers & Title ----------
\usepackage{fancyhdr}
\usepackage{orcidlink}

% --- Header Setup ---
\pagestyle{fancy}
\fancyhf{}
\lhead{Massless Things Do Not Experience Time}
\rhead{\thepage}

% ---------- Theorem-like ----------
\newtheorem{definition}{Definition}
\newtheorem{proposition}{Proposition}
\newtheorem{remark}{Remark}

\begin{document}

\title{Massless Things Do Not Experience Time}
\author{John C. W. McKinley\orcidlink{0009-0005-7097-5035}\\Independent Researcher}
\date{September 21, 2025}
\maketitle

\begingroup
  \footnotetext[0]{This version published at
  \href{https://doi.org/10.5281/zenodo.17173126}{https://doi.org/10.5281/zenodo.17173126}.}
\endgroup

\begin{abstract}
A central, often misunderstood consequence of special relativity is that massless particles (e.g., photons) traverse null worldlines with zero invariant interval. In the proper-time formalism, this implies that a massless particle does not experience time between its emission and absorption: the elapsed proper time along its path is identically zero \cite{einstein1905,MTW,Rindler,TaylorWheeler}. Yet everyday language speaks as if light ``travels for 600 years'' from Betelgeuse to Earth. This paper clarifies the distinction between coordinate time in a chosen frame and proper time along a worldline, demonstrates rigorously that null geodesics have $d\tau=0$, and analyzes common thought experiments that smuggle massive carriers into allegedly ``massless'' scenarios. We then articulate consequences for interpretation and connect these to our speculative Timeless Light Model (TLM) \cite{McKinley16510862,McKinley16479322,McKinley15868624,McKinley16788735,McKinley16791636,McKinley17010029,McKinley16917106,McKinley17139863,McKinley17140029,McKinley17083276}. We include spacetime diagrams and a concise derivation suitable for pedagogy and critique \cite{PenroseRTR,Mermin,Bondi,WheelerFeynman}.
\end{abstract}

\section{Introduction}
Relativity distinguishes two notions of time. \emph{Coordinate time}, $t$, is tied to a reference frame; \emph{proper time}, $\tau$, is the invariant time recorded by an ideal clock carried along a worldline \cite{TaylorWheeler,Rindler}. For timelike worldlines (massive objects), $d\tau>0$. For null worldlines (massless quanta), the invariant interval vanishes and $d\tau=0$ \cite{MTW}. Hence the sharp statement:
\begin{quote}
\textbf{Massless things do not experience time.}
\end{quote}
Despite its textbook status \cite{einstein1905,MTW}, this result is frequently muddled by conflating $t$ with $\tau$, or by building thought experiments that implicitly rely on massive carriers. We will (i) define the invariants, (ii) display a null-geodesic diagram, (iii) dissect a representative paradox (``massless film reel''), and (iv) outline interpretive consequences and TLM implications \cite{PenroseRTR,Mermin,Bondi,McKinley16510862,McKinley16479322}.

\section{Relativity Basics: Proper vs Coordinate Time}
Adopt metric signature $(-,+,+,+)$. The invariant interval between infinitesimally separated events is
\begin{equation}
ds^2 \;=\; -c^2\,dt^2 + dx^2 + dy^2 + dz^2.
\end{equation}
Proper time $d\tau$ along a worldline is defined by
\begin{equation}
d\tau \;=\; \frac{1}{c}\sqrt{-ds^2}\quad\text{for}\quad ds^2<0 \ \ (\text{timelike}).
\end{equation}
For a massive particle with speed $v$, $d\tau = dt/\gamma$, where $\gamma = 1/\sqrt{1-v^2/c^2}$. As $v\to c$, $\gamma\to\infty$ and $d\tau\to 0$. For a \emph{massless} particle, the worldline is \emph{null}:
\begin{equation}
ds^2 = 0 \quad\Longrightarrow\quad d\tau = 0.
\end{equation}
See standard expositions \cite{TaylorWheeler,Rindler,MTW}.

\subsection*{Null worldline on a Minkowski diagram}
\begin{figure}[H]
\centering
\begin{tikzpicture}[scale=1.0]
  % axes
  \draw[->] (-0.2,0) -- (6,0) node[below] {$x$};
  \draw[->] (0,-0.2) -- (0,4.8) node[left] {$ct$};

  % light cone lines
  \draw[thick] (0,0) -- (4.5,4.5) node[above right] {null: $ds^2=0$};
  \draw[thick] (0,0) -- (-4.5,4.5);

  % a timelike worldline
  \draw[very thick, blue] (0,0) .. controls (0.8,1.2) and (1.2,2.4) .. (1.4,3.8)
       node[above right] {\small timelike: $d\tau>0$};

  % spacelike guide
  \draw[dotted] (0,2.5) -- (3.5,2.5) node[right] {spacelike slice};

  \node at (0.4,0.35) {\small O};
\end{tikzpicture}
\caption{Minkowski diagram. Null worldlines lie along the $45^\circ$ light cone ($ds^2=0$). Massive objects follow timelike worldlines with $d\tau>0$.}
\label{fig:minkowski-null}
\end{figure}

\section{Thought Experiments: Where The Paradoxes Creep In}
\subsection{Betelgeuse supernova and the ``film reel''}
A popular scenario imagines a probe at Betelgeuse recording a supernova and sending ``film'' (or data) back to Earth ``at light speed.'' Two confusions typically enter \cite{Bondi,Mermin}:
\begin{enumerate}[label=(\alph*)]
\item A \emph{film reel} or storage medium is massive. Its worldline is timelike and accumulates proper time. You cannot make a massive carrier genuinely massless by fiat.
\item Saying ``600 years passed'' refers to \emph{Earth's coordinate time} between emission and absorption events, not to any proper time along a photon's null worldline.
\end{enumerate}
If one replaces the film with an actual photon stream, each photon still has $d\tau=0$ between emission and detection. The $600$ years pertain to coordinates in Earth's rest frame, not to the photon's experienced time \cite{TaylorWheeler,Rindler}.

\subsection{``Make the film massless''}
Declaring a composite storage medium to be massless while retaining its extended structure, capacity, and dynamics is inconsistent with relativity \cite{MTW}. Massless excitations propagate on null curves and cannot serve as co-moving clocks. If a device ages, it is not massless.

\section{Einstein's Ditch: We Knew This In 1905}
Special relativity already implies: for null separations, the invariant interval is zero \cite{einstein1905}. Textbook expositions sometimes avoid dwelling on the interpretive bite, then continue to speak as if photons ``experience'' a journey. The consistent view is simply: coordinate time elapses in a given frame; the photon's proper time does not \cite{Rindler,MTW}. Any stronger claim smuggles in massive structure \cite{PenroseRTR}.

\section{Consequences}
\paragraph{No experienced duration along null curves.}
Between emission and absorption, a massless particle's proper time does not advance. There is no sense in which it has an intrinsic before/after in its own clock \cite{TaylorWheeler}.

\paragraph{A kind of spacelessness along the same invariant.}
For null separations, the invariant length along the worldline is also zero: the same calculation that kills proper time kills invariant distance along the path. This does not deny coordinates or optical distances in a frame; it states that the worldline's invariant is null \cite{MTW,Rindler}.

\paragraph{Quantum and interpretive hints.}
Because null transport has $d\tau=0$, descriptions invoking an ``in-between'' substrate for the photon are optional and frame-dependent \cite{PenroseRTR,WheelerFeynman}. This observation motivates models that place the primacy on endpoints and constraints, not on a photon's putative inner experience \cite{Mermin,Bondi}.

\section{TLM framing: photons as timeless instructions}
In the Timeless Light Model (TLM), we adopt a two-layer ontology: a \emph{Quantum Platform (QP)} that resolves instructions timelessly, and a \emph{Spacetime Deployment Frame (SDF)} that renders those resolved endpoints with delays consistent with GR/QM. In this view, the relativity result $d\tau=0$ for photons aligns with the statement that photons do not \emph{experience} transit; rather, the frame renders conservation-consistent endpoints and histories \cite{McKinley16510862,McKinley16479322,McKinley15868624,McKinley16788735,McKinley16791636,McKinley17010029,McKinley16917106,McKinley17139863,McKinley17140029,McKinley17083276}. See the brief glossary in \cref{sec:tlm-glossary}.

\subsection*{Schematic QP$\to$Frame$\to$Observables}
\begin{figure}[H]
\centering
\begin{tikzpicture}[node distance=2.8cm]
  \tikzstyle{box}=[rectangle, draw, rounded corners, minimum width=3.7cm, minimum height=1.2cm, align=center]
  \tikzstyle{arr}=[-{Latex[length=3mm,width=2mm]}, very thick]

  \node[box] (QP) {Quantum Platform (QP)\\ \small timeless constraints};
  \node[box, below=of QP] (SDF) {Spacetime Deployment Frame (SDF)\\ \small rendered endpoints};
  \node[box, below=of SDF] (Obs) {Observables\\ \small clicks, tracks, spectra};

  \draw[arr] (QP) -- node[above, xshift=-.1cm]{instruction resolution} (SDF);
  \draw[arr] (SDF) -- node[above, xshift=.1cm]{deployment with delay $T$} (Obs);
\end{tikzpicture}
\caption{Conceptual flow in TLM: instructions at QP are timeless; SDF renders endpoints and conservation-consistent histories.}
\label{fig:tlmflow}
\end{figure}

\section*{Appendix: Rigorous derivations for $d\tau=0$ along null worldlines}
\addcontentsline{toc}{section}{Appendix: Rigorous derivations for $d\tau=0$ along null worldlines}

\subsection*{A.1 Invariant interval and proper time}
With signature $(-,+,+,+)$,
\begin{equation}
ds^2 = -c^2 dt^2 + d\ell^2, \quad d\ell^2 = dx^2+dy^2+dz^2.
\end{equation}
Define proper time for timelike paths:
\begin{equation}
d\tau = \frac{1}{c}\sqrt{-ds^2} = \sqrt{1-\frac{v^2}{c^2}}\;dt = \frac{dt}{\gamma}.
\end{equation}
For a massless particle, the four-momentum satisfies $p^\mu p_\mu = 0$, and its worldline satisfies $ds^2=0$. Hence $d\tau=0$ identically \cite{MTW,Rindler}.

\subsection*{A.2 Limit from timelike to null}
Consider a massive particle with speed $v$ approaching $c$. Over a coordinate interval $\Delta t$,
\begin{equation}
\Delta \tau = \int \frac{dt}{\gamma} = \int dt\,\sqrt{1-\frac{v^2}{c^2}}.
\end{equation}
Holding $\Delta t$ fixed while $v\to c^{-}$, we have $\gamma\to\infty$ and $\Delta\tau\to 0$. The null case is the limiting boundary of timelike motion \cite{TaylorWheeler}.

\subsection*{A.3 Null geodesics and cones}
In flat spacetime, null geodesics satisfy $ct=\pm x$ (choosing $y=z=0$). Then $ds^2 = -c^2 dt^2 + dx^2 = -c^2 dt^2 + c^2 dt^2 = 0$. Thus the light cone is the locus of $ds^2=0$, and any worldline lying on it has vanishing proper time between events \cite{MTW}.

% ----------------- TLM Glossary -----------------
\section*{Glossary (Timeless Light Model)}
\label{sec:tlm-glossary}
\addcontentsline{toc}{section}{Glossary (Timeless Light Model)}
\begin{description}[leftmargin=1.2cm, style=sameline]
  \item[Quantum Platform (QP).] Ontologically senior, timeless layer where physical outcomes are resolved as instructions; not embedded in spacetime.
  \item[Spacetime Deployment Frame (SDF).] The rendered spacetime stage where resolved instructions appear as events and worldlines, subject to GR/QM constraints.
  \item[Delay $T$.] Local deployment pacing in SDF (not an independent control knob); in TLM, GR/QM phenomena are reinterpreted as delay mechanisms governing rendering cadence.
  \item[Endpoints.] Observable emission/absorption (or interaction) events rendered in SDF; in TLM, photons connect endpoints without accumulating proper time.
  \item[Generalized Pairing Law.] No orphan quanta; emissions are paired with absorptions at the level of resolved instructions.
  \item[Emission Delay Law.] Statement that realizations of quanta are paced by delay intrinsic to the deployment frame’s lawful dynamics.
  \item[Mass as Drag.] Mass is interpreted as deployment drag within SDF rather than a primary cause; the frame mediates causal deployment.
  \item[Causal Speed Law.] Compactly: $T \cdot C_s = 1$ (TLM’s rendering-rate heuristic); not used as a dynamical law here, but clarifies that $T$ encodes pacing, not experience.
\end{description}

% ----------------- References -------------------
\begin{thebibliography}{99}

% --- Primary relativity/QM sources ---
\bibitem{einstein1905}
A. Einstein, Zur Elektrodynamik bewegter K{\"o}rper, \emph{Annalen der Physik} \textbf{17} (1905) 891--921.
\href{https://doi.org/10.1002/andp.19053221004}{doi:10.1002/andp.19053221004}.

\bibitem{MTW}
C. W. Misner, K. S. Thorne, J. A. Wheeler, \emph{Gravitation}. W. H. Freeman, 1973.
ISBN: 9780716703440. % no DOI available

\bibitem{Rindler}
W. Rindler, \emph{Relativity: Special, General, and Cosmological}, 2nd ed., Oxford University Press, 2006.
ISBN: 9780198567318 (HB), 9780198567325 (PB). % no DOI available

\bibitem{TaylorWheeler}
E. F. Taylor, J. A. Wheeler, \emph{Spacetime Physics}, 2nd ed., W. H. Freeman, 1992.
ISBN: 0716723271. % no DOI available

\bibitem{PenroseRTR}
R. Penrose, \emph{The Road to Reality}, Jonathan Cape, 2004.
ISBN: 0224044478. % no DOI available

\bibitem{WheelerFeynman}
J. A. Wheeler, R. P. Feynman, Interaction with the Absorber as the Mechanism of Radiation, \emph{Rev. Mod. Phys.} \textbf{17} (1945) 157--181.
\href{https://doi.org/10.1103/RevModPhys.17.157}{doi:10.1103/RevModPhys.17.157}.

\bibitem{Bondi}
H. Bondi, \emph{Relativity and Common Sense}. Dover Publications, 1980.
ISBN: 0486240215.

\bibitem{Mermin}
N. D. Mermin, \emph{Space and Time in Special Relativity}. Waveland Press, 2005.
ISBN: 1577663645.


% --- McKinley / TLM works (representative) ---
\bibitem{McKinley17139863}
J. C. W. McKinley, \emph{Causal Chain in the Timeless Light Model: Mass as Drag, Frame as Causal Site, Quantum Platform as Cause} (2025). Zenodo.
\href{https://doi.org/10.5281/zenodo.17139863}{doi:10.5281/zenodo.17139863}.

\bibitem{McKinley16510862}
J. C. W. McKinley, \emph{Resolving Wave-Particle Duality Through the Proposed Timeless Light Model: Photons as Timeless Instructions and Waves as Deployed Delay} (2025). Zenodo.
\href{https://doi.org/10.5281/zenodo.16510862}{doi:10.5281/zenodo.16510862}.

\bibitem{McKinley16479322}
J. C. W. McKinley, \emph{Photon Out of Time: Why Light Experiences No Time—and What That Means for Physics} (2025). Zenodo.
\href{https://doi.org/10.5281/zenodo.16479322}{doi:10.5281/zenodo.16479322}.

\bibitem{McKinley15868624}
J. C. W. McKinley, \emph{Unified Physics by Subordination of GR to QM: Quantum Phenomena as the Generator of the Classical Universe} (2025). Zenodo.
\href{https://doi.org/10.5281/zenodo.15868624}{doi:10.5281/zenodo.15868624}.

\bibitem{McKinley16788735}
J. C. W. McKinley, \emph{The Quantum Platform as Frame Generator: Ontology, Anatomy, and Dark Matter Implications in TLM} (2025). Zenodo.
\href{https://doi.org/10.5281/zenodo.16788735}{doi:10.5281/zenodo.16788735}.

\bibitem{McKinley16791636}
J. C. W. McKinley, \emph{From Endpoint Pairing to Frame Splitting: Absorption-Frame Motion in the Timeless Light Framework} (2025). Zenodo.
\href{https://doi.org/10.5281/zenodo.16791636}{doi:10.5281/zenodo.16791636}.

\bibitem{McKinley17140029}
J. C. W. McKinley, \emph{Time Travel is Real: Forwards But Not Backwards} (2025). Zenodo.
\href{https://doi.org/10.5281/zenodo.17140029}{doi:10.5281/zenodo.17140029}.

\bibitem{McKinley17083276}
J. C. W. McKinley, \emph{Illusion and Invariant: Making Sense of Time Dilation, Reciprocity, Simultaneity, and Proper Time} (2025). Zenodo.
\href{https://doi.org/10.5281/zenodo.17083276}{doi:10.5281/zenodo.17083276}.

\bibitem{McKinley17010029}
J. C. W. McKinley, \emph{Photons Not in the Universe: An Axiomatic Derivation from Masslessness and Non-Travel} (2025). Zenodo.
\href{https://doi.org/10.5281/zenodo.17010029}{doi:10.5281/zenodo.17010029}.

\bibitem{McKinley16917106}
J. C. W. McKinley, \emph{Quanta are Global, Frames are Local: A Rosetta Statement of the Timeless Light Model} (2025). Zenodo.
\href{https://doi.org/10.5281/zenodo.16917106}{doi:10.5281/zenodo.16917106}.



\end{thebibliography}

\end{document}

```

</details>

---
{% endraw %}
