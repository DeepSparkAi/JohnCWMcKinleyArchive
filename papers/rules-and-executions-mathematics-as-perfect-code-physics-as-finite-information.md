---
layout: default
title: '[2025] Rules and Executions: Mathematics as Perfect Code, Physics as Finite Information'
description: 'Publication metadata and archived raw LaTeX source by John C. W. McKinley.'
permalink: /papers/rules-and-executions-mathematics-as-perfect-code-physics-as-finite-information/
paper: true
---
{% raw %}
# [2025] Rules and Executions: Mathematics as Perfect Code, Physics as Finite Information
*   **DOI:** [10.5281/zenodo.17115196](https://doi.org/10.5281/zenodo.17115196)
*   **Date:** 14 September 2025

<details markdown="1">
<summary><b>Click to view Raw LaTeX Source</b></summary>

```latex
\documentclass[12pt, onecolumn]{article}

% ---------- Encoding & Fonts ----------
\usepackage[utf8]{inputenc}
\usepackage[T1]{fontenc}
\usepackage{lmodern}

% ---------- Page & Layout ----------
\PassOptionsToPackage{letterpaper,margin=1in}{geometry}
\usepackage{geometry}
\usepackage{setspace}
\setstretch{1.12}

% ---------- Math ----------
\usepackage{amsmath,amssymb,amsthm}

% ---------- Figures, Tables, Floats ----------
\usepackage{graphicx}
\usepackage{float}        % for [H]
\usepackage{array}
\usepackage{booktabs}
\newcolumntype{L}[1]{>{\raggedright\arraybackslash}p{#1}}

% ---------- TikZ / PGF (Overleaf-friendly) ----------
\usepackage{tikz}
\usetikzlibrary{arrows.meta,positioning,calc,shapes.geometric,decorations.pathmorphing,fit}
\usepackage{pgfplots}
\pgfplotsset{compat=1.18}

% ---------- Links ----------
\usepackage[hidelinks]{hyperref}

% ---------- Headers ----------
\usepackage{fancyhdr}
\pagestyle{fancy}
\fancyhf{}
\lhead{Rules and Executions}
\rhead{\thepage}

% ---------- Theorem-like ----------
\newtheorem{axiom}{Axiom}
\newtheorem{principle}{Principle}
\newtheorem{theorem}{Theorem}
\newtheorem{lemma}{Lemma}
\newtheorem{corollary}{Corollary}
\theoremstyle{remark}
\newtheorem*{remark}{Remark}
\theoremstyle{definition}
\newtheorem{definition}{Definition}

% HYPERLINK SETUP
\usepackage{hyperref}
\hypersetup{colorlinks=true,linkcolor=blue,urlcolor=blue,citecolor=blue}
\usepackage{cleveref}

% ---------- Title ----------
\title{Rules and Executions: Mathematics as Perfect Code, Physics as Finite Information}
\usepackage{orcidlink}
\author{John C. W. McKinley\orcidlink{0009-0005-7097-5035}\thanks{This version published at
  \href{https://doi.org/10.5281/zenodo.17115196}{https://doi.org/10.5281/zenodo.17115196}.}\\Independent Researcher}
\date{September 13, 2025}

\begin{document}
\maketitle




\begin{abstract}
Only mathematics carries completed infinities. Real systems exhibit finite information and discrete detection events. This paper states and defends a modest thesis: physics is the study of exact rules and their finite executions. Smooth structures in standard SR/GR are read as effective codes for expectations of discrete token events, not as commitments to ontic infinitesimals. We formalize two axioms about rulehood and resource limits, extract an operational indivisibility theorem, supply rigorous derivations from information theory and estimation theory, show how gradual predictions arise without infinite divisibility, and lists empirical habits that follow. A short note maps the view onto a two layer vocabulary: a rule layer outside time and an execution layer inside a universe.
\end{abstract}

\noindent\textbf{Keywords:} finite information, operational indivisibility, estimation theory, SR/GR, smooth codes, rules vs execution

\section{Claim and scope}\label{sec:scope}
This paper makes an operational claim, compatible with standard special and general relativity: completed infinities are mathematical; experimental readouts are finite in information content and discrete in detection events. Therefore smooth formulas are best understood as \emph{codes} whose parameters describe limits of averages or counts, while observations arrive as discrete token events. No change to SR/GR equations is proposed. The claim is about interpretation and testable scaling habits.

\section{Axioms and a working principle}\label{sec:axioms}
\begin{axiom}[Rules exist]\label{ax:rules}
Across domains, compact mathematical rules predict wide classes of observations with far shorter description length than any catalogue of raw events.
\end{axiom}

\begin{axiom}[Executed under limits]\label{ax:limits}
Any physical realization has finite energy, time, and channel capacity. Any readout in finite time has finite precision and nonzero noise.
\end{axiom}

\begin{principle}[Perfection vs attempt]\label{pr:attempt}
Mathematical rules are exact objects. Reality is an execution that approximates those rules within the bounds of \emph{Axiom \ref{ax:limits}}. Smooth parameters live in the code; discrete events and finite estimates live in the execution.
\end{principle}

\section{Operational indivisibility}\label{sec:oi}
We need a minimal notion of a real thing.

\begin{lemma}[Identity by invariants]\label{lem:identity}
A real thing is a token whose identity is fixed by invariants (for example, conserved quantum numbers or topological charges). Any operation that changes those invariants yields a different thing.
\end{lemma}

\begin{theorem}[Operational indivisibility]\label{thm:oi}
Under \emph{Axiom \ref{ax:limits}} and \emph{Lemma \ref{lem:identity}}, every real thing is indivisible at some resolution scale: below that scale, further subdivision is either empirically indistinguishable or destroys the thing by altering its defining invariants.
\end{theorem}

\noindent\textit{Proof sketch.} Finite information bounds how many distinct outcomes any bounded experiment can resolve. Below some step size, cuts produce no new distinguishable outcomes in finite time. If one cuts more drastically and changes the invariants, one no longer has the same token. Either way, subdivision stops being meaningful for the original thing. \(\square\)

\begin{remark}
Theorem \ref{thm:oi} is operational. It does not assert a universal minimal length or time. It states that for any real token there is a smallest \emph{useful} cut, given finite resources.
\end{remark}

\section{Rigorous mathematical derivations}\label{sec:rigor}

\subsection{A finite information bound from capacity and geometry}\label{subsec:cap}
Let \(C\) be the Shannon capacity of an effective readout channel with bandwidth \(B\), power \(P\), and noise \(N_0\):
\begin{equation}\label{eq:shannon}
C = B \log_2\!\bigl(1 + \tfrac{P}{N_0 B}\bigr).
\end{equation}\cite{Shannon1948}
Over time \(T\), the reliably distinguishable bits satisfy \(I(T) \le C T\). With total readout energy \(E=PT\), a finite apparatus of size \(R\) cannot support arbitrarily large \(B\) (mode limit \(B \lesssim \alpha c/R\))\cite{PollakSlepian}. Eliminating \(B,T\) yields the schematic bound
\begin{equation}\label{eq:ERbound}
I \;\leq\; \kappa\,\frac{E\,R}{\hbar c},
\qquad
\text{schematic, Bekenstein-like; } [ER]=\text{J m},\; [\hbar c]=\text{J m}.
\end{equation}\cite{BekensteinBound}

\noindent\emph{Context.} Inequality~\eqref{eq:ERbound} is a device- and convention-dependent scaling law inspired by
capacity limits and Bekenstein-type arguments. It states that a finite apparatus with linear scale \(R\)
and total readout energy \(E\) cannot extract arbitrarily many reliable bits in finite time. The ratio
\((ER)/(\hbar c)\) is dimensionless, so \(\kappa\) is a constant of order unity that absorbs geometry,
bandwidth limits, and the choice of logarithm base.

\subsection{Le Cam two point method and resolution limits}\label{subsec:lecam}
For testing \(\theta=\theta_0\) vs \(\theta=\theta_0+\delta\) with \(N\) i.i.d.\ samples and Fisher information \(J(\theta_0)\),
\begin{equation}\label{eq:resfloor}
\delta_{\min} \;\asymp\; \frac{1}{\sqrt{N\,J(\theta_0)}},
\end{equation}\cite{LeCam}
else total error remains near \(1/2\). This is an operational floor independent of any claim about ontic discreteness.

\subsection{Cram\'er--Rao and quantum Fisher information}\label{subsec:qcrb}
For an unbiased estimator, \(\mathrm{Var}(\hat{\theta}) \ge 1/(N J(\theta))\)\cite{vanTrees,Kay}. Quantum metrology gives \(\mathrm{Var}(\hat{\theta}) \ge 1/(\nu F_Q)\) with typical scaling \(F_Q \lesssim c_1 T^2\)\cite{Helstrom,Hayashi}, hence
\begin{equation}\label{eq:stdquantumlimit}
\mathrm{Var}(\hat{\theta}) \;\gtrsim\; \frac{1}{N\,T^2}.
\end{equation}

\subsection{Gradual predictions from discrete counts}\label{subsec:poisson}
Let counts be an inhomogeneous Poisson process on \(D\) with intensity \(\lambda(x)=A f(x)\), \(f\) smooth. Binning at mesh \(\Delta\) and exposure \(A\), the histogram estimator \(\hat f_\Delta\) obeys
\begin{equation}\label{eq:uniformconv}
\sup_{x\in D}\bigl|\hat f_\Delta(x)-f(x)\bigr| \xrightarrow[]{\;P\;} 0 \quad \text{as } \Delta\to 0,~ A|B_k|\to\infty,
\end{equation}
so smooth codes are recovered as limits of discrete events.

\subsection{Mesh refinement error for smooth codes}\label{subsec:mesh}
For \(f\in C^1(\overline{D})\), the Riemann sum on mesh \(\Delta\) gives
\begin{equation}\label{eq:riemannerr}
\bigl| \int_D f - I_\Delta \bigr| \le C_f \Delta,
\end{equation}
with \(C_f\) depending on \(\|\nabla f\|_\infty\) and \(D\). Finite sums approximate smooth predictions uniformly.

\subsection{One photon, no split detection}\label{subsec:g2}
A single photon in a lossless balanced beam splitter yields \(g^{(2)}(0)=0\):
\begin{equation}\label{eq:coinc}
\langle a_{\mathrm{out}}^\dagger b_{\mathrm{out}}^\dagger b_{\mathrm{out}} a_{\mathrm{out}} \rangle = 0,
\end{equation}\cite{Loudon}
so you can split amplitude, not the detection event. This exemplifies Theorem \ref{thm:oi}: the photon's detection event is operationally indivisible.



\section{Gradual without infinitesimals}\label{sec:gradual}
SR/GR use smooth manifolds to compute derivatives and geodesics. Empirically, estimates from discrete events converge with resources, per \S\ref{subsec:poisson} and \S\ref{subsec:mesh}. Canonical cases: gravitational redshift (line centers from counts), lensing (centroids from hits), and interferometric strain \(h(t)\) after averaging.

\section{A simple diagrammatic model}\label{sec:fig}
\begin{figure}[H]
\centering
\begin{tikzpicture}[node distance=10mm, every node/.style={align=center}]
  \node[draw, rounded corners, thick, inner sep=6pt, minimum width=0.82\textwidth, fill=gray!10] (rule) {Rule layer (outside time)\\
  Exact equations, symmetries, conservation laws, smooth fields as code};
  \node[draw, rounded corners, thick, inner sep=6pt, minimum width=0.82\textwidth, below=of rule, fill=gray!10] (exec) {Execution layer (inside a universe)\\
  Discrete token events, finite precision, noisy channels};
  \draw[-{Latex[length=3mm]}] (rule) -- node[right]{compile to expectations} (exec);
  \draw[-{Latex[length=3mm]}] (exec) -- node[left]{aggregate to estimates} (rule);
\end{tikzpicture}
\caption{Two layer picture: smooth code vs finite execution. Smooth parameters live in the code; detectors report discrete events whose aggregates approach the code predictions in the valid domain.}
\label{fig:two-layer}
\end{figure}

\begin{figure}[H]
\centering
\begin{tikzpicture}
  \begin{axis}[
    width=0.88\textwidth,
    height=6cm,
    xlabel={$x$},
    ylabel={value},
    grid=both,
    legend style={at={(0.02,0.98)},anchor=north west,font=\small,fill=white},
    ymin=-0.5,ymax=1.2,
  ]
    \addplot[domain=0.2:10,samples=200,thick] {sin(deg(x))/x};
    \addlegendentry{smooth code \(f(x)=\sin x / x\)}
\addplot+[only marks, mark=*, mark size=1.5pt] table[row sep=\\] {
  x     y \\
  0.5   0.9837 \\
  1.0   0.8346 \\
  1.5   0.6974 \\
  2.0   0.5308 \\
  2.5   0.2277 \\
  3.0   0.0353 \\
  3.5  -0.0213 \\
  4.0  -0.1508 \\
  4.5  -0.2407 \\
  5.0  -0.1647 \\
  6.0  -0.0697 \\
  7.0   0.0706 \\
  8.0   0.1358 \\
  9.0  -0.0499 \\
  10.0 -0.1406 \\
};
    \addlegendentry{finite estimates from counts}
  \end{axis}
\end{tikzpicture}
\caption{Gradual in practice: a smooth code curve and a cloud of finite estimates from discrete events. Increasing resources tightens the cloud around the curve.}
\label{fig:cloud}
\end{figure}

% ---------- NEW TIKZ DIAGRAM ----------
% ---------- NEW TIKZ DIAGRAM ----------
\begin{figure}[H]
\centering
\begin{tikzpicture}[scale=0.9, every node/.style={font=\small}]
  % Left panel: coarse
  \begin{scope}
    \node at (3,4.6) {\textbf{Coarse mesh} (\(\Delta\))};
    \draw[thick] (0,0) rectangle (6,4);
    % coarse grid
    \foreach \x in {2,4} \draw[gray!60] (\x,0) -- (\x,4);
    \foreach \y in {2}   \draw[gray!60] (0,\y) -- (6,\y);
    % events (few)
    \foreach \pt in {(0.5,0.4),(1.3,0.8),(2.3,0.2),(2.8,1.1),
                     (4.7,3.7),(5.5,2.2),(3.4,3.1),(1.8,2.7),
                     (4.2,0.8),(5.7,0.5),(0.7,3.2)}{
      \fill \pt circle (1.3pt);
    }
    \node[align=left] at (0.1,-0.5) {Events per bin small,\\ variance large};
  \end{scope}

  % Right panel: fine
  \begin{scope}[xshift=8cm]
    \node at (3,4.6) {\textbf{Finer mesh} (\(\Delta/2\))};
    \draw[thick] (0,0) rectangle (6,4);
    % fine grid
    \foreach \x in {1,2,3,4,5} \draw[gray!60] (\x,0) -- (\x,4);
    \foreach \y in {1,2,3}     \draw[gray!60] (0,\y) -- (6,\y);
    % events (more)
    \foreach \pt in {(0.3,0.4),(0.7,0.9),(1.2,0.6),(1.7,0.3),
                     (2.3,0.5),(2.7,1.1),(3.2,1.7),(3.5,2.3),
                     (4.1,2.8),(4.4,3.5),(4.9,3.8),(5.2,3.2),
                     (5.6,2.7),(5.8,1.9),(5.4,1.1),(4.9,0.6),
                     (4.3,0.9),(3.8,0.4),(3.0,3.1),(2.5,2.6),
                     (1.8,2.9),(1.3,3.4),(0.6,3.1)}{
      \fill \pt circle (1.0pt);
    }
    \node[align=left] at (0.1,-0.5) {Events per bin larger,\\ variance smaller};
  \end{scope}

  % Arrow between panels (no extra library required)
  \draw[->, -{Latex}] (6.2,2) -- (7.8,2)
        node[midway, above]{refine mesh, increase exposure \(A\)};
\end{tikzpicture}
\caption{Mesh refinement and exposure increase: discrete events binned on a coarse grid (\(\Delta\))
versus a finer grid (\(\Delta/2\)). Points are illustrative to show the variance trend; they are not a fit
to a particular dataset.}
\label{fig:meshrefine}
\end{figure}




\section{Information bounds and why infinities stay in math}\label{sec:bounds}
Capacity arguments in \S\ref{subsec:cap} yield the schematic inequality \(I \le \kappa E R/(\hbar c)\). Such bounds do not decide discreteness of spacetime. They assert that no finite apparatus can extract infinite digits from a finite region in finite time. That is enough to ground Theorem \ref{thm:oi} and to interpret smooth fields as codes.

\section{Relation to standard SR/GR}\label{sec:srgr}
SR/GR use smooth manifolds with smooth metrics to compute clock rates, geodesics, curvature, and stress energy flow\cite{WaldGR}. On the reading of this paper:
\begin{enumerate}
  \item Smoothness is a model device that produces stable, scale robust predictions in the tested regime.
  \item Observations are discrete; agreement is assessed on aggregates and estimates, with resolution governed by \eqref{eq:resfloor} and \eqref{eq:stdquantumlimit}.
  \item Singularities flag domain limits of the model, not literal infinities in the world. Resource requirements to probe them diverge formally by \eqref{eq:ERbound}.
\end{enumerate}

\section{Habits and tests}\label{sec:tests}
If the thesis is right, several habits follow.
\begin{itemize}
  \item \textbf{Precision scaling.} As resources \(N\) and \(T\) grow, dispersions shrink in line with \eqref{eq:resfloor}--\eqref{eq:stdquantumlimit} until a domain cutoff is reached. Deviations beyond that are evidence of either missing rules or leaving the domain.
  \item \textbf{Universality.} Low energy behavior forgets microdetails. Smooth codes emerge from stepwise substrates. Tuning a few parameters suffices for accuracy on large scales.
  \item \textbf{Symmetry and conservation.} When premises for a symmetry are satisfied, the associated conservation law holds within error budgets. Apparent violations trace to broken premises or domain changes.
\end{itemize}

\medskip
\noindent\textbf{Concrete examples.}
\begin{enumerate}
  \item \emph{Gravitational wave strain from photon counts.}
  Interferometers reconstruct strain \(h(t) \approx \Delta L(t)/L\) from a photodetector that counts shot-noise limited photons.
  If \(N_\gamma \propto T\) photons are collected over integration time \(T\), then the counting uncertainty scales as \(\sigma_{N} \sim \sqrt{N_\gamma}\).
  The fractional precision improves like \(\sigma_{N}/N_\gamma \sim 1/\sqrt{T}\), so the calibrated strain estimate achieves pointwise uncertainty that falls as \(T^{-1/2}\) when other noises are stationary.
  In practice one uses matched filtering, but the same exposure-time scaling appears in the shot-noise term of the noise power spectral density.
  \item \emph{Weak lensing shear from many galaxies.}
  Shape noise per galaxy is \(\sigma_e \sim 0.3\), so stacking \(N\) independent galaxy images gives shear uncertainty \(\sigma_\gamma \approx \sigma_e/\sqrt{2N}\).
  The \(1/\sqrt{N}\) falloff is the same habit: average many discrete events or samples and the estimator variance shrinks predictably.
\end{enumerate}

These illustrate aggregate convergence as per §\ref{subsec:poisson}.




\section{Short note on two layer wording}\label{sec:tlm}
It is often convenient to speak of a rule layer and an execution layer.
\begin{itemize}
  \item Rule layer (outside time): arbitrarily refinable mathematical descriptions, exact equations, symmetries, and conservation laws.
  \item Execution layer (inside a universe): finite information, discrete detection events, delays, and estimates that converge to the rule predictions on appropriate scales.
\end{itemize}
On this wording, slogans like ``no split detections, smooth expectations'' become precise: indivisible token events at readout, smooth parameters in the code.

\section{Objections and replies}\label{sec:objections}
\textbf{Objection.} Smooth manifolds quantify over uncountably many points, so the world must be infinitely divisible. \\
\textbf{Reply.} The manifold is a code. Its quantifiers live in math. Empirical access is only through finite experiments. What matters is stable convergence of estimates, not ontic infinitesimals.

\medskip
\noindent
\textbf{Objection.} If detectors are discrete, you cannot explain continuous phenomena. \\
\textbf{Reply.} Large \(N\) aggregates of discrete events yield smooth estimates. This is how spectra, images, and interferometry already work, as formalized in \S\ref{subsec:poisson}.

\medskip
\noindent
\textbf{Objection.} This is philosophy, not physics. \\
\textbf{Reply.} The thesis makes scaling commitments: how errors shrink with resources; how singularities mark domain limits; how symmetry violations line up with broken premises. These are empirical habits.

\medskip
\noindent
\textbf{Objection.}QM wavefunctions are continuous. \\
\textbf{Reply.}  Wavefunctions are codes; measurements are discrete collapses or branches (in Copenhagen or Everett interpretations, respectively)\cite{QFT}.



\section{Conclusion}\label{sec:conclusion}
Only mathematics carries completed infinities. Real systems carry finite information. Physics, on this view, studies exact rules and their finite executions. SR/GR remain intact as smooth codes that compress and predict aggregates of discrete events. Where rules and execution disagree beyond expected bounds, we have either found a missing rule or crossed a domain boundary.

\section*{Acknowledgments}
For helpful nudges and persistent challenges from colleagues, students, and commenters who kept asking for a clean split between rules and executions.

\begin{thebibliography}{11}
% Shannon 1948 (both parts with DOIs)
\bibitem{Shannon1948}
C. E. Shannon, ``A Mathematical Theory of Communication,'' \emph{Bell System Technical Journal}
\textbf{27} (1948) 379--423; 623--656.
Part I DOI: \href{https://doi.org/10.1002/j.1538-7305.1948.tb01338.x}{10.1002/j.1538-7305.1948.tb01338.x};
Part II DOI: \href{https://doi.org/10.1002/j.1538-7305.1948.tb00917.x}{10.1002/j.1538-7305.1948.tb00917.x}.

% Wald GR full citation (book, no DOI; include ISBN)
\bibitem{WaldGR}
R. M. Wald, \emph{General Relativity} (University of Chicago Press, 1984).
ISBN 978-0-226-87027-4.

% Peskin & Schroeder (book; ISBN)
\bibitem{QFT}
M. E. Peskin and D. V. Schroeder, \emph{An Introduction to Quantum Field Theory} (Westview, 1995).
ISBN 978-0-201-50397-5.

% Bekenstein bound (add DOI)
\bibitem{BekensteinBound}
J. D. Bekenstein, ``Universal upper bound on the entropy-to-energy ratio for bounded systems,''
\emph{Phys. Rev. D} \textbf{23} (1981) 287--298.
DOI: \href{https://doi.org/10.1103/PhysRevD.23.287}{10.1103/PhysRevD.23.287}.

% Le Cam (book; DOI available)
\bibitem{LeCam}
L. Le Cam, \emph{Asymptotic Methods in Statistical Decision Theory} (Springer, 1986).
DOI: \href{https://doi.org/10.1007/978-1-4612-4946-7}{10.1007/978-1-4612-4946-7}.

% Van Trees & Bell (book; ISBN)
\bibitem{vanTrees}
H. L. Van Trees and K. L. Bell, \emph{Detection, Estimation, and Modulation Theory, Part I}, 2nd ed. (Wiley, 2013).
ISBN 978-1-118-64546-2.

% Hayashi (book; DOI available)
\bibitem{Hayashi}
M. Hayashi, \emph{Quantum Information Theory}, 2nd ed. (Springer, 2017).
DOI: \href{https://doi.org/10.1007/978-3-662-49725-8}{10.1007/978-3-662-49725-8}.

% Helstrom (book; DOI)
\bibitem{Helstrom}
C. W. Helstrom, \emph{Quantum Detection and Estimation Theory} (Academic Press, 1976).
DOI: \href{https://doi.org/10.1016/C2013-0-01891-2}{10.1016/C2013-0-01891-2}.

% Kay (book; ISBN)
\bibitem{Kay}
S. M. Kay, \emph{Fundamentals of Statistical Signal Processing, Volume I: Estimation Theory} (Prentice Hall, 1993).
ISBN 978-0-13-345711-7.

% Landau-Pollak-Slepian line (keep as-is or update if needed; PSWF papers have no single DOI per part)
\bibitem{PollakSlepian}
H. J. Landau and H. O. Pollak, ``Prolate spheroidal wave functions, Fourier analysis and uncertainty II,''
\emph{Bell System Technical Journal} \textbf{40} (1961) 65--84.

% Loudon (book; ISBN)
\bibitem{Loudon}
R. Loudon, \emph{The Quantum Theory of Light}, 3rd ed. (Oxford University Press, 2000).
ISBN 978-0-19-850177-2.

\end{thebibliography}

\end{document}
```

</details>



---
{% endraw %}
