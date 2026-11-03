---
layout: default
title: '[2025] From Endpoint Pairing to Absorption-Frame Motion in the Timeless Light Framework'
description: 'Publication metadata and archived raw LaTeX source by John C. W. McKinley.'
permalink: /papers/from-endpoint-pairing-to-frame-splitting-absorption-frame-motion-in-the-timeless-light-framework/
paper: true
---
{% raw %}
# [2025] From Endpoint Pairing to Absorption-Frame Motion in the Timeless Light Framework
*   **DOI:** [10.5281/zenodo.16791851](https://doi.org/10.5281/zenodo.16791851)
*   **Date:** 10 August 2025

<details markdown="1">
<summary><b>Click to view Raw LaTeX Source</b></summary>

```latex
\documentclass[12pt,letterpaper]{article}

% ====== Packages ======
\usepackage[margin=1in]{geometry}
\usepackage[utf8]{inputenc}
\usepackage[T1]{fontenc}
\usepackage{lmodern}
\usepackage{microtype}
\usepackage{amsmath,amssymb,amsthm,mathtools}
\usepackage{bm}
\usepackage{siunitx}
\sisetup{separate-uncertainty=true}
\usepackage{graphicx}
\usepackage{booktabs}
\usepackage{enumitem}
\usepackage{array}
\usepackage{hyperref}
\hypersetup{colorlinks=true,linkcolor=blue,citecolor=blue,urlcolor=blue}
\usepackage{tikz}
\usetikzlibrary{decorations.pathreplacing,arrows.meta}
\usepackage{pgfplots}
\pgfplotsset{compat=1.18}

% ====== Title ======
\title{From Endpoint Pairing to Absorption-Frame Motion in the Timeless Light Framework}
\author{John C.~W.~McKinley\\
\small\href{https://orcid.org/0009-0005-7097-5035}{ORCID: 0009-0005-7097-5035}}
\date{August 10, 2025}

% ====== Theorems/Defs ======
\newtheorem{definition}{Definition}
\newtheorem{postulate}{Postulate}
\newtheorem{proposition}{Proposition}
\newtheorem{lemma}{Lemma}
\newtheorem{theorem}{Theorem}

% ====== Shortcuts ======
\newcommand{\M}{\mathcal{M}}
\newcommand{\g}{g_{\mu\nu}}
\newcommand{\E}{\mathcal{E}}
\newcommand{\A}{\mathcal{A}}
\newcommand{\Cs}{C_s}

\begin{document}
\maketitle

\renewcommand{\thefootnote}{}
\footnotetext[1]{This version published at \href{https://doi.org/10.5281/zenodo.16791851}{doi.org/10.5281/zenodo.16791851.}}



\begin{abstract}
This paper reinterprets apparent photon propagation within the Timeless Light Model (TLM) as the motion of an absorption frame. This approach provides a unified physical actor—the frame—for both GR's geometric delays and QM's instantaneous effects, resolving a key tension. In the Timeless Light Model, a CI-ARC (causal instruction) begins in ZeroSpace on a Quantum Platform with no time and no space. Its first act is to pair two endpoints: an emission frame E and an absorption frame A. We propose that what the SDF observer perceives between emission and detection is not a photon traversing spacetime, but the absorption frame moving through the GR/SR world under the metric. The instruction executes when the absorption frame intersects the emission frame’s lightlike boundary under Fermat stationarity. We formalize this, deriving SDF motion for both null and timelike frames, and include special-relativistic and GR thought experiments showing how this produces forward-only time offsets. In plain language, this paper proposes that a photon is not a particle traveling through space, but a timeless instruction linking its emission and absorption points—a change that could be detected by looking for small, geometry-independent timing residuals in astrophysical observations.
\end{abstract}

\section*{Quick Glossary}
\begin{description}
    \item[TLM (Timeless Light Model)] A physics framework where all events start as timeless instructions on the Quantum Platform and appear in spacetime with mass-dependent delay.
    \item[Quantum Platform (QP)] A timeless, non-spatial layer holding fully resolved outcomes. Spacetime merely renders these with delay.
    \item[ZeroSpace Causality] Events linked by massless instructions (T=0) in the QP resolve with no delay. In the Spacetime Deployment Frame they appear as if instantly connected.
    \item[CI-ARC (Causal Instruction Arc)] A complete, pre-resolved outcome in the QP. It defines what will happen, then renders into spacetime with delay T.
    \item[SDF (Spacetime Deployment Frame)] The observable universe where Quantum Platform instructions appear, with delay set by mass or other resistance.
\end{description}

\section{Introduction and Motivation}

In GR/SR, light is modeled as null geodesics on a smooth manifold \((\M, g_{\mu\nu})\) \cite{einstein1916, peacock1999, wald1984}. In TLM, “photon” denotes a timeless instruction on the QP whose SDF appearance is a null deployment trace (ZeroSpace quality), with delays and phases arising from SDF geometry rather than photon aging \cite{mckinley2025_waveparticle, mckinley2025_clarifyingcs}. However, the mechanism by which a timeless QP instruction manifests as a finite-duration 'journey' in the SDF has remained a 'blackbox' in prior work. This paper replaces that blackbox with an explicit model of absorption-frame dynamics.

We advance an operational reinterpretation: the SDF observer perceives the absorption frame as moving across the GR/SR world relative to the emission frame. This reframes “light in transit” as absorption-frame motion. Absorption-frame motion is distinct from standard null-geodesic propagation because, in TLM, there is no ontic particle or wave traveling; instead, the "path" is an emergent trace of the absorption frame’s dynamics under the metric, subordinated to timeless QP instructions.

\begin{figure}[h!]
\centering
\begin{tikzpicture}[>=stealth,thick]
% Standard Model Panel
\node at (-3,2.5) {\textbf{Standard Photon Model}};
\draw[fill=gray!10] (-6,0) rectangle (-1,2);
\node[circle,fill=blue!60,inner sep=2pt,label=below:E] at (-5,1) {};
\node[circle,fill=red!60,inner sep=2pt,label=below:A] at (-2,1) {};
\draw[->,dashed] (-5,1) -- (-2,1) node[midway,above] {Photon travels};

% TLM Panel
\node at (3,2.5) {\textbf{TLM Absorption-Frame Motion}};
\draw[fill=gray!10] (1,0) rectangle (6,2);
\node[circle,fill=blue!60,inner sep=2pt,label=below:E] at (2,1) {};
\node[circle,fill=red!60,inner sep=2pt,label=below:A initial] at (3,1) {};
\node[circle,fill=red!20,draw=red!60,inner sep=2pt,label=below:A final] at (5,1) {};
\draw[->,red!60] (3,1) -- (5,1) node[midway,above] {A moves};
\end{tikzpicture}
\caption{Standard vs. TLM views: Left, a photon traverses from emission (E) to absorption (A). Right, the absorption frame moves toward E, with no traveling entity. This highlights the shift to frame motion, predicting testable delays.}
\label{fig:standard_vs_tlm}
\end{figure}

\subsection{Overview of TLM Basics}
The Timeless Light Model (TLM) proposes a two-layer ontology: a timeless Quantum Platform (QP) pre-resolving causal instructions, and a Spacetime Deployment Frame (SDF) where these instructions render as observable physics \cite{mckinley2025_synthesis}. Key axioms include the two-layer structure (Axiom 4.1 from \cite{mckinley2025_synthesis}) and core equations such as the Mass-Delay Law \(T \cdot m = \hbar/c^2\) (natural units: \(Tm = 1\)) and the causal rendering law \(T \cdot C_s = 1\) (Core Equations from \cite{mckinley2025_synthesis}, Sec. 4.2). In this framework, all physical phenomena subordinate to timeless QP instructions, with GR curvature emerging as delay gradients and QM probabilities as rendering artifacts.
ZeroSpace refers to the initial, timeless, and extensionless state of a causal instruction in the QP, where there is neither space nor time—only the pre-resolved pairing of endpoints before deployment into the SDF. This concept ensures that causality is authored outside of spacetime, avoiding paradoxes like retrocausality.

\section{Relation to Prior Work}
Prior TLM papers emphasize CI-ARCs as the mechanism for QP to SDF deployment \cite{mckinley2025_ciarc, mckinley2025_clarifyingcs, mckinley2025_photonoutoftime, mckinley2025_waveparticle}, while one treated the transition as a blackbox \cite{mckinley2025_layered}.

\section{Postulates: Endpoint-First Deployment and Moving Absorption Frames}
\begin{postulate}[ZeroSpace Instruction]
A CI-ARC begins in QP with no spacetime attributes. It first selects endpoint classes (\(\E, \A\)) timelessly. No retrocausality is entailed because QP lacks time \cite{wheelerfeynman1945}.
\end{postulate}
\begin{postulate}[Absorption-Frame Motion]
Given (\(\E, \A\)) and \(g_{\mu\nu}\), the deployment map \(\Pi\) produces one or more absorption-frame trajectories in SDF that evolve relative to \(\E\) and obey the local propagation constraints (null for photonic deployment; timelike for massive frames).
\end{postulate}

\section{Mathematical Framework}
\subsection{Null and Timelike SDF Motion}
In geometric optics, \(k^\mu = \nabla^\mu S\) satisfies \(g^{\mu\nu}k_\mu k_\nu = 0\); rays are integral curves of \(k^\mu\). We interpret each extremal not as a “photon path,” but as a candidate absorption-frame SDF trajectory. Massive frames are timelike, with 4-velocity \(u^\mu\) satisfying \(g_{\mu\nu}u^\mu u^\nu = -1\) and geodesic (or forced) motion:
\begin{equation}
\frac{du^\mu}{d\tau} + \Gamma^\mu_{\alpha\beta}u^\alpha u^\beta = f^\mu \quad (f^\mu = 0\ \text{geodesic}).
\end{equation}
Absorption-frame motion is thus:
\begin{align}
\text{photonic deployment:} & \quad k^\mu k_\mu = 0, \quad k^\nu\nabla_\nu k^\mu = 0, \\
\text{massive frame:} & \quad u^\mu u_\mu = -1, \quad u^\nu\nabla_\nu u^\mu = f^\mu.
\end{align}

\begin{proposition}[Deployment Rate for Moving Frames]
For an absorption frame with trajectory \(x^\mu_A(\lambda)\), the SDF coordinate time accrual is \(dt = T d\lambda\), where \(T = \hbar/(mc^2)\) for mass-bearing frames (natural units: \(Tm = 1\)). In the massless limit, \(T \to 0\) implies instantaneous deployment, consistent with null paths.
\end{proposition}
This derives from the causal rendering law \(T \cdot C_s = 1\), with deployment rate \(C_s = d\lambda/dt\), yielding \(dt = Td\lambda\).

\subsection{Optical Metric and Fermat Functional}
In static sectors
\begin{equation}
ds^2 = -V(\mathbf{x})^2dt^2 + h_{ij}(\mathbf{x})dx^i dx^j, \quad n(\mathbf{x}) = 1/V(\mathbf{x}),
\end{equation}
the travel-time functional is
\begin{equation}
T[\gamma] = \int_\gamma n(\mathbf{x}) d\ell_h, \quad d\ell_h^2 = h_{ij}dx^i dx^j,
\end{equation}
and extremals are geodesics of the optical metric \(\tilde{h}_{ij} = n^2 h_{ij}\). We treat these extremals as the admissible absorption-frame trajectories relative to \(\E\).

\subsection{Execution Criterion (Endpoint Intersection)}
Let \(E \in \M\) be the emission-event. A candidate absorption frame \(x^\mu_A(\lambda)\) executes the instruction when \(\exists \lambda^\star\) such that
\begin{equation}
g_{\mu\nu} (x^\mu_A(\lambda^\star) - x^\mu_E)(x^\nu_A(\lambda^\star) - x^\nu_E) = 0,
\end{equation}
(the null interval condition in signature -+++) and the arrival-time functional is stationary.

\section{Special-Relativistic Analog: Alternating Velocities at Fixed Radius}
Consider two identical frames executing repeated rendezvous in flat spacetime. On each leg, one frame cruises at speed \(v_{\text{fast}}\) while the other remains co-moving at \(v_{\text{slow}}\) (possibly 0), for a coordinate interval \(T_{\text{leg}}\). Special-relativistic time dilation gives
\begin{equation}
\frac{d\tau}{dt} = \frac{1}{\gamma(v)}, \quad \gamma(v) = \frac{1}{\sqrt{1 - v^2/c^2}}.
\end{equation}
Hence the proper-time difference accumulated in a single leg is
\begin{equation}
\Delta\tau_{\text{leg}}^{\text{(SR)}} = T_{\text{leg}} \left[\frac{1}{\gamma(v_{\text{slow}})} - \frac{1}{\gamma(v_{\text{fast}})}\right] > 0, \quad v_{\text{fast}} > v_{\text{slow}}.
\label{eq:delta_tau_sr}
\end{equation}
This realizes the same qualitative effect as the gravitational case: one reunion shows a definite forward-only offset. Keeping roles fixed between reunions accumulates an arbitrarily large forward offset without violating causality. Future precision tests, such as atomic clocks in orbital swaps, could probe for TLM-predicted offsets.

\begin{figure}[h!]
\centering
\begin{tikzpicture}[>=stealth,thick,scale=1.0]
% Axes
\draw[->] (-0.3,0) -- (10.6,0) node[right] {$x$};
\draw[->] (0,-0.3) -- (0,7.8) node[above] {$ct$};
% Start + rendezvous events
\fill (1.0,0.8) circle (1.5pt) node[left] {\scriptsize start};
\fill (6.8,4.8) circle (1.5pt) node[right] {\scriptsize reunion};
% Worldline: slow craft
\draw[very thick,blue!70] (1.0,0.8) -- (2.2,2.0) -- (3.6,3.4) -- (5.0,4.8);
\node[blue!70,anchor=west] at (2.05,4.85) {\small slow (A), $v_{\rm slow}$};
% Worldline: fast craft
\draw[very thick,red!70] (1.0,0.8) -- (3.2,2.0) -- (5.0,3.4) -- (6.8,4.8);
\node[red!70,anchor=west] at (6.85,4.3) {\small fast (B), $v_{\rm fast}$};
% Light-cone hint
\draw[gray!50] (1.0,0.8) -- (7.0,6.8);
\draw[gray!50] (1.0,0.8) -- (-1.0,2.8);
% Leg duration brace
\draw[<->] (0.6,0.8) -- (0.6,2.0) node[midway,left] {\scriptsize $T_{\rm leg}$};
% Proper-time rate annotations
\draw[decorate,decoration={brace,amplitude=4pt}] (2.0,1.65) -- (2.0,2.35) node[midway,right=6pt] {\scriptsize $1/\gamma(v_{\rm slow})$};
\draw[decorate,decoration={brace,amplitude=4pt}] (3.9,1.95) -- (3.9,2.65) node[midway,right=6pt] {\scriptsize $1/\gamma(v_{\rm fast})$};
% Alternating roles
\draw[very thick,blue!40,dashed,opacity=0.7] (5.0,4.8) -- (6.8,6.2);
\draw[very thick,red!40,dashed,opacity=0.7] (6.8,4.8) -- (5.0,6.2);
% Legend
\node[anchor=north west] at (-0.3,-1) {
\begin{tabular}{ll}
\color{blue!70} Slow Frame & \\
\color{red!70} Fast Frame & \\
\color{gray!50} Light Cone & \\
\end{tabular}
};
\end{tikzpicture}
\caption{Special-relativistic analog: two frames depart together and reunite. The fast worldline (red) accumulates less proper time, yielding the forward-only offset of Eq.~(\ref{eq:delta_tau_sr}). This demonstrates delay effects testable via precision clocks.}
\label{fig:sr_analog}
\end{figure}

\section{GR Thought Experiment: Alternating Near a Large Mass}
Two identical ships, A and B, alternately park at radii \(r_1 < r_2\) around mass M. Let each stint last \(T_{\text{swap}}\) in coordinate time. Gravitational time dilation gives
\begin{equation}
\Delta\tau_{\text{cycle}} = T_{\text{swap}} \left[\sqrt{1 - \frac{2GM}{r_2 c^2}} - \sqrt{1 - \frac{2GM}{r_1 c^2}}\right] > 0,
\label{eq:delta_tau_gr}
\end{equation}
which is strictly positive for \(r_1 < r_2\) (see Appendix A). Each ship can thereby “jump into the other’s future.” Causal order is preserved as \(d\tau > 0\) for all timelike curves. This process shows how temporal offsets are generated through purely geometric means in the SDF, governed by timeless QP instructions.

\subsection{Causality and Paradox Resolution}
While forward offsets accumulate, no closed timelike curves form. This avoids retrocausality by confining 'jumps' to SDF projections of timeless QP pairings. See the synthesis’s Sec. 3 for details on this \cite{mckinley2025_synthesis}.

\begin{figure}[h!]
\centering
\begin{tikzpicture}[>=stealth,thick,scale=1.0]
% Axes
\draw[->] (-0.3,0) -- (10.6,0) node[right] {$r$};
\draw[->] (0,-0.3) -- (0,8.6) node[above] {$ct$};
% Mass at center
\draw[fill=black!80] (0.4,0.6) circle (2pt) node[below right] {\footnotesize central mass $M$};
\draw[gray,->] (0.4,0.6) -- (0.4,8.2);
% Radii guides
\draw[blue!40,dashed] (1.2,0.2) -- (1.2,8.2) node[pos=0,below,blue!60] {$r_1$};
\draw[blue!40,dashed] (6.0,0.2) -- (6.0,8.2) node[pos=0,below,blue!60] {$r_2$};
% Timing
\def\dt{1.6}
% Ship A
\draw[very thick,blue!70] (6.0,0.6) -- (6.0,0.6+\dt) -- (1.2,0.6+2*\dt) -- (1.2,0.6+3*\dt) -- (6.0,0.6+4*\dt);
% Ship B
\draw[very thick,red!70] (1.2,0.6) -- (1.2,0.6+\dt) -- (6.0,0.6+2*\dt) -- (6.0,0.6+3*\dt) -- (1.2,0.6+4*\dt);
% Labels
\draw[<->] (6.15,0.6) -- (6.15,0.6+\dt) node[midway,right] {\scriptsize $T_{\rm swap}$};
\draw[<->] (1.05,0.6) -- (1.05,0.6+\dt) node[midway,left] {\scriptsize $T_{\rm swap}$};
\draw[decorate,decoration={brace,amplitude=4pt}] (5.7,0.6) -- (5.7,0.6+\dt) node[midway,left=6pt] {\scriptsize $d\tau/dt=\sqrt{1-\tfrac{2GM}{r_2 c^2}}$};
\draw[decorate,decoration={brace,amplitude=4pt}] (0.9,0.6) -- (0.9,0.6+\dt) node[midway,left=6pt] {\scriptsize $d\tau/dt=\sqrt{1-\tfrac{2GM}{r_1 c^2}}$};
% Reunion slice
\draw[gray!60,dashed] (-0.05,0.6+4*\dt) -- (10.4,0.6+4*\dt);
\node[gray!70,anchor=west] at (0.05,0.6+4*\dt+0.15) {\scriptsize reunion slice};
% Offset indicator
\draw[<->,thick] (9.6,0.6+4*\dt-0.38) -- (9.6,0.6+4*\dt+0.38);
\node[align=left] at (9.6-0.1,0.6+4*\dt+0.75) {\scriptsize accumulated offset\\[-1pt]\(\scriptsize \Delta\tau_{\rm cycle} > 0\)};
% Legend
\node[anchor=north west] at (-0.3,-1) {
\begin{tabular}{ll}
\color{blue!70} Ship A & \\
\color{red!70} Ship B & \\
\color{black!80} Mass M & \\
\end{tabular}
};
\end{tikzpicture}
\caption{Two massive frames alternate dwell periods at radii \(r_1 < r_2\) near a mass M. Because proper time accrues more slowly at \(r_1\), one full cycle produces a net forward-only offset \(\Delta\tau_{\text{cycle}} > 0\). This illustrates geometric offsets testable via precision clocks.}
\label{fig:gr_analog}
\end{figure}

\section{Massless Frames in TLM}
\begin{definition}[Massless Frame]
A massless frame is an SDF endpoint with \(m = 0, \tau = 0\), and deployment via timeless QP linkage, addressable as (\(\E, \A\)) without accruing proper time.
\end{definition}
\begin{lemma}[Massless Execution]
Execution occurs when \(g_{\mu\nu}(x^\mu_A - x^\mu_E)(x^\nu_A - x^\nu_E) = 0\), independent of \(\tau_A\), preserving ZeroSpace causality.
\end{lemma}
A massless frame is a meaningful endpoint with \(m = 0\) and zero proper time in SDF. In GR, massless worldlines are null; \(\tau = 0\). In TLM, such a frame may still be addressed by a CI-ARC pairing (\(\E, \A\)) without being “in time” in SDF. This bridges QM nonlocality and GR null paths. This provides a formal mechanism for phenomena like entanglement, where correlated outcomes appear instantaneously in the observer’s frame, as their shared massless absorption frames deploy without proper time accrual in the SDF \cite{mckinley2025_frameasmaster}.

\begin{figure}[h!]
\centering
\begin{tikzpicture}[>=stealth,thick]
% QP layer
\draw[fill=gray!10] (-4,3.5) rectangle (4,5.0);
\node at (0,5.3) {\textbf{Quantum Platform (QP) -- Timeless Layer}};
% Emission and absorption points in QP
\node[circle,fill=blue!60,inner sep=2pt,label=above:{Emission Frame (E)}] (E_qp) at (-2,4) {};
\node[circle,fill=red!60,inner sep=2pt,label=above:{Absorption Frame (A)}] (A_qp) at (2,4) {};
% Connection in QP
\draw[blue!60,thick] (E_qp) -- (A_qp);
% SDF layer
\draw[fill=gray!10] (-4,-.3) rectangle (4,1.3);
\node at (0,1.6) {\textbf{Spacetime Deployment Frame (SDF)}};
% Emission frame in SDF
\node[circle,fill=blue!60,inner sep=2pt,label=below:{E in SDF}] (E_sdf) at (-2,0.5) {};
% Absorption frame in SDF initial and moved
\node[circle,fill=red!60,inner sep=2pt,label=below:{A$_0$ in SDF}] (A0_sdf) at (0,0.5) {};
\node[circle,fill=red!20,draw=red!60,inner sep=2pt,label=below:{A$_1$ in SDF}] (A1_sdf) at (2,0.5) {};
% Vertical projection lines
\draw[dashed] (E_qp) -- (E_sdf);
\draw[dashed] (A_qp) -- (A0_sdf);
% Motion of absorption frame in SDF
\draw[->,red!60,dashed] (A0_sdf) -- (A1_sdf);
% Legend
\node[anchor=north west] at (-4,-1.5) {
\begin{tabular}{ll}
\color{blue!60} Emission Frame & \\
\color{red!60} Absorption Frame & \\
\color{blue!60} Timeless Connection & \\
\end{tabular}
};
\end{tikzpicture}
\caption{Frame baseline. The QP linkage (solid) is timeless; the absorption frame moves in the SDF (dashed) while the emission frame is effectively fixed. This setup predicts delay residuals as in Sec.~\ref{sec:falsifiability}.}
\label{fig:frame_baseline}
\end{figure}

\section{Observational Signatures and Falsifiability}
\label{sec:falsifiability}
The primary measurable predictions of this absorption-frame motion model are:
\begin{itemize}
    \item \textbf{Achromatic Gravitational Delays.} After plasma dispersion removal (\(\propto\nu^{-2}\)), any remaining timing residuals should be achromatic (frequency-independent). The model predicts that broadband offsets tied only to the geometry of the endpoints, not to a frequency-dependent medium, could exist. Discovering such offsets would falsify standard propagation models. Current limits are \textless \(10^{-20}\) s/Mpc using pulsar timing arrays (PTA) like NANOGrav \cite{mckinley2025_qpframegen}.
    \item \textbf{No Photon Aging Terms.} Redshift and other delays should depend only on the SDF geometry between the endpoints (e.g., cosmological expansion \(a(t)\), gravitational potentials), not on the "age" or path length of the instruction. The detection of repeatable extra terms proportional to path length itself would challenge the ZeroSpace deployment model \cite{mckinley2025_waveparticle}.
\end{itemize}

\subsection{Links to Dark Matter and Gravitons}
In clustered geometries (e.g., galactic halos), frame motion may produce 'dark' unrendered branches mimicking DM gravitational effects without luminosity, consistent with delayed clusters in the QP frame generator model \cite{mckinley2025_qpframegen}. Gravitational waves could exhibit discrete residuals, reinterpreting gravitons as geometry-change units \cite{mckinley2025_gravitons}.

\begin{table}[h!]
\centering
\caption{Observables vs. Predictions}
\label{tab:predictions}
\begin{tabular}{|p{3.5cm}|p{4cm}|p{4.5cm}|}
\hline
\textbf{Observable} & \textbf{Frame Prediction} & \textbf{Current Measurement Limits} \\
\hline
Achromatic Delays & Broadband residuals \(<10^{-20}\) s/Mpc & PTA (NANOGrav): \(<10^{-19}\)s/Mpc \\
Photon Aging Terms & None; geometry-dependent only & CMB/FRB: \(<10^{-21}\)s/Mpc \\
\hline
\end{tabular}
\end{table}

\section{Conclusion}
We presented an endpoint-first deployment where a CI-ARC starts with no spacetime attributes, pairs (\(\E, \A\)), and renders in SDF as absorption-frame motion under the metric. The SR analog quantifies forward-only offsets at fixed radius; the GR protocol shows forward-only offsets near a mass. The massless-frame construct clarifies how frames can exist without SDF proper time. Together these sustain TLM’s ZeroSpace causality while preserving GR/SR phenomenology. A key falsifiable prediction is achromatic residuals in gravitational time-delays, testable with VLBI and PTA observations.

\appendix
\section{Derivations and Positivity Proofs}
\paragraph{SR single-leg positivity.}
For \(f(v) = 1/\gamma(v) = \sqrt{1 - v^2/c^2}\), \(f'(v) = - \frac{v/c^2}{\sqrt{1-v^2/c^2}} < 0\) for \(0 < v < c\). Hence \(f(v_{\text{slow}}) - f(v_{\text{fast}}) > 0\) if \(v_{\text{fast}} > v_{\text{slow}}\), which proves \(\Delta\tau_{\text{leg}}^{\text{(SR)}} > 0\) in Eq.~(\ref{eq:delta_tau_sr}).
\paragraph{GR cycle positivity.}
For \(g(r) = \sqrt{1 - 2GM/(rc^2)}\) (Schwarzschild exterior), \(g'(r) = \frac{GM}{c^2r^2} \left(1 - \frac{2GM}{rc^2}\right)^{-1/2} > 0\) for \(r > 2GM/c^2\). Thus \(g(r_2) - g(r_1) > 0\) when \(r_2 > r_1\), proving Eq.~(\ref{eq:delta_tau_gr}).

\section{Glossary and Symbols}
\begin{center}
\begin{tabular}{p{3.5cm} p{11cm}}
\toprule
\textbf{Term} & \textbf{Meaning}\\
\midrule
Quantum Platform (QP) & Timeless, non-spatiotemporal instruction layer.\\
CI-ARC & Causal Instruction Arc: timeless state-transition S \(\to\) E in QP.\\
SDF & Spacetime Deployment Frame: rendered GR/SR layer (observable).\\
Emission frame (\(\E\)) & Endpoint associated with the source side of a CI-ARC.\\
Absorption frame (\(\A\)) & Endpoint associated with the sink/receiver; moves in SDF.\\
Massless frame & Endpoint with \(m = 0\) and \(\tau = 0\) in SDF, yet addressable.\\
\(\Cs\) & Causal deployment rate; in TLM, \(T \cdot \Cs = 1\) phenomenology.\\
ZeroSpace & Timeless, extensionless QP state.\\
Deployment Map \(\Pi\) & QP \(\to\) SDF projection operator.\\
Single-Absorber Principle & Each photon-like instruction resolves to exactly one absorption frame.\\
\bottomrule
\end{tabular}
\end{center}

\begin{thebibliography}{99}

\bibitem{einstein1916}
A.~Einstein, ``Die Grundlage der allgemeinen Relativitätstheorie,'' \emph{Annalen der Physik}, \textbf{49}, 769--822 (1916).

\bibitem{peacock1999}
J.~A.~Peacock, \emph{Cosmological Physics} (Cambridge University Press, 1999).

\bibitem{wald1984}
R.~M.~Wald, \emph{General Relativity} (University of Chicago Press, 1984).

\bibitem{mckinley2025_ciarc}
J.~C.~W. McKinley, ``Causal Instruction Arcs and the Timeless Light Model: A Unified Framework for Physics and Cosmology,'' (2025), doi:\href{https://doi.org/10.5281/zenodo.15813253}{10.5281/zenodo.15813253}.

\bibitem{mckinley2025_clarifyingcs}
J.~C.~W. McKinley, ``Clarifying $C_s$: Deployment Rate, Delay, and Simulation Parameters in the Timeless Light Model,'' (2025), doi:\href{https://doi.org/10.5281/zenodo.15817350}{10.5281/zenodo.15817350}.

\bibitem{mckinley2025_photonoutoftime}
J.~C.~W. McKinley, ``Photon Out of Time: Why Light Experiences No Time—and What That Means for Physics,'' (2025), doi:\href{https://doi.org/10.5281/zenodo.16479322}{10.5281/zenodo.16479322}.

\bibitem{mckinley2025_waveparticle}
J.~C.~W. McKinley, ``Resolving Wave-Particle Duality Through the Proposed Timeless Light Model: Photons as Timeless Instructions and Waves as Deployed Delay,'' (2025), doi:\href{https://doi.org/10.5281/zenodo.16510862}{10.5281/zenodo.16510862}.

\bibitem{mckinley2025_layered}
J.~C.~W. McKinley, ``Unified Physics by Subordination of GR to QM: A Layered Reality Framework,'' (2025), doi:\href{https://doi.org/10.5281/zenodo.15956986}{10.5281/zenodo.15956986}.

\bibitem{mckinley2025_synthesis}
J.~C.~W. McKinley, ``Foundational Equations and Axiomatic Structure of the Timeless Light Model: A Synthesis Across Sixty Papers and Working Notes,'' (2025), doi:\href{https://doi.org/10.5281/zenodo.16187719}{10.5281/zenodo.16187719}.

\bibitem{mckinley2025_qpframegen}
J.~C.~W. McKinley, ``The Quantum Platform as Frame Generator: Ontology, Anatomy, and Dark Matter Implications in TLM,'' (2025), doi:\href{https://doi.org/10.5281/zenodo.16788735}{10.5281/zenodo.16788735}.

\bibitem{mckinley2025_gravitons}
J.~C.~W. McKinley, ``Gravitons as Quantum Platform Geometry Instructions: A Timeless-Light Interpretation of Gravitational Wave Quanta,'' (2025), doi:\href{https://doi.org/10.5281/zenodo.16788039}{10.5281/zenodo.16788039}.

\bibitem{mckinley2025_frameasmaster}
J.~C.~W. McKinley, ``The Frame as Master: A Unified Foundation for the Timeless Light Model,'' (2025), doi:\href{https://doi.org/10.5281/zenodo.16787219}{10.5281/zenodo.16787219}.

\bibitem{wheelerfeynman1945}
J.~A.~Wheeler and R.~P.~Feynman, ``Interaction with the Absorber as the Mechanism of Radiation,'' \emph{Rev. Mod. Phys.}, \textbf{17}, 157 (1945).

\end{thebibliography}

\end{document}
```

</details>

---
{% endraw %}
