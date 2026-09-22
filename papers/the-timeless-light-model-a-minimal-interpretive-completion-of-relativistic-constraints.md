---
layout: default
title: '[2025] The Timeless Light Model: A Minimal Interpretive Completion of Relativistic Constraints'
description: 'Publication metadata and archived raw LaTeX source by John C. W. McKinley.'
permalink: /papers/the-timeless-light-model-a-minimal-interpretive-completion-of-relativistic-constraints/
paper: true
---
{% raw %}
# [2025] The Timeless Light Model: A Minimal Interpretive Completion of Relativistic Constraints
*   **DOI:** [10.5281/zenodo.18012564](https://doi.org/10.5281/zenodo.18012564)
*   **Date:** 21 December 2025

<details markdown="1">
<summary><b>Click to view Raw LaTeX Source</b></summary>

```latex
\documentclass[12pt,onecolumn,a4paper]{article}

% ---------- Encoding, fonts ----------
\usepackage[utf8]{inputenc}
\usepackage[T1]{fontenc}
\usepackage{lmodern}
\usepackage{microtype}



% ---------- Layout ----------
\usepackage[margin=1in]{geometry}
\usepackage{fancyhdr}
\setlength{\headheight}{14pt}
\pagestyle{fancy}
\fancyhf{}

\lhead{TLM: Minimal Interpretive Completion}
\rhead{John C.\ W.\ McKinley}
\cfoot{\thepage}

% ---------- Math ----------
\usepackage{amsmath,amssymb,amsthm}

% --- Theorem-like environments (shared counter) ---
% --- Theorem-like environments (shared counter) ---
\newtheorem{theorem}{Theorem}[section]
\newtheorem{proposition}[theorem]{Proposition}
\newtheorem{definition}[theorem]{Definition}
\newtheorem{remark}[theorem]{Remark}




% ---------- Graphics ----------
\usepackage{graphicx}
\usepackage{tikz}
% --- TikZ libraries for the null-path figure ---
\usetikzlibrary{arrows.meta,decorations.pathreplacing,positioning}


% ---------- Bibliography & links ----------
\usepackage{orcidlink}
\usepackage[numbers,sort&compress]{natbib} % or: [authoryear] if you prefer

\usepackage{hyperref}
\urlstyle{same}
\hypersetup{
  colorlinks=true,
  linkcolor=blue,
  citecolor=blue,
  urlcolor=blue
}

\usepackage[nameinlink,noabbrev]{cleveref} % keep after hyperref

\crefname{proposition}{Proposition}{Propositions}
\Crefname{proposition}{Proposition}{Propositions}
\crefname{definition}{Definition}{Definitions}
\Crefname{definition}{Definition}{Definitions}
\crefname{remark}{Remark}{Remarks}
\Crefname{remark}{Remark}{Remarks}



% (A) Add to PREAMBLE
% Put after your \newtheorem lines.
% ----------------------------

% A lightweight macro set to keep terminology disciplined
\newcommand{\tlm}{\textsc{TLM}}

\newcommand{\Aff}{\lambda} % affine parameter
\newcommand{\ProperTime}{\tau}


\title{\textbf{The Timeless Light Model:\\
A Minimal Interpretive Completion of Relativistic Constraints}}
\author{John C. W. McKinley\orcidlink{0009-0005-7097-5035}\footnote{This version published at \href{https://doi.org/10.5281/zenodo.18012564}{doi:10.5281/zenodo.18012564}.}\\Independent Researcher}



\date{December 21, 2025}

\begin{document}
\maketitle







\begin{abstract}
Building on the kinematic constraint that massless excitations admit no rest frame and no proper-time evolution, this paper addresses how photon language can be consistently interpreted once that constraint is taken seriously. The formalism leaves open a limited representational choice: one may remain instrumentalist or agnostic about physical interpretation, or one may adopt a minimal reading in which ``photon talk'' functions as shorthand for correlations between emission and absorption events.

We label this minimal reading the Timeless Light Model (\tlm{}). Here ``timeless'' means only that null propagation carries no proper-time evolution (\(\ProperTime = 0\)) along the associated null curve; it does \emph{not} assert acausal influence, new degrees of freedom, hidden variables, or modifications to relativity or QED. The aim is to align informal persistence-language with the structures actually present in relativistic and field-theoretic descriptions. \tlm{} is offered as one permissible interpretive guideline among several, not as a uniquely correct ontology.

Throughout, the terms ``photon'' and ``massless excitation'' are used interchangeably, with the latter preferred where kinematic precision is required. 
\end{abstract}


\section{Introduction}

Special Relativity constrains the structures available for describing physical
systems. In particular, the absence of a rest frame for massless excitations
removes the usual rest-frame resources used to ground the standard persistence narrative for localized massive systems.

For standard treatments of relativistic kinematics and null structure, see, e.g., \cite{Rindler}.

The purpose of this paper is to examine how photon language may be used
consistently once the relativistic kinematic facts are taken seriously—namely,
that massless excitations admit no inertial rest frame and no proper-time
parameter along null propagation. Given the absence of the structures that
normally underwrite rest-frame persistence for massive objects, we articulate
a minimal, conservative interpretive discipline for photon descriptions.



\begin{remark}[Scope and claims]
This paper is deliberately \emph{interpretive}. It makes no dynamical proposals, introduces no new fields, and claims no new empirical consequences. Its target is a narrow mismatch between common informal language (``a photon is a little object flying through space'') and the resources that relativistic and field-theoretic formalisms provide for massless excitations. Where the companion note \cite{NoRestFrame} states a negative constraint, the present note offers one conservative way to speak thereafter.
\end{remark}

In a companion paper \cite{NoRestFrame}, this constraint was established as a
purely negative result. The present work addresses the interpretive gap that
remains once that constraint is taken seriously.

\section{Rest-Frame Constraint for Massless Excitations}




\begin{proposition}[Rest-frame constraint]\label{prop:restframe}
For a massless excitation, there exists no inertial frame in which the excitation is at rest. Along any null curve associated with such an excitation, 
the proper time satisfies
\[
d\ProperTime = 0 .
\]
Consequently, the standard rest-frame-based notion of persistence available for massive localized systems is not defined in the same way for massless excitations.
\end{proposition}

This proposition is a direct consequence of relativistic kinematics and requires no additional assumptions. The present paper takes this constraint as given and asks only how photon language may be consistently interpreted once it is acknowledged.





\section{Representational Options After the Constraint}

Relativistic kinematics fixes invariant causal structure but underdetermines how informal particle language should be applied to massless excitations. Once the rest-frame constraint is acknowledged, several representational options remain open:

\begin{enumerate}
\item \emph{Purely calculational usage:} treat ``photon'' as a symbolic device within amplitudes and cross sections.
\item \emph{Underspecified usage:} refrain from assigning any physical reading beyond invariant correlations.
\item \emph{Endpoint-focused usage:} treat ``photon'' language as shorthand for null-mediated correlations between localized interaction events. 
\end{enumerate}


The Timeless Light Model adopts option (3) as a reading consistent with the kinematic structure.

Throughout, we use ``endpoint-description'' (also ``endpoint-focused'') to denote
a minimal interpretive stance in which localized interaction events
(emission, absorption, or interaction vertices) are treated as the primary
spacetime relata, while intermediate ``particle in flight'' language is regarded
as representational shorthand rather than as a claim of rest-frame persistence.




\section{Endpoint-Defined Descriptions of Null-Mediated Correlations}


If photon descriptions do not support a rest-frame-grounded persistence story,
their physical role is naturally understood in terms of relations between
emission and absorption events. This shift requires no modification of existing equations, only a reinterpretation of what those equations describe.

Endpoint-defined descriptions are already implicit in quantum field theory,
where creation and annihilation operators act at spacetime points and
propagators encode correlations rather than trajectories.

This perspective is standard in quantum field theory, where particles appear as asymptotic states and interactions are localized at vertices; see, e.g., \cite{WeinbergQFT,PeskinSchroeder}.

Field theory already encourages restraint about ``particle-in-flight'' ontology: interactions are localized at vertices, and propagation is encoded via Green functions/propagators that support predictions for correlations between events. \tlm{} adopts this familiar restraint as an explicit reading rather than as mere calculational etiquette.

This endpoint-focused reading is also consistent with how single-photon states are operationally defined in modern photonic quantum technologies \cite{OBrienQI}.



\subsection{Endpoint-Descriptions and Null Propagation}

We restate the rest-frame constraint established in \Cref{prop:restframe}
to emphasize its role in motivating the interpretive shift.


\begin{remark}[Modest kinematic point]
For massless excitations, the standard rest-frame grounded persistence picture available for massive localized systems is not available: there exists no inertial frame in which the excitation is at rest, and along null propagation the proper time satisfies \(d\ProperTime=0\). Consequently, any ``persistence'' narrative for photons is representational rather than rest-frame grounded in the manner applicable to massive objects.

This remark does \emph{not} deny the utility of null geodesics, affine parameters, or field evolution in coordinate time. It states only that the common massive-object template for persistence (rest frame + proper time as internal clock) does not transfer unchanged to massless excitations.
\end{remark}


\subsection{Terminology (minimal and operational)}
\begin{definition}[Persistence (rest-frame grounded)]
By ``persistence'' we mean the ordinary relativistic notion used for localized massive systems: identity of an object across a one-parameter family of spacelike hypersurfaces in a frame in which the object is at rest, with internal evolution parameterized by proper time.
\end{definition}

\begin{definition}[Timeless (as used here)]
In \tlm{}, ``timeless'' is shorthand for the kinematic fact that a null worldline has vanishing proper time,
\[
d\ProperTime = 0,
\]
so there is no invariant proper-time parameter available to describe internal evolution along the null worldline. No stronger metaphysical claim is intended.
\end{definition}




\begin{definition}[Endpoint-description (minimal)]
An ``endpoint-description'' is a description in which the physically recorded interaction events (emission/absorption, or more generally interaction vertices) are taken as the primary localized relata, and intermediate ``particle in flight'' language is treated as calculational or representational shorthand.
\end{definition}



\section{Endpoint Descriptions in Field Theory and Causation}


In quantum electrodynamics, the photon propagator encodes correlations between spacetime points rather than a persisting trajectory. In schematic form,
\[
D_{\mu\nu}(x-y)
= \int \frac{d^4 k}{(2\pi)^4}
\frac{-i g_{\mu\nu}}{k^2 + i\epsilon}
e^{-ik\cdot(x-y)} ,
\]
which supports predictions for interaction amplitudes without requiring an intermediate localized object with rest-frame persistence.

The Timeless Light Model does not reinterpret this formalism; it makes explicit the restrained reading already implicit in its use \cite{WeinbergQFT,PeskinSchroeder}.



\section{Relation to Photon Correlation Experiments}

Although empirically neutral, the endpoint-focused reading aligns naturally with experimental practice in quantum optics, where physically recorded quantities are correlations between detection events. Examples include Hanbury Brown--Twiss interferometry and coincidence measurements in quantum information experiments, where ``single-photon'' behavior is operationally defined through detection statistics rather than intermediate trajectories \cite{MandelWolf,HBTOriginal}.

In such contexts, the Timeless Light Model functions as a clarifying interpretive guide, not as an alternative theory.

A representative case is delayed-choice interferometry \cite{JacquesDelayedChoice},
which illustrates that the formalism assigns amplitudes to detection outcomes conditional
on experimental configuration, but does not require a persisting localized object
with a rest-frame internal history along a definite path. On the \tlm{} reading,
``which path'' language is treated as a representational convenience tied to endpoint
correlations and available records, rather than as a literal narrative of an
in-flight photon carrying an evolving internal state.






\begin{figure}[ht]
\centering
\begin{tikzpicture}[x=1cm,y=1cm,>=Latex, font=\small]

  % Axes
  \draw[->] (0,0) -- (0,6.2) node[above] {$ct$};
  \draw[->] (0,0) -- (6.2,0) node[right] {$x$};

  % Light cone (no text labels on the rays)
  \draw[thick] (0,0) -- (5.6,5.6);
  \draw[thick] (0,0) -- (-5.6,5.6);

  % Events: emission and absorption
  \fill (0.9,1.0) circle (2pt);
  \node[below left] at (0.8,1.1) {$E$};

  \fill (4.9,5.0) circle (2pt);
  \node[above right] at (4.7,5.1) {$A$};

  % Null path between endpoints
  \draw[very thick,->] (0.9,1.0) -- (4.9,5.0);

  % Proper-time annotation along the null segment (brace placed away from labels)
  \draw[decorate,decoration={brace,amplitude=8pt},thick]
    (1.1,1.2) -- (4.7,4.8)
    node[midway, left=15pt] {$\Delta \ProperTime = 0$};

  % Timelike worldline example (massive), label placed separately to avoid overlap
  \draw[thick,dashed] (2.2,0.7) -- (2.9,5.7);
  \node[align=left] at (3.9,5.9) {timelike\\(massive)};
  \node[below] at (2.2,0.7) {$m>0$};

  % Small label for the null ray (placed near A, not on top of anything)
  \node[align=left] at (6.0,4.55) {null\\(lightlike)};

\end{tikzpicture}
\caption{Minkowski diagram with emission $E$ and absorption $A$ connected by a null segment. Along a null path, the invariant proper time satisfies $\Delta\ProperTime=0$, so the rest-frame persistence template used for massive objects (timelike worldlines) does not transfer unchanged to massless excitations. The dashed timelike line is shown only for contrast with the massive-object persistence template.}
\label{fig:null-path}
\end{figure}
















\section{The Timeless Light Model (\tlm{}): An Interpretive Rule}
\begin{remark}[On terminology]
The term ``model'' is used here in a weak, non-technical sense, to denote a named
interpretive stance concerning the ontological reading of existing relativistic
and quantum invariants. The relations introduced are not laws in a Newtonian or
dynamical sense, but explicit statements of constraints already enforced
implicitly by the standard formalism. No new formal structure, equations, or
dynamical assumptions are introduced beyond those already present in
relativistic and quantum theory.
\end{remark}


The Timeless Light Model is a minimal interpretive reading of standard practice that makes one constraint on informal language explicit:


\begin{definition}[\tlm{} interpretive rule]
Throughout, ``photon'' is used as shorthand for a null-mediated relation between
interaction events (emission/absorption, or more generally vertex-to-vertex
correlation), not as the name of a persisting localized spacetime object with an
available rest-frame persistence story.
\end{definition}


Concretely, \tlm{} endorses the following weak commitments:
\begin{itemize}
\item \textbf{No persistence template import:} do not import the massive-object persistence template (rest frame + proper time clock) into photon language.
\item \textbf{Endpoint primacy:} treat localized interaction events as the primary ontic candidates; treat ``in flight'' talk as shorthand.
\item \textbf{No extra structure:} introduce no new dynamics, no preferred frames, no hidden variables, and no claims beyond standard SR/GR/QED predictions.
\end{itemize}

\begin{remark}[What \tlm{}\ is not]
\tlm{} is not a claim of superluminal influence, retrocausality, nonlocal signaling, or new physics. ``Timeless'' here means only \(\ProperTime=0\) along null propagation.
\end{remark}


\section{Consistency with Established Physics}

\tlm{} is compatible with Special Relativity, General Relativity, and quantum field
theory. It alters no equations, introduces no preferred frames, and makes no
claims about hidden variables or additional dimensions.

Its contribution is interpretive: it aligns ontology with the structures the
theory actually provides.

\section{Why This Completion Is Minimal}

\tlm{} adds no structure beyond what is required to interpret endpoint-defined descriptions coherently.
 It removes only an assumption—the persistence of photons
as spacetime objects—that is not supported by relativistic kinematics. 

In this sense, \tlm{} is conservative rather than revisionary.


\section{Motivation for an Explicit Interpretive Reading}

If the sole aim were calculation, no additional language would be required. The motivation for an explicit minimal reading is instead \emph{linguistic and pedagogical}: to prevent a recurrent category error in which massive-object persistence intuitions are inadvertently applied to massless excitations. The proposed reading enforces a simple discipline while leaving all computations unchanged.

In this restricted sense, \tlm{} is ``minimal.'' It introduces no postulates about dynamics, measurement, or ontology beyond what is already implicit in relativistic and field-theoretic structure. Its sole contribution is to make explicit a \emph{constraint on informal interpretation} that follows directly from the absence of a rest frame and proper-time evolution for null propagation \cite{NoRestFrame}.

Naming this interpretive stance serves a practical purpose: it renders the constraint explicit, citable, and reusable across contexts where photon language risks importing unsupported persistence narratives. No claim is made that \tlm{} constitutes a competing physical theory; it is offered solely as a disciplined interpretive guideline aligned with existing formalism.



\section{Alternatives and Comparison}

Other responses to the no-go result remain viable. Instrumentalism avoids
ontology altogether; agnosticism defers the question. \tlm{} differs only in
offering a concrete interpretive framework while remaining empirically neutral.

 Related interpretive restraint is common in field-theoretic practice, even when not made explicit at the ontological level \cite{WeinbergQFT}. This restraint is consistent with longstanding views in axiomatic and algebraic quantum field theory, where particle ontology is treated as secondary to local field observables and event structure \cite{HaagQFT}.




\subsection{Relation to other event-based or correlation-first readings (brief)}
Event- or correlation-first ontologies have been developed in several distinct contexts.
For example, ``flash'' ontologies in spontaneous-collapse models take localized spacetime events as primitive rather than persisting particle trajectories \cite{GRW}.
Time-symmetric approaches such as the Transactional Interpretation similarly emphasize emitter--absorber boundary conditions rather than in-flight particle persistence, though they introduce additional interpretive machinery not assumed here \cite{CramerTI}.
These frameworks differ in dynamics and commitments: collapse approaches introduce stochastic modifications, and transactional approaches invoke additional interpretive structure.
By contrast, \tlm{} makes no dynamical additions and claims no time-symmetric mechanism; it is a kinematic discipline on informal photon language motivated solely by the absence of a rest frame and proper-time evolution for null propagation.

For extended discussion of related interpretive literature, see \Cref{app:literature}.





\section{Foreseeable Objections}

Expanded responses to common interpretive objections are collected in Appendix~\ref{app:objections}.

\subsection{``Null worldlines already exist; why is this new?''}
Agreed: \tlm{} introduces no new geometry. Its only contribution is to state explicitly that the massive-object persistence template should not be imported into photon talk.

\subsection{``This is just instrumentalism in disguise.''}
Not quite. Instrumentalism refuses ontology; \tlm{} permits a weak ontic reading (endpoint primacy) while still treating in-flight language as representational shorthand.

\subsection{``Affine parameters provide evolution, so timeless is misleading.''}
Affine parameters \(\Aff\) may parameterize null curves, but they are not proper time and do not supply a rest-frame internal clock. \tlm{} uses ``timeless'' only in the narrow sense of \(\ProperTime=0\).


\section{Conclusion}

The purpose of this paper is to examine how photon language may be used
consistently with Special Relativity, and to argue that treating ``photon'' as
shorthand for endpoint-defined interaction activity provides a minimal and
conservative reading of the formalism.

The companion note \cite{NoRestFrame} motivates a limited interpretive caution: for photons, the rest-frame grounded persistence story familiar from massive objects is not available in its standard form.
This note offers \tlm{} as one explicitly minimal interpretive stance among several permissible readings for respecting that caution: treat ``photon'' as shorthand for a null-mediated relation between interaction events, and treat in-flight persistence language as representational.

No claim of unique correctness is made. The proposal is a conservative reading that aims to reduce a common category error while leaving the formalism and its empirical content unchanged.

Nothing in this reading commits one to claims about the existence or non-existence
of photons beyond the interpretive scope defined here.





\appendix


\section{Extended Literature Context: Photon Ontology and Interpretive Restraint}
\label{app:literature}

This appendix situates the Timeless Light Model (\tlm{}) within a broader landscape
of existing discussions concerning photon ontology, particle persistence, and
interpretive restraint in relativistic quantum field theory. The purpose of this
survey is contextual rather than argumentative: no claim of priority, exclusivity,
or resolution of longstanding debates is made.

A recurring theme in modern quantum field theory is that particle concepts,
particularly for massless excitations, do not straightforwardly support a
localized, persisting object interpretation. In relativistic QFT, particles
appear most cleanly as asymptotic states, while local structure is carried by
fields and local observables rather than by particle trajectories
\cite{WeinbergQFT,HaagQFT}. This structural feature already encourages caution
about importing classical persistence narratives into photon language.

Related concerns arise in discussions of localization. It is widely noted in the
literature that photon localization does not admit a Lorentz-covariant position
operator in the same sense as for massive particles, and that localization is
therefore treated operationally—via detection statistics or wave-packet
descriptions—rather than in terms of sharp position eigenstates
\cite{Wightman1962,NewtonWigner1949,BialynickiBirula1996}.




This fact has motivated a range of views in which
photons are treated as delocalized field excitations or as bookkeeping devices for
energy--momentum transfer, rather than as pointlike entities with well-defined
worldlines. These results underscore the limited applicability of massive-particle
intuition to massless excitations.

Algebraic and axiomatic approaches to quantum field theory reinforce this
perspective by prioritizing local algebras of observables and event structure over
particle ontology \cite{HaagQFT}. Within such frameworks, particles are often
understood as emergent or approximate descriptors tied to specific regimes, rather
than as fundamental spacetime occupants. The present work is compatible with this
outlook, though it does not rely on algebraic machinery.

Pedagogical discussions in both relativity and quantum optics further reveal a
persistent mismatch between informal language and formal structure. Expressions
such as ``the photon travels through space'' or ``the photon experiences no time''
are common heuristics, but they are not literal consequences of relativistic
kinematics. The kinematic result that null worldlines carry vanishing proper time
already constrains how such language may be interpreted without contradiction.

Against this background, \tlm{} should be understood as a minimal interpretive
discipline rather than as a novel ontological proposal. Its contribution is to
state explicitly a restraint that is often applied implicitly in advanced
practice: namely, that the rest-frame-based persistence template used for massive
objects should not be imported wholesale into photon descriptions. In this sense,
\tlm{} functions as a pedagogical and linguistic clarification aligned with
existing formal results, rather than as a competing interpretation of quantum
field theory.



\section{Detailed Responses to Common Interpretive Objections}
\label{app:objections}

This appendix expands on several foreseeable objections that may arise in response
to the interpretive stance adopted in this paper. These remarks are intended to
clarify scope and intent rather than to argue for exclusivity or necessity.

\subsection*{``This is already standard quantum field theory''}

In one sense, this objection is correct. The formalism of relativistic quantum
field theory does not require a persisting, localized photon traveling through
space, and experienced practitioners routinely avoid such language in precise
contexts. The contribution of \tlm{} is not to introduce a new formal insight, but
to elevate this implicit restraint to an explicit interpretive rule. This
clarification is motivated by the persistent reappearance of massive-object
intuition in pedagogical, popular, and even technical discussions of photons.

\subsection*{``This is merely instrumentalism under another name''}

Instrumentalist approaches typically refrain from making any ontological
commitments. By contrast, \tlm{} permits a weak ontic reading in which localized
interaction events (emission, absorption, or interaction vertices) are treated as
the primary spacetime relata, while ``in-flight'' particle language is regarded as
representational shorthand. This position occupies a middle ground between strict
instrumentalism and robust particle ontology.

\subsection*{``Why call this a model at all?''}

The term ``model'' is used here in a deliberately weak sense, referring to a named
interpretive guideline rather than to a dynamical or predictive framework. Naming
the stance serves a practical purpose: it allows the interpretive constraint to be
clearly stated, referenced, and compared with alternatives. No claim is made that
\tlm{} constitutes a physical model in the sense of adding structure or modifying
the formalism.

\subsection*{``Interpretive papers lack scientific value''}

Interpretive clarification plays a well-established role in theoretical physics,
particularly where informal reasoning risks conflict with formal invariants. In
the present case, the clarification concerns the consequences of the null
proper-time condition for photon language. By aligning informal descriptions with
kinematic structure, \tlm{} aims to reduce category errors without altering
calculations or empirical content. Its value is therefore pedagogical and
conceptual rather than predictive.

\subsection*{``Does this imply nonlocality, retrocausality, or acausal influence?''}

No. The present work introduces no claims about causal mechanisms beyond those
already present in relativistic quantum field theory. References to endpoint
correlations are not intended to suggest signaling, time-symmetric dynamics, or
influences outside standard causal structure. ``Timeless'' is used strictly in the
kinematic sense of vanishing proper time along null propagation.




\begin{thebibliography}{99}

\bibitem{NoRestFrame}
J.~C.~W.~McKinley,
\emph{No Rest Frame, No Persistence: A Kinematic Constraint on Photon Interpretation},
Zenodo (2025),
\href{https://doi.org/10.5281/zenodo.18005884}{doi:10.5281/zenodo.18005884}.

\bibitem{Rindler}
W.~Rindler,
\emph{Introduction to Special Relativity},
Oxford University Press (1991).

\bibitem{WeinbergQFT}
S.~Weinberg,
\emph{The Quantum Theory of Fields, Vol.~I: Foundations},
Cambridge University Press (1995).

\bibitem{PeskinSchroeder}
M.~E.~Peskin and D.~V.~Schroeder,
\emph{An Introduction to Quantum Field Theory},
Westview Press (1995).

\bibitem{MandelWolf}
L.~Mandel and E.~Wolf,
\emph{Optical Coherence and Quantum Optics},
Cambridge University Press (1995).

\bibitem{HBTOriginal}
R.~Hanbury Brown and R.~Q.~Twiss,
``Correlation between photons in two coherent beams of light,''
\emph{Nature} \textbf{177}, 27--29 (1956).

\bibitem{OBrienQI}
J.~L.~O'Brien, A.~Furusawa, and J.~Vu\v{c}kovi\'c,
``Photonic quantum technologies,''
\emph{Nature Photonics} \textbf{3}, 687--695 (2009).

\bibitem{GRW}
G.~C.~Ghirardi, A.~Rimini, and T.~Weber,
\emph{Unified dynamics for microscopic and macroscopic systems},
Phys.\ Rev.\ D \textbf{34}, 470--491 (1986).

\bibitem{CramerTI}
J.~G.~Cramer,
\emph{The transactional interpretation of quantum mechanics},
Rev.\ Mod.\ Phys.\ \textbf{58}, 647--688 (1986).

\bibitem{HaagQFT}
R.~Haag,
\emph{Local Quantum Physics: Fields, Particles, Algebras},
2nd ed., Springer (1996).

\bibitem{JacquesDelayedChoice}
V.~Jacques, E.~Wu, F.~Grosshans, F.~Treussart, P.~Grangier, A.~Aspect, and J.-F.~Roch,
``Experimental realization of Wheeler's delayed-choice Gedanken Experiment,''
\emph{Science} \textbf{315}, 966--968 (2007).

\bibitem{NewtonWigner1949}
T.~D.~Newton and E.~P.~Wigner,
\emph{Localized States for Elementary Systems},
Rev.\ Mod.\ Phys.\ \textbf{21}, 400--406 (1949).
\href{https://doi.org/10.1103/RevModPhys.21.400}{doi:10.1103/RevModPhys.21.400}

\bibitem{Wightman1962}
A.~S.~Wightman,
\emph{On the Localizability of Quantum Mechanical Systems},
Rev.\ Mod.\ Phys.\ \textbf{34}, 845--872 (1962).
\href{https://doi.org/10.1103/RevModPhys.34.845}{doi:10.1103/RevModPhys.34.845}

\bibitem{BialynickiBirula1996}
I.~Bialynicki-Birula,
\emph{Photon Wave Function},
Prog.\ Opt.\ \textbf{36}, 245--294 (1996).
\href{https://doi.org/10.1016/S0079-6638(08)70316-0}{doi:10.1016/S0079-6638(08)70316-0}

\end{thebibliography}




\end{document}
```

</details>

---
{% endraw %}
