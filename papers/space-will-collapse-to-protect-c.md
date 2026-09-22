---
layout: default
title: '[2025] Space Will Collapse to Protect c'
description: 'Publication metadata and archived raw LaTeX source by John C. W. McKinley.'
permalink: /papers/space-will-collapse-to-protect-c/
paper: true
---
{% raw %}
# [2025] Space Will Collapse to Protect c
*   **DOI:** [10.5281/zenodo.17164585](https://doi.org/10.5281/zenodo.17164585)
*   **Date:** 20 September 2025

<details markdown="1">
<summary><b>Click to view Raw LaTeX Source</b></summary>

```latex
\documentclass[12pt, onecolumn]{article}

% ---------- Page & Layout ----------
\usepackage[margin=1in]{geometry}
\usepackage[T1]{fontenc}
\usepackage[utf8]{inputenc}
\usepackage{lmodern}
\usepackage{microtype} % For better typography

% ---------- Math ----------
\usepackage{amsmath,amssymb,amsthm}

% ---------- Lists ----------
\usepackage{enumitem}

% ---------- Figures & Floats ----------
\usepackage{graphicx}
\usepackage{float}
\usepackage{tikz}
\usetikzlibrary{shapes.geometric, arrows.meta, positioning}

% ---------- Links & References ----------
\usepackage{hyperref}
\hypersetup{colorlinks=true,linkcolor=blue,urlcolor=blue,citecolor=blue}
\usepackage{cleveref}

% ---------- Headers & Title ----------
\usepackage{fancyhdr}
\usepackage{orcidlink}

% --- Header Setup ---
\pagestyle{fancy}
\fancyhf{}
\lhead{Causal Chain in TLM}
\rhead{\thepage}
% --- Metadata ---
\title{Space Will Collapse to Protect \(c\)}
\author{John C. W. McKinley\orcidlink{0009-0005-7097-5035}\\Independent Researcher}
\date{September 20, 2025}

\begin{document}
\maketitle

\begingroup
  \footnotetext[0]{This version published at
  \href{https://doi.org/10.5281/zenodo.17164585}{https://doi.org/10.5281/zenodo.17164585}.}
\endgroup
\begin{abstract}
If a marble could pass you at twice the speed of light, photons emitted from it would arrive later than the marble itself. The universe forbids this. To enforce causality, space collapses: the distance the marble must traverse is shortened, so its measured speed never exceeds \(c\). This collapse is not an optical trick but a geometric safeguard. Distances contract and times dilate so that the ratio \(\Delta x / \Delta t\) always yields \(v \leq c\). Photons themselves remain unaffected; they always travel at \(c\) in every frame. Space reshapes to ensure no material point ever outruns them. We develop this interpretation and relate it to Einstein’s 1905 postulates \cite{einstein1905} and optical appearances (Terrell--Penrose \cite{terrell1959,penrose1959}), then note parallels in general relativity and connect the idea later to the Timeless Light Model.
\end{abstract}

\section{Introduction: The Problem of Overtaking Light}\label{sec:intro}
Einstein’s 1905 formulation \cite{einstein1905} established the invariance of physical laws across inertial frames and the constancy of the speed of light in vacuum. From these, relativity derives time dilation, relativity of simultaneity, and Lorentz contraction.

The core issue is simple: without contraction, an ordinary particle could appear to travel a long distance in a short time, giving \(v>c\). Imagine a marble racing by at more than light speed. The marble would cross a region of space before its own photons reached the same observer. That would invert cause and effect. To prevent this, relativity reshapes geometry: the distance the marble covers is shortened and the elapsed time dilates, such that \(v \leq c\).

\section{Core Idea: Collapse of Distance}\label{sec:core}
The Lorentz transformation ensures that, in the observer’s frame, length along the motion direction contracts:
\[
L \;=\; \frac{L_0}{\gamma}, \qquad \gamma \;=\; \frac{1}{\sqrt{1-v^2/c^2}}.
\]
This collapse prevents the marble’s worldline from ever tilting outside the light cone. In effect, the transformation shrinks the numerator \(\Delta x\) in the measured speed \(v=\Delta x/\Delta t\) for the marble while photons remain anchored to the light cone. The result is that the measured velocity of the marble stays bounded at or below \(c\). Thus contraction is universal: it applies not only to extended bodies but even to single pointlike particles. The marble outrunning its photons is forbidden because the universe collapses space until that cannot occur.

\section{Optics vs. Measurement}\label{sec:optics}
Two perspectives must be distinguished:
\begin{itemize}
  \item \textbf{Measurement.} With synchronized clocks and rulers, the observer defines length as simultaneous events in their frame. This yields contraction and time dilation.
  \item \textbf{Appearance.} What eyes or cameras see is shaped by light travel time. Terrell \cite{terrell1959} and Penrose \cite{penrose1959} showed that objects in near-\(c\) motion can appear rotated rather than squashed. This is optical distortion that sits on top of geometric contraction.
\end{itemize}

\section{Spacetime Diagram}\label{sec:diagram}
Figure \ref{fig:tikz} shows a marble’s worldline approaching an observer. Dashed lines represent photons emitted from the marble. With contraction, the spatial distance in the observer’s frame shortens so the marble’s worldline stays inside the light cone. Photons remain exactly on the cone in every frame. This is the central safeguard in the argument.

\begin{figure}[h]
\centering
\begin{tikzpicture}[scale=1.0]
  % axes
  \draw[-{Latex[length=3mm]}] (-4,0) -- (4,0) node[below right] {$x$};
  \draw[-{Latex[length=3mm]}] (0,-0.4) -- (0,6) node[left] {$ct$};

  % observer worldline
  \draw[very thick,gray!60] (0,0) -- (0,6) node[pos=0.9,anchor=west] {\small observer};

  % marble worldline (sub-luminal tilt)
  \draw[thick] (-3,0) -- (0,6) node[pos=0.5,anchor=south east] {\small marble};

  % photon worldline (45 degrees)
  \draw[dashed] (-3,0) -- (3,6) node[pos=0.6,anchor=south west] {\small photon};

  % reception event
  \filldraw (0,4) circle (2pt) node[above right] {\small reception};
\end{tikzpicture}
\caption{Spacetime diagram: a marble (solid) and its photon (dashed) approach the observer. Length contraction keeps the marble’s worldline inside the light cone while photons define the cone itself. This contraction of distance prevents any material point from overtaking its own light.}
\label{fig:tikz}
\end{figure}

\section{GR Parallels}\label{sec:GR}
General relativity extends the same safeguard. Gravity collapses spacetime geometry around massive bodies. At horizons, light cones tip until no path escapes outward at \(v>c\). The principle is the same: geometry yields to prevent causal violation.

\section{Relation to the Timeless Light Model}\label{sec:TLM}
In the Timeless Light Model (TLM), our observed universe is a Spacetime Deployment Frame (SDF) that renders pre-resolved instructions from a senior Quantum Platform (QP). The organizing principle is the Principle of Delayed Resolution (PDR): the cosmos meters atemporal causal instructions into a sequential reality suitable for observation. Within this reading, time is emergent from engineered delay rather than fundamental.

TLM formalizes this with the mass–time reciprocity axiom
\[
T \cdot m \;=\; \frac{\hbar}{c^2},
\]
which treats mass as a source of deployment delay and fixes a baseline causal resolution rate for framed observers. Photons, having \(m=0\), sit on null instructions with \(T=0\), and therefore anchor the light cone.

Against this backdrop, Lorentz contraction and time dilation are not cosmetic artifacts; they are rules of deployment in the SDF that prevent any rendered worldline, whether extended or pointlike, from tilting outside the light cone. In short, space collapses in the measured direction of motion so that the marble’s velocity remains bounded by \(c\), while photons remain on the cone in every frame. This ties the paper’s central claim (collapse protects \(c\)) to a single deployment axiom and the PDR purpose statement without altering standard SR calculations.

\section{Conclusion}\label{sec:conclusion}
Relativity’s contraction is not a quirk but a safeguard. If a marble attempted to pass faster than its photons, causality would fail. The universe forbids this by collapsing distance until the marble’s velocity remains \(\leq c\). Photons always travel at \(c\); geometry bends around them. GR echoes this through gravitational collapse, and TLM reframes it as a rendering rule. Space will collapse to protect \(c\).

\appendix

\section{Derivation}\label{sec:appendix}
Length is defined as the separation of simultaneous events in a given frame. The Lorentz transformation gives
\[
L \;=\; \frac{L_0}{\gamma}.
\]
Suppose a marble emits photons. If distance did not collapse, the marble could appear to cover \(\Delta x\) faster than its photons, producing \(v>c\). Contraction ensures \(\Delta x\) shrinks in the observer’s coordinates and, together with time dilation, the measured velocity never exceeds \(c\). Photons remain on the light cone in every frame.

\begin{thebibliography}{99}

\bibitem{einstein1905}
A.~Einstein, \textit{Zur Elektrodynamik bewegter K\"orper} (On the Electrodynamics of Moving Bodies), \emph{Annalen der Physik} \textbf{17} (1905) 891--921. 
\href{https://doi.org/10.1002/andp.19053221004}{doi:10.1002/andp.19053221004}

\bibitem{terrell1959}
J.~Terrell, \textit{Invisibility of the Lorentz Contraction}, \emph{Physical Review} \textbf{116} (1959) 1041--1045. 
\href{https://doi.org/10.1103/PhysRev.116.1041}{doi:10.1103/PhysRev.116.1041}

\bibitem{penrose1959}
R.~Penrose, \textit{The Apparent Shape of a Relativistically Moving Sphere}, \emph{Proceedings of the Cambridge Philosophical Society} \textbf{55} (1959) 137--139.
\href{https://doi.org/10.1017/S0305004100035479}{doi:10.1017/S0305004100035479}

% Representative TLM works for context
\bibitem{qp_causal}
J.~C.~W. McKinley, \textit{Causal Chain in the Timeless Light Model: Mass as Drag, Frame as Causal Site, Quantum Platform as Cause}, \emph{Zenodo} (2025).
\href{https://doi.org/10.5281/zenodo.17139863}{doi:10.5281/zenodo.17139863}

\bibitem{tlm_review}
J.~C.~W. McKinley, \textit{A Review of the Timeless Light Model: Foundations, Derivations, and Empirical Predictions}, \emph{Zenodo} (2025).
\href{https://doi.org/10.5281/zenodo.16958221}{doi:10.5281/zenodo.16958221}

\bibitem{photon_out}
J.~C.~W. McKinley, \textit{Photon Out of Time: Why Light Experiences No Time and What That Means for Physics}, \emph{Zenodo} (2025).
\href{https://doi.org/10.5281/zenodo.16479322}{doi:10.5281/zenodo.16479322}

\end{thebibliography}

\end{document}

```

</details>

---
{% endraw %}
