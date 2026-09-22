---
layout: default
title: '[2025] Bridge Laws in the Timeless Light Model: From Timeless Instructions to Rendered Spacetime'
description: 'Publication metadata and archived raw LaTeX source by John C. W. McKinley.'
permalink: /papers/bridge-laws-in-the-timeless-light-model-from-timeless-instructions-to-rendered-spacetime/
paper: true
---
{% raw %}
# [2025] Bridge Laws in the Timeless Light Model: From Timeless Instructions to Rendered Spacetime
*   **DOI:** [10.5281/zenodo.17240091](https://doi.org/10.5281/zenodo.17240091)
*   **Date:** 30 September 2025

<details markdown="1">
<summary><b>Click to view Raw LaTeX Source</b></summary>

```latex
\documentclass[12pt,onecolumn]{article}

% ---------- Page & Layout ----------
\usepackage[margin=1in]{geometry}
\usepackage[T1]{fontenc}
\usepackage[utf8]{inputenc}
\usepackage{lmodern}
\usepackage{microtype}
\usepackage{setspace}
\onehalfspacing

% ---------- Math ----------
\usepackage{amsmath,amssymb,amsthm}
\usepackage{mathtools}

% ---------- Figures & Plots ----------
\usepackage{tikz}
\usetikzlibrary{arrows.meta,positioning,calc}
\usepackage{pgfplots}
\pgfplotsset{compat=1.18}
\usepackage{graphicx}
\usepackage{float}
\usepackage{booktabs}

% ---------- Links & References ----------
\usepackage{hyperref}
\usepackage{cleveref}
\hypersetup{
  colorlinks=true,
  linkcolor=blue,
  urlcolor=blue,
  citecolor=blue
}

% ---------- Headers ----------
\usepackage{fancyhdr}
\pagestyle{fancy}
\fancyhf{}
\lhead{Bridge Laws in the Timeless Light Model}
\rhead{\thepage}

% ---------- ORCID ----------
\usepackage{orcidlink}

% ---------- Title ----------
\title{\textbf{Bridge Laws in the Timeless Light Model}\\
From Timeless Instructions to Rendered Spacetime}

\author{John C. W. McKinley\orcidlink{0009-0005-7097-5035}\\Independent Researcher\thanks{Preprint DOI: \href{https://doi.org/10.5281/zenodo.17240091}{10.5281/zenodo.17240091}}}
\date{September 30, 2025}

% ---------- Lawbox ----------
\usepackage[most]{tcolorbox}
\tcbset{colback=blue!5!white,colframe=blue!75!black,fonttitle=\bfseries}
\newtcolorbox{lawbox}[2][]{colback=blue!5!white,colframe=blue!65!black,fonttitle=\bfseries,title=#2,#1}

\begin{document}
\maketitle

\begin{abstract}
We formalize the \emph{Bridge Laws} that connect the Timeless Light Model’s (TLM) two ontological layers: a timeless \emph{Quantum Platform} (QP) where emission--absorption instructions are authored, and a rendered \emph{Spacetime Deployment Frame} (SDF) where observers experience sequential events. Bridge Law I (Mass--Delay Duality, $T\cdot m=\hbar/c^2$) encodes how mass induces rendering delay; Bridge Law II (Causal Speed, $T\cdot C_s=1$) constrains the deployment rate of instructions. Together they explain why massless quanta (photons) have no proper time (no frame) while information transfer for observers remains limited by $c$. We clarify terminology (\emph{deployment filters}), distinguish recovery of SR/GR from TLM axioms, add the Generalized Pairing Law (GPL) for QP finalization, detail falsifiable predictions (e.g.\ entanglement latency $\Delta t\!\sim\!GM_{\text{det}}/c^3$; GW phase residuals), and compare TLM with the holographic principle and Loop Quantum Gravity.
\end{abstract}

% =====================================================
\section{Introduction}
A recurring confusion in relativity pedagogy is the apparent contradiction between saying that light has speed $c$ and saying that photons experience no time. The tension dissolves once we separate (i) what is authored in a timeless layer and (ii) what is rendered as experience. We therefore introduce \emph{Bridge Laws} that map timeless records to the observer’s spacetime experience.

% =====================================================
\section{Background: SR Null Structure and No Photon Frame}
\label{sec:SR}
In Minkowski spacetime,
\begin{equation}
  ds^{2}=-c^{2}d\tau^{2}=-c^{2}dt^{2}+dx^{2}+dy^{2}+dz^{2}.
\end{equation}
For lightlike propagation ($ds^{2}=0$),
\begin{equation}
  d\tau=0,
\end{equation}
so photons accrue no proper time and admit no rest frame. Attempting a Lorentz boost to $v'=0$ from $v=c$ fails because
\begin{equation}
  v'=\frac{v-u}{1-\frac{vu}{c^{2}}},\quad v=c \;\Rightarrow\; 
  v'=\frac{c-u}{1-\frac{u}{c}} \;\text{is undefined at } u=c.
\end{equation}

\begin{figure}[H]
\centering
\begin{tikzpicture}[scale=1.0]
  \draw[->] (0,0) -- (0,5) node[above] {Time $t$};
  \draw[->] (0,0) -- (5,0) node[right] {Space $x$};
  \draw[thick,blue] (0,0) -- (1,4) node[midway,left] {Massive (timelike)};
  \draw[thick,red] (0,0) -- (4,4) node[midway,above] {Photon (null)};
  \node at (2.5,-0.5) {Minkowski: timelike vs.\ null ($d\tau=0$ for photons)};
\end{tikzpicture}
\caption{Timelike worldlines accumulate proper time; null worldlines do not.}
\label{fig:minkowski}
\end{figure}

% =====================================================
\section{The Timeless Light Model (TLM)}
\label{sec:TLM}
\paragraph{Architecture.}
\begin{itemize}
  \item \textbf{Quantum Platform (QP):} A timeless issuance layer in which complete emission--absorption records (CI-ARCs) are authored and finalized (no partial records).
  \item \textbf{Spacetime Deployment Frame (SDF):} The observer layer where finalized CI-ARCs appear as sequential events, constrained by deployment rules.
\end{itemize}

\paragraph{Dual filtering.}
Deployment from QP to SDF is shaped by two filters:
\begin{enumerate}
  \item \emph{Delay (GR-associated) filter:} mass-induced rendering delay $T$ governed by Bridge Law I.
  \item \emph{Structure (QM-associated) filter:} quantum-structural constraints (e.g.\ superposition/measurement) determining allowed event structure.
\end{enumerate}
These are \emph{filters} because they shape timing/ordering of already-finished instructions; they are not equations of motion within the SDF.

\subsection{Generalized Pairing Law (GPL): Finalization on QP}
\label{sec:gpl}
\begin{lawbox}{Generalized Pairing Law (GPL)}
A CI-ARC is recorded on the QP iff a compatible absorber exists; there are no half-written records. GPL is strictly a QP rule. Deployment filters act \emph{after} finalization, shaping how the finished record appears to observers in SDF.
\end{lawbox}

% =====================================================
\section{Bridge Laws (Deployment Filters)}
\label{sec:bridge}

\paragraph{Why “deployment filters”.}
They act \emph{between} the timeless QP and the rendered SDF. A CI-ARC is complete on QP; the SDF does not \emph{create} or \emph{propagate} it. Instead, the instruction is \emph{filtered} into observer experience by (i) a delay gate (Bridge Law I) and (ii) a causal-rate gate (Bridge Law II).

\begin{lawbox}{Bridge Law I: Mass--Delay Duality}
\label{law:delay}
\[
T \cdot m = \frac{\hbar}{c^{2}}.
\]
\textbf{Interpretation.} $T$ is the rendering delay per instruction step in the SDF; $m$ is invariant mass. Massive systems ($m>0$) deploy with $T>0$, accruing proper time; for massless quanta ($m=0$), $T=0$ (no delay). Time dilation is reinterpreted as deployment drag.
\end{lawbox}

\begin{lawbox}{Bridge Law II: Causal Speed}
\label{law:cs}
\[
T \cdot C_{s} = 1.
\]
\textbf{Interpretation.} $C_{s}$ is the causal deployment rate (instructions per unit observer time). $T\!\to\!0$ $\Rightarrow$ formal $C_{s}\!\to\!\infty$ on QP, while SDF projection preserves a finite invariant information speed $c$ for observers.
\end{lawbox}

\paragraph{Status relative to SR/GR.}
BL-II aligns with SR’s invariant causal cap and light-cone structure. BL-I is \emph{not} a GR/SR identity; it is a TLM axiom that \emph{recovers} familiar dilation locally while enabling new, testable structure beyond standard formulations (\cref{sec:predictions}).

% =====================================================
\section{Derivation Roadmap (Sketches with Pointers to Proofs)}
\label{sec:rigor}

\subsection{Dimensional checks}
\paragraph{BL-I.} $[T m]=[{\rm time}]\,[{\rm mass}]$ and $[\hbar/c^{2}]=[{\rm energy}\!\cdot\!{\rm time}]/[{\rm speed}]^{2}=[{\rm mass}]$. Hence $T m=\hbar/c^{2}$ has units of mass; equivalently $T=\hbar/(m c^{2})$ has units of time.
\paragraph{BL-II.} $[T C_{s}]=[{\rm time}]\,[1/{\rm time}]=1$ (dimensionless), matching an inverse-rate relation.

\subsection{What is proved where}
To avoid duplication, the heuristic sketches are summarized here and the full arguments are in \S\ref{sec:formal-proofs}:
\begin{itemize}
  \item \textbf{Lorentz kinematics from BL-II:} finite invariant information speed $\Rightarrow$ Lorentz transformations (see Proposition~1 in \S\ref{sec:formal-proofs}).
  \item \textbf{Gravity in the weak field:} delay field $T(\mathbf{x})$ with lapse $\phi=-c^{2}\ln(T/T_0)$ reproduces Newtonian acceleration and Poisson’s equation; redshift follows (Proposition~2).
  \item \textbf{GR as an equation of state:} local horizon thermodynamics + Clausius relation $\Rightarrow$ Einstein field equations (Proposition~3).
  \item \textbf{Schrödinger from structure filtering:} variational principle with Fisher-information term $\Rightarrow$ continuity + quantum HJ $\Rightarrow$ SE (Proposition~4).
\end{itemize}

\subsection{Status note}
Items stated informally above are established rigorously in \S\ref{sec:formal-proofs}. Predictive consequences (entanglement latency, GW residuals) are operationalized in \S\ref{sec:predictions}.














% =====================================================
\section{Formal Derivations: SR Kinematics, Gravity, and Schrödinger from the Bridge Laws}
\label{sec:formal-proofs}

\subsection{Lorentz Kinematics from BL-II (finite causal cap)}
\begin{lawbox}{Proposition 1 (Lorentz transformations from BL-II\\  relativity - homogeneity - isotropy)}
Assume: (i) the \emph{Relativity Principle} (all inertial frames equivalent); (ii) spacetime \emph{homogeneity} and \emph{spatial isotropy}; (iii) \emph{BL-II} $T\cdot C_s=1$ implies a finite, frame-independent information speed $c$ (null front). Then inertial transformations between frames are \emph{Lorentz} (up to trivial translations): for a boost in $x$,
\[
\begin{aligned}
t' &= \gamma\!\left(t - \frac{v x}{c^2}\right),\qquad
x' \;=\; \gamma\,(x - v t),\qquad
y'=y,\;z'=z,\\
\gamma &\equiv \frac{1}{\sqrt{1 - v^2/c^2}}.
\end{aligned}
\]
\end{lawbox}

\begin{proof}
By homogeneity, the transformation between inertial frames is linear. Isotropy restricts the most general linear map to the standard $x$–boost form with two unknown functions $a(v),\,b(v)$:
\[
t' = a(v)\,t + b(v)\,x,\qquad x' = d(v)\,t + e(v)\,x.
\]
The relativity principle forces a group structure in $v$ (velocity addition law) and the inverse map to have the same form with $-v$. BL-II furnishes a frame-independent null speed: the set of rays $x=\pm c t$ must map to $x'=\pm c t'$ in \emph{every} inertial frame. Enforcing invariance of these two null families yields
\[
\frac{x'}{t'}=\pm c \quad \text{whenever}\quad \frac{x}{t}=\pm c,
\]
which implies $a^2(v) - \frac{1}{c^2} d^2(v) = e^2(v) - c^2 b^2(v)$ and $a(v)e(v) - b(v)d(v)=1$. Composition of two boosts $v_1, v_2$ must produce a boost $v$ with the Einstein addition law; solving the functional equations under these constraints gives the Lorentz form with a universal constant $c$ and $\gamma=1/\sqrt{1-v^2/c^2}$. (This is the standard Ignatowsky-type derivation; BL-II supplies the needed finite invariant speed.)
\end{proof}

\subsection{Newtonian Limit and Redshift from the Delay Field}
Define the \emph{delay field} $T(\mathbf{x})$ and the lapse potential
\[
\phi(\mathbf{x}) \equiv -\,c^{2}\,\ln\!\frac{T(\mathbf{x})}{T_0}.
\]

\begin{lawbox}{Proposition 2 (Weak-field gravity and redshift from $T(\mathbf{x})$)}
In the quasi-static, weak-field regime with $|\phi|/c^2\ll 1$:
\begin{enumerate}
\item (Acceleration) Freely deploying records accelerate as
\[
\mathbf{a} \;=\; c^{2}\,\nabla \ln T \;=\; -\,\nabla \phi.
\]
\item (Poisson equation) If matter density $\rho(\mathbf{x})$ sources delay via
\[
\nabla^{2}\ln T \;\approx\; -\,\frac{4\pi G}{c^{2}}\,\rho,
\]
then $\nabla^{2}\phi \approx 4\pi G\rho$, i.e.\ Newtonian gravity.
\item (Redshift) Static clocks at $\mathbf{x}_1,\mathbf{x}_2$ obey
\[
\frac{\nu_2}{\nu_1} = \frac{T(\mathbf{x}_1)}{T(\mathbf{x}_2)}
\approx 1 + \frac{\phi(\mathbf{x}_1)-\phi(\mathbf{x}_2)}{c^{2}}.
\]
\end{enumerate}
\end{lawbox}

\begin{proof}
(1) Proper time increments scale as $d\tau \propto T\,dt$. Extremizing the deployed time functional yields geodesic-like motion with effective potential $-c^{2}\ln T$, giving $\mathbf{a}=c^{2}\nabla\ln T$. (2) Taking the Laplacian and using the sourcing ansatz gives $\nabla^{2}\phi = -c^{2}\nabla^{2}\ln T \approx 4\pi G\rho$. (3) Frequencies scale inversely with proper time, hence $\nu\propto 1/d\tau \propto 1/T$, yielding the stated ratio and its weak-field expansion.
\end{proof}

\subsection{Einstein-like Field Equations as an Equation of State}
We now show that, under local thermodynamic assumptions applied to \emph{null} deployments (consistent with BL-II), the spacetime field equations follow as an equation of state.

\begin{lawbox}{Proposition 3 (Local horizon thermodynamics $\Rightarrow$ Einstein equations)}
Assume for every spacetime event: (i) existence of local Rindler horizons generated by null vectors $k^{a}$; (ii) Clausius relation $\delta Q = \Theta\, dS$ for all such horizons, with Unruh temperature $\Theta=\hbar \kappa/(2\pi k_{B} c)$ (surface gravity $\kappa$) and entropy density $dS=\eta\, dA$ proportional to area; (iii) energy flux $\delta Q = \int T_{ab}\,\chi^{a}\,d\Sigma^{b}$ across the horizon (boost Killing $\chi^{a}$). Then the field equations
\[
R_{ab} - \tfrac{1}{2} R\, g_{ab} + \Lambda g_{ab} \;=\; \frac{8\pi G}{c^{4}}\,T_{ab}
\]
hold, with $G$ set by $\eta$ and $\Lambda$ an integration constant. The delay field $T(\mathbf{x})$ fixes the static lapse via $\phi=-c^{2}\ln(T/T_0)$ and is compatible with these equations in the weak-field limit of Proposition~2.
\end{lawbox}

\begin{proof}
Consider a small patch of a local causal horizon generated by $k^{a}$ with affine parameter $\lambda$ and area element $dA$. The Raychaudhuri equation for the expansion $\theta$ of the null congruence gives
\[
\frac{d\theta}{d\lambda} \;=\; -\tfrac{1}{2}\theta^{2} - \sigma_{ab}\sigma^{ab} - R_{ab}k^{a}k^{b}.
\]
To linear order near equilibrium, shear $\sigma_{ab}$ and $\theta^{2}$ terms are negligible; hence the area change $\delta A$ over $d\lambda$ is governed by $R_{ab}k^{a}k^{b}$. The heat flux across the horizon is $\delta Q = \int T_{ab}\chi^{a} d\Sigma^{b}$ with $\chi^{a}\propto \lambda k^{a}$ near the horizon. Using $\Theta$ as given (Unruh) and $dS=\eta\,\delta A$, the Clausius relation for \emph{all} $k^{a}$ implies $R_{ab}+\Phi g_{ab}=\xi T_{ab}$ for some scalars $\Phi,\xi$. Taking the divergence and using $\nabla^{a}T_{ab}=0$ with the Bianchi identity yields $\Phi=-\tfrac{1}{2}R+\Lambda$ and $\xi=8\pi G/c^{4}$, recovering the Einstein equations with $\Lambda$. Compatibility with Proposition~2 follows since in the static, weak-field sector $g_{00}\approx -\,(1+2\phi/c^{2})$ reproduces Poisson’s equation and redshift, while $\phi$ is set by $T$.
\end{proof}

\subsection{Nonrelativistic Schrödinger Equation from Deployment + Structure Filtering}
Let $\rho(\mathbf{x},t)$ be the event density and $S(\mathbf{x},t)$ the phase (action) field for a massive system of mass $m$. BL-I sets the characteristic time scale $T=\hbar/(m c^{2})$. The \emph{structure} filter enforces a least-action principle with a Fisher-information (quantum) penalty.

\begin{lawbox}{Proposition 4 (Variational derivation of Schrödinger’s equation)}
Consider the action
\[
\mathcal{A}[\rho,S] \;=\; \int dt \int d^{3}x\,\Big\{
\rho\Big(\partial_{t} S + \frac{(\nabla S)^{2}}{2m} + V\Big)
+ \frac{\hbar^{2}}{8m}\,\frac{(\nabla \rho)^{2}}{\rho}
\Big\}.
\]
Stationarity $\delta\mathcal{A}=0$ w.r.t.\ $S$ and $\rho$ yields the continuity equation $\partial_{t}\rho + \nabla\!\cdot(\rho\,\nabla S/m)=0$ and the quantum Hamilton–Jacobi equation $\partial_{t}S + (\nabla S)^{2}/(2m) + V - (\hbar^{2}/2m)\,\frac{\nabla^{2}\sqrt{\rho}}{\sqrt{\rho}}=0$. Setting $\psi=\sqrt{\rho}\,e^{iS/\hbar}$ gives
\[
i\hbar\,\partial_{t}\psi \;=\; -\,\frac{\hbar^{2}}{2m}\,\nabla^{2}\psi + V\,\psi.
\]
\end{lawbox}

\begin{proof}
Variation w.r.t.\ $S$ enforces probability conservation. Variation w.r.t.\ $\rho$ gives the Hamilton–Jacobi equation with the quantum potential $Q=-(\hbar^{2}/2m)\,\nabla^{2}\sqrt{\rho}/\sqrt{\rho}$. The Madelung substitution $\psi=\sqrt{\rho}\,e^{iS/\hbar}$ recombines the pair into the linear Schrödinger equation. BL-I provides the natural time scale entering $\hbar/m$, consistent with the quantum term.
\end{proof}

\paragraph{Remark (Consistency of layers).}
Proposition~1 shows that BL-II enforces Lorentz kinematics in SDF. Proposition~2 ties BL-I to Newtonian gravity and redshift. Proposition~3 promotes gravity to full GR as an equation of state for local null deployments, consistent with BL-II. Proposition~4 exhibits how the structure filter recovers standard nonrelativistic quantum dynamics, with $\hbar/m$ set by BL-I.









\subsection*{Cross-reference to full proofs}
For complete, non-heuristic treatments of (i) an Einstein–like field equation as an equation of state for delay-modulated spacetime (local horizon thermodynamics) and
(ii) recovery of the nonrelativistic Schr\"odinger equation from deployment+structure filtering,
see Appendix~C of \cite{mckinley_consideration}. Those proofs make precise the regularity, covariance, and variational assumptions under which the heuristic lines in \cref{sec:emergence,sec:rigor} and the propositions in \cref{sec:formal-proofs} obtain as theorems.


















% =====================================================
\section{From Bridge Laws to SR/GR: Emergence, Not Control}
\label{sec:emergence}
The Bridge Laws do not ``control'' SR/GR; SR/GR emerge as effective SDF descriptions consistent with the deployment filters:
\begin{itemize}
  \item \textbf{SR (flat, low-mass limit).} A finite invariant information speed (BL-II) enforces Lorentz kinematics; see Proposition~1 in Section~\ref{sec:formal-proofs}.
  \item \textbf{GR (delay gradients).} A delay field $T(\mathbf{x})$ induces the lapse $\phi=-c^{2}\ln(T/T_0)$, recovering Newtonian gravity and redshift in the weak field; see Proposition~2. Local horizon thermodynamics promotes this to the Einstein equations; see Proposition~3.
  \item \textbf{QM (nonrelativistic).} Structure filtering with a Fisher-information penalty yields the Schr\"odinger equation; see Proposition~4.
\end{itemize}










% =====================================================
\section{Falsifiable Predictions Beyond Standard Formulations}
\label{sec:predictions}

\subsection{Entanglement latency experiment}
Prediction: $\Delta t \sim (G M_{\text{det}}/c^{3})$ with positive slope. \textbf{Protocol:} polarization-entangled photons, co-located arms; vary $M_{\text{det}}$ near the detection stack; track correlation-peak shift/width vs.\ $M_{\text{det}}$; control electronic/thermal jitter with mass-invariant baselines.

\subsection{Gravitational-wave (GW) phase residuals}
\[
\Delta \phi(f) \;=\; \alpha_T \,\frac{d}{dt}\!\left[T_{\text{eff}}(f)\right]\;\tau_{\text{cycle}}(f), \quad \alpha_T>0,
\]
implying template-subtractable residuals not captured by GR-only waveform families.

\subsection{Emission Delay Law statistics}
Spontaneous emission shows absorber-availability dependence (GPL-constrained), implying deviations from purely local rates when absorber access is modulated.

\subsection{Lensing/interference residuals}
Geometry-independent timing/phase residuals attributable to deployment delay structure offer non-GR/QM hooks.
















\begin{table}[H]
\centering
\caption{TLM prediction summary (see \cref{sec:predictions} for narrative detail). 
“Null” denotes the GR/QM expectation absent TLM delay/filtering effects.}
\label{tab:tlm-predictions}
\vspace{.5cm}

\rotatebox{90}{%
  \resizebox{0.95\textheight}{!}{%
    \renewcommand{\arraystretch}{1.3}
    \begin{tabular}{@{}p{3cm} p{4cm} p{5cm} p{5cm}@{}}
    \toprule
    \textbf{Prediction} & \textbf{Observable / Signature} & \textbf{TLM scaling} & \textbf{Suggested setup} \\
    \midrule
    Entanglement latency &
    Coincidence peak shift/width vs.\ detector mass &
    $\Delta t \sim \kappa\, GM_{\text{det}}/c^{3}$; slope $>0$; Null: $0$ &
    Co-located polarization entanglement; vary calibrated masses near detection stack \\
    \addlinespace
    GW phase residuals &
    Template-subtracted phase residuals vs.\ $f$ or time &
    $\Delta \phi(f)=\alpha_T\,\tfrac{d}{dt}[T_{\text{eff}}(f)]\,\tau_{\text{cycle}}(f)$; Null: noise-consistent &
    LIGO/Virgo/KAGRA (CBC) or PTA residual analyses; compare to GR-only templates \\
    \addlinespace
    Emission Delay Law stats &
    Spontaneous emission timing vs.\ absorber availability &
    GPL-constrained rate; additional delay variance; Null: local Poisson rate &
    Cavity QED with tunable out-coupling / absorber access; timing histograms \\
    \addlinespace
    Lensing / interference residuals &
    Geometry-independent time-of-flight / phase residuals &
    Extra variance $\propto \mathrm{Var}[T]$ beyond path geometry; Null: path-only &
    Multi-path interferometers; modulate mass distribution near detectors and compare \\
    \bottomrule
    \end{tabular}
  }% resizebox
}% rotatebox
\end{table}



















% =====================================================
\section{Comparisons}
\subsection{TLM vs.\ Holographic Principle}
Holography (e.g.\ AdS/CFT) encodes bulk dynamics on a boundary within spacetime QFT. TLM instead renders spacetime itself from timeless CI-ARCs; its “boundary” is ontological (QP$\to$SDF). Compatible in spirit (economy) but orthogonal in mapping.

\subsection{TLM vs.\ Loop Quantum Gravity (LQG)}
LQG discretizes geometry (spin networks/foams). TLM denies fundamental spacetime: any discreteness is a deployment artifact. LQG seeks microdynamics of geometry; TLM sets rules for \emph{when/how} geometry is rendered from completed instructions.

% =====================================================
\section{Operational Q\&A Hook (Observer vs.\ Photon)}
\textbf{Q.} If light “doesn’t travel,” why does it have a speed? \\
\textbf{A.} There is an information-transfer speed in our frame (SDF)\,---\,but not a photon frame (none exists). Bridge Laws encode this: photons have $T=0$ (no delay/no proper time) in QP, while observers still measure a finite $c$.

% =====================================================
\section{Concise Summary (For Readers in a Hurry)}
\begin{enumerate}
  \item \textbf{Ontology:} CI-ARCs finalized on QP by GPL; spacetime is the SDF rendering.
  \item \textbf{Bridge Laws:} BL-I $T m=\hbar/c^{2}$ (mass induces delay); BL-II $T C_s=1$ (inverse delay–rate).
  \item \textbf{SR/GR:} Recovered as SDF projections (finite $c$, null structure, dilation from delay gradients).
  \item \textbf{Novel tests:} Entanglement latency $\Delta t\sim GM_{\text{det}}/c^{3}$; GW phase residuals; absorber-dependent emission stats; geometry-independent interference residuals.
  \item \textbf{Not restatements:} BL-I is a TLM axiom; BL-II matches SR’s causal cap—together yielding falsifiable predictions outside standard formulations.
\end{enumerate}

% =====================================================
\section*{Glossary}
\begin{description}
  \item[Quantum Platform (QP):] Timeless issuance layer of completed emission--absorption instructions.
  \item[Spacetime Deployment Frame (SDF):] Rendered observer layer where QP instructions appear sequentially.
  \item[Causal Instruction Arc (CI-ARC):] Timeless emission--absorption record authored on QP.
  \item[Generalized Pairing Law (GPL):] QP finalization rule: no record without a compatible absorber.
  \item[Bridge Laws:] Deployment filters linking QP to SDF: \emph{Mass--Delay Duality} ($T m=\hbar/c^{2}$) and \emph{Causal Speed} ($T C_{s}=1$).
  \item[Delay $T$:] Rendering delay per instruction step in SDF (experienced time).
  \item[$C_s$:] Causal deployment rate (instructions per unit observer time).
  \item[$T(\mathbf{x})$, $T_{\text{eff}}(f)$:] Spatial delay field; effective cycle-averaged delay for GWs at frequency $f$.
  \item[$\phi$ (lapse):] $-c^{2}\ln(T/T_{0})$, yields Newtonian potential in weak field.
  \item[$\chi_T,\ \alpha_T$:] Positive coefficients for delay-variance (entanglement widths) and GW phase sensitivity.
\end{description}

% =====================================================
\section*{Figures: Bridge-Law Visuals}
\begin{figure}[H]
\centering
\begin{tikzpicture}
\begin{axis}[
  width=0.8\textwidth,
  height=6cm,
  xlabel={$m$},ylabel={$T$},
  xmin=0.0,xmax=1.2,
  ymin=0.0,ymax=1.2,
  domain=0.05:1.2,
  samples=200,
  axis lines=left,
  legend style={at={(0.98,0.98)},anchor=north east,draw=none,fill=none}
]
\addplot[thick] ({x},{1/x});
\legend{$T m = \text{const}$}
\end{axis}
\end{tikzpicture}
\caption{Bridge Law I as a hyperbola: increasing $m$ increases delay per step ($1/T$ decreases). Units rescaled so $\hbar/c^{2}=1$ for illustration.}
\label{fig:hyperbola}
\end{figure}

\begin{figure}[H]
\centering
\begin{tikzpicture}
\begin{axis}[
  width=0.8\textwidth,
  height=6cm,
  xlabel={$T$},ylabel={$C_s$},
  xmin=0.0,xmax=1.2,
  ymin=0.0,ymax=6.0,
  domain=0.05:1.2,
  samples=200,
  axis lines=left,
  legend style={at={(0.98,0.98)},anchor=north east,draw=none,fill=none}
]
\addplot[thick] ({x},{1/x});
\legend{$T C_s = 1$}
\end{axis}
\end{tikzpicture}
\caption{Bridge Law II: smaller delay $T$ $\Rightarrow$ larger deployment rate $C_s$; $T\to0$ implies formal $C_s\to\infty$ on QP while SDF still enforces finite $c$.}
\label{fig:reciprocal}
\end{figure}

% =====================================================
\section*{Acknowledgments}
Thanks to readers across YouTube, TikTok, and Zenodo whose comments sharpened the articulation of these laws and their tests.

% =====================================================
\begin{thebibliography}{9}

\bibitem{einstein1905}
A.~Einstein, ``Zur Elektrodynamik bewegter Körper,'' \emph{Annalen der Physik}, 17, 891--921 (1905). \href{https://doi.org/10.1002/andp.19053221004}{doi:10.1002/andp.19053221004}.

\bibitem{mckinley_review}
J.~C.~W. McKinley, ``A Review of the Timeless Light Model: Foundations, Derivations, and Empirical Predictions,'' Zenodo (2025). \href{https://doi.org/10.5281/zenodo.16958221}{doi:10.5281/zenodo.16958221}.

\bibitem{mckinley_massless}
J.~C.~W. McKinley, ``Massless Things Do Not Experience Time,'' Zenodo (2025). \href{https://doi.org/10.5281/zenodo.17173126}{doi:10.5281/zenodo.17173126}.

\bibitem{mckinley_propertime}
J.~C.~W. McKinley, ``Photon Proper Time: The Understated Invariant of Special Relativity,'' Zenodo (2025). \href{https://doi.org/10.5281/zenodo.17190047}{doi:10.5281/zenodo.17190047}.

\bibitem{mckinley_delaylaw}
J.~C.~W. McKinley, ``The Emission Delay Law: A General Principle for the Realization of Quanta in the Timeless Light Model,'' Zenodo (2025). \href{https://doi.org/10.5281/zenodo.17032235}{doi:10.5281/zenodo.17032235}.

\bibitem{mckinley_consideration}
J.~C.~W. McKinley, ``Why the Timeless Light Model Deserves Scientific Consideration: A Foundational Framework with Derivations, Critiques, and Experimental Proposals (v1.3),'' Zenodo (2025). \href{https://doi.org/10.5281/zenodo.16724187}{doi:10.5281/zenodo.16724187}.

\end{thebibliography}





\end{document}

```

</details>

---
{% endraw %}
