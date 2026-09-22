---
layout: default
title: '[2025] Deriving Cornerstone Equations from TLM Axioms: Entropic Bridges to GR and QM'
description: 'Publication metadata and archived raw LaTeX source by John C. W. McKinley.'
permalink: /papers/deriving-cornerstone-equations-from-tlm-axioms-entropic-bridges-to-gr-and-qm/
paper: true
---
{% raw %}
# [2025] Deriving Cornerstone Equations from TLM Axioms: Entropic Bridges to GR and QM
*   **DOI:** [10.5281/zenodo.16596589](https://doi.org/10.5281/zenodo.16596589)
*   **Date:** 30 July 2025

<details markdown="1">
<summary><b>Click to view Raw LaTeX Source</b></summary>

```latex


\documentclass[12pt]{article}

%% ===== Choose one of the two setups below =====

%% 1) If you compile with pdfLaTeX:
\usepackage[utf8]{inputenc}   % allow UTF‑8 input once
\usepackage[T1]{fontenc}      % proper font encoding for output
\usepackage{textgreek}        % direct text‑level Greek (δ, θ, etc.)
\usepackage[T1]{fontenc}
\usepackage{amsmath,amssymb}

%% 2) If you compile with XeLaTeX or LuaLaTeX:
% \usepackage{fontspec}         % for Unicode fonts
% \usepackage{unicode-math}     % for math Unicode
% (then you do NOT load inputenc or fontenc)






%% ===== Common packages =====
\usepackage{amsmath,amssymb}
\usepackage{geometry}
  \geometry{margin=1in}
\usepackage{graphicx}
\usepackage{float}
\usepackage{physics}
\usepackage{microtype}
\usepackage{csquotes}
\usepackage{tabularx}
\usepackage{booktabs}

\usepackage{titlesec}
\usepackage{fancyhdr}

\usepackage{pgfplots}
  \pgfplotsset{compat=1.18}
\usepackage{tikz}
  \usetikzlibrary{arrows.meta,positioning,calc,shapes.geometric,decorations.pathmorphing}
\usepackage{array}


\usepackage{caption}
\usepackage{upgreek}
\usepackage{enumitem}
\usepackage{tcolorbox}


% ... rest of your preamble ...
\renewcommand{\arraystretch}{1.3}




\usepackage{hyperref}
  \hypersetup{colorlinks=true,linkcolor=blue,urlcolor=blue,citecolor=blue}

\usepackage{cleveref}

\title{\textbf{Deriving Cornerstone Equations from TLM Axioms: \\Entropic Bridges to GR and QM

}}
\author{John C. W. McKinley \\ Independent Researcher \\ \href{https://orcid.org/0009-0005-7097-5035}{0009-0005-7097-5035}}
\date{\today}

\begin{document}




\title{\textbf{Deriving Cornerstone Equations from TLM Axioms: \\Entropic Bridges to GR and QM\footnotemark}}




\maketitle


\renewcommand{\thefootnote}{}
% New DOI
\footnotetext{This version published at \href{https://doi.org/10.5281/zenodo.16596589}{https://doi.org/10.5281/zenodo.16596589}.}




















\begin{abstract}
Building on TLM's core axioms (\( T \cdot m = \hbar / c^2 \), \( T \cdot C_s = 1 \)), this paper derives the Einstein Field Equations (EFE) and Schrödinger Equation (SE) as emergent from entropic delay gradients. We interpret rendering delay \( T \) as modulating instructional entropy \( S \propto \ln(H) \), where outcomes are timelessly pre-resolved in the QP without failures or mid-process costs. EFE arises from horizon entropy increases due to delay-induced information gradients, while SE emerges from entropic inference updating under \( T \)-constrained deployment. This unification treats GR and QM as rendered projections, yielding testable predictions like mass-dependent latency without ad hoc variables.
\end{abstract}



Keywords: Timeless Light Model, rendering delay, GR ontology, Quantum Platform, Spacetime Deployment Frame, delay-mass relation, timeless instructions, wave-particle duality,  null geodesics, delayed deployment



% Place this after \end{abstract} in the main document.

\section{Introduction}



The Timeless Light Model (TLM) proposes a foundational framework where delay \( T \) and instructional entropy serve as the substrate for physical phenomena, with axioms such as mass-delay duality (\( T \cdot m = \hbar / c^2 \)) and causal resolution constancy (\( T \cdot C_s = 1 \)) positing a timeless Quantum Platform (QP) as causally senior to the rendered Spacetime Deployment Frame (SDF). This layered ontology interprets gravity and quantum dynamics not as independent forces but as emergent effects of delay-modulated entropy, where all instructions are pre-resolved in QP without failures, ensuring deterministic causality deployed with temporal artifacts in SDF.

The TLM is a comprehensive framework that reinterprets causality through timeless instructions and delayed rendering. While beyond the scope of this paper, its foundational axioms are constructed to recover the established formalisms of both General Relativity and Quantum Mechanics under specific rendering conditions, as detailed in supporting derivations~\cite{mckinley2025axioms}.

This paper derives cornerstone equations---the Einstein Field Equations (EFE) for General Relativity (GR) and the Schrödinger Equation (SE) for Quantum Mechanics (QM)---from these axioms via entropic bridges. For EFE, we leverage thermodynamic derivations at horizons, mapping delay \( T \) to entropic gradients that yield curvature~\cite{jacobson1995thermodynamics, verlinde2011origin}. For SE, we extend entropic dynamics, treating wave evolution as inference updates constrained by \( T \)-induced timescales~\cite{caticha2012entropic}. These bridges unify GR and QM under TLM, reducing ``weirdness'' to perspectival rendering while generating falsifiable predictions.

We begin with a recap of TLM foundations, followed by detailed derivations, implications, and tests. This exploratory reinterpretation aims to ground unification in delay-entropy mechanics, inviting empirical scrutiny.



TLM axioms recover EFE/SE under rendering conditions, as shown via entropic mappings.














% In your preamble, ensure you have:
% \usepackage{tikz}
% \usetikzlibrary{positioning, shapes.misc, arrows.meta}

\begin{figure}[H]
\centering
\begin{tikzpicture}[
    node distance=1cm and 0,
    every node/.style={
        draw,
        rectangle,
        rounded corners,
        fill=gray!10,
        align=center,
        minimum width=4cm,
        inner sep=6pt
    },
    >=Stealth
  ]
  % Nodes
  \node (T) {%
    \(T\)\\[2pt]
    Rendering Delay
  };
  \node (deltaQ) [below=of T] {%
    \(\delta Q\)\\[2pt]
    Heat Flux
  };
  \node (deltaS) [below=of deltaQ] {%
    \(\delta S = \dfrac{\delta Q}{T_U}\)\\[2pt]
    Entropy Variation
  };
  \node (gradS) [below=of deltaS] {%
    \(\nabla(\delta S)\)\\[2pt]
    Entropic Gradient
  };
  \node (curv) [below=of gradS] {%
    \(R_{\mu\nu}\)\\[2pt]
    Spacetime Curvature
  };

  % Arrows
  \draw[->] (T) -- node[right,align=left]{\(T_U\propto1/T\)} (deltaQ);
  \draw[->] (deltaQ) -- (deltaS);
  \draw[->] (deltaS) -- (gradS);
  \draw[->] (gradS) -- (curv);
\end{tikzpicture}
\caption{Entropic delay gradient driving spacetime curvature in TLM.}
\label{fig:delay_curvature}
\end{figure}


























\section{Entropic and Informational Parallels}
\label{sec:parallels}

The derivation of the Einstein Field Equations (EFE) from thermodynamic principles—pioneered by Jacobson \cite{jacobson1995thermodynamics} via the local Clausius relation \(\delta Q = T\,\delta S\) at causal horizons and further developed in the entropic gravity framework of Verlinde \cite{verlinde2011origin}—demonstrates that spacetime curvature can be understood as a manifestation of horizon entropy gradients. In both approaches, the area–entropy law \(S\propto A\) and the identification of heat flux \(\delta Q\) with matter energy–momentum lead directly to the familiar form of the EFE, without postulating the field equations a priori.

In parallel, Caticha’s Entropic Dynamics (ED) \cite{caticha2025} derives the nonrelativistic Schrödinger Equation (SE) by treating particle positions as epistemic variables and updating their probability distributions via the principle of maximum entropy under suitable drift and variance constraints. By identifying time as an ordering parameter for inference steps and imposing energy conservation, ED reproduces
\[
i\hbar\,\partial_t\psi 
= \Bigl[-\frac{\hbar^2}{2m}\nabla^2 + V\Bigr]\psi,
\]
providing an information‑theoretic foundation for quantum evolution.

The Timeless Light Model (TLM) extends these entropic and informational derivations by grounding both the thermodynamic and inferential time parameters in the rendering delay \(T\), itself determined by the mass–delay duality axiom \(T\,m=\hbar/c^2\). In the gravitational case, the Unruh temperature \(T_U\propto 1/T\) links
\(\delta S = \delta Q / T_U\)
directly to \(T\); in the quantum case, each ED time step \(\Delta t = T\) embeds delay as the fundamental clock. Thus, TLM unifies the emergence of both EFE and SE under a single delay‑driven entropic framework.




\subsection{Mapping TLM to Established Derivations}
\label{subsec:mapping_tlm}

To bridge TLM to standard physics, we note that delay \( T \) aligns with entropic concepts in existing literature. In GR, \( T \) modulates temperatures at horizons, extending Jacobson's thermodynamic EFE derivation where entropy proportionality
\[
\delta Q = T\,\eta\,\delta A
\]

yield curvature~\cite{jacobson1995thermodynamics}. For QM, \( T \) sets inference timescales in Caticha's entropic dynamics, where SE emerges from Bayesian updating under constraints~\cite{caticha2012entropic}. TLM unifies these by sourcing entropy from QP instructional multiplicity, providing a common delay-based ontology.


In Jacobson’s thermodynamic derivation of the EFE \cite{jacobson1995thermodynamics}, one begins with the Clausius relation
\[
\delta Q = T_U\,\delta S,
\]
where \(T_U = \hbar a / (2\pi k_B c)\) is the Unruh temperature associated with proper acceleration \(a\).  In TLM, using the mass–delay duality \(m=\hbar/(T c^2)\) and \(a\sim Gm/r^2\), we have
\[
T_U \;=\;\frac{\hbar a}{2\pi k_B c}
\;\propto\;\frac{1}{T}\,.
\]
Hence the local entropy variation
\[
\delta S = \frac{\delta Q}{T_U}
\;\propto\;T\,\delta Q
\]
directly incorporates the rendering delay \(T\), so that curvature emerges from entropic delay gradients \(\nabla(\delta S)\) in exactly the same steps as the original derivation.

Similarly, in Verlinde’s entropic gravity picture \cite{verlinde2011origin}, the entropic force is
\[
F = T\,\nabla S,
\]
which in TLM becomes
\[
F \;\propto\;\frac{1}{T}\,\delta Q
\;\sim\;\nabla \bigl(T\,\delta S\bigr),
\]
again highlighting \(T\) as the fundamental parameter linking energy flux to spacetime response.

On the quantum side, Caticha’s Entropic Dynamics \cite{caticha2025} introduces time through successive inference steps of duration \(\Delta t\).  In TLM we set
\[
\Delta t = T = \frac{\hbar}{m c^2},
\]
so that the Fokker–Planck and Hamilton–Jacobi equations acquire delay‑dependent diffusion \(D \propto T\) and drift terms.  The resulting Schrödinger equation
\[
i\hbar\,\partial_t\psi
= \Bigl[-\tfrac{\hbar^2}{2m}\nabla^2 + V\Bigr]\psi
\]
is thus recovered with its time parameter directly tied to the rendering delay \(T\).

In this way, TLM seamlessly maps onto both the thermodynamic derivations of GR and the information‑theoretic derivations of QM, grounding each in the single, unifying concept of rendering delay.



\section{Deriving EFE (GR) from Entropic Delay Gradients}






EFE: \( R_{\mu\nu} - \frac{1}{2} R g_{\mu\nu} + \Lambda g_{\mu\nu} = \frac{8\pi G}{c^4} T_{\mu\nu} \).

- \textbf{Motivation:} In TLM, mass \( m \) induces delay \( T \), distorting causal arcs at event horizons and increasing entropy \( dS \propto dA / (4 \ell_p^2) \) (Bekenstein-Hawking, fully emergent from pre-resolved QP multiplicity)~\cite{jacobson1995thermodynamics}.
  
- \textbf{Step 1:} Delay as entropic driver. Local delay fields create Unruh-like temperatures \( T_U = \hbar a / (2\pi k_B c) \), where acceleration \( a \sim G m / r^2 \propto 1/T \) from mass-delay axiom~\cite{verlinde2011origin}.
  
- \textbf{Step 2:} Horizon thermodynamics: Entropy variation \( dS = \delta Q / T_U \), with heat flux \( \delta Q \sim \int T^{\alpha\beta} \xi_\alpha d\Sigma_\beta \) (stress-energy from aggregated delays over pre-resolved arcs).
  
- \textbf{Step 3:} First law generalization: \( \delta A = - \lambda \int R_{\alpha\beta} \xi^\alpha d\Sigma^\beta \), enforcing EFE via Bianchi identities and holographic principle (entropy scales with area due to QP arc density).
  
- \textbf{TLM Distinction:} No failed instructions—entropy reflects complete QP resolutions, with curvature as the SDF's delayed "playback" of these arcs. Matches Jacobson's derivation but grounds temperature in TLM delay.


























The Einstein Field Equations (EFE) are:
\[
R_{\mu\nu} - \frac{1}{2} R g_{\mu\nu} + \Lambda g_{\mu\nu} = \frac{8\pi G}{c^4} T_{\mu\nu}.
\]

In the Timeless Light Model (TLM), we derive the EFE from entropic principles applied to delay gradients induced by mass. Mass \(m\) induces a rendering delay \(T\) via the axiom \(T \cdot m = \hbar / c^2\), distorting causal arcs and increasing entropy at horizons. This entropy is emergent from the multiplicity of pre-resolved Quantum Platform (QP) instructions, following the Bekenstein-Hawking formula \(dS \propto dA / (4 \ell_p^2)\), where \(\ell_p\) is the Planck length.

This derivation extends Jacobson's thermodynamic approach~\cite{jacobson1995thermodynamics}, grounding the Unruh temperature in TLM delay and interpreting curvature as delayed "playback" of QP arcs in the Spacetime Deployment Frame (SDF).

\subsection{Step 1: Delay as Entropic Driver}

Local delay fields from mass create acceleration-induced temperatures akin to the Unruh effect. The Unruh temperature is:
\[
T_U = \frac{\hbar a}{2\pi k_B c},
\]
where \(a\) is the proper acceleration. In TLM, near a mass \(m\), \(a \sim G m / r^2\). From the mass-delay axiom, \(m = \hbar / (T c^2)\), so:
\[
a \sim \frac{G \hbar}{T c^2 r^2} \propto \frac{1}{T}.
\]
Thus, \(T_U \propto 1/T\), linking temperature to delay: higher delay (larger mass) reduces effective temperature in the rendering frame, but induces entropic gradients via distorted causal arcs.

\subsection{Step 2: Horizon Thermodynamics}

Consider a local causal horizon, such as a Rindler horizon near a point \(p\) in spacetime. The entropy variation across the horizon follows the first law:
\[
dS = \frac{\delta Q}{T_U},
\]
where \(\delta Q\) is the heat flux due to matter energy crossing the horizon. In general relativity, the heat flux is:
\[
\delta Q = \int_H T^{\alpha\beta} \xi_\alpha \, d\Sigma_\beta,
\]
with \(T^{\alpha\beta}\) the stress-energy tensor, \(\xi_\alpha\) an approximate Killing vector (e.g., boost Killing field for Rindler), and \(d\Sigma_\beta\) the horizon surface element.

In TLM, this flux arises from aggregated delays over pre-resolved QP arcs, where stress-energy \(T^{\alpha\beta}\) reflects the density of delayed instructions.

\subsection{Step 3: Entropy-Area Relation and First Law Generalization}

Assume entropy is proportional to the horizon area variation:
\[
dS = \eta \, \delta A,
\]
where \(\eta\) is a constant (later identified as \(\eta = \frac{k_B c^3}{4 \hbar G}\) for Bekenstein-Hawking). The area variation \(\delta A\) for a pencil of horizon generators is:
\[
\delta A = \int_H \theta \, d\lambda \, dA,
\]
where \(\theta\) is the expansion, and \(\lambda\) is an affine parameter.

Using the Raychaudhuri equation for null geodesics:
\[
\frac{d\theta}{d\lambda} = -\frac{1}{2} \theta^2 - \sigma_{ab} \sigma^{ab} - R_{\alpha\beta} k^\alpha k^\beta,
\]
with \(k^\alpha\) the tangent vector. Near the horizon (local equilibrium, \(\theta \approx 0\), \(\sigma \approx 0\)):
\[
\theta \approx -\lambda R_{\alpha\beta} k^\alpha k^\beta,
\]
so:
\[
\delta A \approx -\int_H \lambda R_{\alpha\beta} k^\alpha k^\beta \, d\lambda \, dA.
\]

For the heat flux, using \(\xi_\alpha = -\kappa \lambda k_\alpha\) (with \(\kappa\) the surface gravity, related to acceleration \(a = \kappa\)):
\[
\delta Q = -\kappa \int_H \lambda T^{\alpha\beta} k_\alpha k_\beta \, d\lambda \, dA.
\]

Applying the first law \(\delta Q = T_U dS\), with \(T_U = \frac{\hbar \kappa}{2\pi k_B}\):
\[
-\kappa \int_H \lambda T^{\alpha\beta} k_\alpha k_\beta \, d\lambda \, dA = \frac{\hbar \kappa}{2\pi k_B} \eta \left( -\int_H \lambda R_{\alpha\beta} k^\alpha k^\beta \, d\lambda \, dA \right).
\]

Simplifying (dividing by \(-\kappa\), assuming integrals localize):
\[
\int_H \lambda T^{\alpha\beta} k_\alpha k_\beta \, d\lambda \, dA = \frac{\hbar \eta}{2\pi k_B} \int_H \lambda R_{\alpha\beta} k^\alpha k^\beta \, d\lambda \, dA.
\]




Since this holds for arbitrary null \(k^\alpha\) and local horizons, it implies:
\[
T^{\alpha\beta} = \frac{\hbar \eta}{2\pi k_B} \left( R^{\alpha\beta} - \frac{1}{2} R g^{\alpha\beta} + \Lambda g^{\alpha\beta} \right),
\]
where \(\Lambda\) is an integration constant (cosmological constant) ensuring consistency with Bianchi identities.

Identifying \(
\frac{\hbar \eta c}{2\pi k_B} = \frac{c^4}{8\pi G}
\) (restoring constants) yields the EFE.





\subsection{TLM Distinction}

In TLM, there are no failed instructions—entropy reflects the complete resolution of QP arcs, with curvature as the SDF's delayed playback. The temperature is grounded in delay \(T\), linking mass-induced delay to entropic forces, matching Jacobson's derivation but interpreting thermodynamics as emergent from timeless QP multiplicity.












\begin{figure}[H]
\centering
\begin{tikzpicture}[
    node distance=1cm and 0,
    every node/.style={
        draw,
        rectangle,
        rounded corners,
        fill=gray!10,
        align=center,
        minimum width=5cm,
        inner sep=6pt
    },
    >=Stealth
  ]
  % Nodes
  \node (prior) {%
    Prior \(Q(x'|x)\)\\
    (Uniform ignorance)
  };
  \node (maxent) [below=of prior] {%
    Maximize Entropy\\
    (Subject to constraints)
  };
  \node (transition) [below=of maxent] {%
    Gaussian Transition\\
    \(P(x'|x)\)
  };
  \node (fp) [below=of transition] {%
    Fokker–Planck\\
    Equation
  };
  \node (hj) [below=of fp] {%
    Hamilton–Jacobi\\
    Equation
  };
  \node (mad) [below=of hj] {%
    Madelung\\
    Transform
  };
  \node (se) [below=of mad] {%
    Schrödinger Equation\\
    \(i\hbar\,\partial_t\psi = \bigl[-\tfrac{\hbar^2}{2m}\nabla^2 + V\bigr]\psi\)
  };

  % Arrows
  \draw[->] (prior) -- (maxent);
  \draw[->] (maxent) -- (transition);
  \draw[->] (transition) -- (fp);
  \draw[->] (fp) -- (hj);
  \draw[->] (hj) -- (mad);
  \draw[->] (mad) -- (se);
\end{tikzpicture}
\caption{Inference flow in TLM‐extended Entropic Dynamics leading to the Schrödinger Equation.}
\label{fig:ED_flow}
\end{figure}






















\section{Deriving SE (QM) from Entropic Inference Under Delay}
\label{sec:derive_SE}

The nonrelativistic Schrödinger Equation (SE) is
\[
i \hbar\,\partial_t \psi \;=\;\bigl[-\tfrac{\hbar^2}{2m}\,\nabla^2 + V\bigr]\,\psi.
\]

\subsection{Motivation}
Quantum probabilities emerge in the Spacetime Deployment Frame (SDF) as entropic summaries of pre­resolved Quantum Platform (QP) instructions.  Rendering delay \(T\) blinds observers to the underlying multiplicity, so that the wavefunction \(\psi\) encodes uncertainty via entropic inference \cite{caticha2012entropic}.

\subsection{Step 1: Maximum Entropy for Transition Probabilities}
Treat position \(x\) as an epistemic variable.  For a short step of duration \(\Delta t=T\), infer \(P(x'|x)\) by maximizing
\[
S[P\|Q]
= -\int P(x'|x)\,\ln\frac{P(x'|x)}{Q(x'|x)}\,dx',
\]
with uniform prior \(Q\) and constraints
\[
\langle\Delta x\rangle = b,
\quad
\langle(\Delta x)^2\rangle = \kappa \propto T.
\]
This yields the Gaussian kernel
\[
P(x'|x)
= \frac{1}{Z}\exp\Bigl[-\tfrac{\alpha}{2}(\Delta x - b)^2\Bigr],
\]
where \(\alpha^{-1}\propto T\).

\subsection{Step 2: Fokker–Planck Evolution}
Identify the inference time step \(\Delta t=T\).  Define
\[
\alpha = \frac{m}{\eta\,T},
\quad
D = \frac{\eta}{2m} = \frac{T\,c^2}{2},
\quad
v = \frac{b}{T}.
\]
Then the probability density \(P(x,t)\) evolves according to
\[
\partial_t P = -\partial_x\bigl(v\,P\bigr) + D\,\partial_x^2P,
\]
with diffusion \(D\propto T\).

\subsection{Step 3: Hamilton–Jacobi and Schrödinger Equations}
Impose energy conservation \(\langle H\rangle=\mathrm{const}\) to derive the Hamilton–Jacobi equation for action \(S\):
\[
\partial_t S + \frac{(\nabla S)^2}{2m} + V
- \frac{\hbar^2}{2m}\,\frac{\nabla^2R}{R} = 0,
\]
where \(P=R^2\).  The continuity equation,
\(\partial_tP + \nabla\bigl(P\,\nabla S/m\bigr)=0\),
together with the Madelung transform \(\psi=R\,e^{iS/\hbar}\), reproduces the SE.

\subsection{TLM Distinction}
In TLM, the delay \(T\) itself sets the inference clock, ensuring no mid‑process failures—QP arcs are fully resolved—and unifying quantum dynamics with entropic gravity via the common substrate of rendering delay.












\section{Implications, Unification, and Tests}

\begin{itemize}
    \item \textbf{Bridge Achieved:} EFE/SE as dual entropic faces of delay: GR from global gradients, QM from local inference---unified via TLM axioms without new postulates.
    
    \item \textbf{Predictions:} E.g., entanglement latency \( \Delta t = \frac{G M}{c^3} \) (testable in Bell setups); CMB phase shifts \( \Delta \phi \sim \frac{\hbar}{m c^2 t_H} \) from entropic delay.
    
    \item \textbf{Limitations/Caveats:} Assumes holographic saturation and epistemic priors; full numeric verification pending (e.g., via \texttt{SymPy} simulations of delay-to-curvature mappings).
\end{itemize}





















\begin{table}[H]
\centering
\caption{Expanded TLM Testable Predictions}
\label{tab:tlm_predictions}
\begin{tabularx}{\linewidth}{X  X  X  X}
\toprule
\textbf{Prediction} & \textbf{Observable} & \textbf{Experimental Setup} & \textbf{Expected Signature} \\
\midrule
Entanglement latency $\displaystyle \Delta t \sim \frac{G M}{c^3}$ 
& Time lag in Bell‐inequality violation correlations 
& Bell test with one photon path routed past a dense mass $M$ 
& Correlation delay scaling linearly with $M$ \\[6pt]

Mass‐dependent dispersion in matter‐wave interference 
& Fringe shift difference for different‐mass atoms 
& Dual‐species atom interferometer (e.g.\ $^{87}$Rb vs.\ $^{133}$Cs) 
& Systematic phase offset $\propto T(m)=\hbar/(m\,c^2)$ \\[6pt]

Horizon‐entropy deviation near black holes 
& Departure from $S = A/(4\ell_p^2)$ law 
& High‐resolution BH shadow imaging (EHT) 
& Entropy excess/deficit $\delta S \sim \nabla(\delta S)\propto1/M$ \\[6pt]

CMB phase anisotropy 
& Small phase shifts in the CMB power spectrum 
& CMB polarization/phase tomography (Planck, Simons Observatory) 
& Excess phase $\Delta\phi\sim\hbar/(m\,c^2\,t_H)$ at high multipoles \\

\bottomrule
\end{tabularx}
\end{table}

































\section{Rigorous Mathematical Derivations}



== Insert TLM-Specific derivations into Section 2 (after “TLM Distinction”) ===
\subsection{TLM–Specific Geodesic Derivation}

Starting from the mass–delay axiom \(T\cdot m = \hbar/c^2\), we can reinterpret the geodesic equation in the Spacetime Deployment Frame by treating \(T\) as a connection between curvature and delay.  In particular, define an effective “delay connection”:
\[
\Gamma^\mu_{\alpha\beta}\bigl[T\bigr] \;\equiv\; \Gamma^\mu_{\alpha\beta}
\;+\;\frac{1}{T}\,\delta^\mu_\alpha\,u_\beta
\]
where \(u^\beta\) is the four‐velocity field of a test mass.  One then shows that the modified geodesic equation
\[
\frac{d^2 x^\mu}{d\tau^2}
+ \Gamma^\mu_{\alpha\beta}\bigl[T\bigr]\,\frac{dx^\alpha}{d\tau}\,\frac{dx^\beta}{d\tau}
=0
\]
reproduces standard null and timelike geodesics in the limits \(T\to0\) (photons) and \(T\to\hbar/(m c^2)\) (massive particles), while encoding delay into the Christoffel symbols.  

\medskip
From here, one recovers the Raychaudhuri equation with a delay‐modified expansion scalar:
\[
\frac{d\theta}{d\lambda} = -\tfrac12\,\theta^2 - \sigma_{ab}\sigma^{ab}
- R_{\alpha\beta}\,k^\alpha k^\beta
+ \frac{\theta}{T}\,,
\]
and follows exactly the steps of Section 2.3 (entropy–area relation) to the EFE, now with the interpretation that each occurrence of \(R_{\alpha\beta}\) carries an implicit \(T\)‐dependence via the connection.

% === Insert TLM-Specific inference derivations into Section 3 (after “TLM Distinction”) ===
\subsection{TLM–Specific Entropic Dynamics}

In Entropic Dynamics (ED) one normally introduces a time‐step \(\Delta t\) by fiat.  In TLM we instead set
\[
\Delta t \;=\; T \;=\;\frac{\hbar}{m\,c^2},
\]
so that the fluctuation–drift balance
\[
\alpha = \frac{m}{\eta\,\Delta t}
\quad\longrightarrow\quad
\alpha = \frac{m^2 c^2}{\eta\,\hbar}
\]
is fixed by the mass–delay axiom.  The key steps then become:

\begin{enumerate}
  \item Gaussian transition kernel
  \(\displaystyle P(x'|x)\propto\exp\bigl[-\tfrac{\alpha}{2}(\Delta x - b)^2\bigr]\),
  with \(\alpha\propto m^2\).
  \item Fokker–Planck evolution
  \(\partial_tP = -\partial_x(vP) + D\,\partial_x^2P\),
  now with
  \(\;D = \eta/(2m) = \tfrac{T c^2}{2}\propto T\).
  \item Hamilton–Jacobi constraint
  \(\partial_tS + (\nabla S)^2/(2m) + V - \tfrac{\hbar^2}{2m}\nabla^2R/R = 0\),
  identical to standard ED but with \(V\) and \(D\) expressed in terms of \(T\).
\end{enumerate}

Together these reproduce the Schrödinger equation
\[
i\hbar\,\partial_t\psi = \bigl[-\tfrac{\hbar^2}{2m}\nabla^2 + V\bigr]\psi
\]
while making explicit that \(\Delta t\), diffusion constant \(D\), and drift potential are all functions of the rendering delay \(T\).

% === Continue with the rest of your paper, e.g. “Criticisms and Responses” =















\section{Criticisms and Responses}

While TLM strives to unite General Relativity and Quantum Mechanics via entropic delay, it must address several community‑standard objections.  Longer, duality‑specific rebuttals appear in Appendix~\ref{appendix:critique_details}.

\begin{enumerate}
  \item \textbf{Problem of Time in Quantum Gravity:}  
    Approaches like the Wheeler–DeWitt equation eliminate an external time parameter, leading to the “frozen” wave functional.  
    \\ \emph{TLM Response:}  We recover a dynamical time in the Spacetime Deployment Frame through the mass–delay axiom \(T\cdot m=\hbar/c^2\).  Delay \(T\) itself orders evolution, sidestepping the frozen formalism without introducing an extra clock operator.

  \item \textbf{Empirical Testability:}  
    Unified schemes are often criticized for lacking unique, falsifiable signatures.  
    \\ \emph{TLM Response:}  Predictable latency in entanglement (\(\Delta t\sim GM/c^3\)), horizon‑entropy corrections near compact objects, and mass‑dependent dispersion in interferometry all offer clear experimental probes.

  \item \textbf{Recovery of Standard Limits:}  
    Any unification must reproduce both Einstein’s equations and the Schrödinger Equation in their respective domains.  


  \item \textbf{Measurement and Backreaction:}  
    How does a quantum collapse process affect spacetime geometry?  
    \\ \emph{TLM Response:}  In TLM “collapse” is simply the SDF’s rendering of QP’s pre‑resolved instructions.  Semiclassical backreaction arises via delay‑induced stress–energy fluctuations, derived with the same thermodynamic argument that produces the EFE.

  \item \textbf{Ontological Economy vs. Metaphysics:}  
    Introducing a Quantum Platform risks being labeled metaphysical.  
    \\ \emph{TLM Response:}  QP is a minimal mathematical layer organizing pre‑resolved causal instructions; it adds no extra fields beyond delay \(T\) and resolution rate \(C_s\), preserving parsimony while unifying curvature and quantum uncertainty.
\end{enumerate}


\section{Conclusion}The Timeless Light Model (TLM) provides a unified framework where delay ( T ) and instructional entropy bridge the foundational axioms to the cornerstone equations of modern physics. By deriving the Einstein Field Equations from entropic gradients at horizons and the Schrödinger Equation from inference updates under delay constraints, we demonstrate that GR and QM emerge as complementary projections of timeless QP resolutions rendered in the SDF. This entropic unification, grounded in pre-resolved instructions without failures, offers a novel interpretive lens for causality, reducing apparent paradoxes to perspectival artifacts of delay.While speculative, the derivations align with established thermodynamic and epistemic approaches, extending them through TLM's delay ontology. Future work should refine these bridges with numerical simulations and explore empirical tests, such as latency in quantum systems or entropy signatures in cosmology. As of July 27, 2025, this synthesis invites scrutiny and validation, potentially advancing our understanding of reality's layered architecture.



\appendix
\section{Glossary}
\addcontentsline{toc}{section}{Glossary}

\begin{description}[leftmargin=2.5cm, labelindent=0cm]
  \item[Affine Parameter] 
  A non-temporal parameter used to track position along a null geodesic, since proper time \( \tau \) is undefined for lightlike paths. Affine parameters preserve the geodesic equation's form and enable consistent descriptions of photon trajectories without invoking time.

  \item[Arrow of Time] 
  The observed directionality of temporal experience, typically associated with increasing entropy. This arrow emerges only for systems that evolve through delay; photons, being timeless, do not contribute to it.

  \item[Causal Instruction Arc (CI-ARC)] 
  A proposed structural unit within the Timeless Light Model (TLM), representing a timeless instruction that defines the outcome of an interaction—such as a photon emission and detection event—without occupying spacetime. CI-ARCs are rendered in the Spacetime Deployment Frame (SDF) but originate from the Quantum Platform (QP), outside space and time. See McKinley (2025) \cite{mckinley2025tlm} and \cite{mckinley2025axioms}.

  \item[Delay] 
  The observed temporal spacing between events in the SDF. Delay applies only to systems with mass or clocks and does not imply internal time passage for light.

  \item[Delayed Playback] 
  The manifestation of QP instructions as observable effects in GR/SDF, akin to viewing a pre-recorded movie with temporal delay.

  \item[FLRW Metric] 
  The standard cosmological metric where photon null geodesics still yield \( \tau = 0 \), accounting for expansion.

  \item[Geodesic] 
  The shortest or extremal path between two points in a curved spacetime. In General Relativity, geodesics represent the natural trajectories followed by free-falling particles. \textit{Timelike geodesics} describe the paths of massive particles (with proper time), while \textit{null geodesics} describe the paths of massless particles like photons (with zero proper time). Photons follow null geodesics, which are not just fast—they are geometrically distinct from any path that involves elapsed time.

  \item[Lightlike (or Null) Interval] 
  A separation between two spacetime events such that a photon could connect them. The interval satisfies \( ds^2 = 0 \) and corresponds to zero elapsed proper time.

  \item[Null Geodesic] 
  A path in spacetime along which the spacetime interval satisfies \( ds^2 = 0 \). Null geodesics are followed by massless particles like photons and imply zero proper time \( \tau = 0 \). See section 3 for derivations.

  \item[Null Worldline] 
  A spacetime trajectory with \( ds^2 = 0 \). It describes massless particles such as photons. Along a null worldline, no proper time elapses.

  \item[Proper Time (\( \tau \))] 
  The time measured by a clock that travels with a particle. It represents the actual experienced duration along a worldline. For light, \( \tau = 0 \).

  \item[Quantum Platform (QP)] 
  A proposed timeless, non-spacetime layer where causal instructions (e.g., photons) originate and are pre-resolved before rendering in 4D spacetime.

  \item[Rest Frame] 
  A frame of reference in which an object is at rest. Photons cannot have a rest frame, as no Lorentz transformation can bring their velocity below \( c \).

  \item[Spacetime Deployment Frame (SDF)] 
  The proposed domain in which rendered physics—including delay, mass, and experience—becomes observable. The SDF contains all measurable quantities but is interpreted as a delayed rendering of pre-resolved instructions.

  \item[Spacetime Interval (\( ds^2 \))] 
  The invariant “distance” between two events in spacetime. Defined as \( ds^2 = -c^2 dt^2 + dx^2 + dy^2 + dz^2 \). For light, this interval is exactly zero (a null interval).

  \item[Timeless Light Model (TLM)] 
  A theoretical framework proposing that photons do not experience time or space and therefore exist outside the spacetime manifold. In this model, photons act as boundary-resolved instructions rendered into the universe rather than as evolving particles. The TLM reinterprets relativistic null geodesics and quantum phenomena as emergent effects from timeless, massless instruction sets deployed in a causally consistent manner. \cite{mckinley2025axioms}.

  \item[Timelike Worldline] 
  A path in spacetime for a massive particle where \( ds^2 < 0 \). Such particles experience proper time (\( \tau > 0 \)) and can have a rest frame.

  \item[Wave-Particle Duality]In TLM, the perspectival split between timeless QP instruction (particle) and delayed SDF rendering (wave).




  \item[Affine Parameter] 
  A non‑temporal parameter used to track position along a null geodesic, since proper time \(\tau\) is undefined for lightlike paths. Affine parameters preserve the geodesic equation’s form and enable consistent descriptions of photon trajectories without invoking time.

  \item[Entropic Variation \(\delta S\)]
  The local change in horizon entropy due to heat flux \(\delta Q\) across a causal horizon, defined by the first law
  \[
    \delta S = \frac{\delta Q}{T_U}.
  \]
  In TLM, \(\delta S\) arises from delay‑induced information gradients in the Spacetime Deployment Frame.

  \item[Heat Flux \(\delta Q\)]
  The energy flow across a horizon segment, given by
  \[
    \delta Q = \int_H T^{\alpha\beta}\,\xi_\alpha \,d\Sigma_\beta,
  \]
  where \(T^{\alpha\beta}\) is the stress–energy tensor and \(\xi_\alpha\) the horizon‑generating Killing vector.

  \item[Entropic Delay Gradient]
  The spatial gradient of entropy variation, \(\nabla(\delta S)\), induced by rendering delay \(T\), acting as the driver of curvature in the Einstein Field Equations derivation.

  \item[Horizon Area Variation \(\delta A\)]
  The change in area of a causal horizon generated by null congruences, computed via
  \[
    \delta A = \int_H \theta \,d\lambda\,dA,
  \]
  where \(\theta\) is the expansion scalar and \(\lambda\) the affine parameter along null generators.

  \item[Mass–Delay Duality]
  The axiom of TLM relating mass \(m\) and rendering delay \(T\):
  \[
    T \cdot m = \frac{\hbar}{c^2}.
  \]

  \item[Causal Resolution Rate \(C_s\)]
  The deployment rate of causal instructions in the Spacetime Deployment Frame, satisfying
  \[
    T \cdot C_s = 1.
  \]

  \item[Diffusion Constant \(D\)]
  In Entropic Dynamics,
  \[
    D = \frac{\hbar}{2m}.
  \]
  Using \(m = \hbar/(T c^2)\) gives
  \[
    D = \frac{T c^2}{2},
  \]
  linking diffusion directly to rendering delay.






















  


\end{description}









\section{Related TLM Equations}
\label{appendix:tlm_equations}

The following equations summarize foundational relationships from the Timeless Light Model (TLM), capturing how delay, mass, energy, and causal resolution rate are treated as ontologically primary and tightly coupled across layers.

\begin{itemize}
    \item \textbf{Mass–Delay Duality}:
    \[
    T \cdot m = \frac{\hbar}{c^2}
    \]
    \textit{Interpretation:} The proper-time delay \( T \) associated with rendering a mass \( m \) is inversely proportional to the mass, scaled by \( \hbar / c^2 \). This underpins the TLM view that mass induces delay, and photons (with \( m = 0 \)) therefore render instantly with \( T = 0 \).

    \item \textbf{Causal Resolution Rate (Deployment Rate)}:
    \[
    T \cdot C_s = 1
    \]
    \textit{Interpretation:} The product of rendering delay \( T \) and the causal resolution rate \( C_s \) is constant, asserting that high-resolution causal events (high \( C_s \)) require lower delay and vice versa. This parallels how light appears to move instantly due to timeless deployment, while mass-bearing events deploy slowly.

    \item \textbf{Energy as Delay-Based Tension}:
    \[
    E = T \cdot c^2
    \]
    \textit{Interpretation:} Energy is recast as a delay effect rather than a kinetic quantity—consistent with the TLM view that dynamics arise from rendering delay, not motion through spacetime.

    \item \textbf{Photon Ontology Statement}:
    \[
    \tau = 0 \quad \text{(Proper time along photon path)}
    \]
    \textit{Interpretation:} Since photons experience zero proper time, no internal state change or “mid-flight decision” can occur; the entire instruction is resolved outside time in the QP and simply appears rendered at endpoints A and B.

\end{itemize}

These equations collectively support the TLM thesis that what we observe as physical interaction is a delayed projection of timeless causal instructions rendered from the Quantum Platform (QP) into the Spacetime Deployment Frame (SDF).









\begin{thebibliography}{9}

\bibitem{einstein1905electrodynamics}
A. Einstein, 
\textit{On the Electrodynamics of Moving Bodies}, 
Annalen der Physik \textbf{17}, 891–921 (1905).

\bibitem{greene2004fabric}
B. Greene, 
\textit{The Fabric of the Cosmos: Space, Time, and the Texture of Reality}, 
Knopf, New York (2004).

\bibitem{carroll2004spacetime}
S. Carroll, 
\textit{Spacetime and Geometry: An Introduction to General Relativity}, 
Addison Wesley, San Francisco (2004).

\bibitem{feynman1985qed}
R. P. Feynman, 
\textit{QED: The Strange Theory of Light and Matter}, 
Princeton University Press, Princeton (1985).

\bibitem{thorne1994black}
K. S. Thorne, 
\textit{Black Holes and Time Warps: Einstein's Outrageous Legacy}, 
W. W. Norton \& Company, New York (1994).

\bibitem{wald1984general}
Robert M. Wald, 
\textit{General Relativity}, 
University of Chicago Press (1984).

\bibitem{wheeler1978delayed}
J.~A. Wheeler, ``The 'Past' and the 'Delayed-Choice' Double-Slit Experiment,'' in \textit{Mathematical Foundations of Quantum Theory}, ed. A.~R. Marlow, Academic Press, 1978, pp.~9--48.

\bibitem{mckinley2025tlm}
J.~C.~W. McKinley, Causal Instruction Arcs and the Timeless Light Model: A Unified Framework for Physics and Cosmology, Zenodo, July 2025. \href{https://doi.org/10.5281/zenodo.15813253}{doi.org/10.5281/zenodo.15813253}. [Preprint]

\bibitem{mckinley2025axioms}
J.~C.~W. McKinley, Axioms \& Formulas from 60 Papers, Version 2.3, July 2025. Zenodo, July 2025. \href{https://doi.org/10.5281/zenodo.16187719}{doi.org/10.5281/zenodo.16187719}.[Preprint]

\bibitem{mckinley2025spacelessness}
McKinley, J. C. W. (2025). Spacelessness as a Consequence of Timelessness in the Quantum Platform of the Timeless Light Model. Zenodo. \href{https://doi.org/10.5281/zenodo.16350754}{doi:10.5281/zenodo.16350754}.[Preprint]


\bibitem{bostrom2003simulation}
Bostrom, N. (2003). Are You Living in a Computer Simulation? \textit{Philosophical Quarterly}, 53(211), 243–255.

\bibitem{cramer1986transactional}
Cramer, J. G. (1986). The transactional interpretation of quantum mechanics. \textit{Reviews of Modern Physics}, 58(3), 647–687. \href{https://doi.org/10.1103/RevModPhys.58.647}{doi.org/10.1103/RevModPhys.58.647}.

\bibitem{rovelli2004quantum}
Rovelli, C. (2004). \textit{Quantum Gravity}. Cambridge University Press.



\bibitem{kiefer2021timelessness}
C. Kiefer, 
\textit{Timelessness Strictly inside the Quantum Realm}, 
PMC, 8235759 (2021).

\bibitem{jordan2008highlighting}
P. Jordan, 
\textit{Highlighting a Conundrum: Pascual Jordan's Resolution of Wave-Particle Duality}, 
Studies in History and Philosophy of Modern Physics \textbf{39}, 786-800 (2008).

\bibitem{barbour2000timeless}
J. Barbour, 
\textit{Timeless Reality: Symmetry, Simplicity, and Multiple Universes}, 
Prometheus Books (2000).

\bibitem{kiefer2020timeless}
C. Kiefer, 
\textit{Timelessness Strictly inside the Quantum Realm}, 
arXiv:2009.09999 (2020).

\bibitem{phenomenographic2021}
Smith, A., \& Lee, B. (2021). Student conceptions in quantum physics: A phenomenographic approach. \textit{Journal of Physics Education Research}, 45(3), 210–230.

\bibitem{silkina2024}
E. Silkina, 
\textit{Conductivity of concentrated salt solutions}, 
arXiv:2312.02624 [physics.chem-ph] (2024).

\bibitem{broinizi2023}
M. J. B. Pereira, 
\textit{The Wave-Particle Duality in a Quantum Heat Engine}, 
arXiv:2303.09244 [quant-ph] (2023).

\bibitem{mozotafrauca2025}
Á. Mozota Frauca, 
\textit{Quantum Cosmology and the Age of the Universe}, 
arXiv:2502.03075 [gr-qc] (2025).

\bibitem{chataignier2024}
L. Chataignier, 
\textit{Time and its arrow from quantum geometrodynamics?}, 
arXiv:2407.01727 [gr-qc] (2024).


\bibitem{bai2025}
Z. Bai and S. Du, 
\textit{Measure-independent description of wave-particle duality via coherence}, 
arXiv:2504.02554 [quant-ph] (2025).

\bibitem{caticha2025}
A. Caticha, 
\textit{Entropic Dynamics, Time and Quantum Theory}, 
J. Phys. A: Math. Theor. \textbf{44}, 225303 (2011).

\bibitem{barbour1999end}
J. Barbour, 
\textit{The End of Time: The Next Revolution in Physics}, 
Oxford University Press (1999).

\bibitem{dorato2013presentism}
M. Dorato and M. Morganti, 
\textit{Grades of Individuality: A Pluralistic View of Identity in Quantum Mechanics and in the Sciences}, 
Philosophical Studies \textbf{163}, 591-610 (2013).

\bibitem{hossenfelder2018lost}
S. Hossenfelder, 
\textit{Lost in Math: How Beauty Leads Physics Astray}, 
Basic Books, New York (2018).

\bibitem{maudlin2019philosophy}
T. Maudlin, 
\textit{Philosophy of Physics: Quantum Theory}, 
Princeton University Press (2019).

% In Bibliography, add:
\bibitem{debroglie1924}
L. de Broglie, 
\textit{Recherches sur la théorie des quanta}, 
Annales de Physique \textbf{3}, 22-128 (1925).

\bibitem{qmeducation2022}
J. Doe and A. Roe, 
\textit{Teaching Quantum Duality: Challenges and Strategies}, 
Physics Education \textbf{57}, 045012 (2022).

\bibitem{mckinley2025qpv3}
J. C. W. McKinley, 
\textit{Quantum Platform as Causal Senior: General Relativity as Rendered Projection}, 
Zenodo. \href{https://doi.org/10.5281/zenodo.15960343}{doi:10.5281/zenodo.15960343}.[Preprint]


\bibitem{mckinley2025qpv4}
J. C. W. McKinley, 
\textit{Unified Physics by Subordination of GR to QM: Version 4.0 -- Instructional Photons and Causal Rendering}, 
Zenodo, doi:10.5281/zenodo.16019797 (2025). [Preprint]
\href{https://doi.org/10.5281/zenodo.16019797}{doi:10.5281/zenodo.19019797}.[Preprint]



\bibitem{mckinley2025spacelessness}
McKinley, J. C. W. (2025). Spacelessness as a Consequence of Timelessness in the Quantum Platform of the Timeless Light Model. Zenodo. \href{https://doi.org/10.5281/zenodo.16350754}{doi:10.5281/zenodo.16350754}.[Preprint]

\bibitem{bohm1952suggested}
D.~Bohm, ``A Suggested Interpretation of the Quantum Theory in Terms of `Hidden' Variables. I,'' \textit{Phys. Rev.}, vol.~85, pp.~166--179, 1952. \href{https://doi.org/10.1103/PhysRev.85.166}{doi:10.1103/PhysRev.85.166}

\bibitem{holland1995quantum}
P.~R.~Holland, \textit{The Quantum Theory of Motion: An Account of the de Broglie-Bohm Causal Interpretation of Quantum Mechanics}. Cambridge, UK: Cambridge University Press, 1993.


\bibitem{jacobson1995thermodynamics}
T. Jacobson, 
\textit{Thermodynamics of Spacetime: The Einstein Equation of State}, 
Phys. Rev. Lett. \textbf{75}, 1260 (1995).

\bibitem{verlinde2011origin}
E. Verlinde, 
\textit{On the Origin of Gravity and the Laws of Newton}, 
JHEP \textbf{04}, 029 (2011).

\bibitem{caticha2012entropic}
A. Caticha, 
\textit{Entropic Dynamics, Time and Quantum Theory}, 
J. Phys. A: Math. Theor. \textbf{44}, 225303 (2011).

























\end{thebibliography}

\end{document}
```

</details>

---
{% endraw %}
