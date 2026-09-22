---
layout: default
title: '[2025] The Wait Phase in the Timeless Light Model (TLM v3.0): Explaining a Timeless Checkpoint for Novices and Experts'
description: 'Publication metadata and archived raw LaTeX source by John C. W. McKinley.'
permalink: /papers/the-wait-phase-in-the-timeless-light-model-tlm-v3-0-explaining-a-timeless-checkpoint-for/
paper: true
---
{% raw %}
# [2025] The Wait Phase in the Timeless Light Model (TLM v3.0): Explaining a Timeless Checkpoint for Novices and Experts
*   **DOI:** [10.5281/zenodo.17291452](https://doi.org/10.5281/zenodo.17291452)
*   **Date:** 7 October 2025

<details markdown="1">
<summary><b>Click to view Raw LaTeX Source</b></summary>

```latex
\documentclass[12pt,onecolumn]{article}

% ----- Encoding & fonts (pdfLaTeX) -----
\usepackage[utf8]{inputenc}
\usepackage[T1]{fontenc}
\usepackage{lmodern}

% ----- Page & layout -----
\PassOptionsToPackage{letterpaper,margin=1in}{geometry}
\usepackage{geometry}
\usepackage{setspace}
\setstretch{1.12}
\usepackage{fancyhdr}
\pagestyle{fancy}
\fancyhead{}
\fancyfoot{}
\fancyhead[R]{McKinley 2025}
\fancyfoot[C]{\thepage}
\renewcommand{\headrulewidth}{0.4pt}
\fancypagestyle{plain}{\fancyhead{}\renewcommand{\headrulewidth}{0pt}}

% ----- Graphics & floats -----
\usepackage{graphicx}
\usepackage{float}
\usepackage{booktabs}
\usepackage{array}
\newcolumntype{L}[1]{>{\raggedright\arraybackslash}p{#1}}
\usepackage{rotating}

% ----- Math & refs -----
\usepackage{amsmath,amssymb,amsthm,bm}
\usepackage{tikz}
\usetikzlibrary{arrows.meta,positioning,calc,shapes.geometric}
\usepackage{pgfplots}
\pgfplotsset{compat=1.18}
\usepackage{hyperref}
\hypersetup{colorlinks=true,linkcolor=blue,urlcolor=blue,citecolor=blue}
\usepackage{cleveref}
\usepackage{natbib}  % Added for better citation handling; use \citep{} for parenthetical, \citet{} for textual

% ----- Title -----
\title{\textbf{The Wait Phase in the Timeless Light Model (TLM v3.0): Explaining a Timeless Checkpoint for Novices and Experts}}
\author{John C. W. McKinley\quad \textit{Independent Researcher}\quad
\href{https://orcid.org/0009-0005-7097-5035}{ORCID: 0009-0005-7097-5035}}
\date{October 7, 2025}

\begin{document}
\maketitle
\thispagestyle{plain}

% ----- Abstract -----
\begin{abstract}
A photon in TLM is not a traveler; it is a timeless instruction with zero proper time. To a novice, this begs the question: if the instruction is instant, where do quantum uncertainty ($\psi$) and relativistic delays (GR/SR) originate? This paper presents the Wait Phase---a necessary, atemporal checkpoint in the central \textbf{Emit--Wait--Absorb} process. We emphasize that \textbf{Wait is where the timeless rules (authored by the Quantum Platform, QP) are applied as filters} to each instruction, allowing quantum probabilities to be resolved without time passing. This removes the need for mechanistic explanations of gravity (like ``delay gradients'') in favor of an elegant, axiomatic application layer. Using simple analogy, we clarify how TLM unifies quantum uncertainty and relativistic causality. Testable predictions, such as entanglement latency $\Delta t = \dfrac{GM}{c^3}$ near massive detectors, are emphasized to enhance empirical viability. TLM v3.0 extends transactional interpretations like Wheeler--Feynman absorber theory with a unique ontological framework, offering new insights into causality, time, and quantum gravity. This version published at \href{https://doi.org/10.5281/zenodo.17291452}{https://doi.org/10.5281/zenodo.17291452}. If you remember one thing: Wait is where the rules are applied, not where time passes.
\end{abstract}

\vspace{0.5cm}

% ----- Introduction -----
\section{Introduction}
If you've ever wondered how something that takes no time can still have many possible outcomes, this paper is for you.

Fundamental physics grapples with paradoxes at the intersection of quantum mechanics and general relativity, such as the null proper time of photons ($\tau=0$), instantaneous entanglement, and wavefunction collapse. The Timeless Light Model (TLM) addresses these by reinterpreting light not as particles propagating through spacetime but as timeless causal instructions authored on a pre-spatiotemporal Quantum Platform (QP) and rendered in an observer-accessible Spacetime Deployment Frame (SDF).

The TLM recasts photons as timeless instructions linking emission and absorption. That raises a novice puzzle: if the instruction is pre-resolved, why do we see interference and probabilities, and how does relativity enter? The answer is a middle step: Wait. Wait is not a delay in time; it is a rule-application step in a timeless layer (the QP). Once all rules are satisfied, the instruction finalizes and the SDF renders the single outcome.

This paper presents TLM v3.0, evolving from earlier versions \citep{mckinley2025wait,mckinley2025review} by integrating the Emit--Wait--Absorb triad and the Creator--Law Hierarchy. The addition of the Wait phase refines rather than replaces the model's original aim---answering how a photon ``knows'' its destination if emission and absorption occur in the same instant. Wait represents the timeless eligibility filter between emission and absorption, not a temporal delay. These refinements resolve wavefunction alignment issues and simplify gravitational mechanisms without invoking delay gradients. We highlight testable predictions to promote empirical scrutiny and position TLM as a viable alternative to standard interpretations. The contributions include updated axioms, a consolidated glossary, two diagrams, a sideways predictions table, rigorous derivations, and a discussion of future experimental directions.

 You do not need moving parts between emitter and absorber---just a place to apply the rules.

% ----- TLM Summary -----
\section{TLM Summary: The Two Worlds of Instruction}
The Timeless Light Model (TLM) reclassifies light and causality by proposing a dual-layer ontology. Photons are timeless causal instructions authored on the QP, a senior ontological layer. Effects like interference, energy transfer, and entanglement emerge from rendering these pre-resolved instructions into the SDF, subject to structural (QM) and delay (GR/SR) filtering imposed by the Creator--Law Hierarchy.

\begin{itemize}
  \item \textbf{Quantum Platform (QP):} The timeless, causally senior layer that authors all events as complete, pre-resolved Causal Instruction Arcs (CI-ARCs). Instructions here have no duration or location ($m=0 \Rightarrow T=0$). The QP also encodes the operating rules via the \textbf{Creator--Law Hierarchy}.
  \item \textbf{Spacetime Deployment Frame (SDF):} The observer-accessible layer that renders the instructions in sequence, imposing delay and structural filtering to produce temporally ordered experience. It is subordinate to the QP.
\end{itemize}

The transfer between layers is governed by the Mass--Delay Law ($T m = \hbar/c^{2}$) and the Causal Speed Law ($T C_s = 1$). For $m=0$, $T=0$, which appears in SDF as the $c$ limit.

\subsection*{Postulates/Axioms (v3.0)}
P1. \emph{Timeless Instruction Authoring}: Events are authored on QP as complete Emit--Wait--Absorb triads; only constraint-satisfying outcomes are written. \\
P2. \emph{Rendered Experience}: SDF renders instructions per the Creator--Law Hierarchy (QP authors QM structure and GR/SR delay rules). Time equals rendering delay.

% ----- Core Puzzle -----
\section{The Core Puzzle: How Timelessness Meets Uncertainty}
If an instruction is instant and pre-resolved in the QP, how can it still be a wavefunction ($\psi$) with many possible endings (superposition)? If a photon is an instruction that links emission ($x^\mu_e$) and absorption ($x^\mu_a$) instantaneously in the QP, the process appears predetermined. Yet nature is probabilistic, described by $\psi$.

\textbf{Answer:} the Wait Phase. The original Emit/Absorb pair was functionally complete but ontologically incomplete. The new Emit--Wait--Absorb triad is an internal logic check that ensures all quantum and relativistic constraints are satisfied before the instruction is rendered. Crucially, Wait is \emph{not} a time delay: the clock does not tick during Wait ($T=0$); it is an informational check in the QP’s timeless domain.

\subsection{The Office Metaphor: Why Instructions Wait}
Think of the QP as Head Office that issues a memo (the instruction) requiring approval before execution in the field (the SDF).

\begin{itemize}
  \item \textbf{Emit (Issue):} A worker (emitting atom) sends a complete CI-ARC to the QP with all candidate absorbers ($x^\mu_a$).
  \item \textbf{Wait (Check Eligibility):} The memo enters a non-temporal holding area.
  \begin{itemize}
    \item \textbf{Quantum Filter (QM):} $\psi$ acts as an eligibility map, re-weighting candidate endpoints.
    \item \textbf{Relativistic Filter (GR/SR):} Delay/geometry constraints authored by the QP are applied.
  \end{itemize}
  \item \textbf{Absorb (Finalize):} Once checks pass, a single outcome is finalized and rendered in SDF. Collapse is Wait ending.
\end{itemize}

\subsection{Wait Phase: The Checkpoint Where Rules Are Applied}
\begin{enumerate}
  \item \textbf{Emit:} QP issues a CI-ARC containing possible endpoints.
  \item \textbf{Wait:} Instruction held in timeless suspension ($T=0$) while two filters run: (i) \textbf{QM structure} ($\psi$ eligibility) and (ii) \textbf{GR/SR delay} (Creator--Law authored).
  \item \textbf{Absorb:} Once filters pass, the instruction resolves to one outcome, which SDF renders.
\end{enumerate}
\noindent\emph{Key message:} Wait is a rule check, not a clock tick.

% ----- Creator-Law Hierarchy -----
\section{QP is the Source of All Rules (The Creator--Law Hierarchy)}
We need not ask \emph{why} the universe obeys GR/SR if, in TLM, the QP \emph{drives} them.

\begin{itemize}
  \item \textbf{Axiom:} The QP authored GR/SR as immutable axioms (e.g., $T m = \hbar/c^{2}$). The QP dictates rules; the SDF executes them.
  \item \textbf{Benefit:} Replaces mechanistic ``delay gradients'' with an axiomatic why. Curvature/time dilation are executions of authored rules.
  \item \textbf{Testable Signature:} Because the Relativistic Filter is applied at Wait termination, TLM predicts \emph{entanglement latency} $\Delta t = \dfrac{G M_{\text{detector}}}{c^3}$.
\end{itemize}

% ----- Derivation Sketch -----
\section{Derivation Sketch (For Interested Readers)}
\textbf{Instruction tuple.} For massless quanta,
\[
I=\langle x^\mu_e, x^\mu_a; \Delta p^\mu, \Delta J^{\mu\nu}, \Delta Q \rangle,\quad
\Delta p^\mu \Delta p_\mu = 0,\quad d\tau = 0.
\]
\textbf{Timeless matching.} Let $f$ be a QP matching functional active only in Wait:
\[
|\psi(x_a)|^2 = |f(x_e,x_a)|^2,
\]
projecting to SDF as the observed absorption probability at $x_a$.
\textbf{Bridge laws as constraints.}
\[
T m = \frac{\hbar}{c^2},\qquad T C_s = 1,
\]
enforced at Wait termination; for $m=0$ the resolution is immediate in QP and appears as the $c$ bound in SDF \citep{mckinley2025emission,mckinley2025delay}.

% ----- Predictions & Tests -----
\section{Predictions and Tests}
\begin{table}[H]
  \centering
  \caption{Predictions and tests focused on the Wait Phase (novice and expert view)}
  \begin{tabular}{L{3.2cm} L{4.2cm} L{3.2cm} L{2.4cm} L{2.0cm}}
    \toprule
    \textbf{Prediction} & \textbf{Setup} & \textbf{Observable} & \textbf{Pass if} & \textbf{Status} \\
    \midrule
    Entanglement latency: $\Delta t=\dfrac{G M_{\text{det}}}{c^3}$ &
    Compare coincidence timing for identical entanglement experiments using detectors of different mass. &
    Systematic shift in coincidence time scaling with detector mass and local $G$. &
    Shift follows $GM/c^3$ scaling (within bounds). &
    Open \\
    No mid-flight energy (timeless photon) &
    Energy accounting in emitter/detector with long baselines and variable absorbers. &
    No usable energy exists between endpoints; only endpoint accounting closes. &
    Endpoint-only energy balance; no transport store. &
    Consistent \\
    Rule-first GR/SR compliance &
    High-precision interferometry under variable gravitational potential at detection. &
    Phase/timing follow GR/SR without intermediate transport assumptions. &
    Results match authored-rule predictions without carrier dynamics. &
    Consistent \\
    Null-path consistency ($d\tau=0$) &
    Time-of-flight vs.\ null geodesic constraints across media/vacuum. &
    No photon rest-frame or proper-time effects. &
    No rest-frame signatures; null predictions hold. &
    Consistent \\
    \bottomrule
  \end{tabular}
\end{table}

% ----- Diagrams -----
\section{Diagrams}
\begin{figure}[H]
  \centering
  \begin{tikzpicture}[
    >=Stealth,
    node distance=1.7cm,
    box/.style={rectangle,draw,minimum width=3.8cm,minimum height=1.9cm,align=center}
  ]
    \node (QP)   [box, fill=blue!10] {\textbf{Quantum Platform (QP/ML)}\\ \small Authors All Rules};
    \node (Wait) [box, below=1.5cm of QP, fill=green!10] {\textbf{Wait Phase} ($T=0$)\\ \small Atemporal Rules Application};
    \node (SDF)  [box, below=1.5cm of Wait, fill=red!10] {\textbf{Spacetime Deployment Frame (SDF)}\\ \small Executes Rules / Rendered Events};

    \draw[->,very thick] (QP.south) -- node[right,midway,xshift=1mm]{\textbf{Emit:} Instruction Issued} (Wait.north);
    \draw[->,very thick] (Wait.south) -- node[right,midway,xshift=1mm]{\textbf{Absorb:} Finalization} (SDF.north);

    \node (WvF) [align=left, font=\small, right=0.7cm of Wait, yshift=0.3cm] {Rule 1: QM Filter ($\psi$)};
    \node (Ent) [align=left, font=\small, right=0.7cm of Wait, yshift=-0.3cm] {Rule 2: GR/SR Filter (Creator--Law)};
    \draw[dashed, thin] (Wait.east) -- ++(2.2cm, 0);

    \node (BL1) [align=left, font=\small, left=0.8cm of Wait, yshift=0.4cm] {Source: $T m=\hbar/c^2$};
    \node (BL2) [align=left, font=\small, left=0.8cm of Wait, yshift=-0.4cm] {Source: $T C_s=1$};
    \draw[dashed, thin] (Wait.west) -- ++(-2.2cm, 0);

    \node[align=left, font=\small, below=0.4cm of SDF.center] {Displays time, $c$-limit, and curvature};
  \end{tikzpicture}
  \caption{Emit--Wait--Absorb triad. Instruction originates on QP, is filtered during atemporal Wait, then rendered in SDF.}
  \label{fig:process}
\end{figure}

\begin{figure}[H]
  \centering
  \begin{tikzpicture}
    \draw[->] (0,0) -- (4,0) node[right] {$x$};
    \draw[->] (0,0) -- (0,4) node[above] {$ct$};
    \node at (-0.2,-0.2) [below left] {$ds^2=0$};
    \draw (0,0) -- (3,3) node[midway, above right] {null path ($d\tau=0$)};
  \end{tikzpicture}
  \caption{Null worldline: photon proper time vanishes; no rest frame is definable.}
  \label{fig:nullpath}
\end{figure}

% ----- Glossary -----
\section{Glossary of TLM Terms}
\begin{table}[H]
  \centering
  \caption{Selected TLM glossary for the Emit--Wait--Absorb triad}
  \begin{tabular}{L{3.2cm} L{6.2cm} L{4.6cm}}
    \toprule
    \textbf{Term} & \textbf{Definition} & \textbf{Variants/Notes} \\
    \midrule
    \textbf{Wait Phase} & Atemporal QP checkpoint for applying rules and assessing wavefunction eligibility. & Ontological; $T=0$; ``quality control''. \\
    \textbf{QP} & Timeless layer that authors instructions and fundamental laws (source of rules). & Quantum Platform; Math Layer. \\
    \textbf{Creator--Law Hierarchy} & QP writes rules (QM structure, GR/SR delays); SDF executes them. & Replaces delay gradients. \\
    \textbf{Wavefunction} ($\psi$) & Timeless QP eligibility matching function (Quantum Filter in Wait). & Structure filter (QM). \\
    \textbf{Entanglement Latency} ($\Delta t$) & Predicted tiny delay in Absorb near heavy detectors: $\Delta t=\dfrac{G M_{\text{det}}}{c^{3}}$. & Signature of Wait termination. \\
    \textbf{Mass--Delay Law} & Rendering delay ($T$) vs.\ mass ($m$): $T m=\hbar/c^{2}$. & Instructional delay ($T$). \\
    \bottomrule
  \end{tabular}
\end{table}

% ----- For Experts -----
\section{For Experts: Comparisons and Extensions}
TLM extends transactional interpretations like Wheeler--Feynman absorber theory by treating the absorber as the finalizer of the timeless instruction, with Wait as the domain for quantum indeterminacy. Specifically, while Wheeler-Feynman requires both retarded and advanced waves, TLM's `Wait` phase places the entire eligibility check within the timeless QP, avoiding the need for physical advanced waves in spacetime \citep{mckinley2025photonthought,mckinley2025falsifiable}. For multi-particle systems, entanglement can be viewed as shared Wait arcs, where correlated instructions resolve simultaneously under the same filters. Future work could explore how Wait interacts with quantum gravity, potentially predicting horizon-scale effects in gravitational waves.

% ----- Conclusion -----
\section{Conclusion}
The \textbf{Wait Phase} is not a complicated mystery; it is the logical ``quality control'' step that makes TLM internally consistent. By defining \textbf{Wait as the point where the QP’s timeless rules (QM/GR/SR) are applied}, the model:
\begin{enumerate}
  \item Preserves the absolute timelessness of the photon (solving the $T=0$ paradox).
  \item Gives a non-temporal home to quantum uncertainty (the wavefunction).
  \item Unifies gravity (GR/SR) with quantum mechanics (QM) via complementary filters under the QP.
\end{enumerate}
The next step for TLM is the empirical measurement of \textbf{entanglement latency} ($\Delta t$). \textit{Accessible closer:} If a novice remembers one idea, remember this: Wait is a rule check, not a time delay.

% ----- Bibliography -----
\begin{thebibliography}{99}
\bibitem{mckinley2025wait} McKinley, J. C. W. (2025). The Wait Phase and Creator-Law Framework in the Timeless Light Model (TLM v3.0). \url{https://doi.org/10.5281/zenodo.17284109}.
\bibitem{mckinley2025photonthought} McKinley, J. C. W. (2025). Photon Thought Experiments and the Timeless Ontology: Why Photons and Quanta Are ``Not Here''. \url{https://doi.org/10.5281/zenodo.17216652}.
\bibitem{mckinley2025review} McKinley, J. C. W. (2025). A Review of the Timeless Light Model: Foundations, Derivations, and Empirical Predictions. \url{https://doi.org/10.5281/zenodo.16958221}.
\bibitem{mckinley2025emission} McKinley, J. C. W. (2025). The Emission Delay Law: A General Principle for the Realization of Quanta in the Timeless Light Model. \url{https://doi.org/10.5281/zenodo.17032235}.
\bibitem{mckinley2025falsifiable} McKinley, J. C. W. (2025). Falsifiable Prediction of Horizon-Scale Phase Shifts in Gravitational Waves from the Timeless Light Model. \url{https://doi.org/10.5281/zenodo.16730926}.
\bibitem{mckinley2025delay} McKinley, J. C. W. (2025). Massless Things Do Not Experience Time. \url{https://doi.org/10.5281/zenodo.17173126}.
\end{thebibliography}

\end{document}


```

</details>

---
{% endraw %}
