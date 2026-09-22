---
layout: default
title: '[2025] Whose Frame is it Anyway? — On Photon Timelessness, Proper Time, and the Observer''s Illusion'
description: 'Publication metadata and archived raw LaTeX source by John C. W. McKinley.'
permalink: /papers/whose-frame-is-it-anyway-on-photon-timelessness-proper-time-and-the-observer-s-illusion/
paper: true
---
{% raw %}
# [2025] Whose Frame is it Anyway? — On Photon Timelessness, Proper Time, and the Observer's Illusion
*   **DOI:** [10.5281/zenodo.17239624](https://doi.org/10.5281/zenodo.17239624)
*   **Date:** 30 September 2025

<details markdown="1">
<summary><b>Click to view Raw LaTeX Source</b></summary>

```latex
\documentclass[12pt,onecolumn]{article}

% ---------- Page & Layout ----------
\usepackage[margin=1in]{geometry}
\usepackage[T1]{fontenc}
\usepackage[utf8]{inputenc}
\usepackage{lmodern}
\usepackage{microtype}
\usepackage{setspace}
\onehalfspacing

% ---------- Math ----------
\usepackage{amsmath,amssymb,amsthm}
\usepackage{mathtools}

% ---------- Figures & Floats ----------
\usepackage{tikz}
\usetikzlibrary{arrows.meta,positioning,calc}
\usepackage{graphicx}
\usepackage{float}
\usepackage{booktabs}

% ---------- Links & References ----------
\usepackage{hyperref}
\usepackage{cleveref}
\hypersetup{
  colorlinks=true,
  linkcolor=blue,
  urlcolor=blue,
  citecolor=blue
}

% ---------- Headers ----------
\usepackage{fancyhdr}
\pagestyle{fancy}
\fancyhf{}
\lhead{Whose Frame is it Anyway?}
\rhead{\thepage}

% ---------- ORCID ----------
\usepackage{orcidlink}

% ---------- Title ----------
\title{\textbf{Whose Frame is it Anyway?}\\
On Photon Timelessness, Proper Time, and the Observer’s Illusion}

\author{John C. W. McKinley\orcidlink{0009-0005-7097-5035}\\Independent Researcher\thanks{Preprint DOI: \href{https://doi.org/10.5281/zenodo.17239624}{10.5281/zenodo.17239624}}}
\date{September 30, 2025}

% ---------- Lawbox ----------
\usepackage[most]{tcolorbox}
\tcbset{colback=blue!5!white,colframe=blue!75!black,fonttitle=\bfseries}
\newtcolorbox{lawbox}[2][]{colback=blue!5!white,colframe=blue!65!black,fonttitle=\bfseries,title=#2,#1}

\begin{document}
\maketitle

\begin{abstract}
In this paper we confront a deceptively simple question: \emph{whose frame counts when discussing light?} Special Relativity states that photons traverse null geodesics where proper time vanishes. Yet we commonly assign to them a velocity $c$ and imagine a journey. We show that this duality---speed in our frame, no frame of their own---demands a careful separation between measurement and ontology. The Timeless Light Model (TLM) formalizes this distinction by placing photons outside the Spacetime Deployment Frame (SDF), while preserving the finite causal speed $c$ for all observer-rendered events. The paper provides thought experiments, dialogue, a TLM summary, derivations, and a glossary to clarify why photons and quanta must be reclassified as timeless instructions rather than persisting travelers.
\end{abstract}

% =====================================================
\section{Introduction}
In physics classrooms and pop-science videos alike, photons are described as ``moving through space'' at the cosmic speed limit $c$. But the mathematics of relativity undermines this imagery. Along a null geodesic,
\[
ds^2 = -c^2 d\tau^2 = 0,
\]
which enforces $d\tau = 0$ for any photon path. That means no proper time, no rest frame, and arguably no journey. This motivates our title: \emph{Whose frame is it anyway?} 

To address the measurement/ontology split, we adopt a two-layer framework developed in the Timeless Light Model (TLM): a timeless \emph{Quantum Platform (QP)} that authors complete emission--absorption instructions, and a rendered \emph{Spacetime Deployment Frame (SDF)} where those instructions appear in sequence under relativistic constraints. We summarize this model in \cref{sec:TLMsummary}.

\section{Standard Relativity: No Photon Frame}
Special Relativity distinguishes between timelike and null worldlines. For timelike curves, massive objects can define a rest frame, clock time, and causally ordered events. For null curves, such as those of photons, none of these quantities exist. Photons lack a rest frame and cannot be said to experience motion.

\begin{lawbox}{No-Frame Lemma}
No Lorentz transformation can yield a valid rest frame for a massless particle. Attempting to do so leads to singularities in the transformation equations.
\end{lawbox}

As shown in \cref{fig:minkowski}, timelike worldlines (massive objects) accrue proper time, while null worldlines (photons) have $d\tau=0$.

\begin{figure}[H]
\centering
\begin{tikzpicture}[scale=1.0]
  % Axes
  \draw[->] (0,0) -- (0,5) node[above] {Time $t$};
  \draw[->] (0,0) -- (5,0) node[right] {Space $x$};

  % Timelike worldline
  \draw[thick,blue] (0,0) -- (1,4) node[midway,left] {Massive};

  % Null worldline
  \draw[thick,red] (0,0) -- (4,4) node[midway,above] {Photon};

  % Labels
  \node at (2.5,-0.5) {Minkowski diagram: timelike vs. null};
\end{tikzpicture}
\caption{Massive vs.\ massless worldlines. The photon’s path has $d\tau=0$.}
\label{fig:minkowski}
\end{figure}

\section{The Timeless Light Model Perspective}
\label{sec:TLMsummary}
The Timeless Light Model (TLM) introduces a two-layer ontology:
\begin{itemize}
  \item \textbf{Quantum Platform (QP):} Timeless issuance layer of completed emission--absorption instructions (CI-ARCs).
  \item \textbf{Spacetime Deployment Frame (SDF):} Rendered observer layer where instructions appear with deployment constraints summarized by the \emph{Bridge Laws} (see \cref{sec:bridge}): delay governed by $T \cdot m = \hbar / c^2$ and a causal deployment rate satisfying $T \cdot C_s = 1$, alongside quantum-structural constraints.
\end{itemize}
In TLM, photons are not travelers at all. They are pre-resolved instruction arcs authored on the QP and rendered instantaneously ($T=0$). Their apparent speed $c$ is a property of the SDF deployment filter, not of photon motion.

\subsection{Bridge Laws (Deployment Filters)}
\label{sec:bridge}

\begin{lawbox}{Bridge Law I: Mass--Delay Duality}
\label{law:delay}
\[
T \cdot m = \frac{\hbar}{c^2}.
\]
Mass $m>0$ implies a positive rendering delay $T>0$ in the SDF; conversely, for massless quanta ($m=0$) the delay vanishes ($T=0$). This relation encodes the observed coupling of mass to time (time dilation) as a deployment rule.
\end{lawbox}

\begin{lawbox}{Bridge Law II: Causal Speed}
\label{law:cs}
\[
T \cdot C_s = 1.
\]
Here $C_s$ is the rate at which QP-authored instructions are rendered into the SDF. When $T=0$ (massless case) the intrinsic deployment on the QP side is instantaneous, yet in the SDF this appears as the finite invariant $c$, preserving causal order for observers.
\end{lawbox}

\section{Q\&A: What About the Speed of Light?}
During online discussion of the video \emph{Light Does Not Travel}\footnote{YouTube Short posted at \url{https://youtube.com/shorts/gI0BHqN-SI8}.}, a pointed question was raised:

\medskip
\noindent\textbf{@ZackNehring:} \emph{``If light doesn't travel, then why does it have a speed limit?''}\footnote{Comment by @ZackNehring on the YouTube video \emph{Light Does Not Travel}, September 2025.}

\medskip
To which I replied:

\noindent\textbf{@DiagonalStudios:} \emph{``There is an information transfer speed in our frame\ldots\ but not its frame.''}

\medskip
This exchange encapsulates the TLM stance. The constant $c$ is a rule for observers in the SDF, ensuring causal order. But photons, having no frame, do not ``experience'' this limit. They are timeless links authored on the QP, their $d\tau=0$ status guaranteeing no internal passage of time. The speed of light is thus a property of deployment, not of photons.

\section{Summary of the Timeless Light Model}
TLM asserts that reality operates through a two-level structure:
\begin{enumerate}
  \item \textbf{Quantum Platform (QP):} A timeless domain where Causal Instruction Arcs (CI-ARCs) are fully authored, linking emission and absorption in one indivisible record.
  \item \textbf{Spacetime Deployment Frame (SDF):} The observer’s experiential layer, where these instructions are deployed sequentially under the \emph{Bridge Laws} of \cref{law:delay,law:cs} and the structural rules of quantum mechanics.
\end{enumerate}
Photons ($m=0$) thus deploy with $T=0$ on the QP side, yet appear in SDF as constrained by $c$. Mass imposes delay; delay produces time. Spacetime itself is the rendered playback of timeless instructions.

\section{Rigorous Derivations}
\subsection{Null Geodesics and Proper Time}
The line element in flat Minkowski spacetime is
\[
ds^2 = -c^2 d\tau^2 = -c^2 dt^2 + dx^2 + dy^2 + dz^2.
\]
For photons ($ds^2=0$),
\[
d\tau = 0 \quad \Rightarrow \quad \text{no elapsed proper time}.
\]

\subsection{No Lorentz Frame for Massless Particles}
A Lorentz transformation to the particle’s rest frame requires velocity addition:
\[
v' = \frac{v-u}{1 - vu/c^2}.
\]
For $v=c$, no finite $u$ yields $v'=0$; the denominator vanishes. Thus no rest frame exists for a photon.

\subsection{Mass--Delay Duality}
Using \cref{law:delay}, temporal delay $T$ and mass $m$ satisfy
\[
T \cdot m = \frac{\hbar}{c^2}.
\]
This ensures that massless quanta ($m=0$) render with no delay ($T=0$), while massive bodies accumulate proper time. It recovers the operational content of relativistic time dilation as a deployment rule.

\subsection{Causal Speed}
From \cref{law:cs}, the instruction deployment rate $C_s$ obeys
\[
T \cdot C_s = 1.
\]
For photons: $T=0 \Rightarrow C_s \to \infty$ on the QP, while in the SDF the observable information-transfer rate is limited by $c$, preserving causal order.

\section{Thought Experiments}
\subsection{The Stopwatch and the Flashlight}
A stopwatch times the interval between emission and detection of a photon. The device measures delay in the SDF, not duration in the photon's nonexistent frame.

\subsection{The Marble vs.\ Its Light}
If a marble could outpace its emitted photon, causality would collapse. In TLM, this cannot occur: $c$ is the maximum deployment rate enforced by the \emph{Bridge Laws} \cref{law:delay,law:cs}.

\section{Conclusion}
The answer to our title’s question is: \emph{not the photon’s frame—because it has none}. Photons inherit their apparent motion only from the rendering laws of the SDF. In the TLM framework, this reframing resolves paradoxes of causality, speed, and quantum ontology.

% =====================================================
\section*{Glossary}
\begin{description}
  \item[Quantum Platform (QP):] Timeless instruction layer, outside spacetime.
  \item[Spacetime Deployment Frame (SDF):] Observable relativistic arena where QP instructions manifest.
  \item[Causal Instruction Arc (CI-ARC):] Pre-resolved link between emission and absorption.
  \item[Bridge Laws:] Named pair of deployment constraints, \emph{Mass--Delay Duality} and \emph{Causal Speed}, given in \cref{law:delay,law:cs}.
  \item[Delay Law:] $T \cdot m = \hbar / c^2$ (Bridge Law I), mass induces delay.
  \item[Causal Speed Law:] $T \cdot C_s = 1$ (Bridge Law II), defines deployment rate.
  \item[No-Frame Lemma:] Massless quanta have no rest frame.
\end{description}

% =====================================================
\section*{Acknowledgments}
I thank the YouTube, TikTok, and Zenodo communities for ongoing challenges, comments, and critiques that sharpened this argument.

% =====================================================
\begin{thebibliography}{9}

\bibitem{einstein1905}
A.~Einstein, ``Zur Elektrodynamik bewegter Körper,'' \emph{Annalen der Physik}, vol.~17, pp.~891--921, 1905. \href{https://doi.org/10.1002/andp.19053221004}{doi:10.1002/andp.19053221004}.

\bibitem{mckinley2025_photon}
J.~C.~W. McKinley, ``Photon Proper Time: The Understated Invariant of Special Relativity,'' Zenodo (2025). \href{https://doi.org/10.5281/zenodo.17190047}{doi:10.5281/zenodo.17190047}.

\bibitem{mckinley2025_massless}
J.~C.~W. McKinley, ``Massless Things Do Not Experience Time,'' Zenodo (2025). \href{https://doi.org/10.5281/zenodo.17173126}{doi:10.5281/zenodo.17173126}.

\bibitem{mckinley2025_review}
J.~C.~W. McKinley, ``A Review of the Timeless Light Model: Foundations, Derivations, and Empirical Predictions,'' Zenodo (2025). \href{https://doi.org/10.5281/zenodo.16958221}{doi:10.5281/zenodo.16958221}.
\end{thebibliography}

\end{document}

```

</details>

---
{% endraw %}
