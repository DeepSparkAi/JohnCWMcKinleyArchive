---
layout: default
title: '[2025] Photon as Instruction, Not Traveler: Emission, Absorption, and the Myth of Flight'
description: 'Publication metadata and archived raw LaTeX source by John C. W. McKinley.'
permalink: /papers/photon-as-instruction-not-traveler-emission-absorption-and-the-myth-of-flight/
paper: true
---
{% raw %}
# [2025] Photon as Instruction, Not Traveler: Emission, Absorption, and the Myth of Flight
*   **DOI:** [10.5281/zenodo.17221119](https://doi.org/10.5281/zenodo.17221119)
*   **Date:** 28 September 2025

<details markdown="1">
<summary><b>Click to view Raw LaTeX Source</b></summary>

```latex
\documentclass[12pt,onecolumn]{article}

% ---------- Encoding & Fonts ----------
\usepackage[utf8]{inputenc}
\usepackage[T1]{fontenc}
\usepackage{lmodern}
\usepackage{setspace} % Added for line spacing
\setstretch{1.12} % Set line spacing
\usepackage{microtype}

% ---------- Page & Layout ----------
\usepackage[margin=1in]{geometry}

% ---------- Math ----------
\usepackage{amsmath,amssymb,amsthm}

% ---------- Figures ----------
\usepackage{booktabs}
\usepackage{tikz}
\usetikzlibrary{arrows.meta, positioning, calc, shapes.geometric}

% ---------- Links & References ----------
\usepackage{hyperref}
\hypersetup{colorlinks=true, linkcolor=blue, urlcolor=blue, citecolor=blue}
\usepackage{cleveref} % Added for cross-referencing

% ---------- Headers ----------
\usepackage{fancyhdr}
\pagestyle{fancy}
\fancyhf{}
\lhead{Photon as Instruction, Not Traveler}
\rhead{\thepage}

% ---------- ORCID ----------
\usepackage{orcidlink}

% ---------- Title ----------
\title{Photon as Instruction, Not Traveler: Emission, Absorption, and the Myth of Flight}

\usepackage{orcidlink}
\author{John C. W. McKinley\orcidlink{0009-0005-7097-5035}\\Independent Researcher}
\date{September 28, 2025}

\begin{document}
\maketitle


\begingroup
  \footnotetext[0]{This version published at
  \href{https://doi.org/10.5281/zenodo.17221119}{https://doi.org/10.5281/zenodo.17221119}.}
\endgroup



\begin{abstract}
This paper offers a fresh look at a theme explored across several earlier works in the \textbf{Timeless Light Model (TLM)}: the question of whether photons truly ``travel.'' In both everyday and professional physics discourse, photons are often described as if they ``fly'' across the universe, carrying light from stars to our eyes. This paper challenges that intuition. Building on Einstein's insight that massless quanta accrue no proper time, we argue that all observational evidence consists only of emission and absorption events. What appears to be ``travel'' is a coordinate separation in the observer’s frame, not proof of a persisting particle in transit. We formalize this view within the TLM, where photons are reclassified as \textbf{instruction events} linking endpoints in spacetime deployment, not as objects traversing a void. This reframing avoids contradictions in relativistic limits and clarifies the ontology of light. Here the emphasis is pedagogical and synthetic: we reframe the photon as an instruction linking endpoints, summarize the TLM ontology (\textbf{Quantum Platform} and \textbf{Spacetime Deployment Frame}), and collect the supporting relativistic and axiomatic derivations into a single accessible treatment. By declaring explicitly that the photon’s supposed motion is a myth, we aim to clarify conceptual confusions, unify earlier presentations, and provide a clear entry point for newcomers to the TLM framework.
\end{abstract}


\section{Introduction}
\label{sec:intro}
Conventional physics education describes photons as massless particles emitted, propagating through space at speed $c$, and absorbed at a later time. This narrative carries a Newtonian residue: the assumption of persistence between emission and absorption. Yet relativity undermines this picture. Einstein's 1905 work showed that for massless quanta, the invariant interval $ds^2 = 0$ along their worldlines \cite{einstein1905}. This means the proper time $\tau$ is non-existent, and $d\tau = 0$, leaving the middle stretch ontologically empty from the photon's frame \cite{photon_propertime}.

The observational facts are simpler:
\begin{enumerate}
    \item An emission event occurs.
    \item An absorption event occurs.
    \item Our frame records a delay between the two.
\end{enumerate}
But no direct evidence compels us to posit that a photon ``traveled'' in between. This paper defends that reframing \cite{thought_experiments}.



\section{Relativistic Limits}
\label{sec:relativity}
Consider Minkowski space, with metric signature $(- + + +)$. The invariant interval is
\begin{equation}
ds^2 = -c^2 dt^2 + dx^2 + dy^2 + dz^2.
\end{equation}
For a photon, $ds^2 = 0$, yielding $d\tau = 0$. This means no time accumulates along the path. To treat the photon as a persisting traveler with internal history contradicts this invariant. From relativity’s standpoint, it is more precise to say that a photon’s worldline links two events without interior passage.

\section{Empirical Evidence}
\label{sec:empirical}
Astronomy and laboratory optics measure time-of-flight indirectly. For example, the Sun's photons take about 8 minutes to reach Earth. Yet what is measured is not a traveler's elapsed time, but the difference between emission at the Sun's photosphere and absorption in terrestrial detectors. The ``in flight'' story is interpolated, not observed.

This leads to the central claim: the only empirical evidence is the correlation of endpoints, not a persisting corpuscle in between.

\section{Timeless Light Model (TLM): Ontology, Postulates, Resolutions}
\label{sec:tlm}

\paragraph{Two-layer ontology.}
\emph{Layer 1: Quantum Platform (QP).} A timeless, causally senior layer that records and issues completed emission–absorption instructions. Instructions have no internal evolution, no duration, and no location.
\emph{Layer 2: Spacetime Deployment Frame (SDF).} The observer-accessible GR/SR arena where those instructions are rendered as events with delay and structure. Delay is governed by mass and curvature, structure by quantum rules.

\paragraph{Core postulates.}
\textbf{P1 (Timeless Authoring).} All realized quanta are authored on \textbf{QP} as fully resolved emission–absorption arcs; only arcs satisfying global constraints are written \cite{gpl}.
\textbf{P2 (Rendered Experience).} The \textbf{SDF} renders written arcs in sequence. The experienced “time” is rendering delay $T$.
\textbf{P3 (Dual Filtering).} Deployment obeys a dual filter: a delay filter associated with GR and a structure filter associated with QM. In natural units the bridge laws are $T \cdot m = 1$ and $T \cdot C_s = 1$; in SI units $T \cdot m = \hbar / c^{2}$ \cite{tlm_v2}.

\paragraph{Photon status.}
A photon is not a persisting traveler in \textbf{SDF} but a \textbf{QP} instruction that links an emission endpoint $E$ and an absorption endpoint $A$. Its null trace in \textbf{SDF} satisfies $d\tau=0$, so there is no photon ``clock'' and no in-between persistence to observe \cite{photon_absent}.

\paragraph{Operational resolutions.}
\emph{Entanglement.} Correlated outcomes arise from shared instructions authored on \textbf{QP}; the apparent nonlocality is a rendering artifact.
\emph{Wave–particle duality.} ``Wave'' is structure filtering during deployment; ``particle'' is endpoint accounting of conserved quantities.
\emph{Measurement.} What is called ``collapse'' is reinterpreted as \emph{rendering}: selecting and displaying a \textbf{QP}-written instruction consistent with constraints and context.

\paragraph{Minimal interface.}
An instruction is represented by the tuple
\begin{equation}
\label{eq:instruction_tuple}
I = \langle x^\mu_{E},\, x^\mu_{A};\, \Delta p^\mu,\, \Delta J^{\mu\nu},\, \Delta Q \rangle,
\end{equation}
with conserved transfers enforced at endpoints. The \emph{Generalized Pairing Law} states that no emission is written without a compatible absorber \cite{gpl}.

QP authoring is timeless, but all observable deployment occurs in the SDF at the causal limit set by the bridge law \(T \cdot C_s = 1\); even when \(m=0\) everywhere (so \(T=0\) on QP), rendered links appear as null traces at speed \(c\) in the SDF.\\


\noindent\textit{Clarification.} The timeless resolution on QP does not imply superluminal signaling in the SDF: the bridge law \(T \cdot C_s = 1\) enforces \(C_s=c\) operationally, so all realized CI–ARCs render as null deployments (\(d\tau=0\)) respecting SR/GR causality.






\begin{table}[htbp]
\centering
\caption{Postulates and Bridge Laws of the Timeless Light Model (TLM)}
\label{tab:postulates_bridge_laws}
\rotatebox{90}{%
\begin{tabular}{l p{10cm}}
\toprule
\textbf{Item} & \textbf{Description} \\
\midrule
\textbf{P1: Timeless Instruction Authoring} & All events authored on \textbf{QP} as fully completed emission--absorption arcs; only outcomes satisfying constraints are written. \\
\textbf{P2: Rendered Experience} & \textbf{SDF} renders instructions in order. Time = rendering delay. \\
\textbf{P3: Dual Filtering} & Delay filter (GR) via mass-induced $T \cdot m = \hbar/c^2$, and structure filter (QM) via wavefunction rules. \\
\midrule
\textbf{Bridge Law 1: Mass--Delay Law (Natural Units)} & $T \cdot m = 1$. Binds rest mass $m$ to the delay $T$ it imposes. \\
\textbf{Bridge Law 1: Mass--Delay Law (Standard Units)} & $T \cdot m = \hbar/c^2$. For massless particles ($m=0$), $T=0$ implies instantaneous rendering on \textbf{QP}, appearing as $c$ (max causal rate) in \textbf{SDF}. \\
\textbf{Bridge Law 2: Delay Law (Natural Units)} & $T \cdot C_s = 1$. Defines the inverse relation between deployment delay $T$ and causal speed $C_s$. \\
\textbf{Bridge Law 2: Delay Law (Standard Units)} & $T \cdot C_s = 1$. Governs deployment delay for realized records, independent of energy transfer $\Delta E$. \\
\bottomrule
\end{tabular}
}% rotatebox
\end{table}
















\section{Photon as Instruction}
\label{sec:instruction}
The \textbf{Timeless Light Model (TLM)} reclassifies photons as instruction events resolved in the \textbf{Quantum Platform (QP)} and deployed with delay in the \textbf{Spacetime Deployment Frame (SDF)}. The photon does not occupy spacetime; instead, it specifies the transfer of energy between two endpoints. Its ``timelessness'' follows from the invariant $d\tau = 0$.

Within this model:
\begin{itemize}
    \item Mass imposes delay ($T \cdot m = \hbar / c^2$) \cite{massdelay}.
    \item Causality is preserved as events only deploy after absorption.
    \item Photons are absent from the universe; only emission and absorption are present.
\end{itemize}

\section{Mathematical Formalism}
\label{sec:math}
Let an emission event be $E$ and an absorption event $A$. In the observer's frame:

\begin{equation}
\label{eq:delta_coords}
\Delta t = t_A - t_E, \qquad \Delta x = x_A - x_E.
\end{equation}

The null condition is

\begin{equation}
\label{eq:null_condition}
c^2 \Delta t^2 = \Delta x^2 + \Delta y^2 + \Delta z^2.
\end{equation}

This is satisfied in our coordinates. Yet along the photon's worldline, proper time remains

\begin{equation}
\label{eq:proper_time_zero}
\Delta \tau = 0.
\end{equation}

Thus the notion of ``travel'' is coordinate bookkeeping, not intrinsic physics.

\begin{figure}[htbp]
  \centering
  \begin{tikzpicture}[
    node distance=1.8cm,
    box/.style={rounded corners, draw, thick, inner sep=6pt, minimum width=3.0cm},
    evt/.style={circle, draw, thick, inner sep=2pt, minimum size=7mm},
    arr/.style={-{Latex[length=3mm,width=2mm]}, thick}
  ]

  % QP block
  \node[box, fill=gray!10, label=above:{\small Quantum Platform (QP) -- timeless}] (QP) {%
    \begin{minipage}{4.2cm}\centering
      \footnotesize Causal Instruction Arc \\[2pt]
      $I=\langle x^\mu_E, x^\mu_A; \Delta p^\mu, \Delta J^{\mu\nu}, \Delta Q\rangle$\\[2pt]
      \emph{No duration, no location}
    \end{minipage}
  };

  % Mapping arrow
  \node[box, fill=gray!10, right=5.2cm of QP, label=above:{\small Spacetime Deployment Frame (SDF)}] (SDF) {%
    \begin{minipage}{5.1cm}\centering
      \footnotesize Rendering with dual filter\\
      Delay: $T$ with $T\cdot m=\hbar/c^2$\\
      Structure: QM rules in Hilbert space
    \end{minipage}
  };

  \draw[arr] (QP) -- node[above, yshift=-2cm,sloped]{\footnotesize rendering map $\Pi: \text{QP}\to\text{SDF}$} (SDF);

  % SDF null trace panel
  \begin{scope}[shift={(7.4,0)}]
    % axes
    \draw[->, thick] (-2.0,-1.2) -- (-2.0,1.2) node[above]{\(\,ct\)};
    \draw[->, thick] (-3.2,0) -- (-0.8,0) node[right]{\(x\)};

    % emission and absorption events
    \node[evt, fill=white, label=below left:{\footnotesize \(E\)}] (E) at (-2.6,-0.7) {};
    \node[evt, fill=white, label=above right:{\footnotesize \(A\)}] (A) at (-1.4,0.7) {};

    % null line
    \draw[arr] (E) -- (A) node[midway, below right=2pt]{\scriptsize null: $d\tau=0$};

    % lightcone hints
    \draw[dashed] (-2.6,-0.7) -- (-1.2,-2.1);
    \draw[dashed] (-2.6,-0.7) -- (-4.0,0.7);
  \end{scope}

  \end{tikzpicture}
  \caption{A \textbf{QP Causal Instruction Arc ($I$)} renders into the \textbf{SDF} as a null trace from emission $E$ to absorption $A$. The photon has no ticking proper time ($\Delta \tau = 0$); only endpoints are observable. The instruction tuple $I$ is defined in \cref{eq:instruction_tuple}.}
  \label{fig:qp_to_sdf_null}
\end{figure}

\section{Falsifiable Predictions}
\label{sec:predictions}

While this paper emphasizes the conceptual and ontological reframing of photons within the \textbf{Timeless Light Model (TLM)}, physics demands empirical testability. TLM's descriptive laws---such as the delay law $T \cdot C_s = 1$ and mass-delay duality $T \cdot m = \hbar / c^2$---lead to measurable deviations from standard GR and QM predictions. These residuals arise because TLM treats delay as fundamental, introducing small but fixed-sign corrections (positive for delay-increasing effects) that vanish in the standard model.

Here, we synthesize key falsifiable predictions from prior work \cite{predictions_v3}, focusing on their connection to the photon-as-instruction ontology. In TLM, photons (as timeless instructions) experience no proper time, but their rendering in the \textbf{SDF} is modulated by mass-induced delays. This yields anomalies in timing, phases, and statistics across scales. Each test introduces a coefficient (e.g., $\alpha_T$) that TLM predicts to be nonzero and positive, falsifiable by null results at sufficient precision.

\subsection{Gravitational-Wave Phase Residuals}
Inspiral gravitational waves accumulate phase via delay modulation near massive bodies:

\[
\Delta\phi(f) = \alpha_T \frac{d}{dt} \left[ T_{\text{eff}}(f) \right] \tau_{\text{cycle}}(f),
\]

where $T_{\text{eff}}(f)$ is the effective delay at frequency $f$, and $\tau_{\text{cycle}}(f)$ is one cycle's duration. TLM predicts $\alpha_T > 0$ (order $10^{-3}$ to $10^{-5}$ radians), testable with LIGO/Virgo data.

\subsection{Strong-Lensing Time-Delay Anomalies}
Strong lensing paths experience differential delays:

\[
\Delta t_{\text{obs}} = \Delta t_{\text{GR}} + \beta_T (T_{\text{lens}} - T_{\text{ref}}),
\]

with $T_{\text{lens}}$ and $T_{\text{ref}}$ along lensed/reference paths. TLM predicts $\beta_T > 0$ ($\sim 10^{-2}$ days), detectable in LSST quasar surveys.

\subsection{Cosmological Redshift Drift}
Expansion modulates lightcone delays, modifying drift:

\[
\dot{z}_{\text{obs}} = \dot{z}_{\Lambda\text{CDM}} + \gamma_T \left. \frac{dT}{dt} \right|_{\text{lightcone}},
\]

TLM predicts $\gamma_T > 0$ ($10^{-10}$ yr$^{-1}$), testable with ELT/SKA.

\subsection{Shapiro Echo Perturbations}
Radar/pulsar echoes gain delay gradients:

\[
\Delta t_{\text{echo}} = \Delta t_{\text{Shapiro}} + \kappa_T \int_{\text{path}} \nabla T \cdot dl,
\]

TLM predicts $\kappa_T > 0$ ($\sim 10^{-6}$ s), detectable in pulsar arrays.

\subsection{Clock Gradients in Mass Shells}
Tunable mass shells induce clock differences:

\[
\frac{\Delta \nu}{\nu} = \left( \frac{\Delta \nu}{\nu} \right)_{\text{GR}} + \eta_T \Delta T_{\text{shell}},
\]

TLM predicts $\eta_T > 0$ ($10^{-18}$ precision), testable with optical clocks.

\subsection{Interferometer with Inertial Load}
Mass-loaded interferometer arms add path delays:

\[
\Delta\phi = \frac{2\pi}{\lambda} \left( L + \xi_T \int_{\text{path}} T(r) dl \right),
\]

TLM predicts $\xi_T > 0$, testable in LIGO-like setups.

\subsection{CMB Non-Gaussian Tail Signatures}
Delay fluctuations imprint non-Gaussianity:

\[
K_l = K_l^{\Lambda\text{CDM}} + \zeta_T F_l[T],
\]

at high multipoles ($\ell \gtrsim 2000$). TLM predicts $\zeta_T > 0$, analyzable with Planck/CMB-S4.

\subsection{Entanglement Coincidence Widths}
Entangled pairs vary in delay:

\[
\Delta \tau_{\text{pairs}} = \Delta \tau_{\text{QM}} + \chi_T \text{Var}[T],
\]

TLM predicts $\chi_T > 0$ (fs scales), measurable in quantum optics.

\subsection{Summary of Predictions}
The coefficients vanish in GR/QM but are nonzero in TLM, with signs fixed by delay ontology.

\begin{table}[htbp]
\centering
\caption{Summary of Falsifiable Predictions in TLM}
\label{tab:predictions}
\begin{tabular}{@{}llll@{}}
\toprule
Test Domain & Coefficient & Expected Sign & Key Experiment/Data \\ \midrule
Gravitational Waves & $\alpha_T$ & Positive & LIGO/Virgo inspirals \\
Strong Lensing & $\beta_T$ & Positive & Quasar lens surveys (e.g., LSST) \\
Redshift Drift & $\gamma_T$ & Positive & ELT/SKA campaigns \\
Shapiro Echo & $\kappa_T$ & Positive & Pulsar timing arrays \\
Clock Shells & $\eta_T$ & Positive & Atomic clock labs \\
Interferometer Load & $\xi_T$ & Positive & LIGO-like interferometers \\
CMB Non-Gaussianity & $\zeta_T$ & Positive & Planck/CMB-S4 \\
Entanglement Widths & $\chi_T$ & Positive & Quantum optics setups \\ \bottomrule
\end{tabular}
\end{table}

These tests bridge TLM's photon ontology to data, inviting falsification. Null results would refute TLM; detections could validate its delay-based causality.

\section{Rigorous Derivations from TLM Axioms}
\label{sec:rigorous}

\subsection{Instruction tuple and the Generalized Pairing Law}
An elementary realized quantum is represented by
\begin{equation}
\label{eq:instruction_tuple_full}
I=\langle x^\mu_{E},\, x^\mu_{A};\, \Delta p^\mu,\, \Delta J^{\mu\nu},\, \Delta Q \rangle .
\end{equation}
The \emph{Generalized Pairing Law (GPL)} asserts: an instruction exists if and only if a compatible absorber exists. No orphan emissions are written on \textbf{QP} \cite{gpl}.

\subsection{Bridge laws}
In natural units,
\begin{equation}
T \cdot m = 1, \qquad T \cdot C_s = 1.
\end{equation}
Restoring constants yields
\begin{equation}
\label{eq:bridge_laws}
T \cdot m = \frac{\hbar}{c^{2}}, \qquad T \cdot C_s = 1.
\end{equation}

\subsection{Null deployment}
Between emission and absorption,
\begin{equation}
g_{\mu\nu}\Delta x^\mu \Delta x^\nu = 0, \qquad \Delta \tau = 0.
\end{equation}
Affine parametrization shows photons traverse null geodesics with zero proper time.

\subsection{Delay gradients and curvature}
In the weak-field limit, let delay field $T(x)$ encode lapse:
\begin{equation}
\label{eq:delay_lapse}
\phi(x) = - c^{2}\ln \big(T(x)/T_0\big).
\end{equation}
Then free-fall acceleration is
\begin{equation}
\label{eq:newtonian_a}
\mathbf{a} = c^{2}\nabla \ln T.
\end{equation}
Applying Poisson’s equation yields
\begin{equation}
\label{eq:poisson}
\nabla^{2}\ln T = -\frac{4\pi G}{c^{2}}\rho.
\end{equation}
Thus delay gradients reproduce Newtonian gravity and extend to GR curvature \cite{tlm_v2, massdelay}.

\section{Discussion}
\label{sec:discussion}
This reinterpretation sidesteps paradoxes:
\begin{itemize}
    \item No ``cornering'' of photons at high energy is needed.
    \item No internal evolution of a massless corpuscle must be imagined.
    \item Observational delay is rendered as deployment structure, not as transit.
\end{itemize}
The \textbf{TLM} thereby offers an ontological simplification: photons are not in the universe, but are instructions linking its events.

\section{Conclusion}
\label{sec:conclusion}
From our frame, we observe delays between emission and absorption. From the photon’s frame, there is no passage at all. The story of a particle flying through space is an artifact of classical imagination. By reframing photons as instruction events, the \textbf{Timeless Light Model} unifies relativity’s invariants with a deeper causal ontology.

\section*{Glossary}
\begin{itemize}
\item \textbf{Affine Parameter}: Null-path tracker substituting for proper time.
\item \textbf{Arrow of Time}: Entropic directionality emerging only for delayed systems (not photons).
\item \textbf{Causal Instruction Arc (CI-ARC)}: A complete, pre-resolved causal instruction encoding both cause and effect without temporal order; atomic unit of causality.
\item \textbf{Causal Rendering Law}: $T \cdot m = \hbar/c^2$, $T \cdot C_s = 1$.
\item \textbf{Causal Resolution Rate \(C_s\):} Maximum deployment rate in the SDF. Bridge law \(T \cdot C_s = 1\) makes \(C_s=c\) operationally, so rendered links are \(c\)-limited even if QP authoring is timeless.
\item \textbf{Characteristic Timescale (T)}: Observer's temporal experience; inversely proportional to mass.
\item \textbf{Delay Gradient}: Local variation in rendering delay induced by mass, producing gravitational effects. Delay decreases toward mass, pulling unresolved instructions toward equilibrium.
\item \textbf{Deployment Delay (T)}: Rendering delay in the \textbf{SDF}, encoding how long rendering takes relative to the Frame. Equivalent to time as experienced.
\item \textbf{Generalized Pairing Law (GPL)}: An instruction is recorded in \textbf{QP} iff a compatible absorber condition exists. No pending/partial records.
\item \textbf{Geodesic}: Extremal path in spacetime; null for photons, timelike for massive objects. In \textbf{TLM}, path of least delay resolution.
\item \textbf{Instruction Tuple}: Minimal record linking emitter and absorber: $I = \langle x^\mu_e, x^\mu_a; \Delta p^\mu, \Delta J^{\mu\nu}, \Delta Q \rangle$.
\item \textbf{Mass--Delay Duality}: Axiom: $T \cdot m = \hbar/c^2$.
\item \textbf{Null Geodesic}: Path with $ds^2 = 0$. Defines photon worldline, implying $\tau = 0$.
\item \textbf{Photon}: In \textbf{TLM}, not a particle in transit but an instruction linking emission and absorption.
\item \textbf{Photon as Instruction}: Timeless energy-transfer event with no proper time.
\item \textbf{Proper Time ($\tau$)}: Time measured along a particle's worldline; zero for photons.
\item \textbf{Quantum Platform (QP)}: Timeless layer where instructions originate.
\item \textbf{Rendering}: Mapping of resolved instruction from \textbf{QP} to \textbf{SDF}, introducing delay and curvature.
\item \textbf{Spacetime Deployment Frame (SDF)}: Observable frame where instructions deploy with delay.
\item \textbf{Timeless Instruction}: Pre-resolved directive from \textbf{QP} linking events (e.g., emission to absorption) without traversal.
\item \textbf{Wave-Particle Duality}: In \textbf{TLM}, ``wave'' is structure filtering during deployment; ``particle'' is endpoint accounting of conserved quantities.
\end{itemize}

% ---------- Bibliography ----------
\begin{thebibliography}{9}

\bibitem{einstein1905}
A. Einstein, ``Zur Elektrodynamik bewegter Körper,'' \textit{Annalen der Physik} \textbf{322}, 891–921 (1905).
DOI: \href{https://doi.org/10.1002/andp.19053221004}{10.1002/andp.19053221004}.

\bibitem{massdelay}
J. C. W. McKinley, ``Mass Imposes Delay, Wavefunctions Define Terrain: A Two-Filter Ontology of Reality,'' Zenodo (2025).
DOI: \href{https://doi.org/10.5281/zenodo.16672398}{10.5281/zenodo.16672398}.

\bibitem{photon_absent}
J. C. W. McKinley, ``Light as Absent: Reclassifying the Photon as a Timeless Instruction,'' Zenodo (2025).
DOI: \href{https://doi.org/10.5281/zenodo.16627550}{10.5281/zenodo.16627550}.

\bibitem{gpl}
J. C. W. McKinley, ``Generalized Pairing Law: No Quantum Emission Without an Absorber,'' Zenodo (2025).
DOI: \href{https://doi.org/10.5281/zenodo.16893165}{10.5281/zenodo.16893165}.

\bibitem{tlm_v2}
J. C. W. McKinley, ``Timeless Light Model (TLM v2.0): Frameless Quanta, Framed Observers, and Bridge Laws,'' Zenodo (2025).
DOI: \href{https://doi.org/10.5281/zenodo.16934697}{10.5281/zenodo.16934697}.

\bibitem{photon_propertime}
J. C. W. McKinley, ``Photon Proper Time: The Understated Invariant of Special Relativity,'' Zenodo (2025).
DOI: \href{https://doi.org/10.5281/zenodo.17190047}{10.5281/zenodo.17190047}.

\bibitem{thought_experiments}
J. C. W. McKinley, ``Photon Thought Experiments and the Timeless Ontology: Why Photons and Quanta Are ``Not Here'','' Zenodo (2025).
DOI: \href{https://doi.org/10.5281/zenodo.17216652}{10.5281/zenodo.17216652}.

\bibitem{predictions_v3} % Placeholder for the prediction paper
J. C. W. McKinley, ``From Descriptive Laws to Falsifiable Predictions: Testing the Timeless Light Model,'' Zenodo (2025).
DOI: \href{https://doi.org/10.5281/zenodo.17017852}{10.5281/zenodo.17017852}.

\bibitem{newtonian_limit} % Placeholder for the Newtonian derivation paper
J. C. W. McKinley, ``Unified Quantization Principle: GR, SR, and QM as Quantized Deployments of Binary Quanta,'' Zenodo (2025).
DOI: \href{https://doi.org/10.5281/zenodo.16913967}{10.5281/zenodo.16913967}.

\end{thebibliography}

\end{document}
```

</details>

---
{% endraw %}
