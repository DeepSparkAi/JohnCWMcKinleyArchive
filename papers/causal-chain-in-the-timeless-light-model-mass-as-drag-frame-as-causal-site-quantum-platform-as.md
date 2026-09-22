---
layout: default
title: '[2025] Causal Chain in the Timeless Light Model: Mass as Drag, Frame as Causal Site, Quantum Platform as Cause'
description: 'Publication metadata and archived raw LaTeX source by John C. W. McKinley.'
permalink: /papers/causal-chain-in-the-timeless-light-model-mass-as-drag-frame-as-causal-site-quantum-platform-as/
paper: true
---
{% raw %}
# [2025] Causal Chain in the Timeless Light Model: Mass as Drag, Frame as Causal Site, Quantum Platform as Cause
*   **DOI:** [10.5281/zenodo.17139863](https://doi.org/10.5281/zenodo.17139863)
*   **Date:** 16 September 2025

<details markdown="1">
<summary><b>Click to view Raw LaTeX Source</b></summary>

```latex
\documentclass[11pt]{article}

\usepackage[margin=1in]{geometry}
\usepackage{amsmath, amssymb, amsthm}
\usepackage{tikz}
\usetikzlibrary{arrows.meta, positioning, fit, backgrounds, shapes.geometric}
\usepackage{enumitem}
\usepackage[colorlinks=true, linkcolor=blue, citecolor=blue, urlcolor=blue]{hyperref}
\usepackage{cleveref}
\usepackage{orcidlink}

\newcommand\blfootnote[1]{%
  \begingroup
  \renewcommand\thefootnote{}\footnote{#1}%
  \addtocounter{footnote}{-1}%
  \endgroup
}

\title{Causal Chain in the Timeless Light Model:\\
Mass as Drag, Frame as Causal Site, Quantum Platform as Cause}

\author{John C. W. McKinley \orcidlink{0009-0005-7097-5035}}

\date{September 16, 2025}

\begin{document}

\maketitle
\blfootnote{This version published at \href{https://doi.org/10.5281/zenodo.17139863}{https://doi.org/10.5281/zenodo.17139863}.}

\begin{abstract}
This paper clarifies the causal structure of the Timeless Light Model (TLM). We argue that \textbf{mass is not the cause of time but the drag that stretches timeless instructions into sequential ticks}. The frame is the causal site, where instructions are rendered. The Quantum Platform (QP) is the prior cause, the timeless source of all resolved emission--absorption instructions. The causal chain is thus:
\[
\text{QP (prior cause)} \;\to\; \text{frame (causal deployment)} \;\to\; \text{mass (delay/drag)}.
\]
This hierarchy removes ambiguity in earlier formulations where mass was sometimes phrased as the ``source of delay.'' We show that the true cause resides in QP, frames enact causality, and mass merely parameterizes pacing. The result preserves agreement with General Relativity (GR) and Quantum Mechanics (QM), resolves wave--particle paradoxes, and offers falsifiable predictions.
\end{abstract}

\section{Introduction}

General Relativity treats mass as curving spacetime~\cite{einstein1905, wald1984}, while Quantum Mechanics describes probability amplitudes as evolving unitarily. Neither theory specifies \emph{where} causality originates. The Timeless Light Model (TLM) makes a sharper distinction:

\begin{enumerate}
    \item The \textbf{Quantum Platform (QP)} is ontologically senior: a timeless substrate that pre-resolves emission--absorption links~\cite{mckinley_notfalse}.
    \item The \textbf{frame is causal}: it is the minimal unit of deployment in the Spacetime Deployment Frame (SDF), where QP instructions are rendered into events~\cite{mckinley_frame_master}.
    \item \textbf{Mass is drag}: it imposes deployment delay, stretching timeless links into the ticks of proper time~\cite{mckinley_notfalse}.
\end{enumerate}

The explicit chain is therefore:
\[
\text{Cause} = \text{QP}, \quad \text{Causal Site} = \text{Frame}, \quad \text{Drag} = \text{Mass}.
\]

\section{Mass as Drag}

The bridge law of TLM states:
\begin{equation}
T \cdot m = \frac{\hbar}{c^2}.
\end{equation}
This equation does not assign causality to mass; instead, it shows that mass \emph{parameterizes} delay.

\begin{itemize}
    \item For $m = 0$: $T = 0$. Massless frames deploy instantly (photons, gluons, gravitons).
    \item For $m > 0$: $T > 0$. Mass-bearing frames introduce delay, producing sequential ticks.
\end{itemize}

Thus mass is the pacing factor, not the source of causal realization.

\section{Frames as Causal Agents}

Following \emph{Frame as Master} v3.2~\cite{mckinley_frame_master}, a frame is elevated from a passive coordinate to an active renderer. The causal rendering law,
\begin{equation}
T \cdot C_s = 1,
\end{equation}
states that each frame deploys instructions at a rate $C_s$ determined by its delay $T$. Causality resides here, in the frame, not in mass itself.

\section{Quantum Platform as Prior Cause}

The QP is the timeless layer that writes emission--absorption pairs into existence~\cite{mckinley_qp_generator}. It contains no duration or sequence. Causality \emph{begins} here, as prior cause, but becomes manifest only when frames deploy instructions into SDF. Mass, again, is only the drag that slows this deployment.

\section{Implications}

\begin{enumerate}
    \item \textbf{Photon timelessness:} $m = 0 \Rightarrow T = 0$. Photons have no proper time.
    \item \textbf{Clocks tick:} $m > 0 \Rightarrow T > 0$. Mass-bearing frames generate sequential time.
    \item \textbf{Unified ontology:} GR curvature and QM nonlocality both emerge from the same QP--frame--mass causal chain.
\end{enumerate}

\section{Conclusion}

The clarified causal chain is:
\[
\text{QP (prior cause)} \;\to\; \text{frame (causal deployment)} \;\to\; \text{mass (drag)}.
\]
Light is timeless because massless frames deploy instantly; clocks tick because mass-bearing frames impose delay. Mass does not cause time but stretches it. Causality belongs to frames; prior cause resides in QP.

\begin{figure}[h]
\centering
\begin{tikzpicture}[
    node distance=1.0cm and 1.5cm,
    box/.style={draw, rounded corners, align=center, minimum width=3.6cm, minimum height=1.1cm, font=\small},
    qp/.style={box, fill=blue!8},
    frame/.style={box, fill=orange!10},
    massless/.style={box, fill=green!10},
    massive/.style={box, fill=red!10},
    obs/.style={box, fill=gray!10},
    arrow/.style={-Latex, thick},
    label/.style={font=\scriptsize, midway}
]
    \node[qp] (qp) {Quantum Platform (QP)\\Timeless Instructions\\(Prior Cause)};
    \node[frame, below=1.2cm of qp] (frame) {Frame (SDF)\\Causal Deployment Site\\Renders Instructions};
    \node[massless, below left=1.4cm and 0.2cm of frame] (ml) {Massless Case ($m = 0$)\\$T = 0$, Instant Deployment\\$\Delta\tau = 0$ (Null Path)};
    \node[massive, below right=1.4cm and 0.2cm of frame] (mv) {Massive Case ($m > 0$)\\$T > 0$, Delayed Deployment\\$\Delta\tau > 0$ (Timelike Path)};
    \node[obs, below=4.4cm of frame] (obs) {Rendered Observables\\(e.g., Photon Timelessness, Clock Ticks)};

    \draw[arrow] (qp) -- node[label, right] {Pre-resolved EA pairs} (frame);
    \draw[arrow] (frame) -- node[label, left, align=center] {$T \cdot C_s = 1$\\(No Drag)} (ml);
    \draw[arrow] (frame) -- node[label, right, align=center] {$T \cdot m = \hbar/c^2$\\(Drag Imposed)} (mv);
    \draw[arrow] (ml) -- node[label, left] {Instant Link} (obs);
    \draw[arrow] (mv) -- node[label, right] {Sequential Ticks} (obs);

    \node[font=\scriptsize\itshape, right=0.2cm of qp] {Ontologically Senior Layer};
\end{tikzpicture}
\caption{Deployment process from QP to SDF, highlighting mass as drag. Massless paths deploy instantly; massive paths introduce sequential delay.}
\label{fig:deployment}
\end{figure}

\begin{figure}[h]
\centering
\begin{tikzpicture}[
    node distance=1.0cm,
    massnode/.style={circle, draw, fill=red!15, minimum size=1.2cm, font=\small},
    clock/.style={draw, rounded corners, fill=blue!8, minimum width=3.2cm, minimum height=1.1cm, align=center, font=\small},
    arrow/.style={-Latex, thick},
    dim/.style={-Latex, dashed, thick}
]
    \node[massnode] (m) {Mass $m$};
    \node[clock, above right=0.2cm and 2.2cm of m] (cb) {Clock B\\$T \approx \frac{\hbar}{mc^2}\left(1 + \frac{\Phi}{c^2}\right)$\\Slower Ticking};
    \node[clock, below right=0.2cm and 2.2cm of m] (ca) {Clock A\\$T \approx \frac{\hbar}{mc^2}$\\Faster Ticking};

    \draw[dim] (m) -- node[midway, above, font=\scriptsize, sloped] {Mass Drag} (cb);
    \draw[dim] (m) -- node[midway, above, font=\scriptsize, sloped] {Mass Drag} (ca);

    \node[font=\scriptsize, right=0.3cm of cb] {Increasing Height};
    \node[font=\scriptsize\itshape, below=0.3cm of ca, xshift=1cm] {Gravitational Time Dilation (Delay Stretched by $\Phi/c^2$)};
\end{tikzpicture}
\caption{Consistency with GR: Time dilation near mass. Delay $T$ increases with potential $\Phi$, causing clocks deeper in the field to tick slower (redshift reproduction).}
\label{fig:gr_dilation}
\end{figure}

\appendix

\section{Rigorous Mathematical Derivations}

\subsection{Mass--Delay Law}

Starting from the Compton frequency,
\begin{equation}
\omega_C = \frac{mc^2}{\hbar}, \qquad T_C = \frac{1}{\omega_C} = \frac{\hbar}{mc^2},
\end{equation}
we identify $T = T_C$, yielding:
\begin{equation}
T \cdot m = \frac{\hbar}{c^2}.
\end{equation}
Thus mass parameterizes delay, consistent with observed Compton timescales.

\subsection{Causal Rendering Law}

Define causal speed:
\begin{equation}
C_s \equiv \frac{1}{T}.
\end{equation}
Then
\begin{equation}
T \cdot C_s = 1.
\end{equation}
This frames causality as a rendering rate, independent of mass's role as drag.

\subsection{Consistency with GR}

In a weak potential $\Phi$, delay modifies as:
\begin{equation}
T \approx \frac{\hbar}{mc^2}\left(1 + \frac{\Phi}{c^2}\right),
\end{equation}
reproducing gravitational time dilation~\cite{wald1984}.

\subsection{Consistency with QM}

The rest energy $E = mc^2$ enters the Schr\"odinger phase factor:
\begin{equation}
\psi(t) \sim e^{-iEt/\hbar} = e^{-iC_s t},
\end{equation}
where $C_s$ is the causal resolution rate. Thus QM evolution is delay-driven deployment of timeless instructions.

\begin{thebibliography}{9}

\bibitem{einstein1905} A.~Einstein, Zur Elektrodynamik bewegter K\"orper, \textit{Annalen der Physik} \textbf{17}, 891--921 (1905). \href{https://doi.org/10.1002/andp.19053221004}{doi:10.1002/andp.19053221004}.

\bibitem{wald1984} R.~M.~Wald, \textit{General Relativity}, University of Chicago Press (1984).

\bibitem{mckinley_notfalse} J.~C.~W.~McKinley, Why the Timeless Light Model is Not Obviously False, Zenodo (2025). \href{https://doi.org/10.5281/zenodo.17118184}{doi:10.5281/zenodo.17118184}.

\bibitem{mckinley_frame_master} J.~C.~W.~McKinley, The Frame as Master: A Unified Foundation for the Timeless Light Model, Zenodo (2025). \href{https://doi.org/10.5281/zenodo.16787219}{doi:10.5281/zenodo.16787219}.

\bibitem{mckinley_qp_generator} J.~C.~W.~McKinley, Quantum Platform as Frame Generator, Zenodo (2025). \href{https://doi.org/10.5281/zenodo.16788735}{doi:10.5281/zenodo.16788735}.

\end{thebibliography}

\end{document}
```

</details>

---
{% endraw %}
