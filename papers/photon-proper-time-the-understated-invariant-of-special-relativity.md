---
layout: default
title: '[2025] Photon Proper Time: The Understated Invariant of Special Relativity'
description: 'Publication metadata and archived raw LaTeX source by John C. W. McKinley.'
permalink: /papers/photon-proper-time-the-understated-invariant-of-special-relativity/
paper: true
---
{% raw %}
# [2025] Photon Proper Time: The Understated Invariant of Special Relativity
*   **DOI:** [10.5281/zenodo.17190047](https://doi.org/10.5281/zenodo.17190047)
*   **Date:** 24 September 2025

<details markdown="1">
<summary><b>Click to view Raw LaTeX Source</b></summary>

```latex
\documentclass[12pt, onecolumn]{article}

% ---------- Page & Layout ----------
\usepackage[margin=1in]{geometry}
\usepackage[T1]{fontenc}
\usepackage[utf8]{inputenc}
\usepackage{lmodern}
\usepackage{microtype}

% ---------- Math ----------
\usepackage{amsmath,amssymb,amsthm}

% ---------- Lists ----------
\usepackage{enumitem}

% ---------- Figures & Floats ----------
\usepackage{tikz}
\usetikzlibrary{arrows.meta, positioning}
\usepackage{graphicx}
\usepackage{float}

% ---------- Links & References ----------
\usepackage{hyperref}
\hypersetup{colorlinks=true,linkcolor=blue,urlcolor=blue,citecolor=blue}

% ---------- Headers ----------
\usepackage{fancyhdr}
\pagestyle{fancy}
\fancyhf{}
\lhead{Photon Proper Time: The Understated Invariant of SR}
\rhead{\thepage}

% ---------- ORCID ----------
\usepackage{orcidlink}

% ---------- Title ----------
\title{\textbf{Photon Proper Time: The Understated Invariant of Special Relativity}}
\usepackage{orcidlink}
\author{John C. W. McKinley\orcidlink{0009-0005-7097-5035}\\Independent Researcher}
\date{September 24, 2025}





% ---------- tcolorbox for Laws ----------
\usepackage[most]{tcolorbox}
\tcbset{colback=blue!5!white, colframe=blue!75!black, fonttitle=\bfseries}
\newtcolorbox{lawbox}[1][]{enhanced, breakable, title=Invariant Statement, #1}

\begin{document}

\maketitle


\begingroup
  \footnotetext[0]{This version published at
  \href{https://doi.org/10.5281/zenodo.17190047}{https://doi.org/10.5281/zenodo.17190047}.}
\endgroup

\begin{abstract}
In special relativity, proper time is defined along timelike worldlines; for null (lightlike) paths the invariant interval vanishes, $\Delta s^2=0$, implying $\Delta\tau=0$. This is standard and well taught, yet its physical interpretation is \emph{often understated}: popular and even professional discussions sometimes defer to ``no rest frame for light'' and leave the consequence (timeless photons) unexplored. We restate the invariant result as Einstein framed it \cite{einstein1905}, show its coordinate-free derivation, and summarize its implications (e.g., no photon aging). We then connect the invariant explicitly to the proposed Timeless Light Model (TLM), in which a photon is treated not as a thing that travels but as a \emph{timeless instruction} deployed within a Spacetime Deployment Frame (SDF)\footnote{SDF is the author's term for the rendered relativistic layer where observable events appear; it is standard SR/GR kinematics interpreted as a deployment layer.}. Key geometric references include Taylor \& Wheeler \cite{taylorwheeler}, Misner--Thorne--Wheeler \cite{mtw}, Wald \cite{wald}, and Rindler \cite{rindler}.
\end{abstract}

\section{Introduction}
Special relativity (SR) centers on invariants. Proper time $\tau$ measures elapsed time along a worldline as experienced by the system itself. For massive bodies (timelike paths) $\Delta\tau>0$; for lightlike paths, the invariant interval is null, yielding $\Delta\tau=0$. While this statement is common in pedagogy and popular explanations, its interpretive weight is frequently minimized in practice by appeals to frames (``no frame at $v=c$''). Here we keep focus on the invariant itself and what follows from it, connecting to the geometric pedagogy in \cite{taylorwheeler,mtw,wald,rindler}.

\section{Einstein and Proper Time}
Einstein's 1905 paper introduces the invariant spacetime interval (we adopt the $(+,-,-,-)$ signature for clarity in this note):
\begin{equation}
\Delta s^2 = c^2\Delta t^2 - \Delta x^2 - \Delta y^2 - \Delta z^2, \label{eq:interval}
\end{equation}
see \cite{einstein1905}. For timelike separations ($\Delta s^2>0$), proper time is
\begin{equation}
\Delta\tau = \frac{\Delta s}{c}.
\end{equation}

\begin{lawbox}
For null separations ($\Delta s^2=0$), proper time vanishes identically:
\begin{equation}
\Delta\tau = 0.
\end{equation}
\end{lawbox}

This is an invariant statement; it does not require (nor permit) a photon rest frame.

\section{How the Point Gets Soft-Pedaled}
Standard texts correctly state that photons have no rest frame and that null paths satisfy $\Delta s^2=0$ \cite{taylorwheeler,mtw,wald,rindler}. In many expositions this leads to a practical de-emphasis of consequences (``undefined proper time for a photon''), which can be misread as negating the invariant result. To avoid that confusion, we keep the logical order explicit:
\begin{enumerate}[label=\arabic*), leftmargin=*, itemsep=2pt]
\item Proper time is defined via the interval.
\item The interval on null worldlines is \emph{invariantly} zero.
\item Therefore $\Delta\tau=0$ for photons, independent of any notion of a photon frame.
\end{enumerate}








\section{An Example of How the Point Gets Understated}

To document what we mean by “understated,” here are two representative, widely shared explanations that pivot quickly to “no rest frame” and stop short of discussing the consequences of the null interval $\Delta s^2=0$:

\begin{quote}\itshape
“Time is not frozen from light’s perspective, because light does not have a perspective. There is no valid reference frame in which light is at rest.”%
\footnote{\href{https://www.wtamu.edu/~cbaird/sq/2014/11/03/why-is-time-frozen-from-lights-perspective/}{C.~Baird, \emph{Why is time not frozen from light’s perspective?} West Texas A\&M University (2014)}}
\end{quote}

\begin{quote}\itshape
“The notion that photons experience no time is poorly stated, but it does serve an explanatory purpose.”%
\footnote{\href{https://www.physicsforums.com/threads/why-is-proper-time-undefined-for-spacelike-lightlike-paths.891710/}{PhysicsForums discussion: \emph{Why is proper time undefined for spacelike/lightlike paths?} (2016)}}
\end{quote}

These are accurate as far as they go—photons have no rest frame. Our point is that the invariant statement comes first and is independent of frames:
\[
\Delta s^2 = c^2 \Delta t^2 - \Delta \vec{x}^{\,2} = 0 \;\;\Rightarrow\;\; \Delta \tau = 0.
\]
Emphasizing only “no rest frame” tends to soft-pedal the implication that photons have no proper time \emph{by invariant definition}. The discussion in this note keeps the logical order explicit and then examines the physical consequences in Sections~\ref{sec:Consequences} and~\ref{sec:TLM}.












\section{Mathematical Derivation (SR)}
From Eq.~\eqref{eq:interval}, for lightlike propagation with $|\Delta\vec{x}|=c\,\Delta t$ one has
\begin{equation}
\Delta s^2 = c^2\Delta t^2 - (c\Delta t)^2 = 0 \;\;\Rightarrow\;\; \Delta\tau^2 = \frac{\Delta s^2}{c^2}=0.
\end{equation}
This derivation is coordinate-free in content: every inertial observer computes the same $\Delta s^2$ and hence the same $\Delta\tau$ \cite{taylorwheeler,mtw}.

\section{Consequences (Often Understated)}\label{sec:Consequences}
If $\Delta\tau=0$ on a photon's worldline:
\begin{itemize}[leftmargin=*, itemsep=2pt]
\item A photon does not age; there is no proper-time evolution along a null path.
\item Phase accumulation is not parameterized by proper time for lightlike motion.
\item Statements about what a photon ``experiences'' are ill-posed in proper-time terms.
\end{itemize}
These are direct, non-controversial consequences of SR. In GR, null geodesics preserve $ds^2=0$ as well, maintaining the same conclusion for massless fields in curved spacetime \cite{wald}.

\section{Context in the Timeless Light Model (TLM)}\label{sec:TLM}
TLM takes the invariant result seriously rather than setting it aside: photons are treated as \emph{timeless instructions} whose observable appearances are deployments within the spacetime frame. Mass and delay belong to the deployment (frame) layer, not to the photon. \emph{Concrete example}: a photon is not a thing that travels; it is a set of instructions that manifests as an energy exchange at a detector after a frame-dependent light-time delay. For a fuller development---axioms, derivations, and testable consequences---see \cite{mckinley_photon_out_of_time,mckinley_light_as_absent,mckinley_wave_particle_delay,mckinley_cornerstone}.

\section{Brief Summary of the Timeless Light Model (TLM)}
The Timeless Light Model (TLM) begins from the invariant that photons have no proper time. If a photon does not age, then it cannot meaningfully be described as a thing ``traveling'' through the universe. Instead, TLM reframes the photon as a \emph{timeless instruction} linking an emission and an absorption event. The universe we measure---with clocks, rulers, redshifts, and delays---is not the arena in which the photon exists, but the arena in which those instructions are \emph{deployed}. This deployed layer is called the Spacetime Deployment Frame (SDF), which corresponds to the relativistic geometry of SR and GR. Within the SDF, mass acts as a delay parameter: the more mass, the slower processes unfold. By contrast, the underlying Quantum Platform (QP) issues instructions timelessly, outside spacetime. A photon instruction thus does not traverse a distance in time; it simply manifests a correlation of states between emission and detection, paced by the SDF’s delay. This separation---QP as cause, SDF as deployment---allows TLM to unify relativity’s geometry with quantum phenomena. Light’s timelessness, far from being a mathematical curiosity, becomes the keystone of a model where reality is the rendered output of deeper, timeless rules \cite{mckinley_photon_out_of_time,mckinley_light_as_absent,mckinley_wave_particle_delay,mckinley_cornerstone}.

\paragraph{Quantum Platform (QP).} A timeless, spaceless source of pre-resolved instructions that specify which events will be deployed.

\paragraph{Spacetime Deployment Frame (SDF).} The rendered relativistic layer in which events appear with distances, durations, and trajectories; the place where SR and GR apply as deployment rules.

\paragraph{Timeless Instruction (photon).} A massless instruction that realizes as an energy exchange between emission and absorption, linked by a null separation with $\Delta s^2=0$ and $\Delta\tau=0$.

\paragraph{Mass as Delay.} In TLM, mass is not causal but functions as a drag or delay parameter in the SDF, slowing the deployment of events.

\section{Conclusion}
``Photons have no proper time'' is not a speculative claim; it is the invariant content of SR. What is frequently understated is the interpretive follow-through. TLM is a program that keeps the invariant front-and-center and explores its implications for how we model light, information transfer, and the relationship between quantum descriptions and spacetime deployment \cite{mckinley_cornerstone}.

\section*{Note on Signature}
This paper uses the $(+,-,-,-)$ metric signature in the body and appendix. Some of the author's other papers use $(-,+,+,+)$. Results are invariant under consistent convention.

\begin{figure}[H]
\centering
\begin{tikzpicture}[scale=2]
  % axes
  \draw[-{Latex}] (-1.1,0) -- (1.1,0) node[below right] {$x$};
  \draw[-{Latex}] (0,-1.1) -- (0,1.1) node[above left] {$ct$};
  % light cone lines
  \draw[thick] (-1.0,-1.0) -- (1.0,1.0);
  \draw[thick] (-1.0,1.0) -- (1.0,-1.0);
  % labels
  \node[above right] at (0.05,0.95) {$\Delta s^2=0$};
  \node[below right] at (0.05,-0.95) {$\Delta s^2=0$};
  \node at (0.55,0.55) {future null};
  \node at (0.55,-0.55) {past null};
\end{tikzpicture}
\caption{Minkowski light cone. Null directions (photon worldlines) satisfy $\Delta s^2=0$, hence $\Delta\tau=0$.}
\label{fig:lightcone}
\end{figure}

\appendix

\section{Rigorous Derivation (Coordinate Form)}
With signature $(+,-,-,-)$ the Minkowski metric is
\begin{equation}
ds^2 = g_{\mu\nu}\,dx^\mu dx^\nu = c^2 dt^2 - dx^2 - dy^2 - dz^2.
\end{equation}
Proper time is defined by
\begin{equation}
d\tau^2 = \frac{ds^2}{c^2}.
\end{equation}
For null paths, $ds^2=0$ identically, implying $d\tau=0$. This is unchanged by Lorentz transformations and extends to null geodesics in GR via $ds^2=0$ along the curve \cite{wald}.



\begin{thebibliography}{12}

\bibitem{einstein1905}
A.~Einstein, \textit{Zur Elektrodynamik bewegter K\"{o}rper}, \emph{Annalen der Physik} \textbf{17}, 891--921 (1905). English translation via Wiley: \href{https://doi.org/10.1002/andp.19053221004}{doi:10.1002/andp.19053221004}.

\bibitem{taylorwheeler}
E.~F.~Taylor and J.~A.~Wheeler, \textit{Spacetime Physics} (W. H. Freeman, 2nd ed., 1992). ISBN: 978-0716723271.

\bibitem{mtw}
C.~W.~Misner, K.~S.~Thorne, and J.~A.~Wheeler, \textit{Gravitation} (Princeton University Press reprint, 2017; originally 1973). ISBN: 978-0691177793.

\bibitem{wald}
R.~M.~Wald, \textit{General Relativity} (University of Chicago Press, 1984). \href{https://doi.org/10.7208/chicago/9780226870373.001.0001}{doi:10.7208/chicago/9780226870373.001.0001}.

\bibitem{rindler}
W.~Rindler, \textit{Relativity: Special, General, and Cosmological} (Oxford University Press, 2nd ed., 2006). ISBN: 978-0198567318.

\bibitem{mckinley_photon_out_of_time}
J.~C.~W.~McKinley, \textit{Photon Out of Time: Why Light Experiences No Time---and What That Means for Physics}, Zenodo (2025). \href{https://doi.org/10.5281/zenodo.16479322}{doi:10.5281/zenodo.16479322}.

\bibitem{mckinley_light_as_absent}
J.~C.~W.~McKinley, \textit{Light as Absent: Reclassifying the Photon as a Timeless Instruction}, Zenodo (2025). \href{https://doi.org/10.5281/zenodo.16627550}{doi:10.5281/zenodo.16627550}.

\bibitem{mckinley_wave_particle_delay}
J.~C.~W.~McKinley, \textit{Resolving Wave--Particle Duality Through the Proposed Timeless Light Model: Photons as Timeless Instructions and Waves as Deployed Delay}, Zenodo (2025). \href{https://doi.org/10.5281/zenodo.16510862}{doi:10.5281/zenodo.16510862}.

\bibitem{mckinley_cornerstone}
J.~C.~W.~McKinley, \textit{Foundational Equations and Axiomatic Structure of the Timeless Light Model: A Synthesis Across Sixty Papers and Working Notes}, Zenodo (2025). \href{https://doi.org/10.5281/zenodo.16187719}{doi:10.5281/zenodo.16187719}.

\end{thebibliography}

\end{document}

```

</details>

---
{% endraw %}
