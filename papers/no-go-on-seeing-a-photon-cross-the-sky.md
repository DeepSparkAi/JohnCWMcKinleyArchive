---
layout: default
title: '[2026] No-Go on Seeing a Photon Cross the Sky'
description: 'Publication metadata and archived raw LaTeX source by John C. W. McKinley.'
permalink: /papers/no-go-on-seeing-a-photon-cross-the-sky/
paper: true
---
{% raw %}
# [2026] No-Go on Seeing a Photon Cross the Sky

* **DOI:** [10.5281/zenodo.20225004](https://doi.org/10.5281/zenodo.20225004)

* **Date:** May 15, 2026

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
\usepackage{fancyhdr}

\newtheorem{proposition}{Proposition}[section]
\newtheorem{definition}[proposition]{Definition}
\newtheorem{remark}[proposition]{Remark}
\newtheorem{lemma}[proposition]{Lemma}

\usepackage{cleveref}
\usepackage{orcidlink}

\newcommand\blfootnote[1]{%
  \begingroup
  \renewcommand\thefootnote{}\footnote{#1}%
  \addtocounter{footnote}{-1}%
  \endgroup
}

\newcommand{\doi}[1]{\href{https://doi.org/#1}{#1}}

\setlength{\headheight}{14pt}
\pagestyle{fancy}
\fancyhf{}
\lhead{No-Go on Seeing a Photon Cross the Sky}
\rhead{John C. W. McKinley}
\cfoot{\thepage}

\title{\textbf{No-Go on Seeing a Photon Cross the Sky}}
\author{John C. W. McKinley \orcidlink{0009-0005-7097-5035}}
\date{May 15, 2026}

\begin{document}

\maketitle

\blfootnote{\scriptsize This version published at \url{https://doi.org/10.5281/zenodo.20225003}.}

\begin{abstract}
No photon has ever been seen in flight. Every observation of light is a
registration at a detector, never an observation of a photon between emission
and absorption. This is built into standard photodetection theory. This paper
states the narrow no-go: no procedure exists, has existed, or is available
within standard physics by which a photon in flight is observed without that
observation itself constituting a registration. The fact is built into the
standard treatment of quantum optics, in which photodetection is modeled as
photon absorption at the detector. The argument introduces no new equations
and no modification to relativity, quantum mechanics, or quantum field theory.
It is an empirical no-go on seeing a photon in flight.
\end{abstract}


\section{Introduction}

The intuitive picture is familiar. Light leaves the sun, crosses ninety-three
million miles of space, and arrives at the eye. The crossing is imagined as a
sight: a thing in flight, traversing the sky, observable in principle if not
in practice.

No such sight has ever been recorded. Every observation of light is a
registration event at a detector---an eye, a photographic emulsion, a
charge-coupled device, a photomultiplier, an atom in an excited state. The
photon, as such, has never been caught in flight. This is built into the
standard treatment of quantum optics \citep{Glauber1963}.

The present paper states the narrow no-go that follows: no procedure exists by
which a photon in flight is observed without that observation itself
constituting a registration. The paper makes no claim about what is or is not
the case between emission and absorption. It claims only that the seeing has
never occurred and that no procedure for it is available.

The constant $c$, Maxwell's equations, quantum electrodynamics, and the full
operational apparatus of optics remain untouched. The numerical predictions of
standard physics are unchanged. The claim is observational.


\section{The No-Go}

\begin{definition}[Registration]
A registration is a detector-side event at which a photon-related outcome is
recorded. Emission and absorption are registrations. Scattering at an
intermediate medium consists of further registrations.
\end{definition}

\begin{definition}[Seeing a photon in flight]
To see a photon in flight is to observe the photon at a spacetime point that
is neither its emission event nor its absorption event, without that
observation itself constituting a registration.
\end{definition}

\begin{proposition}[No photon has been seen in flight]
\label{prop:noflight}
No photon has been observed at a spacetime point between its emission and its
absorption without that observation itself constituting a registration.
\end{proposition}

\begin{proof}
This is built into the standard treatment of photodetection in quantum
optics, in which detection of a photon is modeled as absorption of the
photon at the detector and the detector-side registration is the observation
\citep{Glauber1963}. No auxiliary observational channel is supplied by the
theory: there is no procedure by which a photon between its emission and its
absorption is observed without that observation itself constituting a
registration.
\end{proof}

\begin{remark}
The apparent visibility of light in flight through fog, dust, or smoke is not
a counterexample. Each visible point along the apparent path is a scattering
center at which an incoming photon is absorbed and an outgoing photon is
emitted in a new direction. The photons that reach the side-viewer's eye are
those re-emitted photons, not the originals; the originals terminated at the
scattering centers. The visible streak is therefore a sequence of fresh
emission-absorption events, not an observation of any photon between
registrations.
\end{remark}

\begin{proposition}[The narrow no-go]
\label{prop:nogo}
No procedure exists, has existed, or is available within standard physics by
which a photon in flight is observed without that observation itself
constituting a registration.
\end{proposition}

\begin{proof}
By \Cref{prop:noflight}, no such observation has been recorded. The detection
of a photon proceeds by absorption at a detector; the registration is the
observation. Any procedure that placed a detector at an intermediate spacetime
point would constitute a fresh absorption at that point, terminating the
prior emission-to-detector relation at the new detector rather than producing
an observation of a photon between registrations. No auxiliary observational
channel is supplied by the theory. Therefore the seeing is unavailable.
\end{proof}

\begin{remark}
The premise is free. It is built into the standard treatment. The no-go
follows without added ontology.
\end{remark}


\section{Relation to Other Work}

This note is intentionally narrower than the broader photon-side analysis
developed elsewhere. The null-proper-time, no-rest-frame, no-carrier, and
minimal structural arguments appear in related papers
\citep{McKinleyNullProperTime2025,McKinleyNoRestFrame2025,McKinleyNullCurves2025,McKinleyBedrock2026}.
The present note needs only the observational premise: seeing a photon in
flight is not an available operation.


\section{Scope}

The argument introduces no new equations, no new observables, and no
modification to special relativity, general relativity, quantum mechanics, or
quantum field theory. The value and operational role of $c$ are unchanged.
Maxwell's equations are unchanged. Quantum electrodynamics is unchanged. The
predictions of standard optics are unchanged.

The claim is only that no photon has been seen in flight and that no procedure
for such a seeing is available. The paper takes no position on what is or is
not the case between emission and absorption.


\section{Conclusion}

The intuitive picture is of light crossing the sky as a thing in flight. The
crossing, as a sight, has never been recorded. No procedure for recording it
is supplied by standard physics. The fact is built into the treatment.

What is denied is only the seeing. The denial is observational. The
operational apparatus of physics, the numerical value of $c$, and the
predictions of optics are unaffected.

No photon has been seen in flight.


\begin{thebibliography}{99}

\bibitem{Glauber1963}
R. J. Glauber, \emph{The Quantum Theory of Optical Coherence},
Physical Review \textbf{130}, 2529--2539 (1963). \doi{10.1103/PhysRev.130.2529}.

\bibitem{McKinleyNullProperTime2025}
J. C. W. McKinley, \emph{Taking Null Proper Time Seriously: An Interpretive Clarification of Null Proper Time},
Zenodo (2025). \doi{10.5281/zenodo.18004632}.

\bibitem{McKinleyNoRestFrame2025}
J. C. W. McKinley, \emph{No Rest Frame, No Persistence: A Kinematic Constraint on Photon Interpretation},
Zenodo (2025). \doi{10.5281/zenodo.18005884}.

\bibitem{McKinleyNullCurves2025}
J. C. W. McKinley, \emph{Null Curves Without Carriers: Resolving an Ontological Tension in Relativistic Geometry},
Zenodo (2025). \doi{10.5281/zenodo.18028886}.

\bibitem{McKinleyBedrock2026}
J. C. W. McKinley, \emph{A Minimal Structural Statement of the Timeless Light Model},
Zenodo (2026). \doi{10.5281/zenodo.19167403}.

\end{thebibliography}

\end{document}
```

</details>

---
{% endraw %}
