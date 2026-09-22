---
layout: default
title: '[2025] Unlimited Rocket Acceleration and Time Travel to the Future'
description: 'Publication metadata and archived raw LaTeX source by John C. W. McKinley.'
permalink: /papers/unlimited-rocket-acceleration-and-time-travel-to-the-future/
paper: true
---
{% raw %}
# [2025] Unlimited Rocket Acceleration and Time Travel to the Future
*   **DOI:** [10.5281/zenodo.17139392](https://doi.org/10.5281/zenodo.17139392)
*   **Date:** 16 September 2025

<details markdown="1">
<summary><b>Click to view Raw LaTeX Source</b></summary>

```latex
\documentclass[12pt]{article}
\usepackage{amsmath,amssymb}
\usepackage[hidelinks]{hyperref}
\usepackage{geometry}
\usepackage{booktabs}
\usepackage{tikz}
\usetikzlibrary{arrows.meta}
\geometry{margin=1in}
% HYPERLINK SETUP
\usepackage{hyperref}
\hypersetup{colorlinks=true,linkcolor=blue,urlcolor=blue,citecolor=blue}
\usepackage{cleveref}

\title{Unlimited Rocket Acceleration and Time Travel to the Future}
\usepackage{orcidlink}
\author{John C. W. McKinley\orcidlink{0009-0005-7097-5035}\\Independent Researcher}
\date{Septepber 16, 2025}

\begin{document}
\maketitle


\begingroup
  \footnotetext[0]{This version published at
  \href{https://10.5281/zenodo.17139392}{https://doi.org/10.5281/zenodo.17139392}.}
\endgroup




\begin{abstract}
A rocket under \emph{constant proper acceleration} experiences an unending seat push in its own frame, even as distant observers never see superluminal motion: coordinate speeds only approach \( c \). The apparent tension is resolved by the growth of the Lorentz factor \( \gamma \), which diverges while changes in \( v/c \) remain small. We present a narrative worked example (e.g., from \( v = 0.9995c \) to \( v = 0.9999c \)) where time dilation, momentum, and energy soar though velocity increments look tiny, then summarize the standard physics and give rigorous derivations in the Appendix. We close with a brief connection to the Timeless Light Model (TLM), where this rocket scenario exemplifies how the frame follows GR/SR rules in deployment.
\end{abstract}

\section{Introduction}
An astronaut under thrust feels a steady push: the accelerometer reads a nonzero value. That felt push is \emph{proper acceleration}, an invariant measured in the traveler’s own frame. Meanwhile, external observers never record the rocket exceeding \( c \). Near \( c \), additional thrust raises \( \gamma \) much more than it raises the decimal digits of \( v/c \). Thus, time dilation and relativistic momentum and energy balloon even though the quoted speed barely changes \cite{einstein1905,rindler1991,MTW1973}. The result is operational one-way travel into the future: outside time piles up while the astronaut’s proper time thins.

\section{The Worked Example: What Happens}
Let us tell the story slowly, as if riding in the rocket. Imagine a spacecraft already coasting at \( v = 0.9995c \) relative to a scattered belt of asteroids. The pilot, strapped in, floats momentarily free of the engines, looking out at streaks of light sliding past the window. In the pilot’s cabin, everything seems calm. Drinks rest on the console, clocks tick normally, the pilot’s body registers no stress. That is because coasting requires no force and produces no sensation of acceleration.

But then the pilot ignites the thrusters again. Immediately, the seat presses against the back, a familiar heavy push. The pilot cannot mistake this: the rocket is accelerating. An accelerometer on the cabin wall agrees, measuring a steady value. The pilot is being driven forward with real force. The feeling is visceral, absolute, inescapable.

Now pause and compare with the asteroids. From their perspective, the rocket had been racing at \( 0.9995c \). After ignition, they measure again. The velocity climbs: \( 0.99951c \), then \( 0.9997c \), then \( 0.9999c \). These increments are real, but look pitifully small in raw decimals. An asteroid geologist might laugh: ``You are burning all that fuel for an extra few 9s?'' From the asteroid side, the difference seems negligible.

Yet this is where relativity’s hidden lever emerges. At \( 0.9995c \), the rocket’s Lorentz factor is \( \gamma \approx 31.6 \). That means one second on the pilot’s wristwatch matches 31.6 seconds on the asteroid’s clock. When the pilot fires the thrusters to climb to \( 0.9999c \), \( \gamma \) leaps to about 70.7. Now one second inside equals about 70 seconds outside. The decimals in speed hid a dramatic shift in lived time.

\begin{table}[h]
\centering
\caption{Asteroid time vs.\ rocket time at different near-light speeds (rounded).}
\begin{tabular}{@{}llll@{}}
\toprule
Velocity \( v/c \) & \( \gamma \) & Asteroid time (1 h) & Rocket time experienced \\ \midrule
0.9995   & 31.6   & 3600 s & 114 s (1.9 min) \\
0.9999   & 70.7   & 3600 s & 50.9 s (0.85 min) \\
0.99999  & 223.6  & 3600 s & 16.1 s \\
0.999999 & 707.1  & 3600 s & 5.1 s \\ \bottomrule
\end{tabular}
\end{table}

\begin{figure}[h]
\centering
\begin{tikzpicture}[scale=1.0,>=Latex]
  % axes
  \draw[->] (-3.2,0) -- (3.2,0) node[below right] {\(x\)};
  \draw[->] (0,-0.2) -- (0,4.2) node[left] {\(ct\)};

  % light cone through origin
  \draw[dashed] (-3,3) -- (0,0);
  \draw[dashed] (0,0) -- (3,3);

  % coasting worldline (sketch)
  \draw[thick] (0,0) -- (0.095,4) node[pos=0.55, right=2pt] {\small coast at \(0.9995c\)};

  % thrusting worldline bending toward light cone
  \draw[thick,blue] (0,0)
    .. controls (0.25,1.2) and (0.48,2.2) ..
    (0.75,3.0)
    .. controls (0.95,3.4) and (1.15,3.7) ..
    (1.35,4.0);
  \node[blue,above right] at (1.35,4.0) {\small thrust on, \(\gamma \uparrow\)};
\end{tikzpicture}
\caption{Minkowski diagram (schematic). Dashed lines are the light cone. A near-light coasting worldline (black) contrasts with a thrusting worldline (blue) that bends closer to the cone as \(\gamma\) rises. Coordinate speed approaches \( c \) but never crosses, while proper acceleration remains felt on board.}
\label{fig:minkowski}
\end{figure}

To make the effect plain, suppose one asteroid hour ticks by—3600 seconds. At \( 0.9995c \), the astronaut’s watch advances about 114 seconds, less than two minutes. At \( 0.9999c \), the watch advances only 51 seconds, under a single minute. Push further to \( 0.99999c \), and the watch advances just 16 seconds. At \( 0.999999c \), only five seconds pass in the cabin while an entire asteroid hour ticks outside. The thrust has not made much difference in decimals of velocity, but it has radically shortened the astronaut’s share of time.

Momentum and energy tell the same tale. At \( 0.9995c \), the momentum is \( p = \gamma m v \approx 31.6\,m \times 0.9995c \). At \( 0.9999c \), \( p \approx 70.7\,m \times 0.9999c \). The rocket’s momentum more than doubles. Energy rises similarly: from \( 31.6\, m c^2 \) to \( 70.7\, m c^2 \). Thus, although speed barely crept upward, the cost in energy and momentum exploded. Every pulse of thrust poured more into bending the worldline toward the light cone, not into overtaking it.

This resolves the paradox. The pilot can feel the steady push because proper acceleration is real. The asteroids register almost no extra velocity because coordinate speed saturates. Both views are consistent because the true variable soaking up the thrust is \( \gamma \), not \( v \). What changes dramatically is the path: how proper time compares to external time, how energy accumulates, how the future opens.

In effect, the astronaut has found a one-way machine for time travel. No dial must be set, no wormhole must be found. It is enough to burn fuel at near-light speed. Every hour of proper acceleration slices one’s personal duration thinner, while the rest of the universe rushes ahead. The rocket is both ordinary vehicle and extraordinary chronometer. What seems mundane—sitting pressed into a seat—is, in truth, passage into the future.

\section{Standard Physics Picture}
Special relativity encodes subluminal motion and time dilation via the structure of Minkowski spacetime \cite{einstein1905,MTW1973}. The key relations are
\[
\gamma = \frac{1}{\sqrt{1 - v^2/c^2}}, \qquad
E=\gamma m c^2, \qquad
p=\gamma m v.
\]
As \( v \to c \), \( \gamma \to \infty \), so \( E \) and \( p \) diverge while \( v \) approaches \( c \) asymptotically. Proper acceleration \( \alpha \) (felt in the rocket) is related to the coordinate acceleration \( a = dv/dt \) by
\[
\alpha = \gamma^3 a,
\]
so maintaining a fixed felt \( \alpha \) requires progressively smaller \( a \) as \( \gamma \) grows \cite{rindler1991}. Hence the traveler feels a steady push even when the external \( v \) barely changes.

\section{Connection to the Timeless Light Model (TLM)}
TLM proposes that spacetime dynamics are delayed renderings of pre-resolved quantum instructions on a senior quantum platform (QP). In that view, the rocket example is not exotic; it is the frame obeying deployment rules identical to GR/SR: invariant \( c \), Einstein addition, Lorentz dilation, and proper acceleration as the felt invariant. Two specific axioms often cited in TLM v2.0-style summaries are: \emph{mass–delay duality} \( T\cdot m = 1 \) in normalized units, and \emph{causal rendering constancy} \( T\cdot C_s = 1 \), which encode that experienced delay, not superluminal motion, governs observable dynamics.\footnote{See McKinley’s programmatic papers for statements of these axioms and their role in the deployment frame.} In this lens, continuous thrust increases inter-frame delay (higher \( \gamma \)) without breaching \( c \). Thus ``the frame follows GR/SR'' means the observable layer (the spacetime deployment frame) renders events under those laws, while TLM supplies a causal story for why delay governs experience: the traveler’s path lengthens in spacetime accounting, so less proper time accrues for the same external interval. The rocket under thrust is therefore a concrete exemplar of TLM’s claim that everyday relativistic effects are the deployed appearance of deeper instruction dynamics \cite{mckinleyUnified2025,mckinleyRockets2025,mckinleyQPframe2025}.

\appendix
\section{Rigorous Derivations: Constant Proper Acceleration}\label{sec:appendix-derivations}

\subsection{Four-velocity, four-acceleration, and invariants}
Let \( x^\mu(\tau) \) be the worldline parametrized by proper time \( \tau \). The four-velocity is \( u^\mu = \frac{dx^\mu}{d\tau} \) with invariant \( u^\mu u_\mu = -c^2 \). The four-acceleration is \( a^\mu = \frac{du^\mu}{d\tau} \), orthogonal to \( u^\mu \): \( u^\mu a_\mu = 0 \). The \emph{proper acceleration} is the invariant magnitude \( \alpha = \sqrt{a^\mu a_\mu} \) \cite{rindler1991}.

\subsection{Hyperbolic motion}
For constant proper acceleration \( \alpha \) along \( x \) in flat spacetime, the solution with \( x(0)=0 \), \( t(0)=0 \) is
\[
t(\tau) = \frac{c}{\alpha}\,\sinh\!\left(\frac{\alpha \tau}{c}\right), \qquad
x(\tau) = \frac{c^2}{\alpha}\!\left[\cosh\!\left(\frac{\alpha \tau}{c}\right) - 1\right].
\]
Then
\[
v(\tau) = \frac{dx}{dt} = c\,\tanh\!\left(\frac{\alpha \tau}{c}\right), \qquad
\gamma(\tau) = \cosh\!\left(\frac{\alpha \tau}{c}\right).
\]
Thus \( v \to c \) while \( \gamma \to \infty \) as \( \tau \to \infty \).

\subsection{Rapidity}
Define rapidity \( \theta \) by \( v/c = \tanh \theta \). Then
\[
\gamma = \cosh \theta,\qquad \gamma \frac{v}{c} = \sinh \theta,\qquad
\theta(\tau) = \frac{\alpha \tau}{c}.
\]
Equal proper-time steps add equal rapidity, explaining why thrust at high \( v \) mainly raises \( \gamma \).

\subsection{Coordinate vs.\ proper acceleration}
With \( a = dv/dt \) and proper \( \alpha \),
\[
\alpha = \gamma^3 a \quad \Rightarrow \quad a = \frac{\alpha}{\gamma^3}.
\]
For fixed \( \alpha \), \( a \to 0 \) as \( \gamma \to \infty \), reconciling persistent seat push with tiny external \( dv/dt \).

\begin{table}[h]
\centering
\caption{Coordinate acceleration \( a = \alpha/\gamma^3 \) for fixed proper acceleration \( \alpha = 1g \approx 9.8 \,\mathrm{m/s^2} \).}
\begin{tabular}{@{}llll@{}}
\toprule
Lorentz factor \( \gamma \) & Velocity (\( v/c \)) & Proper accel.\ \( \alpha \) & Coordinate accel.\ \( a \) \\ \midrule
1.0   & 0.0       & 9.8 m/s\(^2\) & 9.8 m/s\(^2\) \\
10    & 0.995     & 9.8 m/s\(^2\) & \( 9.8/10^3 = 9.8\times10^{-3} \) m/s\(^2\) \\
100   & 0.99995   & 9.8 m/s\(^2\) & \( 9.8/10^6 = 9.8\times10^{-6} \) m/s\(^2\) \\
1000  & 0.9999995 & 9.8 m/s\(^2\) & \( 9.8/10^9 = 9.8\times10^{-9} \) m/s\(^2\) \\ \bottomrule
\end{tabular}
\end{table}

\subsection{Energy and momentum growth}
\[
E(\tau) = \gamma(\tau) m c^2 = m c^2 \cosh\!\left(\frac{\alpha \tau}{c}\right), \quad
p(\tau) = \gamma(\tau) m v(\tau) = m c \sinh\!\left(\frac{\alpha \tau}{c}\right).
\]
Both grow without bound though \( v(\tau) < c \) always.

\subsection{Elapsed proper time over fixed external time}
For fixed \( v \), \( d\tau = \frac{dt}{\gamma} \). Over an external duration \( \Delta t \), the onboard time is \( \Delta \tau = \frac{\Delta t}{\gamma} \), reproducing the table in Section~2.

\subsection{Geometry of the constant-\( \alpha \) hyperbola}
The worldline above satisfies the hyperbola
\[
(ct)^2 - \bigl(x + \tfrac{c^2}{\alpha}\bigr)^2 = -\bigl(\tfrac{c^2}{\alpha}\bigr)^2,
\]
a right-branch curve with center at \( (-c^2/\alpha, 0) \) and null asymptotes \( ct = \pm\bigl(x + c^2/\alpha\bigr) \). Figure~\ref{fig:hyperbola} sketches this geometry.

\begin{figure}[h]
\centering
\begin{tikzpicture}[scale=0.9,>=Latex]
  % axes
  \draw[->] (-4.2,0) -- (4.6,0) node[below right] {\(x\)};
  \draw[->] (0,-0.4) -- (0,4.6) node[left] {\(ct\)};

  % choose k = c^2/alpha for the sketch (set k=2 units)
  \def\k{2.0}

  % light cone through origin for reference
  \draw[dashed,gray] (-4,4) -- (0,0) -- (4,4);

  % null asymptotes through (-k,0): ct = ±(x + k)
  \draw[dashed] (-\k,0) -- (4,4-\k) node[pos=0.85, right] {\small \(ct = x + \k\)};
  \draw[dashed] (-\k,0) -- (4,-4+\k);
  \node[below left] at (-\k,0) {\small center};

  % hyperbola branch: x = k(cosh-1), ct = k sinh
  \draw[thick,red,domain=0:2.0,smooth,variable=\t]
    plot ({\k*(cosh(\t)-1)}, {\k*sinh(\t)});
  \node[red,below right] at (0,0) {\small \(\tau=0\)};
  \fill[red] (0,0) circle (1.2pt);

  % a few proper-time ticks
  \foreach \T in {0.6,1.2,1.8}{
    \fill[red] ({\k*(cosh(\T)-1)}, {\k*sinh(\T)}) circle (1pt);
  }
\end{tikzpicture}
\caption{Constant-proper-acceleration hyperbola. The null asymptotes \( ct=\pm\bigl(x+c^2/\alpha\bigr) \) are shown as dashed lines through the center at \( (-c^2/\alpha,0) \). Proper time increases along the red branch; for large \( \tau \), the worldline approaches the upper-right null asymptote.}
\label{fig:hyperbola}
\end{figure}

\section{Acknowledgments}
The author thanks standard SR references for canonical derivations of hyperbolic motion and proper acceleration, especially Rindler and MTW.

\begin{thebibliography}{99}

\bibitem{einstein1905}
A.~Einstein, \emph{On the Electrodynamics of Moving Bodies}, Annalen der Physik \textbf{17}, 891 (1905).
\newblock \href{https://doi.org/10.1002/andp.19053221004}{DOI:10.1002/andp.19053221004}

\bibitem{rindler1991}
W.~Rindler, \emph{Introduction to Special Relativity}, 2nd ed.\ (Oxford University Press, 1991).
\newblock ISBN 978\,0198539528. \emph{No DOI available.}

\bibitem{MTW1973}
C.~W.~Misner, K.~S.~Thorne, and J.~A.~Wheeler, \emph{Gravitation} (W.~H. Freeman, 1973).
\newblock ISBN 978\,0716703440. \emph{No DOI available.}

\bibitem{mckinleyUnified2025}
J.~C.~W.~McKinley, \emph{Unified Physics by Subordination of GR to QM: Quantum Phenomena as the Generator of the Classical Universe}, Zenodo (2025).
\newblock \href{https://doi.org/10.5281/zenodo.15868624}{DOI:10.5281/zenodo.15868624}

\bibitem{mckinleyRockets2025}
J.~C.~W.~McKinley, \emph{Why Rockets Can’t Go Faster Than Light}, Zenodo (2025).
\newblock \href{https://doi.org/10.5281/zenodo.16758093}{DOI:10.5281/zenodo.16758093}

\bibitem{mckinleyQPframe2025}
J.~C.~W.~McKinley, \emph{Quantum Platform as Frame Generator}, Zenodo (2025).
\newblock \href{https://doi.org/10.5281/zenodo.16788735}{DOI:10.5281/zenodo.16788735}

\end{thebibliography}

\end{document}

```

</details>

---
{% endraw %}
