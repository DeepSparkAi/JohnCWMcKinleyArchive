---
layout: default
title: '[2026] Local Accrual as the Only Intrinsic Time-Quantity: A Positive Structural Statement for the Massive Regime'
description: 'Publication metadata and archived raw LaTeX source by John C. W. McKinley.'
permalink: /papers/local-accrual-as-the-only-intrinsic-time-quantity-a-positive-structural-statement-for-the/
paper: true
---
{% raw %}
# [2026] Local Accrual as the Only Intrinsic Time-Quantity: A Positive Structural Statement for the Massive Regime

* **DOI:**  [10.5281/zenodo.20225645](https://doi.org/10.5281/zenodo.20225645)

* **Date:**  2026-05-15

<details markdown="1">
<summary><b>Click to view Raw LaTeX Source</b></summary>

```latex
\PassOptionsToPackage{capitalise,nameinlink,noabbrev}{cleveref}
\documentclass[11pt]{article}

\usepackage[margin=1in]{geometry}
\usepackage{amsmath,amssymb,amsthm}
\usepackage{hyperref}
\hypersetup{colorlinks=true,linkcolor=blue,citecolor=blue,urlcolor=blue}
\usepackage{cleveref}
\usepackage{orcidlink}

\newcommand{\doi}[1]{\href{https://doi.org/#1}{#1}}
\newcommand{\blfootnote}[1]{%
  \begingroup
  \renewcommand\thefootnote{}\footnote{#1}%
  \addtocounter{footnote}{-1}%
  \endgroup
}

\newtheorem{proposition}{Proposition}
\newtheorem{corollary}[proposition]{Corollary}
\newtheorem{lemma}[proposition]{Lemma}
\theoremstyle{definition}
\newtheorem{definition}{Definition}
\theoremstyle{remark}
\newtheorem*{remark}{Remark}

\title{Local Accrual as the Only Intrinsic Time-Quantity\\
\large A Positive Structural Statement for the Massive Regime}
\author{John C. W. McKinley\,\orcidlink{0009-0005-7097-5035}}
\date{May 15, 2026}

\begin{document}
\maketitle
\blfootnote{\scriptsize This version published at DOI: \doi{10.5281/zenodo.20225645}.}

\begin{abstract}
For a massive object, the locally accrued proper time along its worldline is the only time-quantity intrinsic to it. Coordinate time, registered dilation, simultaneity assignments, and any other time-like quantity associated with the object are between-frames relations, not intrinsic properties. This paper states that distinction as a positive structural claim. The accrual is the integral of the local clock-tick interval along the worldline; it requires no second frame, no coordinate choice, and no apparatus external to the worldline. Every other time-quantity standardly associated with the object requires such an external reference and is therefore relational. The claim is conservative with respect to Special and General Relativity: it states what the formalism already entails about which time-quantities are worldline-internal and which are between-frames. The contribution is interpretive only.
\end{abstract}

\section{Introduction}

Time-quantities associated with a massive object come in two structurally distinct kinds. The first is the proper time accrued along the object's worldline. The second is any time-quantity that requires a second frame, a coordinate choice, or an external apparatus to define. The two kinds are routinely conflated in expository physics. The conflation is harmless for calculation and harmful for interpretation.

This paper states the structural distinction as a positive claim. The locally accrued proper time is the only time-quantity intrinsic to the object. Everything else --- coordinate time, registered dilation, simultaneity assignments, retardation labels, frame-dependent timestamps --- is a between-frames relation.

The present paper makes the positive structural claim: what \emph{is} intrinsic is the local accrual along the worldline, and only that. The general registration framing on which this claim depends has been stated separately~\cite{mckinley_creg}. The null-case companion, in which no intrinsic time-quantity exists at all, has been stated separately~\cite{mckinley_nocount}.

The same positive content --- proper time as the worldline-internal path integral, environmental factors (mass, speed) as conditions on the integrand, the watch always feeling normal locally, the difference appearing only at comparison --- has been stated in conventional Special Relativity and General Relativity vocabulary in earlier work~\cite{mckinley_massspeed}. The present paper restates that result as a registration-interface structural claim anchored to~\cite{mckinley_creg}, in the vocabulary used throughout the Timeless Light Model corpus, and adds the explicit no-go on competing candidate intrinsic time-quantities.

The argument uses only standard relativistic kinematics~\cite{einstein1905,taylor_wheeler,wald}. No new equations, constants, or postulates are introduced. The claim is interpretive: it states which of the time-quantities licensed by the standard formalism are intrinsic, and which are relational.

\section{Definitions}

\begin{definition}[Worldline]
\label{def:worldline}
A worldline $\mathcal{W}$ is a timelike curve through spacetime, parametrized smoothly, representing the spacetime history of a massive object.
\end{definition}

\begin{definition}[Local clock-tick interval]
\label{def:dtau}
The local clock-tick interval $d\tau$ along $\mathcal{W}$ is the proper-time differential, defined as
\[
d\tau = \sqrt{-g_{\mu\nu}\, dx^\mu\, dx^\nu}\,/\,c
\]
in a metric signature where timelike intervals are negative. The differential is a property of $\mathcal{W}$ and the local metric. It is the interval read by an ideal co-moving clock following $\mathcal{W}$.
\end{definition}

\begin{definition}[Locally accrued proper time]
\label{def:accrual}
The locally accrued proper time of a worldline segment is
\[
\tau(\mathcal{W}) = \int_{\mathcal{W}} d\tau.
\]
The accrual is computed along the worldline using only $d\tau$ along that worldline. No second frame, no external coordinate system, and no apparatus outside the worldline is required for its definition.
\end{definition}

\begin{definition}[Intrinsic time-quantity]
\label{def:intrinsic}
A time-quantity associated with an object is intrinsic if its definition refers only to quantities defined on the object's worldline together with the local metric along that worldline. A time-quantity is relational, or between-frames, if its definition requires reference to a frame, coordinate system, or apparatus external to the object's worldline.
\end{definition}

\begin{definition}[Coordinate time]
\label{def:coord-time}
The coordinate time $t$ assigned to an event by an observer is the time-component of the event's coordinates in the observer's chosen coordinate system. Coordinate time is defined relative to the chosen system; a different system assigns a different coordinate time to the same event.
\end{definition}

\begin{definition}[Registered dilation]
\label{def:dilation}
The registered dilation of frame $B$'s clock by frame $A$'s apparatus is the relation $\Delta t_A = \gamma\, \Delta \tau_B$, where $\Delta \tau_B$ is the proper time accrued on $B$'s worldline between two events and $\Delta t_A$ is the coordinate-time separation $A$'s apparatus assigns to those events, with $\gamma = (1 - v^2/c^2)^{-1/2}$ and $v$ the relative velocity. The relation is defined only when both frames are specified.
\end{definition}

\begin{definition}[Simultaneity assignment]
\label{def:simultaneity}
A simultaneity assignment is a rule by which events at spatially distinct locations are labeled as occurring ``at the same time.'' The rule depends on the choice of reference frame and on the convention used to synchronize distant clocks. Different frames and different conventions yield different simultaneity assignments for the same set of events.
\end{definition}

\section{The Positive Claim}

\begin{proposition}[Local accrual is intrinsic]
\label{prop:accrual-intrinsic}
The locally accrued proper time $\tau(\mathcal{W})$ of an object's worldline is intrinsic to the object.
\end{proposition}

\begin{proof}
By \cref{def:accrual}, $\tau(\mathcal{W})$ is the integral of $d\tau$ along $\mathcal{W}$. By \cref{def:dtau}, $d\tau$ is a property of $\mathcal{W}$ and the local metric along $\mathcal{W}$. Both quantities are defined without reference to any frame, coordinate system, or apparatus external to $\mathcal{W}$. By \cref{def:intrinsic}, the resulting integrated quantity is intrinsic to the object.
\end{proof}

\begin{proposition}[Local accrual is reparametrization-invariant]
\label{prop:reparam}
The value of $\tau(\mathcal{W})$ for a given worldline segment is independent of the coordinate system used to compute it.
\end{proposition}

\begin{proof}
The proper-time differential $d\tau = \sqrt{-g_{\mu\nu}\, dx^\mu\, dx^\nu}/c$ is a scalar under coordinate transformations: $g_{\mu\nu}\, dx^\mu\, dx^\nu$ is constructed from contractions of tensors and is therefore coordinate-invariant. The integral of a scalar along a curve is independent of the coordinate parametrization of the curve. Therefore $\tau(\mathcal{W})$ has the same value in any coordinate system~\cite{wald}.
\end{proof}

\begin{proposition}[Coordinate time is relational]
\label{prop:coord-relational}
The coordinate time $t$ assigned to events on $\mathcal{W}$ is not intrinsic to the object.
\end{proposition}

\begin{proof}
By \cref{def:coord-time}, coordinate time depends on the choice of coordinate system. The coordinate system is external to $\mathcal{W}$: different systems assign different $t$ values to the same event on $\mathcal{W}$. By \cref{def:intrinsic}, a quantity whose definition requires a choice external to the worldline is relational, not intrinsic.
\end{proof}

\begin{proposition}[Registered dilation is relational]
\label{prop:dilation-relational}
The dilation registered for an object's clock is not intrinsic to the object.
\end{proposition}

\begin{proof}
By \cref{def:dilation}, registered dilation is defined only when two frames are specified: the frame $B$ whose clock is being registered and the frame $A$ whose apparatus performs the registration. The factor $\gamma$ contains the relative velocity, which is a between-frames quantity. Therefore the registered dilation is defined only in the presence of a second frame. By \cref{def:intrinsic}, it is relational.
\end{proof}

\begin{proposition}[Simultaneity is relational]
\label{prop:simultaneity-relational}
A simultaneity assignment for events including events on $\mathcal{W}$ is not intrinsic to the object.
\end{proposition}

\begin{proof}
By \cref{def:simultaneity}, a simultaneity assignment depends on the choice of frame and synchronization convention. Both are external to $\mathcal{W}$. Different frames and conventions produce different simultaneity assignments for the same events on $\mathcal{W}$. By \cref{def:intrinsic}, simultaneity is relational.
\end{proof}

\section{The Main Result}

\begin{proposition}[Local accrual is the only intrinsic time-quantity]
\label{prop:main}
Among the time-quantities standardly associated with a massive object, the locally accrued proper time along its worldline is the only one intrinsic to the object. All other standardly associated time-quantities --- coordinate time, registered dilation, simultaneity assignments, retardation labels, frame-dependent timestamps --- are relational.
\end{proposition}

\begin{proof}
By \cref{prop:accrual-intrinsic}, local accrual is intrinsic. By \cref{prop:reparam}, its value is independent of coordinate choice, confirming worldline-internal definition. By \cref{prop:coord-relational}, \cref{prop:dilation-relational}, and \cref{prop:simultaneity-relational}, coordinate time, registered dilation, and simultaneity are each relational. The same reasoning extends to any standardly associated time-quantity whose definition includes a frame choice, coordinate choice, synchronization convention, or external apparatus: each such quantity is, by \cref{def:intrinsic}, relational.

What remains is to verify that no further intrinsic time-quantity is available. An intrinsic time-quantity would have to be definable using only quantities on $\mathcal{W}$ and the local metric. The available constructions from those ingredients are: $d\tau$ itself; integrals of $d\tau$ over worldline segments, which reduce to $\tau(\mathcal{W})$ values; and functions of $\tau$ such as $\tau^2$ or $f(\tau)$, which are reparametrizations of the same underlying quantity. No structurally distinct intrinsic time-quantity is constructible from worldline-internal ingredients alone.

Therefore the locally accrued proper time is the only intrinsic time-quantity.
\end{proof}

\begin{corollary}[Asymmetric aging is a worldline-internal fact]
\label{cor:aging}
The age difference between two objects that meet at a common event after following different worldlines is a difference in their respective locally accrued proper times.
\end{corollary}

\begin{proof}
The age of each object at a given event on its worldline is the locally accrued proper time from a reference event on the same worldline to that event. By \cref{prop:main}, this is an intrinsic worldline-internal quantity. When two worldlines meet at a common terminal event, the difference between their accrued proper times is a difference between two worldline-internal quantities. The asymmetry is determined entirely by the shapes of the two worldlines and the local metric along them. No frame choice, registered dilation, or simultaneity assignment is required to define the difference.
\end{proof}

\begin{corollary}[Decay outcomes are worldline-internal]
\label{cor:decay}
Whether an unstable particle decays before reaching a given event is determined by the proper time accrued along the particle's worldline relative to the proper time required for decay.
\end{corollary}

\begin{proof}
The decay process of an unstable particle is governed by quantities defined on the particle's worldline: its proper lifetime and its locally accrued proper time. By \cref{prop:main}, both are intrinsic worldline-internal quantities. The decay-or-survival outcome at a given event is determined by the comparison of these two intrinsic quantities. No registration by an external frame is required for the outcome itself, though external frames may register the outcome through their own apparatus.
\end{proof}

\section{The Standard Twin and Muon Cases}

The framework is conservative with respect to the standard relativistic results~\cite{mckinley_massspeed}.

In the twin scenario, the traveling twin's worldline and the staying twin's worldline meet at the reunion event. Each worldline has accrued its own locally accrued proper time between the departure event and the reunion event. The traveling twin's worldline has accrued less. The age difference is a fact about the two integrated proper times. By \cref{cor:aging}, the asymmetry is intrinsic to the worldlines and requires no frame-dependent claim about ``whose clock was really running slow.''

In the muon case, the muon's worldline accrues proper time from production in the upper atmosphere to either decay or ground impact, whichever occurs first along the worldline. If the worldline reaches the ground event before the proper-time-required-for-decay has accrued, the muon arrives. By \cref{cor:decay}, the outcome is determined worldline-internally. The Earth frame registers the muon's flight as taking longer than its proper lifetime, which is the standard dilation relation; but the survival outcome is fixed by the muon's own integrated proper time, not by any registration.

Both standard results emerge from the worldline-internal accrual together with the local metric. The registration relations are consistent with the results but do not produce them.

\section{Why the Distinction Matters}

If local accrual is conflated with the relational time-quantities, two errors follow.

The first error is the assumption that a frame's clock has been slowed in itself when registered as dilated by another frame. The present positive claim explains what remains: each frame's clock continues to accrue at its proper rate along its worldline, regardless of how it is registered.

The second error is the assumption that asymmetric outcomes --- aging at reunion, particle survival, GPS clock offsets --- require selecting a privileged frame whose dilation reading is ``correct.'' The present claim removes the need for privilege selection. Asymmetric outcomes are produced by differences between worldline-internal accruals. Different frames register the same outcomes through their respective between-frames relations, all of which are consistent with the worldline-internal facts.

Removing both errors leaves the standard formalism intact and clarifies which quantities in it are properties of objects and which are relations between frames.

\section{Relation to the Null Regime}

The present claim concerns the massive regime. It does not extend without modification to the null regime.

In the null regime, the proper-time differential along a photon-associated null relation vanishes: $d\tau = 0$ everywhere along the relation. The integral of $d\tau$ along such a relation is zero, and no clock can be associated with it. The construction by which an intrinsic time-quantity is defined for a massive object --- integration of $d\tau$ along a timelike worldline --- has no analog. The null companion result~\cite{mckinley_nocount} accordingly states that no intrinsic time-quantity exists for the null case at all; only spacetime-side endpoint registrations are available.

The structural asymmetry between the regimes is therefore: in the massive regime, one intrinsic time-quantity exists (local accrual) and all other time-quantities are relational; in the null regime, no intrinsic time-quantity exists and all available time-related descriptions are between endpoint registrations. The general registration framing~\cite{mckinley_creg} accommodates both cases.

\section{Conservativeness}

The present paper introduces no new formal content. It does not modify Special Relativity, General Relativity, quantum mechanics, or quantum field theory. It does not modify the metric structure of spacetime, the invariance of $c$, or any predictive relation. The proper-time integral is the standard one; the dilation relation is the standard one; the coordinate-time and simultaneity definitions are the standard ones.

The contribution is interpretive: it states which of the standardly recognized time-quantities are worldline-internal and which are between-frames, and it identifies the locally accrued proper time as the unique member of the first category. The empirical content of relativity is unaffected.

\section{Conclusion}

For a massive object, the locally accrued proper time along its worldline is the only time-quantity intrinsic to it. The accrual is computed from $d\tau$ along the worldline and the local metric, using nothing external. Every other time-quantity standardly associated with the object --- coordinate time, registered dilation, simultaneity, frame-dependent timestamps --- requires reference to a frame, coordinate system, synchronization convention, or external apparatus, and is therefore a between-frames relation.

The asymmetric outcomes that relativity correctly predicts --- different ages at reunion, particle survival across long flight paths, GPS clock offsets --- are determined by differences between worldline-internal accruals. Registration relations describe how these worldline-internal facts are reported across frames; they do not produce the facts.

The clean partition is: one intrinsic time-quantity per massive worldline, namely its locally accrued proper time; everything else, relational.

\begin{thebibliography}{9}

\bibitem{einstein1905}
A.~Einstein. Zur Elektrodynamik bewegter K\"orper. \textit{Annalen der Physik} \textbf{17}, 891--921 (1905). \doi{10.1002/andp.19053221004}.

\bibitem{taylor_wheeler}
E.~F.~Taylor and J.~A.~Wheeler. \textit{Spacetime Physics: Introduction to Special Relativity} (2nd ed.). W.~H.~Freeman (1992).

\bibitem{wald}
R.~M.~Wald. \textit{General Relativity}. University of Chicago Press (1984).

\bibitem{mckinley_creg}
J.~C.~W.~McKinley. \textit{c Is a Registration Bound, Not a Traveler's Speed: A Registration-Based Interpretation of the Information Speed Limit}. Zenodo (2026). \doi{10.5281/zenodo.20114176}.

\bibitem{mckinley_nocount}
J.~C.~W.~McKinley. \textit{Spacetime Changes Can Be Counted; Photons Cannot: A No-Go Result on Photon-Object Inventory}. Zenodo (2026). \doi{10.5281/zenodo.20113982}.

\bibitem{mckinley_massspeed}
J.~C.~W.~McKinley. \textit{Mass Slows Time. Speed Slows Time. Concept, Derivations, and Evidence}. Zenodo (2025). \doi{10.5281/zenodo.17083288}.

\end{thebibliography}

\end{document}
```

</details>

---
{% endraw %}
