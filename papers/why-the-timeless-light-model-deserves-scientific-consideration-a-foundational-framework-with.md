---
layout: default
title: '[2025] Why the Timeless Light Model Deserves Scientific Consideration: A Foundational Framework with Derivations, Critiques, and Experimental Proposals'
description: 'Publication metadata and archived raw LaTeX source by John C. W. McKinley.'
permalink: /papers/why-the-timeless-light-model-deserves-scientific-consideration-a-foundational-framework-with/
paper: true
---
{% raw %}
# [2025] Why the Timeless Light Model Deserves Scientific Consideration: A Foundational Framework with Derivations, Critiques, and Experimental Proposals
*   **DOI:** [10.5281/zenodo.16724187](https://doi.org/10.5281/zenodo.16724187)
*   **Date:** 2 August 2025

<details markdown="1">
<summary><b>Click to view Raw LaTeX Source</b></summary>

```latex
\documentclass[12pt]{article}
% Page layout and basics
\usepackage[margin=1in]{geometry}
\usepackage[T1]{fontenc}
\usepackage{lmodern}
\usepackage[utf8]{inputenc}
\usepackage{float} % For [H] placement

% Tables & colors
\usepackage[table]{xcolor}
\usepackage{booktabs,tabularx,longtable,array}

% tcolorbox (only once!)
\usepackage[most]{tcolorbox}
\tcbuselibrary{skins,breakable}

% Math and symbols
\usepackage{amsmath,amssymb,amsthm}

% Lists
\usepackage{enumitem}

% Figures and captions
\usepackage{graphicx}
\usepackage{caption,subcaption}

% TikZ and PGF for diagrams
\usepackage{tikz}
\usepackage{pgfplots}
\usepackage{tikz-3dplot}
\usetikzlibrary{arrows.meta,positioning,shadows,shapes.geometric,decorations.pathmorphing}
\pgfplotsset{compat=1.18}

% Formatting
\usepackage{titlesec}
\usepackage{fancyhdr}

% Hyperlinks
\usepackage{hyperref}
\usepackage{cleveref}
\hypersetup{colorlinks=true,linkcolor=blue,citecolor=blue,urlcolor=blue}

% --- DOCUMENT METADATA ---
\title{Why the Timeless Light Model Deserves Scientific Consideration:\\ A Foundational Framework with Derivations, Critiques, and Experimental Proposals}
\author{John C. W. McKinley \\ Independent Researcher \\ \href{https://orcid.org/0009-0005-7097-5035}{0009-0005-7097-5035}}
\date{\today}


\begin{document}

\maketitle

\begingroup

\renewcommand{\thefootnote}{}%
\footnotemark
\footnotetext{This version published at \href{https://doi.org/10.5281/zenodo.16724187}{https://doi.org/10.5281/zenodo.16724187}.}
\addtocounter{footnote}{-1} % prevent increment
\endgroup


% --- ABSTRACT ---
\begin{abstract}
The Timeless Light Model (TLM) proposes a reclassification of light and causality: photons are not particles within spacetime, but timeless causal instructions authored on a pre-spatiotemporal Quantum Platform (QP). Observed effects such as interference, energy transfer, and entanglement arise not from propagation, but from the rendering of pre-resolved instructions into a Spacetime Deployment Frame (SDF), subject to mass-induced delay (modulated by gravity) and quantum structural filtering. This model dissolves foundational paradoxes—wave-particle duality, retrocausality, and the quantum measurement problem \cite{bell_against_measurement_1990}—by grounding causality outside time and reinterpreting spacetime as an emergent phenomenon, a view that resonates with modern approaches linking geometry to entanglement \cite{ryu_holographic_2006}. Unlike interpretations that retain metaphysical dualities or infinite regress (e.g., Many-Worlds \cite{everett1B57}), TLM recovers the standard formalism of GR and QM as projections from a unified instructional substrate \cite{mckinley_tlm_2025, mckinley_csubs_2025}, as conceptually demonstrated herein. This paper synthesizes the explanatory, mathematical, and experimental grounds for considering TLM a serious candidate for physical unification.
\end{abstract}

% --- INTRODUCTION ---
\section{Introduction}

The photon, long understood as the mediator of electromagnetic interaction \cite{feynmanQED}, remains ontologically unstable. It follows null geodesics, has no proper time (\( \tau = 0 \)), no rest frame, and cannot accumulate internal history—yet is still treated as a thing that travels through space and time. This tension lies at the heart of multiple unresolved paradoxes, from wave-particle duality to the measurement problem, which remains a central, foundational debate \cite{bell_against_measurement_1990}. According to relativity, a photon experiences zero time between emission and absorption \cite{waldGR, penrose_road_2004}. TLM takes this fact seriously—and literally.

In the Timeless Light Model, a photon is not in the universe. It is a timeless causal instruction arc (CI-ARC) defined on the Quantum Platform (QP), a non-spatiotemporal substrate where emission and absorption are co-authored as a single, pre-resolved CI-ARC \cite{mckinley_photons_2025, mckinley_synthesis_2025}. Observable quantum behavior is the consequence of rendering this instruction into the Spacetime Deployment Frame (SDF), where gravity imposes delay and the wavefunction imposes structure \cite{mckinley_tlm_2025}.

This ontological shift resolves longstanding conflicts without inventing new metaphysical entities (as in Many-Worlds \cite{everett1B57}), probabilistic wavefunction collapses \cite{born1926}, or observer-triggered histories \cite{wheelerDelayed, mckinley2025collapse}. Instead, it grounds all causal evolution in a timeless instruction layer and explains classical behavior as delayed deployment filtered by General Relativity and quantum structure.
















In this paper, we argue that the Timeless Light Model is not merely a reinterpretation but a serious candidate for physical unification. We will:
\begin{enumerate}
    \item Reframe the ontological status of light in light of null-time and its absence from spacetime;
    \item Conceptually derive the Einstein Field Equations and Schrödinger Equation from TLM axioms (Appendix C);
    \item Compare TLM to major interpretive models and address external critiques (Sec. 7.3);
    \item Detail experimental predictions that could empirically distinguish TLM from other frameworks (Sec. 5);
    \item Justify the central thesis: that causality is a timeless authoring process, and spacetime represents its sequenced projection under structural and gravitational constraints.
\end{enumerate}

TLM does not modify the equations of physics—it modifies the frame in which those equations are interpreted. In a landscape crowded with speculative metaphysics and incomplete unifications, the Timeless Light Model is compact, falsifiable, and already aligned with established formalisms \cite{bekenstein1973blackhole, hawking1975particle}. It is time to take timelessness seriously.







\begin{tcolorbox}[
    enhanced,
    title={Reframing the Role of Experience in TLM},
    colback=gray!5!white,
    colframe=black!75,
    fonttitle=\bfseries,
    bicolor,
    colbacklower=white,
    sharp corners,
    boxrule=1pt
]
% --- Upper Part: The Physical Principle ---
\begin{tcbitemize}[
    raster columns=1,
    sharp corners,
    boxrule=0.5pt,
    colframe=blue!75!black,
    interior style={top color=blue!5!white,bottom color=blue!15!white}
]
\tcbitem[title={\textbf{The Physical Principle: Delayed Rendering}}]
  The Timeless Light Model is founded on the \textbf{Principle of Delayed Rendering}: observable phenomena are not instantaneous but are deployed into an observer’s frame with a delay ($T$) governed by the interacting mass ($T \cdot m = \hbar/c^2$).

  \vspace{1mm}
  \textit{This is a non-teleological, falsifiable axiom that serves as a core “rule of the game” for the model.}
\end{tcbitemize}

% --- Lower Part: The Philosophical Implication ---
\tcblower
\textbf{The Philosophical Implication: Emergent Experience}

A profound consequence of the Principle of Delayed Rendering is that the universe is structured \textit{as if} to enable coherent, temporal experience. While the principle itself is a mechanistic constraint, its necessary outcome is the emergence of a stable, classical reality for observers.

\vspace{1mm}
This reframes purpose not as a cause, but as a deeply embedded structural consequence.
\end{tcolorbox}









\subsection{This Paper as TLM's Manifesto}
This paper serves as a manifesto for the Timeless Light Model, synthesizing its foundational axioms, mathematical derivations, philosophical implications, and experimental predictions into a single, cohesive argument. Drawing from a series of prior works \cite{mckinley_tlm_2025, mckinley_synthesis_2025, mckinley_photons_2025, mckinley_csubs_2025, mckinley2025collapse}, it consolidates TLM's dispersed elements into a unified framework, demonstrating why this model not only resolves longstanding paradoxes but also offers a parsimonious path toward physical unification. By addressing critiques head-on and highlighting testable differentiators, this document invites the scientific community to evaluate TLM not as mere speculation, but as a serious, falsifiable alternative to prevailing interpretations.


% --- SECTION 2: CORE ONTOLOGY ---
\section{Core Ontology of the Timeless Light Model}
The Timeless Light Model (TLM) begins from a radical ontological shift: light does not exist \textit{in} the universe. Instead, photons are timeless causal instructions authored on a pre-spatiotemporal substrate—the Quantum Platform (QP)—and are only rendered into spacetime at their endpoints. This structure yields a two-layered ontology:













\begin{itemize}
    \item \textbf{Quantum Platform (QP):} A timeless, causally senior layer that issues complete, successful emission–absorption causal instruction arcs (CI-ARC). Instructions on the QP have no duration, no location, and no internal evolution.
    \item \textbf{Spacetime Deployment Frame (SDF):} The observer-accessible layer where those instructions are rendered in sequence. The SDF imposes delay and structural filtering to produce temporally ordered experience.
\end{itemize}









\begin{figure}[h!]
\centering
\begin{tikzpicture}[scale=1.1,tdplot_main_coords]

% Define layers
\def\SDFz{3}
\def\Qz{0}

% Axes for SDF layer
\draw[->] (0,0,\SDFz) -- (5,0,\SDFz) node[below right] {Space ($x$)};
\draw[->] (0,0,\SDFz) -- (0,5,\SDFz) node[above left] {Time ($t$)};

% Rendered mass worldlines
\draw[thick] (1,1,\SDFz) -- (1,4.5,\SDFz) node[above] {Emitter};
\draw[thick] (4,1,\SDFz) -- (4,4.5,\SDFz) node[above] {Absorber};

% Rendered events
\filldraw[black] (1,2,\SDFz) circle (2pt) node[left] {\scriptsize A (Emission)};
\filldraw[black] (4,4,\SDFz) circle (2pt) node[right] {\scriptsize B (Absorption)};

% Link from QPlatform
\draw[dashed, red, thick] (1,2,\SDFz) -- (2.5,2,\Qz);
\draw[dashed, red, thick] (4,4,\SDFz) -- (2.5,2,\Qz);
\filldraw[red] (2.5,2,\Qz) circle (2pt) node[below] {\scriptsize Timeless Instruction};

% QPlatform plane
\draw[gray!60, thick, dashed] (0,0,\Qz) -- (5,0,\Qz) node[right] {};
\draw[gray!60, thick, dashed] (0,0,\Qz) -- (0,5,\Qz) node[left] {};
\node at (4.7,4.7,\Qz) {\scriptsize QPlatform (Timeless Layer)};

% Vertical projection lines
\draw[gray, dotted] (1,2,\SDFz) -- (1,2,\Qz);
\draw[gray, dotted] (4,4,\SDFz) -- (4,4,\Qz);

\end{tikzpicture}
\caption{A 3D illustration of the Timeless Light Model. Events A and B are rendered in the Spacetime Deployment Frame (SDF), but their connection is pre-resolved by a timeless instruction from the QPlatform (bottom layer). The photon does not traverse the space between A and B — it is the appearance of motion caused by delayed rendering of a pre-existing link.}
\label{fig:3d_qplatform}
\end{figure}






\begin{tcolorbox}[
  colback=gray!5,
  colframe=black!80,
  title={Key Insight into TLM's Causal Mechanism},
  fonttitle=\bfseries,
  boxrule=0.7pt,
  sharp corners=southwest,
  width=\textwidth,
  before skip=10pt,
  after skip=10pt
]
In the Timeless Light Model, quantum structures act as static filters and gravitational structures as delay filters, together determining which instruction arcs can be authored. Once authored, these arcs are rendered into the observer’s frame via mass-induced delay (manifesting as the speed of light c, extended by gravitational gradients). Only arcs that satisfy both structure and delay filters are ever written.
\end{tcolorbox}














The photon, in this model, is not a massless particle traveling along a null geodesic—it is a \emph{null-time causal link} that connects an emitter and absorber through a resolved instruction. The "path" it follows has no internal segments, because the spacetime interval along its trajectory is zero: \( ds^2 = 0 \) \cite{waldGR, mckinley_photons_2025}. TLM adopts the following ontological postulates (drawn from \cite{mckinley_tlm_2025, mckinley_synthesis_2025}):
\begin{enumerate}[label=\textbf{P\arabic*.}]
    \item \textbf{Timeless Instruction Authoring:} All physical events are authored on the QP as fully completed emission–absorption arcs. Only outcomes that satisfy all constraints are ever written.
    \item \textbf{Rendered Experience:} The SDF exists to render these prewritten instructions in sequenced order. Time is not a dimension—it is a rendering delay.
    \item \textbf{Dual Filtering:} Instructions from the QP are filtered by two independent systems: a \emph{delay filter} (GR) where mass imposes delay via \( T \cdot m = \hbar / c^2 \) \cite{mckinley_csubs_2025}, and a \emph{structure filter} (QM) where the wavefunction acts as a static rule set \cite{mckinley2025collapse}.
    \item \textbf{No Propagation:} There is no in-universe propagation of photons \cite{feynmanQED, mckinley_photons_2025}.
\end{enumerate}













\subsection{Wavefunction as an Asteroid Belt: A Field of Rules}

If the wavefunction does not cause delay, what is its role? In TLM, the wavefunction is a static, non-causal **rule-set** that functions as the terrain for experience. To illustrate this, we use the metaphor of a spaceship navigating an asteroid belt.

Imagine a spaceship (a CI-ARC) that must travel from an emission point to an absorption point. In the TLM, this journey is not a temporal process but a timeless authoring. The QP considers writing an instruction for this journey. However, the SDF is not empty; it contains an "asteroid belt" (the wavefunction). This belt is a fixed structure with dense regions and safe passages.

\begin{itemize}
    \item The asteroid belt does not cause the spaceship to slow down (it does not create delay).
    \item It simply makes certain trajectories impossible. The ship cannot be authored to exist where an asteroid already is.
    \item The QP does not write "failed" instructions where the ship hits an asteroid. It only writes the single, successful instruction that was always configured to pass through a safe channel.
\end{itemize}

The wavefunction is this asteroid belt. It is a real, structural feature of the SDF. Its amplitudes do not represent probabilities of a particle being in different places at once. Instead, $|\psi(x)|^2$ represents the "density of the terrain" at point $x$. A high amplitude corresponds to a clear passage (high permissibility), while a low amplitude corresponds to a dense cluster of "asteroids" (low permissibility).






\subsubsection{The Role of Mass-Induced Delay in Rendering}
In TLM, the rendering delay \(T\) is fundamentally mass-induced, grounding the model's unification of quantum and relativistic effects. From Axiom 6 (Mass-Delay Duality), \(T \cdot m = \hbar / c^2\) implies that for massless entities like photons (\(m=0\)), \(T=0\), leading to instantaneous rendering in the QP. In the SDF, this manifests as the speed of light \(c\)—the maximum causal rate, not a "travel speed," but the baseline sequencing for zero-delay arcs.

Gravity enters as clustered mass amplifying \(T\) gradients (e.g., time dilation), extending apparent durations beyond \(d/c\) (where \(d\) is spatial separation in the rendered frame). This isn't "additional slowing" on preexisting propagation; there's no transit—CI-ARCs are pre-resolved links, with delay creating the illusion of sequence for observers. Without mass, no delay, no time; c emerges as the no-mass limit, binding massive objects to subluminal paths (v < c).

This resolves key paradoxes: entanglement needs no signals (shared timeless arcs), while wave-particle duality arises from instruction (QP) vs. delayed wave (SDF). As noted: “In the Timeless Light Model, quantum and gravitational structures act as filters determining which instruction arcs can be authored. Once authored, these arcs are rendered into the observer’s frame via mass-induced delay (manifesting as c, extended by gravitational gradients). Only arcs that satisfy both structure and delay filters are ever written.”












\begin{tcolorbox}[%
  skin=enhancedmiddle,
  drop shadow,
  colback=blue!5,
  colframe=blue!75!black,
  colbacktitle=blue!20,
  coltitle=black,
  title={\bfseries Terminology Clarification: Filters vs. Rendering in TLM},
  fonttitle=\bfseries,
  boxrule=1pt,
  arc=4mm,
  attach title to upper shift=-2mm,
  before skip=10pt,
  after skip=10pt,
  left=4mm,
  right=4mm,
  width=\linewidth,
  breakable
]
\begin{tabularx}{\linewidth}{>{\bfseries}l >{\small}X >{\bfseries}l X}
\toprule
Term   & Function                                                        & Where It Happens                              & In Your Stack \\
\midrule
\rowcolor{gray!10}
Filter & Determines whether a CI-ARC is valid (i.e., writable)            & On the Quantum Platform (QP)                   & QP $\rightarrow$ Filter $\rightarrow$ Instruction Authoring \\
Render & Delays and sequences the observable execution of the CI-ARC      & In the Spacetime Deployment Frame (SDF)        & Instruction $\rightarrow$ Render $\rightarrow$ Experience   \\
\bottomrule
\end{tabularx}

\vspace{1em}
\textbf{Implication for Model Consistency:}

\begin{itemize}[left=0pt]
  \item \textbf{Filtering:} Happens before authoring—decides whether an instruction becomes real.
  \item \textbf{Rendering:} Happens after authoring—determines how that instruction appears in spacetime.
\end{itemize}

The wavefunction acts as a structure filter: only instructions matching the geometry of~$\psi$ are authored.  
GR (mass/gravity) acts as a delay filter: it doesn’t block validity but controls unfolding speed in experience.  
Obstructions (e.g., asteroids) can block absorbers—preventing CI-ARC creation. Thus, GR can serve as a pre-filter when macroscopic conditions impede instruction resolution.
\end{tcolorbox}











% --- SECTION 3: EXPLANATORY POWER ---
\section{What TLM Explains That Standard Models Don’t}
TLM directly addresses several foundational paradoxes by reinterpreting their ontology, often resolving issues that require infinite resources or ad hoc mechanisms in alternatives.
\begin{itemize}
    \item \textbf{Wave–Particle Duality Without Dualism:} Duality is not a property of the photon—it is a layering of perspective, distinguishing the timeless \textit{instruction} (particle) from its delayed \textit{rendered deployment} (wave) \cite{mckinley2025collapse, mckinley_tlm_2025}. In contrast, Copenhagen introduces probabilistic collapse without mechanism, while pilot-wave theories add hidden variables—both complicating ontology without necessity.


\begin{figure}[H]
\centering
\begin{tikzpicture}[
    ship/.style={draw, fill=blue!20, rectangle, minimum width=0.6cm, minimum height=0.3cm, rotate=30},
    asteroid/.style={circle, fill=gray!40, minimum size=0.4cm},
    path/.style={->, thick, red}
]
% Asteroids (representing the wavefunction terrain)
\foreach \x/\y in {-2/2, -1.5/3, -1/1.5, -0.5/2.5, 0/1, 0.5/3, 1/2, 1.5/1.5, 2/2.8} {
    \node[asteroid] at (\x,\y) {};
}
% Start and end zones
\node[ship] at (-2.5, 0.5) {};
\node[rectangle, draw, fill=green!10, minimum width=1.2cm, minimum height=0.6cm] at (2.5,3.5) {Absorption};
% The one successful path
\draw[path] (-2.5,0.5) .. controls (-1.5,1) and (0,1.5) .. (1.5,2.2) .. controls (2,3.2) .. (2.5,3.5);
\end{tikzpicture}
\caption{The wavefunction as a static asteroid belt. The observer’s experience is sculpted by these fixed constraints. The QP does not test paths; it authors the single timeless instruction (red line) that aligns with the terrain's safe passages.}
\label{fig:asteroid}
\end{figure}
















    
    \item \textbf{Entanglement Without Nonlocality:} Entanglement is the deployment of a \textit{shared causal instruction arc (CI-ARC)} linking multiple endpoints. The outcomes are co-authored on the QP without reference to distance or time. This reframes Bell violations not as violations of locality, but as signals that causality is not confined to spacetime \cite{wheeler_itfrombit}. Standard QM requires "spooky action" or infinite branches (Many-Worlds), whereas TLM resolves it with a single, pre-resolved arc.
    \item \textbf{Measurement Without Collapse:} TLM replaces collapse with \textit{pre-resolution}. The universe does not “decide” when you measure—it reveals what was already complete on the QP, dismissing the need for retrocausality \cite{wheelerDelayed}. This avoids the infinite regress of Many-Worlds (branching universes for every outcome) or GRW's spontaneous collapses (requiring arbitrary parameters), offering instead a finite, constraint-satisfying ontology.
    \item \textbf{Gravity as Delay, Not Distortion:} Mass imposes rendering delay on the deployment of instructions, and spacetime curvature is a macroscopic description of these delay gradients \cite{mckinley_csubs_2025}. Unlike loop quantum gravity or string theory, which introduce new entities or dimensions to unify GR and QM, TLM derives curvature from delay duality ($T \cdot m = \hbar / c^2$) without additional metaphysics.
\end{itemize}

% --- SECTION 4: MATHEMATICAL FOUNDATIONS ---
\section{Mathematical and Physical Foundations}
TLM does not modify the equations of GR or QM but reinterprets them as rendering consequences. As outlined in Appendix C, the EFE and SE can be recovered from TLM axioms using principles of entropic dynamics \cite{jacobson1995, caticha2011}.

\vspace{.5cm}

\begin{figure}[h!]
\centering
\begin{tikzpicture}[>=Stealth]
\draw[thick] (0,3) -- (8,3); \node at (4,4.5) {\textbf{Quantum Platform (QP)}};
\filldraw[blue] (1.5,3) circle (2pt) node[above=2pt] {$A$};
\filldraw[blue] (6.5,3) circle (2pt) node[above=2pt] {$B$};
\draw[<->, blue, thick] (1.5,3.15) to[bend left=10] node[midway,above] {Causal Instruction Arc $I(A,B)$} (6.5,3.15);
\draw[thick] (0,0) -- (8,0); \node at (4,-1.1) {\textbf{Spacetime Deployment Frame (SDF)}};
\filldraw[red] (2.5,0) circle (2pt) node[below=2pt] {$A'$};
\filldraw[red] (5.5,0) circle (2pt) node[below=2pt] {$B'$};
\draw[->, gray, dashed, thick] (1.5,2.8) -- (2.5,0.2);
\draw[->, gray, dashed, thick] (6.5,2.8) -- (5.5,0.2);
\end{tikzpicture}
\caption{A timeless causal instruction arc (CI-ARC) \( I(A,B) \) is authored on the QP and rendered into the SDF with delay, resulting in observable events \(A'\) and \(B'\).}
\label{fig:TLM_arc_simple}
\end{figure}



% --- SECTION 5: EXPERIMENTAL IMPLICATIONS ---
\section{Experimental Implications and Falsifiability}
A central virtue of TLM is its commitment to falsifiability. This section outlines key predictions and provides feasibility estimates for their verification, summarized in Table \ref{tab:predictions_summary}.

\begin{table}[h!]
\centering
\caption{Summary of Experimental Predictions and Feasibility.}
\label{tab:predictions_summary}
\begin{tabular}{|p{3.5cm}|p{5cm}|p{4.5cm}|}
\hline
\textbf{Prediction} & \textbf{Key Equation / Estimate} & \textbf{Feasibility} \\
\hline
\textbf{1. GW Residuals} & Stacking requirement: $N \approx (\sigma_n/\sigma_r)^2 \sim 10^4$ events. & Challenging but plausible with next-gen detectors and large catalogs. \\
\hline
\textbf{2. Gravitational Eraser} & Phase shift: $\Delta\phi = \omega(\Delta\Phi/c^2)$. Lab estimate: $\sim 10^{-8}$ rad. & Unfeasible on tabletop. Requires a dedicated space-based interferometer. \\
\hline
\textbf{3. Black Hole Rendering Delay} & Delay scales with Lorentz factor: $T' = \gamma T = T/\sqrt{1-R_S/r}$. & Thought experiment. Requires revolutionary advances in quantum astronomy. \\
\hline
\textbf{4. Decoherence Limit} & Coherence time: $T_2 = 1/\Gamma$, where $\Gamma$ is the non-fundamental leakage rate. & Highly feasible. Aligns with current goals in quantum computing research. \\
\hline
\end{tabular}
\end{table}

\subsection{Prediction 1: Residual Phase Shifts in Gravitational Wave Detectors}
TLM posits that gravitational waves are synchronization realignments of the SDF. This leads to the prediction that laser interferometers like LIGO/Virgo should register a small residual phase shift even after the primary gravitational wave signal is subtracted. (See Appendix C.3.1 and Figure \ref{fig:ligo_residual_plot}).

\subsubsection*{Feasibility Estimate}
\begin{itemize}
    \item \textbf{Method:} This test is achievable through advanced post-processing of existing and future data, aligning with current scientific practices of searching for signals in detector residuals \cite{ligo_residuals_2023}. The procedure involves coherently stacking the residuals from many high-SNR events to average out random quantum noise.
    \item \textbf{Challenge \& Outlook:} The predicted TLM residual would be incredibly faint. The required sensitivity might push beyond current capabilities but could be within reach of **next-generation detectors**. This makes it a challenging but plausible long-term test.
\end{itemize}

\subsection{Prediction 2: Gravitationally-Modulated Delayed-Choice Erasers}
TLM predicts that interference in a delayed-choice quantum eraser is restored by revealing a timelessly valid instruction, not by retrocausality. It further predicts this rendering process can be modulated by gravitational potential. (See Appendix C.3.2).

\subsubsection*{Feasibility Estimate}
\begin{itemize}
    \item \textbf{Method:} Construct a quantum eraser where one arm of the interferometer passes through a region with a variable gravitational potential.
    \item \textbf{Challenge \& Outlook:} This experiment is likely **unfeasible with current tabletop technology**. However, it could become viable in a **space-based setting** where larger path lengths and gravitational potential differences can be achieved.
\end{itemize}

\subsection{Prediction 3: Frame-Dependent Rendering Near Event Horizons}
TLM interprets extreme gravitational time dilation as rendering latency. It predicts that for an entangled pair where one particle falls towards a black hole, its "collapse" (rendering) will appear anomalously delayed for a distant observer. (See Appendix C.3.3).

\subsubsection*{Feasibility Estimate}
\begin{itemize}
    \item \textbf{Method:} An astrophysical observation of entangled particles where one particle's trajectory takes it very close to a supermassive black hole.
    \item \textbf{Challenge \& Outlook:} Maintaining quantum entanglement over galactic distances is a monumental obstacle. This remains a **thought experiment for the foreseeable future**, requiring revolutionary advances in quantum astronomy.
\end{itemize}

\subsection{Prediction 4: Indefinite Superposition Without an Absorber}
TLM rejects passive environmental decoherence, positing that a quantum system remains in superposition until a valid absorption endpoint triggers rendering. (See Appendix C.3.4 and Figure \ref{fig:decoherence_plot}).

\subsubsection*{Feasibility Estimate}
\begin{itemize}
    \item \textbf{Method:} This aligns directly with ongoing research in quantum computing, which aims to maximize qubit coherence times.
    \item \textbf{Challenge \& Outlook:} This is **highly feasible** and is, in effect, already being pursued. TLM offers a different interpretation of the results: coherence time is limited only by the leakage rate of rendering triggers (unintended absorbers).
\end{itemize}

% --- SECTION 6: PHILOSOPHICAL IMPLICATIONS ---
\section{Philosophical and Ontological Implications}
TLM repositions our understanding of reality itself, asserting that observer-relative causal sequencing governs rendered dynamics.
\begin{itemize}
    \item \textbf{Time as Delay:} Following Mach, Poincaré, and Einstein \cite{einstein_gr_1916}, TLM pushes the relational view of time to its limit: there is no flowing time, only delay \cite{barbour_nature_2009}. Its interpretation aligns with the foundational ideas of relational quantum mechanics \cite{rovelli_relational_1996} but gives a specific mechanism (rendering delay) for the emergence of a temporal perspective.
    \item \textbf{Instructional Reality:} Recalling Feynman's sum-over-histories \cite{feynmanQED}, TLM removes the need for rejected paths—only the valid instruction is ever written. This touches on the debate over the reality of the quantum state, offering an alternative to purely epistemic views by grounding information in the ontology of the QP \cite{pusey_reality_2012}.
    \item \textbf{The Observer as a Structural Necessity:} TLM builds on Wheeler's “participatory universe” \cite{wheeler_itfrombit} but without invoking consciousness as a mystical agent. Observation corresponds to absorption, which triggers the rendering of a completed causal instruction arc (CI-ARC) \cite{mckinley2025collapse}.
\end{itemize}

% --- SECTION 7: INTEGRATION WITH KNOWN THEORIES ---
\section{Integration with Known Theories}
TLM reinterprets QM and GR within a unified deployment logic, preserving their mathematical structures.

\subsection{Quantum Mechanics as Terrain Constraints}
The wavefunction \( \psi \) is a static, structural filter. The Born rule is not a law of probability but of match frequency between the terrain and a valid causal instruction arc (CI-ARC)\cite{born1926}.

\subsection{General Relativity as Delay Engine}
Spacetime curvature is a delay map governing the timing of rendering. Black hole entropy reflects informational rendering capacity, not just thermodynamics \cite{bekenstein1973blackhole, hawking1975particle}.

\subsection{Critiques and Comparisons to Alternative Models}
While TLM offers a novel framework, it must be compared with other interpretations and withstand potential critiques.
\begin{itemize}
    \item \textbf{Is TLM a Non-Empirical Re-labeling?} A primary critique might be that TLM merely re-labels established concepts. However, this re-labeling is not superficial; it redefines the causal structure, generating specific, falsifiable predictions (Sec. 5).
    \item \textbf{The Nature of the Quantum Platform:} The QP, as a non-spatiotemporal substrate, is axiomatically non-empirical. Its role is analogous to foundational-yet-unobservable constructs in other theories, such as the Everettian multiverse \cite{everett1B57} or the block-universe of eternalism. Its validity is judged by its ability to provide a more parsimonious and causally coherent explanation.
    \item \textbf{Comparison to Timeless Physics:} TLM shares philosophical ground with approaches based on the Wheeler-DeWitt equation \cite{dewitt1967} or Barbour's "Platonia" \cite{barbour_nature_2009}. TLM differs by proposing the two-layer QP/SDF mechanism and the principle of \textit{rendering for frame-relative deployment of completed causal instructions"}.
    \item \textbf{Comparison to Constructor Theory:} TLM's focus on "causal instruction arcs" (CI-ARC) resonates with Deutsch's Constructor Theory \cite{deutsch2013}. A CI-ARC can be seen as a completed "construction," and TLM provides a physical ontology for these constructions.
\end{itemize}

\subsection{The TLM Stack}
The integration is hierarchical, as shown in Figure \ref{fig:causal-hierarchy-new}.
\begin{figure}[H]
\centering
\begin{tikzpicture}[
    layer/.style={rectangle, draw, minimum width=6.5cm, minimum height=1.5cm, align=center, rounded corners=6pt, font=\normalsize},
    arrow/.style={->, thick},
    node distance=1.8cm
]

% QP Layer
\node[layer, fill=blue!10] (QP) {
  \textbf{Quantum Platform (QP)}\\
  {\footnotesize Timeless, Completed Instructions}
};

% Filters Layer
\node[layer, fill=orange!10, below=of QP] (filters) {
  \textbf{Experiential Filters}\\
  {\footnotesize GR (Delay Filter)\quad+\quad QM (Structural Filter)}
};

% SDF Layer
\node[layer, fill=green!10, below=of filters] (SDF) {
  \textbf{Spacetime Deployment Frame (SDF)}\\
  {\footnotesize Rendered, Sequential Experience}
};

% Arrows
\draw[arrow] (QP) -- node[right] {\small Deployment} (filters);
\draw[arrow] (filters) -- node[right] {\small Rendering} (SDF);

\end{tikzpicture}
\caption{The causal hierarchy in the Timeless Light Model. Timeless instructions are authored in the Quantum Platform (QP), filtered by GR (delay) and QM (structure), and rendered into experience via the Spacetime Deployment Frame (SDF).}
\label{fig:causal-hierarchy-new}
\end{figure}


































% --- SECTION 8: CONCLUSION ---
\section{Conclusion}
The Timeless Light Model challenges foundational assumptions at the intersection of quantum mechanics, general relativity, and philosophy. It claims that no particle travels, no wave collapses, and no time flows. The universe, under TLM, is not a machine evolving forward in time, but a pre-resolved dataset selectively rendered as observer-relative events under delay and constraint. TLM implies that the universe is not designed for deterministic computation, but for sequential observables under delay and constraint. These claims are not mere speculation. TLM makes clear, testable predictions that diverge from standard interpretations. This paper calls not for the abandonment of established physics but for its reinterpretation under the more parsimonious premise of delay-based rendering. We invite the community to consider the possibility that what we've been calling "time" is not fundamental—but merely delay in a universe where all outcomes were always resolved.

% --- BIBLIOGRAPHY ---
\begin{thebibliography}{99}
\bibitem{ligo_residuals_2023} R. Abbott et al. (LIGO Scientific, Virgo, and KAGRA Collaborations), “Search for deviations from general relativity in the remnant black hole signal in the GWTC-3 catalog,” \textit{Phys. Rev. D} \textbf{108}, 102003 (2023).
\bibitem{barbour_nature_2009} J. B. Barbour, “The Nature of Time,” arXiv:0903.3489 [gr-qc], 2009.
\bibitem{bekenstein1973blackhole} J. D. Bekenstein, “Black holes and entropy,” \textit{Phys. Rev. D} \textbf{7}, 2333 (1973).
\bibitem{bell_against_measurement_1990} J. S. Bell, “Against ‘measurement’,” \textit{Physics World} \textbf{3}(8), 33–40 (1990).
\bibitem{born1926} M. Born, “Zur Quantenmechanik der Stoßvorgänge,” \textit{Z. Phys.} \textbf{37}, 863–867 (1926).
\bibitem{caticha2011} A. Caticha, “Entropic Dynamics, Time and Quantum Theory,” \textit{J. Phys. A} \textbf{44}, 225303 (2011).
\bibitem{deutsch2013} D. Deutsch, “Constructor theory,” \textit{Synthese} \textbf{190}, 4331–4359 (2013).
\bibitem{dewitt1967} B. S. DeWitt, “Quantum Theory of Gravity. I. The Canonical Theory,” \textit{Phys. Rev.} \textbf{160}, 1113–1148 (1967).
\bibitem{einstein_gr_1916} A. Einstein, “The Foundation of the General Theory of Relativity,” \textit{Annalen der Physik}, 354(7):769–822, 1916.
\bibitem{everett1B57} H. Everett, “‘Relative State’ Formulation of Quantum Mechanics,” \textit{Rev. Mod. Phys.} \textbf{29}, 454–462 (1957).
\bibitem{feynmanQED} R. P. Feynman, \textit{QED: The Strange Theory of Light and Matter} (Princeton University Press, 1985).
\bibitem{griffithsQM} D. J. Griffiths, \textit{Introduction to Quantum Mechanics}, 3rd ed. (Cambridge University Press, 2018).
\bibitem{hawking1975particle} S. W. Hawking, “Particle creation by black holes,” \textit{Commun. Math. Phys.} \textbf{43}, 199–220 (1975).
\bibitem{jacobson1995} T. Jacobson, “Thermodynamics of Spacetime: The Einstein Equation of State,” \textit{Phys. Rev. Lett.} \textbf{75}, 1260–1263 (1995).
\bibitem{penrose_road_2004} R. Penrose, \textit{The Road to Reality: A Complete Guide to the Laws of the Universe}. Jonathan Cape, 2004.
\bibitem{pusey_reality_2012} M. F. Pusey, J. Barrett, and T. Rudolph, “On the reality of the quantum state,” \textit{Nature Phys.} \textbf{8}, 475–478 (2012).
\bibitem{rovelli_relational_1996} C. Rovelli, “Relational quantum mechanics,” \textit{Int. J. Theor. Phys.} \textbf{35}, 1637–1678 (1996).
\bibitem{ryu_holographic_2006} S. Ryu and T. Takayanagi, “Holographic Derivation of Entanglement Entropy from AdS/CFT,” \textit{Phys. Rev. Lett.} \textbf{96}, 181602 (2006).
\bibitem{verlinde2011} E. Verlinde, “On the Origin of Gravity and the Laws of Newton,” \textit{J. High Energ. Phys.} \textbf{2011}, 29 (2011).
\bibitem{waldGR} R. M. Wald, \textit{General Relativity} (University of Chicago Press, 1984).
\bibitem{wheelerDelayed} J. A. Wheeler, “The ‘Past’ and the ‘Delayed-Choice’ Double-Slit Experiment,” in \textit{Mathematical Foundations of Quantum Theory}, edited by A. R. Marlow (Academic Press, 1978), pp. 9–48.
\bibitem{wheeler_itfrombit} J. A. Wheeler, “Information, Physics, Quantum: The Search for Links,” in \textit{Complexity, Entropy, and the Physics of Information}, edited by W. H. Zurek. Addison-Wesley, 1990.
\bibitem{mckinley2025collapse} J. C. W. McKinley, \textit{Observer-Dependent Spacetime Collapse as a Relational Artifact of the Spacetime Deployment Frame}, Zenodo (2025), \href{https://doi.org/10.5281/zenodo.15770329}{doi:10.5281/zenodo.15770329}.
\bibitem{mckinley_photons_2025} J. C. W. McKinley, \textit{The Photon's Exile: A GR-Based Proof That Light Is Not Embedded in Spacetime}, Zenodo (2025), \href{https://doi.org/10.5281/zenodo.16076902}{doi:10.5281/zenodo.16076902}.
\bibitem{mckinley_tlm_2025} J. C. W. McKinley, \textit{The Timeless Light Model: A Unified Framework for Physics and Cosmology}, Zenodo (2025), \href{https://doi.org/10.5281/zenodo.15868624}{doi:10.5281/zenodo.15868624}.
\bibitem{mckinley_csubs_2025} J. C. W. McKinley, \textit{Clarifying \(C_s\): Deployment Rate, Delay, and Simulation Parameters in the Timeless Light Model}, Zenodo (2025), \href{https://doi.org/10.5281/zenodo.16019797}{doi:10.5281/zenodo.16019797}.
\bibitem{mckinley_synthesis_2025} J. C. W. McKinley, \textit{Foundational Equations and Axiomatic Structure of the Timeless Light Model}, Zenodo (2025), \href{https://doi.org/10.5281/zenodo.16187719}{doi:10.5281/zenodo.16187719}.
\end{thebibliography}

% --- APPENDICES ---
\appendix
\section{Formal Axioms of the TLM}
\begin{enumerate}[label=\textbf{A\arabic*.}, wide, labelwidth=!, labelindent=0pt]
\item \textbf{Timeless Instruction Authoring.} All physical events originate as complete causal arcs authored on a timeless Quantum Platform (QP).

\item \textbf{Causal Rendering Sequence.} The Spacetime Deployment Frame (SDF) presents prewritten instructions as temporally ordered observables constrained by delay.


\item \textbf{Wavefunction as Terrain Filter.} The wavefunction is a static terrain filter determining which arcs are validly writable.
\item \textbf{Collapse as Rendering, Not Process.} Measurement is the rendering of a valid causal  instruction arc (CI-ARC).
\item \textbf{Mass–Delay Duality.} The relation \( T \cdot m = \hbar / c^2 \) defines a duality between mass and delay.
\item \textbf{Entanglement as Shared Instruction.} Entangled particles are endpoints of a single, timeless CI-ARC.
\item \textbf{Horizon as Rendering Limit.} An event horizon is a deployment boundary where no new instructions can be rendered.
\end{enumerate}












\begin{figure}[h!]
\centering
\begin{tikzpicture}[
  node distance=2.5cm,
  every node/.style={align=left, font=\small, rounded corners, minimum width=5.5cm, minimum height=1.2cm, draw=black, fill=blue!5, text width=8cm},  % Added text width=5cm for wrapping
  arrow/.style={-{Latex}, thick}
]

% Nodes matching the text axioms
\node (axiom1) {Axiom 1:\\ \textbf{Timeless Instruction Authoring.} All physical events originate as complete causal arcs authored on a timeless Quantum Platform (QP).};
\vspace{1cm}
\node (axiom2) [below of=axiom1] {Axiom 2:\\ \textbf{Causal Rendering Sequence.} The Spacetime Deployment Frame (SDF) presents prewritten instructions as temporally ordered observables constrained by delay.};

\node (axiom3) [below of=axiom2] {Axiom 3:\\ \textbf{Rendering via Delay.} Time is not a flow but a delay \( T \) imposed by mass and gravity.};
\node (axiom4) [below of=axiom3] {Axiom 4:\\ \textbf{Wavefunction as Terrain Filter.} The wavefunction is a static terrain filter determining which arcs are validly writable.};
\node (axiom5) [below of=axiom4] {Axiom 5:\\ \textbf{Collapse as Rendering, Not Process.} Measurement is the rendering of a valid causal instruction arc (CI-ARC).};
\node (axiom6) [below of=axiom5] {Axiom 6:\\ \textbf{Mass–Delay Duality.} The relation \( T \cdot m = \hbar / c^2 \) defines a duality between mass and delay.};
\node (axiom7) [below of=axiom6] {Axiom 7:\\ \textbf{Entanglement as Shared Instruction.} Entangled particles are endpoints of a single, timeless CI-ARC.};
\node (axiom8) [below of=axiom7] {Axiom 8:\\ \textbf{Horizon as Rendering Limit.} An event horizon is a deployment boundary where no new instructions can be rendered.};

% Arrows
\draw[arrow] (axiom1) -- (axiom2);
\draw[arrow] (axiom2) -- (axiom3);
\draw[arrow] (axiom3) -- (axiom4);
\draw[arrow] (axiom4) -- (axiom5);
\draw[arrow] (axiom5) -- (axiom6);
\draw[arrow] (axiom6) -- (axiom7);
\draw[arrow] (axiom7) -- (axiom8);

\end{tikzpicture}
\caption{Flow of logic in the Timeless Light Model (TLM). Each axiom builds on the prior, beginning with the timeless authoring on QP and culminating in horizons as rendering limits.}
\label{fig:tlm_axioms_flow}
\end{figure}







\clearpage




\subsection{Glossary of Key Terms}

This glossary defines core terminology used in TLM, drawing from the axiomatic synthesis \cite{mckinley_synthesis_2025}. Terms are listed alphabetically for reference.

\begin{description}
  \item[Causal Instruction Arc (CI-ARC)] A complete emission-to-absorption instruction on the QP, linking endpoints timelessly without propagation or intermediate states.
  
  \item[CI‑Arcs] Consciousness‑Information Arcs: Internal mechanisms or syntactic processes within the Quantum Platform (QP) that may influence \emph{what} event is rendered (e.g., instruction selection or syntax). However, they do not create or modulate the GR playground; they operate within it, subject to delay effects imposed by QsubGR. CI‑Arcs handle deployment triggers but not the slowing laws of gravity or time dilation.
  
  \item[\(C_s\) (Causal Speed)] The rate at which timeless instructions from QP are resolved into sequential spacetime events in the Spacetime Deployment Frame (SDF). Inversely proportional to rendering delay \(T\), ensuring causality is preserved at or below the speed of light \(c\).
  
  \item[Delay Gradient] A localized variation in rendering delay induced by mass, creating the perceptual effect of gravitational attraction (e.g., the “space river” flowing inward). Delay decreases toward mass, drawing unresolved instructions toward equilibrium.
  
  \item[Geodesic] In GR, the straightest path in curved spacetime; in TLM, a path of least delay resolution, where free‑falling objects naturally progress toward lower‑delay states without force.
  
  \item[GR (General Relativity)] Einstein’s theory of gravity as spacetime curvature; in TLM, subordinated to QP as a descriptive geometry emerging from delay modulation, not a fundamental arena.
  
  \item[Instructional Photon] A photon reinterpreted as a timeless causal instruction rather than a propagating particle; its effects (e.g., interference) arise from delayed rendering in the SDF.
  
  \item[Pre-Resolved Instruction] A fundamental causal directive authored on the QP in a timeless state, fully complete before deployment; forms the "pre-resolved, timeless instruction layer" from which all spacetime observables emerge via filtering and delay.
  
  \item[QP (Quantum Platform)] The timeless, pre‑resolved layer that issues instructions for the universe. Ontologically senior to GR, QP operates outside spacetime, with all observables deploying from it via delayed rendering.
  
  \item[QsubGR] The GR‑modulated substrate: A delay‑imposing mechanism subordinate to QP, enforcing variable resolution rates (e.g., gravity, time dilation) to stretch instantaneous instructions into experiential sequences limited by \(c\).
  
  \item[Rendering Delay (\(T\))] The temporal lag in resolving QP instructions into the SDF, proportional to mass inverse (\(T \cdot m = \hbar / c^2\)). Exists to produce observer-consistent outcomes, unifying GR phenomena like time dilation and attraction.
  
  \item[SDF (Spacetime Deployment Frame)] The observable arena where delayed QP instructions manifest as spacetime events; equivalent to GR’s curved geometry but reinterpreted as a rendered projection, not intrinsic fabric.
  
  \item[Space River] A metaphor for GR’s inward‑flowing spacetime near mass (e.g., in black hole river models); in TLM, an engineered delay effect where space appears to “disappear” into planets to enforce rendering gradients, demystifying why stationary objects fall.
  
  \item[TLM (Timeless Light Model)] The overarching framework proposing that light (photons) is timeless, and the universe deploys from QP instructions via delays, providing causal “why” for GR’s descriptive “what.”
  
  \item[Timeless Instruction] A pre‑resolved directive from QP linking events (e.g., emission to absorption) without traversal; photons exemplify this, experiencing \(\tau = 0\) and resolving instantly (\(T = 0\)).
\end{description}

\section{What This Model Rejects}
To clarify the boundaries of this revised model, it is useful to state what it explicitly rejects:
\begin{tcolorbox}[
  colback=gray!5,
  colframe=black!80,
  title={Key Rejections in the Timeless Light Model},
  fonttitle=\bfseries,
  boxrule=0.7pt,
  sharp corners=southwest,
  width=\textwidth,
  before skip=10pt,
  after skip=10pt
]
\begin{itemize}[leftmargin=*]
  \item \textbf{The Wavefunction as a Physical Wave:} The wavefunction does not propagate, evolve, or carry energy. It is a static rule-set.
  \item \textbf{The Wavefunction as a Delay Mechanism:} The experience of time and delay is governed by mass and gravity, entirely separate from the wavefunction.
  \item \textbf{Wavefunction Collapse:} Since the wavefunction is a static set of rules, it cannot "collapse." Measurement provides a boundary condition that allows a single, compliant instruction to be authored.
  \item \textbf{Ontological Superposition:} A particle is never in multiple states at once. There is only a single, timeless instruction that is rendered. Apparent superposition is a reflection of the multiple permissible routes through the wavefunction's terrain.
  \item \textbf{Wave-Particle Duality:} There is only the timeless instruction (on the QP) and its rendered appearance (in the SDF). The wave-like or particle-like behavior observed is an artifact of the interaction between the rendered instruction and the filters (delay and structural) of the SDF.
\end{itemize}
\end{tcolorbox}

\section{Conceptual Derivations and Calculations}
This appendix outlines conceptual steps for recovering cornerstone equations and quantifies experimental predictions.

\subsection{Recovering the EFE via Entropic Dynamics}
The EFE can be viewed as an equation of state for spacetime \cite{jacobson1995, verlinde2011}. TLM provides a natural basis for this perspective.
\begin{enumerate}
    \item \textbf{Premise:} Assume the holographic principle. The information about a volume in the SDF is encoded on its boundary. In TLM, this information corresponds to the set of valid causal instruction arcs (CI-ARC) \(H\) that can terminate within that volume.
    \item \textbf{Instructional Entropy:} The entropy \(S\) of the boundary is given by the TLM entropy axiom: \(S = k_B \ln H\), which is proportional to the area \(A\): \(S = k_B A / (4 \ell_P^2)\).
    \item \textbf{Rendering and Heat:} For an accelerating observer, the Unruh effect predicts a thermal bath. In TLM, this "heat" is the energy flux associated with the \textit{rendering} of CI-ARCs across the observer's Rindler horizon.
    \item \textbf{Equation of State:} By demanding that the first law of thermodynamics, \(\delta Q = T dS\), holds for all local Rindler horizons, one finds that the geometry of spacetime (related to \(R_{\mu\nu}\)) must be proportional to its energy-momentum content (\(T_{\mu\nu}\)). This constraint resolves to the EFE: \( R_{\mu\nu} - \frac{1}{2} R g_{\mu\nu} = \frac{8\pi G}{c^4} T_{\mu\nu} \).
\end{enumerate}

\subsection{Recovering the SE from Information Dynamics}
The SE can be derived using principles of entropic inference \cite{caticha2011}.
\begin{enumerate}
    \item \textbf{Premise:} A particle's state is a probability distribution \(\rho(x)\) over the \textbf{wavefunction terrain}. \(\rho(x) = |\psi(x)|^2\) represents the density of valid instruction endpoints.
    \item \textbf{Entropic Time:} Time is a parameter \(t\) that orders the sequence of \textbf{rendering delay}.
    \item \textbf{Dynamics:} Maximizing an entropy functional subject to constraints leads to a Fokker-Planck diffusion equation. The geometry of the wavefunction terrain introduces a \textbf{quantum potential}, distinguishing the dynamics from classical diffusion.
    \item \textbf{The Equation:} Combining the Fokker-Planck equation with its conjugate via a complex variable \(\Psi = \sqrt{\rho} e^{i\phi}\) yields the time-dependent Schrödinger Equation: \( i\hbar \frac{\partial \Psi}{\partial t} = \left( -\frac{\hbar^2}{2m} \nabla^2 + V \right) \Psi \). In TLM, this is an equation of entropic inference describing how knowledge of instruction endpoints updates over the sequence of rendering delay.
\end{enumerate}

\subsection{Illustrative Calculations for Experimental Predictions}\label{appendix:calculations}
This section provides simple models to quantify the feasibility of the predictions made in Section 5.

\subsubsection{C.3.1 Back-of-the-Envelope-Calculation for LIGO Residuals}
\begin{itemize}
    \item \textbf{The Model:} Let the signal recorded by the detector be $D(t) = h(t) + r(t) + n(t)$, where $h(t)$ is the true GR signal, $r(t)$ is the predicted TLM residual, and $n(t)$ is the detector noise with standard deviation $\sigma_n$.
    \item \textbf{The Postulate:} Let's hypothesize a TLM residual signal with an effective strain amplitude $\sigma_r$ that is significantly smaller than the detector noise, e.g., $\sigma_n \approx 10^{-23} \text{ strain}/\sqrt{\text{Hz}}$ and $\sigma_r \approx 10^{-25} \text{ strain}/\sqrt{\text{Hz}}$.
    \item \textbf{The Analysis:} After subtracting the best-fit GR template, we are left with the residual data $R(t) \approx r(t) + n(t)$. To detect $r(t)$, we average over $N$ events. The noise in the averaged signal decreases as $\sigma_{\text{avg}} = \sigma_n / \sqrt{N}$.
    \item \textbf{Feasibility Calculation:} To achieve a detection with a signal-to-noise ratio (SNR) of 1 (where $\sigma_{\text{avg}} \approx \sigma_r$), we need $N \approx (\sigma_n / \sigma_r)^2$. For our postulated values:
    \[ N \approx \left( \frac{10^{-23}}{10^{-25}} \right)^2 = (100)^2 = 10,000 \]
    \item \textbf{Conclusion:} This suggests that detecting a TLM residual would require coherently stacking the residuals of approximately **10,000 high-quality gravitational wave events**.
\end{itemize}
\begin{figure}[h!]
\centering
\begin{tikzpicture}
\begin{axis}[
    width=\textwidth, height=6cm,
    title={Conceptual Model of LIGO Residual Analysis},
    xlabel={Time (ms)}, ylabel={Strain (arbitrary units)},
    legend style={at={(0.5,-0.25)},anchor=north, legend columns=-1},
    grid=major, no markers, yticklabel style={/pgf/number format/fixed, /pgf/number format/precision=1},
]
% Raw Data (Signal + High Noise)
\addplot[gray, domain=0:10, samples=201, opacity=0.6] {10*sin(x*36) + 5*(rand-0.5)}; \addlegendentry{Detector Data (Single Event)}
% GR Template Fit
\addplot[blue, thick, domain=0:10, samples=101] {10*sin(x*36)}; \addlegendentry{Best-Fit GR Template}
% TLM Residual (Stacked from many events)
\addplot[red, very thick, domain=0:10, samples=101] {0.5*sin(x*36+180) + 0.1}; \addlegendentry{Stacked Residual (Reveals TLM Signal)}
\end{axis}
\end{tikzpicture}
\caption{A plot illustrating the search for a TLM residual. After subtracting the GR template from noisy data and stacking many events, a systematic, non-GR residual signal may be revealed.}
\label{fig:ligo_residual_plot}
\end{figure}

\subsubsection{C.3.2 Estimate for Gravitational Modulation}
\begin{itemize}
    \item \textbf{The Model:} A quantum eraser's interference visibility depends on the indistinguishability of two paths. A gravitational potential difference $\Delta\Phi$ between the paths introduces a relative time delay via gravitational time dilation, $\Delta t = t_0 (\Delta\Phi/c^2)$.
    \item \textbf{TLM Interpretation:} In TLM, this $\Delta t$ is a real difference in rendering delay. This difference should introduce a phase shift $\Delta\phi = \omega \Delta t$, where $\omega$ is the photon's frequency.
    \item \textbf{Calculation:} Consider a 1-meter tabletop experiment with a 1000 kg mass brought near one path. The potential difference is roughly $\Delta\Phi \sim GM/R \approx (6.67\times10^{-11})(1000)/0.1 \approx 6.7\times10^{-7}$ J/kg. The fractional time delay is $\Delta\Phi/c^2 \approx 7.4\times10^{-24}$. For a visible light photon ($\omega \approx 10^{15}$ Hz) traveling for $\sim 3$ ns, the phase shift is minuscule ($\sim 10^{-8}$ radians), confirming this is unfeasible in a lab.
\end{itemize}

\subsubsection{C.3.3 Estimate for Black Hole Rendering Delay}
\begin{itemize}
    \item \textbf{The Model:} The time dilation for an observer at radius $r$ from a black hole of mass $M$ relative to a distant observer is given by $\gamma = 1/\sqrt{1 - 2GM/rc^2}$.
    \item \textbf{TLM Interpretation:} This factor $\gamma$ directly scales the rendering delay.
    \item \textbf{Calculation:} For a photon detected at $r = 3 R_S$ (where $R_S = 2GM/c^2$ is the Schwarzschild radius), the rendering delay for a distant observer is scaled by $\gamma = 1/\sqrt{1-2/3} \approx 1.73$. At $r = 1.1 R_S$, the delay is scaled by $\gamma \approx 3.3$. As $r \to R_S$, the rendering delay $\gamma \to \infty$. This confirms that the rendering time becomes extreme near the horizon.
\end{itemize}
\clearpage

\subsubsection{C.3.4 Simulation Model for Decoherence Limits}
\begin{itemize}
    \item \textbf{TLM Model:} Decoherence is a Poisson process where the probability of a system remaining coherent up to time $t$ is $P_{\text{coherent}}(t) = e^{-\Gamma t}$, with $\Gamma$ being the rate of unintended rendering events.
    \item \textbf{Falsifiable Prediction:} TLM predicts that $\Gamma$ is **not fundamental** but is directly proportional to shielding effectiveness. Improving shielding to reduce particle flux by a factor of 5 should increase the measured coherence time ($T_2=1/\Gamma$) by a factor of 5.
\end{itemize}
\begin{figure}[h!]
\centering
\begin{tikzpicture}
\begin{axis}[
    width=0.7\textwidth, height=5cm,
    xlabel={Time (arbitrary units)}, ylabel={$P_{\text{coherent}}(t)$},
    xmin=0, xmax=5, ymin=0, ymax=1.1,
    legend pos=north east, grid=major,
]
\addplot[domain=0:5, thick, blue, samples=100] {exp(-x)}; \addlegendentry{$\Gamma = 1.0$}
\addplot[domain=0:5, thick, red, dashed, samples=100] {exp(-0.2*x)}; \addlegendentry{$\Gamma = 0.2$ (Better Shielding)}
\end{axis}
\end{tikzpicture}
\caption{Illustration of the TLM decoherence model. Improving shielding reduces the rendering event rate ($\Gamma$), leading to a longer coherence lifetime.}
\label{fig:decoherence_plot}
\end{figure}

\end{document}

```

</details>

---
{% endraw %}
