---
layout: default
title: '[2026] Worldlines Produce; Dilation Reports: A No-Go on Treating Consequence-Reality as Evidence of Intrinsic Dilation'
description: 'Publication metadata and archived raw LaTeX source by John C. W. McKinley.'
permalink: /papers/worldlines-produce-dilation-reports-a-no-go-on-treating-consequence-reality-as-evidence-of/
paper: true
---
{% raw %}
# [2026] Worldlines Produce; Dilation Reports: A No-Go on Treating Consequence-Reality as Evidence of Intrinsic Dilation

* **DOI:**[10.5281/zenodo.20225757](https://doi.org/10.5281/zenodo.20225757)

* **Date:** 2026-05-17

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

\title{Worldlines Produce; Dilation Reports\\
\large A No-Go on Treating Consequence-Reality as Evidence of Intrinsic Dilation}
\author{John C. W. McKinley\,\orcidlink{0009-0005-7097-5035}}
\date{May 17, 2026}

\begin{document}
\maketitle
\blfootnote{\scriptsize This version published at DOI: \doi{10.5281/zenodo.20225757}.}

\begin{abstract}
Relativistic worldline differences produce real, measurable, decision-relevant physical consequences. Muons reach the ground. The traveling twin is younger at reunion. GPS clocks require correction. These consequences are facts, not appearances. They are commonly described in the language of time dilation, and the reality of the consequences is sometimes treated as evidence that the dilated frame's clock has been slowed in itself --- that dilation is therefore an intrinsic property of the frame after all. This paper states a narrow no-go: the inference from consequence-reality to intrinsicness is not licensed. Consequences follow from the structure of worldline-internal accruals together with between-frames registration relations; neither component requires an intrinsic dilation of any frame's clock. The reality of dilation as a registration relation is fully preserved. What is denied is the further claim that the relation must be located inside one of the parties to it.
\end{abstract}

\section{Introduction}

A standing objection to the registration-interface treatment of dilation runs as follows. If dilation were merely a between-frames relation and not a property of either frame, then dilation would be a kind of appearance. But the consequences of dilation are real: muons reach the ground, the twin ages asymmetrically, GPS depends on the correction. Real consequences require a real underlying cause. Therefore dilation must be intrinsic to the frame whose clock has been slowed.

The objection is intuitive and wrong. It rests on a buried inference from ``real consequence'' to ``intrinsic property of one party.'' The inference is unlicensed.

This paper states the no-go: the reality of the consequences does not entail that any frame's clock has been slowed in itself. Consequences in relativity follow from the joint structure of worldline-internal proper-time accruals and between-frames registration relations~\cite{einstein1905,taylor_wheeler,wald}. The same structural decomposition appears in the conventional-vocabulary treatments of dilation~\cite{mckinley_illusion,mckinley_massspeed}: in-flight reciprocity is a frame-dependent comparison; the reunion difference is a frame-invariant path integral; environmental conditions (mass, speed) act on the integrand rather than on any clock in itself. Neither component is an intrinsic dilation of any frame.

The complementary results are stated separately. The negative no-go on intrinsic dilation~\cite{mckinley_nointrinsic} rules out the claim that a frame's clock is slowed in itself. The positive structural claim~\cite{mckinley_accrual} identifies locally accrued proper time as the only intrinsic time-quantity associated with a massive object. The general registration framing~\cite{mckinley_creg} establishes the regime-level reading of $c$ as a registration bound. The null-case companion~\cite{mckinley_nocount} states the corresponding photon-side result. The present paper closes the standing objection by showing that consequence-reality does not reopen the intrinsic-dilation reading.

\section{Definitions}

\begin{definition}[Physical consequence of dilation]
\label{def:consequence}
A physical consequence of dilation is an outcome in spacetime --- a survival event, an age difference, a clock offset, a phase shift --- whose occurrence and magnitude depend on relativistic-kinematic quantities. The consequence is registrable by appropriate apparatus in at least one frame.
\end{definition}

\begin{definition}[Real, in the relevant sense]
\label{def:real}
A consequence is real when it is a fact in spacetime: a registration occurs, an outcome obtains, an integrated quantity has the value it has. Reality in this sense is opposed to subjective impression. A real consequence is not abolished by changing frames; what changes between frames is the registration of the consequence, not the consequence itself.
\end{definition}

\begin{definition}[Intrinsic dilation]
\label{def:intrinsic-dilation}
An intrinsic dilation of frame $B$'s clock would be a modification of $B$'s clock's accrual rate definable without reference to any frame other than $B$. That is, $B$'s clock would tick more slowly than $\int d\tau$ along $B$'s worldline.
\end{definition}

\begin{definition}[Consequence-from-intrinsicness inference]
\label{def:inference}
The consequence-from-intrinsicness inference is the move from the premise ``dilation produces real consequences'' to ``therefore $B$'s clock is intrinsically dilated.'' Schematically:
\[
\text{Real consequence } \Rightarrow \text{ intrinsic property of one frame.}
\]
\end{definition}

\begin{definition}[Worldline-internal quantity]
\label{def:worldline-internal}
A worldline-internal quantity is one defined using only the worldline geometry and the local metric along the worldline, with no reference to a second frame, coordinate system, synchronization convention, or external apparatus.
\end{definition}

\begin{definition}[Between-frames registration relation]
\label{def:between-frames}
A between-frames registration relation is the quantitative mapping between proper-time accruals on one worldline and coordinate-time separations assigned by another frame's apparatus. For dilation, this is $\Delta t_A = \gamma\, \Delta \tau_B$ with $\gamma = (1 - v^2/c^2)^{-1/2}$.
\end{definition}

\section{The Structure of a Dilation Consequence}

A dilation consequence has two structural components. The first is a worldline-internal accrual. The second is a between-frames registration relation. The consequence emerges from their joint operation.

\begin{lemma}[Two-component structure]
\label{lem:two-component}
Every standardly cited consequence of dilation decomposes into (i) a worldline-internal accrual along one or more worldlines and (ii) a between-frames registration relation describing how the accruals are reported across frames.
\end{lemma}

\begin{proof}
Consider the standard cases.

\emph{Muon survival.} The muon's worldline accrues proper time from production to either decay or ground impact, whichever event occurs first along the worldline. Whether the muon decays before reaching the ground is determined by comparison of two worldline-internal quantities: the proper time accrued and the proper time required for decay. This is component (i). Component (ii) is the Earth frame's registration of the muon's flight as taking longer than the proper lifetime, which is the dilation relation $\Delta t_{\text{Earth}} = \gamma\, \Delta \tau_{\text{muon}}$.

\emph{Asymmetric twin aging.} Each twin's worldline accrues its own proper time between departure and reunion. The age at reunion is the worldline-internal accrual on that twin's worldline up to the reunion event. This is component (i). Component (ii) is the dilation relation each twin's apparatus would register were either to track the other's clock during separation.

\emph{GPS clock correction.} The GPS satellite's worldline accrues proper time in its orbital trajectory; the ground clock's worldline accrues proper time at the surface. The two accruals differ. This is component (i). The metrology-side correction --- the formula by which ground observers translate satellite signals into consistent positional data --- is the registration relation, accounting for both special-relativistic and gravitational components. This is component (ii)~\cite{ashby}.

In each case, the consequence emerges from worldline-internal accruals together with the registration relation. Neither component supplies an intrinsic dilation.
\end{proof}

\begin{proposition}[Consequences are worldline-internal facts]
\label{prop:consequences-internal}
The occurrence and magnitude of every standardly cited consequence of dilation is determined by worldline-internal quantities. The registration relation reports the consequence across frames; it does not produce the consequence.
\end{proposition}

\begin{proof}
By \cref{lem:two-component}, each consequence decomposes into a worldline-internal component and a between-frames component. Component (i) supplies the values: the integrated proper time on each worldline, the proper time required for decay, the age accrued. Component (ii) supplies the mapping by which these values are translated into the coordinate-time language of a chosen frame.

The mapping does not produce the values. The values are fixed by the worldline geometry and the local metric. A different frame applying a different mapping would assign different coordinate-time separations to the same events but would not alter the worldline-internal accruals. The consequence --- the muon's arrival, the twin's age, the GPS clock offset --- is determined by component (i) regardless of which frame's mapping is used to describe it.

Therefore consequences are worldline-internal facts. The registration relation is how they are reported; it is not their cause.
\end{proof}

\section{The No-Go}

\begin{proposition}[Consequence-reality does not license intrinsicness]
\label{prop:no-go}
The reality of the consequences does not license the inference to intrinsic dilation of any frame.
\end{proposition}

\begin{proof}
By \cref{prop:consequences-internal}, every standardly cited consequence of dilation is determined by worldline-internal accruals together with the between-frames registration relation. The worldline-internal component is, by \cref{def:worldline-internal}, defined without reference to any other frame; it is not an intrinsic dilation of a frame's clock, since it is precisely $\int d\tau$ along the worldline, with no modification. The between-frames component is, by \cref{def:between-frames}, a relation between two frames; it is not a property of either frame alone.

Suppose, for contradiction, that the reality of the consequences licenses the inference to intrinsic dilation of some frame $B$. Then there would exist an intrinsic dilation of $B$'s clock --- a modification of $B$'s accrual rate definable without reference to any other frame --- whose existence is required to explain the consequences. But the consequences are already fully explained by component (i) together with component (ii), neither of which is such an intrinsic dilation. The supposed intrinsic dilation does no explanatory work. Its addition is redundant with the worldline-internal accrual it would supposedly correct.

Therefore the inference from consequence-reality to intrinsicness is not licensed.
\end{proof}

\begin{corollary}[The objection fails]
\label{cor:objection-fails}
The standing objection that real consequences require an intrinsic underlying dilation fails.
\end{corollary}

\begin{proof}
The objection assumes that real consequences require a real underlying property of one frame. By \cref{prop:no-go}, this is not the structure of dilation consequences in relativity. The consequences are real; the worldline-internal accruals are real; the registration relations are real; but no frame's clock is intrinsically dilated. The reality of the consequences is fully accounted for without the intrinsicness assumption. The objection therefore fails.
\end{proof}

\section{Why the Inference Is Tempting}

The consequence-from-intrinsicness inference is tempting because it tracks a sound pattern in non-relativistic settings. If a chemical reaction produces a real outcome, one looks for a real property of the reagents that explains it. If a mechanical collision produces a real momentum change, one looks for real masses and velocities. The pattern --- real consequence implies real underlying property --- works in regimes where the relevant properties are intrinsic to single objects.

The pattern breaks in relativity because the relevant properties are partly relational. The dilation relation is real; it is not intrinsic to either frame. Relativistic consequences are produced by joint operations on intrinsic worldline data and relational registration data. The pattern that worked for chemistry and Newtonian mechanics, transferred to relativity unmodified, mislocates the relational component as intrinsic.

The misreading is not a failure to take consequences seriously. It is a failure to recognize that some real components of the explanation are not properties of single objects. Once the structural distinction in \cref{lem:two-component} is in view, the temptation dissipates: the relational component supplies what the supposedly intrinsic dilation was being recruited to supply, and the recruitment becomes unnecessary.

\section{Standard Cases Reread}

The standard cases are reread without loss.

\emph{Muon survival.} The muon's clock ticks at its proper rate along its worldline. The muon's proper lifetime is what it is. The muon's worldline reaches the ground event with less proper time accrued than the proper-lifetime threshold; the muon arrives intact. The Earth frame's apparatus registers the muon's flight using the dilation relation, but the survival outcome itself is fixed by the muon's worldline-internal accrual. No intrinsic dilation of the muon's clock is required.

\emph{Asymmetric twin aging.} Each twin's clock ticks at its proper rate along its worldline. The two worldlines have different geometric shapes between the common departure and reunion events. The two integrated proper times accordingly differ. At reunion, the difference manifests as a difference in biological age, atomic clock reading, or any other proper-time-driven process. No twin's clock has been slowed in itself. The age asymmetry is a difference between two worldline-internal accruals.

\emph{GPS clock correction.} The satellite's clock and the ground clock each tick at their proper rates along their respective worldlines. The two worldlines differ in altitude (gravitational potential) and in velocity (orbital speed). The two integrated proper times accordingly differ, with both special-relativistic and gravitational components. The metrological correction is a between-frames registration mapping that translates satellite-clock readings into a frame the ground apparatus can use. The system works because the worldline-internal accruals are what they are and the registration mapping is correctly specified. Neither clock has been intrinsically dilated.

In all three cases, the consequences are real and the standard predictive machinery is correct~\cite{einstein1905,wald,ashby,mckinley_massspeed}. The intrinsic-dilation interpretive overlay is not required, and adding it is structurally redundant.

\section{What Is Real, Clarified}

Five distinct things are real in any dilation case. Distinguishing them removes the residual force of the standing objection.

\begin{enumerate}
\item Each worldline's locally accrued proper time. Real, intrinsic, worldline-internal.
\item The proper-time-required threshold for any internal process, such as particle decay. Real, intrinsic, worldline-internal.
\item The geometric shape of each worldline. Real, intrinsic, worldline-internal.
\item The between-frames registration relation. Real, relational, between-frames.
\item The spacetime-side registration events themselves: detector clicks, timestamps, comparisons at meeting events. Real, registration-side.
\end{enumerate}

What is \emph{not} on the list, and is not real, is intrinsic dilation: a modification of any frame's accrual rate definable without reference to any other frame. Its absence does not subtract from the reality of items 1 through 5. Each of those is fully present in the standard formalism. The consequence-from-intrinsicness inference treated intrinsic dilation as a sixth real item, supposedly required to explain the others. It is not required, and it is not licensed~\cite{mckinley_nointrinsic}.

\section{Conservativeness}

The present paper introduces no new formal content. Special Relativity, General Relativity, and the standard predictive machinery are preserved. No new equation, constant, or postulate is introduced.

The contribution is interpretive: the reality of the consequences is reconciled with the no-go on intrinsic dilation by showing that the structure of relativistic consequences does not require intrinsicness. Worldline-internal accruals and between-frames registration relations jointly suffice. The standard cases are recovered without modification.

\section{Conclusion}

Relativistic worldline differences produce real consequences. Muons reach the ground. The traveling twin ages asymmetrically. GPS depends on the correction. These are facts in spacetime, not appearances. They are commonly described in the language of time dilation, but the consequences themselves are produced by worldline geometry and proper-time accrual, not by any intrinsic slowing inside a clock.

The reality of the consequences does not license the inference to intrinsic dilation of any frame. Consequences decompose into worldline-internal accruals together with between-frames registration relations. The worldline-internal component is each clock ticking at its proper rate along its worldline; the between-frames component is the registration relation by which one frame's apparatus reports another frame's accrual. Neither component is an intrinsic dilation, and no intrinsic dilation is required to produce the consequences.

The standing objection --- that real consequences must be backed by a real intrinsic property of one frame --- transfers a sound non-relativistic pattern to a regime where some real components of the explanation are not properties of single objects. Once the two-component structure is recognized, the objection dissolves.

Dilation is not the physical cause; it is the registration description. The physical difference is the worldline difference. What is real is the accrual, the worldline, the registration relation, and the registration events. What is not real, and not required, is a slowed clock in itself.

\begin{thebibliography}{9}

\bibitem{einstein1905}
A.~Einstein. Zur Elektrodynamik bewegter K\"orper. \textit{Annalen der Physik} \textbf{17}, 891--921 (1905). \doi{10.1002/andp.19053221004}.

\bibitem{taylor_wheeler}
E.~F.~Taylor and J.~A.~Wheeler. \textit{Spacetime Physics: Introduction to Special Relativity} (2nd ed.). W.~H.~Freeman (1992).

\bibitem{wald}
R.~M.~Wald. \textit{General Relativity}. University of Chicago Press (1984).

\bibitem{ashby}
N.~Ashby. Relativity in the Global Positioning System. \textit{Living Reviews in Relativity} \textbf{6}, 1 (2003). \doi{10.12942/lrr-2003-1}.

\bibitem{mckinley_creg}
J.~C.~W.~McKinley. \textit{c Is a Registration Bound, Not a Traveler's Speed: A Registration-Based Interpretation of the Information Speed Limit}. Zenodo (2026). \doi{10.5281/zenodo.20114176}.

\bibitem{mckinley_nocount}
J.~C.~W.~McKinley. \textit{Spacetime Changes Can Be Counted; Photons Cannot: A No-Go Result on Photon-Object Inventory}. Zenodo (2026). \doi{10.5281/zenodo.20113982}.

\bibitem{mckinley_accrual}
J.~C.~W.~McKinley. \textit{Local Accrual as the Only Intrinsic Time-Quantity: A Positive Structural Statement for the Massive Regime}. Zenodo (2026). \doi{10.5281/zenodo.20225645}.

\bibitem{mckinley_nointrinsic}
J.~C.~W.~McKinley. \textit{Dilation Is Not a Property of the Object: A No-Go Result on Intrinsic Time-Dilation}. Zenodo (2026). \doi{10.5281/zenodo.20225720}.

\bibitem{mckinley_illusion}
J.~C.~W.~McKinley. \textit{Illusion and Invariant: Making Sense of Time Dilation --- Reciprocity, Simultaneity, and Proper Time}. Zenodo (2025). \doi{10.5281/zenodo.17083276}.

\bibitem{mckinley_massspeed}
J.~C.~W.~McKinley. \textit{Mass Slows Time. Speed Slows Time. Concept, Derivations, and Evidence}. Zenodo (2025). \doi{10.5281/zenodo.17083288}.

\end{thebibliography}

\end{document}
```

</details>

---
{% endraw %}
