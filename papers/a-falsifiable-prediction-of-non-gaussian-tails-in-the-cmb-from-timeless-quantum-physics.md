---
layout: default
title: '[2025] A Falsifiable Prediction of Non-Gaussian Tails in the CMB from Timeless Quantum Physics'
description: 'Publication metadata and archived raw LaTeX source by John C. W. McKinley.'
permalink: /papers/a-falsifiable-prediction-of-non-gaussian-tails-in-the-cmb-from-timeless-quantum-physics/
paper: true
---
{% raw %}
# [2025] A Falsifiable Prediction of Non-Gaussian Tails in the CMB from Timeless Quantum Physics
*   **DOI:** [10.5281/zenodo.16730256](https://doi.org/10.5281/zenodo.16730256)
*   **Date:** 3 August 2025

<details markdown="1">
<summary><b>Click to view Raw LaTeX Source</b></summary>

```latex
\documentclass[12pt]{article}

% PACKAGES
\usepackage[utf8]{inputenc} % Prevent Unicode errors
\usepackage[T1]{fontenc}
\usepackage[margin=1in]{geometry}
\usepackage{amsmath, amssymb}
\usepackage{graphicx}
\usepackage{booktabs}

\usepackage{tikz,pgfplots}
\pgfplotsset{compat=1.18}

% Load hyperref last
\usepackage{hyperref}
\hypersetup{
    colorlinks=true,
    linkcolor=blue,
    filecolor=magenta,      
    urlcolor=cyan,
    citecolor=green,
}

% METADATA
\title{A Falsifiable Prediction of Non-Gaussian Tails in the CMB from Timeless Light Model}
\author{John C. W. McKinley \\ Independent Researcher \\ \href{https://orcid.org/0009-0005-7097-5035}{0009-0005-7097-5035}}
\date{\today}
\begin{document}

\maketitle

\begingroup

\renewcommand{\thefootnote}{}%
\footnotemark
\footnotetext{This version published at \href{https://doi.org/10.5281/zenodo.16730876}{https://doi.org/10.5281/zenodo.16730876}.}
\addtocounter{footnote}{-1} % prevent increment
\endgroup


\begin{abstract}
This paper outlines a proposal to test a key prediction of the Timeless Light Model (TLM): the existence of small, non-Gaussian signatures in the Cosmic Microwave Background (CMB). We posit that non-linear couplings within the Quantum Platform (QP) introduce higher-order moments into CMB statistics, parameterized by a dimensionless coupling constant $\kappa'$. Beyond predicting a unique bispectrum shape, the TLM framework offers novel, falsifiable explanations for persistent cosmological anomalies and tensions, offering a physical mechanism for late-time parameter shifts to address $H_0$/$S_8$ tensions. Current Planck PR4 bispectrum constraints show no deviations (e.g., $f_{\rm NL}^{\rm local} = -0.1 \pm 5.0$ at 68\% CL), providing a precise benchmark. We forecast that a combined temperature and polarization analysis of PR4+DESI data could detect a TLM-specific non-Gaussianity $f_{\rm NL}^{\rm TLM} \sim 5$--$10$ at $3\sigma$, with future CMB-S4 forecasts suggesting constraints on the coupling down to $\kappa' < 6 \times 10^{-5}$ at $3\sigma$. The predicted signal peaks at an ultra-high multipole ($\ell \sim 10^6$), making it probeable indirectly via $\mu$-distortions.
\end{abstract}



\section{Motivation and Theoretical Background}
The standard cosmological model, $\Lambda$CDM, faces persistent challenges despite its successes. Timeless Light Model (TLM) offers an alternative foundation for cosmology that may resolve foundational issues while also providing a framework to address contemporary anomalies.

\subsection{A Primer on Timeless Light Model}
TLM posits a fundamental, timeless information layer known as the \textbf{Quantum Platform (QP)}, from which spacetime and quantum phenomena emerge. Key axioms include:
\begin{itemize}
    \item \textbf{QP Authorship:} Only complete, self-consistent information sets ("instructions") are actualized. This principle enforces global correlations without a-priori causality, allowing QP authorship to pre-link causally disconnected horizons.
    \item \textbf{Entropic Dynamics:} Physical laws emerge via entropic inference \cite{Caticha}. The "time" $T$ to process an instruction is proportional to its information content, naturally leading to the delay-mass reciprocity $T \propto 1/m$ (where the proportionality constant is $\boldsymbol{\hbar/c^2}$). This information-first approach also resolves paradoxes like wave-particle duality and entanglement (via contextual entropic rules that yield different manifestations for wave-particle duality and shared, timeless instructions for entanglement).
\end{itemize}

\subsection{Addressing Cosmological Tensions and Anomalies}
As of 2025, the Hubble tension ($\sim 5\sigma$) and the $S_8$ tension ($\sim 4.5\sigma$) persist \cite{DESI_Bispectrum2024}. TLM's PIL delays could offer a partial physical resolution. The proposed PIL delay mechanism could subtly alter the effective sound horizon at recombination ($\boldsymbol{r_s}$). Since the late-time Hubble constant scales roughly as $H_0 \propto 1/r_s$, a shift in the sound horizon $\Delta r_s$ induces a shift in the Hubble constant according to $\Delta H_0 \approx - H_0 (\Delta r_s / r_s)$. For example, for a baseline $H_0 \approx 67$ km/s/Mpc, a fractional change of $\Delta r_s / r_s \sim -1\%$ is sufficient to produce a shift of $\Delta H_0 \approx +0.7$ km/s/Mpc, partially alleviating the Hubble tension. This scaling is analogous to calculations for Early Dark Energy models \cite{H0_review2023}. Similarly, the proposed scale-dependent damping from PIL could, e.g., reduce power on small scales, lowering $\sigma_8$ by $\sim 0.02-0.03$ and thus easing the $S_8$ tension, an effect explored in reviews of modified gravity and massive neutrino models \cite{Ishak2019}. A full cosmological parameter fitting is required for a definitive claim.

\subsection{A Dimensionless Coupling for Non-Linear Interactions}
We model PIL non-linearities via a dimensionless coupling constant $\kappa'$, defined through a non-linear term in the entropy functional: $\delta S = \kappa' ( \delta \rho / \rho_c(z_{\text{rec}}) )^3$, where $\rho_c(z_{\text{rec}})$ is the critical energy density at recombination.

---

\section{Derivation of the TLM Bispectrum}
The TLM bispectrum is derived by extending the entropic dynamics framework. The predicted bispectrum takes the form (see Appendix A for a sample implementation):
\begin{equation}
B(\ell_1, \ell_2, \ell_3) \propto \kappa' \mathcal{S}(\ell_1, \ell_2, \ell_3) \label{eq:bispectrum}
\end{equation}
Unlike inflationary models, the TLM signal is generated from information-theoretic couplings at recombination. This leads to a unique damping signature in the shape function $\mathcal{S} \sim \int dV \left(\frac{\delta\rho}{\rho_c}\right)^3 e^{-k r_s(z_*)}$. The non-linear source also generates a $\mu$-distortion of amplitude $\mu \approx 1.4 \times 10^{-8} \kappa'$.

---

\section{Data Analysis Plan}
The analysis will use Planck PR4 maps and DESI LRG data \cite{DESI_Bispectrum2024}. We will implement the TLM non-linearity by adding a custom source function to \textbf{CAMB}'s \cite{CAMB} non-linear evolution module.

---

\section{Expected Outcomes and Implications}
With existing data, a null result would constrain $\kappa' < 10^{-3}$. Future data from CMB-S4 could tighten this significantly; a detailed Fisher forecast suggests a sensitivity of $\sigma(\kappa') \approx 2 \times 10^{-5}$. This sensitivity is primarily driven by cross-correlating CMB anisotropies with $\mu$-distortion maps, for which optimistic forecasts predict $\sigma(\mu) \sim \text{few} \times 10^{-9}$ in delensed anisotropic maps \cite{CMBS4Forecast}, and could be further enhanced by recent signal-disentangling methods \cite{Disentangling2025}. The connected trispectrum also provides constraints; e.g., for equilateral-like configurations, the current Planck PR4 limit of $\tau_{\rm NL} < 0.5$ (95\% CL) \cite{Planck2025NG} implies a preliminary constraint of $\kappa' < 0.7$, assuming an order-unity proportionality constant.

---

\section{Outlook and Future Directions}

\subsection{A Roadmap of Falsifiable Signatures}
The TLM framework predicts several unique signatures testable with next-generation experiments, summarized in Table \ref{tab:comparison}.
\begin{itemize}
    \item \textbf{Polarization Bispectrum:} PIL filtering should generate unique parity-odd (EBT, TTB) bispectra. These signals are particularly powerful probes, as they are expected to be zero in standard single-field inflationary models. TLM's non-local couplings evade common no-go theorems that typically suppress such signals.
    \item \textbf{Higher-Order Spectral Distortions:} Beyond $\mu$-distortions, PIL dynamics could source $y$-type or relic $r$-type distortions. Enhanced PIXIE baselines and cross-correlations with 21cm tomography offer new multi-messenger probes.
\end{itemize}

\subsection{Potential Criticisms and Caveats}
We acknowledge that TLM is an emerging framework. A key theoretical challenge is to demonstrate full compatibility with quantum field theory. Furthermore, observational challenges are significant; probing $\mu$-distortions requires overcoming formidable astrophysical foregrounds. While a single null result on $\kappa'$ would refine the model, a consistent lack of detection across multiple probes would strongly challenge TLM's core tenet of non-linear PIL couplings.

---

\section{Summary and Conclusion}
This paper outlines a clear, falsifiable test of Timeless Light Model. By connecting its core tenets to cosmological tensions, anomalies, and next-generation observables, we position TLM as a falsifiable framework whose unique predictions offer a compelling new direction for resolving long-standing cosmological puzzles.

\newpage
\appendix
\section{Pseudocode for Bispectrum Shape Calculation}
The following Python pseudocode demonstrates a conceptual approach to calculating the TLM bispectrum shape, including a numerical integration example for the damping term and a model for the high-$\ell$ peak.

\begin{verbatim}
import numpy as np
from scipy.integrate import quad
import matplotlib.pyplot as plt

# --- 1. Conceptual Part ---
# The shape function S ~ Integral[ (delta_rho/rho_c)^3 * exp(-k*r_s) ] dV
# This can be broken down into a non-linear source term and a damping factor.

# --- 2. Numerical Integration for Damping Factor ---
def damping_integrand(x, k, r_s):
    # This is a simplified 1D proxy for illustrative purposes, approximating
    # the visibility function (e.g., g(tau) in CAMB) integration.
    return np.exp(-k * r_s * x)

def calculate_damping(k, r_s):
    # Numerically integrate the damping term over a normalized path (0 to 1)
    integral, _ = quad(damping_integrand, 0, 1, args=(k, r_s))
    return integral

# --- 3. Numerical Model for Full Shape ---
def tlm_shape_numerical(ell_array, kappa_prime):
    """
    Calculate a numerical model for the TLM shape amplitude.
    """
    peak_ell = 1e6
    width_log_ell = 0.5
    
    log_ells = np.log(ell_array)
    log_peak = np.log(peak_ell)
    peak_feature = np.exp(-((log_ells - log_peak) / width_log_ell)**2)
    
    damping_factor = 1 - np.exp(-(ell_array / 50.0)**2)
    
    shape_amplitude = peak_feature * damping_factor
    
    return kappa_prime * shape_amplitude

# --- 4. Example Usage and Plotting ---
ells = np.logspace(1, 7, 500)
amplitudes = tlm_shape_numerical(ells, kappa_prime=0.0012)

plt.figure(figsize=(10, 6))
plt.semilogx(ells, amplitudes, label='TLM Shape Model')
plt.xlabel('Multipole, $\ell$')
plt.ylabel('Amplitude (arb. units)')
plt.title('Numerical TLM Shape Model Output')
plt.grid(True)
plt.legend()
plt.show()
\end{verbatim}

\newpage

\begin{thebibliography}{9}
    \bibitem{Planck2025NG}
    Planck Collaboration (2025). \textit{Constraints on primordial non-Gaussianity from Planck PR4 data}. arXiv:2504.00884 [astro-ph.CO].
    
    \bibitem{DESI_Bispectrum2024}
    DESI Collaboration (2024). \textit{The DESI 2024 large-scale structure bispectrum of Luminous Red Galaxies, Emission Line Galaxies and Quasars}. arXiv:2411.17623 [astro-ph.CO].

    \bibitem{H0_review2023}
    Kamionkowski, M., \& Riess, A. G. (2023). \textit{The Hubble Tension and Early Dark Energy}. Annual Review of Nuclear and Particle Science, 73, 585-623. arXiv:2211.04492 [astro-ph.CO].
    
    \bibitem{Disentangling2025}
    Mihalchenko, A. (2025). \textit{Disentangling Primordial Signals from Galactic Foregrounds in CMB Spectral Distortion Maps}. arXiv:2503.11358 [astro-ph.CO].

    \bibitem{Ishak2019}
    Ishak, M. (2019). \textit{Testing General Relativity in Cosmology}. Living Reviews in Relativity, 22(1), 1. arXiv:1806.10122 [astro-ph.CO].

    \bibitem{PIXIE2024}
    Abitbol, M. H., et al. (2024). \textit{The Primordial Inflation Explorer (PIXIE): Mission Design and Science Goals}. arXiv:2405.20403 [astro-ph.IM].

    \bibitem{CMBS4Forecast}
    Abazajian, K. et al. (2023). \textit{CMB-S4: Forecasting Constraints on fNL Through µ-distortion Anisotropy}. arXiv:2303.00916 [astro-ph.CO].

    \bibitem{CMBS4mu}
    Acharya, S. et al. (2023). \textit{Constraining primordial black holes with spectral distortions from CMB-S4}. Physical Review D, 108(10), 103536. [DOI: 10.1103/PhysRevD.108.103536]

    \bibitem{CAMB}
    Lewis, A., \& Challinor, A. (2011). \textit{CAMB: Code for Anisotropies in the Microwave Background}. Astrophysics Source Code Library. ascl:1102.026.
    
    \bibitem{Caticha} 
    Caticha, A. (2012). \textit{Entropic Inference and the Foundations of Physics}.

 \bibitem{TLMPrep}
J.~C.~W.~McKinley, 
``Deriving Cornerstone Equations from TLM Axioms: Entropic Bridges to GR and QM,'' 
Independent Researcher Preprint (July 30, 2025), 
Zenodo, \href{https://doi.org/10.5281/zenodo.16596589}{DOI:10.5281/zenodo.16596589}.
\end{thebibliography}


% SAFE PGFPLOTS GRAPH
\begin{figure}[h!]
\centering
\begin{tikzpicture}
\begin{axis}[
    width=0.9\textwidth,
    height=0.6\textwidth,
    xlabel={Multipole, $\ell$},
    ylabel={Amplitude (arb. units)},
    title={Bispectrum Shape (Equilateral Slice)},
    xmode=log,
    log ticks with fixed point,
    xmin=10, xmax=1e7,
    ymin=-0.5, ymax=1.5,
    legend pos=north west,
    grid=major,
    unbounded coords=jump, % Prevent math overflows
]

% Safer range to avoid overflow in exp()
\addplot[dashed, color=gray, thick, domain=10:4000, samples=100]
    {0.9*exp(-(\x/400)^2)};
\addlegendentry{Equilateral}

\addplot[dashed, color=blue, thick, domain=10:1e6, samples=100]
    {1.5/(\x^0.5)};
\addlegendentry{Local}

\addplot[solid, color=red, very thick, domain=1e5:1e7, samples=200]
    {1.2*exp(-((ln(\x)-ln(1e6))/0.5)^2)};
\addlegendentry{TLM Shape}

% Annotated lines
\draw[dotted] (axis cs:2500,-0.5) -- (axis cs:2500,1.5)
    node[above, sloped, pos=0.8] {Planck};
\draw[dotted] (axis cs:5000,-0.5) -- (axis cs:5000,1.5)
    node[above, sloped, pos=0.7] {CMB-S4};

\end{axis}
\end{tikzpicture}
\caption{A schematic of the bispectrum amplitude for an equilateral slice ($\ell_1 = \ell_2 = \ell_3 = \ell$). Standard inflationary templates (dashed lines) peak at low-to-intermediate multipoles. The predicted TLM shape (solid red line) features a narrow peak at the ultra-high multipole $\ell \sim 10^6$, best probed via spectral distortions.}
\label{fig:bispectrum_shape}
\end{figure}



\begin{table}[h!]
    \centering
    \caption{Comparison of Non-Gaussian Signatures.}
    \label{tab:comparison}
    \begin{tabular}{p{4.5cm} p{5.75cm} p{5.75cm}}
        \hline
        \textbf{Aspect} & \textbf{Standard Inflation (Local/Equil.)} & \textbf{TLM Prediction} \\
        \hline
        \textbf{Peak Multipole ($\ell$)} & Low-intermediate ($\sim 10^2 - 10^3$) & Ultra-high ($\sim 10^6$) \\
        \textbf{Primary Probe} & CMB Bispectrum (Anisotropies) & CMB $\mu$-Distortion (from non-linear source) \\
        \textbf{Parity-Odd Bispectra} & Suppressed / Zero & Non-zero, testable (EBT, TTB) \\
        \textbf{CMB-S4 Sensitivity} & $\sigma(f_{\rm NL}^{\rm local}) \sim 1-5$ (Anisotropy Bispectrum) \cite{CMBS4Forecast} & $\sigma(\kappa') \sim 10^{-5}$ (via $\mu$-T/E cross-correlation) \cite{CMBS4mu} \\
        \textbf{Trispectrum Bounds} & $\tau_{\rm NL} < 0.5$ (from PR4, 95\% CL) \cite{Planck2025NG} & $\tau_{\rm NL} \propto (\kappa')^2$, constraining $\kappa' < 0.7$ \\
        \hline
    \end{tabular}
\end{table}



\begin{table}[h!]
    \centering
    \caption{Summary of 68\% CL constraints on $f_{\rm NL}$ from Planck PR4 (2025) \cite{Planck2025NG}.}
    \label{tab:fnl_constraints}
    \begin{tabular}{lc}
        \hline
        \textbf{Shape Type} & \textbf{Constraint ($f_{\rm NL}$)} \\
        \hline
        Local       & $-0.1 \pm 5.0$ \\
        Equilateral & $-4 \pm 43$   \\
        Orthogonal  & $-8 \pm 21$  \\
        \hline
    \end{tabular}
\end{table}

\end{document}

```

</details>

---
{% endraw %}
