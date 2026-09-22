---
layout: default
title: '[2025] Why the Timeless Light Model is Not Obviously False'
description: 'Publication metadata and archived raw LaTeX source by John C. W. McKinley.'
permalink: /papers/why-the-timeless-light-model-is-not-obviously-false/
paper: true
---
{% raw %}
# [2025] Why the Timeless Light Model is Not Obviously False
*   **DOI:** [10.5281/zenodo.17118184](https://doi.org/10.5281/zenodo.17118184)
*   **Date:** 15 September 2025

<details markdown="1">
<summary><b>Click to view Raw LaTeX Source</b></summary>

```latex
\documentclass[12pt, onecolumn]{article}

\usepackage[T1]{fontenc}
\usepackage[utf8]{inputenc}
\usepackage{lmodern}
\usepackage{microtype}
\usepackage{amsmath,amssymb,amsthm}
\usepackage{enumitem}
\usepackage{geometry}
\geometry{a4paper, margin=1in}
\usepackage[most]{tcolorbox}
\tcbset{colback=gray!5,colframe=black,boxrule=0.6pt,arc=2mm}
\newtcolorbox{axiombox}[1]{breakable,title={#1},fonttitle=\bfseries}
\usepackage{natbib}
\usepackage{fancyhdr}
\usepackage{array}
\newcolumntype{L}[1]{>{\raggedright\arraybackslash}p{#1}}
\usepackage{tikz}
\usepackage{pgfplots}
\pgfplotsset{compat=1.18}
\usepackage{tikz-3dplot}
\usetikzlibrary{shapes.geometric, arrows.meta, positioning, shadows, fit, backgrounds}
\usepackage{tabularx,longtable,booktabs}
\usepackage{graphicx}
\usepackage{hyperref}
\hypersetup{colorlinks=true,linkcolor=blue,urlcolor=blue,citecolor=blue}
\usepackage{cleveref}
\usepackage{titlesec}
\usepackage{float}

\pagestyle{fancy}
\fancyhf{}
\lhead{TLM Not Obviously False}
\rhead{\thepage}
\title{Why the Timeless Light Model is Not Obviously False}
\usepackage{orcidlink}
\author{John C. W. McKinley\orcidlink{0009-0005-7097-5035}\\Independent Researcher}
\date{Septepber 14, 2025}

\begin{document}
\maketitle


\begingroup
  \footnotetext[0]{This version published at
  \href{https://10.5281/zenodo.17118184}{https://doi.org/10.5281/zenodo.17118184}.}
\endgroup



\begin{abstract}
The Timeless Light Model (TLM) proposes that photons are not travelers within spacetime, but timeless emission--absorption instructions resolved in a senior Quantum Platform (QP) and rendered in a Spacetime Deployment Frame (SDF). This paper does not argue that TLM is true. Instead, it argues that TLM is \emph{not obviously false}: it follows directly from Special Relativity (SR) invariants, it resolves familiar paradoxes (entanglement, pathfinding), and it yields falsifiable predictions, including achromatic timing residuals, gravitational-wave micro-steps, and the strict exclusion of orphan photons. Building on the foundational case in \cite{prior}, we strengthen the argument with recent refinements (e.g., Emission Delay Law) and 30 falsifiability tests. We present the logic, situate the model among standard formalisms, give \emph{rigorous derivations}, and list proposed tests.
\end{abstract}

\section{Introduction}
Extending the foundational case for consideration in \cite{prior}, this paper argues TLM is not obviously false by demonstrating consistency with SR invariants, paradox resolutions, and falsifiable tests. With recent extensions like EDL \cite{edl}, TLM now resolves apparent prohibitions (e.g., eternal excited states). For consolidated axioms, see \cite{tlmv2}.

Novel ontologies often meet a reflexive charge of being ``obviously false.'' The modest claim here is narrower: TLM is consistent with accepted SR invariants, preserves successful calculations, explains several puzzles more directly, and makes concrete, falsifiable predictions. Those criteria warrant empirical attention rather than dismissal \citep{rovelli1996}.

\section{Foundations of TLM}
TLM builds from a compact set of axioms (based on Appendix A of \cite{prior}, enhanced with EDL and no mid-flight energy):

\begin{axiombox}{TLM Axioms}
\begin{enumerate}
  \item Frameless quanta: Photons are not in-transit objects; they exist only as emission (E) and absorption (A) ticks recorded in a senior substrate (QP).
  \item Frames belong to observers: Time, space, and causal ordering are properties of the SDF the observer inhabits.
  \item Bridge laws: Mass imposes deployment delay, \(T \cdot m = \hbar/c^{2}\). Causal resolution rate is fixed, \(T \cdot C_{s} = 1\).
  \item Binary law (location is a 0/1 toggle): a photon is at the emitter (0) or at the absorber (1); no divisible ``half-photons'' \cite{binary_law}.
  \item Single-absorber principle: each photon resolves to exactly one absorber; no orphans \cite{pairing}.
  \item Emission Delay Law (EDL): Emission is delayed until a compatible absorber condition is met \cite{edl}.
  \item Horizon as Rendering Limit: Black hole horizons limit rendering, predicting specific behaviors \cite{prior}.
\end{enumerate}
\end{axiombox}

Hilbert space remains as the frame-level representation of rendered outcomes (not the substrate itself) \cite{hilbert}. Historical absorber intuitions are disentangled from TLM (no advanced waves; no universal absorber boundary) \cite{wfat}.

\section{Concise Figures}\label{sec:figures}
The following figures summarize the two-filter pipeline, test ideas, and additional diagrams from foundational work.

\begin{figure}[p]
\centering
\rotatebox{90}{%
  \resizebox{0.95\textheight}{!}{%
\begin{tikzpicture}[
    node distance=4.8cm,
    blk/.style={draw, rounded corners, thick, minimum width=3.2cm, minimum height=1.05cm, align=center, fill=gray!10},
    arr/.style={-{Latex}, thick}
]
\node[blk, fill=blue!8] (qp) {QP: Instruction $\,\mathcal{I}(A,B)$\\\small (timeless)};
\node[blk, right=of qp, fill=orange!10] (qm) {QM Structural Filter\\\small mask $\mathcal{M}[\psi] \rightarrow |\psi|^2$};
\node[blk, right=of qm, fill=yellow!15] (gr) {GR Delay Kernel\\\small $K_T(\cdot\,;\,m,\Phi)$};
\node[blk, right=of gr, fill=green!12] (sdf) {SDF Render\\\small observable events};

\draw[arr] (qp) -- node[above]{\small admissible endpoints} (qm);
\draw[arr] (qm) -- node[above]{\small structure fixed} (gr);
\draw[arr] (gr) -- node[above]{\small sequencing \& timing} (sdf);

\node[align=left, below=1.2cm of qm] {\small\textbf{Invariant:} $|\psi|^2$ unaffected by $K_T$};
\node[align=left, below=1.2cm of gr, xshift=4.2cm] {\small\textbf{Variant:} arrival times set by $K_T$};
\end{tikzpicture}%
  }% resizebox
}% rotatebox
\caption{TLM two-filter pipeline: QM fixes \emph{what} can render; GR fixes \emph{when/how} it renders.}
\label{fig:two_filter_pipeline}
\end{figure}

\begin{figure}[H]
\centering
\begin{tikzpicture}
    \begin{axis}[
        width=12cm, height=5.4cm,
        xlabel={Screen position $y$ (arb.)},
        ylabel={Normalized intensity $I(y)$},
        title={Interference geometry unchanged; timing shifts only},
        xmin=-6, xmax=6, ymin=0, ymax=1.05,
        grid=both, legend pos=north east, legend cell align=left,
        ytick={0,0.5,1}
    ]
    \addplot[ultra thick, blue, samples=400, domain=-6:6]
        {(cos(deg(2*pi*0.35*x))^2)*exp(-0.11*x^2)};
    \addlegendentry{$g_1$: $|\psi|^2$}

    \addplot[ultra thick, red, dashed, samples=400, domain=-6:6]
        {(cos(deg(2*pi*0.35*x))^2)*exp(-0.11*x^2)};
    \addlegendentry{$g_2$: $|\psi|^2$ (pred. same)}
    \end{axis}

    \begin{axis}[
        at={(0cm,-3.6cm)}, anchor=north west,
        width=12cm, height=4.2cm,
        xlabel={Arrival time $t$ (arb.)},
        ylabel={Counts},
        xmin=0, xmax=10, ymin=0, ymax=1.05,
        grid=both, legend pos=north east, legend cell align=left
    ]
    \addplot[ultra thick, blue, samples=300, domain=0:10]
        {exp(-((x-4.0)^2)/(2*0.6^2))};
    \addlegendentry{$g_1$: earlier}

    \addplot[ultra thick, red, dashed, samples=300, domain=0:10]
        {exp(-((x-6.0)^2)/(2*0.6^2))};
    \addlegendentry{$g_2$: delayed}
    \end{axis}
\end{tikzpicture}
\caption{TLM: $|\psi|^2$ is structural (invariant); only arrival-time statistics shift with gravitational delay.}
\label{fig:ds_gr_invariance}
\end{figure}

\begin{figure}[H]
\centering
\rotatebox{90}{%
  \resizebox{0.95\textheight}{!}{%
\begin{tikzpicture}[
    node distance=1.8cm and 1.6cm,
    box/.style={draw, rounded corners, thick, align=center, minimum width=2.6cm, minimum height=1.0cm, fill=gray!10},
    meas/.style={draw, rounded corners, thick, align=center, minimum width=2.8cm, minimum height=1.0cm, fill=blue!10},
    arr/.style={-{Latex}, thick}
]
\node[box] (spdc) {SPDC Source\\(entangled photons)};
\node[box, right=of spdc] (bs) {Polarization\\Routing};

\node[meas, above right=1.2cm and 2.0cm of bs] (A) {Detector A\\(lightweight)};
\node[meas, below right=1.2cm and 2.0cm of bs] (B) {Detector B\\(massive)\\{\small add ballast $M$}};

\node[box, right=3.2cm of bs] (clk) {Sync: PPS /\\common clock};
\node[box, right=of clk] (cc) {Coincidence\\ Counter};

\draw[arr] (spdc) -- (bs);
\draw[arr] (bs) |- (A.west);
\draw[arr] (bs) |- (B.west);

\draw[arr] (A.east) -- ++(1.0,0) |- (cc.west);
\draw[arr] (B.east) -- ++(1.0,0) |- (cc.west);

\draw[arr] (clk.east) -- (cc.west);
\draw[arr] (clk.west) -- (bs.north);

\node[align=center, below=0.1cm of B] {\small Predicted shift: $\Delta t \simeq GM/c^3$};
\end{tikzpicture}
}
}

\caption{Mass-dependent entanglement latency test: vary $M$ at B and track the minimal coincidence window that preserves correlations.}
\label{fig:latency_setup}
\end{figure}

\begin{figure}[H]
\centering
\begin{tikzpicture}
    \begin{axis}[
        width=12cm, height=7cm,
        xlabel={Detector mass $M$ (kg)},
        ylabel={Predicted latency $\Delta t$ (s)},
        title={TLM prediction: $\Delta t \approx \dfrac{G M}{c^3}$},
        xmin=0, xmax=2000, ymin=0, ymax=8e-24,
        grid=both,
        legend pos=north west,
        scaled y ticks=false,
        ytick={0,2e-24,4e-24,6e-24,8e-24},
        yticklabels={$0$,$2\times10^{-24}$,$4\times10^{-24}$,$6\times10^{-24}$,$8\times10^{-24}$}
    ]
    \addplot[ultra thick, blue, domain=0:2000, samples=2]
        {6.674e-11 * x / (2.99792458e8)^3};
    \legend{$\Delta t = \dfrac{G M}{c^3}$}
    \addplot+[only marks, mark=*, mark size=2pt]
        coordinates {(5,6.2e-27) (50,6.2e-26) (500,6.2e-25) (1500,1.9e-24)};
    \end{axis}
\end{tikzpicture}
\caption{Order-of-magnitude scaling: absolute values are tiny; use differential metrology and long integration.}
\label{fig:latency_vs_mass}
\end{figure}

\begin{figure}[H]
\centering
\begin{tikzpicture}[x=1cm,y=1cm,>=Latex]
  % SDF curved sheet
  \begin{scope}
    \draw[gray!60, line width=0.6pt]
      plot[smooth] coordinates {(-5,0) (-4,-0.2) (-3,0.1) (-2,-0.1) (-1,0.15) (0,0) (1,-0.15) (2,0.1) (3,-0.2) (4,0.05) (5,0)};
    % grid on the sheet
    \foreach \x in {-5,-4,...,5}{
      \draw[gray!30] (\x,-0.8) -- ++(0,1.6);
    }
    \foreach \y in {-0.6,-0.3,0,0.3,0.6}{
      \draw[gray!30] (-5,\y) -- (5,\y);
    }
    \node[anchor=south west,gray!60] at (-5.0,0.65) {SDF: spacetime (GR/SR/QM)};
  \end{scope}

  % Emission and absorption points on SDF
  \fill[blue!70] (-3,0.1) circle (2pt) node[above left=2pt] {\footnotesize Emission};
  \fill[red!70]  (3,-0.2) circle (2pt) node[below right=2pt] {\footnotesize Absorption};

  % Null-like curved path (rendered path)
  \draw[thick,black!70,decorate,decoration={snake,amplitude=0.4mm,segment length=3mm}]
    (-3,0.1) to[bend left=10] (3,-0.2);
  \node[black!70,fill=white,inner sep=1pt] at (0,0.35) {\footnotesize Rendered null path (SDF)};

  % QP box (ledger) above
  \draw[rounded corners=3pt, very thick, black!70, fill=gray!10]
    (-5.2,5.6) rectangle (4.8,2.7);
  \node[align=center] at (-1.5,5) {\textbf{Quantum Platform (QP)}\\ \footnotesize timeless ledger of completed links};

  % Record arrow from SDF endpoints to QP
  \draw[->,thick] (-3,0.1) .. controls (-3,1.5) and (-2.5,2.6) .. (-1.5,3.0);
  \draw[->,thick] ( 3,-0.2) .. controls ( 3,1.5) and ( 2.5,2.6) .. ( 1.5,3.0);

  % Ledger entry inside QP
  \node[rectangle,draw,rounded corners=2pt,fill=white,align=left,anchor=north west,scale=0.9] at (-2.4,4.2)
    {\footnotesize \textbf{Record:}\\[-2pt]
     \footnotesize (Emission@SDF, Absorption@SDF)\\[-2pt]
     \footnotesize \emph{No time, no path, no metric}};
  % Down arrows back to SDF label
  \node[align=center] at (0,2.2) {\footnotesize SDF renders delays:\\[-2pt]
    \footnotesize baseline $c$ + mass/geometry};

  \draw[->,thick] (0,3.0) -- (0,0.8);

\end{tikzpicture}
\caption{3D QP/SDF from foundational work (adapted from \cite{prior} Fig. 1).}
\label{fig:3d_qp_sdf}
\end{figure}

\begin{figure}[H]
\centering
\begin{tikzpicture}[font=\small,
  node distance=1.8cm and 3cm,
  box/.style={draw, rounded corners, minimum width=3.5cm, minimum height=1cm, align=center, fill=gray!10},
  inst/.style={draw, circle, minimum size=1cm, fill=blue!10},
  arrow/.style={->, thick},
  labelbox/.style={draw, rectangle, fill=yellow!20, text width=4.5cm, rounded corners, font=\footnotesize, align=left}
]

\node[box] (qp) at (0,6.5) {Quantum Platform (QP)};
\node[inst] (ciarc) at (0,3.5) {CI-ARC};
\node[box] (sdf) at (0,0.5) {Spacetime Deployment Frame (SDF)};

\draw[arrow] (qp) -- (ciarc) node[midway, right=3pt] {\scriptsize Instruction};
\draw[arrow] (ciarc) -- (sdf) node[midway, right=3pt] {\scriptsize Rendered Event};

\node[labelbox, right=3.5cm of qp] (qlabel) {
\textbf{Quantum Platform (QP):} \\
Timeless, instruction-emitting layer outside of spacetime. No duration, only resolved intent.
};

\node[labelbox, right=3.5cm of ciarc] (cilabel) {
\textbf{CI-ARC:} \\
Causal Instruction Arc. Not a particle or wave, but a resolved link between emitter and absorber.
};

\node[labelbox, right=3.5cm of sdf] (slabel) {
\textbf{Spacetime Deployment Frame (SDF):} \\
Where events are experienced. Time, mass, and measurement occur here as delayed renderings.
};

\draw[dashed] (-5,1.5) -- (5,1.5);
\node at (-4.8,1.7) {\footnotesize Time begins};
\node at (-4.8,4.7) {\footnotesize Timeless};

\end{tikzpicture}
\caption{Instructional flow from the Timeless QP to observable SDF, via a CI-ARC (adapted from \cite{prior} Fig. 4).}
\label{fig:instruction_flow}
\end{figure}

\begin{figure}[H]
\centering
\begin{tikzpicture}
  \draw (0,0) arc (0:180:2) node[midway,above] {Timeless Arc};
  \node at (-2,0) {E};
  \node at (2,0) {A};
\end{tikzpicture}
\caption{Timeless arc (adapted from \cite{prior} Fig. 3).}
\label{fig:timeless_arc}
\end{figure}

\begin{figure}[H]
\centering
\begin{tikzpicture}
  \node (qp) {QP};
  \node [below of=qp] (ciarc) {CI-Arc};
  \node [below of=ciarc] (sdf) {SDF};
  \draw [->] (qp) -- (ciarc);
  \draw [->] (ciarc) -- (sdf);
\end{tikzpicture}
\caption{Hierarchy (adapted from \cite{prior} Fig. 4).}
\label{fig:hierarchy}
\end{figure}

\begin{figure}[H]
\centering
\begin{tikzpicture}
  \node (a1) {Axiom 1: Frameless Quanta};
  \node [below=of a1] (a2) {Axiom 2: Framed Observers};
  \node [below=of a2] (a3) {Axiom 3: Bridge Laws};
  \node [below=of a3] (a4) {Axiom 4: Binary Law};
  \node [below=of a4] (a5) {Axiom 5: Single-Absorber};
  \node [below=of a5] (a6) {Axiom 6: EDL};
  \node [below=of a6] (a7) {Axiom 7: Horizon Limit};
  \draw [->] (a1) -- (a2);
  \draw [->] (a2) -- (a3);
  \draw [->] (a3) -- (a4);
  \draw [->] (a4) -- (a5);
  \draw [->] (a5) -- (a6);
  \draw [->] (a6) -- (a7);
\end{tikzpicture}
\caption{Axiom flow (adapted from \cite{prior} Fig. 5).}
\label{fig:axiom_flow}
\end{figure}

\begin{figure}[H]
\centering
\begin{tikzpicture}
  \begin{axis}[title={LIGO Residual},
    xlabel={Time (s)},
    ylabel={Strain},
    width=12cm, height=7cm,
    grid=both]
    \addplot[blue, thick] coordinates {
      (0,0) (1,0.1) (1,0) (2,-0.05) (2,0.1) (3,0) (3,-0.1) (4,0.05) (4,0)
    };
  \end{axis}
\end{tikzpicture}
\caption{LIGO residual showing potential micro-steps (adapted from \cite{prior} Fig. 6).}
\label{fig:ligo_residual}
\end{figure}

\begin{figure}[H]
\centering
\begin{tikzpicture}
  \begin{axis}[title={Decoherence Rate},
    xlabel={Time},
    ylabel={Coherence},
    width=12cm, height=7cm,
    grid=both]
    \addplot[red, thick] {exp(-x)};
  \end{axis}
\end{tikzpicture}
\caption{Decoherence curve (adapted from \cite{prior} Fig. 7).}
\label{fig:decoherence}
\end{figure}

\section{Why It Is Not Obviously False}
\subsection{Built on accepted invariants}
For photons, \(m=0\) and the invariant interval is null: \(ds^{2} = c^{2}\Delta t^{2} - \Delta x^{2} = 0\). Proper time is \(\tau = s/c = 0\) \cite{einstein1905,wald}. With no proper time, nothing intrinsic to a photon can evolve ``in flight.'' TLM takes this seriously and drops traveler language in favor of endpoint resolution \cite{quanta_global}. As in \cite{prior} Section 1, photon null-time is a key invariant.

\subsection{Resolves familiar paradoxes}
\emph{Entanglement}: correlations are co-resolutions of a single timeless instruction; no superluminal signaling in spacetime is required. \emph{Pathfinding}: no mid-path state must ``know'' where to go. \emph{Wave--particle duality}: interference is rendered geometry in the SDF, not a photon property \cite{cornerstone}.

Expanded from \cite{prior} Section 3, measurement as rendering resolves collapse issues. EDL resolves 'eternal atom' critiques by delaying, not prohibiting, emission \cite{edl}.

\subsection{Compatible with standard formalisms}
Hilbert space remains as the frame-level representation of rendered outcomes (not the substrate itself) \cite{hilbert}. TLM's transactional-like resolution in QP echoes aspects of Cramer's transactional interpretation \cite{cramer1986}, but emphasizes timelessness over advanced/retarded waves.

\subsection{Distinct from Wheeler--Feynman}
TLM assumes no advanced solutions, no universe-wide absorber. It replaces untouchable global boundary conditions with falsifiable local principles: no emission without a compatible absorber; no photon splits \cite{wfat,pairing,binary_law,wheeler1945}. While sharing the absorber motif, TLM avoids the paradoxes of retrocausality by situating resolutions in a timeless QP.

\subsection{Operational Support: No Mid-Flight Energy}
From operational facts (no extractable energy mid-path) and \cite{prior} no-propagation postulate, energy is inaccessible mid-path due to timeless ontology. This aligns with no in-flight interactions without absorption, supporting TLM's frameless quanta.

\section{Explaining the Absence of Paradoxes}
\label{sec:paradox}
A potential paradox in TLM arises from the notion that the instruction is written ``after'' absorption, seemingly implying retrocausality. This could violate causality principles.

However, TLM resolves this through timelessness and layer seniority.

\subsection{Timelessness Eliminates Temporal Sequence}
In the QP, there is no time, so ``before,'' ``after,'' or causation do not apply. The emission-absorption pair is resolved as a single unit. The instruction is defined holistically.

Analogously, \(E = mc^2\) holds timelessly. Similarly, in QP, energy changes are equated acausally.

In SDF, this deploys as a causal chain, but QP ensures consistency without backward flow.

\subsection{Seniority of QP to SDF}
QP is fundamental, unconstrained by SDF rules. GR, SR, QM emerge during deployment.

This mirrors QM's handling of entanglement: correlations without causal influence. Collapse occurs in timeless QP, preserving SDF causality.

\subsection{Avoiding Retrocausality}
Retrocausality would require future altering past within the same framework. In TLM, frameworks are separated. No rewriting of past; past defined with future in mind from QP, deployed causally in SDF.

EDL integrates: delays emission until absorber ready, avoiding eternal states \cite{edl}.























\section{Critiques and Comparisons}
As in \cite{prior} Section 7.3, compare to timeless physics (e.g., Barbour's shape space \cite{barbour1994}) and constructor theory \cite{deutsch2013}.

TLM differs from timeless physics by having active QP authorship rather than static configurations.

Vs. constructor theory: TLM instructions as timeless constructors, specifying possible tasks without dynamical laws as primitives.

Address ``non-empirical re-labeling'' by emphasizing new tests like delayed decays.

\section{Proposed Experimental Tests}
TLM predicts achromatic residuals or micro-structure. Parameterize with coefficients (GR/QM value zero, positive by delay ontology). Prioritize key tests; full 30 in Appendix.

\subsection{Gravitational-Wave Phase/Micro-step Residuals}
Definition: Residual \(r(t)=h(t)-h_{\rm GR}(t)\), \(\Delta\phi(f)\approx\alpha_T \frac{dT_{\rm eff}}{dt} \tau_{\rm cycle}(f)\), \(\alpha_T>0\).

Pipeline: Template fit, residuals, changepoint on r(t), phase-tracking.

Targets: \(\alpha_T \sim 10^{-5}-10^{-3}\) rad/cycle.

Falsifier: No coherent steps, \(\Delta\phi\) noise-consistent.

\subsection{Strong-Lensing Time-Delay Residuals}
\(\Delta t^{\rm obs}_{ij}=\Delta t^{\rm GR}_{ij}+\beta_T \frac{L^{(i)}-L^{(j)}}{c}\), \(\beta_T>0\).

Pipeline: Delays, modeling, remove plasma, geometry-locked residual.

Targets: \(10^{-13}-10^{-12}\) s.

Falsifier: Zero within systematics.

\subsection{Cosmological Redshift Drift}
\(\dot z_{\rm obs}= \dot z_{\Lambda{\rm CDM}}+\gamma_T \frac{dT}{dt}|_{\mathcal{C}}\), \(\gamma_T>0\).

Pipeline: Spectroscopy, fit for offset.

Targets: \(10^{-10} \rm yr^{-1}\).

Falsifier: \(\gamma_T=0\).

\subsection{Shapiro Echo Perturbations}
\(\Delta t_{\rm echo}= \Delta t_{\rm Shapiro} + k_T \int \nabla T \cdot dl\), \(k_T>0\).

Pipeline: Ephemeris, fit Shapiro, path-integrated residual.

Targets: \(10^{-6}-10^{-9}\) s.

Falsifier: No residual.

\subsection{Engineered Clock Gradients}
\(\frac{\Delta\nu}{\nu}=(\frac{\Delta\nu}{\nu})_{\rm GR} + \eta_T \Delta T_{\rm shell}\), \(\eta_T>0\).

Pipeline: Mass shells, compare clocks, modulate.

Targets: \(10^{-18}-10^{-19}\).

Falsifier: Null modulation.

\subsection{Interferometer With Inertial Load}
\(\Delta\phi = \frac{2\pi}{\lambda} [L + \xi_T \int T(r) dl]\), \(\xi_T>0\).

Pipeline: Calibrate phase, vary load, extra phase.

Targets: Instrument-limited.

Falsifier: No surplus.

\subsection{CMB High-$\ell$ Non-Gaussian Tails}
\(K_\ell = K^{\Lambda{\rm CDM}}_\ell + \zeta_T F_\ell[T]\), \(\zeta_T>0\).

Pipeline: Higher-order statistics, non-Gaussian tails.

Targets: Survey-limited.

Falsifier: Gaussian after foregrounds.

\subsection{Entanglement Coincidence Widths}
\(\Delta\tau_{\rm pairs}=\Delta\tau_{\rm QM}+\chi_T \rm Var[T]\), \(\chi_T>0\).

Pipeline: Dispersion compensation, fit broadening.

Targets: fs-ps.

Falsifier: No broadening.

Add EDL test: Delayed decays in absorber-free setups.

Definition: Decay rate suppression without absorbers.

Pipeline: Isolate excited atoms, monitor emission times.

Targets: Statistically significant delay.

Falsifier: Standard exponential decay.











% --- Practical Feasibility Block (paste where you discuss tests, e.g., after Section "Proposed Experimental Tests") ---
\section{Practical Feasibility of Two Key Tests}\label{sec:feasibility}

To bridge the gap between theory and practice, we briefly assess whether two representative tests are achievable with current or near-term technology.

\subsection*{(A) Engineered Clock Gradients / Mass-Shell Modulation}
\textbf{Signal targeted.} A tiny, achromatic timing or frequency shift induced by a controlled local delay field (Sec.~\ref{sec:tests} claims).\\
\textbf{Status.}
\begin{itemize}[leftmargin=*]
  \item \emph{Achievable now:} State-of-the-art optical lattice clocks routinely reach fractional instabilities and accuracies at the $\sim\!10^{-18}$ level over practical averaging times. Differential comparisons over short baselines (meters to tens of meters) with active environmental stabilization are within current lab capabilities.
  \item \emph{Near-term upgrades:} Networked optical clocks linked by phase-stabilized fiber and cavity-enhanced time-transfer can plausibly push sensitivity toward low $10^{-19}$. Purpose-built “mass-shell” fixtures (known geometry, movable load) and lock-in style modulation (on/off at mHz–Hz) can extract coherent, achromatic signatures below static systematics.
  \item \emph{Breakthroughs likely not required:} The limiting factors are engineering---vibration isolation, thermal gradients, refractive-index control, and gravity-potential modeling---rather than new physics instrumentation. A carefully designed differential protocol (two identical stacks, anti-correlated loading) can suppress common-mode drifts.
\end{itemize}

\noindent\textbf{Bottom line.} A first-pass null or positive constraint on the proposed delay term appears feasible with existing optical-clock technology plus standard precision-metrology techniques (lock-in detection, differential referencing).

\vspace{0.6em}
\subsection*{(B) GW Phase Micro-Steps / Residual Structure (LIGO/Virgo/KAGRA)}
\textbf{Signal targeted.} Sub-cycle, step-like or excess-kurtosis residuals in strain phase after best-fit template subtraction (Sec.~\ref{sec:tests}).\\
\textbf{Status.}
\begin{itemize}[leftmargin=*]
  \item \emph{Achievable now (analysis-side):} Re-analysis of public O3–O4 events with change-point detectors, heavy-tail tests, and coherent multi-detector residual stacking is immediately possible. This sets empirical upper bounds on any step-like component without touching hardware.
  \item \emph{Near-term hardware:} Scheduled sensitivity improvements (squeezing, thermal noise reduction, improved coatings and control) increase SNR for high-mass and long-duration signals, making subtle, coherent residuals more testable. Joint pipelines across LIGO/Virgo/KAGRA can enforce cross-site coherence tests that reject instrumental artifacts.
  \item \emph{Next-gen leverage:} Cosmic Explorer / Einstein Telescope will deliver order-of-magnitude SNR gains and longer in-band durations, dramatically improving change-point power. No fundamentally new detection principle is required—just higher SNR and disciplined residual statistics.
\end{itemize}

\noindent\textbf{Bottom line.} A statistically robust \emph{null test} is already practical via re-analysis; decisive discovery space opens with next-gen detectors, but does not require a breakthrough in methodology.

\vspace{0.6em}
\subsection*{Takeaway}
Across clocks and gravitational waves, the first generation of TLM-motivated tests can be framed as \emph{differential, achromatic, and modulation-friendly} null experiments. One path (optical clocks) is laboratory-ready; the other (GW micro-structure) benefits immediately from analysis on existing data and scales strongly with detector upgrades rather than unknown technology.
% --- end feasibility block ---
















\subsection{Summary Table}
\begin{longtable}{llll}
\hline
Domain & Coefficient & Target sensitivity & Falsifier \\
\hline
\endhead
GW phase/steps & $\alpha_T>0$ & $10^{-5}$--$10^{-3}$ rad/cycle & Null steps \& $\Delta\phi$ at floor \\
Strong lensing & $\beta_T>0$ & $10^{-13}$--$10^{-12}$ s & No achromatic common-mode term \\
Redshift drift & $\gamma_T>0$ & few$\times10^{-10}\,\rm yr^{-1}$ & $\gamma_T=0$ within errors \\
Shapiro echo & $k_T>0$ & $10^{-9}$--$10^{-6}$ s & No path-integral residual \\
Clock shells & $\eta_T>0$ & $10^{-18}$--$10^{-19}$ & Lock-in null at precision \\
Interferometer & $\xi_T>0$ & instrument-limited & No load-locked achromatic phase \\
CMB tails & $\zeta_T>0$ & survey-limited & $\zeta_T=0$ after foregrounds \\
Entanglement & $\chi_T>0$ & fs--ps & No achromatic broadening \\
EDL decays & $\delta_T>0$ & emission statistics & Standard decay rates \\
\hline
\caption{Adapted from \cite{prior} Table 1, with added coefficients.}
\label{tab:tests}
\end{longtable}




















\section{Falsifiability}
Clear disproofs: (i) orphan photon; (ii) photon splitting; (iii) photon proper-time; (iv) null bounds on residuals \cite{pairing,binary_law,edl,cornerstone,quanta_global}.

\section{Conclusion}
Echoing \cite{prior}, we call for empirical evaluation over dismissal. TLM is not obviously false and offers clean empirical forks.


\bibliographystyle{plainnat}
\begin{thebibliography}{99}

\bibitem{prior}
J.~C.~W. McKinley,
\textit{Why the Timeless Light Model Deserves Scientific Consideration: A Foundational Framework with Derivations, Critiques, and Experimental Proposals (v1.3)},
\emph{Zenodo} (2025).
\href{https://doi.org/10.5281/zenodo.16724187}{doi:10.5281/zenodo.16724187}.

\bibitem{edl}
J.~C.~W. McKinley, \textit{The Emission Delay Law: A General Principle for the Realization of Quanta in TLM}, \emph{Zenodo} (2025).
\href{https://doi.org/10.5281/zenodo.17032235}{doi:10.5281/zenodo.17032235}.

\bibitem{tlmv2}
J.~C.~W. McKinley, \textit{Timeless Light Model (TLM v2.0): Frameless Quanta, Framed Observers, and Bridge Laws}, \emph{Zenodo} (2025).
\href{https://doi.org/10.5281/zenodo.16934697}{doi:10.5281/zenodo.16934697}.

\bibitem{hilbert}
J.~C.~W. McKinley, \textit{Hilbert Space as Frame Representation: A TLM Reinterpretation}, \emph{Zenodo} (2025).
\href{https://doi.org/10.5281/zenodo.17070118}{doi:10.5281/zenodo.17070118}.

\bibitem{wfat}
J.~C.~W. McKinley, \textit{Timeless Light Model vs Wheeler--Feynman Absorber Theory: A Disambiguation (v5.0)}, \emph{Zenodo} (2025).
\href{https://doi.org/10.5281/zenodo.16924316}{doi:10.5281/zenodo.16924316}.

\bibitem{quanta_global}
J.~C.~W. McKinley, \textit{Quanta are Global, Frames are Local: A Rosetta Statement of the Timeless Light Model (v1.0)}, \emph{Zenodo} (2025).
\href{https://doi.org/10.5281/zenodo.16917106}{doi:10.5281/zenodo.16917106}.

\bibitem{binary_law}
J.~C.~W. McKinley, \textit{The Binary Law of Quanta: Location as a Timeless Choice}, \emph{Zenodo} (2025).
\href{https://doi.org/10.5281/zenodo.16913425}{doi:10.5281/zenodo.16913425}.

\bibitem{pairing}
J.~C.~W. McKinley, \textit{Generalized Pairing Law: No Quantum Emission Without an Absorber}, \emph{Zenodo} (2025).
\href{https://doi.org/10.5281/zenodo.16892099}{doi:10.5281/zenodo.16892099}.

\bibitem{cornerstone}
J.~C.~W. McKinley, \textit{Deriving Cornerstone Equations from TLM Axioms}, \emph{Zenodo} (2025).
\href{https://doi.org/10.5281/zenodo.16596589}{doi:10.5281/zenodo.16596589}.

\bibitem{einstein1905}
A.~Einstein, \textit{Zur Elektrodynamik bewegter Körper}, \emph{Annalen der Physik} \textbf{17}, 891--921 (1905).
\href{https://doi.org/10.1002/andp.19053221004}{doi:10.1002/andp.19053221004}.

\bibitem{wald}
R.~M. Wald, \textit{General Relativity} (University of Chicago Press, Chicago, 1984).
% (Book; DOI typically not used.)

\bibitem{jacobson1995}
T.~Jacobson, \textit{Thermodynamics of spacetime: The Einstein equation of state}, \emph{Phys. Rev. Lett.} \textbf{75}, 1260--1263 (1995).
\href{https://doi.org/10.1103/PhysRevLett.75.1260}{doi:10.1103/PhysRevLett.75.1260}.

\bibitem{caticha2011}
A.~Caticha, \textit{Entropic dynamics, time and quantum theory}, \emph{J. Phys. A: Math. Theor.} \textbf{44}, 225303 (2011).
\href{https://doi.org/10.1088/1751-8113/44/22/225303}{doi:10.1088/1751-8113/44/22/225303}.

\bibitem{cramer1986}
J.~G. Cramer, \textit{The transactional interpretation of quantum mechanics}, \emph{Rev. Mod. Phys.} \textbf{58}, 647--687 (1986).
\href{https://doi.org/10.1103/RevModPhys.58.647}{doi:10.1103/RevModPhys.58.647}.

\bibitem{barbour1994}
J.~B. Barbour, \textit{The timelessness of quantum gravity: I. The evidence from the classical theory}, \emph{Class. Quantum Grav.} \textbf{11}, 2853--2873 (1994).
\href{https://doi.org/10.1088/0264-9381/11/12/005}{doi:10.1088/0264-9381/11/12/005}.

\bibitem{deutsch2013}
D.~Deutsch, \textit{Constructor theory}, arXiv:1210.7439 (2013).
\href{https://arxiv.org/abs/1210.7439}{arXiv:1210.7439}.

\bibitem{rovelli1996}
C.~Rovelli, \textit{Relational quantum mechanics}, \emph{Int. J. Theor. Phys.} \textbf{35}, 1637--1678 (1996).
\href{https://doi.org/10.1007/BF02302261}{doi:10.1007/BF02302261}.

\bibitem{wheeler1945}
J.~A. Wheeler and R.~P. Feynman, \textit{Interaction with the absorber as the mechanism of radiation}, \emph{Rev. Mod. Phys.} \textbf{17}, 157--181 (1945).
\href{https://doi.org/10.1103/RevModPhys.17.157}{doi:10.1103/RevModPhys.17.157}.

\end{thebibliography}


\appendix




\section{Formal Derivations and Consistency Checks}

This appendix provides the mathematical formalism for the Timeless Light Model (TLM). The goal is to demonstrate that its core axioms are not \emph{ad hoc} but are motivated by fundamental physical principles and can be formalized using standard methods of theoretical physics. We make explicit connections to show that the TLM framework is consistent with the validated predictions of Special Relativity (SR), General Relativity (GR), and Quantum Mechanics (QM).

\subsection{Motivation for the Mass--Time Reciprocity Axiom}

The foundational TLM axiom asserts a reciprocal relationship between the deployment delay $T$ and a particle's invariant mass $m$:
\begin{equation}
    T \cdot m = \frac{\hbar}{c^2}
\end{equation}

\paragraph{Physical Motivation.} This relationship is directly motivated by the \textbf{Compton frequency}, which defines an intrinsic timescale for any massive particle. The Compton frequency is given by $\omega_C = mc^2 / \hbar$. The corresponding period, a fundamental timescale associated with a particle's existence, is:
\begin{equation}
    T_C = \frac{1}{\omega_C} = \frac{\hbar}{mc^2}
\end{equation}
This suggests a deep connection between mass and an intrinsic clock. TLM promotes this observation to a foundational axiom by identifying this intrinsic timescale with the \textbf{deployment delay} $T$. This axiom posits that mass itself is the source of the delay experienced when a timeless quantum instruction is rendered into the Spacetime Deployment Frame (SDF).

For massless photons ($m=0$), this axiom correctly implies a zero deployment delay ($T=0$), consistent with their timeless, null-path nature in relativity.

\subsection{Definition of the Causal Resolution Rate}

To describe the rate at which instructions are rendered, we \textbf{define} a quantity called the \textbf{Causal Resolution Rate}, $C_s$, as the reciprocal of the deployment delay $T$:
\begin{equation}
    C_s \equiv \frac{1}{T}
\end{equation}
By this definition, the relation $T \cdot C_s = 1$ is a tautology, not a derived law. It is a definition that provides a useful "rate-based" perspective.

\paragraph{Physical Interpretation.} Substituting the mass-time axiom into this definition gives:
\begin{equation}
    C_s = \frac{mc^2}{\hbar} = \omega_C
\end{equation}
This shows that the Causal Resolution Rate is precisely the Compton frequency. This interpretation is consistent and intuitive: for \textbf{massive particles}, $C_s$ is finite, meaning their realization in spacetime is a rate-limited process.

\subsection{Lagrangian Constraint Formulation}

To embed the mass-time axiom into a dynamic theory, we use a \textbf{Lagrangian with a constraint}, a standard technique in field theory. We treat $T(x)$ and $m(x)$ as scalar fields and enforce the axiom using a Lagrange multiplier field $\lambda(x)$.
\begin{equation}
    \mathcal{L} = \frac{1}{2} m (\partial_\mu T)(\partial^\mu T) - V(m) + \lambda \left( T m - \frac{\hbar}{c^2} \left(1 + \frac{\Phi}{c^2}\right) \right)
\end{equation}

\paragraph{Justification of Terms.}
\begin{itemize}
    \item \textbf{Constraint Term:} The term multiplied by $\lambda$ enforces the mass-time axiom, here generalized to include the effects of a weak gravitational potential $\Phi$, consistent with gravitational time dilation.
    \item \textbf{Kinetic Term for T:} The term $\frac{1}{2} m (\partial_\mu T)(\partial^\mu T)$ models the dynamics of the delay field $T$. The mass field $m(x)$ acts as a coupling, physically representing the idea that the "stiffness" or dynamics of the delay field are sourced by the mass within it.
    \item \textbf{Potential Term V(m):} This term would govern the self-interaction or potential energy of the mass field itself.
\end{itemize}
Varying the action $S = \int d^4x\,\mathcal{L}$ with respect to $\lambda$ returns the constraint equation. Varying with respect to $T$ and $m$ gives the equations of motion, describing how the coupled fields propagate and interact.

\subsection{Consistency with Special \& General Relativity}

The TLM framework does not seek to derive relativity from scratch but to provide a different ontology that is fully consistent with its mathematical predictions.

\paragraph{Special Relativity.} For a particle moving with velocity $v$, its energy is $E = \gamma m c^2$. The observed phase evolution frequency is $\omega = E/\hbar = \gamma (mc^2/\hbar) = \gamma C_s$. The intrinsic resolution rate of the particle, $C_s$, is perceived by a moving observer to be dilated by the factor $\gamma$. TLM interprets this not as time slowing down for a traveling object, but as the frame-dependent rendering of a timeless instruction being affected by the relative motion of the observer.

\paragraph{General Relativity.} The Lagrangian already incorporates the weak-field gravitational potential $\Phi$, which correctly reproduces gravitational time dilation:
\begin{equation}
    T = \frac{\hbar}{mc^2} \left(1 + \frac{\Phi}{c^2}\right) \implies \frac{\Delta T}{T} \approx \frac{\Phi}{c^2}
\end{equation}
This shows consistency with the principle of equivalence. While the provided Lagrangian is insufficient to derive the full Einstein Field Equations, the model's core idea---that mass generates delay gradients in the surrounding space---is a reinterpretation of gravity. In TLM, what we perceive as spacetime curvature is an emergent effect of these underlying delay gradients in the SDF.

\subsection{Connection to Quantum Mechanics}

The phase factor of a quantum state, $\psi(t) \sim e^{-iEt/\hbar}$, is central to its dynamics. For a particle at rest, $E=mc^2$. The phase evolves as:
\begin{equation}
    \psi(t) \sim e^{-i(mc^2/\hbar)t} = e^{-iC_s t}
\end{equation}
The phase of a stationary particle evolves at a rate given precisely by the \textbf{Causal Resolution Rate}.

The full \textbf{Schrödinger Equation}, $i\hbar \partial_t \psi = \hat{H}\psi$, emerges when we include operators for kinetic and potential energy. TLM interprets this as follows: the rest-mass energy term represents the baseline rendering rate ($C_s$), while the kinetic and potential terms ($\hat{p}^2/2m + V(x)$) represent modifications to that rendering process due to motion and interactions within the SDF.






\section{Glossary}



No Mid-Flight Energy: No extractable energy in transit.


\begin{description}
  \item[CI‑Arcs] Causal‑Information Arcs: Internal mechanisms or syntactic processes within the Quantum Platform (QP) that may influence \emph{what} event is rendered (e.g., instruction selection or syntax). However, they do not create or modulate the GR playground; they operate within it, subject to delay effects imposed by QsubGR. CI‑Arcs handle deployment triggers but not the slowing laws of gravity or time dilation.
  
  \item[\(C_s\) (Causal Speed)] The rate at which timeless instructions from QP are resolved into sequential spacetime events in the Spacetime Deployment Frame (SDF). Inversely proportional to rendering delay \(T\), ensuring causality is preserved at or below the speed of light \(c\).
  
  \item[Delay Gradient] A localized variation in rendering delay induced by mass, creating the perceptual effect of gravitational attraction (e.g., the “space river” flowing inward). Delay decreases toward mass, drawing unresolved instructions toward equilibrium.




\item[Emission Delay Law (EDL)] A universal principle for all quanta. The EDL states that an excited state persists until a compatible paired condition becomes available, enabling the quantum transaction. The time an observer measures for this persistence is the "emission delay." This law is a necessary consequence of the TLM framework, providing a clear, falsifiable mechanism for quantum realization that applies to all quanta in all scenarios.

  
  
  \item[Geodesic] In GR, the straightest path in curved spacetime; in TLM, a path of least delay resolution, where free‑falling objects naturally progress toward lower‑delay states without force.
  
  \item[GR (General Relativity)] Einstein’s theory of gravity as spacetime curvature; in TLM, subordinated to QP as a descriptive geometry emerging from delay modulation, not a fundamental arena.

  \item[No Mid-Flight Energy] The principle that there is no accessible store of usable energy in the ``mid-flight'' path of a single photon between emission and absorption. principle reinforces that there is no energetic store along a path to be tapped. There is no mid-flight energy in the frame; instead, the Quantum Platform resolves a conservation-respecting pairing, and the frame renders two ends of one transaction. This positioning is compatible with EPR-style completeness concerns and Bell constraints.

  
  \item[QP (Quantum Platform)] The timeless, pre‑resolved layer that issues instructions for the universe. Ontologically senior to GR, QP operates outside spacetime, with all observables deploying from it via delayed rendering.
  
  \item[QsubGR] The GR‑modulated substrate: A delay‑imposing mechanism subordinate to QP, enforcing variable resolution rates (e.g., gravity, time dilation) to stretch instantaneous instructions into experiential sequences limited by \(c\).
  
  \item[Rendering Delay (\(T\))] The temporal lag in resolving QP instructions into the SDF, proportional to mass inverse (\(T \cdot m = \hbar / c^2\)). Exists purposefully for experience, unifying GR phenomena like time dilation and attraction.
  
  \item[SDF (Spacetime Deployment Frame)] The observable arena where delayed QP instructions manifest as spacetime events; equivalent to GR’s curved geometry but reinterpreted as a rendered projection, not intrinsic fabric.
  
  \item[Space River] A metaphor for GR’s inward‑flowing spacetime near mass (e.g., in black hole river models); in TLM, an engineered delay effect where space appears to “disappear” into planets to enforce rendering gradients, demystifying why stationary objects fall.
  
  \item[TLM (Timeless Light Model)] The overarching framework proposing that light (photons) is timeless, and the universe deploys from QP instructions via delays, providing causal “why” for GR’s descriptive “what.”
  
  \item[Timeless Instruction] A pre‑resolved directive from QP linking events (e.g., emission to absorption) without traversal; photons exemplify this, experiencing \(\tau = 0\) and resolving instantly (\(T = 0\)).
\end{description}




\section{Rejections}
(From \cite{prior} B)

Common rejections: ``Just re-labeling'' - countered by new tests.

``Violates causality'' - resolved by QP seniority.

``No math'' - see derivations.

\section{Thirty Falsifiability Tests}

\begin{enumerate}[leftmargin=*] % Use enumitem for better alignment

    \item \textbf{GW phase grain.}
    \begin{description}
        \item[Prediction] tiny step-like residuals in gravitational wave phases.
        \item[Method] cross-correlate multi-detector phase residuals after full waveform subtraction.
        \item[Fail] residuals remain fully Gaussian and scale as pure noise under increasing sensitivity.
    \end{description}

    \item \textbf{GW amplitude grain.}
    \begin{description}
        \item[Prediction] micro-jitter in amplitude envelopes.
        \item[Method] envelope demodulation and Allan deviation vs. SNR.
        \item[Fail] no deviation from smooth predictions beyond instrument noise.
    \end{description}

    \item \textbf{Pulsar timing steps.}
    \begin{description}
        \item[Prediction] non-Gaussian micro-steps in PTA residuals.
        \item[Method] heavy-tail tests on timing residuals.
        \item[Fail] residuals consistent with known noise models.
    \end{description}

    \item \textbf{Lunar laser ranging staircases.}
    \begin{description}
        \item[Prediction] quantized micro-delays in round-trip time beyond modeled systematics.
        \item[Method] histogram tests of time-transfer bins.
        \item[Fail] null after improved calibration.
    \end{description}

    \item \textbf{Clock redshift discreteness.}
    \begin{description}
        \item[Prediction] height-dependent redshift shows tiny steps at cm scale.
        \item[Method] optical lattice clocks on a precision elevator.
        \item[Fail] purely smooth redshift within error.
    \end{description}

    \item \textbf{Shapiro micro-steps.}
    \begin{description}
        \item[Prediction] step-like structure in solar conjunction delays.
        \item[Method] radio links during occultations.
        \item[Fail] smooth GR delay only.
    \end{description}

    \item \textbf{GPS staircase artifacts.}
    \begin{description}
        \item[Prediction] step signatures in space-to-ground time transfer after removing known effects.
        \item[Method] reanalysis of precise time series.
        \item[Fail] no steps beyond instrument artifacts.
    \end{description}

    \item \textbf{Fiber time-transfer grain.}
    \begin{description}
        \item[Prediction] micro-steps over stabilized fiber links.
        \item[Method] two-way time transfer at sub-ps.
        \item[Fail] no structure beyond thermal and servo noise.
    \end{description}

    \item \textbf{Optical cavity residuals.}
    \begin{description}
        \item[Prediction] quantized phase noise plateaus after subtraction.
        \item[Method] Pound-Drever-Hall residual analysis.
        \item[Fail] residuals track thermal noise only.
    \end{description}

    \item \textbf{Atom interferometer steps.}
    \begin{description}
        \item[Prediction] interferometric phase increments discretize with controlled \( g \) steps.
        \item[Method] drop-tower experiments.
        \item[Fail] smooth dependence only.
    \end{description}

    \item \textbf{Quantum Rabi staircasing.}
    \begin{description}
        \item[Prediction] micro-staircases in high-bandwidth Rabi traces.
        \item[Method] superconducting qubits with GHz readout.
        \item[Fail] continuous curves within noise.
    \end{description}

    \item \textbf{QRNG spectrum tails.}
    \begin{description}
        \item[Prediction] specific non-Gaussian tails in QRNG bitstreams.
        \item[Method] high-order statistics and compression tests.
        \item[Fail] perfect i.i.d. within tests.
    \end{description}

    \item \textbf{GRB spectral-lag bounds.}
    \begin{description}
        \item[Prediction] no energy-dependent photon delay from propagation; lags are source-internal.
        \item[Method] multi-band GRB timing.
        \item[Fail] robust propagation lags.
    \end{description}

    \item \textbf{TeV photon dispersion.}
    \begin{description}
        \item[Prediction] no vacuum dispersion.
        \item[Method] gamma-ray flares time-of-flight.
        \item[Fail] energy-dependent arrival times after source modeling.
    \end{description}

    \item \textbf{Photon mass null.}
    \begin{description}
        \item[Prediction] consistent with zero photon mass within tighter bounds.
        \item[Method] magnetic field curl tests, astrophysical limits.
        \item[Fail] nonzero mass detection.
    \end{description}

    \item \textbf{Neutrino vs. photon simultaneity.}
    \begin{description}
        \item[Prediction] no superluminal anomalies; timing matches standard expectations.
        \item[Method] multi-messenger timing.
        \item[Fail] repeatable anomalies implying propagation beyond framing.
    \end{description}

    \item \textbf{Binary pulsar periastron steps.}
    \begin{description}
        \item[Prediction] micro-steps in post-Keplerian timing.
        \item[Method] residual change-point detection.
        \item[Fail] none beyond modeled processes.
    \end{description}

    \item \textbf{Weak lensing shear grain.}
    \begin{description}
        \item[Prediction] tiny granularity in shear maps after PSF systematics removal.
        \item[Method] shear 2-point residual analysis.
        \item[Fail] smooth residuals only.
    \end{description}

    \item \textbf{CMB high-\( \ell \) tails.}
    \begin{description}
        \item[Prediction] slight heavy-tailed residuals after lensing and foregrounds.
        \item[Method] kurtosis of cleaned maps.
        \item[Fail] purely Gaussian.
    \end{description}

    \item \textbf{Redshift-drift steps.}
    \begin{description}
        \item[Prediction] pixelized drift increments in decades-long monitoring.
        \item[Method] ELT spectrographs.
        \item[Fail] perfectly smooth drift.
    \end{description}

    \item \textbf{Lyman-alpha micro-quantization.}
    \begin{description}
        \item[Prediction] subtle quantization in line-of-sight velocity fields.
        \item[Method] forest clustering residuals.
        \item[Fail] smooth statistics only.
    \end{description}

    \item \textbf{EHT shadow micro-variability.}
    \begin{description}
        \item[Prediction] step-like short-timescale features.
        \item[Method] closure-phase change points.
        \item[Fail] no steps beyond turbulence.
    \end{description}

    \item \textbf{Laboratory delayed-choice invariance.}
    \begin{description}
        \item[Prediction] frame reordering leaves outcomes invariant within TLM ranges.
        \item[Method] moving-detector delayed-choice tests.
        \item[Fail] reproducible frame-order effects.
    \end{description}

    \item \textbf{Entanglement loophole squeeze.}
    \begin{description}
        \item[Prediction] no finite-speed signaling; correlations remain frame-robust.
        \item[Method] cosmic-setting Bell tests.
        \item[Fail] parameter-dependent signaling.
    \end{description}

    \item \textbf{Synchrotron dispersion null.}
    \begin{description}
        \item[Prediction] no propagation dispersion in vacuum.
        \item[Method] storage-ring time-of-flight.
        \item[Fail] energy-dependent delays.
    \end{description}

    \item \textbf{Cavity ring-down grain.}
    \begin{description}
        \item[Prediction] step-like decay residuals at extreme finesse.
        \item[Method] ring-down residual tests.
        \item[Fail] purely exponential.
    \end{description}

    \item \textbf{Atom-clock transport steps.}
    \begin{description}
        \item[Prediction] micro-steps when clocks cross potential gradients.
        \item[Method] portable optical clocks on graded towers.
        \item[Fail] smooth predictions only.
    \end{description}

    \item \textbf{VLBI delay grain.}
    \begin{description}
        \item[Prediction] micro-steps in group delay after troposphere/ionosphere removal.
        \item[Method] geodetic VLBI residuals.
        \item[Fail] null.
    \end{description}

    \item \textbf{Occultation Fresnel steps.}
    \begin{description}
        \item[Prediction] step-like residuals in stellar occultation fringes.
        \item[Method] high-speed photometry.
        \item[Fail] smooth Fresnel curves.
    \end{description}

    \item \textbf{Digital twin falsifier.}
    \begin{description}
        \item[Prediction] a purely smooth digital twin cannot match measured heavy tails without ad hoc noise.
        \item[Method] simulation-to-measurement residual tests.
        \item[Fail] smooth twin matches without extra parameters.
    \end{description}

\end{enumerate}

\end{document}
```

</details>

---
{% endraw %}
