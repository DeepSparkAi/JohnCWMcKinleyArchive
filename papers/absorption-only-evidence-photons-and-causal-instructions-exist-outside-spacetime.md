---
layout: default
title: '[2025] Absorption-Only Evidence: Photons and Causal Instructions Exist Outside Spacetime'
description: 'Publication metadata and archived raw LaTeX source by John C. W. McKinley.'
permalink: /papers/absorption-only-evidence-photons-and-causal-instructions-exist-outside-spacetime/
paper: true
---
{% raw %}
# [2025] Absorption-Only Evidence: Photons and Causal Instructions Exist Outside Spacetime
*   **DOI:** [10.5281/zenodo.17275105](https://doi.org/10.5281/zenodo.17275105)
*   **Date:** 5 October 2025

<details markdown="1">
<summary><b>Click to view Raw LaTeX Source</b></summary>

```latex
\documentclass[12pt,onecolumn]{article}

% ---------- Encoding & Fonts ----------
\usepackage[utf8]{inputenc}
\usepackage[T1]{fontenc}
\usepackage{lmodern}
\usepackage{setspace}
\setstretch{1.12}
\usepackage{microtype}
\usepackage{rotating}

% ---------- Page & Layout ----------
\usepackage[margin=1in]{geometry}

% ---------- Math ----------
\usepackage{amsmath,amssymb,amsthm}

% ---------- Figures ----------
\usepackage{tikz}
\usetikzlibrary{arrows.meta, positioning, calc, shapes.geometric}
\usepackage{graphicx}
\usepackage{booktabs}
\usepackage{float}

% ---------- Links & References ----------
\usepackage{hyperref}
\hypersetup{colorlinks=true, linkcolor=blue, urlcolor=blue, citecolor=blue}
\usepackage{cleveref}

% ---------- Headers ----------
\usepackage{fancyhdr}
\pagestyle{fancy}
\fancyhf{}
\lhead{Absorption-Only Evidence: Photons Outside Spacetime}
\rhead{\thepage}

% ---------- ORCID ----------
\usepackage{orcidlink}

% ---------- Title ----------
\title{\textbf{Absorption-Only Evidence: Photons and Causal Instructions Exist Outside Spacetime}}
\author{John C. W. McKinley\,\orcidlink{0009-0005-7097-5035}\\Independent Researcher}
\date{October 05, 2025}

\begin{document}
\maketitle

\begingroup
  \footnotetext[0]{This version published at
  \href{https://doi.org/10.5281/zenodo.17275105}{https://doi.org/10.5281/zenodo.17275105}.}
\endgroup

\begin{abstract}
We never observe a photon in flight—only absorption events.  
This paper formalizes that statement within the Timeless Light Model (TLM), showing that both photons and the \emph{causal instructions (CI-ARCs)} that resolve them exist outside spacetime.  
What appears as ``light traveling'' is merely the sequential rendering of pre-authored quantum instructions linking two energy states.  
Observable reality, therefore, consists solely of \emph{absorption-state transitions}, which are the rendered results of timeless instructions, delayed and filtered by spacetime geometry.  
In accessible terms: everything you have ever seen was an absorption, not a photon in flight.  
\end{abstract}

\section{Introduction}
Classical intuition teaches that photons traverse space like baseballs between emitter and detector.  
Yet every empirical record—from photodiodes to telescopes—documents only the \emph{absorption} \cite{wheelerFeynman}.  
No instrument has ever measured a photon mid-path without collapsing its endpoints.  
This paper argues that what exists in the universe are energy states and their transitions, not the carrier itself.  

We reinterpret quantum emission and absorption as the endpoints of a single timeless instruction authored on the Quantum Platform (QP).  
Spacetime merely deploys this instruction with a delay governed by the mass–delay law \(T \cdot m = \hbar / c^{2}\).  
The photon, having \(m=0\), experiences no delay (\(T=0\)) and therefore does not reside within the Spacetime Deployment Frame (SDF).  
The \textbf{SDF} provides the observable, time-delayed experience of these instructions.  
In short, photons and instructions are \emph{not in the universe \cite{photonTimeless, tlmConsideration}}—only their rendered results are.

\section{Theoretical Framework}

\subsection{Instruction Tuple and Null Deployment}
The TLM describes each realized quantum as an instruction tuple:
\[
I = \langle x_e^{\mu}, x_a^{\mu}; \Delta p^{\mu}, \Delta J^{\mu\nu}, \Delta Q \rangle ,
\]
where \(x_e^{\mu}\) and \(x_a^{\mu}\) are the emitter and absorber coordinates within the SDF, and the transfer quantities (\(\Delta p^{\mu}\), \(\Delta J^{\mu\nu}\), \(\Delta Q\)) encode momentum, angular momentum, and gauge exchange.

For a photon, the net four-momentum transfer is null (\(\Delta p^{\mu}\Delta p_{\mu} = 0\)), implying a null spacetime interval (\(ds^{2}=0\)) and zero proper time (\(d\tau = 0\)):
\[
\Delta p^{\mu}\Delta p_{\mu} = 0 \quad \Rightarrow \quad ds^{2}=0 \quad \Rightarrow \quad d\tau = 0 .
\]
Hence the instruction has no proper-time interval.  
The emission–absorption pair is a single causal resolution, written timelessly on the QP.

\subsection{Affine Parameter and Absence of Evolution}
\label{sec:affine}
To parameterize null paths without invoking proper time, we define an affine parameter \( \lambda \) satisfying
\[
\frac{d x^{\mu}}{d \lambda} k_{\mu} = 0, \qquad \frac{d k^{\mu}}{d \lambda} = 0,
\]
for the null geodesic tangent \( k^{\mu} \).  
Because \( d\tau = 0 \), \( \lambda \) provides ordering but no evolution.  
The photon’s worldline has no internal clock; its intermediate points are coordinate projections, not physical states.  
In TLM language, this reaffirms that the ``instruction''—like \( \lambda \)—marks logical sequence without temporal experience.

\subsection{Mass–Delay Law and Emission Delay Law}
The bridge between QP and SDF is given by
\[
T \cdot m = \frac{\hbar}{c^{2}}, \qquad T \cdot C_{s} = 1,
\]
where \(T\) is rendering delay and \(C_{s}\) is causal speed.  
Mass introduces delay; delay manifests as time.  
Massless instructions (\(m=0\)) deploy instantaneously (\(T=0\)), meaning they cannot appear as persisting entities within the SDF.  

An excited state persists until an absorber condition exists, consistent with the \emph{Emission Delay Law}—no emission without a compatible absorber \cite{emissionDelay, pairingLaw}.  
Observable “emission” is therefore a delayed appearance of the completed instruction.

\section{Derivation: Absorption-Only Visibility}
Let \(E_{1}\) and \(E_{2}\) denote electron energy states in the emitter, and \(E'_{1}, E'_{2}\) the corresponding states in the absorber.  
Conservation demands
\[
E_{2}-E_{1} = E'_{2}-E'_{1} = \hbar \omega .
\]
Within the QP, this equality is authored instantaneously.  
Within the SDF, the two energy transitions appear separated by a light-travel delay \(\Delta t = \frac{|\Delta x|}{c}\).

However, since the photon has \(d\tau=0\), there exists no intermediate evolving system satisfying both energy conservation and spacetime embedment.  
As discussed in \cref{sec:affine}, the affine parameter \( \lambda \) may label hypothetical points along a null geodesic, but it contributes no temporal accumulation or state change:
\[
\frac{d E}{d \lambda} = 0, \qquad \frac{d J^{\mu\nu}}{d \lambda} = 0.
\]
Therefore, all “in-flight” energy is bookkeeping, not ontology.  
The universe records only the absorber’s state change.



\begin{sidewaysfigure}
\centering
\begin{tikzpicture}[>=Latex, node distance=3cm]
  \node[circle,draw,minimum size=1cm,fill=blue!10,label=below:Emitter]{};
  \node[circle,draw,minimum size=1cm,fill=red!10,right=6cm of current bounding box.north east,anchor=north west,label=below:Absorber]{};
  \draw[dashed, thick, gray, bend left=15] (0,0) to node[above,sloped]{Instruction Arc $(m=0,\; T=0,\; d\tau=0)$} (6,0);
  \draw[->,thick,blue!60] (0,-1.2)--(0,-2) node[midway,left]{Electron drops};
  \draw[->,thick,red!60] (6,-2)--(6,-1.2) node[midway,right]{Electron rises};
  \node[below=2.4cm of current bounding box.south,align=center]{\textbf{Figure 1.} The photon is not a traveler. Only absorber and emitter transitions occur in spacetime.};
\end{tikzpicture}
\end{sidewaysfigure}


\begin{sidewaystable}
\centering
\begin{minipage}{\textwidth}
\caption{TLM predictions relevant to absorption-only interpretation.}
\vspace{1cm}
\small
\renewcommand{\arraystretch}{1.2}
\begin{tabular}{@{}lll@{}}
\toprule
\textbf{Prediction} & \textbf{Observable Signature} & \textbf{Null (Standard) Expectation} \\
\midrule
Emission delay vs absorber availability & Delayed fluorescence tied to detector mass & No dependence on absorber \\
No mid-flight energy extraction & No measurable intermediate photon energy & Possible transient fields \\
Entanglement latency & Coincidence offset $\Delta t \sim GM_{\text{det}}/c^{3}$ & $\Delta t = 0$ (assuming simultaneous measurement) \\
Phase-locked absorption pairs & Synchronous state flips over distance & Decoherence with distance \\
\bottomrule
\end{tabular}
\end{minipage}
\end{sidewaystable}

\section{Discussion}
The reinterpretation removes the need for “traveling photons” within spacetime.  
All light phenomena—interference, diffraction, polarization—emerge from correlations between endpoint instructions deployed through geometric delay filters.  
The QP provides timeless completeness; the SDF provides sequential experience.  
This reframes optical reality as a series of rendered absorptions rather than emitted waves.

\subsection{Experimental and Theoretical Testability}
Critiques may arise that the absence of a photon-in-flight picture risks unfalsifiability.  
However, several experimental domains offer handles:
\begin{itemize}
\item \textbf{Delayed-choice and quantum eraser experiments:} The absorber’s configuration retroactively determines whether a “photon path” existed—matching TLM’s pre-authored instruction logic \cite{ma2013}, as demonstrated even with causally disconnected choice.
\item \textbf{Transient-field tests:} Searches for mid-path electromagnetic energy storage yield null results at high sensitivity, consistent with the “No Mid-Flight Energy” principle \cite{noMidFlight}.
\item \textbf{Entanglement timing asymmetries:} Sub-microsecond coincidence shifts predicted by TLM’s $\Delta t \sim GM_{\text{det}}/c^{3}$ term remain testable with current interferometer networks.
\end{itemize}
These domains collectively make the “absorption-only” claim empirical, not merely metaphysical \cite{wheelerFeynman}.

\section{Conclusion}
Only absorption events exist in the observable universe.  
Both photons and their underlying causal instructions are outside it, resolving timelessly on the Quantum Platform.  
Spacetime shows us only the delayed consequences—the rendered transitions of matter and energy states.  
In everyday language: we do not see light traveling; we see matter reacting.

\section{Summary of the Timeless Light Model (TLM)}
The TLM posits a two-layer ontology and a geometry-driven account of observable delay:

\begin{itemize}
\item \textbf{Quantum Platform (QP):} A timeless instruction layer issuing complete emission–absorption arcs (CI-ARCs). Instructions have no duration, location, or internal evolution.

\item \textbf{Spacetime Deployment Frame (SDF):} The rendered arena that presents completed instructions in a sequence. The \emph{ordering} we experience is a deployment delay determined by the spacetime geometry \(g_{\mu\nu}\) (e.g., gravitational potential and kinematics), not by “mass per se.”

\item \textbf{Geometry–Delay Principle (replaces “mass introduces delay”):}
Observable delay tracks the metric: gravitational redshift/time dilation and kinematic effects set the deployment rate. Mass/energy \emph{influences} delay only indirectly by sourcing curvature (via GR). In short: geometry sets delay; mass/energy sets geometry.

\item \textbf{Null instructions (photons):} For lightlike separations, \(ds^{2}=0 \Rightarrow d\tau=0\). There is no in-universe propagation to observe—only endpoint absorptions rendered under the causal bound \( |\Delta \mathbf{x}|/\Delta t \le c \). The appearance of “travel” is the SDF’s ordered rendering of a pre-resolved CI-ARC.

\item \textbf{Timelike matter:} Systems on timelike worldlines (\(ds^{2}>0\)) accumulate proper time. Nonzero rest mass is a \emph{marker} of timelike deployment, not the generator of delay; the delay equals the proper-time accumulation set by \(g_{\mu\nu}\) along the worldline.

\item \textbf{Structure filter (wavefunction):} The wavefunction is a static rule-set that constrains which CI-ARCs are writable (structure), but it does \emph{not} generate delay. Interference patterns reflect writability under this structure constraint, not mid-flight energy.

\item \textbf{Causal bound and deployment rate:} Observable sequencing respects the causal speed limit \(c\). Any effective “deployment rate” \(C_s\) is a shorthand for the geometry-determined ordering (no separate mass–delay law is assumed).

\item \textbf{Absorption-only evidence:} Empirically, detectors register arrivals/absorptions. TLM takes this literally: what is “in the universe” are state changes at endpoints; the photon/CI-ARC itself is not.
\end{itemize}


\section{Glossary}
\begin{description}
\item[Absorption-Only Evidence:] Experimental fact that only arrival events are observed.
\item[Affine Parameter ($\lambda$):] Path-ordering parameter along a null geodesic with no physical evolution.
\item[CI-ARC:] Causal Instruction Arc linking emission and absorption outside spacetime.
\item[Instruction:] Pre-resolved QP directive; not a spacetime process.
\item[Lightlike Interval:] Event separation satisfying $ds^{2}=0$.
\item[Null Geodesic:] Spacetime path of a massless particle where $d\tau=0$.
\item[Proper Time ($\tau$):] Time measured along a timelike worldline; zero for photons.
\item[Quantum Platform (QP):] Timeless causal source layer.
\item[Spacetime Deployment Frame (SDF):] Observable, delay-filtered projection of QP.
\item[Mass–Delay Law:] \(T \cdot m = \hbar / c^{2}\), the link between delay and mass.
\item[Emission Delay Law:] No emission occurs until absorber condition exists.
\item[No Mid-Flight Energy Principle:] No usable energy between endpoints.
\end{description}


\begin{thebibliography}{9}

\bibitem{emissionDelay}
McKinley, J. C. W. (2025). \emph{The Emission Delay Law: A General Principle for the Realization of Quanta in the Timeless Light Model}. Zenodo. \href{https://doi.org/10.5281/zenodo.17032235}{10.5281/zenodo.17032235}.

\bibitem{noMidFlight}
McKinley, J. C. W. (2025). \emph{The “No Mid-Flight Energy” Principle: Operational Consistency and Ontological Implications for the Timeless Light Model}. Zenodo. \href{https://doi.org/10.5281/zenodo.17018871}{10.5281/zenodo.17018871}.

\bibitem{pairingLaw}
McKinley, J. C. W. (2025). \emph{Generalized Pairing Law: No Quantum Emission Without an Absorber}. Zenodo. \href{https://doi.org/10.5281/zenodo.16893165}{10.5281/zenodo.16893165}.

\bibitem{photonTimeless}
McKinley, J. C. W. (2025). \emph{Photon Thought Experiments and the Timeless Ontology: Why Photons and Quanta Are “Not Here”}. Zenodo. \href{https://doi.org/10.5281/zenodo.17216652}{10.5281/zenodo.17216652}.

\bibitem{tlmConsideration}
McKinley, J. C. W. (2025). \emph{Why the Timeless Light Model Deserves Scientific Consideration: A Foundational Framework with Derivations, Critiques, and Experimental Proposals}. Zenodo. \href{https://doi.org/10.5281/zenodo.16724187}{10.5281/zenodo.16724187}.

\bibitem{wheelerFeynman}
Wheeler, J. A., \& Feynman, R. P. (1945). \emph{Interaction with the Absorber as the Mechanism of Radiation}. \emph{Reviews of Modern Physics}, 17, 157–181. \href{https://doi.org/10.1103/RevModPhys.17.157}{10.1103/RevModPhys.17.157}.

\bibitem{ma2013}
Ma, X.-S., et al. (2013). \emph{Quantum erasure with causally disconnected choice}. \emph{Proceedings of the National Academy of Sciences (USA)}, 110(4), 1221–1226. \href{https://doi.org/10.1073/pnas.1213201110}{10.1073/pnas.1213201110}.

\end{thebibliography}

\end{document}

```

</details>

---
{% endraw %}
