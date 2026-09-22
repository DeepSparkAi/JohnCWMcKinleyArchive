---
layout: default
title: '[2025] From Descriptive Laws to Falsifiable Predictions: Testing the Timeless Light Model'
description: 'Publication metadata and archived raw LaTeX source by John C. W. McKinley.'
permalink: /papers/from-descriptive-laws-to-falsifiable-predictions-testing-the-timeless-light-model/
paper: true
---
{% raw %}
# [2025] From Descriptive Laws to Falsifiable Predictions: Testing the Timeless Light Model
*   **DOI:** [10.5281/zenodo.17017852](https://doi.org/10.5281/zenodo.17017852)
*   **Date:** 1 September 2025

<details markdown="1">
<summary><b>Click to view Raw LaTeX Source</b></summary>

```latex
\documentclass[12pt,letterpaper]{article}

% ------- Packages -------
\usepackage[margin=1in]{geometry}
\usepackage[T1]{fontenc}
\usepackage[utf8]{inputenc}
\usepackage{lmodern}
\usepackage{microtype}
\usepackage{amsmath,amssymb,amsthm,mathtools}
\usepackage{enumitem}
\usepackage[most]{tcolorbox}
\tcbset{colback=gray!5,colframe=black,boxrule=0.6pt,arc=2mm}
\newtcolorbox{lawbox}[1]{breakable,title={#1},fonttitle=\bfseries}
\usepackage{hyperref}
\hypersetup{colorlinks=true,linkcolor=blue,urlcolor=blue,citecolor=blue}
\usepackage{orcidlink}
\usepackage{booktabs} % For better tables

% ------- Metadata -------
\title{From Descriptive Laws to Falsifiable Predictions: \\
Testing the Timeless Light Model}
\author{John C. W. McKinley\orcidlink{0009-0005-7097-5035}\\Independent Researcher}
\date{September 1, 2025}

\begin{document}
\maketitle

\begingroup
  \footnotetext[1]{This version published at
  \href{https://doi.org/10.5281/zenodo.17017852}{https://doi.org/10.5281/zenodo.17017852}.}
\endgroup

\begin{abstract}
The Timeless Light Model (TLM) asserts that quanta are not travelers within spacetime but timeless instructions rendered through delay. 
Previous work has introduced descriptive relations such as \(T \cdot C_s = 1\) (delay times causal speed) and mass-delay duality. 
Here we extend these descriptive laws into testable predictions. 
We identify eight experimental domains where residuals should appear if delay is fundamental: gravitational waves, strong-lensing time delays, cosmological redshift drift, Shapiro echo tests, engineered clock shells, interferometers with inertial loads, cosmic microwave background non-Gaussianity, and entanglement coincidence widths. 
Each test provides a falsifiable coefficient that vanishes under GR/QM but should take a definite nonzero value under TLM. 
This paper serves as a roadmap from descriptive simplicity to predictive physics.

\textbf{Keywords:} Timeless Light Model, falsifiable predictions, alternative gravity, delay ontology, quantum foundations
\end{abstract}

\section{Introduction}
The Timeless Light Model reframes photons as instructions outside spacetime, replacing motion with delay. 
While earlier work~\cite{mckinley2025} emphasized ontological clarity, physics demands falsifiability. 
This paper demonstrates how TLM’s descriptive laws imply measurable deviations from GR and QM~\cite{einstein1905}. 

We proceed by first restating the cornerstone descriptive equations, then deriving their consequences for observational tests across astrophysics, cosmology, and the laboratory. Order-of-magnitude estimates for the coefficients are discussed qualitatively, with quantitative refinements reserved for future work.

\section{Cornerstone Descriptive Laws}
\begin{lawbox}{Delay Law}
\[
T \cdot C_s = 1
\]
where \(T\) is the deployment delay and \(C_s\) is the causal speed, defining the inverse relation between delay and causal deployment.
\end{lawbox}

\begin{lawbox}{Mass-Delay Duality}
\[
T \cdot m = \frac{\hbar}{c^2}
\]
which binds rest mass \(m\) to the delay \(T\) it imposes.
\end{lawbox}

These are descriptive in nature: they restructure the ontology of physics but do not, by themselves, generate experimental numbers. 
The remainder of this paper shows how to extract predictive residuals.

\section{Predictions and Tests}
In each of the following subsections, we present a specific prediction derived from the cornerstone laws. The coefficients (e.g., \(\alpha_T\)) represent the strength of the TLM-specific residual, expected to be small but detectable with current or near-future instruments. Their signs are fixed by the delay ontology: positive for effects that increase apparent delay or phase shifts.

\subsection{Gravitational-Wave Phase Residuals}
In TLM, the delay introduced by massive bodies affects the phase accumulation in gravitational waves. Inspiral events should exhibit a small phase slip:
\[
\Delta \phi(f) = \alpha_T \,\frac{d}{dt}\big[ T_{\text{eff}}(f)\big] \,\tau_{\text{cycle}}(f),
\]
where \(T_{\text{eff}}(f)\) is the effective delay accumulated during the inspiral at frequency \(f\), and \(\tau_{\text{cycle}}(f)\) is the duration of one cycle at that frequency. Standard GR corresponds to \(\alpha_T = 0\). TLM predicts \(\alpha_T > 0\), arising from the mass-delay duality. This could be tested with LIGO/Virgo data, where \(\alpha_T\) might be on the order of $10^{-3}$ to $10^{-5}$ radians for typical events.

\subsection{Strong-Lensing Time-Delay Anomalies}
In strong gravitational lensing, the delay \(T\) varies along different paths, leading to anomalies in observed time delays for quasar lenses:
\[
\Delta t_{\text{obs}} = \Delta t_{\text{GR}} + \beta_T (T_{\text{lens}} - T_{\text{ref}}),
\]
where \(T_{\text{lens}}\) and \(T_{\text{ref}}\) are delays along lensed and reference paths. This residual tests the integration of delay over lensed paths. TLM predicts \(\beta_T > 0\), potentially detectable in surveys like LSST at sensitivities of $\sim 10^{-2}$ days.

\subsection{Cosmological Redshift Drift}
Cosmological expansion modulates the delay along lightcones, resulting in a modified redshift drift:
\[
\dot z_{\text{obs}} = \dot z_{\Lambda \text{CDM}} + \gamma_T \frac{dT}{dt}\bigg|_{\text{lightcone}},
\]
where the derivative is evaluated along the lightcone. This prediction probes large-scale delay gradients. TLM predicts \(\gamma_T > 0\), testable with ELT or SKA at drifts of $10^{-10}$ yr$^{-1}$.

\subsection{Shapiro Echo Perturbations}
The Shapiro delay in radar echoes or pulsar timing is augmented by gradients in \(T\) near massive bodies:
\[
\Delta t_{\text{echo}} = \Delta t_{\text{Shapiro}} + k_T \int_{\text{path}} \nabla T \cdot dl,
\]
where the integral is over the path. This integral residual can be tested with precise timing. TLM predicts \(k_T > 0\), with potential detection in pulsar arrays at $\sim 10^{-6}$ s.

\subsection{Clock Gradients in Mass Shells}
Engineered mass shells create tunable delay differences between clocks:
\[
\frac{\Delta \nu}{\nu} = \left(\frac{\Delta \nu}{\nu}\right)_{\text{GR}} + \eta_T \Delta T_{\text{shell}},
\]
where \(\Delta T_{\text{shell}}\) is the shell-induced delay. Laboratory setups with atomic clocks can falsify this. TLM predicts \(\eta_T > 0\), measurable with optical clocks at $10^{-18}$ precision.

\subsection{Interferometer with Inertial Load}
In interferometers, mass loading in one arm introduces path-dependent delay:
\[
\Delta \phi = \frac{2\pi}{\lambda} \left[ L + \xi_T \int_{\text{path}} T(r) dl \right],
\]
where the integral is over the path and \(T(r)\) is position-dependent delay. This extends standard phase shifts by delay contributions. TLM predicts \(\xi_T > 0\), testable in LIGO-like setups.

\subsection{CMB Non-Gaussian Tail Signatures}
Delay fluctuations imprint non-Gaussianity in the CMB at high multipoles:
\[
K_l = K_l^{\Lambda \text{CDM}} + \zeta_T F_l[T],
\]
where \(F_l[T]\) is a delay-dependent function at multipole \(l\). Analysis of Planck or future data can detect this. TLM predicts \(\zeta_T > 0\), with tails at $\ell \gtrsim 2000$.

\subsection{Entanglement Coincidence Widths}
Entangled pairs experience variance in delay, broadening coincidence timings:
\[
\Delta \tau_{\text{pairs}} = \Delta \tau_{\text{QM}} + \chi_T \, \text{Var}[T],
\]
where \(\text{Var}[T]\) is delay variance. Quantum optics experiments can measure this width. TLM predicts \(\chi_T > 0\), detectable at fs timescales.

\subsection{Summary of Predictions}
\begin{table}[ht]
\centering
\caption{Summary of Falsifiable Predictions in TLM}
\begin{tabular}{lccc}
\toprule
Test Domain & Coefficient & Expected Sign & Key Experiment/Data \\
\midrule
Gravitational Waves & \(\alpha_T\) & Positive & LIGO/Virgo inspirals \\
Strong Lensing & \(\beta_T\) & Positive & Quasar lens surveys (e.g., LSST) \\
Redshift Drift & \(\gamma_T\) & Positive & ELT/SKA campaigns \\
Shapiro Echo & \(k_T\) & Positive & Pulsar timing arrays \\
Clock Shells & \(\eta_T\) & Positive & Atomic clock labs \\
Interferometer Load & \(\xi_T\) & Positive & LIGO-like interferometers \\
CMB Non-Gaussianity & \(\zeta_T\) & Positive & Planck/CMB-S4 \\
Entanglement Widths & \(\chi_T\) & Positive & Quantum optics setups \\
\bottomrule
\end{tabular}
\end{table}

\section{Discussion}
Each coefficient \(\{\alpha_T,\beta_T,\gamma_T,\dots\}\) is falsifiable: GR and QM demand they vanish. 
TLM demands that they are nonzero and, crucially, that their signs are fixed by the ontology of delay (positive for delay-increasing effects). 
Thus the TLM is open to decisive experimental challenge. Null results at sufficient sensitivity would falsify TLM.

\section{Conclusion}
The transition from descriptive laws to predictive signatures provides a bridge for TLM to engage mainstream physics. 
These proposed tests invite comparison with data from LIGO/Virgo, lensing surveys, redshift-drift campaigns, pulsar timing, laboratory clocks, interferometry, and cosmological datasets like Planck. 
Future work will refine magnitudes and perform preliminary data analyses, but the falsifiability is already clear.

\bibliographystyle{plain}
\begin{thebibliography}{9}

\bibitem{einstein1905}
Einstein, A. (1905).
On the electrodynamics of moving bodies.
\textit{Annalen der Physik}, 17, 891--921.

\bibitem{mckinley2025}
McKinley, J. C. W. (2025).
Foundational Equations and Axiomatic Structure of the Timeless Light Model.
Zenodo. DOI:10.5281/zenodo.16187719

\end{thebibliography}

\end{document}
```

</details>

---
{% endraw %}
