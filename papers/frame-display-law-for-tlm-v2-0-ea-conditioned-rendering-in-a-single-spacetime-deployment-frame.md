---
layout: default
title: '[2025] Frame Display Law for TLM v2.0: EA-conditioned Rendering in a Single Spacetime Deployment Frame'
description: 'Publication metadata and archived raw LaTeX source by John C. W. McKinley.'
permalink: /papers/frame-display-law-for-tlm-v2-0-ea-conditioned-rendering-in-a-single-spacetime-deployment-frame/
paper: true
---
{% raw %}
# [2025] Frame Display Law for TLM v2.0: EA-conditioned Rendering in a Single Spacetime Deployment Frame
*   **DOI:** [10.5281/zenodo.16936105](https://doi.org/10.5281/zenodo.16936105)
*   **Date:** 24 August 2025

<details markdown="1">
<summary><b>Click to view Raw LaTeX Source</b></summary>

```latex
\documentclass[12pt,letterpaper]{article}

% ------- Packages -------
\usepackage[margin=1in]{geometry}
\usepackage[T1]{fontenc}
\usepackage[utf8]{inputenc}
\usepackage{lmodern}
\usepackage{microtype}
\usepackage{amsmath,amssymb,amsthm,mathtools}
\usepackage{xcolor}
\usepackage[most]{tcolorbox}
\usepackage{tikz}
\usetikzlibrary{arrows.meta,calc,positioning}
\usepackage{hyperref} % keep this last
\hypersetup{colorlinks=true,linkcolor=blue,urlcolor=blue,citecolor=blue}

% ------- Title -------
\title{Frame Display Law for TLM v2.0:\\
EA-conditioned Rendering in a Single Spacetime Deployment Frame}
\author{John C. W. McKinley \\ Independent Researcher \\ 
\href{https://orcid.org/0009-0005-7097-5035}{0009-0005-7097-5035}}
\date{August 24, 2025}

% ------- Boxes -------
\newtcolorbox{lawbox}[1]{enhanced,breakable,
  colback=white,colframe=black,boxrule=0.7pt,
  sharp corners, left=8pt,right=8pt,top=8pt,bottom=8pt,
  title={#1}}
\newtcolorbox{notebox}[1]{enhanced,breakable,
  colback=white,colframe=black,boxrule=0.6pt,
  sharp corners, left=6pt,right=6pt,top=6pt,bottom=6pt,
  title={#1}}

% ------- Theorem-like -------
\newtheorem{proposition}{Proposition}




\begin{document}
\maketitle
\begingroup\renewcommand\thefootnote{}\footnotetext{This version published at
\href{https://doi.org/10.5281/zenodo.16936105}{https://doi.org/10.5281/zenodo.16936105}.}\endgroup



\begin{abstract}
In the Timeless Light Model v2.0, quanta are frameless ticks and the wavefunction belongs to the observer frame. This short paper states a precise \emph{Frame Display Law} for rendering emitter-absorber movies once the absorber \( A^* \) is ontically fixed in the Quantum Platform. The law uses only standard frame-side propagators, a time-symmetric conditioning on \( (E,A^*) \), and a display rule that draws \( c \)-limited rays along stationary-phase ridges of the EA amplitude. Pacing is governed by the bridge laws \( T\,m=\hbar/c^2 \) and \( T\,C_s=1 \). The result preserves no-retrocausal signaling while matching ordinary optics \cite{BornWolf,FeynmanHibbs}, post-selection statistics via ABL \cite{Aharonov1964}, and the time-symmetric use of advanced solutions familiar from Wheeler-Feynman \cite{WheelerFeynman1945,WheelerFeynman1949}.
\end{abstract}

\section{Introduction and stance}
\label{sec:intro}
TLM v2.0 separates ontology and rendering. Quanta are frameless state-change ticks recorded in a timeless Quantum Platform (QP). Movies, paths, and probabilities are properties of a \emph{Spacetime Deployment Frame} (SDF). In this stance the wavefunction is a \emph{frame amplitude}, not a photon property. When an emission \( E \) and a realized absorber \( A^* \) are a completed pair, the frame renders a causal movie consistent with geometry and records. This paper codifies that rendering as a frame-side law and contrasts it with standard time-symmetric machinery \cite{Aharonov1964,WheelerFeynman1945,WheelerFeynman1949} while remaining compatible with SR and GR pacing \cite{Einstein1905,WaldGR} and with the author’s prior TLM statements \cite{McKinleyQuantaGlobal2025,McKinleyQTransfer2025,McKinleyPairingLaw2025,McKinleyQPlatformFrame2025,McKinleyWFDisambig2025}.

\clearpage

\begin{notebox}{Notation}
\begin{itemize}
  \item \( G \): geometry in the SDF, including metric, boundaries, media, apertures.
  \item \( |E\rangle \) at time \( t_E \): source state that seeds the forward field.
  \item \( |A^*\rangle \) at time \( t_A \): realized absorber state that seeds the backward field.
  \item \( R^* \): recorded tags such as polarization, timing windows, which-way flags.
  \item \( U(t,t_0) \): standard frame-side propagator for the chosen dynamics.
  \item Bridge laws: \( T\,m=\hbar/c^2 \) and \( T\,C_s=1 \) pace the rendered movie \cite{McKinleyQTransfer2025,McKinleyQuantaGlobal2025}.
\end{itemize}
\end{notebox}

\section{Ontic pairing and domain of the law}
\label{sec:setup}
\textbf{Pairing axiom.} Only completed pairs \( (E,A^*) \) are written to QP. Once written, the always-was consistency applies. The SDF never needs to choose an outcome; it conditions on \( A^* \) already realized in QP, then renders the unique movie consistent with \( G \) and \( R^* \) \cite{McKinleyPairingLaw2025,McKinleyQPlatformFrame2025}.

\section{Frame Display Law}
\label{sec:law}
\begin{lawbox}{{Frame Display Law (EA-conditioned rendering)}}
\textbf{Setup in a single SDF that spans \( E \) and \( A^* \).} Inputs: geometry \( G \), source state \( |E\rangle \) at \( t_E \), realized absorber \( |A^*\rangle \) at \( t_A \), and record sector \( R^* \).

\medskip
\textbf{1. Forward field (retarded).}
\[
\psi_f(x,t)=U(t,t_E)\,|E\rangle.
\]
Solve with the standard SDF propagator over \( G \) for the relevant equation set \cite{BornWolf,FeynmanHibbs}.

\medskip
\textbf{2. Backward field (advanced or adjoint).}
\[
\psi_b(x,t)=U(t,t_A)^{\dagger}\,|A^*\rangle.
\]
Time-symmetric use of adjoint solutions is standard in pre- and post-selected formalisms and absorber-style constructions \cite{Aharonov1964,WheelerFeynman1945,WheelerFeynman1949}.

\medskip
\textbf{3. EA amplitude conditioned on \( A^* \) and records.}
\[
\psi_{EA}(x,t)\propto\big(\psi_b(x,t)\big)\,\big(\psi_f(x,t)\big)\quad\text{restricted to sector } R^*.
\]
Interpretation: \( \psi_{EA} \) is a frame amplitude used for rendering. It is not a physical field carried by the photon.

\medskip
\textbf{4. Display rule.}
\begin{itemize}
  \item \emph{Display events, photon-like:} draw \( c \)-limited ray segments along the ridge or stationary-phase curves of \( |\psi_{EA}(x,t)| \). If multiple stationary branches exist, the rendered branch must be consistent with \( R^* \) \cite{BornWolf,FeynmanHibbs}.
  \item \emph{Non-display events, entanglement or tunneling:} show only correlated endpoints. No trajectory is rendered.
\end{itemize}
Rendered paths are movie artifacts inside the SDF. The frameless tick has no path.

\medskip
\textbf{5. Tomography consistency.}
For hypothetical intermediate projectors \( \{\Pi_k\} \),
\[
P(k\,|\,E,A^*)\propto|\langle A^*|\,\Pi_k\,|E\rangle|^2.
\]
This is the ABL conditional; any probe would register conditional frequencies consistent with the EA amplitude without enabling retro-signaling \cite{Aharonov1964}.

\medskip
\textbf{6. Pacing by bridge laws.}
Displayed delays, phases, and energy bookkeeping obey
\[
T\,m=\hbar/c^2,\qquad T\,C_s=1,
\]
so that SR or GR timing, redshift, and eikonal optics along the rendered branch are reproduced \cite{Einstein1905,WaldGR,McKinleyQTransfer2025,McKinleyQuantaGlobal2025}.
\end{lawbox}

\section{Worked micro-examples}
\label{sec:examples}

\paragraph{Double-slit with post-selected pixel.}
Let \( |E\rangle \) seed a Huygens forward field through two slits, and let \( |A^*\rangle \) be the realized pixel on the screen. The product \( \psi_{EA} \) exhibits fringes. The movie draws a \( c \)-limited ray along a stationary-phase ridge that reaches the pixel, consistent with any polarization or timing tags in \( R^* \). Which-way records collapse cross-terms by sector restriction \cite{BornWolf,FeynmanHibbs}.

\paragraph{Gravitational lens with multi-branch geometry.}
With lensing geometry \( G \) that allows several stationary optical paths, \( |\psi_{EA}| \) has multiple ridges. The display renders the branch consistent with \( R^* \) and paces relative delays by the bridge laws, matching time-delay lens phenomenology \cite{WaldGR}.

\begin{figure}[t]
\centering
\begin{tikzpicture}[scale=1.0,>=Latex]
  % Axes
  \draw[->] (-0.2,0) -- (8,0) node[right]{screen coordinate};
  \draw[->] (0,-0.2) -- (0,4) node[above]{intensity schematic};
  % Two-slit envelope (schematic fringes)
  \foreach \x in {0.5,1.0,...,7.5}{
    \pgfmathsetmacro{\y}{2.2 + 1.6*sin(360*(\x/1.5))}
    \fill (\x, 0) circle (0.015);
    \draw[opacity=0.25] (\x,0) -- (\x, {0.2+0.8*max(0,\y)});
  }
  % Mark a realized pixel A*
  \draw[red,very thick] (6.0,0) -- (6.0,3.0);
  \node[red] at (6.0,3.3) {$A^*$};
  % Stationary-phase branch as a ray segment
  \draw[blue,thick,->] (1.0,0.5) .. controls (2.0,1.2) and (4.0,2.2) .. (6.0,3.0);
  \node[blue] at (4.0,2.6) {stationary-phase ridge};
  % Labels
  \node at (1.0,-0.4) {slits};
  \node at (6.0,-0.4) {screen};
\end{tikzpicture}
\caption{EA-conditioned rendering for a post-selected pixel \( A^* \). The frame draws a \( c \)-limited ray along a stationary-phase ridge of \( |\psi_{EA}| \). The tick itself has no path.}
\label{fig:ea}
\end{figure}

\section{Consistency and no-retro signaling}
\label{sec:consistency}
The time-symmetric construction is strictly frame-side and conditional on the completed pair \( (E,A^*) \). The ABL frequency law in Section \ref{sec:law} ensures that any inserted tomography would have produced statistics consistent with \( |\psi_{EA}|^2 \) without enabling retrocausal communication \cite{Aharonov1964}. The QP provides ontic completeness, while the SDF provides causal deployment \cite{McKinleyQPlatformFrame2025}.

\section{Bridge laws and pacing}
\label{sec:bridge}
The bridge laws
\[
T\,m=\hbar/c^2,\qquad T\,C_s=1
\]
fix pacing. They underwrite the observed clocking of the rendered movie, including Doppler and gravitational redshifts and the eikonal phase picked by stationary-phase selection \cite{Einstein1905,WaldGR,McKinleyQTransfer2025,McKinleyQuantaGlobal2025}. The laws do not modify standard equations of motion; they constrain how the SDF deploys them as a movie.

\section{Falsifiable consequences}
\label{sec:falsifiable}
\begin{itemize}
  \item \textbf{Display versus non-display.} Experiments that toggle which-way records \( R^* \) must convert rendered-path movies into endpoint-only displays with no residual sub-trajectory artifacts. Residuals would falsify the display rule \cite{BornWolf}.
  \item \textbf{Tomography neutrality.} Inserting weak or partial tomography upstream must yield conditional frequencies consistent with the ABL law when post-selecting \( A^* \), and no change in unconditional upstream rates \cite{Aharonov1964}.
  \item \textbf{Stationary-phase rendering.} In multi-branch optics and lensing, the rendered branch statistics must match stationary-phase ridges of \( |\psi_{EA}| \) subject to sector restrictions \( R^* \) \cite{BornWolf}.
\end{itemize}

\section{Discussion and conclusion}
\label{sec:conclusion}
The Frame Display Law is not new dynamics. Steps 1 to 2 use ordinary SDF propagators. Step 3 is a time-symmetric conditioning on the realized absorber and records. Step 4 translates amplitude terrain into movies by a stationary-phase display rule. Step 5 guarantees tomography consistency without retrocausal signaling. Step 6 paces the movie with bridge laws. In sum: pre-resolve by constraints -> compute forward and back -> multiply and condition -> render ridges -> pace by the bridges.

\bigskip
\noindent\textbf{One-line slogan.} Pre-resolve by constraints -> compute forward and back -> multiply and condition -> render ridges -> pace by the bridges.

\bigskip
\noindent\textbf{Acknowledgments.} Thanks to readers of the TLM v2.0 series for requesting a compact statement of the frame-side display rule.

\begin{thebibliography}{99}

\bibitem{Aharonov1964}
Y. Aharonov, P. G. Bergmann, and J. L. Lebowitz,
Time Symmetry in the Quantum Process of Measurement,
\emph{Physical Review} 134 (1964): B1410--B1416.
\href{https://doi.org/10.1103/PhysRev.134.B1410}{doi:10.1103/PhysRev.134.B1410}.

\bibitem{WheelerFeynman1945}
J. A. Wheeler and R. P. Feynman,
Interaction with the Absorber as the Mechanism of Radiation,
\emph{Reviews of Modern Physics} 17 (1945): 157--181.
\href{https://doi.org/10.1103/RevModPhys.17.157}{doi:10.1103/RevModPhys.17.157}.

\bibitem{WheelerFeynman1949}
J. A. Wheeler and R. P. Feynman,
Classical Electrodynamics in Terms of Direct Interparticle Action,
\emph{Reviews of Modern Physics} 21 (1949): 425--433.
\href{https://doi.org/10.1103/RevModPhys.21.425}{doi:10.1103/RevModPhys.21.425}.

\bibitem{BornWolf}
M. Born and E. Wolf,
\emph{Principles of Optics}, 7th ed.,
Cambridge University Press, 1999.

\bibitem{FeynmanHibbs}
R. P. Feynman and A. R. Hibbs,
\emph{Quantum Mechanics and Path Integrals},
McGraw-Hill, 1965.

\bibitem{Einstein1905}
A. Einstein,
On the Electrodynamics of Moving Bodies,
\emph{Annalen der Physik} 17 (1905): 891--921.
(English translations widely available.)

\bibitem{WaldGR}
R. M. Wald,
\emph{General Relativity},
University of Chicago Press, 1984.

% ----- Author's TLM papers with DOIs -----

\bibitem{McKinleyQuantaGlobal2025}
J. C. W. McKinley,
Quanta are Global, Frames are Local: A Rosetta Statement of the Timeless Light Model (v1.0),
Zenodo (2025).
\href{https://doi.org/10.5281/zenodo.16917106}{doi:10.5281/zenodo.16917106}.

\bibitem{McKinleyQTransfer2025}
J. C. W. McKinley,
The Quanta Transfer Law (v1.0),
Zenodo (2025).
\href{https://doi.org/10.5281/zenodo.16897573}{doi:10.5281/zenodo.16897573}.

\bibitem{McKinleyPairingLaw2025}
J. C. W. McKinley,
Generalized Pairing Law: No Quantum Emission Without an Absorber,
Zenodo (2025).
\href{https://doi.org/10.5281/zenodo.16892099}{doi:10.5281/zenodo.16892099}.

\bibitem{McKinleyQPlatformFrame2025}
J. C. W. McKinley,
Quantum Platform as Frame Generator,
Zenodo (2025).
\href{https://doi.org/10.5281/zenodo.16788735}{doi:10.5281/zenodo.16788735}.

\bibitem{McKinleyWFDisambig2025}
J. C. W. McKinley,
Timeless Light Model vs Wheeler–Feynman Absorber Theory: A Disambiguation (v5.0),
Zenodo (2025).
\href{https://doi.org/10.5281/zenodo.16924316}{doi:10.5281/zenodo.16924316}.

\end{thebibliography}

\end{document}
```

</details>

---
{% endraw %}
