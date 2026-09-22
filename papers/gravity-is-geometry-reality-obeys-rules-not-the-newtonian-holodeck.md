---
layout: default
title: '[2025] Gravity is Geometry. Reality Obeys Rules. Not the Newtonian Holodeck.'
description: 'Publication metadata and archived raw LaTeX source by John C. W. McKinley.'
permalink: /papers/gravity-is-geometry-reality-obeys-rules-not-the-newtonian-holodeck/
paper: true
---
{% raw %}
# [2025] Gravity is Geometry. Reality Obeys Rules. Not the Newtonian Holodeck.
*   **DOI:** [10.5281/zenodo.17197557](https://doi.org/10.5281/zenodo.17197557)
*   **Date:** 25 September 2025

<details markdown="1">
<summary><b>Click to view Raw LaTeX Source</b></summary>

```latex
% GravityIsGeometry_full.tex
\documentclass[12pt]{article}

% ---------- Fonts & Basics ----------
\usepackage[utf8]{inputenc}
\usepackage[T1]{fontenc}
\usepackage{lmodern}
\usepackage{microtype}

% ---------- Math ----------
\usepackage{amsmath,amssymb}
\usepackage{mathtools} % for \coloneqq

% ---------- Layout ----------
\usepackage{geometry}
\geometry{margin=1in}
\usepackage{titlesec}
\usepackage{enumitem} % compact lists
\usepackage{float}
\usepackage{tikz}
\usetikzlibrary{calc}

% ---------- Links & References ----------
\usepackage{hyperref}
\hypersetup{
  colorlinks=true,
  linkcolor=blue,
  urlcolor=blue,
  citecolor=blue
}
\usepackage{cleveref}

% ---------- Headers & Title ----------
\usepackage{authblk}
\usepackage{fancyhdr}
\usepackage{orcidlink}

\pagestyle{fancy}
\fancyhf{}
\lhead{Gravity is Geometry}
\rhead{\thepage}

\title{Gravity is Geometry. Reality Obeys Rules. Not the Newtonian Holodeck.}
\author{John C. W. McKinley\orcidlink{0009-0005-7097-5035}\\Independent Researcher}
\date{September 24, 2025}

\titleformat{\section}{\large\bfseries}{\thesection.}{0.5em}{}
\titleformat{\subsection}{\normalsize\bfseries}{\thesubsection.}{0.5em}{}

\begin{document}
\maketitle

\begingroup
  \footnotetext[0]{This version published at
  \href{https://doi.org/10.5281/zenodo.17197557}{https://doi.org/10.5281/zenodo.17197557}.}
\endgroup


\begin{abstract}
General Relativity replaces the Newtonian force story with a geometric law: mass and energy tell spacetime how to curve; spacetime tells masses how to move. By ``Newtonian holodeck'' we mean a patched-together force picture that relies on local mechanisms and compensations rather than a unified rule set. Treating gravity as geometry is not cosmetic; it commits us to the thesis that reality is governed by coherent, simple, and falsifiable rules. We review the geometric formulation \cite{einstein1915,mtw1973}, highlight what it buys us conceptually and empirically, note the remaining ``why,'' and sketch how the Timeless Light Model (TLM) can supply an upstream account while leaving GR's empirical content intact \cite{mckinley_stoppretend,mckinley_foundations}.
\end{abstract}

\section{Introduction}
\label{sec:intro}
The textbook slogan is compact: ``Gravity is geometry. Mass and energy curve spacetime; free objects follow that curvature.'' One reading treats geometry as bookkeeping for a mysterious force. Another treats geometry as an ontological rule: the world follows mathematical constraints that are both simple and generative. On that reading, we accept a radical thesis: reality follows clear, simple rules in the sense of consistent geometric constraints, not a Newtonian holodeck patched from local forces and external interventions. For the standard formulation and textbook development, see \cite{einstein1915,mtw1973}.

\section{General Relativity as a Rule System}
\label{sec:GR}
Einstein's field equations can be written
\begin{equation}
\label{eq:efe}
G_{ab} + \Lambda g_{ab} = \frac{8\pi G}{c^4} T_{ab},
\end{equation}
where \(G_{ab}\) is the Einstein tensor, \(g_{ab}\) the metric, \(\Lambda\) the cosmological constant, and \(T_{ab}\) the stress--energy tensor. Test bodies follow geodesics:
\begin{equation}
\label{eq:geodesic}
\frac{D u^a}{D \tau} = 0,
\end{equation}
with 4--velocity \(u^a\) and covariant derivative \(D/D\tau\) along the worldline. The standard derivations are given in \cite{mtw1973}.

Read syntactically, GR says: solve for \(g_{ab}\) from the field equations, then compute geodesics. Read ontologically, GR is a compact rulebook:
\begin{enumerate}[leftmargin=*, itemsep=2pt, topsep=2pt]
\item A spacetime manifold with metric \(g_{ab}\) provides the arena.
\item Matter--energy sets geometry via a local differential relation \(G_{ab}\propto T_{ab}\).
\item Free motion is geodesic motion in that geometry.
\end{enumerate}
As a visual mnemonic, \cref{fig:curvature} schematizes geodesic motion on a curved spacetime slice.

\begin{figure}[htbp]
\centering
\begin{tikzpicture}[scale=0.8]
  % Curved grid (schematic)
  \foreach \x in {-3,-2.5,...,3} {
    \draw[gray!60] plot[domain=-3:3,samples=60] (\x, {(\x*\x)/18 + \x/24});
  }
  \foreach \y in {-3,-2.5,...,3} {
    \draw[gray!60] plot[domain=-3:3,samples=60] ({\y}, {(\y*\y)/18 + \y/24});
  }
  % A geodesic (schematic)
  \draw[very thick] plot[domain=-2.5:2.5,samples=60] ({\x}, {0.12*\x*\x - 0.1*\x});
\end{tikzpicture}
\caption{Schematic of curved spacetime with a geodesic.}
\label{fig:curvature}
\end{figure}

\section{Brief Overview of the Timeless Light Model (TLM)}
\label{sec:tlm-overview}
TLM posits an ontologically senior \emph{Quantum Platform} (QP) that issues timeless instruction primitives, and a \emph{Spacetime Deployment Frame} (SDF) that renders those instructions with delays; observed GR phenomena are the rendered consequences. Cornerstone statements include a causal rendering law and a mass--delay law; see \cite{mckinley_foundations,mckinley_stoppretend} for axioms, glossary, and predictions. This paper uses TLM conservatively: as an upstream explanation that preserves GR's empirical equations while proposing \emph{why} geometric rules hold.

\section{Why Geometry Beats the Newtonian Holodeck}
\label{sec:why}
By a ``Newtonian holodeck'' we mean a worldview where dynamics come from local forces, external compensations, or elaborate mechanisms that fail to unify disparate phenomena. The geometric reading has several virtues:
\begin{itemize}[leftmargin=*, itemsep=2pt, topsep=2pt]
\item \textbf{Explanatory compression:} A small set of equations explains many phenomena.
\item \textbf{Universality:} The same structure governs planetary motion and cosmology.
\item \textbf{Predictive novelty:} Frame dragging and gravitational waves emerged from geometry, not from inverse--square heuristics \cite{mtw1973}.
\item \textbf{Falsifiability:} Ray--bundle behavior, waveform phases, and energy conditions provide sharp tests of the geometric account \cite{mtw1973}.
\item \textbf{Remaining ``why'':} ``Mass tells space how to curve'' still invites a deeper origin story. TLM narrows this by positing the Quantum Platform (QP) as the source of rules, with the Spacetime Deployment Frame (SDF) as the rendered layer that enforces them.
\end{itemize}

\section{Where an Upstream Account Might Fit: The TLM Sketch}
\label{sec:TLM}
Within TLM:
\begin{itemize}[leftmargin=*, itemsep=2pt, topsep=2pt]
\item QP is ontologically senior and encodes discrete instruction primitives.
\item The SDF renders those instructions with delay parameters so that effective fields and metric behavior appear.
\item Observable GR phenomena are emergent consequences of deployment rules and delay structure.
\end{itemize}
Thus TLM does not alter GR's equations but offers a candidate explanation for why a local relation equivalent to \(G_{ab}\propto T_{ab}\) holds \cite{mckinley_foundations,mckinley_stoppretend}.

\section{Falsifiable Suggestions}
\label{sec:falsify}
To be scientifically respectable, an upstream model must propose tests. Examples include:
\begin{enumerate}[leftmargin=*, itemsep=2pt, topsep=2pt]
\item Horizon--scale residual phase shifts in gravitational--wave templates relative to post--Newtonian baselines, predicted from deployment--delay structure.
\item Non--Gaussian tails in cosmological observables associated with discrete instruction deployment.
\item Quantum--optical pairing constraints consistent with TLM's no--orphan--quanta claims.
\end{enumerate}
Quantitative estimates are deferred to a dedicated follow--up.

\section{Glossary}
\label{sec:glossary}
\begin{itemize}[leftmargin=*, itemsep=2pt, topsep=2pt]
\item \textbf{QP (Quantum Platform):} Ontologically senior, timeless instruction source in TLM \cite{mckinley_foundations}.
\item \textbf{SDF (Spacetime Deployment Frame):} The rendered layer where instructions appear as classical fields, geometry, and observables \cite{mckinley_stoppretend}.
\item \textbf{Geodesic:} Curve that extremizes proper time (timelike) or is affinely parameterized (null), satisfying \(\frac{D u^a}{D \tau}=0\) \cite{mtw1973}.
\item \textbf{Einstein Field Equations (EFE):} \cref{eq:efe}, relating geometry and stress--energy \cite{einstein1915}.
\end{itemize}

\section{Conclusion}
\label{sec:conclusion}
Interpreting gravity as geometry recognizes that reality follows a concise rule set. That narrows the ``why'' problem rather than proliferating ad hoc mechanisms. Upstream accounts like TLM may be valuable precisely because they leave GR's geometric rules intact while proposing a testable origin story for those rules \cite{mckinley_foundations}.

\appendix
\section{Rigorous Derivations (Sketches)}
\label{sec:appendix-derivations}

\subsection{Einstein Equations from the Hilbert Action}
\label{sec:hilbert}
Consider the action
\[
S[g,\Psi] \;=\; \frac{c^3}{16\pi G}\int (R - 2\Lambda)\sqrt{-g}\, d^4x \;+\; S_{\text{m}}[g,\Psi],
\]
where \(R\) is the Ricci scalar and \(S_{\text{m}}\) the matter action depending on fields \(\Psi\). Varying w.r.t. \(g^{ab}\) and using \(\delta(\sqrt{-g}) = -\tfrac{1}{2}\sqrt{-g}\,g_{ab}\delta g^{ab}\), and \(\delta R = R_{ab}\delta g^{ab} + \text{(total derivative)}\), yields
\[
\delta S = \frac{c^3}{16\pi G}\int (G_{ab} + \Lambda g_{ab})\,\delta g^{ab}\,\sqrt{-g}\, d^4x
\;-\; \frac{1}{2}\int T_{ab}\,\delta g^{ab}\,\sqrt{-g}\, d^4x,
\]
with
\[
T_{ab} \coloneqq -\tfrac{2}{\sqrt{-g}}\tfrac{\delta S_{\text{m}}}{\delta g^{ab}}.
\]
Setting \(\delta S=0\) for arbitrary \(\delta g^{ab}\) gives the Einstein field equations \(\cref{eq:efe}\).
See \cite[Chs.~17--21]{mtw1973} for a full derivation.

\subsection{Geodesic Equation from the Variational Principle}
\label{sec:geodesic-derivation}
For a timelike worldline \(x^a(\lambda)\) with proper time \(d\tau^2 = -g_{ab}\,dx^a dx^b/c^2\), extremize
\[
S[x] \;=\; \int d\tau \;=\; \int \sqrt{-\frac{g_{ab}\,\dot{x}^a\dot{x}^b}{c^2}}\, d\lambda.
\]
The Euler--Lagrange equations yield
\[
\ddot{x}^a + \Gamma^{a}_{\;\;bc}\,\dot{x}^b\dot{x}^c = f(\lambda)\,\dot{x}^a,
\]
which, upon reparameterization to proper time, reduces to \(\ddot{x}^a + \Gamma^{a}_{\;\;bc}\,\dot{x}^b\dot{x}^c=0\), i.e., \(\frac{D u^a}{D\tau}=0\) \(\cref{eq:geodesic}\). See \cite[Chs.~6--7]{mtw1973}.

\subsection{Null Worldlines and Vanishing Proper Time}
\label{sec:null}
For null curves, \(ds^2=0\), so the proper time increment vanishes, \(\Delta \tau = 0\). Such worldlines are affinely parameterized, and massless excitations follow null geodesics \cite{einstein1915,mtw1973}. This standard result underwrites the ``timeless photon'' premise used elsewhere in TLM \cite{mckinley_foundations}.

% ---------- Manual Bibliography ----------
\begin{thebibliography}{9}


% --- Replace your \bibitem{einstein1915} with this ---
\bibitem{einstein1915}
A.~Einstein,
``Die Feldgleichungen der Gravitation,''
\textit{Sitzungsberichte der Königlich Preussischen Akademie der Wissenschaften (Berlin)} (1915), pp.~844--847.
Available at the Einstein Papers Project: \href{https://einsteinpapers.press.princeton.edu/vol6-doc/433}{einsteinpapers.press.princeton.edu/vol6-doc/433}.



\bibitem{mtw1973}
C.~W.~Misner, K.~S.~Thorne, J.~A.~Wheeler,
\textit{Gravitation}.
W. H. Freeman and Company (1973).
ISBN: 978--0691177793.

\bibitem{mckinley_stoppretend}
J.~C.~W.~McKinley,
\textit{Stop Pretending General Relativity Is Conservative: Why Timeless Models Deserve a Seat at the Table}.
Zenodo (2025).
DOI: \href{https://doi.org/10.5281/zenodo.16261059}{10.5281/zenodo.16261059}.

\bibitem{mckinley_foundations}
J.~C.~W.~McKinley,
\textit{Foundational Equations and Axiomatic Structure of the Timeless Light Model: A Synthesis Across Sixty Papers and Working Notes}.
Zenodo (2025).
DOI: \href{https://doi.org/10.5281/zenodo.16187719}{10.5281/zenodo.16187719}.

\end{thebibliography}

\end{document}

```

</details>

---
{% endraw %}
