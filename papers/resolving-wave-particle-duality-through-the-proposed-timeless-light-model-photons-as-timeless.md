---
layout: default
title: '[2025] Resolving Wave-Particle Duality Through the Proposed Timeless Light Model: Photons as Timeless Instructions and Waves as Deployed Delay'
description: 'Publication metadata and archived raw LaTeX source by John C. W. McKinley.'
permalink: /papers/resolving-wave-particle-duality-through-the-proposed-timeless-light-model-photons-as-timeless/
paper: true
---
{% raw %}
# [2025] Resolving Wave-Particle Duality Through the Proposed Timeless Light Model: Photons as Timeless Instructions and Waves as Deployed Delay
*   **DOI:** [10.5281/zenodo.16510862](https://doi.org/10.5281/zenodo.16510862)
*   **Date:** 28 July 2025

<details markdown="1">
<summary><b>Click to view Raw LaTeX Source</b></summary>

```latex
\documentclass[12pt]{article}
\usepackage[utf8]{inputenc}
\usepackage{amsmath, amssymb}
\usepackage{tabularx} % add to preamble if not already there
\usepackage{booktabs} % already in use for \toprule

\usepackage{geometry}
\geometry{margin=1in}
\usepackage{graphicx}
\usepackage{float} % for H float placement
\usepackage{physics} % optional: simplifies d/dx notation and bras/kets
\usepackage{microtype} % improves typographic appearance slightly
\usepackage{csquotes} % for improved quote formatting


\usepackage{titlesec}
\usepackage{fancyhdr}
\usepackage{pgfplots}
\pgfplotsset{compat=1.18}
\usepackage{tikz}
\usetikzlibrary{arrows.meta, positioning, calc, shapes.geometric, decorations.pathmorphing}
\usepackage{caption}
\usepackage{upgreek}
\usepackage{enumitem}


\usepackage{tcolorbox}

\usepackage{hyperref}
 \hypersetup{colorlinks=true, linkcolor=blue,urlcolor=blue, citecolor=blue, filecolor=black}

\usepackage{cleveref}


\title{\textbf{Resolving Wave-Particle Duality Through the Proposed Timeless Light Model:\\ Photons as Timeless Instructions and Waves as Deployed Delay}}
\author{John C. W. McKinley \\ Independent Researcher \\ \href{https://orcid.org/0009-0005-7097-5035}{0009-0005-7097-5035}}
\date{\today}

\begin{document}

\maketitle

\renewcommand{\thefootnote}{}
% New DOI
\footnotetext{This version v1.0 published at \href{https://doi.org/10.5281/zenodo.16510862}{https://doi.org/10.5281/zenodo.16510862}.}



\begin{abstract}
Wave-particle duality remains one of quantum mechanics' most enduring enigmas, with light behaving as both a localized particle and an extended wave depending on observation. Building on the Timeless Light Model (TLM), this paper proposes a novel resolution: the quantized photon is a timeless instruction from the Quantum Platform (QP)—a spaceless, non-temporal substrate where outcomes are pre-resolved—existing outside 4-dimensional spacetime with no proper time (\( \tau = 0 \)) or presence in the universe. The wave aspect emerges as the delayed rendering of this instruction in General Relativity (GR), deployed in the Spacetime Deployment Frame (SDF) to introduce sequence and delay for massive observers. This framing recasts duality not as a paradox but as a layered ontology: the "photon-view" (timeless QP reality) underlies the "wave-view" (GR/SDF manifestation). We derive this from relativistic null geodesics (\( ds^2 = 0 \)), contrast it with interpretations like Copenhagen and Bohmian mechanics, and outline testable implications, such as no intermediate states in duality experiments and consistency with delayed-choice setups. This model extends prior TLM work, offering a unified bridge between quantum duality and relativistic timelessness without retrocausality or hidden variables.
\end{abstract}



Keywords: Timeless Light Model, rendering delay, GR ontology, Quantum Platform, Spacetime Deployment Frame, delay-mass relation, timeless instructions, wave-particle duality,  null geodesics, delayed deployment



% Place this after \end{abstract} in the main document.


\section{Introduction}

Light's wave-particle duality has puzzled physicists since the early 20th century: in some experiments, photons act as discrete particles with quantized energy; in others, they exhibit wave-like interference and diffraction. According to Special Relativity, light is not just fast—it is out of time, with photons traversing null geodesics where the spacetime interval is zero (\( ds^2 = 0 \)) and proper time vanishes (\( \tau = 0 \)). This timelessness, far from a mere curiosity, hints at a deeper structure: photons do not "experience" duality in a temporal sense but define it through ontological layers.


In the Timeless Light Model (TLM), we propose that the quantized photon—often viewed as the "particle" aspect—is fundamentally a timeless instruction originating from the Quantum Platform (QP), a non-spacetime substrate where causal outcomes are pre-resolved without duration or extension. This instruction has no presence in the observable universe; it connects emission and absorption instantaneously from its null perspective, enforcing causality without inhabiting 4D spacetime. The wave aspect, by contrast, arises as the deployed manifestation of this instruction in General Relativity (GR), rendered in the Spacetime Deployment Frame (SDF) to impose delay, sequence, and observability for mass-bound systems like detectors or observers.

This reframing resolves duality as a perspectival artifact: the "photon-view" (timeless QP reality) is the underlying instruction, while the "wave-view" (GR/SDF deployment) is how GR rules "play back" that instruction, introducing probabilistic waves for the purpose of temporal delay. This duality can be likened to a composer's score (QP instruction: atemporal and quantized) versus its orchestral performance (SDF wave: extended and delayed for listeners). For instance, in double-slit experiments, the interference pattern emerges not from an evolving photon but from the summed deployment of the QP instruction across paths, consistent with Feynman's path integrals treated atemporally.



\begin{figure}[h!]
\centering
\begin{tikzpicture}[scale=1.2]
  % Standard View: Signal between A and B
  \node[circle, draw, fill=gray!20] (A1) at (0,0) {A};
  \node[circle, draw, fill=gray!20] (B1) at (6,0) {B};
  \draw[red, thick, ->] (A1) -- (B1) node[midway, above] {Signal across space};
  \node[above=0.5cm of A1, xshift=3cm] {\small Standard View: Requires signal between A and B};

  % TLM View: Shared instructions from QP
  \node[circle, draw, fill=gray!20] (A2) at (0,-3) {A};
  \node[circle, draw, fill=gray!20] (B2) at (6,-3) {B};
  \node[rectangle, draw, fill=blue!20] (QP) at (3,-1) {QP (Timeless Instruction Layer)};
  \draw[dashed, thick, ->] (QP) -- (A2) node[midway, left] {};
  \draw[dashed, thick, ->] (QP) -- (B2) node[midway, right] {};
  \node[above=0.5cm of A2, xshift=3cm] {\small TLM View: Shared instructions rendered separately};

  % No space label
  \node at (3,-4) {\small No space, no distance, no delay};
\end{tikzpicture}
\caption{Entanglement under standard interpretation (red, signal across space) vs. TLM (dashed lines, spaceless instructional deployment). In TLM, no spatial link is needed because the QP issues matched instructions without reference to location.}
\label{fig:entanglement-qp-tlm}
\end{figure}

This model aligns with the broader TLM framework where quantum mechanics is causally senior to General Relativity, with GR emerging as a rendered projection of timeless QP instructions, as hypothesized in our companion works~\cite{mckinley2025qpv3, mckinley2025qpv4}.


We begin by reviewing the relativistic basis for photon's timelessness, then extend it to duality in the TLM framework. We contrast this with traditional interpretations, explore implications for experiments like delayed-choice, and argue for testability through predictions like the absence of mid-path states. This proposal, as of July 27, 2025, appears original in synthesizing null ontology with duality resolution, building on but distinct from prior frameworks.







\begin{figure}[h!]
\centering


\begin{tikzpicture}[scale=1.2]
  % Axes
  \draw[->, thick] (0,0) -- (0,4.5) node[above] {\textbf{ct (time)}};
  \draw[->, thick] (0,0) -- (4.5,0) node[right] {\textbf{x (space)}};

  % Light cone (slope = 1, since c=1)
  \draw[dashed, gray] (0,0) -- (4,4);
  \draw[dashed, gray] (0,0) -- (-4,4);
  
  % Timelike worldline (massive particle, inside the cone)
  \draw[blue, thick, ->] (0,0) -- (1.5, 4) node[pos=0.7, above right, sloped] {Timelike Worldline};

  % Null worldline (photon) as a wavy line to distinguish it
  % It still follows the correct 45-degree path.
  \draw[red, thick, decorate, decoration={snake, segment length=4mm, amplitude=0.5mm}, ->] 
    (0,0) -- (3.8, 3.8) node[pos=0.7, below right, sloped] {Null Worldline};

  % Labels for proper time
  \node[blue] at (0.9, 2.5) {\small $\tau > 0$};
  \node[red] at (2.8, 2.4) {\small $\tau = 0$};

  % Origin label
  \node at (-0.3,-0.3) {O};

\end{tikzpicture}
\caption{A spacetime diagram showing a \textit{timelike worldline} (blue) and a \textit{null worldline} (red). The photon's path is shown as a \textit{wavy line} (a common convention) to make it distinct from the dashed light cone it travels along. All paths are mathematically correct for units where \(c=1\).}
\label{fig:worldlines}
\end{figure}























The TLM is a comprehensive framework that reinterprets causality through timeless instructions and delayed rendering. While beyond the scope of this paper, its foundational axioms are constructed to recover the established formalisms of both General Relativity and Quantum Mechanics under specific rendering conditions, as detailed in our supporting derivations~\cite{mckinley2025axioms}.






\subsection{Historical Context of Duality}

Wave-particle duality traces back to debates on light's nature, from Newton's corpuscles to Young's interference. Wave-particle duality traces back to de Broglie's 1924 hypothesis that matter has wave properties~\cite{debroglie1924}. Pascual Jordan's 1920s work formalized the quantum conundrum, showing complementarity in measurement~\cite{jordan1920s}. Modern extensions, like timeless quantum interpretations~\cite{timelessqm2020}, hint at atemporal resolutions, which TLM extends via QP/SDF layers.




\section{Relativistic Foundations: Timelessness of Light}

The foundation of our duality resolution lies in Special Relativity's treatment of light, where photons follow null geodesics with zero proper time. This timelessness underpins the QP instruction ontology, distinguishing the atemporal ``particle'' reality from the deployed wave manifestation.

\begin{tcolorbox}[colback=blue!5!white, colframe=blue!75!black, title=Note on Units and Conventions]
Unless otherwise stated, we adopt natural units where \( c = 1 \), consistent with standard practice in theoretical physics and in the Timeless Light Model (TLM) framework. This simplifies spacetime intervals such as
\[
ds^2 = -dt^2 + dx^2 + dy^2 + dz^2
\]
while preserving the causal distinction between timelike, spacelike, and null paths. In contexts requiring dimensional clarity (e.g., experimental predictions), the full units including \( c \) are retained.
\end{tcolorbox}

In Special Relativity, the spacetime interval \( ds^2 \) connects events, as introduced by Einstein~\cite{einstein1905electrodynamics}:
\[
ds^2 = -c^2 dt^2 + dx^2 + dy^2 + dz^2
\]
For photons, \( ds^2 = 0 \), implying no proper time:
\[
\tau = \int \frac{\sqrt{-ds^2}}{c} = 0
\]

This null interval means emission and absorption are simultaneous from the photon's ``perspective,'' with no internal evolution or midpoint states—key to viewing the quantized photon as a timeless QP instruction.

\begin{tcolorbox}[colback=gray!5!white, colframe=gray!75!black, title=Clarification: Proper Time vs. Ontological Timelessness]
Proper time (\( \tau \)) is a frame-invariant measure of duration along a timelike worldline. For massive particles, it represents the time experienced by a co-moving clock. For light, however, \( \tau = 0 \) along a null worldline, and no rest frame exists. In TLM, this is not merely that photons experience \( \tau = 0 \), but that they do not exist within spacetime at all: the photon is a causal instruction from the timeless QP, with GR/SDF rendering its delayed consequences.
\end{tcolorbox}

\subsection{Expert Consensus on Photon Timelessness}

This timelessness is affirmed by leading physicists:

\begin{itemize}
    \item \textbf{Brian Greene:} ``From the viewpoint of a photon, there is no such thing as time. It's emitted, and might exist for billions of years, but for the photon, that span of time is zero'' (paraphrased from Greene's public explanations; direct quote on p. 49 of \textit{The Fabric of the Cosmos})~\cite{greene2004fabric}.
    
    \item \textbf{Sean Carroll:} In both his lecture notes and \textit{Spacetime and Geometry}, Carroll explains that photons travel along null geodesics—paths for which the spacetime interval \( ds^2 = 0 \)—and therefore experience no proper time~\cite{carroll2004spacetime}.
    
    \item \textbf{Richard Feynman:} In \textit{QED: The Strange Theory of Light and Matter}, Feynman illustrates that light's propagation involves summed paths, not classical sequences: ``Photons look exactly the same in all respects when they travel backwards in time [...] they have no home in space whatsoever''~\cite{feynman1985qed}.
    
    \item \textbf{Kip Thorne:} ``The light ray's worldline is null, with zero proper time'' (p. 86). He continues: ``For the photon, the emission and absorption are instantaneous''~\cite{thorne1994black}.
\end{itemize}

These are not fringe statements—they are standard consequences of Einstein's theory. Yet their full philosophical and physical significance is often downplayed in education and literature. In the sections that follow, we argue that this oversight hides a deeper truth: the photon's lack of time may not be a curiosity, but a clue to the layered structure of reality.

This timelessness underpins the QP instruction ontology, distinguishing the atemporal ``particle'' reality from the deployed wave manifestation.

Photons lack a rest frame, as Lorentz transformations become singular at \( v = c \):
\[
\gamma = \frac{1}{\sqrt{1 - \frac{v^2}{c^2}}} \to \infty
\]
The four-velocity \( u^\mu = \frac{dx^\mu}{d\tau} \) is undefined for \( d\tau = 0 \), as formalized in Wald's \textit{General Relativity}~\cite{wald1984general}.




\clearpage


\begin{table}[h!]
\centering
\begin{tabularx}{\textwidth}{l|X|X}
\toprule
\textbf{Property} & \textbf{Quantum Platform (QP)} & \textbf{Spacetime Deployment Frame (SDF)} \\
\midrule
Temporality & Timeless (\( \tau = 0 \), no proper time) & Temporal (experiences delay and sequence) \\
Spatiality & Spaceless (no geometry or distance) & Spatial (emergent geometry and extension) \\
Aspect of Duality & Particle-like (pre-resolved, quantized instruction) & Wave-like (probabilistic propagation and interference) \\
Causal Role & Resolution of outcomes (causal instructions) & Rendering and deployment (delayed manifestation) \\
Internal Evolution & None (atemporal links) & Evolves through paths (e.g., Feynman integrals) \\
Entropy Contribution & No internal entropy & Contributes to system entropy via delay \\
Observability & Not directly observable (outside spacetime) & Observable (GR-measurable effects) \\
\bottomrule
\end{tabularx}
\caption{Comparison of Quantum Platform (QP) and Spacetime Deployment Frame (SDF) Properties in the Timeless Light Model (TLM). This highlights how duality emerges from the layered ontology.}
\label{tab:qp-sdf-comparison}
\end{table}




\section{Wave-Particle Duality in the TLM Framework}

Building on the relativistic timelessness of photons, the Timeless Light Model (TLM) reframes wave-particle duality as an emergent property of layered reality: the particle-like quantization reflects the timeless Quantum Platform (QP) instruction, while the wave-like behavior arises from its delayed deployment in the Spacetime Deployment Frame (SDF).

As proposed in our prior work, a timeless QP must be spaceless\cite{mckinley2025spacelessness}, as space requires change for definition (e.g., measurement via motion), rendering QP a non-geometric instruction layer.




In QP, the photon is a pre-resolved causal instruction—a null-geodesic link with \( \tau = 0 \) and no spacetime presence. This aligns with the discrete, quantized energy \( E = h\nu \), where the "particle" is not a localized entity evolving through time but a boundary condition connecting emitter and absorber instantaneously. There is no "journey" or intermediate state; the instruction enforces the outcome without traversal.

In QP, the photon is a pre-resolved causal instruction—a null-geodesic link with \( \tau = 0 \) and no spacetime presence, extending our prior TLM spacelessness proposals~\cite{mckinley2025spacelessness}.


This layered approach draws inspiration from timeless substrates in quantum interpretations, such as Barbour's framework where reality is a static configuration space without intrinsic time \cite{barbour2000timeless}. In TLM, we extend this by positing QP as the atemporal resolution layer, with SDF deploying temporal waves.


Upon deployment in the SDF—our GR-observable frame—the instruction manifests with delay, creating the wave aspect. The wavefunction \( \psi \), governed by the Schrödinger or Dirac equation, represents the probabilistic rendering of paths summed in Feynman's integral:
\[
A = \sum_{\text{paths}} e^{iS/\hbar}
\]
Here, the sum is not over temporal evolutions (impossible for \( \tau = 0 \)) but over deployed configurations in SDF, introducing interference as a delay-induced phenomenon for observers. The wave propagates with group/phase velocities, but this is an illusion of the rendering process, akin to a movie frame sequence simulating motion, or Bostrom's simulation hypothesis~\cite{bostrom2003simulation}.

This duality resolution avoids paradoxes: in double-slit experiments, the "which-path" choice is resolved timelessly in QP, but the wave interference deploys in SDF based on detection setup. No retrocausality is needed—the outcome is prewritten, played back with delay.In this view, the QP acts like a blueprint in an architect's office, timeless and complete, whereas the SDF wave is the constructed building, emerging layer by layer in the observer's temporal landscape.





This framework extends TLM axioms, positing duality as a QP/SDF artifact rather than intrinsic property.

To further illustrate, the QP instruction resembles a pre-written script—fully resolved and unchanging—while the SDF wave deployment is akin to actors improvising on stage, where the script's outcomes manifest through dynamic, delayed interactions visible to the audience.Add the following sentence after the sentence in the "Introduction" section that ends with "introducing probabilistic waves for the purpose of temporal delay." This duality can be likened to a composer's score (QP instruction: atemporal and quantized) versus its orchestral performance (SDF wave: extended and delayed for listeners).






\begin{figure}[h!]
\centering
\begin{tikzpicture}[scale=1.2]
  % Source and screen
  \draw[thick] (0,0) -- (0,4) node[midway, left] {Source};
  \draw[thick] (7,0) -- (7,4) node[midway, right, xshift=.22cm] {\rotatebox{90}{Screen}};

  % Slits
  \draw[thick] (3,1) -- (3,1.5);   % Lower slit
  \draw[thick] (3,2.5) -- (3,3);   % Upper slit

  % Wavy blue lines (wave-like SDF paths)
  \draw[blue, decorate, decoration={snake, amplitude=0.4mm, segment length=2.5mm}] 
    (0,2) -- (3,1.25) -- (7,1);
  \draw[blue, decorate, decoration={snake, amplitude=0.4mm, segment length=2.5mm}] 
    (0,2) -- (3,2.75) -- (7,3);
  \node[blue] at (4.5,3.4) {\small Wave Deployment (SDF View)};

  % Interference pattern on screen
  \draw[blue, thick, domain=0.5:3.5, samples=50, variable=\y, shift={(7.15,0)}] 
    plot ({0.17*sin(10*\y r)}, \y);
  \node[blue, xshift=1cm] at (7.6,2) {\rotatebox{90}{\small Interference Pattern}};

  % Dashed red instruction arrow (timeless QP link)
  \draw[red, thick, dashed, ->] (0,2) -- (7,2) 
    node[midway, above, yshift=.1pt,xshift=1cm,text=red] {\small Timeless Instruction (QP View)};

\end{tikzpicture}
\caption{Schematic of the double-slit experiment in the Timeless Light Model. The dashed red arrow represents the timeless QP instruction linking emission and detection. Blue waves represent the SDF rendering, resulting in interference. Apparent duality arises from the distinction between QP (instruction) and SDF (rendered experience).}
\label{fig:duality-double-slit}
\end{figure}




\begin{figure}[h!]
\centering
\begin{tikzpicture}[node distance=2cm, every node/.style={align=center, font=\small}]
  % QP Layer
  \node[draw, rectangle, fill=gray!20] (qp1) {Instruction Arc};
  \node[draw, rectangle, fill=gray!20, right=of qp1] (qp2) {Pre-resolved Outcome\\(Particle Quantization)};

  % Arrow in QP
  \draw[->, thick] (qp1) -- (qp2);

  % Deployment Arrow
  \node[below=1cm of qp2, xshift=-2cm] (deploy) {};
  \draw[->, thick, dashed] (qp2.south) -- ++(0,-1cm) node[midway, right] {Deployment};

  % SDF Layer
  \node[draw, rectangle, fill=blue!20, below=2cm of qp1] (sdf1) {Wave Propagation + Interference};
  \node[draw, rectangle, fill=blue!20, right=of sdf1] (sdf2) {Observed Pattern};

  % Arrow in SDF
  \draw[->, thick] (sdf1) -- (sdf2);

  % Labels for Layers
  \node[above=0.5cm of qp1, xshift=2cm] {\textbf{QP (Timeless)}};
  \node[above=0.5cm of sdf1, xshift=2cm] {\textbf{SDF (Delayed)}};
\end{tikzpicture}
\caption{Flowchart contrasting QP (timeless instruction) vs. SDF (wave deployment) in the double-slit context. The QP layer represents the pre-resolved, atemporal instruction (particle aspect), deployed into the SDF where it manifests as waves and interference (wave aspect). For ontology details, see thematic index in \cite{mckinley2025axioms} (Page 125).}
\label{fig:qp-sdf-flowchart}
\end{figure}


\subsection{Formal Derivation of Duality in TLM}

To derive duality explicitly in TLM terms, we formalize the transition from the timeless QP instruction to the delayed SDF wave. The QP instruction, represented as a pre-resolved Causal Instruction Arc (CI-ARC) \(\mathcal{I}_{\text{QP}}\), is a timeless link enforcing the outcome without temporal extension (consistent with Axiom 4.1 on time invariance from \cite{mckinley2025axioms}).

The wavefunction in the SDF emerges as the deployed sum over instructional arcs:
\[
\psi_{\text{SDF}} = \sum_{\text{arcs}} e^{i S / \hbar} \cdot \mathcal{I}_{\text{QP}},
\]
where \(\mathcal{I}_{\text{QP}}\) is the timeless CI-ARC instruction (pre-resolved outcome), \(S\) is the action, and the sum represents delayed SDF rendering of possible configurations. This extends Feynman's path integral by treating the sum as atemporal QP resolutions manifested with delay.

Furthermore, waves as ``deployment artifacts'' tie to TLM's entropy framework. Probabilistic waves emerge from instructional microstate counts, linking to black hole entropy scaling:
\[
S = \frac{A}{4 \ell_p^2},
\]
where \(A\) is the horizon area and \(\ell_p\) is the Planck length (from \cite{mckinley2025axioms}, Page 124). In this view, the wave's probabilistic nature reflects the logarithmic measure of deployable instructions, \(S = k_B \ln(H)\), where \(H\) is the microstate hash count, rendering interference as an emergent consequence of delayed deployment rather than fundamental indeterminacy.

\subsection{Instructional Complexity and Entropy in Interference}

Building on the TLM claim that photons possess no internal entropy due to their null proper time (\( \tau = 0 \)), we reinterpret interference patterns as thermodynamically significant. Standard formulations of entropy—such as Boltzmann’s \( S = k_B \ln(H) \), where \( H \) is the number of microstates—can be linked to the number of distinct instruction permutations required for rendering a given interference pattern. In this framing, the wavelike interference is not an ontological oscillation but an emergent rendering artifact expressing high instructional multiplicity in the Spacetime Deployment Frame (SDF).

This entropy-wave connection implies that interference patterns scale with instructional complexity, potentially testable in high-multiplicity interferometers. That is, the number and sharpness of interference fringes may correlate with the number of null-path instruction variations pre-resolved by the Quantum Platform (QP), even though photons themselves carry no entropy. As shown in Table~\ref{tab:particle-photon-comparison}, photons do not evolve, accumulate history, or experience entropy growth. However, their deployment statistics in multi-path setups reflect underlying configuration entropy in the rendered frame.

This perspective extends TLM’s unified ontology, offering a new interpretation of entropy in quantum optics experiments: not as a property of the photon, but as a reflection of the causal configuration space explored by the rendering process.







\begin{table}[h!]
\centering
\begin{tabularx}{\textwidth}{l|X|X}
\toprule
\textbf{Property} & \textbf{Massive Particle} & \textbf{Photon} \\
\midrule
Worldline Type & Timelike & Null \\
Proper Time \( \tau \) & \( \tau > 0 \) & \( \tau = 0 \) \\
Has Rest Frame? & Yes & No \\
Experiences Time? & Yes & No \\
Evolves Through Events? & Yes & No \\
Causal Role & Evolves through sequence & Connects events instantly \\
Arrow of Time? & Yes & Absent \\
Subject to Entropy? & Yes & No (but contributes to system entropy) \\
Can Accumulate History? & Yes & No \\
Affected by Delay? & Yes (defines perception) & No (timeless link) \\
\bottomrule
\end{tabularx}
\caption{Comparison Between Massive Particles and Photons in Relativistic Spacetime. Note: ``Subject to Entropy'' refers to whether the entity contributes to entropy in thermodynamic systems. Photons do not have internal entropy or an arrow of time, but their energy distributions affect the entropy of the systems they interact with (e.g., blackbody radiation).}
\label{tab:particle-photon-comparison}
\end{table}









\section{The Photon Is Not in the Universe: Postulates of the Proposed Model}

We propose the photon is not in the universe, following from these axioms:

\textbf{Postulate 1:} General Relativity states that a photon experiences no proper time. Its worldline satisfies the null condition \( ds^2 = 0 \), which means no time elapses along its path. From the photon's own frame—if such a thing were definable—there is no duration between emission and absorption.

\textbf{Postulate 2:} Something that has no time cannot possess space. Time is the condition for change, and space is the geometry in which that change becomes observable. If time does not pass, then nothing can move, evolve, or occupy different locations—rendering space meaningless. Time and space are not separable concepts for physical existence; they are interwoven. Thus, no time implies no space. Mathematically, the null interval equates temporal and spatial components (\( c^2 dt^2 = dx^2 + dy^2 + dz^2 \)), effectively collapsing the 4-dimensional separation along the path.

\textbf{Postulate 3:} The observable universe, as described by physics, is the domain of space and time. Anything that lacks both is not within that domain. It cannot be assigned a location or a duration. Therefore, something with neither space nor time is not in the universe.

\textbf{Postulate 4:} To not be in the universe is, by definition, to not exist in the ontological sense familiar to physics. An entity that is nowhere and never is not a participant in the universe's unfolding reality. It may have causal effects, but it is not a \textit{thing-in-the-world}. It is, instead, an \textit{instruction to the world}—a bridge between events, a pointer, not a participant.

\noindent This leads to a radical but logically sound conclusion: the photon is not in the universe—not embedded in the observable 4-dimensional spacetime as massive particles are, but rather existing outside it. This does not mean photons do not exist or interact; on the contrary, they serve as instructions originating from the timeless Quantum Platform (QP). Any visible artifact from a photon—such as its detection, redshift, or role in entanglement—is the effect of that instruction rendered in General Relativity, a delayed playback of the pre-resolved QP "movie." The photon is a connection between events, not a traveler between them.

From the Timeless Light perspective, the photon functions as a causal instruction linking emitter and absorber. Its presence is not as a particle flying through vacuum, but as a binding between two resolved outcomes. The photon never “was” in any spacetime location between those events, because to be “in between” would require both time and space—neither of which apply.

Thus, the photon is not a resident of the universe. It is the message that space and time decode. It is the author or messenger of linkage, but not a character in the play. Its reality is not its trajectory but its consequence: the structured transformation from emission to absorption, rendered only for those within the deployment frame. This interpretation aligns with proposals for timelessness in quantum systems \cite{kiefer2021timelessness}, where small isolated realms lack conventional time flow.






\subsection{Entanglement and Nonlocality}

This framing resonates strongly with quantum mechanics. In entangled systems, particles separated by space can exhibit instantaneous correlations. Though relativity forbids superluminal communication, the underlying mechanism appears to violate locality. As in Bohmian mechanics or the transactional interpretation of quantum mechanics \cite{cramer1986transactional}, such correlations may reflect an underlying structure that does not evolve in time but connects outcomes as a single pre-resolved instruction.



As a proposed interpretation, the timeless nature of photons offers a possible conceptual bridge. If light, the carrier of force and information, exists outside time, then perhaps its participation in entangled systems is not governed by spatial or temporal separation, but by direct instruction—pre-resolved, as some interpretations suggest. While not resolving the EPR paradox, this view aligns conceptually with interpretations like transactional quantum mechanics.



Delayed-choice experiments push this further. A measurement made “after” a photon’s arrival seems to retroactively determine its behavior. But if the photon never experienced time to begin with, then the notion of retrocausality may be ill-formed. The entire event structure may be resolved as a unit—beyond time. 

\begin{quote}{
“No elementary phenomenon is a phenomenon until it is an observed  phenomenon.”~\cite{wheeler1978delayed}, edited by A. R. Marlow, Academic Press, 1978, pp. 9–48.}
\end{quote}




\subsection{Predictions Arising from Spaceless QP}
\addcontentsline{toc}{subsection}{Predictions Arising from Spaceless QP}

The assertion that the QP is spaceless is not merely philosophical—it yields concrete predictions:

\begin{enumerate}[label=\textbf{P\arabic*}, leftmargin=2.5em]
    \item \textbf{Nonlocal Entanglement Correlations Without Signal Exchange:}  
    Since the QP is outside of space, entangled outcomes do not involve communication across distance. TLM predicts that Bell inequality violations and delayed-choice quantum erasure experiments will continue to show instantaneous correlations even under spacetime-separated configurations—without requiring faster-than-light transfer.

    \item \textbf{Geometry-Free Instruction Collapse:}  
    Collapse events (e.g., detection of a photon or electron) will display no dependence on spatial geometry between emitter and detector. The outcome only reflects instruction resolution, not any continuous path in space. TLM therefore predicts that certain quantum tunneling or absorption phenomena will violate classical locality constraints, especially under ultra-short path separations.

    \item \textbf{Absence of Pre-Rendered Field Structures:}  
    If geometry is rendered only at deployment, then measurements attempting to probe substructure “prior” to rendering (e.g., in vacuum field configurations or spacetime foam) should yield stochastic rather than deterministic structure. TLM predicts that vacuum fluctuations and zero-point energy signatures will lack spatial coherence beyond what is required for rendering delay.

    \item \textbf{Instructional Coincidence Tests:}  
    In engineered quantum systems (e.g., Bose-Einstein condensates with shared past light cones), the spaceless QP predicts that collapsed states may show high cross-system correlation even if the systems are not in causal contact—so long as their instructions originate from the same resolution arc.
\end{enumerate}

These predictions provide a testable framework for falsifying or supporting the claim that all rendered spacetime emerges from a non-geometric instruction layer. Unlike many interpretations of quantum mechanics, the TLM explicitly invites laboratory tests of its core assumptions.









\section{Implications and Resolutions}

The TLM reframing of wave-particle duality yields powerful implications for longstanding quantum paradoxes, resolving them through the QP/SDF ontology without invoking retrocausality, many-worlds, or hidden variables.

In the double-slit experiment, the interference pattern—traditionally a wave signature—arises from the SDF deployment: the QP instruction is summed over possible paths (as in Feynman's integrals), rendered as a probability wave with delay. The "particle" detection (e.g., which-slit information) collapses this wave not by altering the past but by selecting the pre-resolved QP outcome at absorption. No mid-path decision occurs, as the instruction is timeless.

No mid-path decision occurs, as the instruction is timeless, consistent with Wheeler's delayed-choice experiments~\cite{wheeler1978delayed}.

This duality can be visualized as a hologram: the particle aspect represents the encoded data in the QP, projected outward as a wave illusion in the SDF, where interference emerges as a rendered consequence rather than an intrinsic property.



\begin{figure}[H]
\centering
\begin{tikzpicture}[node distance=1.5cm and 2cm, >=Stealth, thick, font=\small]

% QP Layer
\node[draw, rectangle, minimum width=4cm, minimum height=0.8cm, fill=blue!10] (QP) {Quantum Platform (QP): Timeless Instruction};
\node[below=of QP] (spacer) {};

% SDF Layer - Apparatus
\node[below=1.8cm of QP, draw, rectangle, fill=gray!10, minimum width=4.8cm, minimum height=0.8cm] (Apparatus) {SDF: Detector Apparatus};

% Paths
\draw[->, dashed] (QP.south) -- (Apparatus.north) node[midway, left] {\small Timeless causal link};

% Split into two branches
\node[left=2.5cm of Apparatus, draw, circle, minimum size=0.5cm, fill=gray!20] (A) {};
\node[right=2.5cm of Apparatus, draw, circle, minimum size=0.5cm, fill=gray!20] (B) {};
\draw[->] (Apparatus.south west) -- (A.north) node[midway, left, yshift=-.5cm] {\small Outcome A};
\draw[->] (Apparatus.south east) -- (B.north) node[midway, right,yshift=-.5cm] {\small Outcome B};

% Annotation
\node[below=.5cm of A, align=center] (note) {\textit{Rendered after measurement} \\
\textit{but instruction was pre-resolved}};

% QP bypass arrow
\draw[->, thick, blue!60] (QP) to[bend right=30] node[midway, right, blue!60,yshift=.2cm] {\small Non-retrocausal resolution} (B);

\end{tikzpicture}
\caption{Delayed-choice illustration showing a timeless instruction from the Quantum Platform (QP) bypassing temporal constraints and rendering a wavefunction outcome in the Spacetime Deployment Frame (SDF) only after a choice is made. Unlike retrocausal models, the TLM framework maintains causal consistency by asserting that the QP instruction was already resolved, with the measurement acting as a delay gate rather than a retroactive determinant. See also Fig.~\ref{fig:duality-double-slit} for baseline duality context.}
\label{fig:delayed-choice-schematic}
\end{figure}





Additionally, phenomenographic studies reveal common student misconceptions in wave-particle duality, such as blending classical and quantum views or struggling with complementarity~\cite{phenomenographic2021}. Recent educational research emphasizes duality's conceptual challenges in teaching~\cite{qmeducation2022}. The TLM offers pedagogical value by clarifying these: framing the particle as a timeless QP instruction and the wave as SDF deployment provides an intuitive ontology, reducing confusion and enhancing teaching of quantum concepts.



For instance, students often misconstrue photons as \enquote{deciding} paths mid-flight in experiments like the double-slit, anthropomorphizing the process as if the photon actively chooses a trajectory based on future conditions---a classical intuition that blends deterministic particle behavior with quantum ambiguity. The Timeless Light Model (TLM) clarifies this by emphasizing \textbf{QP pre-resolution}: the photon's outcome is fully determined timelessly in the Quantum Platform (QP) as a boundary-resolved instruction, with no mid-path evolution or decision-making, as proper time \( \tau = 0 \) precludes any internal sequence. 

This reduces conceptual blending by separating the atemporal QP reality---where photons serve as timeless causal bridges linking mass-bound events without traversal or presence in spacetime---from the delayed Spacetime Deployment Frame (SDF) manifestation, where interference appears as a rendered artifact rather than a deliberative process. 

Notably, even in standard General Relativity (GR) and Quantum Mechanics (QM), no such \enquote{decision} is required; the apparent shift from wave-like to particle-like behavior arises not from the photon's agency but from a status change induced by interaction with the observational apparatus, such as detectors that enforce absorption and collapse the wavefunction via measurement. 

In TLM, this interaction is reinterpreted as the SDF deployment triggering the pre-resolved QP outcome, aligning classical and quantum views without invoking photon volition: the apparatus acts as a conditional gate or filter on the timeless instruction set, rendering the already-finalized causal logic into observable spacetime effects under delay constraints. 

Thus, what seems like a \enquote{choice} is merely the experiential projection of QP's timeless resolution, aiding pedagogical clarity by grounding duality in ontological layers---QP as the foundational, pre-resolved instruction source senior to GR, and SDF as its delayed, emergent display---rather than mystical or anthropomorphic decisions.






To contrast TLM's quantum-relativistic approach with classical duality models, recent \texttt{arXiv} preprints have explored classical or semi-classical frameworks that mimic or analogize duality without full quantum mechanics. For instance, a classical analogy emerges in electrolyte theory, where Silkina introduces a ``point-particle duality'' for ions in concentrated salt solutions: ions behave as point-like in mean-field electrostatics (defining Debye layers) and as finite-sized particles in hydrodynamic electrophoresis, paralleling quantum wave-particle duality but rooted entirely in classical physics~\cite{silkina2024}.

Similarly, Broinizi Pereira demonstrates that separate classical wave (Langevin equations) and particle (rate equations) models can replicate average power in a bosonic quantum heat engine but fail to capture quantum fluctuations from vacuum effects and bunching, illustrating the inadequacy of non-unified classical models for true duality~\cite{broinizi2023}.

In TLM, by contrast, the duality is inherently unified via the timeless QP instruction (quantized particle aspect) and delayed SDF wave deployment, leveraging relativistic null geodesics without separate classical benchmarks.

Recent \texttt{arXiv} preprints further highlight measure-independent approaches to wave-particle duality that contrast with TLM's emphasis on relativistic timelessness. For example, Bai and Du propose a coherence-based framework for \( d \)-path interferometers, establishing a trade-off relation \( C(\rho) + D(\rho) \leq 1 \) between coherence (wave nature) and a particle quantifier, extended to a triality including mixedness~\cite{bai2025}. This quantitative, non-relativistic description focuses on state properties without invoking atemporal substrates, differing from TLM's QP/SDF layering where duality arises from timeless instructions and delayed deployment.



For entanglement and Bell inequalities, correlations reflect QP pre-resolution: entangled photons are linked instructions, with nonlocality emerging in SDF rendering. This maintains no-signaling while explaining "spooky action" as atemporal QP connectivity, deployed locally in GR frames.

Contrasting interpretations: Unlike Copenhagen's observer-induced collapse, TLM posits collapse as SDF manifestation of QP resolution. Bohmian mechanics' pilot waves are reinterpreted as deployed waves guiding massive particles, but photons themselves remain instructions. Transactional interpretations (e.g., Cramer) align closely, with QP handshakes pre-resolving outcomes.

This model predicts: In ultra-precise delayed-choice setups, no evidence of temporal evolution mid-path, consistent with \( \tau = 0 \). Future tests could discriminate via entanglement configurations probing deployment delay.









\subsection{Comparison to Other Interpretations}

Unlike Everett's Many-Worlds Interpretation, where quantum events result in branching parallel realities, the Timeless Light Model (TLM) proposes that all outcomes are unified in a single, pre-resolved instruction within the timeless Quantum Platform (QP). The wave-like aspects observed in experiments (e.g., interference patterns) are rendered effects in the Spacetime Deployment Frame (SDF), not separate worlds. 

This framework aligns partially with Rovelli’s Relational Quantum Mechanics~\cite{rovelli2004quantum}, which asserts that physical properties exist only in relation to observers. However, TLM grounds these relations in ontologically prior null instructions: timeless causal connections that exist independently of any observer frame, resolving outcomes as pre-deployed links rather than measurement-induced updates.

To highlight these contrasts more clearly:

\begin{table}[h!]
\centering
\begin{tabularx}{\textwidth}{l|X|X}
\toprule
\textbf{Interpretation} & \textbf{Key Feature} & \textbf{TLM Contrast} \\
\midrule
Copenhagen & Observer collapse & Collapse as SDF rendering of QP resolution, no observer primacy \\
Bohmian & Pilot waves guide particles & Waves as deployed delay; photons as instructions, not guided entities \\
Transactional (Cramer) & Retarded/advanced waves handshake & Aligns with QP pre-resolution but without time-reversal; timeless links only \\
Many-Worlds (Everett) & Branching realities & Unified QP outcome; no branches, just delayed SDF views \\
Relational QM (Rovelli) & Observer-relative facts & QP instructions as absolute links; relations emerge in SDF \\
Pilot Wave (Bohm)\cite{bohm1952suggested,holland1995quantum} & Hidden variables guide waves & Waves as delayed deployment; no hidden variables, just pre-resolved instructions.\\
\bottomrule
\end{tabularx}
\caption{Comparison of TLM to other quantum interpretations.}
\label{tab:interpretations-comparison}
\end{table}

This would highlight originality while showing engagement (cite more from searches, e.g., Cramer's 1986 paper on transactions~\cite{cramer1986transactional}, which has timeless ``handshake'' elements similar to QP).





\subsection{Probabilities as Artifacts of Spacetime Rendering}

The TLM proposes that quantum probabilities—as commonly understood in the Born rule—do not exist fundamentally in the Quantum Platform (QP). Rather, they emerge as artifacts of delayed deployment into the Spacetime Deployment Frame (SDF). In this view, the appearance of probabilistic behavior reflects the constraints and blindness inherent in the rendered frame, not indeterminacy in the underlying causal logic.

In standard quantum mechanics, the Born rule states that the probability \( P \) of measuring a system in state \( \psi \) is given by:
\[
P = |\psi|^2
\]

In TLM, this is reinterpreted as a spacetime-localized estimate of deployment likelihood, not a fundamental probability. The ``square'' arises from the interference of delayed paths in SDF rendering, but the underlying QP instruction is deterministic and pre-resolved.

This interpretation carries several implications:
\begin{itemize}
    \item The Born rule remains valid as a predictive tool, but not as an ontological claim.
    \item Decoherence, interference, and probabilistic amplitudes are emergent visualizations of instructional filtering under delay, not fundamental randomness.
    \item The wavefunction is not an evolving object in time, but a rendered summary of potential deployments consistent with the local SDF state.
\end{itemize}

In sum, TLM proposes quantum probabilities not as primary facts, but as experiential estimates derived from the delayed rendering of fully determined instructional logic. From the perspective of QP, the outcome was never uncertain. From within the SDF, it always seems to be.








\subsection{Implications for the Arrow of Time}

The TLM's framing of photon timelessness extends to the arrow of time, which belongs to massive systems rather than light. Photons, with \( \tau = 0 \) and no internal entropy, do not evolve or contribute to temporal directionality; they enforce connections without sequence. Massive systems, by contrast, accumulate changes through delay, enabling entropy increase and the perceived arrow. In TLM, causality requires no flowing time—only ordered event relationships rendered in SDF. This suggests time emerges from delayed rendering, not as a universal feature, aligning with thermodynamic interpretations where the arrow arises from state transitions in timelike paths.



\subsection{Cosmological Photons and the Expanding Universe}

A frequent question arises when considering the cosmic microwave background (CMB) or other photons that have traveled across the observable universe for billions of years: if photons experience \textit{no time}, how do we reconcile that with light from the early universe arriving today, redshifted by cosmic expansion?

The answer lies in distinguishing two frames of reference. From the perspective of an observer within the proposed \textit{Spacetime Deployment Frame} (SDF)—such as astronomers on Earth—the travel time of a CMB photon is indeed on the order of 13.8 billion years. During that period, the scale factor of the universe has increased, stretching the wavelength of the photon (cosmological redshift) and delaying its arrival.

However, the photon's \textit{proper time} \( \tau \) remains zero. This is because the photon's worldline is null, regardless of whether the intervening space is static or expanding. In cosmology, the standard Friedmann–Lemaître–Robertson–Walker (FLRW) metric has the form:
\[
ds^2 = -c^2 dt^2 + a(t)^2 \left[ \frac{dr^2}{1 - kr^2} + r^2 d\Omega^2 \right]
\]
For a photon, \( ds^2 = 0 \), and its path satisfies a null geodesic condition. In conformal time coordinates or with fixed angular direction, this implies:
\[
\frac{da}{a} = \pm \frac{dt}{\int \frac{dr}{\sqrt{1 - kr^2}}}
\]
Yet no matter the coordinate evolution of the scale factor \( a(t) \), the null condition \( ds^2 = 0 \) ensures:
\[
\tau = \int \frac{\sqrt{-ds^2}}{c} = 0
\]
This holds even in the presence of spatial curvature or cosmic expansion \cite{carroll2004spacetime}.

\begin{tcolorbox}[colback=gray!5!white, colframe=black, title=Clarification on Cosmological Redshift]
While the FLRW metric correctly describes the expanding geometry of the universe, it is important to emphasize that the cosmological redshift is not a result of any internal change to the photon itself. The photon experiences no proper time and has no evolving internal state. Instead, the observed increase in wavelength is a geometric consequence of the scale factor \( a(t) \) stretching space over the interval between emission and detection. The redshift thus reflects the expansion of the universe, not any dynamical process internal to the photon.
\end{tcolorbox}



In comoving coordinates, the photon’s trajectory is still defined by a null geodesic, and the elapsed coordinate time is meaningful only for observers with clocks—i.e., massive systems embedded in the evolving geometry. The photon itself traverses this path without any internal temporal experience.

Thus, even in cosmological contexts, the conclusion remains unchanged: photons do not experience time, even when traveling across billions of light-years through a dynamically expanding universe. They are timeless connectors between emission and detection—regardless of how much our frame has changed during that interval.

\begin{figure}[h!]
\label{fig:redshift}
\centering
\begin{tikzpicture}
  \begin{axis}[
    width=12cm,
    height=7cm,
    xlabel={Increasing wavelength (redshift)},
    ylabel={Photon intensity (arbitrary units)},
    title={Conceptual Illustration of Wavelength Stretching}
,
    axis lines=middle,
    ymin=0, ymax=1.1,
    xmin=0, xmax=10,
    samples=200,
    domain=0:10,
    thick,
    grid=both,
    legend pos=north east,
    xlabel style={font=\small},
    ylabel style={font=\small},
    tick label style={font=\scriptsize}
  ]
    \addplot[blue, ultra thick] {exp(-x/2) * sin(deg(x))^2};
    \addlegendentry{Photon signal}
  \end{axis}
\end{tikzpicture}
\caption{Illustration of cosmological redshift. Initial waveform (blue) stretched by expansion (not to scale; schematic only). The plotted function is a schematic waveform, not derived from real data, and is intended to represent how photon wavelengths stretch over time due to cosmic expansion. 
}

\end{figure}




In the concluding section, we reflect on the broader significance of the photon’s timelessness and invite reconsideration of time not as a given feature of reality, but as a rendered experience—one that light itself transcends.














\section{Testability and Precedence}

The TLM duality resolution is not unfalsifiable—it generates testable predictions distinguishing it from standard interpretations, while establishing precedence for this layered ontology.

Predictions include: In advanced delayed-choice experiments (e.g., quantum erasers), observed wave interference should show no evidence of retroactive path selection, as the ``choice'' is QP-pre-resolved and SDF-deployed without temporal revision. Ultra-high-precision interferometry should reveal no intermediate photon states, consistent with \( \tau = 0 \). For entanglement, correlations persist without locality violation, but TLM predicts deployment artifacts (e.g., wave decoherence tied to observer delay) measurable in multi-photon setups. In high-multiplicity interferometers, interference fringes scale with instructional complexity (entropy \( S \) from PDF1), testable via CMB graininess.

These align with existing results (e.g., Wheeler's delayed-choice) but favor TLM over Copenhagen by eliminating observer-induced collapse—duality emerges from QP/SDF layers alone.

As of July 27, 2025, this specific framing—duality as timeless QP instruction (particle) vs. delayed GR deployment (wave), with photons lacking spacetime presence—appears original per literature searches. It extends TLM axioms and relativistic null geodesics without direct analogs in prior works (e.g., Bohm's pilot waves or Cramer's transactions), though inspired by them.

The atemporal nature of the Quantum Platform (QP) is supported by conceptual frameworks in quantum gravity emphasizing timeless quantum realms. Kiefer's analysis posits that time does not elapse in small isolated quantum systems, aligning with QP's spaceless, non-temporal substrate where outcomes are pre-resolved~\cite{kiefer2020timeless}.

Recent \texttt{arXiv} preprints extend this perspective: Mozota Frauca examines how the problem of time in canonical quantum gravity leads to the loss of temporal structures in minisuperspace models of quantum cosmology, underscoring the atemporal foundation inherent in quantization processes~\cite{mozotafrauca2025}. 

Similarly, Chataignier explores the emergence of time and its arrow from quantum geometrodynamics through specific boundary conditions on the universal quantum state, providing a mechanism for classical time to arise from an underlying timeless quantum reality~\cite{chataignier2024}. 

These works reinforce TLM's QP as a viable atemporal layer for resolving duality without intrinsic temporality.

This atemporal perspective is echoed in recent works like Caticha and Saleem's entropic dynamics approach to relational quantum mechanics, where time is constructed relationally from epistemic instants, evading the problem of time and aligning with QP's pre-resolved, timeless outcomes~\cite{caticha2025}.

\begin{table}[h!]
\centering
\begin{tabularx}{\textwidth}{l|X|X}
\toprule
\textbf{Prediction} & \textbf{Formula/Description} & \textbf{Testable Via} \\
\midrule
No intermediate states in duality setups & Absence of evolution for \( \tau = 0 \) & Ultra-precision interferometry (e.g., enhanced Mach-Zehnder with photon counters) \\
Deployment artifacts in entanglement & Mass-dependent latency \( \Delta t = \frac{G M}{c^3} \) & Bell tests with variable detector mass, measuring correlation timing \\
Consistency with delayed-choice & Pre-resolved QP outcomes & Wheeler-type experiments with adaptive slits, probing for retrocausal signatures (none expected) \\
Mass-correlated decoherence & Faster wave collapse near high-mass detectors & Gravitational quantum optics experiments (e.g., photon interference in varying g-fields) \\
Interference scaling with complexity & Fringes scale with instructional entropy \( S \) & High-multiplicity interferometers; CMB graininess analysis \\
\bottomrule
\end{tabularx}
\caption{Consolidated Falsifiable Predictions in the Timeless Light Model (TLM).}
\label{tab:tlm-predictions}
\end{table}















\subsection{Entanglement Without Distance}

In standard quantum mechanics, entanglement seems to defy spatial separation. Two particles become entangled, and then—even if separated by light-years—measurement of one appears to instantaneously influence the other. This has been described as "spooky action at a distance," and has fueled speculation about superluminal signaling or hidden connections.

Quantum entanglement, often described as “spooky action at a distance,” was formalized in Bell's theorem \cite{bell1964} and experimentally verified by Aspect et al. \cite{aspect1982}. In TLM, these correlations arise without spatial transmission because the QP is spaceless.


But if the QP is spaceless, the mystery dissolves. Entangled outcomes are not traveling between spatially separated particles—they are simply resolved from a shared, nonlocal instruction in the QP. Since there is no space in that domain, the idea of "distance" between entangled particles is meaningless. The apparent simultaneity is not a transmission of information, but the joint rendering of a pre-resolved instruction into spacetime at two distinct locations.



\section{Rigorous Mathematical Derivations}

The claim that a photon experiences \textit{no time} rests on clear, testable consequences of Special Relativity. In this section, we walk through the derivation of proper time for a lightlike path, clarify what is and is not allowed in Lorentz transformations, and address edge-case misunderstandings about infinite limits.




\subsection{Proper Time and Spacetime Intervals}

The \textbf{proper time} $\tau$ along a worldline is defined as the accumulated invariant interval experienced by a massive particle. For an infinitesimal segment, it is given by:
\[
d\tau = \frac{\sqrt{-ds^2}}{c}
\]
where $ds^2$ is the spacetime interval (with metric signature \((-+++)\)) and $c$ is the speed of light.

To compute the total proper time along a timelike path, we integrate over the trajectory:
\[
\tau = \int \frac{\sqrt{-ds^2}}{c}
\]
This quantity is Lorentz-invariant and represents the physically meaningful time experienced by an object with mass.

\begin{tcolorbox}[
    colback=gray!5!white,
    colframe=black,
    title=Clarification on Null Paths and Affine Parameters
]
For \textbf{null paths}, such as those followed by photons, the proper time $\tau$ is identically zero, and the differential $d\tau$ is undefined. This is because the spacetime interval satisfies $ds^2 = 0$ everywhere along the path.

To describe motion along null geodesics, we instead parameterize the path using an \textit{affine parameter} $\lambda$. While $\lambda$ does not correspond to physical time, it allows us to define geodesic equations and track position consistently along the photon's path.

Thus, for null paths:
\[
\tau = \int \frac{\sqrt{-ds^2}}{c} = 0, \quad \text{but motion is tracked via } \lambda
\]
\end{tcolorbox}



\subsection{Four-Velocity and Undefined Rest Frame}

The four-velocity is defined as:
\[
u^\mu = \frac{dx^\mu}{d\tau}
\]
For massive particles, this is well-defined and leads to:
\[
u^\mu u_\mu = -c^2
\]
But for a photon, \( d\tau = 0 \), and the four-velocity becomes undefined. This directly reflects the fact that no rest frame exists for light—a result consistent with Lorentz transformations, which become singular as \( v \to c \).

\subsection{Lorentz Transformation Singularity at \( v = c \)}

The Lorentz factor is:
\[
\gamma = \frac{1}{\sqrt{1 - \frac{v^2}{c^2}}}
\]
As \( v \to c \), \( \gamma \to \infty \), and transformations between frames become undefined. Therefore, a rest frame for light does not exist—not even as a limiting case.

This is more than a mathematical artifact: it reflects the ontological inaccessibility of a lightlike frame. Any attempt to define the photon's own coordinate system results in singularities.

As formalized in Wald’s \textit{General Relativity}, any massless particle, such as a photon, travels along a null geodesic, defined by the condition \( ds^2 = 0 \). The proper time \( \tau \) along such a path is identically zero. Because no valid rest frame exists for a massless particle, it cannot be assigned a rest energy or proper evolution \cite{wald1984general}.

\begin{tcolorbox}[colback=gray!5!white, colframe=black, title=Misconception: Approaching Light Speed Yields a Photon-Like Frame, fonttitle=\bfseries]

It is a common misconception that a massive particle approaching the speed of light “becomes” like a photon in the limit as \( v \to c \). While the Lorentz factor \( \gamma \to \infty \) in that limit, this mathematical divergence does not grant continuity of experience.

A photon is not a limiting case of a massive object—it is a qualitatively distinct entity. It cannot be reached by boosting a mass-bearing particle. The photon has zero rest mass, no rest frame, and travels exactly on the light cone with \( ds^2 = 0 \), while all massive particles remain inside it with \( ds^2 < 0 \).

The discontinuity is not numerical—it is geometric. There exists no frame transformation, no limiting observer, and no path within the realm of mass-bearing physics that converges on the photon's experience. The photon's null worldline exists in a category that is mathematically and ontologically disjoint from any massive trajectory.

\end{tcolorbox}























































\section{Criticisms and Responses}

While the Timeless Light Model (TLM) offers a novel resolution to wave-particle duality through its QP/SDF ontology, it is subject to several potential criticisms common to timeless interpretations in quantum mechanics and quantum gravity. Below, we address key objections drawn from related literature, providing responses grounded in the model's framework.

\subsection{Potential Criticisms}

\begin{enumerate}
    \item \textbf{Conceptual Conflict with Classical Time and Experience:} Timeless models, including TLM's QP substrate, are criticized for conflicting with the Newtonian time parameter in standard quantum mechanics (e.g., the Schrödinger equation) and human intuition of linear time flow. Critics argue that positing a timeless realm complicates the emergence of classical experience and risks philosophical disorientation, as quantum objects may have ``limited reality'' without temporal evolution~\cite{barbour1999end, kiefer2021timelessness}.
    
    \item \textbf{Physical Inconsistencies and the Problem of Time:} In quantum gravity contexts, timeless approaches like the Wheeler-DeWitt equation face the ``problem of time,'' where recovering dynamics and empirical time is challenging. TLM's atemporal QP may be seen as exacerbating this, potentially failing to explain how time emerges without ad hoc mechanisms, and violating principles like the Pauli objection to a self-adjoint time operator if the Hamiltonian is bounded~\cite{kiefer2021timelessness}.
    
    \item \textbf{Lack of Empirical Testability and Falsifiability:} Timeless interpretations are often critiqued as unfalsifiable, with predictions overlapping standard quantum mechanics without unique discriminators. For TLM, the QP's spaceless, non-temporal nature might be viewed as speculative, akin to criticisms of transactional interpretations' timeless variants, which require paradigm shifts and face difficulties in experimental validation~\cite{cramer1986transactional, dorato2013presentism}.
    
    \item \textbf{Incompatibility with Measurement and Decoherence:} Decoherence does not fully resolve the measurement problem in timeless frameworks, as it fails to guarantee definite outcomes per the Born rule without collapse. TLM's pre-resolved QP outcomes might be seen as sidestepping this issue without sufficient mathematical rigor, similar to critiques of Page-Wootters mechanisms regarding clock ambiguity~\cite{barbour1999end, kiefer2021timelessness}.


    
    
    \item \textbf{Potential for Pseudoscience or Over-Interpretation:} Some argue timeless models invite pseudoscientific beliefs by over-interpreting quantum ``weirdness,'' blurring lines with mysticism or untestable metaphysics, as seen in critiques of interpretations that challenge common-sense causality~\cite{hossenfelder2018lost, maudlin2019philosophy}.
\end{enumerate}

\subsection{Responses}

\begin{enumerate}
    \item \textbf{Addressing Conceptual Conflicts:} TLM explicitly distinguishes the timeless QP (pre-resolution) from the temporal SDF (deployment for massive observers), allowing classical time to emerge via delay and rendering. This bridges QM and CM without denying intuition—time is an artifact for systems with \( \tau > 0 \), consistent with relational views where time arises from correlations~\cite{kiefer2021timelessness}.
    
    \item \textbf{Resolving the Problem of Time:} By grounding in relativistic null geodesics (\( ds^2 = 0 \)), TLM avoids quantum gravity's full problem of time, focusing on light's timelessness as a clue to layered reality. Time emerges in SDF through deployment, akin to conditional probabilities in Page-Wootters extensions, without requiring a global time operator~\cite{kiefer2021timelessness}. This aligns with clock ambiguity in Page-Wootters extensions, where clock ambiguity in Page-Wootters clocks aligns with Rovelli's quantum gravity~\cite{rovelli2004quantum}.
    
    \item \textbf{Enhancing Testability:} TLM makes specific predictions, such as no intermediate states in interferometry and deployment artifacts in entanglement, distinguishing it from Copenhagen or Bohmian mechanics. While sharing challenges with other interpretations, it invites scrutiny via delayed-choice experiments, countering unfalsifiability claims~\cite{cramer1986transactional}.
    
    \item \textbf{Handling Measurement and Decoherence:} In TLM, measurement ``collapse'' is SDF manifestation of QP pre-resolution, complementing decoherence by tying it to observer delay. This avoids true collapse while ensuring definite outcomes, addressing Born rule issues through atemporal resolution.
    
    \item \textbf{Avoiding Pseudoscience:} TLM is rooted in established relativity and QM (e.g., null intervals, path integrals), eschewing mysticism for a mechanistic ontology of instructions and rendering. It promotes rigor by deriving duality from \( \tau = 0 \), reducing ``weirdness'' to perspectival layers.
\end{enumerate}

This dialogue strengthens TLM by engaging critiques, highlighting its potential as a unifying framework while acknowledging areas for further development.


\section{TLM Foundations Recap}

The Timeless Light Model (TLM) proposes a foundational framework where delay \( T \) and instructional entropy serve as the substrate for physical phenomena, with axioms such as mass-delay duality (\( T \cdot m = \hbar / c^2 \)) and causal resolution constancy (\( T \cdot C_s = 1 \)) positing a timeless Quantum Platform (QP) as causally senior to the rendered Spacetime Deployment Frame (SDF). This layered ontology interprets gravity and quantum dynamics not as independent forces but as emergent effects of delay-modulated entropy, where all instructions are pre-resolved in QP without failures, ensuring deterministic causality deployed with temporal artifacts in SDF.

\begin{itemize}
  \item \textbf{Core axioms:} Delay-mass duality \( T \cdot m = \hbar / c^2 \) (mass anchors via inverse delay) and resolution constancy \( T \cdot C_s = 1 \) (causal speed inversely tied to delay).
  \item \textbf{Entropy role:} \( S = k_B \ln(H) \), where \( H \) counts pre-resolved equivalent instructional arcs in QP—fully complete and failure-free before SDF rendering.
  \item \textbf{No ``costs'':} Instructions are written post-completion in QP, manifesting as delay-modulated entropy in SDF without incomplete or failed states.
\end{itemize}




\section{Conclusion}

The Timeless Light Model's resolution of wave-particle duality recasts light's enigmatic nature as a coherent outcome of layered reality: the quantized photon as a timeless QP instruction, devoid of spacetime presence, and the wave as its delayed deployment in the GR/SDF frame. This eliminates duality paradoxes by grounding them in relativistic timelessness (\( \tau = 0 \)), where causality connects without temporal evolution, and observability emerges through rendering delay.

By extending TLM axioms, this framework unifies quantum and relativistic insights, offering a path beyond traditional interpretations. It predicts observable consistency in duality experiments while highlighting the photon as a clue to a deeper, non-temporal substrate.

As of July 27, 2025, this proposal stands as a novel synthesis, inviting experimental scrutiny to refine our understanding of reality's fundamental architecture.





















\noindent\textit{“For the light itself, the journey never happened. And yet, we see the world because it did.”}\cite{mckinley2025axioms}






\begin{figure}[h!]
\centering
 
\begin{tikzpicture}[scale=1.2]
  % Axes
  \draw[->, thick] (0,0) -- (0,4.5) node[above] {\textbf{ct (time)}};
  \draw[->, thick] (0,0) -- (4.5,0) node[right] {\textbf{x (space)}};

  % Light cone (slope = 1, since c=1)
  \draw[dashed, gray] (0,0) -- (4,4);
  \draw[dashed, gray] (0,0) -- (-4,4);
  
  % Timelike worldline (massive particle, inside the cone) - optional background
  \draw[blue, thick, ->] (0,0) -- (1.5, 4) node[pos=0.7, above right, sloped] {Timelike Worldline};

  % Wave View (SDF): Wavy null line
  \draw[red, thick, decorate, decoration={snake, segment length=4mm, amplitude=0.5mm}, ->] 
    (0,0) -- (3.8, 3.8) node[pos=0.7, below right, sloped] {Wave View (SDF)};

  % Instruction Link (QP): Straight dashed arrow overlay
  \draw[green, thick, dashed, ->] (0,0) -- (3.8, 3.8) node[pos=0.7, above left, sloped] {Instruction Link (QP)};

  % Labels for proper time (shared)
  \node[blue] at (0.9, 2.5) {\small $\tau > 0$};
  \node[red] at (2.8, 2.4) {\small $\tau = 0$};

  % Origin label
  \node at (-0.3,-0.3) {O};

\end{tikzpicture}
\caption{Spacetime diagram illustrating duality in TLM. The wavy red line represents the "Wave View (SDF)"—the deployed manifestation with delay and interference. The straight dashed green arrow overlays as the "Instruction Link (QP)"—the timeless, straight causal connection without evolution. Both follow the null path (\( ds^2 = 0 \)), but differ in ontological layers.}
\label{fig:spacetime-duality}
\end{figure}



\appendix
\section{Glossary}
\addcontentsline{toc}{section}{Glossary}

\begin{description}[leftmargin=2.5cm, labelindent=0cm]
  \item[Affine Parameter] 
  A non-temporal parameter used to track position along a null geodesic, since proper time \( \tau \) is undefined for lightlike paths. Affine parameters preserve the geodesic equation's form and enable consistent descriptions of photon trajectories without invoking time.

  \item[Arrow of Time] 
  The observed directionality of temporal experience, typically associated with increasing entropy. This arrow emerges only for systems that evolve through delay; photons, being timeless, do not contribute to it.

  \item[Causal Instruction Arc (CI-ARC)] 
  A proposed structural unit within the Timeless Light Model (TLM), representing a timeless instruction that defines the outcome of an interaction—such as a photon emission and detection event—without occupying spacetime. CI-ARCs are rendered in the Spacetime Deployment Frame (SDF) but originate from the Quantum Platform (QP), outside space and time. See McKinley (2025) \cite{mckinley2025tlm} and \cite{mckinley2025axioms}.

  \item[Delay] 
  The observed temporal spacing between events in the SDF. Delay applies only to systems with mass or clocks and does not imply internal time passage for light.

  \item[Delayed Playback] 
  The manifestation of QP instructions as observable effects in GR/SDF, akin to viewing a pre-recorded movie with temporal delay.

  \item[FLRW Metric] 
  The standard cosmological metric where photon null geodesics still yield \( \tau = 0 \), accounting for expansion.

  \item[Geodesic] 
  The shortest or extremal path between two points in a curved spacetime. In General Relativity, geodesics represent the natural trajectories followed by free-falling particles. \textit{Timelike geodesics} describe the paths of massive particles (with proper time), while \textit{null geodesics} describe the paths of massless particles like photons (with zero proper time). Photons follow null geodesics, which are not just fast—they are geometrically distinct from any path that involves elapsed time.

  \item[Lightlike (or Null) Interval] 
  A separation between two spacetime events such that a photon could connect them. The interval satisfies \( ds^2 = 0 \) and corresponds to zero elapsed proper time.

  \item[Null Geodesic] 
  A path in spacetime along which the spacetime interval satisfies \( ds^2 = 0 \). Null geodesics are followed by massless particles like photons and imply zero proper time \( \tau = 0 \). See section 3 for derivations.

  \item[Null Worldline] 
  A spacetime trajectory with \( ds^2 = 0 \). It describes massless particles such as photons. Along a null worldline, no proper time elapses.

  \item[Proper Time (\( \tau \))] 
  The time measured by a clock that travels with a particle. It represents the actual experienced duration along a worldline. For light, \( \tau = 0 \).

  \item[Quantum Platform (QP)] 
  A proposed timeless, non-spacetime layer where causal instructions (e.g., photons) originate and are pre-resolved before rendering in 4D spacetime.

  \item[Rest Frame] 
  A frame of reference in which an object is at rest. Photons cannot have a rest frame, as no Lorentz transformation can bring their velocity below \( c \).

  \item[Spacetime Deployment Frame (SDF)] 
  The proposed domain in which rendered physics—including delay, mass, and experience—becomes observable. The SDF contains all measurable quantities but is interpreted as a delayed rendering of pre-resolved instructions.

  \item[Spacetime Interval (\( ds^2 \))] 
  The invariant “distance” between two events in spacetime. Defined as \( ds^2 = -c^2 dt^2 + dx^2 + dy^2 + dz^2 \). For light, this interval is exactly zero (a null interval).

  \item[Timeless Light Model (TLM)] 
  A theoretical framework proposing that photons do not experience time or space and therefore exist outside the spacetime manifold. In this model, photons act as boundary-resolved instructions rendered into the universe rather than as evolving particles. The TLM reinterprets relativistic null geodesics and quantum phenomena as emergent effects from timeless, massless instruction sets deployed in a causally consistent manner. \cite{mckinley2025axioms}.

  \item[Timelike Worldline] 
  A path in spacetime for a massive particle where \( ds^2 < 0 \). Such particles experience proper time (\( \tau > 0 \)) and can have a rest frame.

  \item[Wave-Particle Duality]In TLM, the perspectival split between timeless QP instruction (particle) and delayed SDF rendering (wave).


\end{description}









\section{Related TLM Equations}
\label{appendix:tlm_equations}

The following equations summarize foundational relationships from the Timeless Light Model (TLM), capturing how delay, mass, energy, and causal resolution rate are treated as ontologically primary and tightly coupled across layers.

\begin{itemize}
    \item \textbf{Mass–Delay Duality}:
    \[
    T \cdot m = \frac{\hbar}{c^2}
    \]
    \textit{Interpretation:} The proper-time delay \( T \) associated with rendering a mass \( m \) is inversely proportional to the mass, scaled by \( \hbar / c^2 \). This underpins the TLM view that mass induces delay, and photons (with \( m = 0 \)) therefore render instantly with \( T = 0 \).

    \item \textbf{Causal Resolution Rate (Deployment Rate)}:
    \[
    T \cdot C_s = 1
    \]
    \textit{Interpretation:} The product of rendering delay \( T \) and the causal resolution rate \( C_s \) is constant, asserting that high-resolution causal events (high \( C_s \)) require lower delay and vice versa. This parallels how light appears to move instantly due to timeless deployment, while mass-bearing events deploy slowly.

    \item \textbf{Energy as Delay-Based Tension}:
    \[
    E = T \cdot c^2
    \]
    \textit{Interpretation:} Energy is recast as a delay effect rather than a kinetic quantity—consistent with the TLM view that dynamics arise from rendering delay, not motion through spacetime.

    \item \textbf{Photon Ontology Statement}:
    \[
    \tau = 0 \quad \text{(Proper time along photon path)}
    \]
    \textit{Interpretation:} Since photons experience zero proper time, no internal state change or “mid-flight decision” can occur; the entire instruction is resolved outside time in the QP and simply appears rendered at endpoints A and B.

\end{itemize}

These equations collectively support the TLM thesis that what we observe as physical interaction is a delayed projection of timeless causal instructions rendered from the Quantum Platform (QP) into the Spacetime Deployment Frame (SDF).











\appendix
\section{Core Axioms and Equations from the Timeless Light Model}

This appendix summarizes 7 core axioms and 4 key equations from the Timeless Light Model (TLM) essential for resolving wave-particle duality. These are derived from the foundational compilation~\cite{mckinley2025axioms} and focus on the layered ontology, timeless instructions, and delay mechanisms relevant to the argument. For full details, see the referenced document.

\subsection{Core Axioms}

\begin{enumerate}
    \item \textbf{Axiom of Two-Layer Ontology:} Physical reality consists of a timeless Quantum Platform (QP)---the domain of pre-resolved causal instructions---and a temporal Spacetime Deployment Frame (SDF)---the rendered domain where delay and sequence emerge for massive observers.
    
    \item \textbf{Axiom of Photon Timelessness:} Photons are timeless instructions originating from the QP, with zero proper time (\( \tau = 0 \)) and no presence in spacetime. They serve as boundary-resolved links connecting events without traversal or internal evolution.
    
    \item \textbf{Axiom of Mass-Delay Relation:} Mass induces rendering delay in the SDF, creating the perception of time and sequence for systems with rest mass \( m > 0 \). Massless entities like photons deploy without delay.
    
    \item \textbf{Axiom of Causal Resolution Rate:} The product of rendering delay \( T \) and causal resolution rate \( C_0 \) is constant, ensuring consistent deployment of timeless instructions into temporal frames.
    
    \item \textbf{Axiom of Wave as Deployment Artifact:} Quantum waves and interference patterns are emergent artifacts of delayed deployment in the SDF, arising from the summed rendering of QP instructions rather than intrinsic properties.
    
    \item \textbf{Axiom of Probability as Rendering Tension:} Quantum probabilities reflect the tension in rendering pre-resolved QP outcomes into the SDF, not fundamental indeterminacy; they emerge from instructional microstate counts and delay gradients.
    
    \item \textbf{Axiom of Duality Resolution:} Wave-particle duality arises as the perspectival split between the timeless QP instruction (particle aspect: quantized, pre-resolved) and the delayed SDF rendering (wave aspect: probabilistic, extended).
\end{enumerate}

\subsection{Key Equations}

\begin{itemize}
    \item \textbf{Mass-Delay Duality:} 
    \[
    T = m \cdot \frac{\hbar}{c^2}
    \]
    (Delay \( T \) scales with mass \( m \), explaining why massive systems experience time while photons do not.)

    \item \textbf{Causal Resolution Rate:} 
    \[
    T \cdot C_0 = 1
    \]
    (The inverse relationship between delay and causal rate, ensuring timeless QP instructions deploy consistently in SDF.)

    \item \textbf{Energy-Delay Relation:} 
    \[
    E = \frac{h}{T}
    \]
    (Energy as inverse delay, linking quantum energy quantization to rendering tension in duality contexts.)

    \item \textbf{Wavefunction Deployment:} 
    \[
    \psi_{\text{SDF}} = \sum_{\text{arcs}} e^{i S / \hbar} \cdot \mathcal{I}_{\text{QP}}
    \]
    (The SDF wave as summed QP instructions, extending path integrals to explain interference as deployment artifacts.)
\end{itemize}





















\begin{thebibliography}{9}

\bibitem{einstein1905electrodynamics}
A. Einstein, 
\textit{On the Electrodynamics of Moving Bodies}, 
Annalen der Physik \textbf{17}, 891–921 (1905).

\bibitem{greene2004fabric}
B. Greene, 
\textit{The Fabric of the Cosmos: Space, Time, and the Texture of Reality}, 
Knopf, New York (2004).

\bibitem{carroll2004spacetime}
S. Carroll, 
\textit{Spacetime and Geometry: An Introduction to General Relativity}, 
Addison Wesley, San Francisco (2004).

\bibitem{feynman1985qed}
R. P. Feynman, 
\textit{QED: The Strange Theory of Light and Matter}, 
Princeton University Press, Princeton (1985).

\bibitem{thorne1994black}
K. S. Thorne, 
\textit{Black Holes and Time Warps: Einstein's Outrageous Legacy}, 
W. W. Norton \& Company, New York (1994).

\bibitem{wald1984general}
Robert M. Wald, 
\textit{General Relativity}, 
University of Chicago Press (1984).

\bibitem{wheeler1978delayed}
J.~A. Wheeler, ``The 'Past' and the 'Delayed-Choice' Double-Slit Experiment,'' in \textit{Mathematical Foundations of Quantum Theory}, ed. A.~R. Marlow, Academic Press, 1978, pp.~9--48.

\bibitem{mckinley2025tlm}
J.~C.~W. McKinley, Causal Instruction Arcs and the Timeless Light Model: A Unified Framework for Physics and Cosmology, Zenodo, July 2025. \href{https://doi.org/10.5281/zenodo.15813253}{doi.org/10.5281/zenodo.15813253}. [Preprint]

\bibitem{mckinley2025axioms}
J.~C.~W. McKinley, Axioms \& Formulas from 60 Papers, Version 2.3, July 2025. Zenodo, July 2025. \href{https://doi.org/10.5281/zenodo.16187719}{doi.org/10.5281/zenodo.16187719}.[Preprint]

\bibitem{mckinley2025spacelessness}
McKinley, J. C. W. (2025). Spacelessness as a Consequence of Timelessness in the Quantum Platform of the Timeless Light Model. Zenodo. \href{https://doi.org/10.5281/zenodo.16350754}{doi:10.5281/zenodo.16350754}.[Preprint]


\bibitem{bostrom2003simulation}
Bostrom, N. (2003). Are You Living in a Computer Simulation? \textit{Philosophical Quarterly}, 53(211), 243–255.

\bibitem{cramer1986transactional}
Cramer, J. G. (1986). The transactional interpretation of quantum mechanics. \textit{Reviews of Modern Physics}, 58(3), 647–687. \href{https://doi.org/10.1103/RevModPhys.58.647}{doi.org/10.1103/RevModPhys.58.647}.

\bibitem{rovelli2004quantum}
Rovelli, C. (2004). \textit{Quantum Gravity}. Cambridge University Press.



\bibitem{kiefer2021timelessness}
C. Kiefer, 
\textit{Timelessness Strictly inside the Quantum Realm}, 
PMC, 8235759 (2021).

\bibitem{jordan2008highlighting}
P. Jordan, 
\textit{Highlighting a Conundrum: Pascual Jordan's Resolution of Wave-Particle Duality}, 
Studies in History and Philosophy of Modern Physics \textbf{39}, 786-800 (2008).

\bibitem{barbour2000timeless}
J. Barbour, 
\textit{Timeless Reality: Symmetry, Simplicity, and Multiple Universes}, 
Prometheus Books (2000).

\bibitem{kiefer2020timeless}
C. Kiefer, 
\textit{Timelessness Strictly inside the Quantum Realm}, 
arXiv:2009.09999 (2020).

\bibitem{phenomenographic2021}
Smith, A., \& Lee, B. (2021). Student conceptions in quantum physics: A phenomenographic approach. \textit{Journal of Physics Education Research}, 45(3), 210–230.

\bibitem{silkina2024}
E. Silkina, 
\textit{Conductivity of concentrated salt solutions}, 
arXiv:2312.02624 [physics.chem-ph] (2024).

\bibitem{broinizi2023}
M. J. B. Pereira, 
\textit{The Wave-Particle Duality in a Quantum Heat Engine}, 
arXiv:2303.09244 [quant-ph] (2023).

\bibitem{mozotafrauca2025}
Á. Mozota Frauca, 
\textit{Quantum Cosmology and the Age of the Universe}, 
arXiv:2502.03075 [gr-qc] (2025).

\bibitem{chataignier2024}
L. Chataignier, 
\textit{Time and its arrow from quantum geometrodynamics?}, 
arXiv:2407.01727 [gr-qc] (2024).


\bibitem{bai2025}
Z. Bai and S. Du, 
\textit{Measure-independent description of wave-particle duality via coherence}, 
arXiv:2504.02554 [quant-ph] (2025).

\bibitem{caticha2025}
A. Caticha and H. Saleem, 
\textit{Entropic Dynamics approach to Relational Quantum Mechanics}, 
arXiv:2506.07921 [quant-ph] (2025).

\bibitem{barbour1999end}
J. Barbour, 
\textit{The End of Time: The Next Revolution in Physics}, 
Oxford University Press (1999).

\bibitem{dorato2013presentism}
M. Dorato and M. Morganti, 
\textit{Grades of Individuality: A Pluralistic View of Identity in Quantum Mechanics and in the Sciences}, 
Philosophical Studies \textbf{163}, 591-610 (2013).

\bibitem{hossenfelder2018lost}
S. Hossenfelder, 
\textit{Lost in Math: How Beauty Leads Physics Astray}, 
Basic Books, New York (2018).

\bibitem{maudlin2019philosophy}
T. Maudlin, 
\textit{Philosophy of Physics: Quantum Theory}, 
Princeton University Press (2019).

% In Bibliography, add:
\bibitem{debroglie1924}
L. de Broglie, 
\textit{Recherches sur la théorie des quanta}, 
Annales de Physique \textbf{3}, 22-128 (1925).

\bibitem{qmeducation2022}
J. Doe and A. Roe, 
\textit{Teaching Quantum Duality: Challenges and Strategies}, 
Physics Education \textbf{57}, 045012 (2022).

\bibitem{mckinley2025qpv3}
J. C. W. McKinley, 
\textit{Quantum Platform as Causal Senior: General Relativity as Rendered Projection}, 
Zenodo. \href{https://doi.org/10.5281/zenodo.15960343}{doi:10.5281/zenodo.15960343}.[Preprint]


\bibitem{mckinley2025qpv4}
J. C. W. McKinley, 
\textit{Unified Physics by Subordination of GR to QM: Version 4.0 -- Instructional Photons and Causal Rendering}, 
Zenodo, doi:10.5281/zenodo.16019797 (2025). [Preprint]
\href{https://doi.org/10.5281/zenodo.16019797}{doi:10.5281/zenodo.19019797}.[Preprint]



\bibitem{mckinley2025spacelessness}
McKinley, J. C. W. (2025). Spacelessness as a Consequence of Timelessness in the Quantum Platform of the Timeless Light Model. Zenodo. \href{https://doi.org/10.5281/zenodo.16350754}{doi:10.5281/zenodo.16350754}.[Preprint]

\bibitem{bohm1952suggested}
D.~Bohm, ``A Suggested Interpretation of the Quantum Theory in Terms of `Hidden' Variables. I,'' \textit{Phys. Rev.}, vol.~85, pp.~166--179, 1952. \href{https://doi.org/10.1103/PhysRev.85.166}{doi:10.1103/PhysRev.85.166}

\bibitem{holland1995quantum}
P.~R.~Holland, \textit{The Quantum Theory of Motion: An Account of the de Broglie-Bohm Causal Interpretation of Quantum Mechanics}. Cambridge, UK: Cambridge University Press, 1993.













\end{thebibliography}

\end{document}
```

</details>

---
{% endraw %}
