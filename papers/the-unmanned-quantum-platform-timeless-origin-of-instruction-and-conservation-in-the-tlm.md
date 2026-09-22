---
layout: default
title: '[2025] The Unmanned Quantum Platform: Timeless Origin of Instruction and Conservation in the TLM'
description: 'Publication metadata and archived raw LaTeX source by John C. W. McKinley.'
permalink: /papers/the-unmanned-quantum-platform-timeless-origin-of-instruction-and-conservation-in-the-tlm/
paper: true
---
{% raw %}
# [2025] The Unmanned Quantum Platform: Timeless Origin of Instruction and Conservation in the TLM
*   **DOI:** [10.5281/zenodo.17329404](https://doi.org/10.5281/zenodo.17329404)
*   **Date:** 11 October 2025

<details markdown="1">
<summary><b>Click to view Raw LaTeX Source</b></summary>

```latex
\documentclass[12pt,onecolumn]{article}

% ---------- Encoding & fonts ----------
\usepackage[utf8]{inputenc}
\usepackage[T1]{fontenc}
\usepackage{lmodern}
\usepackage{textcomp}

% ---------- Page & layout ----------
\usepackage[letterpaper,margin=1in]{geometry}
\usepackage{setspace}
\setstretch{1.12}
\usepackage{microtype}
\usepackage{fancyhdr}
\pagestyle{fancy}
\fancyhf{}
\lhead{Unmanned Quantum Platform}
\rhead{McKinley}
\cfoot{\thepage}

% ---------- Math & figures ----------
\usepackage{amsmath,amssymb,bm}
\usepackage{graphicx}
\usepackage{float}
\usepackage{booktabs}
\usepackage{array}
\newcolumntype{L}[1]{>{\raggedright\arraybackslash}p{#1}}
\usepackage{rotating} % sideways tables
\usepackage{tikz}
\usetikzlibrary{arrows.meta,positioning,calc,shapes.geometric}
\usepackage{pgfplots}
\pgfplotsset{compat=1.18}

% ---------- Links & refs ----------
\usepackage{hyperref}
\hypersetup{colorlinks=true,linkcolor=blue,urlcolor=blue,citecolor=blue}
\usepackage[nameinlink,capitalize]{cleveref}

% ---------- ORCID (optional) ----------
\newcommand{\orcid}[1]{\href{https://orcid.org/#1}{\texttt{ORCID:#1}}}

% ---------- Handy macros ----------
\newcommand{\MassDelayLaw}{\ensuremath{T\,m=\hbar/c^{2}}}
\newcommand{\CausalSpeedLaw}{\ensuremath{T\,C_{s}=1}}

% ---------- Title ----------
\title{The Unmanned Quantum Platform: Timeless Origin of Instruction and Conservation in the TLM }
\usepackage{orcidlink}
\author{John C. W. McKinley\orcidlink{0009-0005-7097-5035}\thanks{This version published at
  \href{https://doi.org/10.5281/zenodo.17329404}{https://doi.org/10.5281/zenodo.17329404}.}\\Independent Researcher}
\date{October 11, 2025}

\begin{document}
\maketitle

\begin{abstract}
\noindent
In plain terms: the source of instructions is not a spacetime animal at all; it is a “no-space, no-dimension” ledger that records only events that will exist. In the Timeless Light Model (TLM), physical events appear in our spacetime only after a complete causal instruction is authored on a timeless substrate, the \emph{Quantum Platform} (QP). We formalize the claim that the instructions are \emph{automatic}: the QP is an unmanned, extra-spatiotemporal ledger that records emitter and absorber coordinates together with conserved transfers of four-momentum, angular momentum (including helicity), and charge. Time enters only at deployment in the Spacetime Deployment Frame (SDF), not at authoring. We derive conservation as a precondition of eligibility, connect deployment delay to the bridge law \MassDelayLaw{}, and contrast this ontology with Wheeler--Feynman and Cramer's Transactional Interpretation \cite{WheelerFeynman1945,Cramer1986}. A TikZ “ledger” figure and a table summarize falsifiable consequences.
\end{abstract}

\section{Public Dialogue Excerpt and Link}
\begin{quote}\small
\textbf{@swamichatanananda:} Where do the instructions come from?\\[0.4em]
\textbf{@DiagonalStudios (account of the author):} In this model, the instructions are automatic. It is an ``unmanned system'': The ``Quantum Platform'' holds a record of: emitter and absorber event coordinates, conserved four-momentum transfer, angular momentum transfer (including helicity), and charge transfer. This is a part of the process outside of, or free of, time and spatial dimensions. In our frame, we see the energy drop there and increase here, with apparent time in between. This model says the time was introduced AFTER the complete story was fully known.\cite{McKinley2025_OriginOfInstruction}
\end{quote}


\section{TLM Summary}
\label{sec:tlm-summary}
The Timeless Light Model (TLM) addresses longstanding puzzles in quantum mechanics and relativity by positing that certain phenomena, particularly those involving light and instantaneous quantum effects, operate outside the conventional spacetime framework. Drawing from the relativistic insight that photons experience zero proper time, TLM reinterprets photons as “instructions only” events in a timeless layer \cite{McKinley2025LightAbsent,McKinley2025NoMidFlight}. This layer, termed the Quantum Platform (QP), handles non-local and acausal resolutions, while the observable universe—the Spacetime Deployment Frame (SDF)—deploys these resolutions in a causal, time-ordered manner.

In this model, photons are not physical entities (travellers or “little bullets”) traversing spacetime but instantaneous instructions that adjust energy levels between emission and absorption points. These instructions reside in the QP, which is ontologically senior to the SDF governed by General Relativity (GR), Special Relativity (SR), and Quantum Mechanics (QM). A key feature of TLM is that instructions are “written” after absorption in the SDF but resolved timelessly in the QP, avoiding paradoxes like retrocausality. (The instruction is authored timelessly on QP once an absorber condition exists; SDF renders it after absorption. “After” refers only to rendered order in SDF, not to authoring on QP.) Prior TLM derivations of deployment pacing and frame rules are detailed in \cite{McKinley2025FrameDisplay,McKinley2025Endpoint,McKinley2025Massless}.

Instructions are resolved holistically on QP (outside time/space) and only then deployed in SDF, where observers experience delay and causal order. The application of instructions into the SDF, with its usual GR/SR rules, follows the bridge law \(\MassDelayLaw{}\), and the causal rate satisfies \(\CausalSpeedLaw{}\) \cite{McKinley2025NoMidFlight}. There is no orphan emission and no mid-flight energy: every realized instruction maps to exactly one absorber, with no energetic parcel propagating between endpoints \cite{McKinley2025LightAbsent}.

\section{The Core Puzzle: How Timelessness Meets Uncertainty}
If an instruction is instant and pre-resolved in the QP, how can it still be a wavefunction ($\psi$) with many possible endings (superposition)? If a photon is an instruction that links emission ($x^\mu_e$) and absorption ($x^\mu_a$) instantaneously in the QP, the process appears predetermined. Yet nature is probabilistic, described by $\psi$.

\textbf{Answer:} the Wait Phase \cite{McKinley2025FrameDisplay}. The original Emit/Absorb pair was functionally complete but ontologically incomplete. The new Emit--Wait--Absorb triad is an internal logic check that ensures all quantum and relativistic constraints are satisfied before the instruction is rendered. Crucially, Wait is \emph{not} a time delay: the clock does not tick during Wait ($T=0$); it is an informational check in the QP’s timeless domain.

\subsection{The Office Metaphor: Why Instructions Wait}
Think of the QP as Head Office that issues a memo (the instruction) requiring approval before execution in the field (the SDF).
\begin{itemize}
  \item \textbf{Emit (Issue):} A worker (emitting atom) sends a complete CI-ARC to the QP with all candidate absorbers ($x^\mu_a$).
  \item \textbf{Wait (Check Eligibility):} The memo enters a non-temporal holding area.
  \begin{itemize}
    \item \textbf{Quantum Filter (QM):} $\psi$ acts as an eligibility map, re-weighting candidate endpoints.
    \item \textbf{Relativistic Filter (GR/SR):} Delay/geometry constraints authored by the QP are applied (Creator--Law hierarchy: QP as law-authoring layer; SDF as law-executing layer).
  \end{itemize}
  \item \textbf{Absorb (Finalize):} Once checks pass, a single outcome is finalized and rendered in SDF. The apparent wavefunction collapse is interpreted here as the termination of the Wait Phase.
\end{itemize}

\subsection{Wait Phase: The Checkpoint Where Rules Are Applied}
\begin{enumerate}
  \item \textbf{Emit:} QP issues a CI-ARC containing possible endpoints.
  \item \textbf{Wait:} Instruction held in timeless suspension ($T=0$) while two filters run: (i) \textbf{QM structure} ($\psi$ eligibility) and (ii) \textbf{GR/SR delay} (Creator--Law hierarchy).
  \item \textbf{Absorb:} Once filters pass, the instruction resolves to one outcome, which SDF renders.
\end{enumerate}
\noindent\emph{Key message:} Wait is a rule check, not a clock tick.

\section{QP is the Source of All Rules (The Creator--Law Hierarchy)}
We need not ask \emph{why} the universe obeys GR/SR if, in TLM, the QP \emph{drives} them. \emph{Creator--Law hierarchy:} QP as the law-authoring layer; SDF as the law-executing layer \cite{McKinley2025FrameDisplay}.
\begin{itemize}
  \item \textbf{Axiom:} The QP authored GR/SR as immutable axioms (e.g., $T m = \hbar/c^{2}$). The QP dictates rules; the SDF executes them.
  \item \textbf{Benefit:} Replaces mechanistic “delay gradients” with an axiomatic why. Curvature/time dilation are executions of authored rules.
  \item \textbf{Testable Signature:} Because the Relativistic Filter is applied at Wait termination, TLM predicts \emph{entanglement latency} $\Delta t = \dfrac{G M_{\text{detector}}}{c^3}$.
\end{itemize}

\section{Axioms and Minimal Interface}
\label{sec:axioms}
We adopt the minimal QP$\to$SDF interface:
\[
I=\langle x_e^{\mu},x_a^{\mu};\ \Delta p^{\mu},\ \Delta J^{\mu\nu},\ \Delta Q\rangle,
\]
with eligibility conditioned on global conservation at the endpoints. For massless quanta, $\Delta p^\mu \Delta p_\mu=0$ and $d\tau=0$; for spin-1 lightlike instructions, $\Delta J^{\mu\nu}$ reduces to helicity $h\in\{\pm1\}$. The \emph{Generalized Pairing Law} forbids unresolved offers: a record exists iff a compatible absorber exists. Deployment delay is governed by \MassDelayLaw{} and \CausalSpeedLaw{} \cite{McKinley2025NoMidFlight}.

\paragraph{Generalized Pairing Law (explicit helicity fixation).}
Choose the $z$–axis along the instruction momentum $\bm{p}$ so that helicity $h$ is the spin projection along $\hat{\bm{p}}$ (in units of $\hbar$). Global conservation at the endpoints implies the scalar $J_z$ balance
\begin{equation}
\Delta J^{(e)}_z \;+\; h \;+\; \Delta J^{(a)}_z \;=\; 0,
\label{eq:helicity-fixation}
\end{equation}
where $\Delta J^{(e)}_z$ and $\Delta J^{(a)}_z$ are, respectively, the emitter and absorber angular–momentum changes projected onto $\hat{\bm{p}}$ and $h\in\{\pm 1\}$ for spin-1 lightlike instructions. Equation~\eqref{eq:helicity-fixation} yields the \emph{helicity fixation rule}
\begin{equation}
h \;=\; -\bigl(\Delta J^{(e)}_z + \Delta J^{(a)}_z\bigr),
\end{equation}
so $h$ is not chosen “in flight” but determined at authoring by boundary conditions. Together with four-momentum and charge balance,
\begin{equation}
\Delta p^\mu_{\!(e)} \;+\; \Delta p^\mu_{\!(a)} \;+\; \Delta p^\mu_{\!(\text{instr})} \;=\; 0,
\qquad
\Delta Q_{(e)} \;+\; \Delta Q_{(a)} \;=\; 0,
\end{equation}
(and $\Delta p^\mu_{\!(\text{instr})}\Delta p_{\mu\,(\text{instr})}=0$ for lightlike records),
this condition defines the set of eligible emitter–absorber pairs. If and only if there exists an absorber $a$ satisfying these constraints, a CI-ARC is writeable on QP (otherwise no record exists).


\paragraph{Entanglement as a bundle of one–to–one CI-ARCs (no-signaling preserved).}
The base case in TLM is a single-emitter/single-absorber CI-ARC. Entangled deployments are authored on QP as a \emph{bundle of one–emit/one–absorb CI-ARCs} written simultaneously under a shared global eligibility check (conservation across all endpoints and the emitter) rather than as a single multi-endpoint arc. No CI-ARC in the bundle links to more than one absorber, and \emph{no orphan emissions} are writeable.

For the spin-1 (helicity) case with two absorbers whose analyzers define local $z$-axes via $\hat{\bm p}$ projections, global angular-momentum balance imposes
\begin{equation}
\Delta J^{(e)}_z \;+\; h_{(1)} \;+\; h_{(2)} \;=\; 0, \qquad h_{(i)}\in\{\pm 1\},
\label{eq:pair-helicity}
\end{equation}
with standard geometric projections for general analyzer angles. The bundle’s shared eligibility enforces \emph{no-signaling}: the local marginal at site $1$,
\[
P(o_1\,|\,\alpha) \;=\; \sum_{o_2\in\{\pm 1\}} P(o_1,o_2\,|\,\alpha,\beta),
\]
is independent of the remote setting $\beta$, while the joint distribution $P(o_1,o_2\,|\,\alpha,\beta)$ exhibits the familiar Bell-type structure \cite{Bell1964,Einstein1905}.



\section{Conservation as Instruction Eligibility}
\label{sec:conservation}
Conservation in TLM is not an emergent dynamical outcome but a \emph{pre-resolution filter}. Let the total Noether charges of the emitter--absorber system be $\mathcal{C}=\{\mathcal{E},\bm{\mathcal{P}},\bm{\mathcal{J}},\mathcal{Q}\}$. An instruction $I$ is writeable on QP only if
\[
\Delta \mathcal{C} = 0
\quad\text{with}\quad
\Delta \bm{\mathcal{J}} \supset \Delta \text{(helicity)} = h\in\{\pm1\}.
\]
Thus helicity is fixed at authoring by boundary conditions; there is no intermediate “spin choice” \cite{McKinley2025LightAbsent}.

Entangled runs are authored on QP as a simultaneously written \emph{bundle of one–emit/one–absorb CI-ARCs} under a shared eligibility constraint. Local outcome statistics at each station are fixed by eligibility and do not depend on the remote analyzer setting (no-signaling), while joint outcomes display the angle-dependent correlations familiar from Bell tests \cite{Bell1964}. SR’s null interval for lightlike links \cite{Einstein1905} ensures there is no in-transit degree of freedom to carry signals.




\section{Helicity and Polarization: What is Rendered}
\label{sec:helicity}
In SDF the observable is polarization. Because $m=0\Rightarrow T=0$ for the instruction itself, there is no worldline evolution to rotate or flip $h$ between endpoints. The absorber's polarization statistics reflect the structure filter (standard quantum rules) applied at deployment, not a transit process.

\paragraph{External consistency.}
Fixation via boundary conditions is consistent with no in-transit degrees of freedom for lightlike records: special relativity assigns a null interval to such links ($ds^{2}=0\Rightarrow d\tau=0$), eliminating any worldline dynamics that could flip $h$ between endpoints \cite{Einstein1905}. Correlated polarization outcomes across spacelike-separated absorbers further mirror the nonlocal constraints of Bell-type experiments \cite{Bell1964}, here interpreted as a shared-eligibility bundle of one–to–one CI-ARCs rather than any superluminal transport.


\[
ds^{2} = -c^{2}dt^{2} + d\bm{x}^{2} = 0 \quad \Rightarrow \quad d\tau = 0.
\]



\section{Deployment Delay and Apparent Causality}
\label{sec:delay}
Although QP authoring is timeless, observers register a sequence. The \emph{Mass--Delay bridge} \MassDelayLaw{} implies heavier clocks experience greater delay. Apparent causal order arises as SDF pacing\cite{McKinley2025NoMidFlight,McKinley2025Massless}:
\[
T=\frac{\hbar}{m c^{2}},\qquad C_{s}=\frac{1}{T}.
\]
Entanglement phenomena correspond to a \emph{bundle of one–emit/one–absorb CI-ARCs}, authored simultaneously on QP and coupled by a shared eligibility constraint; the bundle deploys with negligible differential delay, up to GR-scale gradients predicted in prior TLM work \cite{McKinley2025NoMidFlight,McKinley2025Massless}.

Each CI-ARC in the bundle remains strictly one–to–one; correlations arise because all arcs share the same global conservation check at authoring (no-signaling preserved).




\paragraph{External consistency.}
For massless instructions $d\tau=0$ along the link, so the apparent ordering arises entirely from SDF pacing, not transit evolution \cite{Einstein1905}. In multipartite deployments, endpoint correlations respecting Bell constraints \cite{Bell1964} emerge from a simultaneously authored bundle of one–to–one CI-ARCs, avoiding any need for intermediate signaling.


\section{Relation to Wheeler--Feynman and Transactional Interpretation}
\label{sec:wf-ti}
Wheeler--Feynman (WF) provides a time-symmetric skeleton of advanced/retarded fields; Cramer's TI adds the transaction metaphor. TLM replaces propagating waves and time symmetry with \emph{timeless eligibility}: instructions are authored only if endpoint constraints are satisfiable. Collapse is avoided—the written instruction deploys; nothing “chooses” mid-flight \cite{WheelerFeynman1945,Cramer1986}.

\section{Figure: QP Ledger Diagram}
\label{sec:figure}
\begin{figure}[H]
\centering
\begin{tikzpicture}[
  >=Stealth, node distance=1.6cm,
  box/.style={rectangle,draw,rounded corners=2pt,minimum width=5.2cm,minimum height=1.2cm,align=center}
]
  \node (QP)   [box, fill=blue!9] {\textbf{Quantum Platform (QP)}\\ \small Unmanned timeless ledger: $I=\langle x_e,x_a;\Delta p,\Delta J,\Delta Q\rangle$};
  \node (ELIG) [box, below=of QP, fill=yellow!12] {\textbf{Eligibility Filter (Wait)}\\ \small Conservation \& pairing check, application of rules};
  \node (SDF)  [box, below=of ELIG, fill=red!9] {\textbf{Spacetime Deployment Frame (SDF)}\\ \small Rendered event; delay set by $T=\hbar/(mc^2)$};

  \draw[->,very thick] (QP) -- node[right]{\small write if eligible} (ELIG);
  \draw[->,very thick] (ELIG) -- node[right]{\small deploy with delay $T$} (SDF);
\end{tikzpicture}
\caption{TLM ontology: a timeless authoring layer (QP) records complete instructions; deployment into the SDF is paced by the Mass--Delay bridge. Timeless authoring (QP) acts as an unmanned ledger: only eligible records are written, and the SDF displays them with delay $T = \hbar / (m c^{2})$.}
\end{figure}
\clearpage

\section{Predictions and Tests}
\label{sec:predictions}
\vspace{0.5em}
\noindent
\begin{minipage}{\textwidth}
\centering
\begin{tabular}{L{4.7cm} L{7.2cm} L{3.8cm}}
\toprule
\textbf{Prediction} & \textbf{Operationalization} & \textbf{Pass / Fail}\\
\midrule
No mid-flight energy for light & Absence of energy storage between emitter and absorber in cavity-exchange nulls; timing correlations match endpoint-only accounting & Pass: endpoint-only balance; Fail: measurable transit energy\\
Helicity fixed by endpoints & Polarization statistics conditioned on emitter/absorber geometry; no transit-contingent helicity flips & Pass: endpoint-conditioned; Fail: in-flight helicity dynamics\\
Entanglement latency scales with GR delay & Differential latencies $\sim GM/c^{3}$ across detectors at different potentials & Pass: matches GR scaling; Fail: independent of potential\\
Deployment delay obeys \MassDelayLaw{} & Clock-rate comparisons vs.\ rest mass across platforms (atomic transitions, oscillators) & Pass: $T\propto 1/m$; Fail: systematic deviation\\
\addlinespace[0.25em]
\textbf{No orphan emissions in null experiments} & Configure a source with an adjustable distant absorber/shutter; test emission statistics when the absorber is absent/blocked versus present (including delayed-choice geometries) & Pass: emission is conditioned on absorber existence; \emph{no} free “orphan” radiation in null configurations; Fail: emission occurs without any eligible absorber\\
\bottomrule
\end{tabular}

\vspace{0.5em}
\footnotesize\textbf{Caption:} Falsifiable signals and pass/fail criteria derived from the unmanned-ledger premise \cite{McKinley2025NoMidFlight}.
\end{minipage}

\section{Core Concepts of the Timeless Light Model}
\label{sec:core}

\subsection{Photons as Timeless Instructions}
In standard quantum field theory, photons are quanta of the electromagnetic field, mediating interactions while traveling at the speed of light. However, from special relativity, a photon's proper time is zero: it experiences no elapsed time between emission and absorption, and in its frame, the distance traveled is also zero (cf.\ \cite{Einstein1905}). TLM builds on this by redefining the photon not as a particle or wave in transit but as an instantaneous instruction: “Decrease energy by one unit at the emission location and increase it by one unit at the absorption location.” This instruction is devoid of path, duration, or spatial dimension, rendering it incompatible with the spacetime fabric of the universe \cite{McKinley2025LightAbsent}.

\subsection{The Layered Reality Framework}
TLM introduces a hierarchical structure to reality:
\begin{itemize}
  \item \textbf{Quantum Platform (QP)}: A timeless, acausal layer outside the universe where instructions are resolved. Here, events like entanglement (correlated states without signaling) and tunneling (barrier penetration without traversal) are handled as holistic pairs. The QP is “senior” to the SDF, meaning it dictates the rules without being bound by them.
  \item \textbf{Spacetime Deployment Frame (SDF)}: The observable universe governed by GR, SR, and QM, where instructions from QP are deployed in a linear, causal sequence. Observers in SDF perceive time, space, and causality, but these emerge from QP resolutions.
\end{itemize}
In this framework, the photon instruction is “written” as a paired recording: emission and absorption are matched in QP only once both endpoints are defined in SDF. However, since QP is timeless, this matching occurs without temporal sequence \cite{McKinley2025FrameDisplay,McKinley2025Endpoint}.

\section{Explaining the Absence of Paradoxes}
\label{sec:paradox}
A potential paradox in TLM arises from the notion that the instruction is written “after” absorption, seemingly implying retrocausality. TLM resolves this via timeless authoring on QP and causal rendering in SDF; “after” refers only to SDF render order, not to QP authoring. This preserves no-signaling constraints while allowing nonlocal correlations, in line with Bell \cite{Bell1964}.

\section{Supporting Evidence and Testability}
\label{sec:evidence}
TLM aligns with established physics: (i) photons’ null proper time in SR \cite{Einstein1905}; (ii) nonlocal correlations consistent with Bell tests \cite{Bell1964}; and (iii) operational constraints summarized in prior TLM reports \cite{McKinley2025NoMidFlight,McKinley2025LightAbsent}. Possible tests include searching for deployment signatures and GR-scaled entanglement latency.

\section{Glossary (TLM)}
\label{sec:glossary}
\textbf{Quantum Platform (QP)}: Timeless, causally senior ledger that authors complete CI-ARCs; not located in spacetime.\\
\textbf{Spacetime Deployment Frame (SDF)}: Rendered arena where instructions appear as events; time is deployment delay.\\
\textbf{Instruction ($I$)}: Minimal record $\langle x_e,x_a;\Delta p,\Delta J,\Delta Q\rangle$ linking endpoints.\\
\textbf{Mass--Delay Law}: \MassDelayLaw{}, deployment delay inversely proportional to mass.\\
\textbf{Causal Speed Law}: \CausalSpeedLaw{}, rate dual to delay.\\
\textbf{Helicity ($h$)}: $\pm 1$ for lightlike instructions; fixed at authoring.\\
\textbf{CI-ARC (Causal Instruction Arc).}:
An atomic, timeless instruction authored on the Quantum Platform (QP) that links an emission endpoint to exactly one absorption endpoint as a single record. It carries conserved transfers and can be written as the instruction tuple
\(I=\langle x_e^{\mu},\, x_a^{\mu};\, \Delta p^{\mu},\, \Delta J^{\mu\nu},\, \Delta Q\rangle\).
Deployment into the Spacetime Deployment Frame (SDF) is paced by the Mass–Delay bridge \(T m=\hbar/c^{2}\), obeys the Generalized Pairing Law (no orphan emissions), the Single-Absorber principle, and the “no mid-flight energy” rule (no usable energy or signal between endpoints).



\section{Conclusion}
\label{sec:conclusion}
The answer to “Where do the instructions come from?” is: not from within spacetime at all. In TLM, an unmanned QP authors only those instructions that already satisfy global conservation and pairing. What appears to us as causal evolution is the paced deployment of a completed story \cite{McKinley2025LightAbsent,McKinley2025NoMidFlight}.

% -------------------- References --------------------

\addcontentsline{toc}{section}{References}

\begin{thebibliography}{99}

\bibitem{McKinley2025LightAbsent}
J.~C.~W. McKinley,
\newblock {\em Light as Absent: Reclassifying the Photon as a Timeless Instruction} (2025).
\newblock Zenodo. \href{https://doi.org/10.5281/zenodo.16627550}{doi:10.5281/zenodo.16627550}.

\bibitem{McKinley2025NoMidFlight}
J.~C.~W. McKinley,
\newblock {\em The ``No Mid-Flight Energy'' Principle: Operational Consistency and Ontological Implications for the Timeless Light Model (TLM)} (2025).
\newblock Zenodo. \href{https://doi.org/10.5281/zenodo.17018871}{doi:10.5281/zenodo.17018871}.

\bibitem{Cramer1986}
J.~G. Cramer,
\newblock The Transactional Interpretation of Quantum Mechanics,
\newblock {\em Reviews of Modern Physics} {\bf 58}, 647--688 (1986).
\newblock \href{https://doi.org/10.1103/RevModPhys.58.647}{doi:10.1103/RevModPhys.58.647}.

\bibitem{WheelerFeynman1945}
J.~A. Wheeler and R.~P. Feynman,
\newblock Interaction with the Absorber as the Mechanism of Radiation,
\newblock {\em Reviews of Modern Physics} {\bf 17}, 157--181 (1945).
\newblock \href{https://doi.org/10.1103/RevModPhys.17.157}{doi:10.1103/RevModPhys.17.157}.

\bibitem{McKinley2025Massless}
J.~C.~W. McKinley,
\newblock {\em Massless Things Do Not Experience Time} (2025).
\newblock Zenodo. \href{https://doi.org/10.5281/zenodo.17173126}{doi:10.5281/zenodo.17173126}.

\bibitem{McKinley2025Endpoint}
J.~C.~W. McKinley,
\newblock {\em From Endpoint Pairing to Frame Splitting: Absorption-Frame Motion in the Timeless Light Framework} (2025).
\newblock Zenodo. \href{https://doi.org/10.5281/zenodo.16791636}{doi:10.5281/zenodo.16791636}.

\bibitem{McKinley2025FrameDisplay}
J.~C.~W. McKinley,
\newblock {\em Frame Display Law for TLM v2.0: EA-Conditioned Rendering in a Single Spacetime Deployment Frame} (2025).
\newblock Zenodo. \href{https://doi.org/10.5281/zenodo.16936105}{doi:10.5281/zenodo.16936105}.

\bibitem{Einstein1905}
A.~Einstein,
\newblock Zur Elektrodynamik bewegter K{\"o}rper,
\newblock {\em Annalen der Physik} {\bf 17}, 891--921 (1905).

\bibitem{Bell1964}
J.~S. Bell,
\newblock On the Einstein Podolsky Rosen Paradox,
\newblock {\em Physics Physique Fizika} {\bf 1}, 195--200 (1964).

\bibitem{McKinley2025_OriginOfInstruction}
J.\ C.\ W.\ McKinley,
\newblock {\em Public dialogue excerpt on “Where do the instructions come from?” (YouTube comment) — archival PDF and context} (2025).
\newblock Zenodo. \href{https://doi.org/10.5281/zenodo.17329883}{doi:10.5281/zenodo.17329883}.


\end{thebibliography}

\end{document}

```

</details>

---
{% endraw %}
