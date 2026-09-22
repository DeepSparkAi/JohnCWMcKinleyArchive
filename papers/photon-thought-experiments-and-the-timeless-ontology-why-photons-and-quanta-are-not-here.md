---
layout: default
title: '[2025] Photon Thought Experiments and the Timeless Ontology: Why Photons and Quanta Are "Not Here"'
description: 'Publication metadata and archived raw LaTeX source by John C. W. McKinley.'
permalink: /papers/photon-thought-experiments-and-the-timeless-ontology-why-photons-and-quanta-are-not-here/
paper: true
---
{% raw %}
# [2025] Photon Thought Experiments and the Timeless Ontology: Why Photons and Quanta Are "Not Here"
*   **DOI:** [10.5281/zenodo.17216652](https://doi.org/10.5281/zenodo.17216652)
*   **Date:** 27 September 2025

<details markdown="1">
<summary><b>Click to view Raw LaTeX Source</b></summary>

```latex
\documentclass[12pt]{article}

% ---------- Core packages ----------
\usepackage[utf8]{inputenc}
\usepackage{amsmath,amssymb,amsthm}
\usepackage{graphicx}
\usepackage{tcolorbox}
\usepackage{authblk}
\usepackage{geometry}
\geometry{margin=1in}

% ---------- TikZ ----------
\usepackage{tikz}
\usetikzlibrary{arrows.meta,calc,positioning,decorations.pathreplacing,shapes.geometric}

% ---------- Links & References ----------
\usepackage{hyperref}
\hypersetup{colorlinks=true,linkcolor=blue,urlcolor=blue,citecolor=blue}

% ---------- Headers ----------
\usepackage{fancyhdr}
\setlength{\headheight}{15pt}
\pagestyle{fancy}
\fancyhf{}
\lhead{Why Photons and Quanta Are ``Not Here''}
\rhead{\thepage}

% ---------- ORCID ----------
\usepackage{orcidlink}

% ---------- Title ----------
\title{Photon Thought Experiments and the Timeless Ontology:\\
Why Photons and Quanta Are ``Not Here''}
\author{John C.\ W.\ McKinley\,\orcidlink{0009-0005-7097-5035}\\Independent Researcher}
\date{September 27, 2025}

% ---------- Unnumbered / blind footnote helper ----------
\makeatletter
\newcommand\blfootnote[1]{%
  \begingroup
  \renewcommand\thefootnote{}%
  \footnotetext{#1}%
  \addtocounter{footnote}{-1}%
  \endgroup
}
\makeatother

\begin{document}
\maketitle

\blfootnote{This version published at
\href{https://doi.org/10.5281/zenodo.17216652}{https://doi.org/10.5281/zenodo.17216652}.}


\begin{abstract}
In this paper we show, in simple terms, why light cannot be thought of as tiny bullets flying through space, but instead as something stranger that only shows up when it is sent and received. 

We collect and formalize a set of thought experiments that follow from Einstein's observation that massless carriers have no proper time \cite{einstein1905,taylorwheeler}. We show that (i) Newtonian intuition catastrophically contradicts $m_\gamma=0$ unless the photon is interpreted as a non-residing instruction; (ii) relativistic limits (momentum, force to turn) forbid massive, cornering, fast agents \cite{jackson}; (iii) the only consistent picture that preserves conservation, directionality and observed momentum transfer is the theoretical QP$\to$SDF instruction ontology (Timeless Light Model family). We discuss standard objections, give empirical predictions that differentiate the ontological reading from mere semantic relabeling, and append rigorous derivations of the SR relations and limiting arguments used in the main text.

In other words, light and other quanta are not really 'in' the universe between start and finish—-they are better understood as instructions that define, and manifest solely through, the acts of emission and absorption.


\end{abstract}



\section{Introduction}\label{sec:intro}
Einstein's 1905 analysis and the relativistic energy--momentum relation already contain the claim that photons are massless and that null carriers have vanishing proper time \cite{einstein1905,taylorwheeler}. Despite this, mainstream practice often treats the photon as ``a particle'' moving through space (albeit one without a rest frame), or as an excitation of fields between emission and absorption \cite{jackson,griffithsEM}. That pragmatic stance is defensible operationally, but it avoids the ontological consequences of masslessness. Here we press that consequence: if a carrier accrues no proper time, then it cannot be plausibly described as a persisting, local object in the Spacetime Deployment Frame (SDF). Instead it is best described as a timeless instruction recorded on an ontologically prior substrate (Quantum Platform, QP) that renders only at boundary events.

\section{Thought experiments that force the issue}\label{sec:thought}

\subsection{Hiroshima flashlight (reductio ad absurdum)}\label{sec:hiro}
Assume for contradiction that photons have a nonzero rest mass $m_\gamma>0$ but otherwise behave like ordinary corpuscles at velocity $c$. If one attempted to treat light under Newtonian inertia at $v\approx c$, each photon would carry a Newtonian inertial content proportional to $m_\gamma c^2$ and would therefore impart catastrophically large impulses on absorption at ordinary fluxes. Sunlight falling on a surface would then deliver destructive impulses; a flashlight would be an artillery weapon. Empirically, visible light does not do this; sunlight warms, exerts tiny radiation pressure \cite{nichols1901,ashkin1970}, and produces well-understood photoelectric \cite{millikan1916} and Compton effects \cite{compton1923} consistent with $p=E/c$ rather than $p=m_\gamma c$ \cite{taylorwheeler,griffithsEM,wang2024apj,pdg2024}. Modern bounds on the photon mass support this massless reading at extremely tight levels \cite{goldhaber2010,ryutov2007,wang2024apj,pdg2024}.



The reductio is illustrated in Fig.~\ref{fig:hiroshima-flashlight}: the Newtonian projectile model predicts absurd outcomes (crossed out), while the correct, massless instruction picture records only boundary data $(\Delta E,\Delta \mathbf{p})$.

\begin{figure}[ht]
\centering
\begin{tikzpicture}[>=Stealth, x=1cm, y=1cm]
  \node[draw, rounded corners, align=center, minimum width=3.4cm, minimum height=1.4cm] (em) at (0,0) {Emitter\\(source)};
  \node[draw, rounded corners, align=center, minimum width=3.8cm, minimum height=1.6cm] (ab) at (9,0) {Absorber / Detector\\(recoil on absorption)};
  \draw[->, very thick] (em.east) -- node[above, yshift=0.05cm] {$\Delta p^{\mu}=(\Delta E/c,\ \Delta\mathbf{p})$} (ab.west);
  \node[draw, ellipse, align=center, minimum width=3.8cm, minimum height=1.4cm, fill=gray!10] (uptick) at (4.5,1.8) {``Uptick''\\$\Delta E=\hbar\omega$};
  \draw[-{Stealth[length=3mm]}, thick] (uptick.south) .. controls +(0,-0.8) and +(0,0.8) .. ($(em.east)!0.50!(ab.west)$);
  \node[align=left] at (4.5,-1.8) {Newtonian projectile model (wrong at $v=c$):\\
  $\quad p=m v,\ E=\tfrac{1}{2}mv^2\ \Rightarrow$ catastrophic impulses \\ 
  \quad at ordinary fluxes (reductio)};
  \draw[line width=2pt, red] (2.8,-2.6) -- (6.2,-1.0);
  \draw[line width=2pt, red] (2.8,-1.0) -- (6.2,-2.6);
  \node[draw, rounded corners, align=left, fill=green!10, minimum width=6.8cm] at (9,-2.2) {Reality: massless, null carrier.\\
  Momentum transfer on absorption with $p=\Delta E/c=\hbar\omega/c$.};
  \node[align=center] at (4.5,3.1) {\small Instruction picture: boundary data only, no persisting carrier in transit};
\end{tikzpicture}
\caption{Hiroshima flashlight paradox resolved. The naive Newtonian picture of a massive projectile at $v=c$ predicts absurd impulses. The correct, massless picture treats the event as an instruction with boundary data $(\Delta E,\Delta \mathbf{p})$ deposited at absorption.}
\label{fig:hiroshima-flashlight}
\end{figure}

\subsection{No cornering: the infinite force problem}\label{sec:corner}
Consider a massive body of rest mass $m$ traveling at speed $v$ in an inertial frame and suppose one tries to execute a circular turn of radius $r$. In relativistic dynamics the instantaneous required centripetal force scales with the four-momentum; treating momentum as \(p=\gamma m v\) gives
\[
F_{\perp}\sim \frac{p v}{r}=\frac{\gamma m v^2}{r}.
\]
As \(v\to c\), \(\gamma\to\infty\) and the required force diverges \cite{jackson}.  \\



\noindent\textit{Contrast with truly massless quanta.}
The no-cornering divergence applies to \emph{massive} agents as $v\to c$, where $\gamma\to\infty$
forces $F_\perp \propto \gamma v^2/r \to \infty$.
By contrast, truly massless quanta follow null connections with $d\tau=0$, have no rest frame,
and possess no SDF-evolving world-tube to ``steer'' in flight \cite{taylorwheeler,jackson}.
In the TLM reading, their apparent directionality at absorption is endpoint data recorded in the
instruction’s four-momentum component $\Delta p^\mu$ rather than the result of an in-flight turn
(see Sec.~\ref{sec:dir} and Fig.~\ref{fig:instruction-tuple}).




This divergence is plotted in Fig.~\ref{fig:no-cornering}: no finite force can steer a massive near-light traveler through finite-radius turns. The everyday depiction of ``super-fast cornering'' massive beings is physically impossible.

\begin{figure}[ht]
\centering
\begin{tikzpicture}[x=8cm, y=4.5cm]
  \draw[->] (0,0) -- (1.08,0) node[below] {$v/c$};
  \draw[->] (0,0) -- (0,1.10) node[left] {$\propto F_\perp$};
  \draw[dashed] (1,0) -- (1,1.05) node[above, yshift=2pt] {\small $v=c$};
  \node[align=left] at (0.56,0.92) {$F_\perp \ \propto\ \gamma v^2/r$};
  \draw[thick, domain=0:0.98, samples=300]
    plot (\x, { (\x*\x)/sqrt(max(1e-6, 1 - \x*\x)) });
\end{tikzpicture}
\caption{No-cornering limit. For nonzero rest mass, $F_\perp \propto \gamma v^2/r$ diverges as $v\to c$. Maneuverable, near-light massive agents are inconsistent.}



\label{fig:no-cornering}
\end{figure}

\subsection{Directionality without a carrier}\label{sec:dir}
The energy uptick (\(\Delta E=\hbar\omega\)) and the three-vector part of the four-momentum \(\Delta \mathbf{p}\) are boundary data recorded in the instruction:
\[
I=\langle x^\mu_e,x^\mu_a;\Delta p^\mu,\Delta J^{\mu\nu},\Delta Q\rangle.
\]
Fig.~\ref{fig:instruction-tuple} illustrates this minimal tuple: endpoints are recorded, the shove is encoded in $\Delta p^\mu$, and angular/gauge transfers are included if needed (compare the standard mode description in \cite{griffithsEM}).


\begin{figure}[ht]
\centering
\begin{tikzpicture}[>=Stealth, x=1cm, y=1cm]
  \fill[blue!70] (0,0) circle (0.12);
  \node[anchor=east] at (-0.10,0.00) {$x^\mu_e$};
  \fill[red!70] (8,0) circle (0.12);
  \node[anchor=west] at (8.10,0.00) {$x^\mu_a$};
  \draw[->, very thick] (0.15,0.25) -- node[above, yshift=0.05cm] {$\Delta p^\mu=(\Delta E/c,\ \Delta\mathbf{p})$} (7.85,0.25);
  \draw [decorate, decoration={brace, amplitude=6pt}] (0,-0.6) -- (8,-0.6);
  \node at (4,-1.05) {\small realized instruction linking emitter and absorber};
  \node[draw, rounded corners, fill=gray!10, inner sep=2pt, align=center] at (4,1.0)
    {$\Delta J^{\mu\nu}$\\[-1pt]\scriptsize (helicity)};
  \node[draw, rounded corners, fill=gray!10, inner sep=2pt, align=center] at (8.0,1.0)
    {$\Delta Q$};
\end{tikzpicture}
\caption{Minimal instruction tuple. Endpoints $x^\mu_e$ and $x^\mu_a$ are rendered events. Four-momentum $\Delta p^\mu$ encodes both magnitude and direction.}
\label{fig:instruction-tuple}
\end{figure}





\section{Relativistic framework and limiting relations}\label{sec:sr}
We summarize the standard relations used in the argument; derivations appear in Appendix \ref{app:deriv}. The invariant energy--momentum relation
\[
E^2=(pc)^2+(m c^2)^2
\]
and the null proper-time result $d\tau=0$ for massless carriers are textbook facts \cite{taylorwheeler,griffithsEM}.

\section{No-Mass $\Rightarrow$ Not-Here (TLM Lemma)}\label{sec:ontology}
\begin{tcolorbox}[title={Lemma}]
If $m=0$ and $d\tau=0$, then between emission and absorption the entity does not exist as a persisting SDF object; it is an instruction recorded on the Quantum Platform and rendered only at endpoints.
\end{tcolorbox}




\section{Timeless Light Model Framework}\label{sec:TLM}
The Timeless Light Model (TLM) provides an ontological reading of the massless, null-carrier condition. 
Instead of persisting particles moving through spacetime, quanta are realized as instructions 
from an upstream Quantum Platform (QP) to the Spacetime Deployment Frame (SDF). 
Each realized event is specified by an instruction tuple
\[
I=\langle x^\mu_e, x^\mu_a; \Delta p^\mu, \Delta J^{\mu\nu}, \Delta Q\rangle,
\]
linking emission and absorption without requiring a persisting carrier in between 
\cite{gpLaw,photonTimeless,emissionDelay}. 

This reclassification removes contradictions inherent in trying to assign Newtonian or even relativistic 
mass-based persistence to photons. Radiation pressure, photoelectric emission, and Compton scattering 
are fully compatible with this instruction ontology: what transfers is boundary data, not a persisting object. 
The TLM is thus both conservative (all standard predictions remain intact) and radical 
(it rejects the tacit assumption that photons ``exist in flight''). 
In this view, Einstein’s 1905 observation ($d\tau=0$ for null carriers \cite{einstein1905}) is not 
just a mathematical curiosity, but an ontological clue: no time elapses because there is no 
carrier persisting in spacetime.



\section{Glossary}
\begin{description}
  \item[Quantum Platform (QP):] Ontologically senior layer that records and issues instructions for physical events. 
  Not directly observable, but inferred from the timeless and massless properties of photons \cite{photonTimeless}.
  
  \item[Spacetime Deployment Frame (SDF):] The rendered layer where instructions appear as events governed by 
  General Relativity and Quantum Mechanics. Delay and mass are properties of deployment, not of the QP \cite{emissionDelay}.
  
  \item[Instruction Tuple:] The minimal record linking emitter and absorber:
  \(I=\langle x^\mu_e, x^\mu_a;\Delta p^\mu,\Delta J^{\mu\nu},\Delta Q\rangle\). 
  Specifies boundary data for realized quanta, without an intermediate carrier \cite{gpLaw}.
  
  \item[No-Mass $\Rightarrow$ Not-Here Lemma:] If a quantum has zero rest mass and $d\tau=0$, it does not exist as a persisting 
  object in SDF but only as an instruction connecting events. This is the central TLM claim.
  
  \item[Delay:] The observable manifestation of mass or curvature that slows deployment of instructions into SDF. 
  In TLM, mass is equivalent to delay in rendering \cite{emissionDelay}.
\end{description}




\section{Criticisms and replies}\label{sec:critics}
Critics call this semantics: QED is predictive, so ontology is optional \cite{jackson}. Reply: ontology matters when it clarifies paradoxes and motivates tests. Null worldlines can be called ``paths,'' but the instruction view avoids contradictions and reframes nonlocal puzzles without extra structure.

\section{Proposed Laboratory Tests}\label{sec:exp}
\subsection{Latency invariance}
Use a tunable single-photon source and fixed-geometry absorber/detector. Prediction: detection latency distribution invariant under $\Delta E$ (until absorber thresholds change channels).

\subsection{Absorber--condition dependence}
Use saturable absorbers or metamaterials with tunable resonances. Prediction: realized emission rates correlate with absorber condition; no orphan photons (contrast operational expectations in standard pictures \cite{griffithsEM}).

\noindent\emph{Continuity with prior tests.}
For continuity with our earlier proposals, the same instruction-centric logic underlies the
gravitational-wave phase–shift tests outlined in \cite{gwPhaseShift}, which probe whether
endpoint-only instruction rendering leaves a distinct imprint on interferometric phase evolution.


\section{Conclusion}\label{sec:conc}
Massless quanta do not persist in SDF. They are best read as QP instructions linking events. The figures (Figs.~\ref{fig:hiroshima-flashlight}--\ref{fig:instruction-tuple}) show how the reductio, the no-cornering limit, and the instruction tuple reinforce this conclusion. This pushes the accepted math (\(d\tau=0\)) to its ontological end-point rather than stopping at formalism \cite{einstein1905,taylorwheeler}.

\appendix
\section{Derivations and formal limits}\label{app:deriv}
\subsection{Four--momentum}
Define $p^\mu=(E/c,\mathbf{p})$, with invariant $p^\mu p_\mu=(mc)^2$. For $m=0$, $E=pc$ \cite{taylorwheeler}.

\subsection{Null geodesic}
$ds^2=0 \Rightarrow d\tau=0$. No rest frame for $m=0$ \cite{taylorwheeler}.

\subsection{Covariant force}
For transverse turning, $F_\perp=\gamma m v^2/r\to\infty$ as $v\to c$ \cite{jackson}.

\begin{thebibliography}{99}

% Foundational SR
\bibitem{einstein1905}
A.~Einstein, ``Zur Elektrodynamik bewegter K{\"o}rper,'' \emph{Annalen der Physik}, 17, 891--921 (1905).

\bibitem{taylorwheeler}
E.~F.~Taylor and J.~A.~Wheeler, \emph{Spacetime Physics}, 2nd ed., W.~H.~Freeman (1992).

% Textbook EM / QED-level operational stance
\bibitem{jackson}
J.~D.~Jackson, \emph{Classical Electrodynamics}, 3rd ed., Wiley (1998).

\bibitem{griffithsEM}
D.~J.~Griffiths, \emph{Introduction to Electrodynamics}, 4th ed., Pearson (2013).

% Classic experiments demonstrating momentum/energy transfer of light
\bibitem{nichols1901}
E.~F.~Nichols and G.~F.~Hull, ``A Preliminary Communication on the Pressure of Heat and Light Radiation,'' \emph{Phys.\ Rev.} \textbf{13}, 307--320 (1901).

\bibitem{ashkin1970}
A.~Ashkin, ``Acceleration and Trapping of Particles by Radiation Pressure,'' \emph{Phys.\ Rev.\ Lett.} \textbf{24}, 156--159 (1970).

\bibitem{millikan1916}
R.~A.~Millikan, ``A Direct Photoelectric Determination of Planck's $h$,'' \emph{Phys.\ Rev.} \textbf{7}, 355--388 (1916).

\bibitem{compton1923}
A.~H.~Compton, ``A Quantum Theory of the Scattering of X-Rays by Light Elements,'' \emph{Phys.\ Rev.} \textbf{21}, 483--502 (1923).

% Photon mass bounds (reviews and representative analyses)
\bibitem{goldhaber2010}
A.~S.~Goldhaber and M.~M.~Nieto, ``Photon and Graviton Mass Limits,'' \emph{Rev.\ Mod.\ Phys.} \textbf{82}, 939--979 (2010).

\bibitem{ryutov2007}
D.~D.~Ryutov, ``Using plasma physics to weigh the photon,'' \emph{Plasma Phys.\ Control.\ Fusion} \textbf{49}, B429 (2007).



% Recent/authoritative photon-mass limits
\bibitem{pdg2024}
Particle Data Group, ``\emph{Photon (}\,$\gamma$\emph{) listing}'' in \emph{Review of Particle Physics},
Phys.\ Rev.\ D \textbf{110}, 030001 (2024).
PDF: \href{https://pdg.lbl.gov/2024/listings/rpp2024-list-photon.pdf}{pdg.lbl.gov (2024)}.

\bibitem{wang2024apj}
Y.-B.~Wang, X.~Zhou, A.~Kurban, F.-Y.~Wang,
``Bounding the Photon Mass with Ultrawide Bandwidth Pulsar Timing Data and Dedispersed Pulses of Fast Radio Bursts,''
\emph{Astrophysical Journal} \textbf{965}, 38 (2024).
arXiv:\href{https://arxiv.org/abs/2403.06422}{2403.06422}.
% Reports an optimum upper bound m_\gamma \lesssim 9.52\times 10^{-46}\,\mathrm{kg} = 5.34\times 10^{-10}\,\mathrm{eV}/c^2.



% ---- Timeless Light Model works (TLM) ----
\bibitem{photonTimeless}
J.~C.~W.~McKinley, \textit{The Photon as a Timeless, Spaceless Energy Transfer} (2025).
Zenodo. \href{https://doi.org/10.5281/zenodo.16735683}{doi:10.5281/zenodo.16735683}.


\bibitem{emissionDelay}
J.~C.~W.~McKinley, \textit{The Emission Delay Law: A General Principle for the Realization of Quanta in the Timeless Light Model} (2025).
Zenodo. \href{https://doi.org/10.5281/zenodo.17032235}{doi:10.5281/zenodo.17032235}.

\bibitem{gpLaw}
J.~C.~W.~McKinley, \textit{Generalized Pairing Law: No Quantum Emission Without an Absorber} (2025).
Zenodo. \href{https://doi.org/10.5281/zenodo.16893165}{doi:10.5281/zenodo.16893165}.

% ---- GW phase-shift continuity item you reference in Sec. \ref{sec:exp} ----
\bibitem{gwPhaseShift}
J.~C.~W.~McKinley, \textit{Falsifiable Prediction of Horizon-Scale Phase Shifts in Gravitational Waves from the Timeless Light Model} (2025).
Zenodo. \href{https://doi.org/10.5281/zenodo.16730926}{doi:10.5281/zenodo.16730926}.




\end{thebibliography}

\end{document}

```

</details>

---
{% endraw %}
