---
layout: default
title: '[2025] Time Travel is Real: Forwards But Not Backwards'
description: 'Publication metadata and archived raw LaTeX source by John C. W. McKinley.'
permalink: /papers/time-travel-is-real-forwards-but-not-backwards/
paper: true
---
{% raw %}
# [2025] Time Travel is Real: Forwards But Not Backwards
*   **DOI:** [10.5281/zenodo.17140029](https://doi.org/10.5281/zenodo.17140029)
*   **Date:** 16 September 2025

<details markdown="1">
<summary><b>Click to view Raw LaTeX Source</b></summary>

```latex
\documentclass[12pt]{article}

% ================== Packages ==================
\usepackage{amsmath,amssymb}
\usepackage{hyperref}
\hypersetup{
  colorlinks=true,
  linkcolor=blue,
  urlcolor=blue,
  citecolor=blue
}
\usepackage{tikz}
\usepackage{pgfplots}
\pgfplotsset{compat=1.18}
\usetikzlibrary{arrows.meta,calc,decorations.markings}

% ================== Title ==================
\title{Time Travel is Real: Forwards But Not Backwards}
\usepackage{orcidlink}
\author{John C. W. McKinley\orcidlink{0009-0005-7097-5035}\\Independent Researcher}
\date{September 16, 2025}

\begin{document}
\maketitle

\begingroup
  \footnotetext[0]{This version published at
  \href{https://doi.org/10.5281/zenodo.17140029}{https://doi.org/10.5281/zenodo.17140029}.}
\endgroup


% ================== Abstract ==================
\begin{abstract}
This paper argues that time travel is not science fiction but an experimentally verified feature of relativistic physics. Every object already experiences different rates of time passage depending on mass and motion, and therefore ``travels'' through time at unique speeds. The forward direction of time travel is well established in special and general relativity, while backward travel remains forbidden by causal consistency. We present the case for forward-only travel, outline a thought experiment for seeing Earth in the year 2300, and speculate whether unlimited forward travel could be powered by atomic energy.
\end{abstract}

% ================== Sections ==================
\section{Introduction}
The word ``time travel'' conjures images of DeLorean cars, police boxes, and paradoxes about grandparents. Yet physics already guarantees a form of time travel: forward motion through spacetime at different rates depending on velocity and gravitational potential. This kind of travel cannot return you to the past, but it can carry you to the future more quickly than those who remain behind.

\section{Forward Time Travel as Physics, Not Fiction}
Einstein's special relativity showed that the proper time experienced by a traveler depends on the path length of the worldline through spacetime:
\begin{itemize}
  \item \textbf{Speed slows time:} at relativistic velocities, travelers age less than stationary observers.
  \item \textbf{Mass slows time:} deep gravitational wells cause clocks to tick slower relative to faraway clocks.
\end{itemize}
The Hafele--Keating experiment with atomic clocks on airplanes supported this, and GPS satellites continually correct for it. Forward time travel is not optional. It is built into the geometry.

\section{Seeing Earth in 2300}
Suppose a spaceship accelerates to near light speed relative to Earth. After a few years aboard, the crew could return to find that three centuries elapsed on Earth. In this sense, they ``visit'' the year 2300. If they do not like what they see, there is no rewind. The arrow of time enforces causality. Only forward progress is allowed.

\section{TikZ Diagram: Paths and Proper Time}
Figure~\ref{fig:worldlines} is a simple Minkowski-style cartoon. The vertical axis is \(ct\) and the horizontal axis is \(x\) in the Earth frame. The straight vertical worldline is Earth at rest. The tilted, piecewise line is a near light speed trip out and back. Proper time ticks along each worldline emphasize that the traveler accrues less proper time than Earth. You can call this forward time travel by path choice.

\begin{figure}[h]
\centering
\begin{tikzpicture}[scale=1.0]
  % Axes
  \draw[->,thick] (-0.2,0) -- (7.2,0) node[below] {$x$};
  \draw[->,thick] (0,-0.2) -- (0,7.2) node[left] {$ct$};

  % Light cones (guides)
  \draw[dashed] (0,0) -- (7,7);
  \draw[dashed] (0,0) -- (-7,7);

  % Earth worldline at x=1.0
  \draw[very thick,blue] (1,0) -- (1,7) node[pos=0.97,right] {Earth};

  % Proper time ticks on Earth
  \foreach \y in {0.8,1.6,2.4,3.2,4.0,4.8,5.6,6.4}{
    \draw[blue] (0.9,\y) -- (1.1,\y);
  }

  % Traveler worldline: out at v ~ 0.9c then back
  \coordinate (A) at (1,0);
  \coordinate (B) at ($(A)+(4,3)$);  % outbound leg
  \coordinate (C) at ($(B)+(-2,3)$); % inbound leg
  \draw[very thick,red] (A) -- (B) -- (C) node[pos=0.98,above right] {Traveler};

  % Proper time ticks along traveler worldline
  \foreach \t in {0.2,0.4,0.6,0.8}{
    % Outbound
    \path let \p1 = ($(A)!{\t}!(B)$) in coordinate (T) at (\x1,\y1);
    \draw[red] ($(T)+(-0.07,0.093)$) -- ($(T)+(0.07,-0.093)$);
  }
  \foreach \t in {0.2,0.4,0.6,0.8}{
    % Inbound
    \path let \p1 = ($(B)!{\t}!(C)$) in coordinate (U) at (\x1,\y1);
    \draw[red] ($(U)+(0.07,0.093)$) -- ($(U)+(-0.07,-0.093)$);
  }

  % Labels
  \node[blue] at (1.8,6.2) {more proper time on Earth};
  \node[red]  at (4.2,3.6) {less proper time on traveler};
\end{tikzpicture}
\caption{Two worldlines in the Earth frame. Blue: Earth at rest accumulates more proper time. Red: high speed out-and-back accumulates less proper time. Forward-only time travel is path choice in spacetime.}
\label{fig:worldlines}
\end{figure}

\section{Could Atomic Power Enable Unlimited Travel}
A craft powered by atomic reactors could, in principle, sustain long acceleration at relativistic speed. By chaining trips, one could ``leap'' 300 years, then 600, then 900, simply by repeating the cycle. No exotic physics is required. The limit is engineering: endurance, shielding, thermal management, and energy storage.

\section{Why Backward Travel is Forbidden}
Relativity preserves causal order. Backward travel would create paradoxes: an observer could arrive before departure, which breaks energy and information consistency. Quantum mechanics tolerates uncertainty, not contradictions in cause and effect. The future is open. The past is locked.

\section{The Postulated Timeless Light Model (TLM)}
The Timeless Light Model reframes relativity as a subordinate projection. General Relativity and Special Relativity live inside the Spacetime Deployment Frame (SDF). The deeper reality is the Quantum Platform (QP): a timeless, spaceless instruction layer that issues events later rendered in spacetime. In this view, clocks, paths, and dilations are surface effects of a causal instruction substrate. TLM says photons are instructions, not travelers. GR and SR are emergent delay tools for experience inside the SDF, while causality lives in the QP. For full derivations and predictions, see McKinley (2025) on Zenodo.

\section{Conclusion}
Time travel is real. By choosing different paths through spacetime, you choose different amounts of proper time. With enough thrust and patience, you can visit Earth's far future. There is no button for backward travel. That is the price of causal consistency.

% ================== Appendix ==================
\appendix
\section{Mathematical Derivation in SR: Worldline Proper Time}
The invariant proper time \(d\tau\) along a worldline in flat Minkowski spacetime is
\begin{equation}
d\tau^2 = dt^2 - \frac{1}{c^2}(dx^2+dy^2+dz^2),
\end{equation}
with metric signature \((+,-,-,-)\) and \(c\) the speed of light. For motion in one dimension,
\begin{equation}
d\tau = dt \sqrt{1 - \frac{v^2}{c^2}}.
\end{equation}
Integrating over the history,
\begin{equation}
\tau = \int_{t_0}^{t_1} dt \, \sqrt{1 - \frac{v^2(t)}{c^2}}.
\end{equation}
A worldline with \(v=0\) maximizes \(\tau\) between the same coordinate times, while any \(v>0\) yields less accumulated proper time:
\begin{equation}
\tau_{\text{traveler}} < \tau_{\text{Earth}}.
\end{equation}
This is the precise sense in which choosing a different path through spacetime is forward-only time travel.

\section{Mathematical Derivation in GR: Gravitational Time Dilation}
For a static, spherically symmetric mass \(M\), the Schwarzschild line element is
\begin{equation}
ds^2 = -\left(1-\frac{2GM}{rc^2}\right)c^2 dt^2
       + \left(1-\frac{2GM}{rc^2}\right)^{-1} dr^2
       + r^2(d\theta^2 + \sin^2\theta\, d\phi^2).
\end{equation}
A stationary observer at fixed \(r,\theta,\phi\) has \(dr=d\theta=d\phi=0\), so
\begin{equation}
d\tau = dt \sqrt{1 - \frac{2GM}{rc^2}}.
\end{equation}
Two stationary clocks at radii \(r_1\) and \(r_2\) therefore tick at rates
\begin{equation}
\frac{d\tau_1}{dt} = \sqrt{1 - \frac{2GM}{r_1 c^2}},
\qquad
\frac{d\tau_2}{dt} = \sqrt{1 - \frac{2GM}{r_2 c^2}},
\end{equation}
and the ratio gives the gravitational redshift
\begin{equation}
\frac{d\tau_2}{d\tau_1} = 
\sqrt{\frac{1 - 2GM/(r_2 c^2)}{1 - 2GM/(r_1 c^2)}}.
\end{equation}

\subsection{Weak-field limit and height difference}
Near Earth, with Newtonian potential \(\Phi(r) \approx -GM/r\) and \(|\Phi| \ll c^2\), the metric time component satisfies
\begin{equation}
g_{00} \approx -\left(1 + \frac{2\Phi}{c^2}\right).
\end{equation}
Hence
\begin{equation}
d\tau \approx dt \left(1 + \frac{\Phi}{c^2}\right).
\end{equation}
For a small height difference \(h\) in a uniform field \(g\) (\(\Phi_2 - \Phi_1 \approx gh\)),
\begin{equation}
\frac{\Delta f}{f} \approx \frac{f_2 - f_1}{f_1} \approx \frac{gh}{c^2},
\end{equation}
the classic gravitational redshift measured by Pound and Rebka in 1960 and later confirmed with high precision by Gravity Probe A.

\subsection{Combining velocity and gravity}
For a slowly moving clock at radius \(r\) with speed \(v \ll c\),
\begin{equation}
\frac{d\tau}{dt} \approx \sqrt{1 - \frac{2GM}{rc^2}} \, \sqrt{1 - \frac{v^2}{c^2}}
\;\;\approx\;\; 1 + \frac{\Phi}{c^2} - \frac{v^2}{2c^2},
\end{equation}
which is the standard approximation used to correct GPS satellite clocks (higher altitude makes them run faster via gravity, orbital speed makes them run slower via SR).

% ================== References ==================
\section*{References}
\begin{itemize}
  \item Einstein, A. (1905). Zur Elektrodynamik bewegter K{\"o}rper. \textit{Annalen der Physik}. \href{https://doi.org/10.1002/andp.19053221004}{doi:10.1002/andp.19053221004}
  \item Hafele, J. C., \& Keating, R. E. (1972). Around-the-World Atomic Clocks: Predicted Relativistic Time Gains. \textit{Science}, 177(4044), 166--168. \href{https://doi.org/10.1126/science.177.4044.166}{doi:10.1126/science.177.4044.166}
  \item Misner, C. W., Thorne, K. S., \& Wheeler, J. A. (1973). \textit{Gravitation}. W. H. Freeman. \href{https://doi.org/10.1201/9780429492563}{doi:10.1201/9780429492563}
  \item Greene, B. (2004). \textit{The Fabric of the Cosmos}. Knopf. \href{https://doi.org/10.2307/j.ctt7sgd0}{doi:10.2307/j.ctt7sgd0}
  \item Pound, R. V., \& Rebka Jr., G. A. (1960). Apparent weight of photons. \textit{Physical Review Letters}, 4, 337--341. \href{https://doi.org/10.1103/PhysRevLett.4.337}{doi:10.1103/PhysRevLett.4.337}
  \item Vessot, R. F. C., \& Levine, M. W. (1979). A test of the equivalence principle using a space-borne clock. \textit{General Relativity and Gravitation}, 10, 181--204. \href{https://doi.org/10.1007/BF00759854}{doi:10.1007/BF00759854}
  \item Vessot, R. F. C., et al. (1980). Test of Relativistic Gravitation with a Space-Borne Hydrogen Maser. \textit{Physical Review Letters}, 45, 2081--2084. \href{https://doi.org/10.1103/PhysRevLett.45.2081}{doi:10.1103/PhysRevLett.45.2081}
\item McKinley, J. C. W. (2025). {Why the Timeless Light Model is Not Obviously False}, Zenodo.
\href{https://doi.org/10.5281/zenodo.17118184}{doi:10.5281/zenodo.17118184}.

  
\end{itemize}

\end{document}

```

</details>

---
{% endraw %}
