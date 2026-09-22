---
layout: default
title: '[2025] The One Blind Spot That Hid Three Simple Solutions: A Testable Reinterpretation of Photon Ontology Outside Spacetime'
description: 'Publication metadata and archived raw LaTeX source by John C. W. McKinley.'
permalink: /papers/the-one-blind-spot-that-hid-three-simple-solutions-a-testable-reinterpretation-of-photon/
paper: true
---
{% raw %}
# [2025] The One Blind Spot That Hid Three Simple Solutions: A Testable Reinterpretation of Photon Ontology Outside Spacetime
*   **DOI:** [10.5281/zenodo.16871293](https://doi.org/10.5281/zenodo.16871293)
*   **Date:** 14 August 2025

<details markdown="1">
<summary><b>Click to view Raw LaTeX Source</b></summary>

```latex

\documentclass[12pt,letterpaper]{article}

% ====== Packages & Setup ======
\usepackage[margin=1in]{geometry}
\usepackage[utf8]{inputenc}
\usepackage[T1]{fontenc}
\usepackage{lmodern}
\usepackage{microtype}
\usepackage{tabularx}
\newcolumntype{Y}{>{\raggedright\arraybackslash}X}
\usepackage{adjustbox} % for robust width control of figures


\usepackage{amsmath,amssymb,amsthm,mathtools}
\usepackage{bm}
\usepackage{siunitx}
\sisetup{separate-uncertainty=true}
\usepackage{graphicx}
\usepackage{booktabs}
\usepackage{enumitem}
\usepackage{array}
\usepackage{multirow}
\usepackage{hyperref}

 \hypersetup{colorlinks=true, linkcolor=blue,urlcolor=blue, citecolor=blue, filecolor=black}

% TikZ / PGF for figures (journal-sharp with restrained color for preprint)
\usepackage{tikz}
\usetikzlibrary{arrows.meta,positioning,fit,calc,shapes,decorations.pathreplacing}
\tikzset{
  >={Latex[length=3mm]},
  box/.style={draw,line width=0.8pt,rounded corners=2pt,inner sep=6pt,align=center},
  sharp/.style={draw,line width=0.8pt,rounded corners=0.5pt},
  note/.style={font=\footnotesize\itshape},
  precolor1/.style={fill=blue!6,draw=blue!50!black},
  precolor2/.style={fill=orange!9,draw=orange!60!black},
  precolor3/.style={fill=yellow!12,draw=yellow!50!black},
  precolor4/.style={fill=green!10,draw=green!60!black}
}
\usepackage{pgfplots}
\pgfplotsset{compat=1.18}

% Theorem environments
\newtheorem{theorem}{Theorem}
\newtheorem{proposition}{Proposition}

% Inline boxes
\usepackage{tcolorbox}
\tcbset{colframe=black,colback=gray!6,boxrule=0.6pt,arc=1pt,left=6pt,right=6pt,top=6pt,bottom=6pt}

% Title
\title{\Large\bfseries The One Blind Spot That Hid Three Simple Solutions:\\
\large A Testable Reinterpretation of Photon Ontology Outside Spacetime}
\author{\normalsize John C. W. McKinley\\
\normalsize Independent Researcher\\
\normalsize ORCID: \href{https://orcid.org/0009-0005-7097-5035}{0009-0005-7097-5035}}
\date{\normalsize August 14, 2025}

\begin{document}
\maketitle


\renewcommand{\thefootnote}{}
% New DOI
\footnotetext{This version v1.0 published at \href{https://doi.org/10.5281/zenodo.16871293}{https://doi.org/10.5281/zenodo.16871293}.}

\begin{abstract}
\noindent
Mainstream physics treats the photon as a massless quantum propagating on null geodesics, with $\tau=0$ a kinematic feature. We propose a \emph{reinterpretation} motivated by a single tacit stance: the assumption that nothing exists outside the universe. Enforcing this non-empirical stance creates tension with Special Relativity’s (SR) photon invariants. Dropping it yields three consequences already implicit in SR: (i) \emph{timeless} implies \emph{spaceless} for photons; (ii) the pathfinding question dissolves (no in-transit state to ``know''); (iii) the photon is better modeled as a correlation (instruction) resolved outside spacetime and \emph{rendered} into the observable frame. We develop a two-layer picture: a timeless, spaceless \emph{Quantum Platform} (QP) \cite{mckinley2025spacelessness} issuing instructions and a \emph{Spacetime Deployment Frame} (SDF) where events appear. We front-load a boxed ``live by the math / die by the math'' chain, a compact theorem from $\tau=0$ to no space, and two figures (logic flow; absorption-front rendering). To avoid mere metaphysics, we add quantitative predictions (explicit formulas, orders of magnitude, comparison table with detection methods and current bounds), discuss tight empirical limits, and indicate non-timing tests if timing residuals are too small. Appendices supply a ready-reference glossary, derivations, and falsifiability protocols.
\end{abstract}

\vspace{-0.6em}
\section*{What is new in this paper (for expert readers)}
\begin{itemize}[leftmargin=1.25em,itemsep=0.3em]
  \item \textbf{Blind-spot reframing (as an existing metaphysical stance):} ``nothing outside the universe'' is non-empirical; it conflicts with SR photon invariants.
  \item \textbf{Live-by-the-math / die-by-the-math chain} (boxed) that forces the non-traveler reading if SR is retained.
  \item \textbf{No-time $\Rightarrow$ no-space theorem} stated and proved.
  \item \textbf{Quantitative section:} explicit $\delta t$ formulas, $\delta t$--$L_{\rm geom}$ plot, and a comparison table with detection methods and bounds.
  \item \textbf{Clarified absorption-frame front:} a \emph{rendering boundary} in the SDF, not a moving object; labeled color TikZ.
  \item \textbf{Counterarguments addressed:} $\tau=0$ minimalism, QED loops, CMB spectrum; empirical bounds and next-step tests.
\end{itemize}

% ================================
\section{Introduction: the blind spot and the logic it hides}
\label{sec:intro}
\textbf{Blind spot.} Standard physics has tacitly adopted a metaphysical axiom without proof: the universe is causally closed and nothing exists outside it. Enforcing this stance produces an avoidable tension with the accepted SR statement that photons have $\tau=0$ and no rest frame.

\paragraph{Compatibility with the Standard Model.}
This model does \emph{not} replace or diminish Standard Model results (including the Higgs field). It adds an ontologically senior explanatory layer that addresses phenomena often described as nonlocal or instantaneous while leaving all in-frame physics intact.

\subsection{Live by the math / die by the math}
\begin{tcolorbox}
\textbf{SR photon chain.}
\begin{enumerate}[label=(\roman*),leftmargin=1.5em]
  \item $v=c$ for photons; $\gamma^{-1}=\sqrt{1-v^2/c^2}\to0$; \emph{no rest frame}.
  \item Invariant interval: $s^2=c^2\Delta t^2-\Delta \bm{x}^2$;\quad $\tau=\frac{s}{c}$.
  \item Photon: $\tau=0\ \Rightarrow\ s^2=0$ (null); ``distance traveled'' is \emph{not} an invariant.
  \item No proper time $\Rightarrow$ no change in photon invariants; no intrinsic in-between state in spacetime.
\end{enumerate}
Either accept these conclusions (and drop the traveler ontology) or alter SR. There is no consistent middle ground.
\end{tcolorbox}

\subsection{No time $\Rightarrow$ no space: a two-step theorem}
We formalize this as a theorem to highlight the interpretation of SR invariants:
\begin{theorem}[No-time $\Rightarrow$ No-space for null entities]\label{thm:notime-nospace}
Let $A,B$ be emission and absorption events for a null entity in Minkowski spacetime. If the entity’s proper time between $A$ and $B$ is $\tau=0$, then $s^2(A,B)=0$, implying no invariant spacetime separation attributable to the entity; any ``distance'' is a coordinate artifact of subluminal observers.
\end{theorem}
\begin{proof}
In any inertial frame, $s^2=c^2\Delta t^2-\Delta \bm{x}^2$. If $\tau=s/c=0$, then $s^2=0$ and $c^2\Delta t^2=\Delta \bm{x}^2$. Because $s$ is invariant and vanishes, the entity’s own invariants register no spacetime separation; only external coordinate descriptions assign a path length. As no photon rest frame exists, ``photon’s frame'' is shorthand for its invariants admitting no elapsed time or intrinsic spatial extent between $A$ and $B$. \qedhere
\end{proof}

\subsection{Logical progression from blind spot to solution}
\begin{figure}[h]
\centering
\begin{tikzpicture}[
  node distance=8mm,
  box/.style={draw, line width=0.8pt, rounded corners=2pt, inner sep=6pt, align=center, text width=0.92\linewidth},
  arrow_label/.style={midway, fill=white, inner sep=2pt, font=\small},
  precolor1/.style={fill=blue!6, draw=blue!50!black},
  precolor2/.style={fill=orange!9, draw=orange!60!black},
  precolor3/.style={fill=yellow!12, draw=yellow!50!black},
  precolor4/.style={fill=green!10, draw=green!60!black}
]
% Nodes
\node[box, precolor1] (blind) {\textbf{Blind spot:} ``Nothing is outside the universe''};
\node[box, precolor2, below=of blind] (force) {Forced narrative: photon must be an \emph{in-spacetime traveler}};
\node[box, precolor3, below=of force] (miss) {Missed consequences: (1) $\tau=0 \Rightarrow s^2=0 \Rightarrow$ no space; (2) no pathfinding paradox; (3) photon \emph{not} in the universe};
\node[box, precolor4, below=of miss] (qp) {\textbf{Reinterpretation:} Two-layer ontology\\ Quantum Platform (timeless, spaceless instructions) $\to$ SDF (rendered events with delay)};

% Arrows with labels placed on the path to prevent horizontal overflow
\draw[->, thick] (blind) -- node[arrow_label] {assumption enforces} (force);
\draw[->, thick] (force) -- node[arrow_label] {contradictions glossed} (miss);
\draw[->, thick] (miss) -- node[arrow_label] {requires bridge} (qp);
\end{tikzpicture}
\caption{\textbf{Causal chain from premise to prediction.} Dropping the blind spot reveals consequences implied by SR and motivates a QP+SDF reinterpretation that yields specific tests.}
\label{fig:logic}
\end{figure}


\subsection{Absorption-frame front: a rendering boundary, not a traveler}
\textbf{Definition.} The \emph{absorption-frame front} is \underline{not} a moving object in spacetime. It is a \emph{rendering boundary} in the SDF: the locus where a timeless QP instruction becomes manifest as an absorption-event family under causal constraints. Analogy: a GPU draws a line whose data (start, end, color) already exists in memory (QP). The moving edge of drawn pixels is the \emph{rendering front} (SDF). Nothing physical ``moves'' through a void; only the manifestation boundary advances at the causal speed limit.

\begin{figure}[h]
\centering
\begin{tikzpicture}[scale=1.03]
% SDF rectangle
\draw[sharp] (0,0) rectangle (11.4,5.0);
\node[anchor=west] at (0.15,4.75) {\small Spacetime Deployment Frame (SDF)};

% QP outside (ellipse)
\draw[sharp,dashed] (5.7,6.6) ellipse (3.0 and 1.0);
\node at (5.7,6.6) {\small Quantum Platform (QP)};

% Events
\fill (1.7,1.1) circle (1.3pt); \node[anchor=south west] at (1.75,1.1) {\footnotesize Emission $E$};
\fill (9.3,3.6) circle (1.3pt); \node[anchor=south east] at (9.35,3.6) {\footnotesize Absorption $A$};

% Instruction arrows with labels (explicit)
\draw[->,thick] (5.7,6.6) -- node[above left]{\footnotesize instruction map} (1.7,1.1);
\draw[->,thick] (5.7,6.6) -- node[above right]{\footnotesize instruction map} (9.3,3.6);

% Absorption front circles with label
\draw[sharp,blue!60] (9.3,3.6) circle (0.9);
\draw[sharp,blue!60] (9.3,3.6) circle (1.7);
\draw[->,blue!70] (10.6,2.15) -- node[above]{\footnotesize front advances} (10.0,2.9);
\node[note,anchor=west] at (10.65,2.1) {rendering boundary at $c$};

% Lightlike visual from E (annotated)
\draw[gray!70,densely dashed] (1.7,1.1) -- node[above]{\footnotesize SDF null directions} (4.2,3.6);
\draw[gray!70,densely dashed] (1.7,1.1) -- (2.5,0.3);
\end{tikzpicture}
\caption{\textbf{Bridge from QP to SDF.} QP instruction links $(E,A)$; the absorption-frame front is a \emph{rendering boundary} (not a traveler). The caption states the causal interpretation to avoid misreading.}
\label{fig:front}
\end{figure}

% ================================
\section{Quantitative predictions and tests}\label{sec:quant}
To move beyond semantics, we parameterize the hypothesized rendering overhead as a small, dimensionless $\alpha_\star$ multiplying the geometric light-path $L_{\rm geom}$ (meters). The induced, achromatic timing offset is modeled as
\begin{equation}
\delta t_{\rm TLM} \;\approx\; \frac{\alpha_\star}{c}\, L_{\rm geom},
\label{eq:deltaT}
\end{equation}
with $\alpha_\star \ll 1$ and independent of frequency $\nu$. This supplements (does not replace) standard propagation effects (geometric + Shapiro + plasma dispersion).

\subsection{Order-of-magnitude examples}
\paragraph{Galaxy–cluster lens (quasar double).}
$L_{\rm geom}\sim \SI{1e22}{m}$ (tens of kpc through the lens) $\Rightarrow$
$\delta t_{\rm TLM} \sim \alpha_\star \times \SI{3.3e13}{s}$; thus $\delta t\sim \SI{1e-13}{s}$ implies $\alpha_\star \sim 3\times 10^{-27}$.

\paragraph{Milky Way ISM segment (FRB line-of-sight).}
$L_{\rm geom}\sim \SI{1e20}{m}$ (few kpc) $\Rightarrow$
$\delta t_{\rm TLM} \approx \alpha_\star \times \SI{3.3e11}{s}$; a $\SI{1e-15}{s}$ residual also corresponds to $\alpha_\star \sim 3\times 10^{-27}$.

\paragraph{PTA per-Mpc bound (illustrative).}
Phenomenological bounds from PTA residuals imply $\delta t \lesssim \SI{1e-6}{s}$ over ~kpc paths, constraining $\alpha_\star \lesssim 3\times 10^{-18}$ for ISM segments; target shorter baselines for detection.

\subsection{Comparison with standard expectations}

\begin{table}[t]
\centering
\setlength{\tabcolsep}{4pt}
\renewcommand{\arraystretch}{1.15}
\caption{Predicted observables: GR/QED vs.\ TLM (QP+SDF). “Achromatic” means independent of $\nu$ after removing plasma dispersion. Bounds are illustrative and system-dependent.}
\begin{tabularx}{\linewidth}{@{}Y Y Y Y Y@{}}
\toprule
\textbf{Observable}
& \textbf{Standard (GR/QED)}
& \textbf{TLM (QP+SDF)}
& \textbf{Detection Method}
& \textbf{Current Bounds} \\
\midrule
Strong-lens delays
& Geometric + Shapiro; achromatic except $\mathrm{DM}\!\propto\!\nu^{-2}$; no extra common-mode term
& Same + small \emph{achromatic}, geometry-independent $\delta t_{\rm TLM}=(\alpha_\star/c)L_{\rm geom}$ across images
& VLBI timing; time-delay cosmography
& System-dependent; targets $\lesssim\!\SI{1e-13}{s}$ \\
\addlinespace[0.25em]
FRB multi-band arrival
& Dispersion $\propto \mathrm{DM}\,\nu^{-2}$; scattering/plasma lensing
& Same + residual \emph{achromatic} offset after dispersion removal; scales with $L_{\rm geom}$
& Co-located multi-band receivers; coherent dedispersion
& Sub-$\mu$s floors; targets $\lesssim\!\SI{1e-12}{s}$ \\
\addlinespace[0.25em]
GW strain residuals
& After GR best-fit, residuals noise-like; glitches instrument-specific
& Small, coherent \emph{stepwise} residuals from discrete rendering units; cross-detector coincidence
& LVK GWTC residual analysis (CUSUM/changepoint)
& No established steps; set upper limits \\
\bottomrule
\end{tabularx}

\vspace{0.3em}
\begingroup
\footnotesize
\emph{Note:} PTA residual RMS typically $\sim$100\,ns–1\,$\mu$s (e.g., NANOGrav 15yr \cite{Agazie2023}, EPTA DR2 \cite{Antoniadis2023}); not yet optimized for explicit achromatic common-mode searches.
\endgroup
\label{tab:compare}
\end{table}

% ==== I have removed the erroneous \footnotetext command that was here ====

\subsection{Why these follow from the model (causal links)}
\begin{itemize}[leftmargin=1.25em]
  \item \textbf{Achromatic residuals} arise \emph{because} the $E\!\leftrightarrow\!A$ connection is a timeless instruction; with no in-medium traveler, only rendering overhead remains, independent of $\nu$ (after DM removal).
  \item \textbf{No in-flight evolution} arises \emph{because} there is no in-spacetime photon state between $E$ and $A$; endpoint correlations saturate under single-absorber post-selection.
  \item \textbf{Stepwise GW residuals} arise \emph{because} geometry is rendered; minimal instruction quanta produce coherent steps after subtracting continuous GR templates.
\end{itemize}

\subsection{Plot: $\delta t$ vs.\ $L_{\rm geom}$ for representative $\alpha_\star$}

\begin{figure}[h]
\centering
\begin{tikzpicture}
\begin{axis}[
    width=0.9\textwidth, height=6.5cm,
    xlabel={$L_{\rm geom}$ (m)},
    ylabel={$\delta t$ (s)},
    xmode=log, ymode=log,
    grid=both,
    minor grid style={gray!20},
    major grid style={gray!30},
    legend style={at={(0.03,0.03)},anchor=south west,draw=none,fill=none},
    tick align=outside,
]
% Three alpha curves: delta t = (alpha/c)*L
\addplot+[thick,domain=1e18:1e23] {3.333333e-36 * x};
\addlegendentry{$\alpha_\star=10^{-27}$}

\addplot+[thick,dashed,domain=1e18:1e23] {3.333333e-39 * x};
\addlegendentry{$\alpha_\star=10^{-30}$}

\addplot+[thick,densely dotted,domain=1e18:1e23] {3.333333e-42 * x};
\addlegendentry{$\alpha_\star=10^{-33}$}

\end{axis}
\end{tikzpicture}
\caption{\textbf{Causal visualization:} rendering overhead predicts $\delta t \propto L_{\rm geom}$ with slope set by $\alpha_\star/c$. Curves for $\alpha_\star=10^{-27},10^{-30},10^{-33}$ span regimes discussed in text. Illustrates mapping experimental baselines to target sensitivities.}
\label{fig:dtplot}
\end{figure}

\paragraph{Open datasets for self-analysis.}
Public data enable immediate tests: LVK GWTC residuals (for step detection), FRB multi-band archives (for achromatic residuals), strong-lens time-delay compilations (for common-mode offsets).

% ================================
\section{Counterarguments and relations to standard theory}
\subsection{``$\tau=0$ is kinematic; ontology shift unnecessary.''}
Response: Theorem~\ref{thm:notime-nospace} is SR-invariant; it states what \emph{is not} present in photon invariants (no time, no space). Traveler language is an \emph{extra} assumption tied to the blind spot. Our proposal reinterprets propagation while keeping standard calculations intact.

\subsection{QED loops and self-interactions}
QED loop corrections (vacuum polarization, vertex functions) are SDF-bound field-theoretic processes; QP reinterprets only \emph{between-vertex} propagation. Renormalized amplitudes and cross sections are unchanged \cite{FeynmanQED,PeskinSchroeder}.

\subsection{CMB blackbody spectrum}
Planck’s law $u(\nu,T)=\frac{8\pi h\nu^3}{c^3}\frac{1}{e^{h\nu/kT}-1}$ arises from SDF thermodynamics (BE statistics over mode density $8\pi\nu^2/c^3$). TLM’s rendering delay is achromatic and does not alter mode counting or BE weights; hence the CMB spectrum remains unchanged.

\subsection{Relation to relational/transactional ideas}
The reinterpretation echoes Rovelli’s relational stance (states relative to interactions) \cite{RovelliRQM} and Wheeler–Feynman/Cramer transactional themes, but differs by providing \emph{quantified} achromatic offsets and GW residual signatures (Tables~\ref{tab:compare}, Fig.~\ref{fig:dtplot}) as falsifiable outputs \cite{Cramer1986,WF1945}.

% ================================
\section{Discussion: speculation, empirical bounds, and next steps}
\paragraph{Phenomenology vs.\ dynamics.}
$\alpha_\star$ is presently phenomenological; a future rendering term in a Lagrangian (e.g., an instruction-rate functional) would formalize QP/SDF dynamics. For now, we infer $\alpha_\star$ empirically. While QP is a minimal, unobserved extension (akin to transactional models), it resolves SR tensions without new evidence yet.

\paragraph{Tight bounds and feasibility.}
If per-Mpc timing bounds imply $\alpha_\star\lesssim 10^{-33}$, then timing searches must leverage extreme baselines and precision. Nevertheless, \emph{non-timing} probes remain viable.

\subsection{Pivot to non-timing tests if needed}\label{sec:pivot}
\begin{itemize}[leftmargin=1.25em]
  \item \textbf{GW phase and step residuals:} seek coherent steps in LVK residuals via CUSUM/changepoint with cross-detector coincidence.
  \item \textbf{Interferometric phase stabilities:} look for achromatic, geometry-locked phase offsets at $<\SI{1e-13}{s}$ scales.
  \item \textbf{Lensing Fermat-surface structure:} search for common-mode offsets post-model across multiply imaged systems.
\end{itemize}

% ================================
\section{Conclusion}
We do not claim to \emph{prove} an ultimate ontology; rather, we propose a testable \emph{reinterpretation} that removes a long-standing inconsistency: SR’s $\tau=0$ for photons is incompatible with traveler language unless one adds a metaphysical assumption (causal closure of spacetime). Dropping that blind spot yields three simple consequences and motivates a QP+SDF picture with concrete, falsifiable predictions. Appendices provide a ready-reference so readers need not consult prior work.

% ================================
\appendix
\section*{Appendices: ready-reference for expert readers}
\addcontentsline{toc}{section}{Appendices: ready-reference for expert readers}

\section{Glossary (self-contained)}\label{app:gloss}
\begin{description}[leftmargin=1.1em,style=nextline]
  \item[Quantum Platform (QP).] Timeless, spaceless substrate on which causal instructions are resolved; only \emph{successful} resolutions are recorded.
  \item[Spacetime Deployment Frame (SDF).] Observable layer where QP instructions render with delay; GR/QM equations govern deployment relations.
  \item[Instruction (CI-ARC).] Event-to-event linkage $(E,A)$ resolved on QP; no in-spacetime in-flight state exists; renders as correlated endpoints.
  \item[Absorption-frame front.] SDF rendering boundary that expands at $c$, consistent with causal horizons; gives the appearance of propagation without traveler ontology.
  \item[Single-absorber principle.] One instruction resolves to exactly one absorber.
\end{description}

\section{Derivations (compact, citable in debate)}\label{app:deriv}
\subsection{SR invariants for photons}
$s^2=c^2\Delta t^2-\Delta \bm{x}^2$;\quad $\tau=s/c$. Photons: $\tau=0\Rightarrow s^2=0$; no rest frame (Lorentz boost undefined at $v=c$) \cite{Einstein1905,Wald}. Coordinate distances are not invariants for null separations.

\subsection{Optical metric and Fermat functional (for lensing tests)}
In static spacetimes with $ds^2=-V^2dt^2+h_{ij}dx^idx^j$, define $n=1/V$ and optical metric $\tilde h_{ij}=n^2h_{ij}$; travel-time functional $T[\gamma]=\int_\gamma n\,d\ell_h$ extremizes on geodesics of $(\Sigma,\tilde h)$ \cite{SchneiderEhlersFalco}. Standard models predict geometry-only delays; QP endpoint deployment predicts an \emph{additional achromatic} residual $\delta t_{\rm TLM}$ (Sec.~\ref{sec:quant}).

\subsection{SR twin-leg offset (for absorption-frame analogies)}
For two legs of different velocities $v_{\rm slow},v_{\rm fast}$ over coordinate time $T_{\rm leg}$:
\[
\Delta\tau = T_{\rm leg}\Big(\gamma^{-1}(v_{\rm slow})-\gamma^{-1}(v_{\rm fast})\Big) > 0,
\]
a forward-only offset with no retrocausality.

\subsection{Numerical anchors (units via \texttt{siunitx})}
\[
\kappa \approx \SI{0.9}{} \quad (\text{dimensionless}), \qquad
m_p \approx \SI{938}{MeV/c^2}.
\]

\subsection{GW microstructure residual model}
Let $h_{\rm GR}(t)$ be best-fit continuous strain. Suppose SDF renders instruction steps $\Delta h$ at times $t_n$, so $h(t)=\sum_n \Delta h\,\Theta(t-t_n)$. Residual $r(t)=d(t)-h_{\rm GR}(t)$ may exhibit stepwise segments detectable by CUSUM/changepoint, cross-validated across detectors.

\section{Falsifiability protocols (expanded)}\label{app:fals}
\subsection{Achromatic residuals in strong lensing}
\textbf{Data:} multi-band lensed quasars/FRBs with precise time delays. \textbf{Pipeline:}
(i) remove plasma dispersion; (ii) fit standard lens model (optical metric); (iii) test for geometry-independent $\delta t_{\rm TLM}$ across images/events; (iv) cross-compare systems for common-mode residuals. \textbf{Prediction:} small, stable $\delta t_{\rm TLM}$ (e.g., $\sim\SI{1e-15}{}$--$\SI{1e-13}{s}$ on VLBI-quality baselines) common to images after systematics. \textbf{Falsifier:} consistent null $\delta t$ bounds below the predicted scale across diverse systems.

\subsection{No in-flight evolution for single-photon channels}
\textbf{Setup:} heralded single-photon experiments with strict one-absorber post-selection; tight temporal gating; low-loss paths. \textbf{Prediction:} endpoint correlations saturate; no intermediate evolution beyond detector noise/systematics. \textbf{Falsifier:} reproducible intermediate-state signatures inconsistent with endpoint-only rendering.

\subsection{GW stepwise residual search}
\textbf{Events:} high-SNR BBH/BNS. \textbf{Method:} fit GR template, compute residuals, apply step-detection, require cross-detector coincidence in step times/heights, control for glitches. \textbf{Prediction:} upper bounds trend toward discrete $\Delta h$; discovery if coherent steps exceed noise expectations with astrophysical consistency. \textbf{Falsifier:} stringent null bounds excluding plausible $\Delta h$ across catalogs.

% ================================
\section*{Acknowledgments}
\addcontentsline{toc}{section}{Acknowledgments}
The author thanks readers of the Timeless Light Model corpus for pressing for stronger, testable claims; this paper leads with the new logic while keeping a complete ready-reference in the appendices.

% ================================
\begin{thebibliography}{99}

% --- Foundational / mainstream ---
\bibitem{Einstein1905}
A.~Einstein, ``Zur Elektrodynamik bewegter K\"orper,'' \emph{Ann. Phys.} \textbf{17}, 891--921 (1905).

\bibitem{FeynmanQED}
R.~P.~Feynman, \emph{QED: The Strange Theory of Light and Matter}, Princeton Univ. Press (1985).

\bibitem{Wald}
R.~M.~Wald, \emph{General Relativity}, Univ. of Chicago Press (1984), pp.~60--63, 199--204.

\bibitem{RovelliRQM}
C.~Rovelli, ``Relational quantum mechanics,'' \emph{Int. J. Theor. Phys.} \textbf{35}, 1637--1678 (1996). \href{https://doi.org/10.1007/BF02302261}{doi:10.1007/BF02302261}.

\bibitem{PeskinSchroeder}
M.~E.~Peskin, D.~V.~Schroeder, \emph{An Introduction to Quantum Field Theory}, Addison-Wesley (1995), Chs.~6--7. \href{https://doi.org/10.1201/9780429503559}{doi:10.1201/9780429503559}.

\bibitem{SchneiderEhlersFalco}
P.~Schneider, J.~Ehlers, E.~E.~Falco, \emph{Gravitational Lenses}, Springer (1992), Chs.~3--5.

\bibitem{Cramer1986}
J.~G.~Cramer, ``The transactional interpretation of quantum mechanics,'' \emph{Rev. Mod. Phys.} \textbf{58}, 647--688 (1986). \href{https://doi.org/10.1103/RevModPhys.58.647}{doi:10.1103/RevModPhys.58.647}.

\bibitem{WF1945}
J.~A.~Wheeler, R.~P.~Feynman, ``Interaction with the Absorber as the Mechanism of Radiation,'' \emph{Rev. Mod. Phys.} \textbf{17}, 157--181 (1945). \href{https://doi.org/10.1103/RevModPhys.17.157}{doi:10.1103/RevModPhys.17.157}.

\bibitem{Agazie2023}
G.~Agazie et al., \emph{ApJL} \textbf{951}, L8 (2023).

\bibitem{Antoniadis2023}
J.~Antoniadis et al., \emph{A\&A} \textbf{678}, A50 (2023).

\bibitem{mckinley2025spacelessness}
McKinley, J. C. W. (2025). Spacelessness as a Consequence of Timelessness in the Quantum Platform of the Timeless Light Model. Zenodo. \href{https://doi.org/10.5281/zenodo.16350754}{doi:10.5281/zenodo.16350754}.[Preprint]

\end{thebibliography}

\end{document}
```

</details>

---
{% endraw %}
