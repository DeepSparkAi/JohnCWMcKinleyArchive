---
layout: default
title: '[2025] Generalized Pairing Law: No Quantum Emission Without an Absorber'
description: 'Publication metadata and archived raw LaTeX source by John C. W. McKinley.'
permalink: /papers/generalized-pairing-law-no-quantum-emission-without-an-absorber/
paper: true
---
{% raw %}
# [2025] Generalized Pairing Law: No Quantum Emission Without an Absorber
*   **DOI:** [10.5281/zenodo.16893165](https://doi.org/10.5281/zenodo.16893165)
*   **Date:** 18 August 2025

<details markdown="1">
<summary><b>Click to view Raw LaTeX Source</b></summary>

```latex
\documentclass[12pt,letterpaper]{article}

\usepackage[margin=1in]{geometry}
\usepackage[T1]{fontenc}
\usepackage[utf8]{inputenc}
\usepackage{lmodern}
\usepackage{booktabs}

\usepackage{amsmath,amssymb,amsthm}
\usepackage{microtype}

% TikZ + needed libraries
\usepackage{tikz}
\usetikzlibrary{arrows.meta,calc,positioning,decorations.pathmorphing,decorations.pathreplacing}
\tikzset{>=Latex} % optional: nicer default arrowheads

\usepackage[most]{tcolorbox}



\title{Generalized Pairing Law:\\ No Quantum Emission Without an Absorber}
\author{John C. W. McKinley \\ Independent Researcher \\ \href{https://orcid.org/0009-0005-7097-5035}{0009-0005-7097-5035}}


\date{August 17, 2025}

\newtheorem{theorem}{Theorem}
\newtheorem{lemma}{Lemma}
\newtheorem{corollary}{Corollary}
\newtheorem{definition}{Definition}
\newtheorem{axiom}{Axiom}
\newtheorem{proposition}{Proposition}


\usepackage{hyperref}
\hypersetup{colorlinks=true, linkcolor=blue, urlcolor=blue, citecolor=blue}




\begin{document}
\maketitle
\begingroup\renewcommand\thefootnote{}\footnotetext{This version published at
\href{https://doi.org/10.5281/zenodo.16893165}{https://doi.org/10.5281/zenodo.16893165}.}\endgroup





\begin{abstract}
This paper restates the Timeless Light Model (TLM) for a general audience and sharpens its emission claims around a canon-neutral conservation principle we call the \textit{Generalized Pairing Law} (GPL). \textbf{GPL:} No excitation is emitted without its paired condition. Equivalently, an emission process is realized if and only if there exists at least one compatible final state or partner process that completes conservation and boundary conditions.\ The photon-specific consequence—first publicly suggested (to the author's knowledge) by Bruce Rosner in early August 2025— is refined and formalized here \cite{Rosner2025}. We give simple proof elements (conservation completeness, mode availability, entangled twins, tunneling), then situate these results inside a novice-friendly TLM primer and axioms. The laws are phrased to stand independently of TLM jargon so that contesting a hypothetical TLM component does not undermine the pairing law itself.
\end{abstract}

\begin{tcolorbox}[title=How to Read This Paper]
\textbf{First:} The laws below (GPL and the photon pairing law) are stated without TLM-specific assumptions.\\
\textbf{Then:} We show how TLM interprets the same phenomena and record Rosner's corollary verbatim.\\
\textbf{Goal:} Even if a TLM hypothesis is disputed, the pairing law remains a conservation statement.
\end{tcolorbox}

\section{Core Laws (Canon-Neutral)}\label{sec:core-laws}


\begin{definition}[Absorption channel]\label{def:absorption-channel}
An \emph{absorption channel} is any physical degree of freedom or receiving mode
with \emph{nonzero coupling to the source} (nonzero transition matrix element)
that can take up the photon's conserved quantities (energy, momentum, angular momentum,
and relevant quantum numbers) so that the combined emission--absorption process preserves
all conservation laws.
\end{definition}


\begin{definition}[Excitation]
An \emph{excitation} is any emitted carrier of conserved quantities
(energy, momentum, angular momentum, charge, spin, quantum numbers), e.g., photons, electrons, phonons, magnons, neutrinos.
\end{definition}

\begin{definition}[Paired condition]
A \emph{paired condition} is any physical condition external to the source that, together with the emission, completes all conservation and boundary constraints.
It may be a receiving mode or absorber, a partner excitation, a compatible final state across a barrier, or a recoil/boundary interaction.
\end{definition}

\begin{theorem}[Generalized Pairing Law (GPL)]
No excitation is emitted without its paired condition.
Equivalently, an emission process is realized if and only if there exists at least one compatible final state or partner process that completes conservation and boundary conditions.
\end{theorem}


\begin{tcolorbox}[title=Scope and Limits of the GPL, colback=white, colframe=black!20]
\small
\begin{itemize}
\item \textbf{No pre-identification required:} GPL requires the existence of at least one compatible absorption channel at realization; it does not require that the specific absorber be known at the source time.
\item \textbf{Distributed pairing allowed:} The absorber may be a mode continuum or environment; pairing need not be to a single localized object in the canon-neutral statement.
\item \textbf{Compatibility test:} Nonzero source–channel coupling and conservation/boundary satisfaction. If either fails, no realized emission.
\end{itemize}
\end{tcolorbox}


\begin{proof}[Proof sketch: scattering and density of states]
Let \(\lvert i\rangle\) be the prepared source state.
Realized emission requires at least one final state \(\lvert f\rangle\) with nonzero transition amplitude \(M_{fi}\) that satisfies conservation.
By Fermi's golden rule,
\(W=(2\pi/\hbar)\sum_{f\in\mathcal{F}}\lvert M_{fi}\rvert^{2}\,\delta(E_f-E_i)\).
If no paired condition exists then \(\mathcal{F}=\varnothing\) or the local density of states at the required quantum numbers is zero, hence \(W=0\) and no emission occurs.
\end{proof}


\paragraph{Compatibility with QED.}
In standard QED,
\(W=(2\pi/\hbar)\sum_f |M_{fi}|^2 \rho_f \,\delta(E_f-E_i)\).
When either the matrix element \(M_{fi}\) vanishes (selection rules) or the relevant density of states \(\rho_f\) is zero (LDOS suppression), the emission rate is zero. GPL is the operational restatement: no realized emission without at least one admissible \(f\).


\subsection{Photon Pairing Law (canon-neutral)}\label{sec:photon-pairing}



\begin{theorem}[Photon Pairing Law (canon-neutral)]
No photon is emitted without concomitant pairing with at least one compatible absorption channel. 
Equivalently, an emission event is realized \emph{iff} a conservation-completing absorption channel exists.
\end{theorem}
\noindent\textit{Compatibility means:} the receiver satisfies conservation \emph{and} has nonzero source–channel coupling (Def.~\ref{def:absorption-channel}).




\paragraph{Derivation sketch (three steps).}
\begin{enumerate}
  \item \textbf{Energy accounting.} Unpaired emission leaves conservation incomplete or creates a field reservoir.
  \item \textbf{Proper-time paradox.} With $\tau=0$, a “waiting photon” narrative is incoherent.
  \item \textbf{Pairing.} Therefore, emission is realized \emph{iff} a conservation-completing absorber/mode exists (Photon Pairing Law).
\end{enumerate}



\begin{proof}[Proof sketch 1: conservation completeness]
Assume a photon is emitted with no compatible absorption channel. Either the radiation field constitutes an indefinitely accessible reservoir of conserved quantities or emission fails to complete global conservation. The first conflicts with bounded energy extraction; the second violates conservation. Hence, no realized emission.
\end{proof}

\begin{proof}[Proof sketch 2: mode availability]
Observed spontaneous emission rates track the local density of electromagnetic modes; near-zero density suppresses emission (Purcell effect) \cite{Purcell1946}. This is consistent with the requirement that a receiving mode exists for realized emission.
\end{proof}

\begin{lemma}[Entangled-pair exemplar]
In parametric down-conversion and atomic cascades, photons are emitted as twins satisfying \(\omega_s+\omega_i=\omega_p\) and \(\mathbf{k}_s+\mathbf{k}_i=\mathbf{k}_p\). Single-photon emission that violates these constraints is forbidden; the twin functions as the paired condition.
\end{lemma}

% --- Standard references for entangled twin-photon sources
\noindent\emph{Standard references.}
For textbook treatments of twin-photon generation and phase matching in nonlinear media,
see \cite{MandelWolf1995,Boyd2020}.



\subsection{Three equivalent formulations of the photon law}

\begin{tcolorbox}[title=Three Equivalent Forms of the Photon Pairing Law]
\begin{enumerate}
  \item \textbf{Conservation form.} A photon is emitted \emph{iff} there exists a receiver that completes conservation.
\item \textbf{Mode form.} A photon is emitted \emph{iff} a compatible electromagnetic mode
(\emph{with nonzero source–mode coupling}) is available to accept it.



\item \textbf{Photon Pairing Corollary.} \textit{No photon-like instruction is ever emitted without a matching absorber. What standard physics treats as an “unmatched photon” is instead never instantiated at all in the QP; EM waves and photons are always tied to absorber-resolution events.}\emph{ Provenance—first publicly suggested (to the author's knowledge) by B.~Rosner in early Aug 2025; formalized and generalized here. See \cite{Rosner2025}.}






  
\end{enumerate}
\end{tcolorbox}



\noindent\textbf{CI-ARC write rule (TLM).} No photon Causal Instruction Arc (CI-ARC) is written
unless the absorption endpoint exists; the pair is written timelessly and only then deployed as
emission and absorption in spacetime.





\section{Application: Quantum Tunneling (canon-neutral)}\label{sec:tunneling}

\begin{definition}[Admissible final state across the barrier]
An \emph{admissible final state} is a propagating mode (real wavevector) on the transmission side with 
an unoccupied state consistent with all conserved quantities \emph{and with nonzero overlap
(matrix element) with the incident state}.

\end{definition}

\begin{theorem}[Tunneling Pairing Law]
No tunneling event is realized without an admissible final state across the barrier. Otherwise, the transmitted amplitude is evanescent and yields zero asymptotic detection current.
\end{theorem}



\begin{figure}[t]
\centering
\begin{tikzpicture}[>=Latex,scale=1]
  % x-axis
  \draw[->] (-0.2,0) -- (8,0) node[right] {$x$};
  % barrier
  \draw[fill=gray!15,draw=gray!40] (3,-0.8) rectangle (5,1.8);
  \node[text=gray!60] at (4,1.95) {\scriptsize Barrier (Region II)};
  \node at (1.5,-0.35) {\scriptsize Region I};
  \node at (6.5,-0.35) {\scriptsize Region III};

  % incident and reflected waves (schematic sinusoids)
  \draw[domain=0:2.9,samples=80, smooth, variable=\x] plot(\x,{0.4*sin(5*\x r)+0.6});
  \draw[domain=0:2.9,samples=80, smooth, variable=\x, dashed] plot(\x,{-0.35*sin(5*\x r)+0.6});

  % evanescent inside barrier
  \draw[domain=3:5,samples=80, smooth, variable=\x] plot(\x,{0.9*exp(-2*(\x-3))+0.6});

  % transmitted wave (present iff admissible final state)
  \draw[domain=5:7.8,samples=80, smooth, variable=\x] plot(\x,{0.35*sin(5*(\x-5) r)+0.6});

  % braces/labels
  \draw[decorate,decoration={brace,raise=3pt}] (5,1.2) -- node[above=4pt] {\scriptsize admissible final state $\Rightarrow$ $T(E)>0$} (7.8,1.2);
  \draw[decorate,decoration={brace,raise=3pt,mirror}] (3,-0.2) -- node[below=4pt] {\scriptsize evanescent for $E<V_0$} (5,-0.2);
\end{tikzpicture}
\caption{Tunneling requires an admissible final state in Region III (compatible, unoccupied, nonzero overlap). Without it, the transmitted current vanishes and the event resolves as reflection/non-emission.}
\label{fig:tunneling}
\end{figure}





\begin{proof}[Proof sketch]
Consider 1D scattering with regions I (source), II (barrier), III (far side). If region III admits no propagating solution at energy \(E\) (e.g., lies in a band gap or there is no continuum state), then \(k_{\!III}\) is imaginary and \(\psi_{III}(x)\) is purely evanescent. The probability current \(j=(\hbar/m)\,\operatorname{Im}\,\psi^{*}\partial_x\psi\) vanishes as \(x\to\infty\); hence \(T(E)=0\) and by flux conservation \(R(E)=1\). If a propagating mode exists but all compatible states are occupied (fermions), Pauli exclusion blocks transmission. Therefore, transmission (a realized tunneling event) occurs iff a conservation-completing final state exists.
\end{proof}

\begin{corollary}[Resonant pairing]
In double-barrier (resonant) tunneling, transmission peaks only when a localized level aligns with \(E\); that intermediate level functions as the paired condition enabling a propagating final state.
\end{corollary}

\begin{corollary}[Transport form]
Net tunneling current requires both nonzero transmission and an occupancy imbalance:
\(I=\frac{2e}{h}\int T(E)\,[f_L(E)-f_R(E)]\,dE\).
If either \(T(E)=0\) (no admissible final states) or \(f_L=f_R\), no net emission across the barrier occurs.
\end{corollary}

\noindent\textbf{Operational phrasing.} ``No particle tunnels unless a compatible final state exists on the far side; otherwise the event resolves as reflection or non-emission.''













\section{TLM Primer for Novices}\label{sec:tlm-primer}

\paragraph{What TLM claims (plain language).}
TLM suggests that what we observe in spacetime is a \emph{deployment} of deeper, timeless instructions. Photons are not traveling beads; they denote endpoints of an instruction that links emission and absorption. The ``path'' in spacetime is the rendered trace consistent with those endpoints and the metric.

\paragraph{Terms used sparingly.}
\emph{Quantum Platform (QP):} shorthand for the timeless instruction layer. \emph{Spacetime Deployment Frame (SDF):} the rendered layer where we make measurements. The core laws above do not depend on accepting these terms; they serve as an interpretive lens.


\section{The TLM Photon Law}\label{sec:tlm-law}

\begin{definition}[TLM Photon Law]
A photon exists only as a paired emission--absorption instruction arc on the Quantum Platform (QP). If no absorber exists, no emission occurs. No loose photons exist.
\end{definition}

This formalizes TLM's claim that photons are not traveling objects inside spacetime, but timeless instructions whose endpoints define the observable deployment trace.


\section{TLM Axioms (Minimally Jargonized) and Rosner's Corollary}\label{sec:tlm-axioms}

\begin{enumerate}
  \item \textbf{Frame primacy.} Observable events occur at frames (measurement contexts); frames, not free-flying objects, anchor physical description.
  \item \textbf{Instruction precedence.} Observable states are deployments of prior instructions (conceptually outside time); spacetime describes their rendered relationships.
  \item \textbf{Mass--delay heuristic.} Delays correlate with mass (\(T\,m=\hbar/c^{2}\) in SI; natural units \(T m=1\)) and characteristic speed \(C_s\) (\(T\,C_s=1\)).
  \item \textbf{Connectivity without travel.} Photon-like ``paths'' connect frames without requiring an ontic traveler between them.
  \item \textbf{Single-absorber principle.} Each photon-like instruction resolves to exactly one absorption frame.\\
 
  \emph{Corollary 5a (Photon Absorber Corollary).} \textit{No photon-like instruction is ever emitted without a matching absorber. What appears in standard physics as an ``unmatched photon'' is instead never instantiated at all in the QP. Thus, EM waves and photons are always tied to absorber resolution events, never free-floating emissions.}


\noindent\emph{Historical note.} The phrasing of this corollary was honed from an Aug 1, 2025 public remark by B. Rosner; see Acknowledgments.

  
  \item \textbf{Gravity as frame interaction.} Mass-induced delay gradients alter relationships among frames, reproducing GR effects.
  \item \textbf{Frame independence.} Initial frames are independent; apparent histories arise from instruction linking.
\end{enumerate}

\section{Conflict With Standard Assumptions}
Standard formulations permit emission without a pre-specified absorber and treat radiation as persisting until absorption. GPL rejects realized emission without a conservation-completing partner or mode and predicts inhibition when compatible final states are unavailable. TLM interprets this as: no instruction is written without paired endpoints.


\begin{figure}[t]
\centering
\begin{tikzpicture}[scale=1]
  % axes
  \draw[->] (-0.2,0) -- (5,0) node[right] {$x$};
  \draw[->] (0,-0.2) -- (0,4) node[above] {$ct$};

  % lightlike guidelines
  \draw[dashed,gray] (0,0) -- (3.8,3.8);
  \draw[dashed,gray] (0,0) -- (-1.8,1.8);

  % events
  \fill (0,0) circle(1.6pt);
  \node[below left] at (0,0) {$E$ (emission)};
  \fill (3,3) circle(1.6pt);
  \node[above right] at (3,3) {$A$ (absorption)};

  % null worldline
  \draw[very thick] (0,0) -- (3,3) node[pos=0.55,above,sloped] {\small null;\, $d\tau=0$};

  % crossed-out "waiting" scribble
  \draw[decorate,decoration={coil,aspect=0.3,segment length=6pt,amplitude=1.5pt}]
      (1.4,1.4) .. controls (1.9,1.8) .. (2.3,2.2);
  \draw[red,thick] (1.2,1.2) -- (2.5,2.5);
  \node[red] at (3.6,2.4) {\scriptsize no ``waiting''};
\end{tikzpicture}
\caption{Null propagation implies zero proper time along $EA$. The traveler narrative (“photon waiting in flight”) is conceptually inconsistent with $d\tau=0$. GPL/TLM avoid this by denying unpaired emission.}
\label{fig:minkowski-null}
\end{figure}



\section{Explicit Tensions in the Standard Picture}

\begin{tcolorbox}[title=Contradictions at a Glance, colback=white, colframe=black!20]
\small
\begin{itemize}
  \item \textbf{Zero proper time vs ``waiting photon''.} In SR a photon follows a null interval with proper time $\tau=0$; the standard narrative that a photon persists ``in flight'' until later absorption tacitly assigns it an intrinsic duration. GPL/TLM resolve by denying unpaired emission: there is no waiting entity.
  \item \textbf{Unpaired emission vs global conservation.} If emission proceeds without any compatible absorber/mode, either energy accounting is incomplete or the EM field acts as an unlimited reservoir. GPL/TLM forbid unpaired emission, closing conservation.
  \item \textbf{Reservoir pathologies.} A durable stock of unmatched photons would enable deferred energy harvest (free-energy–style schemes). GPL/TLM block this by requiring pairing at realization.
\end{itemize}
\end{tcolorbox}


\begin{proposition}[Proper-time tension]
Assume (i) photons traverse null intervals ($\tau=0$), and (ii) unpaired emission occurs with the photon persisting until absorption. Then the photon must both have no intrinsic duration and yet persist as an ontic traveler. This is a conceptual inconsistency.
\end{proposition}

\begin{proof}[Sketch]
Persistence-as-traveler implies existence across an interval with nonzero intrinsic duration, whereas a null worldline entails $\tau=0$. Field descriptions avoid assigning a particle clock, but the traveler narrative still posits an ontic object awaiting fate. GPL/TLM remove the traveler: emission is realized \emph{iff} a compatible absorber/mode exists, so the observed history is the deployment of a paired event, not waiting in time.
\end{proof}

\begin{proposition}[Conservation tension]
If emission is realized without any compatible absorption channel, the source loses energy while no completing process exists to balance conserved quantities; equivalently, the free field must function as a harvestable reservoir. Both options contradict closed-system conservation or enable pathological energy extraction.
\end{proposition}

\noindent\textbf{Resolution under GPL/TLM.}
By the Generalized Pairing Law, emission is realized \emph{iff} at least one compatible channel (nonzero source–mode coupling and conservation) exists; otherwise there is no realized emission. In TLM terms, no CI-ARC is written unless both endpoints exist; the pair deploys as the observed history.



\section{Historical Context}
\paragraph{Einstein (1905).} Photons traverse null intervals: zero proper time \cite{Einstein1905}. TLM removes the need for a waiting traveler.\\
\paragraph{Wheeler--Feynman (1945).} Absorber theory ties radiation to absorbers using time-symmetric fields \cite{WheelerFeynman1945}. TLM locates the requirement outside spacetime and does not rely on advanced solutions.

\section{Experimental Implications}
\begin{itemize}
  \item \textbf{Cavity and LDOS control.} GPL predicts inhibited emission when compatible modes are eliminated (Purcell effect) \cite{Purcell1946,Kleppner1981}.
  \item \textbf{Delayed choice.} Outcomes align with whichever paired condition is realized; no traveler awaiting decision is required \cite{Hellmuth1987,Jacques2007}.
  \item \textbf{Long-baseline isolation.} Absence of a stable source-free photon reservoir supports GPL; robust evidence of such a reservoir would pressure it.
\end{itemize}



% --- Quick discriminator table: Standard vs GPL/TLM
\begin{tcolorbox}[title=Discriminator at a Glance, colback=white, colframe=black!20]
\small
\renewcommand{\arraystretch}{1.2}
\begin{tabular}{p{0.44\linewidth} p{0.52\linewidth}}
\textbf{Standard view} & \textbf{GPL/TLM view} \\
\hline
Emission without a pre-identified absorber is permitted; photons may be emitted into free space and later absorbed. &
Emission is realized \emph{iff} at least one compatible absorption channel exists; no orphan photons. \\
Spontaneous emission rate tracks the local density of EM modes (Purcell effect); a specific absorber need not be specified. &
Same rate–LDOS dependence, interpreted as channel availability: near-zero LDOS $\Rightarrow$ no compatible channels $\Rightarrow$ inhibited emission. \\
Delayed-choice: often described with a photon “in flight” until measurement fixes the history. &
CI-ARC written only when endpoints exist; deployment yields a consistent history. No traveler or retrocausal signaling is required. \\
\end{tabular}
\end{tcolorbox}




\section{Falsifiability Protocols}\label{sec:falsifiability}

\begin{tcolorbox}[title=Decisive Discriminator (Bridge to Experiments), colback=white, colframe=black!20]
\small
The outstanding gap is a single, parameter-specified experiment that yields \emph{mutually exclusive} predictions. 
Goal: design a setup where TLM predicts outcome A while canonical QM/QED predicts outcome B, with the \emph{local electromagnetic environment at the source} held invariant (i.e., the local Green's tensor $G(\mathbf r_0,\mathbf r_0;\omega)$ and LDOS are unchanged between settings). Controlling this removes trivial explanations (LDOS shifts, reflections, loss, detector bias).
\end{tcolorbox}

\subsection*{Candidate A/B Tests (to be locked down into a single decisive protocol)}
\begin{enumerate}
  \item \textbf{Absorber-gated spontaneous emission with invariant LDOS.}\\
  \emph{Setup:} A single two-level emitter couples to a fixed local photonic environment (e.g., photonic crystal cavity or on-chip waveguide splitter feeding two identical, \emph{always-matched} loads). A remote gate toggles whether one load actually \emph{absorbs} (dump) vs \emph{shutters} the photon \emph{far downstream}, beyond any causal influence on the source-region Green's function.\\
  \emph{Hold fixed:} Source position/orientation, transition frequency, pump, temperature, LDOS near emitter.\\
  \emph{Prediction (A/B):} \textbf{TLM:} Excited-state lifetime / emission probability depends on the availability of a compatible absorber even when $G(\mathbf r_0,\mathbf r_0;\omega)$ is unchanged.\\
  \textbf{QM/QED:} With invariant LDOS and coupling at the source, the spontaneous-emission rate and lifetime are unchanged; only far-field detection statistics differ.

  \item \textbf{Herald-rate dependence on remote absorber (SPDC).}\\
  \emph{Setup:} Heralded single photons from SPDC. Idler is detected locally; signal traverses a long, low-loss path to a remote branch that is randomly switched between (i) matched dump absorber and (ii) shutter/no-absorber, with switching spacelike relative to the herald detection. Optical design ensures no back-reflection or LDOS change at the crystal.\\
  \emph{Hold fixed:} Pump, phase matching, coupling optics, and crystal environment.\\
  \emph{Prediction (A/B):} \textbf{TLM:} If no compatible absorber exists for the signal, pair emission is not realized; herald singles rate drops when the remote absorber is unavailable.\\
  \textbf{QM/QED:} Idler singles rate is independent of spacelike choices on the signal arm (no-signaling); only joint (coincidence) statistics respond.

  \item \textbf{Band-gap isolation with certified absence of receivers (control).}\\
  \emph{Setup:} Emitter embedded in a deep photonic band gap at the transition frequency; verified vanishing LDOS.\\
  \emph{Purpose:} Non-discriminator control validating suppression under both frameworks. Any residual emission must be traceable to leakage in LDOS or hidden absorbers before claiming disagreement.
\end{enumerate}

\noindent\emph{Next step:} Promote one of (1) or (2) to a full, parameterized proposal with a quantitative A/B table (rates, confidence targets, nuisance limits), then register it as the primary discriminator.


\begin{enumerate}
  \item \textbf{Near-zero-LDOS cavity.} Engineer near-zero density of states at the transition frequency; persistent emission in a demonstrably mode-free configuration would challenge GPL.
  \item \textbf{Isolated-beam tests.} Instrumented vacuum paths excluding scatterers; look for evidence of a durable orphan-photon population.
  \item \textbf{Absorber-toggled delayed choice.} Toggle absorber presence after source preparation to test whether realized outcomes track paired condition availability.
\end{enumerate}


\section{Philosophical Consequences}
Existence of emissions is relational: to be emitted is to complete a pairing that satisfies conservation. TLM expresses this as instruction endpoints; GPL states it as a canon-neutral law.

\section{Conclusion}
We restated TLM for novices and elevated a simple conservation truth to a general law: no excitation is emitted without its paired condition. The photon case, highlighted by Rosner's comment and preserved as a corollary, is one instance of a broader, testable principle that stands independently of any single TLM hypothesis.

\section*{Acknowledgments}
The author thanks Bruce Rosner for a public YouTube comment in early Aug 2025 that sparked the phrasing of the photon–absorber corollary. A capture of the comment at retrieval time (Aug 17, 2025) is included in the Zenodo deposit \cite{Rosner2025}. Any errors are the author’s.




\appendix


\section{Historical Note}

The following was the narration presented on a YouTube explainer video issued by the author July 20, 2025 upon the release of \href{https://zenodo.org/records/16187719}{Foundational Equations and Axiomatic Structure of the Timeless Light Model}.


\begin{quote}
``Did you know... a photon never experiences time? Not a little. Not ever. According to Einstein's equations, a photon's proper time is exactly zero. That means -- from its own `perspective' -- it travels from the Big Bang to your eye instantly. But what if that is not just math? What if light really exists outside of time... and the entire universe is built on instructions it carries? Now the new Timeless Light Model -- a framework where space and time emerge from a deeper, timeless layer called the Quantum Platform. In this model, mass is delay, causality is rendered, and reality is not unfolding -- it is deploying.''\cite{McKinleyVideo2025}
\end{quote}

Bruce Rosner commented  on the video circa August 1, 2025,  as follows:
\begin{quote}

``A corollary of this theory is that there must be a receptor to catch every emitted photon. That is, photons are never emitted unless there is a receptor to balance the energy.'' 
\end{quote}

Rosner himself called it a corollary. Standard physics does not treat it as a law.

\section{Glossary}
\begin{itemize}
  \item \textbf{Quantum Platform (QP):} A timeless layer where instructions are written; ontologically senior to spacetime.
  \item \textbf{Spacetime Deployment Frame (SDF):} The rendered layer governed by GR/SR/QM in which observations occur.
  \item \textbf{CI-ARC:} Causal instruction arc that pairs emission and absorption.
  \item \textbf{Photon Law:} In TLM, photons exist only as emission--absorption pairs.
\end{itemize}

\section{Appendix A: Unburied Summary in Boxes}

\begin{tcolorbox}[title=1. Clear Statement on Standard Physics]
Standard physics allows emission without a guaranteed absorption point. Photons can be released into the void with no pre-known receptor. This is mathematically encoded in field quantization and wavefunction propagation, but no direct proof exists that such orphan photons persist independently in reality. This is a point of weakness: the possibility is assumed, not observed. \textbf{There is no empirical reservoir of unmatched photons.}
\end{tcolorbox}

\begin{tcolorbox}[title=2. TLM Proposition Goes Uncontested]
TLM asserts axiomatically: photons are never emitted unless an absorption frame exists. The CI-ARC only writes once both emission and absorption are paired. This avoids the conflict of a photon, with no proper time, waiting indefinitely. Since standard physics cannot prove unmatched photons exist, the TLM law presents a cleaner alternative.
\end{tcolorbox}

\begin{tcolorbox}[title=2A. Resolution of Contradictions]
\begin{itemize}
  \item Entanglement: not spooky action, but pre-resolved instructions.
  \item Tunneling: not violation of barriers, but pre-written arc to a valid absorption.
  \item Photon emission: not orphans waiting in zero time, but emission only upon absorption guarantee.
\end{itemize}
\end{tcolorbox}

\begin{tcolorbox}[title=3. Acceptance of QP Resolves All]
Once a timeless Quantum Platform is posited, the contradictions evaporate: no waves bouncing forever as a load, no spooky or acausal jumps, no particles waiting in zero time. The QP writes instructions only upon successful arrival, and spacetime renders the delayed deployment of that arc.
\end{tcolorbox}

\section{Expanded Falsifiability Protocols}
\subsection{Cavity and LDOS Suppression}
\textit{Setup.} Place an emitter with a narrow transition in a high-Q cavity engineered for near-zero LDOS at the transition frequency.\\
\textit{TLM expectation.} Emission is inhibited absent available absorbers/channels.\\
\textit{Standard expectation.} Spontaneous emission rate tracks LDOS (Purcell effect) but does not require a pre-identified absorber.\\
\textit{Discriminator.} Persistent emission into a demonstrably absorber-free configuration would violate the strict pairing claim.

\subsection{Long-Baseline Isolation}
\textit{Setup.} Source aimed into deep, well-characterized vacuum with instrumented far-field region eliminating scatterers.\\
\textit{TLM expectation.} No build-up of ``free'' photon population; detections correspond to paired absorbers only.\\
\textit{Discriminator.} Evidence of a stable orphan-photon reservoir would pressure the law.

\subsection{Delayed-Choice With Absorber Availability}
\textit{Setup.} Implement delayed-choice where the presence/absence of a viable absorber is toggled after emission conditions.\\
\textit{TLM expectation.} Outcomes align with whichever endpoint pairing is realized; there is no traveler awaiting decision.\\
\textit{Discriminator.} Any requirement for a waiting ontic photon conflicts with TLM.

\section{Defense Against Objections}\label{sec:defense}
\paragraph{Lasers emit into empty space.}
\textbf{Response.} Practical environments teem with potential absorbers (matter, dust, walls, detectors, interplanetary medium). TLM allows distributed pairing across a large frame; truly absorber-free emission is not realized in practice.

\paragraph{Cosmological orphan photons.}
\textbf{Response.} Background light pairs with absorbers that may be outside the observer's present SDF reach. TLM forbids the category of permanently orphaned photons.

\paragraph{Is pairing just post-selection?}
\textbf{Response.} TLM asserts that the CI-ARC is written only for successful absorption. There is no traveler awaiting fate; the pair is the photon. Post-selection language in standard analyses is reinterpreted as recognition of which instruction arc was written.

\paragraph{Is this Wheeler--Feynman in disguise?}
\textbf{Response.} No. TLM removes photons from spacetime and treats the pair as a timeless instruction, not as advanced/retarded fields in spacetime.

\paragraph{Free energy via unmatched photons.}
\textbf{Response.} If unmatched photons could exist, they would constitute an unbounded energy reservoir accessible by later absorbers, enabling free-energy schemes. TLM blocks this pathology by forbidding unmatched photons. Any observed energy uptake is part of an already-paired arc.


\subsection*{Response to ``Novelty vs.\ Re-interpretation''}

\paragraph{Reviewer point.}
The GPL appears to restate Fermi’s golden rule (FGR): if no final states exist or $M_{fi}=0$, then the transition rate vanishes. Emission suppression (e.g.\ Purcell) is already a verified QED consequence of local mode control, so where is the new physics?

\paragraph{Author response (summary).}
We agree the \emph{necessary} condition “no admissible states $\Rightarrow$ no emission” is standard. The GPL adds a \emph{stronger, testable} requirement: realized emission depends not only on the \emph{local} availability of electromagnetic modes but also on the existence of at least one \emph{compatible absorber} (a conservation-completing boundary) even when the local Green’s tensor and LDOS at the source are unchanged. This yields a falsifiable divergence from canonical QED.

\paragraph{Formal distinction.}
Let the excited source be at $\mathbf r_0$ with transition frequency $\omega_0$.
Define
\[
\mathcal F_{\mathrm{loc}}
=\Big\{f:\ \rho_f(\mathbf r_0,\omega_0)>0\ \wedge\ M_{fi}\neq 0\Big\},
\quad
\mathcal F_{\mathrm{pair}}
=\Big\{f\in \mathcal F_{\mathrm{loc}}:\ \text{there exists a compatible absorber/channel for }f\Big\}.
\]
Canonical QED computes
\[
W_{\mathrm{QED}}
=\frac{2\pi}{\hbar}\sum_{f\in \mathcal F_{\mathrm{loc}}}\!|M_{fi}|^2\,\delta(E_f-E_i),
\]
so $W_{\mathrm{QED}}$ depends on the \emph{local} density of states (LDOS) and matrix elements at $\mathbf r_0$.\\
The GPL asserts instead
\[
W_{\mathrm{GPL}}
=\frac{2\pi}{\hbar}\sum_{f\in \mathcal F_{\mathrm{pair}}}\!|M_{fi}|^2\,\delta(E_f-E_i),
\]
i.e., emission is realized \emph{iff} at least one conservation-completing absorber/channel exists. Consequently, scenarios with
\[
\mathcal F_{\mathrm{loc}}\neq\varnothing\quad \text{but}\quad \mathcal F_{\mathrm{pair}}=\varnothing
\]
produce a \emph{quantitative} disagreement:
\[
W_{\mathrm{QED}}>0\quad \text{while}\quad W_{\mathrm{GPL}}=0.
\]

\paragraph{Decisive discriminator (empirical).}
Hold fixed the local photonic environment at the source (same retarded Green’s function and LDOS), and toggle only the existence of a distant, perfectly matched absorber \emph{without} altering the source-region boundary conditions (e.g., waveguide with isolators to prevent back-action; absorber gating beyond the causal influence on $G(\mathbf r_0,\mathbf r_0;\omega_0)$). Then:
\begin{itemize}
  \item \textbf{GPL:} Excited-state lifetime/emission probability at the source \emph{changes} with absorber availability ($\mathcal F_{\mathrm{pair}}$ on/off).
  \item \textbf{QED:} With invariant LDOS and $M_{fi}$ at the source, the spontaneous-emission rate is \emph{unchanged}; only far-field detection statistics differ.
\end{itemize}
This A/B difference is not a philosophical rephrasing; it is a rate-level prediction at the emitter under matched local optics. If the measured rate is invariant, GPL (in its strong form) is falsified; if it tracks absorber availability under LDOS control, QED (as ordinarily applied) is incomplete for this regime.

\paragraph{Scope control.}
To avoid trivial reinterpretations, the protocol explicitly (i) certifies identical $G(\mathbf r_0,\mathbf r_0;\omega_0)$ across conditions, (ii) eliminates reflections and loss that would modify the LDOS, and (iii) uses timing that rules out causal back-action to the source region. Under those controls, the two frameworks yield mutually exclusive quantitative outcomes.




\subsection*{Response to ``Speculative Framework and Jargon''}

\paragraph{Reviewer point.}
The paper introduces new terms (QP, CI-ARC, SDF) without a rigorous formalism. Although the GPL is stated to be canon-neutral, much of the manuscript discusses TLM axioms that are not mathematically tied to GR/SM, giving the work a philosophical tone.

\paragraph{Author response (summary).}
We accept that predictions must be couched in standard mathematics. Accordingly, we (i) reduce jargon in the main text, (ii) supply a minimal operator/Green-function formalization for every TLM term we retain, and (iii) move interpretive material to the appendix. The core results (GPL, photon pairing law, tunneling pairing) are now stated purely in standard QED/QO language.

\paragraph{Minimal formalization that replaces jargon.}
Let $\mathcal H$ be the system+field Hilbert space, $U(t)$ the unitary evolution generated by the usual light–matter Hamiltonian, and $\rho$ the prepared state.
\begin{itemize}
  \item \textbf{Frames (formerly ``SDF frames''):} Measurement contexts are POVMs $\{M_\alpha\}$ acting on $\mathcal H$ at spacetime coordinates $(x_\alpha,t_\alpha)$ embedded in a Lorentzian manifold $(\mathcal M,g_{\mu\nu})$.
  \item \textbf{CI-ARC (emission–absorption link):} For an emission operator $V_E$ localized at $(x_E,t_E)$ and an absorber POVM element $M_A$ at $(x_A,t_A)$, the \emph{pair amplitude}
  \[
    \mathcal A_{E\!\to\!A} \;=\; \mathrm{Tr}\!\left[M_A\,U(t_A,t_E)\,V_E\,\rho\,V_E^\dagger\,U^\dagger(t_A,t_E)\right]
  \]
  is the standard detection functional (Glauber photodetection in the weak-coupling limit). ``CI-ARC exists'' $\iff \mathcal A_{E\!\to\!A}\neq 0$.
  \item \textbf{Mode/absorber compatibility:} In macroscopic QED,
  \[
    \Gamma(\mathbf r_0,\omega_0)\;=\;\frac{2}{\hbar^2}\,\mathbf d\cdot \mathrm{Im}\,\mathbf G(\mathbf r_0,\mathbf r_0;\omega_0)\cdot\mathbf d
  \]
  with dipole $\mathbf d$ and Green tensor $\mathbf G$. A ``compatible channel'' is a nonvanishing contribution to $\mathrm{Im}\,\mathbf G$ \emph{and} a nonzero matrix element $M_{fi}$ that completes conservation (standard selection rules).
  \item \textbf{Quantum Platform (QP):} Operationally, QP is \emph{not} used in calculations; it is an interpretive label for the selection of nonzero $\mathcal A_{E\!\to\!A}$. All predictions in this paper follow from the operator and Green-function expressions above.
\end{itemize}

\paragraph{Terminology crosswalk (used henceforth).}
\begin{center}
\begin{tabular}{p{0.33\linewidth} p{0.6\linewidth}}
\toprule
TLM term & Standard construct used in this paper \\
\midrule
Spacetime Deployment Frame (SDF) & Measurement events $(x,t)$ on $(\mathcal M,g_{\mu\nu})$ with POVMs $\{M_\alpha\}$ \\
CI-ARC & Nonzero detection functional $\mathcal A_{E\!\to\!A}$ (Glauber theory / S-matrix element connecting source and absorber) \\
Absorption channel & Final state $|f\rangle$ with $M_{fi}\neq 0$ and contributing LDOS via $\mathrm{Im}\,\mathbf G$ \\
Quantum Platform (QP) & \emph{Interpretive} label only; no role in formulas or fits \\
\bottomrule
\end{tabular}
\end{center}

\paragraph{Editorial changes (implemented).}
\begin{enumerate}
  \item All theorems/proofs (GPL; photon/tunneling pairing) are restated without TLM jargon; only standard symbols $(M_{fi},\,\rho_f,\,\mathbf G,\,\Gamma)$ appear.
  \item The section formerly titled \emph{``TLM Axioms''} is moved to an appendix and retitled \emph{``Interpretive Notes''}.
  \item Claims about GR/SM are narrowed to \emph{interpretive compatibility}; we do not claim to reproduce the Einstein–Hilbert or SM Lagrangians here.
\end{enumerate}

\paragraph{Why this is not merely philosophy.}
Every qualitative TLM term now maps to a quantitative object used to compute rates and detection probabilities. The GPL’s strong form (source rate contingent on absorber existence under fixed LDOS) is framed as a measurable difference at the emitter; see the ``Decisive discriminator'' protocol in Sec.~\ref{sec:falsifiability}. If experiments find no rate change under invariant $\mathrm{Im}\,\mathbf G(\mathbf r_0,\omega_0)$, the strong GPL is falsified; if a change is observed, standard modeling must be extended. Either outcome is empirical.



\section{References}
\begin{thebibliography}{9}


\bibitem{Boyd2020}
R.~W.~Boyd, \emph{Nonlinear Optics}, 4th ed.
Academic Press, 2020.


\bibitem{Einstein1905}
A. Einstein, On the Electrodynamics of Moving Bodies. \emph{Annalen der Physik} (1905).

\bibitem{MandelWolf1995}
L.~Mandel and E.~Wolf, \emph{Optical Coherence and Quantum Optics}.
Cambridge University Press, 1995.


% With this
\bibitem{McKinley2025}
J. C. W. McKinley. \textit{Foundational Equations and Axiomatic Structure of the Timeless Light Model: A Synthesis Across Sixty Papers and Working Notes} (v1.0). Zenodo, DOI:\href{https://doi.org/10.5281/zenodo.16187719}{10.5281/zenodo.16187719}, 2025.




\bibitem{WheelerFeynman1945}
J. A. Wheeler and R. P. Feynman, Interaction with the Absorber as the Mechanism of Radiation. \emph{Rev. Mod. Phys.} 17, 157 (1945).

\bibitem{Purcell1946}
E. M. Purcell, Spontaneous emission probabilities at radio frequencies. \emph{Phys. Rev.} 69, 681 (1946).


% Add to your bibliography
\bibitem{Kleppner1981}
D.~Kleppner, Inhibited Spontaneous Emission. \emph{Phys. Rev. Lett.} 47, 233 (1981).

\bibitem{Hellmuth1987}
T.~Hellmuth, H.~Walther, A.~Zajonc, W.~Schleich, Delayed-choice experiments in quantum interference. \emph{Phys. Rev. A} 35, 2532 (1987).

\bibitem{Jacques2007}
V.~Jacques \emph{et al.}, Experimental realization of Wheeler's delayed-choice. \emph{Science} 315, 966 (2007).


\bibitem{Rosner2025}
B.~Rosner. Public comment on YouTube under McKinley (2025) video
“The Timeless Nature of Light\hspace{1em}60 papers v1 0.” % forces the wide gap
(Captured and archived on Zenodo.) Retrieved 2025-08-17. Zenodo.
DOI:\,\href{https://doi.org/10.5281/zenodo.16892518}{10.5281/zenodo.16892518}. © original rights-holders; all rights reserved.





\bibitem{McKinleyVideo2025}
J.~C.~W.~McKinley. “The Timeless Nature of Light\hspace{1em}60 papers v1 0.” 
(YouTube video), 2025. Title as listed on YouTube (spacing “v1 0” and extra spaces before “60” preserved).
URL: \href{https://youtube.com/shorts/mqKX0JMs8sE}{https://youtube.com/shorts/mqKX0JMs8sE}. Retrieved Aug 17, 2025.

\end{thebibliography}

\end{document}
```

</details>

---
{% endraw %}
