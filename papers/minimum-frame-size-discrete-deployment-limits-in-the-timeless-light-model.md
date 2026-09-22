---
layout: default
title: '[2025] Minimum Frame Size: Discrete Deployment Limits in the Timeless Light Model'
description: 'Publication metadata and archived raw LaTeX source by John C. W. McKinley.'
permalink: /papers/minimum-frame-size-discrete-deployment-limits-in-the-timeless-light-model/
paper: true
---
{% raw %}
# [2025] Minimum Frame Size: Discrete Deployment Limits in the Timeless Light Model
*   **DOI:** [10.5281/zenodo.17009716](https://doi.org/10.5281/zenodo.17009716)
*   **Date:** 30 August 2025

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
\usepackage{amsmath,amssymb,amsthm}
\usepackage{bm}
\usepackage{siunitx}
\sisetup{separate-uncertainty=true}
\usepackage{graphicx}
\usepackage{booktabs}
\usepackage{tikz}
\usepackage{pgfplots}
\pgfplotsset{compat=1.18}
\usepgfplotslibrary{fillbetween}
\usepackage{orcidlink}
\usepackage{hyperref}
\hypersetup{colorlinks=true,linkcolor=blue,citecolor=blue,urlcolor=blue}
\usepackage{enumitem} % Added for better enumeration

% ====== Title ======
\title{Minimum Frame Size: Discrete Deployment Limits in the Timeless Light Model}





\author{John C. W. McKinley\orcidlink{0009-0005-7097-5035}\\Independent Researcher}
\date{August 30, 2025}





% ====== Theorems/Defs ======
\newtheorem{definition}{Definition}
\newtheorem{postulate}{Postulate}
\newtheorem{proposition}{Proposition}
\newtheorem{lemma}{Lemma}
\newtheorem{theorem}{Theorem}

% ====== Shortcuts ======
\newcommand{\M}{\mathcal{M}}
\newcommand{\g}{g_{\mu\nu}}
\newcommand{\Cs}{C_s}
\newcommand{\E}{\mathcal{E}}
\newcommand{\A}{\mathcal{A}}
\newcommand{\Gam}{\Gamma_I}

\begin{document}
\maketitle


\begingroup
  \footnotetext[0]{This version published at
  \href{https://doi.org/10.5281/zenodo.17009716}{https://doi.org/10.5281/zenodo.17009716}.}
\endgroup

\begin{abstract}
In the Timeless Light Model (TLM), observable spacetime phenomena emerge as delayed deployments of timeless instructions from an ontologically senior Quantum Platform (QP). Photons are reinterpreted as instructions lacking an ontic worldline in the Spacetime Deployment Frame (SDF), yet producing SDF-compliant traces with \emph{ZeroSpace} quality. This work addresses a core question: Does SDF deployment impose a minimum frame size (MFS)? We define ``frame'' as the smallest SDF region capable of registering an instruction event (emission or absorption) and derive lower bounds on spatial (\(\ell_{\min}\)) and temporal (\(t_{\min}\)) scales from the TLM delay laws \(T \cdot \Cs = 1\) (massless) and \(T \cdot m = \hbar / c^2\) (massive), ensuring consistency with general relativity (GR) causal structure and quantum limits. These bounds are compatible with, but not fixed to, Planck scales, and yield falsifiable predictions for interferometry, pulsar timing arrays, and high-energy scattering. Visualizations include a discrete deployment lattice against null cones and a tradeoff surface from the delay laws. Keywords: Timeless Light Model, Quantum Platform, Spacetime Deployment, Minimum Frame Size, Delay Laws.
\end{abstract}

\section{Introduction and Motivation}
\label{sec:intro}
In general relativity (GR), physical observations are described on a smooth manifold \((\M, \g)\). The Timeless Light Model (TLM) reinterprets this manifold as an emergent \emph{deployment layer}---the Spacetime Deployment Frame (SDF)---generated from timeless instructions on a senior Quantum Platform (QP) \cite{McKinley2025_Review}. Photonic phenomena arise from projections of QP endpoint pairings into SDF, exhibiting \emph{ZeroSpace} quality: no ontic worldline, but compliant null traces \cite{McKinley2025_TLM,McKinley2025_Cs}.

A key open question in TLM is whether SDF deployments allow arbitrary fine-grained localization or if a \emph{minimum frame size} (MFS) exists, below which instruction events cannot resolve in SDF. Such a bound must harmonize:
\begin{enumerate}[label=\arabic*.]
\item GR causal structure, including null cones and local Lorentz invariance \cite{Einstein1916,Peacock1999};
\item TLM delay laws \(T \cdot \Cs = 1\) for massless instructions and \(T \cdot m = \hbar / c^2\) for massive systems (in natural units where \(\hbar = c = 1\), simplifying to \(T \cdot m = 1\)) \cite{McKinley2025_Cs};
\item Empirical quantum constraints, such as phase noise in interferometry;
\item TLM's exclusion of causal roles for information compression or costs.
\end{enumerate}
This paper develops a rigorous, testable framework that preserves GR while imposing bounds on deployment resolution, advancing TLM's foundational structure \cite{McKinley2025_v2}.

\section{Preliminaries: Frames, ZeroSpace, and Delay Laws}
\label{sec:prelim}

\begin{definition}[SDF Frame]
A \emph{frame} is a localized SDF region with 4-velocity \(u^\mu\), local metric \(\g\), and capability to register instruction events (emission/absorption). Frames \(\E\) and \(\A\) pair on QP, projecting via map \(\Pi\) to null trace \(\Gam\) in SDF.
\end{definition}

\begin{postulate}[ZeroSpace Quality]
Photonic instructions reside outside SDF (no worldline), but \(\Gam\) satisfies GR null conditions and Lorentz invariance. Delays and phases are geometric artifacts of projection and endpoints \(\E, \A\) \cite{McKinley2025_TLM}.
\end{postulate}

\begin{postulate}[Delay Laws]
For massless instructions, \(T \cdot \Cs = 1\), where \(T\) is deployment delay and \(\Cs\) is QP causal rate. For massive systems, \(T \cdot m = \hbar / c^2\) (or \(T \cdot m = 1\) in \(\hbar = c = 1\) units). These constrain deployment without altering GR dynamics \cite{McKinley2025_Cs}.
\end{postulate}

\section{Defining Minimum Frame Size (MFS)}
\label{sec:def-mfs}
MFS represents the smallest viable SDF region for localizing an instruction event. We define:
\begin{align}
\ell_{\min} &: \text{ minimum spatial extent for event registration},\\
t_{\min} &: \text{ minimum temporal integration window}.
\end{align}

\begin{definition}[MFS Consistency]
The pair \((\ell_{\min}, t_{\min})\) is consistent if a neighborhood \(U \subset \M\) of size \(\sim \ell_{\min}\) and interval \(\Delta t \geq t_{\min}\) exists such that: (i) null structure holds, (ii) phases are defined, (iii) delay laws solve for \(\Pi\) in \(U\).
\end{definition}

This bounds deployment, not spacetime discreteness. Bounds may align with, exceed, or undercut Planck scales \((\ell_P, t_P)\) while respecting GR.

\section{Derivation I: Bounds from Causality and Phase}
\label{sec:deriv1}
Consider wavevector \(k^\mu\) along \(\Gam\), with phase \(\Phi = \int_\gamma k_\mu dx^\mu\). For interference resolution in size \(\ell\):
\begin{equation}
\Delta \Phi(\ell, \Delta t) \lesssim \pi.
\label{eq:phase-criterion}
\end{equation}
In curved spacetime, \(k^\mu k_\mu = 0\). For quasi-stationary regions, \(k^0 \sim \omega\), \(|\mathbf{k}| \sim \omega\).

Phase noise scales linearly:
\begin{equation}
\Delta \Phi \gtrsim \alpha_\Phi (\omega \Delta t) + \beta_\Phi (\omega \ell),
\label{eq:phase-noise}
\end{equation}
where \(\alpha_\Phi, \beta_\Phi\) encapsulate fluctuations.\footnote{Conservative; accommodates quantum and classical noise.} Yielding:
\begin{equation}
\omega \Delta t + r \omega \ell \lesssim \pi / \alpha_\Phi, \quad r = \beta_\Phi / \alpha_\Phi.
\end{equation}
Minimization implies:
\begin{equation}
\ell \gtrsim \ell_{\min}(\omega) > 0, \quad \Delta t \gtrsim t_{\min}(\omega) > 0.
\label{eq:minbounds_general}
\end{equation}
High \(\omega\) compensates noise, but finite SNR prevents zero bounds.

\section{Derivation II: Delay-Law Bounds}
\label{sec:deriv2}
For massless, \(T \cdot \Cs = 1\), with \(T\) as minimal discrimination interval:
\begin{equation}
t_{\min} \gtrsim T_{\min} = 1 / \Cs_{\max},
\label{eq:tminCs}
\end{equation}
\(\Cs_{\max}\) from TLM axioms \cite{McKinley2025_Cs}. For massive:
\begin{equation}
t_{\min}(m) \gtrsim \hbar / (m c^2) \quad (\text{or } 1/m \text{ in natural units}).
\label{eq:tminm}
\end{equation}
Spatial link via Fermat in static metrics (lapse \(V\)):
\begin{equation}
\Delta t = \int n \, d\ell_h \implies \ell_{\min} \gtrsim t_{\min} / \max n, \quad n = 1/V.
\label{eq:lfromt}
\end{equation}
Combined:
\begin{equation}
\boxed{
t_{\min} \gtrsim \max\left( \frac{1}{\Cs_{\max}}, \frac{\hbar}{m c^2} \right),
\quad
\ell_{\min} \gtrsim \frac{t_{\min}}{\max n}.
}
\label{eq:main_bounds}
\end{equation}
These constrain resolvable events in TLM.

\section{Comparison to Other Theories}
\label{sec:comparison}
Unlike loop quantum gravity, where spacetime discretizes at Planck scales with area/volume spectra \cite{Rovelli2004}, TLM bounds apply to deployments, leaving manifold smooth. Causal set theory posits discrete events with partial order \cite{Bombelli1987}, but TLM's MFS is operational, tied to delay laws. Empirical floors could distinguish: TLM predicts achromatic residuals, independent of microstructure.

\section{Relation to Planck Scales}
\label{sec:planck}
Planck units:
\begin{equation}
\ell_P = \sqrt{\frac{\hbar G}{c^3}}, \quad t_P = \sqrt{\frac{\hbar G}{c^5}},
\end{equation}
serve as quantum gravity cutoffs in many theories \cite{Rovelli2004, Hossenfelder2013}. TLM remains agnostic; bounds \eqref{eq:main_bounds} depend on \(\Cs_{\max}\) and \(n\). Sub-Planck resolutions, if observed, revise \(\Cs_{\max}\); larger floors support TLM.

\section{Figure 1: Deployment Lattice and Null Cones}
\label{sec:fig1}
\begin{figure}[t]
\centering
\begin{tikzpicture}[scale=1.0]
  \draw[->] (-0.2,0) -- (8.2,0) node[right] {$x$};
  \draw[->] (0,-0.2) -- (0,5.8) node[above] {$ct$};
  \draw[thick, blue] (0,0) -- (5.6,5.6);
  \draw[thick, blue] (0,0) -- (-5.6,5.6);
  \foreach \i in {0,...,8}{
    \foreach \j in {0,...,5}{
      \draw[gray!40] (\i, \j) rectangle (\i+0.8,\j+0.8);
    }
  }
  \draw[fill=red!20,draw=red,very thick] (2.4,1.6) rectangle (3.2,2.4);
  \node[red] at (2.8,2.6) {\small $\ell_{\min} \times c t_{\min}$};
  \filldraw[black] (2.8,2.0) circle (1.5pt) node[below right] {\small event};
  \node at (6.2,5.2) {\small Light cones};
  \draw[thick, blue] (5.9,5.0) -- (6.7,5.8);
  \draw[thick, blue] (5.9,5.0) -- (5.1,5.8);
\end{tikzpicture}
\caption{Schematic deployment lattice: Events below highlighted cell violate bounds. GR null cones (blue) intact; discreteness in resolution only.}
\label{fig:lattice}
\end{figure}

\section{Figure 2: Delay Law Tradeoff}
\label{sec:fig2}
\begin{figure}[t]
\centering
\begin{tikzpicture}
\begin{axis}[
    width=0.95\linewidth,
    height=7cm,
    xlabel={$m$ or $\Cs$ (schematic units)},
    ylabel={$t_{\min}$ (arb.)},
    ymin=0.0, xmin=0.0,
    domain=0.2:5,
    samples=200,
    legend style={at={(0.98,0.98)},anchor=north east,draw=none,fill=none},
    grid=both
]
\addplot+[thick, blue] {1/x}; \addlegendentry{$t_{\min} = 1/\Cs$}
\addplot+[thick, red, dashed] {1/x}; \addlegendentry{$t_{\min} = 1/m$}
\end{axis}
\end{tikzpicture}
\caption{Tradeoff: Operational \(t_{\min}\) takes the maximum curve; \(\ell_{\min}\) from \eqref{eq:lfromt}.}
\label{fig:tradeoff}
\end{figure}

\section{Observational Consequences}
\label{sec:obs}
\begin{description}
\item[Interferometry:] Phase sensitivity saturates at long baselines; frequency sweeps test \(\omega\)-scaling.
\item[PTA:] Consistent residual floors across sight lines, potential-independent.
\item[Scattering:] Non-instrumental timing floors \(\sim 1/m\) in colliders.
\end{description}

\section{Falsifiability}
\label{sec:fals}
Residuals:
\begin{align}
\alpha_\star &: \text{ phase residual (expected 0)},\\
\Delta T_\star &: \text{ time residual (expected 0)}.
\end{align}
Predictions:
\begin{enumerate}[label=\arabic*.]
\item No extra steps post-GR corrections: \(\alpha_\star, \Delta T_\star \to 0\).
\item Floor per \eqref{eq:main_bounds}; violation revises or falsifies laws.
\item Achromatic residuals, unlike dispersive effects.
\end{enumerate}

\section{Discussion and Limits}
\label{sec:disc}
Focuses on deployment, not microstructure. Arbitrary small localizations at fixed SNR falsify or adjust laws. Universal floors support MFS. Agnostic to Planck coincidence.

\section{Conclusion}
\label{sec:concl}
MFS operationalizes SDF bounds in TLM, yielding testable \eqref{eq:main_bounds}. Preserves GR; falsifiable across domains. Clarifies timeless projections without costs.

\appendix

\section{Glossary}
\label{app:glossary}
\begin{description}
\item[SDF] GR layer \((\M, \g)\).
\item[QP] Timeless instruction issuer.
\item[ZeroSpace] Projection-only observation.
\item[\(\E, \A\)] Paired endpoints.
\item[\(\Pi\)] Map to \(\Gam\).
\item[\(\Gam\)] Null trace.
\item[\(T\)] Delay.
\item[\(\Cs\)] Rate; \(T \cdot \Cs = 1\).
\item[\(m\)] Mass; \(T \cdot m = \hbar / c^2\).
\item[\(\ell_{\min}, t_{\min}\)] Min sizes.
\item[\(n\)] Index \(1/V\).
\item[\(k^\mu\)] Wavevector; \(\Phi = \int k_\mu dx^\mu\).
\item[\(\alpha_\star, \Delta T_\star\)] Residuals.
\end{description}

\section{Phase Bounds Notes}
\label{app:rigor}
Geometric optics: \(\Psi = A e^{iS/\epsilon}\), \(k_\mu = \nabla_\mu S\), \(k^\mu k_\mu = 0\). Visibility: \(|\Delta \Phi| \gtrsim \pi\). Noise accumulation yields \eqref{eq:phase-noise}; static: \(dt = n d\ell_h\).

\begin{thebibliography}{99}

\bibitem{Einstein1916}
A.~Einstein, ``Die Grundlage der allgemeinen Relativit{\"a}tstheorie,'' \emph{Annalen der Physik}, vol.~49, pp.~769--822, 1916.

\bibitem{Peacock1999}
J.~A.~Peacock, \emph{Cosmological Physics}. Cambridge University Press, 1999.

\bibitem{McKinley2025_TLM}
J.~C.~W.~McKinley, ``Resolving Wave-Particle Duality Through the Proposed Timeless Light Model: Photons as Timeless Instructions and Waves as Deployed Delay,'' Zenodo, DOI:10.5281/zenodo.16510862, 2025.

\bibitem{McKinley2025_Cs}
J.~C.~W.~McKinley, ``Clarifying \(C_s\): Deployment Rate, Delay, and Simulation Parameters in the Timeless Light Model,'' Zenodo, DOI:10.5281/zenodo.15817350, 2025.

\bibitem{McKinley2025_Review}
J.~C.~W.~McKinley, ``A Review of the Timeless Light Model: Foundations, Derivations, and Empirical Predictions,'' Zenodo, DOI:10.5281/zenodo.16958221, 2025.

\bibitem{McKinley2025_v2}
J.~C.~W.~McKinley, ``Timeless Light Model (TLM v2.0): Frameless Quanta, Framed Observers, and Bridge Laws,'' Zenodo, DOI:10.5281/zenodo.16934697, 2025.

\bibitem{Rovelli2004}
C.~Rovelli, \emph{Quantum Gravity}. Cambridge University Press, 2004.

\bibitem{Hossenfelder2013}
S.~Hossenfelder, ``A possibility to solve the problems with quantizing gravity,'' \emph{Physics Letters B}, vol.~725, pp.~1--3, 2013.

\bibitem{Bombelli1987}
L.~Bombelli et al., ``Space-time as a causal set,'' \emph{Physical Review Letters}, vol.~59, pp.~521--524, 1987.

\end{thebibliography}

\end{document}
```

</details>

---
{% endraw %}
