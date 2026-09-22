---
layout: default
title: '[2025] Falsifiable Prediction of Horizon-Scale Phase Shifts in Gravitational Waves from the Timeless Light Model'
description: 'Publication metadata and archived raw LaTeX source by John C. W. McKinley.'
permalink: /papers/falsifiable-prediction-of-horizon-scale-phase-shifts-in-gravitational-waves-from-the-timeless/
paper: true
---
{% raw %}
# [2025] Falsifiable Prediction of Horizon-Scale Phase Shifts in Gravitational Waves from the Timeless Light Model
*   **DOI:** [10.5281/zenodo.16730926](https://doi.org/10.5281/zenodo.16730926)
*   **Date:** 3 August 2025

<details markdown="1">
<summary><b>Click to view Raw LaTeX Source</b></summary>

```latex
\documentclass[12pt, letterpaper]{article}

% GEOMETRY (only once, and matches paper size)
\usepackage[margin=1in]{geometry}

% ENCODING
\usepackage[utf8]{inputenc}
\usepackage[T1]{fontenc}

% MATH & SYMBOLS
\usepackage{amsmath, amssymb}

% GRAPHICS
\usepackage{graphicx}
\usepackage{booktabs}
\usepackage{tikz}
\usepackage{pgfplots}
\pgfplotsset{compat=1.18}
\usepgfplotslibrary{fillbetween}

% BIBLIOGRAPHY (if using biblatex, otherwise remove)
% \usepackage[backend=biber, style=numeric-comp, sorting=none]{biblatex}

% HYPERLINKS (load last)
\usepackage{hyperref}
\hypersetup{
    colorlinks=true,
    linkcolor=blue,
    filecolor=magenta,      
    urlcolor=cyan,
    citecolor=green,
}


% METADATA
\title{Falsifiable Prediction of Horizon-Scale Phase Shifts in Gravitational Waves from the Timeless Light Model}
\author{John C. W. McKinley \\ Independent Researcher \\ \href{https://orcid.org/0009-0005-7097-5035}{0009-0005-7097-5035}}
\date{\today}
\begin{document}
\maketitle

\begingroup

\renewcommand{\thefootnote}{}%
\footnotemark
\footnotetext{This version published at \href{https://doi.org/10.5281/zenodo.16731229}{https://doi.org/10.5281/zenodo.16731229}.}
\addtocounter{footnote}{-1} % prevent increment
\endgroup






\begin{abstract}
The Timeless Light Model (TLM) posits that black hole event horizons are loci of maximal rendering delay where information capacity becomes infinite. This paper details a key, falsifiable prediction arising from this axiom: the existence of tiny, discrete phase-shift residuals in the gravitational-wave (GW) signals from black hole mergers. These shifts, scaled by mass (e.g., $\Delta \phi \sim 10^{-3}$ rad for a 100 $M_\odot$ merger), arise from the model's entropic derivation of the Einstein Field Equations. This mechanism complements searches for CMB non-Gaussianity and offers a potential avenue for partial relief of the $H_0/S_8$ cosmological tensions via subtle modifications to the sound horizon \cite{McKinley_CMB}. We theorize that as Causal Instruction-Arcs (CI-Arcs) graze the horizon, they experience quantized delays, imprinting discrete phase offsets onto the GW waveform. An absence of such signatures in high-SNR events would constrain this hashing mechanism, while a detection would offer compelling evidence for TLM's two-layer ontology.
\end{abstract}
\textbf{Keywords:} Timeless Light Model, Gravitational Waves, Quantum Gravity, Black Hole Physics, Entropic Gravity.
\hrule

\section{Motivation and Theoretical Background}
The observation of gravitational waves by the LIGO-Virgo-KAGRA (LVK) collaboration has confirmed General Relativity (GR) in the strong-field regime \cite{Aasi2015, LVK_GWTC3}. However, foundational questions regarding quantum gravity and the information paradox suggest that horizons may possess a microstructure not captured by classical GR.

The Timeless Light Model (TLM) offers an alternative ontology where such a microstructure is a natural consequence of its core axioms \cite{McKinley2025Why}. TLM posits a two-layer reality: a timeless, non-spatiotemporal \textbf{Quantum Platform (QP)} where causal outcomes are pre-resolved as \textbf{Causal Instruction Arcs (CI-ARCs)}, and a \textbf{Spacetime Deployment Frame (SDF)} where these instructions are rendered with delay.

Within this framework, event horizons are fundamental deployment boundaries. According to the mass-delay axiom ($T \cdot m = \hbar/c^2$), the rendering delay $T$ at a black hole horizon approaches infinity ($T \to \infty$). This infinite delay capacity allows the horizon to source a limitless number of instructions, resolving the information paradox by providing an infinite storage space consistent with holographic principles \cite{Susskind1995}. It also implies a quantization of the horizon's informational microstates, tying its entropy $S$ to its area $A$ via the Bekenstein-Hawking relation \cite{Bekenstein1973, Hawking1975}:
\begin{equation}
S = \frac{A}{4 \ell_p^2}
\end{equation}
This paper builds on this foundation to make a falsifiable prediction testable with data from recent LVK runs, such as the O4 catalog \cite{LVK_O4_Catalog} and high-mass events like GW230529 (total mass $\sim$200 $M_\odot$, SNR $\sim$25).

\hrule

\section{Derivation of Phase-Shift Signals in TLM}

\subsection{Horizon Microstructure and Quantized Delay}
From the TLM principle that rendering delay $T \to \infty$ at the horizon, the phase shift $\Delta \phi$ is linked to area quantization. For a grazing arc, the delay implies a phase lag $\Delta \phi \sim \hbar c^3 / (G M \Delta A)^{1/2}$, up to $\mathcal{O}(1)$ prefactors. This simplifies to:
\begin{equation}
\Delta \phi \sim 2\pi \sqrt{\frac{\Delta A}{A}}
\end{equation}
where TLM posits a fundamental area quantum $\Delta A = 4 \ell_p^2 \ln 2$. The $\ln 2$ factor arises from the binary ("yes/no") logic of QP instructional hashing \cite{Susskind1995}. For a non-spinning Schwarzschild black hole, the horizon area is $A = 16\pi (GM/c^2)^2$. For a 100 $M_\odot$ black hole, this yields a Planck-suppressed phase shift of $\Delta \phi \sim 10^{-3}$ radians. The $\mathcal{O}(1)$ uncertainty arises from geometric factors of the grazing instruction arc; potential loop corrections may suppress this effect further.

\subsection{Perturbing Gravitational Waveforms}
We inject these quantized delays into standard waveform models. The continuous phase evolution $\phi_{GR}(t)$ is modified to include a series of discrete jumps:
\begin{equation}
\phi_{TLM}(t) = \phi_{GR}(t) + \sum_{n} \Delta \phi_n \cdot \theta(t - t_n)
\end{equation}
Templates are generated by adapting Numerical Relativity (NR) waveform catalogs from sources like the SXS Collaboration.

\subsection{Consistency with Entropic Gravity}
This derivation maintains consistency with entropic gravity frameworks. Just as Jacobson derived the EFE as an equation of state from horizon thermodynamics \cite{Jacobson1995}, our phase shifts arise from the same underlying entropic principles.

\begin{figure}[h!]
\centering
\begin{tikzpicture}
\begin{axis}[
    name=mainplot,
    height=6cm, width=\textwidth,
    xticklabels={},
    ylabel={Strain},
    legend pos=outer north east,
    grid=major,
    ymin=-1.2, ymax=1.2,
    domain=0:15,
]
\addplot[samples=200, color=blue, thick, dashed] {sin(deg(2*pi*x^1.5)) * exp(-0.08*x)};
\addlegendentry{Standard GR}
\addplot[samples=100, color=red, thick] {sin(deg(2*pi*x^1.5)) * exp(-0.08*x)};
\addplot[samples=100, color=red, thick] {sin(deg(2*pi*x^1.5 + 0.5)) * exp(-0.08*x)};
\addplot[samples=100, color=red, thick] {sin(deg(2*pi*x^1.5 + 0.8)) * exp(-0.08*x)};
\addlegendentry{TLM}
\end{axis}
\begin{axis}[
    name=residualplot,
    at=(mainplot.below south), anchor=above north,
    height=4cm, width=\textwidth,
    xlabel={Time (ms post-merger)},
    ylabel={Residual Phase ($\Delta\phi$)},
    grid=major,
    ymin=-0.2, ymax=1.5,
    domain=0:15,
]
\addplot[name path=upper, draw=none] {0.15*abs(sin(deg(30*x))) + 0.05};
\addplot[name path=lower, draw=none] {-0.15*abs(sin(deg(30*x))) - 0.05};
\addplot[fill=gray!30, opacity=0.5] fill between[of=upper and lower];
\addplot[const plot, color=orange, thick] coordinates {(0,0) (3,0) (3,0.5) (6,0.5) (6,0.8) (15,0.8)};
\addlegendentry{Phase Jumps $\Delta\phi_n$}
\end{axis}
\end{tikzpicture}
\caption{A schematic of a standard GR chirp-ringdown waveform versus a TLM-predicted waveform (top). The residual phase (bottom) shows the step-like signature against simulated noise (shaded band). For a real analysis, waveforms from SXS NR simulations would be used.}
\label{fig:waveform}
\end{figure}

\hrule

\section{Data Analysis Plan}
\begin{itemize}
    \item \textbf{Datasets}: The analysis will utilize public data from LVK runs O4 and O5, focusing on high-mass, high-SNR events like GW230529. O5 forecasts of 100+ events/year will enable robust statistical constraints \cite{Hall2021}.
    
    \item \textbf{Methods}: We will employ Bayesian parameter estimation using software like \textbf{PyCBC} or \textbf{Bilby} to compare custom TLM waveform models against the standard GR null hypothesis. Visualization of residuals could use tools like \texttt{healpy}.
    
    \item \textbf{Statistical Tests}: We will use the \textbf{Bayes factor} to compare model evidence. LVK O5 noise curves from \cite{Hall2021} are forecast to enable a 3$\sigma$ null constraint on phase shifts of $\Delta \phi < 10^{-2}$ radians for high-SNR events.
    
    \item \textbf{Systematics and Validation}: The pipeline will be validated through injections of simulated TLM signals into real detector data from the Gravitational Wave Open Science Center (GWOSC).
\end{itemize}

\hrule

\section{Expected Outcomes and Implications}

\subsection{Detection vs. Null Result}
A detection would provide powerful evidence for TLM's quantized spacetime. A null result from O5 at 3$\sigma$ confidence would be equally valuable, placing the first empirical constraints on the horizon quantization mechanism by limiting the area quantum to $\Delta A < \ell_p^2$.

\subsection{Unification with Cosmology}
This prediction is tied to other TLM forecasts. The same entropic principles predict specific non-Gaussian signatures in the Cosmic Microwave Background \cite{McKinley_CMB}. A null GW result would directly constrain the dimensionless parameter $\kappa'$ that governs the shared entropy scaling to be less than $10^{-4}$ \cite{McKinley_CMB}. This work complements other beyond-GR searches, such as for gravitational-wave echoes \cite{Cardoso2016}.

\subsection{Future Prospects}
By the 2030s, the \textbf{Einstein Telescope} is forecast to achieve a sensitivity of $\sigma(\phi) \sim 10^{-4}$ rad, enabling precision tests that could definitively confirm or rule out this prediction \cite{Amann2020}.

\hrule

\section{Conclusion}

The Timeless Light Model offers a concrete, falsifiable prediction: discrete, quantized phase shifts in gravitational waves. This signature, distinct from the smooth waveforms of classical GR, is a direct consequence of the proposed informational microstructure of event horizons. This work pushes gravitational-wave astronomy into the quantum gravity regime, bridging GW phenomenology with TLM's solution to the information paradox and its predictions for cosmology. We encourage the GW consortia to incorporate TLM-based templates in the analysis pipelines for O5 and beyond to probe the fundamental nature of spacetime.

\clearpage


\begin{thebibliography}{99}

\bibitem{Aasi2015}
J. Aasi \textit{et al.}, “Advanced LIGO,” \textit{Class. Quantum Grav.} \textbf{32}, 074001 (2015).

\bibitem{Jacobson1995}
T. Jacobson, “Thermodynamics of Spacetime: The Einstein Equation of State,” \textit{Phys. Rev. Lett.} \textbf{75}, 1260–1263 (1995).

\bibitem{Susskind1995}
L. Susskind, “The World as a Hologram,” \textit{J. Math. Phys.} \textbf{36}, 6377–6396 (1995).

\bibitem{Bekenstein1973}
J. D. Bekenstein, “Black Holes and Entropy,” \textit{Phys. Rev. D} \textbf{7}, 2333–2346 (1973).

\bibitem{Hawking1975}
S. W. Hawking, “Particle Creation by Black Holes,” \textit{Commun. Math. Phys.} \textbf{43}, 199–220 (1975).

\bibitem{McKinley_CMB}
J. C. W. McKinley, “A Falsifiable Prediction of Non-Gaussian Tails in the CMB from Timeless Quantum Physics,” Zenodo preprint (2025). \url{https://doi.org/10.5281/zenodo.16730876}.



\bibitem{McKinley2025Why} J. C. W. McKinley, “Why the Timeless Light Model Deserves Scientific Consideration: A Foundational Framework with Derivations, Critiques, and Experimental Proposals,” Zenodo (2025), \url{https://doi.org/10.5281/zenodo.16724187}. 

\bibitem{LVK_GWTC3}
R. Abbott et al. (LIGO Scientific, Virgo, and KAGRA Collaborations), “GWTC-3: Compact Binary Coalescences Observed by LIGO and Virgo During the Second Part of the Third Observing Run,” \textit{Phys. Rev. X} \textbf{13}, 041039 (2023), arXiv:2111.03606.

\bibitem{LVK_O4_Catalog}
LIGO Scientific Collaboration, Virgo Collaboration, and KAGRA Collaborations, “GWTC-4: A preliminary release of events from the fourth observing run,” arXiv:2504.00884 (2025).

\bibitem{Hall2021}
E. D. Hall and S. E. Dwyer, “Gravitational-Wave Physics and Astronomy in the 2020s and 2030s,” arXiv:2111.06990 (2021).

\bibitem{Amann2020}
F. P. Amann et al. (ET Science Team), “Einstein Telescope: A third-generation gravitational wave observatory,” \textit{Class. Quant. Grav.} \textbf{37}, 215001 (2020).















\end{thebibliography}




\end{document}
```

</details>

---
{% endraw %}
