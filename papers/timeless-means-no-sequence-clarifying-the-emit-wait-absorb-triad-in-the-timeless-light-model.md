---
layout: default
title: '[2025] Timeless Means No Sequence: Clarifying the Emit–Wait–Absorb Triad in the Timeless Light Model'
description: 'Publication metadata and archived raw LaTeX source by John C. W. McKinley.'
permalink: /papers/timeless-means-no-sequence-clarifying-the-emit-wait-absorb-triad-in-the-timeless-light-model/
paper: true
---
{% raw %}
# [2025] Timeless Means No Sequence: Clarifying the Emit–Wait–Absorb Triad in the Timeless Light Model
*   **DOI:** [10.5281/zenodo.17389830](https://doi.org/10.5281/zenodo.17389830)
*   **Date:** 19 October 2025

<details markdown="1">
<summary><b>Click to view Raw LaTeX Source</b></summary>

```latex
\documentclass[12pt,letterpaper,onecolumn]{article}

% --- Fonts & Language ---
\usepackage[T1]{fontenc}
\usepackage[utf8]{inputenc}
\usepackage{lmodern}

% --- Page & layout ---
\usepackage[margin=1in]{geometry}
\usepackage{setspace}
\setstretch{1.12}
\usepackage{microtype}
\usepackage{enumitem}

% ====== Math & Theorems ======
\usepackage{amsmath,amssymb,bm}
\usepackage{amsthm}
\newtheorem{definition}{Definition}
\newtheorem{postulate}{Postulate}
\newtheorem{proposition}{Proposition}
\newtheorem{lemma}{Lemma}
\newtheorem{theorem}{Theorem}

% --- Figures, tables, and layout helpers ---
\usepackage{graphicx}
\usepackage{float}
\usepackage{array}
\usepackage{booktabs}
\newcolumntype{L}[1]{>{\raggedright\arraybackslash}p{#1}}
\usepackage{rotating}   % for sidewaystable
\usepackage{pdflscape}
\usepackage{placeins}

% --- Color boxes ---
\usepackage[most]{tcolorbox}
\tcbset{colback=gray!5,colframe=black,boxrule=0.6pt,arc=2mm}
\newtcolorbox{lawbox}[1]{breakable,title={#1},fonttitle=\bfseries}

% --- TikZ ---
\usepackage{tikz}
\usetikzlibrary{arrows.meta,positioning,calc,shapes.geometric}

% ----- Header/footer -----
\usepackage{fancyhdr}
\usepackage{orcidlink}
\pagestyle{fancy}
\fancyhf{}
\fancyhead[C]{\textit{Timeless Means No Sequence}}
\fancyfoot[C]{\thepage}

% --- Links & refs ---
\usepackage{hyperref}
\hypersetup{
  colorlinks=true,
  linkcolor=blue,
  urlcolor=blue,
  citecolor=blue
}
\usepackage[nameinlink]{cleveref}

% --- Front Matter ---
\title{\vspace{-1.5cm}Timeless Means No Sequence: Clarifying the Emit--Wait--Absorb Triad in the Timeless Light Model}
\author{John C.~W. McKinley\,\orcidlink{0009-0005-7097-5035}\thanks{This version published at
  \href{https://doi.org/10.5281/zenodo.17389830}{https://doi.org/10.5281/zenodo.17389830}.}\\
  Independent Researcher}
\date{October 19, 2025}

\begin{document}
\maketitle

\begin{abstract}
The Emit--Wait--Absorb triad in the Timeless Light Model (TLM) is a logical framing device, not a temporal process. In the timeless Quantum Platform (QP), emission, rule application (``Wait'' filters), and absorption are co-authored as a single, indivisible Causal Instruction Arc (CI-ARC) with no sequence or order. Temporal progression emerges solely during delayed rendering in the Spacetime Deployment Frame (SDF). This paper provides a brief clarification of this point, while the appendices begin to compile a consolidated overview of the TLM canon for reference and tracking the model's state as it approaches completion.
\end{abstract}

\section{Introduction}
The Timeless Light Model (TLM) posits that light and massless quanta are timeless causal instructions authored in the Quantum Platform (QP) and rendered with delay in the Spacetime Deployment Frame (SDF)~\cite{tlm_consideration}. The Emit--Wait--Absorb triad is a pedagogical tool to describe the logical components of a Causal Instruction Arc (CI-ARC), but it does not imply any temporal sequence in QP. This short note clarifies this to avoid misinterpretation, with appendices compiling key elements of the model for ongoing reference.

As TLM evolves, it addresses paradoxes in quantum mechanics and relativity by reclassifying photons as absent from spacetime during ``propagation,'' existing only as pre-resolved instructions. This ontology aligns with Einstein's null proper time for photons \(\tau_\gamma = 0\) and resolves issues like wave--particle duality without retrocausality or hidden variables~\cite{einstein1905,Bell1964}.

\section{Clarification: The Triad is Logical, Not Temporal}
In QP, which is atemporal (\(T=0,\ m=0\)), the entire CI-ARC---including emission (E), filters (quantum \(\psi\), relativistic delay via \(T\cdot m=\hbar/c^{2}\)), and absorption (\(A^{*}\))---is authored holistically as a single unit. There is no ``order'' or ``process''; all aspects are simultaneous in inscription, akin to defining a mathematical equation where inputs, operations, and outputs are specified at once~\cite{causal_chain,frame_display}.

\medskip
\noindent\textbf{Emit:} Logical input (source state at \(x_e^{\mu}\)).\\
\textbf{Wait:} Intrinsic constraint satisfaction (eligibility filters).\\
\textbf{Absorb:} Logical output (realized endpoint at \(x_a^{\mu}\)).
\medskip

Sequence emerges only in SDF via mass-drag delay, where observers perceive propagation. This preserves \(\tau=0\) for photons and resolves paradoxes without retrocausality~\cite{wait_novice}. The triad's logical structure reinforces TLM's unification: quantum nonlocality arises from timeless filters in QP, while relativistic causality emerges from delayed rendering in SDF. Any perceived ``process'' in descriptions is a human artifact for explanatory purposes.

\section{Conclusion}
By emphasizing the triad's logical nature, TLM avoids any implication of time in QP. The appendices below compile the current TLM canon for consolidation and tracking, drawing from prior works to provide a unified reference as the model matures toward formalization and testing.

% ---------------- BIBLIOGRAPHY ----------------
% ---------------- BIBLIOGRAPHY ----------------
\begin{thebibliography}{9}

\bibitem{tlm_consideration}
McKinley, J.~C.~W. (2025).
\newblock \emph{Why the Timeless Light Model Deserves Scientific Consideration: A Foundational Framework with Derivations, Critiques, and Experimental Proposals}.
\newblock Zenodo.
\href{https://doi.org/10.5281/ZENODO.16724187}{doi:10.5281/ZENODO.16724187}.

\bibitem{causal_chain}
McKinley, J.~C.~W. (2025).
\newblock \emph{Causal Chain in the Timeless Light Model: Mass as Drag, Frame as Causal Site, Quantum Platform as Cause}.
\newblock Zenodo.
\href{https://doi.org/10.5281/ZENODO.17139863}{doi:10.5281/ZENODO.17139863}.

\bibitem{frame_display}
McKinley, J.~C.~W. (2025).
\newblock \emph{Frame Display Law for TLM v2.0: EA-conditioned Rendering in a Single Spacetime Deployment Frame}.
\newblock Zenodo.
\href{https://doi.org/10.5281/ZENODO.16936105}{doi:10.5281/ZENODO.16936105}.

\bibitem{wait_novice}
McKinley, J.~C.~W. (2025).
\newblock \emph{The Wait Phase in the Timeless Light Model (TLM v3.0)}.
\newblock Zenodo.
\href{https://doi.org/10.5281/zenodo.17291452}{doi:10.5281/zenodo.17291452}. % Title was not in the new list, retaining original DOI.

\bibitem{newtonian_holodeck}
McKinley, J.~C.~W. (2025).
\newblock \emph{The Failure of the Newtonian Holodeck: Why a Universe Without Relativity Cannot Sustain Itself}.
\newblock Zenodo.
\href{https://doi.org/10.5281/ZENODO.16750632}{doi:10.5281/ZENODO.16750632}.

\bibitem{pdr}
McKinley, J.~C.~W. (2025).
\newblock \emph{The Principle of Delayed Resolution: A Teleological Framework for Unifying Physical Mechanics}.
\newblock SSRN.
\href{https://doi.org/10.2139/ssrn.5310483}{doi:10.2139/ssrn.5310483}.

\bibitem{absent}
McKinley, J.~C.~W. (2025).
\newblock \emph{Light as Absent: Reclassifying the Photon as a Timeless Instruction}.
\newblock Zenodo.
\href{https://doi.org/10.5281/ZENODO.16627550}{doi:10.5281/ZENODO.16627550}.

\bibitem{gravity_geometry}
McKinley, J.~C.~W. (2025).
\newblock \emph{Gravity is Geometry. Reality Obeys Rules. Not the Newtonian Holodeck.}.
\newblock Zenodo.
\href{https://doi.org/10.5281/ZENODO.17197557}{doi:10.5281/ZENODO.17197557}.

\bibitem{einstein1905}
Einstein, A. (1905).
\newblock Zur Elektrodynamik bewegter Körper.
\newblock \textit{Annalen der Physik}, \textbf{17}, 891--921.
\href{https://doi.org/10.1002/andp.19053221004}{doi:10.1002/andp.19053221004}.

\bibitem{Einstein1916}
Einstein, A. (1916).
\newblock The Foundation of the General Theory of Relativity.
\newblock \textit{Annalen der Physik}, \textbf{49}, 769--822.
\newblock \href{https://doi.org/10.1002/andp.19163540702}{doi:10.1002/andp.19163540702}.

\bibitem{Bell1964}
Bell, J.~S. (1964).
\newblock On the Einstein Podolsky Rosen Paradox.
\newblock \textit{Physics Physique Fizika}, \textbf{1}, 195--200.
\newblock \href{https://doi.org/10.1103/PhysicsPhysiqueFizika.1.195}{doi:10.1103/PhysicsPhysiqueFizika.1.195}.


\bibitem{Maxwell1865}
Maxwell, J.~C. (1865).
\newblock A Dynamical Theory of the Electromagnetic Field.
\newblock \textit{Philosophical Transactions of the Royal Society of London}, \textbf{155}, 459--512.
\href{https://doi.org/10.1098/rstl.1865.0008}{doi:10.1098/rstl.1865.0008}.

\bibitem{gpLaw}
McKinley, J.~C.~W. (2025).
\newblock \emph{Generalized Pairing Law: No Quantum Emission Without an Absorber}.
\newblock Zenodo.
\href{https://doi.org/10.5281/ZENODO.16893165}{doi:10.5281/ZENODO.16893165}.

\bibitem{photonTimeless}
McKinley, J.~C.~W. (2025).
\newblock \emph{The Photon as Timeless Instruction}.
\newblock Zenodo.
\href{https://doi.org/10.5281/ZENODO.17221119}{doi:10.5281/ZENODO.17221119}.

\bibitem{emissionDelay}
McKinley, J.~C.~W. (2025).
\newblock \emph{The Emission Delay Law: A General Principle for the Realization of Quanta in the Timeless Light Model}.
\newblock Zenodo.
\href{https://doi.org/10.5281/ZENODO.17032235}{doi:10.5281/ZENODO.17032235}.

\bibitem{McKinley2025b}
McKinley, J.~C.~W. (2025).
\newblock \emph{Generalized Pairing Law Update}.
\newblock Zenodo.
\href{https://doi.org/10.5281/ZENODO.16893165}{doi:10.5281/ZENODO.16893165}. % Retaining the primary GPL reference.

\end{thebibliography}

% ---------------- APPENDICES ----------------
\appendix

\section{Timeless Light Model - Core Ontology}
The Timeless Light Model (TLM) reclassifies photons and massless quanta as timeless causal instructions, not particles propagating through spacetime. Instructions are authored in the timeless Quantum Platform (QP) and rendered with delay in the Spacetime Deployment Frame (SDF)~\cite{tlm_consideration,absent}.

\textbf{QP:} Timeless substrate for pre-resolving emission--absorption pairs (CI-ARCs). No duration or location (\(m=0 \Rightarrow T=0\)). Causality originates here as pre-resolved pairs: emission (E) and absorption (\(A^{*}\)) form a single holistic unit~\cite{causal_chain}.

\textbf{SDF:} Observable arena where instructions are sequenced via delay (e.g., speed of light \(c\)). Temporal order appears here, with mass-induced delay stretching timeless arcs into rendered ``movies'' with proper time \(T>0\).

A CI-ARC is an instantaneous directive:
\[
\mathcal{I} = \langle x_e^\mu, x_a^\mu; \Delta p^\mu, \Delta J^{\mu\nu}, \Delta Q \rangle,
\]
carrying conserved quantities without traversal. This reclassification removes contradictions in assigning persistence to photons, compatible with radiation pressure, photoelectric effect, and Compton scattering~\cite{gpLaw,photonTimeless,emissionDelay}.

The TLM is conservative (preserves predictions) and radical (rejects photons ``existing in flight''). Einstein’s \(\Delta \tau_{\gamma} = 0\) is ontological: no carrier persists in spacetime~\cite{einstein1905}.

\section{Principle of Delayed Resolution (PDR)}
The PDR posits that physical mechanics exist to meter atemporal instructions into sequential reality for experience. Delay \(\times\) Mechanics \(=\) Observed Physics, unifying GR and QM without metaphysical entities~\cite{pdr}. PDR interprets mechanics teleologically: delay enables meaningful sequencing. Mass ties to delay, geometry modulates it, preventing paradoxes like infinite speeds or uniform clocks.

\section{Causal Chain}
The causal hierarchy: QP (prior cause) \(\rightarrow\) SDF (causal site) \(\rightarrow\) mass (delay/drag). Mass parameterizes pacing, not causes time~\cite{causal_chain}. Causality is QP-authored; SDF renders it. Mass influences delay indirectly by sourcing curvature (GR), with geometry setting deployment rate.

\section{Frame Display Law}
Once \(A^{*}\) is fixed in QP, SDF renders a causal movie using standard propagators, time-symmetric conditioning on \((E, A^{*})\), and \(c\)-limited rays along stationary-phase ridges. Pacing via bridge laws \(T \cdot m = \hbar / c^2\), \(T \cdot C_s = 1\)~\cite{frame_display}. The Pairing Axiom ensures only completed arcs are written, preserving conservation laws.

\section{Wait Phase}
Atemporal checkpoint in QP where filters (\(\psi\) eligibility, conservation) are applied. Not a delay, but rule enforcement that makes arcs writable~\cite{wait_novice}. ``Wait'' enforces quantum structure (\(\psi\)) and relativistic constraints intrinsically, preserving \(\tau=0\) for photons.

\section{Bridge Laws}
\begin{lawbox}{Mass--Delay Duality}
\label{law:delay}
\(T \cdot m = \hbar / c^{2}\): Mass induces deployment delay. For massless quanta (\(m=0\)), delay vanishes (\(T=0\)).
\end{lawbox}

\begin{lawbox}{Causal Speed}
\label{law:cs}
\(T \cdot C_s = 1\): Deployment rate \(C_s\) trades with delay. For \(T=0\), QP deployment is instantaneous, appearing as \(c\) in SDF.
\end{lawbox}
These laws encode mass--time coupling as deployment rules~\cite{Einstein1916}.

\section{Generalized Pairing Law (GPL) and Emission Delay Law (EDL)}
\begin{definition}[Paired Condition]
A paired condition is any state/process completing conservation laws with emission (e.g., electromagnetic mode for photons, final state for electrons).
\end{definition}

\begin{theorem}[Generalized Pairing Law (GPL)]
Realization of any quantum requires a compatible paired condition~\cite{McKinley2025b}.
\end{theorem}

\begin{theorem}[Emission Delay Law (EDL)]
Excited states persist until a paired condition is available, enabling QP resolution. Persistence duration in SDF is emission delay.
\end{theorem}

\section{Newtonian Holodeck Failure}
A universe without relativity collapses due to no speed limit, dilation, or curvature, leading to paradoxes and chaos. Relativity is a necessity for stability~\cite{newtonian_holodeck}. Without delay modulation, uniform clocks lead to fragility; gravity ties mass to potential for robust experience.

\section{Gravity as Delay Modulation}
Gravity modulates delay via mass--potential ties, preventing uniform-clock fragility. Reinterprets GR as pacing for meaningful experience~\cite{gravity_geometry,pdr}. Geometry sets delay; mass/energy sets geometry. Aligns with Einstein's GR without Newtonian assumptions~\cite{Einstein1916}.

\section{Quantum Gravity in TLM}
Complementary filters: \(\psi\) for eligibility (QM), \(T \cdot m = \hbar / c^{2}\) for rate (GR). Quantization from discrete frames (\(\Delta T_{\min}\)), with \(\nabla T \longleftrightarrow g_{\mu\nu}\), without gravitons. Resolves singularities by timeless QP authorship; no infinite densities in rendering.

\section{No-In-Between Lemma}
\label{sec:no-in-between}
\begin{tcolorbox}[title=\textbf{No-In-Between Lemma}]
In Lorentzian spacetime \((\mathcal{M},g)\), for a massless excitation along a null curve \(\gamma\) with \(g(\dot\gamma,\dot\gamma)=0\), proper time is zero:
\[
d\tau = \frac{1}{c}\sqrt{-g(\dot\gamma,\dot\gamma)}\, d\lambda = 0.
\]
No internal evolution between endpoints.
\end{tcolorbox}

\textbf{Proof:} For null curves, \(g(\dot\gamma,\dot\gamma)=0\), so \(\tau[\gamma]=0\). No rest frame or mid-flight state~\cite{einstein1905}.

\begin{tcolorbox}[title=\textbf{Corollary: No Mid-Flight State}]
No ``photon in flight''; only endpoint transfers are observable.
\end{tcolorbox}

\section{Predictions and Tests}
TLM predicts observable signatures of discrete rendering and delay modulation.

\begin{table}[H]
\centering
\caption{Predictions from TLM Canon}
\begin{tabular}{L{0.3\textwidth} L{0.6\textwidth}}
\toprule
\textbf{Prediction} & \textbf{Description} \\
\midrule
Entanglement Latency & \(\Delta t = GM/c^{3}\) shift in coincidence timing near massive detectors. \\
No Mid-Flight Energy & Energy balance at endpoints only; no transport store. \\
Rule-First Compliance & Interference follows authored rules without carrier dynamics. \\
Quantized Curvature & Micro-discreteness in GW phases, pulsar timing. \\
CMB Non-Gaussian Tails & Excess kurtosis vs.\ \(\Lambda\)CDM. \\
\bottomrule
\end{tabular}
\end{table}

Expanded falsifiability includes 30 tests, e.g., GW phase grain, clock redshift discreteness~\cite{wait_novice}.

\begin{sidewaystable}[p]
\centering
\begin{tabular}{L{3.7cm} L{3.2cm} L{4.1cm} L{3.7cm} L{3.1cm} L{3.0cm}}
\toprule
\textbf{Prediction} & \textbf{Formula} & \textbf{Observable} & \textbf{Instrument/Setup} & \textbf{Confounders} & \textbf{Pass/Fail} \\
\midrule
Entanglement latency near mass & \(\Delta t=\dfrac{GM}{c^{3}}\) & Arrival-time skew vs.\ mass proximity & Twin entangler; variable \(M\) near detector & Clock drift; path-length bias & Slope \(\propto GM/c^{3}\) \\
GW phase residuals (horizon-scale) & model-dependent & Phase shift vs.\ GR template & LIGO/Virgo/KAGRA & Calibration lines & Stat.\ sig.\ residuals \\
CMB non-Gaussian tails & excess kurtosis & Tail index vs.\ \(\Lambda\)CDM baseline & Planck / Simons & Foregrounds, beams & Tail parameter shift \\
\bottomrule
\end{tabular}
\caption{Predictions and falsifiability matrix for TLM v3.0.}
\label{tab:predictions}
\end{sidewaystable}

\section{Glossary - Consolidated}
\begin{table}[H]
\centering
\caption{Selected TLM Glossary}
\label{tab:glossary}
\begin{tabular}{L{0.25\textwidth} L{0.65\textwidth}}
\toprule
\textbf{Term} & \textbf{Definition} \\
\midrule
Causal Instruction Arc (CI-ARC) & The atomic, pre-resolved instruction that links an emission event \((x_e)\) to a single absorption event \((x_a)\) without traversing spacetime. \\
Quantum Platform (QP) & The timeless, extra-spatiotemporal ledger where instructions are authored and resolved. \\
Spacetime Deployment Frame (SDF) & The observable universe where instructions from the QP are rendered sequentially. Time is experienced as rendering delay. \\
Wait Phase & The atemporal checkpoint (\(T=0\)) where structural rules (\(\psi\)) and conservation laws are applied as eligibility filters to a CI-ARC before it is finalized. \\
Generalized Pairing Law (GPL) & The requirement that an emission is only writeable if a compatible absorber exists to complete the arc; prevents orphan emissions. \\
Mass--Delay Duality & The bridge law \(T \cdot m = \hbar/c^{2}\) linking mass to deployment delay \(T\). For \(m=0\), \(T=0\). \\
Absorption-Only Evidence & Experimental fact that only arrival events are observed. \\
Affine Parameter (\(\lambda\)) & Path-ordering parameter along a null geodesic with no physical evolution. \\
No Mid-Flight Energy Principle & No usable energy between endpoints. \\
\bottomrule
\end{tabular}
\end{table}

\section{Diagrams and Derivations}
\begin{figure}[H]
\centering
\begin{tikzpicture}[
    block/.style={rectangle, draw, thick, text width=5cm, text centered, rounded corners, minimum height=1cm, font=\bfseries},
    process/.style={rectangle, draw, thick, fill=green!10, text width=6cm, text centered, rounded corners, minimum height=1.5cm, font=\bfseries},
    frame/.style={rectangle, draw, thick, fill=red!10, text width=7cm, text centered, rounded corners, minimum height=1.5cm, font=\bfseries},
    arrow/.style={-Latex, very thick, >=stealth}
]
\node[block, fill=blue!10] (QP) {Quantum Platform (QP):\\ Timeless Rules Authoring};
\node[process, below=1cm of QP] (WAIT) {Wait Phase (\(T=0\)):\\ Atemporal Eligibility Filtering};
\node[frame, below=1cm of WAIT] (SDF) {Spacetime Deployment Frame (SDF):\\ Rendered Events (Time, \(c\))};
\draw [arrow] (QP) -- node[right, align=center, xshift=0.2cm] {Emit: Instruction Issued} (WAIT);
\draw [arrow] (WAIT) -- node[right, align=center, xshift=0.2cm] {Absorb: Finalization via Rules} (SDF);
\node[draw, fill=gray!20, minimum width=2.5cm, right=4.8cm of WAIT.north east, anchor=north east, yshift=-.5cm, align=left, font=\small] (QMFilter) {Quantum Filter (\(\psi\), GPL)};
\node[draw, fill=gray!20, minimum width=2.5cm, left=5cm of WAIT.north west, anchor=north west, yshift=-.5cm,  align=right, font=\small] (GRFilter) {Relativistic Filter (\(T\cdot m=\hbar/c^{2}\))};
\end{tikzpicture}
\caption{The Emit--Wait--Absorb triad: the QP authors the instruction, eligibility rules are applied during the atemporal Wait Phase, and the result deploys into the causal SDF.}
\label{fig:triad}
\end{figure}

\noindent\textbf{Null Geodesics:} \(ds^{2} = -c^{2} d\tau^{2} + dx^{2} + dy^{2} + dz^{2}\). For photons, \(ds^{2}=0 \Rightarrow d\tau=0\).\\
\textbf{No Lorentz Frame:} Velocity addition fails for \(v=c\).\\
\textbf{Mass--Delay:} \(T\cdot m=\hbar / c^{2}\).\\
\textbf{Causal Speed:} \(T\cdot C_s=1\).

\section{Falsifiability Matrix}
The following enumerates 30 expanded tests for discreteness and delay signatures:
\begin{enumerate}[leftmargin=2.5em, itemsep=6pt]
    \item \textbf{GW phase grain.} \emph{Prediction:} tiny step-like residuals in gravitational wave phases. \emph{Method:} cross-correlate multi-detector phase residuals after full waveform subtraction. \emph{Fail:} residuals remain fully Gaussian and scale as pure noise under increasing sensitivity.
    \item \textbf{GW amplitude grain.} \emph{Prediction:} micro-jitter in amplitude envelopes. \emph{Method:} envelope demodulation and Allan deviation vs.\ SNR. \emph{Fail:} no deviation from smooth predictions beyond instrument noise.
    \item \textbf{Pulsar timing steps.} \emph{Prediction:} non-Gaussian micro-steps in PTA residuals. \emph{Method:} heavy-tail tests on timing residuals. \emph{Fail:} residuals consistent with known noise models.
    \item \textbf{Lunar laser ranging staircases.} \emph{Prediction:} quantized micro-delays in round-trip time beyond modeled systematics. \emph{Method:} histogram tests of time-transfer bins. \emph{Fail:} null after improved calibration.
    \item \textbf{Clock redshift discreteness.} \emph{Prediction:} height-dependent redshift shows tiny steps at cm scale. \emph{Method:} optical lattice clocks on a precision elevator. \emph{Fail:} purely smooth redshift within error.
    \item \textbf{Shapiro micro-steps.} \emph{Prediction:} step-like structure in solar conjunction delays. \emph{Method:} radio links during occultations. \emph{Fail:} smooth GR delay only.
    \item \textbf{GPS staircase artifacts.} \emph{Prediction:} step signatures in space-to-ground time transfer after removing known effects. \emph{Method:} reanalysis of precise time series. \emph{Fail:} no steps beyond instrument artifacts.
    \item \textbf{Fiber time-transfer grain.} \emph{Prediction:} micro-steps over stabilized fiber links. \emph{Method:} two-way time transfer at sub-ps. \emph{Fail:} no structure beyond thermal and servo noise.
    \item \textbf{Optical cavity residuals.} \emph{Prediction:} quantized phase noise plateaus after subtraction. \emph{Method:} Pound--Drever--Hall residual analysis. \emph{Fail:} residuals track thermal noise only.
    \item \textbf{Atom interferometer steps.} \emph{Prediction:} interferometric phase increments discretize with controlled \(g\) steps. \emph{Method:} drop-tower experiments. \emph{Fail:} smooth dependence only.
    \item \textbf{Quantum Rabi staircasing.} \emph{Prediction:} micro-staircases in high-bandwidth Rabi traces. \emph{Method:} superconducting qubits with GHz readout. \emph{Fail:} continuous curves within noise.
    \item \textbf{QRNG spectrum tails.} \emph{Prediction:} specific non-Gaussian tails in QRNG bitstreams. \emph{Method:} high-order statistics and compression tests. \emph{Fail:} perfect i.i.d.\ within tests.
    \item \textbf{GRB spectral-lag bounds.} \emph{Prediction:} no energy-dependent photon delay from propagation; lags are source-internal. \emph{Method:} multi-band GRB timing. \emph{Fail:} robust propagation lags.
    \item \textbf{TeV photon dispersion.} \emph{Prediction:} no vacuum dispersion. \emph{Method:} gamma-ray flares time-of-flight. \emph{Fail:} energy-dependent arrival times after source modeling.
    \item \textbf{Photon mass null.} \emph{Prediction:} consistent with zero photon mass within tighter bounds. \emph{Method:} magnetic field curl tests, astrophysical limits. \emph{Fail:} nonzero mass detection.
    \item \textbf{Neutrino vs.\ photon simultaneity.} \emph{Prediction:} no superluminal anomalies; timing matches standard expectations. \emph{Method:} multi-messenger timing. \emph{Fail:} repeatable anomalies implying propagation beyond framing.
    \item \textbf{Binary pulsar periastron steps.} \emph{Prediction:} micro-steps in post-Keplerian timing. \emph{Method:} residual change-point detection. \emph{Fail:} none beyond modeled processes.
    \item \textbf{Weak lensing shear grain.} \emph{Prediction:} tiny granularity in shear maps after PSF removal. \emph{Method:} shear 2-point residual analysis. \emph{Fail:} smooth residuals only.
    \item \textbf{CMB high-\(\ell\) tails.} \emph{Prediction:} slight heavy-tailed residuals after lensing and foregrounds. \emph{Method:} kurtosis of cleaned maps. \emph{Fail:} purely Gaussian.
    \item \textbf{Redshift-drift steps.} \emph{Prediction:} pixelized drift increments in decades-long monitoring. \emph{Method:} ELT spectrographs. \emph{Fail:} perfectly smooth drift.
    \item \textbf{Lyman-alpha micro-quantization.} \emph{Prediction:} subtle quantization in line-of-sight velocity fields. \emph{Method:} forest clustering residuals. \emph{Fail:} smooth statistics only.
    \item \textbf{EHT shadow micro-variability.} \emph{Prediction:} step-like short-timescale features. \emph{Method:} closure-phase change points. \emph{Fail:} no steps beyond turbulence.
    \item \textbf{Laboratory delayed-choice invariance.} \emph{Prediction:} frame reordering leaves outcomes invariant within TLM ranges. \emph{Method:} moving-detector delayed-choice tests. \emph{Fail:} reproducible frame-order effects.
    \item \textbf{Entanglement loophole squeeze.} \emph{Prediction:} no finite-speed signaling; correlations remain frame-robust. \emph{Method:} cosmic-setting Bell tests. \emph{Fail:} parameter-dependent signaling.
    \item \textbf{Synchrotron dispersion null.} \emph{Prediction:} no propagation dispersion in vacuum. \emph{Method:} storage-ring time-of-flight. \emph{Fail:} energy-dependent delays.
    \item \textbf{Cavity ring-down grain.} \emph{Prediction:} step-like decay residuals at extreme finesse. \emph{Method:} ring-down residual tests. \emph{Fail:} purely exponential.
    \item \textbf{Atom-clock transport steps.} \emph{Prediction:} micro-steps when clocks cross potential gradients. \emph{Method:} portable optical clocks on graded towers. \emph{Fail:} smooth predictions only.
    \item \textbf{VLBI delay grain.} \emph{Prediction:} micro-steps in group delay after troposphere/ionosphere removal. \emph{Method:} geodetic VLBI residuals. \emph{Fail:} null.
    \item \textbf{Occultation Fresnel steps.} \emph{Prediction:} step-like residuals in stellar occultation fringes. \emph{Method:} high-speed photometry. \emph{Fail:} smooth Fresnel curves.
    \item \textbf{Digital twin falsifier.} \emph{Prediction:} a purely smooth digital twin cannot match measured heavy tails without ad hoc noise. \emph{Method:} simulation-to-measurement residual tests. \emph{Fail:} smooth twin matches without extra parameters.
\end{enumerate}


\section{Complete List of Authored and Related Works (John Christian William McKinley)}
\begin{enumerate}
    \item The Wait Phase and Interference: Timeless Rules Creating Quantum Patterns (2025-10-18, DOI: \href{https://doi.org/10.5281/ZENODO.17383869}{10.5281/ZENODO.17383869})
    \item Archival PDF preserves viewer comments from the YouTube Short "Unmanned - Helicity Fixation" by John C. W. McKinley (Diagonal Studios). Comments posted by users recklesswhisper and gilsonsanguluaniphiri5018. (2025-10-12, DOI: \href{https://doi.org/10.5281/ZENODO.17336373}{10.5281/ZENODO.17336373})
    \item joeythestyle tiktok comment 10 12 25 (2025-10-12, DOI: \href{https://doi.org/10.5281/ZENODO.17337812}{10.5281/ZENODO.17337812})
    \item Redefining Zero: The Extra-Universal State and the Timeless Light Model (2025-10-12, DOI: \href{https://doi.org/10.5281/ZENODO.17336219}{10.5281/ZENODO.17336219})
    \item Time-Free Photons and Extra-Universal Nothingness: Addressing Speed and Existence Queries in the Timeless Light Model (2025-10-12, DOI: \href{https://doi.org/10.5281/ZENODO.17337263}{10.5281/ZENODO.17337263})
    \item YouTube comment from @kevinfraser7869 - Archival Material - video name "Photon 4.0" posted 7/17/25 (2025-10-12, DOI: \href{https://doi.org/10.5281/ZENODO.17335674}{10.5281/ZENODO.17335674})
    \item The Unmanned Quantum Platform: Timeless Origin of Instruction and Conservation in the TLM (2025-10-11, DOI: \href{https://doi.org/10.5281/ZENODO.17329404}{10.5281/ZENODO.17329404})
    \item The Wait Phase and Creator-Law Framework in the Timeless Light Model (TLM v3.0) (2025-10-07, DOI: \href{https://doi.org/10.5281/ZENODO.17284109}{10.5281/ZENODO.17284109})
    \item The Wait Phase in the Timeless Light Model (TLM v3.0): Explaining a Timeless Checkpoint for Novices and Experts (2025-10-07, DOI: \href{https://doi.org/10.5281/ZENODO.17291452}{10.5281/ZENODO.17291452})
    \item Absorption-Only Evidence: Photons and Causal Instructions Exist Outside Spacetime (2025-10-05, DOI: \href{https://doi.org/10.5281/ZENODO.17275105}{10.5281/ZENODO.17275105})
    \item Comment Archive: "Does a Photon Know It Travels?" — Transcript of YouTube Short (hBDI0LFVxF0) (2025-10-05, DOI: \href{https://doi.org/10.5281/ZENODO.17274572}{10.5281/ZENODO.17274572})
    \item No In-Between: Photon Knowledge and Energy Transfer in the Timeless Light Model (2025-10-05, DOI: \href{https://doi.org/10.5281/ZENODO.17274555}{10.5281/ZENODO.17274555})
    \item What Crosses the Cosmos? Timeless Photon Instructions vs. Traveling Particles (2025-10-01, DOI: \href{https://doi.org/10.5281/ZENODO.17247906}{10.5281/ZENODO.17247906})
    \item Bridge Laws in the Timeless Light Model From Timeless Instructions to Rendered Spacetime (2025-09-30, DOI: \href{https://doi.org/10.5281/ZENODO.17240091}{10.5281/ZENODO.17240091})
    \item Whose Frame is it Anyway? - On Photon Timelessness, Proper Time, and the Observer's Illusion (2025-09-30, DOI: \href{https://doi.org/10.5281/ZENODO.17239624}{10.5281/ZENODO.17239624})
    \item Photon as Instruction, Not Traveler: Emission, Absorption, and the Myth of Flight (2025-09-28, DOI: \href{https://doi.org/10.5281/ZENODO.17221119}{10.5281/ZENODO.17221119})
    \item Photon Thought Experiments and the Timeless Ontology: Why Photons and Quanta Are "Not Here" (2025-09-27, DOI: \href{https://doi.org/10.5281/ZENODO.17216652}{10.5281/ZENODO.17216652})
    \item Why It Matters if a Marble Arrives Before Its Light: Causality and the Fragility of a Lawful Universe (2025-09-26, DOI: \href{https://doi.org/10.5281/ZENODO.17205431}{10.5281/ZENODO.17205431})
    \item Gravity is Geometry. Reality Obeys Rules. Not the Newtonian Holodeck. (2025-09-25, DOI: \href{https://doi.org/10.5281/ZENODO.17197557}{10.5281/ZENODO.17197557})
    \item Photon Proper Time: The Understated Invariant of Special Relativity (2025-09-24, DOI: \href{https://doi.org/10.5281/ZENODO.17190047}{10.5281/ZENODO.17190047})
    \item Massless Things Do Not Experience Time (2025-09-22, DOI: \href{https://doi.org/10.5281/ZENODO.17173126}{10.5281/ZENODO.17173126})
    \item If the Quantum Platform Is a Math Layer: An Interpretive Addendum to the Timeless Light Model (2025-09-21, DOI: \href{https://doi.org/10.5281/ZENODO.17169440}{10.5281/ZENODO.17169440})
    \item Space Will Collapse to Protect $c$ (2025-09-20, DOI: \href{https://doi.org/10.5281/ZENODO.17164585}{10.5281/ZENODO.17164585})
    \item Causal Chain in the Timeless Light Model: Mass as Drag, Frame as Causal Site, Quantum Platform as Cause (2025-09-16, DOI: \href{https://doi.org/10.5281/ZENODO.17139863}{10.5281/ZENODO.17139863})
    \item Time Travel is Real: Forwards But Not Backwards (2025-09-16, DOI: \href{https://doi.org/10.5281/ZENODO.17140029}{10.5281/ZENODO.17140029})
    \item Unlimited Rocket Acceleration and Time Travel to the Future (2025-09-16, DOI: \href{https://doi.org/10.5281/ZENODO.17139392}{10.5281/ZENODO.17139392})
    \item Why the Timeless Light Model is Not Obviously False (2025-09-15, DOI: \href{https://doi.org/10.5281/ZENODO.17118184}{10.5281/ZENODO.17118184})
    \item Rules and Executions: Mathematics as Perfect Code, Physics as Finite Information (2025-09-14, DOI: \href{https://doi.org/10.5281/ZENODO.17115196}{10.5281/ZENODO.17115196})
    \item Delay-Engineered Maneuverability: A Timeless Light Model Interpretation of "Tic Tac" UAP Kinematics (2025-09-12, DOI: \href{https://doi.org/10.5281/ZENODO.17111402}{10.5281/ZENODO.17111402})
    \item Why Rockets Can't Go Faster Than Light (2025-09-09, DOI: \href{https://doi.org/10.5281/ZENODO.17083607}{10.5281/ZENODO.17083607})
    \item Illusion and Invariant: Making Sense of Time Dilation, Reciprocity, Simultaneity, and Proper Time (2025-09-08, DOI: \href{https://doi.org/10.5281/ZENODO.17083276}{10.5281/ZENODO.17083276})
    \item Mass Slows Time. Speed Slows Time. Concept, Derivations, and Evidence (2025-09-08, DOI: \href{https://doi.org/10.5281/ZENODO.17083288}{10.5281/ZENODO.17083288})
    \item Hilbert Space as Frame Representation: A Timeless Light Model Reinterpretation (2025-09-06, DOI: \href{https://doi.org/10.5281/ZENODO.17070118}{10.5281/ZENODO.17070118})
    \item From Descriptive Laws to Falsifiable Predictions: Testing the Timeless Light Model (2025-09-01, DOI: \href{https://doi.org/10.5281/ZENODO.17017852}{10.5281/ZENODO.17017852})
    \item Handling Event Magnitude in the Timeless Light Model: A Minimal QP$\rightarrow$SDF Instruction Interface (2025-09-01, DOI: \href{https://doi.org/10.5281/ZENODO.17033795}{10.5281/ZENODO.17033795})
    \item The "No Mid-Flight Energy" Principle: Operational Consistency and Ontological Implications for the Timeless Light Model (TLM) (2025-09-01, DOI: \href{https://doi.org/10.5281/ZENODO.17018871}{10.5281/ZENODO.17018871})
    \item The Emission Delay Law: A General Principle for the Realization of Quanta in the Timeless Light Model (2025-09-01, DOI: \href{https://doi.org/10.5281/ZENODO.17032235}{10.5281/ZENODO.17032235})
    \item Dark Energy as Expansion Within GR: A Timeless Light Model Statement (2025-08-30, DOI: \href{https://doi.org/10.5281/ZENODO.17010816}{10.5281/ZENODO.17010816})
    \item Minimum Frame Size: Discrete Deployment Limits in the Timeless Light Model (2025-08-30, DOI: \href{https://doi.org/10.5281/ZENODO.17009716}{10.5281/ZENODO.17009716})
    \item Photons Not in the Universe: An Axiomatic Derivation from Masslessness and Non-Travel (2025-08-30, DOI: \href{https://doi.org/10.5281/ZENODO.17010029}{10.5281/ZENODO.17010029})
    \item TikTok Comment Archive: @michael40000 on Photon Travel and Masslessness (2025-08-30, DOI: \href{https://doi.org/10.5281/ZENODO.17009839}{10.5281/ZENODO.17009839})
    \item Mathematical Shadows of the Quantum Platform: From Trick to Ontology (2025-08-27, DOI: \href{https://doi.org/10.5281/ZENODO.16977344}{10.5281/ZENODO.16977344})
    \item A Review of the Timeless Light Model: Foundations, Derivations, and Empirical Predictions (2025-08-26, DOI: \href{https://doi.org/10.5281/ZENODO.16958221}{10.5281/ZENODO.16958221})
    \item Test Menu for the Timeless Light Model (TLM) (2025-08-26, DOI: \href{https://doi.org/10.5281/ZENODO.16957884}{10.5281/ZENODO.16957884})
    \item Frame Display Law for TLM v2.0: EA-conditioned Rendering in a Single Spacetime Deployment Frame (2025-08-24, DOI: \href{https://doi.org/10.5281/ZENODO.16936105}{10.5281/ZENODO.16936105})
    \item Ontology of Matter in the Timeless Light Model: From FRAME–CHARGE Toggles to Particles (2025-08-24, DOI: \href{https://doi.org/10.5281/ZENODO.16939101}{10.5281/ZENODO.16939101})
    \item Timeless Light Model (TLM v2.0): Frameless Quanta, Framed Observers, and Bridge Laws (2025-08-23, DOI: \href{https://doi.org/10.5281/ZENODO.16934697}{10.5281/ZENODO.16934697})
    \item Timeless Light Model vs Wheeler–Feynman Absorber Theory: A Disambiguation (2025-08-22, DOI: \href{https://doi.org/10.5281/ZENODO.16924316}{10.5281/ZENODO.16924316})
    \item Quanta are Global, Frames are Local: A Rosetta Statement of the Timeless Light Model (2025-08-21, DOI: \href{https://doi.org/10.5281/ZENODO.16917106}{10.5281/ZENODO.16917106})
    \item The Binary Law of Quanta: Location as a Timeless Choice (2025-08-20, DOI: \href{https://doi.org/10.5281/ZENODO.16913425}{10.5281/ZENODO.16913425})
    \item TLM Addendum: Minimal Formalism and a Decisive Null Test (2025-08-20, DOI: \href{https://doi.org/10.5281/ZENODO.16909382}{10.5281/ZENODO.16909382})
    \item Two Decrees for a Rendered Universe: Charge and Frame-in-Higgs as Sufficient Generators of the Standard Model within the Timeless Light Model (2025-08-20, DOI: \href{https://doi.org/10.5281/ZENODO.16914685}{10.5281/ZENODO.16914685})
    \item Unified Quantization Principle: GR, SR, and QM as Quantized Deployments of Binary Quanta (2025-08-20, DOI: \href{https://doi.org/10.5281/ZENODO.16913967}{10.5281/ZENODO.16913967})
    \item Generalized Pairing Law: No Quantum Emission Without an Absorber (2025-08-18, DOI: \href{https://doi.org/10.5281/ZENODO.16893165}{10.5281/ZENODO.16893165})
    \item The Quanta Transfer Law (2025-08-18, DOI: \href{https://doi.org/10.5281/ZENODO.16897573}{10.5281/ZENODO.16897573})
    \item The One Blind Spot That Hid Three Simple Solutions: A Testable Reinterpretation of Photon Ontology Outside Spacetime (2025-08-14, DOI: \href{https://doi.org/10.5281/ZENODO.16871293}{10.5281/ZENODO.16871293})
    \item Mass as Delay: Rethinking the Universe’s Clockwork (2025-08-12, DOI: \href{https://doi.org/10.5281/ZENODO.16908749}{10.5281/ZENODO.16908749})
    \item From Endpoint Pairing to Frame Splitting: Absorption-Frame Motion in the Timeless Light Framework (2025-08-10, DOI: \href{https://doi.org/10.5281/ZENODO.16791636}{10.5281/ZENODO.16791636})
    \item Gravitons as Quantum Platform Geometry Instructions: A Timeless-Light Interpretation of Gravitational Wave Quanta (2025-08-10, DOI: \href{https://doi.org/10.5281/ZENODO.16788039}{10.5281/ZENODO.16788039})
    \item The Quantum Platform as Frame Generator: Ontology, Anatomy, and Dark Matter Implications in TLM (2025-08-10, DOI: \href{https://doi.org/10.5281/ZENODO.16788735}{10.5281/ZENODO.16788735})
    \item The Frame as Master: A Unified Foundation for the Timeless Light Model (2025-08-09, DOI: \href{https://doi.org/10.5281/ZENODO.16787219}{10.5281/ZENODO.16787219})
    \item At Some Point, You Have to Make Room for a Creator of the Universe—Whether It Be God, Gods, or Unicorn Dreams (2025-08-07, DOI: \href{https://doi.org/10.5281/ZENODO.16757589}{10.5281/ZENODO.16757589})
    \item Frame Pair Stretch and the ZeroSpace Postulate in the Timeless Light Model (2025-08-07, DOI: \href{https://doi.org/10.5281/ZENODO.16777862}{10.5281/ZENODO.16777862})
    \item Why Rockets Can’t Go Faster Than Light (2025-08-07, DOI: \href{https://doi.org/10.5281/ZENODO.16758093}{10.5281/ZENODO.16758093})
    \item The Failure of the Newtonian Holodeck: Why a Universe Without Relativity Cannot Sustain Itself (2025-08-05, DOI: \href{https://doi.org/10.5281/ZENODO.16750632}{10.5281/ZENODO.16750632})
    \item The Photon as a Timeless, Spaceless Energy Transfer (2025-08-04, DOI: \href{https://doi.org/10.5281/ZENODO.16735683}{10.5281/ZENODO.16735683})
    \item A Falsifiable Prediction of Non-Gaussian Tails in the CMB from Timeless Quantum Physics (2025-08-03, DOI: \href{https://doi.org/10.5281/ZENODO.16730256}{10.5281/ZENODO.16730256})
    \item Falsifiable Prediction of Horizon-Scale Phase Shifts in Gravitational Waves from the Timeless Light Model (2025-08-03, DOI: \href{https://doi.org/10.5281/ZENODO.16730926}{10.5281/ZENODO.16730926})
    \item Why the Timeless Light Model Deserves Scientific Consideration: A Foundational Framework with Derivations, Critiques, and Experimental Proposals (2025-08-02, DOI: \href{https://doi.org/10.5281/ZENODO.16724187}{10.5281/ZENODO.16724187})
    \item Mass Imposes Delay, Wavefunctions Define Terrain: A Two-Filter Ontology of Reality (2025-08-01, DOI: \href{https://doi.org/10.5281/ZENODO.16672398}{10.5281/ZENODO.16672398})
    \item No Carrier Needed: Photon Instructions as Direct Energy State Transfers Without Propagation (2025-08-01, DOI: \href{https://doi.org/10.5281/ZENODO.16666652}{10.5281/ZENODO.16666652})
    \item Light as Absent: Reclassifying the Photon as a Timeless Instruction (2025-07-31, DOI: \href{https://doi.org/10.5281/ZENODO.16627550}{10.5281/ZENODO.16627550})
    \item Deriving Cornerstone Equations from TLM Axioms: Entropic Bridges to GR and QM (2025-07-30, DOI: \href{https://doi.org/10.5281/ZENODO.16596589}{10.5281/ZENODO.16596589})
    \item Resolving Wave-Particle Duality Through the Proposed Timeless Light Model: Photons as Timeless Instructions and Waves as Deployed Delay (2025-07-28, DOI: \href{https://doi.org/10.5281/ZENODO.16510862}{10.5281/ZENODO.16510862})
    \item Photon Out of Time: Why Light Experiences No Time—and What That Means for Physics (2025-07-27, DOI: \href{https://doi.org/10.5281/ZENODO.16479322}{10.5281/ZENODO.16479322})
    \item Spacelessness as a Consequence of Timelessness in the Quantum Platform of the Timeless Light Model (2025-07-23, DOI: \href{https://doi.org/10.5281/ZENODO.16350754}{10.5281/ZENODO.16350754})
    \item Stop Pretending General Relativity Is Conservative: Why Timeless Models Deserve a Seat at the Table (2025-07-21, DOI: \href{https://doi.org/10.5281/ZENODO.16261059}{10.5281/ZENODO.16261059})
    \item Foundational Equations and Axiomatic Structure of the Timeless Light Model: A Synthesis Across Sixty Papers and Working Notes (2025-07-20, DOI: \href{https://doi.org/10.5281/ZENODO.16187719}{10.5281/ZENODO.16187719})
    \item The Photon’s Exile: A GR-Based Proof That Light Is Not in Spacetime (2025-07-18, DOI: \href{https://doi.org/10.5281/ZENODO.16076902}{10.5281/ZENODO.16076902})
    \item Unified Physics by Subordination of GR to QM: Version 4.0 – Instructional Photons and Causal Rendering (2025-07-17, DOI: \href{https://doi.org/10.5281/ZENODO.16019797}{10.5281/ZENODO.16019797})
    \item Quantum Platform as Causal Senior: General Relativity as Rendered Projection (2025-07-16, DOI: \href{https://doi.org/10.5281/ZENODO.15960343}{10.5281/ZENODO.15960343})
    \item Unified Physics by Subordination of GR to QM: A Layered Reality Framework (2025-07-16, DOI: \href{https://doi.org/10.5281/ZENODO.15956986}{10.5281/ZENODO.15956986})
    \item Unified Physics by Subordination of GR to QM: Quantum Phenomena as the Generator of the Classical Universe (2025-07-12, DOI: \href{https://doi.org/10.5281/ZENODO.15868624}{10.5281/ZENODO.15868624})
    \item Causality Without Light Speed: Reframing $c$ as Structure, Not Law (2025-07-07, DOI: \href{https://doi.org/10.5281/ZENODO.15826480}{10.5281/ZENODO.15826480})
    \item Clarifying $C_s$: Deployment Rate, Delay, and Simulation Parameters in the Timeless Light Model (2025-07-06, DOI: \href{https://doi.org/10.5281/ZENODO.15817350}{10.5281/ZENODO.15817350})
    \item Causal Instruction Arcs and the Timeless Light Model: A Unified Framework for Physics and Cosmology (2025-07-05, DOI: \href{https://doi.org/10.5281/ZENODO.15813253}{10.5281/ZENODO.15813253})
    \item Gravitational Waves as Synchronization Events: A Testable Prediction from the Timeless Light Model (2025-06-29, DOI: \href{https://doi.org/10.5281/ZENODO.15770287}{10.5281/ZENODO.15770287})
    \item Observer-Dependent Spacetime Collapse as a Relational Artifact of the Spacetime Deployment Frame (2025-06-29, DOI: \href{https://doi.org/10.5281/ZENODO.15770329}{10.5281/ZENODO.15770329})
    \item On a Postulated Mass-Time Action Principle: A Novel Approach to Quantum Gravity (2025-06-29, DOI: \href{https://doi.org/10.5281/ZENODO.15770207}{10.5281/ZENODO.15770207})
    \item The Mass-Time Invariant: A Causal Reinterpretation of Relativistic Spacetime Conservation Laws (2025-06-29, DOI: \href{https://doi.org/10.5281/ZENODO.15769918}{10.5281/ZENODO.15769918})
    \item The Principle of Delayed Resolution: A Teleological Framework for Unifying Physical Mechanics (2025-06-26, DOI: \href{https://doi.org/10.2139/ssrn.5310483}{10.2139/ssrn.5310483})
    \item Timeless Causality and Instruction Delay: A Unified Field Framework from Photon Instructions to Spacetime Geometry (2025-06-13, working paper, no DOI listed)
\end{enumerate}



\FloatBarrier
\end{document}


```

</details>

---
{% endraw %}
