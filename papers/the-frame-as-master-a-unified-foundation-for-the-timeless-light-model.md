---
layout: default
title: '[2025] The Frame as Master: A Unified Foundation for the Timeless Light Model'
description: 'Publication metadata and archived raw LaTeX source by John C. W. McKinley.'
permalink: /papers/the-frame-as-master-a-unified-foundation-for-the-timeless-light-model/
paper: true
---
{% raw %}
# [2025] The Frame as Master: A Unified Foundation for the Timeless Light Model
*   **DOI:** [10.5281/zenodo.16787219](https://doi.org/10.5281/zenodo.16787219)
*   **Date:** 9 August 2025

<details markdown="1">
<summary><b>Click to view Raw LaTeX Source</b></summary>

```latex
\documentclass[12pt,letterpaper]{article}

% ---------------------------------
% PACKAGES & SETUP
% ---------------------------------
\usepackage[margin=1in]{geometry}
\usepackage[utf8]{inputenc}
\usepackage[T1]{fontenc}
\usepackage{lmodern}
\usepackage{setspace}
\onehalfspacing
\usepackage{amsmath,amssymb,amsfonts}
\usepackage{booktabs}
\usepackage{tikz}
\usetikzlibrary{positioning,arrows.meta}
\tikzset{>=Latex, box/.style={draw,rounded corners,thick,align=center}}
\usepackage{graphicx}
\usepackage{microtype}

\usepackage[dvipsnames]{xcolor}      % safe colors; optional but nice
\usepackage[most]{tcolorbox}         % loads core + common libraries
\tcbuselibrary{breakable,skins}      % allow page breaks + titles/skins


% Keep hyperref LAST
\usepackage{hyperref}
\hypersetup{colorlinks=true,linkcolor=blue,urlcolor=blue,citecolor=blue}

% ---------------------------------
% TITLE
% ---------------------------------
\title{\textbf{The Frame as Master: A Unified Foundation for the Timeless Light Model}}


\author{John C. W. McKinley \\ Independent Researcher \\ \href{https://orcid.org/0009-0005-7097-5035}{0009-0005-7097-5035}}
\date{August 9, 2025}


% ---------------------------------
% DOC
% ---------------------------------
\begin{document}
\maketitle

\renewcommand{\thefootnote}{}
\footnotetext[1]{This version published at \href{https://doi.org/10.5281/zenodo.16787219}{doi.org/10.5281/zenodo.16787219.}}


% --- ABSTRACT ---
\begin{abstract}
We propose that the fundamental physical actor in both General Relativity (GR) and Quantum Mechanics (QM) is not the particle, the field, or the wavefunction — but the \emph{frame}. In the Timeless Light Model (TLM), a frame is the minimal unit of spacetime deployment: a definable position and state in which pre-resolved instructions from the Quantum Platform (QP) are rendered. By making the frame the \emph{master controller of reality}, all observed physics emerges from the relationships and timing of two frame classes: massless frames ($m=0,\; T=0$) and mass-bearing frames ($m>0,\; T>0$), governed by the Mass–Delay Law $T\,m=1$ and the causal rendering law $T\,C_s=1$. This principle unifies GR’s geometry and QM’s instantaneous phenomena without altering accepted predictions, while providing causal clarity for effects such as entanglement, gravitational lensing, and the twin paradox.
\end{abstract}

% --- INTRODUCTION ---
\section{Introduction}\label{sec:intro}
General Relativity is built on a profound idea: physical law is the same in every inertial frame, and gravity is the geometry of spacetime. Yet, the frame itself is treated as a passive coordinate system --- a backdrop rather than a driver. The Timeless Light Model reframes the role of the frame: it is not a label for where things happen; it is where and how reality happens.

We elevate the frame from a passive reference to the \emph{primary causal agent}. This builds directly on the familiar reference frame of relativity (\href{https://doi.org/10.1002/andp.19163540702}{Einstein, 1916})---a local coordinate system defining position, motion, and observation---but empowers it as the active renderer of timeless instructions. Frames are the smallest meaningful stages for instruction deployment from the Quantum Platform (QP)\footnote{Earlier drafts and some priors used ``Photon Instruction Layer (PIL)''; we standardize on QP per the synthesis (McKinley, 2025), DOI: 10.5281/zenodo.16187719.} --- the timeless layer that pre-resolves all events. A frame may be \emph{massless}, deploying its instructions instantaneously, or \emph{mass-bearing}, deploying them with delay proportional to its mass. This binary distinction reproduces both the time dilation and geometry of GR, and the nonlocal correlations (\href{https://doi.org/10.1103/PhysicsPhysiqueFizika.1.195}{Bell, 1964})  of QM, without contradiction. This builds on prior reinterpretations of photons as timeless connections (McKinley, 2025; \href{https://doi.org/10.5281/zenodo.16510862}{doi:10.5281/zenodo.16510862}) and horizons as infinite delay loci \href{https://doi.org/10.5281/zenodo.16730926}{doi:10.5281/zenodo.16730926}, resolving Newtonian instabilities \href{https://doi.org/10.5281/zenodo.15826480}{doi:10.5281/zenodo.15826480}.

By taking the frame as master, we achieve a unified ontology: all of physics is frame physics. This perspective complements relational interpretations of quantum mechanics (\href{https://doi.org/10.1007/BF02302261}{Rovelli, 1996}).





% --- DEFINITION ---

\section{Definition of a Frame}\label{sec:def}
A \textbf{frame} in TLM is the same reference frame central to relativity: a local system defining position, orientation, and state relative to which physical laws are measured. However, in TLM it is elevated to the smallest unit of spacetime deployment in the Spacetime Deployment Frame (SDF); the receiver and renderer of a Quantum Platform instruction; classified by mass:
$m=0$ (massless) or $m>0$ (mass-bearing).
\begin{tcolorbox}[colback=gray!10,colframe=gray!50,title=Note on Ontological Structure]
The frame is treated as a blackbox component: its "contents" are emergent from the rendered instruction, including state properties like energy or momentum. It holds no innate metadata beyond its classification and position, ensuring minimality while avoiding an ontological void. Time-like effects (e.g., GR/SR metadata) arise solely during SDF deployment, not in the QP.
\end{tcolorbox}

Massless frames have $T=0$
 (no deployment delay: \emph{timeless} in SDF); mass-bearing frames have T>0
 according to
\begin{equation}
  T \, m = \frac{\hbar}{c^2} \qquad \text{(general form)},,
  \label{eq:Tm}
\end{equation}



\noindent Throughout we adopt natural units $\hbar=c=1$, so $T\,m=1$, meaning mass imposes inversely proportional deployment delay. We also use the causal rendering law
\begin{equation}
  T\,C_s = 1.
  \label{eq:TCs}
\end{equation}
Here $C_s$ is the causal rate (deployment rate) of the frame.



% --- AXIOMS ---
\section{Axioms of Frame Physics}\label{sec:axioms}
\begin{enumerate}
  \item \textbf{Frame Primacy.} Frames, not particles or waves, are the fundamental physical actors.\footnote{This primacy extends the standard reference frame of GR/SR, where frames are passive observers, to active controllers in TLM---rendering QP instructions while preserving local invariance.}
  \item \textbf{Instruction Precedence.} All frame states are the deployed result of pre-resolved instructions from the QP (ontologically senior to SDF).
  \item \textbf{Mass--Delay Law.} $T\,m=\hbar/c^2$ (natural units $T\,m=1$) governs deployment delay at the frame level; together with $T\,C_s=1$.
  \item \textbf{Connectivity Without Travel.} Photon-like ``paths'' are timeless connections between frames; intermediate SDF points are rendered geometry, not ontic waypoints.
  \item \textbf{Single-Absorber Principle.} Each photon-like instruction resolves to exactly one absorption frame.
  \item \textbf{Gravity as Frame Interaction.} Mass-induced delay gradients change relationships between frames, reproducing GR effects.
  \item \textbf{Frame Independence.} Initial frames are independent; apparent histories arise from QP instruction linking.
\end{enumerate}




















\section{Deriving $T\,m=\hbar/c^2$ (natural units $T\,m=1$) at the Frame Level}\label{sec:derivation}
In TLM, the effect of mass is to introduce deployment delay $T$ for instruction realization in the SDF. Define the causal rate $C_s\equiv 1/T$. The Mass--Delay Law in its general form is $T\,m=\hbar/c^2$; adopting natural units ($\hbar=c=1$) recovers $T\,m=1$. Together with the causal rendering law $T\,C_s=1$, this formalizes the deployment kinematics at the frame level as presented in the TLM synthesis (McKinley, 2025; DOI:10.5281/zenodo.16187719). Thus $m=0\Rightarrow T=0$ (instantaneous deployment) while large $m$ implies long delay.

% --- FRAME TYPES ---
\section{Massless vs.~Mass-Bearing Frames}\label{sec:types}
\subsection{Massless Frames ($m=0$)}\label{subsec:massless}
Timeless, instantaneous connections; responsible for quantum nonlocality, photon behavior, and correlations outside SDF time.

\subsection{Mass-Bearing Frames ($m>0$)}\label{subsec:massive}
Subject to GR-like delays, curvature effects, and finite propagation constraints; responsible for gravitational interaction, time dilation, and inertial effects.

% --- DIAGRAM ---
\section{Frame Map Diagram}\label{sec:diagram}
\begin{figure}[htbp]
  \centering
  \resizebox{0.95\linewidth}{!}{%
  \begin{tikzpicture}[node distance=2.2cm, every node/.style={font=\normalsize}]
    % Quantum Platform
    \node[box, fill=blue!10, text width=5.2cm] (QP)
      { \textbf{Quantum Platform (QP)}\\[2pt] Pre-resolved timeless instructions };

    % Frame split
    \node[box, fill=yellow!12, below left=1.6cm and 4.0cm of QP, text width=4.6cm] (Massless)
      { \textbf{Massless Frame}\\[2pt] $m=0,\; T=0$\\[1pt] (Timeless) };
    \node[box, fill=orange!12, below right=1.6cm and 4.0cm of QP, text width=4.8cm] (Massive)
      { \textbf{Mass-Bearing Frame}\\[2pt] $m>0,\; T>0$\\[1pt] (Delayed) };

    % GR and QM boxes
    \node[box, fill=green!12, below=2.6cm of Massless, text width=5.6cm] (QM)
      { \textbf{Quantum Mechanics}\\[2pt] Instantaneous connections\\[1pt] (e.g., entanglement, collapse) };
    \node[box, fill=red!12, below=2.6cm of Massive, text width=5.8cm] (GR)
      { \textbf{General Relativity}\\[2pt] Geometry of delayed frames\\[1pt] (e.g., gravity, time dilation) };

    % Arrows from QP
    \draw[->, thick] (QP.south west) to[out=260, in=90] (Massless.north);
    \draw[->, thick] (QP.south east) to[out=280, in=90] (Massive.north);

    % Arrows to GR/QM
    \draw[->, thick] (Massless.south) -- (QM.north);
    \draw[->, thick] (Massive.south) -- (GR.north);

    % Double arrow between GR and QM
    \draw[<->, dashed, thick] (QM.east) -- (GR.west)
      node[midway, above, sloped] {Unified by Frame Axioms};

    % Legend
    \node[align=left, text width=11.5cm, below=2cm of $(QM)!0.5!(GR)$] (Legend) {
      \textbf{Legend:}\\[-2pt]
      1.\; QP = Timeless instruction source\\
      2.\; Massless frame: $m=0$, $T=0$\\
      3.\; Mass-bearing frame: $T\,m=1$\\
      4.\; GR and QM emerge from the same frame system
    };
  \end{tikzpicture}}
  \caption{Schematic of QP-driven frame split and emergent GR/QM behavior.}
  \label{fig:frame-map}
\end{figure}

% --- STRESS TEST TABLE ---
\section{Stress Test Against Paradoxes}\label{sec:stress}
\begin{center}
  \renewcommand{\arraystretch}{1.3}
  \begin{tabular}{p{3.2cm} p{5.2cm} p{6.1cm}}
  \toprule
  \textbf{Phenomenon} & \textbf{Standard GR/QM View} & \textbf{Frame-as-Master Resolution} \\
  \midrule
  Twin Paradox & Time dilation from velocity & Proper-time accrual differs due to velocity-induced delay multipliers $\Gamma(v)$; resolves asymmetry via frame delay accounting. \\
  EPR Entanglement & Nonlocal collapse & Outcomes share a massless-frame connection outside SDF time; no superluminal signaling. \\
  Gravitational Lensing & Light follows curved spacetime & Apparent bending from delay-geometry in SDF projection of a timeless connection; matches Shapiro-type integrals. \\
  Black Hole Horizon & Infinite time dilation & $T\to\infty$ near horizon in SDF; QP resolution remains well-defined. \\
  Cosmic Redshift & Expanding space stretches wavelength & Destination-frame recession lowers rendered frequency via geometric deployment. \\
  Wavefunction Collapse & Probabilistic collapse & Instruction resolves into a mass-bearing frame with finite $T$; superposition persists for massless links. \\
  Shapiro Delay & Light slows near mass & Extra latency is a line integral of $-\Phi/c^2$ along the projected path (achromatic in vacuum). \\
  Inertia / Simultaneity & Relative motion alters simultaneity & Differences in instruction sequencing across frames fix simultaneity conventions. \\
  Vacuum Energy & Virtual particles in vacuum & Ephemeral frames are not written back as lasting absorptions; no persistent deployment. \\
  Holographic Principle & 3D from a boundary & Frames emerge as projections from a QP boundary layer; consistent with information bounds. \\
  Single-Photon Splitting & Beam-splitter paradox & Single-Absorber Principle: one instruction $\Rightarrow$ one absorption frame only. \\
  \bottomrule
  \end{tabular}
\end{center}
\noindent\footnotesize\emph{Note:} Predictions align with delay-based causality, preventing Newtonian failures (\href{https://doi.org/10.5281/zenodo.16750632}{doi:10.5281/zenodo.16750632}).  Contrasts with Newtonian absolute time (\href{https://doi.org/10.5479/sil.52126.39088015628399}{Newton, 1687}), as resolved in priors.
\normalsize



% --- IMPLICATIONS ---
\section{Implications and Predictions}\label{sec:implications}
\begin{itemize}
  \item All physical phenomena can be re-expressed as frame interactions over $T$ fields.
  \item The $m=0$ vs.~$m>0$ split predicts measurable differences in propagation and correlation without modifying accepted equations.
  \item Frame-centric modeling may suggest new experimental falsifiability conditions for TLM 
  consistent with empirical confrontations of GR (\href{https://doi.org/10.12942/lrr-2014-4}{Will, 2014}; \href{https://www.wiley.com/en-us/Gravitation+and+Cosmology%3A+Principles+and+Applications+of+the+General+Theory+of+Relativity-p-9780471925675}{Weinberg, 1972}), such as horizon-scale phase shifts in gravitational waves (as predicted in the BH prior, \href{https://doi.org/10.5281/zenodo.16730926}{doi:10.5281/zenodo.16730926}; consistent with entropic-gravity arguments in \href{https://doi.org/10.1103/PhysRevLett.75.1260}{Jacobson, 1995}) and photon reinterpretations resolving wave--particle duality (McKinley, 2025; \href{https://doi.org/10.5281/zenodo.16510862}{doi:10.5281/zenodo.16510862}; see also \href{https://doi.org/10.1103/PhysRevLett.116.061102}{Abbott et\,al., 2016}).
\end{itemize}

% --- CONCLUSION ---
\section{Conclusion}\label{sec:conclusion}
By making the frame the master controller of reality, the Timeless Light Model unifies GR and QM under a single causal ontology. Massless and mass-bearing frames, governed by the Mass–Delay and causal rendering laws, explain both the instantaneous phenomena of QM and the geometric effects of GR as projections of the same underlying instruction system.

% =========================
% ======== APPENDICES =====
% =========================
\appendix

% --- APPENDIX A ---
\section{Glossary of Terms}\label{app:glossary}
{\footnotesize\emph{Entropy note:} We use $S = k_B \ln |H(t)|$ per the TLM synthesis.\par}\vspace{0.3em}
\begin{description}
  \item[Quantum Platform (QP):] Timeless, ontologically senior layer from which all spacetime events are pre-resolved before deployment into the SDF.
  \item[Spacetime Deployment Frame (SDF):] The projected 4D geometry in which frames appear to observers; the stage for observable GR/QM effects.
  \item[Frame:] Minimal unit of deployment in the SDF. Receives instructions from QP and renders them as physical events.
  \item[Massless Frame:] $m=0$, $T=0$; instantaneous deployment; exists outside SDF time.
  \item[Mass-Bearing Frame:] $m>0$, $T>0$; deployment delay obeys $T\,m=1$.
  \item[Mass--Delay Law:] $T$ (delay) and $m$ (mass) are inversely proportional: $T\,m=1$.
  \item[Causal Rendering Law:] $T\,C_s=1$ with $C_s$ the causal (deployment) rate.
  \item[Instruction Resolution:] QP finalizing a frame's state before it appears in the SDF.
  \item[Timeless Connection:] A link between two frames in QP that appears as a finite-speed path in SDF.
  \item[Single-Absorber Principle:] Each photon-like instruction resolves to exactly one absorption frame.
\end{description}

% --- APPENDIX B ---
\section{Rigorous Mathematical Derivations}\label{app:math}
\subsection{Derivation of $T\,m=1$ from Causal Invariance}\label{app:deriv}
Assume the Quantum Platform maintains a constant \emph{causal rate} $C_s$ for a given frame state:
\begin{equation}
  C_s = \frac{\text{\# of resolved instructions}}{\text{unit of QP causal time}}.\label{eq:CsDef}
\end{equation}
Let $T$ be the deployment delay of that frame in the SDF. Identifying deployment rate with causal rate yields $C_s=1/T$ and thus
\begin{equation}
  m = \frac{1}{T} \quad \Rightarrow \quad T\,m = 1.\label{eq:TmDerive}
\end{equation}

\subsection{Limits: Massless and Infinite-Mass Frames}\label{app:limits}
For $m\to 0$, $T\to 0$ (instantaneous deployment, matching vanishing photon proper time in SR). For $m\to \infty$, $T\to \infty$ (deployment frozen in SDF; horizon-like behavior).

\subsection{Mapping to GR and QM}\label{app:map}
In GR, proper time obeys $\mathrm{d}\tau = \sqrt{g_{\mu\nu}\,\mathrm{d}x^\mu\,\mathrm{d}x^\nu}$. In TLM, parameterize deployment with $\lambda$ and write
\begin{equation}
  \mathrm{d}\tau = \frac{1}{C_s}\,\mathrm{d}\lambda = T\,\mathrm{d}\lambda,\label{eq:tauCs}
\end{equation}
so curvature or velocity modify $T$ to reproduce dilation effects. In QM, superpositions persist as massless connections (no $T$ penalty) until an absorption resolves to a mass-bearing frame (finite $T$).

\subsection{Photon Connection Without Ontic Travel}\label{app:photon}
Let $F_e$ and $F_a$ denote emission and absorption frames with $T=0$. In QP they are linked timelessly. The SDF projection renders an apparent path of length $L$ at speed $c$; the “travel” is geometric rendering, not ontic motion between intermediate frames.

\subsection{Residual Phase Predictions}\label{app:residual}
SDF projection is a geometric transform of QP resolutions; small changes to intermediate mass-bearing frames produce residual phases between linked endpoints. Interferometers should register tiny, geometry-predictable phase shifts synchronized with gravitational potential variations or GW strain.

% --- APPENDIX C ---
\section{Causal Diagram of the Frame-as-Master Model}\label{app:diagram}
\begin{center}
  \resizebox{0.95\linewidth}{!}{%
  \begin{tikzpicture}[node distance=2cm, >=latex, thick]
    % QP
    \node[draw, rounded corners, fill=blue!10, text width=4.2cm, align=center] (QP) {Quantum Platform (QP) \\ Timeless, pre-resolved instructions};
    % Frame split
    \node[draw, rounded corners, fill=yellow!10, below left=2cm and 3.5cm of QP, text width=4cm, align=center] (Massless) {Massless Frame \\ $m=0$, $T=0$ \\ Instantaneous deployment};
    \node[draw, rounded corners, fill=orange!10, below right=2cm and 3.5cm of QP, text width=4cm, align=center] (Massive) {Mass-Bearing Frame \\ $m>0$, $T>0$ \\ Delayed deployment};
    % Mass-delay law box
    \node[draw, rounded corners, fill=gray!10, below=2.5cm of QP, text width=4.8cm, align=center] (Law) {Mass–Delay Law \\ $T\,m=1$ \\ (Natural units)};
    % Outputs
    \node[draw, rounded corners, fill=green!10, below=3cm of Massless, text width=4.8cm, align=center] (QM) {Quantum Mechanics Limit \\ Instantaneous correlations \\ Nonlocal effects};
    \node[draw, rounded corners, fill=red!10, below=3cm of Massive, text width=4.8cm, align=center] (GR) {General Relativity Limit \\ Time dilation, curvature \\ Finite propagation speed};
    % Arrows
    \draw[->] (QP.south west) -- (Massless.north);
    \draw[->] (QP.south east) -- (Massive.north);
    \draw[->] (QP.south) -- (Law.north);
    \draw[->] (Massless.south) -- (QM.north);
    \draw[->] (Massive.south) -- (GR.north);
    % Unification
    \draw[<->, dashed] (QM.east) -- (GR.west) node[midway, above, sloped] {Unified by Frame Physics};
    % Notes
    \node[below=1cm of GR, text width=12cm, align=left] (Legend) {\textbf{Summary:} QP resolves events; frames deploy them. The mass class sets $T$ via $T\,m=1$, yielding QM (massless) and GR (mass-bearing) behaviors as projections of one system.};
  \end{tikzpicture}}
\end{center}

% --- APPENDIX D ---
\section{Worked Examples in Frame Physics}\label{app:examples}
\noindent Datasets and observing catalogs referenced herein include LVK GWTC-3 (\href{https://doi.org/10.1103/PhysRevX.13.041039}{Abbott et\,al., 2023}).
\subsection{Notation and Laws Used}\label{app:notation}
We use natural units $(\hbar=c=1)$ unless otherwise noted; in these units the general law $T\,m=\hbar/c^2$ reduces to $T\,m=1$. We use deployment-level laws
\begin{align}
  T\,m &= 1, \label{eq:TmOne}\\
  T\,C_s &= 1. \label{eq:TCsOne}
\end{align}
With deployment parameter $\lambda$,
\begin{equation}
  \mathrm{d}\tau = \frac{1}{C_s}\,\mathrm{d}\lambda = T\,\mathrm{d}\lambda.\label{eq:tauLaw}
\end{equation}
\paragraph{Velocity-induced delay.} In SR, $\gamma(v)=1/\sqrt{1-v^2/c^2}$. Treat velocity as delay multiplier $\Gamma(v)\equiv\gamma(v)$ and $T(v)=\Gamma(v)\,T_0$.
\paragraph{Potential-induced delay.} In a weak, static potential $\Phi(\mathbf{x})$ with $|\Phi|/c^2\ll1$,
\begin{equation}
  \mathrm{d}\tau \approx \left(1+\frac{\Phi}{c^2}\right)\mathrm{d}t \;\Rightarrow\; T(\mathbf{x}) \approx T_0\left(1-\frac{\Phi}{c^2}\right)^{-1},\label{eq:weakfieldT}
\end{equation}
so $\delta T/T_0 \approx -\,\Phi/c^2$ to first order.

\subsection{Twin Paradox as Frame-Delay Accounting}\label{app:twin}
Twin A remains inertial; twin B travels at constant speed $v$, turns around, returns. Let the total coordinate duration in A’s frame be $t$. Using \eqref{eq:tauLaw} with $\lambda=t$ and $T(v)=T_0/\gamma(v)$:
\begin{align}
  \tau_A &= \int_0^{t} T_0\,\mathrm{d}t = t\,T_0,\\
  \tau_B &= \int_0^{t} \frac{T_0}{\gamma(v)}\,\mathrm{d}t = \frac{t}{\gamma(v)}\,T_0.
\end{align}
Hence $\Delta \tau = t\,T_0\big(1-1/\gamma(v)\big)$.

\subsection{Shapiro Delay as a Line Integral of Frame Delay}\label{app:shapiro}
A massless connection (projected light ray) grazes a mass $M$ at impact parameter $b$. From \eqref{eq:weakfieldT}, the extra deployment delay along path $\mathcal{C}$ is
\begin{equation}
  \Delta t = -\frac{1}{c^3}\int_{\mathcal{C}} \Phi(\mathbf{x})\,\mathrm{d}\ell \approx \frac{2GM}{c^3}\ln\!\left(\frac{4 r_e r_r}{b^2}\right),\label{eq:shapiro}
\end{equation}
matching the GR Shapiro delay.

\subsection{Interferometric Residual from Time-Varying Delay}\label{app:interf}
For monochromatic frequency $\omega$ and two arms sampling different delay fields $T_1(t),T_2(t)$, the phase difference is
\begin{equation}
  \Delta\phi(t) = \omega\int \big[\delta T_1-\delta T_2\big]\,\frac{\mathrm{d}\ell}{c} \sim \omega\,\frac{L}{c}\,\alpha\,h_{\mathrm{rms}},\label{eq:phiScaling}
\end{equation}
if a metric strain $h(t)$ induces fractional modulation $\delta T/T_0 \sim \alpha\,h(t)$.

% --- REFERENCES ---
\section*{References}\label{sec:refs}
\begin{enumerate}
  \item C. Rovelli, ``Relational quantum mechanics,'' \emph{International Journal of Theoretical Physics}, 35, 1637 (1996). \href{https://doi.org/10.1007/BF02302261}{doi:10.1007/BF02302261}.
  \item T. Jacobson, ``Thermodynamics of Spacetime: The Einstein Equation of State,'' \emph{Phys. Rev. Lett.}, 75, 1260 (1995). \href{https://doi.org/10.1103/PhysRevLett.75.1260}{doi:10.1103/PhysRevLett.75.1260}.
  \item B. P. Abbott et\,al., ``Observation of Gravitational Waves from a Binary Black Hole Merger,'' \emph{Phys. Rev. Lett.}, 116, 061102 (2016). \href{https://doi.org/10.1103/PhysRevLett.116.061102}{doi:10.1103/PhysRevLett.116.061102}.
  \item R. Abbott et al. (LIGO Scientific, Virgo, and KAGRA Collaborations), ``GWTC-3: Compact Binary Coalescences Observed by LIGO and Virgo During the Second Part of the Third Observing Run,'' \emph{Phys. Rev. X}, 13, 041039 (2023). \href{https://doi.org/10.1103/PhysRevX.13.041039}{doi:10.1103/PhysRevX.13.041039}.
  \item J. C. W. McKinley, \emph{Foundational Equations and Axiomatic Structure of the Timeless Light Model: A Synthesis Across Sixty Papers and Working Notes (v1.0)} (2025). \href{https://doi.org/10.5281/zenodo.16187719}{doi:10.5281/zenodo.16187719}.
  \item J. C. W. McKinley, \emph{Resolving Wave–Particle Duality Through the Proposed Timeless Light Model: Photons as Timeless Instructions and Waves as Deployed Delay} (2025). \href{https://doi.org/10.5281/zenodo.16510862}{doi:10.5281/zenodo.16510862}.
  \item J. C. W. McKinley, \emph{Falsifiable Prediction of Horizon-Scale Phase Shifts in Gravitational Waves from the Timeless Light Model} (2025). \href{https://doi.org/10.5281/zenodo.16730926}{doi:10.5281/zenodo.16730926}.
\item J. C. W. McKinley, \emph{The Failure of the Newtonian Holodeck: Why a Universe Without Relativity Cannot Sustain Itself} (2025). \href{https://doi.org/10.5281/zenodo.16750632}{doi:10.5281/zenodo.16750632}.

\item J. C. W. McKinley, \emph{Causality Without Light Speed: Reframing c as Structure, Not Law} (2025). \href{https://doi.org/10.5281/zenodo.15826480}{doi:10.5281/zenodo.15826480}.

\item S. Weinberg, \emph{Gravitation and Cosmology: Principles and Applications of the General Theory of Relativity} (John Wiley \& Sons, New York, 1972). \href{https://www.wiley.com/en-us/Gravitation+and+Cosmology%3A+Principles+and+Applications+of+the+General+Theory+of+Relativity-p-9780471925675}{Link}.










  
\end{enumerate}

\end{document}
```

</details>

---
{% endraw %}
