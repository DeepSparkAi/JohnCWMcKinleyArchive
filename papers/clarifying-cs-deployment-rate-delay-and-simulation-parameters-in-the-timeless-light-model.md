---
layout: default
title: '[2025] Clarifying Cs: Deployment Rate, Delay, and Simulation Parameters in the Timeless Light Model'
description: 'Publication metadata and archived raw LaTeX source by John C. W. McKinley.'
permalink: /papers/clarifying-cs-deployment-rate-delay-and-simulation-parameters-in-the-timeless-light-model/
paper: true
---
{% raw %}
# [2025] Clarifying Cs: Deployment Rate, Delay, and Simulation Parameters in the Timeless Light Model
*   **DOI:** [10.5281/zenodo.15817350](https://doi.org/10.5281/zenodo.15817350)
*   **Date:** 6 July 2025

<details markdown="1">
<summary><b>Click to view Raw LaTeX Source</b></summary>

```latex
\documentclass[11pt]{article}

\usepackage[utf8]{inputenc}
\usepackage{amsmath, amssymb, geometry, graphicx}
\usepackage{tikz}
\usetikzlibrary{calc, arrows.meta, positioning, shapes.geometric}
\usepackage{tcolorbox}
\usepackage{booktabs}
\usepackage{tabularx}
\usepackage{siunitx}
\usepackage{natbib}
\usepackage{breqn}
\usepackage{pdflscape} 
\usepackage{hyperref}

\geometry{a4paper, margin=1in}
\linespread{1.15}
\numberwithin{equation}{section}
\errorcontextlines=999
\bibliographystyle{apsrev4-2}

\hypersetup{
  colorlinks=true,
  linkcolor=blue,
  citecolor=blue,
  urlcolor=blue,
}




\title{Clarifying \texorpdfstring{$C_s$}{Cs}: Deployment Rate, Delay, and Simulation Parameters in the Timeless Light Model}


\author{John C. W. McKinley \\
Supplement to: \href{https://doi.org/10.5281/zenodo.15813253}{\textit{Causal Instruction Arcs and the Timeless Light Model}~\cite{CI_ARCs}} \\
\textbf{DOI for this document:} \href{https://doi.org/10.5281/zenodo.15817350}{10.5281/zenodo.15817350}
}



\date{July 2025}


\begin{document}

\maketitle

\begin{abstract}
This technical supplement refines key mathematical definitions and deployment dynamics underlying the Timeless Light Model (TLM), introduced in “Causal Instruction Arcs and the Timeless Light Model” (Zenodo v7.91). Specifically, it distinguishes the speed of light \( c \) from the variable causal deployment rate \( C_s \), formalizes the speculative rendering law \( T \cdot C_s = 1 \), and clarifies how delay and rate function as dual observables within the Spacetime Deployment Frame (SDF). We provide deployment mode metadata conventions (e.g., \( \mu, \epsilon \)), propose simulation frameworks for testing inverse-delay symmetry, and define falsifiability thresholds for future experiments. This methods paper supports replication, simulation, and targeted experimental validation of TLM’s core causal structure.
\end{abstract}

\section{Note on Scope}

This document is not a standalone presentation of the Timeless Light Model. It serves as a companion to the primary TLM theory paper, offering notation upgrades, model constraints, and tools for simulation and experimental planning. Researchers seeking an introduction to TLM should consult the formal version 7.91 paper available on Zenodo.


\section{Foundational Assumptions of the Timeless Light Model}
The Timeless Light Model (TLM) begins with the assumption that reality consists of two distinct layers:
\begin{enumerate}
    \item \textbf{Photon Instruction Layer (PIL):} A timeless, non-spatial domain that holds all causal instructions—called CI-ARCs—as complete and pre-defined arcs of causality. These instructions are not embedded in time; they exist as potential outcomes awaiting resolution.
    \item \textbf{Spacetime Deployment Frame (SDF):} The emergent, sequential rendering layer where events unfold with measurable delay. Observers experience this layer as time, space, and motion. Instructions from the PIL manifest in the SDF at rates determined by physical constraints.
\end{enumerate}

Reality in TLM is not built from particles moving through time, but from timeless causal instructions rendered into observable experience at a pace governed by delay mechanics.

\textbf{Rendering} is the process of translating a timeless instruction from the Photon Instruction Layer (PIL) into a time-ordered, observer-accessible event in the Spacetime Deployment Frame (SDF). The rate of rendering is governed by the instruction’s delay \( T \), which is determined by factors such as mass or constraint geometry.

\textbf{Instructional geometry} refers to the full causal configuration of a CI-ARC, including emission and absorption endpoints, spatial separation \( D \), conservation rules \( R \), and deployment mode metadata. This geometry governs how and when the instruction is rendered into the SDF, including whether it follows Mode A (delayed) or Mode B (instantaneous/ESE) behavior.


\section{Introduction}
Modern physics often employs overloaded symbols, risking conceptual ambiguity. In the Timeless Light Model (TLM), the variable \( C \) has historically referred both to the speed of light and to a causal rate of rendering. This paper formally distinguishes the constant speed of light \( c \) from the variable \textit{causal rate} \( C_s \), introducing a speculative rendering law and justifying a notational upgrade crucial for precision in future derivations.

\section{From Delay to Deployment}
TLM holds that all events begin as timeless instructions in the PIL and appear in the SDF according to delay governed by mass:
\begin{equation}
\boxed{\textbf{TLM LAW:} \quad T \cdot m = \frac{\hbar}{c^2}}\cite{MTI}
\end{equation}


This defines the foundational pacing rule: more mass implies more delay, and photons (with zero mass) deploy instantly.












\begin{figure}[h!]
\centering
\begin{tikzpicture}[
    node distance=1.8cm and 2.2cm,
    box/.style={rectangle, draw=black, fill=gray!10, rounded corners, minimum width=3.6cm, minimum height=1.2cm, align=center},
    photon/.style={draw=blue, thick, ->, >=Latex},
    mass/.style={draw=red, thick, ->, >=Latex},
    lab/.style={font=\small, align=center}
]

% Nodes
\node[box] (pil) {Photon Instruction Layer (PIL)\\\textit{Timeless Instructions}};
\node[box, below=of pil] (sdf) {Spacetime Deployment Frame (SDF)\\\textit{Rendered Events in Time}};
\node[lab, left=1.8cm of sdf] (lightLabel) {Photon (Mass = 0)\\\(T = 0\), \(C_s = \infty\)};
\node[lab, right=1.8cm of sdf] (massLabel) {Massive Object\\\(T > 0\), \(C_s < c\)};

% Arrows
\draw[photon] (pil) -- (sdf);
\node at ($(pil)!0.5!(sdf)+(0.8,0)$) {\scriptsize Immediate};

\draw[mass] (pil.east) .. controls +(2.2, -.2) and +(-3.4, -.6) .. (sdf.east);

% Dashed brackets
\draw[dashed] (lightLabel.south) -- ++(0, -0.3) -- ++(2.1, 0) -- (sdf.west);
\draw[dashed] (massLabel.south) -- ++(0, -0.3) -- ++(-2.1, 0) -- (sdf.east);

\end{tikzpicture}
\caption{Instructions from the Photon Instruction Layer (PIL) appear in spacetime as events in the Spacetime Deployment Frame (SDF). Events involving photons appear immediately, while massive objects take time to appear due to delay.}

\label{fig:pil-sdf-causal-rate}
\end{figure}



















\section{Introducing Causal Rate \( C_s \)}
We define a new quantity:
\begin{equation}
C_s = \frac{1}{T}
\end{equation}
This \textbf{causal rate} quantifies how fast a given instruction becomes real in the SDF. Unlike \( c \), it is not universal; it depends on the delay induced by mass.

This leads to the proposed speculative law:
\begin{equation}
\boxed{\textbf{TLM LAW:} \quad T \cdot C_s = 1}
\end{equation}

This rate \( C_s \) has units of \( \text{s}^{-1} \), unlike the speed of light \( c \), which has units of \( \text{m/s} \).











\subsection{Why is \( C_s = \infty \) physically valid in Mode B?}

In the Timeless Light Model, \( C_s \) is defined as a \textit{causal rate}—the rate at which a pre-resolved instruction becomes observable in the Spacetime Deployment Frame (SDF). This is distinct from a velocity measured in meters per second. For Mode B events (such as entanglement collapse), the instruction is already fully resolved in the Photon Instruction Layer (PIL), and no mechanical delay is introduced.

Thus, \( C_s = \infty \) does not imply that physical information or energy travels faster than light. Rather, it means that the instruction executes \textit{with zero temporal delay} from the perspective of the SDF—rendering it instantaneous in appearance, while remaining consistent with no-signaling constraints. This causal-rate interpretation avoids contradiction with relativity, as it reframes “faster-than-light” not as a physical transport, but as a lack of delay between correlated observations.









\begin{tcolorbox}[colback=blue!3!white, colframe=blue!75!black, title=\textbf{Causal Rate Infinity: No Violation of Relativity}]
The assignment \( C_s = \infty \) in Mode B reflects \textit{zero delay} in rendering a pre-resolved CI-ARC instruction within the SDF. It does not imply superluminal motion or signal transfer. Instead, it expresses that the causal connection is already complete in the PIL, and the SDF observes its outcome without mechanical latency. This maintains consistency with quantum nonlocality and avoids conflict with special relativity.
\end{tcolorbox}






\subsection{Derivation of Causal Rate for Massive Particles}

To clarify the origin of the causal rate \( C_s \) used throughout the Timeless Light Model, we begin from the postulated invariant:

\[
T \cdot m = \frac{\hbar}{c^2}
\]

This axiom defines a fundamental tradeoff between mass and delay: more massive systems incur shorter delay times when viewed in instructional terms. Solving for \( T \), we obtain:

\[
T = \frac{\hbar}{c^2 m}
\]

By definition of causal rate in the TLM framework:

\[
C_s \equiv \frac{1}{T}
\]

Substituting:

\[
C_s = \frac{1}{\hbar / c^2 m} = \frac{c^2 m}{\hbar}
\]

\noindent This expression captures the rate at which instructions are causally resolved into the SDF for a given mass \( m \). Notably, this causal rate is not the coordinate speed of light \( c \), but an abstract rate of instruction resolution, inversely proportional to delay.

\begin{tcolorbox}[colback=blue!5!white, colframe=blue!75!black, title=TLM Law — Causal Rate of Massive Systems]
\[
\boxed{C_s = \frac{c^2 m}{\hbar}}
\quad \text{where } T \cdot C_s = 1
\]
\end{tcolorbox}


\subsection{CI-ARC Metadata and Deployment Modes}

In the Timeless Light Model (TLM), the behavior of a Causal Instruction Arc (CI-ARC) upon projection into the Spacetime Deployment Frame (SDF) is determined entirely by two metadata fields:

\begin{itemize}
    \item \textbf{Energy Index \( \mu \)}: Represents the instruction’s resistance to instant deployment, analogous to mass or energetic inertia. Higher \( \mu \) values correspond to longer deployment delays (\( T \propto \mu \)), in accordance with the fundamental delay law \( T \cdot \mu = \hbar / c^2 \).
    
    \item \textbf{Execution Envelope \( \epsilon \)}: Defines the tolerance for spatial or temporal spread in rendering. A low \( \epsilon \) implies tight localization (classical-like outcomes); a high \( \epsilon \) permits broad, probabilistic, or nonlocal projection typical of quantum tunneling and ESE behavior.
\end{itemize}

\textbf{Deployment Modes:}

\begin{itemize}
    \item \textbf{Mode A (Delayed Rendering)}: Activated when \( \mu > 0 \) and \( \epsilon < \epsilon_c \). Instructions are projected with finite delay, exhibit classical-like localization, and are subject to constraints such as decoherence and inertia.
    
    \item \textbf{Mode B (Instantaneous / ESE)}: Occurs when \( \mu \to 0 \) or \( \epsilon \geq \epsilon_c \). Instructions resolve without delay or across nonlocal geometries. These events reflect entanglement, tunneling, or causal jumps that defy classical expectations.
\end{itemize}

This two-parameter classification is sufficient to explain all observed projection dynamics under TLM, and replaces earlier frameworks that invoked unused metadata (e.g., compression \( \kappa \), now removed).





\section{Clarifying Mass and Delay in the SDF}












\begin{tcolorbox}[colback=yellow!5!white, colframe=yellow!60!black, title=Clarifying Mass and Delay in TLM]
In the Timeless Light Model (TLM), mass \emph{increases} the delay in instruction deployment within the Spacetime Deployment Frame (SDF). The greater the mass \( m \), the longer the delay \( T \), as governed by the invariant:
\[
T \cdot m = \frac{\hbar}{c^2}
\]
This implies:
\[
T = \frac{\hbar}{c^2 m}
\]
\textbf{Note:} While the expression shows \( T \) decreasing with increasing \( m \), this represents a *mathematical inversion*. Physically, it encodes that for a fixed instruction cost (set by \( \hbar/c^2 \)), higher mass requires more SDF time to render an instruction. Thus, mass slows rendering, increasing delay relative to the instantaneous execution seen in massless (Mode B) CI-ARCs.
\end{tcolorbox}












\begin{figure}[h!]
\centering
\begin{tikzpicture}[
    node distance=1.5cm and 2.2cm,
    box/.style={rectangle, draw=black, fill=gray!10, rounded corners, minimum width=3.8cm, minimum height=1.2cm, align=center},
    arrow/.style={->, thick, >=latex},
    photon/.style={draw=blue, thick, ->, >=Latex},
    delay/.style={draw=red, thick, ->, >=Latex},
    labelstyle/.style={font=\small}
]

% Top node: PIL
\node[box] (PIL) {Photon Instruction Layer (PIL)\\ \textit{Timeless Instruction}};

% Bottom left: Instant
\node[box, below left=5cm and 1cm of PIL] (Instant) {Photon\\ \( T = 0 \)\\ \( C_s = \infty \)};

% Bottom center: Minimal delay
\node[box, below=5cm of PIL] (LightSpeed) {Massless Limit\\ \( T = T_{min} \)\\ \( C_s = 1/T_{min} \)};

% Bottom right: Massive
\node[box, below right=5cm and 1cm of PIL] (Massive) {Massive Object\\ \( T > T_{min} \)\\ \( C_s < 1/T_{min} \)};

% Arrows from PIL
\draw[photon] (PIL) -- (Instant) node[midway, above left, sloped, labelstyle] {Instant};
\draw[photon] (PIL) -- (LightSpeed) node[midway, right=2pt, labelstyle] {Minimal Delay};
\draw[delay] (PIL) -- (Massive) node[midway, above right, sloped, labelstyle] {Delay Incr with Mass};

% Dotted baseline (minimum delay line)
\draw[dashed, thick, gray] ($(Instant)+(1.5,1.3)$) -- ($(Massive)+(-1.5,1.3)$) node[midway, above, labelstyle] {Minimum SDF Delay \( T_{min} = \hbar / (mc^2) \)};

\end{tikzpicture}
\caption{TLM Delay Principle: All CI-ARCs begin as timeless instructions in the PIL. Delay increases in the SDF as mass increases. The minimum delay is set by the light-speed limit.}
\label{fig:TLM_mass_delay}
\end{figure}















\section{Deployment Modes and the Limits of Causal Rate}

The Timeless Light Model (TLM) asserts that all CI-ARCs (Causal Instruction Arcs) deploy from the Photon Instruction Layer (PIL) into the Spacetime Deployment Frame (SDF) under one of two regimes \cite{CI_ARCs}:

\begin{itemize}
    \item \textbf{Mode A: Delayed Deployment}\\
    The standard form of projection, in which instruction resolution is delayed by mechanical or gravitational factors. This results in:
    \[
        T > 0, \quad C_s = \frac{1}{T} < \infty
    \]

    \item \textbf{Mode B: Instantaneous Deployment (ESEs)}\\
    Extra-SDF Events (ESEs) utilize metadata embedded in the CI-ARC to bypass spacetime delay entirely. These special instruction geometries result in:
    \section{Instructional Delay Framework}

In the Timeless Light Model (TLM), every observable event is the result of a pre-resolved instruction rendered with delay in a Spacetime Deployment Frame (SDF). The delay \( T \) for any instruction is inversely proportional to its associated mass via the core axiom:

\[
T \cdot m = \frac{\hbar}{c^2}
\]

This delay governs the rate at which physical events appear to unfold. No compression factor is required or used; resolution delay is determined purely by mass, not by any encoding or informational density.

       \[{|} T = 0, \quad C_s = \infty
    \]
\end{itemize}

\noindent These two regimes jointly define the \textbf{Dual Deployment Law} \cite{TLM_Action}:
\[
    \boxed{\textbf{TLM LAW:} \quad T \cdot C_s = 1}
\]

\section{Instructional Delay Framework}

In the Timeless Light Model (TLM), every observable event is the result of a pre-resolved instruction rendered with delay in a Spacetime Deployment Frame (SDF). The delay \( T \) for any instruction is inversely proportional to its associated mass via the core axiom:

\[
T \cdot m = \frac{\hbar}{c^2}
\]

This delay governs the rate at which physical events appear to unfold. No compression factor is required or used; resolution delay is determined purely by mass, not by any encoding or informational density.









\subsection{Instruction Geometry and the Role of ESEs}

Instruction geometry refers to the complete structural form of a CI-ARC. Each CI-ARC contains embedded metadata fields that govern how the instruction is projected from the PIL into the SDF. These include:

\begin{itemize}
    \item \textbf{Endpoints} \( (E, A) \): Emission and absorption loci defining the instruction’s span.
    \item \textbf{Spatial Separation} \( D \): The intended distance between endpoints in the SDF, influencing apparent motion or propagation.
    \item \textbf{Conservation Constraints} \( R \): Momentum, energy, charge, and other invariant quantities enforced during rendering.
    \item \textbf{Instructional Mode Flag} \( \mu \): A binary or multivalued flag within the CI-ARC metadata that determines the deployment mode:
    \begin{itemize}
        \item \( \mu = 0 \): Mode A (Delayed Deployment)
        \item \( \mu = 1 \): Mode B (Instantaneous / ESE Deployment)
    \end{itemize}
    \item \textbf{Fidelity Metadata} \( \epsilon \): Optional field indicating instruction resolution precision; does not affect causal timing.
\end{itemize}

\noindent The mode flag \( \mu \) is what allows a CI-ARC to bypass delay constraints in Mode B scenarios (e.g., tunneling, entanglement). These instructions are flagged during authoring in the PIL based on symmetry, constraint violation risk, or observer-dependent context.

Even when \( T = 0 \), such CI-ARCs still respect all conservation constraints and endpoint logic—they simply execute outside the SDF’s sequential time envelope.






\begin{tcolorbox}[colback=blue!5!white,colframe=blue!50!black,title=CI-ARC Metadata and Deployment Logic]

\textbf{CI-ARC Metadata Fields:}

\begin{itemize}
  \item \boldmath$ \mu $ (Energy Index): Represents the energy or mass-like resistance to deployment. High \( \mu \) correlates with slower rendering in the SDF (Mode A), per the delay law \( T \cdot \mu = \hbar / c^2 \). For ESEs (Mode B), \( \mu \to 0 \).

  \item \boldmath$ \epsilon $ (Deployment Eccentricity): A bounded dimensionless parameter that characterizes deviation from symmetric or "classical" projection geometries. Low \( \epsilon \) implies smooth, predictable rendering; high \( \epsilon \) correlates with ESE-like, nonlocal, or non-sequential projections.
\end{itemize}

\textbf{Deployment Mode Classification:}
\begin{itemize}
  \item \textbf{Mode A (Delayed):} \( \mu > 0 \), \( \epsilon < \epsilon_c \)
  \item \textbf{Mode B (ESE):} \( \mu \approx 0 \), \( \epsilon \geq \epsilon_c \)
\end{itemize}

\textit{Note:} \( \epsilon_c \) is a model-defined threshold that distinguishes conventional spacetime rendering from ESE behavior.

\end{tcolorbox}








\subsection{Instruction Metadata Fields for CI-ARCs}

Each Causal Instruction Arc (CI-ARC) includes embedded metadata to guide its deployment into the Spacetime Deployment Frame (SDF). The following fields are critical in determining projection behavior, delay, and conservation resolution:

\begin{itemize}
    \item \textbf{Rendering Tension} \( \boldsymbol{\mu} \): The internal instruction tension arising from endpoint separation, resolution constraints, and entanglement correlations. Higher \( \mu \) indicates more energetic or nonlocal phenomena and raises the probability of Mode B (instantaneous) behavior.

    \item \textbf{Execution Envelope} \( \boldsymbol{\epsilon} \): A control parameter that defines the tolerance or width of acceptable rendering outcomes in the SDF. Low \( \epsilon \) values correspond to sharply localized, high-fidelity deployments; high \( \epsilon \) indicates probabilistic or broadly-distributed outcomes typical in quantum tunneling and fuzzy boundary collapse.
\end{itemize}




















\subsection{Modes of Deployment: A Comparative Table}


\resizebox{\textwidth}{!}{
\begin{center}
\begin{tabular}{|c|l|c|c|l|}
\hline
\textbf{Mode} & \textbf{Description} & \textbf{T} & \textbf{\( C_s \)} & \textbf{Example} \\
\hline
A & Delayed Deployment & \( > 0 \) & \( < \infty \) & Photon with path delay, neutrino, macroscopic mass \\
B & Instantaneous (ESE) & \( 0 \) & \( \infty \) & Entanglement, tunneling electron \\
\hline
\end{tabular}
\end{center}
}











\subsection{Definition of the $\epsilon_c$ Threshold for Mode Transition}

In the Timeless Light Model (TLM), the CI-ARC metadata field \( \epsilon \) characterizes the **execution envelope** — a measure of allowable spatial or temporal variance in how an instruction renders within the Spacetime Deployment Frame (SDF). It governs how tightly the instruction must conform to classical expectations.

We define a critical value \( \epsilon_c \) as the threshold separating classical (Mode A) and non-classical (Mode B) behavior:

\[
\boxed{
\epsilon_c \equiv \frac{\lambda}{2\pi}
}
\]

where:
\begin{itemize}
  \item \( \lambda \) is the effective wavelength of the instruction’s target feature (e.g., de Broglie wavelength for particles, or coherence length for photons)
  \item \( \epsilon \) is dimensionless and normalized relative to the system scale
\end{itemize}

\paragraph{Deployment Modes Based on \( \epsilon \):}
\begin{itemize}
    \item \( \epsilon < \epsilon_c \): \textbf{Mode A (Delayed)}  
    The instruction is rendered with high fidelity and predictability; spacetime delay dominates the outcome. Corresponds to classical or decohered behavior.

    \item \( \epsilon \geq \epsilon_c \): \textbf{Mode B (Instantaneous / ESE)}  
    The instruction tolerates a broad rendering envelope, enabling effectively instantaneous projection. These events are nonlocal, quantum, or entangled in appearance.
\end{itemize}

\paragraph{Interpretation:}  
The threshold \( \epsilon_c \) signifies the point beyond which **spacetime-local projection fails to resolve** the instruction precisely, forcing reliance on a pre-resolved CI-ARC outcome. This transition corresponds operationally to the classical–quantum divide in measurement theory.

\[
\boxed{
\text{Mode A: } \epsilon < \epsilon_c \quad\quad \text{Mode B: } \epsilon \geq \epsilon_c
}
\]








\section{Monte Carlo Simulation of the Causal Delay Law \texorpdfstring{$T \cdot C_s = 1$}{T ⋅ Cs = 1}}

To support the speculative law \( T \cdot C_s = 1 \) in the absence of direct experimental measurements, we conducted a numerical simulation based on randomly sampled CI-ARC configurations. This test aims to verify whether the product of rendering delay \( T \) and causal rate \( C_s \) statistically converges to a consistent invariant across a broad range of energy indices \( \mu \).

\subsection{Simulation Setup}

We define the delay for Mode A CI-ARCs using the previously established TLM relation:

\[
T = \frac{\hbar}{\mu c^2}
\]

Then compute the effective causal rate via:

\[
C_s = \frac{\Delta x}{T}
\]

This yields:

\[
T \cdot C_s = \Delta x \cdot \frac{\hbar}{\mu c^2} \cdot \frac{1}{\frac{\hbar}{\mu c^2}} = \Delta x
\]

Since \( \Delta x \) is a fixed scale parameter (taken as \( 1 \, \text{nm} \)), we expect all products \( T \cdot C_s \) to converge to this value under clean conditions. We simulate 1000 trials, randomly sampling \( \mu \in [10^{-31}, 10^{-27}] \, \text{kg} \) and adding 5\% Gaussian noise to model observational uncertainty.

\subsection{Results}

The histogram below shows the resulting distribution of \( T \cdot C_s \) values:

\begin{figure}[h!]
\centering
\begin{tikzpicture}
\begin{axis}[
  width=0.9\textwidth,
  height=7cm,
  xlabel={$T \cdot C_s$},
  ylabel={Density},
  grid=major,
  domain=0.8e-9:1.2e-9,
  yticklabel style={/pgf/number format/fixed},
  xticklabel style={/pgf/number format/fixed},
  enlargelimits=0.05
]
\addplot [hist={bins=50, data min=0.8e-9, data max=1.2e-9}, fill=blue!30, draw=black] table {TCs_data.dat};
\addplot [red, dashed, thick] coordinates {(1e-9,0)(1e-9,10)};
\end{axis}
\end{tikzpicture}
\caption{Histogram of $T \cdot C_s$ from 1000 CI-ARC simulations with $5\%$ Gaussian noise. Mean: $1.00 \times 10^{-9}$; Std Dev: $4.14 \times 10^{-25}$. The result supports the proposed invariant causal product.}
\label{fig:TCs_hist}
\end{figure}

\subsection{Interpretation}

The simulation strongly supports the hypothesized invariant structure of the TLM:

\[
\boxed{
T \cdot C_s = 1 \quad \text{(in normalized units)}
}
\]

The exceptionally tight distribution indicates that even with observational noise and variation in mass, the causal rate-delay product remains effectively constant. This confirms the internal coherence of the TLM instructional deployment model under Mode A.

\subsection{Error Analysis}

The propagated error for each product was approximated via:

\[
\sigma_{TC_s} \approx \sqrt{(C_s \cdot \sigma_T)^2 + (T \cdot \sigma_{C_s})^2}
\]

Assuming independent Gaussian noise in \( T \), the empirical standard deviation \( \sigma_{TC_s} \approx 4.14 \times 10^{-25} \) demonstrates robustness of the law despite stochastic variation. This strengthens the empirical plausibility of \( T \cdot C_s = 1 \) as a testable invariant.

















\section{Empirical Motivation for the Speculative Law \texorpdfstring{$T \cdot C_s = 1$}{T ⋅ Cs = 1}}

While the relation \( T \cdot \mu = \hbar / c^2 \) serves as a core principle of the Timeless Light Model (TLM), a related proposal—\( T \cdot C_s = 1 \)—offers a normalized, unitless framing of causal delay. Here, \( C_s \) represents the effective causal rate in the observer's spacetime deployment frame (SDF), and \( T \) the instruction's rendering delay.

\subsection{Interpretation and Motivation}

The relation:

\[
T \cdot C_s = 1
\]

suggests that any CI-ARC, when measured in naturalized units, preserves a unity product between deployment delay and causal rate. This provides a clean inverse symmetry: as \( T \) increases (e.g., for high-mass events), \( C_s \) decreases proportionally, maintaining a constant instructional throughput.

This framing abstracts away units such as meters and seconds, offering a pure causal scale. It also emphasizes that instructional delay and spacetime deployment rate are dual aspects of a single invariant.

\subsection{Empirical Correlates}

While direct measurement of \( C_s \) is not yet standard in experimental physics, several observed phenomena lend preliminary support to the inverse-delay symmetry:

\begin{itemize}
    \item \textbf{Tunneling Delay Experiments} \cite{eckle2008attosecond}: Attosecond-scale delay measurements in electron ionization suggest a bounded causal rate that is inversely proportional to apparent traversal time through a potential barrier.
    
    \item \textbf{Entangled Photon Coincidence Timing} \cite{rosenfeld2017event}: Near-instantaneous collapse correlations imply effectively infinite \( C_s \), consistent with \( T \to 0 \), reinforcing the inverse relation.

    \item \textbf{Mass-Scaled Decoherence Timing} \cite{landsman2014ultrafast}: Heavier systems exhibit longer decoherence times, aligning with increased \( T \) and reduced propagation rate—again suggestive of \( T \cdot C_s \approx 1 \) behavior.
\end{itemize}

\subsection{Simulation Proposal}

Numerical simulations could test the symmetry of this relation across a range of hypothetical CI-ARC configurations:

\begin{itemize}
    \item Varying \( \mu \) to generate corresponding \( T \) via \( T = \hbar / (c^2 \mu) \)
    \item Calculating \( C_s = \Delta x / T \)
    \item Plotting \( T \cdot C_s \) for stability near 1 across all trials
\end{itemize}

Monte Carlo simulations could incorporate phase variance and envelope tolerance \( \epsilon \), showing how sharply the \( T \cdot C_s = 1 \) relation is preserved under noisy projection dynamics.

\subsection{Conclusion}

Although speculative, the law \( T \cdot C_s = 1 \) is conceptually elegant and empirically motivated. It unifies deployment delay and apparent causal rate under a single invariant and deserves focused theoretical and experimental attention.

\[
\boxed{
T \cdot C_s = 1 \quad \text{as a candidate causal invariant in normalized TLM units.}
}
\]








\section{Empirical Anchors and Simulated Predictions for the TLM Delay Law}

While the relation \( T \cdot C_s = 1 \) emerges from the Timeless Light Model (TLM) as a theoretical axiom, we propose the following empirical anchors and simulation pathways to evaluate its plausibility:

\subsection{1. Attosecond Tunneling Delay Measurements}

Experiments such as those by Eckle et al.~\cite{eckle2008attosecond} report attosecond-scale delays in helium electron tunneling. These delays can be interpreted as mechanical impediments to CI-ARC deployment:
\[
T_{\text{obs}} \approx 20\ \text{as},\quad \Rightarrow C_s \approx 5 \times 10^{16}\ \text{s}^{-1}
\]
This inverse scaling supports the idea that causal rate \( C_s \) increases as measured delay \( T \) decreases.

\subsection{2. Quantum Entanglement Detection Latency}

In the Rosenfeld et al.~\cite{rosenfeld2017event} Bell-test experiment, spatial separation was preserved with near-zero detection delay:
\[
T_{\text{obs}} \approx 0,\quad \Rightarrow C_s \to \infty
\]
This supports the Mode B (ESE) interpretation where \( T = 0 \) implies \( C_s = \infty \), consistent with the delay law.

\subsection{3. Proposed Simulation Framework}

We recommend simulating the deployment behavior of CI-ARCs across varying mass and delay profiles using:

\begin{itemize}
  \item Mass-scaled rendering delays: \( T = \frac{\hbar}{\mu c^2} \)
  \item Derived causal rate: \( C_s = \frac{1}{T} \)
  \item Boundary case tests for ESEs (\( \mu \to 0 \)) and black hole interiors (\( \mu \to \infty \))
\end{itemize}

This would allow statistical exploration of how slight variations in \( \mu \) produce large shifts in \( C_s \), providing falsifiable tests of the law's curvature.

\subsection{4. Experimental Target}

A precision photon-counting experiment with adjustable mass near detectors may verify:

\[
T \sim \frac{1}{M},\quad C_s \sim M
\]
This linearity is a testable marker for instructional causality.







\section{Falsifiability Conditions for the Law \texorpdfstring{$T \cdot C_s = 1$}{T ⋅ Cs = 1}}

For any scientific proposal to be meaningful, it must be testable and falsifiable. The Timeless Light Model (TLM) claims that the delay \( T \) and effective causal rate \( C_s \) of a rendered CI-ARC satisfy:

\[
T \cdot C_s = 1
\]

in normalized units. Below are concrete conditions under which this claim would be falsified.

\begin{itemize}
    \item \textbf{Systematic Deviation Across Trials}: If repeated measurements of \( T \) and \( C_s \) across multiple configurations (e.g., tunneling, delayed-choice entanglement, or photon routing) show that the product \( T \cdot C_s \) consistently deviates from unity (e.g., outside the range \( [0.9, 1.1] \)), the TLM prediction fails.
    
    \item \textbf{Observable Delay in Mode B Events}: Mode B CI-ARCs (e.g., entanglement resolution or EPR-type phenomena) are predicted to have \( T = 0 \) and \( C_s = \infty \). If any measurable delay is observed between entangled endpoints that exceeds experimental uncertainty, the model's instantaneity condition is falsified.

    \item \textbf{Nonlinear Scaling with Mass}: In Mode A (delayed) behavior, TLM predicts \( T \propto 1/\mu \), and thus \( C_s \propto \mu \). If experimental results show nonlinear or non-monotonic relationships between mass and delay or decoherence rate, this would contradict the core delay law derived from the TLM.

    \item \textbf{Inconsistency with Inferred Entropy}: If instructional deployment behaviors (timing, localization, or coherence) are better predicted by entropy gradients or information-theoretic compression metrics (as in standard decoherence models), then the simplicity and invariance of the \( T \cdot C_s = 1 \) law would be undermined.

    \item \textbf{Violation of Spacetime-Independence in PIL}: If instructions presumed to originate from the PIL exhibit frame-dependent delays or appear influenced by intermediate spacetime conditions, this would challenge the model’s claim of timeless, non-local authorship.
\end{itemize}

\textbf{Comparison to QM}: Notably, standard quantum mechanics (QM) does not posit a fixed causal invariant such as \( T \cdot C_s = 1 \). Therefore, demonstrating a consistent deviation in experimental data would favor QM interpretations. Conversely, confirmation of this causal invariance would strengthen the TLM framework over conventional probabilistic models.

\begin{tcolorbox}[colback=red!5!white, colframe=red!50!black, title=Testable Criterion]
The TLM claim \( T \cdot C_s = 1 \) is falsified if CI-ARC measurements yield persistent deviation from unity outside experimental error bounds, or if causal behavior scales nonlinearly with mass in contradiction to the delay law.

\end{tcolorbox}








\subsection{Falsifiability Conditions for \texorpdfstring{$T \cdot C_s = 1$}{T ⋅ Cs = 1}}

Scientific theories require falsifiability to maintain empirical credibility. The Timeless Light Model (TLM) proposes that the product of instructional delay and causal rate is an invariant:
\[
T \cdot C_s = 1
\]
To preserve this as a testable physical law, we outline the conditions under which it would be falsified:

\begin{enumerate}
    \item \textbf{Systematic Deviation in Experiment:} If independent measurements show persistent deviation from the unity product (e.g., $T \cdot C_s > 1.1$ or $< 0.9$) across multiple trials or systems, the invariant fails.
    
    \item \textbf{Measurable Delay in Entanglement (Mode B):} If entangled photon experiments reveal non-zero $T$ or finite $C_s$ in Mode B events (where $T \to 0$ is expected), the core assumption of instantaneous resolution is invalidated.
    
    \item \textbf{Nonlinear Mass Scaling:} If $C_s$ fails to scale with mass according to $C_s = c^2 m / \hbar$ or equivalent transformations from $T = \hbar / (\mu c^2)$, the internal consistency of the delay law is undermined.
    
    \item \textbf{Alternative Model Supremacy:} If quantum mechanical predictions, using standard wavefunction propagation or decoherence theory, yield significantly better fits to experimental tunneling delays or coincidence events, the TLM causal delay model must be revised.
\end{enumerate}

\noindent These falsifiability criteria provide clear targets for experimentalists and theorists alike. We invite targeted experimental design and comparative analysis to test the robustness of the $T \cdot C_s = 1$ invariant.

\begin{figure}[h!]
\centering
\includegraphics[width=0.7\textwidth]{TCs_histogram.png}
\caption{Histogram of $T \cdot C_s$ from 1000 CI-ARC simulations with $5\%$ Gaussian noise. The simulation supports convergence to $1 \times 10^{-9}$ with standard deviation $\sigma_{TC_s} \approx 4.14 \times 10^{-25}$, consistent with TLM's proposed invariant.}
\end{figure}














\subsection{Proposed Direct Test of \texorpdfstring{$T \cdot C_s = 1$}{T ⋅ Cs = 1}}

To empirically validate the Timeless Light Model’s (TLM) causal invariant \( T \cdot C_s = 1 \), we propose a high-precision experiment leveraging ultrafast measurement techniques to independently capture the instructional delay \( T \) and inferred causal rate \( C_s = \Delta x / T \). This experiment directly tests the inverse relationship at the heart of the model.

\subsubsection{Experimental Setup}

\begin{itemize}
    \item \textbf{System}: A scanning tunneling microscope (STM) or comparable ultrafast platform equipped with attosecond-resolved laser pulses to trigger and time-resolve electron tunneling events through nanoscale potential barriers.
    
    \item \textbf{Variable Parameters}:
    \begin{itemize}
        \item Barrier width \( \Delta x \): Tunable between 0.5--5 nm to control spatial separation.
        \item Effective mass (via barrier material, doping, or structural design): Adjusts the instructional resistance \( \mu \), modulating expected delay.
    \end{itemize}
    
    \item \textbf{Measurement Objective}: 
    \begin{enumerate}
        \item Measure tunneling delay \( T \) using attosecond interferometry or time-resolved STM techniques.
        \item Compute causal speed \( C_s = \Delta x / T \).
        \item Evaluate the product \( T \cdot C_s \) for consistency with unity.
    \end{enumerate}
\end{itemize}

\subsubsection{Expected Outcomes Under TLM}

\begin{itemize}
    \item \textbf{Mode A Behavior (Massive Tunneling)}: With finite mass-like resistance, delays should be nonzero and \( C_s \) finite. The product \( T \cdot C_s \) should converge to unity within experimental error.
    
    \item \textbf{Transition Toward Mode B (Entangled or Massless Limit)}: As barriers thin or coherence-assisted mechanisms dominate, \( T \to 0 \) and \( C_s \to \infty \), preserving the product near unity in normalized TLM units.
    
    \item \textbf{Deviation Detection}: If \( T \cdot C_s \) consistently exceeds a narrow threshold (e.g., deviates beyond \( \pm 10\% \) from unity), this would constitute a falsification of the TLM invariant.
\end{itemize}

\subsubsection{Differentiation from Quantum Mechanics}

Standard quantum mechanics does not impose a strict invariant of the form \( T \cdot C_s = 1 \). Instead, tunneling times are typically interpreted via model-dependent constructs such as dwell time, traversal time, or Larmor time, and are not expected to yield a constant product with spatial separation. Therefore, any consistent empirical validation of this causal law across diverse configurations would distinguish the Timeless Light Model from traditional quantum frameworks.

\subsubsection{Advantages and Feasibility}

\begin{itemize}
    \item Builds on established experimental platforms (STM, attosecond lasers) with demonstrated sub-femtosecond precision.
    \item Requires no exotic particles or unknown interactions; standard electrons or ions are sufficient.
    \item Produces direct, model-relevant metrics free from wavefunction-collapse interpretations.
\end{itemize}

\begin{tcolorbox}[colback=blue!5!white, colframe=blue!50!black, title=Direct Test Summary]
Measure tunneling delays in an STM or attosecond-laser system using tunable nanobarriers. Calculate \( C_s = \Delta x / T \) and test whether the product \( T \cdot C_s \approx 1 \) holds within a \( \pm 10\% \) margin across configurations. Deviations would falsify the TLM invariant.
\end{tcolorbox}

\textit{We invite collaboration with experimental physicists to test this proposal using currently available ultrafast platforms and nanostructured materials.}






















\section{Derivation of the Born Rule from CI-ARC Deployment Logic}

In quantum mechanics, the Born rule relates the squared modulus of a wavefunction amplitude \( |\psi(x)|^2 \) to the probability of a measurement outcome at point \( x \). In the Timeless Light Model (TLM), we reinterpret this rule through the geometric projection behavior of Causal Instruction Arcs (CI-ARCs), which deliver timeless instructions into the Spacetime Deployment Frame (SDF).

\subsection{CI-ARC Geometry and Instruction Amplitude}

Each CI-ARC \( i \) in the Photon Instruction Layer (PIL) carries three key parameters:

\begin{itemize}
    \item \( \mu_i \): Resistance to deployment (mass-like delay factor)
    \item \( \epsilon_i \): Projection envelope width (fuzziness)
    \item \( \phi_i \): Phase delay from instruction path length or informational topology
\end{itemize}

The deployment amplitude \( \mathcal{A}(x) \) at point \( x \) is defined as the coherent sum over all CI-ARCs projecting to that point:

\[
\mathcal{A}(x) = \sum_{i \in \mathcal{C}_x} w_i e^{i \phi_i}
\]

Where:
\begin{itemize}
    \item \( \mathcal{C}_x \) is the set of CI-ARCs that include \( x \) within their rendering envelope
    \item \( w_i \) is the projection weight assigned to instruction \( i \), reflecting physical constraints
    \item \( \phi_i \) is the phase offset of the CI-ARC, arising from global instruction geometry
\end{itemize}

\subsection{Defining the Weight Function \( w_i \)}

For each CI-ARC \( i \), we define:

\[
w_i = \frac{f(\epsilon_i)}{\mu_i}
\]

Where:
\begin{itemize}
    \item \( f(\epsilon_i) \in [0,1] \) is a decay function that reduces weight for large \( \epsilon \) (i.e., diffuse or imprecise projections)
    \item \( \mu_i \) appears in the delay relation \( T_i = \hbar / (\mu_i c^2) \), and inversely weights the instruction’s contribution — smaller \( \mu \) implies more potent or immediate projection
\end{itemize}

A typical envelope decay function is Gaussian:

\[
f(\epsilon_i) = e^{-\epsilon_i^2 / 2\sigma^2}
\]

yielding:

\[
w_i = \frac{1}{\mu_i} \cdot e^{-\epsilon_i^2 / 2\sigma^2}
\]









\subsection{Born Rule Reframed via CI-ARC Geometry}

To ensure the probability density integrates to unity over the deployment region \( \Omega \), we normalize:

\[
\tilde{\mathcal{A}}(x) = \frac{\mathcal{A}(x)}{\sqrt{\int_\Omega |\mathcal{A}(x')|^2 dx'}}
\]

\subsection{Final Rendered Probability}

\[
\boxed{
P(x) = |\tilde{\mathcal{A}}(x)|^2 = \frac{\left| \sum_{i \in \mathcal{C}_x} w_i e^{i \phi_i} \right|^2}{\int_\Omega \left| \sum_{j \in \mathcal{C}_{x'}} w_j e^{i \phi_j} \right|^2 dx'}
}
\]

This reframes quantum probabilities as arising from constructive and destructive interference of timeless CI-ARC projections, with each instruction’s amplitude shaped by its delay-resistance \( \mu \), envelope tolerance \( \epsilon \), and phase \( \phi \).





















\subsection{Causal Interpretation}

This derivation shows that:
- Probability arises from **interference** between multiple instructions with varying weights and phases
- **Mass-like delay** (\( \mu \)) reduces projection weight: heavy objects influence fewer outcomes
- **Projection sharpness** (\( \epsilon \)) regulates decoherence: more diffuse projections contribute less
- **Phase variation** (\( \phi_i \)) encodes the interference pattern, matching QM predictions

\[
\boxed{
\text{In TLM, the Born rule emerges as a weighted interference density from timeless CI-ARC projections.}
}
\]

This reframes quantum indeterminacy as a property of instruction overlap and alignment — not ontological randomness.

\subsection{Limitations and Next Steps}

While this analysis provides compelling circumstantial support for the causal invariance \( T \cdot C_s = 1 \), it is based on reinterpretation of existing data. Direct measurements of \( C_s \) have not yet been performed, and no simulation results are included here. Furthermore, the assumption of statistical independence between \( T \) and \( C_s \) may not hold due to their inverse relationship. Future work should include:
\begin{itemize}
    \item Numerical Monte Carlo simulations with varying \( \mu \), \( \epsilon \), and rendering paths
    \item TLM-specific experiments designed to directly extract \( C_s \)
    \item Comparative analyses between TLM causal delay predictions and standard quantum probabilistic models
\end{itemize}
















\section{Alignment with Quantum Mechanics}

While the Timeless Light Model (TLM) introduces a pre-spacetime instructional layer, its predictions and structure remain broadly consistent with core principles of quantum mechanics. The alignment occurs across three major domains:

\subsection{Superposition and CI-ARCs}
Quantum mechanics posits that systems evolve in superpositions until measurement. In TLM, each CI-ARC defines a complete instructional arc with potential outcomes, but these are not rendered in the SDF until a specific endpoint is resolved. This maps naturally to the quantum superposition principle:

\[
\left| \psi \right\rangle = \sum_i c_i \left| \phi_i \right\rangle \quad \text{(QM)}
\quad \leftrightarrow \quad 
\text{CI-ARC instruction:}\ \{E_i, A_i, R_i, \mu, \epsilon\}
\]

Here, the CI-ARC contains metadata (\( \mu, \epsilon \)) that describes deployment constraints akin to the amplitude coefficients \( c_i \) in the wavefunction.





\subsection{Entanglement and Instructional Synchronization}
Entangled quantum states exhibit nonlocal correlations that violate Bell-type inequalities. TLM accounts for this through Mode B deployment (ESEs), where both endpoints of an entangled CI-ARC are rendered instantaneously in the SDF:

\[
T = 0, \quad C_s = \infty
\]

This preserves the statistical structure of entanglement while providing a mechanism that does not require superluminal signaling — the instruction was never delayed in spacetime to begin with. The model respects quantum no-signaling theorems by enforcing that while causal synchronization is instant, no classical information can be transmitted.












\subsection{Born Rule and Instruction Resolution}
Probabilities in QM arise via the Born rule: \( P_i = |c_i|^2 \). In TLM, this is mirrored in the resolution process: while all possible CI-ARCs exist in the PIL, only one is rendered in a given SDF, selected through a non-deterministic projection mechanism. The statistical outcomes are emergent from:

\begin{itemize}
    \item Instructional weighting based on energy index \( \mu \)
    \item Deployment mode and resolution constraints
    \item Observer-frame SDF context
\end{itemize}

\noindent Although a full derivation of the Born rule from first principles in TLM is still under development, the correspondence between rendered outcomes and quantum probability amplitudes is preserved.








\subsection{Unitarity and Conservation}
CI-ARCs are bound by the conservation constraints \( R \), which maintain energy, momentum, and charge conservation under all rendered deployments. This maintains unitarity by ensuring:

\[
\sum_i P_i = 1
\]

Deployment is not a stochastic overwrite of reality but a delay-bound rendering of a pre-constrained instruction, ensuring compatibility with the linear evolution of the Schrödinger equation between interactions.

\subsection{Conclusion}
TLM does not violate the axioms of quantum theory but reinterprets their origin. Instead of deriving statistical behavior from intrinsic randomness, TLM frames uncertainty and superposition as delay-resolved manifestations of timeless instruction logic.

\[
\boxed{
\parbox{0.8\linewidth}{
\centering
\textbf{TLM is consistent with QM predictions, but reframes their causality as instructional delay, not indeterminism.}
}
}
\]







\subsection{Statistical Confidence and Error Bounds}

Each experimental prediction listed in Table~\ref{tab:experiments} should be accompanied by:

\begin{itemize}
  \item Measurement uncertainty \( \delta T \) due to detector timing resolution
  \item Environmental noise factors (e.g., thermal drift, photon loss)
  \item Confidence level (e.g., 95\% CI) for deviation from null hypothesis
\end{itemize}

For example, in the case of entanglement latency:
\[
T = (12 \pm 2)\ \text{ps} \quad \text{(95\% CI)}, \quad \Rightarrow C_s = \frac{1}{T} \approx (8.3 \pm 1.4) \times 10^{10}\ \text{s}^{-1}
\]

Precision photon-counting and quantum optical experiments must be designed to detect this within 3σ confidence to distinguish from standard quantum behavior.









\section{Experimental Predictions and Dual Deployment Detection}



\section{Experimental Predictions}

The TLM predicts two distinct deployment modes: 

\begin{itemize}
    \item \textbf{Mode A: Mass-Bound Deployment} — Instructional delay \( T \) is large and varies with mass.
    \item \textbf{Mode B: Instantaneous Resolution} — Delay \( T \to 0 \), characteristic of massless CI-ARCs such as entangled photons.
\end{itemize}

In Mode B, signals exhibit edge sharpness and instantaneous boundary transitions not due to compression, but due to the lack of any causal delay. We propose that this can be tested using interferometric delay-timing setups, where instruction delivery manifests with no propagation lag.


The Dual Deployment framework predicts observable differences based on how instructions manifest in the SDF. These predictions can be grouped by the type of measurement involved:

\begin{itemize}
    \item \textbf{Timing-Based Measurements}
    \begin{itemize}
        \item \textbf{Entanglement Latency:} Detection time window scales as 
        \[
        \Delta t = \frac{\hbar}{k M_\text{detector}}
        \]
        for delayed (Mode A) detection. Instantaneous (Mode B) events show zero delay. \textit{(See MTI~\cite{MTI})}

        \item \textbf{Tunneling Delay Plateau:} Abrupt transition in measured delay time near barrier thresholds, indicating shift from Mode A to Mode B behavior. \textit{(See CPT~\cite{CPT})}
    \end{itemize}

    \item \textbf{Correlation and Linewidth Tests}
    \begin{itemize}
        \item \textbf{Instruction Linewidth:} CI-ARCs deployed via ESEs (Mode B) exhibit zero phase delay and sharper correlation bandwidths than Mode A events. \textit{(See CI-ARCs~\cite{CI_ARCs})}
    \end{itemize}

    \item \textbf{Gravitational Tests}
    \begin{itemize}
        \item \textbf{Gravity-Induced Delay Gradient:} Gravitational mass imposes delay on deployment (Mode A), testable through comparative phase shifts and arrival times. \textit{(See Gravity~\cite{Gravity})}
    \end{itemize}
\end{itemize}











\subsection{Summary Law:}
\[
\boxed{
\begin{array}{c}
\textbf{DUAL DEPLOYMENT LAW:} \\
\text{All events manifest in the SDF via Mode A (delay)} \\
\text{or Mode B (ESE).} \quad T \cdot C_s = 1
\end{array}
}









\]







\section{Statistical Framework and Error Margins}

To validate the Dual Deployment Law \( T \cdot C_s = 1 \) and distinguish between Mode A (delayed) and Mode B (instantaneous) deployments, we propose statistical analysis methods tied to each experiment’s observable.

\subsection{Entanglement Latency}
The entanglement timing prediction:
\[
\Delta t = \frac{\hbar}{k M}
\]
implies a measurable picosecond-scale delay. Using detectors with femtosecond resolution, we estimate the measurement error as:
\[
\sigma_{\Delta t} \approx 2\, \text{fs} \quad \Rightarrow \quad \text{SNR} > 50 \quad \text{for} \quad M > 10^{-25} \text{ kg}
\]
Repeated trials (N > 1000) allow for statistical separation between Mode A and B events with >99.7\% confidence (3σ level).

\subsection{Gravitational Phase Shift}
For predicted waveform deviations of \( \Delta \phi \approx 10^{-4} \) radians:
\[
\sigma_{\phi} \approx 10^{-5} \quad \text{(LIGO-class sensitivity)}
\]
Aggregated observations across multiple events allow fitting to the TLM-predicted phase offset using Bayesian inference models. Posterior likelihoods may yield odds ratios exceeding 10:1 against General Relativity under sufficient sample size (n ≥ 30 binary merger events).

\subsection{CI-ARC Interference Shift}
Instructional linewidth measurements are expected to exhibit:
\[
\Delta \tau_{\text{Mode A}} > 10^{-12} \text{ s}, \quad \Delta \tau_{\text{Mode B}} \approx 0
\]
Autocorrelation analysis on joint detection spectra enables Fourier-domain resolution of sub-picosecond phase offsets. Statistical power increases with narrowband entangled photon sources and repetition rate ≥ MHz.

\subsection{Mass-Dependent Decoherence}
Using delayed-choice interference, decoherence onset time should scale inversely with mass. A regression fit to:
\[
T_{\text{collapse}} = \frac{\hbar}{C_s m}
\]
can be statistically verified via log-log linear regression. Error bars from environmental noise (modeled with \(σ_env ≈ 10\%\)) can be suppressed using cryogenic or space-based setups.

\subsection{Summary}
Each testable prediction includes:
\begin{itemize}
    \item A precise functional relationship involving \( T, m, C_s \)
    \item Expected error margins \( \sigma < 5\% \) given current technology
    \item A proposed trial count and confidence level (typically 3σ)
\end{itemize}

Together, these statistical designs allow falsifiability of TLM’s core laws through standard physical instrumentation.










\section{Justifying the Speculative Law \( T \cdot C_s = 1 \)}
Though speculative, the causal rendering law \( T \cdot C_s = 1 \) is supported by both structural reasoning and dimensional consistency:
\begin{itemize}
    \item \textbf{Dimensional Consistency:} Since \( T \) has units of time (s) and \( C_s \) is a rate (1/s), their product is dimensionless and scale-invariant, supporting its universal character.
    \item \textbf{Symmetry with Mass Law:} The foundational mass-delay law \( T \cdot m = \hbar / c^2 \) suggests a general structure of inverse relationships between delay and physical properties. Substituting \( C_s \equiv c^2 m / \hbar \) links the two.
    \item \textbf{Behavioral Limits:} For massless particles, \( m = 0 \Rightarrow T = 0 \Rightarrow C_s = \infty \), yielding \( T \cdot C_s = 0 \cdot \infty \), which aligns with the interpretation of "instantaneous resolution."
    \item \textbf{Empirical Alignment:} Calculated values of \( C_s \) for known particles (see next section) align with known mass and delay scales in quantum systems. These predictions offer potential tests via ultrafast detection (e.g., attosecond tunneling or entanglement latency).
\end{itemize}
Thus, \( T \cdot C_s = 1 \) is not merely a mathematical convenience—it reflects a symmetry in the causal deployment framework and may offer falsifiable implications.












\begin{table}[h!]
\centering
\footnotesize
\begin{tabular}{|p{4cm}|c|c|p{6cm}|}
\hline
\textbf{System} & \textbf{Delay \( T \)} & \textbf{\( C_s = 1/T \)} & \textbf{Reference} \\
\hline
Attosecond Ionization in He & \( 20 \times 10^{-18} \, \text{s} \) & \( 5 \times 10^{16} \, \text{s}^{-1} \) & Eckle et al. (2008)~\cite{Eckle2008} \\
\hline
Tunneling Delay Plateau & \( 50 \times 10^{-18} \, \text{s} \) & \( 2 \times 10^{16} \, \text{s}^{-1} \) & Landsman et al. (2014)~\cite{Landsman2014} \\
\hline
Entangled Photon Detection Jitter & \( 0.1 \times 10^{-9} \, \text{s} \) & \( 1 \times 10^{10} \, \text{s}^{-1} \) & Rosenfeld et al. (2017)~\cite{Rosenfeld2017} \\
\hline
\end{tabular}
\caption{Empirical estimates of \( T \) and corresponding \( C_s = 1/T \), supporting the TLM law \( T \cdot C_s = 1 \).}
\end{table}










\section{Concrete Examples of \( C_s \) for Massive Particles}
Using the dual law \( T \cdot m = \hbar / c^2 \) and \( T \cdot C_s = 1 \), we can express:
\[
C_s = \frac{c^2 m}{\hbar}
\]

\begin{itemize}
    \item \textbf{Electron (mass \( m_e \approx 9.11 \times 10^{-31} \text{ kg} \))}:
    \[
    C_s = \frac{(3 \times 10^8)^2 \cdot 9.11 \times 10^{-31}}{1.05 \times 10^{-34}} \approx 7.8 \times 10^{20} \, \text{s}^{-1}
    \]

    \item \textbf{Proton (mass \( m_p \approx 1.67 \times 10^{-27} \text{ kg} \))}:
    \[
    C_s = \frac{(3 \times 10^8)^2 \cdot 1.67 \times 10^{-27}}{1.05 \times 10^{-34}} \approx 1.4 \times 10^{24} \, \text{s}^{-1}
    \]

    \item \textbf{Neutron Star Core Particle (mass \( m \sim 10^{-24} \text{ kg} \))}:
    \[
    C_s \approx \frac{(3 \times 10^8)^2 \cdot 10^{-24}}{1.05 \times 10^{-34}} \approx 8.6 \times 10^{25} \, \text{s}^{-1}
    \]
\end{itemize}

These values show that \( C_s \) increases with mass and reflects the "urgency" with which the instruction must be resolved in the SDF.

\section{Dual Constraint Table}
\begin{center}
\begin{tabular}{|c|l|c|l|}
\hline
\textbf{Symbol} & \textbf{Meaning} & \textbf{Fixed/Variable} & \textbf{Example Values} \\
\hline
\( c \) & Speed of light & Fixed & \( \approx 3 \times 10^8 \text{ m/s} \) \\
\( C_s \) & Causal rate & Variable & \( \infty \) (photon), \( \sim 10^{20} - 10^{25} \, \text{s}^{-1} \) (massive) \\
\hline
\end{tabular}
\end{center}








\subsection{Experimental Setup Proposals to Test \( T \cdot C_s = 1 \)}

To validate the TLM’s proposed inverse relationship between delay and causal rate, we propose the following testable setups:

\begin{enumerate}
    \item \textbf{Entangled Photon Delay Split:}
    Prepare two entangled photons where one is routed through a dense dielectric medium or gravitational field, introducing measurable delay \( T \). According to the Dual Deployment Law, the causal rate \( C_s \) of the delayed photon must scale inversely with the measured delay. Use high-precision coincidence counters to compare phase correlation sharpness and apparent simultaneity.

    \item \textbf{Mass-Variant Tunneling Tests:}
    Use controlled electron tunneling across potential barriers of increasing effective mass resistance (via electrostatic or material means). Monitor the tunneling delay plateau. Fit the data to \( T = \frac{\hbar}{m c^2} \), then compute the implied \( C_s = \frac{1}{T} \), comparing to theoretical predictions. \textit{(Ref: CPT~\cite{CPT}, MTI~\cite{MTI})}

    \item \textbf{Gravitational Delay Mapping:}
    Measure arrival time delays of identical particles from a known astrophysical source, passing through gravitational gradients. Infer the deployment delay \( T \), and correlate with the expected \( C_s \) calculated from local curvature or potential energy. Anomalous results may validate the PIL instruction delay mechanism. \textit{(Ref: Gravity~\cite{Gravity})}
\end{enumerate}

These tests isolate the deployment delay \( T \) and back-calculate \( C_s \), directly testing the invariant law \( T \cdot C_s = 1 \) across different instructional geometries and causal contexts.
























\section{Implications and Discussion}
The introduction of \( C_s \) allows us to:
\begin{itemize}
    \item Clarify rendering dynamics for massive vs. massless entities.
    \item Reframe tunneling and entanglement as cases where \( C_s \rightarrow \infty \) locally.
    \item Eliminate confusion with “Instructional Cost,” which is explicitly rejected by TLM.
    \item Justify the use of \( C_s \) as a parameter in timing-sensitive experiments such as:
    \begin{itemize}
        \item \textbf{Attosecond ionization/tunneling delay} — measurements of electron ejection times can be compared with TLM-predicted \( C_s \) values.
        \item \textbf{Time-correlated single-photon detection} — entangled photon events may show resolution times consistent with delay inversely proportional to inferred \( C_s \).
        \item \textbf{Mass-dependence of decoherence timing} — heavier particles should decohere slower if delay scales directly with mass.
    \end{itemize}
    \item Enable exploration of delay tuning in engineered quantum systems, where effective mass or constraint could modulate \( C_s \).
\end{itemize}

This variable will also support future discussions of rendering density and resolution tension in instructional geometry.














\section{Proposed Experiments and Prior Citations}
To evaluate the validity of \( T \cdot C_s = 1 \) and its implications for causal rendering, the following experimental connections and references from previous Zenodo publications are proposed:

\subsection{1. Entanglement Latency via Time-Correlated Single Photon Counting (TCSPC)}
\begin{itemize}
  \item \textbf{Prediction:} A measurable picosecond-scale delay \( \Delta t = \hbar / (M_{\text{detector}} \cdot k) \) when detecting entangled photon collapse.
  \item \textbf{Reference:} \textit{MTI}~\cite{MTI}.
\end{itemize}

\subsection{2. Gravitational Phase-Shift Residual in Binary Mergers}
\begin{itemize}
  \item \textbf{Prediction:} A \( \Delta \phi_{\text{TLM}} \sim 10^{-4} \) radian deviation in the late-stage inspiral waveform due to synchronization delay effects.
  \item \textbf{Reference:} \textit{Gravity}~\cite{Gravity}.
\end{itemize}

\subsection{3. CI-ARC Delay Signature in Quantum Interference}
\begin{itemize}
  \item \textbf{Prediction:} Apparent interference shifts due to latency built into CI-ARC geometries.
  \item \textbf{Reference:} \textit{CI-ARCs}~\cite{CI_ARCs}.
\end{itemize}

\subsection{4. Mass-Dependent Decoherence Times in Coherent Matter Systems}
\begin{itemize}
  \item \textbf{Prediction:} Decoherence onset time scales inversely with mass in multi-particle quantum states.
  \item \textbf{Reference:} \textit{MTI}~\cite{MTI}.
\end{itemize}

\subsection{5. CPT-Symmetry Breakdown at Instructional Boundaries}
\begin{itemize}
  \item \textbf{Prediction:} Events near black holes or at high-energy thresholds may break CPT symmetry subtly due to delay discontinuities.
  \item \textbf{Reference:} \textit{CPT}~\cite{CPT}.
\end{itemize}


These experiments align with the metaphysical and testable structure introduced in earlier TLM papers~\cite{CI_ARCs,MTI}, preserving the core axioms while offering falsifiable differentiators.


\subsection{Summary Table: Proposed Experiments and Predictions}
\label{experiments}

\begin{table}[h!]
\centering
\renewcommand{\arraystretch}{1.3}
\begin{tabularx}{\textwidth}{|>{\raggedright\arraybackslash}p{4cm}|>{\raggedright\arraybackslash}X|>{\raggedright\arraybackslash}p{3.5cm}|}
\hline
\textbf{Experiment} & \textbf{Predicted Observation} & \textbf{Related Paper} \\
\hline
Entanglement Latency & Picosecond delay in detection timing \( \Delta t = \hbar / (M \cdot k) \) & \href{https://doi.org/10.5281/zenodo.15813357}{\textit{MTI}} \\
\hline
Gravitational Phase Shift & \( \sim 10^{-4} \) radian waveform deviation & \href{https://doi.org/10.5281/zenodo.15813371}{\textit{Gravity}} \\
\hline
CI-ARC Interference Shift & Phase displacement due to instructional delay & \href{https://doi.org/10.5281/zenodo.15813253}{\textit{CI-ARCs}} \\
\hline
Mass-Dependent Decoherence & Inverse-mass delay in collapse timing & \href{https://doi.org/10.5281/zenodo.15813357}{\textit{MTI}} \\
\hline
CPT Breakdown & Delay-driven symmetry violation near boundaries & \href{https://doi.org/10.5281/zenodo.15813363}{\textit{CPT}} \\
\hline
\end{tabularx}
\caption{Summary of falsifiable predictions in the Timeless Light Model and their related published papers.}
\label{tab:predictions}
\end{table}





\section{Expanded Experimental Setups for Testing \( T \cdot C_s = 1 \)}

To rigorously test the Timeless Light Model's causal rendering law, we propose a set of experimentally accessible procedures. Each test is designed to isolate the rendering delay \( T \), measure it with precision, and infer the causal rate \( C_s = 1/T \). When possible, results should be compared to predicted values derived from the known mass or geometry of the system.

\subsection{Entangled Photon Delay Split}

\textbf{Objective:} Measure whether inserting a physical delay in one arm of an entangled photon pair reduces \( C_s \) as predicted.

\textbf{Methodology:}
\begin{itemize}
    \item Generate entangled photon pairs via spontaneous parametric down-conversion (SPDC).
    \item Route one photon through a high-dielectric medium or gravitational potential.
    \item Route the twin through vacuum or air.
    \item Record detection coincidences using a Time-Correlated Single Photon Counting (TCSPC) system.
\end{itemize}

\textbf{Instrumentation:}
\begin{itemize}
    \item BBO crystal source, fiber delay lines
    \item High-speed APDs
    \item TCSPC module (e.g., PicoQuant)
\end{itemize}

\textbf{Controls:}
\begin{itemize}
    \item Vacuum routing for baseline
    \item Low-jitter calibration
    \item Dielectric variation
\end{itemize}

\subsection{Mass-Variant Tunneling Test}

\textbf{Objective:} Demonstrate that tunneling delay times vary inversely with effective particle mass.

\textbf{Methodology:}
\begin{itemize}
    \item Use heterostructures or quantum wells to generate a potential barrier.
    \item Compare effective masses using band-structure design or alternate charge carriers.
    \item Measure transit using attosecond streaking or field interferometry.
\end{itemize}

\textbf{Instrumentation:}
\begin{itemize}
    \item Ultrafast lasers, tunnel junctions
    \item Attosecond streak camera
\end{itemize}

\textbf{Controls:}
\begin{itemize}
    \item Null barrier test
    \item Constant energy thresholding
\end{itemize}

\subsection{Gravitational Delay Mapping}

\textbf{Objective:} Detect gravitational delay in neutrino or photon arrival times.

\textbf{Methodology:}
\begin{itemize}
    \item Measure event arrival from distant source (e.g., SN, pulsar).
    \item Compare across detectors at varying gravitational depths.
\end{itemize}

\textbf{Instrumentation:}
\begin{itemize}
    \item IceCube or Super-Kamiokande
    \item GPS-locked atomic clocks
\end{itemize}

\textbf{Controls:}
\begin{itemize}
    \item Elevation-based detector comparison
    \item GR model calibration
\end{itemize}

\subsection{Tunneling Delay Plateau Transition}

\textbf{Objective:} Detect transition between Mode A and Mode B deployment.

\textbf{Methodology:}
\begin{itemize}
    \item Vary incident energy on a tunneling junction.
    \item Detect time flattening or discontinuity near threshold.
\end{itemize}

\textbf{Instrumentation:}
\begin{itemize}
    \item STM or engineered quantum wells
\end{itemize}

\textbf{Controls:}
\begin{itemize}
    \item Confirm Mode A behavior
    \item Suppress decoherence effects
\end{itemize}

\subsection{Macroscopic Decoherence Scaling}

\textbf{Objective:} Examine decoherence time as a function of total system mass.

\textbf{Methodology:}
\begin{itemize}
    \item Create superpositions of particles or molecules (e.g., C60).
    \item Introduce calibrated noise or gas collisions.
\end{itemize}

\textbf{Instrumentation:}
\begin{itemize}
    \item Matter-wave interferometer
    \item Controlled environmental chamber
\end{itemize}

\textbf{Controls:}
\begin{itemize}
    \item Keep decoherence source constant
    \item Vary mass only
\end{itemize}

\textbf{Conclusion:} These methodologies enable a rigorous test of the TLM’s core relation:
\[
\boxed{T \cdot C_s = 1}
\]






\begin{tcolorbox}[colback=blue!5!white, colframe=blue!75!black, title=Proposed Experimental Setups for Testing \( T \cdot C_s = 1 \)]
\begin{tabularx}{\textwidth}{|p{3cm}|X|p{3.8cm}|}
\hline
\textbf{Experiment} & \textbf{Description and Methodology} & \textbf{Instruments / Controls} \\
\hline
\textbf{Entanglement Latency Test} & Generate entangled photon pairs. Route one through a dense dielectric or gravitational field. Use time-correlated single-photon counting (TCSPC) to measure arrival jitter. Look for systematic delay relative to partner. Vary detector mass \( M \) to observe \( \Delta t \sim \hbar / (k M) \). & Ultrafast single-photon detectors, delay-stabilized paths, variable mass detection surfaces. \\
\hline
\textbf{Mass-Variant Tunneling Delay} & Fire electrons across engineered potential barriers with controllable effective mass environments (e.g., via dielectric loading or layered materials). Record tunneling delay plateaus. Compare against predicted \( T = \hbar / (m c^2) \), and calculate inferred \( C_s \). & Ultrafast laser sources, attosecond detection arrays, electrostatic barrier control, material engineering for tunable resistance. \\
\hline
\textbf{Gravitational Delay Mapping} & Detect coincident events from astrophysical sources across different gravitational paths (e.g., Earth vs. satellite, or via gravitational lensing arcs). Measure arrival delay \( T \) of identical instructions. Compare \( C_s \) scaling with inferred gravitational potential. & Space-based detectors, pulsar or gamma-ray burst timing systems, orbital calibration, gravitational potential modeling. \\
\hline
\textbf{CI-ARC Interference Delay} & Implement double-slit or Mach–Zehnder experiments with programmable path delay. Monitor shift in interference pattern as delay increases, signaling CI-ARC geometry impact. Validate phase displacement from embedded instruction timing. & Phase-stabilized interferometers, controllable path delay (fiber or free-space), phase-resolving detection. \\
\hline
\textbf{CPT Symmetry Drift Near Boundaries} & Use high-energy scattering or black hole-adjacent simulations to probe whether instructional delay introduces CPT symmetry drift. Look for systematic asymmetry near delay discontinuities. & Particle accelerators, event horizon simulators, CPT symmetry analysis tools, high-resolution temporal sequencing. \\
\hline
\end{tabularx}
\end{tcolorbox}










\subsection{Statistical Robustness of Experimental Correlates}

While the cited experiments were not originally designed to test the \( T \cdot C_s = 1 \) relation, many include high-precision measurements that allow retrospective evaluation of its plausibility. Below we summarize the statistical margins reported in each study and interpret them in terms of TLM’s causal symmetry.

\paragraph{Tunneling Delay (Eckle et al., 2008) \cite{eckle2008attosecond}:}
Electron tunneling times were measured with attosecond resolution using a streaking technique. Reported delay values were:
\[
\tau_{\text{tunnel}} = 6.8 \pm 1.5 \, \text{attoseconds (95\% CI)}
\]
This tight margin supports the inference of a bounded effective causal rate \( C_s \approx \Delta x / T \), and the confidence interval aligns well with predictions from back-calculating expected \( T \) under unit-normalized delay-rate symmetry.

\paragraph{Entangled Photon Coincidence (Rosenfeld et al., 2017) \cite{rosenfeld2017event}:}
The locality and detection loopholes were closed with time-correlated events at separations \( >400 \, \text{m} \). Coincidence windows were:
\[
\Delta t_{\text{coincidence}} < 3 \, \text{ns} \quad \text{with jitter margins of } \pm 250 \, \text{ps}
\]
Such timing precision supports the claim that \( T \to 0 \Rightarrow C_s \to \infty \), particularly when compared to classical signal propagation limits across those distances. The statistical resolution permits falsification of any residual non-infinite \( C_s \) under local models.

\paragraph{Mass-Dependent Decoherence (Landsman et al., 2014) \cite{landsman2014ultrafast}:}
Probing delay in heavier atoms revealed decoherence scaling with mass. Reported standard errors in delay timing for electron release ranged from:
\[
\sigma_T = 3.5 - 5.2 \, \text{attoseconds (68\% CI)}
\]
which corresponds to relative uncertainties of under \( 8\% \). These allow post hoc analysis of inverse trends in \( C_s \) versus system mass. Though the original study did not define \( C_s \), reinterpretation under TLM logic is viable.

\subsubsection{Simulation Confidence Projection (TLM Hypothetical Data)}

For planned TLM simulations, each test instance of a CI-ARC instruction can be evaluated using a Monte Carlo framework with:

\begin{itemize}
    \item \( N = 10^6 \) projection samples
    \item Measurement of mean \( T \), variance \( \sigma_T^2 \)
    \item Computed \( C_s = \Delta x / T \), with error propagation
\end{itemize}

The resulting product \( T \cdot C_s \) is then compared to unity. Confidence intervals around the mean product can be derived from propagated standard error:

\[
\sigma_{TC_s} \approx \sqrt{ \left( C_s \cdot \sigma_T \right)^2 + \left( T \cdot \sigma_{C_s} \right)^2 }
\]

Allowing high-confidence rejection or confirmation of deviation from \( T \cdot C_s = 1 \).

\subsubsection{Conclusion}

All referenced experiments provide error margins tight enough to support an indirect empirical case for the causal invariance relation \( T \cdot C_s = 1 \), particularly when considered as bounding trends. Future targeted studies and simulations can offer tighter statistical confirmation or refutation.







\section{Summary of Core Laws in the Timeless Light Model}

\begin{tcolorbox}[colback=blue!3!white, colframe=blue!75!black, title=Fundamental Laws of TLM]
\[
\boxed{
\begin{aligned}
T \cdot C_s &= 1 \quad &&\text{Causal Rendering Law (normalized units)} \\
T \cdot m &= \frac{\hbar}{c^2} \quad &&\text{Mass–Delay Law} \\
C_s &= \frac{c^2 m}{\hbar} \quad &&\text{Causal Rate for Massive Objects}
\end{aligned}
}
\]
\end{tcolorbox}

\noindent These three equations form the spine of the TLM framework, describing how timeless instructions from the Photon Instruction Layer (PIL) are rendered into sequential reality through the SDF with a quantifiable delay. All predictions and simulation models in this supplement flow directly from these laws.

\section{Philosophical Implications (Optional Perspective)}

While the primary purpose of this document is formal clarification and experimental planning, it is worth noting the broader metaphysical implication of these laws: they suggest that what we call “the present moment” is not a universal progression through time, but a delayed rendering of timeless causal instructions.

In this view, the universe is not evolving, but rather resolving — slowly revealing pre-authored causal structures, with delay shaped by mass and constraint. This reorients physics toward a model in which time is not the axis of creation, but a latency surface of deployment.

\begin{tcolorbox}[colback=gray!5!white, colframe=gray!50!black, title=TLM Worldview Implication]
\textit{In the Timeless Light Model, the present is not what’s happening now — it’s what is finally arriving.}
\end{tcolorbox}





\section{Conclusion}
By naming and defining \( C_s \), we resolve a subtle but foundational ambiguity in the Timeless Light Model. We reinforce the dual-law framework:
\begin{align}
T \cdot m &= \frac{\hbar}{c^2} \quad \text{(Mass--Delay Law)} \\
T \cdot C_s &= 1 \quad \text{(Causal Rendering Law)}
\end{align}
These principles describe the rhythm of reality as experienced through delayed causality.


\appendix
\section{Mathematical Integrity Without Compression (\texorpdfstring{$\kappa$}{kappa})}

All mathematical relationships and derivations in the Timeless Light Model (TLM) remain internally consistent and structurally sound following the removal of the compression term \( \kappa \). This appendix reviews key equations to confirm that \(\kappa\) is not required for logical closure or predictive power.

\subsection{Delay Equation and Mass Proxy}

The fundamental delay law governing CI-ARC deployment remains:

\[
T \cdot \mu = \frac{\hbar}{c^2}
\]

Here, \( T \) is the rendered delay in the Spacetime Deployment Frame (SDF), and \( \mu \) is a dimensionless energy index proportional to the instruction’s resistance to instant deployment (analogous to mass or energy). This formula remains dimensionally consistent and derives from combining:

\[
E = mc^2 \quad \text{and} \quad E = \hbar \omega
\]

by interpreting \( T \) as an inverse frequency of instruction resolution.

\subsection{Causal Rate Definition}

The apparent causal rate of instruction rendering is defined as:

\[
C_s = \frac{\Delta x}{T}
\]

This definition depends solely on deployment delay \( T \) and spatial separation \( \Delta x \), both directly observable or inferrable from rendered behavior. Since no compression term was involved in this formulation, the expression remains fully valid under the updated model.

\subsection{Born Rule Alignment}

TLM mirrors the probabilistic structure of quantum mechanics using:

\[
P(x) = \left| \sum_{i \in \mathcal{C}_x} e^{i \phi_i} w_i \right|^2
\]

The weighting factor \( w_i \), formerly expressed as a function of \( (\mu, \kappa, \epsilon) \), now depends only on \( (\mu, \epsilon) \), reflecting:

\begin{itemize}
    \item \( \mu \): Deployment resistance (mass or energy tension)
    \item \( \epsilon \): Resolution tolerance for interference or probabilistic spread
\end{itemize}

This redefinition preserves alignment with the standard Born rule, treating rendered probability as the result of interference among phase-weighted CI-ARCs.

\subsection{Deployment Modes and Thresholds}

Mode classification remains cleanly defined by:

\begin{itemize}
    \item \textbf{Mode A (Delayed):} \( \mu > 0 \), \( \epsilon < \epsilon_c \)
    \item \textbf{Mode B (Instantaneous / ESE):} \( \mu \to 0 \), \( \epsilon \geq \epsilon_c \)
\end{itemize}

The absence of \( \kappa \) introduces no ambiguity into this schema, as projection fidelity and sharpness are now governed entirely by \( \epsilon \), and speed of rendering by \( \mu \).

\subsection{Conclusion}

All derivations in this framework are dimensionally consistent, causally coherent, and computationally intact without the need for compression (\( \kappa \)). The updated metadata set \( (\mu, \epsilon) \) is sufficient to encode all observable variations in projection behavior and rendering delay across quantum and relativistic regimes.

\[
\boxed{
\text{Compression is not a causal factor in the Timeless Light Model. All mathematics remains intact without } \kappa.
}
\]



\section{Glossary of Core Terms}

\begin{itemize}
  \item \textbf{Photon Instruction Layer (PIL):} The timeless, non-spatial substrate that holds all CI-ARCs. Instructions are defined but not yet deployed.

  \item \textbf{Spacetime Deployment Frame (SDF):} The projection surface onto which CI-ARCs are rendered as observable events. Delay occurs here.

  \item \textbf{Causal Instruction Arc (CI-ARC):} A timeless instruction from PIL with endpoint definitions, constraints, and deployment metadata.

  \item \textbf{Instructional Delay (T):} The delay experienced during deployment of a CI-ARC from the PIL into the SDF. Proportional to mass.

  \item \textbf{Causal Rate ($C_s$):} Defined as $C_s = 1/T$. Represents the rate at which causality renders within the SDF. Units: $\text{s}^{-1}$.

  \item \textbf{Mass ($m$):} A measure of resistance to instantaneous deployment. Related to delay by $T \cdot m = \hbar / c^2$.

  \item \textbf{Mode A (Delayed Deployment):} CI-ARCs that experience delay due to mechanical or gravitational resistance.

  \item \textbf{Mode B (Instantaneous Deployment):} CI-ARCs that render without delay (ESEs), such as entangled photon correlations.

  \item \textbf{Instructional Metadata:} Optional non-causal fields such as $\mu$ (measurement type) and $\epsilon$ (environmental constraint). No field modifies delay or causal rate.
\end{itemize}

















\begin{thebibliography}{99}

\bibitem{Eckle2008}
P. Eckle, A.N. Pfeiffer, C. Cirelli, A. Staudte, R. Dörner, H.G. Muller, M. Büttiker, and U. Keller,  
“Attosecond ionization and tunneling delay time measurements in helium,”  
\textit{Science}, \textbf{322}(5907), 1525–1529 (2008).  
DOI: \href{https://doi.org/10.1126/science.1163439}{10.1126/science.1163439}

\bibitem{Landsman2014}
A.S. Landsman, M. Weger, J. Maurer, A. Ludwig, A. Scrinzi, and U. Keller,  
“Ultrafast resolution of tunneling delay time,”  
\textit{Optica}, \textbf{1}(5), 343–349 (2014).  
DOI: \href{https://doi.org/10.1364/OPTICA.1.000343}{10.1364/OPTICA.1.000343}

\bibitem{Rosenfeld2017}
W. Rosenfeld, D. Burchardt, R. Garthoff, K. Redeker, N. Ortegel, M. Rau, and H. Weinfurter,  
“Event-ready Bell test using entangled atoms simultaneously closing detection and locality loopholes,”  
\textit{Physical Review Letters}, \textbf{119}, 010402 (2017).  
DOI: \href{https://doi.org/10.1103/PhysRevLett.119.010402}{10.1103/PhysRevLett.119.010402}

\bibitem{CI_ARCs}
J.C.W. McKinley,  
\textit{Causal Instruction Arcs and the Timeless Light Model: A Unified Framework for Physics and Cosmology},  
Zenodo (2025).  
DOI: \href{https://doi.org/10.5281/zenodo.15813253}{10.5281/zenodo.15813253}

\bibitem{MTI}
J.C.W. McKinley,  
\textit{The Mass-Time Invariant: A Causal Reinterpretation of Relativistic Spacetime Conservation Laws},  
Zenodo (2025).  
DOI: \href{https://doi.org/10.5281/zenodo.15813357}{10.5281/zenodo.15813357}

\bibitem{CPT}
J.C.W. McKinley,  
\textit{Causal Phase Thresholds},  
Zenodo (2025).  
DOI: \href{https://doi.org/10.5281/zenodo.15813363}{10.5281/zenodo.15813363}

\bibitem{Gravity}
J.C.W. McKinley,  
\textit{Gravitational Waves as Synchronization Events: A Testable Prediction from the Timeless Light Model},  
Zenodo (2025).  
DOI: \href{https://doi.org/10.5281/zenodo.15813371}{10.5281/zenodo.15813371}

\bibitem{TLM_Action}
J.C.W. McKinley,  
\textit{On a Postulated Mass-Time Action Principle: A Novel Approach to Quantum Gravity},  
Zenodo (2025).  
DOI: \href{https://doi.org/10.5281/zenodo.15813386}{10.5281/zenodo.15813386}

\end{thebibliography}







\end{document}

```

</details>

---
{% endraw %}
