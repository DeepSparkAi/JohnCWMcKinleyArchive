---
layout: default
title: '[2025] The Photon''s Exile: A GR-Based Proof That Light Is Not in Spacetime'
description: 'Publication metadata and archived raw LaTeX source by John C. W. McKinley.'
permalink: /papers/the-photon-s-exile-a-gr-based-proof-that-light-is-not-in-spacetime/
paper: true
---
{% raw %}
# [2025] The Photon's Exile: A GR-Based Proof That Light Is Not in Spacetime
*   **DOI:** [10.5281/zenodo.16076902](https://doi.org/10.5281/zenodo.16076902)
*   **Date:** 18 July 2025

<details markdown="1">
<summary><b>Click to view Raw LaTeX Source</b></summary>

```latex
\documentclass[11pt]{article}
\usepackage{amsmath}
\usepackage{geometry}
  \geometry{a4paper, margin=1in}

\usepackage{times}
\usepackage{cite}
\usepackage[hidelinks]{hyperref}
\usepackage{booktabs}   % For tables
\usepackage{tikz}
  \usetikzlibrary{arrows.meta, positioning}

\title{%
  The Photon's Exile:\\
  A GR‑Based Proof That Light Is Not in Spacetime%
  \thanks{This is version 1.0 of a preprint published at
    \href{https://doi.org/10.5281/zenodo.16076902}{doi:10.5281/zenodo.16076902}.}%
}

\author{John C. W. McKinley\\
  Independent Researcher\\
  ORCID: \href{https://orcid.org/0009-0005-7097-5035}{0009-0005-7097-5035}
}

\date{July 17, 2025}

\begin{document}

\maketitle

\begin{abstract}
General Relativity (GR) describes photons as traversing null geodesics in spacetime. However, their massless nature precludes a rest frame, proper time, or intrinsic experience of spatial intervals. GR's null interval \(ds^2 = 0\) and divergent Lorentz factor at \(v = c\) mathematically preclude a photon rest frame, supporting Premise 1 of our argument. This paper advances a logical argument that, from GR's own mathematical foundations—such as \(ds^2 = 0\) implying \(\tau = 0\)—photons cannot be embedded as objects within spacetime. We define “existence in the universe” as requiring a timelike worldline with a rest frame, a criterion massive entities satisfy but photons do not. The deductive conclusion: photons are exiled from spacetime, functioning instead as timeless causal instructions. This reinterpretation aligns with the Timeless Light Model (TLM), where photons resolve in a foundational Quantum Platform (Q) and project effects into the Spacetime Deployment Frame (SDF), subordinating GR to quantum logic. Implications include resolving GR–QM paradoxes like entanglement non-locality and offering falsifiable predictions, such as threshold quantization in photon‑mediated curvature. By embracing GR’s math without alteration, this argument provides a conservative pathway to unification, challenging the ontology of light as an embedded entity~\cite{Einstein1905,Rovelli2004,EPR1935}.
\end{abstract}






\section{Introduction}

The photon, as the quantum of light, occupies a peculiar position in modern physics: it is ubiquitous in our descriptions of the universe yet defies the intuitive notion of an “object” embedded within spacetime. In General Relativity (GR), photons follow null geodesics, paths where the spacetime interval \(ds^2\) vanishes, implying zero proper time (\(\tau = 0\)) and an absence of a rest frame~\cite{Einstein1905,EPR1935}. This mathematical reality—rooted in the energy–momentum relation \(E = p c\) for massless particles—raises ontological questions: If a photon experiences neither time nor distance, can it truly be said to exist “in” the universe as massive particles do? Standard interpretations of GR treat photons as integral to spacetime, contributing to the stress–energy tensor \(T_{\mu\nu}\) and influencing curvature via the Einstein field equations~\cite{Rovelli2004}. Yet, their frameless nature suggests a deeper paradox: photons mediate causality across vast distances instantaneously from their perspective, challenging the embedded‑particle paradigm.

This tension is not new; it echoes historical debates on the nature of light, from Einstein’s resistance to quantum indeterminacy to contemporary discussions in quantum gravity~\cite{Barbour2000,Gryb2018}. Approaches like Loop Quantum Gravity or String Theory attempt unification by quantizing spacetime or adding dimensions, but they often retain photons as spacetime‑bound entities despite the mathematical prohibition of null frames~\cite{Polchinski1998}. Here, we propose a conservative alternative: leveraging GR’s mathematics to argue logically that photons are not embedded in spacetime. This “exile” of the photon resolves conceptual inconsistencies and motivates the Timeless Light Model (TLM),\footnote{TLM posits a layered reality: Q is the timeless quantum instruction set; SDF is its delayed, GR-rendered projection~\cite{McKinley2025a}.} where light operates as timeless instructions in a causally senior Quantum Platform (Q), projecting observable effects into the delayed Spacetime Deployment Frame (SDF).

The argument proceeds deductively. Premise~1: GR math denies photons a rest frame (\(ds^2 = 0 \implies \tau = 0\)). Premise~2: Embedment requires a rest frame. As detailed in Section 4, the conclusion follows: photons are ontologically external, manifesting as causal bridges rather than spacetime objects. This reframing preserves all GR predictions—e.g., light bending and redshift—while subordinating GR to quantum causality, as in TLM’s hierarchy (Universe = Q + SDF).

Section~2 reviews frames and photon ontology in GR. Section~3 formalizes the criteria for spacetime embedment. Section~4 presents the logical proof and addresses objections. Section~5 explores TLM implications, including unification and falsifiability. We conclude with calls for further exploration, emphasizing that this argument, far from semantic, illuminates why GR’s math demands a timeless reinterpretation of light~\cite{McKinley2025a}.













\begin{figure}[h]
\centering
\begin{tikzpicture}[scale=1.4,>=Latex]

% Axes
\draw[->] (-0.5,0) -- (3.5,0) node[right] {Space ($x$)};
\draw[->] (0,-0.5) -- (0,4.5) node[above] {Time ($ct$)};

% Timelike worldline
\draw[very thick,blue] (0,0) -- (1,4) node[pos=0.5,left,xshift=-0.2cm] {\textbf{Timelike}};
\draw[blue] (1,4) node[right] {$\tau > 0$};

% Null worldline (photon)
\draw[very thick,red,dashed] (0,0) -- (3,3) node[pos=0.5,right,xshift=0.2cm] {\textbf{Null (Photon)}};
\draw[red] (3,3) node[below right] {$\tau = 0$};

% Light cone guide lines
\draw[dotted] (0,0) -- (0.5,3);
\draw[dotted] (0,0) -- (-0.5,3);

% Label Q and SDF
\draw[fill=gray!10,rounded corners] (3.5,1.5) rectangle (6.5,2.5);
\node at (5,2.1) {\textbf{Quantum Platform (Q)}};

\draw[fill=gray!10,rounded corners] (2.5,3.5) rectangle (7.5,4.3);
\node at (5,3.9) {\textbf{Spacetime Deployment Frame (SDF)}};

% Exile arrow
\draw[thick,->,purple] (5,2.5) -- (5,3.5);
\node at (5.3,3) {\textbf{Exile / Projection}};

% Caption
\end{tikzpicture}
\caption{Timelike worldlines (massive objects) experience proper time \(\tau > 0\), while photons follow null geodesics with \(\tau = 0\). The Timeless Light Model interprets the photon as originating from a timeless Quantum Platform (Q), projecting effects into the Spacetime Deployment Frame (SDF) without traversing time.}
\label{fig:worldlines_exile}
\end{figure}




















\section{Background on Frames and Photons in GR}

In this section, we establish the foundational concepts from General Relativity (GR) that underpin our argument. We begin by clarifying the notion of a frame of reference, then examine the distinct treatment of massive and massless particles, focusing on photons. This review highlights the mathematical peculiarities of null geodesics, setting the stage for the ontological implications discussed in subsequent sections.

\subsection{Frames of Reference in Physics}

A frame of reference in GR is a coordinate system that allows for the description of physical events from a particular viewpoint. For massive objects, an inertial frame can be defined where the object is at rest, and proper time \(\tau\) serves as a natural parameter along its worldline. The proper time is derived from the spacetime interval \(ds^2 = -c^2 d\tau^2 + dx^2 + dy^2 + dz^2\) (in Minkowski signature), where \(ds^2 < 0\) for timelike paths~\cite{Einstein1905}. This framework enables observers to measure intervals and define causality within spacetime.

However, GR's geometry, governed by the Einstein field equations \(G_{\mu\nu} = \frac{8\pi G}{c^4} T_{\mu\nu}\)~\cite{Rovelli2004}, accommodates curved spacetime, where frames are locally inertial but globally influenced by curvature. The key point is that frames require a timelike structure to be physically meaningful, as they presuppose the passage of time and measurable distances.

\subsection{Massive vs. Massless Particles}

Massive particles follow timelike geodesics (\(ds^2 < 0\)), possessing rest mass \(m > 0\) and satisfying the energy-momentum relation \(E^2 = (pc)^2 + (mc^2)^2\). They experience proper time \(\tau > 0\), allowing for rest frames and defining their embedment in spacetime~\cite{Rovelli2004}.

In contrast, massless particles like photons obey \(E = pc\), tracing null geodesics where \(ds^2 = 0\) and \(\tau = 0\)~\cite{Einstein1905}. This absence of proper time means no intrinsic clock or distance scale exists for the photon, rendering a rest frame mathematically undefined---Lorentz boosts diverge at \(v = c\).

\subsection{Photons in General Relativity}

Photons propagate along null geodesics, bending in curved spacetime as predicted by GR (e.g., gravitational lensing). For photons, \(ds^2 = -c^2 dt^2 + dx^2 + dy^2 + dz^2 = 0\), collapsing time and space intervals. They contribute to the stress-energy tensor \(T_{\mu\nu}\) via electromagnetic fields, influencing geometry~\cite{Rovelli2004}. Yet, their null nature implies zero interval between emission and absorption events from the photon's ``perspective,'' challenging the idea of photons as embedded objects traversing spacetime.

This frameless status is not a limitation of GR but a direct consequence of its mathematics, aligning with observations like zero time dilation for light. Existing interpretations often treat photons as ``in'' spacetime despite this, but TLM reframes them as timeless causal links~\cite{McKinley2025a, McKinley2025b}. E.g., the infinities at black hole horizons highlight GR's struggle with null paths~\cite{Rovelli2004}.

\subsection{Existing Interpretations and Gaps}

Interpretations like those in quantum field theory view photons as excitations of the electromagnetic field within spacetime~\cite{Polchinski1998}. However, GR's null-frame prohibition reveals a gap: photons lack the ontological attributes (e.g., proper time) that define spacetime embedment for massive entities. Timeless approaches, such as Barbour's configuration space~\cite{Barbour2000}, hint at resolutions, but TLM explicitly exiles photons to a senior quantum layer.

\section{Defining ``Being Inside the Universe''}

To advance our logical argument, we must first establish a clear criterion for what it means for an entity to be ``inside'' or embedded in the universe, specifically within the fabric of spacetime as described by GR. This definition is not arbitrary but derived from the mathematical and physical principles of GR, where embedment implies participation in the timelike structure that defines measurable intervals and causal relations. We posit that true embedment requires a timelike worldline, proper time, and a rest frame---attributes that confer an intrinsic experience of time and distance.

\subsection{The Requirement of a Rest Frame for Inclusion Inside Spacetime}

In GR, a rest frame is the coordinate system where an entity's 4-velocity is purely timelike, allowing it to serve as an observer with a proper time \(\tau > 0\)~\cite{Rovelli2004}. This criterion is not ad-hoc; GR textbooks define physical observers exclusively via timelike paths~\cite{Rovelli2004}. This frame is essential for defining physical presence: it enables the entity to measure spacetime intervals and interact causally within the manifold. Massive particles satisfy this via timelike geodesics (\(ds^2 < 0\)), embedding them as integral components of spacetime~\cite{Einstein1905}.

Photons, however, lack this: their null geodesics (\(ds^2 = 0\)) prohibit a rest frame, as no Lorentz transformation can reduce their speed to zero without divergence~\cite{Einstein1905}. Thus, photons cannot be observers or embedded objects in the same ontological sense.

\subsection{The Meaning of Time and Distance Experience for Objects in the Universe}

Embedment in spacetime entails experiencing proper time and proper length, derived from the metric. For timelike paths, \(\tau = \int \sqrt{-ds^2/c^2}\) quantifies the passage of time, grounding causality and measurement~\cite{Rovelli2004}. Distance emerges similarly from spatial projections along the worldline.

For photons, \(\tau = 0\) means no experienced time or distance: emission and absorption are simultaneous from their ``perspective''~\cite{Barbour2000}. This absence implies photons do not ``traverse'' spacetime but connect events timelessly, aligning with TLM's view of photons as instructions in Q~\cite{McKinley2025a}.

\subsection{Logical Consequences of Absence of a Rest Frame}

Without a rest frame, an entity lacks the attributes defining spacetime embedment: no proper intervals, no causal self-reference. Logically, if \(\tau = 0\), the entity has no 'duration' in spacetime, precluding embedment. This leads to the conclusion that photons are ontologically external---causal agents manifesting effects in SDF without being bound by it~\cite{McKinley2025b}. In TLM, this resolves paradoxes like infinite redshift at horizons, treating them as projection artifacts rather than intrinsic properties~\cite{Gryb2018}.

\section{The Logical Proof That Photons Are Not Inside the Universe}

Building on the foundational concepts from GR and our ontological criteria for embedment in spacetime, we now present the deductive argument that photons are not embedded as objects within the universe. This proof relies on two premises: one drawn directly from GR's mathematics and the second from the definition established in Section 3. We then derive the conclusion, address potential counterarguments, and demonstrate how this exile aligns with the Timeless Light Model (TLM).

\subsection{Premise 1: GR's Statement That Photons Have No Rest Frame}

General Relativity unequivocally states that photons, as massless particles following null geodesics, possess no rest frame. Mathematically, this arises from the null interval \(ds^2 = 0\), which implies zero proper time \(\tau = 0\) along the photon's worldline~\cite{Einstein1905, Rovelli2004}. The energy-momentum relation \(E = pc\) (for \(m = 0\)) confines photons to lightlike paths, where Lorentz transformations fail to define an inertial frame at \(v = c\)---the boost factor \(\gamma\) diverges. The 4-momentum \(p^\mu = (E/c, \mathbf{p})\) for photons yields \(p^\mu p_\mu = 0\), confirming null nature and frame absence. This is not an interpretive claim but a direct consequence of the theory's formalism: null worldlines lack the timelike component necessary for a rest frame~\cite{Rovelli2004}.

\subsection{Premise 2: Having a Rest Frame Is Necessary to Be ``In'' the Universe as an Object}

As formalized in Section 3, existence as an embedded object in spacetime requires a timelike worldline (\(ds^2 < 0\)), proper time \(\tau > 0\), and a rest frame. These attributes enable an entity to experience time and distance, participate in causal measurements, and define its position within the manifold~\cite{Barbour2000}. Without them, an entity cannot be ontologically ``in'' spacetime in the same manner as massive particles; it functions instead as a boundary or causal connector.

This premise is grounded in GR's treatment of observers: only timelike paths support physical frames, as null paths collapse intervals to zero, precluding intrinsic embedment~\cite{Gryb2018}.

\subsection{Deductive Conclusion}

From Premise 1 (photons lack a rest frame per GR) and Premise 2 (a rest frame is required for embedment in spacetime), it follows deductively that photons are not embedded objects in the universe. Instead, they are ontologically external---timeless entities whose effects manifest within spacetime without being bound by its structure. In TLM terms, photons resolve as instructions in the Quantum Platform (Q), projecting into the Spacetime Deployment Frame (SDF) where GR phenomena emerge~\cite{McKinley2025a, McKinley2025b}.

This conclusion reframes photons not as travelers but as instantaneous causal bridges, resolving paradoxes like zero-time journeys across cosmic distances.

\begin{table}[h]
\centering
\begin{tabular}{lcc}
\toprule
Aspect & Timelike (Massive) & Null (Photons) \\
\midrule
Interval & \(ds^2 < 0\) & \(ds^2 = 0\) \\
Proper Time & \(\tau > 0\) & \(\tau = 0\) \\
Rest Frame & Possible & Impossible \\
Ontology in TLM & Embedded in SDF & Instruction in Q \\
\bottomrule
\end{tabular}
\caption{Comparison of Worldlines in GR and TLM Implications.}
\label{tab:worldlines}
\end{table}

\subsection{Addressing Counterarguments to the Proof}

Critics may argue that photons' contribution to the stress-energy tensor \(T_{\mu\nu}\) proves their embedment, as they source curvature~\cite{Rovelli2004}. However, this confuses effects (projections in SDF) with ontology: TLM views \(T_{\mu\nu}\) as rendered outcomes of Q instructions, preserving GR equations while subordinating them causally~\cite{McKinley2025a}.

Another objection: photons are measurable in observers' frames, implying existence in spacetime. Response: measurability confirms projections in SDF, not intrinsic embedment; analogous to virtual particles mediating forces without being ``real'' objects~\cite{Polchinski1998}.

Finally, claims of unfalsifiability are addressed by TLM's predictions, such as discrete thresholds in photon interactions, testable via quantum optics~\cite{Giacomini2022}.

\section{Implications of the Proof}

The logical exile of the photon from spacetime, as deduced from GR's mathematics, carries profound implications for our understanding of fundamental physics. Rather than invalidating GR, this reinterpretation elevates it as an emergent framework within a broader causal hierarchy. Here, we explore how this proof reconceptualizes photons, integrates with the Timeless Light Model (TLM), and addresses longstanding paradoxes at the GR-QM interface.

\subsection{Reconceptualizing Photons as Timeless Causal Instructions}

The proof establishes that photons, lacking a rest frame and proper time, cannot be embedded objects traversing spacetime. Instead, they must be timeless causal instructions---pre-resolved links that connect events without enduring the intervals between them~\cite{McKinley2025a, McKinley2025b}. In this view, what observers perceive as a photon's "path" is a rendered projection: the null geodesic in GR describes the experiential unfolding in the Spacetime Deployment Frame (SDF), not an intrinsic journey.

This shifts the ontology of light from a particle or wave propagating through spacetime to a foundational instruction in the Quantum Platform (Q). Emission and absorption become the endpoints of an instantaneous resolution in Q, with the apparent "travel time" arising from delay in the SDF~\cite{McKinley2025e}. Such a reconceptualization aligns with GR's null intervals while explaining why photons defy classical embedment.

\subsection{How TLM Provides a Coherent Framework Resolving the Paradox}

The Timeless Light Model (TLM) naturally accommodates this exile by positing a layered reality: the universe comprises Q (timeless quantum instructions) and SDF (delayed GR projection), with photons bridging the two~\cite{McKinley2025a, McKinley2025b}. GR emerges as the rendered dynamics in SDF, subordinate to Q's logic, preserving all empirical predictions like light deflection while resolving conceptual issues. TLM's delay law \(T \cdot C_s = 1\) derives GR from Q~\cite{McKinley2025e}.

For instance, the absence of a photon frame in GR is no longer a peculiarity but evidence of Q's seniority: photons resolve causally outside spacetime constraints, projecting energy-momentum into SDF via thresholds (e.g., \(\Delta E >\) class-specific value)~\cite{McKinley2025a}. This hierarchy unifies GR and QM without new physics, as quantum phenomena (e.g., entanglement) are timeless Q resolutions manifesting non-locally in SDF~\cite{EPR1935, McKinley2025c}.

\subsection{Consequences for Interpretation of Light, Causality, and Spacetime Structure}

This exile redefines causality: light does not "propagate" but instructs instantaneous updates, with apparent speed \(c\) as a derived limit in SDF~\cite{McKinley2025d}. Spacetime curvature becomes a delay-induced effect, where mass (as instructional resistance) warps the projection~\cite{McKinley2025c}. Consequences include:
- \textbf{Cosmological Implications:} The Big Bang as the first Q deployment, resolving the "first frame" paradox~\cite{Barbour2000}.
- \textbf{Black Holes:} Horizons as boundaries where delays approach infinity, with Hawking radiation as metered Q releases~\cite{McKinley2025a}.
- \textbf{Dark Energy/Matter:} Potential photon-silent instructions in Q manifesting as unlinked mass in SDF~\cite{McKinley2025b}.

These reinterpretations challenge the primacy of spacetime geometry, positioning it as experiential rather than foundational.

\subsection{Relationship to Quantum Mechanics and the Nature of Quantum Information}

The proof bridges GR-QM tensions: quantum non-locality (e.g., EPR pairs) arises from timeless Q resolutions, appearing instantaneous in SDF without violating GR's local causality~\cite{EPR1935}. Wavefunction collapse becomes a projection update, with probabilities as SDF-local estimates of Q logic~\cite{McKinley2025a}. Quantum information, carried by photons, is thus timeless in origin, explaining entanglement's frame-independence.

This aligns with timeless quantum gravity approaches~\cite{Gryb2018, Giacomini2022}, but TLM's hierarchy provides a causal mechanism, subordinating GR to QM for unification.

\section{Potential Experimental or Observational Consequences}

The logical proof that photons are exiled from spacetime, while interpretive, yields testable predictions through the Timeless Light Model (TLM). By subordinating GR to quantum instructions in Q, TLM anticipates deviations from standard GR and QM at interfaces where timeless resolutions project into SDF. These predictions focus on threshold effects, non-locality, and quantization artifacts, potentially observable with current or near-future technology. We outline key consequences, falsifiability criteria, and comparisons to standard models.

\subsection{Predictions Arising from TLM’s Photon Interpretation}

TLM's core axiom---photons as timeless instructions---implies discrete deployments triggered by energy thresholds (\(\Delta E >\) class-specific value)~\cite{McKinley2025a}. This leads to:
- \textbf{Quantized Curvature Thresholds:} GR assumes continuous curvature, but TLM predicts step-like effects in photon paths near high-mass regions, e.g., anomalous lensing fluctuations detectable in gravitational wave interferometers like LIGO or future space-based detectors~\cite{McKinley2025a, Gryb2018}.
- \textbf{Mass-Dependent Entanglement Delays:} In entangled systems, resolution in Q is instantaneous, but projection into SDF introduces delays proportional to observer mass (\(T \propto 1/m\)), e.g., \(\Delta t \approx GM/c^3\) for detector mass M~\cite{McKinley2025c}. This could manifest as measurable latency in quantum networks, testable via satellite-based entanglement experiments~\cite{EPR1935}.
- \textbf{Non-Thermal Hawking Radiation Signatures:} Black hole evaporation, as delayed Q releases, may exhibit pulsed or discrete spectra rather than pure thermal emission, observable in analog black holes or high-energy astrophysics~\cite{McKinley2025b, Giacomini2022}.

These arise from TLM's delay-rate invariant \(T \cdot C_s = 1\), where \(C_s\) is the causal deployment rate~\cite{McKinley2025e}.

\subsection{Falsifiability Criteria and Test Proposals}

TLM is falsifiable: absence of predicted thresholds (e.g., no quantization in curvature at Planck scales) would refute it. Proposed tests include:
- \textbf{Quantum Optics Experiments:} Modified delayed-choice setups to probe timelessness, expecting mass-induced asymmetries in interference patterns~\cite{McKinley2025d}.
- \textbf{Precision Gravity Measurements:} Search for discrete jumps in light bending near neutron stars via telescopes like JWST, deviating from GR's smoothness.
- \textbf{Analog Systems:} Lab-based event horizons (e.g., fluid analogs) to detect metered information release, contrasting continuous Hawking predictions~\cite{Barbour2000}.

Failure to observe these would support standard GR interpretations over TLM.

\subsection{Comparison with Standard Photon Behavior in GR and QM}

In GR, photons bend continuously without thresholds; TLM predicts the same averages but with potential noise at extremes. In QM, entanglement is non-local; TLM explains this via Q resolutions, predicting observable delays absent in standard models~\cite{EPR1935}. These distinctions provide clear empirical discriminants, positioning TLM as a testable extension.

\section{Conclusion}

This paper has presented a logical argument, grounded in the mathematics of General Relativity (GR), that photons are not embedded objects within spacetime. By establishing that a rest frame and proper time are essential for ontological inclusion in the universe, and demonstrating GR's denial of these to photons via null geodesics and \(\tau = 0\), we conclude that light is ontologically external---a timeless causal agent rather than a spacetime-bound entity~\cite{Einstein1905, Rovelli2004}.

This non-embedment resolves deep paradoxes, such as the photon's frameless propagation, and motivates the Timeless Light Model (TLM) as a unifying framework. In TLM, photons resolve as instructions in the Quantum Platform (Q), projecting effects into the Spacetime Deployment Frame (SDF) where GR emerges~\cite{McKinley2025a, McKinley2025b}. Far from a semantic exercise, this reinterpretation preserves GR's predictions while subordinating it to quantum causality, offering a pathway to resolve GR-QM tensions like entanglement and wavefunction collapse~\cite{EPR1935, McKinley2025c}.

The implications extend to cosmology, black holes, and quantum information, with falsifiable predictions such as quantized curvature thresholds testable in current experiments~\cite{Gryb2018, Giacomini2022}. We call for further theoretical and empirical exploration: deriving full metrics from TLM's axioms, solving deployment dynamics, and testing mass-dependent delays~\cite{McKinley2025d, McKinley2025e}. Ultimately, the photon's non-embedment illuminates a layered reality, where spacetime is not fundamental but a rendered experience of deeper timeless logic~\cite{Barbour2000}. This perspective invites a reevaluation of light's role, potentially revolutionizing our understanding of the universe. This proof, rooted in GR's equations, compels a timeless ontology for light, as formalized in TLM.

\appendix

\section{Mathematical Derivations Supporting the Proof}

This appendix provides brief derivations of key GR results underpinning Premise 1, emphasizing the mathematical basis for the photon's lack of a rest frame.

\subsection{Derivation of Zero Proper Time for Photons}

The spacetime interval in GR is \(ds^2 = g_{\mu\nu} dx^\mu dx^\nu\). For null geodesics (photons), \(ds^2 = 0\). Proper time \(\tau\) is defined as \(d\tau^2 = -ds^2 / c^2\) (Minkowski signature). Thus, \(d\tau = 0\), implying \(\tau = 0\) along the worldline~\cite{Rovelli2004}. For detailed treatment, see Misner et al. (1973)~\cite{MTW1973}.

\subsection{Lorentz Boost Divergence at \(v = c\)}

The Lorentz factor is \(\gamma = 1 / \sqrt{1 - v^2/c^2}\). As \(v \to c\), \(\gamma \to \infty\), rendering transformations to a photon frame undefined. This mathematical singularity confirms no inertial rest frame exists~\cite{Einstein1905}.

These derivations, standard in GR, directly support the proof's logical structure.

\begin{thebibliography}{99}

\bibitem{Einstein1949} A. Einstein, quoted in "Albert Einstein: Philosopher-Scientist," ed. P. A. Schilpp, Open Court Publishing (1949).

\bibitem{Feynman1965} R. P. Feynman, "The Character of Physical Law," MIT Press (1965).

\bibitem{McKinley2025a} J. C. W. McKinley, "Unified Physics by Subordination of GR to QM: A Layered Reality Framework," Zenodo (2025), doi:10.5281/zenodo.15956986.

\bibitem{McKinley2025b} J. C. W. McKinley, "Unified Physics by Subordination of GR to QM: Version 4.0 Instructional Photons and Causal Rendering," Zenodo (2025), doi:10.5281/zenodo.16019797.

\bibitem{McKinley2025c} J. C. W. McKinley, "On a Postulated Mass-Time Action Principle: A Novel Approach to Quantum Gravity," Zenodo (2025), doi:10.5281/zenodo.15770207.

\bibitem{McKinley2025d} J. C. W. McKinley, "Causality Without Light Speed: Reframing c as a Derived, Not Fundamental, Limit," Zenodo (2025), doi:10.5281/zenodo.15826480.

\bibitem{McKinley2025e} J. C. W. McKinley, "Clarifying Causal Rate: The Instructional Delay Law T $\cdot$ C$_s$=1," Zenodo (2025), doi:10.5281/zenodo.15817350.

\bibitem{Barbour2000} J. Barbour, "The End of Time: The Next Revolution in Physics," Oxford University Press (2000).

\bibitem{Gryb2018} S. Gryb and K. Thébault, "Quantum gravity in timeless configuration space," Classical and Quantum Gravity 35, 035004 (2018). arXiv:1706.08875.

\bibitem{Giacomini2022} F. Giacomini, A. R. H. Smith, and Č. Brukner, "A model of quantum spacetime," Nature Communications 13, 1196 (2022). arXiv:2207.01005.

\bibitem{Einstein1905} A. Einstein, "Zur Elektrodynamik bewegter Körper," Annalen der Physik, 322(10), 891-921 (1905).

\bibitem{EPR1935} A. Einstein, B. Podolsky, \& N. Rosen, "Can Quantum-Mechanical Description of Physical Reality Be Considered Complete?," Physical Review, 47(10), 777-780 (1935).

\bibitem{Rovelli2004} C. Rovelli, "Quantum Gravity," Cambridge University Press (2004).

\bibitem{Polchinski1998} J. Polchinski, "String Theory," Cambridge University Press (1998).

\bibitem{Maudlin2012} T. Maudlin, "Philosophy of Physics: Space and Time," Princeton University Press (2012).

\bibitem{Albert1992} D. Z. Albert, "Quantum Mechanics and Experience," Harvard University Press (1992).

\bibitem{Carroll2019} S. Carroll, "Something Deeply Hidden: Quantum Worlds and the Emergence of Spacetime," Dutton (2019).

\bibitem{MTW1973} C. W. Misner, K. S. Thorne, and J. A. Wheeler, "Gravitation," W. H. Freeman (1973).

\end{thebibliography}

\end{document}
```

</details>

---
{% endraw %}
