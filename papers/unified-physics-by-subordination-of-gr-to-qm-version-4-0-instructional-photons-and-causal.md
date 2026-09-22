---
layout: default
title: '[2025] Unified Physics by Subordination of GR to QM: Version 4.0 – Instructional Photons and Causal Rendering'
description: 'Publication metadata and archived raw LaTeX source by John C. W. McKinley.'
permalink: /papers/unified-physics-by-subordination-of-gr-to-qm-version-4-0-instructional-photons-and-causal/
paper: true
---
{% raw %}
# [2025] Unified Physics by Subordination of GR to QM: Version 4.0 – Instructional Photons and Causal Rendering
*   **DOI:** [10.5281/zenodo.16019797](https://doi.org/10.5281/zenodo.16019797)
*   **Date:** 17 July 2025

<details markdown="1">
<summary><b>Click to view Raw LaTeX Source</b></summary>

```latex
\documentclass[11pt]{article}

\usepackage[utf8]{inputenc}
\usepackage{amsmath, amssymb, geometry}
\usepackage{amsthm}
\usepackage{hyperref}
\usepackage{graphicx}
\usepackage{booktabs}
\usepackage{titlesec}
\usepackage{fancyhdr}
\usepackage{cleveref}
\usepackage{tcolorbox}
\usepackage{tikz}
\usetikzlibrary{arrows.meta, positioning, shapes.geometric}
\geometry{margin=1in}
\linespread{1.15}
\numberwithin{equation}{section}
\bibliographystyle{apsrev4-2}

\theoremstyle{definition}
\newtheorem{axiom}{Axiom}[section]
\newtheorem{law}[axiom]{Law}
\newtheorem{remark}[axiom]{Remark}

\title{
Unified Physics by Subordination of GR to QM:\\ Version 4.0 – Instructional Photons and Causal Rendering

}

\author{John C. W. McKinley \\ Independent Researcher \\ \href{https://orcid.org/0009-0005-7097-5035}{0009-0005-7097-5035}}
\date{July 2025}

\begin{document}

\maketitle

\renewcommand{\thefootnote}{}
\footnotetext{This version published at \href{https://doi.org/10.5281/zenodo.16019797}{10.5281/zenodo.16019797}.}
\renewcommand{\thefootnote}{\arabic{footnote}}






\begin{abstract}
We propose a conservative reformulation of physical causality under the Timeless Light Model (TLM). In this model, quantum phenomena such as tunneling, entanglement, and wavefunction collapse originate from a foundational, timeless instruction structure called the \textit{Quantum Platform} (Q). These quantum instructions either resolve instantaneously, outside of spacetime constraints, or are projected into the delayed, observable framework of classical General Relativity (GR). This projection is denoted $Q_{\text{GR}}$, the Spacetime Deployment Frame (SDF). Our formulation preserves all empirical predictions of GR and QM but reorganizes their relationship: \textbf{quantum mechanics is causally senior to GR, and GR arises as a rendered projection of quantum logic}. No new physics is introduced; rather, known phenomena are given a clarified causal structure.
\end{abstract}

\begin{tcolorbox}[
  colback=blue!3!white,
  colframe=blue!75!black,
  title=Core Thesis: GR is Governed by the Quantum Platform (Q)
]

\textbf{We propose that General Relativity (GR) arises as a rendered projection of timeless quantum instructions.} 
Every classical spacetime phenomenon — from motion to curvature to cosmological expansion — is the result of energy-based deployment events.

\medskip
\noindent
\textit{Clarification on GR Emergence:} \\ 
This model proposes that GR phenomena (e.g., curvature, motion, mass interactions) are rendered from \( Q \) when local energy conditions are met. 

\textbf{In contrast to theories that attempt to quantize spacetime geometry itself, the Timeless Light Model treats spacetime as a rendered projection of pre-resolved causal instructions.} 

\textit{Note on Causal Direction:} While we fully resolve the apparent circularity later in Section~\ref{sec:causalhierarchy} by clarifying that \( Q \) does not react to conditions in the SDF, it is important to prevent misreadings at this stage.

\textbf{This formulation is a projection into the SDF, not a physical constraint on \( Q \).} The Quantum Platform remains timeless and resolved; the energy condition simply expresses when a pre-resolved instruction becomes visible in the rendered frame.

\begin{itemize}
  \item \( \Delta E_{\text{SDF}} \) is the energy drop at the classical, GR-observable level,
  \item and \( Q \) is the timeless Quantum Platform, which governs when and how instructions are rendered into the SDF.
\end{itemize}
\end{tcolorbox}

\begin{tcolorbox}[
  colback=blue!3!white,
  colframe=blue!75!black,
  title=Implications
]

\textbf{Implications:}
\begin{itemize}
  \item \textit{Unification}: GR emerges as a rendered projection of quantum-governed triggers.
  \item \textit{Resolution of Paradoxes}: Wavefunction collapse, entanglement, and cosmogenesis are no longer violations of classical physics, but results of instructional deployment.
  \item \textit{Falsifiability}: Predicts observable thresholds in tunneling and entangled system behavior.
\end{itemize}

This framework unifies quantum mechanics and general relativity by subordinating the apparent smoothness of spacetime to a higher-order quantum control logic: the Quantum Platform.

\end{tcolorbox}

\section{Introduction}

Quantum Mechanics (QM) and General Relativity (GR) have long stood as the two dominant frameworks of modern physics. Each has delivered astonishing predictive success within its domain: GR governs the behavior of mass, curvature, and large-scale structure; QM governs the probabilistic and discrete dynamics of particles and fields. However, these two domains remain conceptually and structurally separate, leading to a persistent lack of unified theory.

This paper presents the foundational architecture of the Timeless Light Model (TLM), where quantum mechanics is causally senior to general relativity, with GR emerging as a rendered projection of timeless instructions in the Quantum Platform (Q). A companion paper~\cite{mckinley2025quantized} explores potential observational consequences, such as threshold-triggered effects mimicking quantized curvature.


The tension between GR and QM has been noted since the early days of modern physics. As Einstein famously resisted the indeterminacy of quantum theory, remarking that “God does not play dice with the universe”~\cite{einstein}, he maintained a preference for continuous, deterministic laws of nature. In contrast, Richard Feynman embraced quantum probability, arguing that it was not just a mathematical trick but a reflection of how nature truly operates. Feynman described quantum mechanics as “the best description of nature we have”~\cite{feynman}, despite its baffling implications. This paper navigates that historical tension by proposing a structural hierarchy: both Einstein’s deterministic geometry and Feynman’s probabilistic amplitudes are valid — but the latter gives rise to the former through a controlled rendering process.

We suggest a different path. Rather than attempting to merge GR and QM through quantized geometry or extra dimensions, we propose a hierarchical realignment: \textbf{QM is not subordinate to GR; it is its source}. The behaviors governed by GR are not incompatible with QM — they are the displayed universe sourced from it.

The Timeless Light Model (TLM), originally developed to explain the unusual behavior of photons and delay~\cite{mckinley2025_causal, mckinley2025_causalrate}, is here extended to a general framework of causal hierarchy. What we observe as spacetime — mass, motion, gravity, light — is a delayed execution of selected Q instructions, denoted $Q_{\text{GR}}$. These projected instructions define what we call the \textit{Spacetime Deployment Frame} (SDF).

In this model, spacetime is not a container but an \textit{experiential display}. It is the visual rendering of quantum logic under causal delay. The universe thus consists of two structurally distinct but causally linked components:
\begin{equation}
    \text{Universe} = Q + Q_{\text{GR}} \quad \text{where} \quad Q_{\text{GR}} \equiv \text{SDF}
\end{equation}

\textbf{Foundational Delay–Rate Law.} \\
The rendering process that determines how and when instructions from Q appear in the SDF is governed by a delay–rate invariant:

\begin{equation}
T \cdot C_s = 1
\end{equation}

This delay–rate invariant was introduced as a causal rendering law in prior work~\cite{mckinley2025_causalrate}.

Here:
\begin{itemize}
  \item \( T \) is the delay (in seconds) between a timeless resolution in Q and its rendered appearance in the SDF,
  \item \( C_s \) is the causal deployment rate (in s\(^{-1}\)) — a measure of how quickly the instruction is deployed.
\end{itemize}

For instructions with \( T = 0 \) (e.g., tunneling or entanglement), the causal rate \( C_s = \infty \): these events are rendered without delay. For high-delay instructions (e.g., massive objects), \( C_s \) becomes small, indicating a slow deployment. This law grounds the model's treatment of mass, time, and rendering priority in a simple, testable invariant.

\subsection{Bootstrapping the First Frame}
\label{sec:bootstrap}

In the Timeless Light Model, the apparent paradox of a first rendering — such as the Big Bang — is resolved by the timeless structure of the instruction set \( Q \). The earliest rendered instruction does not require a pre-existing SDF with energy deltas; instead, it is a logically complete instruction whose conditions are trivially satisfied in the absence of delay. From the observer's point of view, this first projection appears as the start of history. From Q’s perspective, it simply always was.

This resolves the “chicken-and-egg” problem by reclassifying triggers not as temporal causes but as conditional gates within an eternally resolved instruction set. Rendering is delayed. Instruction is not.

\paragraph{Causal Note: No Reaction, Only Constraint.}
The Quantum Platform \( Q \) is not constrained by time and does not react to conditions in the SDF. Instead, it contains all instructions timelessly. When we describe an instruction as “triggered by an energy drop,” we mean that its rendering into the Spacetime Deployment Frame (SDF) occurs only under those constraints — not that Q waits or observes. The SDF is the delayed resolution layer, not the cause of instruction. In this view, the entire deployment structure is timelessly resolved and only "experienced" as contingent or responsive within the rendered frame.

\section{The Quantum Platform (Q)}

We define Q as a dimensionless, "always was, always will be" instruction set that contains all the causal logic required to generate physical reality. Q does not unfold in time, nor does it exist in space. It is not a field, not a waveform, and not a particle. Instead, Q is the source of all resolutions — instantaneous or delayed — that manifest as events in the observable universe.

Quantum events that appear strange from a relativistic standpoint — such as tunneling, entanglement, and wavefunction collapse — are natural in this framework. They are not propagations through space, but \textit{instruction resolutions} governed by Q. Some instructions resolve in such a way that they manifest within the spacetime framework (Q\textsubscript{GR}); others resolve entirely within Q, leaving no spacetime trail but still participating causally.

Crucially, Q is not hypothetical. Its necessity is inferred from the observed violation of relativistic constraints by quantum phenomena. In TLM, the behavior of photons — traveling without time; collapsing without continuity — already points to a time free resolution layer. We now generalize that principle to all of quantum mechanics.

The \textbf{Quantum Platform} (QPlatform, QP, Q) is the \emph{flat-time version of the universe} — a timefree, fully connected causal structure that encodes the entire reality’s instruction set as a static whole. It is the deeper, more fundamental layer, \emph{senior to General Relativity} and the spacetime framework.

From the QPlatform’s instructions, the \textbf{Spacetime Deployment Frame (SDF)} emerges by introducing \emph{delay} through the set of spacetime rules that transform the flat, instantaneous causal relations into the curved, time-evolving experience described by General Relativity.

Symbolically:
\[
\boxed{
Q + \text{Delay} = GR(SDF)
}
\]
where
\begin{itemize}
    \item \( Q \) represents the QPlatform: the universe in flat, timeless form,
    \item \text{Delay} is the introduction of time as a deployment parameter necessary for experience,
    \item \( GR(SDF) \) is the resulting curved spacetime, the deployed universe as experienced and observed.
\end{itemize}




\paragraph{Relation to Prior Work.}
A previous paper introduced a quantized rendering hypothesis, proposing that General Relativity observables might emerge from discrete threshold events governed by energy drop conditions (\(\Delta E_{\text{SDF}} \geq Q_k\)). That version emphasized falsifiability by predicting observable quantization noise in gravitational behavior. In contrast, the present paper abstracts from specific quantization claims and instead focuses on the architectural structure of the Quantum Platform as the primary controller of all rendered spacetime phenomena. Readers interested in experimental implications may consult the related work at~\cite{mckinley2025quantized}.






\begin{tcolorbox}[
  colback=gray!10,
  colframe=gray!75!black,
  title=Insights from Unpublished Prior Work: Timeless-Light and Mass-Bound Gravity (June 3rd 2025)\cite{mckinley2025unpublished}.

,
  sharp corners=south,
  fonttitle=\bfseries,
  boxrule=0.5pt
]

The following concepts are introduced here for the first time in published form, drawn from an unpublished draft dated June 3, 2025. They represent early explorations of the Timeless Light Model (TLM) and complement the current QPlatform architecture by emphasizing the photon's role as a timeless bridge:

\begin{itemize}
  \item \textbf{Photon as Timeless Transition}: A photon is not an object but a timeless event. It represents a causal bridge between two state-changes in the mass-bound world. This is not a particle traveling through space, but a massless instruction linking two massful configurations. A photon does not occupy time; it defines a relationship between mass-based events that do.
  
  \item \textbf{Light as Non-Spatial Instruction Set}: Light is not part of spacetime but a mechanism for updating it. It lives "behind the curtain" of observable physics, issuing update instructions to the mass-based world. Light doesn't move; it synchronizes massful events according to invariant constraints — chiefly, causality.
  
  \item \textbf{Universe as Two-Mode System}: The universe comprises timeless components (photons as Instruction Particles, Events, or Photons — representing causal instructions issued outside of spacetime) and time-bound components (massive particles, spacetime curvature, entropy-bearing matter). This duality explains anomalies as boundary effects between realms.
  
  \item \textbf{Time Emergence}: Time does not exist for timeless components. Instead, it is a property of the sequence of changes enacted by timeless instructions upon mass. What we call "duration" is a record of updates, not a backdrop.
  
  \item \textbf{Causal Finality and the Illusion of Becoming}: All photon-based causal relationships are fixed and resolved. The apparent unfolding is the expression of these instructions in slow motion, not their generation. Time-bound observers perceive this rollout as becoming, but from the timeless layer, all outcomes are already determined.
\end{itemize}

These ideas, mediated by the Blackbox Controller in the current framework, provide intuitive grounding for the QPlatform's timeless resolutions and SDF's delayed renderings.

\end{tcolorbox}







\section{The Layered Structure of Reality: From the Timeless QPlatform to Emergent Spacetime}

A core insight of the Timeless Light Model (TLM) is that the universe comprises two fundamentally different ontological layers. We express the universe as the sum of these layers:
\begin{equation}
    \text{Universe} = U_{\text{Platform}} + U_{\text{subGR}} = U_{\text{ZeroTime}} + U_{\text{RelativityTime}}.
\end{equation}

Here, \(U_{\text{Platform}}\) (also called \(U_{\text{ZeroTime}}\)) is the \emph{timeless quantum instruction layer}, or \emph{QPlatform (Q)}, which exists outside of time and contains the complete set of pre-resolved instructions governing all physical phenomena. The second layer, \(U_{\text{subGR}}\) (or \(U_{\text{RelativityTime}}\)), is the \emph{subordinate, emergent relativistic spacetime universe} that we experience, where time, causality, and mass manifest as delayed, rendered effects.

The existence of \(U_{\text{Platform}}\) introduces a second ontological surprise analogous to the discovery of relativistic time. Just as General Relativity revealed that time is not absolute but relative and malleable, the TLM reveals that beneath this relativistic time layer lies a domain where \emph{time does not exist at all} — a timeless foundation underpinning reality.

We postulate a hierarchical causal relationship linking these layers:
\begin{equation}
    U_{\text{Platform}} \quad \longrightarrow \quad \text{Blackbox Controller} \quad \longrightarrow \quad U_{\text{subGR}}.
\end{equation}

The \textbf{Blackbox Controller} is the causal interpreter or deployment mechanism that reads and executes instructions from the timeless QPlatform to produce the emergent spacetime universe \(U_{\text{subGR}}\). By characterizing this controller as a ``black box,'' we confess that the precise mechanism of this causal translation remains unknown. It is an epistemic boundary: while we can observe and describe \(U_{\text{subGR}}\), the internal operations of the Blackbox Controller and the timeless QPlatform remain hidden from direct observation.

This layered model elegantly captures the counterintuitive aspects of modern physics: the \emph{unexpected nature of relativistic time} and the \emph{even more unexpected nature of timelessness} underlying it. Rather than being paradoxes, these surprises become natural consequences of a universe structured as a timeless quantum platform whose instructions are causally deployed into a relativistic spacetime movie.

Many physical constants and dualities emerge naturally from this framework. In particular, the fundamental relation between mass \(m\) and deployment delay \(T\) is expressed as
\begin{equation}
    T \cdot m = 1,
\end{equation}
where \(T\) represents the causal deployment delay of instructions from \(U_{\text{Platform}}\) into \(U_{\text{subGR}}\). This expresses the reciprocal relationship between mass and delay in rendering spacetime effects.

Similarly, the causal speed \(C_s\) and the deployment delay satisfy
\begin{equation}
    T \cdot C_s = 1,
\end{equation}
establishing a universal causal speed limit intrinsic to the deployment process, distinct from the observed speed of light \(c\).

These dual laws unify the emergent spacetime properties as consequences of the fundamental timeless instruction execution.

\begin{figure}[ht]
    \centering
    \begin{tikzpicture}[
        node distance=3cm,
        box/.style={
            rectangle, 
            draw, 
            thick, 
            minimum width=5cm, 
            minimum height=2cm,
            align=center,
            fill=gray!10
        },
        arrow/.style={
            thick,
            -{Latex[length=3mm, width=2mm]},
        }
    ]
        % Nodes
        \node[box] (qplatform) {\Large \textbf{QPlatform (Q)}\\ \small Timeless Instruction Layer\\ \(U_{\text{Platform}} = U_{\text{ZeroTime}}\)};
        
        \node[box, below=of qplatform] (blackbox) {\Large \textbf{Blackbox Controller}\\ \small Causal Interpreter / Deployment Engine};

        \node[box, below=of blackbox] (subgr) {\Large \textbf{Emergent Spacetime}\\ \small Relativistic Universe Layer\\ \(U_{\text{subGR}} = U_{\text{RelativityTime}}\)};

        % Arrows
        \draw[arrow] (qplatform) -- (blackbox) node[midway,right,xshift=5pt] {\Large \(\longrightarrow\)};
        \draw[arrow] (blackbox) -- (subgr) node[midway,right,xshift=5pt] {\Large \(\longrightarrow\)};
        
        % Labels for equations
        \node[align=center, right=5cm of blackbox, text width=6cm] (eqs) {
            \Large \textbf{Key Relations:}\\[8pt]
            \(T \cdot m = 1\)\\
            \(T \cdot C_s = 1\)\\[8pt]
            \(\text{Universe} = U_{\text{Platform}} + U_{\text{subGR}}\)
        };

    \end{tikzpicture}
    \caption{Layered structure of the universe in the Timeless Light Model. The timeless QPlatform provides fundamental instructions that the Blackbox Controller causally deploys, producing the emergent relativistic spacetime layer.}
    \label{fig:layered-universe-tikz}
\end{figure}

This conceptual model provides a fertile ground for interpreting quantum phenomena such as entanglement, instantaneous correlations, and gravitational effects as reflections of the deployment process from the timeless QPlatform through the Blackbox Controller.

\section{The Black Box of Spacetime Curvature: Recognizing the Unknown Mechanism in General Relativity}

General Relativity (GR) revolutionized our understanding of gravity by describing it as the curvature of spacetime caused by mass and energy. The Einstein field equations,
\begin{equation}
    G_{\mu\nu} = \frac{8\pi G}{c^4} T_{\mu\nu},
\end{equation}
relate the geometry of spacetime, encoded in the Einstein tensor \(G_{\mu\nu}\), to the distribution of mass-energy represented by the stress-energy tensor \(T_{\mu\nu}\). These equations have been spectacularly successful in predicting phenomena ranging from the precession of Mercury’s orbit to gravitational waves.

However, despite this success, GR is fundamentally a \emph{descriptive} theory. It tells us \emph{what} spacetime curvature is and how it responds to mass-energy, but it does not explain \emph{how} or \emph{why} spacetime physically bends. There is no underlying microphysical or causal mechanism specified that mediates this bending.

In essence, the process by which mass-energy \emph{causally} generates curvature is a \textbf{black box} within current physical theory. The mathematical formalism treats the metric and curvature as fundamental dynamical entities without revealing their ontological origin or causal generation.

The Timeless Light Model (TLM) explicitly acknowledges this epistemic boundary by introducing the concept of the \textbf{Blackbox Controller}, a causal interpreter that mediates between the timeless instruction layer (\(U_{\text{Platform}}\), or QPlatform) and the emergent spacetime layer (\(U_{\text{subGR}}\)). This controller executes timeless quantum instructions and causally deploys them into the relativistic spacetime we observe, producing the geometry and dynamics described by GR.

This recognition of the black box:

\begin{itemize}
    \item Highlights a fundamental gap in our understanding of gravity and spacetime.
    \item Provides a conceptual framework to investigate \emph{how} spacetime curvature emerges causally from more fundamental principles.
    \item Aligns with analogous situations in physics where descriptive theories precede mechanistic explanations, such as quantum mechanics before quantum field theory or beyond.
\end{itemize}

By naming and embracing the Blackbox Controller, the TLM offers a roadmap to deepen the foundations of physics beyond the classical description of spacetime curvature, potentially uniting gravity with quantum phenomena under a common causal architecture.

Although some models propose that General Relativity must itself be quantized, our framework treats GR as a rendered illusion — emerging from the deployment of timeless, pre-resolved quantum instructions. Any apparent quantization of spacetime curvature would be a side-effect of instruction thresholds, not a fundamental trait of GR itself.

\bigskip

\noindent\textbf{Summary Equation:}

\begin{equation}
    G_{\mu\nu} = \frac{8\pi G}{c^4} T_{\mu\nu}
    \quad \Longrightarrow \quad
    \text{Curvature Emerges via Blackbox Controller from } U_{\text{Platform}}.
\end{equation}

\section{Lay Summary: What the Model Predicts}

A new quantum instruction is triggered instantly from outside of time. This instruction then causes something to “appear” in the observable universe.

\begin{itemize}
  \item A photon appears.
  \item A quantum state resolves.
  \item A correlated pair is deployed.
  \item A particle bypasses a barrier.
  \item An entire domain renders, e.g. Big Bang.
\end{itemize}

This framework treats our universe as a deployment zone, where instructions from a timeless layer are rendered only when specific trigger conditions are met.

\section{Hypothesis: All General Relativity Observables Are Rendered via Q-Platform Instructions}

\textbf{Proposal.} General Relativity (GR) observables — including motion, curvature, time dilation, gravitational waves, and expansion — are not fundamental. Rather, they are \textbf{rendered as projection events} governed by the Quantum Platform (Q). Each observable arises as an energy condition is met in the classical deployment level.

\textbf{Compatibility with Existing Theory.}
\begin{itemize}
  \item Quantum Field Theory discretizes particle interactions; this model extends similar structure to classical fields (e.g., gravity).
  \item The apparent smoothness of GR emerges from high-frequency, high-density deployments — analogous to how continuous images arise from digital pixels.
\end{itemize}

\textbf{Testable Predictions.}
\begin{itemize}
  \item \textbf{Tunneling and entanglement thresholds:} Look for minimum energy drops required to trigger quantum behaviors in low-energy regimes.
  \item \textbf{Delayed spacetime response:} Search for Planck-scale lags in curvature formation or gravitational wave propagation under controlled, high-mass, low-temperature conditions.
\end{itemize}

\textbf{Implication.} GR is not a fundamental continuum but an experiential rendering of Q instructions. The smooth laws of Einstein's equations emerge in a paced fashion, tamped down from "instant" to the appreciable speeds to which we are accustomed in the GR universe.

\begin{tcolorbox}[colback=gray!5!white, colframe=black!40!white, 
  title=On “Triggers” and Timeless Logic, 
  sharp corners=south, fonttitle=\bfseries, boxrule=0.5pt]

Though we speak of the Quantum Platform (Q) as "responding" to energy drops in the Spacetime Deployment Frame (SDF), this is not a temporal reaction. Q is timeless. Therefore, it does not wait, sense, or change. What we call a “trigger” is actually a conditional rendering — like a logical gate that already includes all future and past conditions in its structure.

Ignorance implies time: a "before" and "after" of knowing. But Q knows all things simultaneously. So the appearance of an event after a drop in energy is not Q reacting — it's Q already containing that conditional outcome, which is only made visible to us when the SDF state aligns with its activation condition.

\end{tcolorbox}

\section{The GR Projection: $Q_{\text{GR}}$ and the Spacetime Deployment Frame}

While Q encodes the total causal logic of the universe, only a subset of these instructions manifest in the delayed, curved, observable domain we associate with General Relativity. This subset is referred to as $Q_{\text{GR}}$, and it defines the \textbf{Spacetime Deployment Frame (SDF)}.

$Q_{\text{GR}}$ is not a portion of Q in a spatial or energetic sense, but a \textit{projection} — a rendered deployment — that obeys delay, locality, and curvature. These are the familiar behaviors of clocks, lightcones, and gravitational interaction. What is experienced as spacetime is thus an \textit{output} of Q logic, constrained and presented in a deployable, measurable format.

This projection behaves exactly as GR predicts because it is \textit{constrained to do so}. TLM does not modify the equations of general relativity; it simply asserts that their deployment occurs \textit{after} a Q instruction renders into the SDF.

It is important to emphasize that under the Timeless Light Model, General Relativity is not a substrate or geometrical entity that exists independently. Rather, it is a logic system — a rulebook — embedded within the Quantum Platform (Q) that governs how certain causal instructions are rendered into the delayed, curved format we associate with classical experience. In this sense, GR is not what is rendered — it is the formal logic by which delay and curvature are made visible.

\begin{figure}[ht]
\centering
\begin{tikzpicture}[
  node distance=1.6cm,
  every node/.style={font=\small, align=center},
  box/.style={
    rectangle, draw=black, thick, 
    minimum width=3cm, minimum height=1.2cm, 
    text width=3cm, inner sep=6pt
  },
  arrow/.style={->, thick}
]

\node[box, fill=gray!10] (instruction) {Timeless Instruction \\ in QPlatform};

\node[box, fill=blue!10, below=of instruction, xshift=-2.8cm] (instant) {Instantaneous Deployment \\ \( T = 0 \), \( C_s = \infty \) \\ e.g., Entanglement, Tunneling};
\node[box, fill=blue!20, below=of instruction, xshift=2.8cm] (delayed) {Delayed Deployment \\ \( T > 0 \), \( C_s < \infty \) \\ e.g., Photons, Gravity};

\node[box, fill=gray!20, below=of instant] (Qonly) {Appears only in Q \\ (Not visible in spacetime)};
\node[box, fill=gray!25, below=of delayed] (QGR) {Appears in Q\(_\text{GR}\) = SDF \\ (Visible: light, motion)};

\draw[arrow] (instruction) -- (instant);
\draw[arrow] (instruction) -- (delayed);
\draw[arrow] (instant) -- (Qonly);
\draw[arrow] (delayed) -- (QGR);

\end{tikzpicture}
\caption{Instructions originate in the timeless Quantum Platform (Q). Some are rendered instantaneously and remain outside the observable SDF (e.g., entanglement), while others deploy with delay and appear in the rendered GR frame (Q\(_\text{GR}\)).}
\label{fig:instruction-deployment-types}
\end{figure}

\paragraph{Clarifying Roles: Instructions Remain Primary.}
The timeless instructions are the foundational entities in the Timeless Light Model. They encode a timeless transition from start to end condition, fully resolved within the Quantum Platform (Q). All rendered phenomena in the Spacetime Deployment Frame (SDF) are delayed manifestations of these instructions.

The action principle formalism offers a potential mathematical description of how a resolved instruction becomes visible: it treats deployment as constrained by a timeless action quantity \( \mathcal{A}_{\text{ins}} \), which reaches a critical value under specific energy conditions in the SDF. This formalism does not determine which instruction is chosen — all instructions in Q are already written — but rather when each becomes observable.

Thus, we distinguish between \textbf{instructions as ontology} (what exists timelessly in Q) and \textbf{deployment as mechanism} (how it becomes visible in the rendered frame). The instruction is not a probability amplitude or a potential event — it is a completed causal instruction. Deployment mechanisms like the action principle are tools to describe when that instruction appears in delayed experience.

Q contains only fully resolved causal instructions — each defining a start-to-end instruction that was, is, and always will be true. If it is in Q, it landed. There is no “unrendered possibility space.”

Q is not a menu. It is the record of everything that always was.

\section{Timeless Light Model (TLM) --- Core Axioms}
\label{sec:tlm_axioms}

\subsection{Redefinition of Instructions}
\label{sec:instructions}

\begin{axiom}[Instruction as State Transition]
The instruction is defined as the timeless, outcome-final instruction encoding a transition from a \emph{Start Condition} to an \emph{End Condition} in the underlying quantum control platform (QPlatform). Formally:
\[
\text{Instruction} : \quad \mathcal{S} \longrightarrow \mathcal{E}
\]\textit{...a completed mapping in logical space from a start condition \( \mathcal{S} \) to a resolved end state \( \mathcal{E} \), with no time elapsed between them.}

where
\begin{itemize}
    \item \(\mathcal{S}\) = Start Condition (timeless initial state vector),
    \item \(\mathcal{E}\) = End Condition (timeless final state vector).
\end{itemize}
The instruction is thus a mapping encoding the difference between \(\mathcal{E}\) and \(\mathcal{S}\), which is timeless and non-probabilistic.
\end{axiom}

\begin{remark}
This redefinition replaces prior parameterizations with a simpler, conceptually clearer state-difference operator.
\end{remark}

\subsection{Fundamental Axioms and Laws}

\begin{axiom}[Time-Flat Senior Reality]
The underlying quantum control platform (QPlatform) is a \emph{time-flat} reality layer, where start and end conditions exist timelessly and are \textbf{prior} to any deployment of time or spacetime structure. This is the senior layer to General Relativity (GR).Q encodes all rendering conditions without respect to time; SDF states do not influence Q but manifest as filtered projections.


\[
\text{QPlatform (Time-Flat)} \quad \xrightarrow[\text{deployment}]{\text{with delay}} \quad \text{GR (Time-Stretched)}
\]
\end{axiom}

\begin{law}[Projection of Timeless Reality]
The classical curved spacetime described by GR emerges as a delayed \emph{projection} or \emph{deployment} of the timeless QPlatform instructions into a spacetime framework parameterized by time:
\[
\text{FLAT} + \text{TIME} = \text{GR}
\]
Where:
\begin{itemize}
    \item \textbf{FLAT} = Timeless, non-deploying instruction layer (QPlatform),
    \item \textbf{TIME} = The deployment delay or rendering parameter,
    \item \textbf{GR} = The emergent curved spacetime experience.
\end{itemize}
\end{law}

\begin{law}[No Fundamental Probabilities]
Probabilities do not exist fundamentally in the QPlatform. All quantum measurement randomness and wavefunction collapse are artifacts arising in the \textbf{GR layer} as consequences of delayed projection from the timeless, deterministic QPlatform.
\[
\text{Probability}_{\text{QM}} = \text{Artifact}_{\text{GR}}
\]
\end{law}

\begin{law}[Delayed Playback and Phenomenological Laws]
The TLM phenomenological laws such as
\[
T \cdot m = 1 \quad \text{and} \quad T \cdot C_s = 1
\]
remain valid as descriptions of the delayed playback process, linking delay \(T\), mass \(m\), and causal speed \(C_s\) as emergent parameters of the deployment of timeless instructions into spacetime.
\end{law}

\begin{axiom}[GR as Emergent Deployment, Not Separate Ontology]
General Relativity is not a separate ontological layer but an emergent \emph{rendering} of the QPlatform instructions:
\[
Q + Q_{\text{subGR}} = \text{Reality as Experienced}
\]
where \(Q\) is the timeless instruction platform and \(Q_{\text{subGR}}\) is the deployment function generating the GR experience.
\end{axiom}



\begin{tcolorbox}[
  colback=gray!10,
  colframe=gray!75!black,
  title=Highlighted Insights from Prior Work on Causal Instruction Arcs,
  sharp corners=south,
  fonttitle=\bfseries,
  boxrule=0.5pt
]

This tcolorbox recovers select foundational elements from an earlier iteration of the Timeless Light Model (TLM)~\cite{mckinley2025ciarc}, where Causal Instruction Arcs (CI-ARCs) were emphasized as timeless mappings. These concepts complement the current QPlatform architecture without requiring quantization:

\begin{itemize}
  \item \textbf{Photon as Timeless Linkage}: A photon is not an object moving through space. It is a timeless instruction linking two mass-bound events — one emission, one absorption — with no delay from its own frame. What we observe as a path is a rendered illusion within the Spacetime Deployment Frame (SDF), but the instruction itself was instantaneously resolved in the Quantum Platform.
  
  \item \textbf{Mass-Induced Delay Axiom}: The relation \( T \cdot m = \hbar / c^2 \) grounds mass as a delay factor in rendering, tying to physical constants (\(\hbar\), \(c\)) and explaining zero-delay for massless instructions like photons.
  
  \item \textbf{Emergence of Three-Dimensional Space}: 3D space may arise as a post-inflationary, low-energy projection from timeless instructions, offering a potential explanation for our universe's dimensionality.
  
  \item \textbf{Resolution of Black Hole Information Paradox}: Horizons could be delayed renderings, preserving information in timeless Q instructions linking interior and exterior events.
  
  \item \textbf{Testable Predictions}: Quantum delays (\(\sim 10^{-12}\) s) in low-energy regimes and CMB phase shifts (\(\sim 10^{-11}\) rad), verifiable through precision cosmology.
\end{itemize}

These ideas, mediated by the Blackbox Controller in the current framework, invite further exploration while preserving the model's conservative stance.

\end{tcolorbox}



\subsection{Summary}

\begin{itemize}
    \item The instruction is now explicitly a \textbf{timeless state transition} from \(\mathcal{S}\) to \(\mathcal{E}\).
    \item The universe’s fundamental description lies in the \textbf{timeless QPlatform}, and spacetime with time arises as a \textbf{deployed rendering}.
    \item QM measurement randomness and probabilities are not fundamental but emerge in the GR frame.
    \item The existing TLM formulas describe this \textbf{display and delay} phenomenologically.
    \item The GR universe is thus the “movie” generated by projecting the timeless “film” of the QPlatform.
\end{itemize}

\section{Two Classes of Quantum Events}

The TLM categorizes quantum events based on whether they render into the SDF (becoming part of $Q_{\text{GR}}$) or remain resolved solely within Q:

\begin{itemize}
  \item \textbf{Timeless/Instantaneous Events:} tunneling, entanglement, wavefunction collapse
  \begin{itemize}
    \item Not delayed
    \item Not curved
    \item Not observable as spacetime motion, but causal
  \end{itemize}

  \item \textbf{Delayed/Observable Events:} photons, mass, gravity, classical force dynamics
  \begin{itemize}
    \item Appear in time
    \item Behave under curvature
    \item Observable in classical GR experiments
  \end{itemize}
\end{itemize}

Both categories originate from Q, but only the latter become part of the visible display that physics traditionally measures.

\section{Reinterpreting Known Phenomena Under the TLM}
\label{sec:phenomena}

The Timeless Light Model offers a clarified causal explanation for many quantum phenomena that appear counterintuitive under a GR-first worldview. By reordering the hierarchy—placing the Quantum Platform (Q) above the observable spacetime frame—we reinterpret key observations as follows:

\subsection{Entanglement}
Entangled particles exhibit correlations that defy spacetime-local models. In the TLM, this is no paradox: both particles are resolved jointly at the level of Q. No signal travels between them; instead, they share a common instruction origin. Because Q is not embedded in spacetime, its resolutions are not subject to relativistic separation or communication constraints.

\subsection{Quantum Tunneling}
Tunneling events, such as electrons appearing across a potential barrier, are not mysterious in Q. There is no “travel” through the barrier—only an instruction that resolves endpoints consistent with boundary conditions. The apparent violation of classical conservation is an illusion of SDF logic being bypassed by a non-delayed Q resolution.

\subsection{Wavefunction Collapse}
Rather than modeling collapse as a mysterious, observer-triggered process, TLM treats it as the finalization of a Q instruction into the SDF. The probabilities encoded in quantum amplitudes are resolved at the Q level, and the “collapse” is simply the deployment of that resolution into the spacetime frame.

\subsection{Photon Travel}
Photons are massless and experience no proper time. In TLM, this is reinterpreted as evidence that photon behavior is a resolved instruction: an instruction rendered into the SDF with an apparent emission and absorption, but no internal passage. Their “travel” is a delayed deployment of an instruction with no time component.

\subsection{The Big Bang}
Under TLM, the Big Bang is not a spacetime-contained event. It is the earliest injection of Q instructions into the SDF. From the perspective of Q, it is simply one resolution pattern among many; from the SDF viewpoint, it marks the beginning of time. This interpretation sidesteps paradoxes about origin and singularities by relocating causal authority to Q.

\paragraph{Initial Deployment: No Need for a Prior Frame.}
The first instruction — corresponding to what we call the Big Bang — is not the result of an SDF-based energy drop. It is simply the first rendered instruction whose conditions are met within the logical structure of \( Q \). From the timeless platform’s perspective, this instruction was always true. From within the SDF, it appears to begin history. The apparent "start" is just the earliest observable rendering — not the beginning of logic.

\section{Causal Hierarchy and the TLM Equation}
\label{sec:causalhierarchy}

\subsection{Causal Clarification: No Reaction, Only Rendering}

It may appear that the Timeless Light Model (TLM) faces a bootstrap problem: if instructions are only rendered when a condition in the Spacetime Deployment Frame (SDF) is met, then how can the SDF exist in the first place?

The resolution lies in the timeless nature of the Quantum Platform \( Q \), which contains all instructions, including their rendering conditions, eternally. Q does not “respond” to events in the SDF. Instead, it encodes which instructions render \emph{as if triggered by} SDF constraints — a view experienced from within the delayed deployment frame.

Thus, the SDF is not the cause of instruction activation, but the \textit{appearance} of rendered instructions whose conditions were always satisfied in Q. This preserves logical consistency, eliminates causal loops, and aligns with the model’s founding principle: that Q is senior to time, experience, and all rendered history.

The \textit{first} instruction is the one whose conditions are satisfied with minimal delay (e.g., \( T \to 0 \)), 
self-consistently encoded within \( Q \). 

Formally, \( Q \) is the fixed point of a timeless operator \( \Omega \) such that:

\[
Q = \Omega(Q)
\]

where \( \Omega \) encodes all instruction deployments whose rendering conditions are satisfied within the structure of \( Q \) itself.

The Timeless Light Model reframes the longstanding tension between General Relativity (GR) and Quantum Mechanics (QM) by introducing a causal hierarchy:

\begin{itemize}
  \item \textbf{Quantum mechanics is not subordinate to GR.}
  \item GR phenomena are "time-expansions"—rendered effects—of deeper quantum logic.
  \item Spacetime is not the stage of physics; it is a surface-level rendering of quantum instruction sets.
\end{itemize}

This leads directly to the structural equation of the TLM framework:

\begin{equation}
\text{Universe} = Q + Q_{\text{GR}} \quad \text{where} \quad Q_{\text{GR}} \equiv \text{SDF}
\end{equation}


Here:
\begin{itemize}
  \item $Q$ is the \textbf{Quantum Platform}: timeless, dimensionless, and instructionally complete.
  \item $Q_{\text{GR}}$ is the \textbf{projected subset} of Q that manifests with observable delay and curvature.
  \item The SDF is simply the experiential frame in which $Q_{\text{GR}}$ is rendered.
\end{itemize}
\medskip
\noindent
\textbf{Definition of Terms:}

\begin{itemize}
  \item \( Q \): The \textbf{Quantum Platform}, an extra-spacetime, dimensionless layer that holds all pre-resolved causal instructions. It is the full set of possible instructions — causal instructions — that define physical outcomes, whether or not they are rendered in observable form.
  
  \item \( Q_{\text{GR}} \): The rendered subset of \( Q \) that appears within the observable universe. It includes only those instructions that are deployed into the Spacetime Deployment Frame (SDF), obeying delay, curvature, and relativistic structure. By definition: 
  \[
  Q_{\text{GR}} \equiv \text{SDF}
  \]
  This means the visible universe is not the full quantum structure, but a projected subset of it.
\end{itemize}



\subsection{Hierarchy}
This causal hierarchy allows us to retain all predictive behavior of both GR and QM without attempting to geometrize quantum effects. Instead of trying to fit quantum phenomena inside spacetime, we reinterpret spacetime as an artifact of quantum control. Entanglement, tunneling, and wavefunction collapse no longer appear “non-local”—they are simply non-deployed.

This perspective clarifies that GR is not a rival to QM, nor its completion, but its experiential rendering. TLM does not eliminate GR; it places it within a deeper logical architecture.

We define \textbf{rendering} as a surjective map 
\[
R : Q \to \text{SDF}
\]
where \( R(\text{Instruction}_k) \) is defined if and only if the condition holds. However, this condition is embedded within the structure of \( Q \), not derived from or influenced by the SDF.


\subsection{Timeless Constraint Functional and Variational Rendering}
\label{sec:variational_rendering}

We define rendering as a timeless variational principle over logical space rather than over classical spacetime trajectories.

Let an instruction connect a start condition \( \mathcal{S} \) to an end condition \( \mathcal{E} \). Then rendering occurs when the following condition holds:

\[
\delta \mathcal{A}(\mathcal{S}, \mathcal{E}) = 0 
\quad \text{subject to} \quad 
\int_{\text{SDF}} \Delta E \, dV 
\]

Here:
\begin{itemize}
  \item \( \delta \mathcal{A}(\mathcal{S}, \mathcal{E}) = 0 \) expresses that the action-like functional \( \mathcal{A} \) is extremized — not over spacetime paths but over logical transitions defined in \( Q \),
  \item The integral is evaluated in the spacetime deployment frame (SDF), representing the accumulated energy shift during rendering.
\end{itemize}

Although the energy condition is evaluated in the SDF, the extremum is pre-resolved in the timeless Quantum Platform \( Q \), meaning the system’s instructional future already “knows” when and where it is rendered.

\medskip

This structure allows us to derive the fundamental rendering delay law:

\[
T \cdot C_s = 1
\]

Here:
\begin{itemize}
  \item \( T \) is the emergent delay (or time) experienced during deployment,
  \item \( C_s \) is the rendering rate or causal velocity of instruction resolution from \( Q \),
  \item The product is invariant, reflecting a conservation principle between delay and rendering rate across all instructions.
\end{itemize}

This formulation shows how classical experience arises as a projection from timeless logic — delay (\( T \)) is not fundamental, but a byproduct of instructional rendering under constraints.

\begin{figure}[ht]
\centering
\begin{tikzpicture}[
  node distance=2cm and 3cm,
  every node/.style={font=\small, align=center},
  box/.style={rectangle, draw=black, thick, minimum width=2.8cm, minimum height=1.2cm, text width=2.8cm},
  arrow/.style={->, thick}
]

% Nodes
\node[box, fill=gray!10] (Q) {Quantum Platform\\ \( Q \)\\ (timeless logic)};
\node[box, fill=blue!10, below=of Q] (cond) {Conditional Visibility};
\node[box, fill=blue!15, below=of cond] (QGR) {Rendered Subset\\ \( Q_{\text{GR}} \)};
\node[box, fill=gray!15, below=of QGR] (SDF) {Spacetime Deployment Frame\\ (observables: mass, motion, light)};

% Arrows
\draw[arrow] (Q) -- (cond) node[midway, right=5pt] {\footnotesize conditional visibility};
\draw[arrow] (cond) -- (QGR) node[midway, right=5pt] {\footnotesize instruction in force};
\draw[arrow] (QGR) -- (SDF) node[midway, right=5pt] {\footnotesize delayed rendering};

\end{tikzpicture}
\caption{Causal deployment flow: instructions existing outside a time bound universe, in \( Q \) are conditionally made visible, which then project into \( Q_{\text{GR}} \) and appear as classical observables in the Spacetime Deployment Frame (SDF).}
\label{fig:q-deployment-diagram}
\end{figure}

\section{Comparison with Existing Unification Models}
\label{sec:comparisons}

Efforts to unify General Relativity (GR) and Quantum Mechanics (QM) have led to a number of theoretical frameworks — most notably, loop quantum gravity (LQG), string theory, and causal set theory. Each introduces profound ideas but carries significant philosophical and technical baggage that the Timeless Light Model (TLM) seeks to avoid.

\paragraph{Loop Quantum Gravity (LQG).}
LQG attempts to quantize spacetime itself by discretizing geometry at the Planck scale. While this honors quantum discreteness, it still treats GR as the foundational substrate being quantized — implying that space and time are primary. In contrast, TLM treats GR as a *projection*, not a platform. The emergence in TLM applies to deployment events, not geometry, and arises from timeless causal logic rather than a fluctuating spacetime lattice.

\paragraph{String Theory.}
String theory posits one-dimensional vibrating objects in 10+ dimensions to unify forces. Though mathematically rich, it remains unfalsifiable, introduces metaphysical structures (extra dimensions, branes, supersymmetry), and has failed to produce definitive experimental predictions. TLM introduces no such entities. It preserves all known equations and restructures their causal ordering, yielding a falsifiable model grounded in instructional delay and deployment.

\paragraph{Causal Set Theory.}
Causal set theory aligns somewhat with TLM in treating spacetime as emergent from discrete events. However, it lacks a mechanism for when and why those events occur. TLM fills this gap via instructions rendered when energy conditions are realized — rooted in the structure of the Quantum Platform.

\paragraph{Conclusion.}
Whereas most unification models attempt to stitch GR and QM together within the same ontological layer, TLM sidesteps this by recognizing a causal hierarchy. GR is not adjusted — it is subordinated. The observable universe becomes a rendered surface, not a fluctuating field, and no new particles or dimensions are needed.

\paragraph{Timeless and Configuration Space Approaches.}
Several existing models have explored physics without a fundamental time parameter, or in terms of configuration space rather than spacetime. Barbour's "The End of Time"~\cite{barbour2000} introduced the idea that time may be an illusion arising from change, proposing a physics built from relative configurations. More recent work by Gryb and Thébault~\cite{gryb2018} formalizes quantum gravity in timeless configuration space using path integrals that bypass standard temporal evolution.

TLM differs by proposing a distinct structure: rather than treating configuration as primary, it introduces a \textit{Quantum Platform} \( Q \) which contains timeless causal instructions. These are only projected into experience (the SDF) when energetic conditions are met. Whereas other models often focus on symmetry reduction or shape dynamics, TLM emphasizes instructional deployment as the mechanism of manifestation — giving rise to delay, time, and gravity as side effects of instruction activation.

Similarly, work like Giacomini et al.~\cite{giacomini2022} investigates the emergence of 3+1D spacetime from entanglement structure. TLM is compatible with this vision, but reframes the source of structure not as informational entanglement alone, but as instruction-level selection and rendering from a timeless substrate.

\section{Benefits of the Timeless Light Model}
\label{sec:benefits}

The Timeless Light Model (TLM) does not attempt to replace established physics—it reorganizes it. By positioning quantum causality as the foundational layer and spacetime as a rendered projection, the TLM provides the following advantages:

\subsection{Resolves Conceptual Paradoxes}
Phenomena such as entanglement, tunneling, and instantaneous wavefunction collapse, which appear paradoxical under spacetime-first models, are straightforward under TLM. These effects are not propagations; they are resolutions. Their “speed” is irrelevant because they never traverse space—they bypass it.

\subsection{Preserves All Empirical Predictions}
TLM changes no equations of GR or QM. It retains the Schrödinger equation, Einstein's field equations, quantum field dynamics, and path integrals exactly as they are. What it changes is their causal interpretation: all observable dynamics are the outcome of instruction resolution at the level of Q.

\subsection{Offers a Unified Causal Framework}
Instead of attempting to quantize gravity or curve Hilbert space, TLM treats the GR domain as a resolved interface—$Q_{\text{GR}}$—projected from Q. This sidesteps incompatibility by removing the false assumption that GR and QM must meet on the same ontological footing.

\subsection{Eliminates the Need for New Entities}
There are no new particles, forces, or extra dimensions proposed. TLM does not rely on branes, strings, supersymmetry, or hidden variables. It accepts existing mathematical predictions but organizes them into a coherent causal hierarchy.

\subsection{Accommodates Future Discoveries}
If new quantum effects are discovered that do not obey GR-style propagation, they fit naturally into the TLM as Q-level instructions. Conversely, any newly discovered gravitational behavior that fits within GR would automatically be interpreted as part of $Q_{\text{GR}}$.

\subsection{Clarifies the Role of Time}
Rather than assuming time as a background parameter, TLM derives temporal experience from the delay between Q instruction and SDF deployment. Mass, gravity, and entropy all emerge from these delays. The photon’s "no time" quality and the behavior of black holes gain a coherent frame.

\subsection{Positions Quantum Mechanics as Causally Senior}
This reframing provides a clean answer to the unification problem: QM is not puzzling—GR is a consequence of it. Spacetime becomes the rendered narrative, not the author.

\section{Open Questions and Future Work}
\label{sec:openquestions}

While the Timeless Light Model offers a clarified causal framework, it also opens new avenues of investigation. Several unresolved questions remain, some of which may be testable through careful interpretation of existing experiments or future observations:

\subsection{Timeless Logic and Philosophical Foundations}

A key area for future refinement lies in the formalization of timeless logic — specifically, how causal instructions can be coherently defined without reference to a time-ordered substrate. While the current model uses functional constraints (e.g., \( \delta \mathcal{A}(\mathcal{S}, \mathcal{E}) = 0 \)) to simulate this structure, a deeper logical foundation is needed.

We anticipate future work will explore:
\begin{itemize}
  \item \textbf{Modal logic frameworks} that distinguish between necessity, possibility, and pre-resolution in a timeless context.
  \item \textbf{Eternalism}, as discussed in the philosophy of physics, where all events are fixed in a four-dimensional structure — compatible with the Quantum Platform’s resolved totality.
  \item \textbf{Instructional consistency logic}, potentially akin to constraint satisfaction in computation, but adapted for a non-temporal rendering substrate.
\end{itemize}

These explorations aim to provide a rigorous account of how logical causality, rendered delay, and experiential emergence can coexist in a framework that does not presuppose time as a fundamental parameter.

\subsection{Nature and Selection of Q Instructions}
What governs which quantum instructions are rendered into the Spacetime Deployment Frame (SDF) and which remain undeployed? Is there a formal selection mechanism for $Q \rightarrow Q_{\text{GR}}$ transitions? This may involve constraints analogous to action minimization or entropy optimization but occurring outside time.

\subsection{Micro Black Hole Distributions}

TLM reframes so-called “dark matter” as an observational symptom of unilluminated, high-delay causal deployments — specifically, rendered instructions that possess mass but no photon-linked instruction. These photon-silent deployments behave gravitationally, but do not emit or absorb light. The result is a gravitational field pattern that resembles a distribution of micro black holes: compact, high-delay mass concentrations that evade electromagnetic detection but curve spacetime in measurable ways. If this interpretation is correct, we should expect to find detectable patterns of gravitational influence consistent with a granular field — not a smooth dark matter halo. Future experiments in gravitational lensing precision, frame-dragging anomalies, or fine-structure deviations in galactic rotation curves may expose these micro black hole distributions, offering a falsifiable signature of TLM's instructional architecture.

\subsection{Entropy and Information Flow}
If mass and energy are projections from Q, then thermodynamic entropy may need reinterpretation as an effect of instruction delay, rather than disorder. Similarly, information loss in black holes might be reframed as non-deployed Q arcs—still present, but inaccessible in SDF terms.

\subsection{The Q--SDF Interface}
The precise mechanics of deployment---how resolved instructions in Q appear as delayed events in $Q_{\text{GR}}$---remain an open area for formalization. While the Timeless Light Model (TLM) rejects the need for spacetime-based dynamics in its senior layer, it invites a rendering framework that translates timeless causal arcs into observable experience.

\paragraph{Toward a Formal Deployment Structure.}
While a full deployment formalism is beyond the scope of this paper, we propose a preliminary candidate framework grounded in causally triggered resolution:

\begin{enumerate}
  \item \textbf{Instruction Action Principle:} Each instruction exists in Q as a resolved transition from a start state \( \mathcal{S} \) to an end state \( \mathcal{E} \). Deployment into the Spacetime Deployment Frame (SDF) occurs not because the arc is chosen, but because its conditions are satisfied. This can be formalized as a constraint-satisfaction principle over a timeless action variable \( \mathcal{A}_{\text{ins}} \). Deployment occurs when:
  \[
    \delta \mathcal{A}_{\text{ins}} = 0
  \]
  subject to energy conditions in the SDF. The calculus involved is not over paths in spacetime, but over instruction fulfillment under causal constraint.

  \item \textbf{Rendering Gate Formalism:} Rather than invoking projection from a superposition, we define a rendering function \( R_k \) associated with each instruction type. This function determines when a resolved instruction arc becomes visible in the SDF:
  \[
    R_k(\text{Instruction}_k) =
    \begin{cases}
      \text{SDF Event} & \text{if condition met} \\
      \varnothing & \text{otherwise}
    \end{cases}
  \]
  This reflects the TLM claim that all instructions are already finalized in Q, and their visibility in the classical frame is governed by delay and conditional deployment—not probabilistic choice or amplitude collapse.
\end{enumerate}

These frameworks suggest that a mathematical bridge from the “always-resolved” logic of Q to the rendered experience of the SDF may be constructed using constraint-based or variational logic, without invoking time-evolution or quantum superposition. The challenge is not to find which instructions are selected, but to define when they appear.

\subsection{Testing the Hierarchy}
Is it possible to empirically demonstrate the causal seniority of quantum instruction? Phenomena such as delayed choice experiments, quantum erasure, or novel forms of non-locality may offer opportunities to falsify classical-first assumptions and support the TLM hierarchy.

\section{Conclusion}
\label{sec:conclusion}

The Timeless Light Model (TLM) offers a structural clarification of modern physics: rather than viewing General Relativity and Quantum Mechanics as competing or incompatible domains, we propose a causal ordering in which quantum instruction is primary. The Quantum Platform (Q) contains all causal logic, while observable physics—mass, light, motion, curvature—are rendered projections into the Spacetime Deployment Frame (SDF), denoted $Q_{\text{GR}}$.

This view requires no changes to existing equations, introduces no new particles, and preserves all testable predictions of GR and QM. What it provides is a coherent frame: quantum phenomena such as entanglement and tunneling are not anomalies—they are evidence of Q’s "forever and never" instruction set operating outside spacetime constraints. Meanwhile, classical GR effects are not foundational—they are delayed renderings.

The key unification is not mathematical but causal. We do not attempt to force GR and QM into a shared substrate; we instead recognize one as the logical source of the other. This reframing offers a path forward that honors both traditions of physics while pointing to a simpler underlying structure:

\begin{equation}
\text{Universe} = Q + Q_{\text{GR}} \quad \text{with} \quad Q_{\text{GR}} \equiv \text{SDF}
\end{equation}

In this model, the universe is not merely a dynamic arena but a projected rendering—an experiential projection of a deeper, time free logic. Future research may refine the formal structure of this projection, quantify instruction resolution, and test the limits of classical observability. The source of the GR universe may already be shaping what we see.

\footnote{“Projection” is used here in the mathematical sense: a mapping from timeless instruction space (Q) to a delayed, rendered experiential domain (SDF). It implies neither illusion nor computational simulation unless specified.}




\section{Glossary}
\addcontentsline{toc}{section}{Glossary}

\begin{description}

  \item[Instruction:]
  A discrete, "pre-time-factor" instruction issued from the Quantum Platform (Q) that defines a complete causal event, such as a photon emission, entangled pair deployment, or tunneling event. These do not propagate — they resolve either instantly or with delay into the Spacetime Deployment Frame (SDF).



  \item[Q (Quantum Platform):]
  A dimensionless layer, senior to time, containing the full set of causal instructions that govern physical reality. Q contains only the instructions that actually landed.

  \item[Deployment:]
The conditional appearance of a timeless instruction in the observable universe, typically rendered in the Spacetime Deployment Frame (SDF). Deployment does not imply computation or simulation—it is the manifestation of a pre-resolved instruction under experiential constraints.

\item[Rendering:]
The process of mapping a resolved instruction from the Quantum Platform (Q) into the Spacetime Deployment Frame (SDF). Rendering introduces delay and curvature into otherwise timeless causal instructions. The term is metaphorical and does not imply digital or anthropomorphic mechanics.


  \item[$Q_{\text{GR}}$:]
  The rendered subset of Q that manifests as classical physics — specifically, General Relativity (GR) behaviors. It includes mass, curvature, motion, and other phenomena that obey delayed deployment. By definition, \( Q_{\text{GR}} \equiv \text{SDF} \).

  \item[SDF (Spacetime Deployment Frame):]
  The observable domain of deployed instructions. All experiences of time, gravity, curvature, and light take place within the SDF. It is not fundamental but a rendered surface of deeper quantum logic.

  \item[Instruction Hash:]
  A shorthand reference to the encoded state of a system's instructional configuration in Q. Instruction hashes are used to track identity, entropy, and re-resolution conditions of deployed instructions. Analogous to cryptographic hashes, they provide a compact causal signature of a physical state.

  \item[Photon:]
A photon is not an object moving through space. It is a timeless instruction linking two mass-bound events — one emission, one absorption — with no delay from its own frame. What we observe as a path is a rendered illusion within the Spacetime Deployment Frame (SDF), but the instruction itself was instantaneously resolved in the Quantum Platform.

  \item[Photon-Silent Mass:]
  A rendered instruction that exerts gravitational influence but carries no electromagnetic interaction pathway. In TLM, such mass is composed of high-delay, photon-unlinked instructions — often interpreted observationally as dark matter or, more precisely, as micro black hole distributions.

  \item[Timeless Resolution:]
  The process by which an instruction in Q becomes complete without temporal propagation. Timeless resolutions include entanglement, tunneling, and wavefunction collapse. From the SDF perspective, these appear instantaneous or non-local; from Q’s perspective, they are simply resolved.

\end{description}



\appendix
\section{\texorpdfstring{Probabilities as Artifacts of Spacetime Rendering}{Probabilities as Artifacts}}
\label{appendix:probability}

The Timeless Light Model (TLM) asserts that quantum probabilities — as commonly understood in the Born rule — do not exist fundamentally in the Quantum Platform (Q). Rather, they emerge as artifacts of delayed deployment into the Spacetime Deployment Frame (SDF). In this view, the appearance of probabilistic behavior reflects the constraints and blindness inherent in the rendered frame, not indeterminacy in the underlying causal logic.

\subsection{A.1 The Born Rule as a GR-Localized Estimate}

In standard quantum mechanics, the Born rule states that the probability \( P \) of measuring a system in state \( \psi_i \) is given by:

\[
P_i = |\langle \psi_i | \Psi \rangle|^2
\]

This is understood as an intrinsic uncertainty within the wavefunction \( \Psi \), resolved only upon measurement. Under the TLM, this interpretation is reversed: the complete outcome is already determined by an instruction in Q. The Born rule simply quantifies the distribution of *rendered experiences* across possible deployments consistent with different energy and boundary conditions in the SDF.

\subsection{A.2 Instructional Finality vs Rendering Uncertainty}

In the Quantum Platform, all instructions are resolved: there is no branching, probability, or interference — only a complete mapping from \( \mathcal{S} \rightarrow \mathcal{E} \). However, not all instructions are rendered into the SDF. The probability structure arises from the observer’s ignorance of which pre-resolved instruction is being deployed at the moment of rendering.

Let \( \mathcal{H}_\text{Q} \) be the set of all valid instructions in Q consistent with the initial condition \( \mathcal{S} \), and let \( \mathcal{H}_\text{SDF} \subset \mathcal{H}_\text{Q} \) be the subset rendered within a given spacetime configuration. Then the apparent probability \( P_i \) of outcome \( i \) is:

\[
P_i = \frac{|\mathcal{H}_i|}{|\mathcal{H}_\text{SDF}|}
\]

where \( \mathcal{H}_i \subset \mathcal{H}_\text{SDF} \) includes only those instructions that render as outcome \( i \) within the SDF. This statistical structure reflects ignorance due to delay and limited frame rendering — not fundamental randomness.

\subsection{A.3 Measurement as Deployment Filtering}

Quantum measurement is therefore reinterpreted as a filter on instruction rendering: among all timelessly valid instructions in Q, only one is projected into the SDF based on boundary constraints. The Born probabilities express how likely a given outcome is to be rendered, given these spacetime-level filters — not how likely it is to “occur” in Q.

\subsection{A.4 Collapse as a Resolution Already Chosen}

In TLM, there is no collapse. The so-called “collapse” is simply the deployment of an already finalized instruction into the SDF. The probabilistic appearance comes from the delayed and filtered rendering process — a kind of spacetime myopia. This aligns with the idea that what we call chance is merely a delayed resolution we have not yet observed — not a fundamental trait of nature.

\subsection{A.5 Consequences for Quantum Theory}

This interpretation carries several implications:

\begin{itemize}
  \item The Born rule remains valid as a predictive tool, but not as an ontological claim.
  \item Decoherence, interference, and probabilistic amplitudes are emergent visualizations of instructional filtering under delay, not fundamental randomness.
  \item The wavefunction is not an evolving object in time, but a rendered summary of potential deployments consistent with the local SDF state.
\end{itemize}

In sum, the TLM treats quantum probabilities not as primary facts, but as experiential estimates derived from the delayed rendering of fully determined instructional logic. From the perspective of Q, the outcome was never uncertain. From within the SDF, it always seems to be.







\begin{thebibliography}{99}


\bibitem{einstein}
A.~Einstein, quoted in ``Albert Einstein: Philosopher-Scientist,'' ed. P.~A.~Schilpp, Open Court Publishing (1949).

\bibitem{feynman}
R.~P.~Feynman, ``The Character of Physical Law,'' MIT Press (1965).


\bibitem{mckinley2025_causal}
J.~C.~W.~McKinley,
\textit{Causality Without Light Speed: Reframing \( c \) as a Derived, Not Fundamental, Limit}, 
Zenodo (2025). doi:\href{https://doi.org/10.5281/zenodo.15826480}{10.5281/zenodo.15826480}

\bibitem{mckinley2025_causalrate}
J.~C.~W.~McKinley,
\textit{Clarifying Causal Rate: The Instructional Delay Law \( T \cdot C_s = 1 \)}, 
Zenodo (2025). doi:\href{https://doi.org/10.5281/zenodo.15817350}{10.5281/zenodo.15817350}

\bibitem{mckinley2025quantized}
J.~C.~W.~McKinley, ``Unified Physics by Subordination of GR to QM: A Layered Reality Framework,'' Zenodo (2025), \href{https://doi.org/10.5281/zenodo.15956986}{doi:10.5281/zenodo.15956986}.

\bibitem{mckinley2025ciarc}
J.~C.~W.~McKinley, ``Causal Instruction Arcs and the Timeless Light Model: A Unified Framework for Physics and Cosmology,'' Zenodo (2025), \href{https://doi.org/10.5281/zenodo.15813253}{doi:10.5281/zenodo.15813253}.

\bibitem{mckinley2025unpublished}
J.~C.~W.~McKinley, ``Toward a Unified Model of Timeless-Light and Mass-Bound Gravity'' (Unpublished Draft, June 3, 2025). 





\bibitem{barbour2000}
J.~Barbour, \textit{The End of Time: The Next Revolution in Physics}, Oxford University Press (2000).

\bibitem{gryb2018}
S.~Gryb and K.~Thébault, ``Quantum gravity in timeless configuration space,'' \textit{Classical and Quantum Gravity} 35, 035004 (2018). arXiv:\href{https://arxiv.org/abs/1706.08875}{1706.08875}.

\bibitem{giacomini2022}
F.~Giacomini, A.~R.~H.~Smith, and Č.~Brukner, ``A model of quantum spacetime,'' \textit{Nature Communications} 13, 1196 (2022). arXiv:\href{https://arxiv.org/abs/2207.01005}{2207.01005}.


\end{thebibliography}


\appendix
\section{Rigorous Derivations in the TLM Framework}
\label{appendix:derivations}

The following derivations formalize key relationships implied by the Timeless Light Model (TLM). Each draws from causal invariants and deployment logic described throughout the main text.

\subsection{A.1 Delay–Energy Relation from Deployment Invariant}
\label{appendix:delay-energy}

We begin with the delay–rate law introduced in Section~\ref{sec:causalhierarchy}:

\begin{equation}
T \cdot C_s = 1
\end{equation}

where \( T \) is the rendering delay (in seconds) and \( C_s \) is the causal deployment rate (in s\(^{-1}\)).

Assume the deployment rate is proportional to the local energy drop in the Spacetime Deployment Frame (SDF):

\begin{equation}
C_s = \alpha \cdot \Delta E_{\text{SDF}}
\end{equation}

with \( \alpha \) a proportionality constant (units: [s·J]\(^{-1}\)). Substituting:

\begin{equation}
T \cdot (\alpha \cdot \Delta E_{\text{SDF}}) = 1 \quad \Rightarrow \quad T = \frac{1}{\alpha \cdot \Delta E_{\text{SDF}}}
\end{equation}

\paragraph{Interpretation.}
A larger energy drop in the SDF causes a faster rendering of the corresponding instruction. Zero-delay events (e.g., tunneling or entanglement) correspond to divergent energy drops from the Q perspective. High-delay events (e.g., classical mass or curvature) result from low-energy rendering conditions.

\subsection{A.2 Triggered Curvature as Discrete Deployment Effect}
\label{appendix:triggered-curvature}

In Einstein's field equations (simplified scalar form), curvature is proportional to energy:

\begin{equation}
R \propto T_{\mu\nu} \propto E
\end{equation}

TLM reframes spacetime curvature as the rendered outcome of instruction events. Curvature appears as instructions are rendered under energy conditions in the SDF.

\paragraph{Interpretation.}
What GR treats as continuous curvature is, in TLM, the result of densely packed deployment events. This suggests potential observables such as lags in curvature formation, detectable in high-precision gravitational wave or frame-dragging measurements.

\subsection{A.3 Instruction Hash Cardinality as Entropy}
\label{appendix:entropy-hash}

Define the instruction hash \( \mathcal{H}(t) \) as the set of currently deployable instructions in the system at time \( t \). TLM reframes entropy as a function of instructional diversity:

\begin{equation}
S(t) = k_B \cdot \ln |\mathcal{H}(t)|
\end{equation}

If the system evolves such that \( \mathcal{H}(t + \delta t) = \mathcal{H}(t) \cup \delta \mathcal{H} \), then:

\begin{equation}
\Delta S = k_B \cdot \ln \left( \frac{|\mathcal{H}(t + \delta t)|}{|\mathcal{H}(t)|} \right)
= k_B \cdot \ln \left( 1 + \frac{|\delta \mathcal{H}|}{|\mathcal{H}(t)|} \right)
\end{equation}

Assuming \( |\delta \mathcal{H}| \ll |\mathcal{H}(t)| \), we apply the approximation \( \ln(1 + x) \approx x \):

\begin{equation}
\Delta S \approx k_B \cdot \frac{|\delta \mathcal{H}|}{|\mathcal{H}(t)|}
\end{equation}

\paragraph{Interpretation.}
Entropy is reinterpreted not as disorder, but as the informational richness of deployable quantum instructions. Thermodynamic behavior corresponds to the growth in active instruction space under Q.






\end{document}
```

</details>

---
{% endraw %}
