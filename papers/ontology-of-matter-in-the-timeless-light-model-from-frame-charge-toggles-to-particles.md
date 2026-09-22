---
layout: default
title: '[2025] Ontology of Matter in the Timeless Light Model: From FRAME–CHARGE Toggles to Particles'
description: 'Publication metadata and archived raw LaTeX source by John C. W. McKinley.'
permalink: /papers/ontology-of-matter-in-the-timeless-light-model-from-frame-charge-toggles-to-particles/
paper: true
---
{% raw %}
# [2025] Ontology of Matter in the Timeless Light Model: From FRAME–CHARGE Toggles to Particles
*   **DOI:** [10.5281/zenodo.16939101](https://doi.org/10.5281/zenodo.16939101)
*   **Date:** 24 August 2025

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

\usepackage{rotating}
\usepackage{amsmath,amssymb,amsthm,mathtools}
\usepackage{bm}
\usepackage{siunitx}
\sisetup{separate-uncertainty=true}
\usepackage{graphicx}
\usepackage{booktabs}
\usepackage{enumitem}
\usepackage{array}
\usepackage{caption}
\usepackage[numbers,sort&compress]{natbib}
\usepackage{tikz}
\usetikzlibrary{decorations.pathreplacing,arrows.meta,positioning,shapes.geometric}
\usepackage{calc} % for \widthof in description labels
\usepackage{orcidlink}
\usepackage{hyperref}
\hypersetup{colorlinks=true,linkcolor=blue,citecolor=blue,urlcolor=blue}

% ====== Title ======
\title{Ontology of Matter in the Timeless Light Model:\\
From FRAME--CHARGE Toggles to Particles}
\author{John C. W. McKinley\orcidlink{0009-0005-7097-5035}\\Independent Researcher}
\date{August 24, 2025}

\begin{document}
\maketitle
\begingroup\renewcommand\thefootnote{}\footnotetext{This version published at
\href{https://doi.org/10.5281/zenodo.16939101}{https://doi.org/10.5281/zenodo.16939101}.}\endgroup
% ====== Abstract ======
\begin{abstract}
The Standard Model (SM) successfully classifies known particles but relies on many fundamental parameters and interaction types, without an obvious minimal generative rule. In contrast, the Timeless Light Model (TLM) holds that \emph{spacetime dynamics are the delayed resolution of pre-resolved instructions} from a Quantum Platform (QP), with outcomes governed by minimal binary toggles. Extending TLM priors on frames and endpoint pairing, we propose two toggles for the ontology of matter: a \emph{FRAME-YES} toggle for spacetime deployment, and a \emph{CHARGE-YES} toggle for interaction-enabled \emph{particle-hood}. We give axioms, derivations tying \(E=mc^2\) to TLM delay \(T\) via \(\omega \propto 1/T\), a quantitative QCD example (\(m_p \approx \SI{938}{MeV/c^2}\) with \(\sim99\%\) gluon-field contribution), and a revised SM--TLM hierarchy (including composites). Predictions include achromatic lensing residuals (achromatic in vacuum) and dark-matter-like behavior for FRAME-YES / CHARGE-NO states. Limitations and extensions (e.g., spin/chirality toggles) are noted.
\end{abstract}

% ====== Position in the Program ======
\paragraph{Position in the program}
This note sits with four companion statements: the \emph{TLM v2.0 frameless quanta} reformulation \citep{McKinley2025TLMv2}, the \emph{Frame Display Law} formalism \citep{McKinley2025FrameDisplay}, the \emph{WFAT disambiguation} against Wheeler--Feynman \citep{McKinley2025WFAT}, and the \emph{Quanta Global, Frames Local} Rosetta statement \citep{McKinley2025QuantaGlobal}. Here we focus on a minimal ontology for \emph{matter}: particles appear iff FRAME-YES and CHARGE-YES, consistent with the program-wide view that spacetime dynamics are delayed resolutions of pre-resolved instructions.

% ====== Quick Glossary ======
\paragraph{Quick Glossary}
\begin{description}[leftmargin=!,labelwidth=\widthof{\bfseries CHARGE-YES}]
\item[FRAME-YES] Binary toggle indicating deployment into the Spacetime Deployment Frame (SDF).
\item[CHARGE-YES] Binary toggle indicating gauge-coupling participation; necessary and sufficient (with FRAME-YES) for a particle.
\item[QP] Quantum Platform; timeless, ontologically senior instruction layer.
\item[TLM] Timeless Light Model; physics as delayed deployment from QP.
\end{description}

% ====== Axioms ======
\section{Axioms}
\begin{enumerate}[label=\textbf{A\arabic*:},leftmargin=1.2cm]
\item \textbf{Timeless Source (QP).} The QP is ontologically prior to spacetime; \emph{spacetime dynamics are the delayed resolution of pre-resolved instructions} \citep{McKinley2025TLMv2,McKinley2025FrameDisplay,McKinley2025QPFrameGen}.
\item \textbf{Frame Primacy.} Deployment into SDF requires \emph{FRAME-YES}; frames are the minimal spacetime substrate in TLM.
\item \textbf{Particle Criterion.} Interaction-enabled excitations require \emph{CHARGE-YES}; a particle exists iff \((\text{FRAME-YES}) \land (\text{CHARGE-YES})\).
\item \textbf{Mass--Energy and Delay.} \(E=mc^2\) \citep{Einstein1905}; in TLM the deployment delay \(T\) and a causal rate \(C_s\) satisfy \(T\,C_s=1\), with deployment frequency \(\omega \propto 1/T\).
\item \textbf{Dark Matter as Delayed Frames.} FRAME-YES with CHARGE-NO corresponds to gravitating, non-gauge-coupled matter candidates \citep{McKinley2025QPFrameGen}.
\end{enumerate}





% ====== Decision Tree Figure ======
\begin{sidewaysfigure}[p]
\centering
\resizebox{0.98\textheight}{!}{%
\begin{tikzpicture}[
  >=Latex,
  node distance=1.4cm and 2.2cm,
  box/.style={draw, rounded corners, thick, align=center, inner sep=5pt, font=\small, text width=3.5cm}
]
\node[box, fill=gray!10] (start) {Instruction in QP};
\node[box, fill=blue!10, below left=of start, xshift=-1.2cm] (frameNo) {FRAME-NO\\\footnotesize not rendered in SDF};
\node[box, fill=blue!10, below right=of start, xshift=1.2cm] (frameYes) {FRAME-YES\\\footnotesize rendered in SDF};
\draw[->, thick] (start) -- node[midway, above left, font=\footnotesize]{\textbf{FRAME?} No} (frameNo);
\draw[->, thick] (start) -- node[midway, above right, font=\footnotesize]{\textbf{FRAME?} Yes} (frameYes);

\node[box, fill=green!10, below left=of frameYes, xshift=-0.8cm] (chargeNo) {CHARGE-NO\\\footnotesize inert / grav-only};
\node[box, fill=green!10, below right=of frameYes, xshift=0.8cm] (chargeYes) {CHARGE-YES\\\footnotesize \textbf{particle}};
\draw[->, thick] (frameYes) -- node[midway, above left, font=\footnotesize]{\textbf{CHARGE?} No} (chargeNo);
\draw[->, thick] (frameYes) -- node[midway, above right, font=\footnotesize]{\textbf{CHARGE?} Yes} (chargeYes);

\node[align=center, font=\footnotesize, below=0.3cm of frameNo] {no spacetime manifestation};
\node[align=center, font=\footnotesize, below=0.3cm of chargeNo] {dark-matter-like};
\node[align=center, font=\footnotesize, below=0.3cm of chargeYes] {gauge-coupled excitation};
\end{tikzpicture}%
}
\caption{Binary decision tree for the FRAME--CHARGE ontology. QP = Quantum Platform (timeless instruction layer). SDF = Spacetime Deployment Frame (rendered, timebound layer).}
\label{fig:toggle-tree}
\end{sidewaysfigure}





% ====== SM vs TLM Table ======
\section{Standard Model vs.\ TLM Reduction}
\begin{table}[h]
\centering
\caption{Standard Model taxonomy vs.\ TLM reduction from \textbf{CHARGE-YES}.}
\label{tab:hierarchy}
\begin{tabular}{@{}p{0.24\linewidth}p{0.34\linewidth}p{0.34\linewidth}@{}}
\toprule
\textbf{Category} & \textbf{Standard Model (SM)} & \textbf{TLM Ontology} \\
\midrule
Quarks & 6 flavors, 3 colors & FRAME-YES, CHARGE-YES; color sector from QP; confinement emerges \\
Leptons & \(e,\mu,\tau,\nu_e,\nu_\mu,\nu_\tau\) & FRAME-YES, CHARGE-YES in EM/weak sectors \\
Gauge bosons & \(\gamma,\,W^\pm,\,Z,\,g\) & FRAME-YES, CHARGE-YES; force mediation as sector toggles \\
Higgs & scalar \(0^+\) & FRAME-YES, CHARGE-YES; delay-setting interface for effective mass \\
\textbf{Composites} & protons, neutrons, nuclei, atoms & \textbf{Aggregates of CHARGE-YES with shared/locked delay \(T\)} \\
Dark matter & (unknown) & FRAME-YES, CHARGE-NO; gravitating, non-gauge-coupled \\
\bottomrule
\end{tabular}
\end{table}

\clearpage

% ====== Rigorous Derivations ======
\section{Rigorous Derivations}
\paragraph{Energy--Delay Link (TLM).}
Einstein gives
\begin{equation}
E = mc^2.
\label{eq:Einstein}
\end{equation}
In TLM, a deployed frame obeys
\begin{equation}
T\,C_s = 1,\qquad \omega \propto \frac{1}{T},
\label{eq:TLM_core}
\end{equation}
so the characteristic frequency \(\omega\) of deployment grows as delay \(T\) shrinks. Combining \eqref{eq:Einstein}--\eqref{eq:TLM_core} expresses mass as a function of charged deployment rate, i.e.\ `mass from charged deployment'' (operationally consistent with \(E\) as a rate-like quantity).

\paragraph{Quantified QCD Example.}
For the proton,
\begin{equation}
m_p \approx \SI{938}{MeV/c^2},
\end{equation}
with lattice/QCD analyses indicating that \(\sim 99\%\) of \(m_p\) originates from gluon-field energy and quark kinetic energy rather than bare quark masses \citep{Wilczek2000}. In the toggle ontology, this is modeled as sustained QP instruction loops in the \emph{CHARGE-YES} (color) sector, which \emph{amplify the effective deployment activity} (large \(\omega\), small effective \(T\)) inside the confinement region. Thus the observed rest energy \(E_p \approx m_p c^2\) is predominantly the manifestation of bound-state deployment dynamics rather than constituent bare masses.

% ====== Discussion ======
\section{Discussion and Implications}
The FRAME--CHARGE ontology compresses the SM's complexity to two toggles while remaining consistent with TLM priors on frames and endpoint pairing. It suggests:
\begin{itemize}[leftmargin=1.1em]
\item \textbf{Achromatic lensing residuals:} small, frequency-independent deflection/time-delay residuals from purely geometric deployment effects (achromatic in vacuum).
\item \textbf{Dark matter re-interpretation:} FRAME-YES / CHARGE-NO states behave as gravitating, non-gauge-coupled matter \citep{McKinley2025QPFrameGen}.
\item \textbf{Relational viewpoint:} the ontology aligns with relational quantum ideas \citep{Rovelli1996} and with emergent/entropic gravity heuristics \citep{Verlinde2011}.
\end{itemize}
\emph{Limitations.} We assume spin and chirality emerge secondarily from sector structure and boundary conditions; a future \emph{spin-YES} (and/or chirality) toggle could address Dirac statistics and parity-violating details explicitly.

% ====== Conclusion ======
\section{Conclusion}
Particles arise when and only when a QP instruction is both \emph{deployed} (FRAME-YES) and \emph{charged} (CHARGE-YES). This minimal ontology preserves the empirical successes of the SM, integrates cleanly with TLM's frame-centric causality, connects \(E=mc^2\) to deployment delay, and yields testable predictions (e.g., achromatic lensing residuals). Composites naturally appear as aggregates of CHARGE-YES constituents with shared/locked delay \(T\).

% ====== Full Glossary ======
\section*{Glossary}
\begin{description}[leftmargin=!,labelwidth=\widthof{\bfseries CHARGE-YES}]
\item[Quantum Platform (QP)] Timeless, ontologically senior layer containing pre-resolved instructions; source of deployments.
\item[Spacetime Deployment Frame (SDF)] Rendered, timebound layer where GR/QM observables appear.
\item[FRAME-YES / FRAME-NO] Binary deployment toggle: whether an instruction is instantiated in SDF.
\item[CHARGE-YES / CHARGE-NO] Binary interaction toggle: whether a deployed frame carries nonzero gauge coupling (EM/weak/strong).
\item[Delay \(T\)] Deployment delay parameter; in TLM relates to causal rate \(C_s\) via \(T\,C_s=1\).
\item[\(C_s\)] Causal rate appearing in \(T\,C_s=1\); increases as \(T\) decreases.
\item[\(\omega\)] Characteristic deployment frequency; scales as \(\omega \propto 1/T\).
\item[Composite] Bound aggregate of CHARGE-YES constituents with shared/locked \(T\) (e.g., nucleons, nuclei, atoms).
\end{description}

% ====== References ======
\bibliographystyle{unsrtnat}
\begin{thebibliography}{99}

\bibitem{Einstein1905}
A.~Einstein.
\newblock Zur Elektrodynamik bewegter K{\"o}rper.
\newblock {\em Annalen der Physik}, 322(10):891--921, 1905.
\newblock doi:\href{https://doi.org/10.1002/andp.19053221004}{10.1002/andp.19053221004}.

\bibitem{Wilczek2000}
F.~Wilczek.
\newblock QCD and Natural Philosophy.
\newblock {\em Annalen der Physik}, 9(10--11):868--885, 2000.
\newblock doi:\href{https://doi.org/10.1002/1521-3889(200011)9:10/11<868::AID-ANDP868>3.0.CO;2-8}{10.1002/1521-3889(200011)9:10/11<868::AID-ANDP868>3.0.CO;2-8}.

\bibitem{Rovelli1996}
C.~Rovelli.
\newblock Relational quantum mechanics.
\newblock {\em International Journal of Theoretical Physics}, 35(8):1637--1678, 1996.
\newblock doi:\href{https://doi.org/10.1007/BF02302261}{10.1007/BF02302261}.

\bibitem{Verlinde2011}
E.~P. Verlinde.
\newblock On the origin of gravity and the laws of Newton.
\newblock {\em Journal of High Energy Physics}, 2011(4):29, 2011.
\newblock doi:\href{https://doi.org/10.1007/JHEP04(2011)029}{10.1007/JHEP04(2011)029}.

\bibitem{McKinley2025TLMv2}
J.~C.~W. McKinley.
\newblock Timeless Light Model (TLM v2.0): Frameless Quanta, Framed Observers, and Bridge Laws.
\newblock Zenodo, 2025.

\bibitem{McKinley2025FrameDisplay}
J.~C.~W. McKinley.
\newblock Frame Display Law (v2.0).
\newblock Zenodo, 2025.
\newblock doi:\href{https://doi.org/10.5281/zenodo.16936105}{10.5281/zenodo.16936105}.

\bibitem{McKinley2025WFAT}
J.~C.~W. McKinley.
\newblock Timeless Light Model vs Wheeler--Feynman Absorber Theory: A Disambiguation (v5.0).
\newblock Zenodo, 2025.
\newblock doi:\href{https://doi.org/10.5281/zenodo.16924316}{10.5281/zenodo.16924316}.

\bibitem{McKinley2025QuantaGlobal}
J.~C.~W. McKinley.
\newblock Quanta are Global, Frames are Local: A Rosetta Statement of the Timeless Light Model (v1.0).
\newblock Zenodo, 2025.
\newblock doi:\href{https://doi.org/10.5281/zenodo.16917106}{10.5281/zenodo.16917106}.

\bibitem{McKinley2025QPFrameGen}
J.~C.~W. McKinley.
\newblock The Quantum Platform as Frame Generator: Ontology, Anatomy, and Dark Matter Implications in TLM.
\newblock Zenodo, 2025.
\newblock doi:\href{https://doi.org/10.5281/zenodo.16788735}{10.5281/zenodo.16788735}.

\end{thebibliography}

\end{document}

```

</details>

---
{% endraw %}
