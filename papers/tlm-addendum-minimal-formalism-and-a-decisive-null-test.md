---
layout: default
title: '[2025] TLM Addendum: Minimal Formalism and a Decisive Null Test'
description: 'Publication metadata and archived raw LaTeX source by John C. W. McKinley.'
permalink: /papers/tlm-addendum-minimal-formalism-and-a-decisive-null-test/
paper: true
---
{% raw %}
# [2025] TLM Addendum: Minimal Formalism and a Decisive Null Test
*   **DOI:** [10.5281/zenodo.16909382](https://doi.org/10.5281/zenodo.16909382)
*   **Date:** 20 August 2025

<details markdown="1">
<summary><b>Click to view Raw LaTeX Source</b></summary>

```latex
\documentclass[11pt]{article}
\usepackage[margin=1in]{geometry}
\usepackage{amsmath,amssymb}
\usepackage[hidelinks]{hyperref}

\title{TLM Addendum: Minimal Formalism and a Decisive Null Test\thanks{A version of related ideas was emailed to associates on 13 June 2025.}}
\author{John Christian William McKinley\thanks{ORCID: \href{https://orcid.org/0009-0005-7097-5035}{0009-0005-7097-5035}}}
\date{August 20, 2025}

\begin{document}
\maketitle


% This creates a footnote for the DOI without a number/marker on the page
\begingroup
\renewcommand\thefootnote{}
\footnotetext{This version published at \href{https://doi.org/10.5281/zenodo.16909382}{https://doi.org/10.5281/zenodo.16909382}.}
\endgroup

\begin{abstract}
This note adds two new pieces to the Timeless Light Model (TLM) series without re-stating prior results: (i) a compact, covariant effective model that encodes ``mass imposes delay'' while preserving stress--energy conservation and the GR/QM limits; and (ii) a decisive A/B protocol designed as a \emph{null test} against orthodox predictions. The model is deliberately conservative (no large laboratory effects claimed) and is intended to serve as a consistency anchor for the August 2025 preprints.
\end{abstract}

\noindent\textbf{What is new relative to prior DOIs.}
(1) \emph{Minimal formalism with explicit conservation.} Prior papers introduced pairing/transfer and frame dynamics conceptually; here I give a one-field action, show the variations, and state the precise GR/QM limits.
(2) \emph{A/B null test.} A concrete protocol where standard QED/GR predicts no change while TLM permits a small, parameterized dependence; result is publishable as a constraint even if null.

\section*{1.\;Minimal effective theory (conservative)}
Let $g_{\mu\nu}$ denote the spacetime metric and $\phi$ a dimensionless ``delay potential.'' Matter fields $\Psi$ couple to the \emph{physical} metric
\[
\tilde g_{\mu\nu} \equiv e^{2\phi} g_{\mu\nu},
\]
so local clock rates scale as $d\tilde\tau = e^{\phi} d\tau$. The total action is
\begin{equation}
\label{eq:S}
S = \frac{1}{16\pi G}\!\int\! d^4x \sqrt{-g}\,(R-2\Lambda)
+ \int\! d^4x \sqrt{-g}\,\Big[-\tfrac12(\nabla\phi)^2 - V(\phi)\Big]
+ S_{\rm m}[\tilde g,\Psi].
\end{equation}
Variation w.r.t.\ $g_{\mu\nu}$ and $\phi$ yields
\begin{align}
G_{\mu\nu}+\Lambda g_{\mu\nu} &= 8\pi G\big(T^{\phi}_{\mu\nu}+T^{\rm (m)}_{\mu\nu}\big),\\
\square\phi - V'(\phi) &= \alpha_{\mathrm m}(\phi)\,T^{\rm (m)},\qquad \alpha_{\mathrm m}(\phi)\equiv \frac{d\ln A(\phi)}{d\phi},\;\; A(\phi)=e^{\phi}\Rightarrow \alpha_{\mathrm m}=1,
\end{align}
where $T^{\rm (m)}\!\equiv\!\tilde g^{\mu\nu}T^{\rm (m)}_{\mu\nu}$. By the contracted Bianchi identities,
\[
\nabla_{\mu}\big(T^{\phi\,\mu}{}_{\nu}+T^{\rm (m)\,\mu}{}_{\nu}\big)=0,
\]
so \emph{total} stress--energy is conserved. Matter follows $\tilde g$-geodesics, implementing ``delay'' as a local rescaling, not a force.

\medskip
\noindent\textbf{GR limit.} If $\phi\!\to\!0$ and $V$ minimized, $\tilde g_{\mu\nu}\!\to\! g_{\mu\nu}$ and Eq.\,\eqref{eq:S} reduces to GR $+\Lambda$; standard tests (redshift, deflection, Shapiro, weak-field waves) are recovered.

\noindent\textbf{QM/clock link.} To tie ``mass imposes delay'' to units, define a characteristic instruction interval $T_\ast$ by $mc^2T_\ast/\hbar=\alpha$ ($\alpha\!=\!2\pi$ recovers the Compton period). Massless propagation remains null (zero proper time), matching the textbook result.

\medskip
\noindent\textbf{Weak-field expectations.} In static weak fields with $|\phi|\!\ll\!1$,
\[
\frac{d\tilde\tau}{dt}\approx 1 + \frac{\Phi}{c^2} + \phi,
\]
so laboratory departures are expected to be \emph{tiny}; this note claims no large anomalies and treats experiments chiefly as constraints unless otherwise stated.

\section*{2.\;Decisive A/B null test (remote absorber toggle with LDOS control)}
\emph{Goal:} distinguish a pure local-LDOS picture (orthodox QED) from a minimal TLM coupling that allows a small dependence on boundary conditions compatible with $\tilde g_{\mu\nu}$.

\noindent\textbf{Setup.}
\begin{itemize}
\item Two identical single-photon emitters (e.g., solid-state or trapped-ion) inside matched high-$Q$ microcavities; continuous monitoring of the local density of optical states (LDOS) at each source via an in-situ probe.
\item A remotely switchable \emph{absorber path} attached to the output of one cavity only (electro-optic gate $\rightarrow$ long fiber $\rightarrow$ black, cold load), with isolators and back-reflection monitors to guarantee that the \emph{local} cavity LDOS at the source is unchanged when the remote absorber is toggled.
\item Measure spontaneous-emission lifetime and linewidth at both sources while toggling the remote absorber on one arm; interleave A/B blocks and swap roles.
\end{itemize}

\noindent\textbf{Predictions.}
\begin{itemize}
\item \textbf{Orthodox (QED/GR):} If the local LDOS and near-field boundary conditions at the emitter are unchanged, the spontaneous-emission rate and linewidth are invariant under remote toggling (null).
\item \textbf{Minimal TLM (this note):} A permitted, conformally induced correction can be parameterized as a tiny fractional shift
$\delta\Gamma/\Gamma \equiv \epsilon_{\rm TLM}$,
bounded by clock/PPN constraints; \emph{a measured non-zero} $\epsilon_{\rm TLM}$ with verified LDOS invariance would favor TLM-style boundary dependence.
\end{itemize}

\noindent\textbf{Controls.} (i) Continuous heterodyne to limit residual back-reflections $<\!10^{-5}$; (ii) in-cavity probe to certify LDOS constancy within statistical error; (iii) environmental swaps and blind toggles.

\noindent\textbf{Outcome.} A null result tightens an explicit upper bound on $\epsilon_{\rm TLM}$; a non-null result (after controls) is a discriminator.

\section*{3.\;How this integrates the series}
This addendum serves as the \emph{consistency anchor} for: the Generalized Pairing Law; the photon as non-traveler/transfer ontology; absorption-frame dynamics; and the Quanta Transfer Law. Please add these as Related Identifiers (``IsSupplementedBy/IsPartOf'') in Zenodo so readers can navigate proofs and derivations.

\medskip
\noindent\textbf{Scope note.} Agency/branching and cosmological speculations are intentionally excluded here; this is a compact, test-first baseline.

\bigskip
\noindent\textit{Keywords:} Timeless Light Model; scalar--tensor effective theory; conservation; LDOS; null test; preprint.

\end{document}

```

</details>

---
{% endraw %}
