---
layout: default
title: '[2026] Dilation Is Not a Property of the Object: A No-Go Result on Intrinsic Time-Dilation'
description: 'Publication metadata and archived raw LaTeX source by John C. W. McKinley.'
permalink: /papers/dilation-is-not-a-property-of-the-object-a-no-go-result-on-intrinsic-time-dilation/
paper: true
---
{% raw %}
# [2026] Dilation Is Not a Property of the Object: A No-Go Result on Intrinsic Time-Dilation

* **DOI:** [10.5281/zenodo.20225720](https://doi.org/10.5281/zenodo.20225720)

* **Date:**  2026-05-16

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

\title{Dilation Is Not a Property of the Object\\
\large A No-Go Result on Intrinsic Time-Dilation}
\author{John C. W. McKinley\,\orcidlink{0009-0005-7097-5035}}
\date{May 16, 2026}

\begin{document}
\maketitle
\blfootnote{\scriptsize This version published at DOI: \doi{10.5281/zenodo.20225720}.}

\begin{abstract}
Relativistic worldline differences produce real, measurable physical consequences. These consequences are commonly described in the language of time dilation, and time dilation as a between-frames registration relation is real, but the consequences themselves are not produced by an intrinsic slowing of any clock. A massive object's proper time accrues locally along its worldline at its own proper rate, always. Dilation is the between-frames relation by which one frame's accumulated proper time is registered through another frame's measurement apparatus. The relation is genuine; the registration is genuine; the consequences are genuine. What is absent is any modification of either frame's intrinsic proper time. This paper states a narrow no-go: there is no such thing as a frame's own dilated time. Dilation lives at the registration interface, not inside the object. Standard Special Relativity is preserved throughout. The only claim is that the dilation relation is not licensed as an intrinsic property of either party to it.
\end{abstract}

\section{Introduction}

The phrase ``time dilation'' is unavoidable in relativistic physics. It names a real measurement relation: when frame $A$ registers frame $B$'s clock through its own apparatus, frame $A$ registers $B$'s clock ticks as separated by $\gamma$ times the proper interval of $B$'s clock. The relation is symmetric. Each frame, registering the other, finds the other's clock to register as dilated.

The relation is real. The muons created in the upper atmosphere really do reach the ground; their reaching is a fact in the Earth frame. The traveling twin really is younger at reunion; the age difference is a fact in any frame. The GPS clocks really do require correction; the correction is a fact in the operational metrology.

None of those facts requires that frame $B$'s own clock has been slowed in itself. Each frame's clock ticks at its own proper rate, locally. The clock has no internal awareness of, and no internal modification by, the frame from which it is being registered. What changes between frames is the registration relation, not the intrinsic accrual.

This paper states that distinction as a narrow no-go: a frame's own dilated time is not licensed. There is no such thing as $B$'s clock running slow from $B$'s own standpoint. There is only the between-frames registration relation by which $A$ registers $B$'s clock through $A$'s apparatus.

The argument uses only Special Relativity~\cite{einstein1905}. The positive structural companion --- that locally accrued proper time along a worldline is the only intrinsic time-quantity for a massive object --- has been stated separately~\cite{mckinley_accrual}. The general registration framing on which the present no-go depends has been stated separately~\cite{mckinley_creg}. The null-case companion has been stated separately~\cite{mckinley_nocount}. The same structural claim --- that reciprocal in-flight dilation statements are frame-dependent comparisons while the reunion difference is a frame-invariant path integral --- has been stated in conventional Special Relativity vocabulary in an earlier work~\cite{mckinley_illusion}. The present paper restates that result as a registration-interface no-go anchored to~\cite{mckinley_creg}, in the vocabulary used throughout the Timeless Light Model corpus.

\section{Definitions}

\begin{definition}[Proper time]
\label{def:proper-time}
The proper time $\tau$ of a timelike worldline $\mathcal{W}$ is the quantity
\[
\tau(\mathcal{W}) = \int_{\mathcal{W}} d\tau,
\]
where $d\tau$ is the local clock-tick interval along $\mathcal{W}$. Proper time is reparametrization-invariant and is the time read by a clock following $\mathcal{W}$.
\end{definition}

\begin{definition}[Local accrual]
\label{def:local-accrual}
A frame's proper time accrues locally along its worldline: each segment of the worldline contributes $d\tau$ to the integrated total. The accrual is intrinsic to the worldline. It is computed without reference to any other frame.
\end{definition}

\begin{definition}[Registration]
\label{def:registration}
A registration is a spacetime-side event in which a lawful state change is physically recorded as a definite localized occurrence by a measurement apparatus~\cite{mckinley_creg}.
\end{definition}

\begin{definition}[Between-frames registration relation]
\label{def:between-frames}
The between-frames registration relation is the quantitative mapping by which frame $A$'s apparatus registers frame $B$'s state. For time-dilation in Special Relativity, the relation is
\[
\Delta t_A = \gamma\, \Delta \tau_B,
\]
where $\Delta \tau_B$ is $B$'s locally accrued proper time between two events on $B$'s worldline, $\Delta t_A$ is the coordinate-time separation $A$ assigns to those events using $A$'s apparatus, and $\gamma = (1 - v^2/c^2)^{-1/2}$ with $v$ the relative velocity.
\end{definition}

\begin{definition}[Intrinsic property of a frame]
\label{def:intrinsic}
A property is intrinsic to a frame if it is defined without reference to any other frame. A property is non-intrinsic, or relational, if its definition requires a second frame or a measurement standpoint outside the frame.
\end{definition}

\begin{definition}[Intrinsically dilated time]
\label{def:intrinsic-dilated}
An intrinsically dilated time would be a time-quantity belonging to a frame whose rate of accrual is modified by something other than the frame's own worldline. That is, it would be a $\tau'$ assigned to a worldline such that $\tau' \neq \int d\tau$ along that worldline.
\end{definition}

\section{The Two Distinct Quantities}

The argument turns on keeping two distinct quantities cleanly separated. They have been used loosely in pedagogical exposition for over a century, and the looseness underwrites the misreading this paper aims to foreclose.

The first quantity is $\tau$, the proper time of a worldline, defined in \cref{def:proper-time}. It is intrinsic to the worldline. It is what the worldline's own clock reads, integrated along its actual history. Different worldlines through the same pair of events give different values of $\tau$. The famous twin-paradox asymmetry at reunion is the statement that the two twins' worldlines, having different shapes, accrue different integrated $\tau$ values.

The second quantity is $\Delta t_A$, the coordinate-time separation that frame $A$ assigns, using $A$'s apparatus, to two events on another worldline. It is not intrinsic to either worldline. It is a registration relation between two frames, defined only in the presence of both.

Standard Special Relativity is explicit on this distinction. $\tau$ is reparametrization-invariant; it is the same value computed in any coordinate system. $\Delta t_A$ depends on the choice of frame; a different $A$ assigns a different $\Delta t_A$ to the same pair of events on $B$'s worldline.

\section{The No-Go}

\begin{proposition}[Proper time is unaffected by registration]
\label{prop:tau-unaffected}
The proper time accrued along a worldline is unaffected by any other frame's registration of that worldline.
\end{proposition}

\begin{proof}
By \cref{def:proper-time}, proper time is the integral of $d\tau$ along the worldline. The integral is determined by the worldline's own geometry. No quantity defined on another worldline, and no measurement performed in another frame, appears in the integrand. Therefore the value of $\tau$ along $\mathcal{W}$ is independent of whether any other frame registers $\mathcal{W}$, and independent of how any such registration is performed.
\end{proof}

\begin{proposition}[Dilation is a between-frames relation]
\label{prop:dilation-relational}
The dilation factor $\gamma$ is defined only between two frames in relative motion. It is not defined for a single frame in isolation.
\end{proposition}

\begin{proof}
The factor $\gamma = (1 - v^2/c^2)^{-1/2}$ contains the relative velocity $v$. Velocity is a relation between two frames~\cite{einstein1905,taylor_wheeler}. A single frame in isolation has no $v$ and therefore no $\gamma$. The factor exists only when two frames are specified. Therefore dilation is a between-frames relation, not a property of a single frame.
\end{proof}

\begin{proposition}[Intrinsically dilated time is not licensed]
\label{prop:no-intrinsic-dilation}
A frame's intrinsically dilated time, in the sense of \cref{def:intrinsic-dilated}, is not licensed.
\end{proposition}

\begin{proof}
Suppose, for contradiction, that a frame $B$ possesses an intrinsically dilated time $\tau'_B$, defined as in \cref{def:intrinsic-dilated}: a time-quantity belonging to $B$ such that $\tau'_B \neq \int d\tau$ along $B$'s worldline.

By \cref{def:intrinsic}, an intrinsic property is defined without reference to any other frame. So $\tau'_B$ must be definable using only quantities belonging to $B$.

The only time-quantity defined using only quantities belonging to $B$ is $\int d\tau$ along $B$'s worldline. Any modification of this quantity must come from outside $B$: from a relative velocity to some second frame, from a coordinate choice external to $B$, or from a registration by another apparatus. Each of these requires reference to a frame other than $B$, violating intrinsicness.

Therefore $\tau'_B$ cannot be both intrinsic to $B$ and different from $\int d\tau$. The supposed intrinsically dilated time is not licensed.
\end{proof}

\begin{corollary}[A frame does not register its own time as dilated]
\label{cor:no-self-dilation}
No frame registers its own clock as dilated.
\end{corollary}

\begin{proof}
By \cref{prop:tau-unaffected}, a frame's proper time is unaffected by registration. By \cref{prop:dilation-relational}, dilation is a between-frames relation. A frame registering its own clock is not in a between-frames relation; it is in a self-registration relation. Therefore no dilation factor applies to its own clock from its own standpoint. The clock registers at its proper rate.
\end{proof}

\section{What Is Real}

The no-go denies the licensing of intrinsic dilation. It does not deny the reality of the between-frames relation, the reality of the registration, or the reality of the physical consequences. Each of these is preserved.

The between-frames relation $\Delta t_A = \gamma\, \Delta \tau_B$ is real in the sense that it is the correct quantitative mapping. Any operationally adequate apparatus in $A$, registering events on $B$'s worldline, will register coordinate-time separations consistent with this relation.

The registration itself is real. The detector clicks, the timestamps, the recorded data --- all are spacetime-side facts. They are not subjective impressions.

The physical consequences are real. When a muon is produced in the upper atmosphere and reaches the ground, the reaching is a fact in the Earth frame. When the traveling twin returns younger, the age difference is a fact at the reunion event. The integrated proper times along the two twins' worldlines differ; this is a consequence of geometry, not of anyone's perception.

What is absent in all of this is intrinsic dilation. The muon's clock is not running slow from the muon's standpoint; the muon decays at its own proper rate along its own worldline. The Earth frame registers the muon's flight as taking longer than the muon's proper lifetime, and this registration is the dilation relation. The decay-versus-survival outcome at the ground is determined by integrated proper time along the muon's worldline relative to the integrated proper time required for decay --- a worldline-internal quantity. The dilation language describes the registration; the worldline integrals determine the consequences.

\section{Relation to the Twin Paradox}

The twin paradox is often presented as if it required selecting between symmetric dilation claims, one twin or the other being the one whose clock is ``actually'' running slow. The no-go forecloses that framing.

Neither twin's clock runs slow from its own standpoint. Each twin's clock ticks at its proper rate. Each twin's apparatus, registering the other, registers the other's clock as dilated. Both registrations are correct between-frames relations. Neither is an intrinsic statement.

The asymmetric aging at reunion is not produced by one twin's clock having been slowed in itself. It is produced by the two worldlines having different geometric shapes. The traveling twin's worldline is longer in space but, because of the Minkowski signature, shorter in integrated proper time. The asymmetry is a fact about the worldlines, not about any clock having been slowed by motion.

This reframing dissolves the apparent paradox. The paradox depends on the assumption that one twin's clock must ``really'' have been running slow. The no-go denies that anyone's clock was ever running slow in itself. There is no real underlying dilation to assign to a winner. There are only worldline integrals and registration relations, both of which behave as Special Relativity says.

\section{Standard Physics Preserved}

The present paper does not modify Special Relativity, the Lorentz transformations, the velocity-addition law, or any predictive content of standard relativistic physics. It does not introduce a new equation, a new constant, or a new postulate.

What it does is decline an interpretive overlay. The overlay says: ``and therefore $B$'s clock is really running slow.'' The no-go says: $B$'s clock is registering at its proper rate from $B$'s standpoint; what is registered as slow is registered as slow by $A$'s apparatus, through the between-frames relation. The equations do not require the overlay. The overlay was a verbal convenience that has been mistaken for a physical claim.

\section{Conclusion}

Time dilation is a real, measurable, consequential between-frames registration relation. It is not a property of any frame.

A frame's proper time accrues locally along its worldline. The accrual is the only intrinsic time-quantity belonging to the frame. Dilation, defined as the registration of one frame's clock by another frame's apparatus, is a relation between two frames; it is not a quantity belonging to either frame alone.

The familiar physical consequences described in the language of dilation --- muon survival, asymmetric aging, GPS corrections --- are determined by integrated proper times along worldlines and by the correct between-frames registration relation. They are not consequences of any frame's clock being slowed in itself.

Therefore: a frame's intrinsically dilated time is not licensed. There is no such thing as the frame's own slowed time. The clock ticks at its proper rate. The dilation lives at the registration interface, and the interface is between frames, not inside the object.

\begin{thebibliography}{9}

\bibitem{einstein1905}
A.~Einstein. Zur Elektrodynamik bewegter K\"orper. \textit{Annalen der Physik} \textbf{17}, 891--921 (1905). \doi{10.1002/andp.19053221004}.

\bibitem{taylor_wheeler}
E.~F.~Taylor and J.~A.~Wheeler. \textit{Spacetime Physics: Introduction to Special Relativity} (2nd ed.). W.~H.~Freeman (1992).

\bibitem{mckinley_creg}
J.~C.~W.~McKinley. \textit{c Is a Registration Bound, Not a Traveler's Speed: A Registration-Based Interpretation of the Information Speed Limit}. Zenodo (2026). \doi{10.5281/zenodo.20114176}.

\bibitem{mckinley_nocount}
J.~C.~W.~McKinley. \textit{Spacetime Changes Can Be Counted; Photons Cannot: A No-Go Result on Photon-Object Inventory}. Zenodo (2026). \doi{10.5281/zenodo.20113982}.

\bibitem{mckinley_accrual}
J.~C.~W.~McKinley. \textit{Local Accrual as the Only Intrinsic Time-Quantity: A Positive Structural Statement for the Massive Regime}. Zenodo (2026). \doi{10.5281/zenodo.20225645}.

\bibitem{mckinley_illusion}
J.~C.~W.~McKinley. \textit{Illusion and Invariant: Making Sense of Time Dilation --- Reciprocity, Simultaneity, and Proper Time}. Zenodo (2025). \doi{10.5281/zenodo.17083276}.

\end{thebibliography}

\appendix
\section{Worked Case: Rocket and Passed Planet}

Consider a rocket under constant proper acceleration and a planet at rest in some chosen inertial frame. The rocket's apparatus registers the planet's clock as dilated; the planet's apparatus registers the rocket's clock as dilated.

Both registrations are correct between-frames relations. Neither corresponds to anyone's clock being slowed in itself. The rocket's clock continues to accrue at its proper rate along the rocket's worldline; the planet's clock continues to accrue at its proper rate along the planet's worldline.

The two registrations report each worldline's accrual through the other's apparatus. No reunion event occurs in this scenario, so the question of which clock ``really'' ran slow has no answer to give; what is asymmetric in the twin case (worldline shapes meeting at a common event) is simply absent here. The symmetry of registration, with no preferred frame, is the structurally honest picture.

The rocket case is the cleanest illustration of \cref{prop:no-intrinsic-dilation}. Where the twin case can mislead by suggesting that one twin's clock must ``really'' have been slowed by motion, the rocket-and-passed-planet case has no reunion to anchor such an inference. Each apparatus registers the other's clock through the standard between-frames relation, both registrations are correct, and there is nothing further to say. The supposed intrinsic dilation has no referent.

\end{document}
```

</details>

---
{% endraw %}
