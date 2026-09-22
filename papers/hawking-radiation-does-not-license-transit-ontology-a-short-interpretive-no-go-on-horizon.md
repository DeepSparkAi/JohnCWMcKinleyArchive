---
layout: default
title: '[2026] Hawking Radiation Does Not License Transit Ontology: A Short Interpretive No-Go on Horizon-Conditioned Particle Appearance'
description: 'Publication metadata and archived raw LaTeX source by John C. W. McKinley.'
permalink: /papers/hawking-radiation-does-not-license-transit-ontology-a-short-interpretive-no-go-on-horizon/
paper: true
---
{% raw %}
# [2026] Hawking Radiation Does Not License Transit Ontology: A Short Interpretive No-Go on Horizon-Conditioned Particle Appearance
*   **DOI:** [10.5281/zenodo.20099663](https://doi.org/10.5281/zenodo.20099663)
*   **Date:** 11 May 2026

<details markdown="1">
<summary><b>Click to view Raw LaTeX Source</b></summary>

```latex
\documentclass[12pt,onecolumn]{article}

\usepackage[utf8]{inputenc}
\usepackage[T1]{fontenc}
\usepackage{lmodern}
\usepackage[margin=1in]{geometry}
\usepackage{setspace}
\usepackage{microtype}
\usepackage{amsmath,amssymb,amsthm,bm}
\usepackage{booktabs}
\usepackage{float}

\PassOptionsToPackage{capitalise,nameinlink,noabbrev}{cleveref}
\usepackage[numbers,sort&compress]{natbib}
\usepackage[colorlinks=true,linkcolor=blue,citecolor=blue,urlcolor=blue]{hyperref}
\newcommand{\doi}[1]{\href{https://doi.org/#1}{#1}}
\usepackage{cleveref}
\usepackage{orcidlink}
\usepackage{fancyhdr}

\newcommand\blfootnote[1]{%
  \begingroup
  \renewcommand\thefootnote{}\footnote{#1}%
  \addtocounter{footnote}{-1}%
  \endgroup
}

\setlength{\headheight}{14pt}
\pagestyle{fancy}
\fancyhf{}
\lhead{Hawking Radiation Does Not License Transit Ontology}
\rhead{John C. W. McKinley}
\cfoot{\thepage}

\newtheorem{proposition}{Proposition}[section]
\newtheorem{definition}[proposition]{Definition}
\newtheorem{remark}[proposition]{Remark}
\newtheorem{corollary}[proposition]{Corollary}

\title{\textbf{Hawking Radiation Does Not License Transit Ontology}\\
\large A Short Interpretive No-Go on Horizon-Conditioned Particle Appearance}
\author{John C. W. McKinley \orcidlink{0009-0005-7097-5035}}
\date{May 11, 2026}

\begin{document}

\maketitle

\blfootnote{\scriptsize This version prepared for Zenodo. DOI: \href{https://doi.org/10.5281/zenodo.20099664}{10.5281/zenodo.20099664}.}

\begin{abstract}
Hawking radiation is often introduced through the heuristic image of virtual particle pairs forming near a black-hole horizon, with one particle falling inward and the other escaping outward. This note states a narrow interpretive no-go result: that narration does not license transit ontology. In the standard quantum-field-theoretic account, Hawking radiation arises from the mismatch between field-mode decompositions associated with the pre-collapse and late-time exterior descriptions. A late-time exterior observer detects a thermal flux because the in-vacuum is not empty relative to the exterior mode basis. This does not establish that a photon, particle, or quantum traveled from the black-hole interior to infinity. Lawful detection does not imply carrier history. The horizon licenses exterior appearance under horizon-conditioned field structure, not transit.
\end{abstract}

\section{Introduction}

Hawking radiation is real physics. The common particle-pair story is not the ontology of that physics.

The standard public description says that a virtual pair appears near the event horizon, one member falls into the black hole, and the other escapes as radiation. This image is pedagogically useful, but it invites the wrong interpretive conclusion. It suggests that a particle has a horizon-straddling history and that the escaping radiation is a traveler that originated behind, at, or just inside the horizon.

This note rejects that conclusion. The claim is not that Hawking radiation is false. The claim is not that quantum field theory in curved spacetime fails. The claim is narrower: the detection of Hawking radiation does not license the assertion that a photon or particle traveled from the black-hole interior to the exterior.

The present claim is independent of any proposed modification to physics. It is an interpretive restriction on what the standard account of Hawking radiation permits one to infer.


\section{Background: The Standard Field-Theoretic Structure}

In quantum field theory on curved spacetime, ``particle'' is not primitive in the same way as the field. Particle number is defined relative to a mode decomposition. That decomposition depends on the relevant time parameter and the observer's asymptotic description.

For a collapsing spacetime that forms a black hole, the natural mode basis in the asymptotic past does not match the natural mode basis in the asymptotic future. A field state that is vacuum with respect to the early-time basis is not vacuum with respect to the late-time exterior basis. The Bogoliubov transformation between these bases mixes positive- and negative-frequency components. The late-time exterior observer therefore assigns nonzero occupation numbers to the field state.

Hawking's result is that the exterior flux measured at future infinity is thermal, with temperature
\[
T_H = \frac{\hbar c^3}{8\pi G M k_B}.
\]
This result concerns field modes, horizon geometry, and observer-relative particle content. It does not require a localized particle-object to travel from the black-hole interior to the exterior.

This is the crucial interpretive point. Particle content is derivative of the chosen mode decomposition; it is not a primitive inventory of localized objects. A particle count assigned by a late-time exterior observer is therefore a result of field-state representation relative to that observer's mode basis, not proof of an occupied route from the black-hole interior to the exterior.

\section{Definitions}

\begin{definition}[Transit ontology]
Transit ontology is the claim that a detected quantum must be interpreted as a persisting object that occupied intermediate spacetime locations along a route between origin and detection.
\end{definition}

\begin{definition}[Horizon-conditioned particle appearance]
A horizon-conditioned particle appearance is a detection event assigned particle content by an exterior observer because the field-mode decomposition appropriate to that exterior description differs from the mode decomposition associated with the initial state.
\end{definition}

\begin{definition}[Transit refusal]
Transit refusal is the interpretive rule that a successful prediction of detection does not, by itself, establish a persisting carrier history, intermediate occupancy, route, or in-flight state.
\end{definition}

\section{The No-Go Result}

\begin{proposition}[Pair narration does not establish particle ontology]
The virtual-pair narration of Hawking radiation does not establish that two localized particle-objects literally appear at the horizon, with one falling inward and the other escaping outward.
\end{proposition}

\begin{proof}
The virtual-pair narration is a heuristic rendering of a field-theoretic result. The actual derivation concerns the relation between early and late field-mode decompositions on a curved background. The thermal exterior flux follows from mode mixing and the observer-relative assignment of particle content. A heuristic story that assists visualization does not supply additional ontology beyond the derivation it summarizes. Therefore the pair narration does not establish literal horizon-straddling particle objects.
\end{proof}

\begin{proposition}[Mode mixing does not imply path occupancy]
Bogoliubov mixing between early and late field modes predicts exterior particle content, but it does not identify an intermediate particle path.
\end{proposition}

\begin{proof}
A Bogoliubov transformation relates one field-mode basis to another. Its coefficients determine how the vacuum of one basis is represented in another basis. The result is an exterior occupation number relative to the late-time observer's mode decomposition. A relation between mode bases is not a spacetime trajectory. It does not assign a photon rest frame, an internal clock, or a sequence of occupied intermediate locations. Hence mode mixing does not imply path occupancy.
\end{proof}

\begin{proposition}[Exterior detection does not imply interior transit]
The exterior detection of a Hawking quantum does not entail that the detected quantum previously existed inside the black hole.
\end{proposition}

\begin{proof}
Exterior detection establishes that the exterior field state contains detectable excitation relative to the observer's mode basis. It does not establish that the detected quantum possessed a prior localized identity in the black-hole interior. The field-theoretic account supplies an exterior flux and a corresponding energy balance. It does not supply a carrier history from the interior to infinity. Therefore exterior detection does not imply interior transit.
\end{proof}

\begin{proposition}[Tunneling language does not rescue transit ontology]
The semiclassical tunneling formulation of Hawking radiation does not license the conclusion that a photon or particle has a continuous transit history through the horizon.
\end{proposition}

\begin{proof}
The tunneling formulation computes an emission amplitude using a classical trajectory and the imaginary part of its action across the horizon pole. The classical path appearing in the calculation is a calculational object: it is the path along which the action is evaluated to extract a rate, not an experimentally licensed worldline of a persistent quantum carrier. The formulation gives an emission probability and a backreaction-corrected spectrum. It does not supply a photon rest frame, photon proper time, or a measurement-licensed continuous interior-to-exterior carrier history. A tunneling probability evaluated along a classical path is not a proof of persistent objecthood along that path. Therefore tunneling language does not rescue transit ontology.
\end{proof}

\section{The Negative-Energy Story}

The common statement that a negative-energy particle falls into the black hole is also bookkeeping language. The physical conservation statement is that the outgoing flux carries positive energy to infinity, while the black hole's mass decreases. The geometry and global energy accounting balance the emission.

Treating the inward member as a literal negative-energy object repeats the same error as the virtual-pair picture. It turns calculational bookkeeping into particle ontology. The no-go result applies equally here: energy balance does not license an interior particle story.


\section{Conclusion}

Hawking radiation is not evidence for a particle route out of a black hole.

The rigorous account concerns quantum fields, curved spacetime, mode decompositions, and observer-relative particle content. The public pair-creation story is a teaching image. It does not establish that a photon or particle traveled from inside the black hole to the exterior. Even the tunneling formulation gives an emission probability, not a photon history.

The no-go result is therefore simple: Hawking radiation licenses exterior appearance under horizon-conditioned field structure, not black-hole particle escape.

\begin{thebibliography}{9}

\bibitem[Hawking(1975)]{Hawking1975}
S.~W. Hawking.
\newblock Particle creation by black holes.
\newblock \emph{Communications in Mathematical Physics} \textbf{43}, 199--220 (1975).
\newblock \doi{10.1007/BF02345020}.

\bibitem[Unruh(1976)]{Unruh1976}
W.~G. Unruh.
\newblock Notes on black-hole evaporation.
\newblock \emph{Physical Review D} \textbf{14}, 870--892 (1976).
\newblock \doi{10.1103/PhysRevD.14.870}.

\bibitem[Parikh and Wilczek(2000)]{ParikhWilczek2000}
M.~K. Parikh and F.~Wilczek.
\newblock Hawking radiation as tunneling.
\newblock \emph{Physical Review Letters} \textbf{85}, 5042--5045 (2000).
\newblock \doi{10.1103/PhysRevLett.85.5042}.

\end{thebibliography}

\end{document}
```

</details>

---
{% endraw %}
