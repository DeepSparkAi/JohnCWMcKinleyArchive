---
layout: default
title: '[2026] Hawking Radiation Is an Exterior Result: A Short Interpretive No-Go on Interior Ontology'
description: 'Publication metadata and archived raw LaTeX source by John C. W. McKinley.'
permalink: /papers/hawking-radiation-is-an-exterior-result-a-short-interpretive-no-go-on-interior-ontology/
paper: true
---
{% raw %}
# [2026] Hawking Radiation Is an Exterior Result: A Short Interpretive No-Go on Interior Ontology
*   **DOI:** [10.5281/zenodo.20100228](https://doi.org/10.5281/zenodo.20100228)
*   **Date:** 12 May 2026

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
\lhead{Hawking Radiation Is an Exterior Result}
\rhead{John C. W. McKinley}
\cfoot{\thepage}

\newtheorem{proposition}{Proposition}[section]
\newtheorem{definition}[proposition]{Definition}
\newtheorem{remark}[proposition]{Remark}
\newtheorem{corollary}[proposition]{Corollary}

\title{\textbf{Hawking Radiation Is an Exterior Result}\\
\large A Short Interpretive No-Go on Interior Ontology}
\author{John C. W. McKinley \orcidlink{0009-0005-7097-5035}}
\date{May 12, 2026}

\begin{document}

\maketitle

\blfootnote{\scriptsize This version prepared for Zenodo. DOI: \href{https://doi.org/10.5281/zenodo.20100229}{10.5281/zenodo.20100229}.}

\begin{abstract}
Hawking radiation is a result about exterior observables. The standard derivation relates an initial vacuum state to late-time exterior particle content through quantum field modes on a collapsing black-hole spacetime. Its measurable outputs are the thermal flux detected at future infinity and the corresponding decrease of the black hole's asymptotic mass. This note states a narrow interpretive no-go result: the Hawking derivation does not, by itself, license an interior ontology. It does not establish what an infalling observer experiences, what localized field configuration exists behind the horizon, or whether a negative-energy particle literally falls inward and reduces the black hole's mass. Those are additional interpretive or theoretical claims. The exterior calculation licenses exterior radiation and exterior mass loss. It does not license interior narration.
\end{abstract}

\section{Introduction}

Hawking radiation is commonly described as if the calculation tells a complete story about both sides of the event horizon. A virtual pair appears; one member escapes; the other falls into the black hole with negative energy; the black hole loses mass. This story is useful as a teaching image, but it says more than the standard derivation establishes.

The standard Hawking result is formulated in terms of field modes, observer-relative particle content, thermal flux at future infinity, and mass measured by the asymptotic geometry. These are exterior or asymptotic quantities. They do not, by themselves, settle what occurs behind the horizon.

This note states a narrow no-go result. The claim is not that black-hole interiors do not exist. The claim is not that no future theory can describe the interior. The claim is not that semiclassical gravity is false. The claim is narrower: the standard Hawking derivation does not license interior ontology. The issue here is not merely whether a particle travels from inside the black hole to the exterior; it is whether an exterior calculation licenses any interior story at all.

An exterior derivation licenses exterior observables. It does not, by itself, license an interior story.

\section{Exterior Structure of the Hawking Result}

In the standard treatment, one studies a quantum field on a spacetime that begins with regular asymptotic structure and later forms a black hole by collapse. The field is assigned an initial vacuum state, usually described at past null infinity. Late-time observers at future null infinity decompose the field into outgoing modes and assign particle content to the state using the corresponding mode basis.

The Hawking effect arises because the early and late mode decompositions do not match. A state that is vacuum relative to the early basis is not vacuum relative to the late exterior basis. The Bogoliubov transformation between the two descriptions yields nonzero late-time occupation numbers and a thermal spectrum.

For a Schwarzschild black hole, the exterior temperature measured at infinity is
\[
T_H = \frac{\hbar c^3}{8\pi G M k_B}.
\]
The outgoing radiation carries positive energy to infinity. In the standard semiclassical extension of Hawking's result, the corresponding black-hole mass, as measured by the asymptotic geometry, decreases.

These statements are physical. The radiation is real. The mass loss is real. The no-go concerns only the inference from these exterior facts to an interior ontology.

\section{Definitions}

\begin{definition}[Exterior observable]
An exterior observable is a quantity defined for observers or measurements outside the black-hole horizon, especially at asymptotic infinity, such as outgoing flux, exterior particle content, and ADM mass.
\end{definition}

\begin{definition}[Interior ontology]
Interior ontology is a claim about what exists, occurs, or is experienced behind the event horizon, including claims about localized particles, negative-energy objects, field configurations, or infalling-observer experience.
\end{definition}

\begin{definition}[Interior narration]
Interior narration is the explanatory move of converting an exterior result into a story about events or objects behind the horizon.
\end{definition}

\begin{definition}[Frame restriction]
Frame restriction is the interpretive rule that a result defined in one descriptive regime cannot be used, without additional argument, to assert ontology in another regime.
\end{definition}

\section{The No-Go Result}

\begin{proposition}[The Hawking derivation is exterior-asymptotic]
The standard Hawking derivation establishes late-time exterior radiation by relating early and late field-mode decompositions. It does not require an independently specified interior particle history.
\end{proposition}

\begin{proof}
The derivation begins with an initial field state and compares mode decompositions associated with past and future asymptotic descriptions. The thermal result is read by late-time exterior observers, especially at future infinity. The calculation yields exterior particle content and outgoing flux. None of these steps requires the identification of a localized particle configuration behind the horizon. Therefore the standard derivation is exterior-asymptotic in its operative content.
\end{proof}

\begin{proposition}[ADM mass loss is an exterior statement]
The decrease of black-hole mass in Hawking evaporation is a real physical statement about the asymptotic geometry, but it is not an interior narrative.
\end{proposition}

\begin{proof}
The relevant black-hole mass in the standard evaporation statement is defined by the exterior spacetime, in particular by the mass parameter measured at infinity. In the standard semiclassical extension of Hawking's result, if outgoing radiation carries positive energy to infinity, then conservation requires a corresponding decrease in the mass attributed to the black hole by the asymptotic geometry. This establishes real exterior mass loss. It does not specify a localized interior mechanism, an infalling object, or an interior observer's account of that loss. Therefore ADM mass loss is an exterior statement, not an interior ontology.
\end{proof}

\begin{proposition}[Negative-energy infall is not licensed ontology]
The common statement that a negative-energy particle falls into the black hole is not established as literal interior ontology by the Hawking derivation.
\end{proposition}

\begin{proof}
The negative-energy-infall story is a heuristic device for representing energy conservation in the pair-creation picture. The standard field-theoretic result does not require a localized negative-energy particle behind the horizon. It requires an outgoing exterior flux and a corresponding decrease in the black hole's asymptotic mass. A bookkeeping narration that helps preserve conservation in a visual model does not establish the existence of the narrated interior object. Therefore negative-energy infall is not licensed ontology.
\end{proof}

\begin{proposition}[Interior experience is not determined by exterior flux]
The exterior detection of Hawking radiation does not determine what an infalling observer experiences behind the horizon.
\end{proposition}

\begin{proof}
Particle content is observer-relative in quantum field theory on curved spacetime. A late-time observer at infinity assigns particle content using an exterior mode decomposition. An infalling observer uses a different local description. In the standard semiclassical picture, an infalling observer crossing the horizon detects locally regular vacuum, not the thermal flux registered at infinity. The fact that radiation is detected at infinity therefore does not, by itself, determine the infalling observer's particle content, field description, or horizon-crossing experience. Thus exterior flux does not determine interior experience.
\end{proof}

\begin{proposition}[Interior ontology requires additional theory]
Claims about the black-hole interior during evaporation require assumptions or formalisms beyond the standard exterior Hawking derivation.
\end{proposition}

\begin{proof}
Questions about the interior include the field state behind the horizon, the fate of infalling information, the experience of an infalling observer, the role of backreaction, and the ultimate resolution of the singularity. The standard Hawking derivation supplies an exterior thermal flux and a corresponding asymptotic mass decrease. It does not resolve these interior questions. Therefore any determinate interior ontology requires additional theoretical commitments beyond the exterior derivation itself.
\end{proof}

\section{The Negative-Energy Story Revisited}

The negative-energy story is the most common way interior ontology enters public explanations of Hawking radiation. The story says that a virtual pair appears at the horizon, the positive-energy member escapes, and the negative-energy member falls inward, reducing the black hole's mass.

This narration is stronger than the derivation. The derivation requires an exterior flux and exterior mass loss. It does not require a literal interior particle doing the subtraction.

The black hole's mass loss is real. The outgoing radiation is real. What is denied is the extra claim that the mass loss has been explained by a localized negative-energy object traveling inward behind the horizon.

The clean statement is:

\begin{quote}
The black hole loses mass as measured from the exterior. The standard Hawking derivation does not convert that exterior fact into an interior particle story.
\end{quote}

\section{Relation to Interior Debates}

The no-go stated here does not solve the black-hole information problem. It does not decide between complementarity, firewall proposals \cite{AMPS2013}, holographic reconstruction, entanglement-based interior proposals \cite{MaldacenaSusskind2013}, or other approaches to black-hole interiors. Its point is narrower and prior: the standard Hawking derivation itself does not supply the interior ontology that those debates contest.

This is why the existence of those debates is significant. If the exterior Hawking calculation already fixed the interior story, there would be no need for competing accounts of horizon crossing, interior reconstruction, information recovery, or breakdown of semiclassical smoothness. The persistence of those disputes reflects the limited scope of the original result.

The no-go is therefore conservative. It does not deny that interior questions matter. It denies only that the standard exterior calculation has already answered them.

\section{Conclusion}

Hawking radiation is an exterior result.

The standard derivation establishes thermal radiation detected by late-time exterior observers and a corresponding decrease in black-hole mass as measured by the asymptotic geometry. These are real physical results. But they do not, by themselves, establish what exists, occurs, or is experienced inside the horizon.

The negative-energy particle story is therefore not licensed as literal interior ontology. It is an explanatory narration attached to an exterior result.

The no-go is simple: exterior radiation and exterior mass loss do not license interior narration.

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

\bibitem[Almheiri et al.(2013)]{AMPS2013}
A.~Almheiri, D.~Marolf, J.~Polchinski, and J.~Sully.
\newblock Black holes: complementarity or firewalls?
\newblock \emph{Journal of High Energy Physics} \textbf{2013}, 62 (2013).
\newblock \doi{10.1007/JHEP02(2013)062}.

\bibitem[Maldacena and Susskind(2013)]{MaldacenaSusskind2013}
J.~Maldacena and L.~Susskind.
\newblock Cool horizons for entangled black holes.
\newblock \emph{Fortschritte der Physik} \textbf{61}, 781--811 (2013).
\newblock \doi{10.1002/prop.201300020}.

\end{thebibliography}

\end{document}
```

</details>

---
{% endraw %}
