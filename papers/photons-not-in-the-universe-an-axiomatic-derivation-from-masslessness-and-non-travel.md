---
layout: default
title: '[2025] Photons Not in the Universe: An Axiomatic Derivation from Masslessness and Non-Travel'
description: 'Publication metadata and archived raw LaTeX source by John C. W. McKinley.'
permalink: /papers/photons-not-in-the-universe-an-axiomatic-derivation-from-masslessness-and-non-travel/
paper: true
---
{% raw %}
# [2025] Photons Not in the Universe: An Axiomatic Derivation from Masslessness and Non-Travel
*   **DOI:** [10.5281/zenodo.17010029](https://doi.org/10.5281/zenodo.17010029)
*   **Date:** 30 August 2025

<details markdown="1">
<summary><b>Click to view Raw LaTeX Source</b></summary>

```latex
\documentclass[12pt,letterpaper]{article}

% ====== Packages ======
\usepackage[margin=1in]{geometry}
\usepackage[utf8]{inputenc}
\usepackage[T1]{fontenc}
\usepackage{lmodern}
\usepackage{microtype}
\usepackage{amsmath,amssymb,amsthm}
\usepackage{bm}
\usepackage{siunitx}
\sisetup{separate-uncertainty=true}
\usepackage{graphicx}
\usepackage{booktabs}
\usepackage{tikz}
\usepackage{pgfplots}
\pgfplotsset{compat=1.18}
\usepgfplotslibrary{fillbetween}
\usepackage{orcidlink}

\newtheorem{theorem}{Theorem}
\usepackage{hyperref}
\hypersetup{colorlinks=true,linkcolor=blue,citecolor=blue,urlcolor=blue}
\usepackage{enumitem} % Added for better enumeration



\title{Photons Not in the Universe: An Axiomatic Derivation from Masslessness and Non-Travel}

\author{John C. W. McKinley\orcidlink{0009-0005-7097-5035}\\Independent Researcher}
\date{August 30, 2025}




\begin{document}

\maketitle

\begingroup
  \footnotetext[0]{This version published at
  \href{https://doi.org/10.5281/zenodo.17010029}{https://10.5281/zenodo.17010029}.}
\endgroup

\begin{abstract}
Inspired by a comment from Michael David \cite{david2025tik} stating ``photons have no mass, they can't travel,'' this paper axiomatically derives the conclusion that photons are not ``in the universe'' in the conventional spatiotemporal sense. We formalize the intuitive logic: masslessness implies zero proper time ($\tau = 0$)\cite{einstein1905}, which entails no change, no space, and thus no presence within the evolving universe. This resolves the foundational question sparking the Timeless Light Model (TLM): ``How does the photon know where it is going?'' The answer: it doesn't ``go''---it connects timelessly from outside spacetime. We state the obvious yet ignored principle: ``If you are not here, you can't move.'' Grounded in Special Relativity (SR) invariants and the established zero rest mass of photons, this derivation reinforces TLM's two-layer ontology---a timeless, spaceless Quantum Platform (QP) issuing instructions, rendered into the Spacetime Deployment Frame (SDF)---without altering empirical physics. Falsifiable predictions include achromatic timing residuals in interferometry.


\end{abstract}

\section{Introduction}

The Timeless Light Model (TLM) originated from a deceptively simple question: ``How does the photon know where it is going?" (Given that it has a destination but no proper time.) This query, posed in early explorations, led to the realization that zero proper time ($\tau = 0$)\cite{einstein1905} implies not just timelessness but spacelessness, positioning photons outside the universe's spatiotemporal fabric \cite{mckinley2025photon, mckinley2025qp}. Michael David's recent comment on social media \cite{david2025tik} is in fact an axiom: ``since photons have no mass, they can't travel.'' While counterintuitive under classical views---where masslessness enables travel at $c$---this statement captures a profound truth ignored in mainstream interpretations: if an entity experiences no time and occupies no space, it cannot ``move'' through the universe; it must exist externally as a correlation or instruction.

This paper axiomatically derives ``photons are not in the universe'' from David's comment, emphasizing the overlooked obvious: ``If you are not here, you can't move.'' We cite established sources for the photon's zero rest mass \cite{pdg2025} and build a logical chain compatible with SR and TLM. The derivation avoids new assumptions, deriving consequences from invariants like $ds^2 = 0$. Implications extend TLM by formalizing masslessness as the gateway to non-universe ontology, with tests via horizon-scale residuals.

\section{Axioms}

We adopt minimal axioms from SR and TLM, ensuring consistency with empirics:

\begin{itemize}
    \item \textbf{Axiom 1 (Masslessness)}: The photon has zero rest mass ($m = 0$). This is an empirical fact, with upper limits $m < 10^{-54}$ kg from cosmological bounds \cite{pdg2025}.
    \item \textbf{Axiom 2 (Null Geodesics)}: Massless particles follow null geodesics, where the spacetime interval $ds^2 = 0$, implying proper time $\tau = 0$.
    \item \textbf{Axiom 3 (No Change Without Time)}: In the absence of proper time ($\tau = 0$), there is no intrinsic change, evolution, or motion for the entity.
    \item \textbf{Axiom 4 (Space Requires Change)}: Spatial extent or traversal requires temporal change to be definable or operational (e.g., measurement implies duration).
    \item \textbf{Axiom 5 (Universe as Spatiotemporal)}: The ``universe'' refers to the observable, evolving spacetime frame (SDF in TLM), where entities with $m > 0$ or $\tau > 0$ reside.
\end{itemize}

These axioms are non-controversial, drawn from SR (Axioms 1-3) and logical necessity (Axioms 4-5), as in prior TLM works \cite{mckinley2025qp}.

\section{Derivation: From Masslessness to Non-Universe Ontology}

We proceed step-by-step, formalizing David's comment into a theorem.

\subsection{Masslessness Implies No Proper Time}

From Axiom 1 ($m = 0$) and SR's energy-momentum relation $E^2 = p^2 c^2 + m^2 c^4$, for photons $E = p c$, mandating $v = c$. The Lorentz factor $\gamma = 1/\sqrt{1 - v^2/c^2} \to \infty$, but more precisely, the proper time along a null path is:

\[
\tau = \int \frac{ds}{c} = 0,
\]

where $ds^2 = -c^2 dt^2 + dx^2 + dy^2 + dz^2 = 0$. Thus, no mass $\to$ no proper time.

\subsection{No Proper Time Implies No Change}

From Axiom 3: $\tau = 0$ means no internal clock ticks; invariants (e.g., energy, polarization) remain fixed. There is no ``during'' for evolution or decision-making, resolving the origin question: the photon doesn't ``know'' its path mid-journey because there is no mid-journey.

\subsection{No Change Implies No Space}

From Axiom 4: Space is operational only through change (e.g., traversal requires $\Delta t > 0$ in any frame). With $\tau = 0$, $ds^2 = 0$ implies no invariant spatial separation $s^2 = 0$. The ``distance'' is a coordinate artifact for massive observers; intrinsically, the photon registers no extent. Theorem from prior work \cite{mckinley2025live}: No time $\Rightarrow$ no space.

\subsection{No Space Implies Not in the Universe}

From Axiom 5: The universe is the SDF, a spatiotemporal domain. An entity with no time or space cannot occupy or traverse it; it exists as a timeless instruction in the QP, bridging emission (E) and absorption (A) without intermediate states.

\subsection{Not in the Universe Implies Can't Travel}

If not ``here'' (in the universe), it can't move (traverse space). David's ``can't travel'' follows: the appearance of travel is SDF rendering of QP instructions, not motion. The ignored obvious: ``If you are not here, you can't move.''

\begin{theorem}[Photon Non-Universe Theorem]
Let $P$ be a photon with $m = 0$. Then $\tau_P = 0 \Rightarrow$ no change $\Rightarrow$ no space $\Rightarrow$ $P$ not in universe $\Rightarrow$ $P$ can't travel (connects E-A timelessly).
\end{theorem}

\textbf{Proof:} Chain Axioms 1-5 as above. Contradiction if assumed in-universe: requires $\tau > 0$ for motion, but $m = 0$ forbids it.

\section{Implications for TLM and Physics}

This derivation strengthens TLM: Photons as QP instructions resolve pathfinding without retrocausality. Massive particles ($m > 0$) impose delay ($T \cdot m = \hbar/c^2$), binding to SDF; photons ($m=0$, $T=0$) remain QP-native.

Predictions:
\begin{itemize}
    \item Achromatic residuals $\delta t \approx \alpha_* L_{\text{geom}} / c$ ($\alpha_* \ll 1$) in lensing/FRBs, independent of frequency.
    \item No intermediate states in ultra-precision interferometry (falsifies traveler ontology).
\end{itemize}

This extends GPL \cite{mckinley2025gpl} by tying masslessness to non-universe status, inspired by David's comment.


\section{Acknowledgment}

The new axiom was articulated by Michael David (@michael40000) in an August 2025 comment, "since photons have no mass, they can’t travel"\cite{david2025tik}. McKinley had already published papers on the photon's timeless, spaceless and not-in-the-universe nature. Michael David's axiom provided the manifest yet overlooked premise that supports that claim and enabled a new axiomatic proof.


\bibliography{references}

\begin{thebibliography}{7}

\bibitem{einstein1905} Einstein, A., Zur Elektrodynamik bewegter K{\"o}rper'', \href{https://doi.org/10.1002/andp.19053221004}{Annalen der Physik 322, 891 (1905)}. English translation: On the Electrodynamics of Moving Bodies''. This paper introduces special relativity, including the concepts leading to zero proper time along null geodesics for light. Available at \href{https://en.wikisource.org/wiki/On_the_Electrodynamics_of_Moving_Bodies_(1920_edition)}{Wikisource}.


\bibitem{pdg2025} S. Navas et al. (Particle Data Group), ``$\gamma$ (photon)'', \href{https://doi.org/10.1103/PhysRevD.110.030001}{Phys. Rev. D 110, 030001 (2024)} and 2025 update.

\bibitem{mckinley2025photon} McKinley, J. C. W., ``Photon Out of Time: Why Light Experiences No Time—and What That Means for Physics'', Zenodo, \href{https://doi.org/10.5281/zenodo.16470584}{DOI: 10.5281/zenodo.16470584}, July 2025.

\bibitem{mckinley2025qp} McKinley, J. C. W., ``Spacelessness as a Consequence of Timelessness in the Quantum Platform of the Timeless Light Model'', Zenodo, \href{https://doi.org/10.5281/zenodo.16350754}{DOI: 10.5281/zenodo.16350754}, July 2025.

\bibitem{mckinley2025live} McKinley, J. C. W., ``The One Blind Spot That Hid Three Simple Solutions: A Testable Reinterpretation of Photon Ontology Outside Spacetime'', Zenodo, \href{https://doi.org/10.5281/zenodo.16871293}{DOI: 10.5281/zenodo.16871293}, August 2025.

\bibitem{mckinley2025gpl} McKinley, J. C. W., ``Generalized Pairing Law: No Quantum Emission Without an Absorber'', Zenodo, \href{https://doi.org/10.5281/zenodo.16892099}{DOI: 10.5281/zenodo.16892099}, August 2025.

\bibitem{david2025tik} David, Michael (@michael40000), ``since photons have no mass, they can't travel.'', TikTok Comment, August 2025. Archived at Zenodo, \href{https://doi.org/10.5281/zenodo.17009839}{DOI: 10.5281/zenodo.17009839}.






\end{thebibliography}
\end{document}
```

</details>

---
{% endraw %}
