---
layout: default
title: '[2025] Frame Pair Stretch and the ZeroSpace Postulate in the Timeless Light Model'
description: 'Publication metadata and archived raw LaTeX source by John C. W. McKinley.'
permalink: /papers/frame-pair-stretch-and-the-zerospace-postulate-in-the-timeless-light-model/
paper: true
---
{% raw %}
# [2025] Frame Pair Stretch and the ZeroSpace Postulate in the Timeless Light Model
*   **DOI:** [10.5281/zenodo.16777862](https://doi.org/10.5281/zenodo.16777862)
*   **Date:** 7 August 2025

<details markdown="1">
<summary><b>Click to view Raw LaTeX Source</b></summary>

```latex

\documentclass[12pt,letterpaper]{article}

% --- Packages ---
\usepackage[margin=1in]{geometry}
\usepackage[utf8]{inputenc}
\usepackage[T1]{fontenc}
\usepackage{lmodern}
\usepackage{amsmath, amssymb, amsthm}
\usepackage{graphicx}
\usepackage{tikz}
\usepackage{pgfplots}
\pgfplotsset{compat=1.18}
\usepackage{hyperref}
\hypersetup{
    colorlinks=true,
    linkcolor=blue,
    citecolor=blue,
    urlcolor=blue
}

% --- Title ---







\title{{Frame Pair Stretch and the ZeroSpace Postulate \\in the Timeless Light Model}}

\author{John C. W. McKinley \\ Independent Researcher \\ \href{https://orcid.org/0009-0005-7097-5035}{0009-0005-7097-5035}}
\date{August 7,  2025}

\begin{document}
\maketitle


\renewcommand{\thefootnote}{\fnsymbol{footnote}}
\footnotetext[1]{This version published at \href{https://doi.org/10.5281/zenodo.16777862}{doi.org/10.5281/zenodo.16777862.}}


























\begin{abstract}
In the Timeless Light Model (TLM), photons are reinterpreted as timeless instructions issued on a Quantum Platform (QP) rather than as in-spacetime particles. This paper introduces the \emph{ZeroSpace Postulate}: photons possess no ontic worldline in the Spacetime Deployment Frame (SDF) but may project observable deployment traces consistent with General Relativity (GR). By treating photons as \emph{frame-pair connectors}---timeless links between emission and absorption frames---we resolve the paradox of how a photon ``knows'' its destination over billions of years of apparent travel. We formalize the deployment map \(\Pi\), derive its optical-metric reduction, present worked examples (Shapiro delay, gravitational lensing, FLRW redshift), and propose precise observational falsifiability criteria. We connect cosmic-scale frame pair stretch to laboratory-scale ``tiny frames'' seen in high-energy accelerators, offering a unified conceptual framework with testable predictions.
\end{abstract}

\section{Introduction and Motivation}
\label{sec:intro}

In the standard General Relativity (GR) deployment frame---here called the \emph{Spacetime Deployment Frame} (SDF)---the trajectory of a photon is described as a null geodesic connecting an emission event to an absorption event~\cite{Einstein1916}. While this description is consistent with all observed phenomena, it leaves open a subtle but critical puzzle when considered in light of the \emph{Timeless Light Model} (TLM)~\cite{McKinley2025_TLM,McKinley2025_Cs}: how can a photon, which experiences zero proper time, ``know'' its eventual destination over cosmological distances and timescales?

The traditional account implicitly embeds the photon entirely \emph{in} the SDF, granting it an in-frame ontic status that accrues no proper time but is still ``present'' in the deployment layer for billions of years. This raises conceptual difficulties when integrated with a timeless instruction framework: if the photon is an instruction issued on a timeless Quantum Platform (QP), why should it have any extended in-SDF existence at all?

We propose a resolution through the \textbf{ZeroSpace Postulate}. In this view, a photonic instruction exists entirely outside the SDF in its essence---possessing no worldline substance---while still producing an \emph{observable deployment trace} in the SDF. This trace obeys all GR constraints, including null propagation and local Lorentz invariance, but is ontologically distinct from the instruction itself.

By treating the photon as a \emph{frame-pair connector} between an emission frame and an absorption frame, we circumvent the ``13.8 billion-year travel'' paradox: the photon does not \emph{traverse} the SDF in time; rather, its deployment trace is a projection of a timeless endpoint-pairing into the SDF geometry. The apparent stretching of frame pairs across expanding space---what we call \emph{frame pair stretch}---is thus a property of the deployment geometry, not a sign of in-SDF photon substance.

\paragraph{Lab-Scale Analogy: Tiny Frames in Accelerators.}
In the TLM/ZeroSpace framework, an SDF \emph{frame} is a spacetime locus carrying its own clock rate and metric relations. High-energy accelerator experiments, such as those at CERN, provide an instructive analogue: no matter how much energy is applied, a massive particle never reaches \(c\). Instead, its SDF frame becomes increasingly time-dilated relative to the lab frame, and its spatial projection stretches asymptotically toward the lightcone without ever lying upon it~\cite{Peacock1999}. 

In our language, this is a \emph{tiny frame}---a frame with such extreme dilation that, from the SDF viewpoint, it is tightly compressed against the causal boundary set by \(c\), but still distinct from a photon’s ZeroSpace projection. Just as cosmological expansion stretches the projection between emission and absorption frames for photons, accelerator physics stretches the separation between a massive particle’s instantaneous SDF frame and the massless limit it can never attain. 

This analogy highlights the frame-pair structure: for massive particles, the two ends of the frame-pair (present state and lightlike limit) never coincide; for photons, the endpoints \((\mathcal{E},\mathcal{A})\) are paired in ZeroSpace and projected into SDF already at the causal boundary.

\section{ZeroSpace Postulate and the Deployment Map}
\label{sec:zerospace}

\subsection{Postulates}
\label{subsec:postulates}
\paragraph{P0 (TLM context).}
All observable spacetime phenomena in the GR deployment layer (SDF) are delayed resolutions of timeless instructions issued on a Quantum Platform (QP). Photons are not spacetime objects; ``photon'' denotes an instruction whose proper time is undefined on QP and zero in SDF~\cite{McKinley2025_TLM}.

\paragraph{P1 (ZeroSpace).}
Each photonic instruction possesses a \emph{ZeroSpace quality}: it remains outside the SDF in its essence (no worldline, no in-frame ontic substrate) while permitting a \emph{deployment trace} to appear in SDF that satisfies GR constraints (local Lorentz invariance; null propagation).

\paragraph{P2 (Endpoints-first).}
Instructions are specified by endpoint data on QP: an emission event class \(\mathcal{E}\) and an absorption event class \(\mathcal{A}\) (possibly distributions). Endpoints are timelessly paired on QP; no retrocausality is entailed because QP lacks time.

\paragraph{P3 (Delay law).}
Deployment obeys the causal rendering law
\begin{equation}
\label{eq:delaylaw}
T \cdot C_s = 1,
\end{equation}
where \(T\) is deployment delay (SDF time-like), and \(C_s\) is the causal rate of the rendering engine (QP-side, timeless parameter). For massive systems the companion balance \(T \cdot m = 1\) describes mass-bound delay~\cite{McKinley2025_Cs}.

\subsection{Deployment Map}
\label{subsec:deployment-map}
Let \((\mathcal{M}, g_{\mu\nu})\) be the SDF spacetime. A photonic instruction \(I\) with ZeroSpace quality is projected into SDF via a \emph{deployment map}
\begin{equation}
\Pi: \; (I; \mathcal{E}, \mathcal{A}; g_{\mu\nu}) \mapsto \Gamma_I \subset \mathcal{M},
\end{equation}
where \(\Gamma_I\) is a null curve family consistent with the metric and boundary data. Concretely, \(\Gamma_I\) is any extremal of the \emph{deployment functional}
\begin{equation}
\label{eq:deployment-functional}
\mathcal{D}[\gamma; g] \;=\; \int_{\gamma} \lambda(g, x) \, d\ell,
\end{equation}
subject to \(\gamma(0)\in \mathcal{E}\) and \(\gamma(1)\in \mathcal{A}\), with \(\lambda\) chosen so that Euler--Lagrange equations enforce \(g_{\mu\nu}\dot{\gamma}^\mu \dot{\gamma}^\nu = 0\) (null) and reproduce standard GR propagation including Shapiro delay~\cite{Shapiro1964}. In stationary spacetimes, \(\mathcal{D}\) reduces to Fermat’s principle in curved space (optical metric)~\cite{Schneider1992,BlandfordNarayan1992}.

\paragraph{Lemma (Worldline appearance without worldline substance).}
Although \(I\) has no ontic worldline in QP, the image \(\Gamma_I\) is a null geodesic (or bundle) in SDF. Thus the instruction can ``travel in SDF while not being of SDF.''

\subsection{Observable Consequences}
\label{subsec:consequences}

\paragraph{(C1) Redshift without photon aging.}
Define the SDF wavevector \(k^\mu\) tangent to \(\Gamma_I\) and the emitter/absorber four-velocities \(u^\mu_{\rm em}, u^\mu_{\rm ab}\). Observed frequencies are
\begin{equation}
\omega_{\rm em} = -k_\mu u^\mu_{\rm em},\qquad
\omega_{\rm ab} = -k_\mu u^\mu_{\rm ab}.
\end{equation}
The ratio \(\omega_{\rm ab}/\omega_{\rm em}\) (cosmological, Doppler, gravitational) is entirely SDF-geometric; no photon proper-time accumulation is needed. ZeroSpace carries an immutable instruction; redshift arises from the projection \(\Pi\) acting through \(g_{\mu\nu}\) along \(\Gamma_I\)~\cite{Peacock1999}.

\paragraph{(C2) Lensing and path selection.}
Multiple extremals of \(\mathcal{D}\) yield multiple images/paths (gravitational lensing). The ZeroSpace instruction selects all admissible \(\Gamma_I\) consistent with boundary classes \((\mathcal{E},\mathcal{A})\); observed multiplicity is a property of \(\Pi\) and \(g_{\mu\nu}\), not of an in-spacetime photon substance~\cite{Schneider1992,BlandfordNarayan1992}.

\paragraph{(C3) Coherence and phase.}
Interference arises from the deployment-phase
\begin{equation}
\Phi[\gamma] \;=\; \int_{\gamma} k_\mu \, dx^\mu,
\end{equation}
a purely SDF quantity. ZeroSpace enforces endpoint coherence rules; \(\Pi\) supplies path-dependent phases, reproducing standard optics and QFT limits.

\paragraph{(C4) Causality and the speed limit.}
ZeroSpace never transmits superluminal \emph{signals} in SDF. For any two events \(p,q \in \mathcal{M}\), \(\Pi\) only yields support on null (or, for media, subluminal effective) trajectories. Hence the SDF light-cone structure is preserved though the instruction itself resides outside it.

\subsection{Schematic}
\label{subsec:schematic}
\begin{figure}[h]
\centering
\begin{tikzpicture}[scale=1.0]
  % SDF plane
  \draw[fill=gray!10, rounded corners] (-4,-1.2) rectangle (4,2.2);
  \node at (.5,-.7) {\small SDF (GR deployment layer)};
  % Emission and absorption
  \filldraw (-3,0) circle (1.5pt) node[left] {\small Emission $E$};
  \filldraw (3,1.6) circle (1.5pt) node[right] {\small Absorption $A$};
  % Null-like path
  \draw[thick] (-3,0) .. controls (-1.5,0.8) and (1.2,0.9) .. (3,1.6);
  % QP cloud
  \draw[dashed, rounded corners] (-4,2.8) rectangle (4,4.2);
  \node at (0,3.7) {\small QP (ZeroSpace: outside SDF)};
  % Instruction arrows
  \draw[->, thick, dashed] (0,2.9) -- (-2.6,0.2) node[midway,left] {\scriptsize $\Pi^\dagger$ sets endpoints};
  \draw[->, thick, dashed] (0,2.9) -- (2.6,1.3) node[near start,right] {\scriptsize $\Pi$ deploys $\Gamma_I$};
\end{tikzpicture}
\caption{ZeroSpace instruction (QP) projecting a null deployment trace \(\Gamma_I\) into SDF between endpoint classes \((\mathcal{E},\mathcal{A})\).}
\label{fig:zerospace-schematic}
\end{figure}

\section{From ZeroSpace to Fermat: The Optical-Metric Derivation}
\label{sec:optical-metric}

We now make \S\ref{subsec:deployment-map} explicit by reducing the deployment functional \(\mathcal{D}\) to Fermat’s principle in GR for the relevant spacetimes, thereby fixing the concrete form of \(\Pi\) in the SDF~\cite{Schneider1992,BlandfordNarayan1992,Peacock1999}.

\subsection{Static spacetimes: exact reduction to Fermat}
\label{subsec:static-optical}
Let the SDF be a static spacetime with line element
\begin{equation}
\label{eq:static-metric}
ds^2 \;=\; -V(\mathbf{x})^2\, dt^2 \;+\; h_{ij}(\mathbf{x})\,dx^i dx^j, \qquad \partial_t V=0, \ \partial_t h_{ij}=0,
\end{equation}
where \(V>0\) is the lapse and \(h_{ij}\) is the spatial metric on the \(t=\)const slices. For a null deployment trace \(\Gamma_I\) we have \(ds^2=0\), hence
\begin{equation}
\label{eq:null-condition-static}
0\;=\;-V^2 dt^2 + h_{ij}\,dx^i dx^j
\quad\Rightarrow\quad
dt \;=\; \frac{1}{V(\mathbf{x})}\,\sqrt{h_{ij}\,dx^i dx^j}.
\end{equation}
Integrating between endpoint classes \(\mathcal{E}\to\mathcal{A}\) along a spatial curve \(\gamma\) yields the SDF travel time
\begin{equation}
\label{eq:travel-time}
T[\gamma] \;=\; \int_{\gamma} \frac{1}{V(\mathbf{x})}\,\sqrt{h_{ij}\,dx^i dx^j}
\;=\; \int_{\gamma} n(\mathbf{x})\, d\ell_h,
\end{equation}
where \(n(\mathbf{x}) \equiv 1/V(\mathbf{x})\) and \(d\ell_h=\sqrt{h_{ij}\,dx^i dx^j}\). Thus
\begin{equation}
\label{eq:fermats-functional}
\mathcal{D}[\gamma;g] \;\equiv\; T[\gamma] \;=\; \int_\gamma n(\mathbf{x})\, d\ell_h,
\end{equation}
and its extremals obey Fermat’s principle in curved space:
\begin{equation}
\delta T[\gamma] = 0
\quad\Longleftrightarrow\quad
\gamma \ \text{is a geodesic of the optical metric}\
\tilde{h}_{ij} \equiv n(\mathbf{x})^2\, h_{ij}.
\end{equation}
Hence the ZeroSpace deployment map \(\Pi\) reduces, in static SDF sectors, to selecting spatial geodesics of \(\tilde{h}_{ij}\) with endpoint constraints. The resulting spacetime lifts are null geodesics.

\paragraph{Shapiro delay (weak field).}
For a weak, static field \(V(\mathbf{x})\simeq 1+\Phi(\mathbf{x})\) with \(|\Phi|\ll 1\), \(n(\mathbf{x})\simeq 1-\Phi\). Along a nearly straight path,
\begin{equation}
\Delta T \;\equiv\; T - T_0 \;\simeq\; -\int_\gamma \Phi(\mathbf{x})\, d\ell
\end{equation}
recovers the standard logarithmic enhancement for point-mass potentials (the Shapiro time delay)~\cite{Shapiro1964}.

\subsection{Stationary spacetimes: optical geometry with shift}
\label{subsec:stationary-optical}
For stationary spacetimes one may write
\begin{equation}
ds^2 \;=\; -V^2 (dt - \omega_i dx^i)^2 + h_{ij}\,dx^i dx^j,
\end{equation}
with time-independent \(V,\omega_i,h_{ij}\). The null condition gives a generalized Fermat functional
\begin{equation}
\label{eq:stationary-fermats}
T[\gamma] \;=\; \int_\gamma \Big[ \omega_i(\mathbf{x})\,\dot{x}^i \;+\; n(\mathbf{x})\,\sqrt{h_{ij}\,\dot{x}^i \dot{x}^j}\Big] d\lambda,
\end{equation}
whose extremals reproduce the correct SDF null geodesics including gravitomagnetic effects. Again, \(\Pi\) extremizes \(T[\gamma]\) under endpoint constraints.

\subsection{Cosmology (FLRW): scale-factor optics}
\label{subsec:flrw-optics}
For spatially flat FLRW,
\begin{equation}
ds^2=-dt^2 + a(t)^2\,\delta_{ij}dx^i dx^j,
\end{equation}
null curves satisfy \(dt = a(t)\,|d\mathbf{x}|\). The deployment time between emission \(t_{\rm em}\) and absorption \(t_{\rm ab}\) is
\begin{equation}
T[\gamma]=\int_{t_{\rm em}}^{t_{\rm ab}} dt = \int_\gamma a(t)\,|d\mathbf{x}|,
\end{equation}
i.e., Fermat with an \emph{effective} index \(n_{\rm FLRW}(t)=a(t)\) acting on comoving space. Redshift then follows purely from SDF expansion, with no photon aging in ZeroSpace (see Appendix~\ref{app:redshift}).

\section{Geometric-Optics Map and the Null Constraint}
\label{sec:eikonal}
In the geometric-optics limit, the field takes the form \(\Psi = A\,e^{i S/\epsilon}\), \(k_\mu\equiv \nabla_\mu S\). The eikonal equation
\begin{equation}
\label{eq:eikonal}
g^{\mu\nu}k_\mu k_\nu = 0
\end{equation}
encodes the null constraint of \(\Gamma_I\). Rays are integral curves of \(k^\mu\), and their projections extremize the Fermat functionals above. The ZeroSpace instruction fixes endpoint classes and coherence conditions; \(\Pi\) supplies the SDF phase accumulation
\begin{equation}
\Phi[\gamma] \;=\; \int_\gamma k_\mu dx^\mu,
\end{equation}
governing interference and lensing multiplicities.

\section{Worked Examples of the Deployment Functional}
\label{sec:worked-examples}

\subsection{Shapiro Delay in a Weak, Static Schwarzschild Field}
\label{subsec:shapiro}
Consider a point mass \(M\) with Schwarzschild radius \(r_s=2GM\) and an asymptotically flat, static region. In isotropic weak field \(V(\mathbf{x}) \simeq 1+\Phi(\mathbf{x})\), \(\Phi(\mathbf{x})=-GM/r\). The optical index is \(n(\mathbf{x})=1/V \simeq 1-\Phi \simeq 1+GM/r\). For an unperturbed straight path with impact parameter \(b\), the excess travel time is
\begin{equation}
\Delta T_{\rm Shapiro}
\simeq \int_{-\infty}^{\infty}\!\Big[n(\mathbf{x})-1\Big]\, d\ell
\;=\; \int_{-\infty}^{\infty}\!\frac{GM}{\sqrt{b^2+z^2}}\,dz
\;=\; 2GM \ln\!\left(\frac{4 z_{\rm max}}{b}\right),
\end{equation}
where \(z\) is the coordinate along the asymptotic line of sight and \(z_{\rm max}\) regulates the logarithm (cancels in relative delays). Between two endpoints at radii \(r_{\rm em}\) and \(r_{\rm ab}\) with closest approach \(b\), the standard form is
\begin{equation}
\Delta T_{\rm Shapiro}
= 2GM \ln\!\left(\frac{r_{\rm em}+r_{\rm ab}+D}{r_{\rm em}+r_{\rm ab}-D}\right),
\qquad
D \equiv \sqrt{(r_{\rm em}+r_{\rm ab})^2 - b^2},
\end{equation}
matching GR to leading post-Newtonian order~\cite{Shapiro1964}. In TLM, this delay is \(\Delta T = \delta \mathcal{D}\) from \(\Pi\) and does not imply photon aging in ZeroSpace.

\subsection{Thin-Lens Time-Delay Surface and Fermat Potential}
\label{subsec:thin-lens}
Let \(D_d, D_s, D_{ds}\) be angular-diameter distances to lens, to source, and lens-to-source (SDF geometry). In the thin-lens limit, the arrival-time functional (Fermat surface) for image angle \(\boldsymbol{\theta}\) and source angle \(\boldsymbol{\beta}\) is~\cite{Schneider1992,BlandfordNarayan1992}
\begin{equation}
\tau(\boldsymbol{\theta}) \;=\;
\frac{D_d D_s}{2 D_{ds}}\; \big|\boldsymbol{\theta}-\boldsymbol{\beta}\big|^2
\;-\; \psi(\boldsymbol{\theta}),
\qquad
\psi(\boldsymbol{\theta}) \equiv \frac{D_d D_s}{D_{ds}}\,\hat{\psi}(\boldsymbol{\theta}),
\end{equation}
where \(\hat{\psi}\) is the scaled 2D lens potential (\(\nabla_{\!\theta}^2 \psi = 2\kappa\), with convergence \(\kappa\)). Stationary points satisfy
\begin{equation}
\nabla_{\!\theta}\tau(\boldsymbol{\theta}) = 0
\quad\Longleftrightarrow\quad
\boldsymbol{\beta} = \boldsymbol{\theta} - \nabla_{\!\theta}\psi(\boldsymbol{\theta})
\end{equation}
(the lens equation). Relative delays between images \(i,j\) are
\begin{equation}
\Delta t_{ij} \;=\; \frac{1+z_d}{c}\,\Big[\,\tau(\boldsymbol{\theta}_i)-\tau(\boldsymbol{\theta}_j)\,\Big],
\end{equation}
with \(z_d\) the lens redshift (set \(c=1\) in natural units). In TLM, multiplicity and \(\Delta t\) arise from multiple extremals of \(\mathcal{D}\) selected by endpoint classes \((\mathcal{E},\mathcal{A})\).

\subsection{FLRW Example: Comoving Distance and Cosmological Redshift}
\label{subsec:flrw-ex}
In spatially flat FLRW, \(ds^2=-dt^2+a(t)^2 d\mathbf{x}^2\). For a null ray, \(dt = a(t)\,|d\mathbf{x}|\). The comoving distance to redshift \(z\) is
\begin{equation}
\chi(z) \;=\; \int_{t(z)}^{t_0}\frac{dt}{a(t)}
\;=\; \int_{0}^{z}\frac{dz'}{H(z')},
\qquad
H(z) \equiv \frac{\dot{a}}{a}.
\end{equation}
Angular-diameter and luminosity distances follow:
\begin{equation}
D_A(z)=\frac{\chi(z)}{1+z}, \qquad D_L(z)=(1+z)\,\chi(z).
\end{equation}
Observed frequency scales as \(\omega \propto a^{-1}\), i.e.
\begin{equation}
1+z=\frac{a(t_0)}{a(t_{\rm em})},
\end{equation}
a pure property of the SDF deployment through \(\Pi\); the ZeroSpace instruction does not age~\cite{Peacock1999}.

\subsection{Phase Difference for Two Admissible Deployments}
\label{subsec:phase-two-paths}
For two admissible deployment traces \(\gamma_1,\gamma_2\) connecting the same endpoint classes, the SDF phase gap is
\begin{equation}
\Delta \Phi
=\int_{\gamma_2} k_\mu dx^\mu - \int_{\gamma_1} k_\mu dx^\mu
=\omega\,\Delta T \;-\; \int_{\gamma_2-\gamma_1}\!\!\!\mathbf{k}\cdot d\mathbf{x},
\end{equation}
which, in the stationary thin-lens limit, reduces to \(\Delta \Phi \propto \tau(\boldsymbol{\theta}_2)-\tau(\boldsymbol{\theta}_1)\). Interference thus probes \(\mathcal{D}\) directly (e.g., fringes in strongly lensed quasars).

\section{Geodesics of the Optical Metric}
\label{sec:tikz-optical}


\begin{figure}[h]
\centering
\begin{tikzpicture}[scale=1.05]
  % Background SDF panel
  \draw[fill=gray!8, rounded corners] (-4.5,-2.3) rectangle (4.5,2.6);
  \node at (.7,2.2) {\small SDF (optical geometry view)};

  % Lens mass
  \shade[ball color=black!60] (0,0) circle (0.25);
  \node[below right] at (0.28,-0.05) {\scriptsize Lens \(M\)};

  % Equipotential / index contours (n=1+GM/r stylized)
  \foreach \r in {0.7,1.1,1.6,2.2,3.0}{
    \draw[gray!50] (0,0) circle (\r);
  }
  \node[gray!60] at (2.3,-1.8) {\scriptsize \(n(\mathbf{x})=1+\frac{GM}{r}\) (schematic)};

  % Two optical geodesics (bent rays) from emitter to absorber
  \fill (-4,-1.2) circle (1.2pt) node[left] {\small Emitter \(\mathcal{E}\)};
  \fill (4,1.8) circle (1.2pt) node[right] {\small Absorber \(\mathcal{A}\)};

  \draw[thick] (-4,-1.2) .. controls (-1.8,-0.6) and (1.2,0.2) .. (4,1.8);
  \draw[thick] (-4,-1.2) .. controls (-2.2,0.4) and (0.9,0.9) .. (4,1.8);

  % Time-delay annotation
  \draw[->] (1.5,0.6) -- (2.6,1.3);
  \node at (2.0,1.6) {\scriptsize different \(\tau(\boldsymbol{\theta})\)};

  % QP / ZeroSpace box floating above
  \draw[dashed, rounded corners] (-2.8,3.4) rectangle (2.8,4.6);
  \node at (0,4.35) {\small QP (ZeroSpace)};
  \draw[->, dashed] (0,3.4) -- (-3.2,-1.1) node[midway, left] {\scriptsize set endpoints};
  \draw[->, dashed] (0,3.4) -- (3.2,1.7) node[near start, right] {\scriptsize deploy \(\Gamma_I\)};
\end{tikzpicture}
\caption{Optical-metric picture: rays are geodesics of \(\tilde{h}_{ij}=n^2 h_{ij}\). Multiple stationary paths between \(\mathcal{E}\) and \(\mathcal{A}\) yield lensing and relative delays. ZeroSpace sets endpoints; \(\Pi\) deploys SDF traces.}
\label{fig:optical-metric-fig}
\end{figure}

\section{Observational Tie-Ins and Falsifiability}
\label{sec:obs-tieins}

\subsection{Strong-Lens Time-Delay Cosmography}
\label{subsec:tdc}
For lensed quasars/SNe with image angles \(\{\boldsymbol{\theta}_i\}\), measured delays \(\Delta t_{ij}\) estimate the Fermat-surface gaps
\begin{equation}
\Delta t_{ij}^{\rm obs} \;=\; \frac{1+z_d}{c}\,\Big[\tau(\boldsymbol{\theta}_i)-\tau(\boldsymbol{\theta}_j)\Big] \;+\; \delta t_{ij}^{\rm sys}.
\end{equation}
\textbf{TLM/ZeroSpace test:} residuals about an optical-metric model should be explained by SDF geometry alone. Parameterize any geometry-independent step as
\begin{equation}
\Delta \Phi_{ij}^{\rm res} \;=\; \alpha_\star \, N_{ij}, \qquad \alpha_\star \in \mathbb{R}, \ N_{ij}\in\mathbb{Z},
\end{equation}
with \(\alpha_\star=0\) under pure \(\Pi\). Joint fits over lenses bound \(|\alpha_\star|\) (phase-step residual); a nonzero, frequency-independent \(\alpha_\star\) indicates extra deployment structure beyond \(\mathcal{D}[\gamma;g]\)~\cite{Schneider1992,BlandfordNarayan1992}.

\subsection{Solar-System and Pulsar Shapiro Stacks}
\label{subsec:pulsar-shapiro}
Two clean regimes probe \(\Delta T=\delta\mathcal{D}\) directly:
\begin{enumerate}
\item \textbf{Solar-system radar/spacecraft links} during superior conjunction: measure \(\Delta T_{\rm Shapiro}\) vs.\ impact parameter \(b\) and compare to the post-Newtonian \(\ln(4r/b)\) law~\cite{Shapiro1964}.
\item \textbf{Binary pulsars \& PTA lines of sight} grazing massive bodies: stack excess arrival times as a function of closest approach.
\end{enumerate}
\textbf{TLM/ZeroSpace expectation:} residuals scale purely with SDF potential; ZeroSpace contributes no additional time-of-flight beyond \(\mathcal{D}\). Any repeatable, potential-independent offset \(\Delta T_\star\) falsifies \(\alpha_\star=0\).

\subsection{FLRW Expansion: SN, BAO, and Strong-Lens Delays}
\label{subsec:flrw-obs}
Cosmological redshift and timing are encoded in SDF via
\begin{equation}
1+z=\frac{a(t_0)}{a(t_{\rm em})}, \qquad D_A=\frac{\chi(z)}{1+z}, \qquad D_L=(1+z)\chi(z).
\end{equation}
\textbf{TLM/ZeroSpace test:} any evidence that photon \emph{aging} affects flux dilution or spectral drift (beyond SDF \(a(t)\)) would violate ZeroSpace. Cross-check time-delay distances from strong lenses with SN/BAO-inferred distances; look for a geometry-independent phase/time offset~\cite{Peacock1999,Schneider1992,BlandfordNarayan1992}.

\subsection{FRB and Multiband Arrival Comparisons}
\label{subsec:frb-mm}
Fast radio bursts (FRBs) provide broadband arrival curves. After subtracting plasma dispersion (\(\propto \nu^{-2}\)), the gravitational (metric) part is achromatic.
\textbf{TLM/ZeroSpace test:} stack residuals across frequencies; achromatic, \emph{constant} offsets \(\Delta T_\star\) correlated only with endpoint classes would challenge \(\Pi\)-only deployment.

\subsection{Multimessenger Phase Lags (GW--EM)}
\label{subsec:gw-em}
For events with GW and EM counterparts, define
\begin{equation}
\Delta t_{\rm GW-EM} \equiv t_{\rm EM}-t_{\rm GW} \;=\; \big[\mathcal{D}_{\rm EM}-\mathcal{D}_{\rm GW}\big]/c \;+\; \delta t_{\rm src}.
\end{equation}
\textbf{TLM/ZeroSpace prediction:} modulo source physics \(\delta t_{\rm src}\), the difference is fully geometric (different effective indices/paths); no extra ZeroSpace latency. Consistent bounds across multiple events constrain any universal offset.

\subsection{Polarization Endpoint-Selection Tests}
\label{subsec:polarization}
Endpoint-class rules in ZeroSpace imply that analyzer settings restrict admissible \(\Gamma_I\). In delayed-choice/which-way variants, standard visibility relations must be recovered solely via SDF phase \(\Phi[\gamma]\) and endpoint constraints---no in-spacetime collapse dynamics. Deviations in fringe visibility not attributable to \(k^\mu\) transport would falsify the map \(\Pi\).

\subsection{Summary: Two Knobs to Constrain}
\label{subsec:knobs}
\begin{align}
\alpha_\star &: \ \text{geometry-independent \emph{phase-step} residual (should be }0\text{)};\\
\Delta T_\star &: \ \text{geometry-independent \emph{time-step} residual (should be }0\text{)}.
\end{align}
Both are predicted zero in pure ZeroSpace+\(\Pi\). Global, multi-domain fits (lensing, Shapiro, FRB, GW--EM) should yield \(|\alpha_\star|,|\Delta T_\star| \to 0\) within uncertainties; persistent nonzero values falsify the current deployment postulate or identify missing SDF terms.

\section{Conclusion: Frame Pair Stretch in ZeroSpace}
\label{sec:conclusion}

The ZeroSpace model reframes the photon not as an in-SDF traveler, but as a timeless connection between two SDF frames---one at emission, one at absorption---whose deployment trace is fully determined by SDF geometry and the endpoint constraints set in the QP. 

Under this view:
\begin{itemize}
\item \textbf{Frame pairs are primary.} The emission frame and the absorption frame are timelessly paired on the QP; the SDF expansion, curvature, and potentials dictate how these frames are \emph{projected apart} in the deployment layer.
\item \textbf{Stretch is geometric, not ontic.} What appears as the gradual ``stretching'' of separation between frames over cosmic time is a change in their SDF projection, not any change to the ZeroSpace connection itself.
\item \textbf{Delays are rendered, not traversed.} All observable delays---cosmological redshift, Shapiro delay, lensing time-lags---are properties of the deployment map \(\Pi\) acting through SDF geometry. No proper-time elapses for the instruction.
\item \textbf{Causality is preserved.} Although the instruction exists outside SDF lightcones, its projection \(\Gamma_I\) never violates the causal structure of the deployment layer.
\end{itemize}

The resulting picture preserves every tested prediction of GR while supplying a causal-ontological framework consistent with a timeless instruction platform. It also yields a concrete falsifiability program: any repeatable, geometry-independent phase- or time-step residual (\(\alpha_\star\) or \(\Delta T_\star\)) across domains---strong lensing, Shapiro delay, FRB dispersion-subtracted arrival times, GW--EM phase lags---would falsify the current postulate. If confirmed, the ZeroSpace + frame pair stretch model offers a way to unify the null-geodesic phenomenology of GR with a deeper, timeless substrate for causation~\cite{McKinley2025_TLM,McKinley2025_Cs}.

%====================================================
\appendix
\section{Rigorous Derivations}
\label{app:rigorous}

\subsection{Derivation of the Optical-Metric Fermat Principle}
\label{app:optical-fermats}
Start with a static SDF metric:
\[
ds^2 = -V(\mathbf{x})^2\, dt^2 + h_{ij}(\mathbf{x})\,dx^i dx^j
\]
For a null path, \(ds^2=0\) implies:
\[
V(\mathbf{x})^2 dt^2 = h_{ij} dx^i dx^j
\]
Taking \(t\) increasing along the ray:
\[
dt = \frac{\sqrt{h_{ij}dx^i dx^j}}{V(\mathbf{x})} \equiv n(\mathbf{x})\,d\ell_h
\]
Integrating between endpoints gives:
\[
T[\gamma] = \int_\gamma n(\mathbf{x})\, d\ell_h
\]
This is Fermat’s principle with \(n(\mathbf{x})\) as the refractive index and \(\tilde{h}_{ij} = n^2 h_{ij}\) as the optical metric. Extremals of \(T[\gamma]\) in \(\tilde{h}_{ij}\) are spatial geodesics whose spacetime lifts are null geodesics.

\subsection{Redshift Without Photon Aging}
\label{app:redshift}
Let \(k^\mu\) be the null wavevector and \(u^\mu\) the observer 4-velocity. Measured frequency is:
\[
\omega = -k_\mu u^\mu
\]
In a stationary spacetime with timelike Killing vector \(\xi^\mu\):
\[
E = -k_\mu \xi^\mu \quad\text{is conserved}
\]
For static observers \(u^\mu = \xi^\mu / \|\xi\| = \xi^\mu / V\), we have:
\[
\omega = \frac{E}{V(\mathbf{x})}
\]
Thus:
\[
\frac{\omega_{\rm ab}}{\omega_{\rm em}} = \frac{V(\mathbf{x}_{\rm em})}{V(\mathbf{x}_{\rm ab})}
\]
No proper-time accrual is needed; the ratio is purely geometric.

\subsection{Shapiro Delay from Optical Index}
In weak field \(V\simeq 1+\Phi\), \(n\simeq 1-\Phi\). For a point mass \(\Phi=-GM/r\) and straight path with impact \(b\):
\[
\Delta T_{\rm Shapiro} \simeq \int_{-\infty}^{\infty} \frac{GM}{\sqrt{b^2+z^2}}\, dz = 2GM \ln\!\left(\frac{4z_{\rm max}}{b}\right)
\]
Matching the post-Newtonian result to leading order~\cite{Shapiro1964}.

\subsection{Thin-Lens Fermat Surface}
For lens-plane coordinates \(\boldsymbol{\theta}\), source position \(\boldsymbol{\beta}\):
\[
\tau(\boldsymbol{\theta}) = \frac{D_d D_s}{2 D_{ds}}|\boldsymbol{\theta}-\boldsymbol{\beta}|^2 - \psi(\boldsymbol{\theta})
\]
Stationary points satisfy the lens equation:
\[
\boldsymbol{\beta} = \boldsymbol{\theta} - \nabla_{\!\theta} \psi
\]
Relative delays:
\[
\Delta t_{ij} = \frac{1+z_d}{c}\big[\tau(\boldsymbol{\theta}_i)-\tau(\boldsymbol{\theta}_j)\big]
\]

\subsection{Phase Differences for Multiple Paths}
In geometric optics:
\[
\Phi[\gamma] = \int_\gamma k_\mu dx^\mu
\]
For two admissible paths \(\gamma_1,\gamma_2\):
\[
\Delta \Phi = \Phi[\gamma_2] - \Phi[\gamma_1]
\]
Interference intensity \(I \propto |e^{i\Phi_1}+e^{i\Phi_2}|^2\) depends only on SDF geometry and endpoints.

%====================================================
\section*{Glossary of Terms and Symbols}
\addcontentsline{toc}{section}{Glossary}
\begin{description}
\item[SDF (Spacetime Deployment Frame)] The GR manifold \((\mathcal{M},g_{\mu\nu})\) in which all observable phenomena are deployed. SDF geometry determines apparent delays, redshift, and curvature effects.
\item[QP (Quantum Platform)] Ontologically senior layer in TLM, existing outside spacetime. Issues timeless instructions (e.g., photon endpoint pairings) that are later rendered into the SDF.
\item[ZeroSpace] The property of an instruction to remain entirely outside the SDF in its essence, while permitting an SDF-compliant projection (\(\Gamma_I\)) consistent with GR null propagation.
\item[Frame Pair Stretch] Apparent increase in SDF separation between emission and absorption frames over cosmic expansion, even though the underlying ZeroSpace connection is unchanging.
\item[$\mathcal{E},\mathcal{A}$] Emission and absorption endpoint classes, defined on QP; paired timelessly before any SDF deployment.
\item[$\Pi$] Deployment map from QP endpoint data and SDF geometry to an SDF null-geodesic trace \(\Gamma_I\).
\item[$\Gamma_I$] Null curve (or bundle) in SDF representing the projection of a ZeroSpace instruction.
\item[$g_{\mu\nu}$] Metric tensor of the SDF.
\item[$T$] Deployment delay in the SDF; the observable interval between emission and absorption events.
\item[$C_s$] Causal rendering rate in TLM; satisfies \(T\cdot C_s = 1\) for photons/instructions.
\item[$m$] Mass in TLM; satisfies \(T\cdot m = 1\) for massive systems.
\item[$n(\mathbf{x})$] Optical index in a static SDF sector; \(n=1/V\) where \(V\) is the lapse function.
\item[$\tilde{h}_{ij}$] Optical metric: \(\tilde{h}_{ij}=n^2 h_{ij}\), where \(h_{ij}\) is the spatial metric.
\item[$k^\mu$] Null wavevector along \(\Gamma_I\).
item[\(\Phi[\gamma]\)] Phase accumulated along SDF path \(\gamma\).
\item[$\alpha_\star$] Geometry-independent phase-step residual, predicted \(=0\) in pure ZeroSpace+\(\Pi\).
\item[$\Delta T_\star$] Geometry-independent time-step residual, predicted \(=0\) in pure ZeroSpace+\(\Pi\).
\end{description}

%====================================================
\begin{thebibliography}{99}

\bibitem{Einstein1916}
A.~Einstein, ``Die Grundlage der allgemeinen Relativitätstheorie,'' \emph{Annalen der Physik}, vol.~49, pp.~769--822, 1916.

\bibitem{Shapiro1964}
I.~I.~Shapiro, ``Fourth Test of General Relativity,'' \emph{Phys.\ Rev.\ Lett.}, vol.~13, no.~26, pp.~789--791, 1964.

\bibitem{Schneider1992}
P.~Schneider, J.~Ehlers, E.~E.~Falco, \emph{Gravitational Lenses}. Springer-Verlag, 1992.

\bibitem{BlandfordNarayan1992}
R.~D.~Blandford, R.~Narayan, ``Cosmological applications of gravitational lensing,'' \emph{Ann.\ Rev.\ Astron.\ Astrophys.}, vol.~30, pp.~311--358, 1992.

\bibitem{Peacock1999}
J.~A.~Peacock, \emph{Cosmological Physics}. Cambridge University Press, 1999.

\bibitem{McKinley2025_TLM}
J.~C.~W.~McKinley, ``Resolving Wave-Particle Duality Through the Proposed Timeless Light Model: Photons as Timeless Instructions and Waves as Deployed Delay,'' Zenodo, DOI:\href{https://doi.org/10.5281/zenodo.16510862}{doi.org/10.5281/zenodo.16510862}, 2025.


\bibitem{McKinley2025_Cs}
J.~C.~W.~McKinley, ``Clarifying $C_s$: Deployment Rate, Delay, and Simulation Parameters in the Timeless Light Model,'' Zenodo, DOI:\href{https://doi.org/10.5281/zenodo.15817350}{doi.org/10.5281/zenodo.15817350}, 2025.

\end{thebibliography}

\end{document}




```

</details>







---
{% endraw %}
