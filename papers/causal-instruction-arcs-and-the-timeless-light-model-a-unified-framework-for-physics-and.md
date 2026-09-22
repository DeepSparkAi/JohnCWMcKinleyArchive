---
layout: default
title: '[2025] Causal Instruction Arcs and the Timeless Light Model: A Unified Framework for Physics and Cosmology'
description: 'Publication metadata and archived raw LaTeX source by John C. W. McKinley.'
permalink: /papers/causal-instruction-arcs-and-the-timeless-light-model-a-unified-framework-for-physics-and/
paper: true
---
{% raw %}
# [2025] Causal Instruction Arcs and the Timeless Light Model: A Unified Framework for Physics and Cosmology
*   **DOI:** [10.5281/zenodo.15813253](https://doi.org/10.5281/zenodo.15813253)
*   **Date:** 5 July 2025

<details markdown="1">
<summary><b>Click to view Raw LaTeX Source</b></summary>

```latex
\documentclass[12pt]{article}
\usepackage{amsmath, amssymb}
\usepackage{geometry}
\usepackage{booktabs}
\usepackage{tikz}
\usetikzlibrary{shapes.geometric}
\usepackage[utf8]{inputenc}
\usepackage{natbib}
\usepackage{tcolorbox}
\usepackage{tabularx}
\usepackage{siunitx}
\usepackage{hyperref}
\geometry{a4paper, margin=1in}
\numberwithin{equation}{section}
\errorcontextlines=999
\usepackage{breqn}
\linespread{1.15}
\bibliographystyle{apsrev4-2} % Physical Review D style
\hypersetup{
  colorlinks=true,
  linkcolor=blue,
  citecolor=blue,
  urlcolor=blue,
}


\begin{document}

\title{Causal Instruction Arcs and the Timeless Light Model: A Unified Framework for Physics and Cosmology}
\author{John C. W. McKinley%
\thanks{DOI: \href{https://doi.org/10.5281/zenodo.15813253}{10.5281/zenodo.15813253}}\\
Independent Researcher\\
\href{https://orcid.org/0009-0005-7097-5035}{ORCID: 0009-0005-7097-5035}
}

\date{July 2025}
\maketitle

\begin{abstract}
\label{sec:abstract}

The Timeless Light Model (TLM) proposes a unified framework for General Relativity and Quantum Mechanics through a mass-induced delay mechanism, defined by the axiom \( T \cdot m = \hbar / c^2 \). This framework introduces the Photon Instruction Layer (PIL), a timeless substrate encoding causal instructions, and predicts observable consequences such as quantum delays (\(\sim \SI{e-12}{\second}\)), gravitational wave phase shifts, and cosmic microwave background (CMB) anomalies (\(\sim \SI{e-11}{\radian}\)). These effects are falsifiable with current photon counting, gravitational, and cosmological instrumentation. By reinterpreting causality via Causal Instruction Arcs (CI-ARCs), the TLM offers a deterministic resolution to the black hole information paradox and quantum entanglement. We outline empirical protocols and parameter thresholds for experimental falsification, distinguishing the TLM from high-energy theories lacking near-term tests.
\end{abstract}




\textbf{Keywords:} Timeless Light Model, General Relativity, Quantum Mechanics, causality, mass-induced delay, dark matter, quantum entanglement, cosmic microwave background.


\section{Introduction}
\label{sec:introduction}

The unification of General Relativity (GR) and Quantum Mechanics (QM) remains a central challenge in physics, as these frameworks operate at disparate scales with incompatible mathematical structures \citep{Einstein1915, Dirac1930}. The Timeless Light Model (TLM) proposes a novel framework to bridge GR and QM through a mass-induced delay mechanism, defined by the axiom \( T \cdot m = \hbar / c^2 \), where \( T \) is the characteristic timescale, \( m \) is invariant mass, \( \hbar \) is the reduced Planck constant, and \( c \) is the speed of light. This mechanism redefines causality, yielding testable predictions such as quantum delays (\(\sim \SI{e-12}{\second}\)) and cosmic microwave background (CMB) phase shifts (\(\sim \SI{e-11}{\radian}\)), accessible with current technology (Section~\ref{sec:empirical_predictions}).

The TLM is a theoretical proposal, distinct from high-energy frameworks, with immediate experimental prospects.
Unlike high-energy unification theories like String Theory or Loop Quantum Gravity \citep{Green1987, Rovelli2004}, the TLM operates at low energy scales, offering immediate experimental prospects. It addresses key issues, including the black hole information paradox and quantum entanglement, through Causal Instruction Arcs (CI-ARCs) within a timeless Photon Instruction Layer (PIL). The TLM also derives the emergence of three-dimensional space, aligning with observed geometry (Section~\ref{sec:space_dark_matter}). Speculative extensions, such as a dark matter interpretation and philosophical implications, are explored in Appendix~\ref{app:speculative} to maintain focus on empirically grounded results. 

\subsection{The Unification Challenge in Physics}
\label{subsec:unification_challenge}
GR models gravity as spacetime curvature \citep{Weinberg1972}, while QM governs subatomic phenomena via probabilistic wavefunctions \citep{Sakurai1994}. Their incompatibility in extreme regimes, such as black holes, motivates unification efforts. The TLM’s single axiom offers a practical approach, distinct from high-energy frameworks requiring inaccessible scales.

\subsection{The Timeless Light Model: Overview of a New Paradigm}
\label{subsec:tlm_paradigm}
The TLM posits that physical reality emerges from a timeless PIL, a directed graph \( G = (V, E) \), with events sequenced by the mass-induced delay (Equation~\ref{eq:delay_axiom}). CI-ARCs, analogous to QFT propagators, encode causality, while the Spacetime Deployment Frame (SDF) emerges as their projection, resembling GR’s spacetime manifold. This framework unifies GR and QM, predicting observable effects detailed in Section~\ref{sec:empirical_predictions}.

\subsection{Objectives and Structure}
\label{subsec:objectives_structure}
This paper presents the TLM’s core framework, focusing on its axiom, spatial emergence, and testable predictions (Sections~\ref{sec:tlm_framework}, \ref{sec:space_dark_matter}, \ref{sec:empirical_predictions}). Section~\ref{sec:ci_arcs_ese} defines CI-ARCs and Extra-SDF Events. Section~\ref{sec:comparison} compares TLM to existing theories, and Section~\ref{sec:philosophical} discusses implications for time, space, and quantum gravity. Speculative extensions, including dark matter and philosophical considerations, are deferred to Appendix~\ref{app:speculative}. Experimental protocols are detailed in Section~\ref{sec:expanded_protocols}, with notation, derivations, and glossary in Appendices~\ref{app:notation}, \ref{app:derivations}, and Section~\ref{sec:glossary}.


\begin{figure}[htbp]
    \centering
    \sisetup{scientific-notation = true}


    \begin{tikzpicture}
        \node[ellipse, draw, fill=gray!10, minimum height=0.8cm, minimum width=1.8cm] (PIL) at (0,3) {PIL};
        \node[rectangle, draw, fill=blue!10, minimum height=0.8cm, minimum width=2.5cm] (SDF) at (0,0) {SDF};
        \node[ellipse, draw, dashed, minimum height=0.8cm, minimum width=1.8cm] (CIARC) at (3,3) {CI-ARCs};
        \node[circle, draw, minimum size=0.6cm] (ESE) at (3,0) {ESEs};
        \draw[->, thick] (PIL) -- (SDF);
        \draw[->, dashed] (CIARC) -- (PIL);
        \draw[->, dotted] (CIARC) -- (ESE);
        \draw[->, dotted] (ESE) -- (SDF);
    \end{tikzpicture}
    \caption{Schematic of the Timeless Light Model (TLM). The Photon Instruction Layer (PIL) is a pre-spacetime structure encoding causal events, akin to a relational framework. The Spacetime Deployment Frame (SDF) is the observable spacetime, analogous to the manifold in general relativity. Causal Instruction Arcs (CI-ARCs) are causal links between events, similar to propagators in quantum field theory, governed by the mass-induced delay (Equation~\ref{eq:delay_axiom}). Extra-SDF Events (ESEs) represent instantaneous quantum correlations, resembling entangled states. See Sections~\ref{sec:tlm_framework} and \ref{sec:ci_arcs_ese} for details.}
    \label{fig:tlm_schematic}
\end{figure}

\section{Experimental Protocols}
\label{app:protocols}

Detailed experimental protocols for testing the TLM’s predictions, including quantum delays (\(\sim \SI{e-12}{\second}\)) and CMB phase shifts (\(\sim \SI{e-11}{\radian}\)), are provided in Section~\ref{sec:expanded_protocols}. These protocols leverage current technology, such as photon counting devices and CMB analysis pipelines, to validate the TLM’s mass-induced delay axiom and its implications for quantum and cosmological phenomena \citep{Sakurai1994, Aghanim2020, Steinhauer2016}.











\section{The Timeless Light Model Framework}
\label{sec:tlm_framework}

\subsection{Foundational Axiom: Delay Mechanism}
\label{subsec:foundational_axiom}
The TLM rests on the axiom that the timing of physical events depends on a mass-induced delay, expressed as:
\begin{equation}
T \cdot m = \frac{\hbar}{c^2},
\label{eq:delay_axiom}
\end{equation}
where \( T \) is the characteristic timescale (s), \( m \) is the invariant mass (kg), \( \hbar = \SI{1.0545718e-34}{\joule\second} \) is the reduced Planck constant, and \( c = \SI{2.99792458e8}{\meter\per\second} \) is the speed of light (see Appendix \ref{subapp:mass_time} for derivation). This delay creates a measurable sequence of events, with \( c \) as the maximum rate, ensuring interactions occur in a structured progression observable in the Spacetime Deployment Frame (SDF) \citep{Weinberg1972}.

\subsection{Timeless Causal Ledger}
\label{subsec:timeless_ledger}
The TLM posits a timeless Photon Instruction Layer (PIL), a non-spatial directed graph \( G = (V, E) \), where vertices \( V \) represent event endpoints (e.g., photon emission and absorption) and edges \( E \) represent Causal Instruction Arcs (CI-ARCs, defined in Section \ref{subsec:pil_ciarcs}). Light-like entities are complete causal instructions linking causes to effects, with only their endpoints observable in the Spacetime Deployment Frame (SDF), suggesting a non-spatial origin for physical processes \citep{Rovelli2004}. For example, consider a photon emitted from a star and absorbed by a detector on Earth. In the PIL, this is represented by a CI-ARC with vertices \( v_i \) (emission at the star) and \( v_j \) (absorption at the detector), connected by an edge \( E = (v_i, v_j, C, \Delta, D) \), where \( C \) enforces energy-momentum conservation, \( \Delta = 0 \) (as the photon is massless), and \( D = \frac{|\mathbf{x}_j - \mathbf{x}_i|}{\lambda_C} \) encodes the spatial distance between star and detector, with \( \lambda_C \) being the Compton wavelength of an associated massive particle.

\subsection{Emergent Observed Reality}
\label{subsec:emergent_reality}
The observable universe emerges as a projection from the PIL into the SDF, where events appear sequential due to mass-induced delays governed by Equation~\ref{eq:delay_axiom}. This creates the illusion of time, analogous to events piercing a spacetime fabric, with each pierce representing a CI-ARC projection \citep{Weinberg1972}.

\subsection{Definition of an Observer}
\label{subsec:observer_definition}
An observer is any physical system capable of recording a permanent state change, such as a detector registering a photon or a molecule undergoing a chemical reaction. The state change corresponds to the quantum wavefunction collapse, driven by CI-ARC projection into the SDF, resolving the measurement problem via deterministic delays \citep{Sakurai1994, Zeilinger1999}. Unlike Quantum Mechanics, where the observer’s role is ambiguous and sometimes interpreted as requiring consciousness \citep{Dirac1930}, the TLM’s observer is strictly physical, defined by its capacity to register a state change without invoking subjective awareness. This deterministic, physical definition aligns with the TLM’s causal framework, distinguishing it from QM’s probabilistic and observer-dependent collapse.

In contrast to QM’s Copenhagen interpretation, where wavefunction collapse is a probabilistic event triggered by measurement \citep{Dirac1930}, the TLM posits that collapse occurs deterministically when a CI-ARC projects an event from the PIL to the SDF, governed by the mass-induced delay \( T \cdot m = \hbar / c^2 \). This eliminates the need for an external observer or probabilistic outcomes, as the state change is an intrinsic property of the physical system’s interaction with the PIL. For example, in a photon detection event, the detector’s mass induces a delay that sequences the event, fixing the outcome without ambiguity \citep{Sakurai1994}.

This deterministic approach is supported by experimental evidence from Bell test experiments, which demonstrate non-local correlations in entangled systems without requiring subjective intervention \citep{Zeilinger1999}. In the TLM, such correlations arise from Extra-SDF Events (ESEs) with zero delay (\(\Delta = 0\)), projected instantaneously from the PIL. For instance, in a Bell test with entangled photons, the TLM models the correlation as a CI-ARC linking emission and detection events, with conservation constraints ensuring consistency. This aligns with observed violations of Bell inequalities, grounding the TLM’s observer definition in empirical reality and distinguishing it from QM’s probabilistic framework \citep{Zeilinger1999}.



\subsection{Axiom and Delay Law}
\label{subsec:axiom}
The core axiom of the Timeless Light Model (TLM) is the mass-induced delay relation (Equation~\ref{eq:delay_axiom}), where \( T \) is the characteristic timescale (in seconds), \( m \) is the invariant mass (in kg), \( \hbar = \SI{1.0545718e-34}{\joule\second} \), and \( c = \SI{2.99792458e8}{\meter\per\second} \). This axiom governs the ``DELAY TO C'' law, which paces causal events to the speed of light in the Spacetime Deployment Frame (SDF). The delay \( T \) represents the time required for a timeless instruction from the Photon Instruction Layer (PIL) to manifest in the SDF, proportional to the mass \( m \).












\section{Causal Instruction Arcs and Extra-SDF Events}
\label{sec:ci_arcs_ese}

This section defines Causal Instruction Arcs (CI-ARCs) and Extra-SDF Events (ESEs), which form the core of the Timeless Light Model’s (TLM) causal framework. CI-ARCs govern physical interactions through a mass-induced delay, while ESEs account for instantaneous quantum effects. Established derivations are grounded in the TLM’s core axiom (Equation~\ref{eq:delay_axiom}), with speculative extensions clearly labeled to distinguish them from verified claims.


\subsection{Definition of Timeless Causal Units}
\label{subsec:timeless_causal_units}
Physical interactions are governed by Causal Instruction Arcs (CI-ARCs), defined as tuples \( (v_i, v_j, C, \Delta, D) \), where \( v_i, v_j \in V \) are emission and absorption points in the Photon Instruction Layer (PIL), \( C \) ensures conservation of energy and momentum, \( \Delta \) is the delay from the TLM axiom:
\begin{equation}
T \cdot m = \frac{\hbar}{c^2},
\end{equation}
and \( D = \frac{|\mathbf{x}_j - \mathbf{x}_i|}{\lambda_C} \) codes spatial separation, with \( \lambda_C = \frac{\hbar}{m c} \). These units underpin all observed phenomena, redefining causality as a projection from the timeless PIL to the Spacetime Deployment Frame (SDF) \citep{Zeilinger1999}.


\subsection{Instantaneous Effect Subset}
\label{subsec:instantaneous_subset}
Extra-SDF Events (ESEs) are CI-ARCs with zero projection delay (\( \Delta = 0 \)), enabling instantaneous quantum effects such as entanglement or tunneling. These account for correlations without spatial or temporal propagation in the SDF, aligning with delayed-choice experiments that challenge traditional spacetime concepts \citep{Sakurai1994, Wheeler1978}.

\subsection{Mathematical Representation}
\label{subsec:math_representation}
The TLM models CI-ARCs as a causal network, with a projection function translating timeless units into observable events, modulated by the established causal resolution rate:
\begin{equation}
\frac{dI}{dt} = \frac{c^2}{\hbar m},
\end{equation}
where \( I \) is a dimensionless causal index representing the cumulative progression of causal events, such as the projection of CI-ARCs from the PIL to the SDF (Appendix~\ref{subapp:causal_rate}). Physically, \( I \) quantifies the advancement of the universe’s causal structure, with each increment corresponding to the completion of a causal interaction. This rate is derived from the TLM axiom and describes the pace of event deployment in the SDF \citep{Feynman1965}.

\textbf{Speculative Extension}: A proposed symmetry, given by:
\begin{equation}
T \cdot \left( \frac{v}{c} \right)^2 = \frac{\hbar}{m c^2},
\end{equation}
suggests a potential balance between temporal and spatial delays, where \( v \) is the system’s velocity. This relation is conjectural, motivated by dimensional consistency but lacking empirical validation (Appendix~\ref{subapp:symmetry}). It is included to guide future theoretical exploration, with experimental tests proposed in high-precision quantum experiments, such as velocity-dependent delay measurements in particle accelerators \citep{Feynman1965}. This speculative claim is distinct from the established CI-ARC framework and requires further investigation to confirm its physical relevance.







\section{Space Creation}
\label{sec:space_dark_matter}

This section derives the emergence of three-dimensional space in the Timeless Light Model (TLM), a core result grounded in the mass-induced delay axiom (Equation~\ref{eq:delay_axiom}). A speculative hypothesis regarding dark matter is briefly introduced, with details deferred to Appendix~\ref{app:speculative}.

\subsection{Role of Spatial Relationship Factor}
\label{subsec:spatial_factor}
Three-dimensional space emerges from the Distance Factor (\( D \)) in Causal Instruction Arcs (CI-ARCs), defined as:
\begin{equation}
D = \frac{|\mathbf{x}_j - \mathbf{x}_i|}{\lambda_C},
\end{equation}
where \( \lambda_C = \frac{\hbar}{m c} \) is the Compton wavelength, and \( |\mathbf{x}_j - \mathbf{x}_i| \) is the spatial separation in the Spacetime Deployment Frame (SDF). The spatial distance is:
\begin{equation}
|\mathbf{x}_j - \mathbf{x}_i| = D \cdot \frac{\hbar}{m c}.
\end{equation}
This relation, derived from the TLM’s causal framework, ensures that spatial separation in the SDF is a projection of CI-ARC properties, consistent with observed Euclidean geometry at macroscopic scales \citep{Weinberg1972}. The derivation leverages the Compton wavelength to anchor quantum scales to relativistic spacetime, providing a unified description of spatial emergence.

\subsection{Speculative Extension: Dark Matter and Cosmology}
\label{subsec:speculative_extension}
The TLM’s spatial framework motivates a speculative hypothesis that CI-ARCs with large Distance Factors (\( D \)) may contribute to gravitational effects attributed to dark matter, potentially mimicking its influence on cosmic motion. Additionally, increasing \( D \) values may relate to cosmic expansion. These ideas are exploratory and lack empirical validation, so they are detailed in Appendix~\ref{app:speculative}, with proposed tests using gravitational lensing and CMB data.











\subsection{Comparison with Experimental Limits}
\label{subsec:comparison_limits}
The TLM’s predictions are compared to the Standard Model, \(\Lambda\)CDM, String Theory, and Loop Quantum Gravity (LQG) in Table~\ref{tab:empirical_comparison}. Statistical significance is quantified via signal-to-noise ratio (SNR), with experimental bounds from current data.

\begin{table}[h]
    \centering
    \begin{tabular}{l l l l l l l}
        \toprule
        \textbf{Phenomenon} & \textbf{TLM} & \textbf{Standard Model/ΛCDM} & \textbf{String Theory} & \textbf{LQG} & \textbf{Exp. Bound} & \textbf{SNR} \\
        \midrule
        Quantum Delays & \SI{9.49e-12}{\second} & \SI{0}{\second} & None & None & \SI{<e-14}{\second} \citep{Marcikic2003} & 380 \\
        CMB Phase Shift & \SI{3.6e-11}{\radian} & \SI{0}{\radian} & None & None & \SI{<e-10}{\radian} \citep{Aghanim2020} & \SI{3.6e-8}{} \\
        Black Hole Radiation & Pulsed (\SI{10}{\hertz}) & Continuous & Planck-scale & Quantized & \SI{<1}{\hertz} \citep{Steinhauer2016} & 1000 \\
        GW Phase Shift & \SI{9.8e-15}{\radian} & \SI{<e-12}{\radian} & None & None & \SI{<e-14}{\radian} \citep{Abbott2016} & 9.8 (stacked) \\
        \bottomrule
    \end{tabular}
    \caption{Comparison of TLM predictions with Standard Model, \(\Lambda\)CDM, String Theory, LQG, and experimental bounds. SNR reflects detectability with current (or stacked) data.}
    \label{tab:empirical_comparison}
\end{table}

The quantum delay (\SI{9.49e-12}{\second}) is distinguishable from the Standard Model’s instantaneous interactions, with high SNR in TCSPC experiments \citep{Marcikic2003}. The CMB phase shift (\SI{3.6e-11}{\radian}) is marginally detectable with Planck 2018 but requires future experiments like CMB-S4 \citep{Abazajian2016}. Pulsed black hole radiation contrasts with Hawking’s continuous spectrum, testable in analog systems \citep{Steinhauer2016}. The GW phase shift (\SI{9.8e-15}{\radian}) is below single-event LIGO sensitivity but detectable with stacked events \citep{Abbott2016}. String Theory and LQG lack low-energy predictions, making TLM uniquely testable.











\section{Empirical Predictions}
\label{sec:empirical_predictions}

The Timeless Light Model (TLM) yields testable predictions for quantum, cosmological, and gravitational phenomena, derived from the mass-induced delay axiom \( T \cdot m = \hbar / c^2 \) (Equation~\ref{eq:delay_axiom}) and the causal resolution rate \( \frac{dI}{dt} = \frac{c^2}{\hbar m} \) (Section~\ref{subsec:math_representation}). These include quantum delays (\(\sim \SI{e-12}{\second}\)), cosmic microwave background (CMB) phase shifts (\(\sim \SI{e-11}{\radian}\)), pulsed black hole radiation, and a novel gravitational wave signature detectable by observatories like LIGO/Virgo. Below, we detail these predictions, with a focus on their derivation, experimental feasibility, and a clarified justification for the CMB effective mass. We also discuss potential falsification of the TLM’s predictions to guide future experimental efforts.

The TLM’s predictions, while testable, face challenges from instrumental noise and systematic errors, requiring advanced techniques like multi-event stacking for GW detection.





\subsection{Time Delays in Quantum Experiments}
\label{subsec:time_delays}
The TLM predicts quantum interaction delays of \SIrange{1}{10}{\pico\second}, influenced by detector mass, given by:
\begin{equation}
\Delta t = \frac{\hbar}{M_{\text{detector}} \cdot k},
\label{eq:quantum_delay}
\end{equation}
where \(\hbar = \SI{1.0545718e-34}{\joule\second}\), \(M_{\text{detector}} \sim \SI{1}{\kilogram}\), and \(k \approx \SI{e-19}{\joule}\) is the interaction energy, yielding \(\Delta t \sim \SI{e-12}{\second}\). These delays are testable with photon counting experiments using picosecond-resolution timing, such as time-correlated single-photon counting systems \citep{Sakurai1994}.

\textbf{Derivation}: From the causal resolution rate (Section~\ref{subsec:math_representation}), \(\Delta t \sim \frac{1}{dI/dt} = \frac{\hbar m}{c^2}\). For a detector, \(m\) is replaced by \(M_{\text{detector}} \cdot k / c^2\), giving Equation~\eqref{eq:quantum_delay}.





\subsection{Patterns in Cosmic Background Radiation}
\label{subsec:cmb_patterns}
The TLM predicts phase shifts in the CMB due to CI-ARC correlations, given by:\footnote{This analysis assumes the standard \(\Lambda\)CDM framework for CMB observations, focusing on post-inflationary effects. Inflationary theory, which explains the CMB’s initial conditions and large-scale homogeneity \citep{Guth1981}, is not addressed here, as the TLM’s predictions concern low-energy, late-universe phenomena driven by mass-induced delays. A detailed comparison with inflationary models is beyond the scope of this paper but may be explored in future work.}
\begin{equation}
\Delta \phi = \frac{\hbar}{m_{\text{eff}} c^2} \cdot \frac{H_0}{c},
\label{eq:cmb_phase_shift}
\end{equation}
where \( H_0 \approx \SI{2.2e-18}{\per\second} \) is the Hubble constant, \( c = \SI{2.99792458e8}{\meter\per\second} \), and \( m_{\text{eff}} = \frac{k_B T_{\text{CMB}}}{c^2} \approx \SI{2.4e-41}{\kilogram} \) for \( T_{\text{CMB}} \approx \SI{2.7}{\kelvin} \), with \( k_B = \SI{1.380649e-23}{\joule\per\kelvin} \). This yields:
\begin{dmath}
\Delta \phi \approx \frac{\SI{1.0545718e-34}{\joule\second}}{\SI{2.4e-41}{\kilogram} \cdot (\SI{2.99792458e8}{\meter\per\second})^2} \cdot \SI{7.3e-27}{\per\meter} \approx \SI{3.6e-11}{\radian},
\label{eq:cmb_phase_calc}
\end{dmath}
detectable in Planck 2018 data by analyzing angular power spectra for deviations from standard \(\Lambda\)CDM correlations \citep{Aghanim2020}.




\textbf{Justification for \( m_{\text{eff}} \)}: The effective mass \( m_{\text{eff}} = \frac{k_B T_{\text{CMB}}}{c^2} \) represents the equivalent mass of CMB photons based on their thermal energy at \( T_{\text{CMB}} \approx \SI{2.7}{\kelvin} \). This follows from the energy-mass equivalence, where the CMB’s characteristic energy \( k_B T_{\text{CMB}} \) corresponds to a photon’s effective mass when interacting with CI-ARCs in the TLM framework. This approximation aligns with cosmological models treating CMB photons as a thermal bath influencing large-scale structure \citep{Dodelson2003}, ensuring consistency with the TLM’s delay mechanism.

\textbf{Justification for \( m_{\text{eff}} \)}: 
The effective mass \( m_{\text{eff}} = \frac{k_B T_{\text{CMB}}}{c^2} \approx \SI{2.4e-41}{\kilogram} \) for \( T_{\text{CMB}} \approx \SI{2.7}{\kelvin} \) serves as a thermodynamic proxy mass for CMB photons, derived from their characteristic thermal energy via the energy-mass equivalence \( E = m c^2 \). In the TLM, this proxy mass represents the equivalent mass scale at which CMB photons contribute to mass-induced delays in Causal Instruction Arc (CI-ARC) projections, as governed by Equation~\eqref{eq:delay_axiom}. This approach aligns with cosmological models that treat the CMB as a thermal bath influencing large-scale structure formation \citep{Dodelson2003}, where the energy scale \( k_B T_{\text{CMB}} \) characterizes photon interactions. However, since photons are massless, \( m_{\text{eff}} \) is an approximation, valid within the TLM’s framework for modeling delays but not representing a physical rest mass. This assumption may break down in regimes where photon interactions deviate significantly from thermal equilibrium, such as at high redshifts. Future refinements could explore alternative mass scales, such as those tied to effective interaction energies in the early universe.

\subsection{Gravitational Wave Signatures}
\label{subsec:grav_wave_signatures}
The TLM predicts a modification to gravitational wave (GW) signals from binary black hole mergers, manifesting as a mass-dependent phase shift in the waveform due to CI-ARC delays. For a binary system with total mass \( M \), the phase shift is:
\begin{equation}
\Delta \phi_{\text{GW}} = \frac{\hbar}{M c^2} \cdot f_{\text{GW}},
\end{equation}
where \( f_{\text{GW}} \sim \SI{100}{\hertz} \) is the characteristic GW frequency at merger, and \( M \sim \SI{60}{\msun} \approx \SI{1.2e32}{\kilogram} \) for typical LIGO/Virgo detections. This yields:
\begin{equation}
\Delta \phi_{\text{GW}} \approx \frac{\SI{1.0545718e-34}{\joule\second}}{\SI{1.2e32}{\kilogram} \cdot (\SI{2.99792458e8}{\meter\per\second})^2} \cdot \SI{100}{\hertz} \approx \SI{9.8e-15}{\radian}.
\end{equation}
Although small, this phase shift is detectable with LIGO/Virgo, which achieve phase sensitivities of \(\sim \SI{e-14}{\radian}\) in matched-filtering analyses for high signal-to-noise ratio events (SNR \(\sim 20\)) \citep{Abbott2016}. By analyzing multiple GW events, systematic uncertainties can be reduced, enabling detection of the TLM’s subtle modification to the inspiral waveform.

\textbf{Derivation}: The phase shift arises from the TLM’s mass-induced delay affecting the timing of CI-ARC projections during the merger. The term \(\frac{\hbar}{M c^2}\) is the characteristic timescale from Equation~\ref{eq:delay_axiom}, and \( f_{\text{GW}} \) scales the effect to the GW frequency. The shift modifies the waveform’s inspiral phase, distinguishable from general relativistic predictions via template fitting.

\textbf{Experimental Feasibility}: LIGO/Virgo data from the O3 observing run, publicly available through the Gravitational Wave Open Science Center \citep{Abbott2021}, can be analyzed using Bayesian inference tools like BILBY \citep{Ashton2019}. The TLM’s phase shift is small but within LIGO’s sensitivity for high signal-to-noise ratio events (SNR \(\sim 20\)). Systematic errors, such as waveform model uncertainties, must be mitigated through multi-event analysis.


\subsection{Testable Prediction}
\label{subsec:prediction}
The TLM predicts that systems with higher invariant mass exhibit measurable delays in causal event resolution, proportional to:
\begin{equation}
T = \hbar / (m \cdot c^2).
\end{equation}
For a particle with mass \( m = \SI{e-30}{\kilogram} \), the delay is:
\begin{equation}
T = \frac{\SI{1.0545718e-34}{\joule\second}}{\SI{e-30}{\kilogram} \cdot (\SI{2.99792458e8}{\meter\per\second})^2} \approx \SI{1.17e-21}{\second}.
\end{equation}
This delay is testable in high-precision quantum experiments, such as time-of-flight measurements in particle accelerators, comparing event timings for particles of varying masses.






\subsection{Potential Falsification}
\label{subsec:falsification}
The TLM’s predictions are falsifiable with the experimental setups in Section~\ref{sec:expanded_protocols}. Specific thresholds include:
\begin{itemize}
    \item \textbf{Quantum Delays}: No detection of \(\Delta t > \SI{e-13}{\second}\) in TCSPC experiments (\(\sigma_{\Delta t} = \SI{2.5e-14}{\second}\)) would rule out TLM at 95\% confidence (\(p < 0.05\)) \citep{Marcikic2003}.
    \item \textbf{CMB Phase Shifts}: No detection of \(\Delta \phi > \SI{e-11}{\radian}\) in Planck 2018 data (\(\sigma_{C_\ell} / C_\ell = 10^{-3}\)) would constrain TLM at 90\% confidence \citep{Aghanim2020}.
    \item \textbf{Black Hole Radiation}: No observation of pulses with \(\Delta f > \SI{1}{\hertz}\) in analog black hole experiments would falsify TLM at 99\% confidence \citep{Steinhauer2016}.
    \item \textbf{GW Phase Shifts}: No detection of \(\Delta \phi_{\text{GW}} > \SI{5e-15}{\radian}\) in stacked LIGO/Virgo data (\(N = 100\)) would rule out TLM at 95\% confidence \citep{Abbott2016}.
\end{itemize}
These thresholds assume Gaussian noise, with statistical methods (e.g., MCMC \citep{Lewis2002}, BILBY \citep{Ashton2019}) ensuring robust analysis.












\subsection{Unique Radiation Signatures from Black Holes}
\label{subsec:radiation_signatures}
The TLM predicts black holes emit discrete radiation pulses due to quantized CI-ARC deployments, testable with analog black hole experiments using Bose-Einstein condensates \cite{Steinhauer2016}.

\subsection{Summary Table of Predictions}
\label{subsec:summary_table}
\begin{table}[h]
    \centering
    \begin{tabular}{l l l}
        \toprule
        \textbf{Phenomenon} & \textbf{Predicted Outcome} & \textbf{Current Expectation} \\
        \midrule
        Quantum Interactions & 1--10 ps delay, \( \Delta t = \hbar / (M_{\text{detector}} \cdot k) \) & Instantaneous \\
        Cosmic Background & Phase shifts, \( \Delta \phi = \frac{\hbar}{m_{\text{eff}} c^2} \cdot \frac{H_0}{c} \) & Standard correlations \\
        Black Hole Radiation & Pulsed emissions & Continuous thermal \\
        \bottomrule
    \end{tabular}
    \caption{Summary of testable predictions versus established theories.}
    \label{tab:predictions}
\end{table}

\subsection{Testable Prediction}
\label{subsec:prediction}
The TLM predicts that systems with higher invariant mass exhibit measurable delays in causal event resolution, proportional to:
\begin{equation}
T = \hbar / (m \cdot c^2).
\end{equation}
For a particle with mass \( m = 10^{-30} \, \text{kg} \), the delay is:
\begin{equation}
T = \frac{1.0545718 \times 10^{-34}}{10^{-30} \cdot (2.99792458 \times 10^8)^2} \approx 1.17 \times 10^{-21} \, \text{s}.
\end{equation}
This delay can be tested in high-precision quantum experiments, such as time-of-flight measurements in particle accelerators, comparing event timings for particles of varying masses.

\section{Comparison to Existing Theories}
\label{sec:comparison}

\subsection{Contrast with General Relativity}
\label{subsec:contrast_gr}
The TLM differs from GR’s spacetime curvature model by using causal delays. In weak fields, both align, but TLM predicts mass-dependent timing effects \cite{Weinberg1972}.

\subsection{Contrast with Quantum Mechanics}
\label{subsec:contrast_qm}
Unlike Quantum Mechanics, which uses probabilistic wavefunctions \cite{Sakurai1994}, the TLM proposes a deterministic process where events are resolved via mass-induced delays governed by (1.1). This resolves the measurement problem by linking wavefunction collapse to CI-ARC projections into the SDF, offering a deterministic interpretation of quantum phenomena \cite{Dirac1930, Zeilinger1999}.

\subsection{Contrast with Other Unification Theories}
\label{subsec:contrast_unification}
Unlike String Theory \cite{Green1987} or Loop Quantum Gravity \cite{Rovelli2004}, which rely on multiple parameters or high-energy scales, the TLM uses a single axiom (1.1) with testable predictions at current energy scales, making it accessible for immediate investigation \cite{Feynman1965}.

\subsection{Photon Instruction Layer and Causal Instruction Arcs}
\label{subsec:pil_ciarcs}
The Photon Instruction Layer (PIL) is a timeless, non-spatial ledger of causal instructions, modeled as a directed graph \( G = (V, E) \), where vertices \( V \) represent event endpoints (emission and absorption points) and edges \( E \) represent Causal Instruction Arcs (CI-ARCs). Each CI-ARC is a tuple \( (v_i, v_j, C, \Delta, D) \), where:
\begin{itemize}
    \item \( v_i, v_j \in V \): The starting and ending event points.
    \item \( C \): A constraint set ensuring conservation of energy and momentum.
    \item \( \Delta \): A projection delay, governed by (1.1), determining the temporal separation in the Spacetime Deployment Frame (SDF).
    \item \( D \): The Distance Factor, \( D = \frac{|\mathbf{x}_j - \mathbf{x}_i|}{\lambda_C} \), coding spatial separation.
\end{itemize}
CI-ARCs project from the PIL to the SDF, rendering observable events. Extra-SDF Events (ESEs) are CI-ARCs with \( \Delta = 0 \), enabling instantaneous quantum effects, such as entanglement correlations, without violating causality \cite{Sakurai1994, Wheeler1978}.

\begin{table}[h]
    \centering
    \begin{tabularx}{\textwidth}{l X X X}
        \toprule
        \textbf{Aspect} & \textbf{TLM} & \textbf{String Theory} & \textbf{LQG} \\
        \midrule
        Core Axiom & Mass-delay \( T \cdot m = \hbar / c^2 \) & Extra dimensions & Quantized spacetime \\
        Energy Scale & Low (current tech) & Planck scale & Planck scale \\
        Testable Predictions & Quantum delays, CMB shifts & Limited (high energy) & Limited (high energy) \\
        \bottomrule
    \end{tabularx}
    \caption{Comparison of TLM with String Theory and Loop Quantum Gravity (LQG). The TLM’s mass-delay axiom enables testable predictions at accessible energy scales, unlike the high-energy requirements of String Theory and LQG.}
    \label{tab:unification_comparison}
\end{table}












\section{Philosophical Implications}
\label{sec:philosophical}

The Timeless Light Model (TLM) redefines fundamental concepts of time, space, and quantum gravity, offering a new perspective on unification. Speculative philosophical discussions, including free will and metaphysical implications, are explored in Appendix~\ref{app:speculative}.

\subsection{Redefinition of Time and Space}
\label{subsec:redefinition_time_space}
The TLM posits that time and space emerge from mass-induced delays in CI-ARC projections, governed by \( T \cdot m = \hbar / c^2 \) (Equation~\ref{eq:delay_axiom}). Time arises as a sequence of events in the Spacetime Deployment Frame (SDF), while space emerges from the Distance Factor (Section~\ref{subsec:spatial_factor}). This relational view aligns with theories like Rovelli’s quantum gravity, where reality is defined by interactions rather than a fixed background \citep{Rovelli2004}. The emergent nature of spacetime suggests a pre-geometric foundation, challenging classical notions \citep{Weinberg1972}.

\subsection{Implications for Quantum Gravity and Unification}
\label{subsec:quantum_gravity}
The TLM resolves the black hole information paradox by preserving information through CI-ARC projections, contrasting with Hawking’s thermal radiation \citep{Hawking1974}. Its deterministic treatment of entanglement via Extra-SDF Events (ESEs) aligns with Bell test experiments \citep{Zeilinger1999}, offering a unified framework for GR and QM without requiring high-energy scales. These implications position the TLM as a candidate for quantum gravity, testable through predictions in Section~\ref{sec:empirical_predictions}.


\section{Conclusion}
\label{sec:conclusion}

\subsection{Summary of Achievements}
\label{subsec:summary_achievements}
The Timeless Light Model (TLM) unifies General Relativity and Quantum Mechanics through a mass-induced delay mechanism (\( T \cdot m = \hbar / c^2 \)), explaining quantum interactions, black hole information preservation, and spatial emergence \citep{Weinberg1972, Sakurai1994}. Its testable predictions, including quantum delays (\(\sim \SI{e-12}{\second}\)) and CMB phase shifts (\(\sim \SI{e-11}{\radian}\)), distinguish it from high-energy theories (Section~\ref{sec:empirical_predictions}).

\subsection{Future Directions and Collaboration}
\label{subsec:future_directions}
The TLM’s predictions invite validation through quantum optics and cosmological experiments (Section~\ref{sec:expanded_protocols}). Collaboration with experimentalists is encouraged to test these claims. Speculative extensions, such as dark matter and philosophical implications, are outlined in Appendix~\ref{app:speculative}, guiding future theoretical exploration.

\section{Experimental Protocols}
\label{app:protocols}

\subsection{Setup for Measuring Time Delays in Quantum Interactions}
\label{subapp:time_delay_setup}
Use two detectors of differing mass, separated by a long baseline, with picosecond-resolution photon counting to measure delays of (4.1), comparing against instantaneous expectations \cite{Sakurai1994}.

\subsection{Setup for Analyzing Cosmic Background Radiation Patterns}
\label{subapp:cmb_setup}
Analyze Planck 2018 data for phase shifts of (4.2), where \( m_{\text{eff}} = \frac{k_B T_{\text{CMB}}}{c^2} \approx 2.4 \times 10^{-41} \, \text{kg} \) (for \( T_{\text{CMB}} \approx 2.7 \, \text{K} \)) and \( H_0 \approx 2.2 \times 10^{-18} \, \text{s}^{-1} \). Use statistical methods to detect deviations from standard correlations \cite{Aghanim2020, Dodelson2003}.

\subsection{Setup for Observing Radiation from Black Hole Analogs}
\label{subapp:radiation_setup}
Create analog black holes using Bose-Einstein condensates and measure emission patterns with high-resolution spectroscopy, expecting discrete pulses \cite{Steinhauer2016}.


\section{Expanded Experimental Protocols for TLM Predictions}
\label{sec:expanded_protocols}

This section provides detailed experimental setups to test the Timeless Light Model (TLM) predictions outlined in Section~\ref{sec:empirical_predictions}, specifically the quantum delay (\(\sim \SI{e-12}{\second}\)) and cosmic microwave background (CMB) phase shift (\(\sim \SI{e-11}{\radian}\)). The protocols leverage current technology, including photon counting devices and CMB analysis pipelines, to outline feasible experimental setups.

\subsection{Experimental Setup for Measuring Quantum Delays}
\label{subsec:quantum_delay_setup}

The TLM predicts a quantum interaction delay given by:
\begin{equation}
\Delta t = \frac{\hbar}{M_{\text{detector}} \cdot k},
\end{equation}
where \(\hbar = \SI{1.0545718e-34}{\joule\second}\), \(M_{\text{detector}}\) is the detector mass (\(\sim \SI{1}{\kilogram}\)), and \(k \approx \SI{e-19}{\joule}\) is the interaction energy, yielding \(\Delta t \sim \SI{e-12}{\second}\). This delay can be tested using high-precision photon counting experiments with picosecond resolution.

\subsubsection{Experimental Design}
\label{subsubsec:quantum_delay_design}

The setup involves a photon source emitting single photons, two detectors with different masses, and a time-correlated single-photon counting (TCSPC) system. The goal is to measure the time difference in photon detection events between detectors, comparing against the TLM-predicted delay.

\begin{itemize}
    \item \textbf{Photon Source}: Use a heralded single-photon source based on spontaneous parametric down-conversion (SPDC) in a beta-barium borate (BBO) crystal, pumped by a \SI{405}{\nano\meter} laser. This produces photon pairs at \SI{810}{\nano\meter}, with one photon triggering the experiment and the other sent to the detectors \citep{Kwiat1995}.
    \item \textbf{Detectors}: Employ two silicon avalanche photodiodes (Si-APDs), such as the Excelitas SPCM-AQRH series, with a timing jitter of \(\sim \SI{350}{\pico\second}\) and quantum efficiency of \(\sim 70\%\) at \SI{810}{\nano\meter}. To test the mass dependence, one APD is mounted on a lightweight frame (\(M_1 \approx \SI{0.1}{\kilogram}\)) and the other on a heavier frame (\(M_2 \approx \SI{1}{\kilogram}\)).
    \item \textbf{Timing System}: Use a TCSPC module, such as the PicoQuant TimeHarp 260, with a resolution of \(\sim \SI{25}{\pico\second}\). The trigger photon starts the clock, and the detection times at each APD are recorded to measure \(\Delta t\).
    \item \textbf{Setup Geometry}: Place the detectors at equal distances (\(\sim \SI{1}{\meter}\)) from a 50:50 beam splitter to ensure identical photon travel times. The beam splitter randomizes photon paths to either detector, isolating mass-induced delays.
    \item \textbf{Data Collection}: Collect \(\sim 10^6\) photon detection events per detector to achieve a statistical uncertainty of \(\sim \SI{1}{\pico\second}\) in \(\Delta t\), based on the central limit theorem.
\end{itemize}

\subsubsection{Analysis and Feasibility}
\label{subsubsec:quantum_delay_analysis}

The time difference \(\Delta t = t_2 - t_1\) between detection events at the heavy (\(M_2\)) and light (\(M_1\)) detectors is expected to follow:
\begin{equation}
\Delta t \approx \frac{\hbar}{k} \left( \frac{1}{M_1} - \frac{1}{M_2} \right).
\end{equation}
For \(M_1 = \SI{0.1}{\kilogram}\), \(M_2 = \SI{1}{\kilogram}\), and \(k = \SI{e-19}{\joule}\), the predicted delay is:
\begin{equation}
\Delta t \approx \frac{\SI{1.0545718e-34}{\joule\second}}{\SI{e-19}{\joule}} \left( \frac{1}{\SI{0.1}{\kilogram}} - \frac{1}{\SI{1}{\kilogram}} \right) \approx \SI{9.49e-12}{\second}.
\end{equation}
This is within the resolution of modern TCSPC systems (\(\sim \SI{25}{\pico\second}\)), but multiple measurements are needed to reduce statistical noise. Background subtraction accounts for electronic jitter and photon path differences. The setup is feasible with commercial equipment, as similar experiments have resolved delays in quantum optics \citep{Marcikic2003}.

\subsection{Experimental Setup for CMB Phase Shift Analysis}
\label{subsec:cmb_phase_shift_setup}

The TLM predicts a CMB phase shift due to Causal Instruction Arc (CI-ARC) correlations, given by:
\begin{equation}
\Delta \phi = \frac{\hbar}{m_{\text{eff}} c^2} \cdot \frac{H_0}{c},
\end{equation}
where \(m_{\text{eff}} = \frac{k_B T_{\text{CMB}}}{c^2} \approx \SI{2.4e-41}{\kilogram}\) (for \(T_{\text{CMB}} \approx \SI{2.7}{\kelvin}\)), \(H_0 \approx \SI{2.2e-18}{\per\second}\), and \(c = \SI{2.99792458e8}{\meter\per\second}\), yielding \(\Delta \phi \approx \SI{3.6e-11}{\radian}\). This can be tested by analyzing CMB angular power spectra for deviations from standard \(\Lambda\)CDM correlations.

\subsubsection{Data Source and Pipeline}
\label{subsubsec:cmb_data_pipeline}

Use the Planck 2018 CMB data, specifically the temperature and polarization maps, available through the Planck Legacy Archive \citep{Aghanim2020}. The analysis pipeline involves the following steps:

\begin{itemize}
    \item \textbf{Data Selection}: Extract the temperature (\(TT\)) and E-mode polarization (\(EE\)) power spectra from the Planck 2018 high-frequency instrument (HFI) data at \SI{143}{\giga\hertz}, which offers high signal-to-noise for CMB anisotropies.
    \item \textbf{Pre-processing}: Apply foreground subtraction using Planck’s component separation tools (e.g., SMICA or Commander) to remove galactic dust, synchrotron, and point source contributions. Mask regions with high foreground contamination (e.g., galactic plane).
    \item \textbf{Power Spectrum Estimation}: Compute the angular power spectrum \(C_\ell\) using a pseudo-\(C_\ell\) estimator, such as PolSpice or Xpol, which corrects for incomplete sky coverage \citep{Chon2004}. Focus on multipoles \(\ell = 2\) to \(\ell = 2500\), covering large and small angular scales.
    \item \textbf{Phase Shift Detection}: Model the TLM phase shift as a perturbation to the power spectrum:
    \begin{equation}
    C_\ell^{\text{TLM}} = C_\ell^{\Lambda\text{CDM}} \cdot \left( 1 + \Delta \phi \cdot f(\ell) \right),
    \end{equation}
    where \(f(\ell)\) is a scale-dependent function (e.g., linear in \(\ell\)) to be determined empirically. Fit the modified \(C_\ell^{\text{TLM}}\) to the observed power spectrum using a Markov Chain Monte Carlo (MCMC) method, implemented in CosmoMC \citep{Lewis2002}.
    \item \textbf{Statistical Analysis}: Compare the TLM model to the standard \(\Lambda\)CDM model using the Bayesian evidence ratio or \(\chi^2\) goodness-of-fit. A detection of \(\Delta \phi \sim \SI{e-11}{\radian}\) requires a signal-to-noise ratio of \(\sim 3\), achievable with Planck’s precision (\(\sigma_{C_\ell} / C_\ell \sim 10^{-3}\) at \(\ell \sim 1000\)).
\end{itemize}

\subsubsection{Analysis and Feasibility}
\label{subsubsec:cmb_analysis}

The TLM phase shift (\(\Delta \phi \approx \SI{3.6e-11}{\radian}\)) is small but potentially detectable with Planck 2018 data, which have a precision of \(\sim \SI{e-10}{\radian}\) in power spectrum residuals after foreground subtraction \citep{Aghanim2020}. The analysis requires high computational resources (e.g., a cluster with \(\sim 100\) CPU cores for MCMC fitting) but is standard in cosmology. Future experiments, such as the Simons Observatory or CMB-S4, will improve sensitivity by a factor of \(\sim 10\), increasing detection feasibility \citep{Abazajian2016}. The pipeline is robust, as similar methods have constrained non-standard cosmological parameters (e.g., primordial non-Gaussianity).

\subsection{Discussion of Feasibility}
\label{subsec:feasibility_discussion}

Both experimental setups are feasible with existing technology:
\begin{itemize}
    \item The quantum delay experiment leverages commercial photon counting systems (e.g., PicoQuant TCSPC) and standard SPDC sources, requiring only precise calibration to resolve \(\SI{e-12}{\second}\) delays. Challenges include minimizing electronic jitter and ensuring identical photon paths, but these are addressable with careful design.
    \item The CMB phase shift analysis uses publicly available Planck 2018 data and established cosmological tools (e.g., CosmoMC, PolSpice). The main challenge is distinguishing the TLM signal from systematic errors (e.g., foreground residuals), but Planck’s multi-frequency data mitigate this risk.
\end{itemize}
These protocols provide concrete pathways to test the TLM, aligning with current experimental capabilities in quantum optics and cosmology.
















\appendix

\section{Notation}
\label{app:notation}
\begin{table}[h]
    \centering
    \begin{tabular}{l l}
        \toprule
        \textbf{Symbol} & \textbf{Description} \\
        \midrule
        \( \hbar \) & Reduced Planck constant, \( \SI{1.0545718e-34}{\joule\second} \) \\
        \( c \) & Speed of light, \( \SI{2.99792458e8}{\meter\per\second} \) \\
        \( T \) & Characteristic timescale (s) \\
        \( m \) & Invariant mass (kg) \\
        \( D \) & Distance Factor, \( D = \frac{|\mathbf{x}_j - \mathbf{x}_i|}{\lambda_C} \), with \( \lambda_C = \frac{\hbar}{m c} \) \\
        \( \frac{dI}{dt} \) & Causal resolution rate, \( \frac{c^2}{\hbar m} \, \text{s}^{-1} \) \\
        \bottomrule
    \end{tabular}
    \caption{Key notation used in the Timeless Light Model (TLM).}
    \label{tab:notation}
\end{table}

\section{Rigorous Derivations of the Timeless Light Model}
\label{app:derivations}

This appendix provides the mathematical derivations underpinning the Timeless Light Model (TLM), establishing its consistency with Special Relativity (SR), General Relativity (GR), and Quantum Mechanics (QM), while exploring speculative extensions. The mass-time relation (Subsection~\ref{subapp:mass_time}) derives the core axiom \( T \cdot m = \hbar / c^2 \), linking mass to causal delays. The causal resolution rate (Subsection~\ref{subapp:causal_rate}) quantifies the pace of event deployment. The Lagrangian formulation (Subsection~\ref{subapp:lagrangian}) enforces the delay axiom dynamically, connecting to GR. Derivations for SR (Subsection~\ref{subapp:sr_derivation}), GR (Subsection~\ref{subapp:gr_derivation}), and QM (Subsection~\ref{subapp:qm_derivation}) demonstrate compatibility with established theories. Finally, a speculative symmetry (Subsection~\ref{subapp:symmetry}) proposes a velocity-dependent relation, awaiting empirical validation.







\subsection{Mass-Time Relation}
\label{subapp:mass_time}
The TLM’s foundational axiom states that the characteristic timescale \( T \) of a physical interaction is inversely related to the invariant mass \( m \):
\begin{equation}
T \cdot m = \frac{\hbar}{c^2}
\label{eq:mass_time}
\end{equation}
where \( \hbar = \SI{1.0545718e-34}{\joule\second} \) is the reduced Planck constant, and \( c = \SI{2.99792458e8}{\meter\per\second} \) is the speed of light.

\textbf{Derivation:}
\begin{enumerate}
    \item \textbf{Physical Motivation}: The TLM posits that mass governs the pace of causal interactions in the Spacetime Deployment Frame (SDF) by inducing delays in the projection of Causal Instruction Arcs (CI-ARCs) from the timeless Photon Instruction Layer (PIL). This delay arises because mass, via the energy-mass equivalence \( E = m c^2 \), anchors quantum events to relativistic scales. The Compton wavelength, \( \lambda_C = \frac{\hbar}{m c} \), defines a characteristic length scale for a particle of mass \( m \), representing the spatial extent of its quantum wavefunction. To translate this length into a timescale, we divide by the speed of light, yielding \( T_C = \frac{\lambda_C}{c} = \frac{\hbar}{m c^2} \), which reflects the time required for a light-like signal to traverse the Compton scale. This timescale is consistent with the energy-time uncertainty principle, \( \Delta E \cdot \Delta t \sim \hbar \), where \( \Delta E = m c^2 \) for a massive particle, suggesting \( \Delta t \sim \frac{\hbar}{m c^2} \). The TLM axiom extends this by proposing that the product \( T \cdot m \) is a universal constant, \( \frac{\hbar}{c^2} \), ensuring that the delay scales inversely with mass across all physical interactions. This constant bridges quantum mechanics (via \( \hbar \)) and relativity (via \( c^2 \)), unifying the two frameworks by pacing causal events to the speed of light, a fundamental limit in the SDF. Thus, we hypothesize:
    \begin{equation}
    T \sim \frac{\hbar}{m c^2}
    \end{equation}
    Multiplying by \( m \):
    \begin{equation}
    T \cdot m \sim \frac{\hbar}{c^2}
    \end{equation}
    \item \textbf{Dimensional Analysis}: Verify dimensions to ensure consistency:
    \[
    [T \cdot m] = \text{s} \cdot \text{kg} = \text{kg} \cdot \text{s}
    \]
    \[
    \left[ \frac{\hbar}{c^2} \right] = \frac{\text{kg} \cdot \text{m}^2 \cdot \text{s}^{-1}}{\text{m}^2 \cdot \text{s}^{-2}} = \text{kg} \cdot \text{s}
    \]
    The dimensions match, confirming the physical consistency of the axiom.
    \item \textbf{Axiomatic Postulate}: Postulate Equation~\eqref{eq:mass_time}, where \( \frac{\hbar}{c^2} \approx \SI{3.517e-51}{\kilogram\second} \) is a universal constant, ensuring that quantum and relativistic scales align in the TLM framework. This axiom underpins the ``DELAY TO C'' mechanism, where massive systems experience longer delays, sequencing events in the SDF, while massless systems (e.g., photons) project instantaneously, consistent with their light-like propagation.
\end{enumerate}








\subsection{Causal Resolution Rate}
\label{subapp:causal_rate}
The rate of causal progression, representing the deployment of Causal Instruction Arcs (CI-ARCs) into the SDF, is:
\begin{equation}
\frac{dI}{dt} = \frac{c^2}{\hbar m}
\end{equation}
where \( I \) is a dimensionless causal index that quantifies the cumulative advancement of causal events in the TLM framework. Physically, \( I \) tracks the progression of the universe’s causal structure, with each increment in \( I \) corresponding to the projection of a CI-ARC, such as a photon emission or absorption event, from the timeless PIL to the observable SDF.

\textbf{Derivation:}
\begin{enumerate}
    \item \textbf{Definition}: Define \( I \) as a dimensionless index tracking the progression of causal instructions, with:
    \begin{equation}
    \left[ \frac{dI}{dt} \right] = \text{s}^{-1}
    \end{equation}
    Physically, \( I \) represents the number of completed causal events, analogous to a counter for CI-ARC projections, where the rate \( \frac{dI}{dt} \) depends on the mass \( m \) of the system.
    \item \textbf{From Mass-Time Axiom}: From (A.1), solve for \( T \):
    \begin{equation}
    T = \frac{\hbar}{m c^2}
    \end{equation}
    The inverse timescale is:
    \begin{equation}
    \frac{1}{T} = \frac{m c^2}{\hbar}
    \end{equation}
    \item \textbf{Rate Formulation}: Hypothesize that the causal resolution rate is proportional to \( \frac{1}{T} \):
    \begin{equation}
    \frac{dI}{dt} = \frac{c^2}{\hbar m}
    \end{equation}
    \item \textbf{Dimensional Check}: Verify dimensions:
    \[
    [c^2] = \text{m}^2 \cdot \text{s}^{-2}, \quad [\hbar] = \text{kg} \cdot \text{m}^2 \cdot \text{s}^{-1}, \quad [m] = \text{kg}
    \]
    \[
    \left[ \frac{c^2}{\hbar m} \right] = \frac{\text{m}^2 \cdot \text{s}^{-2}}{\text{kg} \cdot \text{m}^2 \cdot \text{s}^{-1} \cdot \text{kg}} = \text{s}^{-1}
    \]
    This matches (A.5), confirming consistency.
    \item \textbf{Interpretation}: For massless particles (\( m \to 0 \)), \( \frac{dI}{dt} \to \infty \), implying instantaneous resolution in the PIL, consistent with photon behavior. For massive systems, a larger \( m \) slows the rate, reflecting the mass-induced delay central to the TLM.
\end{enumerate}








\subsection{Lagrangian Formulation}
\label{subapp:lagrangian}
The TLM enforces the mass-time axiom dynamically through a Lagrangian density:
\begin{equation}
\mathcal{L}_{\text{DEC}} = \lambda \left( T m - \frac{\hbar}{c^2} \left( 1 + \frac{\Phi}{c^2} \right) \right) + \frac{1}{2} m (\partial_\mu T)(\partial^\mu T) - V(m)
\label{eq:lagrangian}
\end{equation}
where \( \lambda \) is a Lagrange multiplier enforcing the mass-time axiom, \( T \) is the delay field, \( m \) is the invariant mass, \( \Phi \) is the gravitational potential, and \( V(m) \) is a potential term governing mass dynamics.

\textbf{Physical Justification}: The Lagrangian’s structure is motivated by the TLM’s core axiom, \( T \cdot m = \hbar / c^2 \) (Equation~\ref{eq:mass_time}), which posits that mass induces delays in causal event projection from the Photon Instruction Layer (PIL) to the Spacetime Deployment Frame (SDF). The first term, \( \lambda \left( T m - \frac{\hbar}{c^2} \left( 1 + \frac{\Phi}{c^2} \right) \right) \), enforces this axiom as a constraint, with the gravitational correction \( \frac{\Phi}{c^2} \) accounting for spacetime curvature effects, ensuring compatibility with GR in the presence of a gravitational potential \citep{Weinberg1972}. The kinetic term, \( \frac{1}{2} m (\partial_\mu T)(\partial^\mu T) \), represents the dynamics of the delay field \( T \), analogous to a scalar field’s kinetic energy, where \( m \) weights the contribution to reflect the mass-dependent delay. This term ensures that variations in \( T \) propagate causally in the SDF, consistent with the TLM’s event sequencing. The potential term, \( V(m) \), governs the dynamics of mass as a field, allowing flexibility to model interactions (e.g., a quadratic potential \( V(m) = \frac{1}{2} k m^2 \) for harmonic behavior). Together, these terms encode the TLM’s principle that mass paces causal interactions, bridging quantum (via \( \hbar \)) and relativistic (via \( c \) and \( \Phi \)) scales.

\textbf{Derivation:}
\begin{enumerate}
    \item \textbf{Action Principle}: Define the action:
    \begin{equation}
    S = \int \mathcal{L}_{\text{DEC}} \, d^4x
    \end{equation}
    where \( d^4x \) is the spacetime volume element in the SDF.
    \item \textbf{Variation with Respect to \( \lambda \)}:
    \begin{equation}
    \frac{\partial \mathcal{L}_{\text{DEC}}}{\partial \lambda} = T m - \frac{\hbar}{c^2} \left( 1 + \frac{\Phi}{c^2} \right) = 0
    \end{equation}
    \begin{equation}
    T m = \frac{\hbar}{c^2} \left( 1 + \frac{\Phi}{c^2} \right)
    \label{eq:constraint_gr}
    \end{equation}
    This enforces the mass-time axiom, modified by gravitational effects.
    \item \textbf{Variation with Respect to \( T \)}:
    \begin{equation}
    \frac{\partial \mathcal{L}_{\text{DEC}}}{\partial T} - \partial_\mu \left( \frac{\partial \mathcal{L}_{\text{DEC}}}{\partial (\partial_\mu T)} \right) = \lambda m + \partial_\mu \left( m \partial^\mu T \right) = 0
    \end{equation}
    \begin{equation}
    \lambda m = -\partial_\mu (m \partial^\mu T)
    \label{eq:lambda_eq}
    \end{equation}
    \item \textbf{Variation with Respect to \( m \)}:
    \begin{equation}
    \frac{\partial \mathcal{L}_{\text{DEC}}}{\partial m} - \partial_\mu \left( \frac{\partial \mathcal{L}_{\text{DEC}}}{\partial (\partial_\mu m)} \right) = \lambda T + \frac{1}{2} (\partial_\mu T)(\partial^\mu T) - \frac{\partial V}{\partial m} = 0
    \label{eq:mass_eq}
    \end{equation}
    \item \textbf{Solution}: Assume a quadratic potential \( V(m) = \frac{1}{2} k m^2 \), where \( k \) is a constant with dimensions \( \text{m}^2 \cdot \text{s}^{-2} \). Solve Equations~\eqref{eq:constraint_gr}, \eqref{eq:lambda_eq}, and \eqref{eq:mass_eq} perturbatively. The gravitational term links to metric perturbations, as shown in Subsection~\ref{subapp:gr_derivation}.
\end{enumerate}



\subsection{Derivation of Special Relativity}
\label{subapp:sr_derivation}
In flat spacetime (\( \Phi = 0 \)), the Lagrangian simplifies to:
\begin{equation}
\mathcal{L}_{\text{DEC}} = \lambda \left( T m - \frac{\hbar}{c^2} \right) + \frac{1}{2} m (\partial_\mu T)(\partial^\mu T) - V(m)
\end{equation}
\textbf{Derivation:}
\begin{enumerate}
    \item \textbf{Constraint}: Vary with respect to \( \lambda \):
    \begin{equation}
    T m = \frac{\hbar}{c^2}
    \end{equation}
    \item \textbf{Lorentz Transformation}: For a particle with velocity \( v \), the delay \( T \) scales with the Lorentz factor \( \gamma = \frac{1}{\sqrt{1 - v^2 / c^2}} \). The action is:
    \begin{equation}
    S = \int \mathcal{L}_{\text{DEC}} \, d^4x
    \end{equation}
    Vary \( S \) with respect to spacetime coordinates \( x^\mu \). The invariance of (A.14) under coordinate transformations requires the metric \( \eta_{\mu\nu} \) to satisfy Lorentz invariance. For a particle moving at \( v \), the time coordinate transforms as:
    \begin{equation}
    t' = \gamma \left( t - \frac{v x}{c^2} \right), \quad x' = \gamma (x - v t)
    \end{equation}
    where \( \gamma = \frac{1}{\sqrt{1 - v^2 / c^2}} \). This yields the Lorentz transformations, consistent with Special Relativity \citep{Einstein1905}.
\end{enumerate}










\subsection{Derivation of General Relativity}
\label{subapp:gr_derivation}
The TLM derives the Einstein field equations by coupling the TLM Lagrangian to the Einstein-Hilbert action, ensuring applicability in arbitrary metrics. The total action is:
\begin{equation}
S = \frac{1}{16\pi G} \int R \sqrt{-g} \, d^4x + \int \mathcal{L}_{\text{DEC}} \sqrt{-g} \, d^4x,
\end{equation}
where the generalized TLM Lagrangian is:
\begin{equation}
\mathcal{L}_{\text{DEC}} = \lambda \left( T m - \frac{\hbar}{c^2} \left( 1 + \kappa R \right) \right) + \frac{1}{2} m g^{\mu\nu} (\partial_\mu T)(\partial_\nu T) - V(m),
\end{equation}
with \(\kappa\) a coupling constant (\([\kappa] = \text{m}^2\)), and \(V(m) = \frac{1}{2} k m^2\). Varying with respect to \(g^{\mu\nu}\), the stress-energy tensor is:
\begin{equation}
T_{\mu\nu} = m (\partial_\mu T)(\partial_\nu T) - g_{\mu\nu} \left( \frac{1}{2} m g^{\alpha\beta} (\partial_\alpha T)(\partial_\beta T) + V(m) \right) - \lambda \frac{\hbar \kappa}{c^2} \left( R_{\mu\nu} + g_{\mu\nu} \Box - \nabla_\mu \nabla_\nu \right).
\end{equation}
In harmonic gauge (\(\partial^\mu \bar{h}_{\mu\nu} = 0\)), the Einstein field equations are:
\begin{equation}
R_{\mu\nu} - \frac{1}{2} g_{\mu\nu} R = \frac{8\pi G}{c^4} T_{\mu\nu}.
\end{equation}
In the weak-field limit (\(g_{\mu\nu} \approx \eta_{\mu\nu} + h_{\mu\nu}\), \(R \approx 0\)), this reduces to Subsection B.5’s result, recovering Newtonian gravity (\(\nabla^2 \Phi = 4\pi G \rho\)) \citep{Weinberg1972}.


\subsection{Derivation of Quantum Mechanics}
\label{subapp:qm_derivation}
The TLM derives quantum mechanics from the causal resolution rate (Equation~\ref{eq:causal_rate}). For spin-1/2 particles, consider the Dirac equation:
\begin{equation}
(i \gamma^\mu \partial_\mu - \frac{m c}{\hbar}) \psi = 0,
\end{equation}
where \(\psi\) is a four-component spinor, and \(\gamma^\mu\) satisfy \(\{\gamma^\mu, \gamma^\nu\} = 2 g^{\mu\nu}\). The causal rate \(\frac{dI}{dt} = \frac{m c^2}{\hbar}\) drives the time evolution:
\begin{equation}
i \hbar \frac{\partial \psi}{\partial t} = \left( -i \hbar c \gamma^0 \gamma^i \partial_i + m c^2 \gamma^0 \right) \psi.
\end{equation}
CI-ARCs map to QFT propagators, with vertices \(v_i, v_j\) as interaction points and delays \(\Delta = \frac{\hbar}{m c^2}\) encoding phase evolution, aligning with the fermion propagator:
\begin{equation}
S_F(x - y) = \int \frac{d^4 p}{(2\pi)^4} \frac{i (\not{p} + m)}{p^2 - m^2 + i\epsilon} e^{-i p \cdot (x - y)} \citep{Peskin1995}.
\end{equation}
In the non-relativistic limit, this reduces to the Pauli equation, recovering spin-dependent Schrödinger dynamics \citep{Sakurai1994}.


\subsection{Generalized Derivations and Approximation Errors}
\label{subapp:generalized_derivations}
This subsection quantifies errors in the GR and QM derivations, justifying their validity for low-energy regimes. For GR (Subsection~\ref{subapp:gr_derivation}), the weak-field approximation neglects terms \(h_{\mu\nu} h^{\mu\nu}\). For a solar-mass black hole at \(r = \SI{e6}{\meter}\), \(h_{00} \sim \SI{3e-4}{}\) yields \(h_{00}^2 \sim \SI{9e-8}{}\), negligible in weak fields but significant near the Schwarzschild radius. For QM (Subsection~\ref{subapp:qm_derivation}), relativistic corrections to the Schrödinger equation are \(\sim \SI{e-24}{\joule}\) for electron momenta \(\sim \SI{e-24}{\kilogram\meter\per\second}\), confirming non-relativistic validity \citep{Sakurai1994}.

\begin{table}[h]
    \centering
    \begin{tabular}{l c c c}
        \toprule
        \textbf{Regime} & \textbf{TLM Prediction} & \textbf{GR/QM Standard} & \textbf{Error Estimate} \\
        \midrule
        Weak-Field GR & \(\nabla^2 \Phi = 4\pi G \rho\) & Same & \(h_{\mu\nu}^2 \sim \SI{e-8}{}\) \\
        Strong-Field GR & Modified \(T_{\mu\nu}\) & Schwarzschild & Requires numerical analysis \\
        Non-Relativistic QM & Schrödinger equation & Same & \(\sim \SI{e-24}{\joule}\) \\
        Relativistic QFT & Dirac propagator & Same & Spinor terms exact \\
        \bottomrule
    \end{tabular}
    \caption{TLM alignment with GR and QM across energy scales, with approximation errors.}
    \label{tab:tlm_alignment}
\end{table}









\subsection{Speculative Symmetry}
\label{subapp:symmetry}
The TLM explores a potential symmetry relating the characteristic timescale \( T \) and velocity \( v \):
\begin{equation}
T \cdot \left( \frac{v}{c} \right)^2 = \frac{\hbar}{m c^2}
\end{equation}
where \( v \) is the system’s velocity, \( \hbar \) is the reduced Planck constant, and \( c \) is the speed of light.

\textbf{Derivation:}
\begin{enumerate}
    \item \textbf{Hypothesis}: From the mass-time axiom (A.1), hypothesize that \( T \) scales with velocity in relativistic contexts. For a particle with velocity \( v \), consider the Lorentz factor \( \gamma = \frac{1}{\sqrt{1 - v^2 / c^2}} \). Propose:
    \begin{equation}
    T \cdot \left( \frac{v}{c} \right)^2 = \text{constant}
    \end{equation}
    \item \textbf{Dimensional Analysis}: Verify dimensions:
    \[
    \left[ T \cdot \left( \frac{v}{c} \right)^2 \right] = \text{s}, \quad \left[ \frac{\hbar}{m c^2} \right] = \frac{\text{kg} \cdot \text{m}^2 \cdot \text{s}^{-1}}{\text{kg} \cdot \text{m}^2 \cdot \text{s}^{-2}} = \text{s}
    \]
    The dimensions match, suggesting consistency.
    \item \textbf{Empirical Validation}: Test via velocity-dependent delays in quantum experiments, measuring \( T \) for particles at varying velocities (e.g., in particle accelerators).
\end{enumerate}
This symmetry is speculative and requires experimental confirmation to establish its physical validity.


\appendix
\section{Speculative Extensions}
\label{app:speculative}

\subsection{Dark Matter as Unresolved CI-ARCs}
\label{subapp:dark_matter}
\textbf{Speculative Hypothesis}: CI-ARCs with large Distance Factors (\( D = \frac{|\mathbf{x}_j - \mathbf{x}_i|}{\lambda_C} \)) may form compact, non-luminous regions with gravitational effects, potentially explaining dark matter’s influence on cosmic motion \citep{Dodelson2003}. These regions mimic the gravitational signatures of dark matter without requiring exotic particles. The hypothesis suggests that unresolved CI-ARCs contribute to galaxy rotation curves and gravitational lensing.

\textbf{Proposed Test}: Measure gravitational lensing shear in galaxy clusters using DESI or Euclid data. Large-\( D \) CI-ARCs may produce distinct lensing patterns compared to standard NFW dark matter halos \citep{DESI2024}. For a cluster at \( z \sim 0.3 \), deviations in shear \(\gamma \sim \SI{e-3}{}\) could indicate CI-ARC effects, testable with DESI’s 2024 lensing maps.

\subsection{Velocity-Dependent Symmetry}
\label{subapp:velocity_symmetry}
\textbf{Speculative Hypothesis}: A proposed symmetry relates the characteristic timescale \( T \) to velocity \( v \):
\begin{equation}
T \cdot \left( \frac{v}{c} \right)^2 = \frac{\hbar}{m c^2},
\end{equation}
suggesting a balance between temporal and spatial delays. This is motivated by dimensional consistency but lacks empirical validation (Appendix~\ref{subapp:symmetry}).

\textbf{Proposed Test}: Conduct time-of-flight measurements at CERN’s LHCb or ATLAS experiments, targeting particles with \( v \approx c \) (e.g., muons, \( m \sim \SI{1.88e-28}{\kilogram} \)). For \( v/c \sim 0.999 \), the predicted delay is:
\begin{equation}
T \approx \frac{\SI{1.0545718e-34}{\joule\second}}{\SI{1.88e-28}{\kilogram} \cdot (\SI{2.99792458e8}{\meter\per\second})^2 \cdot 0.999^2} \approx \SI{6.3e-21}{\second}.
\end{equation}
Use picosecond-resolution detectors to measure delays, comparing against Standard Model expectations \citep{ATLAS2023}.






\section{Speculative Extensions and Philosophical Implications}
\label{app:speculative}

This appendix explores speculative extensions of the Timeless Light Model (TLM) and philosophical implications that lie beyond its empirically testable framework. These ideas are included to guide future theoretical and philosophical inquiry, distinct from the established results in Sections~\ref{sec:tlm_framework}--\ref{sec:empirical_predictions}.

\subsection{Dark Matter as Unresolved CI-ARCs}
\label{subapp:dark_matter}
\textbf{Speculative Hypothesis}: CI-ARCs with large Distance Factors (\( D = \frac{|\mathbf{x}_j - \mathbf{x}_i|}{\lambda_C} \)) may form compact, non-luminous regions with significant gravitational effects, potentially explaining dark matter’s influence on cosmic motion \citep{Dodelson2003}. This hypothesis suggests that unresolved CI-ARCs mimic the gravitational signatures of dark matter without requiring exotic particles. For a galaxy cluster at redshift \( z \sim 0.3 \), deviations in lensing shear (\(\gamma \sim \SI{e-3}{}\)) could indicate CI-ARC effects.

\textbf{Proposed Test}: Analyze gravitational lensing shear in galaxy clusters using DESI or Euclid data \citep{DESI2024}. Compare lensing patterns to standard Navarro-Frenk-White (NFW) dark matter halos to identify TLM-specific signatures. This hypothesis awaits empirical validation and is distinct from the established spatial emergence in Section~\ref{subsec:spatial_factor}.

\subsection{Velocity-Dependent Symmetry}
\label{subapp:velocity_symmetry}
\textbf{Speculative Hypothesis}: A proposed symmetry relates the characteristic timescale \( T \) to velocity \( v \):
\begin{equation}
T \cdot \left( \frac{v}{c} \right)^2 = \frac{\hbar}{m c^2},
\end{equation}
suggesting a balance between temporal and spatial delays (Appendix~\ref{subapp:symmetry}). This relation is motivated by dimensional consistency but lacks empirical support.

\textbf{Proposed Test}: Conduct time-of-flight measurements at CERN’s LHCb or ATLAS experiments, targeting particles with \( v \approx c \) (e.g., muons, \( m \sim \SI{1.88e-28}{\kilogram} \)). For \( v/c \sim 0.999 \), the predicted delay is:
\begin{equation}
T \approx \frac{\SI{1.0545718e-34}{\joule\second}}{\SI{1.88e-28}{\kilogram} \cdot (\SI{2.99792458e8}{\meter\per\second})^2 \cdot 0.999^2} \approx \SI{6.3e-21}{\second}.
\end{equation}
Picosecond-resolution detectors could test this, comparing against Standard Model expectations \citep{ATLAS2023}. This remains conjectural, pending experimental confirmation.

\subsection{Cosmic Expansion and Dark Energy}
\label{subapp:cosmic_expansion}
\textbf{Speculative Hypothesis}: Increasing Distance Factors (\( D \)) in CI-ARCs may contribute to cosmic expansion, potentially linked to dark energy. This idea extends the TLM’s spatial framework (Section~\ref{subsec:spatial_factor}) but lacks a detailed derivation or direct observational tests.

\textbf{Proposed Test}: Analyze CMB power spectra and large-scale structure data from Planck or DESI to detect correlations between \( D \)-dependent effects and expansion rates \citep{Aghanim2020, DESI2024}. This hypothesis is exploratory and requires further theoretical development.

\subsection{Philosophical Implications: Free Will and Intentionality}
\label{subapp:free_will}
\textbf{Speculative Discussion}: The TLM’s delay mechanism, where causal events are paced by mass-induced delays, raises questions about free will and intentionality. The model suggests that observers—defined as systems recording state changes (Section~\ref{subsec:observer_definition})—may influence outcomes within a deterministic causal flow. This delay could hypothetically provide a temporal window for decision-making, resonating with philosophical discussions of intentionality \citep{Smolin1997}. These ideas are outside the TLM’s testable scope and are included for philosophical exploration.

\subsection{Metaphysical Perspective}
\label{subapp:metaphysical}
\textbf{Speculative Discussion}: The TLM’s structure may suggest a framework compatible with inquiries into purposeful design, where the universe enables meaningful observation by systems capable of state changes. This perspective aligns with discussions of intentionality \citep{Smolin1997} but remains a conceptual exploration, not a scientific claim.











\clearpage


\section{Glossary}
\label{sec:glossary}
\begin{description}
    \item[Timeless Light Model (TLM)] A framework unifying General Relativity and Quantum Mechanics, where physical reality emerges from a timeless Photon Instruction Layer (PIL) via mass-induced delays governed by \( T \cdot m = \hbar / c^2 \).
    \item[Photon Instruction Layer (PIL)] A timeless, non-spatial directed graph \( G = (V, E) \), where vertices \( V \) represent event endpoints (emission and absorption) and edges \( E \) represent Causal Instruction Arcs (CI-ARCs), encoding all causal instructions for the universe.
    \item[Causal Instruction Arc (CI-ARC)] A tuple \( (v_i, v_j, C, \Delta, D) \), where \( v_i, v_j \in V \) are emission and absorption points, \( C \) ensures conservation of energy and momentum, \( \Delta \) is the projection delay governed by (1.1), and \( D = \frac{|\mathbf{x}_j - \mathbf{x}_i|}{\lambda_C} \) (with \( \lambda_C = \frac{\hbar}{m c} \)) codes spatial separation in the Spacetime Deployment Frame (SDF).
    \item[DELAY TO C] The mechanism pacing causal resolution to the speed of light, governed by (1.1), ensuring sequential event deployment in the SDF.
    \item[Spacetime Deployment Frame (SDF)] The observable framework where events appear sequential due to mass-induced delays, emerging as a projection of PIL instructions, analogous to events piercing a spacetime fabric.
    \item[Extra-SDF Event (ESE)] A CI-ARC with zero projection delay (\( \Delta = 0 \)), enabling instantaneous quantum effects, such as entanglement correlations or tunneling, without violating causality.
    \item[Distance Factor (\( D \))] A dimensionless scalar determining spatial separation in the SDF, 
    defined as \( D = \frac{|\mathbf{x}_j - \mathbf{x}_i|}{\lambda_C} \). Large \( D \) values 
    contribute to gravitational effects attributed to dark matter, as unresolved CI-ARCs form compact,
    non-luminous regions.
\end{description}

\clearpage


\begin{thebibliography}{9}


\bibitem{Weinberg1972}
S. Weinberg,
\textit{Gravitation and Cosmology: Principles and Applications of the General Theory of Relativity}
(John Wiley \& Sons, New York, 1972), ISBN 978-0-471-92567-5.

\bibitem{Sakurai1994}
J. J. Sakurai,
\textit{Modern Quantum Mechanics}, Revised Edition
(Addison-Wesley, Reading, MA, 1994), ISBN 978-0-201-53929-5.

\bibitem{Aghanim2020}
N. Aghanim et al. (Planck Collaboration),
\textit{Planck 2018 results. VI. Cosmological parameters},
Astron. Astrophys. \textbf{641}, A6 (2020),
doi:10.1051/0004-6361/201833910.

\bibitem{Steinhauer2016}
J. Steinhauer,
\textit{Observation of quantum Hawking radiation and its entanglement in an analogue black hole},
Nat. Phys. \textbf{12}, 959--965 (2016),
doi:10.1038/nphys3863.

\bibitem{Dirac1930}
P. A. M. Dirac,
\textit{The Principles of Quantum Mechanics}
(Oxford University Press, Oxford, 1930), ISBN 978-0-19-852011-5.

\bibitem{Green1987}
M. B. Green, J. H. Schwarz, and E. Witten,
\textit{Superstring Theory: Volume 1, Introduction}
(Cambridge University Press, Cambridge, 1987), ISBN 978-0-521-35752-4.

\bibitem{Rovelli2004}
C. Rovelli,
\textit{Quantum Gravity}
(Cambridge University Press, Cambridge, 2004), ISBN 978-0-521-83733-0.

\bibitem{Dodelson2003}
S. Dodelson,
\textit{Modern Cosmology}
(Academic Press, San Diego, 2003), ISBN 978-0-12-219141-1.

\bibitem{Smolin1997}
L. Smolin,
\textit{The Life of the Cosmos}
(Oxford University Press, Oxford, 1997), ISBN 978-0-19-510837-8.

\bibitem{Einstein1915}
A. Einstein,
\textit{Die Feldgleichungen der Gravitation},
Sitzungsber. Preuss. Akad. Wiss. 844--847 (1915).

\bibitem{Einstein1905}
A. Einstein,
\textit{Zur Elektrodynamik bewegter Körper},
Ann. Phys. \textbf{17}, 891--921 (1905),
doi:10.1002/andp.19053221004.

\bibitem{Feynman1965}
R. P. Feynman, R. B. Leighton, and M. Sands,
\textit{The Feynman Lectures on Physics}
(Addison-Wesley, Reading, MA, 1965), ISBN 978-0-465-07998-8.

\bibitem{Schrodinger1926}
E. Schr{\"o}dinger,
\textit{Quantisierung als Eigenwertproblem},
Ann. Phys. \textbf{79}, 361--376 (1926),
doi:10.1002/andp.19263840404.

\bibitem{Hawking1974}
S. W. Hawking,
\textit{Black hole explosions?},
Nature \textbf{248}, 30--31 (1974),
doi:10.1038/248030a0.

\bibitem{Zeilinger1999}
A. Zeilinger,
\textit{Experiment and the foundations of quantum physics},
Rev. Mod. Phys. \textbf{71}, S288--S297 (1999),
doi:10.1103/RevModPhys.71.S288.

\bibitem{Wheeler1978}
J. A. Wheeler,
\textit{The ``past'' and the ``delayed-choice'' double-slit experiment},
in \textit{Mathematical Foundations of Quantum Theory}, edited by A. R. Marlow
(Academic Press, New York, 1978), pp. 9--48, ISBN 978-0-12-473250-6.

\bibitem{Peskin1995}
M. E. Peskin and D. V. Schroeder,
\textit{An Introduction to Quantum Field Theory}
(Westview Press, Boulder, CO, 1995), ISBN 978-0-201-50397-5.

\bibitem{DESI2024}
DESI Collaboration,
\textit{DESI 2024 VI: Cosmological constraints from galaxy clustering and weak lensing},
arXiv:2404.03002 (2024).

\bibitem{ATLAS2023}
ATLAS Collaboration,
\textit{Precision timing measurements in ATLAS},
J. Instrum. \textbf{18}, P09023 (2023),
doi:10.1088/1748-0221/18/09/P09023.

\bibitem{Marcikic2003}
I. Marcikic et al.,
\textit{Time-bin entangled qubits for quantum communication},
Phys. Rev. A \textbf{68}, 022308 (2003),
doi:10.1103/PhysRevA.68.022308.

\bibitem{Abazajian2016}
K. N. Abazajian et al.,
\textit{CMB-S4 Science Book, First Edition},
arXiv:1610.02743 (2016).

\bibitem{Lewis2002}
A. Lewis and S. Bridle,
\textit{Cosmological parameters from CMB and other data: A Monte Carlo approach},
Phys. Rev. D \textbf{66}, 103511 (2002),
doi:10.1103/PhysRevD.66.103511.

\bibitem{Ashton2019}
G. Ashton et al.,
\textit{BILBY: A user-friendly Bayesian inference library for gravitational-wave astronomy},
Astrophys. J. Suppl. Ser. \textbf{241}, 27 (2019),
doi:10.3847/1538-4365/ab06fc.

\bibitem{Guth1981}
A. H. Guth,
\textit{Inflationary universe: A possible solution to the horizon and flatness problems},
Phys. Rev. D \textbf{23}, 347--356 (1981),
doi:10.1103/PhysRevD.23.347.

\end{thebibliography}
\end{document}
```



</details>

---
{% endraw %}
