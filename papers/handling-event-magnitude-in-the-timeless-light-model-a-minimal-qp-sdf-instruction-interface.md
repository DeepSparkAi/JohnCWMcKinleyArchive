---
layout: default
title: '[2025] Handling Event Magnitude in the Timeless Light Model: A Minimal QP→SDF Instruction Interface'
description: 'Publication metadata and archived raw LaTeX source by John C. W. McKinley.'
permalink: /papers/handling-event-magnitude-in-the-timeless-light-model-a-minimal-qp-sdf-instruction-interface/
paper: true
---
{% raw %}
# [2025] Handling Event Magnitude in the Timeless Light Model: A Minimal QP→SDF Instruction Interface
*   **DOI:** [10.5281/zenodo.17033795](https://doi.org/10.5281/zenodo.17033795)
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

% ------- Theorems/Defs -------
\newtheorem{theorem}{Theorem}
\newtheorem{definition}{Definition}

% ------- Metadata -------
\title{Handling Event Magnitude in the Timeless Light Model:\\
A Minimal QP$\to$SDF Instruction Interface}
\author{John C. W. McKinley\orcidlink{0009-0005-7097-5035}%
\thanks{This version published at \href{https://doi.org/10.5281/zenodo.17033795}{https://doi.org/10.5281/zenodo.17033795}.}\\Independent Researcher}
\date{September 1, 2025}

\begin{document}
\maketitle

\begin{abstract}
In the Timeless Light Model (TLM), a realized quantum is a single timeless instruction recorded in the Quantum Platform (QP) and rendered in the Spacetime Deployment Frame (SDF). To avoid black boxes while remaining sufficient for conservation, we propose a minimal instruction interface encoded by the tuple \(I=\langle x_e^\mu, x_a^\mu; \Delta p^\mu, \Delta J^{\mu\nu}, \Delta Q\rangle\): emitter and absorber event coordinates, conserved four-momentum transfer, angular-momentum transfer (including helicity), and charge transfer. Under the Generalized Pairing Law (GPL), an instruction is recorded iff a compatible absorber condition exists; otherwise no record is written. Magnitude enters only through \(\Delta p^\mu\) (via \(\Delta E=\hbar\omega\)) and changes channel availability, rates among realized events, and SDF observables (e.g., \(\lambda=hc/E\)) but does not modify the bridge laws or the timeless ontology. Deployment delay for realized records is set by \(T\cdot m=1\) (or \(T\cdot m=\hbar/c^2\) in standard units) and \(T\cdot C_s=1\), independent of \(\Delta E\).
\end{abstract}

\section{Introduction}
TLM reframes quanta as timeless instructions that enforce energy--momentum balance between emitters and absorbers. A recurring concern is how to represent such an instruction without smuggling in hidden fields or metadata. This note formalizes a minimal QP\(\to\)SDF interface that is sufficient for conservation and relativity, and shows how event magnitude fits into that interface while leaving bridge laws and ontology unchanged.

\section{Minimal QP$\to$SDF Instruction Interface}
\begin{definition}[Instruction tuple]
A realized instruction is the tuple
\[
I=\langle x_e^\mu, x_a^\mu; \Delta p^\mu, \Delta J^{\mu\nu}, \Delta Q\rangle,
\]
with the following meanings and constraints:
\begin{itemize}[leftmargin=1.2em]
  \item \(x_e^\mu, x_a^\mu\): emitter and absorber spacetime coordinates in the chosen SDF chart.
  \item \(\Delta p^\mu\): four-momentum transfer, encoding magnitude \(\Delta E=\hbar\omega\). For photons, \(\Delta p^\mu \Delta p_\mu=0\) and \(d\tau=0\).
  \item \(\Delta J^{\mu\nu}\): angular-momentum transfer; for photons this reduces to helicity \(h\in\{+1,-1\}\).
  \item \(\Delta Q\): net charge/gauge transfer required by the realized channel (often 0 for single-photon processes).
\end{itemize}
Conservation at endpoints is enforced by the record: \(p^\mu_e\to p^\mu_e-\Delta p^\mu\), \(p^\mu_a\to p^\mu_a+\Delta p^\mu\), with analogous updates for \(J^{\mu\nu}\) and charges.
\end{definition}

\begin{lawbox}{Generalized Pairing Law (GPL)}
An instruction is recorded in QP if and only if a compatible absorber condition exists; otherwise no record is written. There are no pending or partial records. For realized records, the SDF deployment delay is assigned by the bridge laws and does not depend on \(\Delta E\).
\end{lawbox}

\begin{lawbox}{Bridge laws (deployment delay)}
In natural units, \(T\cdot m=1\) and \(T\cdot C_s=1\). In standard units, \(T\cdot m=\hbar/c^2\) and \(T\cdot C_s=1\). These laws govern delay for realized records and are independent of \(\Delta E\).
\end{lawbox}

\section{Consequences for Magnitude and Observables}
The minimal interface yields the following:
\begin{itemize}[leftmargin=1.2em]
  \item \textbf{Where magnitude lives.} Magnitude is entirely in \(\Delta p^\mu\). Changing \(\Delta E\) changes which absorber conditions are compatible and the rates among realized events via SDF cross-sections and density of states \(\rho(\omega)\propto\omega^{2}\) (equivalently \(\rho(E)\propto E^{2}\) with \(E=\hbar\omega\)).
  \item \textbf{What does not change.} The bridge laws and the timeless character of the instruction do not change with \(\Delta E\). Photons remain null \((ds^{2}=0,\ d\tau=0)\).
  \item \textbf{SDF observables are emergent.} Wavelength \(\lambda=hc/E\), scattering regimes and angles, interference patterns, penetration depths, and detector responses arise from SDF rendering (GR/SR plus environment), not from extra fields inside \(I\).
\end{itemize}

\section{Implications for High-Magnitude Events}
High-energy quanta (e.g., gamma rays) follow the same rules:
\begin{itemize}[leftmargin=1.2em]
  \item \textbf{Recording in QP.} Larger \(\Delta E\) requires absorbers with sufficient capacity (e.g., nuclear levels or pair-production thresholds). Under GPL, a record exists only when such a condition exists; otherwise no instruction is written \cite{McKinley2025b}.
  \item \textbf{Rendering in SDF.} High magnitude manifests as available SDF channels (photoelectric, Compton, pair production), but these are realized because absorber conditions exist; there is no channel flag inside \(I\).
  \item \textbf{Examples.} Gamma-ray bursts resolve via cosmic absorbers; laboratory gamma emission (e.g., Co-60 decay) pairs with detectors. Rates follow DOS scaling while the ontology and bridge laws remain invariant.
\end{itemize}

\begin{tcolorbox}[title={Testable prediction}]
Condition on detected (realized) events. With absorber geometry and material fixed, sweep photon energy \(\Delta E\) using a tunable source in the single-photon regime. The latency distribution of detections remains invariant under \(\Delta E\) (within experimental error), confirming that deployment delay is independent of magnitude.
\end{tcolorbox}

\section{Conclusion}
By encoding a realized instruction as \(I=\langle x_e^\mu, x_a^\mu; \Delta p^\mu, \Delta J^{\mu\nu}, \Delta Q\rangle\), TLM specifies just the boundary data required for conservation and rendering without hidden metadata. Magnitude affects compatibility and rates via absorber conditions and SDF dynamics, but not the bridge laws or timeless ontology. This minimal interface keeps the model lean, testable, and free of black-box creep.

\begin{thebibliography}{3}

\bibitem{McKinley2025a}
J. C. W. McKinley, \textit{The Photon as a Timeless, Spaceless Energy Transfer (v1.3)}, Zenodo (2025). \href{https://doi.org/10.5281/zenodo.16735683}{DOI: 10.5281/zenodo.16735683}.

\bibitem{McKinley2025b}
J. C. W. McKinley, \textit{Generalized Pairing Law: No Quantum Emission Without an Absorber (v3.93)}, Zenodo (2025). \href{https://doi.org/10.5281/zenodo.16892099}{DOI: 10.5281/zenodo.16892099}.

\bibitem{McKinley2025c}
J. C. W. McKinley, \textit{The Emission Delay Law: A General Principle of Quanta Realization in the Timeless Light Model}, Zenodo (2025). \href{https://doi.org/10.5281/zenodo.17032235}{DOI: 10.5281/zenodo.17032235}.

\end{thebibliography}

\end{document}

```

</details>

---
{% endraw %}
