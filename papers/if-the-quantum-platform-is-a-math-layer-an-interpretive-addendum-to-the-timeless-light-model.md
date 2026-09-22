---
layout: default
title: '[2025] If the Quantum Platform Is a Math Layer: An Interpretive Addendum to the Timeless Light Model'
description: 'Publication metadata and archived raw LaTeX source by John C. W. McKinley.'
permalink: /papers/if-the-quantum-platform-is-a-math-layer-an-interpretive-addendum-to-the-timeless-light-model/
paper: true
---
{% raw %}
# [2025] If the Quantum Platform Is a Math Layer: An Interpretive Addendum to the Timeless Light Model
*   **DOI:** [10.5281/zenodo.17169440](https://doi.org/10.5281/zenodo.17169440)
*   **Date:** 21 September 2025

<details markdown="1">
<summary><b>Click to view Raw LaTeX Source</b></summary>

```latex
\documentclass[11pt]{article}

\usepackage[margin=1in]{geometry}
\usepackage[T1]{fontenc}
\usepackage[utf8]{inputenc}
\usepackage{lmodern}
\usepackage{amsmath,amssymb,mathtools}
\usepackage{physics}
\usepackage{siunitx}
\usepackage[hidelinks]{hyperref}
\usepackage{graphicx}
\usepackage{xcolor}
\usepackage{enumitem}
\usepackage{tikz}
\usepackage{tikz-cd}
\usetikzlibrary{arrows.meta,positioning,calc,shapes.geometric}


% TikZ & PGF (no need in abstract)
\usepackage{tikz}
\usepackage{pgfplots}


\usepackage{pgfplots}
\pgfplotsset{compat=1.18}

% ---------- Headers ----------
\usepackage{fancyhdr}
\pagestyle{fancy}
\fancyhf{}
\lhead{QP - Math Layer}
\rhead{\thepage}


\newcommand{\MTterm}{mass--time relation}


% ---------- Links & References ----------
\usepackage{hyperref}
\hypersetup{colorlinks=true,linkcolor=blue,urlcolor=blue,citecolor=blue}
\usepackage{cleveref}

\setlist{noitemsep}
\sisetup{uncertainty-mode = separate}

\title{If the Quantum Platform Is a Math Layer:\\
An Interpretive Addendum to the Timeless Light Model}
\usepackage{orcidlink}
\author{John C. W. McKinley\orcidlink{0009-0005-7097-5035}\\Independent Researcher}
\date{September 21, 2025}

\begin{document}
\maketitle

\begingroup
  \footnotetext[0]{This version published at
  \href{https://doi.org/10.5281/zenodo.17169440}{https://doi.org/10.5281/zenodo.17169440}.}
\endgroup


\begin{abstract}
This note leaves the Timeless Light Model (TLM) unchanged and develops an interpretive option: identify the Quantum Platform (QP) with a purely mathematical layer (ML) that is timeless and non-dynamical. The ML supplies abstract instructions that are rendered in the Spacetime Deployment Frame (SDF) with delay \(T\). We formalize the ML via an instruction algebra \(\mathcal{A}\), a frame-indexed rendering map \(R_f\), and a delay functional \(T(a,f)\) obeying the bridge laws \(T \cdot m = \hbar/c^2\) and \(T \cdot C_s = 1\). We state an operational equivalence proposition: within the scope of standard experiments, TLM+QP and TLM+ML yield identical observable predictions. We give compact derivations of probability assignment via pushforward measure, compatibility with SR/GR timing, and the TLM \MTterm. We list falsifiers that would refute the ML reading without touching core TLM.
\end{abstract}

\tableofcontents




\section{Positioning and Claim}
\label{sec:positioning}
\textbf{Neutrality.} This paper does not change TLM. It offers a semantics for QP that preserves all operational content and all TLM axioms already published \cite{mckinley_tlm_v20_2025,mckinley_not_obviously_false_2025,mckinley_cornerstone_2025,mckinley_hilbert_frame_2025}. For context on timeless programs more broadly, see Barbour \cite{barbour_1994}.

\textbf{Replacement hypothesis.} If QP is just a math layer, model it as:
\begin{itemize}
\item a unital \(^*\)-algebra of instructions \(\mathcal{A}\),
\item a rendering map \(R_f:\mathcal{A}\to \mathcal{B}(\mathcal{H}_f)\) for each observer frame \(f\) in a set of frames \(\mathcal{F}\),
\item a delay functional \(T:\mathcal{A}\times \mathcal{F}\to \mathbb{R}_{\ge 0}\) obeying \(T(a,f)\,C_s(f)=1\).
\end{itemize}
No new causal knobs are introduced. There is no instruction cost. Description length and compression are metadata only.




\section{Brief Overview of TLM}
\label{sec:tlm-brief}
TLM is a two-layer ontology:
\begin{enumerate}
\item Timeless layer (QP): resolves endpoint instructions without time. Photons have no proper time. One instruction, one absorption.
\item SDF (the GR frame): renders those instructions with delay \(T\) that depends on frame conditions and mass parameters.
\end{enumerate}
Core laws used here:
\begin{align}
T \cdot C_s &= 1, \label{eq:T-Cs}\\
T \cdot m &= \frac{\hbar}{c^2}
\qquad \text{(the \MTterm; rest configurations in the SDF, consistent with Compton frequency).} \label{eq:Tm}
\end{align}



TLM forbids photon splitting and orphan photons (see \cite{mckinley_pairing_2025,mckinley_binary_law_2025}). It treats Hilbert space as the frame-level representation of rendered outcomes, not as the substrate. For SR background on null links and proper time, see \cite{einstein_1905}.








\begin{figure}[t]
\centering
\begin{tikzpicture}[scale=1.0]
% LEFT: GR view
\node at (2.6,5.5) {\small\bfseries GR: Null link in spacetime};
\draw[->] (0.2,0.5) -- (0.2,4.2) node[above] {\small $t$};
\draw[->] (0.2,0.5) -- (4.8,0.5) node[right] {\small $x$};
\draw[thick] (1,1.0) -- (1,4.0) node[above] {\scriptsize Emitter};
\draw[thick] (4,1.0) -- (4,4.0) node[right]  {\scriptsize Absorber};
\draw[blue, thick, dashed, ->] (1,1.3) -- (4,4.3) node[pos=0.55, above, sloped] {\scriptsize $ds^2=0$};
\fill (1,1.3) circle (1.2pt);
\fill (4,4.3) circle (1.2pt);

% RIGHT: TLM view
\begin{scope}[xshift=7.0cm]
\node at (2.6,5.5) {\small\bfseries TLM: Timeless instruction between endpoints};
\draw[->] (0.2,0.5) -- (0.2,4.2) node[above] {\small $t$};
\draw[->] (0.2,0.5) -- (4.8,0.5) node[right] {\small $x$};
\draw[thick] (1,1.0) -- (1,4.0) node[above] {\scriptsize Emitter};
\draw[thick] (4,1.0) -- (4,4.0) node[right] {\scriptsize Absorber};
\fill (1,1.3) circle (1.2pt) node[below left] {\scriptsize A};
\fill (4,4.3) circle (1.2pt) node[above right] {\scriptsize B};
\draw[red, thick, dotted,<->] (1,1.3) -- (4,4.3) node[midway, above, sloped] {\scriptsize timeless instruction};
\end{scope}
\end{tikzpicture}
\caption{Two readings of a lightlike link. GR depicts a null path between emitter and absorber; the TLM/ML reading treats the photon as a timeless instruction linking the rendered endpoints (no traveler in between).}
\label{fig:gr-vs-tlm}
\end{figure}






















\section{Minimal Math Layer Formalism}
\label{sec:ml-formal}

\subsection{Why a unital \(^*\)-algebra?}
Observables in the SDF are represented by self-adjoint operators. A \(^*\)-algebra provides an involution \(a\mapsto a^{*}\) whose self-adjoint elements model observables and whose spectral properties are the basis of measurement. Unitality supplies an identity that renders to \(I\in\mathcal{B}(\mathcal{H}_f)\), needed for normalized channels and measurements.

\paragraph{POVM completeness (brief).}
POVMs are the most general quantum measurements: a finite (or countable) set \(\{E_i\}\) of positive operators with \(\sum_i E_i = I\). The presence of the identity guarantees that outcome probabilities
\(\mathrm{tr}(\rho E_i)\) sum to \(1\). In the ML reading, unitality ensures that \(R_f\) can represent general instruments/POVMs in a way that preserves normalization across frames.

\subsection{Definitions}
Let \(\mathcal{A}\) be a unital \(^*\)-algebra. Elements \(a\in\mathcal{A}\) are instructions. For each frame \(f\in\mathcal{F}\), let \(\mathcal{H}_f\) be a Hilbert space of observables and states, and define
\[
R_f:\mathcal{A}\to \mathcal{B}(\mathcal{H}_f), \qquad a \mapsto O_{a,f}.
\]
Let \(T:\mathcal{A}\times\mathcal{F}\to \mathbb{R}_{\ge 0}\) be a delay functional with the constraint \(T(a,f)\,C_s(f)=1\) in that frame.\\


\noindent For the reading of Hilbert space as a frame-level representation, see \cite{mckinley_hilbert_frame_2025}.


\subsection{Probability as Pushforward (with a toy example)}
\label{ssec:pushforward}
Place a sigma-finite measure \(\mu\) on \(\mathcal{A}\) so that preparation procedures induce measurable subsets. For a projector \(P\) on \(\mathcal{H}_f\),
\[
\mathbb{P}_f(P) \equiv \mu\Big(\{a\in\mathcal{A}:\, \text{the spectrum of } R_f(a) \text{ is recorded in } P\}\Big).
\]
\textbf{Toy example (coin-flip prep).} Suppose a preparation emits instructions from two disjoint measurable classes \(S_0,S_1\subset\mathcal{A}\) with \(\mu(S_1)=p\), \(\mu(S_0)=1-p\), and \(R_f(S_i)\subseteq E_i\) where \(\{E_0,E_1\}\) is a two-outcome POVM on \(\mathcal{H}_f\). Then
\[
\mathbb{P}_f(E_1)=\mu(R_f^{-1}(E_1))=\mu(S_1)=p, \qquad \mathbb{P}_f(E_0)=1-p.
\]
Specialize to a C\(^*\)-algebra and a cyclic representation \(\pi_f\) with state \(\rho\) to recover the Born rule \(\mathrm{tr}(\rho E_i)\). The ML does not change QM statistics; it only supplies a semantics for where the operators come from.

\subsection{Composition and Context (optional category view)}
\label{ssec:category}
View \(\mathbf{M}\) as a category of instructions with morphisms that compose. The rendering is a functor \(\mathcal{R}_f:\mathbf{M}\to \mathbf{SDF}_f\). Delayed-choice experiments correspond to choosing different cones in \(\mathbf{SDF}_f\); ML provides a single consistent assignment when frames couple \cite{baez_stay_2010}.

\subsection{A simple rendering diagram}
\begin{figure}[h]
\centering
\begin{tikzcd}[column sep=large, row sep=large]
{\text{Instruction } a \in \mathcal{A}}
  \arrow[r, "R_f"]
  \arrow[d, phantom, "{\scriptstyle T(a,f)\,C_s(f)=1}" description]
& {O_{a,f} \in \mathcal{B}(\mathcal{H}_f)}
  \arrow[r, "{\text{measurement in frame } f}" yshift=.2cm]
& {\text{record in SDF}} \\
{} & {} & {}
\end{tikzcd}
\caption{Rendering pipeline: an instruction \(a\) is mapped to a frame-operator \(O_{a,f}\) and then measured in the SDF. The delay law \(T \cdot C_s = 1\) constrains deployment timing.}
\label{fig:pipeline}
\end{figure}

\section{Operational Equivalence and Falsifiers}
\label{sec:equivalence}
\textbf{Proposition (operational equivalence).} For standard experiments in scope \(S\) (single-photon interferometry, EPRB tests, delayed choice, standard timing under SR/GR), there exist \((\mathcal{A},R_f,\mu)\) reproducing the TLM predictions.

\textit{Sketch.} For each experiment, pick a representation \(R_f\) that maps instruction classes to the standard POVMs on \(\mathcal{H}_f\). Use the spectral theorem to construct probability assignments equivalent to Born frequencies. Enforce \(T \cdot C_s = 1\) to match SR/GR clock behavior in each frame. One-absorption is encoded by restricting \(\mu\) to instruction sets that select exactly one compatible endpoint per quantum. This reproduces TLM outcomes without adding causal parameters.

\paragraph{Falsifiers that break ML while leaving TLM intact.}
\begin{enumerate}[label=F\arabic*.]
\item Duplicate absorption of a single quantum at spacelike separation with correct energy accounting in both records.
\item Preparation-noncontextual frequency shifts created only by description re-labeling in ML with the same physical state and POVM in SDF.
\item Marginal signaling: target marginals change with distant phase settings without conditioning.
\item Path-history residues in closed loops where SR/GR predict zero net differential aging.
\end{enumerate}

\section{Worked Examples}
\label{sec:examples}
\subsection{Single-Photon Interferometer}
Let \(a\in\mathcal{A}\) denote an instruction class ``emission to absorption with optional recombination.'' Choose \(R_f(a)=U^\dagger (\ket{0}\!\bra{0}) U\) where \(U\) is the Mach--Zehnder unitary with optional second beamsplitter. With the beamsplitter inserted, \(R_f(a)\) projects onto the output port with interference; removed, it projects onto which-path ports. The ML carries no mid-flight state; SDF renders the appropriate operator at detection. No double hits occur.




\subsection{EPRB Correlations}
Let \(a\) encode a bipartite instruction. Pick \(R_f(a)\) that yields a product of local POVMs with a standard entangled state \(\rho\). For angles \(\theta_A,\theta_B\) we obtain
\[
\mathrm{tr}\!\big[\rho\, (\vec{\sigma}\!\cdot\! \hat{n}_{\theta_A})\otimes(\vec{\sigma}\!\cdot\! \hat{n}_{\theta_B})\big].
\]
Ordering flips of spacelike-separated measurements are immaterial at ML level; SDF enforces no-signaling. For interpretational comparators, see the transactional and relational proposals \cite{cramer_1986,rovelli_1996}.




\subsection{Mass--Time Reciprocity and Compton Frequency}
For a rest configuration, we identify the intrinsic rate \(C_s\) with the Compton frequency \(C_s = mc^2/\hbar\). With \(C_s=1/T\) by definition, we obtain
\[
T \cdot m = \frac{\hbar}{c^2}.
\]
For photons \(m=0\) implies \(T=0\), matching null proper time. See also the TLM derivations and bridge-law discussions in \cite{mckinley_cornerstone_2025,mckinley_edl_2025}.






\subsection{SR Compatibility}
For a moving configuration with Lorentz factor \(\gamma\), the observed phase rate is \(\omega = \gamma mc^2/\hbar = \gamma C_s\). Since \(C_s=1/T\), the dilated delay is \(T'=\gamma T\). This is standard time dilation written as a rendering-rate effect, consistent with SR \cite{einstein_1905} without changing TLM.






\subsection{Weak-Field GR and Redshift}
In a potential \(\Phi\) with \(|\Phi|/c^2 \ll 1\), clocks tick with
\[
\frac{\Delta T}{T} \approx \frac{\Phi}{c^2}.
\]
Equivalently, \(C_s\) shifts by \(-\Phi/c^2\). The ML reading preserves the same redshift because \(T\) is rendered in the SDF and inherits GR's potential dependence; for a thermodynamic perspective on Einstein dynamics, see \cite{jacobson_1995}.













\begin{figure}[t]
\centering
\begin{tikzpicture}
  \begin{axis}[
    width=11.5cm, height=7cm,
    xlabel={Mass $m$ (arb.)}, ylabel={Delay $T$ (arb.)},
    title={Inverse relation of the \MTterm: $T \cdot m = \hbar/c^2$},
    domain=0.1:10, samples=200, thick,
    axis lines=left, grid=both, ymin=0, xmin=0,
    legend pos=north east
  ]
    \addplot {1/x};
    \legend{$T \propto 1/m$}
  \end{axis}
\end{tikzpicture}
\caption{Schematic of the \MTterm\ (Eq.~\ref{eq:Tm}). Increasing rest mass corresponds to shorter rendering delay, while massless quanta have \(T=0\).}
\label{fig:Tm-plot}
\end{figure}
















\subsection{Pushforward to Born Statistics}
Let \((\mathcal{A},\mu)\) be such that each preparation induces a probability measure \(\mu_{\text{prep}}\) on instruction classes. If \(R_f\) maps classes to a POVM \(\{E_i\}\), define
\[
p(i) = \mu_{\text{prep}}\big(R_f^{-1}(E_i)\big).
\]
Assume noncontextuality with respect to unitary dilation of \(R_f\) and sigma-additivity. Then \(p(i)\) factors through a density operator \(\rho\) by Gleason-type arguments, yielding \(p(i)=\mathrm{tr}(\rho E_i)\). The ML thus reproduces standard statistics with no extra parameters.

\section{Implications and Unification (Delay \texorpdfstring{\(\times\)}{x} Mechanics)}
\label{sec:implications}
Within TLM, dynamics in the SDF are viewed as delayed renderings rather than causal forces. The ML interpretation leaves this intact while clarifying that: (i) the selection of rendered operators is mathematical (algebraic or functorial), (ii) deployment timing remains governed by \(T \cdot C_s = 1\), and (iii) unification prospects center on identifying structural correspondences between admissible instruction classes and admissible SDF geometries. The practical payoff is a cleaner separation: ``what renders'' (algebraic structure) versus ``how fast it renders'' (delay law).\\

\noindent For detailed axiomatizations and worked derivations within TLM proper, see \cite{mckinley_tlm_v20_2025,mckinley_cornerstone_2025,mckinley_edl_2025}.




\section{Thought-Experiment Table}
\label{sec:tests}
\begin{center}
\begin{tabular}{|l|l|l|l|}
\hline
Setup & TLM prediction & ML prediction & Falsifier \\
\hline
One-photon, two detectors & One hit only & Same & Two hits with energy \\
Delayed choice & Context at detection & Same & Retro-signaling in SDF \\
Entanglement swapping & No signaling & Same & Marginal changes \\
Twin loop with zero net aging & Zero residue & Same & Path-history residue \\
No mid-flight energy & No energy en route & Same & Extractable mid-path energy \\
\hline
\end{tabular}
\end{center}

\clearpage

\section{Glossary}
\label{sec:glossary}
\textbf{\(\mathcal{F}\) (Frames).} The set of observer frames; each \(f\in\mathcal{F}\) carries a Hilbert space \(\mathcal{H}_f\) and rendering map \(R_f\).\\
\textbf{Math Layer (ML).} A timeless, non-dynamical mathematical layer identified with QP. Supplies instruction classes \(a\in\mathcal{A}\).\\
\textbf{Rendering map \(R_f\).} A frame-indexed map from instructions to bounded operators on \(\mathcal{H}_f\).\\
\textbf{Delay \(T\).} Rendering delay in the SDF. Obeys \(T \cdot C_s = 1\).\\
\textbf{Causal resolution rate \(C_s\).} The rate \(1/T\). At rest equals \(mc^2/\hbar\).\\
\textbf{One-absorption rule.} Each quantum resolves to exactly one absorber.\\
\textbf{No instruction cost.} Description length and compression have no causal role.\\
\textbf{SDF.} Spacetime Deployment Frame where events are experienced with GR timing.\\
\textbf{\(\mathcal{B}(\mathcal{H}_f)\).} Bounded linear operators on the Hilbert space \(\mathcal{H}_f\).\\
\textbf{\(^*\)-algebra.} An algebra with an involution supporting adjoints; self-adjoint elements represent observables.\\
\textbf{Mass-Time Relation} The relation \(T \cdot m = \hbar/c^2\) for rest configurations; see Eq.~\ref{eq:Tm}.


\begin{figure}[t]
\centering
\begin{tikzpicture}[node distance=2.6cm, every node/.style={align=center,font=\small}]
\node[draw,rounded corners,fill=green!5,minimum width=3.6cm] (A) {Detector A};
\node[draw,rounded corners,fill=green!5,minimum width=3.6cm,right=of A] (B) {Detector B};
\coordinate (midpoint) at ($(A.east)!0.5!(B.west)$);
\node[draw,rounded corners,fill=blue!8,minimum width=5.4cm,above=1.6cm of midpoint] (QP) {Timeless instruction for bipartite trial};
\draw[dashed, thick, ->] (QP.south) -- (A.north);
\draw[dashed, thick, ->] (QP.south) -- (B.north);
\draw[<->,thick,red!60] (A.east) -- (B.west) node[midway,above,yshift=0.5ex]{\scriptsize (no spacetime signal required)};
\end{tikzpicture}
\caption{Entangled outcomes as co-rendered endpoints of a single timeless instruction; no signaling.}\label{fig:entanglement-schematic}
\end{figure}



\section{Conclusion}
\label{sec:conclusion}
Identifying QP with a math layer is a conservative reading of TLM. It preserves equations, predictions, and test proposals. It offers a compact formal vocabulary for papers and talks while keeping falsifiability clear.



\begin{thebibliography}{99}

\bibitem{mckinley_not_obviously_false_2025}
J.~C.~W. McKinley, \textit{Why the Timeless Light Model is Not Obviously False} (2025).
Zenodo. \href{https://doi.org/10.5281/zenodo.17118184}{doi:10.5281/zenodo.17118184}.

\bibitem{mckinley_tlm_v20_2025}
J.~C.~W. McKinley, \textit{Timeless Light Model (TLM v2.0): Frameless Quanta, Framed Observers, and Bridge Laws} (2025).
Zenodo. \href{https://doi.org/10.5281/zenodo.16934697}{doi:10.5281/zenodo.16934697}.

\bibitem{mckinley_hilbert_frame_2025}
J.~C.~W. McKinley, \textit{Hilbert Space as Frame Representation: A Timeless Light Model Reinterpretation} (2025).
Zenodo. \href{https://doi.org/10.5281/zenodo.17070118}{doi:10.5281/zenodo.17070118}.

\bibitem{mckinley_binary_law_2025}
J.~C.~W. McKinley, \textit{The Binary Law of Quanta: Location as a Timeless Choice} (2025).
Zenodo. \href{https://doi.org/10.5281/zenodo.16913425}{doi:10.5281/zenodo.16913425}.

\bibitem{mckinley_pairing_2025}
J.~C.~W. McKinley, \textit{Generalized Pairing Law: No Quantum Emission Without an Absorber} (2025).
Zenodo. \href{https://doi.org/10.5281/zenodo.16892099}{doi:10.5281/zenodo.16892099}.

\bibitem{mckinley_edl_2025}
J.~C.~W. McKinley, \textit{The Emission Delay Law: A General Principle for the Realization of Quanta in the Timeless Light Model} (2025).
Zenodo. \href{https://doi.org/10.5281/zenodo.17032235}{doi:10.5281/zenodo.17032235}.

\bibitem{mckinley_cornerstone_2025}
J.~C.~W. McKinley, \textit{Deriving Cornerstone Equations from TLM Axioms} (2025).
Zenodo. \href{https://doi.org/10.5281/zenodo.16596589}{doi:10.5281/zenodo.16596589}.

\bibitem{einstein_1905}
A. Einstein, \textit{Zur Elektrodynamik bewegter K\"{o}rper}, Ann. Phys. \textbf{17}, 891--921 (1905).
\href{https://doi.org/10.1002/andp.19053221004}{doi:10.1002/andp.19053221004}.

\bibitem{cramer_1986}
J.~G. Cramer, \textit{The transactional interpretation of quantum mechanics}, Rev. Mod. Phys. \textbf{58}, 647--687 (1986).
\href{https://doi.org/10.1103/RevModPhys.58.647}{doi:10.1103/RevModPhys.58.647}.

\bibitem{rovelli_1996}
C. Rovelli, \textit{Relational quantum mechanics}, Int. J. Theor. Phys. \textbf{35}, 1637--1678 (1996).
\href{https://doi.org/10.1007/BF02302261}{doi:10.1007/BF02302261}.

\bibitem{jacobson_1995}
T. Jacobson, \textit{Thermodynamics of spacetime: The Einstein equation of state}, Phys. Rev. Lett. \textbf{75}, 1260--1263 (1995).
\href{https://doi.org/10.1103/PhysRevLett.75.1260}{doi:10.1103/PhysRevLett.75.1260}.

\bibitem{barbour_1994}
J.~B. Barbour, \textit{The timelessness of quantum gravity: I. The evidence from the classical theory}, Class. Quantum Grav. \textbf{11}, 2853--2873 (1994).
\href{https://doi.org/10.1088/0264-9381/11/12/005}{doi:10.1088/0264-9381/11/12/005}.

\bibitem{baez_stay_2010}
J.~C. Baez and M. Stay, \textit{Physics, Topology, Logic and Computation: a Rosetta Stone}, in \emph{New Structures for Physics}, Springer (2010).
\href{https://doi.org/10.1007/978-3-642-12821-9_1}{doi:10.1007/978-3-642-12821-9\_1}.
\end{thebibliography}




\end{document}


```

</details>

---
{% endraw %}
