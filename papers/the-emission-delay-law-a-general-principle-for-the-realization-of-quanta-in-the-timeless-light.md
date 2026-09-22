---
layout: default
title: '[2025] The Emission Delay Law: A General Principle for the Realization of Quanta in the Timeless Light Model'
description: 'Publication metadata and archived raw LaTeX source by John C. W. McKinley.'
permalink: /papers/the-emission-delay-law-a-general-principle-for-the-realization-of-quanta-in-the-timeless-light/
paper: true
---
{% raw %}
# [2025] The Emission Delay Law: A General Principle for the Realization of Quanta in the Timeless Light Model
*   **DOI:** [10.5281/zenodo.17032235](https://doi.org/10.5281/zenodo.17032235)
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


% ====== Theorems/Defs ======
\newtheorem{definition}{Definition}
\newtheorem{postulate}{Postulate}
\newtheorem{proposition}{Proposition}
\newtheorem{lemma}{Lemma}
\newtheorem{theorem}{Theorem}



\usepackage{hyperref}
\hypersetup{colorlinks=true,linkcolor=blue,urlcolor=blue,citecolor=blue}
\usepackage{orcidlink}
\usepackage{booktabs} % For better tables

\title{The Emission Delay Law: A General Principle for the Realization of Quanta in the Timeless Light Model}

\author{John C. W. McKinley\orcidlink{0009-0005-7097-5035}\\Independent Researcher}
\date{September 1, 2025}

\begin{document}
\maketitle

\begingroup
  \footnotetext[1]{This version published at
  \href{https://doi.org/10.5281/zenodo.17032235}{https://doi.org/10.5281/zenodo.17032235}.}
\endgroup



\begin{abstract}
The Timeless Light Model (TLM) reinterprets quanta not as propagating entities but as timeless, holistic transactions within a fundamental Quantum Platform (QP). A core tenet of this model is that no quantum can be realized without a compatible paired condition (e.g., an absorber). This raises a foundational question: what happens to an excited state in an absorber-free environment? This paper answers by introducing the Emission Delay Law (EDL), a universal principle for all quanta. The EDL states that an excited state persists until a compatible paired condition becomes available, enabling the quantum transaction. The time an observer measures for this persistence is the "emission delay." This law is a necessary consequence of the TLM framework, providing a clear, falsifiable mechanism for quantum realization that applies to all quanta in all scenarios.
\end{abstract}


\section{Introduction}

The Timeless Light Model (TLM) posits that quantum events are holistic, timeless transactions within a fundamental Quantum Platform (QP), which are then rendered into our observer-dependent Spacetime Deployment Frame (SDF) \cite{McKinley2025a}. A key principle, the Generalized Pairing Law (GPL), asserts that \textbf{no quantum is emitted without a paired condition} to complete the transaction and satisfy conservation laws \cite{McKinley2025b}.

This principle, while logically robust, benefits from a clarifying mechanism when considering its ultimate consequences. For example, in a thought experiment with a single excited atom in an otherwise empty universe, the GPL implies the atom could never decay. This apparent prohibition requires a more dynamic formulation. To resolve this, we introduce the \textbf{Emission Delay Law (EDL)} as a general and necessary extension of the GPL. The EDL states that an excited state persists until a paired condition becomes available. This reframes the situation from an absolute prohibition to a conditional, delayed realization, providing a consistent mechanism for all quantum events.





\section{Core Laws for All Quanta}

\begin{definition}[Paired Condition]
A paired condition is any physical state or process that, together with an emission, completes all conservation laws. For a photon, this is an available electromagnetic mode; for an electron, an available final state consistent with the Pauli exclusion principle and selection rules; for a phonon, a thermal bath or coupled vibrational modes.
\end{definition}

\begin{theorem}[Generalized Pairing Law (GPL)]
The realization of any quantum is a holistic transaction that occurs if and only if a compatible paired condition exists \cite{McKinley2025b}.
\end{theorem}

This leads to the new, clarifying law governing the timing of all quantum events.

\begin{theorem}[Emission Delay Law (EDL)]
For any quantum, if an excited state exists but no compatible paired condition is available, the state persists until one becomes available, enabling holistic resolution in the QP. The duration of this persistence, as measured in the SDF, is the emission delay.
\end{theorem}
















\section{Timeless Light Model Foundations}

TLM is built on a two-layer ontology \cite{McKinley2025c}:
\begin{itemize}
    \item \textbf{Quantum Platform (QP):} A timeless, spaceless substrate where all quantum events (for photons, phonons, etc.) are holistic, pre-resolved instructions.
    \item \textbf{Spacetime Deployment Frame (SDF):} The observer's 4D spacetime reality, where QP instructions are rendered with delays, creating the illusion of propagation and causality.
\end{itemize}

For any massless quantum like a photon, its path in the SDF is a null geodesic where proper time is zero ($d\tau = 0$), reinforcing the TLM concept of a timeless transaction in the QP. The EDL extends this logic by introducing a pre-realization delay in the SDF, which represents the time spent waiting for the conditions of the timeless transaction to be met.












\section{Implications and Distinctions}

The EDL implies that the realization of any quantum event is dynamically conditioned by the state of the surrounding universe.
\begin{itemize}
    \item \textbf{Philosophically}, this reduces the ontology of "free particles" and reinforces a relational view of quantum mechanics \cite{Rovelli1996}.
    \item \textbf{It differs from the Wheeler-Feynman absorber theory} as it posits a timeless transaction in the QP, not one mediated by advanced waves or requiring retrocausality within spacetime \cite{Wheeler1945}.
\end{itemize}






\section{Derivation of the Emission Delay Law}

The Emission Delay Law (EDL) follows directly from the Generalized Pairing Law (GPL) and the foundational principles of quantum mechanics, integrated within the Timeless Light Model (TLM). We derive it step by step, showing that the absence of a paired condition causes the excited-state lifetime to diverge, manifesting as persistence until conditions allow resolution.

\subsection{Step 1: Quantum Transition Rates from GPL}

From GPL, the realization of a quantum requires a compatible final state to complete conservation laws. In time-dependent perturbation theory, the emission rate from an excited initial state $|i\rangle$ (energy $E_i$) to final states $|f\rangle$ (energy $E_f$) is governed by Fermi's golden rule:

\[
W = \frac{2\pi}{\hbar} \sum_{f} |M_{fi}|^2 \rho_f(E) \delta(E_f + \hbar\omega - E_i),
\]

where:
- $M_{fi}$ is the transition matrix element, requiring nonzero coupling to the final state,
- $\rho_f(E)$ is the density of states (DOS) for final states, representing the availability of paired conditions,
- $\delta(E_f + \hbar\omega - E_i)$ enforces energy conservation for the emission of a quantum with energy $\hbar\omega$,
- The sum is over all accessible $f$ satisfying GPL compatibility.

This rate $W$ is the probability per unit time for the holistic transaction to resolve.

\subsection{Step 2: Absence of Paired Condition}

If no compatible paired condition exists, the density of available final states $\rho_f(E)$ tends to zero. The lifetime $\tau = 1/W$ diverges as $W \to 0$. Thus, the excited state persists until the environmental conditions change to make a paired condition available.

\subsection{Step 3: Dynamic Resolution and Emission Delay}

In a time-evolving system, if the environment changes such that a paired condition becomes available (e.g., $\rho_f(E) > 0$), then $W$ becomes finite, and resolution (emission) can occur. The duration of persistence before this change, as measured in the observer's Spacetime Deployment Frame (SDF), is the emission delay $\tau_{\text{delay}}$.

In TLM, this delay is framed ontologically:
- In the timeless Quantum Platform (QP), the instruction remains unresolved until the holistic unit (emitter-paired condition) is complete.
- Rendering into SDF introduces delays via bridge laws, such as mass-delay duality:

\[
T \cdot m = \frac{\hbar}{c^2},
\]

where $T$ is the instructional delay (proper-time resistance), linking the persistence to the system's mass and causal structure. For massless quanta (e.g., photons), the null geodesic ($ds^2 = 0$) ensures no internal time, but the pre-realization delay $\tau_{\text{delay}}$ is observer-dependent.

\subsection{Step 4: Universality Across Quanta}

The derivation holds for all quanta:
- \textbf{Photons}: The availability of final states is described by the local density of optical states (LDOS). The lifetime diverges in the limit LDOS $\to 0$; in practice, it should increase dramatically in a photonic bandgap material.
- \textbf{Electrons}: For processes like beta decay or tunneling, if accessible final states are Pauli-blocked at the transition energy, the effective $\rho_f(E)$ tends to 0, and the initial state persists.
- \textbf{Phonons}: A phonon's paired condition is a thermal bath or coupled vibrational modes. In a mechanically isolated system at low temperature, the absence of available modes suppresses thermal transport.
- This generalizes to all bosons and fermions via the appropriate statistics in $\rho_f(E)$.

This confirms the EDL as a universal consequence: an emission delay occurs if no compatible paired condition is available, with the lifetime diverging as $\tau \propto 1/\rho_f(E)$.

Falsifiability: Measure a finite transition rate $W > 0$ in an environment where the density of compatible final states effectively vanishes at the transition.





\section{Empirical Predictions and Falsifiability}

The EDL is a general law, yielding specific tests for different quanta.
\begin{itemize}
    \item \textbf{Photons:} The excited-state lifetime of an emitter should diverge in the limit of vanishing local density of optical states (LDOS); in a photonic bandgap material it should be strongly extended \cite{Haroche2013}.
    \item \textbf{Phonons:} Heat transport in cryogenically isolated nanostructures should be suppressed if there is no available thermal bath or coupled modes to act as a sink for phonons.
    \item \textbf{Cosmology:} The evolution of absorber density (and thus the effective LDOS on a cosmological scale) in the early universe could influence emission patterns, potentially leaving signatures in the CMB, such as primordial non-Gaussianity \cite{Planck2016}.
\end{itemize}
The theory would be falsified by observing any quantum emission in a verifiably isolated environment where the density of compatible final states effectively vanishes.

\section{Conclusion}

The Emission Delay Law (EDL) is a universal and necessary principle within the Timeless Light Model. It clarifies that the requirement of a paired condition for emission manifests as a conditional delay, not an absolute prohibition. Arising from the logical consequences of the TLM in isolated systems, the EDL provides a consistent and falsifiable mechanism for the realization of all quantum transactions. It strengthens the TLM framework by offering a clear rule governing how and when timeless events in the QP are rendered into our observable reality.

\begin{thebibliography}{9}

\bibitem{McKinley2025a}
J. C. W. McKinley, \textit{Timeless Light Model (TLM v2.0): Frameless Quanta, Framed Observers, and Bridge Laws}, Preprint (2025). \href{https://doi.org/10.5281/zenodo.16934697}{DOI: 10.5281/zenodo.16934697}

\bibitem{McKinley2025b}
J. C. W. McKinley, \textit{Generalized Pairing Law: No Quantum Emission Without an Absorber}, Preprint (2025). \href{https://doi.org/10.5281/zenodo.16892099}{DOI: 10.5281/zenodo.16892099}

\bibitem{McKinley2025c}
J. C. W. McKinley, \textit{The Quantum Platform as Frame Generator: Ontology, Anatomy, and Dark Matter Implications in TLM}, Preprint (2025). \href{https://doi.org/10.5281/zenodo.16788735}{DOI: 10.5281/zenodo.16788735}

\bibitem{Rovelli1996}
C. Rovelli, \textit{Relational Quantum Mechanics}, International Journal of Theoretical Physics \textbf{35}, 1637 (1996). \href{https://doi.org/10.1007/BF02302261}{DOI: 10.1007/BF02302261}

\bibitem{Wheeler1945}
J. A. Wheeler \& R. P. Feynman, \textit{Interaction with the Absorber as the Mechanism of Radiation}, Reviews of Modern Physics \textbf{17}, 157 (1945). \href{https://doi.org/10.1103/RevModPhys.17.157}{DOI: 10.1103/RevModPhys.17.157}

\bibitem{Haroche2013}
S. Haroche, \textit{Nobel Lecture: Controlling photons in a box and exploring the quantum-to-classical boundary}, Reviews of Modern Physics \textbf{85}, 1083 (2013). \href{https://doi.org/10.1103/RevModPhys.85.1083}{DOI: 10.1103/RevModPhys.85.1083}

\bibitem{Planck2016}
Planck Collaboration, \textit{Planck 2015 results. XVII. Constraints on primordial non-Gaussianity}, Astronomy \& Astrophysics \textbf{594}, A17 (2016). \href{https://doi.org/10.1051/0004-6361/201525836}{DOI: 10.1051/0004-6361/201525836}

\end{thebibliography}

\end{document}
```

</details>

---
{% endraw %}
