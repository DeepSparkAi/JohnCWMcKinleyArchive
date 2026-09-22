---
layout: default
title: '[2025] Why It Matters if a Marble Arrives Before Its Light: Causality and the Fragility of a Lawful Universe'
description: 'Publication metadata and archived raw LaTeX source by John C. W. McKinley.'
permalink: /papers/why-it-matters-if-a-marble-arrives-before-its-light-causality-and-the-fragility-of-a-lawful/
paper: true
---
{% raw %}
# [2025] Why It Matters if a Marble Arrives Before Its Light: Causality and the Fragility of a Lawful Universe
*   **DOI:** [10.5281/zenodo.17205431](https://doi.org/10.5281/zenodo.17205431)
*   **Date:** 26 September 2025

<details markdown="1">
<summary><b>Click to view Raw LaTeX Source</b></summary>

```latex
\documentclass[12pt, onecolumn]{article}
% ---------- Page & Layout ----------
\usepackage[margin=1in]{geometry}
\usepackage[T1]{fontenc}
\usepackage[utf8]{inputenc}
\usepackage{lmodern}
\usepackage{microtype}
% ---------- Math ----------
\usepackage{amsmath,amssymb,amsthm}
% ---------- Figures & Floats ----------
\usepackage{tikz}
\usetikzlibrary{arrows.meta, positioning}
\usepackage{float}
\usepackage{booktabs}
% ---------- Links & References ----------
\usepackage{hyperref}
\hypersetup{
  colorlinks=true,
  linkcolor=blue,
  urlcolor=blue,
  citecolor=blue
}
% ---------- Headers ----------
\usepackage{fancyhdr}
% ---------- ORCID ----------
\usepackage{orcidlink}
% --- Header Setup ---
\pagestyle{fancy}
\fancyhf{}
\lhead{Marble Before Light}
\rhead{\thepage}
% --- Document Info ---
\title{Why It Matters if a Marble Arrives Before Its Light:\\
Causality and the Fragility of a Lawful Universe}
\author{John C. W. McKinley\orcidlink{0009-0005-7097-5035}\\Independent Researcher}
\date{September 26, 2025}

\begin{document}
\maketitle
\begingroup
  \footnotetext[0]{This version published at
  \href{https://doi.org/10.5281/zenodo.17205431}{https://doi.org/10.5281/zenodo.17205431}.}
\endgroup

\begin{abstract}
Imagine throwing a marble so fast that it reaches its target before the light from your throw does. While this sounds like science fiction, the possibility of a material object outrunning its own emitted light would rupture the fundamental rules of cause and effect in our universe. If a massive object were to arrive at a detector before the light emitted from it, causal order would be unequivocally violated. We show, using Lorentz transformations, that any superluminal worldline segment is spacelike and therefore admits inertial frames in which the arrival precedes the emission. This physical ambiguity permits the construction of tachyonic antitelephones and paradoxes that fundamentally undermine determinism and conservation bookkeeping. The ``marble before light'' scenario therefore dramatizes why special relativity's causal structure is not a trivial speed limit but the essential scaffold that maintains physical self-consistency. We further integrate this analysis with the Timeless Light Model (TLM), in which the Spacetime Deployment Frame (SDF) is a delayed rendering of timeless instructions from the Quantum Platform (QP); superluminal matter would thus rupture the model's foundational delay structure. For empirical traction beyond textbook paradoxes, we point to related phase shift residual tests discussed in our prior TLM proposals. In plain terms: if a marble can beat its own light, some observers would literally see the effect before the cause.
\end{abstract}

\section{Introduction}\label{sec:intro}
The possibility of a material object, such as a marble, moving faster than the speed of light—outrunning the very light it emits—stands as a profound challenge to the foundations of physics. Special relativity sets the invariant speed \(c\) as the boundary of causal influence \cite{einstein_1905}, and this is no mere speed limit; it is the cornerstone of causal structure. In Minkowski spacetime, events outside a light cone are spacelike separated and cannot be joined by physical signals without allowing frame-dependent time reversals \cite[Ch.~8]{mtw_1973}. The everyday thought experiment of a marble that outruns its own light makes this abstract point concrete. Classical surveys of superluminal proposals document the consistency issues that follow when \(u>c\) is allowed \cite{recami_1986}. Within the Timeless Light Model (TLM), photons are treated as timeless energy transfer instructions with zero proper time along null worldlines \cite{mckinley_photon_timeless_2025}; allowing a massive marble to beat those instructions would invert the rendered order in the spacetime deployment frame (SDF), collapsing its lawful sequencing.

\section{Setup: The Marble Before Its Light}\label{sec:setup}
Consider emission event \(E\) and detection event \(D\). Suppose the marble's effective signal speed between \(E\) and \(D\) is \(u>c\) along \(+x\). In the lab frame \(S\),
\[
\Delta x = x_D - x_E > 0, \quad
\Delta t = t_D - t_E = \frac{\Delta x}{u} \in \bigl(0,\ \Delta x/c\bigr).
\]
Because \(u>c\), the interval is spacelike:
\[
\Delta s^2 \equiv c^2 \Delta t^2 - \Delta x^2
= \Delta x^2\!\left(\frac{c^2}{u^2} - 1\right) < 0.
\]

\section{Causality Violation by Lorentz Transformation}\label{sec:lorentz}
Let \(S'\) move at velocity \(v\in(0,c)\) along \(+x\) relative to \(S\). Lorentz transforming the two events yields
\[
\Delta t' = \gamma\!\left(\Delta t - \frac{v}{c^2}\,\Delta x\right), \qquad
\gamma = \frac{1}{\sqrt{1 - v^2/c^2}}.
\]
Since \(\Delta x>0\) and \(0<\Delta t<\Delta x/c\), choose \(v\) so that
\[
\frac{v}{c} > \frac{c}{u}\quad(\text{equivalently } v > \tfrac{c^{2}}{u}).
\]
Then \(\Delta t' < 0\). Thus there exist inertial frames in which \(D\) occurs before \(E\). Any \(u>c\) implies a frame dependent reversal of time order.

\section{Tachyonic Antitelephone: Two Way Loop}\label{sec:antitelephone}
One can close a loop by having a return superluminal response from \(S'\) back to \(S\) with the same speed \(u\). A standard calculation gives a net reception time in \(S\):
\[
T = \frac{L}{u} + \gamma\,\frac{1 - \frac{u v}{c^2}}{u - v}\,L,
\]
where \(L\) is the one way separation at send time. For sufficiently large \(v\) (specifically \(v > \tfrac{2u}{1+u^2/c^2}\) in units \(c=1\)), \(T<0\): the reply arrives before the original message is sent \cite{benford_1970}. This is Tolman's paradox in operational dress; see also the broader classical review \cite{recami_1986}.

\section{Why Superluminal Massive Objects Would Break Causality}
\label{sec:causality_compromise}
The critical issue with a marble arriving before its light is that it fundamentally breaks the rules of cause and effect. In special relativity, causes must precede their effects, and nothing can travel faster than light without disrupting this universal causal order. The relationship between two events is measured by the interval, which determines if one can causally influence the other. This interval acts like a cosmic traffic light: timelike (green) if causes can connect, null (yellow) for light itself, and spacelike (red) for no causal connection.

If an object moves faster than light, the interval becomes spacelike, meaning the events are not universally connected by cause and effect. Different observers, moving at various speeds, could see the marble arrive at its destination before the moment it was even thrown, completely flipping the order of cause and effect. This is the operational absurdity of seeing the effect (arrival) before the cause (emission). While special relativity allows for tachyons mathematically, they would create these exact causal contradictions, which is the primary reason physicists believe they cannot exist as signaling entities in reality. In short, allowing superluminal travel for massive objects would instantly render the universe inconsistent and unpredictable.

\section{Consequences of an Inconsistent Universe}
\label{sec:unruly_detailed}
If superluminal travel were possible for massive objects, the foundations of physics would fail. Here is a step-by-step breakdown of the resulting breakdown in physical law:

\subsection{Closed Timelike Loops and Causal Paradoxes}
The most dramatic consequence is the formation of closed causal loops, where an effect could happen before its cause. As demonstrated by the tachyonic antitelephone construction, a signal could arrive at its origin before it was ever sent. This leads directly to paradoxes like the grandfather paradox, where changing the past creates a logical contradiction. Physicist Stephen Hawking proposed the chronology protection conjecture, suggesting that the laws of physics fundamentally prevent the formation of such time loops to maintain cosmic consistency \cite{hawking_1992}.

\subsection{Violation of Conservation Laws}
Fundamental principles like the conservation of energy and momentum would be violated. These quantities must remain constant unless acted upon by external forces, a principle rooted in the symmetries of spacetime (Noether's theorem \cite{noether_1918}). However, in a universe with reversed causal order, certain observers could see energy and momentum created from nothing because the events that transfer or conserve them occur in the wrong sequence. This undermines the basic bookkeeping of physical processes.

\subsection{Undermining Determinism and Predictability}
Classical physics relies on determinism: if the initial conditions of a system are known, its future state can be predicted. With faster-than-light travel, information from the future could arbitrarily influence the past, meaning the conditions required for prediction could be spoiled by future choices. This makes a logically consistent evolution of the universe impossible, and the outcome of any experiment could be dependent on events that have not yet occurred.

\subsection{Contradiction with Quantum Field Theory}
Quantum field theory (QFT), which governs the behavior of subatomic particles, enforces microcausality. This rule states that fields at spacelike separated points must commute, meaning a measurement at one location cannot instantly affect a measurement at another, ruling out faster-than-light communication \cite{eberhard_ross_1989}. Superluminal massive particles would violate this core tenet of QFT, allowing instant signaling and breaking the theory's structural integrity.

\subsection{Compromised Empirical Reliability}
Ultimately, the ability to change the past, or for observations to depend on future events, would make scientific testing and measurement unreliable. An experiment's result could be conceptually rewritten after the fact, rendering empirical data ambiguous. For science to function, the timeline of observation must be fixed and immutable.

\section{Timeless Light Model Context}\label{sec:TLMintro}
\subsection{Introduction to the Timeless Light Model}
The Timeless Light Model (TLM) proposes a two layer ontology for physics. At the foundational level lies the Quantum Platform (QP), a timeless instruction set that encodes causal relations outside spacetime. On top of this, the Spacetime Deployment Frame (SDF) is rendered: it is the observable world of relativity, where events appear in sequence, delayed by mass and motion. Photons are treated not as particles in spacetime, but as timeless energy transfer instructions emitted and absorbed without proper time \cite{mckinley_photon_timeless_2025}. Gravity and relativistic time dilation are understood as manifestations of delay in the deployment of QP instructions. The explanatory strength of TLM lies in showing that delay is the unifying concept behind relativistic effects. By treating experience itself as the purpose of delay, the TLM reframes physics around empirical consistency and an economy of causal rendering. Connecting back to empirics, TLM has suggested searching for small residual phase shifts in gravitational wave signals as a diagnostic of rendered sequencing; that program provides a quantitative complement to the paradox analysis here \cite{mckinley_gw_phase_2025}.

\subsection{Glossary of TLM Terms}
\textbf{Quantum Platform (QP):} The timeless instruction layer that encodes causal relations.\\
\textbf{Spacetime Deployment Frame (SDF):} The rendered, mass delayed world of General Relativity where events appear to unfold.\\
\textbf{Delay \(T\):} The rendering slowdown imposed by mass or motion.\\
\textbf{Photon as Instruction:} A timeless energy transfer event with no proper time, emitted and absorbed across frames \cite{mckinley_photon_timeless_2025}.\\
\textbf{Experience Principle:} The idea that delay exists to enable structured experience, analogous to causality in GR.\\

\section{Comparison Table: Luminal vs. Superluminal Signalling}\label{sec:table}
\begin{table}[H]
\centering
\begin{tabular}{@{}lll@{}}
\toprule
\textbf{Property} & \textbf{Luminal / sub-luminal} & \textbf{Superluminal} \\
\midrule
Interval type & Timelike or null & Spacelike \\
Time order in all frames & Preserved & Reversible in some frames \\
Closed causal loops & Impossible (classical) & Possible via antitelephone \\
QFT microcausality & Satisfied & Violated for signalling \\
TLM SDF delay structure & Intact & Collapses (sequencing fails) \\
\bottomrule
\end{tabular}
\caption{Operational contrast between ordinary signalling and hypothetical superluminal signalling.}
\label{tab:luminal_vs_superluminal}
\end{table}

\section{Empirical Relevance and TLM Tests}
\label{sec:empirical}
The ``marble before light'' scenario is a powerful thought experiment that clarifies the essential role of the light barrier in maintaining causality. The principle of $u \le c$ has been rigorously tested through similar physical phenomena. For instance, initial reports suggesting that neutrinos traveled faster than light were later determined to be an experimental error (traced to a loose fiber connection and clock calibration) \cite{opera_2012}. Furthermore, the speed of gravitational waves has been measured to be precisely equal to the speed of light \cite{ligo_2017}.

In our Timeless Light Model (TLM), these consistent speed rules are what preserve the orderly sequencing of the SDF. If empirical evidence were ever to reveal a subtle deviation from this structure—for example, small timing delays in gravitational waves that cannot be accounted for by known relativistic effects—it could provide a diagnostic hint regarding the underlying mechanism of rendered sequencing, aligning with the predictions suggested in our prior work \cite{mckinley_gw_phase_2025}.

\section{Conclusion}\label{sec:conclusion}
Any material propagation at a speed $u>c$ is fundamentally spacelike, which guarantees the existence of an inertial frame where arrival precedes emission. Furthermore, when two-way superluminal signalling is permitted, the system inevitably collapses into $T<0$ and closed causal loops. Therefore, the ``marble before light'' is not a mere theoretical curiosity; it represents a rupture of the universe's essential self-consistency. In TLM language, such superluminal propagation would fundamentally rupture the delay-based sequencing of the Spacetime Deployment Frame (SDF). For empirical follow-up beyond paradoxes, searching for phase shift residual in gravitational wave signals offers a concrete, falsifiable venue aligned with TLM’s rendering perspective \cite{mckinley_gw_phase_2025}.

\section{Appendix A: Rigorous Derivations}\label{sec:appendixA}
\subsection{A.1 Spacelike interval implies time order reversal}\label{subsec:A1}
Given \(\Delta s^2<0\), there exists \(v\in(0,c)\) with
\[
\Delta t'=\gamma\!\left(\Delta t - \frac{v}{c^2}\Delta x\right)<0
\iff v > \frac{c^2\,\Delta t}{\Delta x}.
\]
Since \( \Delta t < \Delta x/c \), the threshold on the right is \(<c\), so such \(v\) exists.

\subsection{A.2 Antitelephone inequality}\label{subsec:A2}
Set \(c=1\) for clarity. Alice in \(S\) sends at \(t=0\) from \(x=0\). Bob in \(S'\) moves at \(v\) and replies immediately with speed \(u>1\). Standard algebra yields total lapse
\[
T = \frac{L}{u} + \gamma\,\frac{1 - u v}{u - v}\,L.
\]
Solving \(T<0\) gives \(v > \tfrac{2u}{1+u^2}\). Restoring \(c\) gives the threshold \(v > \tfrac{2u}{1+u^2/c^2}\).

\section{Appendix B: Minkowski Diagram}\label{sec:appendixB}
\begin{figure}[H]
\centering
\begin{tikzpicture}[scale=1.2]
  % axes
  \draw[->] (-0.5,0) -- (3,0) node[right] {$x$};
  \draw[->] (0,-0.5) -- (0,3) node[above] {$ct$};
  % light cone boundaries (future)
  \draw[dashed] (0,0) -- (2.5,2.5);
  \draw[dashed] (0,0) -- (-2.5,2.5);
  \node at (0.4,2.6) {future light cone};
  % marble trajectory (superluminal)
  \draw[very thick,->] (0,0) -- (2.5,1) node[right] {marble path};
\end{tikzpicture}
\caption{Spacelike marble trajectory outside the light cone; time order reverses in suitable inertial frames.}
\label{fig:minkowski}
\end{figure}



\begin{thebibliography}{99}

\bibitem{einstein_1905}
A. Einstein, \textit{Zur Elektrodynamik bewegter K\"{o}rper}, Ann. Phys. \textbf{17}, 891--921 (1905).
\href{https://doi.org/10.1002/andp.19053221004}{doi:10.1002/andp.19053221004}.

\bibitem{mtw_1973}
C. W. Misner, K. S. Thorne, and J. A. Wheeler, \textit{Gravitation} (W. H. Freeman, 1973), Ch.~8 on causality.
\href{https://www.worldcat.org/isbn/0716703440}{ISBN: 0716703440}.

\bibitem{benford_1970}
G. A. Benford, D. L. Book, and W. A. Newcomb, \textit{The Tachyonic Antitelephone}, Phys. Rev. D \textbf{2}, 263--265 (1970).
\href{https://doi.org/10.1103/PhysRevD.2.263}{doi:10.1103/PhysRevD.2.263}.

\bibitem{eberhard_ross_1989}
P. H. Eberhard and R. R. Ross, \textit{Quantum field theory cannot provide faster than light communication}, Found. Phys. Lett. \textbf{2}, 127--149 (1989).
\href{https://doi.org/10.1007/BF00696109}{doi:10.1007/BF00696109}.

\bibitem{recami_1986}
E. Recami, \textit{Classical Tachyons and Possible Applications (Review)}, La Rivista del Nuovo Cimento \textbf{9}(6), 1--178 (1986).
\href{https://doi.org/10.1007/BF02724327}{doi:10.1007/BF02724327}.

% --- TLM cross-references (cited in body) ---
\bibitem{mckinley_photon_timeless_2025}
J.~C.~W. McKinley, \textit{The Photon as a Timeless, Spaceless Energy Transfer} (2025).
Zenodo. \href{https://doi.org/10.5281/zenodo.16735683}{doi:10.5281/zenodo.16735683}.

\bibitem{mckinley_gw_phase_2025}
J.~C.~W. McKinley, \textit{Falsifiable Prediction of Horizon-Scale Phase Shifts in Gravitational Waves from the Timeless Light Model} (2025).
Zenodo. \href{https://doi.org/10.5281/zenodo.16730926}{doi:10.5281/zenodo.16730926}.

\bibitem{hawking_1992}
S. W. Hawking, \textit{Chronology protection conjecture}, Phys. Rev. D \textbf{46}, 603--611 (1992).
\href{https://doi.org/10.1103/PhysRevD.46.603}{doi:10.1103/PhysRevD.46.603}.

\bibitem{noether_1918}
E. Noether, \textit{Invariante Variationsprobleme}, Nachr. d. K\"{o}nig. Gesellsch. d. Wiss. zu G\"{o}ttingen, Math-phys. Klasse 235--257 (1918).

\bibitem{opera_2012}
OPERA Collaboration, \textit{Measurement of the neutrino velocity with the OPERA detector in the CNGS beam}, JHEP \textbf{10}, 093 (2012).
\href{https://doi.org/10.1007/JHEP10(2012)093}{doi:10.1007/JHEP10(2012)093}.

\bibitem{ligo_2017}
B. P. Abbott et al. (LIGO Scientific Collaboration and Virgo Collaboration), \textit{Gravitational Waves and Gamma-Rays from a Binary Neutron Star Merger: GW170817 and GRB 170817A}, Astrophys. J. Lett. \textbf{848}, L13 (2017).
\href{https://doi.org/10.3847/2041-8213/aa920c}{doi:10.3847/2041-8213/aa920c}.

\end{thebibliography}

\end{document}

```

</details>

---
{% endraw %}
