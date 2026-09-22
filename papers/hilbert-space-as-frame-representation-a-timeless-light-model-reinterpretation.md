---
layout: default
title: '[2025] Hilbert Space as Frame Representation: A Timeless Light Model Reinterpretation'
description: 'Publication metadata and archived raw LaTeX source by John C. W. McKinley.'
permalink: /papers/hilbert-space-as-frame-representation-a-timeless-light-model-reinterpretation/
paper: true
---
{% raw %}
# [2025] Hilbert Space as Frame Representation: A Timeless Light Model Reinterpretation
*   **DOI:** [10.5281/zenodo.17070118](https://doi.org/10.5281/zenodo.17070118)
*   **Date:** 6 September 2025

<details markdown="1">
<summary><b>Click to view Raw LaTeX Source</b></summary>

```latex
\documentclass[12pt,letterpaper]{article}

% ------- Packages -------




\usepackage{tikz}
\usetikzlibrary{shapes.geometric, arrows.meta, positioning, shadows, fit, backgrounds}


\usepackage[margin=1in]{geometry}
\usepackage[T1]{fontenc}
\usepackage[utf8]{inputenc}
\usepackage{lmodern}
\usepackage{microtype}
\usepackage{amsmath,amssymb}
\usepackage{enumitem}
\usepackage[most]{tcolorbox}
\tcbset{colback=gray!5,colframe=black,boxrule=0.6pt,arc=2mm}
\newtcolorbox{axiombox}[1]{breakable,title={#1},fonttitle=\bfseries}
\usepackage{hyperref}
\hypersetup{colorlinks=true,linkcolor=blue,urlcolor=blue,citecolor=blue}

% ------- Metadata -------
\title{Hilbert Space as Frame Representation:\\
A Timeless Light Model Reinterpretation}
\usepackage{orcidlink}
\author{John C. W. McKinley\orcidlink{0009-0005-7097-5035}\\Independent Researcher}
\date{September 6, 2025}

\begin{document}
\maketitle

\begingroup
  \footnotetext[1]{This version published at
  \href{https://doi.org/10.5281/zenodo.17070118}{https://doi.org/10.5281/zenodo.17070118}.}
\endgroup

\begin{abstract}
In standard quantum mechanics, the Hilbert space provides the state space for all possible
configurations of a system, equipped with an inner product that yields probabilities and
operators that correspond to observables. In the Timeless Light Model (TLM), the ontologically
senior Quantum Platform (QP) is not a Hilbert space with bases, operators, or inner products.
It is \emph{minimal}: QP records contain only the boundary data required for conservation and
rendering into the Spacetime Deployment Frame (SDF), encoded as an instruction tuple
$I=\langle x^\mu_e,x^\mu_a;\Delta p^\mu,\Delta J^{\mu\nu},\Delta Q\rangle$ \cite{McKinley2025_Magnitude}.
Beyond that boundary data, QP carries no spacetime geometry or superpositional structure.
Accordingly, Hilbert space is \emph{not} the QP itself but the \emph{frame-level representation}
of QP instructions after deployment. In this reinterpretation, the structure of Hilbert space
reflects how frames render outcomes, not the timeless substrate. Collapse is re-read as frame
rendering, entanglement as co-resolution of instructions, and the Born rule as a statistical
law of exclusive deployment. The framework aligns Hilbert formalism with TLM axioms
(frameless ticks, mass--delay duality, causal resolution constancy) \cite{McKinley2025_TLMv2},
and with the minimal instruction interface \cite{McKinley2025_Magnitude}, the no mid-flight
energy principle \cite{McKinley2025_NoMidflight}, and the Emission Delay Law \cite{McKinley2025_EDL}.
Predictions include achromatic lensing residuals, one-absorber exclusivity, and small phase-step
deviations in gravitational wave signals. We reinterpret standard quantum formalisms within a Timeless Light Model. Our account keeps the EPR completeness challenge in view \cite{einstein1935} and respects the empirical constraints of Bell's theorem \cite{bell1964}. At the frame level we retain Hilbert-space vectors and Born probabilities as a rendering rule, without ontic collapse. This stance differs from relational quantum mechanics \cite{rovelli1996}, Everettian branching \cite{wallace2012}, and QBist personalist probability \cite{fuchs2017}. Energy transfer is modeled as one emission-absorption event, echoing absorber-style reasoning \cite{wheelerfeynman1945}.







\end{abstract}

\section{Introduction}
In standard physics, Hilbert space $\mathcal{H}$ is the universal container for quantum
states. It encodes superposition, orthogonality, measurement via Hermitian operators,
and composite systems through tensor products. The TLM program, by contrast, posits
a timeless Quantum Platform (QP) in which quanta exist only as frameless state-change
ticks $\{E,A\}$: emission down-ticks and absorption up-ticks. Frames, owned by observers,
supply time, space, and causal order.

The key concern addressed here is whether the QP should be identified with Hilbert
space. We argue it should not: QP is ontologically senior and \emph{minimal} in content,
while Hilbert space is the \emph{mathematical shadow} that frames project when rendering outcomes.

\section{Hilbert Space in Standard Physics}
\begin{itemize}[leftmargin=2em]
\item \textbf{State vectors:} $|\psi\rangle \in \mathcal{H}$ encode system states.
\item \textbf{Observables:} Hermitian operators $A$ with eigenvalues as outcomes.
\item \textbf{Dynamics:} Schr\"odinger evolution $|\psi(t)\rangle = U(t)|\psi(0)\rangle$.
\item \textbf{Probability:} Born rule $P(a) = |\langle a|\psi\rangle|^2$.
\item \textbf{Composition:} $\mathcal{H}_{\text{tot}} = \mathcal{H}_1 \otimes \mathcal{H}_2$ enables entanglement.
\end{itemize}
This formalism is powerful, but silent on ontology: it tells us how to calculate, not what
\emph{is}.

\section{TLM Foundations}
TLM v2.0 formalizes the following axioms \cite{McKinley2025_TLMv2}:
\begin{axiombox}{Axioms}
\begin{enumerate}[label=A\arabic*]
\item \textbf{Frameless quanta:} Quanta are ticks $\{E,A\}$ with no path, time, or space.
\item \textbf{Frames belong to observers:} Frames provide clocks, rulers, and causal order.
\item \textbf{Mass--Delay Duality:} $T \cdot m = \hbar/c^2$.
\item \textbf{Causal Resolution Constancy:} $T \cdot C_s = 1$.
\item \textbf{Binary Law:} Each instruction resolves to exactly one absorber (0/1 toggle).
\end{enumerate}
\end{axiombox}
These axioms position QP as ontologically senior, with Hilbert space emerging only as a
frame-level formalism. The FRAME--CHARGE toggle ontology provides a compact criterion
for particle-hood in frames \cite{McKinley2025_FrameYes}.

\subsection*{Minimal QP record vs Hilbert structure}
In TLM, a realized instruction in QP is recorded as the minimal tuple
$I=\langle x^\mu_e,x^\mu_a;\Delta p^\mu,\Delta J^{\mu\nu},\Delta Q\rangle$ \cite{McKinley2025_Magnitude}.
This boundary data is sufficient to enforce conservation at endpoints and to render the event
into the SDF. It does \emph{not} endow QP with Hilbert-space structure (no basis decomposition,
no superposition algebra, no operator spectrum). Thus QP is minimal for conservation, whereas
Hilbert space is a predictive representation used by frames.

\section{Hilbert Space as Frame Representation}
We now refine the mapping:
\begin{itemize}[leftmargin=2em]
\item \textbf{Not identity:} QP is not Hilbert space; it lacks bases, operators, and inner products.
\item \textbf{Representation:} Hilbert space formalism is how frames render QP ticks into
predictive structure. This agrees with the \emph{minimal instruction interface}
$I=\langle x^\mu_e,x^\mu_a;\Delta p^\mu,\Delta J^{\mu\nu},\Delta Q\rangle$ that carries only boundary data
required for conservation and rendering \cite{McKinley2025_Magnitude}.
\item \textbf{Collapse:} In TLM, collapse = frame rendering. The QP instruction itself is
already resolved timelessly; the frame chooses the displayed outcome. The \emph{no mid-flight
energy} principle reinforces that there is no energetic store along a path to be tapped
\cite{McKinley2025_NoMidflight}.
\item \textbf{Entanglement:} Entanglement = co-resolution of multiple $\{E,A\}$ instructions
in QP, projected into tensor-product form by frames.
\item \textbf{Born rule:} $|\langle a|\psi\rangle|^2$ emerges as the statistical law of exclusive
absorber registration. Realization of any quantum requires a compatible paired condition;
if none exists, emission is delayed until one becomes available, per the Emission Delay
Law \cite{McKinley2025_EDL}.
\end{itemize}




\begin{tikzpicture}[
    node distance=1.5cm,
    font=\sffamily,
    qp/.style={
        rectangle,
        rounded corners=8pt,
        draw=blue!80,
        fill=blue!10,
        very thick,
        minimum height=2.5cm,
        text width=7.5cm,
        align=center,
        drop shadow={opacity=0.4, shadow xshift=2pt, shadow yshift=-2pt}
    },
    frame/.style={
        rectangle,
        draw=black!70,
        fill=gray!5,
        thick,
        dashed
    },
    hilbert/.style={
        rectangle,
        rounded corners=4pt,
        draw=green!50!black,
        fill=green!10,
        thick,
        text width=6.5cm,
        align=left,
        font=\small\sffamily
    },
    arrow_label/.style={
        align=left,
        font=\sffamily\itshape,
        text width=8cm
    },
    main_arrow/.style={
        -Stealth,
        ultra thick,
        blue!60,
        draw,
        shorten >=4pt,
        shorten <=4pt
    }
]

% Title
\node[font=\Large\bfseries] (title) {Conceptual Hierarchy in the Timeless Light Model (TLM)};

% QP node
\node[qp, below=0.7cm of title] (qp_node) {
    \textbf{Quantum Platform (QP): Ontological Substrate}\\[2pt]
    \rule{\linewidth}{0.4pt}\\[4pt]
    Timeless, frameless, and minimal. Contains only boundary data for conservation and rendering, encoded in instruction tuples:\\
    $I=\langle x^\mu_e,x^\mu_a;\Delta p^\mu,\Delta J^{\mu\nu},\Delta Q\rangle$
};

% Hilbert Space node
\node[hilbert, below=4.5cm of qp_node] (hilbert_node) {
    \textbf{Hilbert Space ($\mathcal{H}$): Frame-Level Formalism}\\[6pt]
    \textbullet\ \textbf{State vectors:} $|\psi\rangle \in \mathcal{H}$\\
    \hspace*{1em}(represent potential outcomes)\\[6pt]
    \textbullet\ \textbf{Observables:} Hermitian operators $\hat{A}$\\
    \hspace*{1em}(represent measurements)\\[6pt]
    \textbullet\ \textbf{Probabilities:} Born rule $|\langle a|\psi\rangle|^2$\\
    \hspace*{1em}(statistical law of rendering)
};

% Draw the SDF frame BEHIND (background layer) so it doesn't cover hilbert_node
\begin{scope}[on background layer]
  \node[frame, fit=(hilbert_node), inner sep=30pt] (sdf_frame) {};
\end{scope}

% SDF label
\node[font=\sffamily\bfseries, above=-.85cm of sdf_frame.north] (sdf_label) {Spacetime Deployment Frame (SDF)};

% Observer's Reality label, positioned relative to SDF label
\node[font=\sffamily\bfseries, anchor=north east, xshift=-1cm, yshift=0.3cm] at (sdf_label.south west) {Observer's Reality};

% Main arrow with annotation
\draw[main_arrow] (qp_node.south) -- (sdf_frame.north)
    node[midway, right=.7cm, arrow_label] (reinterpretation) {
        \textbf{TLM Reinterpretation}\\[5pt]
        Collapse $\equiv$ Frame Rendering\\[5pt]
        Entanglement $\equiv$ Co-resolution
    };

\end{tikzpicture}



\section{Corrections and Clarifications}
\subsection{Phase Units}
Earlier drafts gave $\Delta \phi \sim Gm/c^3$, which has units of time. Corrected:
\[
\Delta \phi \sim \omega \frac{Gm}{c^3},
\]
with $\omega$ the carrier frequency, yielding a dimensionless phase.

\subsection{Relativistic Mapping}
Effective mass $m_{\text{eff}} = \gamma m_0$ gives
\[
T(\gamma) = \frac{\hbar}{c^2 \gamma m_0} = \frac{T_0}{\gamma}.
\]
Intrinsic delay shrinks as mass-energy grows, while frame-rendered clock intervals dilate
as $t = \gamma T_0$, reproducing SR.

\subsection{One-Absorber Exclusivity}
Each photon tick resolves to exactly one absorption; no ``orphan'' or split quanta are
permitted.

\section{Predictions}
\begin{itemize}[leftmargin=2em]
\item \textbf{Achromatic lensing residuals:} frequency-independent delay offsets.
\item \textbf{Gravitational wave micro-steps:} post-template phase staircases of amplitude
$\ll 1$ radian.
\item \textbf{Dark matter analogue:} FRAME-YES / CHARGE-NO states appear as gravitating
yet non-interacting matter.
\end{itemize}



% ===== Background and Motivation (new or revised section) =====
\section{Background and Motivation}
Debates over locality and completeness begin with the EPR argument \cite{einstein1935} and culminate in Bell's no-go results \cite{bell1964}. We take as fixed the observed violations of Bell inequalities with no superluminal signaling. The Timeless Light Model (TLM) explains these nonclassical correlations by relocating causal resolution to a Quantum Platform that is timeless relative to frame rendering, so the Spacetime Deployment Frame records already-resolved outcomes while preserving no-signaling constraints \cite{bell1964}.


% ===== Hilbert Space as Frame-Level Bookkeeping =====
\section{Hilbert Space as Frame-Level Bookkeeping}
Within the Spacetime Deployment Frame we use the standard Hilbert-space formalism: states $|\psi\rangle \in \mathcal{H}$, Hermitian observables, and Born-rule frequencies. Our interpretive claim is not that collapse is ontic, but that it is a rendering update for the frame. This differs from relational QM \cite{rovelli1996}, Everettian treatments \cite{wallace2012}, and QBism \cite{fuchs2017}, while remaining consistent with Bell constraints \cite{bell1964}.


% ===== Measurement and Nonlocal Correlations =====
\section{Measurement and Nonlocal Correlations}
EPR highlights tension between locality, realism, and completeness \cite{einstein1935}. Bell shows that any completion reproducing quantum statistics must violate at least one classical premise \cite{bell1964}. In TLM the Quantum Platform resolves which emission-absorption pairs exist before the frame renders them. Correlations that violate Bell inequalities then reflect co-resolved endpoints, not signals in spacetime, consistent with no signaling \cite{bell1964}.


% ===== Emission-Absorption Principle =====
\section{Emission-Absorption Principle}
Following the absorber intuition \cite{wheelerfeynman1945}, we model each quantum of energy as one event constituted by emission and absorption. There is no mid-flight energy in the frame; instead, the Quantum Platform resolves a conservation-respecting pairing, and the frame renders two ends of one transaction. This positioning is compatible with EPR-style completeness concerns and Bell constraints \cite{einstein1935,bell1964}.


% ===== Positioning vs. Major Interpretations (short comparative note) =====
\section{Positioning vs. Major Interpretations}
TLM keeps the standard mathematics of $\mathcal{H}$ but interprets apparent collapse as frame rendering. This contrasts with RQM's relation-defined states \cite{rovelli1996}, Everettian branching that seeks to recover the Born rule in a decoherent multiverse \cite{wallace2012}, and QBist subjectivist probabilities \cite{fuchs2017}. Empirically, all must answer Bell \cite{bell1964}; TLM does so by treating correlations as co-resolved at the platform level, not as superluminal influences in spacetime.



\section{On Ontology vs. Formalism}
A final clarification: Hilbert space in standard physics is a \emph{formal construct},
not an ontological claim. It is a mathematical container that encodes probabilities,
superpositions, and operator actions, but it does not by itself assert what exists.
Interpretations differ: operational schools treat it as a predictive tool only,
while realist schools identify it with the physical wavefunction. The Timeless Light
Model takes a third stance: the Quantum Platform (QP) is ontological and minimal in content
(boundary data for conservation and rendering), while Hilbert space is the \emph{frame-level
formalism} by which observers represent QP outcomes. Thus, Hilbert space is the mathematical
shadow of QP, not QP itself. This resolves the category error of mistaking a predictive space
for the timeless substrate, while preserving Hilbert formalism as a faithful image of QP deployment.

\section{Conclusion}
Hilbert space is not the QP itself. It is the frame-level representation of timeless
instructions once rendered in SDF. QP remains minimal, carrying only the boundary data
needed for conservation and rendering, without Hilbert-space structure. The revised
interpretation maintains consistency with TLM v2.0 axioms and the minimal instruction
interface, and supports falsifiable predictions.

\begin{thebibliography}{9}



\bibitem{einstein1935}
A. Einstein, B. Podolsky, and N. Rosen,
``Can Quantum-Mechanical Description of Physical Reality Be Considered Complete?''
\emph{Phys. Rev.} \textbf{47}, 777 (1935).
\href{https://doi.org/10.1103/PhysRev.47.777}{doi:10.1103/PhysRev.47.777}

\bibitem{bell1964}
J. S. Bell,
``On the Einstein Podolsky Rosen Paradox,''
\emph{Physics Physique Fizika} \textbf{1}, 195 (1964).
\href{https://doi.org/10.1103/PhysicsPhysiqueFizika.1.195}{doi:10.1103/PhysicsPhysiqueFizika.1.195}

\bibitem{rovelli1996}
C. Rovelli,
``Relational quantum mechanics,''
\emph{Int. J. Theor. Phys.} \textbf{35}, 1637 (1996).
\href{https://doi.org/10.1007/BF02302261}{doi:10.1007/BF02302261}

\bibitem{wallace2012}
D. Wallace,
\emph{The Emergent Multiverse: Quantum Theory according to the Everett Interpretation}
(Oxford University Press, 2012).
ISBN: 978-0199546964

\bibitem{fuchs2017}
C. A. Fuchs,
``Notwithstanding Bohr, the reasons for QBism,''
\emph{Mind and Matter} \textbf{15}(2), 245--300 (2017).
Available at \href{https://arxiv.org/abs/1705.03483}{arXiv:1705.03483}

\bibitem{wheelerfeynman1945}
J. A. Wheeler and R. P. Feynman,
``Interaction with the absorber as the mechanism of radiation,''
\emph{Rev. Mod. Phys.} \textbf{17}, 157 (1945).
\href{https://doi.org/10.1103/RevModPhys.17.157}{doi:10.1103/RevModPhys.17.157}


\bibitem{McKinley2025_TLMv2}
J.~C.~W. McKinley.
\newblock Timeless Light Model (TLM v2.0): Frameless Quanta, Framed Observers,
and Bridge Laws.
\newblock Zenodo (2025). doi:\href{https://doi.org/10.5281/zenodo.16934697}{10.5281/zenodo.16934697}.

\bibitem{McKinley2025_FrameYes}
J.~C.~W. McKinley.
\newblock Ontology of Matter in the Timeless Light Model: From FRAME--CHARGE
Toggles to Particles.
\newblock Zenodo (2025). doi:\href{https://doi.org/10.5281/zenodo.16939101}{10.5281/zenodo.16939101}.

\bibitem{McKinley2025_Magnitude}
J.~C.~W. McKinley.
\newblock Handling Event Magnitude in the Timeless Light Model: A Minimal QP$\rightarrow$SDF Instruction Interface.
\newblock Zenodo (2025). doi:\href{https://doi.org/10.5281/zenodo.17033795}{10.5281/zenodo.17033795}.

\bibitem{McKinley2025_NoMidflight}
J.~C.~W. McKinley.
\newblock The ``No Mid-Flight Energy'' Principle: Operational Consistency and Ontological Implications for the Timeless Light Model (TLM).
\newblock Zenodo (2025). doi:\href{https://doi.org/10.5281/zenodo.17018871}{10.5281/zenodo.17018871}.

\bibitem{McKinley2025_EDL}
J.~C.~W. McKinley.
\newblock The Emission Delay Law: A General Principle for the Realization of Quanta in the Timeless Light Model.
\newblock Zenodo (2025). doi:\href{https://doi.org/10.5281/zenodo.17032235}{10.5281/zenodo.17032235}.


























\end{thebibliography}

\end{document}

```

</details>

---
{% endraw %}
